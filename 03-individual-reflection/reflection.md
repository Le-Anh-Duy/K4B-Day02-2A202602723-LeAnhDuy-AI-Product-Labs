# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Lê Anh Duy
- Mã học viên: 2A202602723
- Nhóm: B1-Matcha latte
- Candidate problem nhóm chọn: Người phụ trách research khách hàng/thị trường mất khoảng 90 phút mỗi tuần để xác định nhu cầu thông tin, tìm nhiều nguồn, đọc và lọc dữ liệu, phân loại thành SWOT rồi tổng hợp báo cáo; bottleneck lớn nhất là bước đọc và lọc thông tin từ nhiều nguồn, khoảng 30 phút/tuần.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Đưa ra 3 top 3 problem cho nhóm để debate|  Nhóm có nhiều candidate về reporting/workflow |
| Pitch Problem Card | Tôi đã propose problem về Task Decomposition & Planning | Gom cụm được những câu hỏi có cùng chủ đề |
| Challenge bài của bạn khác | Đặt câu hỏi làm rõ về bài bug report của Khang và làm rõ về scope của Duyên | Topic của Duyên được làm rõ và được chọn làm pitch |
| Gom trùng / cluster | Gom idea của bạn Duy, Thanh, Thành vào nhóm tasks management; và idea của Duyên, Khang, Đăng thành nhóm resource management | Giúp nhóm hiểu rõ hơn về các chủ đề dưới dạng 1 nhóm tasks lớn |
| Chọn candidate problem | Nêu ra tiêu chí chọn gồm các tính chất như dễ bảo vệ, dễ hiểu, tính impact cao | giúp nhóm chọn được topic |
| Validation / research | Khảo sát tính năng và giới hạn của các công cụ Deep Research (ChatGPT, Gemini, Perplexity) đối chiếu với quy trình research thực tế | Giúp nhóm nhận ra các công cụ hiện có đã làm tốt tìm kiếm và trích dẫn nguồn, từ đó chốt No-Go với việc tự build search engine mà chỉ tập trung vào workflow chuẩn hóa SWOT |
| Workflow nhóm | Cùng nhóm phân rã current workflow thành 5 bước với baseline 90', chỉ ra bottleneck tại bước đọc/lọc (30') và thiết kế future state 3 bước (25–35') | Xác lập rõ human boundary ở bước review (15') và cơ chế fallback nếu AI phân loại sai hoặc thiếu nguồn kiểm chứng |
| Problem Statement | Phản biện bản v0, đề xuất siết chặt tiêu chí thành công với metric truy vết nguồn gốc (100% claim có citation) và xác định boundary nghiêm ngặt | Chuyển hóa Problem Statement từ v0 sang v1 chặt chẽ, loại bỏ rủi ro hallucination và cấm AI tự chốt kết luận chiến lược |
| Rule / Workflow / Agent | Phân tích bài toán theo ma trận độ mơ hồ/phức tạp, lập luận phản đối dựng Agent tự chủ để chọn mức AI-assisted Workflow | Nhóm thống nhất không làm Agent phức tạp, giữ đúng chuỗi nghiệp vụ tuần tự và kiểm soát được rủi ro |
| Decision | Cùng nhóm xây dựng 4 acceptance gates định lượng cho pilot (thời gian, truy vết nguồn, độ chính xác phân loại SWOT, thời gian review) và kịch bản Rollback | Nhóm có kế hoạch pilot 2 case rõ ràng, có tiêu chuẩn nghiệm thu định lượng và điểm dừng an toàn |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là kéo nhóm thoát khỏi bẫy "Agent tự chủ" để chốt giải pháp AI-assisted Workflow thực tế, đồng thời thiết lập 4 acceptance gates định lượng nghiêm ngặt (đặc biệt là gate 100% claim phải truy vết được nguồn và human review ≤ 15 phút).
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý phân tích các bottleneck hàng tuần và lượng hóa theo 4 lăng kính cho bối cảnh sinh viên làm khóa luận AI và học VinAI | Giúp bóc tách các nhóm việc (literature review vs training log) và gợi ý cách đo thời gian cụ thể (90–120 phút) | Đưa ra các pain hời hợt hoặc không sát thực tế cá nhân (như format nộp lab, mentor nhận xét) | Loại bỏ các ý không phải pain thật; giữ lại 5 problem gắn liền với công việc hàng tuần của mình |
| Problem Card | Phản biện Card #2 (Task Decomposition) và ước lượng độ khả thi của workflow | Chỉ ra điểm yếu: AI không thể tự hiểu độ phức tạp kỹ thuật nếu thiếu bối cảnh tài nguyên (GPU limit, debug) | Cho rằng prompt thông thường có thể tự sinh ra to-do list tối ưu mà không cần framework kỹ thuật | Bổ sung nhãn bối cảnh ([GPU wait], [Deep Work]) và quy định bắt buộc 8 phút con người review |
| Workflow | Gợi ý breakdown các bước chuẩn trong quy trình market research và ước lượng thời gian từng khâu | Liệt kê đầy đủ chuỗi logic từ xác định scope, tìm kiếm, đọc lọc đến tổng hợp SWOT | Gộp chung bước đọc/lọc với phân tích SWOT thành một khối "AI tự làm hết trong 5 phút" rất ảo tưởng | Tách bước đọc & lọc thành bottleneck riêng (30 phút) và cố định bước human review (15 phút) ở future state |
| Research | Khảo sát tính năng và hạn chế của các giải pháp Deep Research hiện nay (ChatGPT, Gemini, Perplexity) | Tổng hợp nhanh điểm mạnh về search và truy xuất link tài liệu chính thức của từng công cụ | Đưa ra các tuyên bố tiếp thị phóng đại ("tự động hóa hoàn toàn research") mà bỏ qua rủi ro sai context kinh doanh | Chỉ chọn lọc tài liệu chính thức, nhận diện khoảng trống về phân loại SWOT để định vị giá trị của nhóm |
| Problem Statement | Đóng vai critic phản biện các điểm mơ hồ trong Problem Statement v0 | Nhận ra PS v0 chỉ đo thời gian mà thiếu đo chất lượng, và cụm từ "AI research" dễ bị hiểu lầm là Agent | Đề xuất sửa lại câu chữ theo hướng học thuật chung chung và thêm các chỉ số viễn vông khó đo lường | Giữ nguyên văn phong thực chiến, thêm metric kiểm chứng nguồn (100% claim có citation) và boundary cấm AI tự publish |
| Rule / Workflow / Agent | So sánh tính khả thi giữa Rule, Workflow và Agent cho bài toán xử lý thông tin đa nguồn | Phân tích rõ sự khác biệt giữa filtering theo từ khóa và semantic reasoning khi tổng hợp SWOT | Thiên vị Agent, gợi ý kiến trúc multi-agent phức tạp không cần thiết cho quy trình tuần tự | Bác bỏ phương án Agent rườm rà; bảo vệ giải pháp Workflow có human-in-the-loop để đảm bảo kiểm soát |
| Decision | Gợi ý các tiêu chí nghiệm thu cho giai đoạn pilot và cơ chế kiểm soát rủi ro | Gợi ý các khía cạnh cần đo lường (thời gian, tỷ lệ lỗi, công sức người review) | Đưa ra các tiêu chí chung chung, mang tính định tính (như "kết quả đạt yêu cầu", "người dùng hài lòng") | Cụ thể hóa thành 4 acceptance gates định lượng (≤35', 100% nguồn kiểm được, ≤20% item sai, review ≤15') kèm cơ chế rollback |

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
Khi lắng nghe top 3 problem của các thành viên khác, đặc biệt là bài toán tổng hợp SWOT của Duyên, tôi nhận ra một bài toán hay không nhất thiết phải nghe thật "đao to búa lớn" hay mang nặng tính kỹ thuật như việc bóc tách benchmark paper của tôi, mà quan trọng nhất là phải có workflow quan sát được và baseline thời gian đo lường rõ ràng. Ban đầu, tôi khá tâm đắc với đề xuất Task Decomposition của mình, nhưng sau khi bị nhóm challenge về tính mơ hồ và việc AI thiếu context tài nguyên cá nhân, tôi đã chủ động thay đổi quan điểm và đồng thuận dồn lực cho bài toán SWOT vì nó có bottleneck cụ thể và dễ so sánh giá trị giữa các giải pháp. Trong quá trình thảo luận ở Phase 6, nhóm tôi đã có lúc bị cuốn vào tâm lý solution-first khi một số bạn hào hứng đề xuất dựng một Multi-Agent tự chủ có thể tự tìm kiếm web, tự backtrack và tự xuất báo cáo cho tự động hoàn toàn. Tôi đã chủ động phản biện ý tưởng này bằng cách chỉ ra rằng một Agent tự chủ rất khó kiểm soát chất lượng, chi phí cao và dễ ảo giác trong khi chuỗi nghiệp vụ của người làm research về bản chất đi theo đường thẳng cố định hàng tuần. Nhờ đó, cả nhóm đã cùng thống nhất kéo bài toán về mức AI-assisted Workflow có human-in-the-loop để vừa tận dụng năng lực tóm tắt của AI vừa đảm bảo tính an toàn. Đối với cá nhân tôi, điều khó khăn và thách thức nhất khi viết Problem Statement chính là việc xác lập Boundary thay vì chỉ dừng lại ở Success Metric. Việc đưa ra con số kỳ vọng giảm thời gian từ 90 phút xuống <= 35 phút tương đối trực quan, nhưng để vạch rõ lằn ranh AI được phép can thiệp đến đâu và bắt buộc phải dừng lại ở đâu lại đòi hỏi sự mổ xẻ rất kỹ lưỡng. Chúng tôi đã phải tranh luận nhiều lần để thống nhất rằng AI chỉ được đóng vai trò trợ lý thu thập evidence và draft SWOT có citation, tuyệt đối không được tự ý đưa ra kết luận chiến lược hay publish output khi chưa qua khâu review của người thật. Dấu ấn thực sự của tôi trong artifact cuối nằm ở việc kéo nhóm về bài toán thực tế và cùng xây dựng 4 tiêu chí định lượng cho (đặc biệt là tiêu chí 100% claim phải truy vết được nguồn) kèm phương án rollback rõ ràng. Nếu được làm lại, tôi sẽ challenge nhóm quyết liệt hơn ngay từ Phase 4 trong việc thực hiện phỏng vấn nhanh 1–2 người làm research thực tế thay vì chỉ dựa vào phân tích công cụ và trải nghiệm cá nhân của thành viên, giúp baseline 90 phút càng thêm vững chắc.
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

