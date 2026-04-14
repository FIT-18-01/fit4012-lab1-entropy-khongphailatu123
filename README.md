[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/sHB0KmgB)
# FIT4012 – Lab 1. Entropy, độ dư thừa thông tin và nghịch đảo modulo


## Mục tiêu bài lab
Sau khi hoàn thành bài này, sinh viên có thể:
- Đọc hiểu và chạy được chương trình tính entropy của một chuỗi ký tự.
- Bổ sung chức năng tính độ dư thừa thông tin dựa trên entropy thực tế.
- Cài đặt hàm tìm nghịch đảo modulo bằng thuật toán Euclid mở rộng.
- Tổ chức, kiểm thử và nộp bài bằng GitHub repo.

## Cấu trúc repo
- `src/entropy_redundancy.cpp`: Q1, Q2
- `src/mod_inverse.cpp`: Q3
- `tests/test_cases.md`: test cases tối thiểu
- `logs/run_log.md`: log chạy chương trình
- `report-page.md`: báo cáo 1 trang

## Yêu cầu nộp bài
Hoàn thiện repo và nộp link GitHub. Repo cần có:
- `README.md` với tóm tắt bài lab
- `report-page.md` (báo cáo 1 trang)
- `tests/` với ít nhất 5 test cases
- `logs/` có kết quả chạy thử trên GitHub
- mã nguồn hoàn thiện cho Q1 (entropy), Q2 (redundancy), Q3 (modular inverse)

## Công nghệ và công cụ
- **Entropy**: Độ đo độ bất định trong thông tin
- **Redundancy**: Độ dư thừa thông tin = log₂(N) - H(X)
- **Modulo Inverse**: Nghịch đảo modulo sử dụng thuật toán Euclid mở rộng
- **GitHub**: Nền tảng version control để lưu trữ và nộp bài

## Gợi ý commit
- `Complete Q1 entropy walkthrough`
- `Implement redundancy calculation`
- `Implement modular inverse with extended Euclid`
- `Add tests and report`
