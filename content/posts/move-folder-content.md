---
title: Move folder up a level in shell
date: 2022-09-10 12:17:18
categories: software
tags: shell
---

## 情境描述

```bash
/folder/tmp -> /folder/
```

## command 
```bash
$ mv /folder/tmp/* /foler/tmp/.* /folder && rmdir /folder/tmp
```
