# 02 — Group Problem Statement (Bản nộp nhóm)

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | 
| --: | --------- | ----------- | 
|   1 | Duy       | 2A202602723 | 
|   2 | Duyên     | 2A202603001 | 
|   3 | Thành     | 2A202602647 | 
|   4 | Đăng      | 2A202602591 | 
|   5 | Khang     | 2A202602974 | 
|   6 | Thanh     | 2A202602841 | 

**Candidate problem nhóm chọn (1 câu):**

Người phụ trách research khách hàng/thị trường mất khoảng 90 phút mỗi tuần để xác định nhu cầu thông tin, tìm nhiều nguồn, đọc và lọc dữ liệu, phân loại thành SWOT rồi tổng hợp báo cáo; bottleneck lớn nhất là bước đọc và lọc thông tin từ nhiều nguồn, khoảng 30 phút/tuần.

---

## Phase 3 — Group Convergence: từ 18 candidates về 1

### 3.1. Trình bày top 3 mỗi người

|  # | Người đưa ra | Candidate problem                                                                                          | Người gặp vấn đề                          | Điểm nghẽn                                                                | Cảm nhận nhanh của nhóm                                                 |
| -: | ------------ | ---------------------------------------------------------------------------------------------------------- | ----------------------------------------- | ------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
|  1 | Duy          | Mỗi chiều thứ Hai phải mở log training, tổng hợp Loss/F1/Accuracy và gõ slide/doc báo cáo tiến độ cho GVHD | Sinh viên/nghiên cứu viên báo cáo tiến độ | Gom metrics và context từ nhiều log/file rải rác rồi chuyển thành báo cáo | Workflow hẹp, lặp lại, dễ đo; có khả năng tự động hóa cao               |
|  2 | Duy          | Phân rã mục tiêu nghiên cứu lớn thành các sub-task kỹ thuật theo tuần                                      | Cá nhân/nhóm nghiên cứu                   | Chuyển mục tiêu mơ hồ thành task đủ nhỏ, đúng ưu tiên và phù hợp context  | Có giá trị nhưng phụ thuộc nhiều context và judgement                   |
|  3 | Duy          | Bóc tách, trực quan hóa và so sánh benchmark SOTA từ 3–4 paper                                             | Người làm research AI                     | Đọc bảng PDF, chuẩn hóa số liệu và so sánh giữa các paper                 | Pain rõ, nhưng độ chính xác khi đọc bảng phức tạp là rủi ro lớn         |
|  4 | Duyên        | Email → tìm deadline, lịch học, việc cần làm                                                               | Sinh viên/người nhận nhiều email          | Đọc và lọc email để nhận ra action item/deadline                          | Lặp lại và rõ, nhưng có thể giải phần lớn bằng rule/calendar            |
|  5 | Duyên        | Research khách hàng → SWOT                                                                                 | Người phụ trách customer/market research  | Đọc và lọc thông tin từ nhiều nguồn trước khi phân loại SWOT              | Baseline 90 phút/tuần, bottleneck rõ, phù hợp để so Rule/Workflow/Agent |
|  6 | Duyên        | Xem bài giảng → tổng hợp kiến thức để ôn tập                                                               | Sinh viên                                 | Chắt lọc kiến thức từ video/slide/ghi chú thành bản ôn tập                | Pain phổ biến nhưng overlap với nhiều candidate học tập khác            |
|  7 | Thành        | Xem video bài giảng mất nhiều thời gian                                                                    | Sinh viên                                 | Phải xem tuần tự để tìm phần quan trọng                                   | Impact thời gian rõ nhưng problem còn rộng nếu không bóc chi tiết       |
|  8 | Thành        | Chép và tổng hợp kiến thức bài giảng                                                                       | Sinh viên                                 | Chuyển nội dung bài học thành note cô đọng; mất 20–30 phút/lần            | Measurable, workflow rõ, AI hỗ trợ tốt                                  |
|  9 | Thành        | Update status/tasks trên Jira                                                                              | Thành viên project                        | Chuyển trạng thái công việc thực tế thành cập nhật Jira đều đặn           | Có thể tự động hóa; cần làm rõ integration và thời gian thật            |
| 10 | Đăng         | Đọc paper để hiểu thuật toán rồi code lại mất thời gian và dễ sai                                          | Sinh viên/nghiên cứu viên kỹ thuật        | Hiểu đúng thuật toán và chuyển thành implementation chạy đúng             | Impact cao nhưng phạm vi rộng, rủi ro correctness lớn                   |
| 11 | Đăng         | Tổng hợp các công việc đã làm từng tuần                                                                    | Sinh viên/người làm research              | Nhớ và lọc những việc đáng báo cáo rồi viết lại rõ ràng                   | Workflow rõ, overlap với candidate báo cáo tiến độ của Duy              |
| 12 | Đăng         | Xây dựng kế hoạch học tập từ nhiều môn/tài liệu dễ bị rối và quên                                          | Sinh viên                                 | Ưu tiên việc học theo deadline/độ khó/tầm quan trọng                      | Pain thật nhưng tiêu chí ưu tiên khá chủ quan                           |
| 13 | Khang        | Nhận và chỉnh sửa đồ án từ feedback của giảng viên                                                         | Sinh viên làm đồ án                       | Hiểu feedback và chuyển thành các thay đổi cụ thể                         | Actor rõ nhưng khả năng cải thiện chưa rõ                               |
| 14 | Khang        | Nhận report từ tester cho dự án game                                                                       | Developer/project team                    | Đọc, triage và chuyển report biến thiên thành issue/action                | Workflow có thể rõ nhưng data access và độ biến thiên là rủi ro         |
| 15 | Khang        | Summarize report                                                                                           | Thành viên/lead cần đọc nhiều report      | Chuẩn hóa và tóm tắt report có độ dài/cấu trúc khác nhau                  | AI fit tốt nhưng problem còn chung nếu không chốt loại report           |
| 16 | Thanh        | Requirement assignment/project nằm rải rác ở nhiều nguồn, phải tự tổng hợp checklist                       | Sinh viên                                 | Đối chiếu LMS/slide/chat/rubric thành danh sách requirement đáng tin      | Actor và workflow rõ; có thể process fix nếu có single source of truth  |
| 17 | Thanh        | Scan nhiều paper để biết paper nào thực sự liên quan và đáng đọc sâu                                       | Sinh viên/nghiên cứu viên                 | Đánh giá semantic relevance trước khi quyết định đọc sâu                  | Lặp lại, tốn thời gian; AI fit khá tốt nhưng đã có nhiều tool           |
| 18 | Thanh        | Theo dõi lịch/deadline/thay đổi chương trình AI Thực Chiến từ nhiều thông báo                              | Người tham gia chương trình               | Nhận ra announcement nào làm thay đổi lịch/action item                    | Workflow hẹp; nhiều khả năng rule/shared calendar đã đủ                 |

