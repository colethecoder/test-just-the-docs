---
layout: page
title: GetQuestionnairesForFutureAppointments
nav_order: 13
parent: Appointments
---

# GetQuestionnairesForFutureAppointmentsGets questionnaires for future appointments for logged in patient. Gets complete, incomplete and partially complete questionnaires.## JavaScript library method```patientportal.appointment.getQuestionnairesForFutureAppointments();```## HTTP MethodGET## ****Url****/patientportalapi/appointment/future-questionnaires## ReturnsQuestionnaireOverviewData\[\]## RemarksOverview data doesn’t contain definitions of questionnaires (questionnaire markup). The client has to call GetQuestionnaireDetail to retrieve it.