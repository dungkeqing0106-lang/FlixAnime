# FlixAnime Web – MangoTV-inspired interface

Giao diện mới lấy cảm hứng từ bố cục ứng dụng streaming: nền tối, banner phim 16:9 có nút chuyển và vuốt trên điện thoại, danh sách phim dạng poster ngang, Top 10, Romance, Sports, phim lẻ/bộ, menu kính mờ và thanh điều hướng dưới trên mobile.

## Chạy và triển khai
Mở `index.html` qua máy chủ web hoặc deploy toàn bộ thư mục lên Cloudflare Pages, GitHub Pages, Netlify hay hosting HTTPS. Trên iPhone mở Safari → Chia sẻ → Thêm vào Màn hình chính.

## Dữ liệu và tài khoản
Danh sách demo gọi AniMapper API qua tìm kiếm anime. Kết quả phụ thuộc API, CORS và dữ liệu trả về. Profile, avatar, yêu thích và lịch sử hiện lưu cục bộ trên trình duyệt của thiết bị; form đăng nhập không xác thực tài khoản thật. Muốn đăng ký/đăng nhập đa thiết bị cần backend và cơ sở dữ liệu.

## Phát phim
Luồng phát thử dùng provider `ANIMEVIETSUB`, ưu tiên HDX. Khả năng có Vietsub và phát được phụ thuộc từng tập/host; không đảm bảo mọi phim có nguồn. Tích hợp hiện thử nghiệm và không vượt DRM, paywall, đăng nhập hoặc cơ chế bảo vệ.

## Nguồn
https://animevietsub.best · https://animapper.net/docs/providers/animevietsub/


## Giao diện web mới
Bản hiện tại đã bỏ sidebar bên trái. Thanh điều hướng 5 mục được thiết kế dạng viên thuốc bo cong, kính mờ, cố định phía dưới như dock trên iPhone. Trang web tự co giãn trên điện thoại, tablet và máy tính.
