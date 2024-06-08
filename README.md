# jmater
Kiểm tra hiệu năng trang web :

Mục tiêu:

Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://www.coursera.org/learn/machine-learning.

Chạy kịch bản kiểm tra và ghi lại kết quả.

Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.

Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.


Kịch bản kiểm tra:

Web performance :

Number of Threads (users): 100

Ramp-Up Period (in seconds): 10

Loop Count: 2

Forever: Check để lặp không giới hạn, uncheck để lặp bằng số Loop Count
Listeners:

View Results Tree

Summary Report  

View Results in Table


Kết quả kiểm tra:
![Screenshot 2024-06-08 122100](https://github.com/Cuongpham14/jmater/assets/96830691/0a09bc97-5790-4358-ad04-c5e81b401883)

![Screenshot 2024-06-08 122038](https://github.com/Cuongpham14/jmater/assets/96830691/6b49c1ed-7d06-40f3-837f-cbad3e42ac1d)

![Screenshot 2024-06-08 122016](https://github.com/Cuongpham14/jmater/assets/96830691/98b3438b-f871-4998-ad80-a3a5d3873a26)

Phân tích kết quả kiểm tra:

Tổng số lần run của request : 200

Thời gian phản hồi trung bình : 365ms

% số lượng request bị lỗi : 0

Lượng requests được hệ thống (server) xử lý trong 1s : 20.4

Respone Time thấp nhất của request đã gửi : 115

Respone Time cao nhất của request đã gửi : 2204

Dung lượng nhận được từ server : 3586.97 KB/sec

Dung lượng gửi lên server : 2.39 KB/sec


Kết luận :

Tổng kết lại, kết quả kiểm thử cho thấi trang web có hiệu năng tốt, ổn định và đáp ứng được các yêu cầu về tốc độ, thời gian phản hồi và khả năng xử lý lớn.


Kiểm tra hiệu năng API :

Mục tiêu:

Sử dụng jMeter để tạo một kịch bản kiểm tra https://jsonplaceholder.typicode.com/users 

Chạy kịch bản kiểm tra và ghi lại kết quả.

Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.

Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

Kịch bản kiểm tra:

Number of Threads (users): 100

Ramp-Up Period (in seconds): 10

Loop Count: 2

Forever: Check để lặp không giới hạn, uncheck để lặp bằng số Loop Count

Listeners:

View Results Tree

Summary Report  

View Results in Table


Kết quả kiểm tra:

![Screenshot 2024-06-08 125844](https://github.com/Cuongpham14/jmater/assets/96830691/0c690b3e-4bab-46e3-be5f-59277c73a940)
![Screenshot 2024-06-08 125905](https://github.com/Cuongpham14/jmater/assets/96830691/c4c062df-d295-43fa-b2a7-5c185c9a7e87)
![Screenshot 2024-06-08 125923](https://github.com/Cuongpham14/jmater/assets/96830691/7f232989-aea8-4e53-afac-a3f3ac1cb924)

Phân tích kết quả kiểm tra:

Tổng số lần run của request : 215

Thời gian phản hồi trung bình : 106ms

% số lượng request bị lỗi : 0

Lượng requests được hệ thống (server) xử lý trong 1s : 7.3

Respone Time thấp nhất của request đã gửi : 59

Respone Time cao nhất của request đã gửi : 469

Dung lượng nhận được từ server : 6.00 KB/sec

Dung lượng gửi lên server : 1.33 KB/sec


Kết luận :

Kết quả kiểm thử cho thấy API có hiệu năng tốt, ổn định và đáp ứng được các yêu cầu về tốc độ, thời gian phản hồi và khả năng xử lý

So sánh :

Tổng kết, API có hiệu năng cao hơn về thời gian phản hồi và ổn định, trong khi Website có khả năng xử lý số lượng request và truyền tải dữ liệu nhanh hơn. Tùy thuộc vào yêu cầu của ứng dụng, mỗi giải pháp có ưu điểm và nhược điểm riêng



