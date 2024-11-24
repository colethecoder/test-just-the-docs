---
layout: page
title: QuickSearch
nav_order: 1
parent: Patients
---

# QuickSearchReturns the patient that meets the search criteria.## JavaScript library method```patientportal.patients.quickSearch ({employeeNumber: &lt;employee-number&gt;,personalEmail: &lt;personal-email&gt;,workEmail: &lt;work-email&gt;});```## HTTP MethodGET## ****Url****/patientportalapi/patients/patient## URL Parameters| employee-number | string | The employee number of the patient. || --- | --- | --- || personal-email | string | The patient’s personal email. || work-email | string | The patient’s work email. |## ReturnsPersonDemographicData## RemarksThrows various exceptions if there are duplicate records or if the user is not allowed to access the patient record. The client must to display the error message and allow user to put full patient’s details.