# Báo cáo cá nhân — 2A202603817_NguyenTrongLam

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Trọng Lâm
- MSSV: 2A202603817
- Email trường (không bắt buộc, repo có thể để public):26ai.lamnt6@vinuni.edu.vn
- Tên nhóm:E99
- Link repo nhóm: https://github.com/phamtuan2xx3-alt/K5-L3B-DAY02-E99-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                                                                    | Ai chịu ảnh hưởng?                          | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng)                                   |
| --: | --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------------------------- |
|   1 | Lặp lại                           | Khi giảng viên yêu cầu sửa fomat hoặc nội dung báo cáo, tôi muốn cập nhật một chỗ mà tất cả tự đồng bộ(mục lục, hình trích dẫn), để khỏi chỉnh tay từng trang    | Sinh viên làm báo cáo đồ án, khóa luận      | 2-5 giờ mỗi vòng sửa; 2-3 vòng mỗi báo cáo; gần như mọi sinh viên cuối khóa đều gặp phải    |
|   2 | Tốn thời gian                     | Khi cần làm giấy tờ (tạm trú, bảo hiểm, xin xác nhận), tôi muốn biết chính xác cần những gì, nộp ở đâu, theo thứ tự nào, để không đi lại nhiều lần               | Gần như mọi người                           | 2-6 giờ/thủ tục; 1-2 lần/năm; thường phải đi hoặc nộp lại 2-3 lần vì thiếu giấy             |
|   3 | Cần đọc, tổng hợp nhiều thông tin | Khi chuẩn bị đi xin việc, tôi muốn so sánh nhanh yêu cầu của nhiều công ty và biết mình thiếu kỹ năng gì, để tập trung ôn đúng thứ.                              | Sinh viên năm cuối trong giai đoạn xin việc | đọc cập nhật tin tuyển dụng 5-10 giờ/tuần, apply và phỏng vấn trong 1-2 tháng               |
|   4 | Lặp lại                           | Khi thêm một endpoint hay entity mới, tôi muốn có sẵn khung code và test theo đúng convention của dự án, để tập trung vào logic nghiệp vụ                        | Fresher backend, sinh viên                  | 30-60 phút/endpoint; 5-10 lần/tuần, các commit có diff gần giống nhau, file test copy-paste |
|   5 | Pain từ người khác                | Khi nhóm trao đổi hàng trăm tin nhắn mỗi tuần, tôi muốn biết ai đã nhận việc gì, việc nào chưa xong và quyết định nào đã chốt                                    | Nhóm trưởng, thành viên bị giao việc mơ hồ  | 2-3 giờ/tuần theo dõi và nhắc việc; 5-10 lần nhắc/tuần                                      |
|   6 | Tốn thời gian                     | Khi cần chuyển chỗ ở, tôi muốn lọc nhanh tin đăng đúng giá, đúng khu vực và không lừa đảo, để không phải xem 10 phòng mới chọn được một                          | Sinh viên, người ra thành phố đi làm        | 10-20 giờ/lần chuyển; 1-2 lần/năm                                                           |
|   7 | Pain từ người khác                | Khi người thân gặp rắc rối với điện thoại, app ngân hàng hay tin nhắn lừa đảo, tôi muốn họ tự xử lý được hoặc nhận biết nguy hiểm, để khỏi gọi tôi giữa giờ làm. | Nạn nhân của lừa đảo qua mạng               | 3-5 cuộc gọi/tuần; 10-30 phút/cuộc; từng có người thân bị lừa đảo                           |
|   8 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận kết quả khám hoặc có triệu chứng lạ, tôi muốn hiểu các chỉ số nghĩa là gì và nên hỏi bác sĩ điều gì, để không lo lắng vô cớ hoặc chủ quan               | Gần như mọi người                           | chụp ảnh kết quả xét nghiệm gửi hỏi người quen                                              |

**AI gợi ý thêm:** Sau khi tự scan 5 ý, tôi nhờ AI scan thêm 3 ý và hỗ trợ phân tích. Sau đó, tôi đưa ra quyết định bỏ ý #8 do sai một lần rất đắt và và bằng chứng chủ yếu là chuyện riêng tư khó thu thập, ý #2 quy định và dữ liệu thay đổi liên tục theo địa phương. Tần suất chỉ 1-2 lần/năm nên khó thu bằng chứng.

