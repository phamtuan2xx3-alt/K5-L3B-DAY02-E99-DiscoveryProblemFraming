# Research candidate — Kiểm tra dữ liệu học tập từ tài liệu scan

Ngày research: 09/11/2026. Người thực hiện research: trợ lý AI theo yêu cầu của Pham Quang Tuan.

> Đây là tài liệu gợi ý từ nguồn công khai, chưa phải bảng scan trải nghiệm cá nhân hoặc kết quả kiểm chứng của nhóm. Job Story, actor, quy trình và target bên dưới là giả thuyết để chọn và kiểm tra. Không có baseline, phỏng vấn hay survey nào đã được thực hiện trong tài liệu này.

## 1. Hướng đề xuất

**Kiểm tra số liệu trích từ tài liệu scan trước khi đưa vào báo cáo học tập.**

Phạm vi dự kiến: sinh viên phải lấy số liệu từ bảng trong tài liệu scan có quyền sử dụng, sau đó ghi vào bảng tổng hợp của nhóm. Điểm cần tìm hiểu là đối chiếu giá trị, đơn vị và trang nguồn trước khi người khác sử dụng số liệu.

Điểm khác so với đề tài tóm tắt tài liệu: không cố hiểu toàn bộ giáo trình; tập trung vào một lần bàn giao dữ liệu có thể kiểm tra đúng/sai. Chưa khẳng định đây là vấn đề mới trên thị trường hay phổ biến trong lớp.

## 2. Scan 5 candidate theo format CP1

| # | Lăng kính | Job Story giả thuyết | Actor dự kiến | Cơ sở công khai và điều chưa biết |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi đưa số liệu từ bảng trong tài liệu scan vào báo cáo nhóm, tôi muốn kiểm tra đúng giá trị, dấu thập phân và đơn vị, để các phép tính sau đó dùng đúng dữ liệu | Sinh viên phụ trách tổng hợp số liệu | Adobe có hướng dẫn rà và sửa từ nhận dạng không chắc chắn [S2]. Suy luận cần kiểm chứng: lỗi ở giá trị/đơn vị có khiến sinh viên phải kiểm tra lâu hoặc làm lại không? |
| 2 | Tốn thời gian | Khi cần tìm lại một khái niệm trong tài liệu chỉ có ảnh, tôi muốn xác định được trang chứa đoạn cần đọc, để tiếp tục làm bài mà không lật từng trang | Sinh viên sử dụng giáo trình scan | CU Boulder nêu vấn đề thiếu văn bản có thể chọn và chất lượng ảnh kém [S1]. Chưa biết người trong lớp có gặp, mất bao lâu và đã dùng OCR chưa. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi nhóm hỏi nguồn của một con số trong bảng tổng hợp, tôi muốn mở được đúng trang và đoạn gốc, để kiểm tra lại con số mà không đọc lại cả tài liệu | Người tổng hợp và người review báo cáo | Zotero có ghi chú gắn liên kết quay lại trang PDF [S3]. Đây cũng là tín hiệu phản bác nhu cầu tự xây: công cụ hiện có có thể đã đủ. |
| 4 | Lặp lại | Khi nhận thêm PDF bài đọc vào thư mục chung, tôi muốn xác định đúng tên tài liệu, tác giả và năm, để không gắn nhầm nguồn cho bài viết | Sinh viên quản lý tài liệu tham khảo | Zotero có lấy metadata tự động và cách nhập bổ sung nếu không tìm được [S4]. Chưa biết lỗi metadata có phải pain thực tế của người được hỏi. |
| 5 | Pain từ người khác | Khi người đọc bản ghi chú không hiểu biểu đồ được chèn vào, họ muốn có mô tả về trục, đơn vị và xu hướng chính, để theo dõi lập luận của báo cáo | Người đọc báo cáo chứa biểu đồ | W3C hướng dẫn mô tả thông tin thiết yếu của hình phức tạp [S5]. Chưa có phản hồi thực tế từ người đọc của nhóm; không coi đây là pain đã xác nhận. |

## 3. Top 3 Problem Cards nháp theo CP2

Xếp hạng dưới đây là đề xuất research, chưa phải quyết định qua pitch hoặc chấm điểm của nhóm.

