# Filter Message Spam
## Giới thiệu chung:
Trong dự án này, tôi tạo một bộ lọc tin nhắn rác với mong đợi là độ chính xác 80%.

Để huấn luyện thuật toán này, tôi đã sử dụng tập dữ liệu với 5,572 tin nhắn được con người phân loại.
## Mục tiêu:
Làm sạch dữ liệu cho những input tin nhắn mới.

Chia tập dữ liệu thành hai bộ dữ liệu, một bộ để huấn luyện mô hình và một bộ để kiểm tra hiệu quả mô hình. 

Sử dụng thuật toán multinomial Navie Bayes để huấn luyện mô hình. 

Xây dựng hàm để tính toán độ chính xác mô hình. 
