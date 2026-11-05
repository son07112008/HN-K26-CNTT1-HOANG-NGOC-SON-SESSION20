1. báo cáo phân tích (ipo)
input: mã dự phòng (backup codes) được lưu trữ ngoại tuyến từ trước.
process:

dùng một mã dự phòng chưa xài để đăng nhập vào aws.

hủy ngay mã vừa dùng và vô hiệu hóa thiết bị 2fa cũ.

cài app authenticator trên thiết bị mới, bật lại 2fa và tạo bộ backup codes mới.

output: hệ thống aws được bảo vệ an toàn, khôi phục quyền quản trị cho lead developer.

2. vì sao không được lưu backup codes dưới dạng ảnh trong máy?
nếu điện thoại mất khóa màn hình hoặc bị kẻ gian lấy được, ảnh chụp chứa danh sách backup codes sẽ lộ nguyên văn dưới dạng plaintext, giúp kẻ gian đăng nhập aws dễ dàng.

nếu ảnh bị tự động đồng bộ lên cloud hoặc máy dính mã độc infostealer, toàn bộ mã dự phòng sẽ bị trộm từ xa, làm mất tác dụng của lớp 2fa.