| Rank | Problem | Vì sao đáng kiểm tra | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Kiểm tra số liệu từ bảng scan (#1) | Đầu ra có thể đối chiếu với ảnh gốc; dễ giới hạn vào giá trị, đơn vị và trang nguồn | Người dùng có thực sự lấy số liệu từ scan thường xuyên? Công cụ OCR sẵn có đã đủ chưa? |
| 2 | Truy lại trang gốc của số liệu (#3) | Actor và thao tác rõ; có phương án No AI để so sánh | Ghi số trang hoặc dùng Zotero có thể giải quyết hoàn toàn |
| 3 | Tìm đoạn cần đọc trong PDF ảnh (#2) | Có tình huống và thao tác quan sát được | Chỉ cần tìm bản PDF có text hoặc chạy OCR một lần có thể đã đủ |

### Problem Card #1 — Kiểm tra giá trị và đơn vị từ bảng scan

| Trường | Nội dung nháp |
|---|---|
| Job Story | Khi đưa số liệu từ bảng trong tài liệu scan vào báo cáo nhóm, tôi muốn kiểm tra đúng giá trị, dấu thập phân và đơn vị, để các phép tính sau đó dùng đúng dữ liệu |
| Actor | Sinh viên được giao trích số liệu cho một báo cáo có sử dụng bảng nguồn |
| Thời điểm / bối cảnh | Trước khi bàn giao bảng tổng hợp cho thành viên phân tích hoặc viết báo cáo |
| Quy trình hiện tại giả thuyết | Mở trang → lấy dữ liệu bằng cách đang dùng → đối chiếu ảnh → kiểm đơn vị → ghi nguồn → bàn giao |
| Bottleneck cần kiểm tra | Đối chiếu từng giá trị với đúng hàng/cột trong ảnh; chưa đo thời gian |
| Impact cần kiểm tra | Thời gian rà, số ô sửa lại, số lỗi người review phát hiện; chưa có kết quả |
| Success metric đề xuất | Đo baseline trên 10 ô số liệu ở quy trình hiện tại; thử phương án thay thế trên bộ 10 ô tương đương. Target thăm dò: giảm ít nhất 30% thời gian, không tăng số lỗi so với đáp án do người kiểm tra độc lập lập. Đây là ngưỡng đề xuất, không phải số liệu đã đo |
| Phương án không dùng AI | Xin bảng dữ liệu gốc; checklist giá trị–đơn vị–nguồn; hai người đối chiếu các ô được sử dụng |
| Giả thuyết về AI | Chỉ cân nhắc gợi ý bản trích có gắn vị trí nguồn nếu phương án đơn giản chưa đủ; người dùng phải kiểm lại ảnh |
| Cảm nhận nhanh | Chưa biết; thử No AI và công cụ OCR hiện có trước |

```text
QUY TRÌNH CẦN QUAN SÁT — chưa đo tổng thời gian
[1 Mở trang: t1] → [2 Lấy dữ liệu: t2]
→ [3 Đối chiếu từng giá trị với ảnh: t3] ← BOTTLENECK GIẢ THUYẾT
→ [4 Kiểm đơn vị: t4] → [5 Ghi nguồn: t5] → [6 Bàn giao: t6]
Tổng = t1 + t2 + t3 + t4 + t5 + t6; thay t bằng số phút quan sát thật.
```

### Problem Card #2 — Truy lại nguồn của số liệu

| Trường | Nội dung nháp |
|---|---|
| Job Story | Khi nhóm hỏi nguồn của một con số trong bảng tổng hợp, tôi muốn mở được đúng trang và đoạn gốc, để kiểm tra lại con số mà không đọc lại cả tài liệu |
| Actor | Sinh viên tổng hợp số liệu và thành viên review |
| Thời điểm / bối cảnh | Rà báo cáo trước khi nộp hoặc sửa một giá trị bị nghi ngờ |
| Quy trình hiện tại giả thuyết | Đọc câu hỏi → tìm file → tìm trang → tìm bảng → phản hồi kèm nguồn |
| Bottleneck cần kiểm tra | Tìm lại trang/bảng khi bảng tổng hợp không lưu vị trí nguồn |
| Impact cần kiểm tra | Phút/lần truy nguồn, số lần không tìm được nguồn và số vòng hỏi lại |
| Success metric đề xuất | Đo thời gian truy lại 5 giá trị trước/sau cách ghi nguồn. Target thăm dò: tìm đúng nguồn cho 5/5 giá trị và giảm ít nhất 50% thời gian; baseline chưa thu thập |
| Phương án không dùng AI | Thêm cột file–trang–tên bảng; dùng ghi chú liên kết về PDF trong Zotero [S3] |
| Giả thuyết về AI | Chưa thấy cần AI khi vị trí nguồn được ghi đầy đủ |
| Cảm nhận nhanh | Ưu tiên thử No AI |

```text
QUY TRÌNH CẦN QUAN SÁT — chưa đo tổng thời gian
[1 Nhận câu hỏi: t1] → [2 Tìm file: t2]
→ [3 Tìm trang: t3] ← BOTTLENECK GIẢ THUYẾT
→ [4 Định vị bảng/đoạn: t4] → [5 Phản hồi nguồn: t5]
Tổng = t1 + t2 + t3 + t4 + t5; ghi số phút thật khi quan sát.
```

### Problem Card #3 — Tìm đoạn cần đọc trong PDF ảnh

| Trường | Nội dung nháp |
|---|---|
| Job Story | Khi cần tìm lại một khái niệm trong tài liệu chỉ có ảnh, tôi muốn xác định được trang chứa đoạn cần đọc, để tiếp tục làm bài mà không lật từng trang |
| Actor | Sinh viên đang dùng tài liệu scan không tìm kiếm được văn bản |
| Thời điểm / bối cảnh | Làm bài cần đối chiếu một định nghĩa hoặc khái niệm đã đọc |
| Quy trình hiện tại giả thuyết | Mở tài liệu → thử tìm từ → xem mục lục → lật trang → ghi vị trí |
| Bottleneck cần kiểm tra | Lật trang bằng mắt sau khi tìm kiếm văn bản không trả kết quả |
| Impact cần kiểm tra | Thời gian đến đoạn đúng, số lượt đổi từ khóa và số lần bỏ cuộc |
| Success metric đề xuất | Đo 5 lượt tìm với câu hỏi tương đương trước/sau xử lý. Target thăm dò: tìm đúng ít nhất 4/5 đoạn và giảm ít nhất 30% thời gian; baseline chưa thu thập |
| Phương án không dùng AI | Tìm bản text do nhà xuất bản cung cấp; mục lục và bookmark trang |
| Giả thuyết về AI | OCR hiện có có thể đủ để tìm bằng từ khóa; chưa có bằng chứng cần mô hình sinh văn bản |
| Cảm nhận nhanh | Thử bản text hoặc OCR có sẵn; chưa chọn mức can thiệp theo lab |

```text
QUY TRÌNH CẦN QUAN SÁT — chưa đo tổng thời gian
[1 Mở tài liệu: t1] → [2 Thử tìm từ: t2] → [3 Xem mục lục: t3]
→ [4 Lật trang tìm đoạn: t4] ← BOTTLENECK GIẢ THUYẾT
→ [5 Ghi vị trí: t5]
Tổng = t1 + t2 + t3 + t4 + t5; ghi số phút thật khi quan sát.
```

## 4. Research công cụ / pattern cho CP4

| Công cụ / pattern | Giải bước nào | Điểm đã kiểm từ tài liệu | Khoảng trống phải thử | Bài học |
|---|---|---|---|---|
| Adobe Acrobat — rà lỗi nhận dạng [S2] | Kiểm và sửa chữ sau OCR | Có hướng dẫn review/correct các từ nhận dạng đáng ngờ | Chưa thử bảng, tiếng Việt, số liệu hoặc phiên bản người dùng có | Không tự xây OCR chỉ vì tài liệu là ảnh; thử chức năng có sẵn trước |
| Zotero — ghi chú liên kết trang [S3] | Truy từ ghi chú về nguồn | Annotation trong note có liên kết PDF và trích dẫn | Việc gắn từng ô bảng vào đúng vùng nguồn cần thử | Vấn đề truy nguồn có thể giải bằng cách ghi chú |
| Tìm bản PDF text thay bản scan [S1] | Loại bỏ trở ngại trước khi trích | CU Boulder khuyên tìm bản thay thế có text | Có bản hợp lệ, đúng phiên bản và đúng bảng không? | Sửa đầu vào có thể tốt hơn thêm AI |

## 5. Kế hoạch kiểm chứng đề xuất cho candidate #1

Tìm 2–3 người ngoài nhóm **thật sự vừa trích số liệu từ tài liệu scan**. Nếu không tìm được người phù hợp, đổi candidate; không phỏng vấn bất kỳ ai rồi giả định họ gặp pain.

Các câu hỏi đề xuất, chưa phải phỏng vấn đã thực hiện:

1. Lần gần nhất bạn đưa số liệu từ tài liệu scan vào bài viết là khi nào? Cho xem một ví dụ đã ẩn thông tin nhạy cảm nếu tiện.
2. Bạn đã làm những bước nào, từ mở tài liệu đến đưa số liệu vào bài?
3. Lần đó bạn kiểm giá trị và đơn vị thế nào? Có phát hiện lỗi cụ thể nào không?
4. Khi bạn khác hỏi nguồn một con số, bạn đã tìm lại thế nào?
5. Bạn đã thử xin bảng gốc, tìm bản PDF text hoặc công cụ OCR chưa? Kết quả lần đó ra sao?

Nếu được đồng ý, quan sát một tác vụ trích và rà 10 ô số liệu. Lưu thời gian từng bước, lỗi trước/sau rà và công cụ đang dùng. Chỉ dùng tài liệu có quyền truy cập, không đưa dữ liệu riêng lên dịch vụ ngoài khi chưa được phép.

**Tín hiệu phản bác cần tìm:** ít người dùng scan; hiếm khi cần trích số liệu; kiểm tra chỉ mất ít thời gian; bản text/bảng gốc đã sẵn có; OCR hiện tại đủ tốt; nỗi đau chính là hiểu nội dung chứ không phải kiểm số.

**Điều kiện tiếp tục nghiên cứu, chưa phải quyết định nhóm:** có người dùng phù hợp và quan sát được khó khăn lặp lại. Chỉ đề xuất Workflow nếu thử nghiệm cho thấy cách đơn giản không đủ. Chưa có cơ sở chọn Agent hoặc kết luận Go.

## 6. Nguồn đã mở và kiểm

Các nguồn bên dưới được mở ngày 09/11/2026. Chúng chứng minh đặc điểm tài liệu/công cụ; không chứng minh mức độ đau, thời gian hay nhu cầu của sinh viên trong lớp.

- **S1:** [University of Colorado Boulder — Choosing Accessible PDFs for Your Course](https://www.colorado.edu/digital-accessibility/resources/choosing-accessible-pdfs). PDF scan có thể thiếu text chọn được; OCR có thể sai và phụ thuộc chất lượng ảnh; nên tìm bản text thay thế khi có.
- **S2:** [Adobe — Fix text recognition errors in scanned PDFs](https://helpx.adobe.com/acrobat/desktop/create-documents/scan-documents-to-pdfs/fix-scanned-text.html). Hướng dẫn rà và sửa phần chữ nhận dạng không chắc chắn.
- **S3:** [Zotero — PDF Reader and Note Editor](https://www.zotero.org/support/pdf_reader). Ghi chú từ annotation có liên kết về trang PDF và trích dẫn.
- **S4:** [Zotero — Retrieve PDF Metadata](https://www.zotero.org/support/retrieve_pdf_metadata). Có lấy metadata tự động và phương án bổ sung khi không tìm được kết quả phù hợp.
- **S5:** [W3C WAI — Complex Images](https://www.w3.org/WAI/tutorials/images/complex/). Mô tả hình phức tạp cần truyền đạt thông tin thiết yếu như thang đo, giá trị, quan hệ và xu hướng.

## 7. Cách dùng vào bài nộp

Chỉ chuyển candidate vào báo cáo cá nhân sau khi đối chiếu trải nghiệm thật và ghi rõ ý do AI gợi ý. Bổ sung dữ liệu đo trước khi gọi các quy trình này là quy trình hiện tại. Nhóm tự pitch, phản biện và chọn candidate ở CP3. Phỏng vấn thực tế, đóng góp cá nhân, reflection và quyết định nhóm vẫn cần được thực hiện và ghi trung thực.
