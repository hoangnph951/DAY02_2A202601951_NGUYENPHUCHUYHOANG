## Scan rộng

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại  | Các thành viên không biết rõ ai đang phụ trách phần nào vì việc phân công chỉ trao đổi trong nhóm chat. | Tất cả thành viên | Mỗi bài nhóm đều có người hỏi lại phần này ai làm?, đôi khi một nhiệm vụ bị hai người làm trùng hoặc bị bỏ sót. |
| 2 | Lặp lại | Trưởng nhóm phải thường xuyên nhắn hỏi tiến độ từng người vì không có cách cập nhật thống nhất. | Trưởng nhóm | Mỗi tuần phải nhắc nhiều lần, mất 10–20 phút/lần để hỏi và tổng hợp tiến độ. |
| 3 |Tốn thời gian  | Nhóm mất nhiều thời gian tìm lại quyết định cũ vì thông tin nằm rải rác trong chat. | Tất cả thành viên | Phải cuộn lại lịch sử tin nhắn, hỏi lại các quyết định đã chốt, mất khoảng 10–15 phút/lần. |
| 4 | AI có thể tốt hơn | Nhóm khó phát hiện các đoạn nội dung bị trùng hoặc mâu thuẫn khi ghép bài. | Người review nội dung, cả nhóm | Sau khi ghép mới phát hiện hai phần viết giống nhau hoặc số liệu, ý kiến không thống nhất. |
| 5 | AI có thể tốt hơn | Sau khi nhận góp ý từ giảng viên, nhóm khó chuyển phản hồi thành danh sách việc cần sửa rõ ràng. | Cả nhóm, đặc biệt là trưởng nhóm | Có góp ý bị bỏ sót, cùng một lỗi bị nhắc lại, mất thời gian phân tích feedback. |
| 6 | Pain từ người khác | Một số thành viên hoàn thành đúng hạn nhưng đầu ra không đúng yêu cầu nên không dùng được ngay. | Người làm nhiệm vụ, người tổng hợp bài | Nhiệm vụ phải làm lại 1–2 lần, trưởng nhóm phải giải thích thêm hoặc chỉnh sửa lại. |
| 7 | Pain từ người khác | Thành viên vắng họp hoặc vào nhóm muộn khó nắm bắt tình hình hiện tại của dự án. | Thành viên vắng họp, trưởng nhóm | Phải đọc lại rất nhiều tin nhắn, hỏi lại từ đầu, mất 20–30 phút để bắt kịp. |



## Top 3
| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
| ---- | ---- | ---- | ---- |
| 1 | Khó chuyển feedback của giảng viên thành danh sách việc cần sửa rõ ràng | Actor và workflow rõ; feedback bị bỏ sót ảnh hưởng trực tiếp đến chất lượng bài; AI có thể hỗ trợ phân tích và cấu trúc hóa nội dung | Chưa đo chính xác thời gian nhóm đang dành để xử lý mỗi lần nhận feedback    |
| 2 | Khó phát hiện nội dung trùng lặp hoặc mâu thuẫn khi ghép bài | Có bottleneck rõ ở bước review; vấn đề phù hợp với khả năng so sánh và kiểm tra nội dung của AI | Chưa thống kê số lỗi trùng hoặc mâu thuẫn trung bình trong mỗi bài |
| 3 | Thành viên vắng họp hoặc vào nhóm muộn khó nắm bắt tình hình dự án | Actor cụ thể; tác động có thể đo bằng thời gian bắt kịp; có thể xây dựng workflow tóm tắt nhưng vẫn giữ người dùng kiểm tra nguồn | Chưa rõ thông tin của nhóm chủ yếu nằm trong chat, tài liệu hay biên bản họp |
---

# Problem Card #1 — Chuyển feedback thành nhiệm vụ cần sửa

## Problem 1 câu

Sau khi nhận feedback từ giảng viên, nhóm gặp khó khăn trong việc phân tích và chuyển toàn bộ góp ý thành danh sách nhiệm vụ sửa bài rõ ràng, khiến một số góp ý bị bỏ sót hoặc xử lý lặp lại.

## Actor

* Trưởng nhóm.
* Thành viên chịu trách nhiệm chỉnh sửa bài.
* Người tổng hợp và kiểm tra phiên bản cuối.

## Thời điểm / bối cảnh

Sau khi nhóm thuyết trình, nộp bản nháp hoặc nhận nhận xét trực tiếp từ giảng viên qua lời nói, tin nhắn, comment trong tài liệu hay rubric chấm bài.

## Current workflow 3–7 bước

