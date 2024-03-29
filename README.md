# Muc luc

## [1. Gioi thieu ve git](docs/git.md)
## [2. cac thuat ngu cua git](docs/git_terms.md)
## demo
## 5. Demo: Tải và Cài đặt Git từ Đầu

Trong phần demo này, chúng ta sẽ đi qua các bước để tải về và cài đặt Git trên máy tính của bạn, sau đó thực hiện một số lệnh cơ bản để khởi tạo một repository Git mới.

### Bước 1: Tải Git

1. **Truy cập trang web chính thức của Git**
   - Mở trình duyệt web và truy cập vào [https://git-scm.com/](https://git-scm.com/).
   
2. **Tải xuống**
   - Nhấp vào nút "Download" để tải xuống phiên bản Git mới nhất cho hệ điều hành của bạn.

### Bước 2: Cài đặt Git

1. **Mở file cài đặt**
   - Sau khi tải xuống, mở file cài đặt Git (.exe, .dmg, hoặc .sh tùy thuộc vào hệ điều hành).
   
2. **Chạy trình cài đặt**
   - Thực hiện theo các bước trong trình cài đặt. Đối với người dùng Windows, bạn có thể chọn các tùy chọn mặc định. Người dùng macOS và Linux thường cần chạy qua Terminal.
   
3. **Kiểm tra việc cài đặt**
   - Mở Terminal hoặc Command Prompt và nhập `git --version` để xác nhận Git đã được cài đặt thành công.

### Bước 3: Cấu hình Git

1. **Thiết lập tên người dùng và email**
   - Mở Terminal hoặc Command Prompt.
   - Đặt tên người dùng của bạn bằng cách nhập `git config --global user.name "Tên của bạn"`.
   - Đặt email của bạn bằng cách nhập `git config --global user.email "email@của bạn"`.
   
2. **Kiểm tra cấu hình**
   - Kiểm tra các cấu hình hiện tại bằng lệnh `git config --list`.

### Bước 4: Khởi tạo một Repository mới

1. **Tạo một thư mục mới** (nếu cần)
   - Sử dụng lệnh `mkdir ten-du-an` để tạo một thư mục mới cho dự án của bạn.
   
2. **Di chuyển vào thư mục dự án**
   - Sử dụng lệnh `cd ten-du-an` để chuyển vào thư mục dự án bạn vừa tạo.
   
3. **Khởi tạo repository**
   - Trong thư mục dự án, nhập `git init` để khởi tạo một repository Git mới.
   
4. **Thêm file vào repository** (tùy chọn)
   - Sử dụng lệnh `git add <file_name>` để thêm các file vào staging area.
   - Hoặc sử dụng `git add .` để thêm tất cả các file trong thư mục hiện tại.
   
5. **Commit thay đổi**
   - Sử dụng lệnh `git commit -m "Thông điệp commit"` để lưu các thay đổi vào repository.

Lưu ý: Đảm bảo rằng bạn đã đặt tên và email trong cấu hình Git trước khi thực hiện commit đầu tiên.
