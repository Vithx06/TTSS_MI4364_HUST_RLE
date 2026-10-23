# ĐỀ TÀI RIÊNG: XÂY DỰNG CHƯƠNG TRÌNH NÉN VÀ GIẢI NÉN RUN-LENGTH ENCODING SONG SONG SỬ DỤNG PREFIX SUM

**Dự án cuối kỳ môn: Tính toán song song - MI4364**  
**Nhóm: 22**  
**Mã lớp học: 174400**  
**Học kỳ: 20261**

## Mục lục

1. [Tổng quan bài toán](#1-tổng-quan-bài-toán)
2. [Môi trường phát triển](#2-môi-trường-phát-triển)
3. [Cấu trúc chương trình](#3-cấu-trúc-chương-trình)
4. [Hướng dẫn chạy chương trình](#4-hướng-dẫn-chạy-chương-trình)
5. [Kiểm thử chương trình](#5-kiểm-thử-chương-trình)
6. [Đánh giá hiệu năng](#6-đánh-giá-hiệu-năng)
7. [Khai báo sử dụng AI](#7-khai-báo-sử-dụng-ai)
8. [Kết quả đạt được](#8-kết-quả-đạt-được)

## 1. Tổng quan bài toán

### 1.1. Giới thiệu

Chương trình xây dựng thuật toán nén và giải nén dữ liệu Run-Length Encoding (RLE) song song bằng C++, OpenMP và Prefix Sum, nhằm tối ưu thời gian xử lý dữ liệu.

### 1.2. Các khái niệm cơ bản

- **Run-Length Encoding (RLE):** Thuật toán nén dữ liệu bằng cách biểu diễn các phần tử liên tiếp giống nhau thành giá trị và số lần lặp.
- **Prefix Sum:** Phép tính tổng tiền tố, hỗ trợ xác định vị trí ghi dữ liệu đầu ra.
- **OpenMP:** Thư viện hỗ trợ lập trình song song trên CPU bằng nhiều luồng xử lý.

### 1.3. Mục tiêu

- Xây dựng thuật toán nén và giải nén RLE song song sử dụng Prefix Sum.
- Đảm bảo dữ liệu sau giải nén khớp với dữ liệu ban đầu.
- Đánh giá hiệu năng thông qua thời gian thực thi, tỷ lệ nén và thông lượng xử lý.

## 2. Môi trường phát triển

| Thành phần | Công cụ / Thông số |
| :--- | :--- |
| **Ngôn ngữ lập trình** | C++ |
| **Môi trường phát triển** | Visual Studio Code |
| **Thư viện tính toán song song** | OpenMP |
| **Trình biên dịch** | GCC |
| **Quản lý mã nguồn** | Git & GitHub |
| **Hệ điều hành** | Windows |