# Tải truyện tranh

Một user script để lưu trữ lại các truyện tranh từ các trang truyện trực tiếp trên trình duyệt.

Dự án này được phát triển dựa trên [lelinhtinh/Userscript](https://github.com/lelinhtinh/Userscript/tree/master/manga_comic_downloader) (Nay đã được `archived`). Bản thân script cũ cũng đã hoạt động đúng ý mình rồi, nên phiên bản này chỉ có thêm một số cải thiện nhỏ:

- Cập nhật lại tên miền.
- Xóa toàn bộ các trang NSFW cũng như các trang đã không còn được duy trì.

## Cách cài đặt

Bạn có thể hiểu Userscript là một đoạn lệnh được viết ra để thực hiện một nhiệm vụ bất kì, và cần có một tiện ích trình duyệt khác để chạy đoạn lệnh đó: `Violentmonkey` hoặc `Tampermonkey` *(chỉ cài 1 trong 2)*.

### Cài đặt user script manager

-   Chrome: [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) or [Violentmonkey](https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag)
-   Firefox: [Greasemonkey](https://addons.mozilla.org/firefox/addon/greasemonkey/), [Tampermonkey](https://addons.mozilla.org/firefox/addon/tampermonkey/), or [Violentmonkey](https://addons.mozilla.org/firefox/addon/violentmonkey/)

### Cài đặt script để tải truyện tranh

Hiện tại thì mình chưa đăng lên trên các nền tảng, bạn có thể tải phần script cũ, sau đó mở tệp [taitruyentranh.js](taitruyentranh.user.js) và copy toàn bộ nội dung vào đó.

Cài script gốc tại [OpenUserJS](https://openuserjs.org/scripts/baivong/manga_comic_downloader), hoặc [SleazyFork](https://sleazyfork.org/scripts/369802-manga-comic-downloader).

## Hướng dẫn

### Cơ bản

- Vào trang đọc truyện tranh, phần danh sách truyện.
- Right-click lên liên kết chương truyện cần tải *(Hoặc Hold nếu dùng mobile)*.
- Nhấn tổ hợp phím `Alt+Y` hoặc chọn **Download All Chapters** từ Scripts commands để tải toàn bộ.

### Nâng cao

- **Bỏ qua chương**: Hold phím `Ctrl+Shift` và Click lên liên kết, sau đó khi tải toàn bộ, những chương này sẽ bị bỏ qua.
- **Tải nhiều chương**: Hold phím `Ctrl` và Click lên liên kết, khi thả phím `Ctrl` ra việc tải sẽ bắt đầu, chỉ những chương vừa chọn và theo thứ tự đã Click.
- **Gộp nhiều chương**: Tương tự **Tải nhiều chương**, thay phím `Ctrl` bằng `Shift`. Những chương đã chọn sẽ được gộp vào chung một file khi tải.
- **Gộp toàn bộ**: Nhấn tổ hợp phím `Shift+Alt+Y` hoặc chọn **Download All To One File** từ Scripts commands để tải toàn bộ vào một file duy nhất.

## Lưu ý

- Chỉ có thể tải một chương truyện mỗi lần, bạn cần phải đợi tiến trình hiện tại hoàn thành. Sau đó mới có thể tải chương truyện khác.
- Vì script yêu cầu quyền truy cập nội dung trên mọi trang web *(`@connect *`)* nên **Tampermonkey** sẽ có hiện cảnh báo. Chọn **Always allow all domains** để bỏ qua.

### Danh sách host hỗ trợ

- <http://www.nettruyenx.net/>
- <http://www.hamtruyentranh.net/>
- <https://truyensieuhay.com/>
- <http://truyenqqgo.com/>
- <http://tuthienbao.com/>
- <https://vietcomic.net/>
- <https://truyenvn.shop/>


