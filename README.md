For now this contains patches to apply on top of Linux 3.14-rc5 that,
as the patchset grows, will allow building a functional Flight
Controller.  This is like OpenPilot, ArduCopter, MultiWii and many
others but based on an actual Linux kernel and userspace instead of
being a small custom firmware.

Testing currently done on an i.MX233 OLinuXino-Nano board but the code
is hopefully platform independent.

If this project progresses I'm going to move to a non-"patchset"
repository that may be rebased on current vanilla HEAD from time to
time, and add a userspace repository.  Currently I'm using a busybox-
based tiny rootfs with a few scripts and executables to make use of
the added kernel drivers.
