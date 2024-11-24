---
layout: page
title: \[DEPRECATED\] SendValidationEmail
nav_order: 15
parent: Authentication
---

# \[DEPRECATED\] SendValidationEmailThis method has been deprecated. Please use SendActivationEmail.Sends the validation email to the patient’s email address. Validation email includes URL to the patient portal website and contains validation key: <http://www.yourportal.com/#/confirm-email?key=><key\>## JavaScript library method```patientportal.auth.sendValidationEmail({email: &lt;email&gt;, isOH: &lt;is-oh&gt;});```## HTTP MethodGET## ****Url****/patientportalapi/auth/send-validation-email## URL Parameters| email | string | Patient’s email address. || --- | --- | --- || is-oh | bool | True for the referral portal. False for the patient portal. |## RemarksSometimes the patient needs to send the validation email again because (for example) she deletes it before activating her account or the last validation email was marked as a spam and it was deleted automatically.The client needs to submit confirmation key from the URL by calling \[DEPRECATED\] SubmitValidationEmail.