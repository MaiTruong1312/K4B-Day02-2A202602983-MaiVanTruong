# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Mai Văn Trường
- Mã học viên:2A202602983
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm cuối đang trong quá trình tìm, tiếp cận các cơ hội nâng cao bản thân để cải thiện khả năng tìm việc trong tương lai.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
- Học tập và làm đồ án
- Đi làm thêm 
- Họp meet, discord với team
---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian / Lặp lại | Mất nhiều thời gian xử lý lỗi môi trường khi build và chạy các project Flutter/Android thay vì tập trung vào chức năng chính. | Bản thân | Trong các project gần đây đã nhiều lần gặp lỗi Gradle/Kotlin daemon, JDK, Firebase, plugin, NDK, ADB hoặc target sai. Mỗi lần thường phải chạy lại `flutter clean`, `pub get`, dừng Gradle, xóa cache và build lại; có buổi mất khoảng **1–2 giờ** chỉ để đưa project về trạng thái chạy được. |
| 2 | Lặp lại / AI có thể tốt hơn | Khi gặp lỗi lập trình thường phải đọc log dài, tìm dòng lỗi chính rồi thử nhiều cách sửa trước khi xác định đúng nguyên nhân. | Bản thân | Trong tuần học/làm đồ án có thể gặp khoảng **3–5 lỗi build hoặc runtime**, mỗi lỗi mất khoảng **20–60 phút** để đọc log, tìm trên mạng/AI và thử lại. Các lỗi gần đây có Gradle daemon, Kotlin cache, Firebase, package không hỗ trợ Windows và cấu hình Android. |
| 3 | Tốn thời gian | Khó quản lý đồng thời nhiều đầu việc cuối kỳ: học môn trên trường, đồ án, bài lab, công việc làm thêm và họp team. | Bản thân | Một tuần thường có ít nhất **4 nhóm hoạt động**: học, đồ án, làm thêm, họp team. Khi deadline gần nhau dễ phải chuyển context nhiều lần trong ngày và có việc bị dồn sang cuối ngày hoặc cuối tuần. |
| 4 | Lặp lại / Pain từ người khác | Khi làm việc nhóm, thông tin kỹ thuật và quyết định trong các buổi Meet/Discord dễ bị phân tán, sau đó phải hỏi lại hoặc tổng hợp lại. | Bản thân và thành viên team | Team có các buổi Meet/Discord hằng tuần; sau họp thường phải nhớ lại ai làm gì, module nào đang lỗi, quyết định nào đã chốt. Chỉ cần **2–3 người hỏi lại một nội dung** hoặc mất **10–20 phút/buổi** để tổng hợp là đã tạo ra thời gian lặp lại đáng kể. |
| 5 | Tốn thời gian / AI có thể tốt hơn | Viết báo cáo cho từng bài thực hành hoặc đồ án mất nhiều thời gian vì phải chuyển từ code, log và kết quả test thành tài liệu có cấu trúc. | Bản thân | Với một bài lab kiểm thử, phải tổng hợp từ yêu cầu → test case → code → kết quả chạy → coverage → nhận xét. Một báo cáo hoàn chỉnh có thể mất khoảng **1–3 giờ**, dù phần lớn dữ liệu đã tồn tại trong source code và log. |
| 6 | Lặp lại | Việc kiểm tra và chỉnh sửa cấu hình phần cứng trong đồ án IoT bị lặp lại mỗi khi thay đổi module hoặc cách bố trí. | Bản thân và team đồ án | Smart Delivery Box dùng khoảng **10+ thành phần/phần cứng** như ESP32-S3, camera, HX711, HC-SR04, MC-38, servo, solenoid, keypad, LED, buzzer. Mỗi lần đổi GPIO hoặc cơ cấu phải kiểm tra lại pin, điện áp, nguồn và sơ đồ nối dây; chỉ một thay đổi có thể kéo theo kiểm tra lại **5–10 kết nối**. |
| 7 | Tốn thời gian / Pain từ người khác | Tài liệu kỹ thuật của đồ án nằm rải rác giữa code, sơ đồ mạch, bản vẽ hộp, ghi chú và nội dung trao đổi nên khó tìm lại quyết định cũ. | Bản thân và thành viên team | Đồ án hiện có nhiều loại tài liệu: source code, sơ đồ mạch, bản vẽ hộp 2D, pin mapping, thông số module và ghi chú. Khi cần tìm lại một thông tin như GPIO hoặc kích thước linh kiện có thể mất **5–15 phút/lần** để tìm lại đúng phiên bản. |
| 8 | AI có thể tốt hơn | Quá trình học một công nghệ mới thường bị ngắt quãng vì phải vừa đọc lý thuyết, vừa tìm ví dụ, vừa sửa lỗi thực hành. | Bản thân | Khi học các chủ đề như Flutter, Firebase, RAG, Transformer, Oracle hoặc testing, một nội dung có thể cần **2–4 nguồn** khác nhau mới hiểu và áp dụng được. Thời gian tìm và ghép thông tin có thể chiếm **30–60 phút/chủ đề**. |
| 9 | Tốn thời gian / Lặp lại | Dung lượng ổ đĩa và cache của môi trường phát triển thường tăng trở lại, buộc phải kiểm tra và dọn dẹp định kỳ. | Bản thân | Đã từng phải kiểm tra các thư mục/cache lớn như NVIDIA DXCache khoảng **3.4 GB**, Android Studio khoảng **2.49 GB**, Dart cache khoảng **1.3 GB**, cùng Gradle/build cache. Khi ổ C gần đầy có thể phải mất **20–40 phút/lần** để tìm thư mục chiếm dung lượng và dọn an toàn. |
| 10 | AI có thể tốt hơn / Tốn thời gian | Khó xác định kỹ năng nào cần ưu tiên để chuẩn bị xin việc vì đang học và làm nhiều mảng khác nhau nhưng chưa có quy trình đánh giá khoảng cách kỹ năng rõ ràng. | Bản thân | Hiện đang tiếp xúc với nhiều mảng như Flutter, PHP, database, AI, testing và IoT. Mỗi tuần dành thời gian học thêm nhưng chưa có một hệ thống cố định để đối chiếu với yêu cầu tuyển dụng; có thể mất **1–2 giờ/tuần** xem JD, học rải rác nhưng khó biết kỹ năng nào mang lại giá trị cao nhất khi xin việc. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Viết báo cáo cho từng bài thực hành hoặc đồ án mất nhiều thời gian vì phải chuyển từ code, log và kết quả test thành tài liệu có cấu trúc. | Actor rất cụ thể là sinh viên làm bài lab/đồ án. Workflow có thể vẽ rõ: hoàn thành code → chạy test → lấy log/kết quả → chọn nội dung quan trọng → viết báo cáo → chỉnh format. Bottleneck nằm ở bước tổng hợp và chuyển dữ liệu kỹ thuật thành nội dung báo cáo. Impact đo được bằng thời gian khoảng **1–3 giờ/báo cáo**. | Chưa đo chính xác bao nhiêu phần trăm thời gian có thể tự động hóa và giảng viên có yêu cầu format khác nhau đến mức nào. |
| 2 | Khi làm việc nhóm, thông tin kỹ thuật và quyết định trong các buổi Meet/Discord dễ bị phân tán, sau đó phải hỏi lại hoặc tổng hợp lại. | Actor cụ thể là sinh viên làm việc nhóm. Workflow rõ: họp → trao đổi vấn đề → chốt quyết định → phân công → thành viên thực hiện → hỏi lại khi quên. Bottleneck nằm ở bước ghi lại quyết định và action item. Impact có thể đo bằng **10–20 phút/buổi** tổng hợp lại và số lần thành viên hỏi lại nội dung đã trao đổi. | Chưa có số liệu chính xác về số lần team hỏi lại trong mỗi tuần và chưa biết mọi buổi họp có thể ghi/thu âm để xử lý hay không. |
| 3 | Khi gặp lỗi lập trình thường phải đọc log dài, tìm dòng lỗi chính rồi thử nhiều cách sửa trước khi xác định đúng nguyên nhân. | Actor cụ thể là sinh viên lập trình khi học hoặc làm đồ án. Workflow rõ: chạy chương trình → phát sinh lỗi → đọc log → xác định lỗi chính → tìm giải pháp → thử sửa → chạy lại. Bottleneck nằm ở bước đọc log và xác định nguyên nhân. Impact khá rõ: khoảng **3–5 lỗi/tuần**, mỗi lỗi mất **20–60 phút**. | Chưa chắc lỗi nào AI có thể chẩn đoán chính xác; một số lỗi phụ thuộc môi trường, phiên bản hoặc cấu hình máy nên vẫn cần người kiểm tra thủ công. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu:
Sinh viên mất nhiều thời gian chuyển code, kết quả test và log kỹ thuật thành một báo cáo có cấu trúc hoàn chỉnh.
Actor:
Sinh viên làm bài thực hành, bài lab hoặc đồ án có yêu cầu nộp báo cáo.
Thời điểm / bối cảnh:
Sau khi hoàn thành phần code và chạy test, trước thời điểm nộp bài hoặc báo cáo tiến độ.
Current workflow 3-7 bước:
1.Hoàn thành code và chạy chương trình/test.
2.Đọc kết quả test, log và coverage.
3.Chọn các phần code, kết quả và ảnh minh họa cần đưa vào báo cáo.
4.Tự viết nội dung mô tả từng phần theo yêu cầu của bài.
5.Chỉnh format, kiểm tra thiếu nội dung và hoàn thiện báo cáo.

