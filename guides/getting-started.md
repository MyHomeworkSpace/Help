---
title: Getting Started
layout: layout
categories: [ guide ]
---

Welcome, and thanks for your interest in the PlanHub API!

Currently, there are no helper libraries available. API calls are done via HTTPS (or HTTP if you really want) requests. Your language of choice should be able to decode and encode JSON so you can communicate with the PlanHub server.

Almost every API call requires a *nonce*, a special token that can be generated from the [/api/v1/csrf](/APIDocs/api/v1/csrf) endpoint. Each request requires its own nonce.

...to be continued...