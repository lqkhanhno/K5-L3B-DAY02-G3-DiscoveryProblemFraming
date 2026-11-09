# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên:
- MSSV:
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:
- Link repo nhóm:

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi đến tối Chủ Nhật trước buổi họp khóa luận sáng thứ Hai, tôi muốn gom đầy đủ kết quả chạy thực nghiệm mô hình, bộ tham số đã thử và các vướng mắc trong tuần về một chỗ, để gửi báo cáo tiến độ cho giảng viên hướng dẫn (GVHD) trước 22h mà không bị sót số liệu. | Sinh viên làm KLTN, GVHD, 4 thành viên cùng nhóm nghiên cứu | 1 lần/tuần, mất 60–75 phút/lần lục lại các file Jupyter Notebook, log CSV và ghi chú rời rạc; 3/8 tuần gần nhất gửi email muộn sau 23h (bằng chứng: lịch sử gửi email cho GVHD). |
| 2 | Lặp lại | Khi hoàn thiện từng chương khóa luận trên Overleaf mỗi cuối tuần, tôi muốn biết các mục tài liệu tham khảo mới thêm đã đủ trường thông tin (tác giả, năm, tên hội nghị/tạp chí, chuẩn viết tắt) theo format IEEE hay chưa, để không bị lỗi hiển thị hoặc phải dò sửa thủ công từng dòng trước khi nộp bản nháp. | Sinh viên viết KLTN/bài báo khoa học, đồng tác giả trong lab | 1–2 lần/tuần (mỗi lần thêm 5–10 paper), mất 25–30 phút rà soát file `.bib` hơn 60 bài; bản nháp Chương 2 vừa qua bị GVHD comment 8 lỗi thiếu tên tạp chí/sai format trên file PDF. |
| 3 | Tốn thời gian | Khi đọc một bài báo khoa học dài 12–20 trang về tối ưu hóa hoặc học máy để cài đặt lại thuật toán cho đồ án, tôi muốn nắm nhanh mối liên hệ giữa các ký hiệu toán học, giả thiết của định lý và từng bước giả mã (pseudocode), để bắt tay vào code thử nghiệm mà không hiểu sai công thức. | Sinh viên năm cuối làm KLTN, thành viên nhóm seminar (5 người) | Đọc 2–3 paper/tuần, mất trung bình 2,5–3 giờ/paper; riêng việc lật qua lại giữa phần Phương pháp và Phụ lục (Appendix) để tra ký hiệu chiếm 40–50 phút/bài (bằng chứng: hàng chục highlight và note tay trên PDF). |
| 4 | Tốn thời gian | Khi chạy xong 10–15 tổ hợp siêu tham số (hyperparameters) của thuật toán trên Python, tôi muốn chuyển chính xác các chỉ số đánh giá (RMSE, Accuracy, thời gian chạy, số vòng lặp hội tụ) sang bảng so sánh trong Overleaf, để đưa vào báo cáo mà không bị gõ nhầm số hoặc lệch hàng cột. | Sinh viên làm thực nghiệm Toán-Tin, GVHD đọc báo cáo | 2–3 đợt chạy thực nghiệm/tuần, mỗi lần copy tay và căn chỉnh cú pháp `\multicolumn`, `\textbf` trong LaTeX mất 30–40 phút; từng bị phát hiện 2 con số trong bảng lệch với biểu đồ khi báo cáo giữa kỳ. |
| 5 | Tốn thời gian | Khi nhận bộ dữ liệu mới từ mentor thực tập hoặc đề bài project môn Thống kê/Học máy, tôi muốn phát hiện sớm các cột bị lệch định dạng, giá trị ngoại lai (outlier) và sai lệch tên biến giữa các bảng, để đưa dữ liệu vào mô hình huấn luyện ngay trong buổi làm việc mà không phải chạy lại. | Sinh viên thực tập Data/AI, nhóm project môn học (4 thành viên) | 2 lần/tuần khi cập nhật dữ liệu, mất 45–60 phút/lần kiểm tra thủ công; tuần trước cả nhóm mất 3 giờ huấn luyện lại mô hình vì 1 cột tỷ lệ bị lưu lẫn dạng chuỗi và số thập phân (lưu trong Git commit log). |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi viết phần Tổng quan nghiên cứu (Related Work) cho khóa luận từ 25–30 bài báo đã tải về, tôi muốn đối chiếu được các bài theo bài toán, giả thiết toán học (như tính lồi, tính trơn), bộ dữ liệu và hạn chế của từng phương pháp, để chỉ ra khoảng trống nghiên cứu (research gap) có căn cứ xác đáng. | Sinh viên làm KLTN, các bạn cùng lab nghiên cứu (5 người) | Đã lưu 28 file PDF trong Zotero nhưng cuối tuần trước mất hơn 4 giờ mở lại từng bài để tìm xem những bài nào dùng giả thiết hàm lồi chặt (strongly convex), do ghi chú cũ nằm rải rác ở Notion, tên file và sổ tay. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi ghép phần code thuật toán và phần chứng minh lý thuyết của 4 thành viên nhóm đồ án vào tối trước hạn nộp, tôi muốn đối chiếu nhanh quy ước tên biến, kích thước ma trận (dimension) và các thống nhất cũ trong nhóm chat, để tích hợp các module không bị lỗi xung đột. | Cả nhóm đồ án 4 người, nhóm trưởng phụ trách ghép bài | Mỗi đợt ghép bài (1–2 lần/tuần) mất 35–45 phút lội lại hơn 200 tin nhắn Zalo/Discord và comment Google Docs; tuần trước mất 1,5 giờ debug lỗi nhân ma trận vì 2 thành viên quy ước chiều vector ngược nhau. |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi đọc 5–7 tin tuyển dụng (JD) các vị trí Data Scientist, AI Engineer và Quantitative Researcher mỗi tuần, tôi muốn đối chiếu nhanh yêu cầu từng JD với các đồ án Toán-Tin và kỹ năng mình đã có, để chọn đúng project và số liệu nổi bật đưa vào CV trước khi nộp đơn. | Sinh viên năm cuối đang tìm việc/thực tập (15–20 bạn cùng lớp) | Ứng tuyển 4–5 vị trí/tuần, mất 40–50 phút/JD để đọc kỹ yêu cầu và sửa mô tả project trong CV LaTeX; hỏi nhanh 5 bạn cùng lớp đều dùng 1 bản CV chung vì ngại chỉnh sửa nên tỷ lệ phản hồi thấp (2/12 đơn). |
| 9 | Pain từ người khác | Khi GVHD hoặc mentor thực tập kiểm tra kết quả chạy mô hình hàng tuần của tôi, họ muốn biết ngay bảng kết quả đó được sinh ra từ phiên bản code nào, tập dữ liệu nào và thay đổi gì so với tuần trước, để đưa ra nhận xét hướng đi tiếp theo ngay trong buổi họp mà không phải hỏi lại. | GVHD, Mentor thực tập, Sinh viên báo cáo | Trong 4 buổi họp lab gần nhất, mất 15–20 phút đầu mỗi buổi (trên tổng 45 phút họp) chỉ để trả lời các câu hỏi lặp lại của thầy như "Bảng này đã lọc outlier chưa?" hay "So với tuần trước chỉ số tăng hay giảm?" (ghi nhận từ biên bản họp lab). |
| 10 | Pain từ người khác | Khi sinh viên khóa dưới (trong lớp tôi làm trợ giảng hoặc thành viên mới vào lab) bắt đầu cài đặt môi trường và chạy bài tập lớn, họ muốn tra cứu được ngay cách xử lý các lỗi cấu hình phổ biến và quy định nộp bài, để không bị kẹt hàng giờ chờ người trả lời. | Sinh viên khóa dưới (lớp 45 SV), Trợ giảng (TA) / đàn anh năm cuối | Mỗi đợt giao bài tập lớn (2 tuần/lần), nhận được 12–15 tin nhắn riêng và câu hỏi trên Discord hỏi lặp lại đúng 3–4 vấn đề (lệch bản CUDA/PyTorch, xin academic license Gurobi, sai cấu trúc thư mục nộp), mất ~10 phút/lần giải thích lại. |