1. Nhóm nhận feedback từ giảng viên qua nhiều nguồn khác nhau.
2. Trưởng nhóm đọc hoặc nghe lại toàn bộ feedback.
3. Trưởng nhóm tự xác định từng vấn đề cần sửa.
4. Trưởng nhóm viết lại các góp ý thành nhiệm vụ trong nhóm chat.
5. Các thành viên trao đổi để xác định người phụ trách.
6. Từng thành viên sửa phần của mình.
7. Người tổng hợp kiểm tra thủ công xem còn góp ý nào chưa được xử lý.

## Bottleneck

Bước đọc, diễn giải và chuyển feedback thành các nhiệm vụ cụ thể.

Feedback có thể dài, không theo cấu trúc và chứa nhiều ý trong cùng một câu. Trưởng nhóm phải tự xác định:

* Nội dung nào cần sửa.
* Phần nào của bài bị ảnh hưởng.
* Mức độ ưu tiên.
* Người phù hợp để xử lý.
* Tiêu chí để biết nhiệm vụ đã hoàn thành.

Thời gian hiện tại chưa được đo chính xác; ước lượng ban đầu cần kiểm chứng là khoảng **20–30 phút cho mỗi lần nhận feedback**.

## Impact

* Một số góp ý của giảng viên có thể bị bỏ sót.
* Các thành viên hiểu khác nhau về cùng một góp ý.
* Một lỗi có thể được nhiều người sửa trùng.
* Nhóm mất thời gian trao đổi lại yêu cầu.
* Cùng một lỗi có thể tiếp tục xuất hiện trong lần nộp sau.
* Chất lượng bài giảm dù nhóm đã nhận được feedback phù hợp.

## Success metric

* Giảm thời gian chuyển feedback thành danh sách nhiệm vụ từ mức ước lượng **20–30 phút xuống dưới 10 phút**.
* Ít nhất **95% góp ý** được chuyển thành nhiệm vụ hoặc được đánh dấu rõ là không cần xử lý.
* Mỗi nhiệm vụ có đủ:

  * Nội dung cần sửa.
  * Phần tài liệu liên quan.
  * Người phụ trách.
  * Mức độ ưu tiên.
  * Trạng thái hoàn thành.
* Không còn góp ý bị bỏ sót khi kiểm tra phiên bản cuối.
* Giảm số lần trưởng nhóm phải giải thích lại feedback cho thành viên.

## Non-AI alternative

* Sử dụng một mẫu ghi feedback thống nhất.
* Tạo bảng gồm các cột:

  * Feedback gốc.
  * Việc cần làm.
  * Người phụ trách.
  * Deadline.
  * Trạng thái.
  * Bằng chứng đã sửa.
* Cử một thành viên làm thư ký ghi feedback trong mỗi buổi.
* Trưởng nhóm và một thành viên khác kiểm tra chéo danh sách trước khi phân công.
* Dùng checklist cố định để bảo đảm không bỏ sót góp ý.

## AI hypothesis

AI có thể:

1. Đọc transcript, ghi chú hoặc comment của giảng viên.
2. Tách feedback thành từng ý độc lập.
3. Phân loại feedback theo phần của bài.
4. Đề xuất nhiệm vụ sửa tương ứng.
5. Gợi ý mức độ ưu tiên và tiêu chí hoàn thành.
6. Phát hiện các feedback có nội dung tương tự.
7. Tạo bản nháp task list để trưởng nhóm kiểm tra.

AI chỉ tạo **bản nháp**. Trưởng nhóm vẫn phải:

* Kiểm tra AI có hiểu đúng feedback không.
* Quyết định có thực hiện góp ý hay không.
* Chọn người phụ trách.
* Xác nhận nhiệm vụ đã được sửa đúng.

## Quick gut


Workflow

**Lý do:** Đây phù hợp với một workflow có AI hỗ trợ ở bước phân tích và cấu trúc hóa feedback. Chưa cần Agent tự phân công hoặc tự chỉnh sửa nội dung mà không có sự xác nhận của con người.

---

# Problem Card #2 — Phát hiện nội dung trùng hoặc mâu thuẫn

## Problem 1 câu

Khi ghép các phần do nhiều thành viên viết, nhóm khó phát hiện sớm những nội dung bị trùng lặp, mâu thuẫn hoặc sử dụng số liệu không thống nhất.

## Actor

* Người tổng hợp bài.
* Người review nội dung.
* Trưởng nhóm.
* Các thành viên viết từng phần của bài.

## Thời điểm / bối cảnh

Gần deadline, sau khi các thành viên hoàn thành phần việc riêng và gửi nội dung cho người tổng hợp ghép thành tài liệu hoàn chỉnh.

## Current workflow 3–7 bước

