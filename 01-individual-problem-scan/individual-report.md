# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Lê Anh Duy
- Mã học viên: 2A202602723
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): sinh viên năm cuối, đang vừa phải đi học VinAI thực chiến, vừa phải làm khóa luận tốt nghiệp. Nên công việc nhiều và khó quản lý.

- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): 
+ Họp để báo cáo tiến độ với giảng viên hướng dẫn
+ Đi học và làm lab VinAI
+ Làm research và chạy thực nghiệm cho đề tài khóa luận
+ Tổng hợp paper và đọc paper
+ Tổng hợp và phân chia tasks

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.


| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
| --- | --- | --- | --- | --- |
| 1 | Lặp lại | Chiều thứ Hai hằng tuần phải mở log training, tổng hợp metrics (Loss, F1, Accuracy) và gõ slide/doc báo cáo tiến độ cho GVHD | Duy, GVHD | Mất 90–120 phút/tuần; quy trình copy-paste số liệu thủ công lặp lại 100% |
| 2 | Tốn thời gian | Đọc lướt 5–7 paper arXiv/conference mỗi tuần để lọc ra paper có baseline/methodology áp dụng được cho đề tài | Duy | Mất 45–60 phút/paper (~4–5 tiếng/tuần); thường xuyên quá tải thông tin và đọc lan man |
| 3 | AI có thể tốt hơn | Bóc tách và so sánh bảng benchmark (SOTA) từ 3–4 paper liên quan vào mục Literature Review của khóa luận | Duy, GVHD | Mất 2–3 tiếng/lần trích xuất thủ công các bảng kết quả, đối chiếu dataset và metric tương ứng |
| 4 | AI có thể tốt hơn | Phân rã mục tiêu nghiên cứu lớn của đề tài thành các sub-tasks kỹ thuật cụ thể theo tuần cho nhóm/cá nhân | Duy, bạn làm chung | Tốn 60 phút thảo luận đầu tuần nhưng task phân chia vẫn mơ hồ, dễ trễ deadline sprint |
| 5 | Pain từ người khác | Bạn làm chung đồ án cập nhật tiến độ chậm, format kết quả không đồng nhất khiến Duy không thể ghép nối pipeline thực nghiệm | Duy, bạn làm chung | Tốn 30–45 phút nhắn tin hỏi lại tiến độ và format dữ liệu trước hạn chót |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Dựa trên bối cảnh sinh viên năm cuối làm khóa luận tốt nghiệp AI và học VinAI thực chiến, hãy phân tích các bottleneck hàng tuần và lượng hóa thành các problem scan có số liệu cụ thể theo 4 lăng kính.
- Ý dùng được: Tách bạch giữa việc đọc paper tổng quan và việc bóc tách bảng SOTA benchmark. Đo lường cụ thể thời gian tổng hợp log chạy mô hình thành báo cáo hàng tuần.
- Ý bỏ vì không phải pain thật: Chuyển đổi mã nguồn thực nghiệm (notebook/script) thành báo cáo kết quả theo format nộp lab tuần của VinAI; VHD / Mentor VinAI nhận xét code thực nghiệm hoặc draft báo cáo thiếu giải thích trực quan về error analysis


**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Chiều thứ Hai hằng tuần phải mở log training, tổng hợp metrics (Loss, F1, Accuracy) và gõ slide/doc báo cáo tiến độ cho GVHD | Vì bước này phải tổng hợp từ nhiều nguồn, các file log lưu rải rác ở các web khác nhau. Làm slide và báo cáo mất thời gian| Dùng AI tổng hợp báo cáo có đủ cô đọng hay nó bị ảo giác |
| 2 | Phân rã mục tiêu nghiên cứu lớn của đề tài thành các sub-tasks kỹ thuật cụ thể theo tuần cho nhóm/cá nhân| Vì khi vừa thực tập vừa nghiên cứu thì là 2 việc đều đòi hỏi thời gian và quy trình khác nhau. Các tasks cũng có tính chất khác nhau| AI chia tasks thì thiếu context và có thể chia tasks sai, không phù hợp |
| 3 | Bóc tách, trực quan hóa và so sánh benchmark (SOTA) từ 3–4 paper liên quan cho research |Đọc và lọc bảng kết quả từ PDF mất nhiều thời gian. Chỉ bóc tách số liệu vẫn khó so sánh; AI có thể trực quan hóa số liệu đó thành biểu đồ, giúp GVHD nhanh chóng nhận ra các xu hướng.|Khả năng đọc chính xác cấu trúc bảng phức tạp và nguy cơ AI sinh ra code visualization bị lỗi hoặc scale sai trục|

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Weekly report]

