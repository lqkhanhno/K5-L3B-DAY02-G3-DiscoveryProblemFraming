# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Đoàn Đăng Khoa | Khi Bộ/Sở ban hành công văn, thông tư mới, tôi muốn biết nhanh điểm nào thay đổi ảnh hưởng đến môn và khối mình dạy, để kịp điều chỉnh ma trận đề và kế hoạch bài dạy. | Giáo viên bộ môn (người áp dụng); tổ trưởng chuyên môn (người phổ biến, giải đáp, duyệt) | Bước 3-4 (lọc phần liên quan, đối chiếu với cái cũ): ước tính ~30-60 phút/văn bản. Bước 5 (chờ họp tổ) gây độ trễ tính bằng ngày. | Tại sao lại cần 1 người duyệt sau khi đã sử dụng AI, có phải tự xây ra 1 nghề khác cho giáo viên không? |
| 2 | Đoàn Đăng Khoa | Khi đã có ma trận đề và cần nhiều mã đề tương đương, tôi muốn các mã đúng ma trận, độ khó tương đương, không trùng hay lộ câu, để không mất nhiều buổi soạn đề và rà soát. | Giáo viên bộ môn (người ra đề); tổ trưởng chuyên môn (người duyệt); học sinh (làm các mã đề khác nhau) | Bước 2 (soạn câu tương đương cho nhiều mã) và bước 5 (rà soát chéo giữa các mã). Ước tính nhiều giờ cho mỗi bộ đề. | Tại sao không thay đổi mã đề đơn giản chỉ thay các số trong đề đã soạn ra mà phải sử dụng LLM để tạo đề (Khánh) |
| 3 | Đoàn Đăng Khoa | Khi phải viết nhận xét cho từng học sinh theo các tiêu chí tôi đã đặt, tôi muốn không phải nghĩ lại câu chữ từ đầu cho mỗi em mà vẫn đúng mức độ của em đó, để giảm thời gian và giữ nhất quán giữa các học sinh. | Giáo viên bộ môn / GVCN; học sinh, phụ huynh. | Bước 3–4: quyết định mức độ và suy nghĩ lời văn để viết nhận xét. Ước tính ~3–5 phút/em, khoảng ~2–3 giờ/lớp. | Nếu như dùng tool tự động thì có thể giải quyết được vấn đề này không (Khoa) |
| 4 | Lê Quốc Khánh | Khi nhóm đang chọn dự án và phân công công việc, tôi muốn biết chính xác năng lực thực tế của từng thành viên, để giao đúng người đúng việc và tránh giao việc vượt quá khả năng hiện tại. | Trưởng nhóm / người phân công (chịu trách nhiệm chính), toàn bộ thành viên nhóm (bị ảnh hưởng) | Bước 3: Hỏi thêm / đoán năng lực → mất 20-40 phút, thông tin thiếu khách quan | Liệu có thực sự cần AI không, khi leader phải nắm được tình hình của nhóm và chọn đề tài phù hợp (Khoa) |
| 5 | Lê Quốc Khánh | Khi mỗi ngày phải kiểm tra nhiều nhóm lớp, nhóm dự án và các deadline, tôi muốn nhìn nhanh những việc quan trọng trong ngày, để không bỏ sót hoặc nộp muộn. | Tôi (sinh viên) | Bước 3: Check lại nhiều lần vì thông tin phân tán → mất 10-15 phút | Liệu có khả thi và cần thiết không, chi phí vận hành có quá lớn so với 1 việc có thể tự giác làm là xong không (Minh) |
| 6 | Lê Quốc Khánh | Khi phải tìm tài liệu học tập từ nhiều nguồn trong khóa học AI, tôi muốn gom nhanh những phần quan trọng, để học tập hiệu quả hơn và không lãng phí thời gian. | Tôi (sinh viên) | Bước 3: Đọc lướt + lọc thông tin quan trọng từ nhiều nguồn → mất 30-50 phút | Có thể sử dụng notebook LLM để tổng hợp luôn không (Huy) |
| 7 | Nguyễn Quang Huy | Khi đến tối Chủ Nhật trước buổi họp khóa luận sáng thứ Hai, tôi muốn gom đầy đủ kết quả chạy thực nghiệm mô hình, bộ tham số đã thử và các vướng mắc trong tuần về một chỗ, để gửi báo cáo tiến độ cho GVHD trước 22h mà không bị sót số liệu hay phải giải thích lại ngữ cảnh. | Sinh viên năm cuối ngành Toán-Tin ứng dụng đang làm khóa luận tốt nghiệp (cùng 4 bạn trong lab và GVHD đọc báo cáo). | Bước 5 — Viết phần nhận định & giải thích nguyên nhân thay đổi kết quả thực nghiệm (mất ~20 phút, cộng với 20 phút ở bước 1-2 do phải lục tìm ngữ cảnh rời rạc). | Sử dụng WanDB có thể ghi lại log rồi thì có cần thiết gom lại kết quả để chạy mô hình này không (Khoa) |
| 8 | Nguyễn Quang Huy | Khi viết phần Tổng quan nghiên cứu (Related Work) cho khóa luận từ 25-30 bài báo đã tải về, tôi muốn đối chiếu được các bài theo bài toán, giả thiết toán học (như tính lồi chặt, tính trơn Lipschitz), bộ dữ liệu và hạn chế của từng phương pháp, để chỉ ra khoảng trống nghiên cứu (research gap) có căn cứ xác đáng. | Sinh viên năm cuối Toán-Tin ứng dụng đang viết Chương 1-2 khóa luận tốt nghiệp hoặc chuẩn bị seminar nhóm nghiên cứu. | Bước 2 & 3 — Mở lại từng PDF để dò tìm đúng giả thiết toán học và tốc độ hội tụ (mất ~135 phút/đợt tổng hợp ~15-20 bài, vì mỗi bài ký hiệu một kiểu). | Liệu có thể sử dụng các LLM thông thường để thực hiện research này không (Minh) |
| 9 | Nguyễn Quang Huy | Khi hoàn thiện từng chương khóa luận trên Overleaf mỗi cuối tuần, tôi muốn biết các mục tài liệu tham khảo mới thêm đã đủ trường thông tin (tác giả, năm, tên hội nghị/tạp chí, chuẩn viết tắt) theo format IEEE hay chưa, để không bị lỗi hiển thị hoặc phải dò sửa thủ công từng dòng trước khi nộp bản nháp. | Sinh viên năm cuối viết khóa luận tốt nghiệp / bài báo khoa học bằng LaTeX trên Overleaf. | Bước 2 & 3 — Dò lỗi bằng mắt trên PDF và lên Google Scholar tìm lại bản xuất bản chính thức thay cho bản arXiv/thiếu trường (mất ~20 phút/lần kiểm tra). | Sử dụng tool như Zotero liệu có tối ưu hơn luôn không, vì Zotero đã chỉnh lại format thống nhất theo kiểu mình đã chọn rồi (Khoa) |
| 10 | Lã Thái Minh | Khi đến cuối tháng nhận bill trọ và tiền ăn chung, tôi muốn đối soát nhanh ai đã ứng trước khoản nào và chia đều tiền, để đóng tiền đúng hạn cho chủ trọ. | 2 roommate | Bước 2 & 3: Tìm kiếm và phân loại bill chung/riêng từ nhiều nguồn tin nhắn, ảnh chụp, app ngân hàng (mất 50 phút do dữ liệu nằm rải rác, ảnh mờ, dễ quên). | Liệu có thực sự cần tool để làm việc này không (Khánh) |
| 11 | Lã Thái Minh | Khi cả hai đứa đều bận học và làm việc, tôi muốn phân chia rõ người làm từng việc dọn dẹp (đổ rác, rửa bát), để phòng sạch sẽ mà không phải nhắc nhở, tị nạnh nhau. | 2 roommate | Bước 2 & 3: Bàn bạc, nghĩ món và thống nhất ý kiến khi cả hai đều mệt mỏi (mất 20-25 phút). | Làm chung với nhau thì có nhanh hơn không (Huy) |
| 12 | Lã Thái Minh | Khi đến giờ nấu bữa tối, tôi muốn biết nhanh hôm nay nấu món gì từ đồ còn trong tủ lạnh, để không mất công bàn cãi và tránh đồ ăn bị hỏng. | 2 bạn cùng phòng (hoặc người phụ trách nấu ăn ngày hôm đó). | Bước 2 & 4: Đùn đẩy, trì hoãn và tranh cãi xem lượt dọn/đổ rác thuộc về ai (mất 15–20 phút tranh luận và gây khó chịu cả ngày). | Note lại đồ ăn đã cất thời gian nào rồi lấy ra dùng rồi thì đã giải quyết được vấn đề chưa (Huy) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | #1, #6, #8 | Phải đọc nhiều tài liệu dài, rồi lọc ra vài đoạn liên quan đến việc mình đang làm và đối chiếu với cái đã có. |
| B | #7, #10 | Thông tin nằm rải rác ở nhiều chỗ, mất công lục lại và gom về một bản trước khi dùng được (để báo cáo hoặc đối soát). |
| C | #4, #5, #11 | Chia việc và nhớ việc đang dựa vào đoán, nhắc nhau hoặc check đi check lại, nên dễ giao sai, quên hoặc tị nạnh. |
| D | #2, #3, #9 | Đã có sẵn chuẩn (ma trận, tiêu chí, format), nhưng vẫn phải viết hoặc kiểm tra thủ công từng bản lặp lại. |
| Để riêng | #12 | Chốt một quyết định nhỏ hằng ngày (nấu gì) giữa hai người. Không hợp cluster nào nên không bỏ vào cluster. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm ≥ 50% số phút mỗi tuần mà người dạy và người học trong nhóm dành cho việc
         tìm, gom và rà soát thông tin lặp lại, trong khi số lỗi hoặc sót bị phát hiện
         sau đó không tăng.
         (Đơn vị đo: phút/tuần/người. Mốc ban đầu lấy từ các ước tính trong bảng pitch,
          sẽ đo lại thực tế cho candidate được chọn.)
