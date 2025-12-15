# [SQL] MiniSQL-Hackathon
## I. Introduction
I built this mini project to get hands-on practice with SQL fundamentals and sharpen my problem-solving mindset
## II. Questions
<img width="382" height="173" alt="image" src="https://github.com/user-attachments/assets/d3549a6c-6793-4c67-8cc3-33bab8951092" />

## III. Exploring the Dataset
## 1. Tổng số đơn hàng theo tháng 
- ### Query
  <img width="830" height="159" alt="image" src="https://github.com/user-attachments/assets/acb48efa-c93f-4319-b078-a445801f0811" />
- ### Result
<img width="427" height="223" alt="image" src="https://github.com/user-attachments/assets/ff2b7fc6-beef-4141-9f4a-ef8ca307531a" />

## 2. Số khách hàng mua hàng mỗi tháng
- ### Query 
  P/S: Em tính lượng khách hàng unique mua hàng từng tháng để ko tính những khách hàng mua lặp lại. Nếu tính lặp lại thì output sẽ giống như QQ1
  
<img width="797" height="178" alt="image" src="https://github.com/user-attachments/assets/c77460cf-c0f3-4082-a4e1-9a41847fcec7" />

- ### Result 
<img width="730" height="257" alt="image" src="https://github.com/user-attachments/assets/a1e261f6-7382-415d-9e79-a716fa1811bf" />

## 3. Ba thương hiệu điện thoại được ưa chuộng nhất theo giới tính

- ### Query 
<img width="800" height="312" alt="image" src="https://github.com/user-attachments/assets/2097b1a2-7aad-4a57-a537-4cc1cb20f27a" />

- ### Result 
<img width="830" height="260" alt="image" src="https://github.com/user-attachments/assets/3f142853-9b64-4dd4-90e6-07facb46f5f7" />

## 4. Phân tích theo nhóm tuổi
- ### Query
  <img width="548" height="514" alt="image" src="https://github.com/user-attachments/assets/1312ef28-78c0-4eb3-99ed-2a113a34a63d" />
- ### Result
  <img width="772" height="217" alt="image" src="https://github.com/user-attachments/assets/9dd41f20-5290-4984-b942-1ace0e439284" />

- #### Conclusions
  + Nhóm 26–30 chi tiêu nhiều nhất → nên tập trung chiến dịch marketing.
  + 31–35 đứng thứ hai, ưa chuộng phân khúc trung–cao.
  + <21 & 21–25: sức mua thấp, cần khuyến mãi giá mềm.
  + 40 trở đi : ít mua, nên tối giản trải nghiệm & tăng hỗ trợ.
## 5. Top 3 mẫu điện thoại doanh thu cao nhất từng tháng
- ### Query
  <img width="616" height="350" alt="image" src="https://github.com/user-attachments/assets/25ef753d-5069-4c23-b747-62af2840c15d" />
- ### Result
<img width="819" height="308" alt="image" src="https://github.com/user-attachments/assets/2270d6bb-8558-40d5-bff9-5f553ec5405d" />

- #### Insight : Từ data lấy được từ câu trên thì business đã có thông tin về các sản phẩm điện thoại bán chạy theo từng tháng, dựa vào đó có thể phân tích đặc điểm của dòng điện thoại đó đối với từng tháng và phát triển thêm các tính năng tương tự hay các sản phẩm dịch vụ bổ sung tương thích với đặc điểm để tăng doanh thu

## 6. Thương hiệu “đinh” của nhóm tuổi 26–30 
- ### Query
  <img width="888" height="313" alt="image" src="https://github.com/user-attachments/assets/e42f6456-33aa-4925-904e-2f51be054653" />
  
- ### Result
  <img width="860" height="133" alt="image" src="https://github.com/user-attachments/assets/c2d13e8f-c59f-44be-900a-10fbf3368878" />
## 7. Tỷ lệ nhóm 26–30 mua kèm phụ kiện/bảo hiểm 
- ### Query
  <img width="827" height="333" alt="image" src="https://github.com/user-attachments/assets/6fc7385f-a96d-4a17-8a62-c3075447cc27" />
  
- ### Result
  <img width="827" height="149" alt="image" src="https://github.com/user-attachments/assets/5ad4ff1e-c458-4b54-b93e-8e104192f4b6" />

## 8. Hành vi mua phụ kiện/bảo hiểm theo thương hiệu 
- ### Query
  <img width="855" height="322" alt="image" src="https://github.com/user-attachments/assets/4f29fb42-e695-4eff-a023-a6074725ec48" />
  
- ### Result
<img width="468" height="489" alt="image" src="https://github.com/user-attachments/assets/05b09d12-64c9-4c56-a272-eff36d4780bd" />

- #### Insight  : Chỉ thấy Samsung, Apple iPhone, BlackBerry có khách hàng mua kèm phụ kiện/ bảo hiểm

## 9. Nhóm tuổi chuộng mua trả góp nhất 
- ### Query
<img width="726" height="293" alt="image" src="https://github.com/user-attachments/assets/bb608077-4e23-4f84-a5f0-47a7c09386b8" />

- ### Result
<img width="761" height="92" alt="image" src="https://github.com/user-attachments/assets/206d9cc4-dd1a-4767-a693-4b5005b9f751" />

- #### Insight : Nhóm tuổi 26-30  thường là nhóm khách hàng trẻ, đã đi làm, có nhiều nhu cầu cần thiết và nhưng chưa có nhiều vốn sẵn có nên ưu tiên trả góp để cân bằng tài chính.

## 10. Thương hiệu có nhiều đơn trả góp nhất 
-- P/S: được mua trả góp nhiều nhất sẽ tính theo số lượng điện thoại được mua trả góp của từng hãng
- ### Query
  <img width="781" height="235" alt="image" src="https://github.com/user-attachments/assets/72e0af31-927d-4f7f-b0de-75400475fa70" />

- ### Result
  <img width="675" height="107" alt="image" src="https://github.com/user-attachments/assets/4154564b-c1dd-4e6a-8bc5-3db12042971e" />















