---
title: "Tying up a loose end - How class-based emails will save your day"
date: 2023-08-08T10:45:00+02:00
talk_date: 2023-10-06T10:20:00+02:00
talk_by: "Ronny Vedrilla"
img_name: "ronny.jpeg"
layout: "single"
remote: false
stage: true
# twitter: "MHLut"
description: "Tying up a loose end - How class-based emails will save your day"
published: true
type: "talk"
# fediverse: "@mahryekuh@fosstodon.org"
# fediverse_url: "https://fosstodon.org/@mahryekuh"

# youtube_id: "zAKcwo5Cyw8"
# slides: "https://docs.google.com/presentation/d/1OTI--ZQLLR3N8ixl4OktEwbXfiau_0BNXicl_3j5uYc/edit?usp=sharing"
# notes: "andrew.jpeg"
---


Improve your codebase and developer experience by using the novel class-based emails from “django-pony-express” – shipped with a test-suite – to finally have a DRY email setup and save the day!

## Abstract
 
Yes, it's possible to send emails from your Django application. And in most business cases, it's required. But is it fun? Is it DRY? Where do my variables for my base template go? Does it feel like reinventing the wheel when implementing some level of abstraction? And how the heck am I supposed to write a proper unit test? Well, in most cases, most of the Djangonauts I know including myself would go for a "no" or at least “dunno”.

That’s why I implemented "django-pony-express" to tackle those problems. Like existing djangoesque patterns and therefore easy to grasp, you'll define your emails in a neat class instead of a bunch of similar looking functions. The presented approach will take care of having duplicated templates for the plain-text and HTML parts, variables needed for your base template and much more.

But the best part: It ships with a test suite which transforms the Django test mailbox to a QuerySet-like object which can be worked with without having to have a diploma. Furthermore, it provides a best-practice to unit-test your emails to finally enable every developer in the team to test even those parts of your code.

I’m going to present the package “django-pony-express” which delivers a class-based abstraction layer like the Django Class-based views.
Emails are a crucial part of many business applications. Having worked on many (>15) different projects in various industry sectors over the last 11 years, I realised that implementing clean, reusable code for your emails is always a challenge. The whole project is neat and DRY – except your email setup and of course the duplicated templates for the plain-text and HTML part.

Here’s what I want to talk about:

* Motivation how a professional email setup looks like and what issues you must tackle to achieve it.
* Introducing the solution and its benefits and tweaks.
* Presenting the test suite and demonstrate the best practices to write unittests with it.
* Critical review and outlook to the future.

As a take-away, every attendee should have gotten an idea what’s required to create a professional email setup, why the package will help them achieve that (in less time) and how to write neat unit-tests for your mails.
