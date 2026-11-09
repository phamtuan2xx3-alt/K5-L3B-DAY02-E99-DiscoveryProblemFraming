# Báo cáo bài lab

Thư mục nộp bài được tổ chức theo README và SUBMISSION của dự án:

```text
report/
├── README.md
├── individual/
│   ├── README.md
│   └── MSSV_HoTen.md       # Template; copy thành MSSV_HoTen thực tế của mỗi người
├── team/
│   ├── README.md
│   └── group_report.md    # Một báo cáo chung cho CP3–CP6
└── assets/
    └── README.md          # Hướng dẫn đặt tên ảnh và bằng chứng
```

## Bắt đầu điền bài

1. Điền thông tin nhóm và phân công trong [TEAM.md](../TEAM.md).
2. Mỗi thành viên copy [template cá nhân](individual/MSSV_HoTen.md) thành file `MSSV_HoTen.md` mang MSSV và họ tên thật, không dấu; ví dụ `20241234_NguyenVanAn.md`. Mỗi người tự điền và commit file của mình. Giữ template đến khi mọi người đã có file riêng rồi xóa template.
3. Điền phần CP3–CP6 vào [báo cáo nhóm](team/group_report.md).
4. Đặt ảnh, ghi chú phỏng vấn và bằng chứng trong [assets/](assets/README.md). Tên file bắt đầu bằng checkpoint, ví dụ `cp4-interview-snapshot-1.md` hoặc `cp5-workflow-future.png`. Chỉ ghi dữ liệu thực tế đã thu thập và ẩn thông tin cá nhân.
5. Chèn sơ đồ Mermaid trực tiếp trong báo cáo bằng khối code `mermaid` để GitHub hiển thị. Từ báo cáo cá nhân hoặc nhóm, dẫn ảnh bằng đường dẫn `../assets/ten-file.png`.
6. Đối chiếu [checklist nộp bài](../SUBMISSION.md) trước khi mỗi thành viên nộp cùng link repo nhóm trên LMS.

Tài liệu hướng dẫn nằm trong [docs/](../docs/README.md). Lab không yêu cầu code; giữ nguyên [src/](../src/README.md).
