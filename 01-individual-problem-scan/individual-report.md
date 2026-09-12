# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Đinh Quốc Bảo
- Mã học viên: 2A202602933
- Vai trò / bối cảnh: intern phát triển phần mềm Full stack
- Công việc hằng tuần: (3-5 gạch đầu dòng để soi problem):
  - Tiếp nhận, phân tích yêu cầu và task được Mentor/BA giao.
  - Phát triển, chỉnh sửa và kiểm thử các chức năng Front-end/Back-end.
  - Đọc tài liệu API, source code và nghiên cứu công nghệ phục vụ task.
  - Trao đổi với BA, Tester và Mentor để làm rõ yêu cầu, xử lý lỗi và review code.
  - Viết tài liệu chức năng, báo cáo tiến độ và sử dụng AI hỗ trợ phân tích task, viết prompt, tra cứu kỹ thuật.
  - Debug và xử lý lỗi phát sinh trong quá trình phát triển, tích hợp API.
  - Tìm hiểu source code có sẵn để xác định luồng xử lý trước khi sửa hoặc thêm chức năng.
  - Kiểm tra API bằng Postman và đối chiếu dữ liệu giữa Front-end, Back-end và Database.
  - Sửa code theo feedback sau các buổi review code hoặc sau khi Tester báo lỗi.
  - Quản lý source code bằng Git, xử lý conflict và cập nhật code từ các thành viên trong nhóm.




---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian / AI có thể tốt hơn | Mất nhiều thời gian đọc và phân tích task trước khi bắt đầu code do yêu cầu chưa rõ hoặc có nhiều tài liệu liên quan. | Intern / Developer | Khoảng **30–60 phút/task**, gặp **3–5 task/tuần**. Có thể đối chiếu thời gian từ lúc nhận task đến commit đầu tiên. |
| 2 | Lặp lại / Tốn thời gian | Phải đọc nhiều tài liệu API và source code để xác định endpoint, request/response và luồng xử lý trước khi phát triển chức năng. | Intern / Developer | Khoảng **30–90 phút/task**, thực hiện **3–5 lần/tuần**. Bằng chứng từ tài liệu API, lịch sử commit hoặc task được giao. |
| 3 | Tốn thời gian / Pain từ người khác | Yêu cầu nghiệp vụ đôi khi chưa rõ, phải trao đổi lại nhiều lần với BA, Tester hoặc Mentor trước khi triển khai. | Developer / BA / Tester / Mentor | Trung bình **2–4 lần trao đổi/task**, mỗi lần khoảng **5–15 phút**. Có thể kiểm tra lịch sử chat hoặc comment trên task. |
| 4 | Lặp lại / AI có thể tốt hơn | Viết tài liệu chức năng và báo cáo tiến độ mất thời gian do phải tổng hợp lại thông tin từ task, source code và kết quả đã làm. | Intern / Mentor | Khoảng **30–60 phút/lần**, thực hiện **1–3 lần/tuần**. Bằng chứng từ các file tài liệu và báo cáo đã viết. |
| 5 | Tốn thời gian / AI có thể tốt hơn | Debug lỗi tích hợp giữa Front-end, Back-end và API mất nhiều thời gian vì phải kiểm tra nhiều tầng của hệ thống. | FE / BE / Tester | Một lỗi thường mất khoảng **30–120 phút** để xác định nguyên nhân; gặp khoảng **2–5 lỗi/tuần**. Bằng chứng từ bug/ticket và commit sửa lỗi. |
| 6 | Lặp lại / Tốn thời gian | Kiểm tra API bằng Postman và đối chiếu request, response, database phải thực hiện thủ công nhiều lần. | Developer / Tester | Khoảng **10–20 phút/API**, kiểm tra khoảng **5–10 API/tuần**. Bằng chứng từ Postman Collection và API đã test. |
| 7 | Pain từ người khác / Lặp lại | Sau khi Tester báo lỗi hoặc Mentor review code, phải quay lại tìm vị trí code liên quan và sửa theo feedback. | Intern / Mentor / Tester | Khoảng **2–5 feedback/tuần**, mỗi lần sửa khoảng **15–60 phút**. Bằng chứng từ comment review, bug report và commit sửa code. |
| 8 | Tốn thời gian / AI có thể tốt hơn | Khi gặp công nghệ hoặc thư viện chưa quen, mất nhiều thời gian tìm tài liệu và lựa chọn cách áp dụng phù hợp vào dự án. | Intern / Developer | Khoảng **1–2 giờ/chủ đề**, gặp **1–3 lần/tuần**. Bằng chứng từ lịch sử nghiên cứu, tài liệu đã đọc và task liên quan. |
| 9 | Tốn thời gian / Pain từ người khác | Git conflict hoặc thay đổi code từ thành viên khác làm gián đoạn quá trình phát triển và phải kiểm tra lại code trước khi merge. | Developer / Team | Khoảng **15–45 phút/lần conflict**, gặp khoảng **1–3 lần/tuần**. Bằng chứng từ Git history, pull request hoặc merge conflict. |
| 10 | Lặp lại / AI có thể tốt hơn | Việc viết prompt AI để phân tích task, tìm lỗi hoặc nghiên cứu công nghệ phải chỉnh sửa nhiều lần mới nhận được kết quả phù hợp. | Intern | Trung bình **2–4 lần chỉnh prompt/vấn đề**, khoảng **10–30 phút/vấn đề**, sử dụng AI khoảng **3–5 lần/tuần**. Có thể đối chiếu lịch sử hội thoại AI. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

