---
layout: page
title: POST Data Format
nav_order: 4
parent: Communication Overview
---

Certain methods use the HTTP POST method to send data to the server. The client must format all POST data into the JSON format.

For example, the method ValidateProfileData requires two POST parameters: the ‘regCode’ and the ‘demog’. The POST data example:

```javascript
{
    "regCode": "value"
    "demog": {
        // properties
    }
}
```
