---
layout: page
title: ConfirmNotification
nav_order: 2
parent: Notifications
---

# ConfirmNotificationConfirms notification so the notification will not be returned by GetNotifications further.## JavaScript library method```patientportal.notification.confirm({notification: &lt;notification&gt;});```## HTTP MethodGET## ****Url****/patientportalapi/notification/confirm## URL Parameters| notification | string | Key of the notification provided by the API upon GetNotifications. || --- | --- | --- |## RemarksOnly certain notification types are allowed to confirm. Types that are allowed by current version of the API are:- 8 = Outstanding Messages