---
layout: page
title: SendValidationSMS
nav_order: 1
parent: Patient Medical Report Review
---

# SendValidationSMSSends the validation code through the text message.## JavaScript library method```patientportal.patientReportReview.sendValidationSMS({key: &lt;key&gt;});```## HTTP MethodGET## ****Url****/patientportalapi/patient-report-review/send-validation-sms## URL Parameters| key | string | The validation key provided in the URL. || --- | --- | --- |## RemarksMethod does not return any data. If something goes wrong please check exception (see Error handling).