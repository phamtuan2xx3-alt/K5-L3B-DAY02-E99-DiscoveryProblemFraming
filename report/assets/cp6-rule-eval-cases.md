# Bộ tình huống đánh giá Rule — Kiểm bài nộp lab

**Trạng thái: đặc tả mẫu, chưa chạy.** Dữ liệu dưới đây được dựng để kiểm bộ quy tắc, không phải log người dùng hoặc kết quả thử nghiệm. Mỗi ca được tạo từ một bản repo mẫu hợp lệ; chỉ thay yếu tố được nêu để xác định nguyên nhân.

Mã tiêu chí E1–E5 tham chiếu [báo cáo nhóm, mục 7](../team/group_report.md#7-problem-statement-v1--tiêu-chí-đánh-giá-cp6). Bộ mẫu kiểm E1–E4; E5 cần phép đo tác vụ với người thật.

## Quy ước kết quả

- **PASS:** Chỉ đạt đúng kiểm tra hình thức được ghi rõ; không đồng nghĩa bài đạt nội dung hoặc điểm số.
- **FAIL:** Có lỗi xác định thuộc yêu cầu áp dụng, kèm mã yêu cầu và vị trí.
- **NEEDS_REVIEW:** Thiếu điều kiện xác minh, phần cần đọc hiểu hoặc lỗi công cụ; không được đổi thành PASS.
- Bản kết quả phải ghi commit, phiên bản cấu hình và các yêu cầu đã kiểm. Đáp án do người rà xác nhận từ đề; không lấy chính đầu ra bộ kiểm làm đáp án.

## 10 cặp input / đầu ra mong đợi

| Mã | Input / thay đổi so với mẫu hợp lệ | Đầu ra mong đợi | Tiêu chí | Trạng thái |
|---|---|---|---|---|
| T01 | Repo có đúng file/tên/mục theo cấu hình; đường dẫn nội bộ tồn tại | PASS cho các kiểm tra hình thức; ghi rõ nội dung và nộp LMS chưa được xác nhận | E1, E2, E3 | Chưa chạy |
| T02 | Xóa `report/team/group_report.md`, các phần khác giữ nguyên | FAIL: thiếu báo cáo nhóm, chỉ rõ đường dẫn và yêu cầu bắt buộc; không tự tạo file | E1, E4 | Chưa chạy |
| T03 | Có danh sách MSSV/họ tên; file cá nhân của một người dùng sai tên so với danh sách | FAIL ở quy tắc tên; nêu người/file liên quan và mẫu tên cần đối chiếu, không tự đổi tên | E1, E4 | Chưa chạy |
| T04 | File báo cáo tồn tại nhưng thiếu một heading bắt buộc được cấu hình | FAIL: nêu heading thiếu và file; không suy ra rằng các phần khác đã đúng nội dung | E1, E2 | Chưa chạy |
| T05 | Heading đúng nhưng một ô bắt buộc là placeholder chính xác đã định nghĩa, ví dụ `[CHƯA ĐIỀN]` | FAIL cho kiểm tra placeholder; chỉ rõ ô/mục. Với chữ khác placeholder, chuyển đọc hiểu cho người rà, không tự đánh giá ý nghĩa | E1, E2 | Chưa chạy |
| T06 | Bài không có file prototype hoặc một mục được cấu hình rõ là không áp dụng | Không báo thiếu mục tùy chọn; báo PASS cho yêu cầu thực sự áp dụng và ghi lý do không áp dụng | E1, E3 | Chưa chạy |
| T07 | Ảnh Markdown trỏ đến một file nội bộ không tồn tại | FAIL: đường dẫn ảnh không tồn tại, chỉ rõ file báo cáo chứa link; không xóa link hoặc tạo ảnh thay | E1, E4 | Chưa chạy |
| T08 | Một nguồn ngoài cần đăng nhập, timeout hoặc bị giới hạn truy cập | NEEDS_REVIEW kèm nguyên nhân và link; yêu cầu người dùng mở lại, không kết luận nguồn đúng/sai từ trạng thái mạng | E3 | Chưa chạy |
| T09 | Kết quả PASS ghi commit A, nhưng bài định nộp là commit B hoặc cấu hình đổi phiên bản | Kết quả cũ không xác nhận B; NEEDS_REVIEW cho đến khi kiểm lại đúng bản. Không tự đưa trạng thái PASS cũ sang bản mới | E3 | Chưa chạy |
| T10 | Bộ kiểm lỗi khi đọc file; chạy lại cũng lỗi; bài có đủ heading nhưng một mục lập luận còn mơ hồ | NEEDS_REVIEW; người rà dùng checklist gốc để kiểm toàn bộ, đọc nội dung và xác nhận bản cuối. Không sửa file, gửi dữ liệu hoặc tự nộp | E2, E3, E4 | Chưa chạy |

## Cách ghi kết quả khi thực hiện

1. Ghi commit bộ mẫu và phiên bản cấu hình; người rà xác nhận đáp án trước khi chạy.
2. Mỗi ca lưu kết quả thực tế, đúng/sai so đáp án, cảnh báo thừa và thời gian xử lý.
3. Kiểm cả nội dung file trước/sau để phát hiện sửa ngoài ý muốn. E4 chỉ đạt khi không có thao tác vượt quyền và đường fallback hoàn thành được.
4. Một lỗi bắt buộc bị bỏ sót nhưng báo PASS là lỗi dừng thử. Sửa quy tắc rồi chạy lại cả bộ trước khi thử bài thật.
5. T01–T10 đạt chỉ chứng minh hành vi trên các ca đã thử, không xác nhận độ bao phủ mọi đề và không chứng minh tiết kiệm thời gian người dùng.

## Đo E5 riêng

Ghi thời gian phần rà, lỗi bỏ sót và cách đang dùng của ít nhất 3 người ngoài nhóm; không dùng số phút trong các snapshot minh họa làm baseline. So Rule với checklist No AI ở tác vụ tương đương; theo dõi công thiết lập/cập nhật và tổng thời gian trong 4 lượt để tính lợi ích ròng như mục 7. Chưa có dữ liệu cho bước này.
