# Phần 1: Phân tích lỗi
Nguyên nhân Auto TOC hỏng: Word quét mục lục dựa trên Heading Styles (metadata) chứ không nhìn hình thức hiển thị. Toàn bộ tiêu đề đang dùng định dạng thủ công (Normal), khiến Word bỏ qua.

Hậu quả nhầm cấp Heading: Làm sai lệch độ thụt lề trong mục lục (ví dụ H3 bị đẩy ra ngang hàng H2), phá vỡ cấu trúc logic tài liệu.

# Phần 2: Sửa lỗi & Nghiệm thu
Các bước gán lại Heading:

Dùng phím tắt Ctrl + Alt + 1 cho các dòng H1 (1., 2., 3.).

Dùng Ctrl + Alt + 2 cho các dòng H2 (1.1, 1.2, 2.1).

Dùng Ctrl + Alt + 3 cho dòng H3 (2.1.1).

Sau đó vào Mục lục, chọn Update Field → Update entire table.

Cập nhật số trang khi lệch trang:

Nhấn phím F9 (hoặc chuột phải chọn Update Field → Update page numbers only) để làm mới lại số trang chính xác.
