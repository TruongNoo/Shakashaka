# Shakashaka Puzzle Solver

## Giới thiệu

Đây là một ứng dụng Python giúp giải các câu đố Shakashaka. Shakashaka là một loại câu đố logic trên một lưới hình vuông, trong đó bạn phải xác định mỗi ô có màu đen hay trắng và cách chúng kết nối với nhau.

## Cách sử dụng

1. **Chạy ứng dụng**: Chạy script `Shakashaka.py` để mở giao diện ứng dụng.
2. **Nhập dữ liệu**: Nhập ma trận `A` và ma trận `B` vào các biến tương ứng. Ma trận `A` chứa các kí tự mô tả màu sắc và các loại cạnh của mỗi ô, trong khi ma trận `B` chứa các số xác định số lượng các ô đen xung quanh mỗi ô trắng.
3. **Giải puzzle**: Nhấn nút "Solve" để giải puzzle. Kết quả sẽ được hiển thị trên cửa sổ ứng dụng.

## Yêu cầu

- Python 3.x
- Tkinter
- NumPy
- Thư viện Gurobi: `pip install gurobipy`

## Cấu trúc mã

- `Shakashaka.py`: Chứa mã chính của ứng dụng.
- `linear_programming.py`: Chứa hàm giải bài toán tối ưu sử dụng thư viện Gurobi.
- `example_puzzles.py`: Một số ví dụ về ma trận `A` và `B` cho các câu đố Shakashaka.

## Tham khảo

- [Shakashaka Puzzle Solver](https://github.com/TruongNoo/Shakashaka.git): Repository GitHub của dự án.

## Tác giả

- **Nhóm 3 thành viên**: Đã tạo dự án và phát triển mã nguồn.

## Bản quyền

Dự án được phát hành dưới [Giấy phép MIT](LICENSE).
