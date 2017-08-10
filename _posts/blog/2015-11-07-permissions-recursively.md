---
layout: post
title: "Set Files and Folders Permissions Recursively"
excerpt: ""
description: ""
categories: [Linux, blog]
tags: [files and folders, permissions, quick facts]
author: kerner1000
comments: true
share: true
---


```bash
find /some/directory/ -type d -exec chmod 755 {} +
find /some/directory/ -type f -exec chmod 644 {} + 
```

Files and folders need different file mode bits set even if they should have the same ‘permissions’, since a folder always needs the executable bit set to be accessible. Using chmod -R 755 * will set the executable bit as well for all files, which is never the desired result.