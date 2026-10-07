**Bài 4 : Quản lý đường dẫn trong hệ thống tệp** 

### ***Phần 1: Phân tích & Đề xuất***

| Tiêu chí | Đường dẫn tuyệt đối | Đường dẫn tương đối |
| :---- | :---- | :---- |
| Tính di động | Thấp, phụ thuộc máy/ổ đĩa của An  | Cao, gửi cả thư mục Project vẫn chạy  |
| Độ dài câu lệnh | Dài | Ngắn |
| Tính an toàn | Dễ lỗi khi đổi máy | Ít phụ thuộc môi trường máy |

### ***Phần 2: Lựa chọn***

\-Chọn cách 2 là phù hợp, vì code nằm trong thư mục src  
\-Đường dẫn tương đối phù hợp hơn vì có tính di động cao, không phụ thuộc tên User hay ổ đĩa của máy.   
