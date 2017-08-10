---
layout: post
title: "Debug Automount Problems"
excerpt: ""
description: ""
categories: [blog]
tags: [Automount, Linux]
author: kerner1000
comments: true
share: true
---


0. Stop autofs service
```bash
sudo service autofs stop
```

0. Start automount in foreground and debug messages enabled
```bash
sudo automount -f -v
```