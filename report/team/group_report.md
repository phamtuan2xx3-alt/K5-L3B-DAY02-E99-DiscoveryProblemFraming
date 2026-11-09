# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: E99
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

Bảng tổng hợp 9 candidate của Pham Quang Tuan, Nguyen Trong Lam và Chu Văn Nhật. Candidate #1–#3 tham chiếu [Problem Cards của Pham Quang Tuan](../individual/2A202603824_PhamQuangTuan.md#3-top-3-problem-cards--quy-trình-nháp-cp2), bottleneck còn là giả thuyết cần kiểm chứng. Số liệu ở candidate #4–#9 được giữ theo nội dung thành viên cung cấp. Câu hỏi phản biện và người hỏi được đồng bộ từ cập nhật của nhóm trên main.

|   # | Người đưa ra                   | Candidate (Job Story ngắn)                                                                                                                                                                                                                        | Actor                                                        | Bottleneck                                                                                                                                                              | Câu hỏi phản biện nhận được (ai hỏi)                                                                                               |
| --: | ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Pham Quang Tuan — 2A202603824  | **Bỏ sót hoặc ghi trùng đơn qua tin nhắn:** Khi nhiều khách nhắn đặt món giờ trưa, tôi muốn biết hội thoại nào đã thành đơn được xác nhận, để không bỏ quên khách hoặc ghi trùng đơn.                                                             | Chủ quán hoặc nhân viên nhận đơn, đồng thời phục vụ tại quầy | Đọc và tổng hợp chuỗi tin khi liên tục bị gián đoạn; cần xác minh điểm sót ở đọc tin, ghi phiếu hay chuyển bếp                                                          | "Nếu quán dùng form đặt món cố định (No AI) thì khách có chịu dùng không?" (Nhật hỏi)                                              |
|   2 | Pham Quang Tuan — 2A202603824  | **Thay đổi đơn không tới người chuẩn bị:** Khi khách đổi món sau khi đã chuyển đơn, tôi muốn biết thay đổi thuộc đơn nào và bếp đã làm tới đâu, để xử lý đúng lúc và tránh dùng thông tin cũ.                                                     | Nhân viên nhận tin và người chuẩn bị đang dùng phiếu đã chốt | Xác định trạng thái chế biến và phiên bản phiếu bếp đang dùng trước khi chấp nhận thay đổi                                                                              | "Làm sao kết nối trạng thái của bếp theo thời gian thực nếu bếp không dùng màn hình KDS?" (Lâm hỏi)                                |
|   3 | Pham Quang Tuan — 2A202603824  | **Giao thiếu hoặc nhầm túi đồ:** Khi giao túi đồ cho khách hoặc người tới lấy, tôi muốn đối chiếu đúng đơn và đủ món, để không giao nhầm hoặc thiếu món.                                                                                          | Nhân viên đóng gói và bàn giao đơn mang đi                   | Đối chiếu món, số lượng và ghi chú với phiếu trước khi bàn giao                                                                                                         | "In bill dán lên túi đồ và tick kiểm thủ công (Rule) đã đủ giải quyết chưa?" (Nhật hỏi)                                            |
|   4 | Nguyen Trong Lam — 2A202603817 | **Tổng hợp phân công và quyết định từ chat nhóm:** Khi nhóm trao đổi hàng trăm tin nhắn mỗi tuần, tôi muốn biết ai đã nhận việc gì, việc nào chưa xong và quyết định nào đã chốt, để không phải nhắn hỏi từng người.                              | Nhóm trưởng; thành viên được giao việc chưa rõ ràng          | Lướt lại chat mất khoảng 20–30 phút/lần, nhắn hỏi từng người mất khoảng 10–15 phút/lần; lặp 5–10 lần/tuần                                                               | "Các thỏa thuận ngầm hoặc tiếng lóng trong chat Zalo có làm công cụ hiểu sai không?" (Nhật hỏi)                                    |
|   5 | Nguyen Trong Lam — 2A202603817 | **Đối chiếu yêu cầu tuyển dụng để xác định kỹ năng còn thiếu:** Khi chuẩn bị đi xin việc, tôi muốn so sánh nhanh yêu cầu của nhiều công ty và biết mình thiếu kỹ năng gì, để tập trung ôn đúng thứ.                                               | Sinh viên năm cuối trong giai đoạn xin việc                  | Đọc và đối chiếu khoảng 20–30 phút/JD, tổng 5–10 giờ/tuần (thành viên ghi đã đo); khó thấy kỹ năng nào xuất hiện nhiều nhất trên toàn bộ JD                             | "Mỗi công ty viết JD một kiểu và có yêu cầu ngầm, làm sao xếp hạng kỹ năng chuẩn xác được?" (Tuấn hỏi)                             |
|   6 | Nguyen Trong Lam — 2A202603817 | **Đồng bộ định dạng và nội dung liên quan trong báo cáo:** Khi giảng viên yêu cầu sửa định dạng hoặc nội dung báo cáo, tôi muốn cập nhật một chỗ mà các phần liên quan như mục lục, hình và trích dẫn cùng đồng bộ, để khỏi chỉnh tay từng trang. | Sinh viên làm báo cáo đồ án, khóa luận                       | Chỉnh định dạng và đồng bộ mục lục, hình, trích dẫn mất khoảng 2–5 giờ/vòng, 2–3 vòng/báo cáo (thành viên ghi đã đo)                                                    | "Dùng tính năng Styles, Caption và References tự động trong Word/LaTeX có đủ giải quyết bài này mà không cần AI không?" (Nhật hỏi) |
|   7 | Chu Văn Nhật — 2A202603848     | **Đối chiếu checklist bài nộp lab:** Khi chuẩn bị nộp bài lab môn AI trước hạn chót, tôi muốn đối chiếu nhanh toàn bộ cấu trúc repo và checklist yêu cầu, để không bị trừ điểm do sai sót hình thức như sai tên file hoặc thiếu mục.              | Sinh viên làm lab; bạn cùng nhóm                             | Mở từng file dò thủ công mất trung bình 35–45 phút; diễn ra 1 lần/tuần trước 23h50. Thành viên cho biết tuần trước nhóm bị trừ 5 điểm vì sót 1 trường trong file report | "Nếu chỉ cần kiểm tra tên file/folder thì một shell script (Rule) có đủ chưa, tại sao cần AI?" (Lâm hỏi)                           |
|   8 | Chu Văn Nhật — 2A202603848     | **Tìm lại giải đáp cũ trong chat lớp:** Khi gặp sự cố kỹ thuật hoặc thắc mắc về đề bài lab, tôi muốn tìm lại nhanh giải đáp mà giảng viên hoặc trợ giảng đã trả lời trong kênh chat lớp, để tự sửa ngay mà không phải hỏi lặp lại.                | Sinh viên trong lớp khoảng 40–50 bạn; trợ giảng              | Tìm từ khóa trong hàng nghìn tin nhắn mất 15–20 phút/lần, 2–3 lần/tuần; theo thành viên, trợ giảng trả lời cùng một câu hỏi cài đặt môi trường ít nhất 4 lần/tuần       | "Nếu không có quyền admin bot Discord/Teams thì làm sao trích xuất được dữ liệu chat tự động?" (Tuấn hỏi)                          |
|   9 | Chu Văn Nhật — 2A202603848     | **Nắm tiến độ và blocker trước deadline đồ án:** Khi sắp đến hạn nộp đồ án nhóm, tôi muốn biết chính xác ai đã làm xong phần nào và ai đang gặp vướng mắc, để chủ động hỗ trợ hoặc phân bổ lại công việc kịp deadline.                            | Trưởng nhóm; 3–4 thành viên                                  | Nhắn từng người và đọc lại chat mất 45–60 phút/lần, 2 lần/tuần; thành viên cho biết tuần trước có 1 task chậm 2 ngày do kẹt bug nhưng không thông báo sớm               | "Dùng bảng Kanban (Trello/Notion) chuẩn có giải quyết được không nếu thành viên lười cập nhật?" (Lâm hỏi)                          |