Bottleneck:
Bước 3-4: phải tự đọc nhiều nguồn đầu vào rồi chuyển thành nội dung báo cáo có cấu trúc, tránh thiếu ý hoặc mô tả sai kết quả.
Impact:
Mỗi báo cáo có thể mất khoảng 1-3 giờ để tổng hợp và viết, dù phần lớn dữ liệu đã tồn tại trong source code, test result và log.
Success metric:
- Giảm thời gian tạo bản nháp báo cáo từ 1-3 giờ xuống còn khoảng 20-40 phút. 
- Bản nháp chứa đúng >= 90% các mục bắt buộc của template. 
- Người dùng chỉ cần review và chỉnh sửa thay vì viết lại từ đầu.
Non-AI alternative:
Tạo sẵn template báo cáo cố định và checklist các mục cần điền; dùng script để lấy tự động test result và coverage.
AI hypothesis:
AI có thể đọc code, log, test result và template rồi tự tạo bản nháp báo cáo theo từng mục, sau đó sinh viên chỉ cần kiểm tra và chỉnh sửa các phần chưa chính xác.
Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 120 phút

[1 Chạy code/test: 15'] → [2 Đọc log + kết quả: 20'] → [3 Chọn nội dung cần đưa vào báo cáo: 25'] → [4 Viết mô tả từng phần: 45']  <-- bottleneck

