---
title: /api/v1/features/get
layout: layout
categories: [ apiv1 ]
---

Gets a list of features enabled on the account.

### Parameters
None.

### Returns
A JSON object with the following properties:

* status - "ok" if the operation was successful, or "error" if there was a problem.
* features - an array containing a list of features enabled on the account.

### Example response
{% highlight javascript %}
{
	"status": "ok",
	"features": [ "planner", "hwView" ]
}
{% endhighlight %}