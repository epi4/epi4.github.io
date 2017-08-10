---
layout: post
title: "prevent git user from logging in via ssh"
description: "git users should only be allowed to push and pull things from a git repository (ssh) but should have no rights on the server."
excerpt: "git users should only be allowed to push and pull things from a git repository (ssh) but should have no rights on the server."
categories: [Linux, blog]
tags: [git]
author: kerner1000
comments: true
share: true
---

0. Change `/etc/passwd` from something like this:

```bash
[...]
git:x:1001:1001:,,,:/home/git:/bin/bash
[...]
```

  to something like this:
  
```bash
[...]
git:x:1001:1001:,,,:/home/git:/usr/bin/git-shell
[...]
```

  (assuming git userid is `1001` and git home is `/home/git`)
  
0. Append to `/etc/shells` `/usr/bin/git-shell`

```bash
[...]
/usr/bin/screen
/usr/bin/git-shell
[...]
```
