# Hướng dẫn làm bài Day 02 — Discovery & Problem Framing

Tài liệu này là lộ trình thao tác nhanh cho nhóm 3–4 người. Bài lab **không cần viết hoặc chạy code**. Kết quả cần có là một vấn đề đã được kiểm chứng, Problem Statement và quyết định **Go / Not Yet / No-Go** có lý do. Khi cần ví dụ và mẫu điền chi tiết, mở [worksheet](docs/01-worksheet.md) và [bài mẫu](docs/02-deliverable-example.md).

## 1. Chuẩn bị repo chung

1. Nhóm trưởng fork repo đề bài và đặt tên `K5-<L3A hoặc L3B>-DAY02-TenNhom-DiscoveryProblemFraming`, trong đó `TenNhom` không dấu, không khoảng trắng. Chỉ dùng **một repo nhóm**; không fork thêm repo cá nhân và không tạo Pull Request về repo gốc.
2. Nhóm trưởng mời các thành viên tại **Settings → Collaborators**. Mọi người chấp nhận lời mời rồi làm việc trên repo này. Nếu repo private, thêm coach theo hướng dẫn trên LMS.
3. Mỗi người sao chép [mẫu báo cáo cá nhân](report/individual/MSSV_HoTen.md) thành `report/individual/<MSSV>_<HoTenKhongDau>.md`, ví dụ `20241234_NguyenVanAn.md`, rồi sửa tiêu đề trong file. Giữ file mẫu đến khi cả nhóm đã tạo file riêng, sau đó xóa mẫu.
4. Nhóm dùng chung [báo cáo nhóm](report/team/group_report.md) và [bảng thành viên](TEAM.md). Mỗi người tự viết báo cáo cá nhân và phần đóng góp của mình trong bảng thành viên, rồi commit bằng tài khoản GitHub của chính mình.

Nếu làm bằng GitHub web, có thể mở file và bấm **Edit** để điền, rồi **Commit changes**. Tránh để nhiều người sửa cùng một đoạn cùng lúc; chia mục theo checkpoint trước khi bắt đầu.

## 2. Làm theo thứ tự CP0–CP7

| CP | Ai làm | Việc cần hoàn thành | Ghi vào |
|---|---|---|---|
| **CP0 — 15 phút** | Cá nhân | Đọc [bài mẫu](docs/02-deliverable-example.md), nhất là cách chọn một vấn đề, kiểm chứng và ra quyết định. | Không nộp |
| **CP1 — 25 phút** | Cá nhân | Tự tìm **ít nhất 5 vấn đề thật** qua 4 lăng kính: việc lặp lại, tốn thời gian, cần tổng hợp thông tin, pain của người khác. Viết từng vấn đề dạng “Khi…, tôi muốn…, để…” và ghi dấu hiệu đo được như số phút hoặc tần suất. | Báo cáo cá nhân, mục 2 |
| **CP2 — 35 phút** | Cá nhân | Chọn **3 vấn đề tốt nhất**. Với mỗi vấn đề, điền Problem Card và vẽ quy trình hiện tại **3–7 bước**, có thời gian và bước nghẽn. Chọn một card để pitch; nhờ AI phản biện card và ghi mình đã sửa gì. | Báo cáo cá nhân, mục 3 |
| **CP3 — 30 phút** | Nhóm | Mỗi người pitch top 3 và phản biện người khác. Gom candidate thành cluster, lập cây Opportunity Solution Tree với **một outcome**, chấm shortlist theo 7 tiêu chí và chọn **một candidate problem**. Ghi lý do chọn và loại ít nhất hai candidate khác. | Báo cáo nhóm, mục 2; đóng góp cá nhân ở mục 4 báo cáo cá nhân |
| **CP4 — 30 phút** | Nhóm | Lập **4–6 giả định** và ưu tiên giả định quan trọng nhưng ít bằng chứng. Kiểm chứng bằng phỏng vấn **2–3 người thật** hoặc survey/poll **5–10 người**; hỏi việc đã xảy ra, ghi cả tín hiệu phản bác. Tìm **2–3 giải pháp/case/pattern** đã có, mở và kiểm từng link. Nêu vấn đề đã thay đổi thế nào sau kiểm chứng. | Báo cáo nhóm, mục 3; snapshot hoặc ảnh ở `report/assets/` |
| **CP5 — 45 phút** | Nhóm | Vẽ quy trình hiện tại với actor, input, output, thời gian; đánh dấu bottleneck. Vẽ quy trình tương lai, chỉ ra bước của Rule/AI/con người, ranh giới và cách quay về khi AI sai. Lập bảng before/after; viết Problem Statement **v0** gồm Actor, Quy trình, Bottleneck, Impact, Success Metric, Boundary. | Báo cáo nhóm, mục 4–5 |
| **CP6 — 25 phút** | Nhóm | So sánh **No AI / Rule / Workflow / Agent** và chọn mức đơn giản nhất đủ dùng. Với phương án AI, điền AI Canvas, trả lời hai câu hỏi PAIR và viết 3–5 tiêu chí đánh giá. Viết Problem Statement **v1** và giải thích điểm đổi từ v0. Đánh giá 4 rủi ro Value, Usability, Feasibility, Viability; chốt Go / Not Yet / No-Go cùng bước tiếp theo và ngưỡng dừng đo được. | Báo cáo nhóm, mục 6–8 |
| **CP7 — 15 phút** | Cá nhân | Ghi việc mình đã làm, câu hỏi đã hỏi và nhận, cách dùng AI; viết reflection **ít nhất 200 từ** cho câu 6.1–6.6 bằng trải nghiệm thật. Tự giải thích chuỗi vấn đề → quy trình → metric → boundary → mức can thiệp → quyết định trong câu 6.7. Điền phần của mình trong bảng thành viên. | Báo cáo cá nhân, mục 4–6; `TEAM.md` |

