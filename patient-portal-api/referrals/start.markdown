---
layout: page
title: Start
nav_order: 3
parent: Referrals
---

# StartStarts and returns a new referral.## JavaScript library method```patientportal.referrals.start({patient: &lt;patient&gt;,appointmentType: &lt;appointment-type&gt;,caseTitle: &lt;case-title&gt;});```## HTTP MethodGET## ****Url****/patientportalapi/referrals/start## URL Parameters| patient | string | The key of the patient provided by the API upon section Patients. || --- | --- | --- || appointmentType | string | The key of the appointment type provided by the API upon GetAppointmentTypes. To find out how to work with referral appointments please read section **Error! Reference source not found.**. || caseTitle | string | The reason for starting the referral. |## ReturnsReferralData