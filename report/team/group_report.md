# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: G1
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Card #3 của Đoàn Đăng Khoa — giáo viên bộ môn cần xác định phần thay đổi trong văn bản Bộ/Sở liên quan đến môn, khối mình dạy để kịp cập nhật ma trận đề và kế hoạch bài dạy.
- Quyết định cuối: Go / Not Yet / No-Go

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
