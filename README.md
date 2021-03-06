Installers and Scripts for Compatibility Layers
=============================

Installers and Scripts for some Compatibility Layers

Installers
=============================

### emuroot.sh

    linux-arm64 (Debian)
	linux-armel (Debian)
	linux-armhf (Debian)
	linux-i386 (Debian)
	linux-mips (Debian)
	linux-mips64el (Debian)
	linux-mipsel (Debian)
	linux-powerpc (Void Linux PPC)
	linux-powerpc64 (Void Linux PPC)
	linux-powerpc64le (Debian)
	linux-s390x (Debian)
	linux-x86_64 (Debian)

**NOTE: Requires qemu-user-static and debootstrap (qemu i386 installation is broken because of bug "Failure trying to run:  /sbin/ldconfig")**


### install_houdini32.sh

Installs Houdini (32-bit ARM Emulator) on i386 or amd64 PC


### install_houdini64.sh

Installs Houdini (64-bit ARM Emulator) on amd64 PC


### install_box86_generic.sh

Installs Box86 (x86 Emulator) on ARM 32-bit or ARM 64-bit PC

**NOTE: Requires armhf root and libc6:armhf package on ARM 64-bit PCs**


### uninstall_houdini.sh

Removes Houdini on amd64 or i386 PC

Sources
=============================
* [Houdini: run Arm 32-bit and 64-bit applications on an x86_64 system
](https://threedots.ovh/blog/2020/12/houdini-run-arm-32-bit-and-64-bit-applications-on-an-x86_64-system/)