### AI đã dùng ở Phase 1

- **Prompt đã hỏi:** Phân tích các công việc hằng tuần của một Intern Full-stack Developer và phản biện các vấn đề có tính lặp lại, tốn thời gian hoặc có khả năng được AI hỗ trợ.
- **Ý dùng được:** Đọc và phân tích task, đọc API/source code, debug lỗi tích hợp, kiểm thử API, tổng hợp tài liệu và nghiên cứu công nghệ.
- **Ý bỏ vì không phải pain thật:** Các vấn đề quá rộng như "code chậm", "thiếu kinh nghiệm", "làm việc chưa hiệu quả" vì không chỉ ra được workflow, bottleneck và số đo cụ thể.

### Self-check Phase 1

- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

# Phase 2 — Top 3 Problem Cards

## 2.1. Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Mất nhiều thời gian đọc và phân tích task trước khi bắt đầu code. | Xảy ra gần như mỗi khi nhận task mới; ảnh hưởng trực tiếp đến thời gian bắt đầu phát triển; có thể chuẩn hóa workflow và dùng AI hỗ trợ. | AI có hiểu đúng nghiệp vụ và context dự án khi thông tin task chưa đầy đủ hay không. |
| 2 | Debug lỗi tích hợp giữa Front-end, Back-end và API mất nhiều thời gian. | Một lỗi có thể mất 30–120 phút; có nhiều bước kiểm tra thủ công; AI có thể hỗ trợ phân tích log và khoanh vùng nguyên nhân. | AI có xác định đúng root cause khi thiếu log hoặc lỗi liên quan nhiều module hay không. |
| 3 | Phải đọc nhiều tài liệu API và source code trước khi phát triển chức năng. | Lặp lại 3–5 lần/tuần; mỗi lần mất 30–90 phút; có thể hỗ trợ bằng tìm kiếm và tóm tắt source code. | AI có hiểu đúng source code khi documentation không được cập nhật hay không. |

---

## 2.2. Problem Cards chi tiết

### Problem Card #1 — Phân tích task trước khi phát triển

