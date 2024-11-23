---
layout: page
title: Response Data Format
nav_order: 5
parent: Communication Overview
---

All response data is formatted in the JSON data format. The server response is an envelope that always looks like this example:

```javascript
{
    "status": "ok/error"
    "result": {
        // result object according a called method&gt;
    },
    "error": {
        // a ServiceExceptionData object
    }
}
```

The response envelope includes:

- status – ‘ok’ for successful response or ‘error’ when an exception throws.
- result – returns object from the server within successful response.
- error – a ServiceExceptionData object that provides information about an exception that was thrown.

> The JavaScript API library wraps the response envelope into ‘done’ and ‘fail’ methods with an appropriate result/error object. The client that uses JavaScript API library doesn’t need to consider this envelope.