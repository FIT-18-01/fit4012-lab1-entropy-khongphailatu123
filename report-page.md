# Report 1 Page – FIT4012 Lab 1

## 1. Mục tiêu
Tóm tắt ngắn gọn mục tiêu của bài lab.

## 2. Cách làm
- Đọc hiểu chương trình entropy mẫu.
- Bổ sung hàm tính redundancy.
- Hoàn thiện hàm mod_inverse().
- Chạy thử trên nhiều test case.

## 3. Kết quả chính
### 3.1 Entropy và redundancy
| Input | Entropy | Redundancy | Nhận xét |
|---|---:|---:|---|
| aaaa | 0.00 | 8.00 | Entropy thấp vì chỉ có 1 ký tự, redundancy cao |
| abcd | 2.00 | 6.00 | Entropy cao hơn vì 4 ký tự khác nhau |
| hello world | 2.85 | 5.15 | Entropy trung bình với sự phân bố ký tự |

### 3.2 Modulo inverse
| a | m | Kết quả mong đợi | Kết quả chương trình |
|---:|---:|---|---|
| 3 | 7 | 5 | 5 |
| 10 | 17 | 12 | 12 |
| 6 | 9 | Không tồn tại | Không tồn tại |

## 4. Kết luận
Nêu ngắn gọn em học được gì từ bài lab, khó khăn lớn nhất là gì, và điều gì giúp em hiểu rõ hơn về entropy hoặc modulo inverse.