### 3.2. Gom trùng / cluster

| Cluster                                       | Candidates included                      | Pattern chung                                                                     | Ghi chú                                                                 |
| --------------------------------------------- | ---------------------------------------- | --------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| A — Research & evidence synthesis             | Duy #3; Duyên #2; Đăng #1; Thanh #2      | Tìm/đọc nhiều nguồn, lọc evidence rồi chuyển thành insight kỹ thuật/kinh doanh    | Có semantic judgement nên Rule đơn thuần thường khó đủ                  |
| B — Learning & academic information digestion | Duyên #1, #3; Thành #1, #2; Thanh #1, #3 | Nội dung học tập/deadline/requirement phân tán, người học phải tự đọc và tổng hợp | Một phần có thể giải bằng process, shared calendar hoặc source-of-truth |
| C — Reporting & project/status tracking       | Duy #1; Thành #3; Đăng #2; Khang #2, #3  | Chuyển log/status/report thô thành bản cập nhật dễ dùng cho người khác            | Workflow lặp lại và có đầu ra tương đối chuẩn                           |
| D — Planning & action decomposition           | Duy #2; Đăng #3; Khang #1                | Chuyển mục tiêu/feedback/nhiều việc thành kế hoạch hoặc action cụ thể             | Độ mơ hồ cao, phụ thuộc context và judgement cá nhân                    |

### 3.3. Shortlist

