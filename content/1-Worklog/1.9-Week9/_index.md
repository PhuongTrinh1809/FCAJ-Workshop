---
title: "Worklog Week 9"
date: 2026-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 goals:

* Prepare Workshop deployment for the auth and edge layer: Cognito, API Gateway, CloudFront, and AWS WAF.
* Finalize infrastructure deployment architecture for the project.
* Research configuration processes for content delivery and security layer services.

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
      <td class="col-task">- Finalize the system architecture diagram. <br> - Review the project deployment architecture. <br> - Compare with the planned Workshop architecture.</td>
      <td class="col-date">15/06/2026</td>
      <td class="col-date">15/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">2</td>
      <td class="col-task">- Revise the architecture diagram. <br> - Finalize architecture documentation and send it to mentors for feedback.</td>
      <td class="col-date">16/06/2026</td>
      <td class="col-date">16/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">3</td>
      <td class="col-task">- Compare the original design (Route 53 + custom domain) with the new Workshop architecture. <br> - Decided to remove Route 53; use the default CloudFront domain (*.cloudfront.net) to simplify deployment and reduce costs in the workshop environment. <br> - Analyze requirements to update Cognito callback URL and production Frontend URL.</td>
      <td class="col-date">17/06/2026</td>
      <td class="col-date">17/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">4</td>
      <td class="col-task">- Build a CloudFront Distribution deployment plan (Origin pointing to API Gateway, no Route 53 managed domain). <br> - Analyze Origin, Cache Behaviors, and default HTTPS on *.cloudfront.net.</td>
      <td class="col-date">18/06/2026</td>
      <td class="col-date">18/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">5</td>
      <td class="col-task">- Research security models using AWS WAF. <br> - Select appropriate Managed Rules and Rate Limits. <br> - Research Cognito User Pool deployment and JWT Authorizer on API Gateway.</td>
      <td class="col-date">19/06/2026</td>
      <td class="col-date">19/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">6</td>
      <td class="col-task">- Analyze the full flow: <br> - User → CloudFront (*.cloudfront.net) → AWS WAF → API Gateway (JWT/Cognito) → ALB.</td>
      <td class="col-date">20/06/2026</td>
      <td class="col-date">20/06/2026</td>
      <td class="col-ref"></td>
    </tr>
    <tr>
      <td class="col-day">7</td>
      <td class="col-task">- Consolidate Workshop documentation. <br> - Prepare the deployment environment for the following week.</td>
      <td class="col-date">21/06/2026</td>
      <td class="col-date">21/06/2026</td>
      <td class="col-ref"></td>
    </tr>
  </tbody>
</table>

### Week 9 results:

* Finalized deployment architecture for the Workshop.
* Built a deployment process for Cognito, API Gateway, CloudFront, and AWS WAF (without Route 53).
* Fully prepared documentation and environment for the actual configuration phase.