├── Opportunity A: Phải đọc lại cả văn bản hoặc cả bài báo chỉ để tìm vài đoạn liên quan,
│                  rồi tự đối chiếu với cái cũ.
├── Opportunity B: Thông tin nằm rải rác nhiều nơi nên mất thời gian lục và gom lại
│                  trước khi dùng được.
├── Opportunity C: Chia việc và nhớ hạn đang dựa vào đoán và nhắc nhau, nên dễ giao
│                  quá sức, quên hoặc cãi nhau.
└── Opportunity D: Cùng một chuẩn nhưng phải viết hoặc kiểm tra tay từng bản,
                   tốn công và dễ lệch giữa các bản.
```


Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ~~Chatbot tóm tắt công văn cho giáo viên~~ (có tên công cụ, người dùng đau ở chỗ phải lọc phần liên quan, không phải ở chỗ thiếu chatbot)
- ~~Tool tự sinh nhận xét cho học sinh~~ (đây là cách giải, pain thật là phải nghĩ lại câu chữ cho từng em)
- ~~Bảng nhắc deadline mỗi ngày~~ (đây là tính năng, pain thật là thông tin phân tán nên phải check nhiều lần)
- ~~Trợ lý AI chia việc cho thành viên~~ (có chữ AI, pain thật là leader chưa nắm rõ năng lực từng người)
- ~~Dùng LLM tạo mã đề~~ (đây là công cụ, pain thật là soạn và rà soát nhiều mã tương đương mất nhiều giờ)

### 2.4. Chấm điểm shortlist (1-5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 Theo dõi văn bản quy định mới | 5 | 5 | 3 | 4 | 4 | 4 | 4 | 29 |
| #8 Đối chiếu bài báo cho Related Work | 4 | 4 | 4 | 5 | 3 | 4 | 4 | 28 |
| #2 Nhiều mã đề tương đương | 4 | 3 | 2 | 3 | 2 | 3 | 3 | 20 |

**Candidate được chọn:** #1 (problem card #3 của Khoa), theo dõi và áp dụng văn bản quy định mới của Bộ/Sở.

**Vì sao chọn:** #1 có tổng cao nhất (29/35). Điểm cao nhất ở hai tiêu chí nền: Actor rõ (5) và Quy trình rõ (5), với hai vai cụ thể và 7 bước, bước nghẽn xác định rõ là bước 3-4 và bước 5. Impact đo được (4) vì có sẵn 3 chỉ số: thời gian từ lúc nhận văn bản đến lúc biết việc cần làm, số lần hỏi lại tổ trưởng, và số lỗi áp dụng sai khi duyệt đề. So sánh được 4 mức (4) vì đã mô tả được phương án không dùng AI: tóm tắt 1 trang theo mẫu cố định, tổ trưởng phân công luân phiên.

**Vì sao loại các candidate còn lại:**
- #8: số ~135 phút/đợt là số của một người, chưa kiểm chứng với người khác. Mỗi bài báo ký hiệu một kiểu nên có rủi ro trích sai giả thiết toán học, mà lỗi kiểu này khó phát hiện nếu không mở lại từng bài. Câu hỏi của Minh (dùng LLM thông thường có làm được việc này không) cũng chưa có câu trả lời rõ.
- #2: pain mới ở mức "nhiều giờ", chưa có số đo. Chưa có cách đo "độ khó tương đương" giữa các mã đề. Câu hỏi của Khánh (chỉ đổi số trong đề đã soạn) chưa bị bác bỏ, nên phương án rule-based chưa chắc thua LLM.
- #3, #6: #3 cùng cụm D với #2, chưa rõ cách đo "đúng mức độ của từng em". #6 cùng cluster A với #8, nguồn tài liệu của khóa học rộng và Huy đã hỏi về notebook LLM, chưa có lý do tách khỏi công cụ có sẵn.
- #4, #5, #10, #11, #12: thông tin đầu vào mang tính cá nhân hoặc chủ quan (năng lực thành viên, việc nhà, bữa ăn), việc nhỏ 10-50 phút, và các câu hỏi "có thực sự cần tool không" chưa có lời đáp rõ.
- #7, #9: #7 bị hỏi vì đã có công cụ ghi log thí nghiệm; #9 bị hỏi vì công cụ quản lý tài liệu tham khảo có thể làm được việc này. Cả hai chưa chứng minh được phần việc còn lại mà công cụ có sẵn không làm.

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1-5) | Đã có bằng chứng (1-5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4-6 giả định; xóa dòng thừa.*

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

**Tiêu chí đánh giá đầu ra của AI (3-5 tiêu chí):**

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
# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: G1
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Card #3 của Đoàn Đăng Khoa — giáo viên bộ môn cần xác định phần thay đổi trong văn bản Bộ/Sở liên quan đến môn, khối mình dạy để kịp cập nhật ma trận đề và kế hoạch bài dạy.
- Quyết định cuối: Go / Not Yet / No-Go
Go
---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
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
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

**Phản biện đã nhận từ nhóm khác:** ba câu hỏi dưới đây giúp kiểm tra lập luận về giải pháp. Đây **không phải** kết quả phỏng vấn giáo viên hoặc survey về hành vi đã xảy ra, nên chưa được tính là bằng chứng xác nhận pain.

| Câu hỏi phản biện | Cách nhóm trả lời ở mức giả thuyết | Cần kiểm chứng bằng gì? |
|---|---|---|
| Có cần dùng AI không? | Chưa thể kết luận. Thử trước quy trình không AI: một người trong tổ đọc văn bản, ghi một trang theo mẫu và gửi cả tổ. Chỉ cân nhắc AI nếu bước lọc điều khoản và so bản cũ vẫn tốn nhiều thời gian. | Hỏi giáo viên lần gần nhất họ mất bao lâu ở bước đọc/lọc/đối chiếu, và thử so thời gian với mẫu một trang. |
| Có phải tạo thêm bộ phận để kiểm tra tính đúng không? | Không đề xuất lập bộ phận mới. Giáo viên và tổ trưởng chuyên môn đang là người thống nhất cách hiểu; nếu có AI, họ kiểm điều/khoản gốc và duyệt trước khi phổ biến. | Hỏi tổ trưởng hiện nay ai kiểm và duyệt cách áp dụng văn bản, mất bao lâu, có phải chờ họp tổ không. |
| Đã có AI sẵn thì sao phải tạo thêm? | Bài lab chưa đặt mục tiêu xây AI mới. Cần thử công cụ sẵn có và cách làm thủ công trước; giá trị cần kiểm là lọc đúng môn/khối, chỉ đúng điều khoản, phát hiện thay đổi so với bản cũ và rút ngắn thời gian đến khi giáo viên biết việc cần làm. | Dùng cùng một cặp văn bản mới/cũ để so bản tóm tắt thủ công với công cụ sẵn có; đếm điều khoản đúng, bị bỏ sót, dẫn nguồn sai và thời gian giáo viên phải sửa. |

**Kiểm chứng với đúng actor:** phỏng vấn 2–3 giáo viên/tổ trưởng từng trực tiếp xử lý văn bản mới, hoặc survey 5–10 người có trải nghiệm đó. Hỏi về **lần gần nhất**: nhận văn bản qua đâu, tìm phần liên quan bằng cách nào, đối chiếu bản cũ ra sao, hỏi lại ai, mất bao lâu và cuối cùng đã sửa tài liệu gì. Ghi cả trường hợp không gặp pain hoặc chỉ cần mẫu tóm tắt chung. Chưa điền số người hay kết quả khi chưa có phản hồi thực tế.

Cách đã dùng với giáo viên/tổ trưởng: **chưa có dữ liệu để xác nhận**. Khi có khảo sát hoặc phỏng vấn, ghi ngày, cách hỏi, số phản hồi hợp lệ và link biểu mẫu/kết quả được phép chia sẻ tại đây.

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`). **Chưa thực hiện phỏng vấn người có trải nghiệm trực tiếp, nên chưa có snapshot để ghi.** Sau buổi phỏng vấn thật, thay bảng mẫu dưới đây bằng câu trả lời nguyên văn và tình huống cụ thể:

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
| Phản biện của nhóm khác | 3 câu hỏi | Chưa xác nhận pain của giáo viên | Chất vấn việc có cần AI, có cần thêm người kiểm và có cần xây công cụ mới; đây là phản biện giả thuyết giải pháp, không phải câu chuyện sử dụng đã xảy ra. |
| Phỏng vấn/survey giáo viên hoặc tổ trưởng chuyên môn | Chưa có dữ liệu | Chưa kết luận | Chưa kết luận |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** Chưa có kết quả kiểm chứng từ giáo viên để kết luận. Sau phản biện của nhóm khác, nhóm cần tách hai giả định: (1) giáo viên mất thời gian lọc/đối chiếu văn bản; (2) thời gian chờ tổ thống nhất cách hiểu. Nếu giả định (2) là bottleneck chính, ưu tiên sửa quy trình duyệt và phổ biến thay vì chỉ tăng tốc độ tóm tắt bằng AI.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Một người trong tổ viết tóm tắt một trang bằng Google Docs, tổ trưởng góp ý và phân công việc | [Google Docs: comments và action items](https://support.google.com/docs/answer/65129) | Bước 5–6: thống nhất cách hiểu và giao việc sau khi đọc văn bản | Không cần AI; dùng cùng một bản ghi chú, có thể góp ý và giao việc trong tài liệu | Người viết vẫn phải tự lọc/đối chiếu điều khoản; hiệu quả phụ thuộc thời gian tổ trưởng duyệt | Đây là phương án chuẩn để so với AI, không cần lập bộ phận kiểm tra mới. |
| Gemini Notebook với văn bản mới và cũ làm nguồn | [Google: chat với nguồn và trích dẫn](https://support.google.com/gemininotebook/answer/16179559) | Bước 3–4: hỏi phần liên quan đến môn/khối và điểm khác giữa hai nguồn | Cho phép hỏi trên tài liệu đã đưa vào và mở trích dẫn để kiểm lại ngữ cảnh | Trích dẫn không chứng minh đã tìm đủ mọi điều liên quan; bản scan và cách hiểu quy định vẫn cần người kiểm | Thử công cụ có sẵn để tạo **bản nháp có nguồn**, rồi kiểm từng điều/khoản với văn bản gốc. |
| Adobe Acrobat Compare Files / AI Assistant | [Adobe: so sánh hai PDF](https://helpx.adobe.com/acrobat/using/compare-documents.html), [Adobe: hỏi PDF có trích dẫn](https://helpx.adobe.com/acrobat/desktop/use-acrobat-ai/generative-ai-features/ai-get-answers.html) | Bước 3–4: phát hiện khác biệt giữa hai phiên bản PDF và hỏi nội dung trong tài liệu | Có báo cáo khác biệt; AI Assistant có liên kết về đoạn nguồn để kiểm | So sánh chữ không tự xác định môn/khối nào chịu ảnh hưởng. [Adobe lưu ý AI có thể trả lời hoặc dẫn nguồn sai](https://helpx.adobe.com/acrobat/desktop/use-acrobat-ai/understand-usage-policies/user-disclosures.html), nên phải tự kiểm lại. | Không cần tự xây công cụ so sánh PDF; đánh giá liệu công cụ sẵn có cộng bước tổ trưởng duyệt đã đủ. |

**Kết luận research sơ bộ:** các công cụ sẵn có đã hỗ trợ đọc, so sánh và dẫn về nguồn. Nhóm chưa có bằng chứng để đề xuất xây AI mới. Điểm cần thử trong lab là quy trình **văn bản gốc → bản nháp điểm thay đổi theo môn/khối → giáo viên/tổ trưởng kiểm nguồn → thông báo việc cần làm**, so với phương án tóm tắt thủ công. Đây là đánh giá từ tài liệu sản phẩm, **chưa phải kết quả thử nghiệm trên văn bản của nhóm**.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
[Văn bản mới: PDF / scan, qua email – Zalo – hệ thống trường]
   → (1) Nhận văn bản                               
   → (2) Đọc lướt / đọc toàn văn                   
   → (3) Lọc phần liên quan đến môn, khối mình dạy       ← bottleneck
   → (4) Đối chiếu với văn bản / cách làm cũ             ← bottleneck
   → (5) Hỏi tổ trưởng / chờ họp tổ thống nhất        
   → (6) Xác định việc cần làm                         
   → (7) Cập nhật ma trận đề / kế hoạch bài dạy    
Lặp lại (2)–(5) × số giáo viên trong tổ × số văn bản/học kỳ
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Giáo viên bộ môn; Tổ trưởng chuyên môn | Công văn, thông tư mới từ Bộ/Sở (file PDF hoặc bản scan) gửi qua email, hệ thống văn bản của trường hoặc nhóm Zalo | Giáo viên nhận và mở được file văn bản | ~5 phút / mỗi khi có văn bản mới (đầu năm học, đầu học kỳ, trước kỳ kiểm tra) | Handoff từ trường/tổ trưởng xuống giáo viên; tin nhắn Zalo dễ bị trôi |
| 2 | Giáo viên bộ môn | Toàn bộ văn bản mới (thường dài, nhiều trang, ngôn ngữ hành chính) | Nắm được chủ đề chung và bố cục của văn bản | ~15–20 phút/văn bản × mỗi giáo viên trong tổ | Mỗi giáo viên trong tổ đều phải tự đọc lại cùng một văn bản |
| 3 | Giáo viên bộ môn | Văn bản mới + thông tin môn học, khối lớp mình đang dạy | Các điều, khoản, mục liên quan trực tiếp đến môn và khối phụ trách | ~15–30 phút/văn bản | **Bottleneck:** Văn bản quy định chung cho nhiều cấp/môn; file scan không tìm kiếm nhanh được, dễ đọc sót |
| 4 | Giáo viên bộ môn | Các phần liên quan vừa lọc + văn bản quy định cũ / cách làm cũ (ma trận đề, kế hoạch bài dạy hiện hành) | Danh sách điểm thay đổi so với quy định/cách làm cũ | ~15–30 phút/văn bản (gộp bước 3–4 mất ~30–60 phút/văn bản) | **Bottleneck:** Văn bản mới thường chỉ ghi sửa đổi/bổ sung điều khoản nên phải tự lục lại văn bản cũ để đối chiếu thủ công |
| 5 | Giáo viên bộ môn; Tổ trưởng chuyên môn | Các điểm thay đổi còn mơ hồ hoặc hiểu khác nhau giữa các giáo viên | Cách hiểu thống nhất trong toàn tổ chuyên môn | ~15–30 phút trao đổi/họp (độ trễ chờ họp tổ tính bằng ngày: ~1–3 ngày) | Tổ phải họp riêng chỉ để "giải nghĩa" văn bản; gây chậm tiến độ áp dụng |
| 6 | Giáo viên bộ môn; Tổ trưởng chuyên môn | Nội dung thay đổi đã được thống nhất cách hiểu | Danh sách việc cần làm cụ thể (sửa ma trận đề, kế hoạch bài dạy, cách đánh giá) | ~10 phút/văn bản | Chuyển từ quy định hành chính sang đầu việc chuyên môn của từng giáo viên |
| 7 | Giáo viên bộ môn (người áp dụng); Tổ trưởng (người duyệt) | Danh sách việc cần làm + ma trận đề, kế hoạch bài dạy hiện tại | Ma trận đề, kế hoạch bài dạy đã cập nhật theo quy định mới | ~20–30 phút/lần cập nhật | Nếu bước 3–5 hiểu sai hoặc sót, tài liệu cập nhật sẽ sai cấu trúc mới và bị nhắc khi kiểm tra chuyên môn |

**Bottleneck chính:**
- **Bước 3–4 (Lọc phần liên quan đến môn/khối và đối chiếu với văn bản/cách làm cũ):** Tốn ước tính ~30–60 phút/văn bản cho mỗi giáo viên, lặp lại cho toàn bộ giáo viên trong tổ (`số giáo viên × số văn bản/học kỳ`) do văn bản dài, ngôn ngữ hành chính và phải tự đối chiếu thủ công với quy định cũ.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
[Văn bản mới (PDF/scan) + Văn bản quy định cũ liên quan]
   → (1) Trích xuất văn bản (OCR nếu là scan), tách điều/khoản và gắn thẻ môn/khối [~2 phút]       ← RULE
   → (2) Trích xuất điểm liên quan theo môn/khối + so sánh văn bản cũ              [~2 phút]       ← AI (LLM)
         (kèm trích dẫn số điều/khoản/trang gốc và gợi ý việc cần làm)
   → (3) Tổ trưởng kiểm tra đối chiếu nguồn gốc, chỉnh sửa và duyệt phổ biến       [~10–15 phút]   ← CON NGƯỜI (HITL)
   → (4) Giáo viên xem bản tóm tắt chuẩn của tổ (5') & cập nhật ma trận đề/bài dạy [~20–30 phút]   ← CON NGƯỜI

BOUNDARY (Ranh giới của AI):
- AI CHỈ tóm tắt điểm thay đổi, lọc theo môn/khối và gợi ý việc cần làm dựa trên văn bản đầu vào, bắt buộc trích dẫn rõ số điều/khoản/trang gốc cho từng ý.
- AI KHÔNG tự động gửi thông báo/hướng dẫn cho giáo viên khi chưa có Tổ trưởng chuyên môn duyệt (HITL), KHÔNG tự ý sửa trực tiếp vào file ma trận đề hay kế hoạch bài dạy của giáo viên, và KHÔNG suy diễn quy định ngoài văn bản gốc.

PHƯƠNG ÁN QUAY VỀ (Fallback khi AI sai hoặc bản scan quá mờ):
- Nếu AI đọc lỗi bản scan, trích dẫn sai điều/khoản hoặc tóm tắt lệch nội dung quá 30%: Tổ trưởng bỏ bản nháp của AI và quay về phương án không dùng AI — phân công luân phiên 1 giáo viên trong tổ đọc văn bản và điền mẫu tóm tắt 1 trang cố định (thay đổi gì – áp dụng cho môn/khối nào – từ khi nào – việc cần làm – điều/khoản gốc) vào sổ theo dõi văn bản dùng chung của tổ.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 7 bước (lặp lại bước 2–5 ở từng GV) | 4 bước (xử lý tập trung 1 lần cho cả tổ ở bước 1–3) | Loại bỏ việc mỗi giáo viên trong tổ phải tự đọc toàn văn và tự đối chiếu từ đầu |
| Tổng thời gian | ~65–115 phút/GV + độ trễ 1–3 ngày chờ họp tổ | ~15–20 phút (Tổ trưởng duyệt) + ~5 phút/GV đọc tóm tắt (trong 1 buổi) | Chưa tính ~20–30 phút GV tự sửa ma trận đề/kế hoạch bài dạy; đạt mục tiêu biết việc cần làm trong 1 buổi và giảm ≥ 50% số lần hỏi lại |
| Số bước thủ công | 7/7 bước | 2/4 bước | Bước 1 dùng Rule/OCR, Bước 2 dùng AI; Tổ trưởng vẫn duyệt (Bước 3) và GV cập nhật tài liệu (Bước 4) |
| Bottleneck | Bước 3–4 (lọc & đối chiếu: 30–60 phút/GV) | Bước 3 (Tổ trưởng kiểm tra đối chiếu bản nháp AI với điều/khoản gốc: ~10–15 phút) | Bottleneck chuyển thành bước kiểm soát chất lượng (HITL) của 1 người, giúp giải phóng thời gian cho cả tổ |
| Rủi ro mới | — | AI hiểu sai ngữ cảnh hành chính, thêm nội dung không có trong văn bản (hallucination), hoặc đọc lỗi chữ từ file PDF scan mờ | Kiểm soát bằng yêu cầu bắt buộc trích dẫn điều/khoản/trang gốc và Tổ trưởng chuyên môn kiểm tra lại trước khi ban hành cho tổ |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Giáo viên bộ môn (người trực tiếp áp dụng quy định mới vào ma trận đề, kế hoạch bài dạy) và Tổ trưởng chuyên môn (người phổ biến, giải đáp, duyệt chuyên môn trong tổ). |
| **Quy trình** | Khi Bộ/Sở ban hành công văn, thông tư mới (đầu năm học, đầu học kỳ, trước các kỳ kiểm tra): (1) Nhận văn bản qua email/Zalo/hệ thống trường → (2) Đọc lướt hoặc đọc toàn văn → (3) Tìm phần liên quan đến môn và khối mình dạy → (4) Đối chiếu với văn bản/cách làm cũ để thấy điểm khác → (5) Hỏi tổ trưởng/đồng nghiệp hoặc chờ họp tổ thống nhất cách hiểu → (6) Xác định việc cần làm → (7) Cập nhật ma trận đề và kế hoạch bài dạy. |
| **Bottleneck** | Bước 3–4 (lọc phần liên quan đến môn, khối mình dạy và đối chiếu với văn bản/cách làm cũ): tốn ước tính ~30–60 phút/văn bản cho mỗi giáo viên vì văn bản dài, ngôn ngữ hành chính, thường là file PDF/scan và chỉ dẫn chiếu sửa đổi, bổ sung điều khoản cũ. |
| **Impact** | Mỗi giáo viên trong tổ phải lặp lại việc đọc và đối chiếu cùng một văn bản (`~30–60 phút × số giáo viên trong tổ`); áp dụng chậm (trễ 1–3 ngày chờ họp tổ "giải nghĩa" văn bản) hoặc hiểu sai quy định mới khiến ma trận đề/kế hoạch bài dạy sai cấu trúc mới, bị tổ hoặc Ban giám hiệu nhắc nhở khi kiểm tra chuyên môn. |
| **Success Metric** (baseline → target, cách đo) | - **Thời gian từ lúc nhận văn bản đến lúc biết việc cần làm:** từ ~65–115 phút tự đọc/đối chiếu + trễ 1–3 ngày chờ họp tổ (baseline ước tính) → rút xuống hoàn thành **trong 1 buổi** (~15–20 phút tổ trưởng duyệt + ~5 phút/GV đọc bản tóm tắt). *Cách đo:* ghi nhận thời gian thực tế từ lúc nhận văn bản đến lúc chốt danh sách việc cần làm cho tổ trong 2–3 văn bản đợt pilot.<br>- **Số lần hỏi lại:** số lượt giáo viên phải hỏi lại tổ trưởng/đồng nghiệp cho mỗi văn bản giảm ≥ 50% so với đợt văn bản trước (*Cách đo:* đếm tin nhắn hỏi lại trong nhóm Zalo tổ).<br>- **Độ chính xác áp dụng:** số lỗi áp dụng sai quy định mới bị phát hiện khi duyệt đề/kế hoạch bài dạy → giảm về 0 (*Cách đo:* biên bản/góp ý duyệt chuyên môn của tổ trưởng). |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | - **AI không được làm gì:** AI không tự động ban hành hay gửi hướng dẫn cho giáo viên, không tự ý sửa trực tiếp vào file ma trận đề/kế hoạch bài dạy của giáo viên, và không suy diễn thêm quy định ngoài văn bản gốc.<br>- **Khi nào cần con người kiểm tra (HITL):** Mọi điểm thay đổi do AI trích xuất bắt buộc kèm số điều/khoản/trang gốc; **Tổ trưởng chuyên môn** phải kiểm tra đối chiếu với văn bản gốc và duyệt trước khi phổ biến cho giáo viên trong tổ. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- **Phản biện 1 (về phạm vi văn bản & Actor):** Không phải công văn nào của Bộ/Sở cũng dài và cần đối chiếu văn bản cũ (nhiều công văn hành chính ngắn hoặc chỉ thông báo lịch thì đọc 5 phút là xong). → **Nhóm đồng ý:** Ở bản v1 sẽ thu hẹp phạm vi vào các văn bản quy định chuyên môn dài (thông tư quy chế đánh giá, hướng dẫn nhiệm vụ năm học, cấu trúc/định dạng đề thi mới) có sửa đổi hoặc thay thế quy định cũ.
- **Phản biện 2 (về Success Metric):** Baseline `30–60 phút/văn bản` mới dựa trên ước tính trí nhớ, và metric hiện mới đo kết quả cuối mà chưa đo trực tiếp chất lượng đầu ra ở bước tóm tắt (nếu tóm tắt nhanh nhưng sót điều khoản quan trọng hoặc tổ trưởng phải sửa lại gần hết thì sao?). → **Nhóm đồng ý:** Sẽ bổ sung tiêu chí đo chất lượng bản nháp (tỉ lệ trích dẫn đúng điều/khoản gốc và tỉ lệ nội dung tổ trưởng phải viết lại < 30%) ở Problem Statement v1.
- **Phản biện 3 (về phương án No AI):** Nếu tổ trưởng phân công 1 người đọc và viết tóm tắt 1 trang dùng chung cho cả tổ thì đã bỏ được việc lặp lại giữa các giáo viên, vậy còn cần AI ở đâu? → **Nhóm đồng ý một phần:** Phân công 1 đầu mối là cải tiến quy trình bắt buộc phải có, nhưng bản thân người được phân công (hoặc tổ trưởng) vẫn bị nghẽn 30–60 phút ở bước lọc và đối chiếu thủ công với văn bản cũ, nên AI sẽ can thiệp đúng vào bước hỗ trợ người đầu mối này.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: mơ hồ và phức tạp trung bình 

Vì sao: văn bản diễn đạt pháp lý + việc đối chiếu với văn bản cũ và xác định ảnh hưởng đến từng môn/khối vẫn còn mơ hồ. AI không thể tự quyết định mà chỉ hỗ trợ lọc và chỉ ra điểm khác. Phần phán đoán cuối cùng vẫn cần tổ trưởng để chốt

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) |Tổ trưởng phân công luân phiên 1 người đọc + viết tóm tắt 1 trang theo mẫu cố định| Tổ nhỏ, ít văn bản, mọi người đều có thời gian | Vẫn mất 30–60 phút/người, chậm khi có nhiều văn bản cùng lúc | Không |
| **Rule**| Dùng checklist + từ khóa cố định để lọc| Văn bản rất chuẩn hóa, ít thay đổi cấu trúc| Dễ bỏ sót vì văn bản pháp lý diễn đạt vòng vo | Không |
| **Workflow**| AI trích xuất điểm liên quan đến môn/khối + so sánh với văn bản cũ + kèm trích dẫn nguồn → giáo viên/tổ trưởng kiểm tra và chốt | Cần tốc độ + vẫn giữ được sự kiểm soát của con người | AI hiểu sai hoặc thêm nội dung → bắt buộc có người duyệt |Có|
| **Agent**| AI tự đọc, tự cập nhật ma trận đề và kế hoạch bài dạy, chỉ báo cáo kết quả| Khi độ tin cậy rất cao và chấp nhận rủi ro lớn | Rủi ro pháp lý và chuyên môn quá cao nếu AI sai | Không |

**Mức chọn:** Workflow

**Vì sao không chọn mức đơn giản hơn:** No AI và Rule vẫn để giáo viên mất nhiều thời gian đọc và đối chiếu. Workflow vừa giảm thời gian đáng kể vừa giữ được bước kiểm tra của con người

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? |Danh sách các điểm thay đổi liên quan đến môn + khối cụ thể, kèm số điều/khoản/trang gốc và điểm khác biệt so với văn bản cũ |
| **Judgment** — con người cân nhắc, quyết định gì?| Giáo viên và tổ trưởng kiểm tra độ chính xác của phần trích xuất, quyết định mức độ ảnh hưởng và việc cần làm cụ thể |
| **Action** — hành động cuối cùng là gì, ai làm?| Giáo viên cập nhật ma trận đề / kế hoạch bài dạy; tổ trưởng duyệt và phổ biến |
| **Outcome** — đo kết quả bằng gì?| Thời gian từ lúc nhận văn bản → biết việc cần làm < 1 buổi; số lần hỏi lại giảm ≥ 50%; lỗi áp dụng sai → 0 |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | File PDF văn bản mới + (nếu có) văn bản cũ tương ứng + thông tin môn/khối của giáo viên. Có sẵn qua email/Zalo/hệ thống trường |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?| Tổ trưởng và giáo viên đánh dấu chỗ AI trích sai hoặc thiếu sau mỗi lần dùng, dùng để tinh chỉnh prompt/mẫu |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Muốn được hỗ trợ (augment).
Bằng chứng: Văn bản liên quan đến chuyên môn và trách nhiệm pháp lý của giáo viên. Họ cần tự kiểm tra lại trước khi áp dụng, không thể giao hoàn toàn cho AI quyết định.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Báo nhầm (hallucination / thêm nội dung không có) tệ hơn, vì có thể khiến giáo viên sửa sai ma trận đề hoặc cách đánh giá.
Thiết kế xử lý: Bắt buộc AI phải kèm trích dẫn điều/khoản/trang gốc, và có bước tổ trưởng kiểm tra trước khi phổ biến.
---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor**|Giáo viên bộ môn (người áp dụng); Tổ trưởng chuyên môn (người phổ biến & duyệt) |
| **Quy trình**| Nhận văn bản → Đọc → Lọc phần liên quan môn/khối → Đối chiếu văn bản cũ → Thống nhất cách hiểu → Xác định việc cần làm → Cập nhật tài liệu |
| **Bottleneck**| Bước lọc phần liên quan + đối chiếu với cái cũ (30–60 phút/văn bản) và chờ họp tổ (độ trễ tính bằng ngày) |
| **Impact**| Giáo viên tốn thời gian lặp lại, lệch chuẩn giữa các giáo viên, học sinh có nguy cơ học/thi theo quy định cũ |
| **Success Metric** (baseline → target, cách đo) | Thời gian từ nhận văn bản → biết việc cần làm: vài ngày → trong 1 buổi<br>Số lần hỏi lại tổ trưởng/đồng nghiệp: giảm ≥ 50%<br>Lỗi áp dụng sai khi duyệt đề/kế hoạch: → 0 |
| **Boundary**| Chỉ xử lý công văn/thông tư liên quan đến chuyên môn, đánh giá, cấu trúc đề thi. Không bao gồm văn bản hành chính chung hoặc văn bản không liên quan môn dạy |
| **AI intervention point**| Sau khi nhận văn bản: AI hỗ trợ trích xuất điểm liên quan đến môn/khối + so sánh với văn bản cũ, kèm trích dẫn nguồn |
| **Mức chọn**| Workflow |
| **Rủi ro & người kiểm tra**| AI hiểu sai hoặc thêm nội dung → Tổ trưởng là người kiểm tra cuối cùng trước khi phổ biến |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor| Chủ yếu giáo viên| Giáo viên + Tổ trưởng chuyên môn| Làm rõ vai trò kiểm tra và phổ biến |
| Boundary| Chưa giới hạn rõ| Chỉ văn bản chuyên môn, đánh giá, cấu trúc đề| Tránh scope creep |
| AI intervention| Chung chung “AI đọc văn bản”| Cụ thể: trích xuất + so sánh + bắt buộc trích dẫn nguồn| Tăng tính kiểm soát và giảm hallucination |
| Mức can thiệp| Chưa chốt| Workflow| Phù hợp với yêu cầu con người phải kiểm tra |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 |Độ chính xác nội dung| Mọi điểm trích ra đều có trong văn bản gốc, không thêm thông tin mới   | Có nội dung không tồn tại trong văn bản|
| 2  | Có trích dẫn nguồn rõ ràng| Mỗi ý đều kèm số điều/khoản hoặc số trang| Thiếu hoặc sai vị trí trích dẫn|
| 3  | Đúng phạm vi môn & khối| Chỉ nêu những điểm ảnh hưởng đến môn/khối được chỉ định| Đưa cả nội dung không liên quan |
| 4  | Chỉ ra được điểm khác biệt| So sánh được với văn bản cũ (nếu có) và nêu rõ thay đổi| Không chỉ ra được sự khác biệt hoặc chỉ ra sai|
| 5  | Ngắn gọn, dễ kiểm tra| Giáo viên đọc phần tóm tắt + trích dẫn là hiểu được việc cần làm| Quá dài hoặc vẫn phải đọc lại toàn bộ văn bản gốc |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? |Thấp| Giáo viên và tổ trưởng đều đang mất 30–60 phút/văn bản và thường xuyên hỏi lại nhau → nhu cầu rõ ràng |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Trung bình | Cần giao diện đơn giản + bắt buộc hiện trích dẫn nguồn để giáo viên dễ kiểm tra |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?| Thấp – Trung bình| Input là PDF có sẵn; có thể dùng LLM hiện có. Điểm khó là PDF scan chất lượng thấp |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?| Trung bình| Văn bản mang tính quy phạm → bắt buộc có người kiểm tra (tổ trưởng). Chi phí thấp nếu dùng API có sẵn |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go
Go
**Lý do:**
Problem có pain thật, đo được, actor rõ, và mức Workflow vừa đủ mạnh để giảm thời gian đáng kể nhưng vẫn giữ được kiểm soát của con người
**Nếu Go — pilot nhỏ nhất:**
Lấy 3–5 văn bản gần đây nhất, chạy thử quy trình AI trích xuất + tổ trưởng kiểm tra, đo thời gian và số lỗi còn lại
**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):
Nếu sau khi pilot 5 văn bản mà tỷ lệ AI trích sai vẫn > 30%, hoặc giáo viên vẫn phải đọc lại gần như toàn bộ văn bản gốc thì quay lại phương án No AI và chỉ dùng AI ở mức hỗ trợ tìm từ khóa.
---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