```text
Problem 1 câu:
Intern mất khoảng 30–60 phút cho mỗi task để đọc, tổng hợp và làm rõ yêu cầu trước khi có thể bắt đầu code.

Actor:
Intern / Developer.

Thời điểm / bối cảnh:
Khi Mentor hoặc BA giao một task phát triển, chỉnh sửa hoặc sửa lỗi mới.

Current workflow 3-7 bước:

1. Nhận task từ Mentor/BA.
2. Đọc description và acceptance criteria của task.
3. Tìm tài liệu, API và source code liên quan.
4. Xác định các module/file có khả năng phải chỉnh sửa.
5. Ghi lại các điểm chưa rõ và hỏi Mentor/BA.
6. Tổng hợp lại yêu cầu và xác định hướng triển khai.
7. Bắt đầu code.

Bottleneck:
Bước 3–5: phải tự tìm context từ nhiều nguồn và trao đổi lại khi yêu cầu chưa rõ.

Impact:
Mất khoảng 30–60 phút/task.
Với 3–5 task/tuần, tương đương khoảng 1,5–5 giờ/tuần chỉ để chuẩn bị trước khi code.

Success metric:
- Giảm thời gian phân tích một task từ 30–60 phút xuống khoảng 15–30 phút.
- Giảm số lần phải hỏi lại Mentor/BA.
- Không làm tăng số task phải sửa lại do hiểu sai yêu cầu.

Non-AI alternative:
Chuẩn hóa template giao task gồm mục tiêu, acceptance criteria, API liên quan, module liên quan và expected output.

AI hypothesis:
AI đọc task cùng tài liệu/source code liên quan, sau đó tóm tắt yêu cầu, xác định module có khả năng bị ảnh hưởng và tạo danh sách câu hỏi cần làm rõ trước khi code.

Quick gut:

[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

### Draft workflow Card #1

```text
CURRENT STATE — khoảng 45 phút/task

