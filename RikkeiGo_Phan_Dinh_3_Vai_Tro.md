# PHÂN ĐỊNH LẠI 3 VAI TRÒ TRONG ĐỘI RIKKEIGO

## Phần 1 - Phân tích

| Quy ước | Đúng/Sai | Quyết định này thuộc về vai trò nào & vì sao | Triệu chứng ở Bối cảnh do quy ước này gây ra |
|---|---|---|---|
| QU1. Đức duyệt từng đoạn code và tự chọn thư viện bản đồ cho tính năng đặt xe | Sai | **Developers.** Cách triển khai kỹ thuật (chọn thư viện, kiểm tra code) là việc của Developers vì họ tự tổ chức và có chuyên môn kỹ thuật; Product Owner chỉ quyết định *làm gì* và *theo thứ tự nào*, không quyết định *làm thế nào*. | Có. Đức quá tải vì mọi đoạn code đều chờ anh duyệt; lập trình viên bị bắt làm theo cách kém hiệu quả vì thư viện do người không trực tiếp làm kỹ thuật chọn. |
| QU2. Trong Daily Scrum, Lan giao cụ thể ai làm thẻ việc nào | Sai | **Developers.** Daily Scrum là buổi họp của Developers để đồng bộ tiến độ và tự lập kế hoạch cho ngày làm việc; Scrum Master là người phục vụ (coach, gỡ rào cản, điều phối sự kiện) nên không ra lệnh hay phân công. | Có. Lập trình viên bị bắt làm theo cách kém hiệu quả vì người nhận việc do người khác chỉ định thay vì tự chọn theo năng lực và tình hình thực tế. |
| QU3. Đức sắp xếp thứ tự ưu tiên Product Backlog dựa trên giá trị mang lại cho người đặt xe | Đúng | **Product Owner.** Product Owner sở hữu Product Backlog, là người duy nhất quyết định thứ tự ưu tiên, và dùng giá trị mang lại cho người dùng làm căn cứ chính là đúng vai trò cầu nối giữa business và đội phát triển. | Không (quy ước đúng, giữ nguyên). |
| QU4. Developers tự đổi thứ tự hạng mục trong Product Backlog khi thấy tính năng khác dễ làm hơn | Sai | **Product Owner.** Thứ tự Product Backlog phải dựa trên giá trị, không dựa trên độ dễ làm; Developers có thể đề xuất nhưng quyền quyết định thuộc về Product Owner. | Không gây trực tiếp triệu chứng nào trong 2 triệu chứng đã nêu; đây là rủi ro khiến đội làm tính năng dễ thay vì tính năng có giá trị nhất. |

## Phần 2 - Vá lỗi

- **QU1 (viết lại):** Developers tự quyết định cách triển khai kỹ thuật (gồm chọn thư viện bản đồ và review code lẫn nhau), còn Đức chỉ làm rõ yêu cầu và tiêu chí chấp nhận của tính năng đặt xe.
- **QU2 (viết lại):** Trong Daily Scrum, Developers tự thống nhất ai làm thẻ việc nào trong ngày, còn Lan chỉ đảm bảo buổi họp diễn ra đúng timebox và hỗ trợ gỡ rào cản đội nêu ra.
- **QU4 (viết lại):** Developers có thể đề xuất đổi thứ tự hạng mục trong Product Backlog kèm lý do, nhưng chỉ Đức quyết định thứ tự cuối cùng dựa trên giá trị mang lại cho người đặt xe.

## Cách các quy ước viết lại gỡ 2 triệu chứng

- **Đức quá tải:** QU1 viết lại chuyển việc duyệt code và chọn thư viện về Developers nên Đức không còn là điểm nghẽn.
- **Lập trình viên bị bắt làm theo cách kém hiệu quả:** QU1 và QU2 viết lại trả quyền chọn cách làm và người nhận việc về cho Developers.
