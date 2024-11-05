# Word-suggestion-system

## I. Giới thiệu

Dự án án này cung cấp cho người dùng một hệ thống có thể đưa ra các gợi ý từ cho người dùng sử dụng cho các ứng dụng.
Mục tiêu: dựa trên đầu vào từ người dùng, sử dụng mô hình n-gram và mô hình học sâu LSTM để gợi ý các từ phù hợp và liên quan tới dữ liệu đào vào.

## II. Cài đặt

Vui lòng chạy mô hình đang được chạy trên trình google colab.

## III. Hướng dẫn sử dụng
### 1. Khởi động hệ thống
Đầu tiên cần phải đảm bảo rằng dữ liệu của file demo-full.text dược tải lên trên google colab.
### 2. Khởi chạy chương trình 
Chạy tất cả các ô chương trình code
### 3. Nhập văn bản

nhập văn bản vào ô nhập văn bản, người dùng có thể chọn nhập tiếp hoặc chọn từ được gợi ý để làm từ tiếp theo của văn bản
### 4. Đưa ra các từ gợi ý cho người dùng 

Sử dụng mô hình 2-gram với văn bản ngắn từ 1-2 từ để đưa ra 5 từ gợi ý có xác suất cao nhất.
Sử dụng mô hình 3-gram với các văn bản từ 3-5 từ để đưa ra 5 từ gợi ý có xác suất cao nhất.
Với các văn bản có số từ lớn hơn 5 sử dụng mô hình LSTM để đưa ra 4 từ gợi ý và 2-gram để đưa ra 1 từ gợi ý. 
## IV. Tổng kết
Hệ thống này đưa ra các gợi ý cho người dùng dựa trên văn bản đầu vào và dữ liệu đã được sử dụng trong huấn luyện hệ thống. Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào, vui lòng liên hệ với chúng tôi qua email: 22010085@st.phenikaa-uni.edu.vn
