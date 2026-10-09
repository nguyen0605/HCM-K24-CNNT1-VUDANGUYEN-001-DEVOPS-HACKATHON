# DevOps Hackathon - Đề 001: Quản lý phòng Lab


## 1. Thông tin sinh viên
|   Họ và tên  |Mã sinh viên|    Lớp    |   Tài khoản Linux   |  GitHub  |Cổng Nginx|
|Vũ Đăng Nguyên| N24DTCN056 |D24TXCN01-N|vudangnguyen-k24it209|nguyen0605|8099|

## 2. Môi trường triển khai
- Hệ điều hành: Ubuntu 24.04 LTS (VPS Cloud)
- Phiên bản: Nginx 1.24+, Git 2.43+

## 3. Cấu trúc dự án
```text
HACKATHON/


## 4. Cấu hình Nginx
|Tham số trong template|Giá trị đã điền|Giải thích|
|nginx.service - A high performance web server and a reverse proxy server
     Loaded: loaded (/usr/lib/systemd/system/nginx.service; enabled; preset: enabled)
     Active: active (running) since Fri 2026-10-09 02:47:27 BST; 50s ago
       Docs: man:nginx(8)
    Process: 368598 ExecStartPre=/usr/sbin/nginx -t -q -g daemon on; master_process on; (code=exited, status=0/SUCCESS)
    Process: 368601 ExecStart=/usr/sbin/nginx -g daemon on; master_process on; (code=exited, status=0/SUCCESS)
    Process: 368844 ExecReload=/usr/sbin/nginx -g daemon on; master_process on; -s reload (code=exited, status=0/SUCCESS| 

## 5. Tường lửa UFW 
## 6. Các bước triển khai
## 7. Kiểm tra & minh chứng
## 8. Quy trình cập nhật website
## 9. Sự cố gặp phải & cách khắc phục (nếu có)
