# Báo cáo cá nhân — 2A202603824_PhamQuangTuan

> Trình bày theo [bài làm mẫu](../../docs/02-deliverable-example.md), đối chiếu yêu cầu trong [worksheet](../../docs/01-worksheet.md). Các mục chưa có dữ liệu thực tế được để trống.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phạm Quang Tuấn
- MSSV: 2A202603824
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: E99
- Link repo nhóm: https://github.com/phamtuan2xx3-alt/K5-L3B-DAY02-E99-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

**Vai trò khi thuyết trình:** Founder đề xuất một thử nghiệm giúp quán ăn nhỏ hạn chế bỏ sót đơn đặt qua tin nhắn giờ cao điểm. Mục tiêu của bài pitch là thuyết phục người nghe cho thử nghiệm tại một quán và đánh giá kết quả, chưa phải chứng minh đã có sản phẩm hoặc khách hàng trả tiền.

**Actor của vấn đề:** Chủ quán hoặc nhân viên vừa nhận tin nhắn đặt món, vừa thu tiền và chuyển đơn cho người chuẩn bị. Founder là người trình bày phương án nghiên cứu, không phải người đang chịu pain thay chủ quán.

**Bối cảnh nghiên cứu:** Quán cơm mang đi gần trường hoặc văn phòng, nhận đơn qua một kênh nhắn tin như Zalo trong giờ trưa. Phạm vi dự kiến chỉ gồm đơn văn bản, một quán và một thực đơn; chưa xử lý thanh toán, giao hàng hoặc nhiều chi nhánh.

**Trạng thái bằng chứng:** Các candidate là giả thuyết từ tình huống nghiên cứu và nguồn công khai, chưa có phỏng vấn hoặc số đo tại quán. Thời gian minh họa trong CP2 không phải kết quả thực tế. Nguồn được mở và kiểm ngày 09/11/2026.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Bằng chứng công khai / dấu hiệu thật cần bổ sung |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi nhiều khách nhắn đặt món trong giờ trưa, tôi muốn biết cuộc hội thoại nào đã thành đơn được xác nhận, để không bỏ quên khách hoặc ghi trùng đơn. | Chủ quán; nhân viên nhận đơn; khách đặt món | Toast có mô hình duyệt và theo dõi trạng thái đơn [S1], là pattern để đối chiếu chứ chưa chứng minh quán nhận chat bị sót. Cần ghi số cuộc hội thoại, đơn xác nhận và đơn sót/trùng trong một ca thật. |
| 2 | Tốn thời gian | Khi khách nhắn món, số lượng và ghi chú ở nhiều tin liên tiếp, tôi muốn chốt được nội dung cuối cùng của đơn, để chuyển đúng thông tin cho người chuẩn bị. | Nhân viên nhận đơn; người chuẩn bị | KiotViet có thông tin món, số lượng, ghi chú và mã đơn trên màn hình bếp [S2]. Cần quan sát thời gian từ tin đầu đến phiếu được xác nhận và số lần phải đọc lại. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi khách đổi món sau khi tôi đã chuyển đơn, tôi muốn biết thay đổi đó thuộc đơn nào và bếp đã làm tới đâu, để xử lý thay đổi đúng lúc và tránh chuẩn bị theo thông tin cũ. | Chủ quán; người chuẩn bị; khách đổi món | Quy trình Toast phân biệt nhận đơn, chuyển bếp, chuẩn bị và hoàn tất [S3]. Đây là cơ sở đặt giả thuyết về bàn giao; cần ghi một lần đổi đơn thật và cách quán đã xử lý. |
| 4 | Pain từ người khác | Khi nhận nhiều phiếu trong giờ cao điểm, tôi muốn thấy rõ thứ tự, món và ghi chú của từng đơn, để không phải hỏi lại người nhận đơn giữa lúc đang chuẩn bị. | Người chuẩn bị món | KiotViet có danh sách món và thông tin phục vụ bếp [S2]. Chưa có lời kể của người làm bếp tại quán; cần ghi số lần hỏi lại và nguyên nhân trong một ca. |
| 5 | Lặp lại | Khi giao túi đồ cho khách hoặc người tới lấy, tôi muốn đối chiếu đúng đơn và đủ món, để không giao nhầm hoặc thiếu món. | Người đóng gói; người giao đơn; khách | Toast mô tả bước hoàn tất và giao đơn [S3]. Cần quan sát số lượt bàn giao, số lần phát hiện thiếu/nhầm và công cụ đối chiếu đang dùng. |

