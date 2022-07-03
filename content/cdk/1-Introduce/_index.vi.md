---
title : "Giới thiệu"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---

#### Tổng quan 

CloudFormation là một dịch vụ cho phép người dùng có khả năng triển khai kiến trúc ứng dụng bằng code (Infrastructure as code). Người dùng có thể viết file JSON hoặc YAML để triển khai tất cả dịch vụ của AWS (VPC, EC2, Lambda,…). Một tập hợp tài nguyên AWS sẽ được triển khai qua một CloudFormation Stack, và bạn có thể dễ dàng quản lý phiên bản, tạo phiên bản mới hoặc xoá toàn bộ tài nguyên liên quan. Toàn bộ quá trình có thể được tạo tự động và hoàn toàn miễn phí (bạn chỉ cần trả phí cho những tài nguyên được tạo bên dưới).

AWS Cloud Development Kit (CDK) là một dịch vụ của AWS hoạt động dựa trên CloudFormation. Tuy nhiên, với CDK, người dùng có thể định nghĩa kiến trúc các tài nguyên của AWS bằng các ngôn ngữ lập trình phổ biến như TypeScript, JavaScript, Python, Java, C# 

Trong bài lab này, chúng ta sẽ thực hành sử dụng CDK. Sau khi hoàn thành bài lab, người đọc sẽ có thể

- Hiểu các khái niệm cơ bản của CDK
- Triển khai một kiến trúc cơ bản lên AWS sử dụng CDK
- Cấu hình EC2 thông qua user data

Trước khi làm workshop này về CDK, bạn nên làm [workshop về CloudFormation](https://000037.awsstudygroup.com/vi/1-introduce/) để hiểu một vài khái niệm cơ bản, do CDK thực chất **hoạt động dựa trên CloudFormation**