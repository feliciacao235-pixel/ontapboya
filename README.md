# Ôn tập Boya Chinese

Đây là website tĩnh để học viên ôn tập 30 bài Boya Chinese trên điện thoại, iPad hoặc máy tính.

## Nội dung

- `index.html`: trang chọn 5 bài ôn tập.
- `bai-01-06.html`: ôn tập Bài 01 đến 06.
- `bai-07-12.html`: ôn tập Bài 07 đến 12.
- `bai-13-18.html`: ôn tập Bài 13 đến 18.
- `bai-19-24.html`: ôn tập Bài 19 đến 24.
- `bai-25-30.html`: ôn tập Bài 25 đến 30.
- `reviews/ON_TAP_BOYA_BAI_01_06.html`: ôn tập Bài 01 đến 06.
- `reviews/ON_TAP_BOYA_BAI_07_12.html`: ôn tập Bài 07 đến 12.
- `reviews/ON_TAP_BOYA_BAI_13_18.html`: ôn tập Bài 13 đến 18.
- `reviews/ON_TAP_BOYA_BAI_19_24.html`: ôn tập Bài 19 đến 24.
- `reviews/ON_TAP_BOYA_BAI_25_30.html`: ôn tập Bài 25 đến 30.

Mỗi bài có 50 câu, tự chấm điểm trong trình duyệt và hiện giải thích đúng/sai sau khi nộp bài.

## Cách đưa lên GitHub

1. Tạo một repository mới trên GitHub.
2. Upload toàn bộ nội dung trong thư mục này lên repository đó.
3. Vào **Settings** của repository.
4. Chọn **Pages**.
5. Ở mục **Build and deployment**, chọn **GitHub Actions**.
6. Quay lại tab **Actions** và chờ workflow `Deploy static site to GitHub Pages` chạy xong.
7. Mở link GitHub Pages được tạo ra để kiểm tra trên điện thoại hoặc iPad.

## Cách chạy

Website không cần backend, không cần cài package và không cần build.

Sau khi đưa lên GitHub Pages, học viên chỉ cần mở link website.

Nếu muốn gửi thẳng một bài cho học viên, dùng link ngắn dạng:

- `/bai-01-06.html`
- `/bai-07-12.html`
- `/bai-13-18.html`
- `/bai-19-24.html`
- `/bai-25-30.html`

## Cập nhật bài ôn tập

Nếu sửa nội dung HTML:

1. Sửa file trong thư mục `reviews/`.
2. Commit và push lên nhánh `main`.
3. GitHub Actions sẽ tự deploy lại website.
