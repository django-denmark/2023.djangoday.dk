---
title: "How 12 factor app helped Divio migrate over 10k Postgres instances"
date: 2021-08-04T17:10:00+02:00
talk_date: 2022-04-08T10:30:00+02:00
talk_by: "Michael Nicholson"
img_name: "michael.jpg"
remote: false
layout: "single"
stage: true
twitter: "michjnich"
description: "How 12 factor app helped Divio migrate over 10k Postgres instances"
youtube_id: "i4GQHpSb1Rk"
# slides: "https://docs.google.com/presentation/d/1OTI--ZQLLR3N8ixl4OktEwbXfiau_0BNXicl_3j5uYc/edit?usp=sharing"
# notes: "andrew.jpeg"
published: true
type: "talk"
---

When AWS announced that Postgres 9.6 would no longer be supported, Divio needed to upgrade more than 10,000 instances with minimal downtime for our customers.

Fortunately, following 12-factor app principles while developing the Divio PaaS and then enforcing them for our clients meant the solution was relatively simple and we could schedule and scale the upgrades, as well as offer the customer an easy manual solution for full flexibility.

### Talk objectives

* Introduce people to the 12-factor app, in case they aren’t already familiar with it
* Describe how the 12-factor principles made it easy for Divio to migrate over 10,000 Postgres services from 9.6 => 13, as well as give the customers control over the process if they needed it.
