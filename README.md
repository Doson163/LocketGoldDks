# Bản sao cấu hình của Doson163

Nguồn: dinhduyvinh09/AppPre, bản ZIP commit 7a39081d901ff8d27dcbd21cd6f212c5473d936c.
Giữ nguyên ghi công tác giả và nội dung JavaScript trong ZIP.

## Cách đưa lên GitHub

1. Tạo repository PUBLIC trong tài khoản Doson163, tên chính xác LocketGoldDks, nhánh main.
2. Giải nén gói này. Upload NỘI DUNG thư mục LocketGoldDks vào gốc repo:
   All_In_One.conf, All_In_One.sgmodule, thư mục js và assets, cùng README.md và SHA256.json.
   Không upload riêng file ZIP; không đặt thêm một thư mục LocketGoldDks bao ngoài.
3. Sau khi commit, mở hai URL:
   https://raw.githubusercontent.com/Doson163/LocketGoldDks/main/All_In_One.conf
   https://raw.githubusercontent.com/Doson163/LocketGoldDks/main/All_In_One.sgmodule
4. Nếu tiếp tục dùng hai Gist/TinyURL hiện tại: dán toàn bộ nội dung cấu hình tương ứng
   từ gói này vào Gist cũ rồi lưu. Các script sẽ tải từ repo mới.
   configUrl/moduleUrl trong gói được đặt về repo mới.
5. Nếu TinyURL vốn trỏ đến một revision Gist cụ thể, sửa Gist sẽ không đổi nội dung
   tại revision đó; cần dùng URL Raw không có revision hoặc cập nhật đích TinyURL.

## Các thay đổi

- Đổi script-path của AppPre từ repo tác giả sang Doson163/LocketGoldDks/main.
- Đổi configUrl/moduleUrl và icon sang repo mới.
- Tắt ba mục Sub-Store: chúng dùng release latest từ repo ngoài và mã không có trong ZIP.
  Muốn bật lại, cần sao lưu riêng ba script và đổi đường dẫn trước.
- Không thay đổi JavaScript, quy tắc xử lý request/response hoặc danh sách MITM.
- Không sao chép website, workflow tự động hay các profile mobileconfig vì hai cấu hình không cần chúng.

## Giới hạn kiểm tra

Đã đối chiếu mọi script-path đang bật với tệp có thật trong gói và kiểm tra SHA-256
các tệp JavaScript khớp ZIP gốc. Đây là kiểm tra tệp và đường dẫn, chưa chạy trên Shadowrocket.
Một số JavaScript bị làm rối mã, chưa kiểm chứng hết hành vi hay URL được ghép khi chạy.
Các endpoint dịch vụ và tài nguyên bên ngoài vẫn có thể thay đổi; bản sao code không bảo đảm
các tính năng luôn hoạt động. Không thiết lập đồng bộ tự động với repo gốc.

Nếu chọn tên repo/nhánh khác, thay tiền tố
https://raw.githubusercontent.com/Doson163/LocketGoldDks/main/
trong cả hai cấu hình bằng địa chỉ tương ứng.
