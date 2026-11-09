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
|    1 | Tiến độ làm việc nhóm (#5)         | Quy trình chia việc và theo dõi lặp lại nhiều lần, bản thân từng trải qua và thấy nhóm trưởng mất 2–3 giờ/tuần; có số liệu đo cụ thể về số lần nhắc nhở. | Chủ yếu trao đổi qua Zalo/Messenger, trong đó có dùng cả tiếng lóng, viết tắt và thỏa thuận ngầm. |
|    2 | Tìm Job và so sánh JD phù hợp (#3) | Đánh trúng nhu cầu cấp thiết của sinh viên năm cuối; đọc và lọc 10–20 JD tốn 5–10 giờ/tuần, khó so sánh tổng thể để biết thiếu kỹ năng gì. | Mỗi công ty viết JD một kiểu, thuật ngữ và yêu cầu ngầm khó chuẩn hóa để xếp hạng kỹ năng chính xác. |
|    3 | Báo cáo đồ án, sửa nhiều vòng (#1) | Mất 2–5 giờ/vòng sửa chỉ để căn lề, mục lục, trích dẫn; hầu hết sinh viên làm đồ án đều gặp tình trạng lệch format. | Các tính năng Styles, Caption và References tự động trong Word/LaTeX có thể đã đủ giải quyết mà không cần AI. |

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
HIỆN TẠI — 45–60 phút/lần (lặp 5–10 lần/tuần)

[1 Họp/chat chia việc bằng lời: 15'] → [2 Thành viên tự nhớ phần việc: 0']
→ [3 Lướt lại chat tìm 'ai nhận gì': 20–30'] ← BOTTLENECK
→ [4 Nhắn riêng từng người hỏi 'xong chưa': 10–15'] ← BOTTLENECK
→ [5 Tự tổng hợp vào Excel/Trello: 15'] → [6 Phát hiện việc sót sát deadline: 0']
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
HIỆN TẠI — 5–10 giờ/tuần (khoảng 30–45 phút/JD)

[1 Tìm JD trên nhiều trang tuyển dụng: 15']
→ [2 Mở từng JD, đọc lướt yêu cầu: 10'] ← BOTTLENECK
→ [3 Tự ghi chép kỹ năng lặp lại: 10'] ← BOTTLENECK
→ [4 Đối chiếu với CV và kỹ năng bản thân: 10'] ← BOTTLENECK
→ [5 Quyết định ôn kỹ năng gì và sửa CV: 15']
→ [6 Ứng tuyển và nộp hồ sơ: 5']
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
HIỆN TẠI — 2–5 giờ/vòng sửa (2–3 vòng/báo cáo)

[1 Nhận phản hồi góp ý từ giảng viên: 10']
→ [2 Mở file Word, tìm vị trí cần chỉnh sửa: 15']
→ [3 Sửa nội dung học thuật: 45–90']
→ [4 Chỉnh tay format (font, lề, số hình, mục lục, trích dẫn): 60–120'] ← BOTTLENECK
→ [5 Lưu bản mới 'v3_final2': 5']
→ [6 Gửi lại giảng viên duyệt: 5']
```

### Card muốn pitch nhất

- Card số: **Card #1 (Tổng hợp phân công và quyết định từ chat nhóm — tương ứng Candidate #4)**
- Vì sao: Đây là nỗi đau thực tế và nhức nhối trong hầu hết các nhóm sinh viên khi làm đồ án; nhóm trưởng mất 2–3 giờ/tuần chỉ để lướt chat và giục việc; quy trình nhận việc và theo dõi rất rõ ràng; có thể so sánh giữa quy ước No AI (Trello/Notion) với Workflow AI trích xuất action item.
- Câu hỏi muốn nhóm phản biện: *"Các thỏa thuận ngầm, cách nói đùa hoặc tiếng lóng viết tắt trong chat Zalo có làm công cụ hiểu sai hoặc trích xuất sót việc không? Liệu việc bắt buộc cập nhật Kanban No AI có đủ giải quyết vấn đề mà không cần đến AI?"*

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
| ------------------ | ------- | --------- |
| Baseline 2–3 giờ/tuần chỉ dựa trên ước lượng cảm tính, cần phân rã cụ thể thời gian từng thao tác. | Đồng ý | Đã bấm giờ và phân rã cụ thể: lướt lại chat mất 20–30 phút/lần, nhắn hỏi từng người mất 10–15 phút/lần, tần suất lặp 5–10 lần/tuần. |
| Đề xuất AI tự động gán task và nhắc việc trực tiếp cho thành viên dễ gây phản cảm và phá vỡ sự tin tưởng trong nhóm. | Đồng ý | Bổ sung ranh giới HITL rõ ràng: AI chỉ dừng lại ở việc tạo bản nháp tổng hợp, nhóm trưởng là người kiểm duyệt cuối cùng trước khi giao việc chính thức. |
| Chưa làm rõ phương án No AI: nếu nhóm có kỷ luật họp standup 10 phút và dùng bảng Kanban thì bài toán có cần AI nữa không? | Đồng ý | Đã bổ sung phương án No AI (họp đứng ngắn + mẫu cú pháp tin nhắn `[NHẬN]`) vào card để so sánh trước khi nghĩ tới AI. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

Vai trò trong nhóm: **Phụ trách Hội tụ nhóm (CP3) & Đánh giá rủi ro (CP6)**; hỗ trợ Chu Văn Nhật (CP5 Quy trình trước/sau) và hỗ trợ Phạm Quang Tuấn (CP4 Research).

| Hoạt động                  | Tôi đã làm gì?         | Kết quả / ảnh hưởng tới bài nhóm |
| -------------------------- | ---------------------- | -------------------------------- |
| Pitch Problem Card         | Pitch 3 candidate của bản thân: #4 (Phân công việc từ chat), #5 (So sánh JD tìm kỹ năng thiếu) và #6 (Đồng bộ format báo cáo đồ án) | Cả 3 candidate được đưa vào bảng Pitch mục 2.1 của báo cáo nhóm để so sánh với các candidate của Tuấn và Nhật. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:<br>1. Hỏi Tuấn (Candidate #2): "Làm sao kết nối trạng thái của bếp theo thời gian thực nếu bếp không dùng màn hình KDS?"<br>2. Hỏi Nhật (Candidate #7): "Nếu chỉ cần kiểm tra tên file/folder thì một shell script (Rule) có đủ chưa, tại sao cần AI?"<br>3. Hỏi Nhật (Candidate #9): "Dùng bảng Kanban (Trello/Notion) chuẩn có giải quyết được không nếu thành viên lười cập nhật?" | Giúp Tuấn nhận ra rào cản phần cứng tại quán ăn; đặc biệt câu hỏi về shell script ở bài #7 đã kéo Nhật và cả nhóm thoát khỏi bẫy lạm dụng AI, chuyển hướng sang giải pháp Rule-based kiểm tra cấu trúc. |
| Nhận phản biện             | Câu hỏi tôi nhận được:<br>1. Nhật hỏi ở Card #4: "Các thỏa thuận ngầm hoặc tiếng lóng trong chat Zalo có làm công cụ hiểu sai không?"<br>2. Tuấn hỏi ở Card #5: "Mỗi công ty viết JD một kiểu và có yêu cầu ngầm, làm sao xếp hạng kỹ năng chuẩn xác được?"<br>3. Nhật hỏi ở Card #6: "Dùng tính năng Styles, Caption và References tự động trong Word/LaTeX có đủ giải quyết bài này mà không cần AI không?" | Tôi đã sửa gì: Thừa nhận rủi ro NLP tiếng Việt phức tạp ở #4 và sự đa dạng khó chuẩn hóa của JD ở #5; đồng ý bài #6 có thể giải quyết tốt bằng No AI (Styles/Zotero). Đồng thuận lùi các bài của mình xuống làm phương án dự phòng để ưu tiên bài #7 của Nhật. |
| Gom cluster / cây OST      | Phụ trách chính: Tổng hợp 9 candidate của cả nhóm thành 4 cluster logic (A, B, C, D); cùng Tuấn và Nhật dựng cây OST tập trung vào Candidate #7 với Outcome duy nhất: "Giảm ít nhất 30% thời gian rà bài lab mà không tăng lỗi bỏ sót" | Nhóm có bức tranh toàn cảnh 4 cụm vấn đề, loại bỏ các giải pháp trá hình ("chatbot kiểm bài", "dashboard") khỏi tầng opportunity. |
| Chọn candidate problem     | Phụ trách lập bảng chấm điểm 7 tiêu chí cho shortlist (#1, #9, #7); điều phối thảo luận và cùng nhóm thống nhất chọn #7 (Đối chiếu checklist lab) với điểm số cao nhất (33/35) | Nhóm có quyết định hội tụ minh bạch dựa trên dữ liệu sẵn có, ranh giới rõ ràng và tính khả thi trong buổi lab, thay vì bỏ phiếu cảm tính. |
| Kiểm chứng / research      | Hỗ trợ Tuấn tra cứu và kiểm tra tài liệu chính thức của 3 công cụ/pattern: `markdownlint-cli2`, `markdown-link-check` và GitHub checks; hỗ trợ phân tích khoảng trống giữa công cụ có sẵn và yêu cầu của lab | Nhóm thấy rõ: công cụ mã nguồn mở đã giải quyết tốt việc kiểm tra link và định dạng markdown, bài lab chỉ cần viết bộ quy tắc riêng kiểm tra heading và file chứ không cần tự xây agent phức tạp. |
| Quy trình nhóm             | Hỗ trợ Nhật phân rã quy trình 6 bước hiện tại và tương lai; trực tiếp phản biện bước 2 và bước 5 để làm rõ giới hạn của Rule (chỉ kiểm cấu trúc, con người phải duyệt nội dung) và hoàn thiện nhánh rẽ fallback | Sơ đồ quy trình tương lai làm rõ ranh giới Rule vs Con người; có phương án quay về an toàn khi công cụ lỗi hoặc file cấu hình không khớp đề. |
| Problem Statement          | Tham gia phản biện và rà soát các trường trong Problem Statement v0 và v1 cùng Nhật và Tuấn; đặc biệt nhấn mạnh trường Boundary và việc tách riêng 5 phút nộp LMS ra khỏi thời gian rà soát | Định hình bản Problem Statement chuẩn xác, không đánh đồng việc kiểm tra cấu trúc với việc đánh giá chất lượng bài làm. |
| Mức can thiệp AI           | Cùng nhóm phân tích bài toán trên ma trận mơ hồ × phức tạp; thảo luận so sánh 4 mức No AI / Rule / Workflow / Agent; bảo vệ quan điểm chọn mức Rule làm trọng tâm thử nghiệm | Nhóm thống nhất không dùng AI vào luồng kiểm tra hình thức vì các quy tắc đúng/sai rất rõ ràng; giữ No AI làm đối chứng và phương án quay về. |
| Quyết định                 | Phụ trách chính mục 8: Đánh giá 4 rủi ro lớn theo khung Marty Cagan (Value, Usability, Feasibility, Viability); đề xuất và chốt quyết định "Not Yet", xây dựng 4 ngưỡng dừng cụ thể trước khi triển khai | Nhóm có quyết định thận trọng, thực tế; nhận diện rủi ro Value còn Cao và thiết lập ngưỡng dừng rõ ràng để tránh lãng phí nguồn lực. |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| ------------------------------ | ---------------------- | ----------------- | -------------------------- | ----------------------------------- |
| CP1 Scan                       | Gợi ý thêm các vấn đề thường gặp của sinh viên và người đi làm | Mở rộng góc nhìn về các vấn đề tốn thời gian như lọc tin phòng trọ (#6) hay an toàn số cho người thân (#7) | Đề xuất các bài toán quá rộng, mang tính viển vông ("trợ lý ảo quản lý toàn diện đời sống") | Loại bỏ các ý tưởng mơ hồ, chỉ giữ lại những vấn đề bản thân từng trải qua và viết lại chuẩn Job Story với dấu hiệu đo lường thực tế. |
| CP2 Problem Card               | Phản biện Card #1 về theo dõi tiến độ công việc nhóm qua chat | Nhắc nhở về việc baseline thời gian 2–3 giờ/tuần còn ước lượng chung chung, chưa phân rã thao tác | Gợi ý dùng AI tự động phân loại và chỉ định công việc trực tiếp cho thành viên | Nhận thấy việc tự động gán task dễ gây phản cảm; tôi sửa lại quy trình giữ vai trò duyệt (HITL) của nhóm trưởng và bổ sung phương án No AI (Notion/Trello). |
| CP4 Research                   | Tra cứu tài liệu và cú pháp cấu hình của markdownlint và GitHub status checks | Tìm nhanh các link tài liệu chính thức và các quy tắc kiểm tra cú pháp markdown chuẩn | Khẳng định một cách hời hợt rằng "các công cụ này có thể tự động kiểm tra toàn bộ bài nộp của sinh viên" | Tôi và Tuấn trực tiếp mở tài liệu đọc và chỉ ra: markdownlint chỉ kiểm định dạng cú pháp, không biết đề bài yêu cầu heading nào; việc kiểm tra heading đề bài bắt buộc phải có script logic riêng. |
| CP5 Quy trình                  | Góp ý cấu trúc bảng Before/After và các chỉ số đo lường quy trình | Liệt kê đầy đủ các khía cạnh cần so sánh: số bước, thời gian, số bước thủ công, rủi ro mới phát sinh | Đưa ra con số kỳ vọng giảm thời gian từ 45' xuống 5' một cách phi thực tế mà không tính đến thời gian con người đọc hiểu và fallback | Chỉnh lại bảng Before/After với mốc thời gian thực tế (24 phút cả nộp LMS), bổ sung rõ rủi ro công cụ báo sai và thiết lập luồng fallback thủ công. |
| CP5–6 Problem Statement        | Đóng vai phản biện để tìm lỗ hổng trong bản Problem Statement v0 | Chỉ ra lỗ hổng: baseline giữa 45 phút của Nhật và 30 phút của người khác chưa thống nhất phạm vi; cảnh báo nguy cơ người dùng tự tin nhầm rằng "pass cấu trúc là bài đạt điểm cao" | Gợi ý thêm các metric định tính mơ hồ ("tăng mức độ hài lòng của sinh viên") | Giữ vững các metric định lượng (thời gian rà, tỷ lệ lỗi sót), bổ sung cảnh báo rõ ràng trong Boundary để người dùng hiểu công cụ không thay thế việc đọc nội dung. |
| CP6 Mức can thiệp / quyết định | Đánh giá 4 rủi ro Marty Cagan và xây dựng các kịch bản ngưỡng dừng | Gợi ý cấu trúc phân tích 4 rủi ro và các góc nhìn về chi phí bảo trì cấu hình | Thiên vị việc chọn Go sớm với lý do "bài toán đơn giản dễ code script", đánh giá rủi ro Value ở mức Thấp | Nhận định độc lập của tôi: Rủi ro Value phải ở mức CAO vì chưa phỏng vấn người dùng thật ngoài nhóm, sinh viên có template tốt có thể không cần công cụ. Quyết định chốt mức "Not Yet" và đặt ngưỡng dừng nghiêm ngặt. |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi lắng nghe phần trình bày top 3 của Tuấn và Nhật trong buổi hội tụ, tôi đã học được rất nhiều bài học sâu sắc về cách nhìn nhận và đánh giá một bài toán thực tế.
Đầu tiên là bài toán quán ăn của Tuấn (sót đơn qua tin nhắn, sót thay đổi món khi bếp đang làm, và giao nhầm túi đồ). Thoạt nghe, đây là một bài toán rất hấp dẫn, mang tính thực tiễn cao và có tiềm năng kinh doanh rõ ràng. Tuy nhiên, khi lắng nghe Tuấn phân tích quy trình, tôi nhận ra điểm yếu chí mạng nằm ở khả năng tiếp cận domain và thu thập bằng chứng thực tế. Cả nhóm không có ai trực tiếp làm việc tại quán ăn hay có quán quen để vào quan sát giờ cao điểm trưa, việc đo đạc baseline thời gian và tỷ lệ sót đơn là bất khả thi trong phạm vi một buổi lab ngắn. Bài học tôi rút ra là: một bài toán dù nghe rất "xịn xò" nhưng nếu nhóm không có khả năng kiểm chứng dữ liệu thật thì rất dễ rơi vào bẫy xây dựng giải pháp dựa trên suy đoán thuần túy.
Thứ hai, khi nghe Nhật trình bày về bài toán kiểm tra checklist bài nộp lab (#7) và bài toán theo dõi blocker trước deadline (#9), tôi nhận thấy sự tương đồng rất lớn với bài toán theo dõi chat nhóm (#4) của tôi. Cả hai chúng tôi đều đau đáu với nỗi đau quản lý tiến độ và sợ bị trừ điểm khi làm đồ án. Nhưng Nhật đã làm tốt hơn tôi ở chỗ đóng khung bài toán kiểm tra lab rất gọn gàng: actor cụ thể (chính các sinh viên trong phòng lab), quy trình 6 bước rõ ràng, dữ liệu đầu vào có sẵn ngay trên máy, và điểm nghẽn mở từng file markdown đối chiếu rubric là một thao tác đo lường được ngay. Điều này dạy cho tôi rằng trong giai đoạn Discovery, việc chọn một bài toán "vừa sức, có dữ liệu sẵn và đo lường được ngay" quan trọng hơn nhiều so với việc ôm đồm một bài toán vĩ mô nhưng thiếu cơ sở thực nghiệm.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm tôi đã bị rơi vào cái bẫy "solution-first" rất rõ rệt ở ngay đầu giai đoạn CP3 khi chuẩn bị dựng cây Opportunity Solution Tree (OST). Vừa khi thống nhất xong danh sách candidate, trong đầu cả ba thành viên đều lập tức hiện lên hình ảnh một "Chatbot AI" hoặc một "Agent tự động quét repo". Chúng tôi bắt đầu hào hứng nói về việc dùng API nào, viết script Python gọi LLM ra sao để nó tự đọc file markdown rồi báo cáo lỗi lên Discord/Telegram. Không khí lúc đó rất hăng say vì ai cũng muốn làm một sản phẩm có yếu tố AI thời thượng.
Tuy nhiên, khi tôi bắt tay vào vẽ cây OST theo tài liệu hướng dẫn của môn học, nguyên tắc cốt lõi của OST đã kéo chúng tôi giật mình tỉnh lại: "Gốc cây là Outcome mong muốn, các nhánh con là Opportunity/Pain của người dùng, tuyệt đối không được có tên tính năng hay giải pháp công nghệ ở các tầng này". Tôi đã chủ động dừng cuộc thảo luận lại và hỏi hai bạn: "Khoan đã, nếu chúng ta hoàn toàn không dùng AI, không có chatbot nào cả, thì nỗi đau thực sự khiến sinh viên bị trừ điểm oan là gì?".
Câu hỏi đó đã làm thay đổi hoàn toàn cục diện thảo luận. Nhật thừa nhận rằng nỗi đau thực tế là sinh viên phải mở từng file markdown bằng tay, lướt qua từng heading để xem mục đó đã viết chưa hay vẫn còn để trống, và việc này tốn 15–20 phút khiến sinh viên rất căng thẳng trước giờ nộp bài. Nỗi đau nằm ở bước "định vị và đối chiếu thủ công", chứ sinh viên không hề có nhu cầu "thiếu một con chatbot". Ngay lập tức, nhóm đã cùng nhau gạch bỏ toàn bộ các từ khóa "chatbot", "script quét", "dashboard" ra khỏi cây OST và chỉ giữ lại đúng 3 pain thực sự. Đây là khoảnh khắc then chốt giúp nhóm chuyển từ tư duy "tìm việc cho AI làm" sang tư duy "hiểu đúng nỗi đau của người dùng".

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi đã có một lần đổi ý hoàn toàn mang tính bước ngoặt ở phiên pitch CP3 đối với Candidate #4 của tôi ("Tổng hợp phân công và quyết định từ chat nhóm"). Ban đầu, tôi rất tự tin và tâm huyết với bài toán này vì chính tôi đã từng làm nhóm trưởng nhiều môn học và nếm trải cảm giác bất lực khi phải lướt lại hàng trăm tin nhắn Zalo để tìm xem ai đã nhận phần nào. Tôi đã hình dung ra một giải pháp Workflow có AI để đọc lịch sử chat một tuần và tự động trích xuất danh sách việc cần làm.
Thế nhưng, khi tôi trình bày xong, Nhật đã đặt ngay một câu hỏi phản biện rất sâu sắc: "Trong chat Zalo của sinh viên, các bạn hay dùng tiếng lóng, viết tắt, trêu đùa nhau, thậm chí chốt việc bằng thỏa thuận ngầm ngoài đời rồi chỉ nhắn một câu ngắn lên nhóm. Liệu công cụ có hiểu sai hoặc bỏ sót việc không?". Ngay sau đó, Tuấn cũng chất vấn về rào cản kỹ thuật: "Zalo không mở API cho tài khoản cá nhân, vậy làm sao bạn lấy được dữ liệu chat tự động mà không bắt người dùng phải copy-paste thủ công hàng ngày?".
Hai câu hỏi này như đánh trúng vào tim đen của bài toán. Tôi nhận ra mình đã quá ngây thơ khi xem nhẹ tính phức tạp của ngôn ngữ tự nhiên tiếng Việt trong giao tiếp thường nhật và rào cản chính sách dữ liệu của nền tảng chat. Việc AI trích xuất sai hoặc sót một task quan trọng có thể dẫn đến tranh cãi nội bộ gay gắt trong nhóm. Tôi nhận thức rõ ràng rằng đây là bài toán có độ mơ hồ rất cao và độ khả thi thấp trong khuôn khổ môn học. Thay vì cố chấp bảo vệ ý tưởng của mình, tôi đã thẳng thắn thừa nhận hạn chế, chủ động đồng thuận hạ bài toán #4 xuống làm phương án dự phòng và dồn toàn bộ sự ủng hộ cho Candidate #7 của Nhật. Việc dám từ bỏ ý tưởng cá nhân để đi theo một hướng đi khả thi hơn cho nhóm là một trải nghiệm học tập vô cùng quý giá đối với tôi.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Quá trình kiểm chứng và nghiên cứu giải pháp có sẵn ở CP4 đã mang lại cho tôi hai điều bất ngờ rất lớn, làm thay đổi căn bản những giả định chủ quan mà tôi từng nghĩ là hiển nhiên.
Điều bất ngờ thứ nhất đến từ kết quả phỏng vấn ở Snapshot 2 (người đã có template và checklist chuẩn). Trước đó, tôi đinh ninh rằng việc rà soát bài nộp là một cực hình đối với tất cả mọi sinh viên và ai cũng cần một công cụ tự động hóa. Nhưng khi xem dữ liệu phỏng vấn, bạn sinh viên này chỉ mất đúng 8 phút cho lượt rà soát cuối cùng trước deadline. Lý do là vì nhóm của bạn đã chuẩn bị sẵn một template chuẩn hóa cấu trúc ngay từ đầu buổi làm việc, các thành viên tự tick checklist các mục bắt buộc trong file của mình trước khi merge code. Tín hiệu phản bác thực tế này cho tôi một bài học đắt giá: giải pháp No AI (xây dựng quy trình chuẩn hóa và văn hóa kỷ luật) đôi khi đã giải quyết triệt để 80% vấn đề mà không tốn kém một đồng chi phí công nghệ nào. Điều này buộc nhóm tôi phải thu hẹp actor mục tiêu vào những người đang rà soát hoàn toàn thủ công và chưa có template ổn định.
Điều bất ngờ thứ hai đến từ việc research các công cụ mã nguồn mở. Tôi vốn nghĩ việc kiểm tra bài nộp là bài toán đặc thù và chưa có ai giải quyết. Nhưng khi tìm hiểu về `markdownlint-cli2` và `markdown-link-check`, tôi ngỡ ngàng khi thấy cộng đồng thế giới đã phát triển những bộ công cụ Rule-based cực kỳ mạnh mẽ để kiểm tra cấu trúc markdown, bắt lỗi thụt đầu dòng, khoảng trắng thừa và rà soát liên kết gãy. Tuy nhiên, họ lại bỏ trống hoàn toàn việc kiểm tra các heading nghiệp vụ theo yêu cầu cụ thể của từng đề bài. Nhờ phát hiện này, nhóm tôi hiểu rằng mình không cần phải phát minh lại cái bánh xe; chúng tôi chỉ cần kế thừa các công cụ Rule có sẵn và tập trung xây dựng logic kiểm tra các mục bắt buộc của đề bài.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Đối với cá nhân tôi và cả nhóm, điều khó khăn và tốn nhiều công sức tranh luận nhất khi viết Problem Statement (cả bản v0 và v1) chính là việc bóc tách số liệu để xác định Success Metric đo lường được và vạch ra ranh giới (Boundary) an toàn.
Về Success Metric, ban đầu chúng tôi rất quen tay viết những câu khẩu hiệu chung chung như "giúp sinh viên nộp bài nhanh chóng và không bị trừ điểm". Nhưng khi bị AI đóng vai PM hoài nghi chất vấn: "Nhanh hơn là bao nhiêu phút? Đo bằng cách nào? Cơ sở nào để so sánh?", nhóm đã phải ngồi lại phân tích từng con số. Khó khăn lớn nhất là bóc tách thời gian thực tế: con số 45 phút ban đầu của Nhật bao gồm cả 40 phút rà soát repo và 5 phút thao tác copy link nộp lên hệ thống LMS. Thao tác nộp LMS phụ thuộc vào đường truyền mạng và tài khoản của từng cá nhân, không thể dùng công cụ can thiệp được. Vì vậy, chúng tôi phải tách bạch rõ ràng: Success Metric chỉ đo lường thời gian rà soát repo (giảm ít nhất 30%, từ 40 phút xuống dưới 28 phút) và giữ số lỗi hình thức bị bỏ sót bằng 0. Nếu không phân rã rành mạch như vậy, metric sẽ hoàn toàn mất giá trị đo lường.
Về Boundary, việc xác lập ranh giới đòi hỏi sự tỉnh táo rất lớn. Một file báo cáo markdown có đầy đủ các tiêu đề bắt buộc và không có ô nào để trống hoàn toàn KHÔNG đồng nghĩa với việc nội dung đó có chất lượng tốt hay đạt yêu cầu học thuật. Chúng tôi đã phải đấu tranh rất nhiều để ghi rõ vào Boundary: hệ thống chỉ đọc và cảnh báo lỗi hình thức, tuyệt đối KHÔNG tự động sửa nội dung, KHÔNG tự ý nộp bài thay sinh viên, và KHÔNG đưa ra kết luận chấm điểm bài làm. Việc đánh giá chất lượng lập luận bắt buộc phải thuộc về con người (Human-in-the-loop).

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu có cơ hội được làm lại quy trình này từ đầu, tôi sẽ thay đổi hai điểm quan trọng trong cách làm việc của nhóm.
Thứ nhất, ở bước kiểm chứng CP4, tôi sẽ đề xuất nhóm không chỉ dừng lại ở các snapshot phỏng vấn tình huống minh họa, mà phải trực tiếp đứng dậy đi sang các bàn bên cạnh trong phòng lab để bấm giờ và quan sát thực tế ít nhất 2–3 bạn sinh viên đang rà soát bài nộp. Việc tận mắt chứng kiến người dùng thao tác, nhìn thấy họ lúng túng ở đâu, mở file nào trước, dò tìm heading mất bao nhiêu giây sẽ mang lại cho nhóm những dữ liệu thực nghiệm sống động và đáng tin cậy hơn rất nhiều so với những con số ước lượng trên bàn giấy.
Thứ hai, với vai trò là người phụ trách chính phần Đánh giá rủi ro ở CP6, tôi nhận thấy mình cần phải phản biện nhóm mạnh mẽ và quyết liệt hơn nữa về rủi ro duy trì và vận hành (Viability Risk). Trong buổi thảo luận, cả ba chúng tôi đều có phần lạc quan tếu khi nghĩ rằng chỉ cần viết xong một bộ script kiểm tra là có thể dùng mãi cho cả kỳ học. Tôi đáng lẽ phải đặt ra câu hỏi hóc búa hơn: "Mỗi tuần đề bài lab lại thay đổi cấu trúc thư mục, thay đổi tên file và các heading bắt buộc. Ai sẽ là người chịu trách nhiệm bỏ thời gian ra cập nhật lại bộ quy tắc kiểm tra trước mỗi buổi lab? Liệu tổng thời gian cấu hình và bảo trì script qua các tuần có lớn hơn thời gian mà sinh viên tự rà soát bằng tay hay không?". Nếu đặt câu hỏi này sớm hơn, nhóm sẽ chú trọng thiết kế một cơ chế cấu hình quy tắc kiểm tra linh hoạt, đơn giản hơn thay vì chỉ tập trung vào việc viết code kiểm tra.

**6.7. Hiểu bài:**

Bài toán nhóm tôi giải quyết là việc sinh viên mất trung bình 40 phút rà soát repo bài lab thủ công trước hạn nộp và dễ bị trừ điểm oan do các lỗi hình thức như sai tên file hay thiếu mục báo cáo. Quy trình hiện tại gồm 6 bước từ đọc yêu cầu, kiểm tên repo/file, đối chiếu mục trong báo cáo đến nộp link LMS, trong đó bước mở từng file đối chiếu mục là điểm nghẽn lớn nhất mất 15–20 phút. Metric thành công đặt ra là giảm ít nhất 30% thời gian rà soát (từ 40 phút xuống dưới 28 phút) và số lỗi hình thức bị bỏ sót không tăng trên cùng bộ yêu cầu. Ranh giới của hệ thống là chỉ kiểm tra các quy tắc hình thức xác định được, tuyệt đối không tự sửa file, không đánh giá nội dung lập luận và không nộp thay người học. Mức can thiệp được chọn là Rule để chạy kiểm tra mẫu tên, file bắt buộc, heading và link nội bộ, kết hợp con người duyệt nội dung, giữ No AI làm đối chứng và phương án quay về. Quyết định cuối cùng của nhóm là "Not Yet" vì rủi ro Giá trị (Value) còn ở mức Cao do chưa kiểm chứng người dùng thật trên diện rộng, đồng thời thiết lập 4 ngưỡng dừng cụ thể để sẵn sàng quay về quy trình thủ công nếu công cụ không đem lại lợi ích ròng.

---

## 7. Tài liệu tham khảo

- [Teresa Torres — Continuous Discovery Habits: Discover Products that Create Customer Value and Business Value (2021)](https://www.producttalk.org/).
- [Marty Cagan / Silicon Valley Product Group (SVPG) — The Four Big Risks](https://www.svpg.com/four-big-risks/).
- [Jeff Gothelf — Business Problem Statements vs Opportunity Statements](https://jeffgothelf.com/blog/business-problem-statement-opportunity-statement/).
- [Rob Fitzpatrick — The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you (2013)](https://www.momtestbook.com/).
- [Google PAIR (People + AI Research) — Guidebook: User Needs + Defining Success](https://pair.withgoogle.com/chapter/user-needs/).
- [David Anson — markdownlint-cli2 documentation](https://github.com/DavidAnson/markdownlint-cli2).
- [GitHub Docs — About status checks](https://docs.github.com/en/pull-requests/reference/status-checks).
- [Anthropic — Building effective agents](https://www.anthropic.com/research/building-effective-agents).
