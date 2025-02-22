---
title: 'Understanding Linux Memory Management'
tags:
  - notes
---

Resource recommandation for understanding Linux.

---

**TL;DR**: Personally, I recommend to read
the book ["Understanding the Linux Virtual Memory Manager"](https://www.kernel.org/doc/gorman/html/understand/) 
and the source code.

---

**Crash course**: [Linux Kernel Labs](https://linux-kernel-labs.github.io/) provides 
a quick overview about Linux subsystems. 

Eg.
* [Memory Management](https://linux-kernel-labs.github.io/refs/heads/master/lectures/memory-management.html)
* [Filesystem Management](https://linux-kernel-labs.github.io/refs/heads/master/lectures/fs.html)

**Detailed learning**: the book ["Linux Kernel Development"](http://books.gigatux.nl/mirror/kerneldevelopment/0672327201/toc.html) 
provides a quick introduction to Linux.  

Eg. 
* [Chapter 11.  Memory Management](http://books.gigatux.nl/mirror/kerneldevelopment/0672327201/ch11.html)
* [Chapter 12.  The Virtual Filesystem](http://books.gigatux.nl/mirror/kerneldevelopment/0672327201/ch12.html)

The book ["Understanding the Linux Virtual Memory Manager"](https://www.kernel.org/doc/gorman/html/understand/) 
provides a more detailed description about memory management in Linux.

Note that the book is a bit out-of-date -- the code in it is from Linux 2.x
versions.  Nevertheless, it serves as a great guide.  Also, you can
refer to the lastest Linux source code using [Bootlin source code browser](https://elixir.bootlin.com/linux/latest/source) 
to have a sense of what current Linux behaves.

