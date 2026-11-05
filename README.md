# Điền từ đồng nghĩa TOEIC

Web điền từ từ 620 nhóm từ đồng nghĩa TOEIC. Mỗi nhóm là một câu: cho sẵn từ đầu và nghĩa tiếng Việt, bạn điền các từ còn lại theo gợi ý chữ cái đầu. Dấu gạch nối (ví dụ `up-to-date`) được hiện sẵn và tự điền khi bạn gõ tới vị trí đó.

## Chạy trên GitHub Pages
1. Tạo repo mới, upload `index.html`, `data.json` và `README.md`.
2. Vào **Settings → Pages**, chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`.
3. Mở `https://<tên-github>.github.io/<tên-repo>/`.

`index.html` đã chứa sẵn dữ liệu nên chạy độc lập. `data.json` là bản dữ liệu để bạn chỉnh sửa hoặc dùng lại.

## Sửa dữ liệu
Mỗi phần tử trong `data.json` có dạng `{"c": "chủ đề", "w": ["từ cho sẵn", "đồng nghĩa 1", ...], "vi": "nghĩa"}`. Sau khi sửa, dán nội dung mảng vào biến `const DATA = [...]` trong `index.html`.