| Candidate                                | Vì sao vào shortlist                                                                                                          | Rủi ro / điều chưa rõ                                                                            |
| ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| Research khách hàng → SWOT               | Có baseline 90 phút/tuần; workflow 5 bước và bottleneck 30 phút rõ; output SWOT có cấu trúc; so sánh Rule/Workflow/Agent được | Chất lượng phụ thuộc nguồn; AI có thể hallucinate hoặc phân loại SWOT không hợp lý               |
| Training logs → báo cáo tiến độ cho GVHD | Tần suất hàng tuần; metrics đầu vào rõ; đầu ra report/slide cụ thể; dễ đo time saving                                         | Log nằm ở nhiều nền tảng; cần access/integration; narrative có thể cần context mà model không có |
| Tổng hợp requirement assignment/project  | Actor rộng và dễ hiểu; workflow có thể quan sát; hậu quả bỏ sót requirement rõ; có thể thử cả non-AI và AI                    | Chưa có baseline thời gian/số lỗi; có thể process fix bằng single source of truth                |

### 3.4. Score để đồng thuận

| Candidate                               | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain |   Tổng |
| --------------------------------------- | -------: | ----------: | ---------------: | -------------: | ------------: | -----------------: | ---------------: | -----: |
| Research khách hàng → SWOT              |        5 |           5 |                4 |              5 |             5 |                  5 |                5 | **34** |
| Training logs → báo cáo tiến độ         |        5 |           5 |                4 |              4 |             5 |                  4 |                5 | **32** |
| Tổng hợp requirement assignment/project |        5 |           5 |                3 |              4 |             5 |                  5 |                5 | **32** |

**Candidate nhóm chọn:**

Research khách hàng/thị trường → tổng hợp thành SWOT.

**Vì sao chọn:**

Candidate có actor và workflow đủ hẹp để quan sát, với baseline hiện tại khoảng 90 phút/tuần và bottleneck cụ thể 30 phút ở bước đọc, lọc thông tin. Bài toán cũng có đầu ra tương đối rõ là một bản SWOT, nhưng vẫn cần semantic judgement nên tạo được phép thử tốt giữa Rule, Workflow và Agent. Nhiều bước hiện tại là thao tác tìm kiếm/tổng hợp lặp lại, trong khi quyết định cuối về ý nghĩa chiến lược vẫn nên thuộc về người thật. Candidate vì vậy vừa có tiềm năng tiết kiệm thời gian rõ, vừa có boundary và rủi ro AI đủ cụ thể để phân tích trong lab.

**Vì sao KHÔNG chọn các candidate còn lại:**

* **Training logs → báo cáo tiến độ:** candidate rất mạnh và measurable, nhưng phụ thuộc quyền truy cập nhiều nguồn log và integration cụ thể. Phần metrics cũng có thể được giải đáng kể bằng script/rule trước khi cần AI, nên nhóm ưu tiên candidate SWOT để kiểm tra giá trị AI ở bước đọc hiểu/ngữ nghĩa.

* **Tổng hợp requirement assignment/project:** pain có khả năng phổ biến nhưng nhóm chưa có baseline đủ chắc. Một thay đổi quy trình như single source of truth hoặc checklist chuẩn có thể loại bỏ phần lớn pain mà không cần AI.

**Disagreement:**

Nhóm không giữ lại disagreement nào sau vòng scoring. Concern lớn nhất là liệu các công cụ AI research hiện có đã giải gần hết bài toán hay chưa. Nhóm chốt **không xây một research agent mới**; phần đáng kiểm chứng chỉ là một **AI-assisted Workflow** chuẩn hóa đầu ra SWOT, bắt buộc có source traceability và human review. Concern này được chuyển thành boundary của solution thay vì là lý do loại candidate.

---

## Phase 4 — Quick Validation + Research
### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | | | | |
| Survey / poll | | | | |
| Log / ticket / review (nếu có) | | | | |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text

