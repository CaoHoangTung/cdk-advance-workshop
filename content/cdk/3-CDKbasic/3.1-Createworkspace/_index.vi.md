---
title : "Tạo workspace"
date :  "`r Sys.Date()`" 
weight : 1
chapter : false
pre : " <b> 3.1 </b> "
---

#### Tạo workspace
Nếu bạn đã làm [workshop về CloudFormation](https://000037.awsstudygroup.com/vi/1-introduce/), bạn có thể sử dụng Cloud9 workspace đã tạo trong bài lab đó và bỏ qua **6 bước đầu** của phần này.

Nếu không, bạn có thể tiếp tục với các bước sau đây.


1. Truy cập vào giao diện [AWS Management Console](https://aws.amazon.com/console/)

   - Tìm **Cloud9**
   - Chọn **Cloud9**

![Amazon CDk](/images/2.2-prerequisite/0001.png?featherlight=false&width=90pc)

2. Trong giao diện **AWS Cloud9**

   - Chọn **Create environment**

![Amazon CDk](/images/2.2-prerequisite/0002.png?featherlight=false&width=90pc)

3. Trong giao diện **Create environment**

   - **Name**, nhập `ASG-Cloud9-Workshop`
   - Chọn **Next step**

![Amazon CDk](/images/2.2-prerequisite/0003.png?featherlight=false&width=90pc)

4. Trong phần **Configure settings**

   - **Create a new EC2 instance for environment (direct access)**: EC2 Instance được khởi tạo cùng với Cloud9 environment. Instance được truy cập qua Cloud9 IDE sử dụng phương thức SSH.
   - **Create a new no-ingress EC2 instance for environment (access via Systems Manager)**: EC2 Instance cũng được khởi tạo cùng với Cloud9 environment và Instance có thể được truy cập qua System Manager.
   - **Create and run in remote server (SSH connection)**: EC2 Instance đã có sẵn, Cloud9 eviroment thiết lập môi trường để đủ điều kiện truy cập EC2 Instance.
   - Trong phạm vi bài giới thiệu về dịch vụ CDK hôm nay, để
   đơn giản và tập trung vào nội dung chính chúng ta sẽ chọn option thứ
   nhất - EC2 và Cloud9 được khởi tạo cùng lúc và có thể truy cập Instance
   qua SSH.
   - Các nội dung cấu hình còn lại ta để mặc định với:
   - **Cost-saving setting**: sau 30’ nếu EC2 Instance không có tiến trình nào được chạy, Cloud9 sẽ stop Instance.
   - **IAM Role**: AWSServiceRoleForAWSCloud9 - là service-linked role được tạo sẵn bởi AwS và gắn với dịch vụ Cloud9
   - **Environment type**, chọn **Create a new EC2 instance for environment (direct access)**
   - **Instance type**, chọn **t3.small(2GiB RAM + 2vCPU)**
   - **Platform**, chọn **Amazon Linux 2 (recommended)**
   - Để tuỳ chọn **Network** theo như mặc định (default VPC)

![Amazon CDk](/images/2.2-prerequisite/0004.png?featherlight=false&width=90pc)

5. Chọn **Next step**

![Amazon CDk](/images/2.2-prerequisite/0005.png?featherlight=false&width=90pc)

6. Chọn **Create environment**

![Amazon CDk](/images/2.2-prerequisite/0006.png?featherlight=false&width=90pc)

7. Giao diện môi trường vừa khởi tạo

![Amazon CDk](/images/2.2-prerequisite/0007.png?featherlight=false&width=90pc)
