---
layout: post
title: "List Top 10 Largest Files and Directories"
description: ""
excerpt: ""
categories: [Linux, blog]
tags: [disk space, files and folders, free]
author: kerner1000
comments: true
share: true
---

```bash
du -hsx * 2>/dev/null | sort -rh | head -10
```

[source](http://www.cyberciti.biz/faq/how-do-i-find-the-largest-filesdirectories-on-a-linuxunixbsd-filesystem/)