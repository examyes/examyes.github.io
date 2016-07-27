---
layout: post
title: Remove Git Credential
---


找到C:\Program Files\Git\mingw64\etc\gitconfig（和你在Git安装位置有关），删除   
``` ini
[credential]   
    helper = manager   
```
