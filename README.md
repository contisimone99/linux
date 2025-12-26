This repo contains my patch for my Master Thesis for the host machine.

In order to compile this repo you should follow the [official documentation](https://canonical-kernel-docs.readthedocs-hosted.com/latest/how-to/develop-customise/build-kernel/) and update the grub in order to use it.

---

Linux kernel
============

There are several guides for kernel developers and users. These guides can
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.  The formatted documentation can also be read online at:

    https://www.kernel.org/doc/html/latest/

There are various text files in the Documentation/ subdirectory,
several of them using the Restructured Text markup notation.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.
