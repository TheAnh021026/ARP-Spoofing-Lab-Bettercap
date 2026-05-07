# ARP Spoofing Lab: MITM Attack & Defense Analysis

## Giới thiệu
Dự án này mô phỏng kỹ thuật tấn công Man-in-the-Middle (MITM) thông qua ARP Spoofing trong môi trường mạng nội bộ thực tế. Mục tiêu chính là hiểu rõ lỗ hổng của giao thức ARP và triển khai các biện pháp phòng vệ thực chiến.

## Các công cụ sử dụng
* **Môi trường:** Ubuntu (Attacker), Windows 11 (Victim), Router FPT (Gateway).
* **Công cụ:** Bettercap (Tấn công), Wireshark (Phân tích).

## Kết quả đạt được
1. Thực hiện thành công việc điều hướng lưu lượng từ nạn nhân qua máy tấn công.
2. Phân tích được các dấu hiệu nhận biết cuộc tấn công trên Wireshark (tần suất gói tin, Unsolicited ARP Reply).
3. Triển khai thành công giải pháp Static ARP và IP-MAC Binding để chặn đứng cuộc tấn công.

## Tài liệu chi tiết
Bạn có thể tải về báo cáo đầy đủ (bao gồm hình ảnh chi tiết và phân tích sâu) tại đây:
* [Nghiên cứu Kỹ thuật Giả mạo địa chỉ ARP và Giải pháp Phòng thủ trên Windows 11.docx](https://github.com/user-attachments/files/27469535/Nghien.c.u.K.thu.t.Gi.m.o.d.a.ch.ARP.va.Gi.i.phap.Phong.th.tren.Windows.11.docx)

* [Nghiên cứu Kỹ thuật Giả mạo địa chỉ ARP và Giải pháp Phòng thủ trên Windows 11 - Copy.pdf](https://github.com/user-attachments/files/27469529/Nghien.c.u.K.thu.t.Gi.m.o.d.a.ch.ARP.va.Gi.i.phap.Phong.th.tren.Windows.11.-.Copy.pdf)


---
*Thực hiện bởi: Nguyễn Thế Anh*
