---
layout: note
title: dream strace
date: 2025-09-01
---

i do not dream in color i dream in strace

```
openat(AT_FDCWD, "/home/me/.secret", O_RDONLY) = -1 ENOENT
openat(AT_FDCWD, "/home/me/.secret", O_RDONLY) = -1 ENOENT
openat(AT_FDCWD, "/home/me/.secret", O_RDONLY) = -1 ENOENT
```

same path. same error. different night. once it returned 3 and i woke up sweating and the file was still not there in the morning. file descriptor 3 was stderr. of course it was. the dream knew before i did that the secret is just another way of saying "look at what you already dump errors into"