**AI đã được dùng thế nào:**

- Tôi chọn hướng quán ăn nhỏ bỏ sót đơn qua tin nhắn vì tình huống cụ thể, dễ minh họa và phù hợp để trình bày đề xuất thử nghiệm dưới vai founder.
- AI hỗ trợ tìm nguồn, diễn đạt 5 Job Stories và chuẩn bị Problem Cards theo worksheet.
- Tôi dùng AI để phản biện phạm vi, actor, cách đo và phương án không dùng AI của chủ đề quán ăn; các điểm cần làm rõ được bổ sung vào bản nháp CP2.
- Candidate cần đối chiếu với cách một quán thật đang làm. Không xem tài liệu sản phẩm là bằng chứng quán đã có pain, cũng không mặc định cần AI.

**Nguồn đối chiếu:**

- **S1:** [Toast — Get Started With Orders Hub](https://support.toasttab.com/en/article/Order-Hub-Overview?lang=en_US): tham khảo pattern duyệt và theo dõi trạng thái đơn.
- **S2:** [KiotViet — Cách sử dụng màn hình bếp](https://www.kiotviet.vn/huong-dan-su-dung-kiotviet/bep-bar-cafe-nha-hang/cach-su-dung-man-hinh-bep/): tham khảo cách hiển thị thông tin đơn cho bếp.
- **S3:** [Toast — Tracking the order fulfillment](https://doc.toasttab.com/doc/platformguide/platformOrdersTrackFulfillment.html): tham khảo các bước từ nhận đến giao đơn.

Các nguồn xác nhận công cụ/pattern đã có. Chưa xác minh các công cụ này nhận được tin nhắn từ tài khoản Zalo của quán; không khẳng định có tích hợp hoặc phù hợp chi phí với quán nghiên cứu.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

Top 3 lấy từ CP1 #1, #3 và #5: bỏ sót lúc nhận, bỏ sót thay đổi và nhầm lúc giao. Đây là ba điểm lỗi khác nhau trong cùng chuỗi xử lý đơn. **Mọi số phút dưới đây là giả định minh họa để thiết kế phép đo**, chưa phải baseline thực tế.

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Bỏ sót hoặc ghi trùng đơn qua tin nhắn — CP1 #1 | Dễ kể và demo; actor rõ; quan sát được trạng thái từng đơn; có phương án thủ công để so sánh | Sót vì chưa đọc tin, chưa ghi phiếu hay chưa chuyển bếp? Bao nhiêu ca thực sự gặp? |
| 2 | Thay đổi đơn không tới người chuẩn bị — CP1 #3 | Minh họa rõ rủi ro của thông tin cũ; tách được lúc trước và sau khi bếp làm | Khách đổi đơn có thường xuyên không? Quán có quy tắc ngừng nhận thay đổi chưa? |
| 3 | Giao thiếu hoặc nhầm túi đồ — CP1 #5 | Đầu ra kiểm tra được bằng mã đơn và checklist món | Có thực sự do dữ liệu tin nhắn hay chỉ thiếu bước kiểm túi? |

### Problem Card #1 — Bỏ sót hoặc ghi trùng đơn qua tin nhắn

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhiều khách nhắn đặt món trong giờ trưa, tôi muốn biết cuộc hội thoại nào đã thành đơn được xác nhận, để không bỏ quên khách hoặc ghi trùng đơn. |
| Actor | Chủ quán hoặc nhân viên nhận đơn qua tin nhắn, đồng thời phục vụ tại quầy |
| Thời điểm / bối cảnh | Giờ trưa; một kênh chat, đơn văn bản theo thực đơn hiện có. Tin hỏi giá chưa mặc nhiên là đơn, tin nhắn bổ sung chưa mặc nhiên là đơn mới |
| Quy trình hiện tại (giả thuyết) | Mở hội thoại → đọc chuỗi tin → hỏi lại chỗ thiếu → ghi phiếu và đánh dấu đã chốt → chuyển người chuẩn bị → rà cuộc hội thoại còn treo |
| Bottleneck | Bước 2 — đọc và tổng hợp chuỗi tin khi liên tục bị gián đoạn; giả định 2 phút/đơn. Cần kiểm tra thêm liệu điểm nghẽn thật là bước ghi phiếu hoặc chuyển bếp |
| Impact | Có thể bỏ quên khách, ghi trùng hoặc phải hỏi lại; chưa có số liệu thiệt hại thực tế. Kịch bản giả định 5 phút thao tác/đơn, không gồm thời gian chờ khách trả lời hoặc chế biến |
| Success metric (baseline → target, cách đo) | Thu baseline ít nhất 2 ca trưa, ghi thời gian thao tác và lỗi/100 đơn xác nhận. Target thử nghiệm đề xuất: giảm ≥30% thời gian thao tác trung vị, không tăng tỷ lệ sai món/số lượng/ghi chú; giảm ≥50% tỷ lệ bỏ sót/trùng nếu baseline có lỗi. Nếu baseline bằng 0 lỗi, mục tiêu giữ 0 và chỉ đánh giá tốc độ. Mốc minh họa 5 → ≤3,5 phút/đơn, chưa phải cam kết kết quả |
| Phương án không dùng AI | Một người nhận đơn; mẫu nhắn món–số lượng–giờ lấy; phiếu có mã và trạng thái; chỉ chuyển bếp sau khi nhân viên xác nhận. Thử link form đặt món nếu khách chấp nhận |
| Giả thuyết về AI | Nếu khách vẫn dùng câu tự do và cách đơn giản chưa đủ, AI có thể soạn nháp phiếu từ đoạn chat được phép dùng. Nhân viên đối chiếu rồi xác nhận; AI không tự đoán món, tự chốt đơn hay chuyển bếp |
| Cảm nhận nhanh | Thử No AI/Rule trước; Workflow có một bước đọc tin là giả thuyết tiếp theo. Chưa có lý do chọn Agent |

Quy trình nháp hiện tại:

```text
KỊCH BẢN GIẢ ĐỊNH — 6 bước, 5 phút thao tác/đơn, chưa đo thực tế

[1 Mở hội thoại: 0,5'] → [2 Đọc và gom nội dung: 2'] ← BOTTLENECK GIẢ THUYẾT
→ [3 Hỏi lại chỗ thiếu: 1'] → [4 Ghi phiếu, đánh dấu đã chốt: 0,5']
→ [5 Chuyển người chuẩn bị: 0,5'] → [6 Rà hội thoại còn treo: 0,5']
Đo riêng thời gian chờ khách phản hồi; không tính thời gian nấu.
```

### Problem Card #2 — Thay đổi đơn không tới người chuẩn bị

| Trường | Nội dung |
|---|---|
| Job Story | Khi khách đổi món sau khi tôi đã chuyển đơn, tôi muốn biết thay đổi đó thuộc đơn nào và bếp đã làm tới đâu, để xử lý thay đổi đúng lúc và tránh chuẩn bị theo thông tin cũ. |
| Actor | Nhân viên nhận tin và người chuẩn bị đang dùng phiếu đã chốt |
| Thời điểm / bối cảnh | Khách đổi món, số lượng hoặc ghi chú sau khi đơn đã chuyển; việc đổi phải được người phụ trách chấp nhận, không mặc định thực hiện được |
| Quy trình hiện tại (giả thuyết) | Nhận tin đổi → tìm đúng phiếu → hỏi bếp trạng thái → thống nhất với khách → sửa phiếu và báo thay đổi → bếp xác nhận nhận bản mới |
| Bottleneck | Bước 3 — xác định bếp đang dùng bản nào và đã chuẩn bị tới đâu; giả định 1,5 phút/lần |
| Impact | Có thể phải làm lại, sai yêu cầu hoặc phát sinh tranh cãi; kịch bản minh họa 5 phút thao tác/lần đổi. Chưa có tần suất và chi phí làm lại |
| Success metric (baseline → target, cách đo) | Ghi mọi lượt đổi trong 2 ca baseline và 2 ca thử; đo từ lúc nhân viên thấy tin đến khi bếp xác nhận hướng xử lý. Target đề xuất giảm ≥30% thời gian trung vị và không có thay đổi được chấp nhận nhưng bếp dùng bản cũ. Mốc minh họa 5 → ≤3,5 phút/lượt. Báo riêng số mẫu, lượt không thể đổi và lượt phải chờ khách |
| Phương án không dùng AI | Mã đơn duy nhất; phiếu sửa đánh dấu phiên bản; thông báo thay đổi có bếp xác nhận; quy tắc xử lý khi đã bắt đầu làm |
| Giả thuyết về AI | Chỉ gợi ý phần thay đổi so với nội dung đã xác nhận. Tin mơ hồ phải hỏi lại; không tự hủy món, sửa phiếu bếp hay hứa với khách rằng đổi được |
| Cảm nhận nhanh | No AI/Rule có thể đủ; ưu tiên sửa bàn giao trước khi thêm AI |

Quy trình nháp hiện tại:

```text
KỊCH BẢN GIẢ ĐỊNH — 6 bước, 5 phút/lượt đổi, chưa đo thực tế

[1 Nhận tin đổi: 0,5'] → [2 Tìm phiếu: 1']
→ [3 Hỏi trạng thái bếp: 1,5'] ← BOTTLENECK GIẢ THUYẾT
→ [4 Thống nhất với khách: 1'] → [5 Sửa phiếu, báo đổi: 0,5']
→ [6 Bếp xác nhận bản mới: 0,5']
Không đổi được → báo khách và giữ phương án đã thống nhất, không âm thầm sửa.
```

### Problem Card #3 — Giao thiếu hoặc nhầm túi đồ

| Trường | Nội dung |
|---|---|
| Job Story | Khi giao túi đồ cho khách hoặc người tới lấy, tôi muốn đối chiếu đúng đơn và đủ món, để không giao nhầm hoặc thiếu món. |
| Actor | Nhân viên đóng gói và bàn giao đơn mang đi |
| Thời điểm / bối cảnh | Nhiều túi chuẩn bị gần nhau trong ca trưa; không bao gồm xác nhận thanh toán hoặc vận chuyển |
| Quy trình hiện tại (giả thuyết) | Tìm phiếu → gom món → đối chiếu số lượng và ghi chú → gắn mã túi → xác nhận người nhận → đánh dấu đã giao |
| Bottleneck | Bước 3 — đối chiếu món và ghi chú với phiếu; giả định 1 phút/đơn. Nếu phiếu đúng nhưng vẫn nhầm túi, pain thuộc thao tác bàn giao chứ không phải đọc tin |
| Impact | Có thể khách thiếu món hoặc nhận túi khác; kịch bản minh họa 3 phút kiểm và bàn giao/đơn. Chưa có số lần nhầm hoặc chi phí xử lý |
| Success metric (baseline → target, cách đo) | Đo lỗi thiếu/nhầm trên 100 đơn bàn giao và thời gian từ bắt đầu kiểm túi đến giao. Target đề xuất giảm ≥50% tỷ lệ lỗi nếu baseline có lỗi, không làm tăng thời gian trung vị. Nếu baseline không có lỗi, giữ 0 lỗi và xem checklist có gây thêm thao tác không; ghi rõ số mẫu quan sát |
| Phương án không dùng AI | Mã phiếu trùng mã túi; checklist món–số lượng–ghi chú; tách khu chờ lấy và đã giao; người nhận đọc mã đơn |
| Giả thuyết về AI | Chưa thấy cần AI cho bước này. Không mở rộng sang camera nhận diện món khi mã đơn và checklist chưa được thử |
| Cảm nhận nhanh | No AI/Rule là hướng ưu tiên |

Quy trình nháp hiện tại:

```text
KỊCH BẢN GIẢ ĐỊNH — 6 bước, 3 phút/đơn, chưa đo thực tế

[1 Tìm phiếu: 0,5'] → [2 Gom món: 0,5']
→ [3 Đối chiếu món và ghi chú: 1'] ← BOTTLENECK GIẢ THUYẾT
→ [4 Gắn mã túi: 0,5'] → [5 Xác nhận người nhận: 0,25']
→ [6 Đánh dấu đã giao: 0,25']
```

### Card muốn pitch nhất

- Card đề xuất: **#1 — Bỏ sót hoặc ghi trùng đơn qua tin nhắn**.
- Vì sao: dễ minh họa bằng chuỗi tin nhắn và phiếu đơn; điểm can thiệp cụ thể; có thể thử trên một ca làm thay vì hứa thay đổi toàn bộ hoạt động quán.
- Câu hỏi muốn nhóm phản biện: “Nếu dùng một mẫu đặt món và một người chốt đơn thì đã đủ chưa? Đơn đang sót ở lúc đọc tin, ghi phiếu hay chuyển bếp?”
- Đề nghị khi pitch: xin hợp tác với một quán để quan sát 2 ca baseline và thử quy trình trong 2 ca tương đương; chưa đề nghị xây hệ thống lớn.
- Phương án quay về: nháp sai hoặc không dùng được → nhân viên ghi phiếu theo cách cũ; chỉ đơn do người xác nhận mới được chuyển bếp.
- Trạng thái: chuẩn bị trình bày; chưa có kết quả thử nghiệm tại quán.
- Bản luyện thuyết trình: [pitch khoảng 90 giây, demo và câu hỏi thường gặp](../assets/cp2-pitch-quan-an.md).

### AI đã phản biện card thế nào

Phản biện tập trung vào việc làm rõ bài toán bỏ sót đơn qua tin nhắn tại quán ăn. Các điều chỉnh dưới đây đã được đưa vào bản nháp để chuẩn bị pitch.

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Actor cần cụ thể hơn: chủ quán nhận tin và người chuẩn bị gặp khó ở các bước khác nhau | Đã ghi nhận | Card #1 tập trung vào người nhận đơn; card #2 làm rõ bàn giao thay đổi cho bếp; card #3 tách bước đóng gói và giao đơn |
| “Quản lý quán ăn” quá rộng và khó demo | Đã ghi nhận | Giới hạn một quán, một kênh chat, ca trưa và đơn văn bản |
| Dễ nhảy sang AI trong khi form hoặc phiếu có mã đã đủ | Đã ghi nhận | Thêm No AI/Rule ở cả 3 card; chỉ cân nhắc AI khi cách đơn giản chưa đủ |
| Nhầm tin hỏi giá hoặc tin đổi món thành một đơn mới | Đã ghi nhận | Thêm bước xác nhận con người; phân biệt hội thoại, đơn và phiên bản thay đổi |
| Chỉ đo nhanh hơn có thể làm tăng sai đơn | Đã ghi nhận | Đo cả thời gian và tỷ lệ lỗi; không tự chốt hoặc chuyển bếp |
| Mẫu ít hoặc baseline không có lỗi khiến mục tiêu giảm 50% thiếu ý nghĩa | Đã ghi nhận | Nêu cách xử lý baseline 0 lỗi và yêu cầu báo số mẫu; không suy ra hiệu quả từ vài tình huống demo |

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

- [Toast — Get Started With Orders Hub](https://support.toasttab.com/en/article/Order-Hub-Overview?lang=en_US).
- [KiotViet — Cách sử dụng màn hình bếp](https://www.kiotviet.vn/huong-dan-su-dung-kiotviet/bep-bar-cafe-nha-hang/cach-su-dung-man-hinh-bep/).
- [Toast — Tracking the order fulfillment](https://doc.toasttab.com/doc/platformguide/platformOrdersTrackFulfillment.html).
