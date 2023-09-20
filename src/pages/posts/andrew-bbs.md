---
description: An experiment in "deep web" content management
public: true
project: true
links:
  web: https://andrewbbs.net/
  github: https://github.com/lostways/andrewbbs
layout: ../../layouts/MarkdownPostLayout.astro
title: Andrew BBS
createdAt: 1695025201595
updatedAt: 1695201146742
tags:
  - projects
heroImage: /posts/andrew-bbs_thumbnail.png
slug: andrew-bbs
---

## Description
Andrew BBS is an experiment in "deep web" content management. All content must be accesed using an appropriate access code. Once screens are unlocked, they are stored in the session. Users can register as a member to save their findings.

The UI imitates a classic DOS interface invoking nostalgia for the pre-internet BBS days. All content is organized into "screens" which can be unlocked with access codes.

Site is built in Python with [Django](https://www.djangoproject.com/). The UI is a modified version of the [Bootstrap 386 Theme](https://github.com/kristopolous/BOOTSTRA.386)

![screens](/posts/andrew-bbs_screens.png)

## Features

### Passwordless OTP login via SMS
Users register and login using a one time password sent via SMS. This is implemented using the [Twilio Verification API](https://www.twilio.com/docs/verify/api).

![login](/posts/andrew-bbs_login.png)

### Messaging
Users can send messages to any other user on the system. They will get a SMS alert when a new messsage arrives.

![messaging](/posts/andrew-bbs_messaging.png)
