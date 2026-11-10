# Báo cáo cá nhân — 2A202603768_NguyenQuangHuy

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Quang Huy
- MSSV: 2A202603768
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: G3
- Link repo nhóm: https://github.com/lqkhanhno/K5-L3B-DAY02-G3-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi đến tối Chủ Nhật trước buổi báo cáo đồ án hằng tuần, tôi muốn gom đầy đủ kết quả các lần chạy code thử nghiệm trong tuần, các thiết lập đã thay đổi và những chỗ đang bị kẹt về một chỗ, để gửi báo cáo tiến độ cho thầy hướng dẫn trước 22h mà không bị sót ý. | Tôi, giảng viên hướng dẫn | 1 lần/tuần, mất 60–70 phút mỗi tối Chủ Nhật để mở lại từng file Google Colab, bảng Excel và tin nhắn nháp; 3/7 tuần gần đây gửi báo cáo muộn sau 23h (bằng chứng: lịch sử gửi email/Zalo cho thầy). |
| 2 | Lặp lại | Khi viết thêm nội dung mới vào file Word báo cáo đồ án mỗi cuối tuần, tôi muốn biết ngay các mục lục, số thứ tự bảng biểu, hình ảnh và danh sách tài liệu tham khảo đã khớp nhau và đúng quy định trình bày của khoa hay chưa, để không phải dò mắt sửa từng trang trước khi gửi thầy xem. | Tôi | 1–2 lần/tuần trước khi gửi bản nháp, mất 25–30 phút/lần kéo chuột dò từng trang Word dài hơn 40 trang; lần gửi Chương 2 tuần trước vẫn bị thầy khoanh đỏ 6 lỗi nhảy sai số thứ tự bảng và lệch cỡ chữ. |
| 3 | Tốn thời gian | Khi chạy thử mô hình dự đoán trên Python với nhiều cách thiết lập khác nhau (đổi biến đầu vào, đổi tham số), tôi muốn chuyển nhanh các con số kết quả (độ chính xác, tỷ lệ sai số, thời gian chạy) sang bảng so sánh trong file báo cáo, để không phải gõ tay lại từng con số và sợ nhìn nhầm dòng. | Tôi, giảng viên hướng dẫn | Chạy thử nghiệm 2–3 buổi/tuần (mỗi buổi chạy 8–10 lần), mất 30–35 phút/buổi để copy từng số từ màn hình code sang bảng Word; tuần trước từng gõ nhầm 2 con số làm kết luận trong bài viết bị ngược với biểu đồ. |
| 4 | Tốn thời gian | Khi tải một bộ dữ liệu thực tế (file CSV/Excel vài chục nghìn dòng) về làm đồ án một mình, tôi muốn phát hiện sớm các dòng bị bỏ trống, cột bị nhập sai kiểu (chữ lẫn vào cột số, sai định dạng ngày tháng) và các con số bất thường, để xử lý sạch trước khi đưa vào chạy code mà không bị báo lỗi giữa chừng. | Tôi | 1–2 lần/tuần khi thử bộ dữ liệu mới hoặc ghép thêm bảng dữ liệu, mất 45–60 phút/lần mở Excel và viết lệnh kiểm tra thủ công; tuần trước mất gần 2 tiếng chạy lại từ đầu vì sót 1 cột tiền tệ có chứa ký hiệu chữ (còn lưu lịch sử lỗi trong notebook). |
| 5 | Tốn thời gian | Khi tự đọc một tài liệu hoặc bài viết tiếng Anh dài 15–20 trang để học cách họ làm cho đồ án của mình, tôi muốn nắm nhanh họ dùng dữ liệu gì, các bước tính toán chính ra sao và kết quả đạt được thế nào, để áp dụng thử vào bài của mình mà không mất cả buổi vừa đọc vừa dịch từng đoạn. | Tôi | Đọc 2–3 tài liệu tiếng Anh/tuần, mất trung bình 2–2,5 tiếng/bài; riêng việc tra từ chuyên ngành và lật qua lật lại giữa các trang để hiểu quy trình làm mất khoảng 45 phút/bài (bằng chứng: thư mục tài liệu đồ án có 18 file PDF tô kín highlight). |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi viết phần Tổng quan (Chương 1) cho đồ án từ gần 20 tài liệu đã tải về máy trong suốt 1 tháng qua, tôi muốn so sánh được các tài liệu đó theo cách làm, loại dữ liệu sử dụng và điểm mạnh/điểm yếu của từng bên, để giải thích rõ vì sao hướng làm trong đồ án của mình là hợp lý. | Tôi, giảng viên hướng dẫn | Đã lưu 18 file PDF trong máy nhưng ghi chú nằm rải rác ở tên file, sổ tay và Zalo Cloud ("Truyền file"); cuối tuần trước mất hơn 3 tiếng mở lại từng file để tìm xem bài nào có cùng loại dữ liệu với đồ án của mình. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi cần kiểm tra lịch nộp quyển đồ án, quy định mẫu bìa, điều kiện xét tốt nghiệp và lịch rảnh của thầy hướng dẫn, tôi muốn gom các thông tin nằm rải rác ở nhiều kênh về một chỗ theo thứ tự thời gian, để không bị lỡ mốc quan trọng nào trong học kỳ cuối. | Sinh viên năm cuối trong khoa (khoảng 60 SV cùng khóa) | 2–3 lần/tuần phải lục tìm thông báo trên website khoa, email trường và nhóm Zalo lớp (trôi hơn 300 tin nhắn/tuần), mất 15–20 phút/lần; tháng trước có 4 bạn trong lớp nộp trễ form đăng ký đề tài vì tin nhắn bị trôi trên Zalo. |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi tìm chỗ thực tập hoặc việc làm đầu tiên (vị trí phân tích dữ liệu / lập trình Python) vào năm cuối, tôi muốn đối chiếu nhanh yêu cầu của từng tin tuyển dụng (JD) với những đồ án và môn học Toán-Tin mình đã làm, để chỉnh lại CV cho sát với vị trí đó trước khi bấm nộp. | Tôi và các bạn năm cuối đang đi rải CV  | Xem 5–7 tin tuyển dụng/tuần trên TopCV và LinkedIn, mất 35–45 phút/tin để đọc kỹ yêu cầu và sửa lại mô tả đồ án trong CV; hỏi 5 bạn cùng lớp thì cả 5 đều ngại sửa nên dùng chung 1 CV rải mọi nơi, tỷ lệ được gọi phỏng vấn rất thấp (1–2/10 đơn). |
| 9 | Pain từ người khác | Khi thầy hướng dẫn xem bảng kết quả chạy mô hình hằng tuần của tôi, thầy muốn biết ngay bảng số liệu đó chạy trên tập dữ liệu nào và đã sửa gì so với tuần trước, để góp ý hướng làm tiếp theo ngay trong buổi gặp mà không phải hỏi đi hỏi lại. | Thầy hướng dẫn, bản thân tôi (người báo cáo) | Trong 4 buổi gặp thầy gần nhất, mất 10–15 phút đầu mỗi buổi (trên tổng 30 phút gặp mặt) chỉ để tôi mở lại code tra cứu và trả lời các câu hỏi lặp lại của thầy như "Bảng này đã bỏ các dòng lỗi chưa?" hay "Tuần trước con số này là bao nhiêu?" (ghi trong sổ tay họp đồ án). |
| 10 | Pain từ người khác | Khi các bạn cùng lớp hoặc mấy em khóa dưới tự cài đặt thư viện Python và chạy code làm đồ án cá nhân, họ muốn biết ngay cách xử lý các lỗi cài đặt quen thuộc và cách lấy dữ liệu mẫu, để tự chạy được bài mà không bị đứng hình chờ người khác trả lời tin nhắn. | Các bạn cùng lớp và em khóa dưới (khoảng 15–20 người hay nhắn hỏi), bản thân tôi | Mỗi tuần tôi nhận được 5–7 tin nhắn riêng trên Zalo/Discord hỏi đi hỏi lại đúng 3–4 lỗi cơ bản (lỗi xung đột phiên bản thư viện Python, lỗi tràn bộ nhớ trên Google Colab, lỗi đường dẫn đọc file CSV), mỗi lần chỉ dẫn lại qua màn hình chụp mất 10–15 phút. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Quy trình thực hiện:** Tôi tự liệt kê trước 8 vấn đề thật từ việc làm đồ án một mình và chuẩn bị ra trường (#1 đến #8), sau đó dùng prompt theo 4 lăng kính để hỏi AI gợi ý thêm góc nhìn.
- **Ý giữ lại (sau khi đã viết lại bằng trải nghiệm và số liệu thật của chính mình):**
  - **Ý #9** (Pain từ thầy hướng dẫn phải hỏi lại ngữ cảnh bảng số liệu mỗi buổi gặp) và **Ý #10** (Pain từ bạn bè/em khóa dưới nhắn hỏi lặp lại lỗi cài đặt Python/Colab): AI gợi ý lăng kính "Ai quanh bạn đang phải hỏi lại cùng một câu hỏi mỗi tuần?", giúp tôi nhận ra nỗi đau rất thật từ thầy hướng dẫn và các bạn nhắn Zalo hỏi bài, có số phút và lịch sử tin nhắn đếm được.
- **Ý bỏ đi và lý do:**
  - *"Cần một trợ lý AI tự động code và giải toàn bộ bài toán trong đồ án tốt nghiệp"* — **Bỏ** vì đây là giải pháp đội lốt vấn đề (nhét sẵn chữ "trợ lý AI"), phạm vi quá rộng kiểu "AI toàn năng", không chỉ ra được bước nghẽn cụ thể nào và làm mất ý nghĩa tự làm đồ án.
  - *"Tự động hóa việc phân tích xung đột khi ghép code giữa các thành viên trong nhóm đồ án"* — **Bỏ** vì không đúng trải nghiệm thật của tôi (tôi làm đồ án độc lập 1 mình, không làm theo nhóm nên không có bước ghép code với bạn khác).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Gom kết quả chạy code thử nghiệm trong tuần để viết báo cáo tiến độ đồ án gửi thầy hướng dẫn (#1 kết hợp #9) | Việc lặp lại đều đặn mỗi tối Chủ Nhật khi làm đồ án 1 mình; quy trình 7 bước rất rõ (65 phút/tuần); giải quyết được cả nỗi đau của mình lẫn việc thầy hướng dẫn phải hỏi lại mỗi buổi gặp; dễ so sánh 4 mức No AI / Rule / Workflow / Agent | Đo chất lượng phần "giải thích vì sao kết quả tuần này tăng/giảm" như thế nào cho khách quan ngoài việc đếm số phút? |
| 2 | Tổng hợp và so sánh gần 20 tài liệu đã đọc để viết Chương 1 (Tổng quan) cho đồ án (#6) | Tốn rất nhiều thời gian (hơn 3 tiếng mỗi đợt ngồi viết) vì làm đồ án 1 mình phải tự đọc hết; bước nghẽn rất rõ là phải mở lại từng file PDF để tìm xem bài đó dùng dữ liệu gì và cách làm có điểm yếu gì | Nếu nhờ công cụ tóm tắt từ file PDF tiếng Anh thì có bị sót ý hoặc dịch lệch các thuật ngữ chuyên ngành Toán-Tin không? |
| 3 | Kiểm tra lỗi nhảy số thứ tự bảng biểu, hình ảnh, mục lục và lệch cỡ chữ trong file Word báo cáo đồ án (#2) | Làm hằng tuần trước mỗi lần gửi bài cho thầy; đầu vào và đầu ra cực kỳ rõ ràng (file Word báo cáo), rất vừa sức để kiểm chứng ngay trong 1 buổi học | Thực ra chỉ cần dùng đúng công cụ có sẵn của Word (No AI) hoặc lệnh kiểm tra cố định (Rule) là đã giải quyết được 85–90% mà không cần dùng đến AI? |

### Problem Card #1 — Gom kết quả chạy code và viết báo cáo tiến độ đồ án hằng tuần (Problem #1 & #9)

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến tối Chủ Nhật trước buổi báo cáo đồ án hằng tuần, tôi muốn gom đầy đủ kết quả các lần chạy code thử nghiệm trong tuần, các thiết lập đã thay đổi và những chỗ đang bị kẹt về một chỗ, để gửi báo cáo tiến độ cho thầy hướng dẫn trước 22h mà không bị sót ý hay phải mất thời gian tra cứu lại khi thầy hỏi. |
| Actor | Sinh viên năm cuối ngành Toán-Tin ứng dụng làm đồ án tốt nghiệp 1 mình (và thầy hướng dẫn là người đọc báo cáo). |
| Thời điểm / bối cảnh | Tối Chủ Nhật hằng tuần (khoảng 20h30–22h), sau một tuần tự chạy thử nhiều phiên bản code khác nhau và trước buổi gặp thầy sáng thứ Hai. |
| Quy trình hiện tại (3–7 bước) | 1. Mở lại các file code trên Google Colab / máy tính đã chạy từ thứ Hai đến thứ Bảy để tìm số liệu (10') · 2. Xem lại lịch sử sửa code để nhớ tuần này đã đổi tham số gì, thêm bớt cột dữ liệu nào (10') · 3. Copy các con số kết quả (độ chính xác, sai số, thời gian chạy) vào một bảng so sánh với tuần trước (10') · 4. Lục lại ghi chú trong sổ tay và tin nhắn Zalo Cloud ("Truyền file") xem tuần qua gặp lỗi gì (10') · 5. Ngồi viết đoạn nhận xét: vì sao kết quả tuần này tốt hơn hay kém đi, tuần tới dự định làm gì tiếp (15') · 6. Chụp ảnh biểu đồ dán vào email/file báo cáo và chỉnh lại trình bày (5') · 7. Đọc lại lần cuối rồi gửi cho thầy hướng dẫn (5'). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Có 2 điểm nghẽn liên tiếp: **Bước 1–2** (mất 20 phút lục tìm lại kết quả và nhớ xem mình đã sửa gì trong code vì trong tuần chạy xong không ghi lại ngay) và **Bước 5** (mất 15 phút ngồi viết đoạn giải thích nguyên nhân kết quả tăng/giảm sao cho rõ ý). |
| Impact (nếu không giải thì sao) | Mất 65 phút mỗi tối Chủ Nhật; 3/7 tuần gần đây gửi báo cáo trễ sau 23h; sáng thứ Hai gặp thầy lại mất thêm 10–15 phút đầu buổi chỉ để mở máy tìm lại xem bảng số liệu đó chạy với dữ liệu nào khi thầy hỏi. |
| Success metric (baseline → target) | (1) Thời gian làm báo cáo tối Chủ Nhật giảm từ 65 phút xuống dưới 20 phút/lần; (2) Số câu thầy hướng dẫn phải hỏi lại về thông tin cơ bản ("chạy trên dữ liệu nào, thay đổi gì so với tuần trước") giảm từ 3–4 câu xuống tối đa 1 câu mỗi buổi gặp. |
| Phương án không dùng AI | Lập một bảng mẫu (template) cố định trên Excel/Notion và tập thói quen mỗi lần chạy code xong phải điền ngay 1 dòng (ngày chạy, dữ liệu, tham số, kết quả) — cách này giảm được thời gian lục tìm ở bước 1–2, nhưng tối Chủ Nhật vẫn phải tự tổng hợp và viết nhận xét ở bước 5. |
| Giả thuyết về AI (nếu có) | Kết hợp **Rule + AI (Workflow)**: Thêm vài dòng lệnh cố định (Rule) ở cuối file code Python để mỗi lần chạy xong tự động lưu thông số và kết quả vào 1 file Excel chung; đến tối Chủ Nhật đưa bảng kết quả tuần này + tuần trước cho AI soạn nháp đoạn nhận xét so sánh, sau đó tôi tự đọc kiểm tra lại rồi mới gửi thầy. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 65 phút/tuần (7 bước thủ công)

[1 Mở lại các file Colab/code tìm kết quả: 10']  ← BOTTLENECK 1 (Lục tìm thông tin rời rạc: 20')
→ [2 Xem lịch sử code để nhớ đã sửa tham số gì: 10']
→ [3 Copy số liệu vào bảng so sánh với tuần trước: 10']
→ [4 Lục sổ tay & Zalo Cloud tìm lại các lỗi gặp phải: 10']
→ [5 Viết đoạn giải thích vì sao kết quả tăng/giảm & hướng tuần tới: 15'] ← BOTTLENECK 2 (Viết tổng hợp: 15')
→ [6 Chèn ảnh biểu đồ & chỉnh trình bày: 5']
→ [7 Đọc rà soát & gửi email/Zalo cho thầy: 5']
```

### Problem Card #2 — Tổng hợp và so sánh tài liệu đã đọc để viết Chương 1 đồ án (Problem #6)

| Trường | Nội dung |
|---|---|
| Job Story | Khi viết phần Tổng quan (Chương 1) cho đồ án từ gần 20 tài liệu đã tải về máy trong suốt 1 tháng qua, tôi muốn so sánh được các tài liệu đó theo cách làm, loại dữ liệu sử dụng và điểm mạnh/điểm yếu của từng bên, để giải thích rõ vì sao hướng làm trong đồ án của mình là hợp lý. |
| Actor | Sinh viên năm cuối Toán-Tin ứng dụng làm đồ án một mình, đang trong giai đoạn viết báo cáo Chương 1 (Tổng quan). |
| Thời điểm / bối cảnh | Các buổi cuối tuần khi ngồi viết báo cáo đồ án, sau khi đã tải và đọc rải rác khoảng 18–20 tài liệu/bài báo trong suốt tháng trước. |
| Quy trình hiện tại (3–7 bước) | 1. Mở thư mục chứa 18 file PDF tài liệu đã tải trong máy tính (5') · 2. Mở lại từng file PDF, lướt tìm phần giới thiệu và phương pháp để nhớ lại bài đó giải quyết vấn đề gì, dùng cách tính toán nào (75') · 3. Kéo xuống phần thử nghiệm của từng bài để xem họ dùng bộ dữ liệu nào, kích thước bao nhiêu (35') · 4. Đọc phần kết luận và lục lại ghi chú cũ trong sổ tay/Zalo xem cách của họ có nhược điểm gì (30') · 5. Gõ tay từng dòng tóm tắt vào bảng so sánh trong Word/Excel (25') · 6. Dựa vào bảng để viết thành đoạn văn nhận xét cho Chương 1 (30'). |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 2 & 3** — Phải mở lại từng file PDF tiếng Anh để đọc dò tìm phương pháp và bộ dữ liệu (mất 110 phút cho khoảng 15–18 tài liệu, vì lúc đọc lần đầu không ghi chép theo cùng một mẫu nên quên hết chi tiết). |
| Impact (nếu không giải thì sao) | Tốn более 3 tiếng (200 phút) mỗi đợt ngồi viết tổng quan; làm một mình nên rất dễ nản, dễ nhớ nhầm số liệu của bài này sang bài kia khiến lập luận ở Chương 1 bị thầy hướng dẫn bắt bẻ. |
| Success metric (baseline → target) | Thời gian lập bảng đối chiếu cho 15–18 tài liệu giảm từ 200 phút xuống dưới 60 phút; 100% thông tin về bộ dữ liệu và ưu/nhược điểm trong bảng có ghi kèm số trang của file PDF gốc để tra lại ngay khi cần. |
| Phương án không dùng AI | Tạo sẵn 1 bảng Excel gồm 5 cột cố định (Tên bài, Cách làm chính, Dữ liệu sử dụng, Kết quả, Điểm yếu) và bắt buộc mình điền ngay lúc vừa đọc xong mỗi bài lần đầu tiên. |
| Giả thuyết về AI (nếu có) | Dùng **Workflow**: Đưa từng file PDF đã tải vào công cụ đọc tài liệu, yêu cầu AI trích xuất nháp đúng 5 cột thông tin trên kèm trích dẫn trang số mấy trong bài; tôi chỉ việc mở đúng trang đó kiểm tra lại rồi ghép vào bảng. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 200 phút/đợt viết tổng quan (~18 file PDF)

[1 Mở thư mục lọc danh sách file PDF đã tải: 5']
→ [2 Mở lại từng PDF đọc dò tìm phương pháp tính toán: 75'] ← BOTTLENECK (1)
→ [3 Kéo tìm thông tin bộ dữ liệu ở phần thử nghiệm: 35']   ← BOTTLENECK (2)
→ [4 Tìm điểm yếu ở cuối bài & lục lại ghi chú cũ: 30']
→ [5 Gõ tay từng bài vào bảng so sánh trên Word/Excel: 25']
→ [6 Viết đoạn văn nhận xét tổng quan cho Chương 1: 30']
```

### Problem Card #3 — Kiểm tra lỗi đánh số bảng biểu, hình ảnh và trình bày trong file Word đồ án (Problem #2)

| Trường | Nội dung |
|---|---|
| Job Story | Khi viết thêm nội dung mới vào file Word báo cáo đồ án mỗi cuối tuần, tôi muốn biết ngay các mục lục, số thứ tự bảng biểu, hình ảnh và danh sách tài liệu tham khảo đã khớp nhau và đúng quy định trình bày của khoa hay chưa, để không phải dò mắt sửa từng trang trước khi gửi thầy xem. |
| Actor | Sinh viên năm cuối làm đồ án tốt nghiệp, tự viết và căn chỉnh quyển báo cáo trên Microsoft Word (cùng khoảng 30 bạn cùng đợt làm đồ án). |
| Thời điểm / bối cảnh | Cuối mỗi tuần, ngay trước khi xuất file báo cáo đồ án gửi cho thầy hướng dẫn đọc duyệt. |
| Quy trình hiện tại (3–7 bước) | 1. Mở file Word báo cáo (dài hơn 40 trang) và lướt từ đầu đến cuối để kiểm tra cỡ chữ, giãn dòng (5') · 2. Dò bằng mắt từng hình vẽ và bảng biểu xem khi chèn thêm hình mới ở giữa bài thì các hình phía sau và câu dẫn trong bài ("như ở Bảng 2.3...") có bị lệch số thứ tự không (10') · 3. Kiểm tra danh sách tài liệu tham khảo cuối bài xem có tài liệu nào trích dẫn trong bài mà quên ghi ở cuối (hoặc ngược lại) không (8') · 4. Gõ tay sửa lại từng số thứ tự bị lệch và bấm cập nhật lại mục lục (5') · 5. Xuất ra file PDF kiểm tra lần cuối trước khi gửi thầy (2'). |
| Bottleneck (bước nào, mất bao nhiêu phút) | **Bước 2 & 3** — Dò bằng mắt qua hơn 40 trang để tìm chỗ lệch số thứ tự bảng/hình và đối chiếu tài liệu tham khảo (mất 18 phút/lần kiểm tra và rất dễ nhìn sót khi mỏi mắt). |
| Impact (nếu không giải thì sao) | Mất 30 phút mỗi tuần lặp đi lặp lại; dù đã dò tay nhưng bản gửi Chương 2 tuần trước vẫn bị thầy khoanh đỏ 6 lỗi nhảy sai số bảng và lệch font chữ, gây mất thiện cảm về sự chỉn chu. |
| Success metric (baseline → target) | Thời gian kiểm tra trình bày trước khi gửi bài giảm từ 30 phút xuống dưới 5 phút/lần; giảm số lỗi đánh số bảng biểu/hình ảnh bị thầy phát hiện từ 6 lỗi xuống 0 lỗi. |
| Phương án không dùng AI | Chuyển sang dùng tính năng đánh số tự động (Insert Caption & Cross-reference) và tạo Style chuẩn ngay từ đầu trong Microsoft Word, kết hợp ấn `Ctrl + A` rồi `F9` để Word tự cập nhật toàn bộ số thứ tự và mục lục trong 30 giây. |
| Giả thuyết về AI (nếu có) | Bài toán này **không cần AI** (chỉ cần **No AI** là dùng đúng tính năng tự động của Word, hoặc tối đa là **Rule** bằng một macro/script kiểm tra font chữ và lề giấy theo quy định cố định của khoa). Dùng AI đọc file Word để dò số thứ tự vừa tốn thời gian vừa dễ bị AI nhìn nhầm. |
| Cảm nhận nhanh | No AI / Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 30 phút/lần kiểm tra (file Word >40 trang)

[1 Lướt kiểm tra cỡ chữ & giãn dòng toàn bài: 5']
→ [2 Dò mắt từng trang tìm bảng/hình bị nhảy lệch số thứ tự: 10'] ← BOTTLENECK (1)
→ [3 Đối chiếu trích dẫn trong bài với danh sách cuối bài: 8']     ← BOTTLENECK (2)
→ [4 Sửa tay từng số bị lệch & bấm cập nhật mục lục: 5']
→ [5 Xuất file PDF & kiểm tra lần cuối: 2']
```

### Card muốn pitch nhất

- **Card số:** Card #1 — Gom kết quả chạy code và viết báo cáo tiến độ đồ án hằng tuần (Problem #1 kết hợp #9).
- **Vì sao:**
  1. Đây là việc thật 100% xảy ra đều đặn mỗi tối Chủ Nhật khi tôi làm đồ án một mình, có số phút đo được rõ ràng (65 phút/tuần) và giải quyết cùng lúc nỗi đau của cả 2 phía: bản thân tôi đỡ vất vả gom số liệu tối Chủ Nhật, còn thầy hướng dẫn đỡ mất 10–15 phút đầu buổi gặp để hỏi lại "bảng này chạy với dữ liệu nào, sửa gì so với tuần trước?".
  2. Quy trình tách rất rõ bước nào chỉ cần **Rule** (vài dòng lệnh Python tự lưu tham số và kết quả ra file Excel mỗi khi chạy code xong) và bước nào **AI trong Workflow** mới phát huy tác dụng (đọc bảng so sánh tuần này với tuần trước để nháp đoạn nhận xét).
- **Câu hỏi muốn nhóm phản biện:**
  1. Điểm nghẽn thật sự nằm ở bước "ngồi viết đoạn giải thích kết quả (15 phút)" hay nằm ở thói quen "lúc chạy code trong tuần lười ghi chú lại khiến tối Chủ Nhật mất 20 phút lục tìm"?
  2. Nếu chỉ dùng một bảng Excel mẫu cố định + đoạn lệnh tự động lưu kết quả mỗi lần chạy code (**No AI + Rule**), liệu đã giải quyết được 80% vấn đề mà chưa cần tới AI viết nháp nhận xét chưa?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| 1. **Xác định thiếu điểm nghẽn ở Card #1:** Ban đầu chỉ ghi bước 5 (viết nhận xét, 15 phút) là bottleneck, nhưng thực tế bước 1 + 2 (mở lại từng file code và nhớ xem đã sửa tham số gì) ngốn tới 20 phút. Nếu không gom được số liệu đúng thì AI cũng không viết nhận xét được. | Đồng ý | Sửa lại mục Bottleneck và sơ đồ quy trình của Card #1: tách rõ **Bottleneck 1** (20 phút lục tìm thông tin rời rạc — giải bằng Rule tự lưu kết quả lúc chạy code) và **Bottleneck 2** (15 phút viết nhận xét — giải bằng Workflow có AI soạn nháp). |
| 2. **Thước đo thành công (Metric) của Card #1 mới chỉ đo độ nhanh:** Nếu giảm từ 65 phút xuống 20 phút nhờ AI viết nháp, nhưng bản nháp giải thích sai nguyên nhân làm thầy hướng dẫn phải hỏi lại nhiều hơn thì giải pháp vẫn thất bại. | Đồng ý | Bổ sung tiêu chí đo chất lượng vào `Success metric` của Card #1: số câu hỏi xác nhận lại thông tin cơ bản của thầy hướng dẫn ở đầu buổi gặp giảm từ 3–4 câu xuống tối đa 1 câu. |
| 3. **Nhảy sang dùng AI quá sớm ở Card #3 (kiểm tra file Word):** Việc đánh số thứ tự bảng biểu, hình ảnh và kiểm tra cỡ chữ có quy tắc đúng/sai tuyệt đối; dùng AI cho việc này là phức tạp hóa vấn đề. | Đồng ý | Đổi `Cảm nhận nhanh` của Card #3 sang **No AI / Rule** (dùng sẵn tính năng Insert Caption / Cross-reference của Word kết hợp quy tắc kiểm tra định dạng cố định thay vì dùng AI). |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày 3 card cá nhân, tập trung pitch Card #1 (gom kết quả chạy code viết báo cáo tiến độ đồ án hằng tuần) và Card #2 (đối chiếu ~20 file PDF viết tổng quan Chương 1). | Card #2 của tôi và Card #3 của Khoa (lọc công văn/thông tư mới của Bộ/Sở) được gom chung vào nhóm bài toán "Đọc, lọc và đối chiếu tài liệu PDF dài". |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: |  |
| Nhận phản biện | Câu hỏi tôi nhận được: | 	Tôi đã sửa gì: |
| Gom cluster / cây OST |  |  |
| Chọn candidate problem |  |  |
| Kiểm chứng / research |  |  |
| Quy trình nhóm | Cùng nhóm lập bảng quy trình hiện tại 7 bước (chỉ rõ bottleneck 30–60 phút ở bước 3–4 và thiết kế quy trình tương lai 4 bước (Bước 1 Rule/OCR → Bước 2 AI lọc & đối chiếu → Bước 3 Tổ trưởng duyệt HITL → Bước 4 Giáo viên áp dụng). | Hoàn thiện mục 4 (`Quy trình trước/sau`) và bảng `Before / after` trong `group_report.md`, giúp chuyển từ 7 bước thủ công lặp lại ở từng giáo viên sang xử lý tập trung 1 lần tại Tổ trưởng (~15–20 phút). |
| Problem Statement | Tham gia viết `Success Metric`, `Boundary` và phần phản biện của Problem Statement v0; đề xuất thêm tiêu chí đo chất lượng bản nháp (tỉ lệ trích dẫn đúng điều/khoản gốc và phần Tổ trưởng phải sửa lại < 30%) cho bản v1. | Hoàn thiện mục 5 (`Problem Statement v0`) và định hình thay đổi cho `Problem Statement v1` trong `group_report.md` |
| Mức can thiệp AI | Phân tích lý do chọn mức **Workflow** (Rule/OCR tách điều khoản → AI đối chiếu văn bản cũ → Tổ trưởng duyệt) thay vì chỉ dùng Rule (không hiểu được câu chữ sửa đổi hành chính) hay Agent (rủi ro tự suy diễn và tự gửi thông báo sai). | Nhóm thống nhất chọn mức **Workflow**, xác định người dùng muốn được hỗ trợ chứ không giao trắng, ưu tiên tránh lỗi bỏ sót điều khoản thay đổi. |
| Quyết định | Cùng nhóm đánh giá 4 rủi ro và đề xuất ngưỡng dừng + phương án quay về: nếu AI đọc lỗi bản scan hoặc tóm tắt lệch làm Tổ trưởng phải sửa quá 30% thì quay về phân công luân phiên 1 giáo viên điền mẫu tóm tắt 1 trang cố định. | Đưa ngưỡng dừng (< 30% nội dung phải sửa lại) và phương án quay về (Fallback) vào quy trình tương lai và phần kết luận quyết định của nhóm trong `group_report.md`. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý thêm problem theo 4 lăng kính cho SV năm cuối Toán-Tin làm đồ án 1 mình sau khi đã tự liệt kê 8 vấn đề hằng tuần. | Giúp nhận ra thêm góc nhìn "Pain từ người khác" (#9 thầy hướng dẫn hỏi lại, #10 bạn bè hỏi lỗi cài Python) và rà lại cấu trúc câu Job Story. | Ban đầu gợi ý ý quá rộng ("trợ lý AI tự giải đồ án"), dùng từ ngữ học thuật hoặc giả định tôi làm đồ án theo nhóm. | Bỏ các ý "trợ lý toàn năng" và ý làm nhóm; tự viết lại bằng từ ngữ đời thường, gắn số phút và bằng chứng thật từ Zalo, email, file Word và Google Colab. |
| CP2 Problem Card | Đóng vai PM hoài nghi để phản biện 3 Problem Cards cá nhân theo 6 câu hỏi trong worksheet. | Chỉ ra đúng Bottleneck ở Card #1 gồm cả khâu lục tìm kết quả (20') lẫn viết nhận xét (15'), và nhắc Card #3 (kiểm tra file Word) chỉ cần No AI / Rule. | Khi gợi ý hướng giải cho Card #1, AI đề xuất làm hệ thống tự động lấy kết quả và tự gửi email báo cáo luôn cho thầy hướng dẫn. | Bác bỏ việc để AI tự gửi báo cáo; giữ boundary sinh viên phải tự kiểm tra số liệu trước khi gửi, đồng thời chốt Card #3 ở mức No AI / Rule. |
| CP4 Research |Không dùng AI | |  |  |
| CP5 Quy trình | Hỗ trợ chuẩn hóa sơ đồ quy trình hiện tại (7 bước), quy trình tương lai (4 bước) và bảng `Before / after` cho bài toán Công văn của nhóm. | Giúp trình bày rõ luồng xử lý từ lúc nhận văn bản đến lúc cập nhật ma trận đề và ước tính nhanh thời gian tiết kiệm được cho cả tổ chuyên môn. | Gộp bước 3 (lọc phần liên quan môn/khối) với bước 4 (đối chiếu văn bản cũ) thành 1 bước chung và bỏ quên phương án quay về (Fallback) khi AI sai. | Tách rõ bước 3 và bước 4 để làm nổi bật bottleneck (30–60 phút/GV); thêm bước Tổ trưởng duyệt HITL (10–15') và thêm Fallback phân công 1 GV điền mẫu tóm tắt 1 trang. |
| CP5–6 Problem Statement | Phản biện Problem Statement v0 theo 6 trường để tìm điểm còn mơ hồ hoặc thiếu thước đo chất lượng trước khi cập nhật lên v1. | Chỉ ra phạm vi "mọi công văn mới" là quá rộng (vì nhiều thông báo ngắn đọc 5 phút là xong) và metric ở v0 mới chỉ đo thời gian chứ chưa đo chất lượng bản nháp. | Gợi ý đặt mục tiêu "AI tự động sửa luôn ma trận đề và kế hoạch bài dạy cho giáo viên" — lấn sang giải pháp và vi phạm boundary. | Thu hẹp phạm vi vào các văn bản quy định chuyên môn dài có sửa đổi quy định cũ; bổ sung metric chất lượng (trích dẫn đúng điều/khoản gốc, Tổ trưởng sửa lại < 30%) và giữ chặt boundary. |
| CP6 Mức can thiệp / quyết định | Không dùng AI| |  |  |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe trình bày 3 bài toán của giáo viên (viết nhận xét 40 học sinh, trộn mã đề và đọc công văn mới của Bộ/Sở), mình nhận ra những việc lặp đi lặp lại ở cả một tập thể (như cả tổ giáo viên cùng phải đọc một văn bản) có mức độ ảnh hưởng lớn và dễ kiểm chứng thực tế hơn nhiều so với những việc chỉ một mình mình gặp khi tự làm đồ án cá nhân.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Lúc gom nhóm và vẽ cây OST ở CP3, tụi mình từng ghi ngay ý "làm chatbot hỏi đáp công văn" và "tool tự động trộn đề" vào nhánh cơ hội. Sau đó cả nhóm nhận ra đó là giải pháp đội lốt vấn đề nên đã gạch bỏ, sửa lại thành nỗi đau thật là giáo viên mất 30–60 phút tự dò tìm điều khoản liên quan đến môn/khối và phải tự đối chiếu thủ công với văn bản cũ.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Lúc đầu mình rất muốn giữ Card #1 của mình (gom kết quả chạy code tối Chủ Nhật để viết báo cáo đồ án gửi thầy hướng dẫn), nhưng khi các bạn phản biện là bài này chỉ có một mình mình làm đồ án gặp phải và chỉ cần dùng bảng Excel mẫu cộng vài dòng lệnh Python tự lưu kết quả là đã giải quyết được phần lớn rồi, mình thấy hợp lý nên đồng ý rút bài cá nhân để chọn bài Công văn của Khoa.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Mình khá bất ngờ khi thấy không phải công văn nào giáo viên cũng ngại đọc vì các thông báo hành chính ngắn chỉ lướt 5 phút là xong; thứ thực sự làm mất thời gian là các văn bản quy định chuyên môn dài gửi dưới dạng file PDF scan mờ mà chỉ ghi "sửa đổi, bổ sung điều khoản cũ", buộc giáo viên phải tự lục lại văn bản cũ để so sánh từng mục.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Khó nhất là viết phần thước đo thành công (Success Metric) và ranh giới (Boundary) sao cho đo đếm được mà không bị lấn sang giải pháp: ngoài việc rút thời gian biết việc cần làm xuống trong 1 buổi, nhóm phải bàn rất kỹ mới chốt thêm được tiêu chí bắt buộc trích dẫn đúng điều/khoản gốc và tỉ lệ nội dung Tổ trưởng phải sửa lại dưới 30%.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, ở bước CP1–CP2 mình sẽ bấm giờ thực tế ngay từ đầu thay vì ước lượng số phút theo trí nhớ, và khi phản biện bài nhóm mình sẽ hỏi kỹ hơn về việc hiện tại các tổ chuyên môn đang lưu trữ văn bản quy định cũ ở đâu để lúc cần đối chiếu thì lấy ra ngay được.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Bài toán của nhóm mình là khi Bộ/Sở ban hành công văn, thông tư chuyên môn mới, từng giáo viên trong tổ đều phải tự đọc file PDF/scan dài để lọc phần liên quan đến môn, khối mình dạy và đối chiếu thủ công với quy định cũ để kịp sửa ma trận đề, kế hoạch bài dạy. Quy trình hiện tại gồm 7 bước thủ công lặp lại ở từng giáo viên, bị nghẽn nặng nhất ở bước 3–4 (lọc và đối chiếu văn bản cũ mất 30–60 phút/người) và bước 5 (phải chờ họp tổ 1–3 ngày để thống nhất cách hiểu). Nhóm đặt mục tiêu (metric) rút thời gian từ lúc nhận văn bản đến lúc cả tổ nắm được việc cần làm xuống gọn trong 1 buổi (~15–20 phút Tổ trưởng duyệt và 5 phút giáo viên đọc bản tóm tắt), giảm ít nhất 50% số tin nhắn hỏi lại trên Zalo và giảm số lỗi áp dụng sai quy định về 0. Về ranh giới (boundary), AI chỉ được lọc điểm thay đổi theo môn/khối kèm trích dẫn rõ số điều, khoản, trang gốc chứ tuyệt đối không được tự gửi thông báo hay tự sửa vào file ma trận đề, kế hoạch bài dạy của giáo viên. Nhóm chọn mức can thiệp là Workflow (bước 1 dùng Rule/OCR tách điều khoản từ file scan, bước 2 dùng AI đối chiếu với văn bản cũ, bước 3 Tổ trưởng kiểm tra duyệt HITL trước khi phổ biến cho giáo viên ở bước 4) vì chỉ dùng Rule thì không hiểu được ngữ cảnh sửa đổi, còn dùng Agent tự động hoàn toàn thì rủi ro sai sót quá cao. Cuối cùng, nhóm quyết định triển khai thử ở phạm vi nhỏ cho các văn bản quy định chuyên môn dài, kèm ngưỡng dừng rõ ràng là nếu AI đọc lỗi bản scan hoặc Tổ trưởng phải sửa lại quá 30% bản nháp thì sẽ quay về cách phân công luân phiên 1 giáo viên điền mẫu tóm tắt 1 trang cố định cho cả tổ.

---

## 7. Tài liệu tham khảo

-
