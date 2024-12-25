---
layout: post
title: AX_MONITOR - AI powered API monitoring tool
---

### Technologies used
- Golang
- Kafka
- React.js

### Basic architecture

AX_MONITOR is an API monitoring tool that can provide realtime monitoring for any set of API endpoints.

It uses a publish-subscribe model, where the APIs are polled constantly and the updates are pushed to a Kafka topic.

A React.js dashboard subscribes to the Kakfa topic and then displays these updates in realtime.