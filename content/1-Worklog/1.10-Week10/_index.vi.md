---
title: "Worklog Tuần 10"
date: 2026-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Thực hiện phần hạ tầng AWS được phân công trong đồ án.
* Triển khai lớp xác thực và edge (Cognito, API Gateway, CloudFront, WAF) cho hệ thống ZeroBug Agent.
* Kiểm tra khả năng hoạt động của các dịch vụ sau khi cấu hình.

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
      <td class="col-task">- Chuẩn bị môi trường triển khai Workshop. <br> - Tạo IAM User và cấp quyền cho Amazon Cognito, Amazon API Gateway, Amazon CloudFront và AWS WAF. <br> - Kiểm tra quyền truy cập và cấu hình AWS CLI phục vụ quá trình triển khai.</td>
      <td class="col-date">22/06/2026</td>
      <td class="col-date">22/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">2</td>
      <td class="col-task">- Thực hiện cấu hình Amazon Cognito User Pool và App Client SPA. <br> - Thiết lập Cognito domain, Hosted UI và callback URL. <br> - Triển khai Amazon API Gateway với JWT Authorizer, stage prod và tích hợp ALB DNS từ Toàn.</td>
      <td class="col-date">23/06/2026</td>
      <td class="col-date">23/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">3</td>
      <td class="col-task">- Triển khai Amazon CloudFront Distribution. <br> - Cấu hình Origin kết nối đến API Gateway (để trống Route 53 managed domain và Alternate domain). <br> - Thiết lập Cache Behaviors, Origin request policy và HTTPS redirect.</td>
      <td class="col-date">24/06/2026</td>
      <td class="col-date">24/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">4</td>
      <td class="col-task">- Hoàn thiện cấu hình CloudFront Distribution (HTTPS mặc định trên *.cloudfront.net). <br> - Cập nhật Cognito Allowed callback URLs và redirect URIs trỏ đến CloudFront domain. <br> - Kiểm tra khả năng truy cập qua HTTPS.</td>
      <td class="col-date">25/06/2026</td>
      <td class="col-date">25/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">5</td>
      <td class="col-task">- Triển khai AWS WAF. <br> - Tạo Web ACL. <br> - Cấu hình Core Rule Set và Rate Limit. <br> - Gắn Web ACL vào CloudFront Distribution.</td>
      <td class="col-date">26/06/2026</td>
      <td class="col-date">26/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">6</td>
      <td class="col-task">- Kiểm tra toàn bộ luồng truy cập: <br> - User → CloudFront (*.cloudfront.net) → AWS WAF → API Gateway (JWT/Cognito). <br> - Kiểm tra CloudFront domain, HTTPS và khả năng phản hồi của hệ thống.</td>
      <td class="col-date">27/06/2026</td>
      <td class="col-date">27/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">7</td>
      <td class="col-task">- Rà soát toàn bộ cấu hình đã thực hiện. <br> - Ghi nhận kết quả triển khai và cập nhật bảng tham số (CloudFront domain, Cognito, API Gateway).</td>
      <td class="col-date">28/06/2026</td>
      <td class="col-date">28/06/2026</td>
      <td class="col-ref"></td>
    </tr>
  </tbody>
</table>

### Kết quả đạt được tuần 10:

* Hoàn thành phần hạ tầng AWS được phân công.
* Triển khai thành công Amazon Cognito, Amazon API Gateway, Amazon CloudFront và AWS WAF.
* Hoàn thiện lớp xác thực và edge theo kiến trúc Workshop (không dùng Route 53).
* Sẵn sàng tích hợp với hệ thống chung của nhóm.
