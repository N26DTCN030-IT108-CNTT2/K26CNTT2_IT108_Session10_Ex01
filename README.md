# K26CNTT2_IT108_Session10_Ex01
### 1. Tại sao định dạng thủ công lại gây ra lỗi mục lục trống?
- **Nguyên lý hoạt động của Auto TOC:** Chức năng tạo mục lục tự động (Auto TOC) trong Google Docs chỉ quét và thu thập các đoạn văn bản được gán nhãn **Heading Styles** (Heading 1, Heading 2, Heading 3,...).
- **Lỗi sai của Nam:** Nam chỉ thay đổi hình thức bên ngoài (phóng to chữ size 20, 18, in đậm) nhưng về mặt bản chất hệ thống, các tiêu đề đó vẫn mang nhãn Normal text. Do đó, công cụ Auto TOC không nhận diện được đâu là tiêu đề để đưa vào bảng mục lục, dẫn đến thông báo lỗi *"No table of contents entries found"*.
- **Hậu quả bổ sung:** Khi cần thay đổi màu sắc hay định dạng chung cho toàn bộ tiêu đề, Nam phải đi sửa thủ công từng trang một thay vì chỉ cần cập nhật Style đại diện.

### 2. Nguyên nhân đoạn văn dài 5 trang bị hiện lên mục lục
- **Lỗi gán nhãn sai:** Nam đã vô tình bôi đen toàn bộ đoạn văn bản dài 5 trang đó và chọn gán cho nó nhãn **Heading 1** thay vì nhãn **Normal**.
- **Hậu quả:** Hệ thống Auto TOC sẽ hiểu toàn bộ 5 trang văn bản đó là một "Tiêu đề lớn" và trích xuất nguyên cả đoạn văn đó hiển thị vào bảng mục lục.
