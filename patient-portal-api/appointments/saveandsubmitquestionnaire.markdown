---
layout: page
title: SaveAndSubmitQuestionnaire
nav_order: 18
parent: Appointments
---

# SaveAndSubmitQuestionnaireCombination of SaveQuestionnaire and SubmitQuestionnaire. This method can be used on the latest questionnaire page where you may save the answers on the latest page and submit the questionnaire at once.## JavaScript library method```patientportal.appointment.saveAndSubmitQuestionnaire({questionnaire: &lt;questionnaire&gt;,answers: &lt;answers&gt;});```## HTTP MethodPOST## ****Url****/patientportalapi/appointment/save-submit-questionnaire## URL Parameters| questionnaire |     | string | The key of the questionnaire provided by the API upon GetQuestionnaires. || --- |     | --- | --- || answers | QuestionnaireAnswerData\[\] |     | Collection of answers. |## RemarksThe client calls this method when all required questions are answered. After submitting the questionnaire the status will change to Complete. The questionnaire is still accessible using GetQuestionnaires until the appointment starts (in real-life).When any required question is not answered the exception with event code 40001 is thrown (see Error handling).