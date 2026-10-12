# Xây dựng Prioritized Product Backlog bằng kỹ thuật MoSCoW

## 1. Phân loại 12 hạng mục theo MoSCoW và Lý do

Dựa trên bối cảnh dự án, mục tiêu MVP (Release 1 dự kiến 3 sprint, năng lực 20 điểm) và các quy tắc MoSCoW, tôi tiến hành phân loại 12 hạng mục như sau:

| STT | Hạng mục | Công sức | MoSCoW | Lý do |
|---|---|---|---|---|
| 1 | Đăng nhập/đăng ký tài khoản độc giả | M (2) | Must Have | Là nền tảng cơ bản để độc giả có thể tương tác với hệ thống, mượn sách và thực hiện các thao tác cá nhân hóa khác. Không có tính năng này, hệ thống online không thể hoạt động. |
| 2 | Tìm kiếm sách theo tên/tác giả | M (2) | Must Have | Cần thiết để độc giả có thể tìm thấy sách mà họ muốn mượn. Thiếu tính năng này, việc mượn sách trở nên bất khả thi. |
| 3 | Mượn sách online (có giới hạn số sách mượn cùng lúc) | L (3) | Must Have | Là chức năng cốt lõi, định nghĩa của một hệ thống mượn sách online. Không có tính năng này, dự án không đạt được mục tiêu MVP. |
| 4 | Gia hạn mượn sách online | S (1) | Should Have | Quan trọng để tăng trải nghiệm người dùng và giảm sách quá hạn. Tuy nhiên, độc giả có thể liên hệ thủ thư để gia hạn thủ công như một giải pháp tạm thời trong MVP nếu tính năng này bị hoãn. Phụ thuộc vào hạng mục 3. |
| 5 | Đặt trước sách khi hết (kèm thông báo khi sách có sẵn) | M (2) | Must Have | Rất quan trọng để tối ưu hóa trải nghiệm mượn sách, đặc biệt với sách phổ biến. Nó hỗ trợ trực tiếp quy trình mượn sách, đảm bảo độc giả có thể tiếp cận sách khi có. Phụ thuộc vào hạng mục 3. |
| 6 | Đánh giá & bình luận sách sau khi đọc | M (2) | Could Have | Có giá trị trong việc xây dựng cộng đồng và giúp độc giả khác lựa chọn sách. Tuy nhiên, không phải là tính năng cốt lõi cho việc mượn/trả sách trong MVP. Phụ thuộc vào hạng mục 1 và 3. |
| 7 | Gợi ý sách theo sở thích cá nhân (recommendation) | L (3) | Won't Have (this time) | Là một tính năng nâng cao, đòi hỏi công sức lớn và không thiết yếu cho phiên bản đầu tiên. Có thể phát triển trong các bản phát hành sau để nâng cao trải nghiệm. |
| 8 | Thông báo email khi sắp đến hạn trả sách | S (1) | Should Have | Cải thiện trải nghiệm người dùng và giảm tỷ lệ sách trả muộn. Độc giả vẫn có thể tự theo dõi lịch trả sách nếu không có tính năng này. |
| 9 | Xem lịch sử mượn sách của bản thân | S (1) | Should Have | Giúp độc giả quản lý thông tin mượn trả của mình. Mặc dù không trực tiếp phục vụ việc mượn sách, đây là một tính năng mong đợi cho tài khoản cá nhân. Phụ thuộc vào hạng mục 1 và 3. |
| 10 | Thủ thư quản lý kho sách (thêm/sửa/xóa sách) | L (3) | Must Have | Chức năng thiết yếu để quản lý danh mục sách của thư viện. Không có nó, hệ thống không có dữ liệu sách để độc giả mượn. |
| 11 | Chat trực tiếp với thủ thư | L (3) | Won't Have (this time) | Là tính năng hỗ trợ tốt nhưng không cốt lõi cho MVP. Trong bản phát hành đầu tiên, độc giả có thể liên hệ thủ thư qua các kênh truyền thống khác (điện thoại, email). |
| 12 | Tích hợp đăng nhập bằng Google/Facebook | M (2) | Could Have | Tăng tiện lợi cho người dùng nhưng không bắt buộc vì đã có chức năng đăng nhập/đăng ký riêng của hệ thống. Đây là một cải tiến, không phải tính năng cốt lõi của MVP. Phụ thuộc vào hạng mục 1. |

