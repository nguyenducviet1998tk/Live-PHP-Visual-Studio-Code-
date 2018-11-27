# Live-PHP-Visual-Studio-Code-

File liên kết giữa extensions Live Server &amp; PHP Server

### Yêu cầu cài đặt:

    * [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
    * Server PHP bất kỳ [PHP Server](https://marketplace.visualstudio.com/items?itemName=brapifra.phpserver)

### Hướng dẫn:

    B1: Tải file index.html bỏ vào thư mục PHP cần chạy.

    B2: Coppy: [ echo "<script> parent.postMessage(location.pathname+location.search,'http://127.0.0.1:5500');</script>"; ]
    vào các file PHP cần Live.

    B3: Chạy Server PHP tương ứng và Go Live.
