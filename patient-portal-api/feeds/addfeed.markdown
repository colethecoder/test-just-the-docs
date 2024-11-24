---
layout: page
title: AddFeed
nav_order: 3
parent: Feeds
---

# AddFeedAdds a new feed to the patient’s feeds and returns it.## JavaScript library method```patientportal.feed.addFeed({messageText: &lt;messageText&gt;,referral:&lt;referral&gt;});```## HTTP MethodPOST## ****Url****/patientportalapi/feed/add-feed## POST Parameters| messageText | string | Text of the first message within a new feed. Text can be formatted as HTML or plain text. || --- | --- | --- || referral | string (optional) | The key of the referral provided by the API upon GetReferrals. |## ReturnsFeedData