**AI để gợi ý thêm:**

- **Ý giữ lại:** Ý **#8** (đối chiếu JD tuyển dụng với các đồ án Toán-Tin để chỉnh CV) và **#10** (pain từ sinh viên khóa dưới hỏi lặp lại lỗi cài đặt môi trường/academic license) — sau khi tự scan 8 vấn đề xoay quanh khóa luận và đồ án, dùng prompt theo 4 lăng kính giúp nhận ra thêm bối cảnh ứng tuyển cuối khóa và công việc hỗ trợ lab có số liệu đếm được từ tin nhắn Discord/Zalo.
- **Ý bỏ đi:**
  - *"Xây dựng trợ lý AI tự động giải và chứng minh các bài toán tối ưu lồi phức tạp"* — bỏ vì gài sẵn giải pháp ("trợ lý AI") vào vấn đề, phạm vi quá rộng và độ rủi ro sai số toán học rất cao, không có quy trình từng bước cố định để đo bottleneck trong phạm vi 1 buổi lab.
  - *"Hệ thống tự động viết toàn bộ khóa luận tốt nghiệp từ code"* — bỏ vì vi phạm đạo đức học thuật và không phản ánh đúng pain thật (pain thật nằm ở khâu tổng hợp bảng biểu/tài liệu và đối chiếu thực nghiệm chứ không phải giao trắng việc viết khóa luận).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp & viết báo cáo tiến độ thực nghiệm khóa luận hằng tuần (#1) | Lặp lại cố định mỗi tuần, quy trình 7 bước rất rõ, có baseline thời gian thật (70 phút/tuần) và giải quyết luôn pain hỏi lại ngữ cảnh của GVHD; dễ so sánh 4 mức No AI / Rule / Workflow / Agent | Đo chất lượng "bản phân tích nguyên nhân mô hình tăng/giảm" như thế nào ngoài việc giảm thời gian? |
| 2 | Đối chiếu giả thiết toán học & kết quả giữa các bài báo để viết Related Work (#6) | Pain rất nặng với SV Toán-Tin làm KLTN, mất hàng giờ mở lại 25–30 file PDF; bước nghẽn (trích xuất điều kiện định lý & hạn chế) rất cụ thể | AI có dễ đọc sai ký hiệu toán học phức tạp (như điều kiện Lipschitz hay hàm lồi chặt) trong PDF hai cột không? |
| 3 | Kiểm tra & chuẩn hóa tài liệu tham khảo BibTeX trên Overleaf theo chuẩn IEEE (#2) | Tần suất lặp lại cao mỗi khi viết báo cáo/KLTN, đầu vào/đầu ra cực kỳ tường minh (`.bib` file), vừa sức kiểm chứng ngay trong 1 buổi lab | Liệu chỉ dùng Rule (script Python + Zotero Better BibTeX) đã giải quyết được 85–90% mà không cần tới AI chưa? |

### Problem Card #1 — Báo cáo tiến độ thực nghiệm khóa luận hằng tuần (Problem #1)

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến tối Chủ Nhật trước buổi họp khóa luận sáng thứ Hai, tôi muốn gom đầy đủ kết quả chạy thực nghiệm mô hình, bộ tham số đã thử và các vướng mắc trong tuần về một chỗ, để gửi báo cáo tiến độ cho GVHD trước 22h mà không bị sót số liệu hay phải giải thích lại ngữ cảnh. |
| Actor | Sinh viên năm cuối ngành Toán-Tin ứng dụng đang làm khóa luận tốt nghiệp (cùng 4 bạn trong lab và GVHD đọc báo cáo). |
| Thời điểm / bối cảnh | Tối Chủ Nhật hằng tuần (khoảng 20h–22h), sau khi chạy xong các đợt thực nghiệm trong tuần và trước buổi họp lab sáng thứ Hai lúc 8h30. |
| Quy trình hiện tại (3–7 bước) | 1. Mở lại các file Jupyter Notebook / terminal log trong tuần để tìm các lần chạy (10') · 2. Đối chiếu `git log` để nhớ ứng với kết quả đó đã sửa hàm loss hay siêu tham số gì (10') · 3. Gom các chỉ số (RMSE, Accuracy, thời gian hội tụ) vào bảng nháp (10') · 4. Xem lại ghi chú rời rạc trên Notion/sổ tay về các lỗi phát sinh (10') · 5. Viết phần nhận định: vì sao mô hình cải thiện/suy giảm, tuần tới thử hướng nào (20') · 6. Format lại email/Markdown kèm ảnh biểu đồ (5') · 7. Kiểm tra và gửi cho GVHD (5'). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5 — Viết phần nhận định & giải thích nguyên nhân thay đổi kết quả thực nghiệm (mất ~20 phút, cộng với 20 phút ở bước 1–2 do phải lục tìm ngữ cảnh rời rạc). |
| Impact (nếu không giải thì sao) | Tốn ~70 phút/tuần/sinh viên (nhóm 5 SV khóa luận mất ~350 phút/tuần); 3/8 tuần gần nhất gửi trễ sau 23h; vào buổi họp sáng thứ Hai mất thêm 15–20 phút đầu giờ để GVHD hỏi lại "bảng này chạy trên tập dữ liệu nào, thay đổi gì so với tuần trước?". |
| Success metric (baseline → target) | (1) Thời gian làm báo cáo giảm từ trung bình 70 phút/tuần xuống dưới 25 phút/tuần; (2) Số câu hỏi xác nhận lại ngữ cảnh dữ liệu/tham số của GVHD đầu buổi họp giảm từ 3–4 câu xuống tối đa 1 câu. |
| Phương án không dùng AI | Tạo template báo cáo cố định trên Notion/Markdown + quy định đặt tên file log theo chuẩn `YYYYMMDD_model_dataset_param.csv` ngay khi chạy code (giúp giảm thời gian tìm kiếm ở bước 1–3, nhưng vẫn phải tự viết phần nhận định ở bước 5). |
| Giả thuyết về AI (nếu có) | Dùng script (Rule) gom tự động bảng CSV log + `git diff` tóm tắt thay đổi code trong tuần, sau đó đưa vào LLM (Workflow) để soạn bản nháp phần nhận định so sánh với tuần trước; sinh viên kiểm tra lại độ chính xác toán học/thực nghiệm trước khi gửi. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 70 phút/tuần (7 bước thủ công)

[1 Lục tìm kết quả trong Notebook/CSV: 10'] → [2 Đọc git log tìm tham số & code đã sửa: 10']
→ [3 Gom chỉ số vào bảng so sánh: 10'] → [4 Đọc lại note lỗi phát sinh: 10']
→ [5 Viết nhận định nguyên nhân tăng/giảm & hướng tuần tới: 20'] ← BOTTLENECK
→ [6 Format báo cáo + chèn biểu đồ: 5'] → [7 Rà soát & gửi email GVHD: 5']
```

### Problem Card #2 — Đối chiếu giả thiết toán học & kết quả giữa các bài báo để viết Related Work (Problem #6)

| Trường | Nội dung |
|---|---|
| Job Story | Khi viết phần Tổng quan nghiên cứu (Related Work) cho khóa luận từ 25–30 bài báo đã tải về, tôi muốn đối chiếu được các bài theo bài toán, giả thiết toán học (như tính lồi chặt, tính trơn Lipschitz), bộ dữ liệu và hạn chế của từng phương pháp, để chỉ ra khoảng trống nghiên cứu (research gap) có căn cứ xác đáng. |
| Actor | Sinh viên năm cuối Toán-Tin ứng dụng đang viết Chương 1–2 khóa luận tốt nghiệp hoặc chuẩn bị seminar nhóm nghiên cứu. |
| Thời điểm / bối cảnh | Giai đoạn viết đề cương chi tiết và Chương Tổng quan của khóa luận (hoặc mỗi đợt tổng hợp 10–15 bài báo theo chủ đề mới cho nhóm lab). |
| Quy trình hiện tại (3–7 bước) | 1. Mở thư mục Zotero gồm 25–30 file PDF đã lưu (5') · 2. Mở lại từng file PDF, tìm đọc phần Problem Formulation và Assumptions (90') · 3. Tra cứu phần Theorem/Convergence Rate để xem tốc độ hội tụ và điều kiện đi kèm (45') · 4. Đọc phần Experiments & Conclusion để tìm bộ dữ liệu và hạn chế (30') · 5. Điền tay từng dòng vào bảng tổng hợp trên Notion/Excel (30') · 6. Nhóm các bài cùng giả thiết để viết đoạn văn nhận xét Research Gap (40'). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 3 — Mở lại từng PDF để dò tìm đúng giả thiết toán học và tốc độ hội tụ (mất ~135 phút/đợt tổng hợp ~15–20 bài, vì mỗi bài ký hiệu một kiểu). |
| Impact (nếu không giải thì sao) | Mất ~4 giờ (240 phút) cho mỗi đợt tổng hợp; dễ bỏ sót điều kiện quan trọng của định lý (ví dụ nhầm giữa hàm lồi thường và lồi chặt $\mu$-strongly convex) dẫn đến nhận định sai research gap khi GVHD phản biện. |
| Success metric (baseline → target) | Thời gian tổng hợp và lập bảng so sánh cho 15 bài báo giảm từ 240 phút xuống dưới 75 phút; 100% giả thiết toán học trong bảng có trích dẫn đúng số trang/định lý trong PDF gốc. |
| Phương án không dùng AI | Thiết lập form ghi chú cố định 6 trường (Bài toán, Giả thiết hàm, Thuật toán, Tốc độ hội tụ, Dataset, Hạn chế) trong Zotero/Notion và bắt buộc điền ngay lúc vừa đọc xong từng bài lần đầu tiên. |
| Giả thuyết về AI (nếu có) | Dùng Workflow trích xuất văn bản/LaTeX từ PDF (qua công cụ đọc PDF khoa học) và yêu cầu LLM điền nháp bảng 6 trường kèm trích dẫn vị trí đoạn văn gốc (Section/Theorem số mấy); sinh viên kiểm tra lại các công thức trước khi viết nhận xét. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 240 phút/đợt tổng hợp (~15–20 bài báo)

[1 Lọc danh sách PDF trong Zotero: 5']
→ [2 Mở từng PDF dò tìm Problem Formulation & Assumptions: 90'] ← BOTTLENECK (1)
→ [3 Dò đọc Theorem & tốc độ hội tụ: 45']                       ← BOTTLENECK (2)
→ [4 Tìm Dataset & hạn chế ở phần cuối bài: 30']
→ [5 Nhập tay vào bảng so sánh Notion/Excel: 30']
→ [6 Phân nhóm & viết đoạn văn Research Gap: 40']
```

### Problem Card #3 — Kiểm tra & chuẩn hóa tài liệu tham khảo BibTeX trên Overleaf (Problem #2)

| Trường | Nội dung |
|---|---|
| Job Story | Khi hoàn thiện từng chương khóa luận trên Overleaf mỗi cuối tuần, tôi muốn biết các mục tài liệu tham khảo mới thêm đã đủ trường thông tin (tác giả, năm, tên hội nghị/tạp chí, chuẩn viết tắt) theo format IEEE hay chưa, để không bị lỗi hiển thị hoặc phải dò sửa thủ công từng dòng trước khi nộp bản nháp. |
| Actor | Sinh viên năm cuối viết khóa luận tốt nghiệp / bài báo khoa học bằng LaTeX trên Overleaf. |
| Thời điểm / bối cảnh | Cuối mỗi tuần hoặc trước mỗi đợt xuất file PDF nộp bản nháp từng chương cho GVHD. |
| Quy trình hiện tại (3–7 bước) | 1. Compile file PDF trên Overleaf và kéo xuống mục References cuối bài (2') · 2. Đọc dò bằng mắt từng mục trích dẫn trong PDF để phát hiện bài bị thiếu năm, thiếu tên tạp chí, lỗi viết hoa tên riêng (như `{B}ayesian`, `{KKT}`) hoặc còn dính bản `arXiv preprint` dù đã xuất bản chính thức (10') · 3. Mở Google Scholar tìm lại từng bài bị thiếu/lỗi để lấy bản BibTeX đầy đủ (10') · 4. Copy đè vào file `references.bib` và sửa tay tên key/format cho thống nhất (5') · 5. Compile lại và kiểm tra lần cuối (3'). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & 3 — Dò lỗi bằng mắt trên PDF và lên Google Scholar tìm lại bản xuất bản chính thức thay cho bản arXiv/thiếu trường (mất ~20 phút/lần kiểm tra). |
| Impact (nếu không giải thì sao) | Mất 30 phút/tuần; dễ sót lỗi trình bày làm giảm tính chuyên nghiệp của khóa luận (bản nháp Chương 2 từng bị GVHD đánh dấu 8 lỗi trích dẫn). |
| Success metric (baseline → target) | Thời gian rà soát và chuẩn hóa file `.bib` (60+ mục) giảm từ 30 phút xuống dưới 5 phút/lần; 0 lỗi thiếu trường bắt buộc (`author`, `title`, `journal`/`booktitle`, `year`) khi xuất PDF. |
| Phương án không dùng AI | Dùng extension Zotero Better BibTeX đồng bộ thẳng với Overleaf kết hợp công cụ kiểm tra cú pháp tĩnh như `bibtool` hoặc `biber --validate-datamodel`. |
| Giả thuyết về AI (nếu có) | Thực chất 80% bài toán giải được bằng **Rule** (script Python bắt lỗi thiếu trường, tự bọc ngoặc nhọn `{}` cho từ viết hoa và gọi API CrossRef/DBLP để cập nhật bài `arXiv` sang bản hội nghị chính thức); chỉ cần AI nếu muốn chuẩn hóa các ghi chú tự do không đúng cấu trúc. |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 30 phút/lần kiểm tra (~60 mục trích dẫn)

[1 Compile Overleaf & mở trang References: 2']
→ [2 Đọc dò bằng mắt tìm mục thiếu trường / lỗi viết hoa / bản arXiv cũ: 10'] ← BOTTLENECK (1)
→ [3 Lên Google Scholar tra lại từng bài bị lỗi để lấy BibTeX mới: 10']       ← BOTTLENECK (2)
→ [4 Sửa tay key & cú pháp trong references.bib: 5']
→ [5 Compile lại & kiểm tra PDF: 3']
```


### Card muốn pitch nhất

- **Card số:** Card #1 — Báo cáo tiến độ thực nghiệm khóa luận hằng tuần (Problem #1).
- **Vì sao:** Đây là vấn đề xảy ra đều đặn mỗi tuần với hầu hết sinh viên năm cuối ngành Toán-Tin/CNTT làm khóa luận hoặc nghiên cứu thực nghiệm; nó kết nối cả pain của bản thân sinh viên (mất 70 phút gom log rời rạc và viết nhận định tối Chủ Nhật) lẫn pain của người khác (GVHD mất 15–20 phút đầu giờ họp để hỏi lại ngữ cảnh dữ liệu và tham số). Hơn nữa, bài toán này tách bạch rất rõ phần việc của **Rule** (gom số liệu CSV + `git diff`) và phần việc của **AI trong Workflow** (soạn nháp nhận định so sánh tuần này với tuần trước).
- **Câu hỏi muốn nhóm phản biện:**
  1. Bottleneck thật sự nằm ở bước "viết nhận định (20 phút)" hay nằm ở thói quen "không ghi log có cấu trúc ngay lúc chạy mô hình khiến tối Chủ Nhật phải lục lại (20 phút)"?
  2. Nếu chỉ áp dụng template báo cáo cố định + script tự động gom bảng CSV (No AI + Rule) thì đã giải quyết được bao nhiêu phần trăm nỗi đau của cả sinh viên và GVHD?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| 1. **Bottleneck bị pha tạp:** Bạn nói bước 5 (viết nhận định, 20') là bottleneck, nhưng bước 1 + 2 (lục tìm Notebook và đọc lại `git log`) cũng ngốn đúng 20'. Nếu không nhớ mình đã chạy gì thì lấy gì viết nhận định? | Đồng ý | Ghi rõ trong Card #1: bước 1–2 là nguyên nhân gốc về dữ liệu đầu vào (giải bằng Rule/quy ước đặt tên file log), còn bước 5 là bottleneck về tổng hợp ngôn ngữ (giải bằng Workflow AI soạn nháp từ bảng dữ liệu đã gom). |
| 2. **Metric ban đầu chỉ đo thời gian:** Giảm từ 70 phút xuống 25 phút nhưng nếu AI viết nhận định hời hợt hoặc suy diễn sai nguyên nhân toán học khiến GVHD phải hỏi lại nhiều hơn thì báo cáo đó thất bại. | Đồng ý | Bổ sung metric thứ 2 về chất lượng vào `Success metric`: số câu hỏi xác nhận lại ngữ cảnh dữ liệu/tham số của GVHD ở đầu buổi họp giảm từ 3–4 câu xuống tối đa 1 câu. |
| 3. **Nhảy sang AI ở Card #3 quá sớm:** Với Card #3 (chuẩn hóa BibTeX), các trường thông tin và cú pháp hoàn toàn cố định; dùng LLM để sửa file `.bib` vừa chậm vừa có nguy cơ AI tự bịa số trang hoặc năm xuất bản. | Đồng ý | Đổi cảm nhận nhanh của Card #3 từ `Workflow` sang `Rule` (dùng script kiểm tra trường bắt buộc + truy vấn API CrossRef/DBLP chính thức thay vì dùng LLM). |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Mở rộng danh sách problem theo 4 lăng kính cho vai trò SV năm cuối Toán-Tin sau khi đã tự liệt kê các việc làm khóa luận hằng tuần | Gợi ý thêm góc nhìn từ người khác (#9, #10) và bối cảnh rải CV cuối khóa (#8); giúp rà lại cấu trúc câu "Khi..., tôi muốn..., để..." không bị lẫn giải pháp | Ban đầu gợi ý các ý quá rộng hoặc solution-first như "AI giải bài tập Giải tích số" hay "Chatbot viết khóa luận", thiếu con số đo lường cụ thể | Loại bỏ các ý mang tính "trợ lý toàn năng"; tự điền lại số phút thực tế, tần suất/tuần và bằng chứng thật từ lịch sử email GVHD, Git log, Overleaf và tin nhắn Discord của mình |
| CP2 Problem Card | Đóng vai Product Manager hoài nghi để phản biện 3 Problem Cards theo 6 câu hỏi trong worksheet | Chỉ ra rất trúng việc Bottleneck ở Card #1 thực chất gồm cả khâu lục tìm log (20') lẫn viết nhận định (20'), và cảnh báo Card #3 (BibTeX) chỉ cần Rule chứ không nên lạm dụng AI | Khi gợi ý giả thuyết AI cho Card #1, AI đề xuất làm Agent tự động đọc Notebook và tự gửi email báo cáo cho GVHD | Bác bỏ ý tưởng Agent tự gửi báo cáo; chốt mức can thiệp là Workflow (Rule gom log CSV/Git → AI nháp nhận định → Sinh viên bắt buộc kiểm tra công thức và số liệu trước khi gửi) và chuyển Card #3 về mức Rule |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
