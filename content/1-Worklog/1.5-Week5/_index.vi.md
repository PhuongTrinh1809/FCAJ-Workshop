---
title: "Worklog Tuần 5"
date: 2026-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Tìm hiểu dịch vụ lưu trữ Amazon S3 trên nền tảng AWS.
* Thực hành triển khai Static Website Hosting bằng Amazon S3.
* Tìm hiểu cơ chế phân phối nội dung thông qua Amazon CloudFront.
* Nghiên cứu các tính năng quản lý dữ liệu như Versioning và bảo mật truy cập.

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
      <td class="col-task">- Tiếp tục thực hiện Lab Create Auto Scaling Group. <br> - Thực hiện kiểm thử các kịch bản: <br> &nbsp;&nbsp;&nbsp;&nbsp;- Manual Scaling. <br> &nbsp;&nbsp;&nbsp;&nbsp;- Scheduled Scaling.</td>
      <td class="col-date">18/05/2026</td>
      <td class="col-date">18/05/2026</td>
      <td class="col-ref">https://000057.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">2</td>
      <td class="col-task">- Tiếp tục thực hiện kiểm thử các kịch bản: <br> &nbsp;&nbsp;&nbsp;&nbsp;- Dynamic Scaling. <br> &nbsp;&nbsp;&nbsp;&nbsp;- Predictive Scaling. <br> - Đánh giá khả năng tự động mở rộng và thu hẹp tài nguyên theo nhu cầu sử dụng.</td>
      <td class="col-date">19/05/2026</td>
      <td class="col-date">19/05/2026</td>
      <td class="col-ref">https://000057.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">3</td>
      <td class="col-task">- Tìm hiểu tổng quan về dịch vụ Amazon S3. <br> - Nghiên cứu khái niệm S3 Bucket, Object Storage và vai trò của S3 trong hệ sinh thái AWS. <br> - Tìm hiểu các quy tắc đặt tên Bucket và lựa chọn AWS Region phù hợp.</td>
      <td class="col-date">20/05/2026</td>
      <td class="col-date">20/05/2026</td>
      <td class="col-ref">https://000057.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">4</td>
      <td class="col-task">- Thực hiện tạo S3 Bucket trên AWS. <br> - Cấu hình: <br> &nbsp;&nbsp;&nbsp;&nbsp;- Bucket Name. <br> &nbsp;&nbsp;&nbsp;&nbsp;- AWS Region. <br> &nbsp;&nbsp;&nbsp;&nbsp;- Object Ownership (ACLs Disabled). <br> &nbsp;&nbsp;&nbsp;&nbsp;- Block Public Access theo khuyến nghị của AWS. <br> - Tìm hiểu các thiết lập bảo mật mặc định của Amazon S3.</td>
      <td class="col-date">21/05/2026</td>
      <td class="col-date">21/05/2026</td>
      <td class="col-ref">https://000057.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">5</td>
      <td class="col-task">- Thực hiện tải mã nguồn website tĩnh lên S3 Bucket. <br> - Upload toàn bộ dữ liệu website vào Bucket. <br> - Kiểm tra cấu trúc thư mục và các đối tượng đã được lưu trữ thành công trên Amazon S3. <br> - Kích hoạt tính năng Static Website Hosting cho S3 Bucket. <br> - Cấu hình trang mặc định của website.</td>
      <td class="col-date">22/05/2026</td>
      <td class="col-date">22/05/2026</td>
      <td class="col-ref">https://000057.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">6</td>
      <td class="col-task">- Điều chỉnh Public Access Block và cấp quyền truy cập công khai cho các đối tượng phục vụ website. <br> - Kiểm tra khả năng truy cập website thông qua S3 Website Endpoint. <br> - Thực hiện kiểm thử website sau khi triển khai. <br> - Xác nhận khả năng truy cập các trang và tài nguyên tĩnh. <br> - Tìm hiểu cơ chế lưu trữ và phân phối nội dung của Amazon S3.</td>
      <td class="col-date">23/05/2026</td>
      <td class="col-date">23/05/2026</td>
      <td class="col-ref">https://000057.awsstudygroup.com</td>
    </tr>
    <tr>
      <td class="col-day">7</td>
      <td class="col-task">- Thực hiện Lab Accelerate Static Websites with CloudFront. <br> - Cấu hình Amazon CloudFront Distribution. <br> - Thiết lập S3 Bucket làm Origin cho CloudFront. <br> - Kiểm tra khả năng phân phối nội dung thông qua CloudFront. <br> - So sánh hiệu quả truy cập giữa S3 Website Endpoint và CloudFront Distribution.</td>
      <td class="col-date">24/05/2026</td>
      <td class="col-date">24/05/2026</td>
      <td class="col-ref">https://000057.awsstudygroup.com</td>
    </tr>
  </tbody>
</table>

### Kết quả đạt được tuần 5:

* Thực hành thành công các mô hình mở rộng hệ thống bao gồm Manual Scaling, Scheduled Scaling, Dynamic Scaling và Predictive Scaling.
* Tạo thành công Amazon S3 Bucket.
* Upload và quản lý dữ liệu trên Amazon S3.
* Triển khai thành công Static Website Hosting bằng Amazon S3.
* Hiểu cơ chế Public Access Control và Object Ownership trong S3.
* Cấu hình thành công Amazon CloudFront để tăng tốc truy cập website tĩnh.
* Nắm được nguyên lý hoạt động của Content Delivery Network (CDN).
