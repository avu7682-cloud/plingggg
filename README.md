# CHEMFORCES // HÓA 11 KẾT NỐI TRI THỨC (10 CHALLENGES VAULT)

Bộ mã nguồn tĩnh đã được đóng gói sẵn (Single-File Encrypted Vault) để host miễn phí trên **GitHub Pages**.

## Cách đưa lên GitHub Pages trong 60 giây:

1. Đăng nhập vào [GitHub.com](https://github.com) và bấm **New repository** (tạo repo mới, đặt tên tuỳ ý ví dụ `chem-challenge`, chọn **Public**).
2. Bấm vào **uploading an existing file** (hoặc kéo thả file).
3. Giải nén file `chemforces-github-deploy.zip` này và kéo toàn bộ 3 file (`index.html`, `.nojekyll`, `README.md`) vào repo rồi bấm **Commit changes**.
4. Vào mục **Settings** của repository -> chọn tab **Pages** (menu bên trái).
5. Tại mục **Build and deployment** -> **Branch**, chọn nhánh `main` (hoặc `master`) và thư mục `/ (root)` -> bấm **Save**.
6. Đợi khoảng 30-60 giây, GitHub sẽ cấp cho bạn đường link dạng `https://<ten-github-cua-ban>.github.io/<ten-repo>/` để gửi cho bạn bè!

## Cơ chế bảo mật chống F12 / Inspector:
- Bức ảnh gốc đã được cắt thành 10 mảnh (lưới 5×2) và mã hóa nhị phân bằng thuật toán **SHA-256-CTR Stream Cipher** kết hợp **4.000 vòng Key Stretching** từ đáp án của 10 câu hỏi Hóa học 11.
- Không có bất kỳ file ảnh gốc hay chuỗi đáp án plaintext nào tồn tại trong mã nguồn trang web.
- Bắt buộc nộp ảnh chụp bài giải viết tay (có kiểm tra chống ảnh AI, chống ảnh chụp màn hình và chống nộp trùng ảnh) trước khi chấm từng câu.
