# emulation-resources
A collection of resources re: emulation for preservation and access. Maintained by myself for [personal](https://ethan-gates.com/talks/2018-02-20-talk-5) and [professional](https://www.softwarepreservationnetwork.org/emulation-as-a-service-infrastructure) reasons, but pull requests welcome!

If you have never contributed to GitLab before, feel free to [file a new issue](https://gitlab.com/EG-tech/emulation-resources/issues) with a link and I'll add it! Or just ping me [elsewhere](https://digipres.club/@The_BFOOL).

There is a related companion repository for disk imaging resources at [disk-imaging-resources](https://gitlab.com/EG-tech/disk-imaging-resources)

## Contents
- [Emulators](#emulators)
- [Software Download Sites](#software-download-sites)
- [Setup Guides](#setup-guides)
- [Hobby Sites and Computer History Resources](#hobby-sites-and-computer-history-resources)
- [Emulators Written in JavaScript](#emulators-written-in-javascript)
- [Hardware Emulators](#hardware-emulators)
- [Bibliography](#bibliography)
---

## Emulators
Organized by target system.

#### x86 PCs
- [DOSBox](https://www.dosbox.com/) (DOS-based x86 PCs)
- [PCem](http://pcem-emulator.co.uk/) (x86 PCs)
  - [86Box](https://86box.net/) (x86 PCs, fork of PCem, Windows-only)
- [Bochs](http://bochs.sourceforge.net/) (x86 PC emulation)
- [Microsoft Virtual PC](https://www.microsoft.com/en-us/download/details.aspx?id=3702) (x86 PC virtualization)
- [VirtualBox](https://www.virtualbox.org/) (x86 PC virtualization)
- [VMware](https://www.vmware.com/products/personal-desktop-virtualization.html) (x86 PC virtualization) - I think Workstation Player is the current free product/version for Windows + Linux, and Fusion for Macs, but good luck sorting that out
- [QEMU](https://www.qemu.org/) (x86 PC virtualization)
  - [Qiwi](https://gitlab.com/eg-tech/qiwi) (QEMU launcher; cross-platform Python app; developed by yours truly, feedback welcome :smile: )
  - [QEMU Manager](http://www.davereyn.co.uk/) (QEMU front-end; Windows-only)
  - [AQEMU](https://github.com/tobimensch/aqemu) (QEMU front-end, not actively developed and must be compiled from source)
  - [UTM](https://mac.getutm.app/) (QEMU front-end, macOS-only)
  - [Virtual Machine Manager](https://virt-manager.org/) (can be used as a QEMU front-end but largely targeted at managing modern KVM virtual machines/virtualization rather than emulation)  
  - [qemu-virgil](https://snapcraft.io/qemu-virgil) (QEMU build with the [Virgil 3D](https://virgil3d.github.io/) rendering library pre-configured; Linux-only Snap)
  - [qemu-screamer](https://github.com/mcayland/qemu) (QEMU fork with experimental sound support for PowerPC MacOS guests; must build from source)
- [Windows95.js](https://github.com/felixrieseberg/windows95) (Windows 95 image running in v86 - a JavaScript PC emulator, see [JS emulators](#emulators-written-in-javascript) - packaged as a desktop app)

#### Apple
- [OpenEmulator](https://github.com/openemulator/openemulator) (Apple I and Apple II series, Mac-only)
- [microM8](https://paleotronic.com/software/microm8/download/) (Apple II)
- [AppleWin](https://github.com/applewin/applewin) (Apple II series, for Windows)
  - [LinApple](http://linapple.sourceforge.net/index.html) (AppleWin port for Linux)
- [Virtual II](https://www.virtualii.com/) (Apple II, for MacOS)
- [KEGS](http://kegs.sourceforge.net/) (Apple IIgs)
  - [GSPlus](https://apple2.gs/plus/) (Apple IIgs, based on KEGS, nice interface)
  - [GSport](https://david-schmidt.github.io/gsport/) (Apple IIgs, based on KEGS, ethernet and printing cabaility)
- [LisaEm](https://lisa.sunder.net/) (Apple Lisa, for macOS + Linux)
- [Advanced Mac Substitute](https://www.v68k.org/advanced-mac-substitute/) (68k Mac emulator w/no need for ROMs or system software)
- [Shoebill](https://github.com/pruten/shoebill) (Macintosh II, IIx and IIcx emulator that runs A/UX)
- [Mini vMac](https://www.gryphel.com/c/minivmac/index.html) (early 68k Macs)
  - [µvMac "Micro vMac"](https://github.com/InvisibleUp/uvmac) (fork of Mini vMac intended for a cleaner code base and user configuration, but doesn't really work yet; worth keeping an eye on)
- [Basilisk II](https://basilisk.cebix.net/) (later 68k Macs)
  - [Macintosh.js](https://github.com/felixrieseberg/macintosh.js/) (MacOS 8 image running in JavaScript port of Basilisk, packaged as a desktop app)
- [SheepShaver](https://sheepshaver.cebix.net/) (PowerPC Macs)
- [QEMU](https://www.qemu.org/) (also does PowerPC emulation, OS 9.2.x-OSX)
- .... and keeping an eye on [Spoiled Apples](https://avpres.net/Spoiled_Apples/)

#### Commodore
- [CCS64](http://ccs64.com/) (Commodore 64, for Windows)
- [VICE](http://vice-emu.sourceforge.net/) (Commodore series)
- [UAE](https://amiga.technology/) (Amiga series)
  - [WinUAE](http://www.winuae.net/) (port for Windows)
  - [FS-UAE](https://fs-uae.net/) (port for Mac, Linux, Windows)  
- [Amiga Forever](https://www.amigaforever.com/) (Amiga, commercial product)
- [WinFellow](https://petschau.github.io/WinFellow/) (Amiga)

#### Acorn
- [BeebEm](http://www.mkw.me.uk/beebem/) (BBC Micro + Master 128)
- [Arculator](http://b-em.bbcmicro.com/arculator/index.html) (Acorn Archimedes)
- [ArcEm](http://arcem.sourceforge.net/) (Acorn Archimedes)
- [RPCEmu](http://www.marutan.net/rpcemu/index.php) (various Acorn + RiscPC machines)
- [VirtualRPC](http://www.virtualacorn.co.uk/product.htm) (RiscPC, commercial product)

#### Wang
- [Wang3300](https://www.wang3300.org/emu.html) and [Wang2200](https://www.wang2200.org/emu.html) (Wang mini/microcomputer series emulators)
- [QDAE](https://www.seasip.info/Unix/QDAE/) (Apricot series and Wang Professional Computer)

#### Xerox
- [ContrAlto](https://github.com/livingcomputermuseum/ContrAlto) (Xerox Alto)
- [Salto](http://toastytech.com/guis/salto.html) (Xerox Alto, for Windows)
- [Dark Star](https://github.com/livingcomputermuseum/Darkstar) (Xerox Star 8010)
- [Medley Interlisp](https://interlisp.org/) (not an emulator per se; modern re-write of the Medley Lisp IDE running on a portable VM, but could be used to run Lisp-based code/software in a modern environment)

#### PalmOS
- [Mu](https://meepingsnesroms.github.io/)
- [POSE (Palm OS Emulator)](https://palmdb.net/app/palm-emulator) (for Windows)

#### Multi-System
- [Clock Signal](https://github.com/tomharte/CLK) (a variety of common 8- and 16-bit PC systems)
- [Hercules](http://www.hercules-390.org/) (Mainframe sysytems, including: IBM System/370, ESA/390, z/Architecture)
- [MAME/MESS](https://www.mamedev.org/) ([wide variety](http://www.progettoemma.net/mess/) of arcade/video game machines and vintage CPUs)
- [PCE](http://www.hampa.ch/pce/) (Atari ST, IBM PC5150, and 68k Mac emulation)
- [QEMU](https://www.qemu.org/) (can also do various SPARC, MiPS, ARM, RISC-V, and other machines, see https://wiki.qemu.org/Documentation/Platforms)
- [SimH](http://simh.trailing-edge.com/) (Multi-system early microprocessor emulator)

#### Other
- [AlmostTI](https://fms.komkon.org/ATI85/) (Texas Instruments Z80-based graphing calculators)
- [Android Emulator](https://developer.android.com/studio/run/emulator) (built-in Android device emulator included in downloads for all systems with Android Studio)
- [Blackberry Simulator series](https://www.softpedia.com/dyn-search.php?search_term=blackberry+simulator&) (Blackberry mobile devices, for Windows)
- [KLH10](http://klh10.trailing-edge.com/) (DEC PDP-10 series)
- [Previous](http://previous.alternative-system.com/) (NeXT machines)
- [Ruffle](https://ruffle.rs/) (Flash Player emulator)

## Software Download Sites

I have generally had luck with these sites, but be careful out there. (WinWorld is usually the first stop, then try others)

- [ArchiveOS](https://archiveos.org/)
- [Asimov](https://ftp.apple.asimov.net)
- [BeBytes](https://www.be.wildman-productions.org/index.php)
- [Bitsavers](http://bitsavers.org/bits)
- [Dave's Old Computers](http://www.classiccmp.org/dunfield/img/index.htm)
- [Hobbes OS/2 Archive](https://hobbes.nmsu.edu/)
- [Internet Archive Software Collection](https://archive.org/details/software)
- [Macintosh Garden](http://macintoshgarden.org/)
- [Macintosh Repository](https://www.macintoshrepository.org)
- [Mac GUI](https://www.macgui.com/)
- [NeXT File Archive](http://www.nextcomputers.org/NeXTfiles/)
- [crawls of Oldapps.com](https://web.archive.org/web/http://www.oldapps.com/)  
*Note: downloads on the live site at Oldapps.com stopped working some time ago (c. 2017 or 2018), but you can sometimes still snag what you need by going to a Wayback Machine crawl from before that*
- [Oldversion.com](http://www.oldversion.com/)
- [Old versions of Linux](https://soft.lafibre.info/)
- [OSBoxes](https://www.osboxes.org/)
- [PalmDB](https://palmdb.net/)
- [PulkoMandy's BeOS software archive](http://pulkomandy.tk/~beosarchive/)
- [Retrocomputing Archive](http://www.retroarchive.org/)
- [Software Heritage source code archive](https://archive.softwareheritage.org/)
- [QEMU Advent Calendars](https://www.qemu-advent-calendar.org/)
- [Vetusware.com](https://www.vetusware.com/)
- [WinWorld](https://winworldpc.com/home)

#### ROMS
ssshhh
- https://github.com/macmade/Macintosh-ROMs
- https://www.macintoshrepository.org/7038-all-macintosh-roms-68k-ppc
- [SPARC system ROMs](https://github.com/itomato/NeXTSPARC/tree/master/ROMs/SPARC)
- [RISC OS ROMs](https://www.4corn.co.uk/aview.php?sPath=/roms)

#### Drivers
- [Drivers for QEMU's emulated devices](http://www.claunia.com/qemu/drivers/)
- [Drivers Library](http://www.driverslib.com/)
- [VOGONS Vintage Drivers](http://vogonsdrivers.com/)


## Setup Guides

#### QEMU
- [QEMU QED](https://eaasi.gitlab.io/program_docs/qemu-qed) ([Wayback](https://web.archive.org/web/20210219201541/https://eaasi.gitlab.io/program_docs/qemu-qed/))
- [QEMU Wikibooks info/guides](https://en.wikibooks.org/wiki/QEMU) ([Wayback](https://web.archive.org/web/20210218214031/https://en.wikibooks.org/wiki/QEMU))
- [QEMU Tutorials, Computer History Wiki](http://gunkies.org/wiki/Category:QEMU_Tutorials) ([Wayback](https://web.archive.org/web/20190911061951/http://gunkies.org:80/wiki/Category:QEMU_Tutorials))
- ["How to install Windows 1/2 in QEMU"](https://computernewb.com/wiki/How_to_install_Windows_1/2_in_QEMU)
- [QEMU and mouse integration in DOS, Windows 3.x, Windows 95](http://ostimeline.org/wctablet)
- ["How Linux got to be Linux: Test driving 1993-2003 distros"](https://opensource.com/article/16/12/yearbook-linux-test-driving-distros) (includes relevant QEMU configurations and tips for a bunch of older Linux OSes) ([Wayback](https://web.archive.org/web/20201108121819/https://opensource.com/article/16/12/yearbook-linux-test-driving-distros))
- ["Build your own SPARC with QEMU and Solaris"](https://learn.adafruit.com/build-your-own-sparc-with-qemu-and-solaris?view=all) (how to set up and configure Solaris with qemu-system-sparc) ([Wayback](https://web.archive.org/web/20200819152940/https://learn.adafruit.com/build-your-own-sparc-with-qemu-and-solaris?view=all))
  - [Getting Started with Solaris 2.6](https://gekk.info/articles/solaris26.htm) (builds off the previous tutorial, adds instructions for running/using particular programs) ([Wayback](https://web.archive.org/web/20200610003130/https://gekk.info/articles/solaris26.htm))
- ["Running Dano (BeOS) in Qemu"](https://discuss.haiku-os.org/t/running-dano-in-qemu/4354) ([Wayback](https://web.archive.org/web/20210219202855/https://discuss.haiku-os.org/t/running-dano-in-qemu/4354))
- ["OS/2 Warp 4 and QEMU"](https://sites.mpc.com.br/ric/qemu/index.html) ([Wayback](https://web.archive.org/web/20201025063943/http://sites.mpc.com.br/ric/qemu/index.html))
- ["QEMU with OS/2 Warp 3 as Guest"](https://wiki.gentoo.org/wiki/QEMU/OS2WarpV3_guest) ([Wayback](https://web.archive.org/web/20201001152447/https://wiki.gentoo.org/wiki/QEMU/OS2WarpV3_guest))
- ["Running Mac OS X as a QEMU/KVM Guest"](https://www.contrib.andrew.cmu.edu/~somlo/OSXKVM/) ([Wayback](https://web.archive.org/web/20210124131818/https://www.contrib.andrew.cmu.edu/~somlo/OSXKVM/))

#### VirtualBox
- Socket 3's VirtualBox setup guides:
  - [MS-DOS 6.22 & Windows 3.1](https://socket3.wordpress.com/2016/08/25/install-configure-ms-dos-6-22-and-windows-3-1-using-oracle-virtualbox/)
  - [Windows 95](https://socket3.wordpress.com/2016/09/06/install-configure-windows-95-using-oracle-virtualbox/)
  - [Windows 98](https://socket3.wordpress.com/2018/10/28/install-configure-windows-98-using-oracle-virtualbox/)
  - [Windows NT 3.1](https://socket3.wordpress.com/2016/12/18/install-configure-windows-nt-3-1-using-oracle-virtualbox/)
  - [OS/2 Warp 4.52](https://socket3.wordpress.com/2017/04/02/install-configure-ibm-os2-warp-4-52-using-oracle-virtualbox/)
  - [BeOS R5.1D](https://socket3.wordpress.com/2020/03/01/install-configure-beos-r5-1d-using-oracle-virtualbox/)
- [Windows 95/98 Guest OSes in VirtualBox](https://forums.virtualbox.org/viewtopic.php?f=2&t=33359&start=30) ([Wayback](https://web.archive.org/web/20210219202504/https://forums.virtualbox.org/viewtopic.php?f=2&t=33359&start=30))
- [Running NeXTSTEP in VirtualBox](https://sites.google.com/site/benvirtualbox/home/nextstep) ([Wayback](https://web.archive.org/web/20201006153754/https://sites.google.com/site/benvirtualbox/home/nextstep))
- [Installing NextStep OS (OpenStep) in VirtualBox](https://stuffjasondoes.com/2018/07/25/installing-nextstep-os-openstep-on-virtualbox-in-2018/) ([Wayback](https://web.archive.org/web/20201128130349/https://stuffjasondoes.com/2018/07/25/installing-nextstep-os-openstep-on-virtualbox-in-2018/))
- ["Build your own BeBox and run BeOS using Virtualbox"](https://learn.adafruit.com/build-a-bebox-with-beos-and-virtualbox?view=all#overview) ([Wayback](https://web.archive.org/web/20201029012617/https://learn.adafruit.com/build-a-bebox-with-beos-and-virtualbox?view=all))
- ["OS/2 on Virtualbox Guide"](https://gekk.info/articles/os2.html) ([Wayback](https://web.archive.org/web/20201031214848/https://gekk.info/articles/os2.html))

#### Macs
- [A Guide to Legacy Mac Emulators](https://patchbay.tech/2018/05/21/a-guide-to-legacy-mac-emulators/) ([Wayback](https://web.archive.org/web/20201125013621/https://patchbay.tech/2018/05/21/a-guide-to-legacy-mac-emulators/))
- [E-maculation How-Tos](https://emaculation.com/doku.php) ([Wayback](https://web.archive.org/web/20210104032116/https://emaculation.com/doku.php))
- [Redundant Robot SheepShaver Tutorial](http://www.redundantrobot.com/sheepshaver) ([Wayback](https://web.archive.org/web/20201118135240/https://www.redundantrobot.com/sheepshaver))

#### Other
- [DOSBox Wiki](https://www.dosbox.com/wiki/Basic_Setup_and_Installation_of_DosBox) ([Wayback](https://web.archive.org/web/20210128214159/http://www.dosbox.com/wiki/Basic_Setup_and_Installation_of_DosBox))
- ["How do I activate Windows XP nowadays (in 2019)?](https://superuser.com/questions/1502796/how-do-i-activate-windowsxp-now-that-support-has-ended)


## Hobby Sites and Computer History Resources
I've received many questions about where I get information about using and configuring old operating systems (and troubleshooting them with various emulation applications). Short answer: wherever search engines take me, even if it's a random forum post from 2004. But there are some vintage computing hobbyist sites and resources that have popped up more often, so a shoutout to those here:

- [4corn Computers](https://www.4corn.co.uk)
- [Amit Singh (kernelthread.com)](http://www.kernelthread.com/)
- [Apple Fandom Wiki](https://apple.fandom.com/wiki/Main_Screen)
- [Awesome Computer History](https://github.com/watson/awesome-computer-history)
- [Centre for Computing History](http://www.computinghistory.org.uk/pages/590/Search-Our-Archive/)
- [Commodore Computers](https://web.archive.org/web/*/https://www.commodore.ca/)
- [Computer History Museum](https://computerhistory.org/)
- [Computer History Wiki](http://gunkies.org/wiki/Main_Page)
- [Computer Hope](https://www.computerhope.com/)
- [David and Steve's Blog](https://www.savagetaylor.com/)
- [E-maculation forum](https://www.emaculation.com/forum/)
- [Emulation General wiki](https://emulation.gametechwiki.com/index.php/Main_Page)
- [EveryMac.com](https://everymac.com/)
- [Halt and Catch Fire Syllabus](https://bits.ashleyblewer.com/halt-and-catch-fire-syllabus/)
- [Infinite Mac](https://blog.persistent.info/2022/03/blog-post.html)
  - [System7.app](https://system7.app/)
  - [MacOS8.app](https://macos8.app/)
- [Info-Mac](https://www.info-mac.org/)
- [Interlisp bibliography](https://www.zotero.org/groups/2914042/interlisp/library)
- [IT History Society](https://www.ithistory.org/)
- [KnowledgeBase Archive](https://jeffpar.github.io/kbarchive/)
- [kraxel's news](https://www.kraxel.org/blog/)
- [The Linux Documentation Project](https://www.tldp.org/index.html)
- [Low End Mac](https://lowendmac.com/)
- [Macintosh Librarian](http://www.maclibrarian.com/)
- [Macintosh System Error Codes Explained (PreOSX)](http://www.macwizard.com/errors.html)
- [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)
- [NeXT Computers](http://www.nextcomputers.org/)
- [Old Computer Museum](http://www.oldcomputermuseum.com/default.htm)
- [Old-Computers.com](https://www.old-computers.com/museum/default.asp)
- [Oldlinux.org](http://oldlinux.org/)
- [The OS Files](https://web.archive.org/web/20200729003129/http://www.osfiles.com/)
- [OS/2 Museum](http://www.os2museum.com/wp/)
- [RetroWeb Vintage Computer Museum](http://retroweb.maclab.org/)
- [Siber-Sonic World O' Apple & Macintosh](https://siber-sonic.com/mac/index.html)
- [Socket 3: Bits & Bytes on Retro Computing](https://socket3.wordpress.com/)
- [System 7 Today](http://forums.system7today.com/)
- [Toasty Tech's GUI Gallery](http://toastytech.com/guis/index.html)
- [TOSEC - The Old School Emulation Center](https://www.tosecdev.org/)
- [The Ultimate Computer Acronyms Archive](/PDFs/Computer_Acronyms_Archive.pdf)
- [VintageApple.org](https://vintageapple.org/)
- [Virtually Fun](https://virtuallyfun.com/wordpress/)
- [What is the Apple IIGS](https://www.whatisthe2gs.apple2.org.za/final-assault.html)

I should also mention that the Internet Archive frequently has scanned manuals, magazines and self-help books that you can download or check out from their [eBook library](https://archive.org/details/texts)!

## Emulators Written in JavaScript

Many of the emulators listed above and more have been ported to [JavaScript](https://en.wikipedia.org/wiki/JavaScript), enabling them to be hosted and embedded on web pages and run by a browser. This is, for instance, how Internet Archive does their in-browser console and early PC emulation (e.g. with Em-DOSBox, a JS port of DOSBox, and JSMESS, a JS port of MAME/MESS).

JavaScript emulation has many advantages, especially that it makes emulated computers widely and quickly shareable. However, it passes much of the computing load on to client browsers - the entire emulator application, plus whatever operating system and applications or files the user wants to view, have to get downloaded into the user's browser. So it makes a lot of sense for early systems that barely take up much storage space or computing power by modern standards, but trying to run anything from ~2000 on (e.g. Windows XP and up) or the size of a CD-ROM runs the risk of unexpected/slow behavior, crashing the browser or client system, etc.

There are A LOT of emulators written in JavaScript, and I have found an already-existing list organized very similar to my own, so instead of recreating that work I will just link it here:

 - [Emulators written in Javascript](https://github.com/fcambus/jsemu), by @fcampbus on GitHub


## Hardware Emulators
[Hardware emulation](https://en.wikipedia.org/wiki/Hardware_emulation) refers to the process of imitating one piece of hardware with another piece of hardware. Its utility is a little unclear in preservation and archiving use cases - part of the advantage of software emulation is the portability and flexibility of working in virtual environments.

Hardware emulation projects are frequently pushed forward by retro-computing and gaming hobbyists who want, for example, to maintain and use legacy computers without relying on fragile and no-longer-produced digital media (i.e. floppy disks, CD-ROMs) or parts.

They're pretty neat though, so I thought I'd include them here.

#### Floppy Drive Emulators
- [HxC](https://hxc2001.com/)
- [Floppy Emu](https://www.bigmessowires.com/floppy-emu/)
- [GOTEK](https://www.philscomputerlab.com/gotek-floppy-emulator.html)

#### FPGAs
- [MiSTer](https://www.retrorgb.com/mister.html)

## Bibliography
For some time, I maintained a bilbiography here of published resources related to emulation and software/digital preservation, including blog posts, journal articles, use cases, discussions of copyright consideration, training modules, and more. It ultimately grew to a point that GitLab/markdown was not a great place to keep adding to it.

I have instead moved those citations and resources to a [collection on my Zotero account](https://www.zotero.org/ethan-gates/collections/ERZIYJ3T). Going forward, I will add new resources I find there - do check it out, as that page now has everything I previously linked in this repo and more. (This bibliography has also been copied/mirrored to the Software Preservation Network's [public Zotero](https://www.zotero.org/software-preservation/library)); much thanks to the SPN Training & Education working group for accepting my contribution!)


### Repository Copyright
<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="https://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="https://creativecommons.org/publicdomain/zero/1.0/">
    <img src="https://licensebuttons.net/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/EG-tech/emulation-resources">https://github.com/EG-tech/emulation-resources</a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">emulation-resources</span>.
</p>