[1. Nhận task: 2']
        ↓
[2. Đọc yêu cầu: 8']
        ↓
[3. Tìm API/source code: 15']
        ↓
[4. Phân tích ảnh hưởng: 10']  <-- bottleneck
        ↓
[5. Hỏi lại Mentor/BA: 10']

FUTURE STATE — mục tiêu khoảng 20 phút/task

[1. Nhận task + context: 2']
        ↓
[2. AI tổng hợp task + source/API: 5']
        ↓
[3. AI đề xuất phạm vi ảnh hưởng + câu hỏi: 5']
        ↓
[4. Developer kiểm tra và xác nhận: 8']  <-- human boundary

Fallback:
Nếu AI thiếu context hoặc phân tích không chắc chắn, Developer tự đọc source code/tài liệu và xác nhận trực tiếp với Mentor/BA trước khi code.
```

File đính kèm: `01-individual-problem-scan-workflow-card-1.png`

---

### Problem Card #2 — Debug lỗi tích hợp FE/BE/API

```text
Problem 1 câu:
Developer mất khoảng 30–120 phút cho một lỗi tích hợp vì phải kiểm tra thủ công nhiều tầng từ Front-end, request API, Back-end đến Database.

Actor:
Intern / FE Developer / BE Developer / Tester.

Thời điểm / bối cảnh:
Khi phát triển chức năng mới hoặc khi Tester báo một chức năng hoạt động sai.

Current workflow 3-7 bước:

1. Nhận bug hoặc phát hiện lỗi.
2. Thực hiện lại thao tác để reproduce lỗi.
3. Kiểm tra request/response từ Front-end.
4. Kiểm tra API và log Back-end.
5. Kiểm tra Database hoặc dữ liệu liên quan.
6. Khoanh vùng nguyên nhân và sửa code.
7. Test lại chức năng.

Bottleneck:
Bước 3–5: mất nhiều thời gian kiểm tra thủ công từng tầng để tìm chính xác nguyên nhân.

Impact:
Một lỗi mất khoảng 30–120 phút.
Khoảng 2–5 lỗi/tuần có thể tiêu tốn từ 1–10 giờ làm việc/tuần.

Success metric:
- Giảm thời gian xác định root cause trung bình ít nhất 30%.
- Giảm số bước kiểm tra thủ công không cần thiết.
- Không làm tăng tỷ lệ fix sai nguyên nhân hoặc phát sinh regression.

Non-AI alternative:
Chuẩn hóa logging, error response, correlation ID và checklist debug FE → API → BE → DB.

AI hypothesis:
AI nhận error message, stack trace, request/response và các đoạn log liên quan để phân loại lỗi, đề xuất tầng có khả năng xảy ra lỗi và gợi ý file/code cần kiểm tra trước.

Quick gut:

[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

### Draft workflow Card #2

```text
CURRENT STATE — khoảng 75 phút/lỗi

[1. Reproduce: 10']
        ↓
[2. Kiểm tra FE/request: 15']
        ↓
[3. Kiểm tra API + BE log: 20']  <-- bottleneck
        ↓
[4. Kiểm tra DB: 15']
        ↓
[5. Khoanh vùng nguyên nhân: 15']

FUTURE STATE — mục tiêu khoảng 40 phút/lỗi

[1. Reproduce + thu thập log: 10']
        ↓
[2. AI phân tích error/log/request: 5']
        ↓
[3. AI đề xuất root cause: 5']
        ↓
[4. Developer xác minh + sửa lỗi: 20']  <-- human boundary

Fallback:
Nếu AI không xác định được nguyên nhân hoặc kết quả không đáng tin cậy, Developer sử dụng checklist debug và kiểm tra thủ công FE → API → BE → DB.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

### Problem Card #3 — Tìm hiểu API và source code

```text
Problem 1 câu:
Intern mất khoảng 30–90 phút/task để tìm và đọc API, source code và luồng xử lý liên quan trước khi chỉnh sửa hoặc phát triển chức năng.

Actor:
Intern / Developer.

Thời điểm / bối cảnh:
Khi nhận một task liên quan đến module chưa quen hoặc cần sửa chức năng đã tồn tại trong hệ thống.

Current workflow 3-7 bước:

1. Đọc yêu cầu task.
2. Tìm endpoint/API liên quan.
3. Tìm Controller/Service/Repository hoặc component liên quan.
4. Đọc các class và luồng gọi giữa các module.
5. Kiểm tra Database/model liên quan.
6. Tổng hợp luồng xử lý.
7. Bắt đầu sửa hoặc phát triển chức năng.

Bottleneck:
Bước 2–5: phải tìm kiếm và đọc nhiều file để hiểu quan hệ giữa API, business logic và dữ liệu.

Impact:
Khoảng 30–90 phút/task.
Với 3–5 task/tuần, có thể mất khoảng 1,5–7,5 giờ/tuần cho việc tìm hiểu context.

Success metric:
- Giảm ít nhất 30% thời gian tìm hiểu source code.
- Xác định đúng các file/module liên quan ngay từ lần phân tích đầu.
- Giảm số lần sửa nhầm module hoặc bỏ sót dependency.

Non-AI alternative:
Cải thiện tài liệu kiến trúc, API documentation, README và sơ đồ luồng của từng module.

AI hypothesis:
AI tìm kiếm source code theo task, tóm tắt luồng Controller → Service → Repository → Database và liệt kê các file/module có khả năng bị ảnh hưởng.

Quick gut:

[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

### Draft workflow Card #3

```text
CURRENT STATE — khoảng 60 phút/task

[1. Đọc task: 5']
        ↓
[2. Tìm API: 10']
        ↓
[3. Tìm source code liên quan: 20']  <-- bottleneck
        ↓
[4. Đọc business flow: 15']
        ↓
[5. Tổng hợp context: 10']

FUTURE STATE — mục tiêu khoảng 30 phút/task

[1. Đọc task: 5']
        ↓
[2. AI tìm API + source liên quan: 5']
        ↓
[3. AI tóm tắt luồng xử lý: 5']
        ↓
[4. Developer đọc và kiểm chứng source: 15']  <-- human boundary

Fallback:
Nếu AI xác định sai hoặc bỏ sót dependency, Developer sử dụng IDE search, API documentation và Git history để kiểm tra lại source code thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

## 2.3. Card muốn pitch nhất

### Card tôi muốn pitch nhất

```text
Problem Card #1 — Phân tích task trước khi phát triển.
```

### Vì sao

```text
Khi nhận một task mới, tôi thường phải đọc yêu cầu, tìm API, đọc source code và trao đổi lại với Mentor/BA trước khi có thể bắt đầu code.

Quá trình này mất khoảng 30–60 phút/task và xảy ra khoảng 3–5 task/tuần, tương đương khoảng 1,5–5 giờ/tuần.

Bottleneck chính nằm ở việc thông tin của task nằm ở nhiều nguồn khác nhau và Intern chưa quen toàn bộ source code.

Tôi muốn thử một workflow có AI hỗ trợ tổng hợp task, tìm context liên quan và tạo danh sách câu hỏi cần làm rõ. Developer vẫn là người kiểm tra kết quả cuối cùng trước khi bắt đầu code.

Mục tiêu là giảm thời gian phân tích task xuống khoảng 15–30 phút mà không làm tăng số lần sửa lại do hiểu sai yêu cầu.
```

### Câu hỏi tôi muốn nhóm challenge

```text
1. Nếu AI chỉ giúp tóm tắt task nhưng Developer vẫn phải đọc lại source code để kiểm chứng thì workflow này có thực sự tiết kiệm đủ thời gian không?

2. Làm thế nào để đo được AI giúp hiểu task tốt hơn mà không chỉ đo việc hoàn thành bước phân tích nhanh hơn?
```

### AI phản biện Card

- **Điểm yếu AI chỉ ra:** Không nên giả định nguyên nhân của việc phân tích task lâu hoàn toàn là do thiếu AI. Nguyên nhân có thể đến từ task chưa đủ acceptance criteria, tài liệu dự án chưa tốt hoặc Intern chưa quen source code. AI cũng có nguy cơ đưa ra kết luận sai khi thiếu context.
- **Tôi sửa gì:** Giữ AI ở vai trò hỗ trợ tổng hợp và tìm context thay vì tự quyết định cách triển khai. Thêm `human boundary` để Developer kiểm tra kết quả trước khi code. Đồng thời bổ sung `Non-AI alternative` là chuẩn hóa template giao task và cải thiện tài liệu dự án.

---

## Kết luận Phase 2

Qua Phase 1, ba vấn đề được ưu tiên gồm:

1. **Phân tích task trước khi code:** khoảng 30–60 phút/task.
2. **Debug lỗi FE/BE/API:** khoảng 30–120 phút/lỗi.
3. **Tìm hiểu API và source code:** khoảng 30–90 phút/task.

Trong đó, **Problem Card #1 — Phân tích task trước khi phát triển** được chọn để pitch vì xảy ra thường xuyên, workflow có thể mô tả rõ, bottleneck cụ thể và có metric trước/sau để kiểm chứng.

AI chưa được xem là giải pháp mặc định mà chỉ là một hypothesis cần thử nghiệm. Giải pháp AI cần được so sánh với các cải tiến không dùng AI như chuẩn hóa task template, cải thiện API documentation và tài liệu source code.

---

## Self-check nộp phần 01

- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có actor cụ thể
- [x] Mỗi Card có workflow 3–7 bước
- [x] Mỗi Card có bottleneck
- [x] Mỗi Card có impact định lượng
- [x] Mỗi Card có success metric
- [x] Mỗi Card có Non-AI alternative
- [x] Mỗi Card có AI hypothesis
- [x] Mỗi Card có workflow trước/sau
- [x] Mỗi Card có human boundary
- [x] Mỗi Card có fallback
- [x] Đã chọn 1 Card để pitch
- [x] Có câu hỏi challenge
- [x] Có AI phản biện và điều chỉnh Card