```

### 4.2. Research giải pháp đã có

| Nguồn / tool / case   | Link                                        | Họ giải quyết bước nào?                                                              | Điểm mạnh                                                                             | Khoảng trống / rủi ro                                             | Bài học cho nhóm                                             |
| --------------------- | ------------------------------------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ------------------------------------------------------------ |
| ChatGPT Deep Research | https://help.openai.com/en/articles/10500283 | Lập kế hoạch research, tìm/đọc nhiều nguồn và tổng hợp report có citation/source links | Có research plan, có thể giới hạn/ưu tiên nguồn và tạo report truy vết được | Không đảm bảo SWOT classification đúng với context kinh doanh; vẫn cần human verify | Tận dụng research capability có sẵn, không build search/research engine mới |
| Gemini Deep Research | https://support.google.com/gemini/answer/15719111?hl=en | Research nhiều nguồn, lập research plan và tổng hợp report | Dùng Google Search mặc định và có thể bổ sung nguồn như Drive/Gmail/file | Strategic interpretation và SWOT classification vẫn cần người review | Tách rõ bước evidence gathering khỏi bước strategic judgement |
| Perplexity Research | https://www.perplexity.ai/help-center/en/articles/10738684-what-is-research-mode | Tự search nhiều vòng, đọc nguồn, reasoning và tổng hợp thành report | Nhanh ở source discovery + synthesis, phù hợp để tạo evidence pack ban đầu | Research tốt không đồng nghĩa phân loại SWOT đúng hoặc đủ business context | Giá trị khác biệt phải nằm ở SWOT schema, traceability và review workflow |

**Research takeaway:**

Các công cụ research AI hiện có đã giải phần lớn capability nền tảng: lập kế hoạch tìm kiếm, đọc nhiều nguồn, tổng hợp và dẫn nguồn. Vì vậy **No-Go đối với ý tưởng build một research agent/web crawler riêng từ đầu**. Nhóm chỉ **Go** với lớp workflow phía trên: xác định scope → AI research có nguồn → AI draft SWOT theo schema → human verify → final SWOT. Giá trị cần kiểm chứng không phải “AI có search được web không”, mà là workflow này có giảm thời gian từ 90 phút xuống ≤35 phút mà vẫn giữ được khả năng kiểm chứng nguồn và chất lượng phân loại SWOT hay không.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

```text

CURRENT STATE — ~90 phút/tuần

