## Thành viên nhóm:
| STT | Họ tên | MSSV | 
| :---: | --- | --- |
| 1 | Phan Minh Nhật | 19521956 |
| 2 | Lê Võ Tiến Phát | 19521993 |   
| 3 | Hồ Thịnh | 19522274 | 

## Bài tâp: Tìm các ví dụ về bài toán regression trong thực tế.
### Ví dụ 1: Dự đoán cân nặng thông qua chiều cao của người đó.
Input: Chiều cao(đơn vị: cm; kiểu dữ liệu: float).

Output: Cân nặng(đơn vị: kg; kiểu dữ liệu: float).

Thu thập dữ liệu: 
- Lấy thông tin tại các cơ sở y tế.

- Tạo form để mọi người có thể điền các thông tin: chiều cao, cân nặng.

Xử lí dữ liệu:
- Gom các dữ liệu vào một file CSV. 

- Loại bỏ các dòng mà thuộc tính không có giá trị(Null).

- Loại bỏ các dòng mà thuộc tính có giá trị bất thường (Ví dụ: số âm, số quá nhỏ, số quá lớn).
### Ví dụ 2: Dự đoán tiền lương của một giáo viên.
Input: Tuổi nghề(đơn vị: năm; kiểu dữ liệu: int), học hàm,học vị của giáo viên đó (0: Cử nhân, 1: Giáo sư, 2: Tiến sĩ,...).

Output: Lương của giáo viên đó (đơn vị: đồng; kiểu dữ liệu: int).

Thu thập dữ liệu: 
- Thu thập dữ liệu ở các ngôi trường.
- Hoặc tạo form để các giáo viên điền các thông tin cần thiết vào.

Xử lí dữ liệu:
- Gom các dữ liệu vào một file CSV. 

- Loại bỏ các dòng mà thuộc tính không có giá trị(Null).

- Loại bỏ các dòng mà thuộc tính có giá trị bất thường (Ví dụ: số âm, số quá lớn,...)

### Ví dụ 3: Dự đoán tỉ lệ mua hàng của một người đối với một món hàng cụ thể.
Input: Độ tuổi(kiểu dữ liệu: int), giới tính(0: Nam, 1: Nữ), thu nhập(đơn vị: đồng, kiểu dữ liệu: int).

Output: Tỉ lệ mua hàng(kiểu dữ liệu: float).

Thu thập dữ liệu: Tạo form để mọi người điền các thông tin cần thiết vào.

Xử lí dữ liệu:
- Gom các dữ liệu vào một file CSV. 

- Loại bỏ các dòng mà thuộc tính không có giá trị(Null).

- Loại bỏ các dòng mà thuộc tính có giá trị bất thường (Ví dụ: số âm, giá trị khác 0 và 1 ở thuộc tính giới tính)

