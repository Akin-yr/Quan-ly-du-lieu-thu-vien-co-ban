# 📚 Hệ thống Quản lý Sách Đơn giản (Simple Book Management System)

Dự án này là một ứng dụng quản lý sách cơ bản được phát triển bằng C++, cho phép người dùng thực hiện các thao tác quản lý dữ liệu sách như hiển thị danh sách, tìm kiếm, cập nhật thông tin và liệt kê sách theo năm xuất bản.

--------------------------------------------------------------------------------------------------------------------------

## 🚀 Tính năng chính

* **Đọc dữ liệu từ file:** Đọc thông tin sách từ file `input.txt` để khởi tạo cơ sở dữ liệu.
* **Hiển thị danh sách sách:** Liệt kê toàn bộ thông tin các cuốn sách hiện có.
* **Tìm kiếm nâng cao:** Cho phép tìm kiếm sách theo mã sách, tên sách, tác giả hoặc năm xuất bản (không phân biệt chữ hoa/thường).
* **Cập nhật số lượng sách:** Cập nhật số lượng của một cuốn sách cụ thể dựa trên mã sách.
* **Liệt kê sách cùng năm xuất bản:** Hiển thị các cuốn sách được xuất bản trong cùng một năm.

--------------------------------------------------------------------------------------------------------------------------

## 🛠️ Công nghệ sử dụng

* **Ngôn ngữ:** C++
* **Môi trường phát triển:** Mọi IDE hỗ trợ C++ (ví dụ: Visual Studio Code, Code::Blocks, Dev-C++)

--------------------------------------------------------------------------------------------------------------------------

## 📦 Cấu trúc dự án

├── main.cpp                # Source code chính của chương trình
├── input.txt               # File chứa dữ liệu đầu vào (danh sách sách)
└── README.md               # File mô tả dự án (bạn đang đọc đây!)

--------------------------------------------------------------------------------------------------------------------------

## 📝 Cách sử dụng

Để chạy chương trình, bạn cần thực hiện các bước sau:

1.  **Clone repository về máy tính của bạn:**
    ```bash
    git clone [https://github.com/Tên_GitHub_của_bạn/Tên_repo_của_bạn.git](https://github.com/Tên_GitHub_của_bạn/Tên_repo_của_bạn.git)
    cd Tên_repo_của_bạn
    ```
    *(Hãy thay thế `Tên_GitHub_của_bạn` và `Tên_repo_của_bạn` bằng thông tin thực tế của bạn)*

2.  **Chuẩn bị file `input.txt`:**
    Chương trình đọc dữ liệu sách từ file `input.txt`. Mỗi cuốn sách sẽ có 5 dòng thông tin theo thứ tự:
    * Mã sách
    * Tên sách
    * Tác giả
    * Năm xuất bản
    * Số lượng (số nguyên)

    **Ví dụ file `input.txt`:**
    ```
    MS001
    Toan Hoc Cao Cap A1
    Nguyen Van A
    2020
    15
    MS002
    Lap Trinh Huong Doi Tuong
    Tran Thi B
    2021
    10
    MS003
    Co So Du Lieu
    Le Van C
    2020
    20
    ```
    *(Lưu ý: Bạn cần tạo file `input.txt` này trong cùng thư mục với file `main.cpp`.)*

3.  **Biên dịch và chạy chương trình:**
    Sử dụng trình biên dịch C++ (ví dụ: g++):
    ```bash
    g++ main.cpp -o book_management
    ./book_management
    ```
    Sau khi chạy, chương trình sẽ hiển thị danh sách sách, sau đó cho phép bạn thực hiện các thao tác tìm kiếm, cập nhật và liệt kê sách.

--------------------------------------------------------------------------------------------------------------------------

## 💡 Hướng phát triển tiếp theo (Future Improvements)

Dự án này có thể được mở rộng với các tính năng sau:

* **Thêm/Xóa sách:** Chức năng để thêm một cuốn sách mới hoặc xóa một cuốn sách hiện có.
* **Lưu dữ liệu:** Ghi dữ liệu danh sách sách đã cập nhật trở lại vào file (`output.txt` hoặc cập nhật `input.txt`).
* **Giao diện người dùng:** Phát triển giao diện người dùng đồ họa (GUI) thay vì giao diện dòng lệnh.
* **Sắp xếp:** Sắp xếp danh sách sách theo tên, tác giả, năm xuất bản, v.v.
* **Tối ưu hóa tìm kiếm:** Áp dụng các thuật toán tìm kiếm hiệu quả hơn (ví dụ: tìm kiếm nhị phân nếu dữ liệu được sắp xếp).
* **Xử lý lỗi mạnh mẽ hơn:** Bắt và xử lý các trường hợp lỗi nhập liệu hoặc file không hợp lệ một cách chi tiết hơn.
* **Thêm hàm ghi file vào một file output**

--------------------------------------------------------------------------------------------------------------------------

## ✉️ Liên hệ

Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào về dự án, đừng ngần ngại liên hệ với tôi qua:
* **Email:** [ralandotutrinh0576@gmail.com](mailto:ralandotutrinh0576@gmail.com)
* **LinkedIn:** [Ra Lan Đỗ Tú Trinh](https://www.linkedin.com/in/ra-lan-do-tu-trinh-199217279/)
--------------------------------------------------------------------------------------------------------------------------
