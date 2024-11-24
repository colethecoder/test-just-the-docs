---
layout: page
title: SendLink
nav_order: 1
parent: Password reset
---

# SendLinkSends a password reset link via an email to the patient’s personal email address or to the manager’s work email address. The link includes the portal URL with a password reset key in a format: <http://www.yourportal.com/#/password-reset?key=><key\>## JavaScript library method```patientportal.passwordReset.sendLink({ email: &lt;email&gt; });```## HTTP MethodPOST## ****Url****/patientportalapi/password-reset/send-link## URL Parameters| is-oh | bool | True for the referral portal. False for the patient portal. || --- | --- | --- |## POST Parameters| email | string | Email address. || --- | --- | --- |## RemarksThe email is sent even if the email address isn’t registered with us. In that case we inform user the email address is incorrect and we recommend them to try again or register.