---
title: "Kolo: Understanding everything your Django app is doing at runtime"
date: 2021-08-04T17:10:00+02:00
talk_date: 2022-04-08T11:20:00+02:00
talk_by: "Wilhelm Klopp"
img_name: "wilhelm.png"
remote: false
layout: "single"
stage: true
twitter: "wilhelmklopp"
description: "Kolo: Understanding everything your Django app is doing at runtime"
# youtube_id: "zAKcwo5Cyw8"
# slides: "https://docs.google.com/presentation/d/1OTI--ZQLLR3N8ixl4OktEwbXfiau_0BNXicl_3j5uYc/edit?usp=sharing"
# notes: "andrew.jpeg"
published: true
type: "talk"
---

Reading and understanding code is a big part of our day to day lives as software developers. We're constantly learning about and exploring code that we did not write and are not familiar with. Yet the tools we have at our disposal for this frequent task leave a lot to be desired. In this talk we explore how we can make use of runtime inspection to observe what our Django app is actually doing as it's running and how that can help us more rapidly build a strong mental model that we can then draw on when writing new code.

## Abstract

One of the most time consuming aspects of creating great software is reading and understanding the code we're extending or building on top of. In fact, some say that for every 1 new line of code that we write, we first read and understand 10 other lines of code. Yet we seem to have few tools that really help us read, learn, and understand existing codebases.

This talk discusses how more often than not, we rely on our own imagination and brain power to understand and explore our codebases. We talk about where debuggers can be useful and the many places where they fall short and actually slow down our learning process.

We explore the inspection of runtime data and observing what our code is actually doing as a potential approach to speed up how quickly we can learn and understand a codebase. Specifically we look at all the information we can observe and visualise during a Django HTTP request/response cycle to help us understand everything that our code is doing.

Finally, we think about where else we could apply this idea of "runtime inspection" to solve other problems: Could this approach help us generate test cases? Or at least help us write test fixtures more quickly? Could it help us notice more quickly when our SQL queries are not efficient? And much more

## Outline

* The problem with reading and understanding code
* Inspecting runtime data as a potential solution
* Demo of Kolo: What can Kolo do today?
* The Glorious Future of collecting, inspecting, and visualizing our code at runtime