### 2.2. Cluster

9 candidate được gom thành 4 cluster theo khó khăn chung trong quy trình:

| Cluster                          | Các candidate                                            | Pattern chung                                                                   |
| -------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------- |
| A — Tiếp nhận và bàn giao đơn ăn | #1 Sót/trùng đơn; #2 Sót thay đổi; #3 Giao thiếu/nhầm    | Thông tin đơn bị thiếu hoặc không thống nhất giữa người nhận, bếp và người giao |
| B — Phân công và tiến độ nhóm    | #4 Tổng hợp việc/quyết định; #9 Theo dõi tiến độ/blocker | Phải đọc lại chat và hỏi từng người để biết trạng thái công việc                |
| C — Tìm và đối chiếu thông tin   | #5 So sánh JD; #8 Tìm giải đáp cũ                        | Thông tin đã có nhưng nằm rải rác, khó tìm đúng phần cần dùng                   |
| D — Kiểm tra đầu ra              | #6 Đồng bộ báo cáo; #7 Kiểm checklist bài nộp            | Phải rà nhiều phần để phát hiện mục thiếu, sai hoặc chưa nhất quán              |

#4 và #9 gần nhau nên shortlist dùng #9 làm đại diện, tập trung vào lúc rà tiến độ trước deadline. Với cluster A, chọn #1 để xét riêng bước tiếp nhận đơn, tránh ôm cả vận hành quán. #6 và #7 cùng cluster nhưng thời gian sửa báo cáo và thời gian kiểm bài nộp được xem riêng.

### 2.3. Opportunity Solution Tree rút gọn

Cây tập trung vào candidate #7, hướng được ưu tiên theo bảng điểm ở mục 2.4. Các pain dưới đây sẽ được kiểm chứng ở CP4.

