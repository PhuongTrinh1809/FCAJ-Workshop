---
title: "Worklog Week 10"
date: 2026-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 goals:

* Complete assigned AWS infrastructure for the project.
* Deploy the auth and edge layer (Cognito, API Gateway, CloudFront, WAF) for the ZeroBug Agent system.
* Verify service operation after configuration.

### Tasks for this week:
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
      <th>Day</th>
      <th>Task</th>
      <th>Start date</th>
      <th>End date</th>
      <th>Reference</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="col-day">1</td>
      <td class="col-task">- Prepare the Workshop deployment environment. <br> - Create IAM User and grant permissions for Amazon Cognito, Amazon API Gateway, Amazon CloudFront, and AWS WAF. <br> - Verify access permissions and configure AWS CLI for deployment.</td>
      <td class="col-date">22/06/2026</td>
      <td class="col-date">22/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">2</td>
      <td class="col-task">- Configure Amazon Cognito User Pool and SPA App Client. <br> - Set up Cognito domain, Hosted UI, and callback URL. <br> - Deploy Amazon API Gateway with JWT Authorizer, prod stage, and ALB DNS integration from Toan.</td>
      <td class="col-date">23/06/2026</td>
      <td class="col-date">23/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">3</td>
      <td class="col-task">- Deploy Amazon CloudFront Distribution. <br> - Configure Origin connected to API Gateway (leave Route 53 managed domain and Alternate domain blank). <br> - Set up Cache Behaviors, Origin request policy, and HTTPS redirect.</td>
      <td class="col-date">24/06/2026</td>
      <td class="col-date">24/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">4</td>
      <td class="col-task">- Finalize CloudFront Distribution configuration (default HTTPS on *.cloudfront.net). <br> - Update Cognito Allowed callback URLs and redirect URIs to point to the CloudFront domain. <br> - Test HTTPS access.</td>
      <td class="col-date">25/06/2026</td>
      <td class="col-date">25/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">5</td>
      <td class="col-task">- Deploy AWS WAF. <br> - Create Web ACL. <br> - Configure Core Rule Set and Rate Limit. <br> - Attach Web ACL to CloudFront Distribution.</td>
      <td class="col-date">26/06/2026</td>
      <td class="col-date">26/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">6</td>
      <td class="col-task">- Test the full access flow: <br> - User → CloudFront (*.cloudfront.net) → AWS WAF → API Gateway (JWT/Cognito). <br> - Verify CloudFront domain, HTTPS, and system response.</td>
      <td class="col-date">27/06/2026</td>
      <td class="col-date">27/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">7</td>
      <td class="col-task">- Review all completed configuration. <br> - Document deployment results and update the parameter table (CloudFront domain, Cognito, API Gateway).</td>
      <td class="col-date">28/06/2026</td>
      <td class="col-date">28/06/2026</td>
      <td class="col-ref"></td>
    </tr>
  </tbody>
</table>

### Week 10 results:

* Completed assigned AWS infrastructure.
* Successfully deployed Amazon Cognito, Amazon API Gateway, Amazon CloudFront, and AWS WAF.
* Completed the auth and edge layer per Workshop architecture (without Route 53).
* Ready to integrate with the team's shared system.
