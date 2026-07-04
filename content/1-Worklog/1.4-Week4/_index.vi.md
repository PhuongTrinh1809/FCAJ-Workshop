---
title: "Worklog Tuần 4"
date: 2026-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Tiếp tục học tập và thực hành các bài Lab trên nền tảng AWS.
* Tìm hiểu quy trình triển khai ứng dụng Web trên AWS sử dụng Amazon EC2 và Amazon RDS.
* Nghiên cứu cơ chế sao lưu, khôi phục dữ liệu và tự động mở rộng tài nguyên (Auto Scaling).
* Thực hành cấu hình Load Balancer và các phương pháp mở rộng hệ thống.

### Các công việc cần triển khai trong tuần này:
<table class="worklog-table">
<colgroup>
  <col class="col-day" style="width:5%">
  <col class="col-task" style="width:42%">
  <col class="col-start" style="width:13%">
  <col class="col-end" style="width:13%">
  <col class="col-ref" style="width:27%">
</colgroup>
  <thead>
    <tr>
      <th>Ngày</th>
      <th>Công việc</th>
      <th>Ngày bắt đầu</th>
      <th>Ngày hoàn thành</th>
      <th>Nguồn tài liệu</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="col-day">1</td>
      <td class="col-task">- Tìm hiểu kiến trúc triển khai ứng dụng trên AWS. <br> - Thực hiện các bước chuẩn bị môi trường Lab. <br> - Nghiên cứu mô hình triển khai ứng dụng sử dụng Amazon EC2 kết hợp Amazon RDS.</td>
      <td class="col-date">11/05/2026</td>
      <td class="col-date">11/05/2026</td>
      <td class="col-ref">https://000005.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">2</td>
      <td class="col-task">- Thực hiện Lab triển khai ứng dụng: <br> - Tạo EC2 Instance. <br> - Cấu hình môi trường máy chủ. <br> - Tạo Amazon RDS Database Instance. <br> - Kết nối ứng dụng với cơ sở dữ liệu.</td>
      <td class="col-date">12/05/2026</td>
      <td class="col-date">12/05/2026</td>
      <td class="col-ref">https://000005.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">3</td>
      <td class="col-task">- Thực hiện triển khai ứng dụng lên môi trường AWS. <br> - Kiểm tra khả năng kết nối giữa EC2 và RDS. <br> - Thực hành các thao tác sao lưu (Backup) và khôi phục dữ liệu (Restore).</td>
      <td class="col-date">13/05/2026</td>
      <td class="col-date">13/05/2026</td>
      <td class="col-ref">https://000005.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">4</td>
      <td class="col-task">- Thực hiện các bước chuẩn bị cho Auto Scaling: Thiết lập hạ tầng mạng, khởi tạo EC2 Instance, khởi tạo RDS Database, cấu hình dữ liệu cho hệ thống, triển khai Web Server và chuẩn bị các chỉ số giám sát phục vụ Auto Scaling.</td>
      <td class="col-date">14/05/2026</td>
      <td class="col-date">14/05/2026</td>
      <td class="col-ref">https://000006.awsstudygroup.com/</td>
    </tr>
    <tr>
      <td class="col-day">5</td>
      <td class="col-task">- Thực hiện Lab Create Launch Template. <br> - Tìm hiểu vai trò của Launch Template trong việc tự động khởi tạo EC2. <br> - Cấu hình các thông số cần thiết cho việc mở rộng hệ thống.</td>
      <td class="col-date">15/05/2026</td>
      <td class="col-date">15/05/2026</td>
      <td class="col-ref">https://000006.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">6</td>
      <td class="col-task">- Thực hiện Lab Setting Up Load Balancer. <br> - Tạo Target Group. <br> - Tạo và cấu hình Application Load Balancer. <br> - Kiểm tra khả năng phân phối lưu lượng truy cập đến các máy chủ EC2.</td>
      <td class="col-date">16/05/2026</td>
      <td class="col-date">16/05/2026</td>
      <td class="col-ref">https://www.youtube.com/watch?v=CXU8D3kyxIc&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=27</td>
    </tr>
    <tr>
      <td class="col-day">7</td>
      <td class="col-task">- Thực hiện Lab Create Auto Scaling Group. <br> - Cấu hình Auto Scaling Group cho hệ thống. <br> - Thực hiện kiểm thử các kịch bản: Manual Scaling, Scheduled Scaling, Dynamic Scaling, Predictive Scaling. <br> - Đánh giá khả năng tự động mở rộng và thu hẹp tài nguyên theo nhu cầu sử dụng.</td>
      <td class="col-date">17/05/2026</td>
      <td class="col-date">17/05/2026</td>
      <td class="col-ref">https://000006.awsstudygroup.com/</td>
    </tr>
  </tbody>
</table>

### Kết quả đạt được tuần 4:

* Nắm được quy trình triển khai ứng dụng Web trên AWS sử dụng Amazon EC2 và Amazon RDS.
* Thực hiện thành công các thao tác Backup và Restore dữ liệu.
* Nắm được nguyên lý hoạt động của Launch Template và Auto Scaling Group.
* Cấu hình thành công Application Load Balancer và Target Group.
* Thực hành các mô hình mở rộng hệ thống bao gồm Manual Scaling, Scheduled Scaling, Dynamic Scaling và Predictive Scaling.
* Củng cố lại kiến thức về khả năng mở rộng, tính sẵn sàng cao và tối ưu tài nguyên trên nền tảng AWS.