```mermaid
flowchart TD
    O["OUTCOME<br/>Giảm ít nhất 30% thời gian rà bài lab trước khi nộp<br/>Không tăng số lỗi hình thức bị bỏ sót"]

    O --> A["Opportunity A<br/>Mất công tìm và đọc lại yêu cầu nộp bài"]
    O --> B["Opportunity B<br/>Mất thời gian mở từng file để đối chiếu yêu cầu"]
    O --> C["Opportunity C<br/>Vẫn có thể sót mục sau khi rà thủ công"]

    A --> A1["Quy tắc tên repo, tên file và mục bắt buộc<br/>nằm ở nhiều tài liệu"]
    B --> B1["Phải kiểm cả cấu trúc thư mục<br/>lẫn các mục trong báo cáo"]
    C --> C1["Nhật báo cáo một lần nhóm bị trừ điểm<br/>vì thiếu trường trong report"]

    classDef outcome fill:#164e63,stroke:#0e7490,color:#ffffff
    classDef opportunity fill:#e0f2fe,stroke:#0369a1,color:#0c4a6e
    classDef detail fill:#f8fafc,stroke:#64748b,color:#0f172a
    class O outcome
    class A,B,C opportunity
    class A1,B1,C1 detail
```

Mức giảm 30% là mục tiêu đề xuất, chưa phải kết quả đo. Phạm vi đang xét là tên, cấu trúc và mục bắt buộc; chất lượng lập luận vẫn cần người đọc đánh giá.

**Các ý loại khỏi tầng opportunity:** “chatbot kiểm bài”, “script quét repo”, “dashboard checklist”. Đây là cách giải quyết; pain cần giữ là mất thời gian đối chiếu và bỏ sót yêu cầu.

### 2.4. Chấm điểm shortlist (1–5)

Shortlist gồm #1, #9 và #7: ba tác vụ có actor rõ, có thể khoanh phạm vi và đo thời gian/lỗi. #5 cần thêm cách đánh giá năng lực so với JD; #6 cần tách công sửa nội dung khỏi định dạng; #8 còn vướng khả năng lấy dữ liệu chat và xác định câu trả lời còn phù hợp.

Chấm 7 tiêu chí với trọng số bằng nhau, tối đa 35 điểm. Điểm 1 là chưa rõ/chưa có cơ sở; 3 là đã mô tả được nhưng còn cần xác minh; 5 là rõ và thuận lợi để kiểm trong lab. Riêng bằng chứng: tự báo cáo cụ thể được 3; muốn đạt 5 cần có mẫu/log và nguồn xác nhận bổ sung. Phương án No AI/Rule đủ dùng vẫn có thể đạt điểm cao.

| Candidate                                  | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain |   Tổng |
| ------------------------------------------ | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | -----: |
| #1 — Bỏ sót/trùng đơn qua tin nhắn         |        5 |            4 |                  1 |              4 |           3 |                                      5 |                2 | **24** |
| #9 — Nắm tiến độ và blocker trước deadline |        4 |            4 |                  3 |              4 |           4 |                                      5 |                5 | **29** |
| #7 — Đối chiếu checklist bài nộp lab       |        5 |            5 |                  3 |              5 |           5 |                                      5 |                5 | **33** |

**Lý do chấm:**

- **#1 — 24/35:** Tác vụ nhận đơn cụ thể, nhưng thời gian mới là giả định và chưa có chủ quán xác nhận. Cần tiếp cận quán để quan sát, nên điểm bằng chứng và hiểu domain thấp hơn hai hướng còn lại.
- **#9 — 29/35:** Nhóm quen việc làm đồ án và có tình huống chậm task do thành viên cung cấp. Tuy nhiên, việc biết blocker còn phụ thuộc người gặp khó có báo tin hay không; cần xác định nguồn cập nhật đáng tin cậy.
- **#7 — 33/35:** Có repo và yêu cầu để đối chiếu ngay, dễ đo thời gian rà và lỗi bỏ sót. Nhật cung cấp trải nghiệm cụ thể nhưng chưa kèm log hoặc phản hồi chấm, nên bằng chứng chỉ đạt 3/5.

**Hướng ưu tiên theo điểm:** **#7 — Đối chiếu checklist bài nộp lab**; nhóm cần xác nhận lựa chọn trước CP4.

**Vì sao ưu tiên:** Phạm vi rõ, dữ liệu đầu vào sẵn có và dễ tìm người cùng gặp tác vụ để hỏi. Nhóm có thể kiểm tra nhu cầu trước khi quyết định checklist, Rule hay AI hỗ trợ.

**Vì sao chưa chọn hai hướng còn lại:** #9 khó phát hiện vướng mắc chưa được thành viên thông báo; #1 chưa có dữ liệu thực tế và điều kiện quan sát quán. Giữ cả hai làm phương án dự phòng.

**Cần làm rõ ở CP4:** Với #7, 35–45 phút là cả lượt rà, còn 15–20 phút trong card cá nhân là riêng bước đối chiếu file. Cần đo lại cùng phạm vi, kiểm tra trường hợp bị trừ điểm và hỏi người ngoài nhóm xem cách rà hiện tại đã đủ tốt chưa.

**Xử lý bất đồng:** Chưa ghi nhận. Nếu nhóm chọn khác thứ tự điểm, bổ sung lý do và điều kiện thực tế dẫn đến lựa chọn đó.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

