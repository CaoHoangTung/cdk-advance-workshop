---
title : "Tạo IAM Role"
date :  "`r Sys.Date()`" 
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---

#### Tạo IAM Role

1. Truy cập giao diện [AWS Management Console](https://aws.amazon.com/console/)

   - Tìm **IAM**
   - Chọn **IAM**

![Amazon CDk](/images/1/0001.png?featherlight=false&width=90pc)

2. Trong giao diện **IAM**


   - Chọn **Roles**
   - Chọn **Create role**

![Amazon CDk](/images/1/0002.png?featherlight=false&width=90pc)

3. Trong giao diện **Select trusted entity**

   - Chọn **AWS service**
   - **Use case**, chọn **EC2**
   - Chọn **Next**

![Amazon CDk](/images/1/0003.png?featherlight=false&width=90pc)

4. Trong giao diện **Create role**

   - Tìm policy **AdministratorAccess**
   - Chọn policy **AdministratorAccess**
   - Chọn **Next**

![Amazon CDk](/images/1/0004.png?featherlight=false&width=90pc)

5. Trong giao diện **Role details**

   - **Role name**, nhập `CDK-Role`

![Amazon CDk](/images/1/0005.png?featherlight=false&width=90pc)

6. Chọn **Create role**

![Amazon CDk](/images/1/0006.png?featherlight=false&width=90pc)

7. Hoàn thành tạo role

![Amazon CDk](/images/1/0007.png?featherlight=false&width=90pc)

