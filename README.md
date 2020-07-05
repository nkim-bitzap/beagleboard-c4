Collection of tools and utilities for the BeagleBoard Rev. C4

I recently re-discovered my old BeagleBoard Rev. C4 i once bought (because of the contained C64x+ DSP) to acompany our former compiler development group. The hardware didn't age that bad, however, in contrast, the software did advance quite a bit. And this usually means, there is no way of setting up a modern linux distro on an older device without suffering (at least a little).

Most information available is old (well, we are talking about an old device), somewhat inconsistent and usually incomplete. My objective was to reactivate the device again for the LLVM-TI port experiments. This reactivation means a linux distro, a compatible u-boot image, binary tools to address the DSP and of course the compiler.

LINUX:

I went Debian with applied TI patches this time. The source is cloned from https://github.com/RobertCNelson/armv7-multiplatform with "origin/ti-linux-4.19.y" being the remote branch to check out.