1. Mỗi thành viên viết phần được giao trong một tài liệu riêng hoặc một khu vực riêng.
2. Thành viên gửi nội dung cho người tổng hợp.
3. Người tổng hợp sao chép hoặc ghép các phần vào tài liệu chung.
4. Người tổng hợp đọc lại toàn bộ bài.
5. Người tổng hợp đánh dấu các đoạn có vẻ trùng hoặc mâu thuẫn.
6. Các thành viên trao đổi để xác định nội dung nào đúng.
7. Người tổng hợp sửa và kiểm tra lại phiên bản cuối.

## Bottleneck

Bước đọc chéo toàn bộ tài liệu để tìm các điểm không nhất quán.

Người review phải ghi nhớ nội dung của nhiều phần và so sánh:

* Hai đoạn có đang trình bày cùng một ý không.
* Các khái niệm có được định nghĩa giống nhau không.
* Số liệu giữa các phần có khớp không.
* Kết luận có mâu thuẫn với phần phân tích không.
* Thuật ngữ và tên gọi có được sử dụng thống nhất không.

Các lỗi thường chỉ được phát hiện sau khi đã ghép bài hoàn chỉnh, khi thời gian trước deadline còn ít.

## Impact

* Nội dung bài bị lặp, dài và thiếu liên kết.
* Số liệu hoặc lập luận không thống nhất làm giảm độ tin cậy.
* Người tổng hợp phải liên hệ lại nhiều thành viên để xác minh.
* Một số phần phải viết lại sát deadline.
* Nhóm có nguy cơ bỏ sót lỗi trong phiên bản nộp cuối.
* Điểm số có thể giảm vì bài thiếu tính nhất quán.

## Success metric

* Phát hiện ít nhất **90% đoạn trùng hoặc mâu thuẫn** trước vòng review cuối.
* Giảm thời gian kiểm tra tính nhất quán của tài liệu ít nhất **50%**.
* Mỗi cảnh báo phải chỉ rõ:

  * Hai vị trí đang liên quan.
  * Loại vấn đề.
  * Nội dung cần kiểm tra.
  * Mức độ chắc chắn của cảnh báo.
* Giảm số lỗi không nhất quán được phát hiện sau khi đã xuất bản nộp bài.
* Không tự động xóa hoặc thay đổi nội dung khi chưa được người review xác nhận.

Baseline về số lỗi và thời gian review cần được đo trên một hoặc hai bài nhóm gần nhất.

## Non-AI alternative

* Thống nhất outline trước khi bắt đầu viết.
* Quy định rõ phạm vi nội dung của từng thành viên.
* Sử dụng chung một glossary về thuật ngữ.
* Lưu số liệu trong một bảng nguồn duy nhất.
* Phân công hai thành viên review chéo.
* Dùng chức năng tìm kiếm từ khóa để kiểm tra các thuật ngữ và số liệu quan trọng.
* Sử dụng checklist review:

  * Trùng ý.
  * Trùng ví dụ.
  * Mâu thuẫn số liệu.
  * Mâu thuẫn kết luận.
  * Không thống nhất thuật ngữ.

## AI hypothesis

AI có thể đọc tài liệu đã ghép và tạo danh sách cảnh báo gồm:

1. Các đoạn có mức độ tương đồng cao.
2. Các phát biểu có khả năng mâu thuẫn.
3. Các số liệu khác nhau nhưng đang mô tả cùng một đối tượng.
4. Các thuật ngữ được sử dụng không thống nhất.
5. Các kết luận không được hỗ trợ bởi phần nội dung trước đó.
6. Các đoạn có thể cần người review kiểm tra lại.

AI chỉ nên **đánh dấu và giải thích**, không tự quyết định đoạn nào đúng hoặc tự động xóa nội dung.

Người review chịu trách nhiệm:

* Đọc lại ngữ cảnh.
* Kiểm tra nguồn số liệu.
* Xác định cảnh báo có chính xác không.
* Quyết định giữ, sửa hay xóa nội dung.

## Quick gut


Workflow


**Lý do không chọn làm #1:** AI có thể hỗ trợ so sánh ngữ nghĩa tốt hơn quy tắc tìm từ khóa đơn giản, nhưng quyết định cuối cần người review vì hai đoạn giống nhau chưa chắc đã dư thừa và hai phát biểu khác nhau chưa chắc đã mâu thuẫn.

---

# Problem Card #3 — Giúp thành viên bắt kịp tình hình dự án

## Problem 1 câu

Thành viên vắng họp hoặc tham gia nhóm muộn phải đọc lại nhiều tin nhắn và hỏi lại các thành viên khác mới có thể hiểu được trạng thái hiện tại của dự án.

## Actor