- ***

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                            | Vì sao chọn | Điều còn chưa chắc                                                              |
| ---: | ---------------------------------- | ----------- | ------------------------------------------------------------------------------- |
|    1 | Tiến độ làm việc nhóm (#5)         |             | Chủ yếu trao đổi qua Zalo/Messenger, trong đó có dùng cả tiếng lóng và viết tắt |
|    2 | Tìm Job và so sánh JD phù hợp (#3) |             |                                                                                 |
|    3 | Báo cáo đồ án, sửa nhiều vòng      |             |                                                                                 |

### Problem Card #1

| Trường                                    | Nội dung                                                                                                                                                                                                                                                        |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi nhóm trao đổi hàng trăm tin nhắn mỗi tuần, tôi muốn biết ai đã nhận việc gì, việc nào chưa xong và quyết định nào đã chốt, để không phải nhắn hỏi từng người.                                                                                               |
| Actor                                     | Nhóm trưởng đồ án (chịu nặng nhất); thành viên bị giao việc mơ hồ.                                                                                                                                                                                              |
| Thời điểm / bối cảnh                      | Làm đồ án nhóm 4-5 người, nhất là 2-3 tuần trước deadline; trao đổi chủ yếu qua Zalo/Messenger, lẫn tiếng lóng và viết tắt.                                                                                                                                     |
| Quy trình hiện tại (3–7 bước)             | 1) Họp hoặc chat chia việc bằng lời. 2) Mỗi người tự nhớ phần của mình. 3) Nhóm trưởng lướt lại chat để tìm “ai nhận gì”. 4) Nhắn riêng từng người hỏi “xong chưa?”. 5) Tự tổng hợp vào Excel/Trello (thường bị bỏ). 6) Phát hiện việc bị sót khi gần deadline. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 và 4: lướt lại chat mất khoảng 20-30 phút/lần, nhắn hỏi từng người mất khoảng 10-15 phút/lần, lặp 5-10 lần/tuần                                                                                                                                          |
| Impact (nếu không giải thì sao)           | Việc bị sót hoặc trùng, nhóm trưởng kiệt sức, xích mích giữa thành viên, nộp trễ hoặc thiếu phần.                                                                                                                                                               |
| Success metric (baseline → target)        | Baseline: 2-3 giờ/tuần theo dõi, 5-10 lần nhắc/tuần (đo). Target: dưới 30 phút/tuần, dưới 2 lần nhắc/tuần, 0 việc bị sót khi gần deadline.                                                                                                                      |
| Phương án không dùng AI                   | Bảng Trello/Notion bắt buộc cập nhật; họp đứng 10 phút mỗi tuần; quy ước nhắn tin theo mẫu “[NHẬN] việc - hạn”.                                                                                                                                                 |
| Giả thuyết về AI (nếu có)                 | Nếu đưa lịch sử chat 1 tuần vào, AI trích được danh sách (việc, người phụ trách, hạn, trạng thái) với độ chính xác đủ cao để người duyệt chỉ mất 1-2 phút sửa. Rủi ro: bỏ sót thỏa thuận ngầm, hiểu sai tiếng lóng.                                             |
| Cảm nhận nhanh                            | Workflow                                                                                                                                                                                                                                                        |

Quy trình nháp hiện tại:

```text

```

### Problem Card #2

| Trường                                    | Nội dung                                                                                                                                                                                                      |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi chuẩn bị đi xin việc, tôi muốn so sánh nhanh yêu cầu của nhiều công ty và biết mình thiếu kỹ năng gì, để tập trung ôn đúng thứ.                                                                           |
| Actor                                     | Sinh viên CNTT năm cuối đang xin thực tập/fresher.                                                                                                                                                            |
| Thời điểm / bối cảnh                      | Tháng trở đi, trước và trong mùa tuyển dụng; ứng tuyển 10-20 vị trí; JD tiếng Việt và tiếng Anh lẫn lộn.                                                                                                      |
| Quy trình hiện tại (3–7 bước)             | 1) Tìm JD trên nhiều trang. 2) Mở từng JD, đọc yêu cầu. 3) Tự ghi kỹ năng lặp lại vào ghi chú. 4) Đối chiếu với CV và kỹ năng của mình. 5) Quyết định ôn gì, sửa CV ra sao. 6) Ứng tuyển, chuẩn bị phỏng vấn. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2-4: đọc và đối chiếu khoảng 20-30 phút/JD, tổng 5-10 giờ/tuần (đo); khó thấy kỹ năng nào xuất hiện nhiều nhất trên toàn bộ JD.                                                                          |
| Impact (nếu không giải thì sao)           | Ôn tràn lan hoặc ôn sai thứ, CV không khớp JD, bỏ lỡ cơ hội, hết thời gian trước khi tuyển dụng đóng.                                                                                                         |
| Success metric (baseline → target)        | Baseline: 5-10 giờ/tuần cho việc đọc và đối chiếu (đo). Target: dưới 2 giờ/tuần; có danh sách top 10 kỹ năng thiếu có xếp hạng trong 1 buổi.                                                                  |
| Phương án không dùng AI                   | Bảng tính tự lập: mỗi JD một hàng, mỗi kỹ năng một cột, đánh dấu tay; hoặc hỏi anh chị đi trước và đọc roadmap có sẵn.                                                                                        |
| Giả thuyết về AI (nếu có)                 | AI trích kỹ năng từ JD, so khớp với CV bạn cung cấp và xếp hạng khoảng cách kỹ năng. Đúng khi chỉ dùng thông tin thật trong CV, đối chiếu lại với JD gốc. Rủi ro: thổi phồng CV, bỏ sót yêu cầu ngầm.         |
| Cảm nhận nhanh                            | Workflow / Rule                                                                                                                                                                                               |

