---
layout: post
title: "WordPress: Categories and Tags result in page not found on server"
excerpt: "When selecting a Category or a Tag from your wordpress site, an error is occouring: “page not found on server”."
description: "When selecting a Category or a Tag from your wordpress site, an error is occouring: “page not found on server”."
categories: [blog]
tags: [page-not-found-on-server, WordPress]
author: kerner1000
comments: true
share: true
---

**Problem:**
When selecting a Category or a Tag from your wordpress site, an error is occouring: *page not found on server*.

**Solution:**
Activate Apache2 `mod_rewrite`:
```bash
sudo a2enmod rewrite
sudo service apache2 restart
```
