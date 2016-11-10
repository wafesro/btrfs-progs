Btrfs-progs [![build status](https://travis-ci.org/kdave/btrfs-progs.svg?branch=devel)](https://travis-ci.org/kdave/btrfs-progs) [![coverity status](https://scan.coverity.com/projects/617/badge.svg)](https://scan.coverity.com/projects/btrfs-progs)
===========

Userspace utilities to manage btrfs filesystems.
License: GPLv2.

Btrfs is a copy on write (COW) filesystem for Linux aimed at implementing
advanced features while focusing on fault tolerance, repair and easy
administration.


This repository hosts following utilities:

* **btrfs** &mdash; the main administration tool ([manual page](https://btrfs.wiki.kernel.org/index.php/Manpage/btrfs))
* **mkfs.btrfs** &mdash; utility to create the filesystem ([manual page](https://btrfs.wiki.kernel.org/index.php/Manpage/mkfs.btrfs))

See INSTALL for build instructions and [tests/README.md](tests/README.md) for
testing information.

Release cycle
-------------

The major version releases are time-based and follow the cycle of the linux
kernel releases. The cycle usually takes 2 months. A minor version releases may
happen in the meantime if there are queued bug fixes or minor useful
improvements.

Development
-----------

The patch submissions, development or general discussions take place at
*linux-btrfs@vger.kernel.org* mailinglist, subsciption is not required to post.

References
----------

* [Wiki with more information](https://btrfs.wiki.kernel.org)
* [Btrfs-progs changelogs](https://btrfs.wiki.kernel.org/index.php/Changelog#By_version_.28btrfs-progs.29)
* [wiki/FAQ](https://btrfs.wiki.kernel.org/index.php/FAQ)
* [wiki/Getting started](https://btrfs.wiki.kernel.org/index.php/Getting_started)
* [wiki/TODO](https://btrfs.wiki.kernel.org/index.php/Project_ideas#Userspace_tools_projects)
* [wiki/Developer's FAQ](https://btrfs.wiki.kernel.org/index.php/Developer's_FAQ)
