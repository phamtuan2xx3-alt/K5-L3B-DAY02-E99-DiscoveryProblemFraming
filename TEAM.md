# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: E99
- Candidate problem phân tích: Sinh viên rà repo bài lab thủ công mất thời gian đối chiếu tên, cấu trúc và mục bắt buộc, nhưng vẫn có thể bỏ sót lỗi hình thức.
- Quyết định trong báo cáo: **Not Yet** — kiểm chứng người dùng thật trước khi triển khai; **Rule** là hướng thử, **No AI** là đối chứng và phương án quay về.

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Chu Văn Nhật | 2A202603848 | Phụ trách Thiết kế quy trình & Problem Statement v0 | moyymochi11 |
| 2 | Phạm Quang Tuấn | 2A202603824 | Nhóm trưởng, Phụ trách Kiểm chứng (CP4) & Bộ Eval | phamtuan2xx3-alt |
| 3 | Nguyễn Trọng Lâm | 2A202603817 | Phụ trách Hội tụ nhóm (CP3) & Đánh giá rủi ro (CP6) | NTLam108 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Nguyễn Trọng Lâm | Chu Văn Nhật, Phạm Quang Tuấn | Gom 4 cluster, vẽ cây OST, lập bảng chấm điểm 7 tiêu chí ưu tiên bài #7 |
| CP4 — Kiểm chứng | Phạm Quang Tuấn | Chu Văn Nhật | Assumption map 6 giả định, tổng hợp 3 snapshot minh họa; phỏng vấn thực tế còn cần thực hiện |
| CP4 — Research | Phạm Quang Tuấn | Nguyễn Trọng Lâm | Research 3 công cụ/pattern: markdownlint-cli2, markdown-link-check, GitHub checks; có link chính thức |
| CP5 — Quy trình trước/sau | Chu Văn Nhật | Nguyễn Trọng Lâm | 2 sơ đồ Mermaid hiện tại/tương lai, bảng before/after và phương án quay về |
| CP5 — Problem Statement v0 | Chu Văn Nhật | Phạm Quang Tuấn | 6 trường Problem Statement v0, tổng hợp phản biện từ AI |
| CP6 — Mức can thiệp & Problem Statement v1 | Phạm Quang Tuấn | Chu Văn Nhật | Ma trận mơ hồ/phức tạp, so sánh 4 mức chọn Rule, v1 và bộ 10 tình huống eval chưa chạy |
| CP6 — Quyết định | Nguyễn Trọng Lâm | Chu Văn Nhật, Phạm Quang Tuấn | 4 rủi ro theo Marty Cagan, kết luận Not Yet và 4 ngưỡng dừng |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### ChuVanNhat-2A202603848

**Phần việc phụ trách:**

- Chuẩn bị Problem Card #1 (Kiểm tra checklist bài nộp lab - được chọn làm Candidate #7 của nhóm), phụ trách chính thiết kế Quy trình trước/sau (CP5) và soạn thảo Problem Statement v0.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Cung cấp trải nghiệm và dữ liệu baseline thực tế cho bài toán được nhóm chọn (#7).
- Phụ trách chính vẽ 2 sơ đồ Mermaid (Quy trình thủ công hiện tại và Quy trình tương lai với Rule), thiết lập bảng Before/After so sánh 7 chỉ số và xây dựng phương án fallback khi công cụ gặp sự cố.
- Trực tiếp soạn thảo bản dự thảo Problem Statement v0 gồm 6 trường chi tiết và tiếp thu phản biện từ AI.
- Tham gia phản biện các candidate khác ở CP3 và cùng nhóm thống nhất lựa chọn giải pháp Rule ở CP6 với quyết định "Not Yet".

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Mục 2.1 (Candidate #7), Mục 4 (Quy trình trước/sau), Mục 5 (Problem Statement v0) trong `report/team/group_report.md`.
- File báo cáo cá nhân `report/individual/2A202603848_ChuVanNhat.md`.

**Điều mình học được từ phần nhóm:**

- Hiểu được sự khác biệt rất lớn giữa suy đoán cá nhân và quy trình thực tế của nhóm: ban đầu mình nghĩ cần AI để kiểm tra, nhưng khi ngồi phân tích quy trình cùng các bạn mới nhận ra Rule và Checklist chuẩn hóa đã giải quyết được phần lớn vấn đề mà không tốn chi phí vận hành hay đối mặt với rủi ro ảo giác của AI.

### PhamQuangTuan-2A202603824

**Phần việc phụ trách:**

- Nhóm trưởng; phụ trách CP4 (assumption map, snapshot minh họa, research) và CP6 (mức can thiệp, Problem Statement v1, bộ eval).
- Hỗ trợ Lâm tổng hợp CP3 và quyết định CP6; hỗ trợ Nhật phản biện Problem Statement v0.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Điều phối việc tổng hợp và chỉnh báo cáo nhóm, có AI hỗ trợ research, soạn nháp và phản biện.
- Chuẩn bị assumption map 6 giả định, 3 snapshot minh họa và bảng research 3 công cụ/pattern; chưa ghi nhận phỏng vấn thực tế.
- Chuẩn bị so sánh 4 mức can thiệp, v1, 5 tiêu chí đánh giá và bộ 10 tình huống đầu vào/đầu ra mong đợi cho Rule; bộ mẫu chưa chạy.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- [Báo cáo nhóm — CP4](report/team/group_report.md#3-kiểm-chứng--research-giải-pháp-đã-có-cp4).
- [Báo cáo nhóm — CP6](report/team/group_report.md#6-mức-can-thiệp-ai-cp6).
- [Bộ eval Rule](report/team/group_report.md#bộ-10-tình-huống-đầu-vàođầu-ra-mong-đợi).
- [Báo cáo cá nhân](report/individual/2A202603824_PhamQuangTuan.md).

**Điều mình học được từ phần nhóm:**

-
