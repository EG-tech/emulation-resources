# emulation-resources
A collection of resources re: emulation for preservation and access.

In the spirit of the AMIA [open-workflows](https://github.com/amiaopensource/open-workflows), [analog-inspection](https://github.com/amiaopensource/analog-inspection) and [time-based-media-art](https://github.com/amiaopensource/time-based-media-art) repositories. Maintained by myself for [personal](https://ethan-gates.com/talks/2018-02-20-talk-5) and [professional](https://softwarepreservationnetwork.org/eaasi) reasons, but pull requests welcome!

If you have never contributed to GitHub before, feel free to [file a new issue](https://github.com/EG-tech/emulation-resources/issues) with a link and I'll add it! Or just ping me [elsewhere](https://digipres.club/@The_BFOOL).

## Contents
- [Emulators](#emulators)
- [Software Download Sites](#software-download-sites)
- [Setup Guides](#setup-guides)
- [Hobby Sites and Computer History Resources](#hobby-sites-and-computer-history-resources)
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
- [AppleWin](https://github.com/applewin/applewin) (Apple II, for Windows)
  - [LinApple](http://linapple.sourceforge.net/index.html) (AppleWin port for Linux)
- [Virtual II](https://www.virtualii.com/) (Apple II, for MacOS)
- [KEGS](http://kegs.sourceforge.net/) (Apple IIgs)
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
- [Previous](http://previous.alternative-system.com/) (NeXT systems)

## Software Download Sites

I have generally had luck with these sites, but be careful out there. (WinWorld is usually the first stop, then try others)

- [ArchiveOS](https://archiveos.org/)
- [Bitsavers](http://bitsavers.org/bits)
- [Hobbes OS/2 Archive](https://hobbes.nmsu.edu/)
- [Macintosh Garden](http://macintoshgarden.org/)
- [Macintosh Repository](https://www.macintoshrepository.org)
- [Mac GUI](https://www.macgui.com/)
- [Internet Archive Software Collection](https://archive.org/details/software)
- [crawls of Oldapps.com](https://web.archive.org/web/http://www.oldapps.com/)  
*Note: downloads on the live site at Oldapps.com stopped working some time ago (c. 2017 or 2018), but you can sometimes still snag what you need by going to a Wayback Machine crawl from before that*
- [Oldversion.com](http://www.oldversion.com/)
- [Old versions of Linux](https://soft.lafibre.info/)
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

- [QEMU QED](https://eaasi.gitlab.io/qemu-qed)
- [A Guide to Legacy Mac Emulators](https://patchbay.tech/2018/05/21/a-guide-to-legacy-mac-emulators/)
- [E-maculation How-Tos](https://emaculation.com/doku.php)
- [Redundant Robot SheepShaver Tutorial](http://www.redundantrobot.com/sheepshaver)
- [Running NeXTSTEP in VirtualBox](https://sites.google.com/site/benvirtualbox/home/nextstep)
- [QEMU Wikibooks info/guides](https://en.wikibooks.org/wiki/QEMU)
- [QEMU Tutorials, Computer History Wiki](http://gunkies.org/wiki/Category:QEMU_Tutorials)
- [DOSBox Wiki](https://www.dosbox.com/wiki/Basic_Setup_and_Installation_of_DosBox)
- [Windows 95/98 Guest OSes in VirtualBox](https://forums.virtualbox.org/viewtopic.php?f=2&t=33359&start=30)
- ["How Linux got to be Linux: Test driving 1993-2003 distros"](https://opensource.com/article/16/12/yearbook-linux-test-driving-distros) (includes relevant QEMU configurations and tips for a bunch of older Linux OSes)
- ["Build your own SPARC with QEMU and Solaris"](https://learn.adafruit.com/build-your-own-sparc-with-qemu-and-solaris?view=all) (how to set up and configure Solaris with qemu-system-sparc)
  - [Getting Started with Solaris 2.6](https://gekk.info/articles/solaris26.htm) (builds off the previous tutorial, adds instructions for running/using particular programs)


## Hobby Sites and Computer History Resources

I've received many questions about where I get information about using and configuring old operating systems (and troubleshooting them with various emulation applications). Short answer: wherever search engines take me, even if it's a random forum post from 2004. But there are some vintage computing hobbyist sites and resources that have popped up more often, so a shoutout to those here:

- [4corn Computers](https://www.4corn.co.uk)
- [Amit Singh (kernelthread.com)](http://www.kernelthread.com/)
- [Awesome Computer History](https://github.com/watson/awesome-computer-history)
- [Centre for Computing History](http://www.computinghistory.org.uk/pages/590/Search-Our-Archive/)
- [Computer History Museum](https://computerhistory.org/)
- [Computer History Wiki](http://gunkies.org/wiki/Main_Page)
- [Computer Hope](https://www.computerhope.com/)
- [Info-Mac](https://www.info-mac.org/)
- [IT History Society](https://www.ithistory.org/)
- [The Linux Documentation Project](https://www.tldp.org/index.html)
- [Low End Mac](https://lowendmac.com/)
- [Macintosh System Error Codes Explained (PreOSX)](http://www.macwizard.com/errors.html)
- [Old Computer Museum](http://www.oldcomputermuseum.com/default.htm)
- [Oldlinux.org](http://oldlinux.org/)
- [The OS Files](http://www.osfiles.com/index.htm)
- [OS/2 Museum](http://www.os2museum.com/wp/)
- [System 7 Today](http://forums.system7today.com/)
- [VintageApple.org](https://vintageapple.org/)
- [Virtually Fun](https://virtuallyfun.com/wordpress/)

I should also mention that the Internet Archive frequently has scanned manuals and self-help books that you can download or check out from their [eBook library](https://archive.org/details/texts)!


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
- ["Avoiding Technological Quicksand: Finding a Viable Technical Foundation for Digital Preservation"](https://clir.wordpress.clir.org/wp-content/uploads/sites/6/2016/09/pub77.pdf), Jeff Rothenberg, *A Report to the Council on Library and Information Resources*, 1999
- ["Emulation as a Digital Preservation Strategy"](http://www.dlib.org/dlib/october00/granger/10granger.html), Stewart Granger, *D-Lib Magazine Vol. 6, No. 10*, 2000
- ["Software archives as a vital base for digital preservation strategies"](http://eprints.rclis.org/14732/1/OR2010-SoftwareArchives-IEEE.pdf), Dirk von Suchodoletz, Klaus Rechert, Maurice van den Dobbelsteen, 2010
- ["QEMU - A Crucial Building Block in Digital Preservation Strategies"](http://eprints.rclis.org/15406/1/qemu-in-ltp.pdf), Dirk von Suchodoletz, Klaus Rechert, Achille Nana Tchayep, 2011
- ["Rendering Matters - Report on the results of research into digital objet rendering"](https://assets.ctfassets.net/etfoy87fj9he/5zYVqadGI4U3rVP6gHP1z9/c51d5a8907be57d202d26be2e49f84e1/rendering_matters.pdf), produced by Archives New Zealand, 2012-01-03
- "The Foundations of Emulation as a Service: An Interview with Dirk von Suchodoletz", [Part 1](https://blogs.loc.gov/thesignal/2012/12/the-foundations-of-emulation-as-a-service-an-interview-with-dirk-von-suchodoletz-part-one/) and [Part 2](https://blogs.loc.gov/thesignal/2012/12/the-foundations-of-emulation-as-a-service-an-interview-with-dirk-von-suchodoletz-part-two/), *The Signal*, 2012-12-10 and 2012-12-11
- ["The Emularity"](http://ascii.textfiles.com/archives/4546), Jason Scott, 2015-01-23
- ["Characterization of CD-ROMs for Emulation-based Access"](https://services.phaidra.univie.ac.at/api/object/o:429556/diss/Content/get), Klaus Rechert, Thomas Liebetraut, Oleg Stobbe, Isgandar Valizada, Tobias Steinke, *12th International Conference on Digital Preservation (iPRES)*, 2015
- ["Emulation and Virtualization as Preservation Strategies"](https://mellon.org/media/filer_public/0c/3e/0c3eee7d-4166-4ba6-a767-6b42e6a1c2a7/rosenthal-emulation-2015.pdf), David Rosenthal, *Mellon Foundation*, 2015
- ["How to Party Like It's 1999: Emulation for Everyone"](https://journal.code4lib.org/articles/11386), Dianne Dietrich, Julia Kim, Morgan McKeehan, and Alison Rhonemus, *The Code4Lib Journal* Issue 32, 2016-04-25
- ["Wikidata as a digital preservation knowledgebase"](https://openpreservation.org/blog/2016/09/30/wikidata-as-a-digital-preservation-knowledgebase/), Euan Cochrane, *Open Preservation Foundation blog*, 2016-09-30
- ["Classroom Access to Interactive DVDs"](https://patchbay.tech/2017/09/29/classroom-access-to-interactive-dvds/), Ethan Gates, *The Patch Bay*, 2017-09-29
- ["Exploring Email Emulation"](http://www.emailarchivestaskforce.org/documents/exploring-email-emulation/), *Task Force on Technical Approaches for Email Archives*, 2018-03-01
- ["Preserving Virtual Research Environments - Introducing CiTAR"](https://openpreservation.org/blog/2018/12/12/preserving-virtual-research-environments-introducing-citar-part-1/), Klaus Rechert, *Open Preservation Foundation blog*, 2018-12-12
- ["Teaching a Young Dog Old Tricks: Emulation Research at the National Library of Scotland"](https://dpconline.org/blog/idpd/emulation-research-nls), Sara Day Thomson, *Digital Preservation Coalition blog*, 2019-11-07
- ["Emulating Amnesia"](http://campuspress.yale.edu/borndigital/2020/01/06/emulating-amnesia/), Alice Prael and Ethan Gates, *Saving Digital Stuff blog*, 2020-01-06


### EaaSI + SPN

- ["Emulation as a Service (EaaS) at Yale University Library](https://blogs.loc.gov/thesignal/2014/08/emulation-as-a-service-eaas-at-yale-university-library/), Euan Cochrane, *The Signal*, 2014-08-20
- ["Software Preservation Literature Review"](https://osf.io/abk2g/), Jessica Meyerson, *Educopia Institute/SPN*, Fall 2017
- ["Designing a Universal Virtual Interactor for digital objects"](https://dpconline.org/blog/idpd/designing-a-uvi-for-digital-objects), Euan Cochrane, *Digital Preservation Coalition blog*, 2018-11-23
- ["Making Things EaaSIer: Overview from EaaSI's PI"](https://www.softwarepreservationnetwork.org/blog/making-things-eaasier-overview-from-eaasis-pi/), Euan Cochrane, *EaaSI Blog*, 2019-02-11
- ["Towards a Universal Virtual Interactor (UVI) for Digital Objects"](https://ipres2019.org/static/pdf/iPres2019_paper_128.pdf), Euan Cochrane, Klaus Rechert, Seth Anderson, Ethan Gates, Jessica Meyerson, *16th International Conference on Digital Preservation (iPRES)*, 2019
- ["Preserving and Integrating Community Knowledge of Computing Systems"](https://dpconline.org/blog/idpd/preserving-and-integrating-community-knowledge), Ethan Gates, *Digital Preservation Coalition blog*, 2019-11-07
- ["Software Preservation Bibliography"](https://www.zotero.org/software-preservation/items), Zotero library maintained by SPN's Training & Education Working Group
- Recorded webinars + resources from [Software Preservation Network](https://www.softwarepreservationnetwork.org/spn-resources/)


### Art and Exhibition

- ["Final Report, _Erl-King_ Project"](https://www.guggenheim.org/wp-content/uploads/2015/11/guggenheim-conservation-treatment-report-erl-king-project-2004.pdf), Isaac Dimitrovsky, 2004-04-01
- *Re-Collection: Art, New Media and Social Memory*, [Educational Resources](http://re-collection.net/educational_resources.html), Jon Ippolito, Richard Rinehart, 2014
- ["Cyberspace, the old-fashioned way"](https://rhizome.org/editorial/2015/nov/30/oldweb-today/), *Rhizome blog*, 2015-11-30
- ["The Theresa Duncan CD-ROMs: Putting interactive classics online with Emulation as a Service"](https://artsandculture.google.com/exhibit/qgIS10kvri3IJw), 2015
- ["Emulation and Access"](https://vimeo.com/278042613/a78ee5e46b), Dragan Espencheid, presentation from *Peer Forum on Disk Imaging at MoMA*, 2017-12-07
- ["Researcher Access to Born-Digital Collections: an Exploratory Study](https://elischolar.library.yale.edu/cgi/viewcontent.cgi?article=1046&context=jcas), Julia Kim, *Journal of Contemporary Archival Studies, vol. 5*, 2018
- ["_Floating Time_ with QEMU at the Denver Art Museum](http://www.dylanlorenz.net/files/Floating-Time-with-QEMU-at-the-DAM.pdf), Dylan Lorenz, *dylanlorenz.net*, 2019-09-24
- ["Introduction to an emulation-based preservation strategy for software-based art works"](https://www.tate.org.uk/download/file/fid/105887), Klaus Rechert, Patricia Falcao, Tom Ensom, *PERICLES Project, Tate*



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
