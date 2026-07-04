---
title: "Worklog Tuần 9"
date: 2026-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Chuẩn bị triển khai Workshop về lớp xác thực và edge: Cognito, API Gateway, CloudFront và AWS WAF.
* Hoàn thiện kiến trúc triển khai hạ tầng cho đồ án.
* Nghiên cứu quy trình cấu hình các dịch vụ phục vụ lớp phân phối nội dung và bảo mật.

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
      <td class="col-task">- Hoàn thiện sơ đồ kiến trúc hệ thống. <br> - Rà soát kiến trúc triển khai của đồ án. <br> - Đối chiếu với kiến trúc Workshop dự kiến triển khai.</td>
      <td class="col-date">15/06/2026</td>
      <td class="col-date">15/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">2</td>
      <td class="col-task">- Chỉnh sửa sơ đồ kiến trúc. <br> - Hoàn thiện tài liệu kiến trúc và gửi cho các anh/chị hướng dẫn góp ý.</td>
      <td class="col-date">16/06/2026</td>
      <td class="col-date">16/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">3</td>
      <td class="col-task">- Đối chiếu thiết kế ban đầu (Route 53 + custom domain) với kiến trúc Workshop mới. <br> - Quyết định bỏ Route 53; dùng CloudFront domain mặc định (*.cloudfront.net) để đơn giản hóa triển khai và giảm chi phí trong môi trường workshop. <br> - Phân tích yêu cầu cập nhật Cognito callback URL và URL production Frontend.</td>
      <td class="col-date">17/06/2026</td>
      <td class="col-date">17/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">4</td>
      <td class="col-task">- Xây dựng phương án triển khai CloudFront Distribution (Origin trỏ API Gateway, không cấu hình Route 53 managed domain). <br> - Phân tích Origin, Cache Behaviors và HTTPS mặc định trên *.cloudfront.net.</td>
      <td class="col-date">18/06/2026</td>
      <td class="col-date">18/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">5</td>
      <td class="col-task">- Nghiên cứu mô hình bảo mật bằng AWS WAF. <br> - Lựa chọn các Managed Rules và Rate Limit phù hợp. <br> - Nghiên cứu quy trình triển khai Cognito User Pool, JWT Authorizer trên API Gateway.</td>
      <td class="col-date">19/06/2026</td>
      <td class="col-date">19/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">6</td>
      <td class="col-task">- Phân tích toàn bộ luồng: <br> - User → CloudFront (*.cloudfront.net) → AWS WAF → API Gateway (JWT/Cognito) → ALB.</td>
      <td class="col-date">20/06/2026</td>
      <td class="col-date">20/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">7</td>
      <td class="col-task">- Tổng hợp tài liệu Workshop. <br> - Chuẩn bị môi trường triển khai trong tuần tiếp theo.</td>
      <td class="col-date">21/06/2026</td>
      <td class="col-date">21/06/2026</td>
      <td class="col-ref"></td>
    </tr>
  </tbody>
</table>

### Kết quả đạt được tuần 9:

* Hoàn thiện kiến trúc triển khai cho Workshop.
* Xây dựng được quy trình triển khai Cognito, API Gateway, CloudFront và AWS WAF (không dùng Route 53).
* Chuẩn bị đầy đủ tài liệu và môi trường cho giai đoạn cấu hình thực tế.
