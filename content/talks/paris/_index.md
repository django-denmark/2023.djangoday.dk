---
title: "Taming rich text content in Django"
date: 2023-08-08T10:45:00+02:00
talk_date: 2023-10-06T16:10:00+02:00
talk_by: "Paris Kasidiaris"
img_name: "paris.jpeg"
layout: "single"
remote: false
stage: true
twitter: "pariskasid"
description: "Taming rich text content in Django"
published: true
type: "talk"
#fediverse: "@mahryekuh@fosstodon.org"
#fediverse_url: "https://fosstodon.org/@mahryekuh"

# youtube_id: "zAKcwo5Cyw8"
# slides: "https://docs.google.com/presentation/d/1OTI--ZQLLR3N8ixl4OktEwbXfiau_0BNXicl_3j5uYc/edit?usp=sharing"
# notes: "andrew.jpeg"
---

All kinds of text content is equal, but some are more equal than others. And, Django is here to help us tame one of the "more equal" forms of text; rich text. The need to handle rich text led us to create Django Prose, an open source library exactly for this. Through the process of building Django Prose we learned the good, the bad and the ugly of authoring and presenting rich text and how Django can be your ally in this. In this talk we will walk you through this journey.

## Abstract

Rich text is all around us. Virtually, every tab in your browser is rendered rich text. On the other hand, we see that web applications allowing users to author their own content, in the form of posts, comments etc., are quite reluctant in allowing users to share rich text content and for good reasons. The most important challenges; security, performance and user experience.

At [LOGIC](https://withlogic.co), we built [Django Prose](https://github.com/withlogicco/django-prose), an open-source library for this exact reason; providing Django applications with wonderful rich text text capabilities. Through the process of building this library we came to understand the different challenges that rich text poses, contrary to plain text and eventually overcome them.

In this talk, we will walk through rich text, the challenges it poses and some solutions for Django applications. In particular, first we will explore what is rich text and how it compares to plain text. Then we will navigate through the different security implications of it, with the most prominent being XSS attacks through user content and how to mitigate them. Also, we will see how rich text affects the performance of database queries in a web application compared to plain text and a few techniques in working this out. Last, we will focus on the user experience of editing and presenting rich text and a few ideas for doing both with style.

Rich text makes the web more beautiful, we want more of it and in this talk we will see how we can get more it, in the right way.