## 2. Tổng điểm công sức của nhóm Must

*   **Các hạng mục Must Have:**
    *   1. Đăng nhập/đăng ký tài khoản độc giả (M - 2 điểm)
    *   2. Tìm kiếm sách theo tên/tác giả (M - 2 điểm)
    *   3. Mượn sách online (L - 3 điểm)
    *   5. Đặt trước sách khi hết (M - 2 điểm)
    *   10. Thủ thư quản lý kho sách (L - 3 điểm)
*   **Tổng số hạng mục Must Have:** 5 hạng mục.
*   **Tổng điểm công sức nhóm Must Have:** 2 + 2 + 3 + 2 + 3 = 12 điểm.

Năng lực của nhóm cho Release 1 là 20 điểm. Tổng công sức nhóm Must Have (12 điểm) nằm trong ngưỡng khoảng 60% năng lực Release 1 (12/20 điểm = 60%), đáp ứng đúng yêu cầu của bài tập.

## 3. Product Backlog có thứ tự duy nhất

Dựa trên phân loại MoSCoW và tôn trọng các phụ thuộc, Product Backlog được sắp xếp thứ tự như sau:

| Thứ tự | STT | Hạng mục | MoSCoW | Công sức |
|---|---|---|---|---|
| 1 | 1 | Đăng nhập/đăng ký tài khoản độc giả | Must Have | M (2) |
| 2 | 10 | Thủ thư quản lý kho sách (thêm/sửa/xóa sách) | Must Have | L (3) |
| 3 | 2 | Tìm kiếm sách theo tên/tác giả | Must Have | M (2) |
| 4 | 3 | Mượn sách online (có giới hạn số sách mượn cùng lúc) | Must Have | L (3) |
| 5 | 5 | Đặt trước sách khi hết (kèm thông báo khi sách có sẵn) | Must Have | M (2) |
| 6 | 9 | Xem lịch sử mượn sách của bản thân | Should Have | S (1) |
| 7 | 4 | Gia hạn mượn sách online | Should Have | S (1) |
| 8 | 8 | Thông báo email khi sắp đến hạn trả sách | Should Have | S (1) |
| 9 | 12 | Tích hợp đăng nhập bằng Google/Facebook | Could Have | M (2) |
| 10 | 6 | Đánh giá & bình luận sách sau khi đọc | Could Have | M (2) |
| 11 | 7 | Gợi ý sách theo sở thích cá nhân (recommendation) | Won't Have (this time) | L (3) |
| 12 | 11 | Chat trực tiếp với thủ thư | Won't Have (this time) | L (3) |

## 4. Tự phản biện

Mặc dù việc phân loại và sắp xếp ưu tiên đã tuân thủ các quy tắc, vẫn có thể có các lập luận khác cho một số hạng mục gây tranh cãi:

*   **Hạng mục 7 (Gợi ý sách theo sở thích cá nhân):** Tôi xếp vào "Won't Have". Tuy nhiên, một Product Owner khác có thể lập luận rằng tính năng gợi ý sách là cực kỳ quan trọng để thúc đẩy sự gắn kết của người dùng và tăng số lượng sách được mượn, biến nó thành một "Should Have" hoặc thậm chí là "Must Have" nếu mục tiêu chính là cá nhân hóa trải nghiệm ngay từ đầu. Họ có thể sẵn sàng cắt giảm một số tính năng "Should" hoặc "Could" để ưu tiên điều này.

*   **Hạng mục 12 (Tích hợp đăng nhập bằng Google/Facebook):** Tôi xếp vào "Could Have". Tuy nhiên, một Product Owner có thể lập luận rằng việc tích hợp đăng nhập qua mạng xã hội là một "Should Have" hoặc thậm chí là "Must Have" để giảm thiểu rào cản đăng ký, tăng tỷ lệ chuyển đổi người dùng mới và nâng cao trải nghiệm tiện lợi, đặc biệt trong bối cảnh các ứng dụng hiện đại. Họ có thể cho rằng sự tiện lợi này mang lại giá trị kinh doanh đáng kể hơn so với các tính năng "Should" khác.