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

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Pham Quang Tuan — 2A202603824 | **Bỏ sót hoặc ghi trùng đơn qua tin nhắn:** Khi nhiều khách nhắn đặt món giờ trưa, tôi muốn biết hội thoại nào đã thành đơn được xác nhận, để không bỏ quên khách hoặc ghi trùng đơn. | Chủ quán hoặc nhân viên nhận đơn, đồng thời phục vụ tại quầy | Đọc và tổng hợp chuỗi tin khi liên tục bị gián đoạn; cần xác minh điểm sót ở đọc tin, ghi phiếu hay chuyển bếp | "Nếu quán dùng form đặt món cố định (No AI) thì khách có chịu dùng không?" (Nhật hỏi) |
| 2 | Pham Quang Tuan — 2A202603824 | **Thay đổi đơn không tới người chuẩn bị:** Khi khách đổi món sau khi đã chuyển đơn, tôi muốn biết thay đổi thuộc đơn nào và bếp đã làm tới đâu, để xử lý đúng lúc và tránh dùng thông tin cũ. | Nhân viên nhận tin và người chuẩn bị đang dùng phiếu đã chốt | Xác định trạng thái chế biến và phiên bản phiếu bếp đang dùng trước khi chấp nhận thay đổi | "Làm sao kết nối trạng thái của bếp theo thời gian thực nếu bếp không dùng màn hình KDS?" (Lâm hỏi) |
| 3 | Pham Quang Tuan — 2A202603824 | **Giao thiếu hoặc nhầm túi đồ:** Khi giao túi đồ cho khách hoặc người tới lấy, tôi muốn đối chiếu đúng đơn và đủ món, để không giao nhầm hoặc thiếu món. | Nhân viên đóng gói và bàn giao đơn mang đi | Đối chiếu món, số lượng và ghi chú với phiếu trước khi bàn giao | "In bill dán lên túi đồ và tick kiểm thủ công (Rule) đã đủ giải quyết chưa?" (Nhật hỏi) |
| 4 | Nguyen Trong Lam — 2A202603817 | **Tổng hợp phân công và quyết định từ chat nhóm:** Khi nhóm trao đổi hàng trăm tin nhắn mỗi tuần, tôi muốn biết ai đã nhận việc gì, việc nào chưa xong và quyết định nào đã chốt, để không phải nhắn hỏi từng người. | Nhóm trưởng; thành viên được giao việc chưa rõ ràng | Lướt lại chat mất khoảng 20–30 phút/lần, nhắn hỏi từng người mất khoảng 10–15 phút/lần; lặp 5–10 lần/tuần | "Các thỏa thuận ngầm hoặc tiếng lóng trong chat Zalo có làm công cụ hiểu sai không?" (Nhật hỏi) |
| 5 | Nguyen Trong Lam — 2A202603817 | **Đối chiếu yêu cầu tuyển dụng để xác định kỹ năng còn thiếu:** Khi chuẩn bị đi xin việc, tôi muốn so sánh nhanh yêu cầu của nhiều công ty và biết mình thiếu kỹ năng gì, để tập trung ôn đúng thứ. | Sinh viên năm cuối trong giai đoạn xin việc | Đọc và đối chiếu khoảng 20–30 phút/JD, tổng 5–10 giờ/tuần (thành viên ghi đã đo); khó thấy kỹ năng nào xuất hiện nhiều nhất trên toàn bộ JD | "Mỗi công ty viết JD một kiểu và có yêu cầu ngầm, làm sao xếp hạng kỹ năng chuẩn xác được?" (Tuấn hỏi) |
| 6 | Nguyen Trong Lam — 2A202603817 | **Đồng bộ định dạng và nội dung liên quan trong báo cáo:** Khi giảng viên yêu cầu sửa định dạng hoặc nội dung báo cáo, tôi muốn cập nhật một chỗ mà các phần liên quan như mục lục, hình và trích dẫn cùng đồng bộ, để khỏi chỉnh tay từng trang. | Sinh viên làm báo cáo đồ án, khóa luận | Chỉnh định dạng và đồng bộ mục lục, hình, trích dẫn mất khoảng 2–5 giờ/vòng, 2–3 vòng/báo cáo (thành viên ghi đã đo) | "Dùng tính năng Styles, Caption và References tự động trong Word/LaTeX có đủ giải quyết bài này mà không cần AI không?" (Nhật hỏi) |
| 7 | Chu Văn Nhật — 2A202603848 | **Đối chiếu checklist bài nộp lab:** Khi chuẩn bị nộp bài lab môn AI trước hạn chót, tôi muốn đối chiếu nhanh toàn bộ cấu trúc repo và checklist yêu cầu, để không bị trừ điểm do sai sót hình thức như sai tên file hoặc thiếu mục. | Sinh viên làm lab; bạn cùng nhóm | Mở từng file dò thủ công mất trung bình 35–45 phút; diễn ra 1 lần/tuần trước 23h50. Thành viên cho biết tuần trước nhóm bị trừ 5 điểm vì sót 1 trường trong file report | "Nếu chỉ cần kiểm tra tên file/folder thì một shell script (Rule) có đủ chưa, tại sao cần AI?" (Lâm hỏi) |
| 8 | Chu Văn Nhật — 2A202603848 | **Tìm lại giải đáp cũ trong chat lớp:** Khi gặp sự cố kỹ thuật hoặc thắc mắc về đề bài lab, tôi muốn tìm lại nhanh giải đáp mà giảng viên hoặc trợ giảng đã trả lời trong kênh chat lớp, để tự sửa ngay mà không phải hỏi lặp lại. | Sinh viên trong lớp khoảng 40–50 bạn; trợ giảng | Tìm từ khóa trong hàng nghìn tin nhắn mất 15–20 phút/lần, 2–3 lần/tuần; theo thành viên, trợ giảng trả lời cùng một câu hỏi cài đặt môi trường ít nhất 4 lần/tuần | "Nếu không có quyền admin bot Discord/Teams thì làm sao trích xuất được dữ liệu chat tự động?" (Tuấn hỏi) |
| 9 | Chu Văn Nhật — 2A202603848 | **Nắm tiến độ và blocker trước deadline đồ án:** Khi sắp đến hạn nộp đồ án nhóm, tôi muốn biết chính xác ai đã làm xong phần nào và ai đang gặp vướng mắc, để chủ động hỗ trợ hoặc phân bổ lại công việc kịp deadline. | Trưởng nhóm; 3–4 thành viên | Nhắn từng người và đọc lại chat mất 45–60 phút/lần, 2 lần/tuần; thành viên cho biết tuần trước có 1 task chậm 2 ngày do kẹt bug nhưng không thông báo sớm | "Dùng bảng Kanban (Trello/Notion) chuẩn có giải quyết được không nếu thành viên lười cập nhật?" (Lâm hỏi) |