```text
Problem 1 câu: Chiều thứ Hai hằng tuần, Duy mất 90–120 phút thu thập log thực nghiệm phân tán từ nhiều nền tảng (Kaggle/Colab, server lab, local script) để tổng hợp metrics và viết báo cáo tiến độ dạng slide/doc cho GVHD, trong đó khâu vẽ biểu đồ và viết nhận xét phân tích lỗi (error analysis) tốn thời gian nhất.

Actor: Sinh viên, GVHD

Thời điểm / bối cảnh: Chiều thứ Hai hằng tuần, trước buổi họp sync tiến độ định kỳ với GVHD.

1. Đăng nhập các nền tảng training (Kaggle, Colab, Server lab) để tải log/checkpoint
2. Thu thập các chỉ số metrics (Train/Val Loss, Accuracy, F1-score) vào file nháp
3. Chụp màn hình hoặc export đồ thị learning curve
4. Tổng hợp số liệu vào Google Docs / Slides theo template tuần trước
5. Viết narrative: nhận xét sự hội tụ, phân tích lý do model overfit/underfit và error analysis
6. Lên danh sách next actions / hướng thử nghiệm cho tuần tiếp theo
7. Tự review định dạng và gửi trước cho GVHD

Bottleneck: Bước 5 - viết phần narrative (đọc hiểu raw metrics/loss curves để rút ra nhận xét mô hình học tốt hay xấu, phân tích ca lỗi) mất 30–40 phút và dễ bị bí từ/thiếu ý khi kết quả thực nghiệm không đạt kỳ vọng.

Impact: 
- Mất từ 90 đến 120 phút/tuần cho một đầu việc lặp lại.
- Dễ trễ deadline nộp báo cáo trước giờ họp khiến GVHD không kịp đọc trước để góp ý sâu.
- Báo cáo vội vàng thường chỉ dừng ở việc "khoe số" mà thiếu phần phân tích bản chất kỹ thuật.

Success metric:
- Giảm tổng thời gian làm báo cáo tuần từ 105 phút xuống dưới 35 phút.
- 100% số liệu thực nghiệm (Loss, F1, Epoch) khớp chính xác với log gốc.
- GVHD không phải hỏi lại các câu cơ bản về điều kiện thí nghiệm (hyperparameters, dataset split).

Non-AI alternative: Dùng công cụ tracking như Weights & Biases (Wandb) hoặc MLflow: Tự động vẽ đồ thị và gom log tốt, nhưng không tự viết được đoạn văn narrative giải thích bối cảnh, phân tích nguyên nhân lỗi và đề xuất hướng giải quyết phù hợp với yêu cầu của GVHD.

AI hypothesis: AI nhận input là raw log/json metrics và tham số config, sau đó tự động cấu trúc thành bảng so sánh và nháp đoạn văn nhận xét kỹ thuật (technical narrative). Duy chỉ cần kiểm tra tính chính xác và bổ sung góc nhìn chuyên môn.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 105 phút

[1 Tải log & checkpoint từ các server: 15']
→ [2 Thu thập metrics vào nháp: 15']
→ [3 Chụp ảnh / export biểu đồ: 15']
→ [4 Dán vào Docs/Slide template: 15']
→ [5 Viết narrative & error analysis: 35']  <-- bottleneck
→ [6 Lên kế hoạch tuần tới: 10']
```

<!-- File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png` -->

```
FUTURE STATE — 25 phút