Tập trung vào candidate #7 — kiểm checklist bài nộp lab. Research đã thực hiện từ tài liệu chính thức; phỏng vấn người ngoài nhóm chưa thực hiện. Các tự báo cáo ở CP3 là tín hiệu ban đầu để đặt câu hỏi, chưa thay thế kiểm chứng.

### 3.1. Assumption Map

Thang bằng chứng: 1 = chưa có; 2 = có tín hiệu gián tiếp; 3 = có tự báo cáo cụ thể hoặc tài liệu kỹ thuật phù hợp; 4–5 cần kiểm trực tiếp và đối chiếu thêm. Điểm dưới đây đánh giá đúng từng giả định, không suy từ tính năng công cụ sang nhu cầu người dùng.

|   # | Giả định                                                                                                       | Loại        | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước?                                            |
| --: | -------------------------------------------------------------------------------------------------------------- | ----------- | ---------------: | ---------------------: | ------------------------------------------------------------ |
|   1 | Sinh viên ngoài nhóm cũng mất công rà tên, cấu trúc và mục bắt buộc, không chỉ mất thời gian viết/sửa nội dung | Value       |                5 |                      2 | Có — quan sát một lần rà gần nhất                            |
|   2 | Checklist/template hiện có chưa đủ giảm thời gian và lỗi cho nhóm người dùng cần hỗ trợ                        | Value       |                5 |                      1 | Có — tìm cả người đã có cách làm tốt                         |
|   3 | Người dùng phân biệt được “đạt kiểm tra cấu trúc” với “nội dung đã đạt yêu cầu”                                | Usability   |                5 |                      1 | Có — cho xem mẫu kết quả, yêu cầu giải thích lại             |
|   4 | Có thể biến các yêu cầu hình thức thành quy tắc rõ và chỉ ra đúng file/mục cần xem                             | Feasibility |                5 |                      3 | Có — đối chiếu yêu cầu với repo mẫu; chưa coi là đã chạy thử |
|   5 | Lợi ích qua các lần nộp bù được công cấu hình và cập nhật khi đề thay đổi                                      | Viability   |                4 |                      1 | Đo công thiết lập, bảo trì và số lượt dùng lại               |
|   6 | Có thể kiểm bài bằng bản repo được phép truy cập, không cần quyền LMS hoặc gửi bài lên dịch vụ ngoài           | Feasibility |                4 |                      2 | Xác nhận quyền truy cập và thử phạm vi file cần đọc          |

**Ưu tiên:** #1 và #2 kiểm pain và cách đang xử lý; #3 kiểm nguy cơ người dùng tin nhầm; #4 kiểm khả năng làm một mẫu nhỏ. Chưa đề xuất AI trước khi biết các yêu cầu nào Rule đã xử lý đủ.

### 3.2. Kiểm chứng
#### Snapshot 1 — Sinh viên rà bài nhóm bằng tay

| Trường                                | Nội dung                                                                                                                 |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Vai trò                               | Sinh viên phụ trách tổng hợp và rà repo nhóm trước khi nộp lab                                                           |
| Bối cảnh hỏi đáp                      | Kể lại tình huống chuẩn bị một lượt nộp bài và cách đối chiếu yêu cầu                                                    |
| Câu hỏi chính                         | “Trong lần nộp gần nhất, bạn kiểm bài theo những bước nào? Phần nào khiến bạn phải quay lại đọc nhiều nhất?”             |
| Câu trả lời                           | “Mình mở hướng dẫn rồi mở từng report. Mất công nhất là tìm mục nào đã điền, mục nào vẫn chỉ là khung.”                  |
| Diễn biến                             | Đọc lại yêu cầu, dò tên file, mở từng báo cáo, ghi các mục còn trống rồi nhắn tác giả bổ sung; sau đó kiểm lại bản cuối  |
| Cách đang xử lý                       | Checklist ghi tay và nhắn trong nhóm; chưa có cách chỉ thẳng tới mục cần xem                                             |
| Thời gian / tần suất trong tình huống | Khoảng 30 phút/lượt rà, một lượt trước mỗi lần nộp lab; không tính viết bài ban đầu                                      |
| Tín hiệu ủng hộ giả thuyết            | Công định vị và đối chiếu mục có thể là pain riêng, không chỉ là thời gian sửa bài                                       |
| Điều cần hỏi tiếp                     | Yêu cầu xem một checklist hoặc ví dụ mục từng bị sót; quan sát lại để tách thời gian tìm mục khỏi thời gian sửa nội dung |

#### Snapshot 2 — Sinh viên đã có checklist và template

