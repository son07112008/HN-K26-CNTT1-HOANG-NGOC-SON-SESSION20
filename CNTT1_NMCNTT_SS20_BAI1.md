1. ký tự lạ & homograph attack
ký tự lạ: chữ ú (u có dấu) trong URL [https://githúb.com/login](https://githúb.com/login).

lý do đánh lừa: kẻ xấu dùng ký tự Unicode gần giống để lập tên miền giả mạo qua mắt thị giác, lừa nạn nhân nhập thông tin.

2. quy trình kiểm tra url
bằng mắt thường: soi kỹ từng ký tự ngay trước .com xem có bị gắn dấu hoặc biến tấu không.

bằng công cụ: dùng tính năng Auto-fill của Bitwarden (nếu web giả mạo, pass manager sẽ không tự điền vì lệch tên miền).