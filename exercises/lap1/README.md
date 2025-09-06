# Lap 1: Làm quen với môi trường lập trình Python

[Bài tập 1](#ex2_scientific1)
[Bài tập 2](#ex4_scientific2)

## ex2_scientific1

### Mục tiêu: Sinh N = 50 hình tròn ngẫu nhiên

- **Import thư viện**:
    - **numpy as np** để sinh số ngẫu nhiên và xử lý mảng.
    - **matplotlib.pyplot as plt** để vẽ.
    - **from IPython import display** hỗ trợ hiển thị trong notebook.

- **Sinh dữ liệu ngẫu nhiên**:
    - N = 50 — số điểm (hình tròn).
    - Các điểm (x, y), màu, diện tích.

- **Vẽ scatter plot**:
    - %matplotlib inline để đảm bảo hình hiển thị trong notebook.
    - plt.show() để hiển thị.

## ex4_scientific2

### Mục tiêu: Vẽ hai đồ thị cos(x) và sin(x) trên đoạn [-π, π].

- **Tạo dữ liệu**:
    - np.linspace(-np.pi, np.pi, 256) → tạo 256 điểm đều nhau trong khoảng từ -π đến +π.
    - Tính cos(x) và sin(x) cho mỗi điểm đó.

- **Kiểm tra dữ liệu**:
    - Kích thước mảng
    - Một vài mẫu đầu tiên.

- **Vẽ đồ thị**