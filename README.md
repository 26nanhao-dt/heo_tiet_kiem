# Ống Heo

Ứng dụng quản lý thu chi cá nhân, chạy trên trình duyệt và lưu dữ liệu trong `localStorage` của thiết bị.

## Chạy thử

Mở `ong-heo.html` trên trình duyệt. Để cài ứng dụng hoặc dùng ngoại tuyến, hãy chạy trang qua HTTPS hoặc localhost; service worker không chạy khi mở bằng `file://`.

## Deploy lên Render

Repo có sẵn `render.yaml` để Render build thành static site. Sau khi đẩy repo lên GitHub, tạo Static Site từ repo này trên Render hoặc tạo Blueprint từ `render.yaml`.

## Dữ liệu

Dữ liệu giao dịch lưu cục bộ trong trình duyệt. Mỗi người dùng cần tự xuất file JSON để sao lưu; deploy trang web không đồng bộ dữ liệu giữa các thiết bị.
