## **Phần 1: Phân tích**

**Bẫy mã AI:** Câu lệnh Remove-Item \-Path "C:\\\*" \-Recurse \-Force.  
**Hậu quả:** **Xóa sạch toàn bộ hệ điều hành Windows** và mọi dữ liệu trong ổ C:\\, làm hỏng máy tính ngay lập tức.

## **Phần 2: Triển khai**

Đoạn **Script PowerShell** an toàn theo yêu cầu:  
Select-String \-Path "water\_log.txt" \-Pattern "WARNING" | Out-File \-FilePath "incident.txt"  
Write-Host "Hoan thanh"