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

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Pham Quang Tuan — 2A202603824 | **Bỏ sót hoặc ghi trùng đơn qua tin nhắn:** Khi nhiều khách nhắn đặt món giờ trưa, tôi muốn biết hội thoại nào đã thành đơn được xác nhận, để không bỏ quên khách hoặc ghi trùng đơn. | Chủ quán hoặc nhân viên nhận đơn, đồng thời phục vụ tại quầy | Đọc và tổng hợp chuỗi tin khi liên tục bị gián đoạn; cần xác minh điểm sót ở đọc tin, ghi phiếu hay chuyển bếp | "Nếu quán dùng form đặt món cố định (No AI) thì khách có chịu dùng không?" (Nhật hỏi) |
| 2 | Pham Quang Tuan — 2A202603824 | **Thay đổi đơn không tới người chuẩn bị:** Khi khách đổi món sau khi đã chuyển đơn, tôi muốn biết thay đổi thuộc đơn nào và bếp đã làm tới đâu, để xử lý đúng lúc và tránh dùng thông tin cũ. | Nhân viên nhận tin và người chuẩn bị đang dùng phiếu đã chốt | Xác định trạng thái chế biến và phiên bản phiếu bếp đang dùng trước khi chấp nhận thay đổi | "Làm sao kết nối trạng thái của bếp theo thời gian thực nếu bếp không dùng màn hình KDS?" (Lâm hỏi) |
| 3 | Pham Quang Tuan — 2A202603824 | **Giao thiếu hoặc nhầm túi đồ:** Khi giao túi đồ cho khách hoặc người tới lấy, tôi muốn đối chiếu đúng đơn và đủ món, để không giao nhầm hoặc thiếu món. | Nhân viên đóng gói và bàn giao đơn mang đi | Đối chiếu món, số lượng và ghi chú với phiếu trước khi bàn giao | "In bill dán lên túi đồ và tick kiểm thủ công (Rule) đã đủ giải quyết chưa?" (Nhật hỏi) |
| 4 | Chu Văn Nhật — 2A202603848 | **Kiểm tra checklist bài nộp lab:** Khi nộp bài lab môn AI, tôi muốn đối chiếu nhanh toàn bộ cấu trúc repo và checklist, để không bị trừ điểm oan do sai sót hình thức. | Sinh viên thực hành AI/CNTT có nộp bài qua GitHub/LMS | Mở từng file markdown đọc lướt dò rubric (15–20 phút) | "Nếu chỉ cần kiểm tra tên file/folder thì một shell script (Rule) có đủ chưa, tại sao cần AI?" (Lâm hỏi) |
| 5 | Chu Văn Nhật — 2A202603848 | **Tìm giải đáp lỗi cũ trên chat lớp:** Khi gặp lỗi kỹ thuật đề lab, tôi muốn tìm lại nhanh giải đáp trợ giảng từng trả lời trên kênh chat lớp, để tự sửa ngay không phải hỏi lại. | Sinh viên thực hành lab trên lớp hoặc tại nhà | Mở từng thread chat đọc nội dung tìm giải pháp phù hợp (10 phút) | "Nếu không có quyền admin bot Discord/Teams thì làm sao trích xuất được dữ liệu chat tự động?" (Tuấn hỏi) |
| 6 | Chu Văn Nhật — 2A202603848 | **Theo dõi blocker đồ án nhóm:** Khi sắp đến hạn nộp đồ án, tôi muốn biết chính xác ai đã làm xong phần nào và ai đang kẹt blocker, để chủ động hỗ trợ kịp deadline. | Trưởng nhóm đồ án môn học | Đọc và tổng hợp các tin nhắn chat rời rạc để lọc blocker (15 phút) | "Dùng bảng Kanban (Trello/Notion) chuẩn có giải quyết được không nếu thành viên lười cập nhật?" (Lâm hỏi) |
| 7 | Nguyễn Trọng Lâm — 202603817 | **Theo dõi phân công việc nhóm qua chat:** Khi nhóm trao đổi hàng trăm tin nhắn mỗi tuần, tôi muốn biết ai đã nhận việc gì, việc nào chưa xong, để không phải nhắn hỏi từng người. | Nhóm trưởng đồ án (4–5 người) | Lướt lại chat và nhắn hỏi từng người (20–30 phút/lần, lặp 5–10 lần/tuần) | "Các thỏa thuận ngầm hoặc tiếng lóng trong chat Zalo có làm công cụ hiểu sai không?" (Nhật hỏi) |
| 8 | Nguyễn Trọng Lâm — 202603817 | **So sánh JD và tìm kỹ năng thiếu:** Khi chuẩn bị đi xin việc, tôi muốn so sánh nhanh yêu cầu nhiều công ty và biết mình thiếu kỹ năng gì, để tập trung ôn đúng thứ. | Sinh viên CNTT năm cuối xin thực tập/fresher | Đọc và đối chiếu JD với CV của mình (20–30 phút/JD, 5–10 giờ/tuần) | "Mỗi công ty viết JD một kiểu và có yêu cầu ngầm, làm sao xếp hạng kỹ năng chuẩn xác được?" (Tuấn hỏi) |
| 9 | Nguyễn Trọng Lâm — 202603817 | **Sửa format báo cáo nhiều vòng:** Khi giảng viên yêu cầu sửa format báo cáo, tôi muốn cập nhật một chỗ mà tất cả tự đồng bộ, để khỏi chỉnh tay từng trang. | Sinh viên làm báo cáo đồ án, khóa luận (file 50–100 trang) | Chỉnh format và đồng bộ mục lục, hình, trích dẫn (2–5 giờ/vòng, 2–3 vòng/báo cáo) | "Dùng tính năng Styles, Caption và References tự động trong Word/LaTeX có đủ giải quyết bài này mà không cần AI không?" (Nhật hỏi) |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

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
