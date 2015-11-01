---
title: /api/v1/csrf
layout: layout
categories: [ apiv1 ]
---

Use this to get a nonce.

### Returns
A JSON object with the following properties:
* status - "ok" if the operation was successful, or "error" if there was a problem.
* version - always "1".
* nonce - a nonce, associated with the current session.

### Example
```
{
	"status":"ok",
	"version":"1",
	"nonce":"ae74b93dd7dfc59190594d2780b86d47"
}
```