Quy trình nháp hiện tại:

```text

```

### Problem Card #3

| Trường                                    | Nội dung                                                                                                                                                                                                                                    |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story                                 | Khi giảng viên yêu cầu sửa format hoặc nội dung báo cáo, tôi muốn cập nhật một chỗ mà tất cả tự đồng bộ (mục lục, hình, trích dẫn), để khỏi chỉnh tay từng trang.                                                                           |
| Actor                                     | Sinh viên làm báo cáo đồ án, khóa luận.                                                                                                                                                                                                     |
| Thời điểm / bối cảnh                      | Sau mỗi lần giảng viên hoặc khoa góp ý, nhất là 1-2 tuần trước nộp; file Word dài 50-100 trang, nhiều người cùng sửa.                                                                                                                       |
| Quy trình hiện tại (3–7 bước)             | 1) Nhận phản hồi (thường là văn bản hoặc ghi chú rời). 2) Mở file, tìm chỗ cần sửa. 3) Sửa nội dung. 4) Chỉnh tay format (font, lề, đánh số hình/bảng, mục lục, trích dẫn). 5) Lưu bản mới “v3_final2”. 6) Gửi lại và chờ vòng sửa kế tiếp. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: chỉnh format và đồng bộ mục lục, hình, trích dẫn khoảng 2-5 giờ/vòng, 2-3 vòng/báo cáo (đo).                                                                                                                                        |
| Impact (nếu không giải thì sao)           | Mất nhiều giờ vào việc không tạo giá trị, lỗi format bị trừ điểm, file nhiều phiên bản gây nhầm lẫn khi làm nhóm.                                                                                                                           |
| Success metric (baseline → target)        | Baseline: 2-5 giờ/vòng sửa format (đo). Target: dưới 30 phút/vòng, 0 lỗi format khi nộp.                                                                                                                                                    |
| Phương án không dùng AI                   | Dùng Styles và mục lục tự động của Word, template của khoa, Zotero/Mendeley cho trích dẫn, đánh số hình bằng Caption. Phần lớn pain này giải được bằng cách dùng đúng công cụ có sẵn.                                                       |
| Giả thuyết về AI (nếu có)                 | AI đọc quy định format của trường, kiểm tra file và báo danh sách lỗi (hoặc sửa tự động). Giá trị AI chỉ có nếu cách không dùng AI không đủ; cần kiểm chứng điều này trước.                                                                 |
| Cảm nhận nhanh                            | No AI / Rule / Workflow                                                                                                                                                                                                                     |

Quy trình nháp hiện tại:

```text

```

### Card muốn pitch nhất

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
| ------------------ | ------- | --------- |
|                    |         |           |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động                  | Tôi đã làm gì?         | Kết quả / ảnh hưởng tới bài nhóm |
| -------------------------- | ---------------------- | -------------------------------- |
| Pitch Problem Card         |                        |                                  |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:    |                                  |
| Nhận phản biện             | Câu hỏi tôi nhận được: | Tôi đã sửa gì:                   |
| Gom cluster / cây OST      |                        |                                  |
| Chọn candidate problem     |                        |                                  |
| Kiểm chứng / research      |                        |                                  |
| Quy trình nhóm             |                        |                                  |
| Problem Statement          |                        |                                  |
| Mức can thiệp AI           |                        |                                  |
| Quyết định                 |                        |                                  |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| ------------------------------ | ---------------------- | ----------------- | -------------------------- | ----------------------------------- |
| CP1 Scan                       |                        |                   |                            |                                     |
| CP2 Problem Card               |                        |                   |                            |                                     |
| CP4 Research                   |                        |                   |                            |                                     |
| CP5 Quy trình                  |                        |                   |                            |                                     |
| CP5–6 Problem Statement        |                        |                   |                            |                                     |
| CP6 Mức can thiệp / quyết định |                        |                   |                            |                                     |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi _problem → quy trình → metric → boundary → mức can thiệp AI → quyết định_ của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