| Trường                                | Nội dung                                                                                                                          |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Vai trò                               | Sinh viên chuẩn bị khung báo cáo ngay từ đầu và tự kiểm trước khi nộp                                                             |
| Bối cảnh hỏi đáp                      | Xem cách một người đã có quy trình ổn định rà bài lab                                                                             |
| Câu hỏi chính                         | “Trong lần nộp gần nhất, checklist giúp bạn làm được gì? Còn phần nào phải tự đọc kỹ?”                                            |
| Câu trả lời                           | “Mình mất khoảng 8 phút. Tên và thư mục có sẵn rồi; phần cần đọc kỹ là lập luận, không phải cấu trúc.”                            |
| Diễn biến                             | Dùng khung chuẩn, điền dần trong quá trình làm; trước khi nộp chỉ đối chiếu checklist và đọc các mục vừa thay đổi                 |
| Cách đang xử lý                       | Template đúng đề, checklist ngắn và phân công tác giả tự kiểm file của mình                                                       |
| Thời gian / tần suất trong tình huống | Khoảng 8 phút/lượt rà cuối; công tạo và cập nhật template chưa được tính                                                          |
| Tín hiệu phản bác                     | Không phải sinh viên nào cũng cần công cụ mới; với người đã có quy trình tốt, tự động kiểm cấu trúc có thể tiết kiệm ít thời gian |
| Điều cần hỏi tiếp                     | Đo thêm công chuẩn bị template, số lần dùng lại và lỗi vẫn lọt qua checklist; tránh chỉ so lượt rà cuối                           |

#### Snapshot 3 — Người review gặp mục đủ chữ nhưng thiếu ý

| Trường                                | Nội dung                                                                                                        |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Vai trò                               | Sinh viên đọc và phản biện nội dung báo cáo của các thành viên                                                  |
| Bối cảnh hỏi đáp                      | Phân biệt đủ mục trong file với đáp ứng đúng yêu cầu của đề                                                     |
| Câu hỏi chính                         | “Có lỗi nào trong lần review gần nhất mà việc nhìn tên mục không phát hiện được? Bạn đã nhận ra bằng cách nào?” |
| Câu trả lời                           | “Mục metric có chữ nhưng chỉ ghi ‘nhanh hơn’, không có cách đo. Nếu chỉ kiểm heading thì vẫn thấy đủ.”          |
| Diễn biến                             | Mở mục metric, so với yêu cầu, nhận ra thiếu baseline và cách đo; hỏi tác giả làm rõ rồi đọc lại phần sửa       |
| Cách đang xử lý                       | Đọc nội dung theo checklist và trao đổi trực tiếp với tác giả                                                   |
| Thời gian / tần suất trong tình huống | Khoảng 15 phút cho bước review nội dung; chưa có tần suất để suy ra công theo tuần                              |
| Tín hiệu ủng hộ và giới hạn           | Cần thông báo rõ phần đã kiểm; công cụ kiểm cấu trúc không thay thế được người đánh giá lập luận                |
| Điều cần hỏi tiếp                     | Cho người dùng đọc mẫu kết quả “đủ heading, nội dung cần tự kiểm” và giải thích lại phần việc còn phải làm      |

#### Tổng hợp ba tình huống

| Tình huống          | Điều gợi mở                          | Tín hiệu phản bác / giới hạn                                   | Hướng cần kiểm ngoài thực tế                                |
| ------------------- | ------------------------------------ | -------------------------------------------------------------- | ----------------------------------------------------------- |
| 1 — Rà bằng tay     | Tìm và đối chiếu mục có thể tốn công | Chưa biết phần lớn thời gian nằm ở rà hay sửa                  | Quan sát thời gian từng bước và một lỗi cụ thể              |
| 2 — Có template     | Cách đơn giản có thể đã đủ           | Lợi ích công cụ mới có thể thấp; chưa tính công chuẩn bị       | So sánh tổng công qua nhiều lần nộp, không chỉ lượt rà cuối |
| 3 — Review nội dung | Đủ cấu trúc chưa bảo đảm đủ ý        | Không thể lấy trạng thái kiểm cấu trúc làm kết luận bài đã đạt | Thử cách diễn đạt kết quả và giữ bước con người duyệt       |

**Điều chỉnh đề xuất:** Thu hẹp actor ưu tiên vào người đang rà thủ công, chưa có checklist ổn định. Tách kiểm tên/file/mục khỏi đánh giá nội dung; metric phải tính cả công thiết lập và số lỗi bỏ sót. Người đã có template hiệu quả là nhóm đối chiếu để kiểm xem giải pháp mới có thực sự đáng dùng.

### 3.3. Research giải pháp đã có

Nguồn đã mở và kiểm ngày 09/11/2026. Bảng ghi khả năng theo tài liệu, chưa phải kết quả cài đặt hoặc thử nghiệm trong repo.