### 2.2. Cluster

9 candidate được gom thành 4 cluster theo khó khăn chung trong quy trình:

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Tiếp nhận và bàn giao đơn ăn | #1 Sót/trùng đơn; #2 Sót thay đổi; #3 Giao thiếu/nhầm | Thông tin đơn bị thiếu hoặc không thống nhất giữa người nhận, bếp và người giao |
| B — Phân công và tiến độ nhóm | #4 Tổng hợp việc/quyết định; #9 Theo dõi tiến độ/blocker | Phải đọc lại chat và hỏi từng người để biết trạng thái công việc |
| C — Tìm và đối chiếu thông tin | #5 So sánh JD; #8 Tìm giải đáp cũ | Thông tin đã có nhưng nằm rải rác, khó tìm đúng phần cần dùng |
| D — Kiểm tra đầu ra | #6 Đồng bộ báo cáo; #7 Kiểm checklist bài nộp | Phải rà nhiều phần để phát hiện mục thiếu, sai hoặc chưa nhất quán |

#4 và #9 gần nhau nên shortlist dùng #9 làm đại diện, tập trung vào lúc rà tiến độ trước deadline. Với cluster A, chọn #1 để xét riêng bước tiếp nhận đơn, tránh ôm cả vận hành quán. #6 và #7 cùng cluster nhưng thời gian sửa báo cáo và thời gian kiểm bài nộp được xem riêng.

### 2.3. Opportunity Solution Tree rút gọn

Cây tập trung vào candidate #7, hướng được ưu tiên theo bảng điểm ở mục 2.4. Các pain dưới đây sẽ được kiểm chứng ở CP4.

```text
OUTCOME: Giảm ít nhất 30% thời gian rà bài lab trước khi nộp,
         đồng thời không tăng số lỗi hình thức bị bỏ sót.
│
├── Opportunity A: Mất công tìm và đọc lại các yêu cầu nộp bài
│   └── Quy tắc tên repo, tên file và mục bắt buộc nằm ở nhiều tài liệu
│
├── Opportunity B: Mất thời gian mở từng file để đối chiếu yêu cầu
│   └── Phải kiểm cả cấu trúc thư mục lẫn các mục trong báo cáo
│
└── Opportunity C: Vẫn có thể sót mục sau khi đã rà thủ công
    └── Nhật báo cáo một lần nhóm bị trừ điểm vì thiếu trường trong report
```

Mức giảm 30% là mục tiêu đề xuất, chưa phải kết quả đo. Phạm vi đang xét là tên, cấu trúc và mục bắt buộc; chất lượng lập luận vẫn cần người đọc đánh giá.

**Các ý loại khỏi tầng opportunity:** “chatbot kiểm bài”, “script quét repo”, “dashboard checklist”. Đây là cách giải quyết; pain cần giữ là mất thời gian đối chiếu và bỏ sót yêu cầu.

### 2.4. Chấm điểm shortlist (1–5)

Shortlist gồm #1, #9 và #7: ba tác vụ có actor rõ, có thể khoanh phạm vi và đo thời gian/lỗi. #5 cần thêm cách đánh giá năng lực so với JD; #6 cần tách công sửa nội dung khỏi định dạng; #8 còn vướng khả năng lấy dữ liệu chat và xác định câu trả lời còn phù hợp.

Chấm 7 tiêu chí với trọng số bằng nhau, tối đa 35 điểm. Điểm 1 là chưa rõ/chưa có cơ sở; 3 là đã mô tả được nhưng còn cần xác minh; 5 là rõ và thuận lợi để kiểm trong lab. Riêng bằng chứng: tự báo cáo cụ thể được 3; muốn đạt 5 cần có mẫu/log và nguồn xác nhận bổ sung. Phương án No AI/Rule đủ dùng vẫn có thể đạt điểm cao.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 — Bỏ sót/trùng đơn qua tin nhắn | 5 | 4 | 1 | 4 | 3 | 5 | 2 | **24** |
| #9 — Nắm tiến độ và blocker trước deadline | 4 | 4 | 3 | 4 | 4 | 5 | 5 | **29** |
| #7 — Đối chiếu checklist bài nộp lab | 5 | 5 | 3 | 5 | 5 | 5 | 5 | **33** |

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

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

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
