# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đinh Quốc Bảo
- Mã học viên: 2A202602933
- Nhóm: C2
- Candidate problem nhóm chọn: Nhập liệu thủ công từ báo cáo viết tay

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi rà soát công việc hằng tuần của một Intern Full-stack và ghi lại 10 vấn đề có actor, tần suất, thời gian cùng bằng chứng có thể đối chiếu. | Tạo được danh sách đủ rộng theo nhiều lăng kính và chọn ra 3 vấn đề có workflow, bottleneck, impact cùng metric rõ để đưa vào vòng pitch. |
| Pitch Problem Card | Tôi pitch bài toán phân tích task trước khi code: mất 30–60 phút/task, xảy ra 3–5 task/tuần; đồng thời trình bày workflow AI hỗ trợ tổng hợp context nhưng Developer phải kiểm chứng. | Candidate của tôi được đưa vào shortlist, được nhóm chấm 30 điểm và trở thành một trong ba phương án cuối để so sánh. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi về khả năng OCR đọc sai chữ viết tay tiếng Việt, sự phụ thuộc vào chất lượng ảnh và cách phát hiện trường hợp AI trả kết quả sai nhưng confidence cao. | Nhóm bổ sung bước kiểm tra ảnh, human review, ép kiểm tra các trường số lượng/đơn giá và audit ngẫu nhiên thay vì cho AI ghi thẳng vào hệ thống. |
| Gom trùng / cluster | Tôi cùng nhóm đối chiếu điểm chung giữa các candidate và đưa các bài #4, #5, #6, #15 vào cluster “Hiểu task, code và kiểm tra/debug hệ thống”. | Danh sách 15 candidate được gom thành 4 cluster, giúp nhóm tránh so sánh các ý trùng nhau và rút còn 3 bài trong shortlist. |
| Chọn candidate problem | Tôi so sánh candidate phân tích task của mình với bài nhập liệu viết tay theo độ rõ của actor, workflow, evidence, khả năng đo impact và phạm vi làm trong lab. | Tôi đồng thuận chọn bài nhập liệu viết tay vì đạt 34 điểm, cao hơn bài của tôi 30 điểm, có bottleneck tập trung và dễ dựng pilot nhất. |
| Validation / research | Với vai trò Research, tôi khảo sát Google Document AI, Azure AI Document Intelligence và Amazon Textract, tập trung vào handwriting, confidence score, layout và giới hạn với tiếng Việt. | Nhóm chốt không xây OCR hoàn toàn từ đầu; trước mắt pilot bằng công cụ có sẵn, kiểm thử trên dữ liệu thật và chuyển trường confidence thấp cho người review, sau đó mới cân nhắc fine-tune theo từng loại biểu mẫu. |
| Workflow nhóm | Tôi góp ý vị trí can thiệp của AI: sau bước kiểm tra chất lượng ảnh và trước Rule validate cùng human review; đồng thời nêu fallback khi OCR lỗi hoặc hết quota. | Future workflow tách rõ AI, Rule và người kiểm tra, giữ được đường quay về nhập tay và không cho dữ liệu chưa xác nhận đi thẳng vào hệ thống kho. |
| Problem Statement | Tôi rà lại tính khả thi của AI intervention point, rủi ro OCR và boundary dựa trên kết quả research; góp ý chỉ làm 1 loại phiếu, 8 trường và loại ghi chú tự do khỏi phạm vi. | Problem Statement v1 xác định rõ chỗ AI được phép can thiệp, dữ liệu không xử lý và người chịu trách nhiệm xác nhận cuối. |
| Rule / Workflow / Agent | Tôi cùng nhóm phân biệt Rule dùng để kiểm tra định dạng, AI dùng để đọc chữ viết tay và Workflow dùng để nối các bước cố định; tôi phản biện việc dùng Agent khi không cần tự lập kế hoạch. | Nhóm chọn Workflow (Rule + AI + Human-in-the-loop), không chọn Rule thuần vì không đọc được chữ tay và không chọn Agent vì tăng rủi ro, chi phí, độ khó debug. |
| Decision | Tôi tham gia rà các điều kiện Go, nhất là độ sẵn sàng của dữ liệu, accuracy OCR và ngưỡng dừng/rollback. | Nhóm chốt Go có điều kiện với pilot 50 ảnh, đo thời gian/phiếu, field-level accuracy, tỷ lệ sửa tay và chỉ mở rộng khi đạt ngưỡng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là phần đối chiếu ba nền tảng OCR và việc chuyển kết quả research thành thiết kế confidence-based human-in-the-loop. Đóng góp này giúp nhóm đặt AI đúng một mắt xích, xác định rủi ro chữ viết tay tiếng Việt và không chọn Agent vượt quá nhu cầu.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Sau khi tự liệt kê công việc hằng tuần, tôi dùng AI để phản biện và gợi ý thêm các pain theo 4 lăng kính. | AI giúp tôi nhận ra các việc lặp lại như đọc task, tìm API/source, debug nhiều tầng và tổng hợp tài liệu. | AI đưa ra vài mô tả quá rộng như “code chậm”, “thiếu kinh nghiệm”, không có actor, workflow hay số đo. | Tôi bỏ các ý không xuất phát từ trải nghiệm thật và chỉ giữ 10 vấn đề có tần suất, thời gian cùng bằng chứng có thể đối chiếu. |
| Problem Card | Tôi dùng AI để chỉ ra điểm yếu của ba card và phản biện giả thuyết dùng AI cho việc phân tích task. | AI giúp tôi thấy nguyên nhân có thể là task thiếu acceptance criteria hoặc tài liệu kém, không chỉ do thiếu công cụ AI. | AI có xu hướng giả định đã có đủ context dự án và đánh giá quá cao khả năng hiểu đúng source code. | Tôi giới hạn AI ở vai trò tổng hợp/gợi ý, thêm human boundary, fallback và phương án non-AI là chuẩn hóa task template cùng tài liệu. |
| Workflow | Tôi dùng AI để rà chuỗi bước, vị trí bottleneck, handoff và các điểm cần fallback trong current/future workflow. | AI hữu ích khi kiểm tra xem pipeline đã có bước validate và review trước khi xuất dữ liệu hay chưa. | AI ban đầu mô tả luồng quá trơn tru, chưa phản ánh trường hợp ảnh kém, chữ khó đọc hoặc confidence cao nhưng kết quả vẫn sai. | Tôi giữ bước kiểm tra ảnh, bắt buộc người review các trường quan trọng, thêm audit và đường quay về nhập tay. |
| Research | Tôi dùng AI để lập danh sách hướng cần kiểm tra khi so sánh Google Document AI, Azure AI Document Intelligence và Amazon Textract. | AI giúp hệ thống hóa các tiêu chí handwriting, layout, confidence score, khả năng trích xuất trường và human-in-the-loop. | AI có thể nói chung chung về độ chính xác hoặc khả năng hỗ trợ tiếng Việt mà không gắn với dữ liệu thật của nhóm. | Tôi chỉ giữ nhận định đối chiếu được với tài liệu sản phẩm, ghi handwriting tiếng Việt còn rủi ro và yêu cầu benchmark trên phiếu thật. |
| Problem Statement | Tôi dùng AI để soi các field còn mơ hồ trong impact, success metric, boundary và AI intervention point. | AI giúp phát hiện các cụm như “nhanh hơn”, “chính xác hơn” chưa có baseline, target hoặc cách đo. | AI dễ biến số mục tiêu thành kết quả đã được chứng minh, dù baseline 125 phút mới chỉ được đo sơ bộ. | Tôi giữ các số này ở dạng baseline/mục tiêu cần kiểm chứng, bổ sung cách đo 5 ngày và khóa phạm vi còn 1 biểu mẫu, 8 trường. |
| Rule / Workflow / Agent | Tôi dùng AI để phản biện ba mức giải pháp trên cùng bài toán và kiểm tra xem có thật sự cần Agent hay không. | AI giúp tách rõ OCR là một node AI, validation là Rule và toàn chuỗi là Workflow cố định. | AI có xu hướng đề xuất Agent gọi nhiều tool dù thứ tự xử lý đã biết trước và đầu ra có đúng/sai rõ ràng. | Tôi cùng nhóm hạ giải pháp xuống Workflow, giữ Agent ngoài phạm vi và giao quyền xác nhận cuối cho nhân viên nhập liệu. |
| Decision | Tôi dùng AI để stress-test quyết định Go và gợi ý các tình huống cần dừng hoặc rollback. | AI giúp liệt kê các chỉ số pilot gồm thời gian/phiếu, field-level accuracy và tỷ lệ trường phải sửa tay. | Các ngưỡng 0,90, 95% hay mức giảm 40% chỉ là giả định thiết kế, AI không thể coi đó là bằng chứng thực tế. | Tôi ghi rõ chúng là ngưỡng cần hiệu chỉnh bằng pilot, chọn Go có điều kiện và giữ phương án nhập tay/biểu mẫu điện tử nếu không đạt. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 problems của các bạn, tôi học được rằng một pain gần với công việc của mình chưa chắc là candidate tốt nhất nếu workflow và cách đo còn phụ thuộc nhiều vào từng trường hợp. Candidate phân tích task trước khi code của tôi đã vào shortlist, nhưng tôi thay đổi ý kiến và đồng thuận chọn bài nhập liệu viết tay vì bottleneck tập trung hơn, cách dựng baseline rõ hơn và pilot cũng khả thi hơn. Khi nhóm bắt đầu nói đến OCR, tôi nhận ra chúng tôi rất dễ đi từ tên công nghệ sang giải pháp trước khi khóa actor, loại biểu mẫu và các trường dữ liệu cần xử lý. Vai trò Research giúp tôi đóng góp trực tiếp bằng việc so sánh Google Document AI, Azure AI Document Intelligence và Amazon Textract, đặc biệt ở khả năng đọc handwriting và trả confidence. Dấu tay rõ nhất của tôi trong artifact cuối là đề xuất không xây OCR hoàn toàn từ đầu, thử công cụ có sẵn trong pilot và đặt AI sau bước kiểm tra ảnh, trước Rule validate cùng human review. Điều khó nhất khi hoàn thiện Problem Statement là tách số liệu đã có khỏi giả định, vì baseline 125 phút và các ngưỡng accuracy vẫn cần được đo lại trên dữ liệu thật. Tôi hiểu rằng metric không chỉ là một con số mục tiêu mà còn phải có baseline, cùng người đo, cùng loại phiếu và cách chấm chéo cụ thể. Tôi cũng hiểu rõ hơn mạch problem → workflow → bottleneck → metric → boundary trước khi quyết định mức tự động hóa. AI hữu ích khi phản biện độ mơ hồ và hệ thống hóa lựa chọn, nhưng thường trả lời quá tự tin về độ chính xác OCR nếu chưa được cung cấp dữ liệu thực tế. Nếu làm lại, tôi sẽ challenge nhóm sớm hơn về nguồn ảnh thật, quyền riêng tư, quote phỏng vấn nguyên văn và ngưỡng confidence thay vì để các giả định này đến cuối mới được ghi chú.


```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

