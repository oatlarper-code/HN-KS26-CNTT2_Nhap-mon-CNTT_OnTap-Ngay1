# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Nguyễn Hoàng Minh Phúc
- **Lớp:** CNTT2
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** Window

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```
..Downloads\trung-tam-tieng-anh> pwd
..Downloads\trung-tam-tieng-anh> ls -force
..Downloads\trung-tam-tieng-anh> mv .\Lich_Hoc.txt .\docs\
..Downloads\trung-tam-tieng-anh> mv .\Logo_Trung_Tam.PNG, .\Anh_Lop_Hoc.JPG .\media\
..Downloads\trung-tam-tieng-anh> cp .\media\Logo_Trung_Tam.PNG .\archive\
..Downloads\trung-tam-tieng-anh> cd .\logs\
..Downloads\trung-tam-tieng-anh\logs> gc .\Access.log
..Downloads\trung-tam-tieng-anh\logs> cd ..
..Downloads\trung-tam-tieng-anh> rm *.tmp
..Downloads\trung-tam-tieng-anh> cd .\docs\
..Downloads\trung-tam-tieng-anh\docs> cp ..\media\Anh_Lop_Hoc.JPG ..\archive\; cd..
..Downloads\trung-tam-tieng-anh> Get-ChildItem -Recurse -Force
```

### Kết quả B1 (pwd)

```
Path
----
C:\Users\My Laptop\Downloads\trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```


    Directory: C:\Users\My Laptop\Downloads\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          20/10/26   7:09 PM                archive
d-----          20/10/26   7:07 PM                data
d-----          20/10/26   7:08 PM                docs
d-----          20/10/26   7:07 PM                logs
d-----          20/10/26   7:08 PM                media
d-----          20/10/26   7:07 PM                Trung Tam Tieng Anh FINAL
-a----          19/10/26  10:04 AM            902 bai_lam_ngay1.md


    Directory: C:\Users\My Laptop\Downloads\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          19/10/26  10:04 AM          13559 Anh_Lop_Hoc.JPG
-a----          19/10/26  10:04 AM           5184 Logo_Trung_Tam.PNG


    Directory: C:\Users\My Laptop\Downloads\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          19/10/26  10:04 AM           5070 Hoc_Vien_Khoa_3.xlsx


    Directory: C:\Users\My Laptop\Downloads\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          19/10/26  10:04 AM             67 Lich_Hoc.txt


    Directory: C:\Users\My Laptop\Downloads\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          19/10/26  10:04 AM           1072 Access.log


    Directory: C:\Users\My Laptop\Downloads\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          19/10/26  10:04 AM          13559 Anh_Lop_Hoc.JPG
-a----          19/10/26  10:04 AM           5184 Logo_Trung_Tam.PNG
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
