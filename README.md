# linux-hdr-atomic-async
Copied from linux-hdr/josh-hdr-colorimtery from Joshua Ashton (https://gitlab.freedesktop.org/JoshuaAshton/linux-hdr), with the Atomic Async Patchset implemented for atomic async pageflip commits, for immediate mode with gamesope (https://lore.kernel.org/dri-devel/20220824150834.427572-1-contact@emersion.fr/)   

Full credit is provided to these individuals
- Simon Ser (contact@emersion.fr)
- Joshua Ashton (joshua@froggi.es)
- daniel.vetter@ffwll.ch, 
- mwen@igalia.com,
- alexander.deucher@amd.com, 
- hwentlan@amd.com,
- nicholas.kazlauskas@amd.com,



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
