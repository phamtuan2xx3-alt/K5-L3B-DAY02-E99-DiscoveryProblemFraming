# Pitch nháp — Hạn chế bỏ sót đơn qua tin nhắn giờ cao điểm

Vai trình bày: founder đề xuất thử nghiệm quy trình tại một quán ăn nhỏ.

## Lời trình bày khoảng 90 giây

Hãy hình dung một quán cơm vào giờ trưa: chủ quán vừa nhận tiền tại quầy, vừa đọc tin nhắn đặt món, vừa báo cho người chuẩn bị. Một khách gửi ba tin liên tiếp: đặt hai phần cơm gà, thêm một phần cơm cá, rồi đổi một phần cơm gà sang cơm cá. Nếu chỉ đọc tin đầu hoặc ghi từng tin thành đơn mới, phiếu đưa vào bếp sẽ sai.

Đó là tình huống minh họa cho vấn đề tôi muốn kiểm chứng: làm sao người nhận đơn biết nội dung cuối cùng, đơn nào đã chốt và đơn nào đã chuyển bếp?

Tôi không đề xuất xây cả hệ thống quản lý quán ngay. Bước đầu là thử một quy trình nhỏ: mỗi đơn có mã, có món, số lượng, ghi chú và trạng thái; nhân viên kiểm tra trước khi xác nhận chuyển bếp. Nếu mẫu đặt món và phiếu thủ công đã đủ, chúng ta dùng cách đó. Nếu khách vẫn nhắn tự do và nhân viên còn mất nhiều công tổng hợp, lúc đó mới thử AI tạo phiếu nháp để người nhận đơn duyệt.

Tôi đề nghị hợp tác với một quán: quan sát hai ca trưa hiện tại rồi thử trong hai ca có điều kiện tương đương. Chúng ta đo thời gian xử lý, số đơn sót, trùng và sai nội dung; chỉ tiếp tục nếu nhanh hơn mà chất lượng không giảm.

Điều tôi muốn thuyết phục hôm nay là cho phép một thử nghiệm nhỏ có thể kiểm tra, trước khi quyết định đầu tư xây sản phẩm.

## Demo bằng dữ liệu giả lập

Đây là dữ liệu dựng để minh họa, không phải tin nhắn khách hàng thật.

```text
Khách A: Cho mình 2 cơm gà, 12h lấy.
Khách A: Thêm 1 cơm cá nữa nhé.
Khách A: Đổi 1 cơm gà sang cơm cá giúp mình.
```

Phiếu nháp sau khi đọc đủ chuỗi tin:

| Trường | Nội dung |
|---|---|
| Mã minh họa | A01 |
| Món và số lượng cuối | 1 cơm gà, 2 cơm cá |
| Giờ lấy | 12h |
| Trạng thái | Chờ nhân viên xác nhận |
| Lưu ý | Chưa chuyển bếp; phải kiểm đủ tin và khả năng đáp ứng |

## Câu hỏi dễ gặp

| Câu hỏi | Hướng trả lời |
|---|---|
| Tại sao không dùng form? | Đó là phương án cần thử trước. Nếu quán và khách dùng được form thì chưa cần AI. |
| Phần mềm quản lý quán đã có rồi? | Đúng. Cần xem công cụ hiện có giải được bước nào; không tự xây lại chức năng đã đủ dùng. Chưa khẳng định có khoảng trống thị trường. |
| AI đọc sai thì sao? | AI chỉ tạo nháp. Nhân viên xác nhận trước khi chuyển bếp; không đọc được hoặc tin mơ hồ thì hỏi lại, quay về ghi phiếu thủ công. |
| Có bằng chứng quán bị sót đơn không? | Hiện đây là giả thuyết. Đề nghị quan sát tác vụ thật để kiểm chứng, chưa đưa tỷ lệ lỗi hoặc doanh thu thiệt hại chưa đo. |
| Cần đầu tư bao nhiêu? | Chưa có dự toán đủ căn cứ. Bước đề nghị hiện tại là quyền tiếp cận quán và thời gian phối hợp; chi phí xây sản phẩm chỉ tính sau khi xác nhận pain và cách can thiệp. |