[1 Xác định thông tin cần tìm: 10' - người phụ trách research]

→ [2 Search nhiều nguồn: 25' - người phụ trách research]

→ [3 Đọc & lọc thông tin: 30' - người phụ trách research]  <-- BOTTLENECK

→ [4 Phân tích + phân loại SWOT: 15' - người phụ trách research]

→ [5 Tổng hợp + review: 10' - người phụ trách research]

```

| Bước | Actor                                    | Input                                              | Output                              | Thời gian / tần suất | Ghi chú                                            |
| ---: | ---------------------------------------- | -------------------------------------------------- | ----------------------------------- | -------------------- | -------------------------------------------------- |
|    1 | Người phụ trách customer/market research | Mục tiêu research, đối tượng khách hàng/thị trường | Danh sách câu hỏi/thông tin cần tìm | ~10'/tuần            | Định nghĩa scope                                   |
|    2 | Người phụ trách research                 | Câu hỏi, keyword, nguồn web/tài liệu               | Tập link/tài liệu thô               | ~25'/tuần            | Search nhiều nguồn                                 |
|    3 | Người phụ trách research                 | Link/tài liệu thô                                  | Facts/insights đã lọc               | ~30'/tuần            | **Bottleneck:** đọc nhiều nội dung không đồng nhất |
|    4 | Người phụ trách research                 | Facts/insights đã lọc                              | Draft SWOT                          | ~15'/tuần            | Cần semantic judgement                             |
|    5 | Người phụ trách research/team            | Draft SWOT + nguồn                                 | Bản SWOT cuối                       | ~10'/tuần            | Review logic và diễn đạt                           |

**Bottleneck chính:**

Bottleneck nằm ở bước 3: đọc và lọc thông tin, chiếm khoảng 30/90 phút của toàn workflow. Input đến từ nhiều nguồn và có cấu trúc/chất lượng khác nhau nên người thực hiện phải tự đọc, đánh giá relevance và giữ lại evidence trước khi mới có thể phân loại SWOT. Đây là phần vừa tốn thời gian vừa có yếu tố hiểu ngữ nghĩa.

### 5.2. Future workflow bản nhóm

```text

FUTURE STATE — kỳ vọng ~25–35 phút/tuần

[1 AI research nhiều nguồn: ~10' - AI]

→ [2 AI tóm tắt + draft SWOT + dẫn nguồn: ~10' - AI]

→ [3 Human review & chỉnh sửa: ~15' - HUMAN BOUNDARY]

Fallback:

Nếu AI thiếu nguồn, dẫn nguồn không kiểm được hoặc phân loại SWOT không hợp lý

→ quay lại nguồn gốc để kiểm tra, bổ sung thủ công và sửa SWOT.

```

| Metric                 |                                         Trước |                                      Sau kỳ vọng | Cách đo                             |
| ---------------------- | --------------------------------------------: | -----------------------------------------------: | ----------------------------------- |
| Tổng thời gian         |                                 ~90 phút/tuần |                                 ~25–35 phút/tuần | Bấm giờ end-to-end                  |
| Số bước                |                                             5 |                                                3 | Đếm step                            |
| Số bước thủ công chính |                                             5 |                              1 bước review chính | Ghi actor từng step                 |
| Bottleneck chính       |                                Đọc & lọc ~30' |                      Human verify/chỉnh sửa ~15' | Bấm giờ bottleneck                  |
| Risk mới | Không có hallucination AI nhưng tốn thời gian | Hallucination, nguồn kém, SWOT misclassification | Log claim/source phải sửa hoặc loại |

Nếu đạt 25–35 phút, workflow giảm khoảng **55–65 phút/tuần**, tương đương khoảng **61–72%** thời gian so với baseline 90 phút.

### 5.3. Problem Statement v0

| Field              | Nội dung                                                                                                                                                                                    |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**          | Người phụ trách research khách hàng/thị trường theo tuần cho project/nhóm. Người này cần biến thông tin từ nhiều nguồn thành một bản SWOT ngắn gọn để phục vụ thảo luận hoặc ra quyết định. |
| **Workflow**       | Actor xác định thông tin cần tìm, search nhiều nguồn, đọc/lọc thông tin, phân loại SWOT rồi tổng hợp và review. Toàn bộ workflow mất khoảng 90 phút/tuần qua 5 bước.                        |
| **Bottleneck**     | Bước đọc và lọc thông tin mất khoảng 30 phút/tuần và là bottleneck lớn nhất. Nguồn có format/chất lượng khác nhau nên actor phải tự quyết định đâu là evidence liên quan.                   |
| **Impact**         | Khoảng 1,5 giờ mỗi tuần bị dùng cho workflow research lặp lại. Thời gian này làm chậm việc chuyển từ raw information sang insight/decision.                                                 |
| **Success Metric** | Giảm tổng thời gian từ ~90 xuống ~25–35 phút/tuần, đồng thời giữ khả năng truy ngược các claim quan trọng về nguồn.                                                                         |
| **Boundary**       | AI được tìm nguồn, tóm tắt và tạo draft SWOT có citation. AI không tự chốt kết luận chiến lược hoặc publish output khi chưa qua người thật kiểm tra.                                        |

**AI phản biện v0:**

* **Field mơ hồ:** chất lượng đầu ra chưa thể chỉ đo bằng thời gian; “AI research nhiều nguồn” cũng có thể bị hiểu thành Agent tự chủ.

* **Sửa:** thêm source traceability, human review bắt buộc và xác định product-level solution là workflow cố định.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp

* Độ mơ hồ: **Cao** — cùng một evidence có thể có nhiều cách diễn giải hợp lý; SWOT phụ thuộc context.

* Độ phức tạp: **Cao** — nhiều nguồn và 3+ bước phụ thuộc nhau.

**Bài toán nằm ở ô:**

Độ mơ hồ cao × độ phức tạp cao.

**Vì sao:**

Bài toán cần tổng hợp evidence không cấu trúc từ nhiều nguồn và tạo một draft mang tính diễn giải. Tuy nhiên nghiệp vụ vẫn đi theo một chuỗi tương đối cố định mỗi tuần, nên độ phức tạp cao không đồng nghĩa bắt buộc phải dùng Agent.

### 6.1. So sánh Rule / Workflow / Agent

| Mức          | Phương án                                                                             | Khi nào đủ                                                      | Rủi ro                                               | Chọn?                          |
| ------------ | ------------------------------------------------------------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------- | ------------------------------ |
| **Rule**     | Query/keyword cố định; lọc domain/date; mapping một số field vào SWOT                 | Khi nguồn ít, có cấu trúc ổn định                               | Không hiểu context; bỏ sót synonym/quan hệ ngữ nghĩa | Không chọn làm giải pháp chính |
| **Workflow** | User xác định scope → AI research → AI tóm tắt + draft SWOT + citation → human review | Khi quy trình lặp lại, các bước rõ nhưng cần semantic reasoning | Hallucination, nguồn kém, misclassification          | **Chọn**                       |
| **Agent**    | AI tự phân rã câu hỏi, chọn query/tool/source tiếp theo và tự backtrack               | Khi research rất mở và cần branching động                       | Khó kiểm soát, cost cao, khó reproduce               | Chưa cần ở pilot               |

**5 câu hỏi chốt:**

1. **Rule có giải được 70–80% case không?** Không. Rule hỗ trợ filtering nhưng không đủ để đọc hiểu và phân loại SWOT theo context.

2. **Các bước có đi thẳng một đường không?** Phần lớn có: research → synthesis/SWOT → review.

3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?** Chưa. Mục tiêu và output tương đối cố định.

4. **Nếu AI sai, ai phát hiện và sửa?** Người phụ trách research phát hiện ở bước human review, kiểm citation/source rồi sửa.

5. **Có hạ được từ Agent → Workflow → Rule không?** Hạ Agent xuống Workflow được; hạ toàn bộ xuống Rule thì mất phần semantic reasoning.

**Mức chọn:**

**Workflow**

**Vì sao chọn:**

Workflow phù hợp vì chuỗi nghiệp vụ rõ và lặp lại hàng tuần, trong khi hai bước đầu có thể được AI tăng tốc đáng kể. AI hỗ trợ research/synthesis nhưng quyết định SWOT cuối vẫn nằm ở người thật, tạo boundary dễ kiểm soát. Mức này lấy được giá trị AI mà không phải chịu thêm độ phức tạp và rủi ro của Agent tự chủ.

**Vì sao không chọn mức đơn giản hơn:**

Rule có thể giảm một phần thời gian search bằng keyword/domain/date filter nhưng không xử lý tốt nội dung không cấu trúc và semantic classification. Nếu chỉ dùng Rule, bottleneck đọc/lọc 30 phút vẫn còn phần lớn.

### 6.2. Problem Statement v1

| Field                            | Nội dung                                                                                                                                                                               |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                        | Người phụ trách customer/market research hàng tuần cho một project/nhóm và cần tạo SWOT dựa trên evidence từ nhiều nguồn.                                                              |
| **Workflow**                     | Current: xác định scope (10') → search (25') → đọc/lọc (30') → SWOT (15') → review (10'), tổng ~90'. Future: AI research (~10') → AI draft SWOT có nguồn (~10') → human review (~15'). |
| **Bottleneck**                   | Đọc và lọc thông tin đa nguồn là bottleneck lớn nhất, ~30 phút/tuần.                                                                                                                   |
| **Impact**                       | Workflow tiêu tốn ~90 phút/tuần. Nếu đạt 25–35 phút, tiết kiệm 55–65 phút/tuần (~61–72%).                                                                                              |
| **Success Metric**               | (1) Tổng thời gian ≤35 phút/tuần; (2) claim quan trọng giữ lại phải có nguồn kiểm được; (3) human review mục tiêu quanh ~15 phút và không phải đọc lại gần như toàn bộ nguồn.          |
| **Boundary**                     | AI được research, summarize, draft SWOT và gắn nguồn. AI không tự publish/chốt chiến lược và không được giữ claim không verify được.                                                   |
| **AI intervention point**        | Sau khi scope research được xác định và trước final review.                                                                                                                            |
| **Mức chọn**                     | **Workflow** — các bước nghiệp vụ cố định và có human boundary rõ.                                                                                                                     |
| **Rủi ro & người thật kiểm tra** | Hallucination/source kém và SWOT classification sai context. Người phụ trách research kiểm citation/source và sửa/xóa item trước khi dùng.                                             |

### 6.3. Final decision

| Câu hỏi                               | Yes / Not Yet / No               | Ghi chú                                                                  |
| ------------------------------------- | -------------------------------- | ------------------------------------------------------------------------ |
| Actor + workflow rõ chưa?             | **Yes**                          | Actor và workflow 5 bước đã xác định                                     |
| Baseline + metric đo được chưa?       | **Yes**                          | Baseline ~90 phút/tuần, có breakdown từng bước                           |
| Data/input đủ dùng chưa?              | **Yes**                          | Chủ yếu là câu hỏi research và nguồn web/tài liệu có thể truy cập        |
| AI sai, hậu quả chấp nhận được không? | **Yes**                          | Output chỉ là draft và phải được review trước khi dùng                   |
| Có người review/owner không?          | **Yes**                          | Người phụ trách research là owner/reviewer cuối                          |
| Có cách non-AI đơn giản hơn không?    | **Yes, nhưng chỉ giải một phần** | Filter/template giúp search nhưng không giải bottleneck semantic reading |

**Decision:**

**Go — nhưng Go ở mức pilot một AI-assisted Workflow, không build Agent riêng.**

**Lý do:**

Pain có baseline 90 phút/tuần và bottleneck 30 phút rõ. Existing tools đã cung cấp research + citation nên pilot không cần build hạ tầng search riêng; nhóm chỉ cần chuẩn hóa prompt/schema SWOT và bước human review. Quyết định **Go** được chấp nhận nếu pilot đạt đồng thời ba gate: **≤35 phút end-to-end**, **100% factual claim được giữ lại có nguồn kiểm được**, và **≤20% SWOT items phải sửa/xóa do AI phân loại sai context**. Nếu không đạt, solution không được mở rộng.

**Pilot nhỏ nhất:**

Chạy **2 research cases** có độ rộng tương đương trong cùng một tuần: 1 case theo workflow hiện tại để đối chứng và 1 case theo AI-assisted Workflow.

**Acceptance gates:**

1. **Time gate:** AI-assisted workflow ≤35 phút end-to-end, tức giảm ít nhất ~61% so với baseline 90 phút.
2. **Traceability gate:** 100% factual claim được giữ trong final SWOT có source link kiểm lại được.
3. **Quality gate:** ≤20% SWOT items trong AI draft phải đổi quadrant, sửa nội dung trọng yếu hoặc bị xóa vì sai context.
4. **Human-effort gate:** human review ≤15 phút và reviewer không phải đọc lại phần lớn tài liệu nguồn.

**Pass:** đạt cả 4 gate → tiếp tục dùng Workflow cho các research case tương tự.  
**Fail:** trượt bất kỳ gate nào → không scale; chuyển sang nhánh Not Yet và sửa workflow/prompt/source policy trước khi test lại.

**Nếu Not Yet:**

Chuyển decision từ Go → **Not Yet** ngay khi pilot trượt ít nhất một acceptance gate nhưng lỗi còn có khả năng sửa ở workflow, ví dụ source policy chưa tốt, prompt SWOT chưa rõ, hoặc human review >15 phút. Nhóm chỉ sửa **một biến mỗi vòng** (nguồn, schema/prompt hoặc review checklist), chạy lại tối đa **2 vòng pilot** và so với cùng baseline.

**Nếu No-Go:**

Chuyển decision thành **No-Go cho AI-assisted SWOT workflow** nếu sau tối đa 2 vòng chỉnh sửa vẫn xảy ra một trong các điều kiện: (1) thời gian end-to-end >45 phút; (2) không đảm bảo 100% factual claim giữ lại có nguồn kiểm được; (3) >30% SWOT items vẫn phải sửa/xóa vì sai context; hoặc (4) reviewer phải đọc lại phần lớn nguồn nên AI không tạo ra tiết kiệm thực tế. Khi No-Go, dùng phương án non-AI: research checklist + danh sách nguồn ưu tiên + SWOT template chuẩn.

**Exit / rollback:**

Rollback ngay về manual research + standardized checklist/SWOT template nếu pilot chạm điều kiện No-Go hoặc xuất hiện claim không truy được nguồn nhưng vẫn lọt vào bản dùng để ra quyết định. Không lưu/publish SWOT do AI tạo trực tiếp; chỉ **final SWOT đã qua human review** mới được dùng. Đây là boundary cố định của solution, không phải tùy chọn.

---
### Self-check nộp phần 02

* [x] Có nhật ký hội tụ 18 → 1

* [x] Validation thực tế không áp dụng theo cập nhật BTC; không bịa quote/survey

* [x] Research có nguồn chính thức kiểm được

* [x] Workflow trước/sau có thời gian, bottleneck, boundary và fallback

* [x] Có PS v0 → v1, metric và boundary

* [x] Có so sánh Rule/Workflow/Agent

* [x] Có Decision Go + pilot + rollback
