# Awesome UNIX® 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# FAQ

###  What is UNIX?

The greatest operating system ever invented you have probably never heard about whose genius design ideas now enable everything great you love. [More...](https://en.wikipedia.org/wiki/History_of_Unix)

### Why is UNIX relevant today?

The ideas behind UNIX, a research operating system from AT&T in the 1960s, have evolved to form a set of core [computer science principles](https://en.wikipedia.org/wiki/Unix_philosophy) around which dozens of operating systems are built. These operating systems and applications built on them underpin most of modern computing, from the mobile devices in your pocket to mainframes that perform climate change analysis. They exist on a continuum that includes certified UNIX, projects descendanted from the original UNIX, and UNIX-like projects designed to be UNIX-compatible. [More...](https://en.wikipedia.org/wiki/Unix#Impact)

### Disambiguation: AT&T UNIX®, UNIX® Certification, UNIX-Like, and Linux

<a href="https://raw.githubusercontent.com/sirredbeard/Awesome-UNIX/master/venn_diagram.png"><img src="https://raw.githubusercontent.com/sirredbeard/Awesome-UNIX/master/venn_diagram.png" alt="Venn Diagram" width="600" height="500"></a>

#### Commercial UNIX®

UNIX was originally a research operating system developed at AT&T's Bell Labs.® It has evolved today into a set of operating systems standards, called [POSIX](https://en.wikipedia.org/wiki/POSIX)® overseen by the [IEEE®](https://en.wikipedia.org/wiki/POSIX), and an official certification that can be obtained by companies for their commercial operating systems, this through a process administrated by [The Open Group®](https://www.opengroup.org/openbrand/register/). Among the commercial are massive mainframe operating systems like IBM®'s AIX® as well Apple®'s macOS® desktop operating for their MacBook® and iMac® lineup.

#### UNIX Philosophy

UNIX philosophy is a core set of computer science principles, first implemented in UNIX, now codified in standards set forth by IEEE and The Open Group, and duplicated in dozens of UNIX-like operating systems that emphasize building simple, short, clear, modular, and extensible software on a common set of programming standards and libraries that allow that software to be easily maintained and repurposed by developers other than its creators, across operating systems and platforms. This enables the rapid spread and development of new and better software. It goes hand in hand with [open source philosophy](https://opensource.org/osd-annotated).

> "This is the Unix philosophy: Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface." - *Douglas McIlroy, former head of Bell Labs Computing Sciences Research Center*

#### AT&T UNIX-Derived Descendants, e.g FreeBSD®

The term UNIX also debatedbly encompasses operating systems that are direct descendants of the original AT&T UNIX codebase but have since [re-implemented the AT&T code with code under open source licenses](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution). The most prominent of which the family of BSDs: FreeBSD, OpenBSD, and NetBSD, and their derivatives. These are not UNIX certified, they are technically UNIX-like, but share a unique direct link back to AT&T UNIX and newcomers like RedoxOS do not.

#### UNIX-Like Operating Systems, e.g. Linux®

For a variety of historical and legal reasons, there has also been a massive explosion of *UNIX-like* operating systems. MINIX, for example, was created as a UNIX-like teaching operating system by Prof. Andrew S. Tanenbaum. Linux was created because Linus Torvalds, a college student, [wanted to run a UNIX-like operating system](https://www.cs.cmu.edu/~awb/linux.history.html) on his own hardware. Linux has since gone on to be come the most popular Unix-like operating system. Twenty years later, when Android, Inc. needed a kernel for their new namesake mobile operating system they borrowed one from Linux. Unix-like operating systems implement some degree of the POSIX standards and UNIX principles but do not seek official UNIX certification.

----------

# "UNIX"

## Certified UNIX® Operating Systems💰

* [macOS](https://www.apple.com/macos/)® - macOS is the current series of Unix-based graphical operating systems developed and marketed by Apple Inc. designed to run on Apple's personal computers.
* [AIX](https://www.ibm.com/power/operating-systems/aix)® - AIX is a series of proprietary Unix operating systems developed and sold by IBM for several of its computer platforms. 
* [HP-UX](https://www.hpe.com/us/en/servers/hp-ux.html)® - HP-UX is  Hewlett Packard Enterprise's proprietary implementation of the Unix operating system, based on UNIX System V.
* [UnixWare](https://www.xinuos.com)® - UnixWare is a Unix operating system made by Xinuos from the assets of SCO Group.
* [Solaris](https://www..com/solaris/solaris11/index.html)® - Solaris is a Unix operating system originally developed by Sun Microsystems, acquired by Oracle in 2010.

#### [Get More macOS](#more-macos) <br>
#### [Get More Solaris](#more-solaris)

## AT&T UNIX-Derived Operating Systems ![Open Source][OSS Icon]

* [FreeBSD](https://www.freebsd.org)® - FreeBSD is a free and open-source Unix-like operating system descended from Research Unix via the Berkeley Software Distribution (BSD) known for it's package availability.
	* [GhostBSD](http://www.ghostbsd.org) - GhostBSD is a Unix-like operating system based on FreeBSD with MATE as its default desktop environment.
	* [TrueOS](https://www.trueos.org)® - TrueOS (formerly PC-BSD or PCBSD) is a Unix-like, desktop-oriented operating system built upon the most recent releases of FreeBSD. Features Lumina desktop environment.
	* [MidnightBSD](http://www.midnightbsd.org) - MidnightBSD is a free Unix-like, desktop-oriented operating system based on FreeBSD 6.1 and borrowing heavily from the NeXTSTEP graphical user interface.
	* [PacBSD](https://pacbsd.org) - A lightweight and flexible FreeBSD distribution that implements the Pacman package manager from Arch Linux.
	* [FreeNAS](http://www.freenas.org)® - FreeNAS is a free and open-source network-attached storage (NAS) software based on FreeBSD and the OpenZFS file system.
	* [pfSense](https://www.pfsense.org)® - pfSense is an open source firewall/router computer software distribution based on FreeBSD
	* [RaspBSD](http://www.raspbsd.org) - RaspBSD is a image of FreeBSD  that is preconfigured for Raspberry Pi Computers.
	* [Open Server 10](https://www.xinuos.com/menu-products/openserver-10)® - Xinuos® OpenServer 10® is a 64-bit operating system based on the popular FreeBSD and designed to support business applications. 💰
	* [NAS4Free](https://www.nas4free.org) - NAS4Free is an embedded Open Source NAS (Network-Attached Storage) distribution based on the latest FreeBSD releases.
* [NetBSD](https://www.netbsd.org)® - NetBSD is a free and open source Unix-like operating system that descends from Berkeley Software Distribution (BSD), a Research Unix derivative developed at the University of California, Berkeley known for it's wideranging platform support.
* [OpenBSD](http://www.openbsd.org) - OpenBSD is a free and open-source Unix-like computer operating system descended from Berkeley Software Distribution (BSD), a Research Unix derivative developed at the University of California, Berkeley known for it's security and development discipline.
	* [FuguIta](http://fuguita.org/?FuguIta) - FuguIta is an OpenBSD live CD featuring portable workplace, low hardware requirements, additional software, and partial support for Japanese. 
	* [MirBSD](http://www.mirbsd.org) - Fork of OpenBSD that tracks OpenBSD base with a number of enhancements and modifications.  
* [DragonflyBSD](https://www.dragonflybsd.org) - DragonFly BSD is a free and open source Unix-like operating system created as a fork of FreeBSD 4.8.
* [PureDarwin](http://www.puredarwin.org) - PureDarwin is a operating system based on the open-source components of Apple's macOS operating system, principally code derived from NeXTSTEP, BSD, Mach, and other software projects released under free software licenses.

#### [Get More BSD](#more-bsd)

## UNIX-Certified Linux-Based Operating Systems

* [K-UX](http://www.inspursystems.com/product/32-way-system/)® - K-UX is a Linux distribution based on CentOS produced by Inspur®, a Chinese multinational company specializing in information technology. 💰
* [EulerOS](http://developer.huawei.com/ict/en/site-euleros)® -  EulerOS is a Linux distribution based on CentOS produced by Huawei®, a Chinese networking and telecommunications equipment and services company. 💰

#### [Get More UNIX](#more-unix)

# Linux
<big>The Most Popular *UNIX-Like* Operating System</big>

## Most UNIX-Like Designed Linux [Distributions](https://en.wikipedia.org/wiki/Linux_distribution) ![Open Source][OSS Icon]

* [Devuan](https://devuan.org) - Devuan Linux is a fork of Debian without systemd from UNIX veterans with the goal of becoming the new go-to base distribution for Linux. XFCE is default desktop environment.
	* [heads](https://heads.dyne.org/about.html) - heads is a live CD to connect securely over Tor, unlike Tails it does not rely on systemd or non-free software. awesome is default desktop environment.
	* [Gnuinos](http://gnuinos.org/) - Gnuinos is a lightweight Linux libre distro based on Devuan with no non-free software featuring OpenBox desktop.
	* [Dynebolic Linux](https://www.dyne.org/software/dynebolic/) - Dyne:bolic is a Free Software Foundation-approved Linux libre distro for media activists, artists and creatives. 
* [Alpine](https://alpinelinux.org) - Alpine Linux is an independent, non-commercial, general purpose Linux distribution designed for power users who appreciate security, simplicity and resource efficiency.
	* [Adélie](http://adelielinux.org/) - Adélie Linux was created by Gentoo users who combined the power of Alpine with the ease-of-use of a binary package manager. Adélie is notable for supporting x86, PowerPC, MIPS, and ARM platforms.
* [Void](https://www.voidlinux.eu) - Void is a general purpose operating system, based on the monolithic Linux kernel, Features XBPS packaging system.
* [Cucumber](http://cucumberlinux.com) - Cucumber Linux aims to provide a Linux distribution that is usable as an every day, general purpose operating system. It aims to do this in as minimalistic a way as possible and in a way that follows the Unix Philosophy. 
* [Slackware](http://www.slackware.com) - Slackware is a Linux distribution created by Patrick Volkerding in 1993. Slackware aims for design stability and simplicity and to be the most "Unix-like" Linux distribution
* [GuixSD](https://www.gnu.org/software/guix/) - GuixSD is an advanced distribution of the GNU operating system developed by the GNU Project —which respects the freedom of computer users.
* [Gentoo](https://www.gentoo.org)® - Gentoo is a Linux distribution built using the Portage package management system. Unlike a binary software distribution, the source code is compiled locally.
	* [Funtoo](https://www.funtoo.org/Welcome) - Funtoo Linux is a Linux-based operating system that is a variant of Gentoo Linux.
	* [Redcore](https://redcorelinux.org) - Redcore Linux is a distribution based on Gentoo Linux that aims to be a very quick way to install a pure Gentoo Linux system without spending hours or days compiling from source code.
* [Dragora](https://www.dragora.org/) - The Dragora project produces a libre, reliable, UNIX-like GNU/Linux distribution made from scratch!
* [Morpheus](https://morpheus.2f30.org) - Linix distribution built with staticly linked binaries using [musl libc](http://www.musl-libc.org) featuring suckless tools.
* [Stali](https://sta.li) - stali is a static linux distribution based on the original pre-2010 plans of the suckless.org project, but with a couple of revised goals.
* [OviOS](http://www.ovios.org) - OviOS is a distribution designed to easily deploy a Linux unified storage server. Written from scratch it is fully compatible with the Linux Standard Base.
* [KNOPPIX](http://www.knopper.net/) - KNOPPIX is a Debian-based distribution that can be run entirely from a CD or USB on computers with minimal hardware specificiations. Replaces systemd in Debian with sysV and systemd-shim.
* [OpenWrt](https://en.wikipedia.org/wiki/OpenWrt) - OpenWrt is an open source project for an embedded operating system based on Linux, primarily used on embedded devices to route network traffic.

## Popular Commercial Linux Distributions ![Open Source][OSS Icon]

* [Red Hat Enterprise](https://www.redhat.com)® - Red Hat Enterprise Linux is a Linux distribution developed by Red Hat® and targeted toward the commercial market. 💰
* [Ubuntu](https://ubuntu.com)® - Ubuntu is a Debian-based Linux distribution published by Canonical® who offer commercial support for enterprise-class Ubuntu Server variant.
* [SUSE Linux Enterprise](https://www.suse.com)® - SUSE Linux Enterprise workstation/server is a Linux-based operating system developed by SUSE®. It is designed for servers, mainframes, and workstations. 💰
* [elementaryOS](https://elementary.io) - elementary OS is a consumer-oriented Linux distribution based on Ubuntu. It is the flagship distribution to showcase the Pantheon desktop environment.💰
* [Oracle](https://www.oracle.com/linux/)® - Oracle Linux® is compiled from Red Hat Enterprise Linux source code, replacing Red Hat branding with Oracle's, optimized to run Oracle software. 💰
* [Pop!_OS](https://system76.com/pop) - POP!_OS is a developer-focused minimalist Linux distro from Linux hardware manufacturer System 76®.

## Popular Non-Commercial Linux Distributions ![Open Source][OSS Icon]

* [Debian](https://www.debian.org)® - Debian is a Unix-like computer operating system that is composed entirely of free software, most of which is under the GNU General Public License and packaged by a group of individuals participating in the Debian Project.
* [Fedora](https://getfedora.org)® - Fedora is an Unix-like operating system based on the Linux kernel and GNU programs (a Linux distribution), developed by the community-supported Fedora Project and sponsored by the Red Hat company.
* [CentOS](https://centos.org) - CentOS is a Linux distribution that attempts to provide a free, enterprise-class, community-supported computing platform functionally compatible with its upstream source, Red Hat Enterprise Linux.
* [Magiea](https://www.mageia.org) - Mageia is a Linux based operating system, distributed as free and open source software. It is forked from the Mandriva Linux distribution.
* [OpenSUSE](https://www.opensuse.org) - openSUSE formerly SUSE Linux and SuSE Linux Professional, is a Linux-based project and distribution sponsored by SUSE Linux GmbH and other companies.
* [Arch](https://www.archlinux.org) - Arch Linux is a Linux distribution for computers based on x86-64 architectures.
	* [Antergos](https://antergos.com) - Antergos is a Linux distribution based upon Arch Linux.
	* [Manjaro](https://manjaro.org) - Manjaro Linux is an open source operating system for computers. It is a distribution of Linux based on the Arch Linux distribution.
* [Solus](https://solus-project.com) - Solus is an independent desktop operating system based on the Linux kernel. It is offered as a curated rolling release model under the slogan "Install Today. Updates Forever".
* [Mint](https://linuxmint.com) - Linux Mint is a community-driven Linux distribution based on Debian and Ubuntu that strives to be a "modern, elegant and comfortable operating system which is both powerful and easy to use.

## Popular Mobile Linux Distributions ![Open Source][OSS Icon]

* [Android](https://source.android.com)™ - Android is a mobile operating system developed by Google®, based on the Linux kernel and designed primarily for touchscreen mobile devices such as smartphones and tablets.
* [Chrome OS](https://en.wikipedia.org/wiki/Chrome_OS)™ - Chrome OS is an operating system designed by Google that is based on the Linux kernel and uses the Google Chrome web browser as its principal user interface.
* [CopperheadOS](https://copperhead.co/android/)® - CopperheadOS is a source-available operating system for smartphones and tablet computers, based on the Android mobile platform. It is based on the official releases of the Android Open Source Project by Google, with added privacy and security features.💰
* [LineageOS](https://lineageos.org) - LineageOS is a free and open-source operating system for smartphones and tablet computers, based on the Android mobile platform.
* [postmarketOS](https://postmarketos.org) - postmarketOS, is a free and open-source operating system under development primarily for smartphones, based on the lightweight Alpine Linux distribution.

## Interesting Linux Distributions/Related Projects 

* [GoboLinux](https://www.gobolinux.org) - GoboLinux is an alternative Linux distribution which redefines the entire filesystem hierarchy. In GoboLinux you don't need a package database because the filesystem is the database. ![Open Source][OSS Icon]
* [oasis](https://github.com/michaelforney/oasis) - A small statically-linked linux system suitable for a range of uses including server and desktop. The entire system can be compiled in minutes.
* [Tails](https://tails.boum.org) - Tails is a security-focused Debian-based Linux distribution aimed at preserving privacy and anonymity ![Open Source][OSS Icon]
* [Bedrock](https://bedrocklinux.org/) - Bedrock Linux is a Linux distribution created with the aim of making most of the (often seemingly mutually-exclusive) benefits of various other Linux distributions available simultaneously and transparently. ![Open Source][OSS Icon]
* [QubesOS](https://www.qubes-os.org) - Qubes OS is a security-focused desktop operating system that aims to provide security through isolation. Virtualization is performed by Xen®, and user environments can be based on Fedora, Debian, Whonix, and Microsoft Windows, among other operating systems. ![Open Source][OSS Icon]
* [Windows Linux Subsystem](https://msdn.microsoft.com/en-us/commandline/wsl/faq) - Windows® Subsystem for Linux (WSL) is a compatibility layer for running Linux binary executables (in ELF format) natively on Windows 10.® 💰

### [Get more Linux](#more-linux)

# Other UNIX-Like/Related Operating Systems

## illumos® ![Open Source][OSS Icon]

Solaris® was originally a UNIX operating system developed jointly by Sun Microsystems® and AT&T® as a version of AT&T's UNIX System V Release 4. Sun continued development on Solaris and later obtained UNIX certification for Solaris. In 2004 Sun open-sourced much of the Solaris code base as OpenSolaris. Sun was acquired by Oracle in 2010 who discontinued formal support of the OpenSolaris project. OpenSolaris was forked and lives on as illumos.

* [illumos](https://wiki.illumos.org/display/illumos/illumos+Home) - illumos is a free and open-source Unix operating system. It derives from OpenSolaris, which in turn derives from SVR4 UNIX and Berkeley Software Distribution (BSD). 
	* [OpenIndiana](https://www.openindiana.org) - OpenIndiana is a free and open-source, Unix operating system derived from OpenSolaris and based on illumos. Developers forked OpenSolaris after Oracle Corporation discontinued it.
	* [SmartOS](https://www.joyent.com/smartos) - SmartOS is a free and open-source SVR4 hypervisor, based on the UNIX operating system that combines OpenSolaris technology with Linux's KVM virtualization. Its core kernel contributed to illumos project.
	* [OmniOS](https://omniosce.org) - OmniOS builds on Illumos to make a complete operating system and provide users with a familiar, installable operating system with a minimal package set to ease regulatory compliance.
	* [DilOS](http://www.dilos.org) - DilOS is an illumos-based platform featuring the Debian package manager (dpkg+apt).
	* [Tribblix](http://tribblix.org) - Tribblix is an operating system created by Peter Tribble. Derived from OpenSolaris, OpenIndiana, and illumos, it blends a retro style with modern components.
	* [XStreamOS](http://www.sonicle.com/index.jsp?pagename=xstreamos&parent=products) - XStreamOS is an  effort to mantain a distribution of the illumos kernel, featuring a customized text install, the ZFS fileystem, advanced features, and a starting point to contribute and develop the illumos kernel.
	
#### [Get More illumos](#more-illumos)

## Other UNIX-Like Operating Systems ![Open Source][OSS Icon]

* [Minix](http://www.minix3.org)® - Minix is a POSIX-compliant Unix-like computer operating system based on a microkernel architecture.
* [Haiku](https://www.haiku-os.org) - Haiku is a free and open-source operating system compatible with the now-discontinued BeOS.® Its development began in 2001, and the operating system became self-hosting in 2008.
* [Minoca OS](https://github.com/minoca/os) - Minoca OS is a general purpose operating system written from scratch. It aims to be lean, maintainable, modular, and compatible with existing software.
* [Redox](https://www.redox-os.org) - Redox is a Unix-like microkernel operating system written in the programming language Rust, a language with focus on safety and high performance. Redox aims to be secure, usable, and free.
* [GNUSTEP](http://www.aiei.ch/gnustep/) - GNUSTEP is a Linux live CD distribution based on Debian that prominently features the [GNUstep](https://en.wikipedia.org/wiki/GNUstep) application frameworks, a free software re-implementation of the OPENSTEP and Cocoa frameworks originally developed by NeXT with Sun Microsystems.
* [GNU/Hurd](https://www.gnu.org/software/hurd/hurd.html) - GNU Hurd is the multiserver microkernel written as part of GNU. It has been under development since 1990 by the GNU Project of the Free Software Foundation, designed as a replacement for the Unix kernel, and released as free software under the GNU General Public License.
* [Akaros](https://github.com/brho/akaros) - Akaros is an open source, GPL-licensed operating system for manycore architectures. The goal is to provide support for parallel and high-performance applications and to scale to a large number of cores.
* [Sortix](https://sortix.org) - Sortix is a small self-hosting operating-system aiming to be a clean and modern POSIX implementation, a hobbyist operating system written from scratch with its own base system, including kernel and standard library, as well as ports of third party software.
* [OpenVMS](http://www.vmssoftware.com)™ - OpenVMS is a enterprise operating system known for it's reliability. It is the successor to the VMS Operating System and runs on DEC Alpha systems. POSIX compatibility was added in 1991.

## Plan 9® Derivatives ![Open Source][OSS Icon]

Plan 9 was developed by Bell Labs as the successor to UNIX and incorporated novel ideas, such as a GUI and [distributed computing](https://en.wikipedia.org/wiki/Distributed_operating_system). Official development by Bell Labs has since halted but the code was re-released under the GPL and projects exist to build on Plan 9. Many Bell Labs employees still volunteer on these projects.

* [9front](http://9front.org) - 9front is a fork of Plan 9 from Bell Labs by the People's Front of Cat-V. It is a next generation mushroom cloud computing platform for the 20th century. 
* [9legacy](http://9legacy.org) - 9legacy is an experimental patch queue for Plan 9 from Bell Labs.
* [Harvey OS](https://harvey-os.org) - Harvey is an effort to provide a modern, distributed, 64 bit operating system. A different environment for researching and finding new lines of work. It can be built with gcc and clang and has an ANSI/POSIX compliant subsystem.
* [Inferno](http://www.vitanuova.com/inferno/)® - Inferno was an effort to commercialize Plan 9 as networking software, however like Plan 9 it remained obscure while it's ideas permeated into current operating systems. 
* [Jehanne](http://jehanne.io) - Jehanne is a new distributed operating system designed for programmers. The core values that lead the development are simplicity and security. Jehanne is a fork of Harvey.

## UNIX-Like Real Time Operating Systems ([RTOS](https://en.wikipedia.org/wiki/Real-time_operating_system))

A real-time operating system (RTOS) is an operating system (OS) intended to serve real-time applications that process data as it comes in, typically without buffer delays. An example of this in QNX which is used widely in cars and trucks.

* [QNX](https://blackberry.qnx.com/en)® - QNX is a commercial Unix-like real-time operating system, aimed primarily at the embedded systems market, found in many modern automobiles. 💰
* [Integrity](https://www.ghs.com/products/rtos/integrity.html)® - Integrity is a real-time operating systems produced and marketed by Green Hills Software. Integrity-178B has a top National Security Agency rating. 💰
* [Contiki](http://contiki-os.org) - Contiki is an operating system for networked, memory-constrained systems with a focus on low-power wireless Internet of Things devices. ![Open Source][OSS Icon]
* [LynxOS](http://www.lynx.com/products/real-time-operating-systems/lynxos-rtos/)® - The LynxOS RTOS is a Unix-like real-time operating system from Lynx Software Technologies. LynxOS features full POSIX conformance and, more recently, Linux compatibility. 💰
* [nuttX](http://nuttx.org)® - NuttX is a real-time operating system (RTOS) with an emphasis on standards compliance and small footprint. Scalable, the primary focus in NuttX are POSIX and ANSI standards. ![Open Source][OSS Icon]
* [Fuchsia](https://github.com/fuchsia-mirror?utf8=✓&query=Escher) - Fuchsia is a new real-time operating system (RTOS) [currently being developed](https://lwn.net/Articles/718267/) by Google with a degree of POSIX compataibility.

-----

# Additional Resources

## More UNIX

### Disambiguation

* [Differentiating UNIX and Linux](https://www.ibm.com/developerworks/aix/library/au-unix-difflinux.html) - From IBM
* [What, a real UNIX®?](https://www.freebsd.org/doc/en_US.ISO8859-1/articles/explaining-bsd/what-a-real-unix.html) - Excerpt from [Explaining BSD](https://www.freebsd.org/doc/en_US.ISO8859-1/articles/explaining-bsd/index.html).
* [10 differences between Linux and BSD](https://www.techrepublic.com/blog/10-things/10-differences-between-linux-and-bsd/) - From Tech Republic 📰
	
### History

* [Unix Heritage Wiki](http://wiki.tuhs.org/doku.php?id=start) - The Unix Heritage Wiki aims to collect the available historical documents of Unix into one central place so they can be studied by researchers and Unix enthusiasts alike.
* [Unix History](https://www.levenez.com/unix/) - Éric Lévénez has produced a simplified diagram of UNIX history and collected several useful other UNIX historical resources.
* [Unix and Multics](http://www.multicians.org/unix.html) - The Multicians web site presents the story of the Multics operating system for people interested in the system's history.
* [The Evolution of the Unix Time-sharing System](https://www.bell-labs.com/usr/dmr/www/hist.html) - Paper presents a brief history of the early development of the Unix operating system, by Dennis M. Ritchie.
* [A Quarter Century of Unix](http://wiki.tuhs.org/doku.php?id=publications:quarter_century_of_unix), Peter Salus, Addison-Wesley Professional, June 10, 1994, ISBN 978-0201547771. 📚
* [The C Programming Language](https://ia801303.us.archive.org/1/items/TheCProgrammingLanguageFirstEdition/The%20C%20Programming%20Language%20First%20Edition%20%5BUA-07%5D.pdf), Brian Kernighan and Dennis Ritchie, Bell Telephone Laboratories, 1978, ISBN 0131101633. 📚
* [AT&T Archives: The UNIX Operating System](https://www.youtube.com/watch?v=tc4ROCJYbm0) 📼
* [UNIX](https://archive.org/details/UNIX1985) - From "Computer Chronicles" TV Series (1985). 📼
* [UNIX](https://archive.org/details/unix_2) - From "Computer Chronicles" TV Series (1989). 📼
* [C and Unix at Bell Labs](https://www.youtube.com/watch?v=TUWt_StXKsY) - By Brian Kernighan at Vintage Computer Federation East 10 (2016). 📼

### Philosophy

* [The Art of Unix Programming](http://www.catb.org/~esr/writings/taoup/html/), Eric Steven Raymond, Thyrsus Enterprises, 2003. 📚
	* [Basics of the Unix Philosophy](http://www.catb.org/~esr/writings/taoup/html/ch01s06.html)
	* [The Unix Philosophy in One Lesson](http://www.catb.org/~esr/writings/taoup/html/ch01s07.html)
* [Program Design in the UNIX Environment](https://nymity.ch/sybilhunting/pdf/Pike1983a.pdf) 📄
* [Bringing the Unix Philosophy to Big Data](https://www.youtube.com/watch?v=S0mviKhVmBI) - By Bryan Cantrill, CTO of Joylent, developer of illumos-based SmartOS, at FutureStack13 (2013). 📼
* [Do one thing, and do it well: 40 years of UNIX](https://techcrunch.com/2009/08/21/do-one-thing-and-do-it-well-40-years-of-unix/) 📰

### Introductory UNIX Skills

* [The Unix Workbench](http://seankross.com/the-unix-workbench/) - A book for anyone to get started with Unix.
* [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - Master the command line, in one page.
* [The Bash Academy](http://www.bash.academy) - The Bash Academy is an initiative to promote the bash shell language and educate people on its use.
* [Awesome Command Line Apps](https://github.com/herrbischoff/awesome-command-line-apps) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

### Introductory Programming

* [Learn-C.org](http://www.learn-c.org) - [C](https://en.wikipedia.org/wiki/C_(programming_language)) is a general-purpose computer programming language developed at Bell Labs concurrently with UNIX. Most UNIX and NIX operating systems are still written in versions of C, with notable exceptions such as [Haiku](https://en.wikipedia.org/wiki/Haiku_(operating_system)) in [C++](https://en.wikipedia.org/wiki/C%2B%2B) and [Redox](https://en.wikipedia.org/wiki/Redox_(operating_system)) in [Rust](https://en.wikipedia.org/wiki/Rust_(programming_language)).
	* [Awesome C](https://github.com/aleksandar-todorovic/awesome-c) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [Rust Learning](https://github.com/ctjhoa/rust-learning) - A bunch of links to blog posts, articles, videos, etc for learning Rust.
	* [Awesome Rust](https://github.com/rust-unofficial/awesome-rust) - A curated list of Rust code and resources. [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [learning-fortran](https://github.com/pwittchen/learning-fortran) - Repository created in order to learn basics of Fortran, with links to several tutorials.
	* [Awesome Fortran](https://github.com/rabbiabram/awesome-fortran) - A curated list of Fortran libraries. [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [Python Learning Resources](https://github.com/CodementorIO/Python-Learning-Resources) - Resources for learning Python.
	* [Awesome Python](https://github.com/vinta/awesome-python) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

### UNIX Code/Emulation

* [WinWorld Library](https://winworldpc.com/library/operating-systems) - Collection of abandonware operating systems, including many old UNIX and UNIX-like.
* [AT&T 3B1 Emulator](http://www.philpem.me.uk/code/3b1emu/) - Emulate the original AT&T consumer UNIX.
* [The UNIX Tree](http://minnie.tuhs.org/cgi-bin/utree.pl) -  Browse the source code and manuals of various old versions of Unix
* [Unix History Repository](https://github.com/dspinellis/unix-history-repo) - The source code of the original UNIX through it's various versions implemented in git.

### UNIX/POSIX Technical Standards

* [The Open Group](http://www.opengroup.org)®
	* [UNIX Certified Products](https://www.opengroup.org/openbrand/register/)
	* [POSIX Certification Register](http://get.posixcertified.ieee.org/register.html)
* [IEEE Standard 1003.1™-2008](http://pubs.opengroup.org/onlinepubs/9699919799/)

### Community

* [nixCraft](https://www.cyberciti.biz) - NixCraft is an online community of new and seasoned Linux / Unix users.
* [LWN](https://lwn.net) - LWN is a reader-supported news site dedicated to producing the best coverage from within the Linux and free software development communities. 
* [DistroWatch](http://distrowatch.com) - DistroWatch is a website which provides news, popularity rankings, and other general information about various Linux distributions and Unix-like operating systems.
* IRC [freenode](https://webchat.freenode.net)
	* ##unixlove
	* ##climagic
	* ##kernel
* [Awesome Sysadmin](https://github.com/kahun/awesome-sysadmin) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

### UNIX/Linux-Related Trade Groups

* [USENIX](https://www.usenix.org)℠
* [The Open Group](http://opengroup.org/unix)®
* [The Linux Foundation](http://opengroup.org/unix)®
* [FreeBSD Foundation](https://www.freebsdfoundation.org)

### Notable Historic UNIX and UNIX-Like Operating Systems

* [Microsoft Xenix](https://en.wikipedia.org/wiki/Xenix) - Xenix is a discontinued version of the Unix operating system for various microcomputer platforms, licensed by Microsoft from AT&T Corporation in the late 1970s.
* [BSD386](https://en.wikipedia.org/wiki/BSD/OS) - BSD/OS (originally called BSD/386 and sometimes known as BSDi) is a discontinued proprietary version of the BSD operating system developed by Berkeley Software Design, Inc. (BSDi).
* [NeXTSTEP](https://en.wikipedia.org/wiki/NeXTSTEP) - NeXTSTEP is a discontinued object-oriented, multitasking operating system based on UNIX. It was developed by NeXT Computer in the late 1980s and early 1990s and was initially used for its range of proprietary workstation computers such as the NeXTcube.
* [IRIX](https://en.wikipedia.org/wiki/IRIX) - IRIX is a discontinued operating system developed by Silicon Graphics (SGI) to run natively on their MIPS workstations and servers. It is based on UNIX System V with BSD extensions. SGI's Indigo Magic™ Desktop for IRIX® is still [under active development](http://www.maxxinteractive.com/site/?page_id=2) for IRIX and Linux.
* [BeOS](https://en.wikipedia.org/wiki/BeOS) - BeOS is an operating system for personal computers first developed by Be Inc. in 1991 built for digital media work with partial POSIX compatibility. An open source replacement, [Haiku](https://www.haiku-os.org), is under active development.
* [MkLinux](https://en.wikipedia.org/wiki/MkLinux) - MkLinux is an open source computer operating system started by the Open Group and Apple in 1996 to port Linux to Macintosh computers. It's last release was in 2002.
* [CoLinux](https://en.wikipedia.org/wiki/Cooperative_Linux) - Cooperative Linux, abbreviated coLinux, was software which allowed Microsoft Windows and the Linux kernel to run simultaneously in parallel on the same machine.

## More macOS

* [Awesome Mac](https://github.com/jaywcjlove/awesome-mac) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [Awesome macOS Command Line](https://github.com/herrbischoff/awesome-osx-command-line) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [OS X for UNIX Users](http://images.apple.com/media/us/osx/2012/docs/OSX_for_UNIX_Users_TB_July2011.pdf) - Apple Technical Brief, July 2011
* Learning Unix for OS X: Going Deep With the Terminal and Shell, Dave Taylor, O'Reilly Media, 2nd edition (February 12, 2016), ISBN 1491939982. 📚

## More illumos

* [Fork Yeah! The Rise and Development of illumos](https://www.youtube.com/watch?v=-zRN7XLCRhc) - By Bryan Cantrill, CTO of Joylent, developer of illumos-based [SmartOS](https://www.joyent.com/smartos), at USENEX LISA '11 (2011). 📼
* [Illumos at 6](https://www.youtube.com/watch?v=29yGVdtaN_0) - By Peter Tribble, developer of illumos-based [Tribblix](http://www.tribblix.org), at FLOSSUK8 (2017). 📼
* [Awesome DTrace](https://awesome-dtrace.com) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [What are SunOS and Solaris?](https://kb.iu.edu/d/agjq)
* [UNIX Packages](http://unixpackages.com) - Archive of pre-compiled open source applications for Sun Solaris 2.5 through 11.
	
## More BSD

* [Awesome BSD](https://github.com/DiscoverBSD/awesome-bsd) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [MeetBSD](https://www.meetbsd.com) - MeetBSD is an annual event gathering of users and developers of the BSD operating systems family.
* [BSD v. Linux](https://www.over-yonder.net/~fullermd/rants/bsd4linux/01)
* [A Narrative History of BSD](https://www.youtube.com/watch?v=DEEr6dT-4uQ) - By Kirk McKusick, USENIX℠ Board Member, at MeetBSD California (2014). 📼
	
## More Linux

* [Awesome Linux Software](https://github.com/LewisVo/Awesome-Linux-Software) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [Awesome Linux](https://github.com/aleksandar-todorovic/awesome-linux) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [Linux Standard Base](https://en.wikipedia.org/wiki/Linux_Standard_Base) - LSB is an effort to develop a unifying set of standards for Linux not unlike the Open Group's standards for UNIX.

# UNIX and UNIX-Like Hardware Vendors

* [Apple](https://apple.com)® - macOS laptops and desktops, x86
* [iXsystems](https://www.ixsystems.com/servers/)® - FreeBSD servers from company that develops [TrueOS](https://www.trueos.org) and [FreeNAS](http://www.freenas.org), x86
* [System76](https://system76.com)® - Linux laptops and desktops, x86
* [Purism](https://puri.sm)® - Linux laptops, x86
* [Entroware](https://www.entroware.com/store/)® - Linux laptops, desktops, and servers, x86
* HP®
	* [Consumer/Business](http://www8.hp.com/us/en/campaigns/ubuntu/index.html)® - Linux laptops, desktops, and servers
	* [HP Enterprise](https://www.hpe.com/us/en/servers/hp-ux.html)® - HP-UX servers, x86 and PA-RISC
* [Oracle](https://www.oracle.com/servers/index.html)® - Linux and Solaris servers, x86 and SPARC
* [Dell](http://www.dell.com/learn/us/en/555/campaigns/xps-linux-laptop_us)® - Linux laptops, desktops, and servers; x86
* [IBM](https://www.ibm.com/linuxone)® - Linux and AIX servers, x86 and RISC
* [Lenovo](https://support.lenovo.com/us/en/solutions/pd031426) - Linux laptops, desktops, and servers; x86
* [Raptor Engineering](https://raptorcs.com/TALOSII/)® - Linux PowerPC® workstation
* [PowerPC Notebook](https://www.powerpc-notebook.org/) - Linux laptop with PowerPC architecture
* [StationX](https://stationx.rocks) - Linux laptops and desktops, x86
* [Fujitsu](http://www.fujitsu.com/global/products/computing/servers/unix/sparc/index.html)® - Linux and Solaris servers, SPARC®
* [Inspur](http://www.inspursystems.com/product/32-way-system/)® - Linux servers, x86
* [Huawei](http://developer.huawei.com/ict/en/site-euleros)™ - Linux servers, x86
* [Ubuntu-Certified Hardware](https://certification.ubuntu.com)

-----

### Intellectual Property Notices

* UNIX®, The Open Group®, and UnixWare® are registered trademarks of The Open Group, Inc.
* FreeBSD® is a registered trademark of The FreeBSD Foundation.
* NetBSD® is a registered trademark of The NetBSD Foundation, Inc.
* Apple®, MacBook®, iMac®, and macOS® are registered trademarks of Apple, Inc.
* Debian® is a registered trademark of Software in the Public Interest, Inc.
* IEEE®, IEEE Standard 1003.1, and POSIX® are trademarks or registered trademarks of The Institute of Electrical and Electronics Engineers, Inc.
* Bell Labs® and Plan 9® are reademarks or registered trademarks of Alcatel-Lucent USA, Inc.
* Linux® is a registered trademark of Linus Torvalds.
* AT&T® is a registered trademark of AT&T Intellectual Property II, LLC.
* AIX®, PowerPC®, and IBM® are trademarks or registered trademarks of IBM Corporation.
* HP® and HP-UX® are trademarks or registered trademarks of HP Hewlett Packard Group, LLC.
* Illumos® is a registered trademark of Garrett D'Amore.
* Xinuos® is a registered trademark of Xinuos, Inc.
* Solaris, Oracle, and Sun Microsystems are trademarks or registered trademarks of Oracle Corporation.
* Slackware is a trademark of Patrick Volkerding.
* Google®, Chrome OS™, and Android™ are registered trademarks of Alphabet, Inc.
* IXsystems®, TrueOS® and FreeNAS® are registered trademarks of IXsystems, Inc.
* BeOS® is a trademark or registered trademark of ACCESS Systems Americas, Inc. 
* Xen® is a registered trademark of the Linux Foundation.
* K-UX® and Inspur® are registered trademarks of Inspur Technologies Co., Ltd.
* EulerOS® and Huwaei® is a registered trademarks of Huawei Technologies Co., Ltd.
* pfSense® is a registered trademark of Electric Sheep Fencing, LLC.
* Inferno® is a registered trademark of Vita Nuova Holdings Ltd.
* Red Hat®, Fedora®, and Red Hat Enterprise Linux® are trademarks or registered trademarks of Red Hat, Inc.
* Ubuntu® and Canonical® are registered trademark of Canonical Limited.
* SUSE® and SUSE Linux Enterprise® are registered trademarks of SUSE.
* System76® is a registered trademark of System76, Inc.
* Windows®, Microsoft®, and Xenix® are trademarks or registered trademarks of Microsoft Corporation.
* QNX® is a registered trademark of Blackberry Limited.
* Huawei™ is is a trademark or registered trademark of Huawei Technologies Co. Ltd.
* Integrity® and Green Hills Software are registered trademarks of Green Hills Software.
* LynxOS® is a registered trademark of Lynx Software Technologies, Inc.
* CopperheadOS® is a registered trademark of Copperhead Limited.
* MINIX® is a trademark or registered trademark of Pearson Education, Inc. in the United States.
* Gentoo® is a registered trademark of Gentoo Foundation, Inc.
* Dell® is a trademark or registered trademark of Dell, Inc.
* Entroware® is a trademark of Entroware, a UK company.
* Raptor Computing Systems® is a registered trademark of Timothy Pearson.
* OpenVMS is a trademark or registered trademark of VMS Software, Inc.
* Fujistu® is a trademark or registered trademark of Fujitsu Limited.
* SPARC® is a trademark or registered trademarks of SPARC International, Inc.
* Lenovo® is a trademark or registered trademark of Lenovo Group Ltd.
* The Linux Foundation® is a registered trademark of The Linux Foundation.
* USENIX℠ is a servicemark of the Advanced Computing Systems Association.
* O'Reilly Media is a trade name of O'Reilly Media, Inc.
* The OSI logo ![Open Source][OSS Icon] is a trademark of Open Source Initiative and is used [under OSI Trademark Guidelines](https://opensource.org/trademark-guidelines#Noncommercial_and_community_web_sites).
* Joylent™ is a trademark of Joylent, Inc.
* IRIX®, SGI®, and Indigo Magic are trademarks or registered trademarks of Silicon Graphics, Inc.

All other trademarks mentioned herein are the property of their respective owners.

This document is licensed under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).

Portions of the descriptions above are from Wikipedia and used under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).

[OSS Icon]: https://cdn.rawgit.com/iCHAIT/awesome-osx/master/media/oss.svg
