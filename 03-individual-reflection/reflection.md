# 03 — Individual Reflection Example

## Đóng góp trong nhóm

# Đóng góp trong nhóm

| Hoạt động | Những việc đã làm | Kết quả |
| ---- | ---- | ---- |
| Scan cá nhân | Đưa ra 7 problems liên quan đến việc phối hợp, theo dõi tiến độ, xử lý feedback và tổng hợp bài trong nhóm | Nhóm có thêm các candiate problem cụ thể để tham khảo và so sánh |
| Pitch | Pitch problem “Chuyển feedback của giảng viên thành danh sách nhiệm vụ cần sửa” | Giúp nhóm có thêm góc nhìn, có thêm nhiều ý tưởng để cải thiện đề tài của mình |
| Validation | Khảo sát nhanh 4 người bạn đang làm marketing freelance về quá trình sử dụng AI để lập kế hoạch marketing | 3/4 người thường dùng ChatGPT nhưng phải prompt lại nhiều lần; 2/4 người cho rằng AI phân bổ hoặc tính toán ngân sách chưa chính xác |
| Challenge | Đặt các câu hỏi phản biện cho nhóm: “Google Sheets template đã đủ đáp ứng nhu cầu của SME chưa?”, “Vì sao cần dùng AI thay vì chỉ dùng template và rule?”, “BrandFlow có thực sự thay thế agency hay chỉ nên tạo draft plan?”, “AI lấy context doanh nghiệp từ đâu để tránh output chung chung?”, “Nếu AI tính sai ngân sách thì bước nào sẽ kiểm soát?”, “Vì sao chọn Workflow mà không chọn Agent?”, “Chủ doanh nghiệp cần kiểm tra và quyết định ở bước nào?” | Giúp nhóm bổ sung non-AI alternative, thu hẹp BrandFlow thành công cụ tạo draft plan, thêm RAG để lấy context doanh nghiệp, sử dụng Python để kiểm soát ngân sách và giữ human review trước khi sử dụng plan |


## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
| ---- | ---- | ---- | ---- | ---- |
| Scan | Gợi ý thêm problems theo các lăng kính lặp lại, tốn thời gian, AI có thể làm tốt hơn và pain từ người khác | Giúp tôi mở rộng danh sách lên 10 problems về phân công, theo dõi tiến độ, xử lý feedback và tổng hợp bài | Một số problem quá rộng hoặc giống ý tưởng giải pháp hơn là vấn đề thực tế | Bỏ các ý không có actor, workflow hoặc dấu hiệu thật rõ ràng |
| Problem Card | Nhờ AI chuyển top 3 problems thành Problem Card theo template | Giúp trình bày đầy đủ actor, bối cảnh, workflow, bottleneck, impact và success metric | AI tự ước lượng một số thời gian và tỉ lệ khi chưa có dữ liệu thật | Ghi rõ số liệu nào chỉ là ước lượng và chỉnh lại workflow theo trải nghiệm thực tế |
| Validation | Nhờ AI gợi ý câu hỏi khảo sát người làm marketing freelance | Giúp câu hỏi tập trung vào cách dùng ChatGPT, chất lượng output và lỗi tính ngân sách | Một số câu hỏi ban đầu mang tính dẫn dắt, dễ khiến người trả lời nghiêng về việc cần AI  | Viết lại câu hỏi trung lập và ghi nhận cả ý kiến rằng Google Sheets template có thể đã đủ |
| Research | Nhờ AI gợi ý các tool và phương án tương tự BrandFlow | Giúp xác định các nhóm giải pháp như LLM trực tiếp, template, dashboard và workflow automation | Một số nhận xét về tool còn chung chung hoặc có claim không kèm nguồn kiểm chứng | Chỉ giữ thông tin có thể kiểm tra và không sử dụng số liệu chưa được verify |

## Bài học:

* Problem tốt không phải là problem nghe “AI” nhất, mà là problem có actor, workflow, bottleneck và success metric rõ ràng.
* Vẽ workflow giúp tôi nhận ra không phải bước nào cũng cần AI: RAG phù hợp để lấy context doanh nghiệp, Python phù hợp để kiểm soát ngân sách, còn AI hữu ích ở bước tạo và phản biện draft plan.
* Agent không phải đích đến mặc định. Trong trường hợp BrandFlow, Workflow hợp lý hơn vì quy trình có đường đi cố định, mỗi bước có input/output rõ và chủ doanh nghiệp vẫn review trước khi sử dụng plan.
* Validation giúp nhóm nhận ra pain không chỉ nằm ở chi phí thuê agency, mà còn ở việc SME thiếu kiến thức marketing và các LLM hiện tại thường cho output chung chung hoặc tính ngân sách chưa chính xác.
* Research không phải để sao chép sản phẩm có sẵn, mà để nhận ra các pattern phù hợp: lưu context doanh nghiệp, dùng AI tạo bản nháp, dùng rule cho phép tính chính xác và để người thật kiểm tra quyết định cuối.
* Non-AI alternative vẫn rất quan trọng. Template và dashboard có thể đã đủ với một số doanh nghiệp nhỏ, vì vậy nhóm không nên mặc định mọi trường hợp đều cần AI.
* AI có thể hỗ trợ cấu trúc, gợi ý và phản biện, nhưng evidence thực tế và quyết định cuối vẫn cần dựa trên khảo sát và đánh giá của nhóm.

Nếu làm lại:

```text
Tôi sẽ khảo sát thêm nhiều chủ doanh nghiệp SME và người làm marketing trước khi chốt các metric về thời gian, chi phí và chất lượng plan, vì baseline hiện tại mới dựa trên một nhóm người được hỏi khá nhỏ. Tôi cũng sẽ chuẩn bị câu hỏi trung lập hơn để so sánh rõ giữa việc dùng template, LLM trực tiếp, thuê agency và sử dụng BrandFlow.
```


---