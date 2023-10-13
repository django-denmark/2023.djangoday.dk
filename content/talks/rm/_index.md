---
title: "Privilege-separated installation of many Django applications on the same host"
date: 2023-08-08T10:45:00+02:00
talk_date: 2023-10-06T13:35:00+02:00
talk_by: "rm"
img_name: "rm.jpeg"
layout: "single"
remote: false
stage: true
# twitter: "aivarskalvans"
description: "Privilege-separated installation of many Django applications on the same host"
published: true
type: "talk"

youtube_id: "nWH-9kk5tac"

fediverse: "@rm@norrebro.space"
fediverse_url: "https://norrebro.space/@rm"

slides: "slides.txt"
# notes: "andrew.jpeg"
---

I run many different weakly trusted Django applications on the same host. I feel safe doing this because of the various restrictions I put on each application. I will show you how I do this. I will show how I configure the particular softwares I use, but I also invite inquiries about different softwares so that I can explain how to achieve a similar approach with different softwares.

Topics include creation of users, configuration of the firewall (pf), database configuration (particularly PostgreSQL), inter-user communication approaches (mainly doas, relayd, and PostgreSQL), privilege-separated package installation (pip, with and without venv), alignment of environment and shell configurations across the users, alignment of configuration across hosts, and configuration of WSGI servers as daemons (rc.d and rc.subr).

