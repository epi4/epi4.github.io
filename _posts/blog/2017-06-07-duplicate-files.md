---
layout: post
title: "Find and Remove Duplicate Files"
excerpt: ""
description: ""
categories: [Unix, blog]
tags: [files and folders, duplicates]
author: kerner1000
comments: true
share: true
---

---
```bash
user@client:~$ fdupes -rdNS some/directory/
```

+ `-r`: recurse into subdirectories
+ `-d`: delete duplicates
+ `-N`: don’t ask which file to keep, just keep the first one (delete all others)
+ `-S`: show file size of duplicates