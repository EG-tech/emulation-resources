# emulation-resources
A collection of resources re: emulation for preservation and access. Maintained by myself for [personal](https://ethan-gates.com/talks/2018-02-20-talk-5) and [professional](https://softwarepreservationnetwork.org/eaasi) reasons, but pull requests welcome!

If you have never contributed to GitLab before, feel free to [file a new issue](https://gitlab.com/EG-tech/emulation-resources/issues) with a link and I'll add it! Or just ping me [elsewhere](https://digipres.club/@The_BFOOL).

There is a related companion repository for disk imaging resources at [disk-imaging-resources](https://gitlab.com/EG-tech/disk-imaging-resources)

## Contents
- [Emulators](#emulators)
- [Software Download Sites](#software-download-sites)
- [Setup Guides](#setup-guides)
- [Hobby Sites and Computer History Resources](#hobby-sites-and-computer-history-resources)
- [Emulators Written in JavaScript](#emulators-written-in-javascript)
- [Hardware Emulators](#hardware-emulators)
- [Copyright](#copyright)
- [Reading](#reading)
---

## Emulators
Organized by target system.

#### x86 PCs
- [DOSBox](https://www.dosbox.com/) (DOS-based x86 PCs)
- [PCem](http://pcem-emulator.co.uk/) (x86 PCs)
- [Bochs](http://bochs.sourceforge.net/) (x86 PC emulation)
- [Microsoft Virtual PC](https://www.microsoft.com/en-us/download/details.aspx?id=3702) (x86 PC virtualization)
- [VirtualBox](https://www.virtualbox.org/) (x86 PC virtualization)
- [VMware](https://www.vmware.com/products/personal-desktop-virtualization.html) (x86 PC virtualization) - I think Workstation Player is the current free product/version for Windows + Linux, and Fusion for Macs, but good luck sorting that out
- [QEMU](https://www.qemu.org/) (x86 PC virtualization)
  - [QEMU Manager](http://www.davereyn.co.uk/) (QEMU front-end; Windows-only)
  - [AQEMU](https://github.com/tobimensch/aqemu) (QEMU front-end, not actively developed and must be compiled from source)
  - [Virtual Machine Manager](https://virt-manager.org/) (can be used as a QEMU front-end but largely targeted at managing modern KVM virtual machines/virtualization rather than emulation)  

#### Apple
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
- [Basilisk II](https://basilisk.cebix.net/) (later 68k Macs)
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

#### Multi-System
- [SimH](http://simh.trailing-edge.com/) (Multi-system early microprocessor emulator)
- [MAME/MESS](https://www.mamedev.org/) ([wide variety](http://www.progettoemma.net/mess/) of arcade/video game machines and vintage CPUs)
- [PCE](http://www.hampa.ch/pce/) (Atari ST, IBM PC5150, and 68k Mac emulation)
- [QEMU](https://www.qemu.org/) (can also do various SPARC, MiPS, ARM, RISC-V, and other machines, see https://wiki.qemu.org/Documentation/Platforms)

#### Other
- [AlmostTI](https://fms.komkon.org/ATI85/) (Texas Instruments Z80-based graphing calculators)
- [ContrAlto](https://github.com/livingcomputermuseum/ContrAlto) (Xerox Alto)
- [KLH10](http://klh10.trailing-edge.com/) (DEC PDP-10 series)
- [Previous](http://previous.alternative-system.com/) (NeXT systems)
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
- [QEMU QED](https://eaasi.gitlab.io/program-docs/qemu-qed)
- [A Guide to Legacy Mac Emulators](https://patchbay.tech/2018/05/21/a-guide-to-legacy-mac-emulators/)
- [E-maculation How-Tos](https://emaculation.com/doku.php)
- [Redundant Robot SheepShaver Tutorial](http://www.redundantrobot.com/sheepshaver)
- [Running NeXTSTEP in VirtualBox](https://sites.google.com/site/benvirtualbox/home/nextstep)
- [Installing NextStep OS (OpenStep) in VirtualBox](https://stuffjasondoes.com/2018/07/25/installing-nextstep-os-openstep-on-virtualbox-in-2018/)
- [QEMU Wikibooks info/guides](https://en.wikibooks.org/wiki/QEMU)
- [QEMU Tutorials, Computer History Wiki](http://gunkies.org/wiki/Category:QEMU_Tutorials)
- [DOSBox Wiki](https://www.dosbox.com/wiki/Basic_Setup_and_Installation_of_DosBox)
- [Windows 95/98 Guest OSes in VirtualBox](https://forums.virtualbox.org/viewtopic.php?f=2&t=33359&start=30)
- ["How Linux got to be Linux: Test driving 1993-2003 distros"](https://opensource.com/article/16/12/yearbook-linux-test-driving-distros) (includes relevant QEMU configurations and tips for a bunch of older Linux OSes)
- ["Build your own SPARC with QEMU and Solaris"](https://learn.adafruit.com/build-your-own-sparc-with-qemu-and-solaris?view=all) (how to set up and configure Solaris with qemu-system-sparc)
  - [Getting Started with Solaris 2.6](https://gekk.info/articles/solaris26.htm) (builds off the previous tutorial, adds instructions for running/using particular programs)
- ["Running Mac OS X as a QEMU/KVM Guest"](https://www.contrib.andrew.cmu.edu/~somlo/OSXKVM/)
- ["Running Dano (BeOS) in Qemu"](https://discuss.haiku-os.org/t/running-dano-in-qemu/4354)
- ["Build your own BeBox and run BeOS using Virtualbox"](https://learn.adafruit.com/build-a-bebox-with-beos-and-virtualbox?view=all#overview)
- ["OS/2 Warp 4 and QEMU"](https://sites.mpc.com.br/ric/qemu/index.html)
- ["QEMU with OS/2 Warp 3 as Guest"](https://wiki.gentoo.org/wiki/QEMU/OS2WarpV3_guest)
- ["OS/2 on Virtualbox Guide"](https://gekk.info/articles/os2.html)


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
- [E-maculation forum](https://www.emaculation.com/forum/)
- [Emulation General wiki](https://emulation.gametechwiki.com/index.php/Main_Page)
- [EveryMac.com](https://everymac.com/)
- [Halt and Catch Fire Syllabus](https://bits.ashleyblewer.com/halt-and-catch-fire-syllabus/)
- [Info-Mac](https://www.info-mac.org/)
- [IT History Society](https://www.ithistory.org/)
- [kraxel's news](https://www.kraxel.org/blog/)
- [The Linux Documentation Project](https://www.tldp.org/index.html)
- [Low End Mac](https://lowendmac.com/)
- [Macintosh System Error Codes Explained (PreOSX)](http://www.macwizard.com/errors.html)
- [NeXT Computers](http://www.nextcomputers.org/)
- [Old Computer Museum](http://www.oldcomputermuseum.com/default.htm)
- [Oldlinux.org](http://oldlinux.org/)
- [The OS Files](http://www.osfiles.com/index.htm)
- [OS/2 Museum](http://www.os2museum.com/wp/)
- [RetroWeb Vintage Computer Museum](http://retroweb.maclab.org/)
- [Siber-Sonic World O' Apple & Macintosh](https://siber-sonic.com/mac/index.html)
- [System 7 Today](http://forums.system7today.com/)
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

## Copyright
Some important guidance on copyright concerns when it comes to using emulation for preservation and access purposes. Note that these are limited to United States copyright law.

- [ARL Code of Best Practices in Fair Use for Software Preservation](https://www.arl.org/wp-content/uploads/2018/09/2019.2.28-software-preservation-code-revised.pdf)
- [A Preservationist's Guide to the DMCA Exception for Software Preservation](http://softwarepn.webmasters21.com/wp-content/uploads/2019/01/2018-12_DMCAchecklist_updated_12132018.pdf)
- ["Intellectual Property Rights Issues for Software Emulation: An Interview with Euan Cochrane, Zach Vowell and Jessica Meyerson"](https://blogs.loc.gov/thesignal/2016/01/intellectual-property-rights-issues-for-software-emulation-an-interview-with-euan-cochrane-zach-vowell-and-jessica-meyerson/), Morgan McKeehan, *The Signal*, 2016-01-22

## Reading
More scholarly considerations of emulation as an access service and digital/software preservation, and/or summaries of emulation used in cultural heritage projects:

### General
- ["Ensuring the Longevity of Digital Documents"](https://www.jstor.org/stable/24980135), Jeff Rothenberg, *Scientific American*, Vol. 272, No. 1, pp 42-7, 1995-01
  - [revised, expanded, and open version](https://www.clir.org/wp-content/uploads/sites/6/ensuring.pdf), *Council on Library and Information Resources*, 1999-02-22
- ["Metadata to Support Data Quality and Longevity"](https://web.archive.org/web/19990202095702/http://www.computer.org/conferen/meta96/rothenberg_paper/ieee.data-quality.html), Jeff Rothenberg, *The First IEEE Metadata Conference*, NOAA Auditorium, Silver Spring, MD, 1996-04-16
- ["Avoiding Technological Quicksand: Finding a Viable Technical Foundation for Digital Preservation"](https://clir.wordpress.clir.org/wp-content/uploads/sites/6/2016/09/pub77.pdf), Jeff Rothenberg, *A Report to the Council on Library and Information Resources*, 1999
- ["Using Emulation to Preserve Digital Documents"](https://www.imaginar.org/taller/dppd/DPPD/148%20pp%20usingemulation.pdf), Jeff Rothenberg, *Koninklijke Bibliotheek*, 2000-07
- ["Emulation as a Digital Preservation Strategy"](http://www.dlib.org/dlib/october00/granger/10granger.html), Stewart Granger, *D-Lib Magazine Vol. 6, No. 10*, 2000
- ["Emulation, Preservation and Abstraction"](http://sw.ccs.bcs.org/CAMiLEON/dh/ep5.html), David Holdsworth, Paul Wheatley, *CAMiLEON project*, c. 2002
- ["Modular emulation as a long-term preservation strategy for digital objects"](https://web.archive.org/web/20121120221149/http://www.iwaw.net/05/papers/iwaw05-hoeven.pdf), Jeffrey van der Hoeven, Hilde van Wijngaarden, *Proceedings of IWAW, Vienna, Austria*, 2005
- ["Emulation for Digital Preservation in Practice: The Results"](http://www.ijdc.net/article/view/50/35), Jeffrey van der Hoeven, Bram Lohman, Remco Verdegem, *International Journal of Digital Curation*, Vol. 2 No. 2, 2007
- ["Planets Project: Report Describing Results of Case Studies"](https://www.planets-project.eu/docs/reports/Planets_PA5-D3_CaseStudies-final.pdf), Dirk von Suchodoletz, Peter Bright, Paul Wheatley, Jasper Schröder, Jeffrey van der Hoeven, Remco Verdegem, *Planets Project EU deliverable*, 05-30-2008
- ["Amiga disk data recovery: progress and limitations"](https://digitalcuration.blogspot.com/2009/04/amiga-disk-data-recovery-progress-and.html), Chris Rusbridge, *Digtal Curation Blog*, 2009-04-19
- ["Emulation: From Digital Artefact to Remotely Rendered Environments"](http://www.ijdc.net/article/view/141/177), Dirk von Suchodoletz, Jeffrey van der Hoeven, *International Journal of Digital Curation*, Vol. 4 No. 3, 2009
- ["Software archives as a vital base for digital preservation strategies"](http://eprints.rclis.org/14732/1/OR2010-SoftwareArchives-IEEE.pdf), Dirk von Suchodoletz, Klaus Rechert, Maurice van den Dobbelsteen, 2010
- ["QEMU - A Crucial Building Block in Digital Preservation Strategies"](http://eprints.rclis.org/15406/1/qemu-in-ltp.pdf), Dirk von Suchodoletz, Klaus Rechert, Achille Nana Tchayep, 2011
- ["A Comprehensive Approach to Born-Digital Archives"](https://archivaria.ca/index.php/archivaria/article/view/13360/14664), Laura Carroll, Erika Farr, Peter Hornsby, Ben Ranker, *Archivaria* 72, pp 61-92, 2011-12-02
- ["Rendering Matters - Report on the results of research into digital objet rendering"](https://assets.ctfassets.net/etfoy87fj9he/5zYVqadGI4U3rVP6gHP1z9/c51d5a8907be57d202d26be2e49f84e1/rendering_matters.pdf), produced by Archives New Zealand, 2012-01-03
- ["A Measurement Framework for Evaluating Emulators for Digital Preservation"](PDFs/measurement_framework_for_evaluating_emulators.pdf), Mark Guttenbrunner, Andreas Rauber, *ACM Transactions on Information Systems*, Vol. 30, No. 2, Article 14, 2012-05
- "The Foundations of Emulation as a Service: An Interview with Dirk von Suchodoletz", [Part 1](https://blogs.loc.gov/thesignal/2012/12/the-foundations-of-emulation-as-a-service-an-interview-with-dirk-von-suchodoletz-part-one/) and [Part 2](https://blogs.loc.gov/thesignal/2012/12/the-foundations-of-emulation-as-a-service-an-interview-with-dirk-von-suchodoletz-part-two/), *The Signal*, 2012-12-10 and 2012-12-11
- ["Preserving.exe: Toward a National Strategy for Preserving Software"](http://www.digitalpreservation.gov/multimedia/documents/PreservingEXE_report_final101813.pdf), *National Digital Information Infrastructure and Preservation Program*, 2013-10
- ["The Digital Life of Salman Rushdie"](https://www.newyorker.com/tech/annals-of-technology/digital-life-salman-rushdie), Dan Rockmore, *The New Yorker*, 2014-07-29
- ["The Emularity"](http://ascii.textfiles.com/archives/4546), Jason Scott, 2015-01-23
- ["Characterization of CD-ROMs for Emulation-based Access"](https://services.phaidra.univie.ac.at/api/object/o:429556/diss/Content/get), Klaus Rechert, Thomas Liebetraut, Oleg Stobbe, Isgandar Valizada, Tobias Steinke, *12th International Conference on Digital Preservation (iPRES)*, 2015
- ["Functional Access to Forensic Disk Images in a Web Service"](https://kamwoods.net/publications/woods_functional-access-to-forensic-disk-images.pdf), Kam Woods, Christopher A. Lee, Oleg Stobbe, Thomas Liebetraut, Klaus Rechert, *12th International Conference on Digital Preservation (iPRES)*, 2015
- ["Emulation and Virtualization as Preservation Strategies"](https://mellon.org/media/filer_public/0c/3e/0c3eee7d-4166-4ba6-a767-6b42e6a1c2a7/rosenthal-emulation-2015.pdf), David Rosenthal, *Mellon Foundation*, 2015
- ["How to Party Like It's 1999: Emulation for Everyone"](https://journal.code4lib.org/articles/11386), Dianne Dietrich, Julia Kim, Morgan McKeehan, and Alison Rhonemus, *The Code4Lib Journal* Issue 32, 2016-04-25
- ["Wikidata as a digital preservation knowledgebase"](https://openpreservation.org/blog/2016/09/30/wikidata-as-a-digital-preservation-knowledgebase/), Euan Cochrane, *Open Preservation Foundation blog*, 2016-09-30
- ["Classroom Access to Interactive DVDs"](https://patchbay.tech/2017/09/29/classroom-access-to-interactive-dvds/), Ethan Gates, *The Patch Bay*, 2017-09-29
- ["Exploring Email Emulation"](http://www.emailarchivestaskforce.org/documents/exploring-email-emulation/), *Task Force on Technical Approaches for Email Archives*, 2018-03-01
- ["Preserving Virtual Research Environments - Introducing CiTAR"](https://openpreservation.org/blog/2018/12/12/preserving-virtual-research-environments-introducing-citar-part-1/), Klaus Rechert, *Open Preservation Foundation blog*, 2018-12-12
- ["Teaching a Young Dog Old Tricks: Emulation Research at the National Library of Scotland"](https://dpconline.org/blog/idpd/emulation-research-nls), Sara Day Thomson, *Digital Preservation Coalition blog*, 2019-11-07
- ["Emulating Amnesia"](http://campuspress.yale.edu/borndigital/2020/01/06/emulating-amnesia/), Alice Prael and Ethan Gates, *Saving Digital Stuff blog*, 2020-01-06
- ["Emulation Encounters: Software Preservation in Libraries, Archives, And Museums"](https://www.softwarepreservationnetwork.org/wp-content/uploads/2020/06/Emulation-Encounters_Acker_RESEARCH.pdf), Amelia Acker, *PRE-PRINT Proceedings of the 83rd Annual Meeting of the Association for Information Science & Technology*, 2020-06-26
- ["Metaphors for Understanding Born Digital Collection Access: Part III (Emulation or Strange Magic)"](https://blogs.loc.gov/thesignal/2020/08/metaphors-for-understanding-born-digital-collection-access-part-iii/), Kathleen O'Neill, *The Signal*, 2020-08-28
- ["Emulation as a Service for Heritage Institutions: Test Report"](https://www.netwerkdigitaalerfgoed.nl/wp-content/uploads/2020/11/Emulation-as-a-Service-Test-Report.pdf), Eoin O’Donohoe, *Dutch Digital Heritage Network*, 10-2020
- ["Emulating Networks - Preserving Access to Webservers"](https://openpreservation.org/blogs/emulating-networks-preserving-access-to-webservers/), Klaus Rechert, *Open Preservation Foundation blog*, 2020-11-05
- ["An Archivist's Perspective on Legacy Files"](https://blogs.loc.gov/thesignal/2020/11/an-archivists-perspective-on-legacy-files/), Chad Conrady, *The Signal*, 2020-11-16
- ["Emulation or it Didn't Happen"](https://rhizome.org/editorial/2020/dec/21/flash-preservation/), Dragan Espenschied, *Rhizome*, 2020-12-21
- ["Four Android Emulators, Two Apps"](https://www.bitsgalore.org/2021/02/09/four-android-emulators-two-apps), Johan van der Knijff, *bitsgalore*, 2021-02-09


### EaaSI + SPN
- ["Emulation as a Service (EaaS) at Yale University Library](https://blogs.loc.gov/thesignal/2014/08/emulation-as-a-service-eaas-at-yale-university-library/), Euan Cochrane, *The Signal*, 2014-08-20
- ["Software Preservation Literature Review"](https://osf.io/abk2g/), Jessica Meyerson, *Educopia Institute/SPN*, Fall 2017
- ["Designing a Universal Virtual Interactor for digital objects"](https://dpconline.org/blog/idpd/designing-a-uvi-for-digital-objects), Euan Cochrane, *Digital Preservation Coalition blog*, 2018-11-23
- ["Making Things EaaSIer: Overview from EaaSI's PI"](https://www.softwarepreservationnetwork.org/blog/making-things-eaasier-overview-from-eaasis-pi/), Euan Cochrane, *EaaSI Blog*, 2019-02-11
- ["Towards a Universal Virtual Interactor (UVI) for Digital Objects"](https://ipres2019.org/static/pdf/iPres2019_paper_128.pdf), Euan Cochrane, Klaus Rechert, Seth Anderson, Ethan Gates, Jessica Meyerson, *16th International Conference on Digital Preservation (iPRES)*, 2019
- ["Preserving and Integrating Community Knowledge of Computing Systems"](https://dpconline.org/blog/idpd/preserving-and-integrating-community-knowledge), Ethan Gates, *Digital Preservation Coalition blog*, 2019-11-07
- ["Sustaining Software Preservation Efforts Through Use and Communities of Practice"](https://doi.org/10.2218/ijdc.v15i1.696), Fernando Rios, Monqiue Lassere, Judd Ethan Ruggill, Ken S. McAllister, *International Journal of Digital Curation, Vol. 15 No. 1*, 2020-08-02
- ["The EaaSI Interaction API"](https://www.dpconline.org/blog/wdpd/blog-euan-cochrane-wdpd), Euan Cochrane, *Digital Preservation Coalition blog*, 2020-11-05
- ["Introducing the YUL Emulation Viewer](https://campuspress.yale.edu/borndigital/2020/11/05/introducing-the-yul-emulation-viewer/), Seth Anderson, *Saving Digital Stuff blog*, 2020-11-05
- ["Software Preservation Bibliography"](https://www.zotero.org/software-preservation/items), Zotero library maintained by SPN's Training & Education Working Group
- Recorded webinars + resources from [Software Preservation Network](https://www.softwarepreservationnetwork.org/spn-resources/)
- EaaSI Training Modules:
  - [#1: Emulation Environments](https://www.softwarepreservationnetwork.org/eaasi-training-module-emulation-environments/), 2020-10
  - [#2: Software vs. Content](https://www.softwarepreservationnetwork.org/eaasi-training-module-2-software-and-content/), 2021-01
- EaaSI Case Studies:
  - [#1: The Would-Be Gentleman](https://www.softwarepreservationnetwork.org/eaasi-case-study-1-the-would-be-gentleman/), 2021-01
- EaaSI Roundtable Discussions:
  - [What We Talk About When We Talk About Emulation](https://www.softwarepreservationnetwork.org/eaasi-roundtable-1/), 2021-01


### Art and Exhibition
- ["Final Report, _Erl-King_ Project"](https://www.guggenheim.org/wp-content/uploads/2015/11/guggenheim-conservation-treatment-report-erl-king-project-2004.pdf), Isaac Dimitrovsky, 2004-04-01
- *Re-Collection: Art, New Media and Social Memory*, [Educational Resources](http://re-collection.net/educational_resources.html), Jon Ippolito, Richard Rinehart, 2014
- ["Cyberspace, the old-fashioned way"](https://rhizome.org/editorial/2015/nov/30/oldweb-today/), *Rhizome blog*, 2015-11-30
- ["The Theresa Duncan CD-ROMs: Putting interactive classics online with Emulation as a Service"](https://artsandculture.google.com/exhibit/qgIS10kvri3IJw), 2015
- ["Emulation and Access"](https://vimeo.com/278042613/a78ee5e46b), Dragan Espencheid, presentation from *Peer Forum on Disk Imaging at MoMA*, 2017-12-07
- ["Researcher Access to Born-Digital Collections: an Exploratory Study](https://elischolar.library.yale.edu/cgi/viewcontent.cgi?article=1046&context=jcas), Julia Kim, *Journal of Contemporary Archival Studies, vol. 5*, 2018
- ["_Floating Time_ with QEMU at the Denver Art Museum](http://www.dylanlorenz.net/files/Floating-Time-with-QEMU-at-the-DAM.pdf), Dylan Lorenz, *dylanlorenz.net*, 2019-09-24
- ["Introduction to an emulation-based preservation strategy for software-based art works"](https://www.tate.org.uk/download/file/fid/105887), Klaus Rechert, Patricia Falcao, Tom Ensom, *PERICLES Project, Tate*
- [Christine Tamblyn's Interactive CD-ROM Artworks](https://sites.google.com/view/tamblynproject), Carolina Quezada Meneses, *UC Irvine Libraries Special Collections & Archives*, 2020


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