* Thành viên vắng buổi họp.
* Thành viên mới tham gia nhóm.
* Trưởng nhóm.
* Thành viên phải giải thích lại thông tin.

## Thời điểm / bối cảnh

Khi một thành viên:

* Vắng một hoặc nhiều buổi họp.
* Không theo dõi nhóm chat trong một khoảng thời gian.
* Được thêm vào nhóm sau khi dự án đã bắt đầu.
* Quay lại làm việc sau thời gian bận hoặc nghỉ.

## Current workflow 3–7 bước

1. Thành viên mở nhóm chat và đọc các tin nhắn chưa xem.
2. Thành viên tìm tài liệu hoặc đường dẫn được chia sẻ.
3. Thành viên cố xác định những quyết định đã được chốt.
4. Thành viên kiểm tra các nhiệm vụ đang được thực hiện.
5. Thành viên hỏi lại trưởng nhóm hoặc các thành viên khác.
6. Trưởng nhóm giải thích lại bối cảnh và thay đổi gần nhất.
7. Thành viên bắt đầu hoặc tiếp tục phần việc của mình.

## Bottleneck

Bước tìm và tổng hợp thông tin quan trọng từ nhiều tin nhắn, tài liệu và cuộc họp.

Thông tin thường bị trộn lẫn giữa:

* Thảo luận chưa chốt.
* Quyết định cuối cùng.
* Thay đổi yêu cầu.
* Phân công nhiệm vụ.
* Deadline.
* Đường dẫn tài liệu.
* Tin nhắn không liên quan đến công việc.

Thành viên hiện mất khoảng **20–30 phút** để bắt kịp tình hình, chưa tính thời gian của người phải giải thích lại.

## Impact

* Thành viên bắt đầu công việc chậm.
* Có nguy cơ thực hiện theo yêu cầu cũ.
* Những câu hỏi đã được giải đáp tiếp tục được hỏi lại.
* Trưởng nhóm phải dành thời gian lặp lại thông tin.
* Thành viên có thể bỏ sót quyết định quan trọng.
* Công việc mới có thể không liên kết với phần nhóm đã hoàn thành.
* Tiến độ chung bị ảnh hưởng khi nhiều người vắng hoặc không theo dõi thường xuyên.

## Success metric

* Giảm thời gian bắt kịp từ **20–30 phút xuống dưới 10 phút**.
* Thành viên xác định đúng:

  * Mục tiêu hiện tại.
  * Những quyết định đã chốt.
  * Việc đã hoàn thành.
  * Việc đang thực hiện.
  * Việc của bản thân.
  * Deadline tiếp theo.
* Giảm ít nhất **50% số câu hỏi lặp lại** sau khi thành viên quay lại.
* Mỗi thông tin quan trọng trong bản tóm tắt có liên kết tới tin nhắn hoặc tài liệu nguồn.
* Thành viên có thể tiếp tục công việc mà không cần trưởng nhóm giải thích lại toàn bộ dự án.

## Non-AI alternative

* Ghi meeting notes sau mỗi buổi họp.
* Ghim một tin nhắn “Project status” trong nhóm chat.
* Duy trì bảng gồm:

  * Quyết định mới nhất.
  * Người phụ trách.
  * Trạng thái nhiệm vụ.
  * Deadline.
  * Link tài liệu.
* Yêu cầu trưởng nhóm cập nhật changelog sau mỗi thay đổi quan trọng.
* Sử dụng một tài liệu onboarding ngắn cho thành viên mới.
* Tách các kênh thảo luận, thông báo và quyết định.

## AI hypothesis

AI có thể tạo bản tóm tắt “catch-up” theo khoảng thời gian hoặc theo lần truy cập cuối của thành viên, bao gồm:

1. Những thay đổi quan trọng.
2. Các quyết định đã được chốt.
3. Các nhiệm vụ mới, hoàn thành hoặc bị trễ.
4. Deadline sắp tới.
5. Nội dung có liên quan trực tiếp đến thành viên.
6. Các vấn đề chưa được giải quyết.
7. Liên kết về tin nhắn, tài liệu hoặc meeting note gốc.

AI cần phân biệt rõ:

* Nội dung đã chốt.
* Đề xuất đang thảo luận.
* Thông tin chưa được xác minh.

Thành viên vẫn phải mở nguồn gốc để kiểm tra trước khi thực hiện các quyết định quan trọng.

## Quick gut

Workflow


**Lý do không chọn làm #1:** Bài toán phù hợp với workflow thu thập dữ liệu và tạo bản tóm tắt theo yêu cầu. Chưa cần Agent tự tham gia thảo luận, tự đưa ra quyết định hoặc tự thay đổi nhiệm vụ của nhóm.
