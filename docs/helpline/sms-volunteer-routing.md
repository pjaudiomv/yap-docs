---
layout: default
title: SMS Volunteer Routing
nav_order: 10
parent: Helpline / Volunteer Routing
---

## SMS Volunteer Routing

---


This is enabled in the service body configuration through the drop down selecting "Volunteer and SMS".

There are two routing strategies, random or blast.  Blast will send to all active volunteers at that moment in time.

This is configured similarly to phone volunteer routing.  You can add shifts as `SMS` or `Phone & SMS`.

The SMS trigger keyword by default is "talk", followed by the location information.  You can override this by using the `sms_helpline_keyword` setting.  You cannot use the word "help" or "stop" by itself as these are reserved keywords by Twilio.  You could however, use a combination of words like "get help" or "need help".

As a safety measure, if no volunteers are specified with "SMS", but it's enabled on the service body configuration, it will send to the primary contact number.  