| Công cụ / case / pattern | Link                                                                            | Giải bước nào trong quy trình?                                           | Điểm mạnh                                                 | Khoảng trống / rủi ro                                                                                                               | Bài học cho nhóm                                                                      |
| ------------------------ | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| markdownlint-cli2        | [Tài liệu chính thức](https://github.com/DavidAnson/markdownlint-cli2)          | Rà Markdown trên tập file theo cấu hình, thay một phần việc dò định dạng | Có cấu hình và bộ quy tắc, có thể tái sử dụng             | Không tự biết file/mục nào đề lab bắt buộc; không chấm đúng nội dung. Quy tắc phong cách mặc định có thể gây cảnh báo ngoài yêu cầu | Chỉ bật kiểm tra liên quan; kiểm đủ mục theo template cần cấu hình/logic riêng        |
| markdown-link-check      | [Tài liệu chính thức](https://github.com/tcort/markdown-link-check)             | Hỗ trợ rà liên kết trong báo cáo                                         | Tách được việc thử liên kết khỏi việc đọc toàn bộ báo cáo | Trang cần đăng nhập, giới hạn truy cập hoặc lỗi mạng cần người xác minh; link truy cập được không bảo đảm nguồn hỗ trợ claim        | Phân biệt lỗi chắc chắn với chưa kiểm được; người dùng vẫn mở và đọc nguồn quan trọng |
| GitHub checks            | [GitHub Docs](https://docs.github.com/en/pull-requests/reference/status-checks) | Gắn kết quả kiểm tra với commit để người rà xem đúng phiên bản           | Có trạng thái và thông tin chi tiết về kiểm tra           | Là cơ chế chạy/hiển thị kết quả, không phải bộ kiểm yêu cầu lab; cần thiết lập. Kết quả cũ không xác nhận bản mới hoặc việc nộp LMS | Có thể bắt đầu local; nếu đưa lên GitHub, chỉ dùng kết quả của đúng commit định nộp   |

**Kết luận research:** Không có cơ sở xây Agent chỉ để rà cấu trúc bài. Hướng cần thử là checklist theo đề + Rule kiểm phần rõ ràng + con người đọc phần cần hiểu nội dung. Còn phải kiểm chứng liệu lợi ích này đáng kể hơn cách sinh viên đang dùng và công cấu hình có hợp lý không.

---

## 4. Quy trình trước/sau (CP5)

Phân tích cho candidate #7 — đối chiếu checklist bài nộp lab. CP4 chưa có kết quả nên đây là bản quy trình để nhóm kiểm chứng. Thời gian hiện tại lấy từ [Problem Card của Nhật](../individual/2A202603848_ChuVanNhat.md#problem-card-1--kiểm-tra-checklist-bài-nộp-lab); thời gian tương lai là dự kiến, chưa đo tại người dùng.

### 4.1. Quy trình hiện tại

Một lượt bắt đầu khi sinh viên đã có bản bài làm để rà và kết thúc khi nộp link repo trên LMS. Không tính thời gian viết bài ban đầu; thời gian sửa nội dung lớn và chờ mạng cần ghi riêng ở cả hai phương án.

```mermaid
flowchart TD
    A["1. Đọc lại yêu cầu: 10 phút"] --> B["2. Kiểm tên repo: 5 phút"]
    B --> C["3. Kiểm file cá nhân: 5 phút"]
    C --> D["4. Mở từng báo cáo, dò mục bắt buộc: 15 phút"]
    D --> E["5. Kiểm trạng thái Git và file sẽ nộp: 5 phút"]
    E --> F["6. Nộp link repo trên LMS: 5 phút"]
    style D fill:#b71c1c,stroke:#8e0000,color:#ffffff
```

| Bước | Actor                                        | Input                                                  | Output / bàn giao                                   | Thời gian / tần suất | Ghi chú                                                          |
| ---: | -------------------------------------------- | ------------------------------------------------------ | --------------------------------------------------- | -------------------- | ---------------------------------------------------------------- |
|    1 | Sinh viên nộp bài                            | Đề bài, hướng dẫn nộp, template                        | Danh sách yêu cầu cần kiểm                          | 10 phút/lượt         | Đọc lại và tự gom yêu cầu                                        |
|    2 | Sinh viên nộp bài                            | Tên repo trên GitHub; quy tắc đặt tên                  | Kết quả kiểm lớp, ngày và tên nhóm                  | 5 phút/lượt          | Đối chiếu tên repo thực tế, không chỉ tên thư mục local          |
|    3 | Sinh viên nộp bài                            | Danh sách thành viên và thư mục individual             | Kết quả kiểm tên và sự hiện diện của file cá nhân   | 5 phút/lượt          | Phát hiện thiếu file, tên chưa đổi hoặc sai mẫu                  |
|    4 | Người rà bài; tác giả báo cáo khi cần làm rõ | Báo cáo cá nhân/nhóm và danh sách yêu cầu              | Danh sách mục thiếu, trống hoặc cần tác giả xem lại | 15 phút/lượt         | **Bottleneck:** mở từng file, tìm từng mục và đối chiếu thủ công |
|    5 | Sinh viên nộp bài                            | Trạng thái Git, danh sách file và bản repo trên GitHub | Bản bài làm đã đối chiếu với nội dung định nộp      | 5 phút/lượt          | Xác nhận cập nhật đã có trên remote; không chỉ kiểm bản local    |
|    6 | Mỗi thành viên                               | Link repo nhóm và tài khoản LMS của mình               | Link đã nộp; xác nhận nộp trên LMS                  | 5 phút/lượt          | Mỗi người tự kiểm link và trạng thái nộp                         |

**Bottleneck chính:** Bước 4 mất khoảng 15–20 phút theo mô tả của Nhật; sơ đồ dùng 15 phút để khớp tổng 45 phút trong card. Tổng 45 phút là một tự báo cáo, chưa phải baseline chung của nhóm. Bước 1 còn gây lặp vì yêu cầu phải được gom lại ở mỗi lượt rà.

### 4.2. Quy trình tương lai

Hướng thử trước: gom yêu cầu thành một checklist theo đúng phiên bản đề, dùng Rule kiểm phần xác định được và để con người duyệt phần cần đọc hiểu. **Chưa đưa AI vào luồng chính** vì chưa có bằng chứng Rule không đủ.

```mermaid
flowchart TD
    A["1. Chọn checklist đúng đề và bản repo: 2 phút<br/>CON NGƯỜI"]
    A --> B["2. Kiểm cấu trúc, tên, mục và liên kết: 1 phút<br/>RULE"]
    B --> C["3. Đọc báo cáo kiểm tra, phân loại cảnh báo: 4 phút<br/>CON NGƯỜI"]
    C --> D["4. Đối chiếu nội dung và xử lý mục cần xem lại: 10 phút<br/>CON NGƯỜI"]
    D --> E["5. Kiểm lại bản cuối và đối chiếu remote: 2 phút<br/>RULE + CON NGƯỜI"]
    E --> Q{"Còn lỗi hoặc mục chưa xác minh?"}
    Q -->|Có| D
    Q -->|Không| F["6. Người nộp duyệt và nộp link LMS: 5 phút<br/>CON NGƯỜI"]
    B -. Công cụ lỗi / cấu hình không phù hợp .-> G["Quay về checklist và rà từng file thủ công"]
    G --> E
    style D fill:#155e75,stroke:#164e63,color:#ffffff
    style F fill:#166534,stroke:#14532d,color:#ffffff
```

| Bước | Actor / mức xử lý               | Input                                                             | Output / bàn giao                                                                        | Thời gian dự kiến |
| ---: | ------------------------------- | ----------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ----------------: |
|    1 | Sinh viên — con người           | Đề đang áp dụng, checklist đã đối chiếu với đề, bản repo hiện tại | Bộ yêu cầu và bản bài làm cần rà                                                         |            2 phút |
|    2 | Bộ kiểm tra — Rule              | Quy tắc tên/path/heading; danh sách thành viên; file trong repo   | Báo cáo chỉ rõ file/mục và trạng thái: đạt kiểm tra cấu trúc, có lỗi hoặc cần người kiểm |            1 phút |
|    3 | Sinh viên — con người           | Báo cáo kiểm tra và yêu cầu gốc                                   | Danh sách cảnh báo hợp lệ, mục không áp dụng có lý do và việc giao lại tác giả           |            4 phút |
|    4 | Người rà và tác giả — con người | Báo cáo, checklist và cảnh báo đã phân loại                       | Nội dung được người rà đối chiếu; tác giả tự sửa mục của mình khi cần                    |           10 phút |
|    5 | Bộ kiểm tra và người nộp        | Bản cuối sau sửa; kết quả kiểm lại; bản remote                    | Xác nhận kết quả áp dụng cho đúng phiên bản đã đẩy lên GitHub                            |            2 phút |
|    6 | Mỗi thành viên — con người      | Link repo, kết quả rà cuối và tài khoản LMS                       | Xác nhận nộp link của chính thành viên                                                   |            5 phút |

**Rule kiểm đến đâu?** Tên và file bắt buộc, heading theo template, ô trống hoặc placeholder đã định nghĩa, đường dẫn ảnh/file nội bộ. Các kiểm tra này cần cấu hình riêng theo đề. Một heading hiện diện hoặc một ô có chữ không đồng nghĩa nội dung đã đạt; công cụ phải chuyển phần đánh giá đó sang người đọc.

**Cơ sở research:**

| Công cụ / pattern                                                                 | Dùng được ở bước nào                                                   | Giới hạn cần giữ                                                                                                                                       |
| --------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [markdownlint-cli2](https://github.com/DavidAnson/markdownlint-cli2)              | Kiểm một tập file Markdown theo cấu hình ở bước 2 và 5                 | Lint Markdown không tự kiểm đủ yêu cầu của lab; chỉ bật quy tắc liên quan, tránh làm người dùng mất công sửa phong cách ngoài yêu cầu                  |
| [markdown-link-check](https://github.com/tcort/markdown-link-check)               | Hỗ trợ kiểm liên kết ở bước 2 và 5                                     | Link phản hồi được chưa chứng minh nội dung nguồn đúng. Timeout hoặc trang cần đăng nhập phải được người dùng mở lại, không kết luận ngay là link hỏng |
| [GitHub checks](https://docs.github.com/en/pull-requests/reference/status-checks) | Nếu sau này chạy kiểm tra trên GitHub, gắn kết quả với commit ở bước 5 | Cần thiết lập workflow trước; kết quả chỉ có giá trị cho bản được kiểm. Không coi trạng thái xanh là bài đã hoàn tất hoặc đã nộp LMS                   |

Đây là khả năng tham khảo từ tài liệu chính thức, chưa triển khai hay chạy thử trong repo. Phiên bản thử nhỏ nhất có thể chạy kiểm tra local; chưa cần thiết lập CI hoặc mua công cụ.

**Boundary:** Bộ kiểm tra chỉ đọc và báo vấn đề; không tự sửa/xóa bài, không viết nội dung thay tác giả và không tự nộp LMS. Người rà xác nhận các mục cần đọc hiểu. Bất kỳ sửa đổi nào sau khi kiểm cũng phải được rà lại trước khi nộp. Nếu CP6 đề xuất AI hỗ trợ đọc, đầu ra vẫn là gợi ý để người dùng kiểm, không phải kết luận chấm điểm.

**Phương án quay về:** Công cụ lỗi, không đọc được file hoặc quy tắc không khớp đề → đánh dấu chưa kiểm và rà thủ công theo yêu cầu gốc. Link không kiểm tự động được → mở bằng tài khoản phù hợp. Không bỏ qua cảnh báo để lấy trạng thái đạt. Thời gian fallback và các vòng sửa được cộng vào tổng thời gian thực tế.

### 4.3. Before / after

| Chỉ số                        | Trước                               | Sau (kỳ vọng)                                       | Ghi chú                                                                                      |
| ----------------------------- | ----------------------------------- | --------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| Số bước chính                 | 6                                   | 6                                                   | Giữ bước duyệt và nộp; giảm công dò thay vì cố giảm số bước                                  |
| Tổng thời gian/lượt           | 45 phút theo card cá nhân           | 24 phút nếu đi một vòng                             | 2 + 1 + 4 + 10 + 2 + 5; chưa gồm chuẩn bị công cụ, fallback và vòng sửa bổ sung              |
| Số bước có con người tham gia | 6/6                                 | 5/6                                                 | Bước 2 chạy bằng Rule; bước 5 kết hợp kiểm lại và người đối chiếu remote                     |
| Bottleneck                    | Mở từng file dò yêu cầu: 15–20 phút | Người rà đối chiếu nội dung: dự kiến 10 phút        | Vẫn giữ kiểm tra con người; thời gian phải đo lại                                            |
| Mức giảm thời gian tham chiếu | —                                   | Khoảng 47% nếu đạt 45 → 24 phút                     | Là tính toán theo kịch bản, chưa phải mức cải thiện đã quan sát; mục tiêu CP3 là ít nhất 30% |
| Lỗi hình thức bị bỏ sót       | Chưa có tỷ lệ baseline              | Không tăng trên cùng bộ yêu cầu                     | Người rà độc lập đối chiếu; không lấy số cảnh báo công cụ làm số lỗi thật                    |
| Rủi ro mới                    | Phụ thuộc người nhớ và dò đủ        | Cấu hình thiếu quy tắc, báo sai hoặc tin kết quả cũ | Đối chiếu cấu hình với đề, người duyệt cảnh báo và kiểm lại bản cuối                         |

**Cách đo khi thử:** Ghi thời gian từ bắt đầu rà đến xác nhận nộp, cùng số file, số yêu cầu và lỗi còn sót. Nếu dùng hai bộ bài để so sánh, chọn độ phức tạp tương đương; tránh để người dùng rà lại đúng bài vừa nhớ lỗi. Tính cả chạy lại, chờ công cụ và fallback; ghi riêng công thiết lập ban đầu và sửa nội dung lớn ở cả hai cách. Chỉ kết luận nhanh hơn khi số lỗi bỏ sót không tăng.

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung |
| -------------------------------------------------------------------------- | -------- |
| **Actor**                                                                  |          |
| **Quy trình**                                                              |          |
| **Bottleneck**                                                             |          |
| **Impact**                                                                 |          |
| **Success Metric** (baseline → target, cách đo)                            |          |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) |          |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- ***

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| ------------------------- | -------------------------- | ---------- | ------ | ----- |
| **No AI** (sửa quy trình) |                            |            |        |       |
| **Rule**                  |                            |            |        |       |
| **Workflow**              |                            |            |        |       |
| **Agent**                 |                            |            |        |       |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung |
| ----------------------------------------------------------------- | -------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          |          |
| **Judgment** — con người cân nhắc, quyết định gì?                 |          |
| **Action** — hành động cuối cùng là gì, ai làm?                   |          |
| **Outcome** — đo kết quả bằng gì?                                 |          |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? |          |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   |          |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                        |
| ----------------------------------------------- | ------------------------------- |
| **Actor**                                       |                                 |
| **Quy trình**                                   |                                 |
| **Bottleneck**                                  |                                 |
| **Impact**                                      |                                 |
| **Success Metric** (baseline → target, cách đo) |                                 |
| **Boundary**                                    |                                 |
| **AI intervention point**                       |                                 |
| **Mức chọn**                                    | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra**                     |                                 |

**Thay đổi so với v0 và lý do:**

| Trường | v0  | v1  | Vì sao đổi |
| ------ | --- | --- | ---------- |
|        |     |     |            |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí | Đạt khi | Không đạt khi |
| --: | -------- | ------- | ------------- |
|   1 |          |         |               |
|   2 |          |         |               |
|   3 |          |         |               |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       |                                                       |                    |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? |                                                       |                    |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     |                                                       |                    |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     |                                                       |                    |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
