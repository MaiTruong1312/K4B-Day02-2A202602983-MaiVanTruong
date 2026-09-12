# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Mai Văn Trường
- Mã học viên: 2A202602983
- Nhóm: K4B-Day02
- Candidate problem nhóm chọn: #12 — Trả lời câu hỏi tài chính phức tạp từ nhiều bảng và tài liệu

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Quét 10 problems từ trải nghiệm học tập, làm đồ án Flutter/IoT và bài lab. Lập 3 Problem Cards chi tiết. | Đóng góp 3 candidates (#7, #8, #9) vào danh sách chung của nhóm, trong đó Card #7 đạt 33 điểm ở shortlist. |
| Pitch Problem Card | Pitch Card #1 (Tổng hợp báo cáo từ code/test/log), phân tích workflow 120 phút xuống 35 phút và điểm nghẽn ở khâu tổng hợp dữ liệu. | Giúp nhóm hiểu rõ cấu trúc của một Problem Card chuẩn với baseline, bottleneck và human boundary. |
| Challenge bài của bạn khác | Challenge candidate #13 (nhập hóa đơn) về khả năng xử lý file scan mờ và #14 (gán thẻ ticket) về nguy cơ thiếu taxonomy chuẩn. | Giúp nhóm nhìn ra rủi ro về chất lượng dữ liệu đầu vào của các candidate khác trước khi chấm điểm. |
| Gom trùng / cluster | Cùng nhóm phân loại 15 candidates thành 4 cụm (A, B, C, D) dựa trên pattern workflow. | Đưa bài #12 vào Cluster C (Tra cứu & phân tích) và bài #7 vào Cluster A (Tạo báo cáo đa nguồn). |
| Chọn candidate problem | Thảo luận ma trận chấm điểm shortlist (#7, #14, #12), bảo vệ bài #12 nhờ có impact lớn và khả năng đo lường rõ ràng. | Nhóm đạt đồng thuận chọn candidate #12 với tổng 34 điểm (cao nhất shortlist). |
| Validation / research | Đóng góp dữ liệu phỏng vấn 3 NV tài chính, tổng hợp log 15 câu hỏi ad-hoc và nghiên cứu RAG pattern (LlamaIndex). | Xác định pain thật nằm ở bước truy xuất/đối chiếu đa nguồn (15–30 phút) và khẳng định RAG là pattern phù hợp nhất. |
| Workflow nhóm | Xây dựng chi tiết Current Workflow 7 bước (35 phút) và Future Workflow 6 bước tích hợp RAG pipeline. | Xác định chính xác bottleneck tại bước 3–4 và đặt ranh giới Human Review bắt buộc ở bước 5. |
| Problem Statement | Viết và hoàn thiện các field cho PS v0, sau đó tinh chỉnh lên PS v1 với đầy đủ 9 field chuẩn. | Đưa ra baseline cụ thể (35 phút/câu) và metric đo accuracy (≥ 85% khớp giá trị, kỳ, đơn vị). |
| Rule / Workflow / Agent | Đánh giá ma trận độ phù hợp (Mơ hồ Cao - Phức tạp Cao) và so sánh 3 cấp độ giải pháp trên bài #12. | Thuyết phục nhóm chọn mức Workflow thay vì Agent để giảm rủi ro, dễ kiểm soát và tối ưu chi phí. |
| Decision | Lập bảng đánh giá 6 câu hỏi quyết định, xây dựng kế hoạch pilot 10 câu hỏi BCTC và tiêu chí rollback khi accuracy < 70%. | Chốt quyết định GO kèm phương án thử nghiệm thực tế rõ ràng và kịch bản rút lui an toàn. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi nằm ở việc thiết kế Future Workflow 6 bước tích hợp RAG pipeline, trong đó xác định chính xác bottleneck ở bước trích xuất đa nguồn và thiết lập ranh giới bắt buộc Human Review ở bước 5 để ngăn ngừa rủi ro hallucination của AI.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý mở rộng lăng kính cho các problem trong đồ án IoT và Flutter. | Gợi ý cách diễn đạt 1 câu problem gãy gọn và cấu trúc hóa dấu hiệu thật. | AI đưa ra một số problem chung chung như "khó quản lý thời gian" không có số đo. | Lọc bỏ ý chung chung, chỉ giữ lại các problem có số liệu thực tế từ việc bấm giờ và đếm lỗi. |
| Problem Card | Phản biện Card #1 về tính khả thi của việc tạo báo cáo tự động từ log. | Chỉ ra rủi ro AI tự suy diễn kết quả test nếu log không đầy đủ. | AI đề xuất tự động nộp báo cáo luôn mà không cần người kiểm tra. | Thêm bước Human Review bắt buộc và quy định fallback sửa thủ công khi AI sinh sai. |
| Workflow | Gợi ý các bước xử lý dữ liệu chi tiết cho workflow tra cứu tài chính. | Gợi ý bổ sung bước kiểm chứng đơn vị tính và kỳ báo cáo vào workflow. | AI vẽ workflow 3 bước quá đơn giản, bỏ qua khâu phân tích câu hỏi và trích nguồn. | Tách thành workflow 7 bước hiện tại và 6 bước future có ranh giới AI/Người rõ ràng. |
| Research | Tìm kiếm các tool/pattern AI đang được ứng dụng trong mảng tài chính. | Gợi ý pattern RAG (LlamaIndex) và Microsoft Copilot for Finance. | AI tự bịa một số tính năng chưa có thật và đưa link không truy cập được. | Tự kiểm tra lại documentation chính thức, thay bằng link thật và ghi rõ các rủi ro thực tế. |
| Problem Statement | Phản biện PS v0 để tìm ra các field còn mơ hồ hoặc thiếu căn cứ. | Chỉ ra field Impact và Metric còn mang tính giả định, chưa có baseline. | AI viết Problem Statement theo kiểu quảng cáo, thiếu tính kỹ thuật. | Bổ sung baseline 35 phút/câu từ log 15 mẫu và định nghĩa accuracy = đúng giá trị + kỳ + đơn vị. |
| Rule / Workflow / Agent | Phân tích rủi ro nếu nâng cấp bài toán tài chính từ Workflow lên Agent. | Phân tích rõ sự khác biệt giữa Agent tự chọn tool và Workflow chạy pipeline tuần tự. | AI có xu hướng xúi chọn Agent cho "tiên tiến" dù không cần thiết ở giai đoạn pilot. | Kiên quyết giữ lựa chọn Workflow để đảm bảo tính kiểm soát, giảm chi phí và dễ debug. |
| Decision | Xây dựng kịch bản exit/rollback khi dự án pilot không đạt yêu cầu. | Gợi ý các chỉ số định lượng như ngưỡng accuracy 70% và thời gian tiết kiệm 30%. | AI đề xuất dừng ngay lập tức nếu gặp 1 câu sai duy nhất (quá khắt khe). | Sửa thành đánh giá trên tập mẫu 10 câu hỏi pilot để có cái nhìn khách quan hơn. |

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?

**Reflection:**

```text
Khi lắng nghe top 3 problem cards của các thành viên trong nhóm, tôi nhận ra mỗi người đều có những góc nhìn và điểm đau rất thực tế từ bối cảnh làm việc riêng, từ việc chấm bài IELTS của TA đến việc nhập hóa đơn kế toán hay xử lý ticket hỗ trợ. Học hỏi từ các bạn giúp tôi hiểu rằng một problem tốt không nằm ở công nghệ phức tạp mà ở chỗ actor có nỗi đau đủ lớn và workflow có bottleneck đo lường được bằng số liệu cụ thể. Trong quá trình thảo luận ở Phase 6, nhóm tôi từng có lúc chớm rơi vào bẫy "solution-first" khi một số thành viên muốn chọn mô hình Agent tự động hoàn toàn cho "ngầu" và hợp xu hướng. Tuy nhiên, sau khi phân tích kỹ ma trận độ phù hợp và 5 câu hỏi chốt, tôi đã cùng nhóm kéo tư tư duy trở lại thực tế: bài toán tài chính ad-hoc đòi hỏi sự chính xác tuyệt đối, pipeline xử lý hiện tại vẫn đi theo các bước tuần tự rõ ràng nên một Workflow RAG kết hợp kiểm soát người thật là phương án tối ưu và an toàn nhất. Đóng góp rõ nhất của tôi vào artifact nhóm là việc thiết lập Future Workflow 6 bước và đưa ra các metric định lượng chặt chẽ cho Problem Statement v1. Đối với tôi, điều khó nhất khi viết Problem Statement chính là việc xác định Boundary và Success Metric, bởi vì rất dễ đưa ra các con số cảm tính nếu không có baseline từ trước. Nhờ trải nghiệm này, tôi rút ra bài học sâu sắc về tư duy làm sản phẩm AI: luôn bắt đầu từ bottleneck thực sự của người dùng, xác định ranh giới can thiệp an toàn của công nghệ và kiểm chứng giải pháp bằng các thử nghiệm nhỏ nhất trước khi mở rộng.
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
