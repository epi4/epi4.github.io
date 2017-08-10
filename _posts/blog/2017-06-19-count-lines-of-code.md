---
layout: post
title: "Count Lines of Code"
excerpt: ""
description: ""
categories: [Java, blog]
tags: [Unix, LOC]
author: kerner1000
comments: true
share: true
---

---
Inside of the root source directory, execute

```bash
find . -name '*.java' | xargs wc -l
```
