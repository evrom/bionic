platform_bionic
===============
Trying to build NetBSD libc on desktop amd64 linux

Why fork Bionic?
------------
Bionic contains header files and syscalls that allow BSD libc's to run on linux. Using these as a starting point will allow the port to progress towards running on linux.

Status
---------
Translating Android.mk makefiles to bsd style makefiles.
specification for that here:
[http://netbsd.gw.com/cgi-bin/man-cgi?make+1+NetBSD-5.0.1+i386](http://netbsd.gw.com/cgi-bin/man-cgi?make+1+NetBSD-5.0.1+i386)