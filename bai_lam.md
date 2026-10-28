# BÀI LÀM – HACKATHON 01

- **Mã đề:** 17
- **Họ tên:Tran Thien Thuat
- **Lớp:CNTT1 
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):Windows

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
 pwd
 ls -Force
 Move-Item nguon_hang.txt/docs
  mv nguon_hang.txt docs/
  mv logo_trai_cay_sach.png media/
   cp media/logo_trai_cay_sach.png backup/
   rm temp_252.tmp
   cd logs
   ls -Force

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
# Get-Content logs/fruit.log|Select-String "ERROR" >> logs/daily_report.txt

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-07-28 09:31:32 [ERROR] Thanh toan bi tu choi
2026-07-28 09:40:32 [ERROR] Het thoi gian cho (timeout)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [x] Heading 1: tên dự án
- [x] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [x] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [x] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [x] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# "===BAO CAO LOI==="> logs/auto_report.txt
Get-Content logs/fruit.log| Select-String "ERROR" >>logs/auto_report.txt
```

### Kết quả hiển thị

```Hoan Thanh

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Get-Content logs/fruit.log | Select-String "ERROR" | Measure-Object

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
Count    : 5
Average  :
Sum      :
Maximum  :
Minimum  :
Property :

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/ban_trai_cay_thang_7.xlsx`, không cần ghi vào đây.
