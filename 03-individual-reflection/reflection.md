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
|---|---|---|---|---|
| Scan | Gợi ý thêm problems theo role PM | Giúp nhớ thêm Slack Search, PRD Review | Gợi ý vài ý quá rộng | Bỏ các ý không có workflow thật |
| Workflow | Nhờ AI chuyển mô tả thành Mermaid | Nhanh hơn khi vẽ flow | AI gộp bước viết narrative và review | Tách lại vì bottleneck nằm ở narrative |
| Research | Tìm tool tương tự | Gợi ý Jira, Slack AI, Gemini, Fellow | Có claim tiết kiệm thời gian không nguồn | Chỉ giữ link tool chính thức, không dùng số liệu không verify |
| Problem Statement | Nhờ AI phản biện field mơ hồ | Chỉ ra metric quality yếu | AI đề xuất agent quá sớm | Nhóm hạ về Workflow |

## Bài học:

- Problem tốt không phải problem nghe "AI" nhất, mà là problem có workflow và metric rõ.
- Vẽ workflow giúp thấy phần nào rule đủ, phần nào AI mới có ích.
- Agent không phải đích đến mặc định. Trong case này, Workflow hợp lý hơn vì có đường đi cố định và có PM review.
- Research không phải để copy tool, mà để thấy pattern: nhiều sản phẩm tốt đều để AI draft, người thật review.

Nếu làm lại:

```text
Tôi sẽ validate với nhiều PM hơn trước khi chốt metric 90 phút → 30 phút, vì baseline hiện tại chủ yếu đến từ trải nghiệm của tôi.
```

---