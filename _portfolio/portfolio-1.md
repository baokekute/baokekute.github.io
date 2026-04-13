---
title: "Hệ thống Giám sát Nhiệt độ đa kênh LM35"
excerpt: "Dự án tích hợp cảm biến nhiệt độ LM35, vi điều khiển Arduino và ứng dụng C# để theo dõi dữ liệu thời gian thực."
collection: portfolio
---

## Tổng quan dự án
Đây là dự án trọng tâm trong học phần Mạng cảm biến, tập trung vào việc thu thập dữ liệu vật lý và quản lý mã nguồn bằng Git/GitHub. Hệ thống cho phép đọc giá trị nhiệt độ từ nhiều cảm biến LM35 và truyền dữ liệu lên máy tính để xử lý.

## Các tính năng chính
* **Thu thập dữ liệu:** Đọc tín hiệu Analog từ cảm biến LM35 với độ chính xác cao.
* **Truyền thông:** Sử dụng giao tiếp Serial (UART) để gửi dữ liệu lên PC.
* **Giao diện người dùng:** Ứng dụng C# (WinForms) hiển thị nhiệt độ dưới dạng đồ thị trực quan.

## Công nghệ sử dụng
* **Phần cứng:** Arduino Uno R3, Cảm biến LM35.
* **Phần mềm:** Arduino IDE, Visual Studio (C#), Proteus.

[👉 Truy cập GitHub Repository của dự án](https://github.com/baokekute/Arduino_LM35_TempMonitor)