[1 Export log JSON/CSV từ các lần chạy: 3']
→ [2 Tool tự động tạo bảng metrics & đồ thị: 2']
→ [3 AI đọc log & draft narrative phân tích kết quả: 3']
→ [4 Duy review, verify số liệu và chỉnh sửa narrative: 15']  <-- human boundary
→ [5 Xuất slide/doc gửi GVHD: 2']

Fallback: AI phân tích sai lệch xu hướng mô hình → Duy dùng bảng số liệu tự viết lại phần nhận xét (mất ~15 phút).
```

---

#### Problem Card #2 — [Task Decomposition & Planning]

```text
Problem 1 câu: Đầu mỗi tuần, Duy mất khoảng 60–75 phút để gom và phân loại các đầu việc từ nhiều kênh khác nhau (yêu cầu nghiên cứu của GVHD, bài lab/assignment VinAI, việc học trên trường), nhưng việc ước lượng thời gian và phân rã task vẫn mang tính cảm tính, dẫn đến xung đột lịch trình, task bị nghẽn và dồn việc sát deadline vào cuối tuần.

Actor: Duy (người lập kế hoạch và thực thi task).

Thời điểm / bối cảnh: Sáng thứ Ba hằng tuần (ngay sau buổi họp sync tiến độ với GVHD vào chiều thứ Hai).


Current workflow 3-7 bước:
1. Gom toàn bộ đầu việc mới từ các kênh: ghi chú họp GVHD, portal/Discord VinAI, lịch học trên trường (10')
2. Lọc và phân nhóm task theo mục tiêu: Khóa luận, VinAI, Khác (10')
3. Đối chiếu với lịch cố định trong tuần (giờ lên lớp, ca trực/học lab) để tìm các khung giờ trống (10')
4. Tự phân rã các đầu việc lớn thành checklist thực thi và áng chừng thời gian hoàn thành (25')
5. Xếp lịch thủ công, gán nhãn ưu tiên và nhập vào Notion / Todo app (15')

Bottleneck: Bước 4 — phân rã các đầu việc đa dạng tính chất (từ task nghiên cứu mở của khóa luận đến bài lab có rubric chấm điểm của VinAI) thành các action item khả thi với dung lượng thời gian thực tế thường bị mơ hồ; dễ ước lượng quá lạc quan (underestimate) dẫn đến bể kế hoạch.

Impact: 
- Tốn 60–75 phút/tuần cho việc lên lịch nhưng kế hoạch nhanh chóng bị phá vỡ sau 2–3 ngày đầu tuần.
- Tình trạng quá tải nhận thức (cognitive overload) khi phải liên tục chuyển ngữ cảnh (context switching) giữa làm nghiên cứu và làm bài lab.
- Thường xuyên bị dồn dập vào thứ Bảy và Chủ Nhật: vừa phải nộp bài lab VinAI vừa phải chạy code kịp lấy số liệu báo cáo đầu tuần sau.


Success metric: 
- Giảm thời gian lên kế hoạch tuần từ 60 phút xuống dưới 15 phút.

- 100% các task lớn đều được bẻ nhỏ thành các action item dưới 3 tiếng, có gắn nhãn ưu tiên rõ ràng (P0, P1, P2).

Non-AI alternative: Dùng template Notion/Trello dạng Kanban có sẵn: Chỉ giải quyết được mặt hiển thị (UI), không giúp bẻ nhỏ một đầu việc kỹ thuật phức tạp thành các bước cụ thể.

AI hypothesis: AI nhận input là raw meeting notes hoặc yêu cầu của GVHD, sau đó dựa trên context nghiên cứu hiện tại để gợi ý checklist kỹ thuật chuẩn (kèm ước lượng độ phức tạp và gợi ý thứ tự thực thi). Duy chỉ cần tinh chỉnh lại theo quỹ thời gian thực tế.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 70 phút

[1 Gom task từ nhiều nguồn: 10']
→ [2 Phân loại theo mục tiêu: 10']
→ [3 Tra cứu lịch trống: 10']
→ [4 Phân rã task & ước lượng thời gian: 25']  <-- bottleneck
→ [5 Nhập liệu thủ công vào Notion: 15']

FUTURE STATE — 15 phút

[1 Nhập input thô (notes GVHD, đề bài VinAI, to-do tuần): 2']
→ [2 AI phân loại, bẻ nhỏ task & đề xuất thời lượng + priority: 3']
→ [3 Duy review, cân đối lại theo sức tải thực tế: 8']  <-- human boundary
→ [4 Đồng bộ trực tiếp vào Notion/Todo app: 2']

Fallback: AI phân rã task chưa sát thực tế → Duy dùng khung danh mục do AI nhóm sẵn, tự gõ lại 3-4 đầu việc quan trọng nhất (mất ~15 phút).
```
---

#### Problem Card #3 — [SOTA Benchmark Extraction & Visualization]

```text
Problem 1 câu: Khi làm khóa luận, Duy mất 2–3 tiếng cho mỗi nhóm 3–4 paper chỉ để bóc tách thủ công số liệu SOTA từ file PDF, và sau đó vẫn gặp khó khăn trong việc so sánh trực quan (cognitive overload) để nhận ra các xu hướng và sự đánh đổi (trade-offs) giữa các phương pháp.

Actor: Duy (sinh viên nghiên cứu làm khóa luận) và Giảng viên hướng dẫn (người thẩm định và định hướng phương pháp).

Thời điểm / bối cảnh: Giai đoạn khảo sát tài liệu và viết Chương 2 (Literature Review), hoặc mỗi khi xuất hiện baseline mới cần đưa vào đối chiếu với đề tài.

Current workflow 3-7 bước:
1. Tải 3-4 file PDF paper từ arXiv / OpenReview (5')
2. Lướt phần Experiments / Results tìm bảng so sánh chính (15')
3. Kiểm tra dataset, metric (mAP, F1), backbone, và các variants (20')
4. Copy số liệu thủ công và gõ lại vào bảng Notion / Excel / LaTeX (45')
5. Tự viết script Python (Matplotlib/Seaborn) để vẽ biểu đồ so sánh (F1 vs Latency, Pareto front) (40')
6. Đọc phần Methodology để tóm tắt 2-3 câu ưu/nhược điểm cốt lõi (20')
7. Đối chiếu chéo để đảm bảo cùng điều kiện so sánh (fair comparison) (10')
Bottleneck:
- Bước 4: Trích xuất thủ công các số liệu kỹ thuật từ PDF cực kỳ tốn thời gian và dễ nhầm lẫn giữa các biến thể mô hình (variants) hoặc bảng ablation study.

- Bước 5: Việc tự code biểu đồ so sánh đòi hỏi nhiều công sức nên thường bị bỏ qua, khiến báo cáo gửi GVHD chỉ toàn bảng số khô khan, khó thấy được sự vượt trội hay trade-off giữa các kiến trúc.

Impact:
- Tốn khoảng 155 phút (~2.5 tiếng) cho mỗi lần tổng hợp một cụm phương pháp.

- Tổng thời gian cho toàn bộ chương Literature Review có thể ngốn 20–25 giờ chỉ riêng việc gõ số và vẽ biểu đồ.

- GVHD mất nhiều thời gian hơn để đọc hiểu và thẩm định vì báo cáo thiếu trực quan hóa.

Success metric:
- Giảm tổng thời gian từ 155 phút xuống dưới 35 phút cho mỗi cụm 3–4 paper.

- 100% số liệu (metrics, dataset, backbone) khớp chính xác với paper gốc sau bước verify.

- Tự động sinh ra ít nhất 1 biểu đồ trực quan (Scatter/Bar chart biểu diễn Pareto curve) sẵn sàng chèn vào báo cáo khóa luận mà không cần tự code tay từ đầu.
Non-AI alternative:
- Dùng Papers With Code: Chỉ có sẵn cho các benchmark/dataset quá phổ biến; các bài toán ngách hoặc các paper mới công bố trong năm thường chưa có dữ liệu tổng hợp.
- Dùng template Excel/Origin vẽ đồ thị: Vẫn phải mất công bóc tách số liệu thủ công từ PDF (không giải quyết được bottleneck #1).
AI hypothesis:
- AI (Multimodal LLM) đọc hiểu bảng biểu từ PDF, trích xuất cấu trúc dữ liệu chuẩn (JSON/DataFrame), đồng thời tự sinh đoạn mã Python visualization (Matplotlib/Seaborn) chuẩn xuất bản khoa học. Duy chỉ cần làm bước verify số liệu và nhận xét chuyên môn.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 155 phút

[1 Tải PDF: 5']
→ [2 Tìm bảng Experiments: 15']
→ [3 Đọc hiểu metric & variant: 20']
→ [4 Copy số vào LaTeX/Excel: 45']        <-- bottleneck #1
→ [5 Thủ công code vẽ biểu đồ so sánh: 40']  <-- bottleneck #2
→ [6 Tóm tắt ưu/nhược điểm: 20']
→ [7 Đối chiếu chéo: 10']

FUTURE STATE — 35 phút

[1 Nạp 3-4 file PDF / arXiv link: 2']
→ [2 AI parse text & table, chuẩn hóa JSON schema: 4']
→ [3 AI tự sinh script vẽ biểu đồ trực quan (Scatter/Bar): 2']   <-- giải quyết bottleneck #2
→ [4 AI draft tóm tắt method & pros/cons: 2']
→ [5 Duy review, verify số liệu gốc và chạy script vẽ hình: 20'] <-- human boundary
→ [6 Xuất biểu đồ & bảng LaTeX nộp khóa luận: 5']                <-- giải quyết bottleneck #1

Fallback: AI đọc sai bảng biểu phức tạp hoặc code vẽ bị lỗi → Duy tự trích xuất bảng đó bằng tay và dùng template vẽ có sẵn (mất ~60 phút).

```

<!-- File đính kèm: `01-individual-problem-scan-workflow-card-3.png` -->

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #2 — Task Decomposition & Planning (Phân rã và điều phối công việc tuần giữa Khóa luận tốt nghiệp và VinAI thực chiến)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là bài toán gom thông tin đa nguồn (ghi chú họp GVHD, portal VinAI, lịch học) rồi phân rã thành checklist kỹ thuật và lịch trình khả thi. Về số đo, quy trình thủ công hiện ngốn 60–75 phút mỗi sáng thứ Ba nhưng kế hoạch thường bị vỡ chỉ sau 2-3 ngày do ước lượng cảm tính; mục tiêu là rút ngắn xuống dưới 15 phút với 100% task lớn được bẻ nhỏ dưới 3 tiếng. Impact lớn nhất là loại bỏ nút thắt quá tải nhận thức do chuyển ngữ cảnh liên tục và chấm dứt cảnh dồn việc chạy deadline nghẽn mạng vào cuối tuần.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Làm thế nào để AI ước lượng thời gian chạy thực nghiệm/code chính xác khi bản thân các task nghiên cứu khóa luận vốn có độ bất định (uncertainty) rất cao?
2. Giới hạn nào để AI chỉ dừng ở mức gợi ý phân rã công việc thay vì can thiệp quá sâu vào việc quyết định độ ưu tiên cá nhân của Duy?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI tự hiểu độ phức tạp kỹ thuật" là quá lạc quan vì AI thiếu ngữ cảnh tài nguyên phần cứng (GPU limit, lỗi debug phát sinh) và năng lực thực tế của người làm. Dễ biến thành một "to-do list generator" chung chung nếu chỉ nạp prompt đơn giản mà không có framework phân loại task kỹ thuật cụ thể (Deep Work vs GPU wait time).
- Tôi sửa gì: Thêm nhãn bối cảnh đặc thù kỹ thuật ([GPU wait], [Deep Work - Code], [Writing/Sync]) vào cấu trúc output của AI để không tính thời gian máy chạy vào thời gian con người làm việc. Thiết lập rõ boundary ở tương lai: AI chỉ đóng vai trò phân rã các đầu mục lớn thành draft sub-tasks; việc gán deadline và chốt lịch cuối cùng bắt buộc là 8 phút review của Duy (Human-in-the-loop).

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