Sau CP2 và CP5 có thể nghỉ 10 phút theo [lịch lab](README.md). Xem [yêu cầu chi tiết và tự kiểm tra từng CP](CHECKPOINTS.md) nếu cần đối chiếu trước khi chuyển bước.

## 3. Cách viết phần quan trọng

- **Problem trước giải pháp:** “Mỗi tuần mất 90 phút tổng hợp 5 nguồn dữ liệu” là vấn đề có thể kiểm tra. “Cần chatbot tổng hợp dữ liệu” đã là một phương án giải quyết.
- **Bottleneck:** chỉ đúng *bước nào* trong quy trình đang nghẽn, mất bao lâu và gây hậu quả gì. Tránh viết chung “quy trình chậm”.
- **Bằng chứng kiểm chứng:** ghi vai trò người được hỏi, thời điểm và cách hỏi; mô tả lần gần nhất họ gặp vấn đề, cách họ đang xử lý, thời gian hoặc tần suất. Không xem lời khen hoặc dự đoán “sẽ dùng” là bằng chứng.
- **Success Metric:** ghi **baseline → target → cách đo**, ví dụ thời gian hoàn thành trung vị trước và sau. Nếu chưa đo được baseline, ghi rõ cần đo và để quyết định phù hợp với mức độ chưa chắc chắn.
- **Boundary:** nói rõ việc giải pháp/AI không được tự làm, điểm con người kiểm tra và cách xử lý khi đầu ra sai.
- **Quyết định:** Go cần pilot nhỏ và ngưỡng dừng; Not Yet cần nêu giả định phải kiểm chứng tiếp; No-Go cần nêu phương án thay thế. Kết luận không dùng AI vẫn hợp lệ nếu lập luận dựa trên bằng chứng.

Nếu chọn **No AI hoặc Rule**, [rubric](RUBRIC.md) cho phép bỏ AI Canvas và câu hỏi PAIR. Vẫn phải giải thích vì sao mức đó đủ, ghi `AI intervention point: Không có` kèm lý do, và viết tiêu chí đánh giá cho giải pháp đã chọn.

## 4. Quy định dùng AI và dữ liệu

Đọc đầy đủ [quy định](RULES.md) trước khi làm. Các điểm dễ sai:

- CP1: tự scan trước khi hỏi AI. CP2: dùng AI để phản biện, không để AI bịa Problem Card.
- CP3: không dùng AI khi pitch và phản biện. CP4: không dùng AI đóng vai người được phỏng vấn; dữ liệu phải từ người thật. Có thể dùng AI hỗ trợ research, nhưng mọi claim quan trọng phải có link đã tự kiểm.
- CP5–CP6: dùng AI để tìm lỗ hổng trong lập luận; nhóm tự viết và tự chốt quyết định. CP7: AI không viết reflection thay bạn.
- Mỗi lần dùng AI, ghi vào bảng **Dùng AI** trong báo cáo cá nhân: dùng để làm gì, giúp gì, sai hoặc hời hợt ở đâu, mình sửa gì.
- Không bịa phỏng vấn/survey. Không đưa tên đầy đủ, số điện thoại, email của người được hỏi, thông tin nội bộ, API key, password hay file `.env` lên repo. Che thông tin nhạy cảm trong ảnh.

## 5. Kiểm tra và nộp bài

- [ ] Repo nhóm và file báo cáo cá nhân đúng quy tắc đặt tên; mỗi người có một file riêng, không còn file mẫu sau khi cả nhóm đã tạo file.
- [ ] Báo cáo cá nhân có đủ CP1, CP2, CP7; báo cáo nhóm có đủ CP3–CP6; [TEAM.md](TEAM.md) ghi đóng góp cụ thể và bằng chứng của từng người.
- [ ] Sơ đồ, ảnh và snapshot nằm trong [report/assets/](report/assets/) và link hiển thị được trên GitHub. Nếu dùng Mermaid, đặt trực tiếp trong khối code `mermaid` của báo cáo.
- [ ] Link research đã mở kiểm; số liệu có nguồn; không có thông tin cá nhân hoặc bí mật trong repo.
- [ ] Mỗi thành viên nộp **cùng link repo nhóm** tại bài Day 02 trên LMS bằng tài khoản của mình, trước hạn do lớp áp dụng.

Hạn mặc định: lab sáng **23h59 GMT+7 ngày lab**; lab chiều/tối **11h59 GMT+7 ngày hôm sau**. Nếu coach thông báo gia hạn trên LMS thì theo hạn được thông báo. Người chấm xem commit cuối cùng trước hạn. Xem [hướng dẫn nộp bài](SUBMISSION.md) và [thang điểm](RUBRIC.md) để tự rà soát lần cuối.
