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
| aaaa | 0 | 8 | Toàn kí tự giống nhau-> không có thông timn dư thừa tối đa |
| abcd | 2 | 6 | 4 ký tự phân bố đều-> entropy trung bình, còn nhiều dư thừa |
| hello world | 3.18 | 4.82 | Ngôn ngữ tự nhiên-> có kí tự lặp(l,o), dư thừa ~64% |

### 3.2 Modulo inverse
| a | m | Kết quả mong đợi | Kết quả chương trình |
|---:|---:|---|---|
| 3 | 7 | 5 | 5 |
| 10 | 17 | 12 | 12 |
| 6 | 9 | Không tồn tại | -1 |

## 4. Kết luận
Qua bài lab này, em đã nắm vững cách tính Entropy để đo lường độ hỗn loạn của thông tin và hiểu được mối quan hệ giữa nó với độ dư thừa (Redundancy) trong dữ liệu. Đồng thời, việc thực hiện thuật toán Euclid mở rộng để tìm nghịch đảo modulo đã giúp em củng cố nền tảng toán học quan trọng trong mật mã học.