FUTURE STATE — 35 phút

[1 Chạy code/test: 15'] → [2 AI đọc code + log + template và tạo draft: 5'] → [3 Sinh viên review + sửa nội dung: 15']  <-- human boundary

Fallback: Nếu AI mô tả sai kết quả hoặc bỏ sót nội dung, sinh viên đối chiếu lại với code/log gốc và sửa thủ công trước khi nộp.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu:
Sau các buổi Meet/Discord, sinh viên trong team dễ quên hoặc hiểu khác nhau về các quyết định và phần việc đã được phân công.
Actor:
Sinh viên làm đồ án hoặc bài tập nhóm.
Thời điểm / bối cảnh:
Trong và ngay sau các buổi họp online để trao đổi tiến độ, lỗi kỹ thuật và phân công công việc.
Current workflow 3-7 bước:
1.Thành viên tham gia Meet/Discord.
2.Team trao đổi vấn đề và đề xuất giải pháp.
3.Team chốt quyết định hoặc phân công nhiệm vụ.
4.Một người ghi chú hoặc mọi người tự nhớ nội dung.
5.Sau họp, thành viên bắt đầu thực hiện.
6. Khi quên hoặc chưa rõ, thành viên hỏi lại trong nhóm.

Bottleneck:
Bước 4: việc ghi lại quyết định, task, deadline và người phụ trách không được thực hiện nhất quán.
Impact:
Có thể mất khoảng 10-20 phút sau mỗi buổi để tổng hợp lại nội dung; ngoài ra có thể xuất hiện 2-3 lần hỏi lại cùng một thông tin trong tuần.
Success metric:
- 100% quyết định chính và action item được ghi lại sau mỗi buổi họp. 
- Giảm ít nhất 50% số lần thành viên phải hỏi lại nội dung đã họp. 
- Bản tổng hợp được tạo trong vòng dưới 5 phút sau cuộc họp.
Non-AI alternative:
Dùng mẫu meeting note cố định gồm: Decisions, Action Items, Owner, Deadline và bắt buộc một người ghi chú trong mỗi buổi.
AI hypothesis:
AI có thể xử lý transcript hoặc ghi chú thô của cuộc họp để tự động trích xuất quyết định, nhiệm vụ, người phụ trách và deadline, sau đó yêu cầu một thành viên review trước khi gửi cho team.
Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 30 phút

[1 Họp và trao đổi] → [2 Chốt quyết định/task] → [3 Tự ghi nhớ hoặc ghi chú rời rạc: 10'] → [4 Thành viên hỏi lại sau họp: 10-20'] <-- bottleneck

FUTURE STATE — 10 phút

[1 Họp + có transcript/note] → [2 AI tạo summary + action items: 2-3'] → [3 Một thành viên review và gửi team: 5-7']  <-- human boundary

Fallback: Nếu AI nhận sai người phụ trách, deadline hoặc quyết định, người review sửa trực tiếp trước khi chia sẻ cho cả nhóm.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu:
Sinh viên lập trình mất nhiều thời gian đọc log dài và thử nhiều cách sửa trước khi xác định được nguyên nhân chính của lỗi.
Actor:
Sinh viên lập trình trong quá trình học, làm bài lab hoặc đồ án.
Thời điểm / bối cảnh:
Khi build project, chạy ứng dụng hoặc test và phát sinh lỗi compile, runtime hoặc lỗi cấu hình môi trường.
Current workflow 3-7 bước:
1.Chạy build hoặc chạy ứng dụng.
2.Hệ thống trả về log lỗi.
3.Đọc log để tìm dòng lỗi quan trọng.
4.Tìm nguyên nhân bằng tài liệu, Google hoặc hỏi AI.
5.Thử một cách sửa. 
6. Build/chạy lại để kiểm tra.
7. Nếu chưa hết lỗi thì quay lại bước 3. 

Bottleneck:
Bước 3-4: xác định đâu là lỗi gốc trong log và phân biệt lỗi chính với các warning hoặc lỗi phát sinh sau đó.
Impact:
Có khoảng 3-5 lỗi build/runtime trong một tuần học hoặc làm đồ án, mỗi lỗi có thể mất khoảng 20-60 phút để đọc log, tìm nguyên nhân và thử sửa.
Success metric:
- Giảm thời gian xác định nguyên nhân ban đầu xuống dưới 10 phút/lỗi. 
- AI chỉ ra đúng lỗi gốc hoặc nhóm nguyên nhân phù hợp trong ít nhất 80% trường hợp phổ biến. 
- Giảm số lần thử sửa không liên quan trước khi tìm được cách xử lý đúng.
Non-AI alternative:
Xây dựng checklist debug theo từng loại lỗi, ví dụ Flutter/Gradle/Firebase, và lưu lại các lỗi cũ cùng cách sửa trong một knowledge base cá nhân.
AI hypothesis:
AI có thể nhận log, thông tin môi trường và context project rồi xác định dòng lỗi quan trọng, nhóm nguyên nhân khả dĩ và đề xuất thứ tự kiểm tra thay vì để sinh viên tự đọc toàn bộ log.
Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 40 phút

[1 Chạy build/app: 5'] → [2 Nhận log lỗi: 1'] →  [3 Đọc và lọc log: 10']  <-- bottleneck → [4 Tìm nguyên nhân + giải pháp: 15'] → [5 Thử sửa + chạy lại: 9']

FUTURE STATE — 20 phút

[1 Chạy build/app: 5'] → [2 Đưa log + context cho AI: 2'] → [3 AI chỉ ra lỗi gốc + thứ tự kiểm tra: 3'] → [4 Sinh viên kiểm tra và chọn cách sửa: 5']  <-- human boundary →  [5 Chạy lại: 5']

Fallback: Nếu AI chẩn đoán sai, sinh viên quay lại log gốc, dùng checklist debug hoặc tra tài liệu chính thức rồi tiếp tục xử lý thủ công. 
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Tổng hợp báo cáo từ code, test và log.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Tôi chọn Card #1 vì đây là workflow tôi thường xuyên gặp khi làm bài thực hành và đồ án: sau khi hoàn thành code và test, tôi vẫn phải đọc log, chọn kết quả, viết mô tả và chỉnh format để tạo báo cáo. Quá trình hiện tại mất khoảng 1-3 giờ cho một báo cáo, trong đó bottleneck lớn nhất là bước tổng hợp dữ liệu kỹ thuật và chuyển chúng thành nội dung có cấu trúc. Nếu dùng AI để tạo bản nháp từ code, test result, log và template, mục tiêu là giảm thời gian xuống khoảng 20-40 phút nhưng vẫn giữ bước review cuối cùng do sinh viên thực hiện.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Làm thế nào để kiểm chứng rằng AI đang mô tả đúng kết quả của code/test thay vì tự suy diễn hoặc tạo thông tin không có trong dữ liệu đầu vào?
2. Với các môn học có template và tiêu chí báo cáo khác nhau, giải pháp này có còn tiết kiệm thời gian nếu người dùng phải cấu hình lại template cho từng bài hay không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:Các số liệu 1-3 giờ và mục tiêu 20-40 phút hiện chủ yếu dựa trên trải nghiệm cá nhân, chưa được đo trên nhiều lần làm báo cáo. Ngoài ra, nếu chỉ dùng AI để viết nội dung thì một phần vấn đề có thể giải quyết được bằng template và script thông thường, nên cần chứng minh AI tạo thêm giá trị ở bước hiểu và tổng hợp nội dung kỹ thuật.
- Tôi sửa gì:Tôi giữ phạm vi bài toán ở bước tạo bản nháp báo cáo, không để AI tự tạo và nộp báo cáo hoàn chỉnh. Tôi cũng bổ sung human review làm ranh giới bắt buộc và sẽ đo thời gian thực tế của workflow hiện tại và workflow có AI trên một số bài lab để so sánh.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
