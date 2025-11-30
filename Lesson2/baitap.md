# Tổng hợp bài tập về hàm trong Python, bao gồm các phần từ cơ bản đến nâng cao.
## Phần 1: Hàm không trả về (chỉ in hoặc làm gì đó - kiểu void)
1. Viết hàm in_hello() in ra dòng chữ "Hello World"  
→ Gọi hàm 3 lần.
2. Viết hàm in_bang_cu_chuong(n) in bảng cửu chương của số n (từ 1 → 10).
3. Viết hàm ve_tam_giac_can(h) in tam giác cân bằng dấu *, ví dụ h=4:
```bash
   *
  ***
 *****
*******
```
## Phần 2: Hàm có trả về (return)
1. Viết hàm binh_phuong(x) trả về x².
2. Viết hàm tong_2_so(a, b) trả về tổng a + b.
3. Viết hàm chu_vi_hinh_vuong(canh) trả về chu vi hình vuông.
4. Viết hàm la_so_duong(n) trả về True nếu n > 0, False nếu không.
   
## Phần 3: Hàm có tham số mặc định (default parameter)

1. Viết hàm chao(name="bạn") in ra "Xin chào, [name]!"
2. Viết hàm tinh_luy_thua(x, mu=2) trả về x^mu (mặc định là bình phương).
3. Viết hàm mua_hang(ten, so_luong=1, don_gia=10000) trả về tổng tiền.

## Phần 4: Hàm với *args (nhận số lượng tham số bất kỳ)

1. Viết hàm tong_tat_ca(*numbers) nhận bao nhiêu số cũng được và trả về tổng.
2. Viết hàm tich_cac_so(*args) trả về tích của tất cả các số truyền vào.
3. Viết hàm in_cac_so(*args) chỉ in lần lượt từng số ra màn hình (mỗi số 1 dòng).
4. Viết hàm tim_max(*args) trả về số lớn nhất trong các số truyền vào (không dùng max()).

## Phần 5: Hàm với **kwargs (nhận tham số có tên)

1. Viết hàm in_thong_tin(**info) in từng cặp key-value.
2. Gọi thử: in_thong_tin(ho="Nguyen", ten="An", tuoi=20)
3. Viết hàm tao_sinh_vien(ten, **mon_hoc) trả về điểm trung bình.
Ví dụ: tao_sinh_vien("Lan", Toan=8, Ly=7.5, Hoa=9)

## Phần 6: Kết hợp *args và **kwargs
1. Viết hàm ban_tin(msg, *names, **options)  
in lần lượt chào từng tên trong names  
nếu có sep=" | " thì dùng dấu đó để ngăn cách
Ví dụ:
```python
ban_tin("Chào các bạn", "An", "Bình", "Cường", sep=" +++ ")
# Chào các bạn An +++ Bình +++ Cường
```
## Phần 7: Hàm lambda (hàm vô danh) - cơ bản nhất
1. Dùng lambda viết hàm tính lập phương (x³).
2. Dùng lambda + map() để chuyển list độ C sang độ F (F = C×1.8 + 32)
```python
do_c = [0, 20, 30, 100]
# → [32.0, 68.0, 86.0, 212.0]
```
Dùng lambda + filter() để lấy ra tất cả số chẵn từ list
```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
# → [2, 4, 6, 8, 10]
```

Dùng google colab để làm bài tập này : https://colab.research.google.com/