---
title: "Django and Wiremock: End-to-end tests made easy"
date: 2021-08-04T17:10:00+02:00
talk_date: 2022-04-08T13:00:00+02:00
talk_by: "Rômulo Jales"
img_name: "romulo.jpeg"
remote: false
layout: "single"
stage: true
twitter: "romulojales"
description: "Django and Wiremock: End-to-end tests made easy"
youtube_id: "Crf01fcg_OE"
# slides: "https://docs.google.com/presentation/d/1OTI--ZQLLR3N8ixl4OktEwbXfiau_0BNXicl_3j5uYc/edit?usp=sharing"
# notes: "andrew.jpeg"
published: true
type: "talk"
---

Do you have tests that start your Django project and then test it by making "real" calls to external APIs?

In this talk I'm gonna introduce the concept of end-to-end tests and how to use Wiremock to help achieve its objectives alongside a Django project.

## Abstract

Tests are a central element that guarantees a project performs what has been designed for and preserves the same behavior as it grows, changes and evolves. 

It is common that projects consume 3rd parties APIs, and many projects decide either to make a real call to the API or not test the flows that consume those APIs at all. This setup is not ideal.

As an alternative, we can use wiremock to avoid making real calls and create a good end-to-end test environment.

In this presentation, I describe what is an end-to-end test, why they are important and how to create them, using concepts that I use successfully in projects that run in production. Also, I demonstrate how to analyse a bug, using end-to-end tests and how wiremock is really useful in this situation.
