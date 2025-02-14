- `xfs_repair`: repair an XFS filesystem
- `zipinfo`: list detailed information about a ZIP archive
- `usb_modeswitch_dispatcher`: Linux wrapper for usb_modeswitch (not intended for direct invocation)
- `version.1s`: print OpenSSL version information
- `a2p`: Awk to Perl translator
- `zipnote`: write the comments in zipfile to stdout, edit comments and rename files in zipfile
- `encfs`:  encrypted virtual filesystem
 EncFS integrates file system encryption into the Unix(TM) file system.
 Encrypted data is stored within the native file system, thus no
 fixed-size loopback image is required.
 .
 EncFS uses the FUSE kernel driver and library as a backend.


- `brew`: The missing package manager for macOS
- `userdel`: delete a user account and related files
- `base32`: base32 encode/decode data and print to standard output
- `acpi_available`: test whether ACPI subsystem is available
- `ModemManager`: mobile broadband modem management daemon
- `a2dismod`: enable or disable an apache2 module
- `adb`:  Android Debug Bridge
 A versatile command line tool that lets you communicate with an emulator
 instance or connected Android-powered device.
 .
 This package recommends "android-sdk-platform-tools-common" which contains
 the udev rules for Android devices. Without this package, adb and fastboot need
 to be running with root permission.


- `add-apt-key`: Command line tool to add GPG keys to the APT keyring
- `zenity`:  Display graphical dialog boxes from shell scripts
 Zenity allows you to display GTK+ dialogs from shell scripts; it is a
 rewrite of the `gdialog' command from GNOME 1.
 .
 Zenity includes a gdialog wrapper script so that it can be used with
 legacy scripts.


- `utmpdump`: dump UTMP and WTMP files in raw format
- `Xorg`: X11R7 X server
- `xrandr`: primitive command line interface to RandR extension
- `aapt`:  Android Asset Packaging Tool
 The Android Asset Packaging Tool (aapt) takes your application resource
 files, such as the AndroidManifest.xml file and the XML files for your
 Activities, and compiles them. An R.java is also produced so you can
 reference your resources from your Java code. This tool allows you to view,
 create, and update Zip-compatible archives (zip, jar, apk). It can also
 compile resources into binary assets.


- `zdump`: timezone dumper
- `VBoxService`: x86 virtualization solution
- `7z`: A file archiver with highest compression ratio
- `accessdb`: dumps the content of a man-db database in a human readable format
- `vcstime`: Show time in upper right hand corner of the console screen
- `addftinfo`: add information to troff font files for use with groff
- `usermod`: modify a user account
- `add-apt-repository`: Adds a repository into the /etc/apt/sources.list
   or /etc/apt/sources.list.d or removes an existing one
- `ab`: Apache HTTP server benchmarking tool
- `aconnect`: ALSA sequencer connection manager
- `aircrack-ng`:  wireless WEP/WPA cracking utilities
 aircrack-ng is an 802.11a/b/g WEP/WPA cracking program that can recover a
 40-bit, 104-bit, 256-bit or 512-bit WEP key once enough encrypted packets
 have been gathered. Also it can attack WPA1/2 networks with some advanced
 methods or simply by brute force.
 .
 It implements the standard FMS attack along with some optimizations,
 thus making the attack much faster compared to other WEP cracking tools.
 It can also fully use a multiprocessor system to its full power in order
 to speed up the cracking process.
 .
 aircrack-ng is a fork of aircrack, as that project has been stopped by
 the upstream maintainer.


- `addr2line`: convert addresses into file names and line numbers.
- `afmtodit`: create font files for use with groff  -Tps and  -Tpdf
- `alias`: define or display aliases
- `animate.im6`: animates an image or image sequence on any X server.
- `airdecap-ng`: decrypt a WEP/WPA crypted pcap file
- `airdecloak-ng`: Removes wep cloaked framed from a pcap file.
- `alsactl`: advanced controls for ALSA soundcard driver
- `alsaloop`: command -line PCM loopback
- `apm_available`: test whether APM subsystem is available
- `airolib-ng`: manage and create a WPA/WPA2 pre-computed hashes tables
- `amap`:  next-generation scanning tool for pentesters
 AMAP stands for Application MAPper. It is a next-generation scanning
 tool for pentesters. It attempts to identify applications even if they
 are running on a different port than normal.
 .
 It also identifies non-ascii based applications. This is achieved by
 sending trigger packets, and looking up the responses in a list of
 response strings.


- `apg`:  Automated Password Generator - Standalone version
 APG (Automated Password Generator) is the tool set for random
 password generation. It generates some random words of required type
 and prints them to standard output. This binary package contains only
 the standalone version of apg.
 Advantages:
  * Built-in ANSI X9.17 RNG (Random Number Generator)(CAST/SHA1)
  * Built-in password quality checking system (now it has support for Bloom
    filter for faster access)
  * Two Password Generation Algorithms:
     1. Pronounceable Password Generation Algorithm (according to NIST
        FIPS 181)
     2. Random Character Password Generation Algorithm with 35
        configurable modes of operation
  * Configurable password length parameters
  * Configurable amount of generated passwords
  * Ability to initialize RNG with user string
  * Support for /dev/random
  * Ability to crypt() generated passwords and print them as additional output.
  * Special parameters to use APG in script
  * Ability to log password generation requests for network version
  * Ability to control APG service access using tcpd
  * Ability to use password generation service from any type of box (Mac,
    WinXX, etc.) that connected to network
  * Ability to enforce remote users to use only allowed type of password
    generation
 The client/server version of apg has been deliberately omitted.
 .
 Please note that there are security flaws in pronounceable
 password generation schemes (see Ganesan / Davis "A New Attack on
 Random Pronounceable Password Generators", in "Proceedings of the 17th
 National Computer Security Conference (NCSC), Oct. 11-14, 1994
 (Volume 1)", http://csrc.nist.gov/publications/history/nissc/
 1994-17th-NCSC-proceedings-vol-1.pdf, pages 203-216)
 .
 Also note that the FIPS 181 standard from 1993 has been withdrawn by NIST in
 2015 with no superseding publication. This means that the document is
 considered by its publicher as obsolete and not been updated to reference
 current or revised voluntary industry standards, federal specifications, or
 federal data standards.
 .
 apg has not seen upstream attention since 2003, upstream is not answering
 e-mail, and the upstream web page (http://www.adel.nursat.kz/apg/) has been
 gone for years.  The Debian maintainer plans to discontinue apg maintenance as
 soon as an actually maintained software with a comparable feature set becomes
 available.


- `acpid`:  Advanced Configuration and Power Interface event daemon
 Modern computers support the Advanced Configuration and Power Interface (ACPI)
 to allow intelligent power management on your system and to query battery and
 configuration status.
 .
 ACPID is a completely flexible, totally extensible daemon for delivering
 ACPI events. It listens on netlink interface (or on the deprecated file
 /proc/acpi/event), and when an event occurs, executes programs to handle the
 event. The programs it executes are configured through a set of configuration
 files, which can be dropped into place by packages or by the admin.


- `appres`: list X application resource database
- `apt-clone`: manual page for apt-clone 0.2
- `apt`:  commandline package manager
 This package provides commandline tools for searching and
 managing as well as querying information about packages
 as a low-level access to all features of the libapt-pkg library.
 .
 These include:
  * apt-get for retrieval of packages and information about them
    from authenticated sources and for installation, upgrade and
    removal of packages together with their dependencies
  * apt-cache for querying available information about installed
    as well as installable packages
  * apt-cdrom to use removable media as a source for packages
  * apt-config as an interface to the configuration settings
  * apt-extracttemplates is used by debconf to prompt for configuration
    questions before installation.


- `apt-add-repository`: Adds a repository into the /etc/apt/sources.list
   or /etc/apt/sources.list.d or removes an existing one
- `apt-cache`: query the APT cache
- `apt-cdrom`: APT CD-ROM management utility
- `apt-config`: APT Configuration Query program
- `apt-extracttemplates`: Utility to extract debconf config and templates
   from Debian packages
- `apt-secure`: Archive authentication support for APT
- `apt-ftparchive`: Utility to generate index files
- `aptd`: package managing daemon proving a D-Bus interface
- `aptdcon`: command line client for aptdaemon
- `aptitude-create-state-bundle`: bundle the current aptitude state
- `aptitude-curses`: high-level interface to the package manager
- `aptitude-run-state-bundle`: unpack an aptitude state bundle and invoke aptitude on it
- `apturl`: graphical apt-protocol interpreting package installer
- `apt-get`: command-line interface
- `apt-key`: APT key management utility
- `uuidd`: UUID generation daemon
- `archdetect`: detect hardware architecture
- `arduino`: an IDE and uploader for Arduino development boards.
- `apgbfm`: APG Bloom filter management program
- `arm2hpdl`: Add HP download header/trailer to an ARM ELF binary.
- `airodump-ng-oui-update`: IEEE oui list updater for airodump-ng
- `airserv-ng`: a wireless card server
- `apache2`:  Apache HTTP Server
 The Apache HTTP Server Project's goal is to build a secure, efficient and
 extensible HTTP server as standards-compliant open source software. The
 result has long been the number one web server on the Internet.
 .
 Installing this package results in a full installation, including the
 configuration files, init scripts and support scripts.


- `aplay`: command-line sound recorder and player for ALSA sound‐
   card driver
- `uptime`: Tell how long the system has been running.
- `hostname`:  utility to set/show the host name or domain name
 This package provides commands which can be used to display the system's
 DNS name, and to display or set its hostname or NIS domain name.


- `amidi`: read from and write to ALSA RawMIDI ports
- `asn1parse.1s`: ASN.1 parsing tool
- `apt-sortpkgs`: Utility to sort package index files
- `amixer`: command-line mixer for ALSA soundcard driver
- `apache2ctl`: Apache HTTP server control interface
- `arch`: print machine hardware name (same as uname -m)
- `arping`:  sends IP and/or ARP pings (to the MAC address)
 The arping utility sends ARP and/or ICMP requests to the specified host
 and displays the replies. The host may be specified by its hostname,
 its IP address, or its MAC address.


- `anacron`:  cron-like program that doesn't go by time
 Anacron (like "anac(h)ronistic") is a periodic command scheduler.  It
 executes commands at intervals specified in days.  Unlike cron, it
 does not assume that the system is running continuously.  It can
 therefore be used to control the execution of daily, weekly, monthly,
 and yearly jobs (or anything with a period of n days), on systems that
 don't run 24 hours a day.  When installed and configured properly,
 Anacron will make sure that the commands are run at the specified
 intervals as closely as machine uptime permits.
 .
 This package is pre-configured to execute the daily jobs of the
 Debian system.  You should install this program if your system isn't
 powered on 24 hours a day to make sure the maintenance jobs of other
 Debian packages are executed each day.


- `aseqdump`: show the events received at an ALSA sequencer port
- `addpart`: tell the kernel about the existence of a partition
- `aspell-import`: import old personal dictionaries into GNU Aspell
- `arpspoof`: intercept packets on a switched LAN
- `avahi-autoipd`:  Avahi IPv4LL network address configuration daemon
 Avahi is a fully LGPL framework for Multicast DNS Service Discovery.
 It allows programs to publish and discover services and hosts
 running on a local network with no specific configuration. For
 example you can plug into a network and instantly find printers to
 print to, files to look at and people to talk to.
 .
 This tool implements IPv4LL, "Dynamic Configuration of IPv4 Link-Local
 Addresses" (IETF RFC3927), a protocol for automatic IP address
 configuration from the link-local 169.254.0.0/16 range without the
 need for a central server. It is primarily intended to be used in
 ad-hoc networks which lack a DHCP server.


- `avahi-publish`: Register an mDNS/DNS-SD service or host name or
   address mapping using the Avahi daemon
- `avahi-publish-address`: Register an mDNS/DNS-SD service or host name or
   address mapping using the Avahi daemon
- `aspell`:  GNU Aspell spell-checker
 GNU Aspell is a spell-checker which can be used either as a standalone
 application or embedded in other programs.  Its main feature is that it
 does a much better job of suggesting possible spellings than just about
 any other spell-checker available for the English language, including
 Ispell and Microsoft Word.  It also has many other technical
 enhancements over Ispell such as using shared memory for dictionaries
 and intelligently handling personal dictionaries when more than one
 Aspell process is open at once.
 .
 Aspell is designed to be a drop-in replacement for Ispell.


- `at`:  Delayed job execution and batch processing
 At and batch read shell commands from standard input
 storing them as a job to be scheduled for execution in the
 future.
 .
 Use
  at    to run the job at a specified time
  batch to run the job when system load levels permit


- `avidemux`: a free video editor
- `apropos`: search the manual page names and descriptions
- `axi-cache`: query the Apt Xapian Index
- `arp-scan`:  arp scanning and fingerprinting tool
 arp-scan is a command-line tool that uses the ARP protocol to discover and
 fingerprint IP hosts on the local network. It is available for Linux and BSD
 under the GPL licence


- `banshee`: Media Management and Playback application  Muinshee
- `avahi-resolve-address`: Resolve  one  or more mDNS/DNS host name(s) to IP ad‐
   dress(es) (and vice versa) using the Avahi daemon
- `autopsy`:  graphical interface to SleuthKit
 The Autopsy Forensic Browser is a graphical interface to the command line
 digital forensic analysis tools in The Sleuth Kit. Together, The Sleuth Kit
 and Autopsy provide many of the same features as commercial digital forensics
 tools for the analysis of Windows and UNIX file systems (NTFS, FAT, FFS,
 EXT2FS, and EXT3FS).


- `c++filt`: Demangle C++ and Java symbols.
- `axel`:  light command line download accelerator
 Axel tries to accelerate the downloading process by using multiple
 connections for one file, similar to DownThemAll and other famous
 programs. It can also use multiple mirrors for one download.
 .
 Using Axel, you will get files faster from Internet. So, Axel can
 speed up a download up to 60% (approximately, according to some tests).
 .
 Axel supports HTTP, HTTPS, FTP and FTPS protocols.
 .
 Axel tries to be as light as possible, so it might be useful as a
 wget clone (and other console based programs) on byte-critical systems.


- `bash`:  GNU Bourne Again SHell
 Bash is an sh-compatible command language interpreter that executes
 commands read from the standard input or from a file.  Bash also
 incorporates useful features from the Korn and C shells (ksh and csh).
 .
 Bash is ultimately intended to be a conformant implementation of the
 IEEE POSIX Shell and Tools specification (IEEE Working Group 1003.2).
 .
 The Programmable Completion Code, by Ian Macdonald, is now found in
 the bash-completion package.


- `avahi-set-host-name`: Change mDNS host name
- `avahi-autoipd.action`: avahi-autoipd action script
- `vercmp`: version comparison utility
- `baobab`:  GNOME disk usage analyzer
 Disk Usage Analyzer is a graphical, menu-driven application to analyse
 disk usage in a GNOME environment. It can easily scan either the whole
 filesystem tree, or a specific user-requested directory branch (local or
 remote).
 .
 It also auto-detects in real-time any changes made to your home
 directory as far as any mounted/unmounted device. Disk Usage Analyzer
 also provides a full graphical treemap window for each selected folder.


- `b2sum`: compute and check BLAKE2 message digest
- `beep`:  advanced PC-speaker beeper
 beep does what you'd expect: it beeps. But unlike printf "\a", beep allows
 you to control pitch, duration, and repetitions. Its job is to live inside
 shell/perl scripts and allow more granularity than one has otherwise. It is
 controlled completely through command line options. It's not supposed to be
 complex, and it isn't - but it makes system monitoring (or whatever else it
 gets hacked into) much more informative.


- `bdftopcf`: convert X font from Bitmap Distribution Format to Portable Compiled Format
- `veritysetup`: manage dm-verity (block level verification) volumes
- `avahi-resolve-host-name`: Resolve  one  or more mDNS/DNS host name(s) to IP ad‐
   dress(es) (and vice versa) using the Avahi daemon
- `bashbug`: report a bug in bash
- `avahi-browse-domains`: Browse for mDNS/DNS-SD services using the Avahi daemon
- `base64`: base64 encode/decode data and print to standard output
- `bluetooth-agent`: Bluetooth pass agent
- `batch`: schedule commands to be executed in a batch queue
- `bluetooth-wizard`: GTK wizard for setting up devices with the Linux Bluetooth stack
- `bccmd`: Utility for the CSR BCCMD interface
- `bluez-simple-agent`: A PIN management and agent program for pairing to Bluetooth device.
- `bonobo-activation-server`: GNOME component tracker
- `brasero`:  CD/DVD burning application for GNOME
 Brasero is a simple application to burn, copy and erase CD and DVD
 media: audio, video or data. It features among other things:
  * On-the-fly burning
  * Multisession support
  * On-the-fly conversion of music playlists in all formats supported by
    GStreamer
 .
 This package contains the standalone app.
 .
 The following packages, if installed, will provide Brasero with added
 functionality:
  * cdrdao to burn combined data/audio CDs and for byte-to-byte copy
  * GStreamer backends to support more audio formats
  * vcdimager to create VCDs or SVCDs
  * libdvdcss2 to copy encrypted DVDs
  * tracker to search for video, audio, image and document files


- `avahi-resolve`: Resolve one or more mDNS/DNS host name(s) to IP address(es) (and vice versa) using the Avahi daemon
- `vgcfgbackup`: Backup volume group configuration(s)
- `brltty`:  Access software for a blind person using a braille display
 BRLTTY is a daemon which provides access to the console (text mode)
 for a blind person using a braille display.  It drives the braille
 display and provides complete screen review functionality.
 The following display models are supported:
  * Alva/Optelec (ABT3xx, Delphi, Satellite, Braille System 40, BC 640/680)
  * Baum
  * BrailComm
  * BrailleLite
  * BrailleNote
  * Cebra
  * EcoBraille
  * EuroBraille (AzerBraille, Clio, Esys, Iris, NoteBraille, Scriba)
  * Freedom Scientific (Focus and PacMate)
  * Handy Tech
  * HIMS (Braille Sense, SyncBraille)
  * HumanWare (Brailliant)
  * Iris
  * LogText 32
  * MDV
  * Metec (BD-40)
  * NinePoint
  * Papenmeier
  * Pegasus
  * Seika
  * Tieman (Voyager, CombiBraille, MiniBraille, MultiBraille,
            BraillePen/EasyLink)
  * Tivomatic (Albatross)
  * TSI (Navigator, PowerBraille)
  * VideoBraille
  * VisioBraille
 .
 BRLTTY also provides a client/server based infrastructure for applications
 wishing to utilize a Braille display.  The daemon process listens for incoming
 TCP/IP connections on a certain port.  A shared object library for clients is
 provided in the package libbrlapi0.8.  A static library, header files and
 documentation is provided in package libbrlapi-dev.  Bindings to other
 programming languages can be found in cl-brlapi (Lisp), libbrlapi-java (Java)
 and python3-brlapi (Python).


- `besside-ng`: crack a WEP or WPA key without user intervention and col‐
   laborate with WPA cracking statistics
- `bitmap`: bitmap editor and converter utilities for the X
   Window System
- `btcflash`: firmware flash utility for BTC DRW1008 DVD+/-RW recorder.
- `bsd-from`: print names of those who have sent mail
- `bsd-write`: send a message to another user
- `bulk_extractor`: Scans a disk image for regular expressions and other
   content.
- `bundle`: Ruby Dependency Management
- `busybox`:  Tiny utilities for small and embedded systems
 BusyBox combines tiny versions of many common UNIX utilities into a single
 small executable. It provides minimalist replacements for the most common
 utilities you would usually find on your desktop system (i.e., ls, cp, mv,
 mount, tar, etc.). The utilities in BusyBox generally have fewer options than
 their full-featured GNU cousins; however, the options that are included
 provide the expected functionality and behave very much like their GNU
 counterparts.
 .
 This package installs the BusyBox binary but does not install
 symlinks for any of the supported utilities. Some of the utilities
 can be used in the system by installing the busybox-syslogd,
 udhcpc or udhcpd packages.


- `bzcmp`: compare bzip2 compressed files
- `bzdiff`: compare bzip2 compressed files
- `bzegrep`: search possibly bzip2 compressed files for a
   regular expression
- `bzexe`: compress executable files in place
- `captoinfo`: convert a termcap description into a terminfo description
- `binwalk`:  tool library for analyzing binary blobs and executable code
 Binwalk is a tool for searching a given binary image for embedded files
 and executable code. Specifically, it is designed for identifying files
 and code embedded inside of firmware images. Binwalk uses the libmagic
 library, so it is compatible with magic signatures created for the Unix
 file utility.
 .
 Binwalk also includes a custom magic signature file which contains
 improved signatures for files that are commonly found in firmware images
 such as compressed/archived files, firmware headers, Linux kernels,
 bootloaders, filesystems, etc.
 .
 This package is an empty package, because the binary tool is already
 provided with the library, dependency of this package.


- `bzgrep`: search possibly bzip2 compressed files for a
   regular expression
- `c_rehash.1s`: Create symbolic links to files named by the hash values
- `ca.1s`: sample minimal CA application
- `CA.pl.1s`: friendlier interface for OpenSSL certificate programs
- `blockdev`: call block device ioctls from the command line
- `vgcfgrestore`: Restore volume group configuration
- `bzip2`:  high-quality block-sorting file compressor - utilities
 bzip2 is a freely available, patent free, data compressor.
 .
 bzip2 compresses files using the Burrows-Wheeler block-sorting text
 compression algorithm, and Huffman coding.  Compression is generally
 considerably better than that achieved by more conventional
 LZ77/LZ78-based compressors, and approaches the performance of the PPM
 family of statistical compressors.
 .
 The archive file format of bzip2 (.bz2) is incompatible with that of its
 predecessor, bzip (.bz).


- `calibrate_ppa`: pnm2ppa calibration tool
- `canberra-gtk-play`: play a sound event
- `badblocks`: search a device for bad blocks
- `vgchange`: Change volume group attributes
- `avahi-daemon`:  Avahi mDNS/DNS-SD daemon
 Avahi is a fully LGPL framework for Multicast DNS Service Discovery.
 It allows programs to publish and discover services and hosts
 running on a local network with no specific configuration. For
 example you can plug into a network and instantly find printers to
 print to, files to look at and people to talk to.
 .
 This package contains the Avahi Daemon which represents your machine
 on the network and allows other applications to publish and resolve
 mDNS/DNS-SD records.


- `cabextract`:  Microsoft Cabinet file unpacker
 Cabextract is a program which unpacks cabinet (.cab) files, which
 are a form of archive Microsoft uses to distribute their software
 and things like Windows Font Packs.


- `casper-snapshot`: a simple script to ease persistence usage.
- `bzfgrep`: search possibly bzip2 compressed files for a
   regular expression
- `talk`:  Chat with another user
 Talk is a visual communication program which copies lines from your terminal
 to that of another user.
 .
 In order to talk locally, you will need to install the talkd package.


- `blkid`: locate/print block device attributes
- `cd-create-profile`: Color Manager Profile Creation Tool
- `cal`: print a calendar
- `calendar`:  display upcoming dates and provide reminders
 This package contains the "calendar" program commonly found on BSD-style
 systems, which displays upcoming relevant dates on a wide variety of
 calendars.


- `bc`:  GNU bc arbitrary precision calculator language
 GNU bc is an interactive algebraic language with arbitrary precision which
 follows the POSIX 1003.2 draft standard, with several extensions including
 multi-character variable names, an `else' statement and full Boolean
 expressions.  GNU bc does not require the separate GNU dc program.


- `bluetoothd`: Bluetooth daemon
- `cancel`: cancel jobs
- `bdftruncate`: generate truncated BDF font from ISO 10646-1-encoded BDF font
- `c99-gcc`: ANSI (1999) C compiler
- `capsh`: capability shell wrapper
- `tail`: copy the last part of a file
- `vgck`: Check the consistency of volume group(s)
- `cd-fix-profile`: Color Manager Testing Tool
- `chardet`: universal character encoding detector
- `bridge`: show / manipulate bridge addresses and devices
- `catchsegv`: Catch segmentation faults in programs
- `cifscreds`: manage NTLM credentials in kernel keyring  rst2man-indent-level 
- `chkdupexe`: find duplicate executables
- `catman`: create or update the pre-formatted manual pages
- `vgconvert`: Change volume group metadata format
- `chem`: groff preprocessor for producing chemical structure diagrams
- `vgcreate`: Create a volume group
- `chattr`: change file attributes on a Linux file system
- `vgdisplay`: Display volume group information
- `chage`: change user password expiry information
- `cd`: change the working directory
- `chacl`: change the access control list of a file or directory
- `chcon`: change file security context
- `chat`: Automated conversational script with a modem
- `chirpw`: A tool for programming two-way radio equipment
- `chkrootkit`:  rootkit detector
 The chkrootkit security scanner searches for signs that the system is
 infected with a 'rootkit'. Rootkits are a form of malware that seek
 to exploit security flaws to grant unauthorised access to a
 computer or its services, generally for malicious purposes.
 .
 chkrootkit can identify signs of over 70 different rootkits (see the
 project's website for a list).
 .
 Please note that an automated tool like chkrootkit can never
 guarantee a system is uncompromised. Nor does every report always
 signify a genuine problem: human judgement and further investigation
 will always be needed to assure the security of your system.


- `chfn`: change your finger information
- `cinnamon`:  Innovative and comfortable desktop
 Cinnamon is a desktop environment which provides advanced innovative
 features and a traditional user experience.
 .
 The desktop layout is similar to GNOME 2.  The underlying technology is
 forked from gnome-shell.  The emphasis is put on making users feel at home
 and providing them with an easy to use and comfortable desktop experience.


- `cinnamon-extension-tool`: extension management program
- `cinnamon-launcher`: Start or restart a cinnamon session
- `cinnamon-menu-editor`: Editor for the panel menu
- `cinnamon-screensaver`:  Cinnamon screen saver and locker
 cinnamon-screensaver is a screen saver and locker that aims to have simple,
 sane and secure defaults, and be well integrated with the Cinnamon desktop.


- `cinnamon-screensaver-command`: controls Cinnamon screensaver
- `cinnamon-session`:  Cinnamon Session Manager - Minimal runtime
 The Cinnamon Session Manager is in charge of starting the core components
 of the Cinnamon desktop, and applications that should be launched at
 login time. It also features a way to save and restore currently
 running applications.
 .
 This package contains the binaries for the Cinnamon Session Manager, but
 no startup scripts. It is meant for those willing to start
 cinnamon-session by hand with the components of their choice, and for
 applications such as MDM that use cinnamon-session internally.


- `cinnamon-session-properties`: Configure applications to start on login
- `cinnamon-session-quit`: End the current GNOME session
- `cinnamon-settings`: Configuration panel for cinnamon
- `cinnamon-settings-daemon`:  daemon handling the Cinnamon session settings
 This package contains the daemon which is responsible for setting the
 various parameters of a Cinnamon session and the applications that run
 under it. It handles the following kinds of settings:
 .
  * Keyboard: layout, accessibility options, shortcuts, media keys
  * Clipboard management
  * Theming: background, icons, GTK+ applications
  * Cleanup of unused files
  * Startup of other daemons: screensaver
  * Typing break
 .
 It also sets various application settings through X resources and
 freedesktop.org XSETTINGS.


- `ciphers.1s`: SSL cipher display and cipher list tool.
- `chromium`:  web browser
 Web browser that aims to build a safer, faster, and more stable internet
 browsing experience.
 .
 This package contains the web browser component.


- `zsoelim`: satisfy .so requests in roff input
- `chrt`: manipulate the real-time attributes of a process
- `chgrp`: change the file group ownership
- `ckbcomp`: compile a XKB keyboard description to a keymap suitable for
   loadkeys or kbdcontrol
- `cli-wrapper`: No manpage for this program.
- `vgexport`: Unregister volume group(s) from the system
- `vgextend`: Add physical volumes to a volume group
- `vgimport`: Register exported volume group with system
- `lolcat`:  colorful `cat`
 lolcat concatenates files like the UNIX `cat` program, but colors it for the
 lulz in a rainbow animation. Terminals with 256 colors and animations are
 supported.


- `chcpu`: configure CPUs
- `cms.1s`: CMS utility
- `clang`:  C, C++ and Objective-C compiler (LLVM based), clang binary
 Clang project is a C, C++, Objective C and Objective C++ front-end
 for the LLVM compiler. Its goal is to offer a replacement to the GNU Compiler
 Collection (GCC).
 .
 Clang implements all of the ISO C++ 1998, 11, 14 and 17 standards and also
 provides most of the support of C++20.
 .
 This is a dependency package providing the default clang compiler.


- `ciptool`: Bluetooth Common ISDN Access Profile (CIP)
- `clear_console`: clear the console
- `colord.conf`: Color Manager Configuration File
- `chpasswd`: update passwords in batch mode
- `cksum`: write file checksums and sizes
- `clear`: clear the terminal screen
- `combinediff`: create a cumulative unified patch from two incremental patches
- `codepage`: extract a codepage from an MSDOS codepage file
- `julia`: draws spinning, animating julia-set fractals
- `compare.im6`: mathematically and visually annotate the difference between an image and its reconstruction.
- `composite.im6`: overlaps one image over another.
- `isaset`: set ISA registers
- `conjure.im6`: interprets and executes scripts written in the Magick Scripting Language (MSL).
- `conky`: A system monitor for X originally based on the torsmo code, but more kickass. It just keeps on given&rsquo;er. Yeah.
- `usb_modeswitch`: control the mode of 'multi-state' USB devices
- `cmp`: compare two files
- `convert.im6`: convert between image formats as well as resize an image, blur, crop, despeckle, dither, draw on, flip, join, re-sample, and much more.
- `cp`: copy files
- `cowsay`:  configurable talking cow
 Cowsay (or cowthink) will turn text into happy ASCII cows, with
 speech (or thought) balloons. If you don't like cows, ASCII art is
 available to replace it with some other creatures (Tux, the BSD
 daemon, dragons, and a plethora of animals, from a turkey to
 an elephant in a snake).


- `cpan`: easily interact with CPAN from the command line
- `ivstools`: extract  IVs from a pcap file or merges several .ivs files
   into one
- `cpan2dist`: The CPANPLUS distribution creator
- `cpanp`: The CPANPLUS launcher
- `chmod`: change the file modes
- `col`: filter reverse line feeds from input
- `cpp-4.8`: The C Preprocessor
- `zsh`:  shell with lots of features
 Zsh is a UNIX command interpreter (shell) usable as an
 interactive login shell and as a shell script command
 processor. Of the standard shells, zsh most closely resembles
 ksh but includes many enhancements. Zsh has command-line editing,
 built-in spelling correction, programmable command completion,
 shell functions (with autoloading), a history mechanism, and a
 host of other features.


- `cpufreq-aperf`: Calculates the average frequency over a time period
- `cpufreq-info`: Utility to retrieve cpufreq kernel information
- `cpufreq-set`: A small tool which allows to modify cpufreq settings.
- `chsh`: change your login shell
- `chgpasswd`: update group passwords in batch mode
- `crc32`: compute CRC-32 checksums for the given files
- `cpgr`: copy with locking the given file to the password or group
   file
- `cppw`: copy with locking the given file to the password or group
   file
- `upowerd`: UPower Daemon
- `crl.1s`: CRL utility
- `crl2pkcs7.1s`: Create a PKCS#7 structure from a CRL and certificates.
- `colormgr`: Color Manager Testing Tool
- `iptables-xml`: Convert iptables-save format to XML
- `cracklib-format`: cracklib dictio‐
   nary utilities
- `convert`: convert between image formats as well as resize an image, blur, crop, despeckle, dither, draw on, flip, join, re-sample, and much more.
- `create-cracklib-dict`: Check passwords using libcrack2
- `cron`:  process scheduling daemon
 The cron daemon is a background process that runs particular programs at
 particular times (for example, every minute, day, week, or month), as
 specified in a crontab. By default, users may also create crontabs of
 their own so that processes are run on their behalf.
 .
 Output from the commands is usually mailed to the system administrator
 (or to the user in question); you should probably install a mail system
 as well so that you can receive these messages.
 .
 This cron package does not provide any system maintenance tasks. Basic
 periodic maintenance tasks are provided by other packages, such
 as checksecurity.


- `colrm`: remove columns from a file
- `cracklib-check`: Check passwords using libcrack2
- `desktop-file-validate`: Validate desktop entry files
- `crda`: send to the kernel a wireless regulatory domain for a given ISO / IEC 3166 alpha2
- `cups-deviced`: cupsd helper programs
- `cups-driverd`: cupsd helper programs
- `cupsaddsmb`: export printers to samba for windows clients
- `cups-lpd`: receive print jobs and report printer status to lpd clients (deprecated)
- `config_data`: Query or change configuration of Perl modules
- `cryptdisks_stop`: wrapper around cryptsetup that parses /etc/crypttab.
- `cifs.idmap`: Userspace helper for mapping ids for Common Internet File System (CIFS)
- `cups-browsed`:  OpenPrinting CUPS Filters - cups-browsed
 This package provides cups-browsed, a daemon which browses the Bonjour
 broadcasts of shared remote CUPS printers and makes the printers
 available locally, replacing the CUPS broadcasting/browsing which was
 dropped in CUPS 1.6.x. This way the old behavior of having the remote
 printers available automatically is now re-implemented with Bonjour.
 .
 cups-browsed is also useful with a CUPS >= 1.6 client to allow the
 latter to browse the printer list of CUPS < 1.6 servers (by using the
 old 'cups' protocol in BrowseRemoteProtocols).
 .
 cups-browsed is also useful with a CUPS >= 1.6 server to allow CUPS <
 1.6 clients to browse its printer list (by using the old 'cups'
 protocol in BrowseLocalProtocols).


- `bluetooth-sendto`: GTK application for transferring files over Bluetooth
- `cupsctl`: configure cupsd.conf options
- `bg`: run jobs in the background
- `cryptdisks_start`: wrapper around cryptsetup that parses /etc/crypttab.
- `crunch`:  tool for creating wordlist
 Crunch is a wordlist generator where you can specify a standard
 character set or any set of characters to be used in generating
 the wordlists. The wordlists are created through combination and
 permutation of a set of characters. You can determine the amount
 of characters and list size.
 .
 This program supports numbers and symbols, upper and lower case
 characters separately and Unicode.


- `cupsenable`: stop/start printers and classes
- `cifs.upcall`: Userspace upcall helper for Common Internet File System (CIFS)
- `cytune`: tune driver parameters for Cyclades-Z multiport serial card
- `cpio`:  GNU cpio -- a program to manage archives of files
 GNU cpio is a tool for creating and extracting archives, or copying
 files from one place to another.  It handles a number of cpio formats
 as well as reading and writing tar files.


- `cupstestdsc`: test conformance of postscript files (deprecated)
- `cutycapt`:  utility to capture WebKit's rendering of a web page
 CutyCapt is a small cross-platform command-line utility
 to capture WebKit's rendering of a web page
 into a variety of vector and bitmap formats,
 including SVG, PDF, PS, PNG, JPEG, TIFF, GIF, and BMP.


- `cups-genppdupdate`: update CUPS+Gutenprint PPD files
- `csplit`: split files based on context
- `cupstestppd`: test conformance of ppd files
- `dash`:  POSIX-compliant shell
 The Debian Almquist Shell (dash) is a POSIX-compliant shell derived
 from ash.
 .
 Since it executes scripts faster than bash, and has fewer library
 dependencies (making it more robust against software or hardware
 failures), it is used as the default system shell on Debian systems.


- `curl`:  command line tool for transferring data with URL syntax
 curl is a command line tool for transferring data with URL syntax, supporting
 DICT, FILE, FTP, FTPS, GOPHER, HTTP, HTTPS, IMAP, IMAPS, LDAP, LDAPS, POP3,
 POP3S, RTMP, RTSP, SCP, SFTP, SMTP, SMTPS, TELNET and TFTP.
 .
 curl supports SSL certificates, HTTP POST, HTTP PUT, FTP uploading, HTTP form
 based upload, proxies, cookies, user+password authentication (Basic, Digest,
 NTLM, Negotiate, kerberos...), file transfer resume, proxy tunneling and a
 busload of other useful tricks.


- `cut`: cut out selected fields of each line of a file
- `date`: write the date and time
- `dbus-uuidgen`: Utility to generate UUIDs
- `cvt`: calculate VESA CVT mode lines
- `ddate`: convert Gregorian dates to Discordian dates
- `dbus-daemon`:  simple interprocess messaging system (reference message bus)
 D-Bus is a message bus, used for sending messages between applications.
 Conceptually, it fits somewhere in between raw sockets and CORBA in
 terms of complexity.
 .
 This package contains dbus-daemon, the reference implementation of a
 D-Bus message bus, and dbus-run-session, a utility to start a temporary
 session dbus-daemon in a constrained environment or for automated tests.
 .
 To provide a complete D-Bus session bus, install one of the packages
 that implement the dbus-session-bus virtual package, such as
 dbus-user-session. The recommended implementation is indicated by
 the default-dbus-session-bus virtual package.


- `deb-systemd-helper.`: subset of systemctl for machines not running systemd
- `deb-systemd-invoke.`: wrapper around systemctl, respecting policy-rc.d
- `dbus-cleanup-sockets`: clean up leftover sockets in a directory
- `dbus-monitor`: debug probe to print message bus messages
- `dbus-send`: Send a message to a message bus
- `dc`:  GNU dc arbitrary precision reverse-polish calculator
 GNU dc is a reverse-polish desk calculator which supports unlimited
 precision arithmetic.  It also allows you to define and call macros.
 .
 A reverse-polish calculator stores numbers on a stack. Entering a number
 pushes it on the stack.  Arithmetic operations pop arguments off the
 stack and push the results.


- `debconf`:  Debian configuration management system
 Debconf is a configuration management system for debian packages. Packages
 use Debconf to ask questions when they are installed.


- `debconf-apt-progress`: install packages using debconf to display a
   progress bar
- `debconf-communicate`: communicate with debconf
- `cupsaccept`: accept/reject jobs sent to a destination
- `dbwrap_tool`: low level TDB/CTDB manipulation tool using the dbwrap
   interface
- `dehtmldiff`: get usable diff from an HTML page
- `vgimportclone`: Import a VG from cloned PVs
- `debconf-copydb`: copy a debconf database
- `cryptsetup-reencrypt`: tool for offline LUKS device re-encryption
- `dbus-launch`: Utility to start a message bus from a shell script
- `debconf-escape`: helper when working with debconf's escape capability
- `cups-calibrate`: ESP CUPS Printer Calibration Tool
- `debconf-set-selections`: insert new values into the debconf database
- `dfutool`: Device Firmware Upgrade utility
- `dgst.1s`: message digests
- `dconf-service`:  simple configuration storage system - D-Bus service
 DConf is a low-level key/value database designed for storing desktop
 environment settings.
 .
 This package contains the DConf service, which applications talk to
 using D-Bus in order to obtain their settings. It is mostly used by the
 GSettings backend.


- `debconf-show`: query the debconf database
- `desktop-file-install`: Installation and edition of
   desktop files
- `dd`: convert and copy a file
- `dh_pycentral`: use the python-central framework to handle Python modules and extensions
- `acm`:  Multi-player classic aerial combat simulation
 A multiplayer aerial combat simulation. Players engage in air to air
 combat against one another using heat seeking missiles and cannons.
 .
 Main features include:
  * Simulation with 6 degrees of freedom.
  * Structural limit to the vertical positive/negative load.
  * Classic instruments, navigation and head-up display (HUD).
  * Several aircraft models implemented, both civil and military.
  * Two scenes provided, with many runways and radio stations.
 .
 acm runs under the X window system.  This version of acm is
 implemented as a distributed simulation.  It communicates information
 via the IEEE Distributed Interactive Simulation protocol.
 .
 The original version of acm was written by Riley Rainey.  This is
 Umberto Salsi's updated version.


- `dh_pysupport`: use the python-support framework to handle Python modules
- `adventure`: an exploration game
- `arithmetic`: quiz on simple arithmetic
- `df`: report free disk space
- `cupsd`: cups scheduler
- `dhparam.1s`: DH parameter manipulation and generation
- `dialog`:  Displays user-friendly dialog boxes from shell scripts
 This application provides a method of displaying several different types
 of dialog boxes from shell scripts.  This allows a developer of a script
 to interact with the user in a much friendlier manner.
 .
 The following types of boxes are at your disposal:
  yes/no           Typical query style box with "Yes" and "No" answer buttons
  menu             A scrolling list of menu choices with single entry selection
  input            Query style box with text entry field
  message          Similar to the yes/no box, but with only an "Ok" button
  text             A scrollable text box that works like a simple file viewer
  info             A message display that allows asynchronous script execution
  checklist        Similar to the menu box, but allowing multiple selections
  radiolist        Checklist style box allowing single selections
  gauge            Typical "progress report" style box
  tail             Allows viewing the end of files (tail) that auto updates
  background tail  Similar to tail but runs in the background.
  editbox          Allows editing an existing file


- `dh_bash-completion`: install bash completions for package
- `dh_dkms`: correctly handle DKMS usage by a kernel module package
- `diffstat`:  produces graph of changes introduced by a diff file
 This program is a simple filter that reads the output of the 'diff' program,
 and produces a histogram of the total number of lines that were changed.
 It is useful for scanning a patch file to see which files were changed.


- `deluser`: remove a user or group from the system
- `debugfs`: ext2/ext3/ext4 file system debugger
- `delpart`: tell the kernel to forget about a partition
- `dh_installxmlcatalogs`: install and register XML catalog files
- `dh_numpy`: adds Numpy depends to python:Depends substvar
- `display.im6`: displays an image or image sequence on any X server.
- `cupsfilter`: convert a file to another format using cups filters (deprecated)
- `dlltool`: Create files needed to build and use DLLs.
- `dot`: execute commands in the current environment
- `diff3`: compare three files line by line
- `debugreiserfs`: The debugging tool for the ReiserFS filesystem.
- `dircolors`: color setup for ls
- `deallocvt`: deallocate unused virtual consoles
- `diff`: compare two files
- `dnstop`:  console tool to analyze DNS traffic
 dnstop is a console tool to analyze and display various tables of DNS traffic.
 Currently dnstop displays tables of (among others):
  * Source IP addresses
  * Destination IP addresses
  * Query types
  * Top level domains
  * Second level domains


- `dmitry`:  Deepmagic Information Gathering Tool
 DMitry is a UNIX/(GNU)Linux command line application written in C.
 DMitry can find possible subdomains, email addresses, uptime information,
 perform tcp port scan, whois lookups, and more.


- `dnsrecon`:  Powerful DNS enumeration script
 DNSRecon is a Python script that provides the ability to perform:
 .
  * Check all NS Records for Zone Transfers.
  * Enumerate General DNS Records for a given Domain
    (MX, SOA, NS, A, AAAA, SPF and TXT).
  * Perform common SRV Record Enumeration.
  * Top Level Domain (TLD) Expansion.
  * Check for Wildcard Resolution.
  * Brute Force subdomain and host A and AAAA records
    given a domain and a wordlist.
  * Perform a PTR Record lookup for a given IP Range or CIDR.
  * Check a DNS Server Cached records for A, AAAA and CNAME
  * Records provided a list of host records in a text file to check.
  * Enumerate Hosts and Subdomains using Google


- `dnstracer`:  trace DNS queries to the source
 dnstracer determines where a given Domain Name Server (DNS) gets its
 information from for a given hostname, and follows the chain of DNS
 servers back to the authoritative answer.


- `dos2unix`:  convert text file line endings between CRLF and LF
 This package contains utilities dos2unix, unix2dos, mac2unix,
 unix2mac to convert the line endings of text files between UNIX (LF),
 DOS (CRLF) and Mac (CR) formats.
 .
 Text files under Windows and DOS typically have two ASCII characters
 at the end of each line: CR (carriage return) followed by LF (line
 feed). Older Macs used just CR, while UNIX uses just LF. While most
 modern editors can read all these formats, there may still be a need
 to convert files between them.
 .
 This is the classic utility developed in 1989.


- `dirname`: return the directory portion of a pathname
- `dotlockfile`: Utility to manage lockfiles
- `depmod`: Generate modules .dep and map files .
- `dpkg`:  Debian package management system
 This package provides the low-level infrastructure for handling the
 installation and removal of Debian software packages.
 .
 For Debian package development tools, install dpkg-dev.


- `dhclient-script`: DHCP client network configuration script
- `dpkg-repack`:  Debian package archiving tool
 dpkg-repack creates a .deb file out of a package that has already been
 installed. If any changes have been made to the package while it was
 unpacked (i.e. files in /etc were modified), the new package will inherit
 the changes.
 .
 This utility can make it easy to copy packages from one computer to another,
 or to recreate packages that are installed on your system, but no longer
 available elsewhere, or to store the current state of a package before you
 upgrade it.


- `dpkg-deb`: Debian package archive (.deb) manipulation tool
- `dpkg-divert`: override a package's version of a file
- `dpkg-maintscript-helper`: works  around  known  dpkg  limitations  in
   maintainer scripts
- `dsa.1s`: DSA key processing
- `dsaparam.1s`: DSA parameter manipulation and generation
- `dpkg-split`: Debian package archive split/join tool
- `dhclient`: Dynamic Host Configuration Protocol Client
- `dpkg-statoverride`: override ownership and mode of files
- `vgmknodes`: Create the special files for volume group devices in /dev
- `duplicity`:  encrypted bandwidth-efficient backup
 Duplicity backs directories by producing encrypted tar-format volumes
 and uploading them to a remote or local file server. Because duplicity
 uses librsync, the incremental archives are space efficient and only
 record the parts of files that have changed since the last backup.
 Because duplicity uses GnuPG to encrypt and/or sign these archives, they
 will be safe from spying and/or modification by the server.


- `dvd+rw-booktype`: format DVD+-RW/-RAM disk with a logical format
- `dvd+rw-format`: format DVD+-RW/-RAM disk
- `dvd+rw-mediainfo`: display information about dvd drive and disk
- `dvd-ram-control`: checks features of DVD-RAM discs
- `dkms`:  Dynamic Kernel Module System (DKMS)
 DKMS is a framework designed to allow individual kernel modules to be upgraded
 without changing the whole kernel. It is also very easy to rebuild modules as
 you upgrade kernels.


- `dpkg-trigger`: a package trigger utility
- `dmidecode`:  SMBIOS/DMI table decoder
 Dmidecode reports information about the system's hardware as described in the
 system BIOS according to the SMBIOS/DMI standard.
 .
 This information typically includes system manufacturer, model name, serial
 number, BIOS version, asset tag as well as a lot of other details of varying
 level of interest and reliability depending on the manufacturer. This will
 often include usage status for the CPU sockets, expansion slots (e.g. AGP, PCI,
 ISA) and memory module slots, and the list of I/O ports (e.g. serial, parallel,
 USB).
 .
 Beware that DMI data have proven to be too unreliable to be blindly trusted.
 Dmidecode does not scan the hardware, it only reports what the BIOS told it to.


- `dmevent_tool`: A utility used to load a DSO into dmeventd and (un)reg‐
   ister devices with it for monitoring
- `driftnet`:  picks out and displays images from network traffic
 Inspired by EtherPEG, Driftnet is a program which listens to network
 traffic and picks out images from TCP streams it observes. It is
 interesting to run it on a host which sees a lot of web traffic.
 .
 (Obviously, this is an invasion of privacy of a fairly blatant sort.
 Also, if you are possessed of Victorian sensibilities, and share an
 unswitched network with others who are not, you should probably not
 use it.)


- `dmesg`: print or control the kernel ring buffer
- `dpkg-reconfigure`: reconfigure an already installed package
- `dumpkeys`: dump keyboard translation tables
- `ec.1s`: EC key processing
- `echo`: write arguments to standard output
- `ecparam.1s`: EC parameter manipulation and generation
- `dumpe2fs`: dump ext2/ext3/ext4 filesystem information
- `fsadm`: utility to resize or check filesystem on a device
- `ecryptfs-add-passphrase`: add an eCryptfs mount passphrase to the kernel keyring.
- `e2label`: Change the label on an ext2/ext3/ext4 filesystem
- `eject`:  ejects CDs and operates CD-Changers under Linux
 This program will eject CD-ROMs (assuming your drive supports the CDROMEJECT
 ioctl). It also allows setting the autoeject feature.
 .
 On supported ATAPI/IDE multi-disc CD-ROM changers, it allows changing
 the active disc.
 .
 You can also use eject to properly disconnect external mass-storage
 devices like digital cameras or portable music players.


- `elfedit`: Update ELF header and program property of ELF files.
- `ecryptfs-find`: use inode numbers to match encrypted/decrypted filenames
- `e4defrag`: online defragmenter for ext4 filesystem
- `ebtables`:  Ethernet bridge frame table administration
 Ebtables is used to set up, maintain, and inspect the tables of
 Ethernet frame rules in the Linux kernel. It is analogous to iptables,
 but operates at the MAC layer rather than the IP layer.


- `ecryptfs-generate-tpm-key`: generate an eCryptfs key for TPM hardware.
- `ecryptfs-recover-private`: find and mount any encrypted private direc‐
   tories
- `ecryptfs-insert-wrapped-passphrase-into-keyring`: unwrap a wrapped passphrase from file and insert into the kernel keyring.
- `ecryptfs-mount-private`: interactive eCryptfs private mount wrapper script.
- `ecryptfs-rewrap-passphrase`: unwrap an eCryptfs wrapped passphrase, rewrap it with a new passphrase, and write it back to file.
- `ecryptfs-rewrite-file`: force a file to be rewritten (reencrypted) in the lower filesystem
- `ecryptfs-setup-private`: setup an eCryptfs private directory.
- `ecryptfs-setup-swap`: ensure that any swap space is encrypted
- `ecryptfs-verify`: validate an eCryptfs encrypted home or encrypted private configuration
- `editdiff`: fix offsets and counts of a hand-edited diff
- `dpkg-preconfigure`: let packages ask questions prior to their
   installation
- `ecryptfs-stat`: Present statistics on encrypted eCryptfs file attributes
- `dwp`: The DWARF packaging utility
- `ecryptfs-umount-private`: eCryptfs private unmount wrapper script.
- `elinks`:  advanced text-mode WWW browser
 ELinks is a feature-rich program for browsing the web in text mode.  It is
 like enhanced Lynx and Links.  The most noteworthy features of ELinks are:
 .
  * Lots of protocols (local files, finger, HTTP(S), FTP, IPv4/6 etc.)
  * Internationalized domain names
  * Persistent cookies, HTTP authentication and proxy authentication
  * Tabbed browsing, good looking menus and dialogs, and key-binding manager
  * History browsing and typeahead searches
  * Forms history and completion, and history in commonly used input dialogs
  * CSS support and support for browser scripting (Perl, Lua, Guile etc.)
  * Tables and frames rendering, and configurable color support
  * Compressed and background (non-blocking) downloads, and download resuming
 .
 This package is based on elinks fork, since original elinks seems to be no
 longer maintained.


- `emacs`:  GNU Emacs editor (metapackage)
 GNU Emacs is the extensible self-documenting text editor.
 This is a metapackage that will always depend on the latest
 recommended Emacs variant (currently emacs-gtk).


- `enc.1s`: symmetric cipher routines
- `edit`: text editor
- `ecryptfs-unwrap-passphrase`: unwrap an eCryptfs mount passphrase from file.
- `compose`: execute programs via en‐
   tries in the mailcap file
- `ecryptfs-wrap-passphrase`: wrap an eCryptfs mount passphrase.
- `corelist`: a commandline frontend to Module::CoreList
- `editres`: a dynamic resource editor for X Toolkit applications
- `vgs`: Display information about volume groups
- `vgmerge`: Merge volume groups
- `virtualbox`:  x86 virtualization solution - base binaries
 VirtualBox is a free x86 virtualization solution allowing a wide range
 of x86 operating systems such as Windows, DOS, BSD or Linux to run on a
 Linux system.
 .
 This package provides the binaries for VirtualBox. Either the virtualbox-dkms
 or the virtualbox-source package is also required in order to compile the
 kernel modules needed for virtualbox. A graphical user interface for
 VirtualBox is provided by the package virtualbox-qt.


- `ecryptfs-manager`: eCryptfs key manager.
- `enchant-lsmod`: Show information about available spell-checking modules
   and dictionaries.
- `errstr.1s`: lookup error codes
- `esc-m`: ease viewing output of driver data
- `espdiff`: apply the appropriate transformation to a set of patches
- `fsck`: check and repair a Linux filesystem
- `eutp`: EuroBraille file transferring
- `vgreduce`: Remove physical volume(s) from a volume group
- `e2image`: Save critical ext2/ext3/ext4 filesystem metadata to a file
- `enchant`: a spellchecker
- `eqn2graph`: convert an EQN equation into a cropped image
- `vlc`:  multimedia player and streamer
 VLC is the VideoLAN project's media player. It plays MPEG, MPEG-2, MPEG-4,
 DivX, MOV, WMV, QuickTime, WebM, FLAC, MP3, Ogg/Vorbis files, DVDs, VCDs,
 podcasts, and multimedia streams from various network sources.
 .
 VLC can also be used as a streaming server that duplicates the stream it
 reads and multicasts them through the network to other clients, or serves
 them through HTTP.
 .
 VLC has support for on-the-fly transcoding of audio and video formats, either
 for broadcasting purposes or for movie format transformations. Support for
 most output methods is provided by this package, but features can be added by
 installing additional plugins:
  * vlc-plugin-access-extra
  * vlc-plugin-fluidsynth
  * vlc-plugin-jack
  * vlc-plugin-notify
  * vlc-plugin-samba
  * vlc-plugin-skins2
  * vlc-plugin-svg
  * vlc-plugin-video-splitter
  * vlc-plugin-visualization


- `eval`: construct command by concatenating arguments
- `vlc-wrapper`: a wrapper to drop privileges with VLC
- `espeak`:  Multi-lingual software speech synthesizer
 eSpeak is a software speech synthesizer for English, and some other
 languages.
 .
 eSpeak produces good quality English speech. It uses a different synthesis
 method from other open source text to speech (TTS) engines, and sounds quite
 different. It's perhaps not as natural or "smooth", but some find the
 articulation clearer and easier to listen to for long periods.
 .
 It can run as a command line program to speak text from a file or from stdin.
 .
   * Includes different Voices, whose characteristics can be altered.
   * Can produce speech output as a WAV file.
   * Can translate text to phoneme codes, so it could be adapted as a front end
     for another speech synthesis engine.
   * Potential for other languages. More than 40 languages are included.
   * Compact size. The program and its data total about 350 kbytes.
   * Written in C++.


- `ettercap`: multipurpose  sniffer/content filter for man in the middle
   attacks
- `expand`: convert tabs to spaces
- `envsubst`: substitutes environment variables in shell format strings
- `f2py`: Fortran to Python interface generator
- `acpi_listen`: ACPI event listener
- `eqn`: format equations for troff or MathML
- `evince-thumbnailer`: create png thumbnails from PostScript and PDF doc‐
   uments
- `exit`: cause the shell to exit
- `env`: set the environment for command invocation
- `expiry`: check and enforce password expiration policy
- `export`: set the export attribute for variables
- `faked-sysv`: daemon that remembers fake ownership/permissions of files ma‐
   nipulated by fakeroot processes.
- `vmmouse_detect`: VMware mouse device autodetection tool
- `chown`: change the file ownership
- `easside-ng`: an auto-magic tool which allows you to communicate via an
   WEP-encrypted AP without knowing the key
- `faked-tcp`: daemon that remembers fake ownership/permissions of files ma‐
   nipulated by fakeroot processes.
- `exec`: execute commands and open, close, or copy file descriptors
- `fakeroot-sysv`: run a command in an environment faking root privileges for
   file manipulation
- `ethtool`:  display or change Ethernet device settings
 ethtool can be used to query and change settings such as speed, auto-
 negotiation and checksum offload on many network devices, especially
 Ethernet devices.


- `fakeroot-tcp`: run a command in an environment faking root privileges for
   file manipulation
- `cryptsetup`:  disk encryption support - startup scripts
 Cryptsetup provides an interface for configuring encryption on block
 devices (such as /home or swap partitions), using the Linux kernel
 device mapper target dm-crypt. It features integrated Linux Unified Key
 Setup (LUKS) support.
 .
 Cryptsetup is backwards compatible with the on-disk format of cryptoloop,
 but also supports more secure formats. This package includes support for
 automatically configuring encrypted devices at boot time via the config
 file /etc/crypttab. Additional features are cryptoroot support through
 initramfs-tools and several supported ways to read a passphrase or key.
 .
 This package provides the cryptdisks_start and _stop wrappers, as well as
 luksformat.


- `fatlabel`: set or get MS-DOS filesystem label
- `chroot`: change root directory
- `addgroup`: add a user or group to the system
- `viewres`: graphical class browser for Xt
- `vimtutor`: the Vim tutor
- `e2undo`: Replay an undo log for an ext2/ext3/ext4 filesystem
- `ecryptfs-migrate-home`: migrate a user's home directory to an encrypted home setup
- `eventlogadm`: push records into the Samba event log store
- `ffmpeg-bitstream-filters`: FFmpeg bitstream filters
- `ffmpeg-devices`: FFmpeg devices
- `ffmpeg-formats`: FFmpeg formats
- `ffmpeg-protocols`: FFmpeg protocols
- `ffmpeg-resampler`: FFmpeg Resampler
- `ffmpeg-scaler`: FFmpeg video scaling and pixel format converter
- `ffmpeg-utils`: FFmpeg utilities
- `ffmulticonverter`: GUI application which converts multiple file formats to different extensions
- `expr`: evaluate arguments as an expression
- `faillog`: display faillog records or set login failure limits
- `ffserver`: ffserver video server
- `ffplay`: FFplay media player
- `false`: return false value
- `fc-cache`: build font information cache files
- `fc-validate`: validate font files
- `fc-list`: list available fonts
- `filezilla`:  Full-featured graphical FTP/FTPS/SFTP client
 FileZilla is a full-featured FTP client with an easy-to-use GUI.
 .
 It is written in C++ and uses the wxWidgets library.
 .
 FileZilla includes the following features:
   * Supports FTP, FTP over SSL/TLS (FTPS) and SSH File Transfer Protocol (SFTP)
   * IPv6 support
   * Available in more than 40 languages
   * Supports resume and transfer of large files >4GB
   * Easy to use Site Manager and transfer queue
   * Bookmarks
   * Drag & drop support (in application)
   * Speed limits
   * Filename filters
   * Directory comparison
   * Network configuration wizard
   * Remote file editing
   * Keep-alive
   * HTTP/1.1, SOCKS5 and FTP Proxy support
   * Logging to file
   * Synchronized directory browsing
   * Remote file search
   * Tabbed interface to connect to multiple servers


- `filterdiff`: extract or exclude diffs from a diff file
- `fc`: process the command history list
- `find2perl`: translate find command lines to Perl code
- `fcrackzip`:  password cracker for zip archives
 fcrackzip is a fast password cracker partly written in assembler. It is
 able to crack password protected zip files with brute force or dictionary
 based attacks, optionally testing with unzip its results. It can also crack
 cpmask'ed images.
 .
 This package is useful for pentesters, ethical hackers and forensics
 experts.


- `ffmpeg`:  Tools for transcoding, streaming and playing of multimedia files
 FFmpeg is the leading multimedia framework, able to decode, encode, transcode,
 mux, demux, stream, filter and play pretty much anything that humans and
 machines have created. It supports the most obscure ancient formats up to the
 cutting edge.
 .
 This package contains:
  * ffmpeg: a command line tool to convert multimedia files between formats
  * ffplay: a simple media player based on SDL and the FFmpeg libraries
  * ffprobe: a simple multimedia stream analyzer
  * qt-faststart: a utility to rearrange Quicktime files


- `fc-pattern`: parse and show pattern
- `firefox`: a free and open source web browser from Mozilla
- `ctrlaltdel`: set the function of the Ctrl-Alt-Del combination
- `fixcvsdiff`: fix problematic diff files
- `flipdiff`: exchange the order of two incremental patches
- `fdformat`: low-level format a floppy disk
- `VBoxClient`: x86 virtualization solution
- `fdisk`:  collection of partitioning utilities
 This package contains the classic fdisk, sfdisk and cfdisk partitioning
 utilities from the util-linux suite.
 .
 The utilities included in this package allow you to partition
 your hard disk. The utilities supports both modern and legacy
 partition tables (eg. GPT, MBR, etc).
 .
 The fdisk utility is the classical text-mode utility.
 The cfdisk utility gives a more userfriendly curses based interface.
 The sfdisk utility is mostly for automation and scripting uses.


- `file-roller`:  archive manager for GNOME
 File-roller is an archive manager for the GNOME environment. It allows you to:
 .
  * Create and modify archives.
  * View the content of an archive.
  * View a file contained in an archive.
  * Extract files from the archive.
 .
 File-roller supports the following formats:
  * Tar (.tar) archives, including those compressed with
    gzip (.tar.gz, .tgz), bzip (.tar.bz, .tbz), bzip2 (.tar.bz2, .tbz2),
    compress (.tar.Z, .taz), lzip (.tar.lz, .tlz), lzop (.tar.lzo, .tzo),
    lzma (.tar.lzma) and xz (.tar.xz)
  * Zip archives (.zip)
  * Jar archives (.jar, .ear, .war)
  * 7z archives (.7z)
  * iso9660 CD images (.iso)
  * Lha archives (.lzh)
  * Archiver archives (.ar)
  * Comic book archives (.cbz)
  * Single files compressed with gzip (.gz), bzip (.bz), bzip2 (.bz2),
    compress (.Z), lzip (.lz), lzop (.lzo), lzma (.lzma) and xz (.xz)
 .
 File-roller can extract following formats:
  * Cabinet archives (.cab)
  * Debian binary packages (.deb)
  * Xar archives (.xar)
 .
 File-roller doesn't perform archive operations by itself, but relies on
 standard tools for this.


- `font2c`: Write PostScript Type 0 or Type 1 font as C code
- `fontforge`:  font editor
 FontForge is a font editor.
 Use it to create, edit and convert fonts
 in OpenType, TrueType, UFO, CID-keyed, Multiple Master,
 and many other formats.
 .
 This package also provides these programs and utilities:
  fontimage - produce a font thumbnail image;
  fontlint  - checks the font for certain common errors;
  sfddiff   - compare two font files.


- `fontimage`: produce a font thumbnail image
- `filefrag`: report on file fragmentation
- `foo2hbpl2`: Convert Ghostscript pbmraw or bitcmyk format into a ZJS printer stream
- `foo2hbpl2-wrapper`: Convert Postscript into a ZJS printer stream
- `foo2hiperc`: Convert Ghostscript pbmraw or bitcmyk format into a HIPERC printer stream
- `foo2hiperc-wrapper`: Convert Postscript into a HIPERC printer stream
- `foo2hp`: Convert Ghostscript pbmraw or bitcmyk format into a ZJS printer stream
- `foo2hp2600-wrapper`: Convert Postscript into a ZJS printer stream
- `foo2lava`: Convert Ghostscript pbmraw or bitcmyk format into a LAVAFLOW or a OPL printer stream
- `foo2lava-wrapper`: Convert Postscript into a LAVAFLOW or OPL printer stream
- `foo2oak`: Convert Ghostscript pbmraw, pgmraw or bitcmyk format into an OAKT printer stream
- `foo2oak-wrapper`: Convert Postscript into an OAKT printer stream
- `foo2qpdl`: Convert Ghostscript pbmraw or bitcmyk format into a QPDL printer stream
- `foo2qpdl-wrapper`: Convert Postscript into a QPDL printer stream
- `foo2slx`: Convert Ghostscript pbmraw or bitcmyk format into a SLX printer stream
- `foo2slx-wrapper`: Convert Postscript into a SLX printer stream
- `foo2xqx`: Convert Ghostscript pbmraw into a XQX printer stream
- `foo2xqx-wrapper`: Convert Postscript into a XQX printer stream
- `foo2zjs`: Convert Ghostscript pbmraw or bitcmyk format into a ZJS printer stream
- `foo2zjs-icc2ps`: little cms PostScript converter.
- `foo2zjs-pstops`: Add PS code for foo2*-wrapper
- `foo2zjs-wrapper`: Convert Postscript into a ZJS printer stream
- `flex`:  fast lexical analyzer generator
 Flex is a tool for generating scanners: programs which recognized lexical
 patterns in text. It reads the given input files for a description of a
 scanner to generate. The description is in the form of pairs of regular
 expressions and C code, called rules. Flex generates as output a C source
 file, lex.yy.c, which defines a routine yylex().  This file is compiled
 and linked with the -lfl library to produce an executable. When the
 executable is run, it analyzes its input for occurrences of the regular
 expressions. Whenever it finds one, it executes the corresponding C code.


- `vstp`: VisioBraille file transferring
- `fortune`: print a random, hopefully interesting, adage
- `flac`:  Free Lossless Audio Codec - command line tools
 FLAC stands for Free Lossless Audio Codec. Grossly oversimplified, FLAC is
 similar to MP3, but lossless.  The FLAC project consists of:
 .
  * The stream format
  * libFLAC, which implements a reference encoder, stream decoder, and file
    decoder
  * flac, which is a command-line wrapper around libFLAC to encode and decode
    .flac files
  * Input plugins for various music players (Winamp, XMMS, and more in the
    works)
 .
 This package contains the command-line tools flac (used for encoding and
 decoding FLACs) and metaflac (used for manipulating FLAC metadata.)


- `fc-match`: match available fonts
- `fc-query`: query font files
- `fallocate`: manipulate file space
- `fgconsole`: print the number of the active VT.
- `foremost`:  forensic program to recover lost files
 Foremost is a forensic program to recover lost files based on
 their headers, footers, and internal data structures.
 .
 Foremost can work on image files, such as those generated by dd,
 Safeback, Encase, etc, or directly on a drive. The headers and
 footers can be specified by a configuration file or you can use
 command line switches to specify built-in file types. These built-in
 types look at the data structures of a given file format allowing
 for a more reliable and faster recovery.


- `fsck.nfs`: Dummy fsck.nfs script that always returns success.
- `fsck.fat`: check and repair MS-DOS filesystems
- `fg`: run jobs in the foreground
- `fslsfonts`: list fonts served by X font server
- `fold`: filter for folding lines
- `vncserver`: a wrapper to launch an X server for VNC.
- `fstobdf`: generate BDF font from X font server
- `findfs`: find a filesystem by label or UUID
- `fstrim-all`: call fstrim on all mounted file systems which support it
- `wireshark`:  network traffic analyzer - graphical interface
 Wireshark is a network "sniffer" - a tool that captures and analyzes
 packets off the wire. Wireshark can decode too many protocols to list
 here.


- `factor`: factor numbers
- `fix-qdf`: repair PDF files in QDF form after editing
- `findmnt`: find a filesystem
- `readprofile`: read kernel profiling information
- `w3m`:  WWW browsable pager with excellent tables/frames support
 w3m is a text-based World Wide Web browser with IPv6 support.
 It features excellent support for tables and frames. It can be used
 as a standalone file pager, too.
 .
  * You can follow links and/or view images in HTML.
  * Internet message preview mode, you can browse HTML mail.
  * You can follow links in plain text if it includes URL forms.
  * With w3m-img, you can view inline images.
 .
 This package provides Debian's w3m, forked from the original version
 <https://sourceforge.net/projects/w3m/>.


- `lpinfo`: show available devices or drivers (deprecated)
- `fzputtygen`: SFTP private key converter of FileZilla
- `fzsftp`: SFTP connection handler of FileZilla
- `gacutil`: Global Assembly Cache management utility.
- `fmt`: simple optimal text formatter
- `free`: Display amount of free and used memory in the system
- `gcc-ar-4.8`: a wrapper around ar adding the --plugin option
- `gcc-nm-4.8`: a wrapper around nm adding the --plugin option
- `gcc-ranlib-4.8`: a wrapper around ranlib adding the --plugin option
- `gconf-schemas`: register gconf schemas with the gconf database
- `ftp`:  dummy transitional package for tnftp
 This is a dummy transitional package transitioning ftp to tnftp.


- `fsck.xfs`: do nothing, successfully
- `gcov-4.8`: coverage testing tool
- `gdb`:  GNU Debugger
 GDB is a source-level debugger, capable of breaking programs at
 any specific line, displaying variable values, and determining
 where errors occurred. Currently, gdb supports C, C++, D,
 Objective-C, Fortran, Java, OpenCL C, Pascal, assembly, Modula-2,
 Go, and Ada. A must-have for any serious programmer.


- `foomatic-rip`: Universal print filter/RIP wrapper
- `gdebi`:  simple tool to view and install deb files - GNOME GUI
 gdebi lets you install local deb packages resolving and installing
 its dependencies, like apt.
 .
 The package is also scanned via lintian before the install and its
 possible to inspect the control and data members of the packages.
 .
 This package contains the graphical user interface.


- `gdebi-gtk`: Simple tool to install deb files
- `fuser`: list process IDs of all processes that have one or more files open
- `g++`:  GNU C++ compiler
 This is the GNU C++ compiler, a fairly portable optimizing compiler for C++.
 .
 This is a dependency package providing the default GNU C++ compiler.


- `gendsa.1s`: generate a DSA private key from a set of parameters
- `genpkey.1s`: generate a private key
- `genrsa.1s`: generate an RSA private key
- `dmsetup`:  Linux Kernel Device Mapper userspace library
 The Linux Kernel Device Mapper is the LVM (Linux Logical Volume Management)
 Team's implementation of a minimalistic kernel-space driver that handles
 volume management, while keeping knowledge of the underlying device layout
 in user-space.  This makes it useful for not only LVM, but software raid,
 and other drivers that create "virtual" block devices.
 .
 This package contains a utility for modifying device mappings.


- `vncviewer`: an X viewer client for VNC
- `wallpaper`: Find images which can be used as wallpapers
- `vimdiff`: edit two, three or four versions of a file with Vim and show
   differences
- `e2freefrag`: report free space fragmentation information
- `galleta`:  Internet Explorer cookie forensic analysis tool
 Galleta is a forensics tool that examines the content of cookie files
 produced by Microsoft Internet Explorer (MSIE). It parses the file and
 outputs a field separated that can be loaded in a spreadsheet.


- `gcc`:  GNU C compiler
 This is the GNU C compiler, a fairly portable optimizing compiler for C.
 .
 This is a dependency package providing the default GNU C compiler.


- `vigr`: edit the password or group file
- `wftopfa`: Convert a Wadalab base font to Postscript .PFA (or .PFB) format using ghostscript
- `volatility`: advanced memory forensics framework
- `volname`: return volume name
- `gcore`: Generate a core file for a running process
- `regdbdump`: parse and print out regulatory rules file
- `fstrim`: discard unused blocks on a mounted filesystem
- `vmstat`: Report virtual memory statistics
- `unshare`: disassociate parts of the process execution context
- `gethostip`: convert an IP address into various formats
- `w`: Show who is logged on and what they are doing.
- `wait`: await process completion
- `fsfreeze`: suspend access to a filesystem (Ext3/4, ReiserFS, JFS, XFS)
- `gem`:  Graphics Environment for Multimedia - Pure Data library
 Gem is a loadable library for Pure Data (Pd), which adds OpenGL graphics
 rendering and animation to Pd.  Pd is a graphical programming language and
 computer music system.
 .
 This package contains the core library.
 If you want to use external data (live video capture, film footage, still
 images, ...), you have to install one (or all) of the gem-plugin-* packages.


- `wall`: write a message to all users
- `wget`:  retrieves files from the web
 Wget is a network utility to retrieve files from the web
 using HTTP(S) and FTP, the two most widely used internet
 protocols. It works non-interactively, so it will work in
 the background, after having logged off. The program supports
 recursive retrieval of web-authoring pages as well as FTP
 sites -- you can use Wget to make mirrors of archives and
 home pages or to travel the web like a WWW robot.
 .
 Wget works particularly well with slow or unstable connections
 by continuing to retrieve a document until the document is fully
 downloaded. Re-getting files from where it left off works on
 servers (both HTTP and FTP) that support it. Both HTTP and FTP
 retrievals can be time stamped, so Wget can see if the remote
 file has changed since the last retrieval and automatically
 retrieve the new version if it has.
 .
 Wget supports proxy servers; this can lighten the network load,
 speed up retrieval, and provide access behind firewalls.


- `windmc`: generates Windows message resources.
- `watch`: execute a program periodically, showing output fullscreen
- `winetricks`:  simple tool to work around common problems in Wine
 Winetricks lets you install missing DLLs or tweak various Wine settings
 individually.  It also has a menu of supported games/apps for which it
 can do all the workarounds automatically.
 .
 It can be used via GUI or commandline, whichever you prefer; the
 commandline mode is particularly useful as a building block in fancier
 wine frontends and in automated regression testing.


- `vgsplit`: Move physical volumes into a new or existing volume group
- `unix_update`: Helper binary that updates the password of a given user
- `whereis`: locate the binary, source, and manual page files for a command
- `wodim`:  command line CD/DVD writing tool
 wodim allows you to create CDs or DVDs on a CD/DVD recorder.
 It supports writing data, audio, mixed, multi-session, and CD+ disc and DVD
 data and video disks on DVD capable devices, on just about every type of
 CD/DVD recorder out there.
 .
 Please install cdrkit-doc if you want most of the documentation and
 README files.


- `which`: shows the full path of (shell) commands.
- `libnetcfg`: configure libnet
- `getcifsacl`: Userspace helper to display an ACL in a security descriptor for Common Internet File System (CIFS)
- `visudo`: edit the sudoers file
- `vpnc`:  Cisco-compatible VPN client
 vpnc is a VPN client compatible with cisco3000 VPN Concentrator (also
 known as Cisco's EasyVPN equipment). vpnc runs entirely in userspace
 and does not require kernel modules except for the tun driver to
 communicate with the network layer.
 .
 It supports most of the features needed to establish connection to the
 VPN concentrator: MD5 and SHA1 hashes, 3DES and AES ciphers, PFS and
 various IKE DH group settings.


- `gamma4scanimage`: create a gamma table for scanimage
- `wc`: word, line, and byte or character count
- `whatis`: display one-line manual page descriptions
- `gftp`:  FTP client (metapackage)
 gFTP is a multithreaded FTP client, using GLib.
 .
 This is an upgrade convenience package, it's only useful for depending on.


- `ginstall-info`: update info/dir entries
- `geteltorito`: an El Torito boot image extractor
- `gipddecode`: Decode a GIPD stream into human readable form.
- `link`: call    link () function
- `gettextize`: install or upgrade gettext infrastructure
- `gio-querymodules`: GIO module cache creation
- `git-add`: Add file contents to the index
- `git-am`: Apply a series of patches from a mailbox
- `git-annotate`: Annotate file lines with commit information
- `git-apply`: Apply a patch to files and/or to the index
- `git-archive`: Create an archive of files from a named tree
- `git-bisect`: Use binary search to find the commit that introduced a bug
- `git-blame`: Show what revision and author last modified each line of a file
- `git-branch`: List, create, or delete branches
- `git-bundle`: Move objects and refs by archive
- `git-cat-file`: Provide content or type and size information for repository objects
- `git-check-attr`: Display gitattributes information
- `git-check-ignore`: Debug gitignore / exclude files
- `git-check-ref-format`: Ensures that a reference name is well formed
- `git-check-mailmap`: Show canonical names and email addresses of contacts
- `git-checkout-index`: Copy files from the index to the working tree
- `git-checkout`: Switch branches or restore working tree files
- `git-cherry-pick`: Apply the changes introduced by some existing commits
- `git-clean`: Remove untracked files from the working tree
- `git-column`: Display data in columns
- `git-clone`: Clone a repository into a new directory
- `git-commit`: Record changes to the repository
- `git-credential-cache`: Helper to temporarily store passwords in memory
- `git-count-objects`: Count unpacked number of objects and their disk consumption
- `git-config`: Get and set repository or global options
- `git-credential-cache--daemon`: Temporarily store user credentials in memory
- `git-credential-store`: Helper to store credentials on disk
- `git-credential`: Retrieve and store user credentials
- `git-diff-index`: Compare a tree to the working tree or index
- `git-daemon`: A really simple server for Git repositories
- `git-describe`: Give an object a human readable name based on an available ref
- `git-diff-files`: Compares files in the working tree and the index
- `git-diff-tree`: Compares the content and mode of blobs found via two tree objects
- `git-diff`: Show changes between commits, commit and working tree, etc
- `git-difftool`: Show changes using common diff tools
- `git-fast-import`: Backend for fast Git data importers
- `git-fast-export`: Git data exporter
- `git-fetch-pack`: Receive missing objects from another repository
- `git-fetch`: Download objects and refs from another repository
- `git-filter-branch`: Rewrite branches
- `git-fmt-merge-msg`: Produce a merge commit message
- `git-format-patch`: Prepare patches for e -mail submission
- `git-for-each-ref`: Output information on each ref
- `git-fsck-objects`: Verifies the connectivity and validity of the objects in the database
- `git-fsck`: Verifies the connectivity and validity of the objects in the database
- `git-gc`: Cleanup unnecessary files and optimize the local repository
- `git-get-tar-commit-id`: Extract commit ID from an archive created using git -archive
- `git-grep`: Print lines matching a pattern
- `git-hash-object`: Compute object ID and optionally creates a blob from a file
- `git-help`: Display help information about Git
- `git-http-backend`: Server side implementation of Git over HTTP
- `git-http-fetch`: Download from a remote Git repository via HTTP
- `git-http-push`: Push objects over HTTP/DAV to another repository
- `git-index-pack`: Build pack index file for an existing packed archive
- `git-imap-send`: Send a collection of patches from stdin to an IMAP folder
- `git-init-db`: Creates an empty Git repository
- `git-init`: Create an empty Git repository or reinitialize an existing one
- `git-instaweb`: Instantly browse your working repository in gitweb
- `git-log`: Show commit logs
- `git-ls-files`: Show information about files in the index and the working tree
- `git-ls-remote`: List references in a remote repository
- `git-ls-tree`: List the contents of a tree object
- `git-merge-one-file`: The standard helper program to use with git -merge -index
- `git-mailinfo`: Extracts patch and authorship from a single e -mail message
- `git-mailsplit`: Simple UNIX mbox splitter program
- `git-merge-base`: Find as good common ancestors as possible for a merge
- `git-merge-file`: Run a three -way file merge
- `git-merge-index`: Run a merge for files needing merging
- `git-merge`: Join two or more development histories together
- `git-merge-tree`: Show three -way merge without touching index
- `git-mergetool--lib`: Common Git merge tool shell scriptlets
- `git-mergetool`: Run merge conflict resolution tools to resolve merge conflicts
- `git-mktag`: Creates a tag object
- `git-mktree`: Build a tree -object from ls -tree formatted text
- `git-mv`: Move or rename a file, a directory, or a symlink
- `git-name-rev`: Find symbolic names for given revs
- `git-notes`: Add or inspect object notes
- `git-p4`: Import from and submit to Perforce repositories
- `git-pack-objects`: Create a packed archive of objects
- `git-pack-redundant`: Find redundant pack files
- `git-pack-refs`: Pack heads and tags for efficient repository access
- `git-patch-id`: Compute unique ID for a patch
- `git-parse-remote`: Routines to help parsing remote repository access parameters
- `git-prune-packed`: Remove extra objects that are already in pack files
- `git-prune`: Prune all unreachable objects from the object database
- `git-pull`: Fetch from and integrate with another repository or a local branch
- `git-push`: Update remote refs along with associated objects
- `git-quiltimport`: Applies a quilt patchset onto the current branch
- `getconf`: get configuration values
- `git-rebase`: Reapply commits on top of another base tip
- `git-relink`: Hardlink common objects in local repositories
- `git-remote-ext`: Bridge smart transport to external command .
- `git-receive-pack`: Receive what is pushed into the repository
- `git-reflog`: Manage reflog information
- `git-remote-testgit`: Example remote-helper
- `git-remote-fd`: Reflect smart transport stream back to caller
- `git-remote`: Manage set of tracked repositories
- `git-repack`: Pack unpacked objects in a repository
- `git-replace`: Create, list, delete refs to replace objects
- `git-request-pull`: Generates a summary of pending changes
- `git-reset`: Reset current HEAD to the specified state
- `git-restore`: Restore working tree files
- `git-rev-list`: Lists commit objects in reverse chronological order
- `git-rev-parse`: Pick out and massage parameters
- `git-revert`: Revert some existing commits
- `git-send-pack`: Push objects over Git protocol to another repository
- `git-rm`: Remove files from the working tree and from the index
- `git-sh-i18n--envsubst`: Git (Aqs own envsubst(1) for i18n fallbacks
- `getfacl`: get file access control lists
- `git-sh-setup`: Common Git shell script setup code
- `git-show-index`: Show packed archive index
- `git-shell`: Restricted login shell for Git -only SSH access
- `git-shortlog`: Summarize  (Aqgit log (Aq output
- `git-show-branch`: Show branches and their commits
- `git-show-ref`: List references in a local repository
- `git-show`: Show various types of objects
- `git-stage`: Add file contents to the staging area
- `git-stash`: Stash the changes in a dirty working directory away
- `git-status`: Show the working tree status
- `git-stripspace`: Remove unnecessary whitespace
- `git-svn`:  fast, scalable, distributed revision control system (svn interoperability)
 Git is popular version control system designed to handle very large
 projects with speed and efficiency; it is used for many high profile
 open source projects, most notably the Linux kernel.
 .
 Git falls in the category of distributed source code management tools.
 Every Git working directory is a full-fledged repository with full
 revision tracking capabilities, not dependent on network access or a
 central server.
 .
 This package provides tools for interoperating with Subversion repositories,
 and importing SVN development history.


- `git-switch`: Switch branches
- `git-symbolic-ref`: Read, modify and delete symbolic refs
- `git-tag`: Create, list, delete or verify a tag object signed with GPG
- `git-unpack-file`: Creates a temporary file with a blob (Aqs contents
- `git-unpack-objects`: Unpack objects from a packed archive
- `git-update-index`: Register file contents in the working tree to the index
- `gdisk`:  GPT fdisk text-mode partitioning tool
 GPT fdisk (aka gdisk) is a text-mode partitioning
 tool that provides utilities for Globally Unique
 Identifier (GUID) Partition Table (GPT) disks.
 .
 Features:
 .
  - Edit GUID partition table definitions
  - In place conversion of BSD disklabels to GPT
  - In place conversion of MBR to GPT
  - In place conversion of GPT to MBR
  - Create hybrid MBR/GPT layouts
  - Repair damaged GPT data structures
  - Repair damaged MBR structures
  - Back up GPT data to a file (and restore from file)


- `getent`: get entries from Name Service Switch libraries
- `git-upload-archive`: Send archive back to git -archive
- `git-upload-pack`: Send objects packed back to git -fetch -pack
- `git-var`: Show a Git logical variable
- `git-verify-pack`: Validate packed Git archive files
- `git-verify-tag`: Check the GPG signature of tags
- `git-whatchanged`: Show logs with difference each commit introduces
- `ascii`:  interactive ASCII name and synonym chart
 The ascii utility provides easy conversion between various byte representations
 and the American Standard Code for Information Interchange (ASCII) character
 table.  It knows about a wide variety of hex, binary, octal, Teletype mnemonic,
 ISO/ECMA code point, slang names, XML entity names, and other representations.
 Given any one on the command line, it will try to display all others.  Called
 with no arguments it displays a handy small ASCII chart.


- `git`:  fast, scalable, distributed revision control system
 Git is popular version control system designed to handle very large
 projects with speed and efficiency; it is used for many high profile
 open source projects, most notably the Linux kernel.
 .
 Git falls in the category of distributed source code management tools.
 Every Git working directory is a full-fledged repository with full
 revision tracking capabilities, not dependent on network access or a
 central server.
 .
 This package provides the git main components with minimal dependencies.
 Additional functionality, e.g. a graphical user interface and revision
 tree visualizer, tools for interoperating with other VCS's, or a web
 interface, is provided as separate git* packages.


- `gksu`: GTK+ frontend for su and sudo
- `gksu-properties`: Configure the behaviour of gksu
- `glances`:  Curses-based monitoring tool
 Glances is a curses-based monitoring tool for GNU/Linux or BSD OS.
 Glances uses the PsUtil library to get information from your system.
 .
 It monitors CPU, load, memory, network bandwidth, disk I/O, disk use, process.


- `git-write-tree`: Create a tree object from the current index
- `getopt`: parse command options (enhanced)
- `glxdemo`: a demonstration of the GLX functions
- `glxgears`: ``gears'' demo for GLX
- `glxheads`: exercise multiple GLX connections
- `glxinfo`: show information about the GLX implementation
- `gettext`:  GNU Internationalization utilities
 Interesting for authors or maintainers of other packages or programs
 which they want to see internationalized.


- `gnome-desktop-item-edit`: tool to edit .desktop file
- `git-read-tree`: Reads tree information into the index
- `git-update-server-info`: Update auxiliary info file to help dumb servers
- `git-sh-i18n`: Git (Aqs i18n setup code for shell scripts
- `gnome-open`: Open files and URLs using the GNOME file handlers
- `gnome-panel`:  traditional panel, used in GNOME Flashback
 GNOME Flashback continues the traditional desktop interface which was used
 in GNOME 2.x, but using modern GNOME technologies.
 .
 GNOME Panel is a part of the GNOME Flashback desktop, and provides panels
 and default applets for the desktop. A panel is a horizontal or vertical
 bar that can be added to a screen margin. It can contain various applets,
 such as the menu bar, application launch icons, the clock, volume controls,
 and displays for network connectivity, battery level, and other system
 monitors.


- `gnome-power-statistics`: gnome power statistics gui
- `gnome-screensaver-command`: controls GNOME screensaver
- `gitweb`:  fast, scalable, distributed revision control system (web interface)
 Git is popular version control system designed to handle very large
 projects with speed and efficiency; it is used for many high profile
 open source projects, most notably the Linux kernel.
 .
 Git falls in the category of distributed source code management tools.
 Every Git working directory is a full-fledged repository with full
 revision tracking capabilities, not dependent on network access or a
 central server.
 .
 This package configures a web interface for browsing git repositories.
 .
 If apache2 is installed, the web interface is automatically made
 available at http://localhost/gitweb.  Other servers that support CGI
 or mod_perl are supported through manual configuration.
 .
 If libcgi-fast-perl is installed, gitweb can also be run over FastCGI
 (and served by nginx, for example).


- `git-update-ref`: Update the object name stored in a ref safely
- `atc`: air traffic controller game
- `backgammon`: the game of backgammon teachgammon
- `gitk`:  fast, scalable, distributed revision control system (revision tree visualizer)
 Git is popular version control system designed to handle very large
 projects with speed and efficiency; it is used for many high profile
 open source projects, most notably the Linux kernel.
 .
 Git falls in the category of distributed source code management tools.
 Every Git working directory is a full-fledged repository with full
 revision tracking capabilities, not dependent on network access or a
 central server.
 .
 This package provides the gitk program, a tcl/tk revision tree visualizer.


- `gnome-session-properties`: Configure applications to start on login
- `glib-compile-resources`: GLib resource compiler
- `gnome-settings-daemon`:  daemon handling the GNOME session settings
 This package contains the daemon which is responsible for setting the
 various parameters of a GNOME session and the applications that run
 under it. It handles the following kinds of settings:
 .
  * Keyboard: layout, accessibility options, shortcuts, media keys
  * Clipboard management
  * Theming: background, icons, GTK+ applications
  * Cleanup of unused files
  * Mouse: cursors, speed, accessibility options
  * Startup of other daemons: screensaver, sound daemon
 .
 It also sets various application settings through X resources and
 freedesktop.org XSETTINGS.


- `gnome-ssh-askpass`: prompts a user for a passphrase using GNOME
- `gnome-calculator`:  GNOME desktop calculator
 The GNOME calculator is a powerful graphical calculator with financial,
 logical and scientific modes. It uses a multiple precision package to do its
 arithmetic to give a high degree of accuracy.


- `gnome-disk-image-mounter`: Attach and mount disk images
- `glib-compile-schemas`: GSettings schema compiler
- `google`: command-line access to (some) Google services
- `google-chrome`: the web browser from Google
- `fstab-decode`: run a command with fstab-encoded arguments
- `gnome-session-inhibit`: inhibit gnome -session functionality
- `getcap`: examine file capabilities
- `gnome-keyring-daemon`: The gnome -keyring daemon
- `gnome-screenshot`:  screenshot application for GNOME
 This tool takes a picture of the desktop or of a window and saves it
 into a file.


- `gedit`:  popular text editor for the GNOME desktop environment
 gedit is a text editor which supports most standard editor features,
 extending this basic functionality with other features not usually
 found in simple text editors. gedit is a graphical application which
 supports editing multiple text files in one window (known sometimes as
 tabs or MDI).
 .
 gedit fully supports international text through its use of the Unicode
 UTF-8 encoding in edited files. Its core feature set includes syntax
 highlighting of source code, auto indentation and printing and print preview
 support.
 .
 gedit is also extensible through its plugin system, which currently
 includes support for spell checking, comparing files, viewing CVS
 ChangeLogs, and adjusting indentation levels.


- `gnome-session`:  GNOME Session Manager - default GNOME session
 The GNOME Session Manager is in charge of starting the core components
 of the GNOME desktop, and applications that should be launched at
 login time. It also features a way to save and restore currently
 running applications.
 .
 This package contains the required components for the standard GNOME
 session, based on the GNOME Shell. It can be started from a display
 manager such as GDM, and requires 3D acceleration to work properly.


- `gpgsplit`: Split an OpenPGP message into packets
- `grep-dctrl`: grep Debian control files
- `grepdiff`: show files modified by a diff containing a regex
- `gpg`:  GNU Privacy Guard -- minimalist public key operations
 GnuPG is GNU's tool for secure communication and data storage.
 It can be used to encrypt data and to create digital signatures.
 It includes an advanced key management facility and is compliant
 with the proposed OpenPGP Internet standard as described in RFC4880.
 .
 This package contains /usr/bin/gpg itself, and is useful on its own
 only for public key operations (encryption, signature verification,
 listing OpenPGP certificates, etc).  If you want full capabilities
 (including secret key operations, network access, etc), please
 install the "gnupg" package, which pulls in the full suite of tools.


- `gpg-zip`: encrypt or sign files into an archive
- `gpasswd`: administer /etc/group and /etc/gshadow
- `gpgv`:  GNU privacy guard - signature verification tool
 GnuPG is GNU's tool for secure communication and data storage.
 .
 gpgv is actually a stripped-down version of gpg which is only able
 to check signatures. It is somewhat smaller than the fully-blown gpg
 and uses a different (and simpler) way to check that the public keys
 used to make the signature are valid. There are no configuration
 files and only a few options are implemented.


- `grep`:  GNU grep, egrep and fgrep
 'grep' is a utility to search for text in files; it can be used from the
 command line or in scripts.  Even if you don't want to use it, other packages
 on your system probably will.
 .
 The GNU family of grep utilities may be the "fastest grep in the west".
 GNU grep is based on a fast lazy-state deterministic matcher (about
 twice as fast as stock Unix egrep) hybridized with a Boyer-Moore-Gosper
 search for a fixed string that eliminates impossible text from being
 considered by the full regexp matcher without necessarily having to
 look at every character. The result is typically many times faster
 than Unix grep or egrep. (Regular expressions containing backreferencing
 will run more slowly, however.)


- `gnome-system-log`: the GNOME System Log Viewer
- `boot`: System bootup process based on UNIX System V Release 4
- `grn`: groff preprocessor for gremlin files                          nr grn_C  [.C] 0
- `gprof`: display call graph profile data
- `grog`: guess options for a following groff command
- `grap2graph`: convert a GRAP diagram into a cropped image
- `grepjar`: search files in a jar file for a pattern
- `gconftool-2`: GNOME configuration tool
- `gnome-disks`: the GNOME Disks application
- `gresource`: GResource tool
- `gitremote-helpers`: Helper programs to interact with remote repositories
- `growisofs`:  DVD+-RW/R recorder
 growisofs is a general purpose DVD recording program that supports:
 .
  * random-access media (DVD+RW, DVD-RAM, plain files, hard disk partitions)
  * mastering multisession DVD media (DVD+R, DVD-R/-RW, and Blu-ray Disc)
  * first-/single-session recording of arbitrary pre-mastered image
    (formatted as UDF, ISO9660 or any other file system, if formatted at
    all) to all supported DVD media types.
 .
 growisofs is able to either write pre-created ISO images or create them
 on-the-fly (by calling genisoimage).
 .
 This package also contains dvd+rw-format, a utility to format a DVD+RW media.


- `groffer`: display groff files and man pages on X and tty
- `getty`: alternative Linux getty
- `grolj4`: groff driver for HP LaserJet 4 family
- `grohtml`: HTML driver for groff
- `gnome-session-quit`: End the current GNOME session
- `gparted`:  GNOME partition editor
 GParted uses libparted to detect and manipulate devices and partition
 tables while several (optional) filesystem tools provide support for
 filesystems not included in libparted.


- `gropdf`: PDF driver for groff    nr gropdf_C  [.C] 0                          if ' \ *(.T'ps' .ft  \ $1 if ' \ *(.T'pdf' .ft  \ $1
- `grolbp`: groff driver for Canon CAPSL printers (LBP-4 and LBP-8    series laser printers)    nr grolbp_C  [.C] 0
- `grops`: PostScript driver for groff
- `getkeycodes`: print kernel scancode-to-keycode mapping table
- `groupadd`: create a new group
- `grpunconv`: convert to and from shadow
   passwords and groups
- `groupdel`: delete a group
- `grotty`: groff driver for typewriter-like devices                          nr grotty_C  [.C] 0
- `groups`: display current group names
- `grub-editenv`: edit GRUB environment block
- `grub-file`: check file type
- `groupmod`: modify a group definition on the system
- `grpck`: verify integrity of group files
- `grub-install`: install GRUB to a device
- `grub-kbdcomp`: generate a GRUB keyboard layout file
- `grub-menulst2cfg`: transform legacy menu.lst into grub.cfg
- `grpconv`: convert to and from shadow
   passwords and groups
- `grub-fstest`: debug tool for GRUB filesystem drivers
- `grub-mkfont`: make GRUB font files
- `grub-mkimage`: make a bootable image of GRUB
- `grub-mklayout`: generate a GRUB keyboard layout file
- `grub-glue-efi`: generate a fat binary for EFI
- `grub-mkdevicemap`: make a device map file automatically
- `grub-mkrelpath`: make a system path relative to its root
- `grub-mkstandalone`: make a memdisk-based GRUB image
- `grub-probe`: probe device information for GRUB
- `grub-mkrescue`: make a GRUB rescue image
- `grub-mkconfig`: generate a GRUB configuration file
- `grub-render-label`: generate a .disk_label for Apple Macs.
- `gst-feedback-0.10`: generate debug info for GStreamer bug reports
- `gst-inspect-0.10`: print info about a GStreamer plugin or element
- `grub-script-check`: check grub.cfg for syntax errors
- `gst-install`: installs missing GStreamer plugins
- `gst-launch-0.10`: build and run a GStreamer pipeline
- `gs`: Ghostscript (PostScript and PDF language interpreter and previewer)
- `gst-discoverer-1.0`: Display file metadata and stream information
- `gst-typefind-0.10`: print MIME type of file
- `gst-inspect-1.0`: print info about a GStreamer plugin or element
- `gst-visualise-0.10`: Run a GStreamer pipeline to display an audio visualisation
- `gst-xmllaunch-0.10`: build and run a GStreamer pipeline from an XML serialization
- `gsettings-data-convert`: GConf to GSettings data migration
- `gst-play-1.0`: Simple command line playback testing tool
- `gsettings-schema-convert`: GConf to GSettings schema conversion
- `gtk-query-immodules-2.0`: Input method module registration utility
- `gslp`: Format and print text using ghostscript
- `gst-launch-1.0`: build and run a GStreamer pipeline
- `gtk-update-icon-cache-3.0`: Icon theme caching utility
- `gucharmap`:  Unicode character picker and font browser
 This program allows you to browse through all the available Unicode
 characters and categories for the installed fonts, and to examine
 their detailed properties.  It is an easy way to find the character
 you might only know by its Unicode name or code point.


- `gvfs-cat`: Concatenate files
- `gvfs-copy`: Copy files
- `gvfs-info`: Show information about files
- `gvfs-ls`: List files
- `gvfs-mime`: Get or set mime handlers
- `gvfs-mkdir`: Create directories
- `gvfs-monitor-dir`: Monitor directories for changes
- `gvfs-monitor-file`: Monitor files for changes
- `gvfs-mount`: Mounts the locations
- `gvfs-move`: Copy files
- `gvfs-open`: Open files with the default handler
- `gvfs-rename`: Rename a file
- `gvfs-rm`: Delete files
- `gvfs-save`: Save standard input
- `gvfs-set-attribute`: Set file attributes
- `gvfs-trash`: Move files or directories to the trash
- `gvfs-tree`: List contents of directories in a tree-like format
- `gvfsd-fuse`: Fuse daemon for gvfs
- `gtk-update-icon-cache`:  icon theme caching utility
 gtk-update-icon-cache creates mmap()able cache files for icon themes.
 .
 GTK can use the cache files created by gtk-update-icon-cache to avoid a lot
 of system call and disk seek overhead when the application starts. Since the
 format of the cache files allows them to be mmap()ed shared between multiple
 applications, the overall memory consumption is reduced as well.


- `guile`: The GNU Project Extension Language
- `gsnd`: Run ghostscript (PostScript and PDF engine) without display
- `gsettings`: GSettings configuration tool
- `grub-syslinux2cfg`: transform syslinux config into grub.cfg
- `gst-typefind-1.0`: print Media type of file
- `gunzip`: compress or expand files
- `grub-mknetdir`: prepare a GRUB netboot directory.
- `hardening-check`: check binaries for security hardening features
- `hbpldecode`: Decode a HBPL stream into human readable form.
- `enc2xs`: Perl Encode Module Generator
- `gxditview`: display groff intermediate output files
- `hciemu`: HCI emulator
- `hashcat`:  World's fastest and most advanced password recovery utility
 Hashcat supports five unique modes of attack for over 300 highly-optimized
 hashing algorithms. hashcat currently supports CPUs, GPUs, and other
 hardware accelerators on Linux, and has facilities to help enable
 distributed password cracking.
 .
 Examples of hashcat supported hashing algorithms are:
 MD5, HMAC-MD5, SHA1, HMAC-SHA1, MySQL323, MySQL4.1/MySQL5, phpass,
 MD5(Wordpress), MD5(phpBB3), MD5(Joomla), md5crypt, MD5(Unix),
 FreeBSD MD5, Cisco-IOS, MD4, NTLM, Domain Cached Credentials (DCC),
 MS Cache, SHA256, HMAC-SHA256, md5apr1, MD5(APR), Apache MD5, SHA512,
 HMAC-SHA512, Cisco-PIX, Cisco-ASA, WPA/WPA2, Double MD5, bcrypt,
 Blowfish(OpenBSD), MD5(Sun), Double SHA1, SHA-3(Keccak),Half MD5,
 Password Safe SHA-256, IKE-PSK MD5, IKE-PSK SHA1,
 NetNTLMv1-VANILLA/NetNTLMv1-ESS, NetNTLMv2, Cisco-IOS SHA256,
 Android PIN, AIX {smd5}, AIX {ssha256}, AIX {ssha512}, AIX {ssha1},
 GOST, GOST R 34, Fortigate (FortiOS), OS X v10.8+, GRUB 2, IPMI2, RAKP,
 HMAC-SHA1, sha256crypt, SHA256(Unix), Drupal7, WBB3, scrypt, Cisco $8$,
 Cisco $9$, Radmin2, Django (PBKDF2-SHA256), Cram MD5, SAP, iSSHA-1,
 PrestaShop, PostgreSQL, Challenge-Response Authentication (MD5),
 MySQL Challenge-Response, Authentication (SHA1),
 SIP digest authentication (MD5), Plaintext, Joomla < 2.5.18, PostgreSQL,
 osCommerce, xt:Commerce, Skype, nsldap, Netscape, LDAP, nsldaps,
 SSHA-1(Base64), Oracle S: Type (Oracle 11+), SMF > v1.1, OS X v10.4,
 v10.5, v10.6, EPi, Django (SHA-1), MSSQL(2000), MSSQL(2005),
 PeopleSoft, EPiServer 6.x < v4, hMailServer, SSHA-512(Base64),
 LDAP {SSHA512}, OS X v10.7, MSSQL(2012 & 2014), vBulletin < v3.8.5,
 PHPS, vBulletin > v3.8.5, IPB2+, MyBB1.2+, Mediawiki B type,
 WebEdition CMS, Redmine.
 .
 Hashcat offers multiple attack modes for obtaining effective and
 complex coverage over a hash's keyspace. These modes are:
 .
  * Brute-Force attack
  * Combinator attack
  * Dictionary attack
  * Fingerprint attack
  * Hybrid attack
  * Mask attack
  * Permutation attack
  * Rule-based attack
  * Table-Lookup attack
  * Toggle-Case attack
  * PRINCE attack


- `hcitrace`: hcitrace daemon
- `hddtemp`: Utility to monitor hard drive temperature
- `grub-mkpasswd-pbkdf2`: generate hashed password for GRUB
- `hashdeep`:  recursively compute hashsums or piecewise hashings
 hashdeep is a set of tools to compute MD5, SHA1, SHA256, tiger
 and whirlpool hashsums of arbitrary number of files recursively.
 .
 The main hashdeep features are:
 .
   * It can compare those hashsums with a list of known hashes;
   * The tools can display those that match the list or those that
     does not match;
   * It can  display a time estimation when processing large files.
   * It can do piecewise hashing (hash input files in arbitrary
     sized blocks).
 .
 This package is useful in forensics investigations.


- `hciattach`: attach serial devices via UART HCI to BlueZ stack
- `grub-mount`: export GRUB filesystem with FUSE
- `grub-macbless`: bless a mac file/directory
- `hid2hci`: Bluetooth HID to HCI mode switching utility
- `hipercdecode`: Decode a HIPERC stream into human readable form.
- `upx`: compress or expand executable files
- `hciconfig`: configure Bluetooth devices
- `helpztags`: generate the help tags file for directory
- `hexchat`:  IRC client for X based on X-Chat 2
 HexChat is a graphical IRC client with a GTK+ GUI. Features include Python,
 Perl and Lua scripting support, a plugin API, multiple server/channel
 windows, spell checking, multiple authentication methods including SASL, and
 customizable notifications. For more information on IRC, see
 http://irchelp.org/.


- `7za`: A file archiver with highest compression ratio
- `hp-align`: Printer Cartridge Alignment Utility
- `hp-check`: Dependency/Version Check Utility
- `hp-clean`: Printer Printhead Cleaning Utility
- `hp-colorcal`: Printer Cartridge Color Calibration Utility
- `hp-firmware`: Firmware Download Utility
- `hp-info`: Device Information Utility
- `hp-levels`: Supply Levels Utility
- `hp-makeuri`: Device URI Creation Utility
- `hp-pkservice`: Policy Kit Service
- `hp-plugin`: Plugin Download and Install Utility
- `hp-probe`: Printer Discovery Utility
- `hp-query`: Model Query Utility
- `hp-scan`: Scan Utility
- `hp-setup`: Printer/Fax Setup Utility
- `hp-testpage`: Testpage Print Utility
- `hp-timedate`: Time/Date Utility
- `hp-unload`: Photo Card Access Utility
- `host`: DNS lookup utility
- `gtk-query-immodules-3.0`: Input method module registration utility
- `hexdump`: display file contents in hexadecimal, decimal, octal, or ascii
- `exportfs`: maintain table of exported NFS file systems
- `head`: output the first part of files
- `hydra`:  very fast network logon cracker
 Hydra is a parallelized login cracker which supports numerous protocols
 to attack. It is very fast and flexible, and new modules are easy to add.
 .
 This tool makes it possible for researchers and security consultants to
 show how easy it would be to gain unauthorized access to a system
 remotely.
 .
 It supports: Cisco AAA, Cisco auth, Cisco enable, CVS, FTP, HTTP(S)-FORM-GET,
 HTTP(S)-FORM-POST, HTTP(S)-GET, HTTP(S)-HEAD, HTTP-Proxy, ICQ, IMAP, IRC,
 LDAP, MS-SQL, MySQL, NNTP, Oracle Listener, Oracle SID, PC-Anywhere, PC-NFS,
 POP3, PostgreSQL, RDP, Rexec, Rlogin, Rsh, SIP, SMB(NT), SMTP, SMTP Enum,
 SNMP v1+v2+v3, SOCKS5, SSH (v1 and v2), SSHKEY, Subversion, Teamspeak (TS2),
 Telnet, VMware-Auth, VNC and XMPP.


- `gzip`:  GNU compression utilities
 This package provides the standard GNU file compression utilities, which
 are also the default compression tools for Debian.  They typically operate
 on files with names ending in '.gz', but can also decompress files ending
 in '.Z' created with 'compress'.


- `grub-set-default`: set the saved default boot entry for GRUB
- `identify.im6`: describes the format and characteristics of one or more image files.
- `idevicecrashreport`: Retrieve crash reports from a device.
- `hping3`:  Active Network Smashing Tool
 hping3 is a network tool able to send custom ICMP/UDP/TCP packets and
 to display target replies like ping does with ICMP replies. It handles
 fragmentation and arbitrary packet body and size, and can be used to
 transfer files under supported protocols. Using hping3, you can test
 firewall rules, perform (spoofed) port scanning, test network
 performance using different protocols, do path MTU discovery, perform
 traceroute-like actions under different protocols, fingerprint remote
 operating systems, audit TCP/IP stacks, etc.  hping3 is scriptable
 using the Tcl language.


- `ico`: animate an icosahedron or other polyhedron
- `htpasswd`: Manage user files for basic authentication
- `id`: return user identity
- `idevice_id`: Prints device name or a list of attached devices.
- `idevicebackup`: Create or restore backup for devices.
- `idevicebackup2`: Create or restore backups for devices running iOS 4 or later.
- `idevicedate`: Display the current date or set it on a device.
- `idevicedebugserverproxy`: Remote debugging proxy.
- `ideviceinstaller`:  Utility to manage installed applications on an iDevice
 ideviceinstaller is a tool to interact with the installation_proxy
 of an iDevice allowing to install, upgrade, uninstall, archive, restore,
 and enumerate installed or archived applications.
 .
 It makes use of the libimobiledevice library that allows communication
 with the devices.


- `iconv`: codeset conversion
- `idevicediagnostics`: Interact with the diagnostics interface of a device.
- `ideviceenterrecovery`: Make a device enter recovery mode.
- `ideviceimagemounter`: Mount disk images on the device.
- `ideviceinfo`: Show information about the first connected device.
- `wifite`:  Python script to automate wireless auditing using aircrack-ng tools
 Wifite is a tool to audit WEP or WPA encrypted wireless networks.
 It uses aircrack-ng, pyrit, reaver, tshark tools to perform the audit.
 .
 This tool is customizable to be automated with only a few arguments
 and can be trusted to run without supervision.


- `idmap_rfc2307`: Samba's idmap_rfc2307 Backend for Winbind
- `idmapwb`: winbind ID mapping plugin for cifs-utils
- `idevicename`: Display the device name or set it to NAME if specified.
- `efibootmgr`:  Interact with the EFI Boot Manager
 This is a Linux user-space application to modify the Intel Extensible
 Firmware Interface (EFI) Boot Manager configuration. This application can
 create and destroy boot entries, change the boot order, change the next
 running boot option, and more.
 .
 Additional information about (U)EFI can be found at http://www.uefi.org/.
 .
 Note: efibootmgr requires that the kernel module efivars be loaded prior
 to use. 'modprobe efivars' should do the trick if it does not
 automatically load.


- `httrack`:  Copy websites to your computer (Offline browser)
 HTTrack is an offline browser utility, allowing you to download a World
 Wide website from the Internet to a local directory, building recursively
 all directories, getting html, images, and other files from the server to
 your computer.
 .
 HTTrack arranges the original site's relative link-structure. Simply
 open a page of the "mirrored" website in your browser, and you can
 browse the site from link to link, as if you were viewing it online.
 HTTrack can also update an existing mirrored site, and resume
 interrupted downloads. HTTrack is fully configurable, and has an
 integrated help system.


- `hostnamectl`: Control the system hostname
- `hpftodit`: create font description files for use with groff  -Tlj4    nr hpftodit_C  [.C] 0
- `ifuse`:  FUSE module for iPhone and iPod Touch devices
 iFuse is a FUSE filesystem driver which uses libiphone to connect to iPhone
 and iPod Touch devices without needing to "jailbreak" them. iFuse uses the
 native Apple AFC protocol over a normal USB cable in order to access the
 device's media files.
 .
 Although iFuse is now in a working state it is still under heavy
 development and should be considered experimental.


- `igawk`: gawk with include files
- `im-config`:  Input method configuration framework
 im-config package provides the framework to configure and to switch
 the input method. This input method is the essential mechanism for
 Japanese, Chinese and Korean (CJK) languages to enter their non-ASCII
 native characters.
 .
 Many modern input methods such as IBus support not only one of these CJK
 languages but support almost all languages simultaneously by
 dynamically switching keyboard modes with GUI helper program.
 .
 By installing this package, the most desirable input method and its
 backend conversion engine are automatically configured with both the X
 Window System Input Method (XIM), GTK input method module, Qt input
 method module, and clutter input method module.
 .
 You can further customize your input method with 'im-config' command.


- `im-launch`: launch input method end execute session program
- `h2ph`: convert .h C header files to .ph Perl header files
- `iceauth`: ICE authority file utility
- `import.im6`: saves any visible window on an X server and outputs it as an image file. You can capture a single window, the entire screen, or any rectangular portion of the screen.
- `ideviceprovision`: Manage provisioning profiles on a device.
- `hdparm`:  tune hard disk parameters for high performance
 Get/set device parameters for Linux SATA/IDE drives.
 Provides a command line interface to various kernel interfaces supported by
 the Linux SATA/PATA/SAS "libata" subsystem and the older IDE driver subsystem.
 Many newer (2008 and later) USB drive enclosures now also support "SAT"
 (SCSI-ATA Command Translation) and therefore may also work with hdparm.


- `i386`: change  reported  architecture  in  new program environment
   and/or set personality flags
- `infokey`: compile customizations for Info
- `idevicepair`: Manage host pairings with devices and usbmuxd.
- `ifconfig`: configure a network interface
- `init-checkconf`: manual page for init-checkconf
- `pg_restore`: restore a PostgreSQL database from an archive file created
   by pg_dump
- `initctl`: init daemon control tool
- `initctl2dot`: manual page for initctl2dot
- `initramfs-tools`:  generic modular initramfs generator (automation)
 This package builds a bootable initramfs for Linux kernel packages.  The
 initramfs is loaded along with the kernel and is responsible for
 mounting the root filesystem and starting the main init system.


- `wine`:  Windows API implementation - standard suite
 Wine is a free MS-Windows API implementation.
 .
 This package provides essential wrappers and convenience tools for the
 standard Wine components. It also employs the Debian alternatives system to
 provide the usual command names, e.g. "wine" instead of "wine-stable".


- `wpaclean`: clean wpa capture files
- `x509.1s`: Certificate display and signing utility
- `inputattach`:  utility to connect serial-attached peripherals to the input subsystem
 inputattach connects legacy serial-attached input peripherals to the input
 subsystem: keyboards, mice, joysticks, touch-screens...
 .
 Amongst other things this allows legacy mice to be accessed via the
 /dev/input/mice multiplexer.
 .
 Supported devices include:
  * Serial-attached keyboards including the Apple Newton keyboard, DEC LK201
    / LK401 keyboards, the Stowaway keyboard, Sun type 4 and 5 keyboards,
    standard PS/2 keyboards with a serial adapter
  * Serial mice using Genius, Logitech, Microsoft or Mouse Systems protocols
  * Serial-attached touchscreens including those manufactured by 3M, ELO,
    Fujitsu, Penmount, Touchright, Touchwindow
  * Serial-attached joysticks including I-Force, SpaceBall, SpaceOrb, Gravis
    Stinger, WingMan Warrior
  * The Handykey Twiddler used as a joystick or a chording keyboard


- `ifdown`: parse interface configuration
- `insserv`:  boot sequence organizer using LSB init.d script dependency information
 The insserv program is used by the standard SysV-based init system. It
 updates the order of symlinks in /etc/rc?.d/ based on dependencies
 specified by LSB headers in the init.d scripts themselves.
 .
 These declared relations between scripts make it possible to optimize
 the boot sequence for the currently installed set of packages, while
 detecting and rejecting dependency loops.
 .
 Using insserv incorrectly can result in an unbootable system.


- `idevicesyslog`: Relay syslog of a connected device.
- `install-docs`: manage online Debian documentation
- `ifup`: parse interface configuration
- `idevicescreenshot`: Gets a screenshot from the connected device.
- `ike-scan`:  discover and fingerprint IKE hosts (IPsec VPN Servers)
 ike-scan discovers IKE hosts and can also fingerprint them using the
 retransmission backoff pattern.
 .
 ike-scan does two things:
 .
 a) Discovery: Determine which hosts are running IKE.
    This is done by displaying those hosts which respond to the IKE requests
    sent by ike-scan.
 .
 b) Fingerprinting: Determine which IKE implementation the hosts are using.
    This is done by recording the times of the IKE response packets from the
    target hosts and comparing the observed retransmission backoff pattern
    against known patterns.
 .
    The retransmission backoff fingerprinting concept is discussed in more
    detail in the UDP backoff fingerprinting paper which should be included
    in the ike-scan kit as udp-backoff-fingerprinting-paper.txt.


- `iecset`: Set or dump IEC958 status bits
- `intel_audio_dump`: Dumps the Intel GPU registers for HDMI audio setup.
- `intel_bios_dumper`: Saves the Intel video BIOS contents to a file.
- `intel_bios_reader`: Parses an Intel BIOS and displays many of its tables
- `intel_error_decode`: Decodes an Intel GPU dump automatically captured by the kernel at the time of an error.
- `intel_gpu_top`: Display a top-like summary of Intel GPU usage
- `intel_gtt`: Dump the contents of an Intel GPU's GTT
- `intel_infoframes`: View and change HDMI InfoFrames
- `intel_lid`: Polls the values of different reports about laptop lid state.
- `intel_panel_fitter`: Change the panel fitter settings
- `intel_reg_dumper`: Decode a bunch of Intel GPU registers for debugging
- `intel_reg_read`: Reads an Intel GPU register value
- `intel_reg_write`: Set an Intel GPU register to a value
- `intel_stepping`: Display the stepping information for an Intel GPU
- `intel_upload_blit_large`: microbenchmark of Intel GPU performance
- `intel_upload_blit_large_gtt`: microbenchmark of Intel GPU performance
- `intel_upload_blit_large_map`: microbenchmark of Intel GPU performance
- `intel_upload_blit_small`: microbenchmark of Intel GPU performance
- `interdiff`: show differences between two diff files
- `install`: copy files and set attributes
- `exiftool`: Read and write meta information in files
- `scala`: Run code in the Scala 2 language
- `salt`: allows for commands to be executed across a swath of remote systems in parallel
- `infotocap`: convert a terminfo description into a termcap description
- `import`: saves any visible window on an X server and outputs it as an image file. You can capture a single window, the entire screen, or any rectangular portion of the screen. The window to capture is selected by clicking the desired window or a program option.
- `w.procps`: Show who is logged on and what they are doing.
- `wpa_cli`: WPA command line client
- `vpddecode`: VPDstructure decoder
- `wpa_action`: wpa_cli action script
- `who`: display who is on the system
- `aseqnet`: ALSA sequencer connectors over network
- `ifquery`: parse interface configuration
- `xbiff`: mailbox flag for X
- `xcalc`: scientific calculator for X
- `xclipboard`: X clipboard client
- `gvfsd-metadata`: Metadata daemon for gvfs
- `init`:  metapackage ensuring an init system is installed
 This package is a metapackage which allows you to select from the available
 init systems while ensuring that one of these is available on the system at
 all times.


- `instmodsh`: A shell to examine installed modules
- `intro`: introduction to administration and privileged commands
- `ip-addrlabel`: protocol address label management
- `ip-fou`: Foo-over-UDP receive port configuration  ip-gue  -Generic UDP Encapsulation receive port configuration
- `ip-l2tp`: L2TPv3 static unmanaged tunnel configuration
- `ip-monitor`: state monitoring
- `ip-link`: network device configuration
- `ip-maddress`: multicast addresses management
- `ip-mroute`: multicast routing cache management
- `ip-neighbour`: neighbour/arp tables management.
- `ip-netconf`: network configuration monitoring
- `ip-netns`: process network namespace management
- `ip-ntable`: neighbour table configuration
- `ip-route`: routing table management
- `ip-rule`: routing policy database management
- `ip-tcp_metrics`: management for TCP Metrics
- `ip-token`: tokenized interface identifier support
- `xclock`: analog / digital clock for X
- `gzexe`: compress executable files in place
- `grodvi`: convert groff output to TeX DVI format                          nr grodvi_C  [.C] 0       if ' \ *(.T'dvi' .ft  \ $1
- `hwclock`: time clocks utility
- `flock`: apply or remove an advisory lock on an open file
- `iconvconfig`: create iconv module configuration cache
- `iproxy`: proxy that enables tcp service access to iPhone/iPod
- `installkernel`: install a new kernel image
- `groff`:  GNU troff text-formatting system
 This package contains optional components of the GNU troff text-formatting
 system. The core package, groff-base, contains the traditional tools like
 troff, nroff, tbl, eqn, and pic. This package contains additional devices
 and drivers for output to DVI, HTML (when recommended packages are
 installed - see below), PDF, HP LaserJet printers, and Canon CAPSL LBP-4
 and LBP-8 printers.
 .
 The X75, X75-12, X100, and X100-12 devices, which allow groff output to be
 conveniently viewed on an X display using the standard X11 fonts, are now
 included here. They were previously in a separate package, groff-x11.
 .
 Besides these, the groff package contains man pages describing the language
 and its macro sets, info documentation, and a number of supplementary
 programs:
 .
  - gxditview, which is used to display the output of the X* devices, and
    can also be used to view PostScript output from groff;
  - grn, a preprocessor for pictures in the 'gremlin' format;
  - tfmtodit, which creates font files for use with 'groff -Tdvi';
  - hpftodit, which creates font files for use with 'groff -Tlj4';
  - afmtodit, which creates font files for use with 'groff -Tps';
  - refer, which preprocesses bibliographic references for use with groff;
  - indxbib, which creates inverted indices for bibliographic databases used
    by 'refer';
  - lkbib and lookbib, which search bibliographic databases;
  - addftinfo, which adds metric information to troff font files for use
    with groff;
  - pfbtops, which translates a PostScript font in .pfb format to ASCII for
    use with groff;
  - mmroff, a simple groff preprocessor which expands references in mm;
  - pic2graph, which converts PIC diagrams into cropped image files;
  - eqn2graph, which converts EQN equations into cropped image files;
  - pdfmom, which runs 'groff -mom' to produce PDFs.
 .
 All the standard macro packages are supported.
 .
 Some facilities only work if certain recommended packages are installed:
 .
  - ghostscript, netpbm, psutils: required for HTML output;
  - imagemagick: required for the pic2graph and eqn2graph programs;
  - perl: required for PDF output and for the chem preprocessor.


- `ipcmk`: make various IPC resources
- `flatpak`:  Application deployment framework for desktop apps
 Flatpak installs, manages and runs sandboxed desktop application bundles.
 Application bundles run partially isolated from the wider system, using
 containerization techniques such as namespaces to prevent direct access
 to system resources. Resources from outside the sandbox can be accessed
 via "portal" services, which are responsible for access control; for
 example, the Documents portal displays an "Open" dialog outside the
 sandbox, then allows the application to access only the selected file.
 .
 Each application uses a specified "runtime", or set of libraries, which is
 available as /usr inside its sandbox. This can be used to run application
 bundles with multiple, potentially incompatible sets of dependencies within
 the same desktop environment.
 .
 This package contains the services and executables needed to install and
 launch sandboxed applications, and the portal services needed to provide
 limited access to resources outside the sandbox.


- `install-sgmlcatalog`: maintain transitional SGML catalog
- `irqbalance`:  Daemon to balance interrupts for SMP systems
 Daemon to balance interrupts across multiple CPUs, which can lead to better
 performance and IO balance on SMP systems. This package is especially useful
 on systems with multi-core processors, as interrupts will typically only be
 serviced by the first core.
 .
 Note: irqbalance is not useful if you don't have more than one CPU core.


- `iptables-apply`: a safer way to update iptables remotely
- `inxi`:  full featured system information script
 Inxi is a system information script that can display various things about
 your hardware and software to users in an IRC chatroom or support forum.
 It runs with the /exec command in most IRC clients.


- `iostat`: Report Central Processing Unit (CPU) statistics and input/out‐
   put statistics for devices and partitions.
- `isohybrid`: Postprocess ISO images for hybrid mode
- `isohybrid.pl`: Postprocess ISO images for hybrid mode (Perl)
- `ipcs`: report XSI interprocess communication facilities status
- `ipcrm`: remove an XSI message queue, semaphore set, or shared memory segment identifier
- `invoke-rc.d`: executes System-V style init script actions
- `ionice`: set or get process I/O scheduling class and priority
- `ippfind`: find internet printing protocol printers
- `insmod`: Simple program to insert a module into the Linux Kernel
- `iptables-restore`: Restore IP Tables  ip6tables-restore  Restore IPv6 Tables
- `ispell-autobuildhash`: Autobuilding the ispell hash file for some dicts
- `isadump`: examine ISA registers
- `iwconfig`: configure a wireless network interface
- `iwevent`: Display  Wireless  Events  generated by drivers and setting
   changes
- `jdownloader`: download manager for one-click hosting sites
- `zipgrep`: search files in a ZIP archive for lines matching a pattern
- `zmore`: file perusal filter for crt viewing of compressed text
- `zstd`:  fast lossless compression algorithm -- CLI tool
 Zstd, short for Zstandard, is a fast lossless compression algorithm, targeting
 real-time compression scenarios at zlib-level compression ratio.
 .
 This package contains the CLI program implementing zstd.


- `jfs_debugfs`: shell-type JFS file system editor
- `jfs_fsck`: initiate  replay of the JFS transaction log, and check and
   repair a JFS formatted device
- `jfs_fscklog`: extract a JFS fsck service log into a file and/or format
   and display the extracted file
- `ispell-wrapper`: smart wrapper for ispell
- `join-dctrl`: perform relational join on data in dctrl format
- `jq`:  lightweight and flexible command-line JSON processor
 jq is like sed for JSON data – you can use it to slice
 and filter and map and transform structured data with
 the same ease that sed, awk, grep and friends let you
 play with text.
 .
 It is written in portable C, and it has minimal runtime
 dependencies.
 .
 jq can mangle the data format that you have into the
 one that you want with very little effort, and the
 program to do so is often shorter and simpler than
 you’d expect.


- `jfs_logdump`: dump a JFS formatted device's journal log
- `kate`:  powerful text editor
 Kate is a powerful text editor that can open multiple files simultaneously.
 .
 With a built-in terminal, syntax highlighting, and tabbed sidebar, it performs
 as a lightweight but capable development environment.  Kate's many tools,
 plugins, and scripts make it highly customizable.
 .
 Kate's features include:
 .
  * Multiple saved sessions, each with numerous files
  * Scriptable syntax highlighting, indentation, and code-folding
  * Configurable templates and text snippets
  * Symbol viewers for C, C++, and Python
  * XML completion and validation


- `gvfsd`: Main daemon for gvfs
- `jfs_mkfs`: create a JFS formatted partition
- `iwlist`: Get more detailed wireless information from a wireless inter‐
   face
- `xcmsdb`: Device Color Characterization utility for X Color Management
   System
- `kerneloops`: program to collect and submit kernel oopses to oops.kernel.org
- `xconsole`: monitor system console messages with X
- `iwpriv`: configure optionals (private) parameters of a wireless network
   interface
- `javac`: Reads Java class and interface definitions and compiles them
   into bytecode and class files.
- `x11perf`: X11 server performance test program
- `jmap`: Prints shared object memory maps or heap memory details for a
   process, core file, or remote debug server. This command is
   experimental and unsupported.
- `x11perfcomp`: X11 server performance comparison program
- `jstack`: Prints Java thread stack traces for a Java process, core file,
   or remote debug server. This command is experimental and unsupported.
- `install-info`:  Manage installed documentation in info format
 The install-info utility creates the index of all installed documentation
 in info format and makes it available to info readers.


- `xcursorgen`: create an X cursor file from a collection of PNG images
- `kpartx`:  create device mappings for partitions
 Kpartx can be used to set up device mappings for the partitions of any
 partitioned block device.
 .
 It is part of the Linux multipath-tools, but is useful on any
 device-mapper using system.


- `iw`:  tool for configuring Linux wireless devices
 This package contains the 'iw' command line tool which allows one to configure
 and show information about wireless devices.
 .
 iw is based on the nl80211 kernel interface and supports the majority of
 fairly recent hardware. The old tool iwconfig, which uses Wireless Extensions
 interface, is deprecated and it is strongly recommended to switch to iw and
 nl80211.


- `exa`: new 2D acceleration architecture for X.Org
- `laptop-detect`:  system chassis type checker
 This package provides a simple shell script which attempts to determine
 whether it is being run on a laptop (or similar portable machine). It is
 mainly useful for installers.


- `kismet`:  wireless network and device detector (metapackage)
 Kismet is a wireless network and device detector, sniffer, wardriving tool,
 and WIDS (wireless intrusion detection) framework.
 .
 Kismet works with Wi-Fi interfaces, Bluetooth interfaces, some SDR (software
 defined radio) hardware like the RTLSDR, and other specialized capture
 hardware.
 .
 This is a metapackage containing the kismet tools.


- `kstats`: show  statistical  FMS algorithm votes for an ivs dump and a
   specified WEP key
- `lavadecode`: Decode a LAVAFLOW stream into human readable form.
- `json_pp`: JSON::PP command utility
- `last`: show a listing of last logged in users
- `ld.so`: dynamic linker/loader
- `iwspy`: Get wireless statistics from specific nodes
- `journalctl`: Query the systemd journal
- `isosize`: output the length of an iso9660 filesystem
- `kbd_mode`: report or set the keyboard mode
- `ldapsearch`: LDAP search tool
- `killall5`: send a signal to all processes.
- `lcf`: Determine  which  of the historical versions of a config is in‐
   stalled
- `lastlog`: reports the most recent login of all users or of a given user
- `killall`: kill processes by name
- `ld.gold`: The GNU ELF linker
- `keyctl`: manipulate the kernel's key management facility
- `line`: read one line
- `lessecho`: expand metacharacters
- `xcutsel`: interchange between cut buffer and selection
- `openssl`:  Secure Sockets Layer toolkit - cryptographic utility
 This package is part of the OpenSSL project's implementation of the SSL
 and TLS cryptographic protocols for secure communication over the
 Internet.
 .
 It contains the general-purpose command line binary /usr/bin/openssl,
 useful for cryptographic operations such as:
  * creating RSA, DH, and DSA key parameters;
  * creating X.509 certificates, CSRs, and CRLs;
  * calculating message digests;
  * encrypting and decrypting with ciphers;
  * testing SSL/TLS clients and servers;
  * handling S/MIME signed or encrypted mail.


- `lintian`:  Debian package checker
 Lintian dissects Debian packages and reports bugs and policy violations. It
 contains automated checks for many aspects of Debian policy as well as some
 checks for common errors.
 .
 This package is useful for all people who want to check Debian packages for
 compliance with Debian policy. Every Debian maintainer should check packages
 with this tool before uploading them to the archive.


- `lintian-info`: give detailed information about Lintian's error tags
- `infocmp`: compare or print out terminfo descriptions
- `lesspipe`: "input preprocessor" for  less.
- `xargs`: construct argument lists and invoke utility
- `lesskey`: specify key bindings for less
- `join`: relational database operator
- `xauth`:  X authentication utility
 xauth is a small utility to read and manipulate Xauthority files, which
 are used by servers and clients alike to control authentication and access
 to X sessions.


- `lft`:  layer-four traceroute
 This sends various TCP SYN and FIN probes (differing from Van Jacobson's
 UDP-based method) utilizing the IP protocol "time to live" field and
 attempts to elicit an ICMP TIME_EXCEEDED response from each gateway along
 the path to some host.
 lft also listens for various TCP and ICMP messages along the way to assist
 network managers in ascertaining per-protocol heuristic routing information
 and can optionally retrieve various information about the networks it
 traverses.


- `lexgrog`: parse header information in man pages
- `libreoffice`:  office productivity suite (metapackage)
 LibreOffice is a full-featured office productivity suite that provides
 a near drop-in replacement for Microsoft(R) Office.
 .
 This metapackage installs all components of libreoffice:
  * libreoffice-writer: Word processor
  * libreoffice-calc: Spreadsheet
  * libreoffice-impress: Presentation
  * libreoffice-draw: Drawing
  * libreoffice-base: Database
  * libreoffice-math: Equation editor
 It also recommends additional packages (e.g. fonts) in order to match an
 upstream LibreOffice install as closely as possible.
 .
 You can extend the functionality of LibreOffice by installing these
 packages:
  * hunspell-*/myspell-*: Hunspell/Myspell dictionaries
    for use with LibreOffice
  * libreoffice-l10n-*: UI interface translation
  * libreoffice-help-*: User help
  * mythes-*: Thesauri for the use with LibreOffice
  * hyphen-*: Hyphenation patterns for LibreOffice
  * libreoffice-gtk(2|3): Gtk UI Plugin, GNOME File Picker support
  * libreoffice-gnome: GIO backend
  * unixodbc: ODBC database support
  * cups-bsd: Allows LibreOffice to detect your CUPS printer queues
    automatically
  * libsane: Use your sane-supported scanner with LibreOffice
  * libxrender1: Speed up display by using Xrender library
  * libgl1: OpenGL support
  * openclipart-libreoffice: Open Clip Art Gallery with LibreOffice index
    files
  * firefox-esr | thunderbird | firefox:
    Mozilla profile with Certificates needed for XML Security...
  * openjdk-11-jre | openjdk-8-jre | java8-runtime:
    Java Runtime Environment for use with LibreOffice
  * pstoedit / imagemagick / ghostscript: helper tools for EPS
  * gstreamer0.10-plugins-*: GStreamer plugins for use with LibreOffices
    media backend
  * libpaper-utils: papersize detection support via paperconf
  * bluez: Bluetooth support for Impress (slideshow remote control)


- `loadndisdriver`: load ndis driver (wrapper)
- `loadndisdriver-1.9`: Userspace ndis driver loader for the ndiswrapper Linux kernel module
- `linux64`: change  reported  architecture  in  new program environment
   and/or set personality flags
- `linux32`: change  reported  architecture  in  new program environment
   and/or set personality flags
- `l2ping`: Send L2CAP echo request and receive answer
- `listres`: list resources in widgets
- `nroff`: use groff to format documents for TTY devices
- `nsenter`: run program with namespaces of other processes
- `lockfile-progs`:  Programs for locking and unlocking files and mailboxes
 This package includes several programs to safely lock and unlock
 files and mailboxes from the command line.  These include:
 .
   lockfile-create
   lockfile-remove
   lockfile-touchlock
   mail-lock
   mail-unlock
   mail-touchlock
 .
 These programs use liblockfile to perform the file locking and
 unlocking, so they are guaranteed compatible with Debian's
 file locking policies.


- `bastet`:  ncurses Tetris clone with a bastard algorithm
 Bastet ("bastard Tetris") is a free clone of Tetris which tries to
 compute how useful blocks are and gives you the worst possible brick.
 Playing bastet can be a painful experience, especially if you usually
 make "canyons" and wait for the long I-shaped block.


- `log2pcap`: Extract network traces from Samba log files
- `ldattach`: attach a line discipline to a serial line
- `ln`: link files
- `lkbib`: search bibliographic databases
- `ldconfig`: configure dynamic linker run-time bindings
- `start-pulseaudio-x11`: PulseAudio Sound Server X11 Startup Script
- `tty`: controlling terminal
- `key.dns_resolver`: upcall for request -key to handle dns_resolver keys
- `xdg-desktop-icon`: command line tool for (un)installing icons to the desktop
- `locate`:  maintain and query an index of a directory tree
 updatedb generates an index of files and directories. GNU locate can be used
 to quickly query this index.


- `kbdrate`: reset the keyboard repeat rate and delay time
- `localectl`: Control the system locale and keyboard layout settings
- `tar`:  GNU version of the tar archiving utility
 Tar is a program for packaging a set of files as a single archive in tar
 format.  The function it performs is conceptually similar to cpio, and to
 things like PKZIP in the DOS world.  It is heavily used by the Debian package
 management system, and is useful for performing system backups and exchanging
 sets of files with others.


- `localedef`: define locale environment
- `locale-gen`: generates localisation files from templates
- `lnstat`: unified linux network statistics
- `logger`: log messages
- `lppasswd`: add, change, or delete digest passwords.
- `loginctl`: Control the systemd login manager
- `look`: display lines beginning with a given string
- `logrotate`:  Log rotation utility
 The logrotate utility is designed to simplify the administration of
 log files on a system which generates a lot of log files.  Logrotate
 allows for the automatic rotation compression, removal and mailing of
 log files.  Logrotate can be set to handle a log file daily, weekly,
 monthly or when the log file gets to a certain size.  Normally, logrotate
 runs as a daily cron job.


- `lorder`: list dependencies for object files
- `loadunimap`: load the kernel unicode-to-font mapping table
- `lpc`: line printer control program (deprecated)
- `info`:  Standalone GNU Info documentation browser
 The Info file format is an easily-parsable representation for online
 documents. This program allows you to view Info documents, like the
 ones stored in /usr/share/info.
 .
 Much of the software in Debian comes with its online documentation in
 the form of Info files, so it is most likely you will want to install it.


- `indxbib`: make inverted index for bibliographic databases
- `lpoptions`: display or set printer options and defaults
- `lsdiff`: show which files are modified by a patch
- `xdg-desktop-menu`: command line tool for (un)installing desktop menu items
- `zip`:  Archiver for .zip files
 This is InfoZIP's zip program. It produces files that are fully
 compatible with the popular PKZIP program; however, the command line
 options are not identical. In other words, the end result is the same,
 but the methods differ. :-)
 .
 This version supports encryption.


- `lpq`: show printer queue status
- `login`:  system login tools
 This package provides support for console-based logins and for
 changing effective user or group IDs, including:
  * login, the program that invokes a user shell on a virtual terminal,
  * nologin, a dummy shell for disabled user accounts,
  * newgrp, a program to change the effective group IDs.


- `lrzuntar`: Extract whole tarball from .tar.lrz files
- `ls`: list directory contents
- `lss16toppm`: Convert an LSS-16 image to PPM
- `losetup`: set up and control loop devices
- `ltrace`:  Tracks runtime library calls in dynamically linked programs
 ltrace is a debugging program which runs a specified command until it
 exits.  While the command is executing, ltrace intercepts and records
 the dynamic library calls which are called by
 the executed process and the signals received by that process.
 It can also intercept and print the system calls executed by the program.
 .
 The program to be traced need not be recompiled for this, so you can
 use it on binaries for which you don't have the source handy.
 .
 You should install ltrace if you need a sysadmin tool for tracking the
 execution of processes.


- `lsblk`: list block devices
- `logname`: return the user's login name
- `lrzip`:  compression program with a very high compression ratio
 A compression program that can achieve very high compression
 ratios and speed when used with large files. It uses the combined
 compression algorithms of zpaq and lzma for maximum compression, lzo
 for maximum speed, and the long range redundancy reduction of rzip.
 It is designed to scale with increases with RAM size, improving
 compression further. A choice of either size or speed optimizations
 allows for either better compression than even lzma can provide, or
 better speed than gzip, but with bzip2 sized compression levels.


- `lpadmin`: configure cups printers and classes
- `lpmove`: move a job or all jobs to a new destination
- `lslocks`: list local system locks
- `lsinitramfs`: list content of an initramfs image
- `lvmchange`: change attributes of the logical volume manager
- `lspci`: list all PCI devices
- `luksformat`: Create and format an encrypted LUKS device
- `lshw`:  information about hardware configuration
 A small tool to provide detailed information on the hardware
 configuration of the machine. It can report exact memory
 configuration, firmware version, mainboard configuration, CPU version
 and speed, cache configuration, bus speed, etc. on DMI-capable x86
 systems, on some PowerPC machines (PowerMac G4 is known to work) and AMD64.
 .
 Information can be output in plain text, HTML or XML.


- `lsusb`: list USB devices
- `lvcreate`: Create a logical volume
- `lvchange`: Change the attributes of logical volume(s)
- `lvconvert`: Change logical volume layout
- `lvextend`: Add space to a logical volume
- `lvm`: LVM2 tools
- `lvmconf`: LVM configuration modifier
- `lvmdiskscan`: List devices that may be used as physical volumes
- `lvmdump`: create lvm2 information dumps for diagnostic purposes
- `lynx`:  classic non-graphical (text-mode) web browser
 In continuous development since 1992, Lynx sets the standard for
 text-mode web clients. It is fast and simple to use, with support for
 browsing via FTP, Gopher, HTTP, HTTPS, NNTP, and the local file system.


- `lz`: gunzips and shows a listing of a gzip'd tar'd archive
- `lsattr`: list file attributes on a Linux second extended file system
- `xdotool`:  simulate (generate) X11 keyboard/mouse input events
 xdotool lets you programmatically (or manually) simulate keyboard
 input and mouse activity, move and resize windows, etc. It does this
 using X11's XTEST extension and other Xlib functions.


- `macchanger`:  utility for manipulating the MAC address of network interfaces
 GNU MAC Changer is an utility that makes the maniputation of MAC addresses of
 network interfaces easier.  MAC addresses are unique identifiers on networks,
 they only need to be unique, they can be changed on most network hardware.
 MAC addresses have started to be abused by unscrupulous marketing firms,
 government agencies, and others to provide an easy way to track a computer
 across multiple networks.  By changing the MAC address regularly, this kind
 of tracking can be thwarted, or at least made a lot more difficult.
 .
 Features:
 .
   * set specific MAC address of a network interface
   * set the MAC randomly
   * set a MAC of another vendor
   * set another MAC of the same vendor
   * set a MAC of the same kind (eg: wireless card)
   * display a vendor MAC list (today, 6200 items) to choose from


- `lvremove`: Remove logical volume(s) from the system
- `MAKEDEV`: create devices
- `luit`:  locale and ISO 2022 support for Unicode terminals
 Luit is a filter that can be run between an arbitrary application and a
 UTF-8 terminal emulator.  It will convert application output  from  the
 locale's  encoding  into  UTF-8,  and convert terminal input from UTF-8
 into the locale's encoding.
 .
 This is version 2.0 of luit, which can use encoding information from
 either the font-encoding data-files in the "xfonts-encodings" package,
 or the standard locale support in the C runtime library.


- `mail`: send and receive Internet mail
- `loadkeys`: load keyboard translation tables
- `lzmainfo`: show information stored in the .lzma file header
- `manhole`: Connect to a Twisted Manhole service
- `mailq`: a Mail Transfer Agent
- `m4`:  macro processing language
 GNU `m4' is an implementation of the traditional UNIX macro
 processor.  It is mostly SVR4 compatible, although it has some
 extensions (for example, handling more than 9 positional parameters to
 macros).  `m4' also has builtin functions for including files, running
 shell commands, doing arithmetic, etc.  Autoconf needs GNU `m4' for
 generating `configure' scripts, but not for running them.


- `mattrib`: change MSDOS file attribute flags
- `mako-render`: renders Mako templates
- `mbadblocks`: tests a floppy disk, and marks the bad blocks in the FAT
- `xdg-email`: command line tool for sending mail using the user (Aqs preferred e -mail composer
- `lvscan`: List all logical volumes in all volume groups
- `mcat`: dump raw disk image
- `mcd`: change MSDOS directory
- `mcheck`: verify all files on an MS-DOS formatted disk
- `mcomp`: Compares two files using mtools
- `locale`: description of multilanguage support
- `mcopy`: copy MSDOS files to/from Unix
- `md5pass`: Create an MD5 password hash
- `lvs`: Display information about logical volumes
- `mdel`: delete an MSDOS file
- `mdeltree`: recursively delete an MSDOS directory and its contents
- `mdir`: display an MSDOS directory
- `mdm`:  Utilities for single-host parallel shell scripting
 The Middleman System (mdm) is a set of utilities that help you
 parallelize your shell scripts.  Simply label the commands to run in
 parallel, and the System automatically exploits every parallelization
 opportunity that arises at runtime.  You can also specify dependency
 between commands so that they run in an appropriate order.
 .
 mdm comes with an ncurses-based monitoring console and is compatible with
 xargs, find, make and any shell. It can be run in a script or interactively.


- `grub-reboot`: set the default boot entry for GRUB, for the next boot only
- `mdmflexiserver`: start a MDM session using the MDM flexible server mechanism
- `mdmlogin`: MDM Display Manager greeting window
- `mdu`: display the amount of space occupied by an MSDOS directory
- `melt`:  command line media player and video editor
 melt was meant as a test tool for the MLT framework, but it is also a powerful
 multitrack command line oriented video editor. It could also used as an
 minimalistic media player for audio and video files.


- `memdiskfind`: utility to search for a MEMDISK instance
- `mencoder`:  MPlayer's Movie Encoder
 MPlayer plays most MPEG, VOB, AVI, Ogg/OGM, VIVO,
 ASF/WMA/WMV, QT/MOV/MP4, FLI, RM, NuppelVideo, yuv4mpeg, FILM, RoQ, PVA files,
 supported by many native, XAnim, RealPlayer, and Win32 DLL codecs. It can
 also play VideoCD, SVCD, DVD, 3ivx, RealMedia, and DivX movies.
 .
 This package contains mencoder, a simple movie encoder, designed to
 encode MPlayer-playable movies
 (AVI/ASF/OGG/DVD/VCD/VOB/MPG/MOV/VIV/FLI/RM/NUV/NET) to other
 MPlayer-playable formats. It can encode with various codecs, like DivX4
 (1 or 2 passes), libavcodec, PCM/MP3/VBRMP3 audio. Also has stream
 copying and video resizing capabilities.


- `ip-xfrm`: transform configuration
- `metacity`:  lightweight GTK window manager
 Metacity is a small window manager, using GTK to do everything.
 .
 As the author says, metacity is a "Boring window manager for the adult in
 you. Many window managers are like Marshmallow Froot Loops; Metacity is
 like Cheerios."
 .
 This package contains the core binaries.


- `metacity-message`: a command to send a message to Metacity
- `metacity-theme-viewer`: view metacity themes
- `metacity-window-demo`: demo of window features
- `mformat`: add an MSDOS filesystem to a low-level formatted floppy disk
- `midori`: fast and lightweight web browser
- `xdg-open`: opens a file or URL in the user (Aqs preferred application
- `mimeopen.`: Open files by mimetype
- `mimetype.`: Determine file type
- `min12xxw`: Convert pbmraw streams to Minolta PagePro 12xxW languages
- `xdg-screensaver`: command line tool for controlling the screensaver
- `minfo`: print the parameters of a MSDOS filesystem
- `mintstick`:  USB stick formatter and ISO image writer
 GUI tool to write .img or .iso files to a USB Key. It can also format them.
 .
 This software is developed by Linux Mint.


- `mii-tool`: view, manipulate media-independent interface status
- `medusa`:  fast, parallel, modular, login brute-forcer for network services
 Medusa is intended to be a speedy, massively parallel, modular, login
 brute-forcer. The goal is to support as many services which allow remote
 authentication as possible. The author considers following items as some of
 the key features of this application:
      * Thread-based parallel testing. Brute-force testing can be
        performed against multiple hosts, users or passwords
        concurrently.
      * Flexible user input. Target information (host/user/password) can
        be specified in a variety of ways. For example, each item can be
        either a single entry or a file containing multiple entries.
        Additionally, a combination file format allows the user to
        refine their target listing.
      * Modular design. Each service module exists as an
        independent .mod file. This means that no modifications are
        necessary to the core application in order to extend the
        supported list of services for brute-forcing.


- `xditview`: display ditroff output
- `xdpyinfo`: display information utility for X
- `mkdiskimage`: Create a blank MS-DOS formatted hard disk image
- `make-ssl-cert`: Debconf wrapper for openssl
- `mandb`: create or update the manual page index caches
- `mc`:  Midnight Commander - a powerful file manager
 GNU Midnight Commander is a text-mode full-screen file manager. It
 uses a two panel interface and a subshell for command execution. It
 includes an internal editor with syntax highlighting and an internal
 viewer with support for binary files. Also included is Virtual
 Filesystem (VFS), that allows files on remote systems (e.g. FTP, SSH
 servers) and files inside archives to be manipulated like real files.


- `mdk3`:  Wireless attack tool for IEEE 802.11 networks
 MDK is a proof-of-concept tool to exploit common
 IEEE 802.11 (Wi-Fi) protocol weaknesses.
 Features:
   * Bruteforce MAC Filters.
   * Bruteforce hidden SSIDs (some small SSID wordlists included).
   * Probe networks to check if they can hear you.
   * Intelligent Authentication-DoS to freeze APs (with success checks).
   * FakeAP - Beacon Flooding with channel hopping (can crash NetStumbler and
     some buggy drivers)
   * Disconnect everything (aka AMOK-MODE) with Deauthentication and
     Disassociation packets.
   * WPA TKIP Denial-of-Service.
   * WDS Confusion - Shuts down large scale multi-AP installations.


- `mdb-sql`: SQL interface to MDB Tools
- `mfterm`:  Terminal for working with Mifare Classic 1-4k Tags
 mfterm is a terminal interface for working with Mifare Classic tags.
 Tab completion on commands is available. Also, commands that have file name
 arguments provide tab completion on files. There is also a command history,
 like in most normal shells.


- `mcookie`: generate magic cookies for xauth
- `mkdosfs`: create an MS-DOS filesystem under Linux
- `mapscrn`: load screen output mapping table
- `mkfs.fat`: create an MS-DOS filesystem under Linux
- `md5sum`: compute and check MD5 message digest
- `mkfs.cramfs`: make compressed ROM file system
- `mkfs.exfat`: create an exFAT file system
- `mkmanifest`: makes list of file names and their DOS 8+3 equivalent
- `mimetype`: Determine file type
- `xdriinfo`: query configuration information of DRI drivers
- `xedit`: simple text editor for X
- `mkfs.ntfs`: create an NTFS file system
- `mkdir`: make directories
- `mkfs.vfat`: create an MS-DOS filesystem under Linux
- `mkfs.minix`: make a Minix filesystem
- `mesg`: permit or deny messages
- `mdadm`:  tool for managing Linux MD devices (software RAID)
 The mdadm tool is used to create, manage, and monitor Linux MD (software
 RAID) devices.
 .
 This package configures mdadm to by default assemble arrays automatically
 during the system startup process.


- `mlabel`: make an MSDOS volume label
- `mke2fs`: create an ext2/ext3/ext4 filesystem
- `Xephyr`: X server outputting to a window on a pre-existing X display
- `xev`: print contents of X events
- `xdg-icon-resource`: command line tool for (un)installing icon resources
- `mkfs.xfs`: construct an XFS filesystem
- `mmd`: make an MSDOS subdirectory
- `mmount`: mount an MSDOS disk
- `mmove`: move or rename an MSDOS file or subdirectory
- `mk_modmap`: translate a Linux keytable file into an xmodmap file
- `mkntfs`: create an NTFS file system
- `xdg-mime`: command line tool for querying information about file type handling and adding descriptions for new file types
- `mkinitramfs`: low-level tool for generating an initramfs image
- `mkzftree`: Create a zisofs/RockRidge compressed file tree
- `mogrify.im6`: resize an image, blur, crop, despeckle, dither, draw on, flip, join, re-sample, and much more. Mogrify overwrites the original image file, whereas, convert(1) writes to a different image file.
- `mono`: Mono's ECMA-CLI native code generator (Just-in-Time and Ahead-of-Time)
- `mklost+found`: create a lost+found directory on a mounted Linux second extended file system
- `mkfontdir`: create an index of X font files in a directory
- `xfs_check`: check XFS filesystem consistency
- `mkhomedir_helper`: Helper binary that creates home directories
- `mknod`: make block or character special files
- `mmcli`: Control and monitor the ModemManager
- `time`:  GNU time program for measuring CPU resource usage
 The 'time' command runs another program, then displays information
 about the resources used by that program, collected by the system while
 the program was running.  You can select which information is reported
 and the format in which it is shown, or have 'time' save the information
 in a file instead of display it on the screen.
 .
 The resources that 'time' can report on fall into the general
 categories of time, memory, I/O, and IPC calls.
 .
 The GNU version can format the output in arbitrary ways by using a
 printf-style format string to include various resource measurements.


- `mksmbpasswd`: formats a /etc/passwd entry for a smbpasswd file
- `mkswap`: set up a Linux swap area
- `mountall`: Mount filesystems during boot
- `mktemp`: create a temporary file or directory
- `mkfontscale`: create an index of scalable font files for X
- `xdg-settings`: get various settings from the desktop environment
- `mpartition`: partition an MSDOS hard disk
- `steghide`:  steganography hiding tool
 Steghide is steganography program which hides bits of a data file
 in some of the least significant bits of another file in such a way
 that the existence of the data file is not visible and cannot be proven.
 .
 Steghide is designed to be portable and configurable and features hiding
 data in bmp, jpeg, wav and au files, blowfish encryption, MD5 hashing of
 passphrases to blowfish keys, and pseudo-random distribution of hidden bits
 in the container data.
 .
 Steghide is useful in digital forensics investigations.


- `wpa_passphrase`: Generate a WPA PSK from an ASCII passphrase for a SSID
- `kill`: send signal to a process
- `wpa_supplicant`: Wi-Fi Protected Access client and IEEE 802.1X supplicant
- `mrd`: remove an MSDOS subdirectory
- `xfs_admin`: change parameters of an XFS filesystem
- `mren`: rename an existing MSDOS file
- `mscompress`:  Microsoft "compress.exe/expand.exe" compatible (de)compressor
 This package contains two programs:
 .
  * msexpand which decompresses files compressed by the Microsoft
    compress.exe utility (e.g. Win 3.x installation files);
  * mscompress which compresses files using the LZ77 compression
    algorithm.
 .
 Files can be decompressed using Microsoft expand.exe or msexpand(1).


- `msexpand`: decompress data compressed using mscompress(1) or COMPRESS.EXE
- `mmroff`: cross-reference preprocessor for GNU roff mm macro package    nr mmroff_C  [.C] 0
- `mogrify`: resize an image, blur, crop, despeckle, dither, draw on, flip, join, re-sample, and much more. Mogrify overwrites the original image file, whereas, convert(1) writes to a different image file.
- `mount.ecryptfs_private`: eCryptfs private mount helper.
- `mountpoint`: see if a directory or file is a mountpoint
- `mousetweaks`:  mouse accessibility enhancements for the GNOME desktop
 This package contains a daemon and some panel applets to improve mouse
 usability on the GNOME desktop. These enhancements are:
 .
  * The possibility to click without a button
  * The ability to bring the context menu with a one-button mouse
    (like MacOS does)
  * An area to capture the mouse pointer until it is released with a
    pre-defined key combination.


- `xfs_bmap`: print block mapping for an XFS file
- `msgattrib`: attribute matching and manipulation on message catalog
- `msgcat`: combines several message catalogs
- `msgcmp`: compare message catalog and template
- `msgcomm`: match two message catalogs
- `xfs_copy`: copy the contents of an XFS filesystem
- `msgconv`: character set conversion for message catalog
- `msgen`: create English message catalog
- `msgexec`: process translations of message catalog
- `xfs_db`: debug an XFS filesystem
- `msgfilter`: edit translations of message catalog
- `msgfmt`: compile message catalog to binary format
- `mshowfat`: shows FAT clusters allocated to file
- `xfs_estimate`: estimate the space that an XFS filesystem will take
- `montage`:  Toolkit for assembling FITS images into mosaics
 Montage is a toolkit for assembling astronomical images into custom mosaics.
 .
 It uses algorithms that preserve the calibration and positional (astrometric)
 fidelity of the input images to deliver mosaics that meet user-specified
 parameters of projection, coordinates, and spatial scale. It supports all
 projections and coordinate systems in use in astronomy.
 .
 It contains independent modules for analyzing the geometry of images on the
 sky, and for creating and managing mosaics; these modules are powerful tools
 in their own right and have applicability outside mosaic production, in areas
 such as data validation.


- `mtools`:  Tools for manipulating MSDOS files
 Mtools is a collection of utilities to access MS-DOS disks from Unix without
 mounting them. It supports Win'95 style long file names, OS/2 Xdf disks,
 ZIP/JAZ disks and 2m disks (store up to 1992kB on a high density 3 1/2 disk).
 .
 Also included in this package are commands to eject and manipulate the
 write/password protection control of Zip disks.


- `mtoolstest`: tests and displays the configuration
- `mtr`:  Full screen ncurses and X11 traceroute tool
 mtr combines the functionality of the 'traceroute' and 'ping' programs
 in a single network diagnostic tool.
 .
 As mtr starts, it investigates the network connection between the host
 mtr runs on and a user-specified destination host.  After it
 determines the address of each network hop between the machines,
 it sends a sequence of ICMP ECHO requests to each one to determine the
 quality of the link to each machine.  As it does this, it prints
 running statistics about each machine.


- `ischroot`: detect if running in a chroot
- `mtype`: display contents of an MSDOS file
- `muffin`:  window and compositing manager
 Muffin is a window manager performing compositing as well based on
 GTK+ and Clutter and used in Cinnamon desktop environment.
 .
 This package contains the core binaries.


- `muffin-message`: a command to send a message to Muffin
- `muffin-theme-viewer`: view muffin themes
- `muffin-window-demo`: demo of window features
- `more`: display files on a page-by-page basis
- `mxtar`: Wrapper for using GNU tar directly from a floppy disk
- `mpstat`: Report processors related statistics.
- `mzip`: change protection mode and eject disk on Zip/Jaz drive
- `msggrep`: pattern matching on message catalog
- `mkreiserfs`: The create tool for the Linux ReiserFS filesystem.
- `mt-gnu`: control magnetic tape drive operation
- `xfs_freeze`: suspend access to an XFS filesystem
- `nc_openbsd`: arbitrary TCP and UDP connections and listens
- `msginit`: initialize a message catalog
- `nasm`:  General-purpose x86 assembler
 Netwide Assembler.  NASM will currently output flat-form binary files,
 a.out, COFF and ELF Unix object files, and Microsoft 16-bit DOS and
 Win32 object files.
 .
 Also included is NDISASM, a prototype x86 binary-file disassembler
 which uses the same instruction table as NASM.
 .
 NASM is released under the 2-clause BSD license.


- `nc`: TCP/IP swiss army knife
- `ndiswrapper`: install/modify/remove ndis driver (wrapper)
- `ndiswrapper-1.9`: Linux kernel module and user space tool to load and run Windows XP drivers for wireless cards
- `nemo`:  File manager and graphical shell for Cinnamon
 Nemo is the official file manager for the Cinnamon desktop. It allows one
 to browse directories, preview files and launch applications associated
 with them. It is also responsible for handling the icons on the Cinnamon
 desktop. It works on local and remote filesystems.
 .
 Several icon themes and components for viewing different kinds of files
 are available in separate packages.


- `nemo-connect-server`: To Access a remote server
- `ncal`:  display a calendar and the date of Easter
 This package contains the "ncal" program and the traditional "cal"
 program, both are commonly found on BSD-style systems. This utility displays a
 simple calendar in a traditional or an alternative and more advanced layout,
 and the date of Easter.


- `ncrack`:  High-speed network authentication cracking tool
 Ncrack is a high-speed network authentication cracking tool.
 It was built to help companies secure their networks by
 proactively testing all their hosts and networking devices
 for poor passwords. Security professionals also rely on
 Ncrack when auditing their clients. Ncrack was designed
 using a modular approach, a command-line syntax similar to
 Nmap and a dynamic engine that can adapt its behaviour
 based on network feedback. It allows for rapid, yet
 reliable large-scale auditing of multiple hosts.
 .
 Ncrack's features include a very flexible interface granting
 the user full control of network operations, allowing for
 very sophisticated bruteforcing attacks, timing templates
 for ease of use, runtime interaction similar to Nmap's and
 many more. Protocols supported include RDP, SSH, http(s),
 SMB, pop3(s), VNC, FTP, and telnet.
 .
 Be sure to read the Ncrack man page (https://nmap.org/ncrack/man.html)
 to fully understand Ncrack usage.


- `mysql`: the MariaDB command-line tool
- `mysqldump`: a database backup program
- `namei`: follow a pathname until a terminal point is found
- `mount.vboxsf`: x86 virtualization solution
- `nano`:  small, friendly text editor inspired by Pico
 GNU nano is an easy-to-use text editor originally designed as a replacement
 for Pico, the ncurses-based editor from the non-free mailer package Pine
 (itself now available under the Apache License as Alpine).
 .
 However, GNU nano also implements many features missing in Pico, including:
  - undo/redo
  - line numbering
  - syntax coloring
  - soft-wrapping of overlong lines
  - selecting text by holding Shift
  - interactive search and replace (with regular expression support)
  - a go-to line (and column) command
  - support for multiple file buffers
  - auto-indentation
  - tab completion of filenames and search terms
  - toggling features while running
  - and full internationalization support


- `nameif`: name network interfaces based on MAC addresses
- `ncurses5-config`: helper script for ncurses libraries
- `netdiscover`:  active/passive network address scanner using ARP requests
 Netdiscover is an active/passive address reconnaissance tool, mainly
 developed for those wireless networks without dhcp server, when you
 are wardriving. It can be also used on hub/switched networks.
 .
 Built on top of libnet and libpcap, it can passively detect online
 hosts, or search for them, by actively sending ARP requests.
 .
 Netdiscover can also be used to inspect your network ARP traffic,
 or find network addresses using auto scan mode, which will scan for
 common local networks.
 .
 Netdiscover uses the OUI table to show the vendor of the each MAC
 address discovered and is very useful for security checks or in
 pentests.


- `xfs_fsr`: filesystem reorganizer for XFS
- `netcat`: TCP/IP swiss army knife
- `ncursesw5-config`: helper script for ncurses libraries
- `xfs_growfs`: expand an XFS filesystem
- `manpath`: format of the /etc/man_db.conf file
- `nlmconv`: converts object code into an NLM.
- `ngrep`:  grep for network traffic
 ngrep strives to provide most of GNU grep's common features,
 applying them to the network layer.  ngrep is a pcap-aware tool that
 will allow you to specify extended regular expressions to match
 against data payloads of packets.  It currently recognizes TCP, UDP
 and ICMP across Ethernet, PPP, SLIP and null interfaces, and
 understands bpf filter logic in the same fashion as more common
 packet sniffing tools, such as tcpdump and snoop.


- `gnome-terminal`:  GNOME terminal emulator application
 GNOME Terminal is a terminal emulation application that you can use to
 perform the following actions:
  - Access a UNIX shell in the GNOME environment.
  - Run any application that is designed to run on VT102, VT220, and xterm
 terminals.
 .
 GNOME Terminal features the ability to use multiple terminals in a single
 window (tabs) and profiles support.


- `newusers`: update and create new users in batch
- `nologin`: politely refuse a login
- `nikto`:  web server security scanner
 Nikto is a pluggable web server and CGI scanner written in Perl, using
 rfp's LibWhisker to perform fast security or informational checks.
 .
 Features:
  - Easily updatable CSV-format checks database
  - Output reports in plain text or HTML
  - Available HTTP versions automatic switching
  - Generic as well as specific server software checks
  - SSL support (through libnet-ssleay-perl)
  - Proxy support (with authentication)
  - Cookies support


- `nm-tool`: utility to report NetworkManager state and devices
- `netstat`: Print network connections, routing tables, interface statis‐
   tics, masquerade connections, and multicast memberships
- `netsniff-ng`:  Linux network packet sniffer toolkit
 netsniff-ng is a high performance Linux network sniffer for packet inspection.
 It can be used for protocol analysis, reverse engineering or network
 debugging. The gain of performance is reached by 'zero-copy' mechanisms, so
 that the kernel does not need to copy packets from kernelspace to userspace.
 .
 netsniff-ng toolkit currently consists of the following utilities:
 .
  * netsniff-ng: a zero-copy packet analyzer, pcap capturing/replaying tool
  * trafgen: a multithreaded low-level zero-copy network packet generator
  * mausezahn: high-level packet generator for appliances with Cisco-CLI
  * ifpps: a top-like kernel networking and system statistics tool
  * curvetun: a lightweight curve25519-based multiuser IP tunnel
  * astraceroute: an autonomous system trace route and DPI testing utility
  * flowtop: a top-like netfilter connection tracking tool
  * bpfc: a [seccomp-]BPF (Berkeley packet filter) compiler, JIT disassembler


- `newgrp`: change to a new group
- `modinfo`: Show information about a Linux Kernel module
- `nm-applet`: network monitor and control GUI applet
- `neqn`: format equations for ASCII output
- `nfnl_osf`: OS fingerprint loader utility
- `nfsiostat`: Emulate iostat for NFS mount points using /proc/self/mountstats
- `nmblookup`: NetBIOS over TCP/IP client used to lookup NetBIOS names
- `nseq.1s`: create or examine a netscape certificate sequence
- `nm-online`: ask NetworkManager whether the network is connected
- `nginx`:  small, powerful, scalable web/proxy server
 Nginx ("engine X") is a high-performance web and reverse proxy server
 created by Igor Sysoev. It can be used both as a standalone web server
 and as a proxy to reduce the load on back-end HTTP or mail servers.


- `nmtui`: Text User Interface for controlling NetworkManager
- `nohup`: invoke a utility immune to hangups
- `ntfs-3g.secaudit`: NTFS Security Data Auditing
- `ntfs-3g.usermap`: NTFS Building a User Mapping File
- `nokogiri`: an HTML, XML, SAX, and Reader parser
- `net`: Tool for administration of Samba and remote CIFS servers .
- `notify-send`: a program to send desktop notifications
- `nslookup`: query Internet name servers interactively
- `nm`: write the name list of an object file (   DEVELOPMENT  )
- `nproc`: print the number of processing units available
- `nmbd`: NetBIOS name server to provide NetBIOS over IP naming services
   to clients
- `nsupdate`: Dynamic DNS update utility
- `mount.ecryptfs`: eCryptfs mount helper.
- `ntfslabel`: display/change the label on an ntfs file system
- `mount.cifs`: mount using the Common Internet File System (CIFS)
- `ntfs-3g.probe`: Probe an NTFS volume mountability
- `ntpdate`:  Network Time Protocol client (transitional package)
 This is a dummy transitional package to transition to NTPsec.
 It can be safely removed.


- `ntpdate-debian`: set the date and time via NTP
- `nmcli`: command -line tool for controlling NetworkManager
- `oakdecode`: Decode an OAKT printer stream into human readable form.
- `obex-data-server`: D-Bus service providing OBEX functionality
- `ntfscat`: print NTFS files and streams on the standard output
- `ntfsclone`: Efficiently clone, image, restore or rescue an NTFS
- `ntfscp`: copy file to an NTFS volume.
- `ocsp.1s`: Online Certificate Status Protocol utility
- `ntfscmp`: compare two NTFS filesystems and tell the differences
- `odbcinst`:  Helper program for accessing ODBC configuration files
 UnixODBC is an implementation of the Open Database Connectivity standard,
 a database abstraction layer that allows applications to be used with
 many different relational databases by way of a single library.
 .
 This package contains the odbcinst helper tool, which allows ODBC driver
 packages to install and manage their driver configuration.


- `ods-server`: minimal OBEX server based on obex-data-server
- `objcopy`: copy and translate object files
- `omshell`: OMAPI Command Shell
- `ntfs-3g`:  read/write NTFS driver for FUSE
 NTFS-3G uses FUSE (Filesystem in Userspace) to provide support for the NTFS
 filesystem used by Microsoft Windows.


- `xfs_io`: debug the I/O path of an XFS filesystem
- `xfs_logprint`: print the log of an XFS filesystem
- `openshot`: Non-Linear Video Editor
- `openshot-render`: OpenShot command line renderer
- `openssh-server`:  secure shell (SSH) server, for secure access from remote machines
 This is the portable version of OpenSSH, a free implementation of
 the Secure Shell protocol as specified by the IETF secsh working
 group.
 .
 Ssh (Secure Shell) is a program for logging into a remote machine
 and for executing commands on a remote machine.
 It provides secure encrypted communications between two untrusted
 hosts over an insecure network. X11 connections and arbitrary TCP/IP
 ports can also be forwarded over the secure channel.
 It can be used to provide applications with a secure communication
 channel.
 .
 This package provides the sshd server.
 .
 In some countries it may be illegal to use any encryption at all
 without a special permit.
 .
 sshd replaces the insecure rshd program, which is obsolete for most
 purposes.


- `openssl.1s`: OpenSSL command line tool
- `oclock`: round X clock
- `opldecode`: Decode a Raster Object (opl) stream into human readable form.
- `xfs_mdrestore`: restores an XFS metadump image to a filesystem image
- `ntfsfix`: fix common errors and force Windows to check NTFS
- `od`: dump files in various formats
- `openvpn`:  virtual private network daemon
 OpenVPN is an application to securely tunnel IP networks over a
 single UDP or TCP port. It can be used to access remote sites, make
 secure point-to-point connections, enhance wireless security, etc.
 .
 OpenVPN uses all of the encryption, authentication, and certification
 features provided by the OpenSSL library (any cipher, key size, or
 HMAC digest).
 .
 OpenVPN may use static, pre-shared keys or TLS-based dynamic key exchange. It
 also supports VPNs with dynamic endpoints (DHCP or dial-up clients), tunnels
 over NAT or connection-oriented stateful firewalls (such as Linux's iptables).


- `on_ac_power`: test whether computer is running on AC power
- `numfmt`: Convert numbers from/to human-readable strings
- `p7zip`:  transitional package
 This is a transitional package. It can be safely removed.


- `ntfsresize`: resize an NTFS filesystem without data loss
- `ntfsls`: list directory contents on an NTFS filesystem
- `paccache`: flexible pacman cache cleaning utility
- `pam_ck_connector`: Register session with ConsoleKit
- `pacman`:  Chase Monsters in a Labyrinth
 You are Pacman, and you are supposed to eat all the small dots to get to
 the next level. You are also supposed to keep away from the ghosts,
 if they take you, you lose one life, unless you have eaten a large dot,
 then you can, for a limited amount of time, chase and eat the ghosts.
 There is also bonus available, for a limited amount of time.
 An X gives just points, but a little pacman gives an extra life.


- `pam_access`: PAM module for logdaemon style login access control
- `pam_debug`: PAM module to debug the PAM stack
- `pam_deny`: The locking -out PAM module
- `pam_echo`: PAM module for printing text messages
- `pam_ecryptfs`: PAM module for eCryptfs
- `pam_env`: PAM module to set/unset environment variables
- `pam_exec`: PAM module which calls an external command
- `pam_faildelay`: Change the delay on failure per -application
- `arecordmidi`: record Standard MIDI Files
- `pam_filter`: PAM filter module
- `pam_ftp`: PAM module for anonymous access module
- `pam_group`: PAM module for group access
- `pam_issue`: PAM module to add issue file to user prompt
- `pam_keyinit`: Kernel session keyring initialiser module
- `pam_lastlog`: PAM module to display date of last login and perform inactive account lock out
- `pam_limits`: PAM module to limit resources
- `pam_listfile`: deny or allow services based on an arbitrary file
- `pam_localuser`: require users to be listed in /etc/passwd
- `pam_loginuid`: Record user (Aqs login uid to the process attribute
- `pam_mail`: Inform about available mail
- `pam_mkhomedir`: PAM module to create users home directory
- `pam_motd`: Display the motd file
- `pam_namespace`: PAM module for configuring namespace for a session
- `pam_nologin`: Prevent non -root users from login
- `pam_permit`: The promiscuous module
- `pam_pwhistory`: PAM module to remember last passwords
- `pam_rhosts`: The rhosts PAM module
- `pam_selinux`: PAM module to set the default security context
- `pam_sepermit`: PAM module to allow/deny login depending on SELinux enforcement state
- `pam_rootok`: Gain only root access
- `pam_securetty`: Limit root login to special devices
- `pam_shells`: PAM module to check for valid login shell
- `modprobe`: Add and remove modules from the Linux Kernel
- `p0f`:  Passive OS fingerprinting tool
 p0f performs passive OS detection based on SYN packets. Unlike nmap
 and queso, p0f does recognition without sending any data.
 Additionally, it is able to determine the distance to the remote
 host, and can be used to determine the structure of a foreign or
 local network. When running on the gateway of a network it is able
 to gather huge amounts of data and provide useful statistics. On a
 user-end computer it could be used as powerful IDS add-on. p0f
 supports full tcpdump-style filtering expressions, and has an
 extensible and detailed fingerprinting database.


- `pam_tally`: The login counter (tallying) module
- `pam_tally2`: The login counter (tallying) module
- `packetforge-ng`: forge packets: ARP, UDP, ICMP or custom packets.
- `pam_tty_audit`: Enable or disable TTY auditing for specified users
- `pam_timestamp`: Authenticate using cached successful authentication attempts
- `pam_timestamp_check`: Check to see if the default timestamp is valid
- `pam_userdb`: PAM module to authenticate against a db database
- `pam_umask`: PAM module to set the file mode creation mask
- `pam_unix`: Module for traditional password authentication
- `pam_warn`: PAM module which logs all PAM items if called
- `panel-test-applets`: display installed applets
- `ownership`: Compaq ownership tag retriever
- `p11-kit`:  p11-glue utilities
 The p11-kit library provides a way to load and enumerate Public-Key
 Cryptography Standard #11 modules, along with a standard configuration
 setup for installing PKCS#11 modules so that they're discoverable. It
 also solves problems with coordinating the use of PKCS#11 by different
 components or libraries living in the same process.
 .
 This package contains the p11-kit tool for listing PKCS#11 modules.


- `ntfsundelete`: recover a deleted file from an NTFS volume.
- `paprefs`:  PulseAudio Preferences
 PulseAudio, previously known as Polypaudio, is a sound server for POSIX and
 WIN32 systems. It is a drop in replacement for the ESD sound server with
 much better latency, mixing/re-sampling quality and overall architecture.
 .
 PulseAudio Preferences (paprefs) is a simple GTK+ based configuration dialog
 for the PulseAudio sound server.


- `parsechangelog.`: parse Debian changelogs and output them in other formats
- `pam-auth-update`: manage PAM configuration using packaged profiles
- `pacmd`: Reconfigure a PulseAudio sound server during runtime
- `pam_getenv`: get environment variables from /etc/environment
- `pactl`: Control a running PulseAudio sound server
- `passwd.1s`: compute password hashes
- `pam_systemd`: Register user sessions in the systemd login manager
- `paperconf`: print paper configuration information
- `pam_time`: PAM module for time control access
- `paperconfig`: configure the system default paper size
- `xfs_metadump`: copy XFS filesystem metadata to a file
- `openvt`: start a program on a new virtual terminal (VT).
- `pccardctl`: PCMCIA card control utility lspcmcia
- `xfsinfo`: X font server information utility
- `pcimodules`: List kernel driver modules available for all currently plugged in PCI devices
- `pam_wheel`: Only permit root access to members of group wheel
- `pdb3.4`: the Python debugger
- `pam_xauth`: PAM module to forward xauth keys between users
- `pkcheck`: Check whether a process is authorized
- `pasuspender`: Temporarily suspend PulseAudio
- `pkaction`: Get details about a registered action
- `pdfedit`: Editor for PDF files
- `paste`: merge corresponding or subsequent lines of files
- `pdb2.7`: the Python debugger
- `pdbedit`: manage the SAM database (Database of Samba Users)
- `pax11publish`: PulseAudio X11 Credential Utility
- `pdf2dsc`: generate a PostScript page list of a PDF document
- `pathchk`: check pathnames
- `pax`:  Portable Archive Interchange (cpio, pax, tar)
 paxtar is an implementation of an archiving utility that reads
 and writes several formats - traditional ones, the extended
 formats specified in IEEE 1003.1, and the ar(5) format used
 by deb(5) packages (MirBSD specific paxtar extension). The
 pax interface was designed by IEEE 1003.2 as a compromise in
 the chronic controversy over which of tar or cpio is best, but
 this implementation offers paxcpio and paxtar for easy calling.
 .
 This is the MirBSD paxtar implementation supporting the formats
 ar, bcpio, cpio, SVR4 cpio with and without CRC, old tar, and
 ustar, but not the format known as pax yet. It has extensions
 for removing non-numerical user and group IDs from the archive,
 storing hardlinked files only once, setting ownership to the
 superuser, anonymising inode and device information, changing
 the mtime to zero, and producing GNU tar compatible trailing
 slashes on ustar directory nodes. Its "ar" format is suitable
 for operating on *.deb files, unlike that of GNU binutils.
 .
 Note that ACLs and Extended Attributes are not supported.


- `pdffonts`: Portable Document Format (PDF) font analyzer (version 3.03)
- `pdfimages`: Portable Document Format (PDF) image extractor (version 3.03)
- `pdf2ps`: Ghostscript PDF to PostScript translator
- `pdfdetach`: Portable Document Format (PDF) document embedded file extractor (version 3.03)
- `pdfinfo`: Portable Document Format (PDF) document information extractor (version 3.03)
- `pdfmom`: produce PDF documents using the mom macro package for groff
- `xeyes`: a follow the mouse X demo
- `xfd`: display all the characters in an X font
- `pdfroff`: create PDF documents using groff    nr pdfroff_C  [.C] 0                           pdfmark
- `pdfseparate`: Portable Document Format (PDF) page extractor
- `pdftocairo`: Portable Document Format (PDF) to PNG/JPEG/TIFF/PDF/PS/EPS/SVG using cairo
- `xfs_mkfile`: create an XFS file
- `java`: Launches a Java application .
- `less`:  pager program similar to more
 This package provides "less", a file pager (that is, a memory-efficient
 utility for displaying text one screenful at a time). Less has many
 more features than the basic pager "more". As part of the GNU project,
 it is widely regarded as the standard pager on UNIX-derived systems.
 .
 Also provided are "lessecho", a simple utility for ensuring arguments
 with spaces are correctly quoted; "lesskey", a tool for modifying the
 standard (vi-like) keybindings; and "lesspipe", a filter for specific
 types of input, such as .doc or .txt.gz files.


- `lex`: generate programs for lexical tasks (   DEVELOPMENT  )
- `pg`: browse pagewise through text files
- `pdftohtml`: program to convert PDF files into HTML, XML and PNG images
- `peekfd`: peek at file descriptors of running processes
- `perl`:  Larry Wall's Practical Extraction and Report Language
 Perl is a highly capable, feature-rich programming language with over
 20 years of development. Perl 5 runs on over 100 platforms from
 portables to mainframes. Perl is suitable for both rapid prototyping
 and large scale development projects.
 .
 Perl 5 supports many programming styles, including procedural,
 functional, and object-oriented. In addition to this, it is supported
 by an ever-growing collection of reusable modules which accelerate
 development. Some of these modules include Web frameworks, database
 integration, networking protocols, and encryption. Perl provides
 interfaces to C and C++ for custom extension development.


- `perlbug`: how to submit bug reports on Perl
- `phar`: PHAR (PHP archive) command line tool
- `php`:  server-side, HTML-embedded scripting language (default)
 PHP (recursive acronym for PHP: Hypertext Preprocessor) is a widely-used
 open source general-purpose scripting language that is especially suited
 for web development and can be embedded into HTML.
 .
 This package is a dependency package, which depends on latest stable
 PHP version (currently 8.2).


- `perf`: performance analysis tools for Linux
- `pic`: compile pictures for troff or TeX
- `perlivp`: Perl Installation Verification Procedure
- `xfontsel`: point and click selection of X11 font names
- `xidel`: is a command line tool to download and extract data from HTML/XML pages.
- `pam_succeed_if`: test account characteristics
- `pico`: Nano's ANOther editor, inspired by Pico
- `ping6`: send ICMP ECHO_REQUEST to network hosts
- `pkcs12.1s`: PKCS#12 file utility
- `pkcs7.1s`: PKCS#7 utility
- `pkcs8.1s`: PKCS#8 format private key conversion tool
- `piconv`: iconv(1), reinvented in perl
- `pkey.1s`: public or private key processing tool
- `pkeyparam.1s`: public key algorithm parameter processing tool
- `pkeyutl.1s`: public key algorithm utility
- `pip3`: A tool for installing and managing Python packages
- `pklocalauthority`: PolicyKit Local Authority
- `pip`: A tool for installing and managing Python packages
- `pkexec`:  run commands as another user with polkit authorization
 polkit is an application-level toolkit for defining and handling the policy
 that allows unprivileged processes to speak to privileged processes.
 It was previously named PolicyKit.
 .
 pkexec is a setuid program to allow certain users to run commands as
 root or as a different user, similar to sudo. Unlike sudo, it carries
 out authentication and authorization by sending a request to polkit,
 so it uses desktop environments' familiar prompting mechanisms for
 authentication and uses polkit policies for authorization decisions.
 .
 By default, members of the 'sudo' Unix group can use pkexec to run any
 command after authenticating. The authorization rules can be changed by
 the local system administrator.
 .
 If this functionality is not required, removing the pkexec package will
 reduce security risk by removing a setuid program.


- `play`: Sound eXchange, the Swiss Army knife of audio manipulation
- `pkg-config`:  manage compile and link flags for libraries (transitional package)
 pkgconf is an implementation of the pkg-config system, which helps to configure
 compiler and linker flags for development frameworks.
 .
 pkgconf is a replacement for pkg-config, providing additional functionality
 while also maintaining compatibility.
 .
 This package only provides a dependency link to the pkgconf package to help
 with package upgrades. It can be safely removed.


- `padsp`: PulseAudio OSS Wrapper
- `pm-action`: Suspend or Hibernate your computer
- `pm-is-supported`: Test whether suspend or hibernate is supported.
- `pm-powersave`: Put your computer into low power mode
- `pdftotext`: Portable Document Format (PDF) to text converter (version 3.03)
- `pnm2ppa`: convert portable anymap (PNM) images to HP's PPA printer format.
- `pidof`: find the process ID of a running program.
- `pod2latex.`: convert pod documentation to latex format
- `pod2latex.bundled`: convert pod documentation to latex format
- `pinky`: lightweight finger
- `pgrep`: look up or signal processes based on name and other at‐
   tributes
- `nice`: change process priority
- `preconv`: convert encoding of input files to something GNU troff    understands    nr preconv_C  [.C] 0
- `pkttyagent`: Textual authentication helper
- `pivot_root`: change the root filesystem
- `pkgdelta`: package delta generation utility
- `xfs_quota`: manage use of quota on XFS filesystems
- `prezip`: bin  -prefix zip delta word list compressor/decompressor
- `xinput`:  Runtime configuration and test of XInput devices
 Xinput is an utility for configuring and testing XInput
 devices.


- `pidstat`: Report statistics for Linux tasks.
- `pod2man`: Convert POD data to formatted *roff input
- `pidgin`:  graphical multi-protocol instant messaging client
 Pidgin is a graphical, modular instant messaging client capable of using
 multiple networks at once.  Currently supported out of the box are:
 Jabber/XMPP, Bonjour, Gadu-Gadu, IRC, Novell GroupWise Messenger, Lotus
 Sametime, SIMPLE, and Zephyr. It can support many more with plugins.
 .
 Some extra packages are suggested to use increased functionality:
  * libsqlite3-0:
    - To use Contact Availability Prediction plugin


- `poweroff`: Halt, power-off or reboot the machine
- `podchecker`: check the syntax of POD format documentation files
- `podselect`: print selected sections of pod documentation on standard output
- `ppmtolss16`: Convert a PPM to an LSS16 image
- `pppconfig`:  Text menu based utility for configuring ppp
 It provides extensive explanations at each step.  pppconfig supports
 PAP, CHAP, and chat methods of authentication.  It uses the standard
 ppp configuration files and sets ppp up so that the standard pon and
 poff commands can be used to control ppp.
 Some features supported by pppconfig are:
  - Multiple ISPs with separate nameservers.
  - Modem detection.
  - Dynamic DNS.
  - Dial on demand.


- `parted`:  disk partition manipulator
 GNU Parted is a program that allows you to create, destroy, resize,
 move, and copy disk partitions. This is useful for creating space
 for new operating systems, reorganizing disk usage, and copying data
 to new hard disks.
 .
 This package contains the binary and manual page. Further
 documentation is available in parted-doc.
 .
 Parted currently supports DOS, Mac, Sun, BSD, GPT, MIPS, and PC98
 partitioning formats, as well as a "loop" (raw disk) type which
 allows use on RAID/LVM. It can detect and remove ASFS/AFFS/APFS,
 Btrfs, ext2/3/4, FAT16/32, HFS, JFS, linux-swap, UFS, XFS, and ZFS
 file systems. Parted also has the ability to create and modify file
 systems of some of these types, but using it to perform file system
 operations is now deprecated.
 .
 The nature of this software means that any bugs could cause massive
 data loss. While there are no such bugs known at the moment, they
 could exist, so please back up all important files before running
 it, and do so at your own risk.


- `pppd-radattr`: RADIUS utility plugin for pppd(8)
- `pppd-radius`: RADIUS authentication plugin for pppd(8)
- `pfbtops`: translate Printer Font Binary files to PostScript ASCII
- `pppoe`:  PPP over Ethernet driver
 PPP over Ethernet (PPPoE) is a protocol used by
 many ADSL Internet service providers. This package allows
 you to connect to those PPPoE service providers.


- `pppoe-connect`: Shell script to manage a PPPoE link
- `ppdc`: cups ppd compiler (deprecated)
- `pppoe-relay`: user-space PPPoE relay agent.
- `pppoe-server`: user-space PPPoE server
- `pppoe-setup`: Shell script to configure Roaring Penguin PPPoE client
- `pppoe-sniff`: examine network for non-standard PPPoE frames
- `pppoe-start`: Shell script to bring up a PPPoE link
- `pppoe-status`: Shell script to report on status of PPPoE link
- `pppoe-stop`: Shell script to shut down a PPPoE link
- `pppoeconf`:  configures PPPoE/ADSL connections
 User-friendly tool for initial configuration of a DSL (PPPoE) connection.


- `ppdhtml`: cups html summary generator (deprecated)
- `pon`: starts up, shuts down or lists the log of PPP connec‐
   tions
- `polkit`: Authorization Manager
- `pldd`: display dynamic shared objects linked into a process
- `xfreerdp`: FreeRDP X11 client
- `xfs_ncheck`: generate pathnames from i-numbers for XFS
- `pkill`: look up or signal processes based on name and other at‐
   tributes
- `prename`: renames multiple files
- `pppd`: Point-to-Point Protocol Daemon
- `pppdump`: convert PPP record file to readable format
- `pppstats`: print PPP statistics
- `pod2text`: Convert POD data to formatted ASCII text
- `qsub`: submit a script
- `printer-profile`: Profile using X-Rite ColorMunki and Argyll CMS
- `pr`: print files
- `pl2pm`: Rough tool to translate Perl4 .pl files to Perl5 .pm modules.
- `xgc`: X graphics demo
- `print`: execute programs via en‐
   tries in the mailcap file
- `protoc`: compile protocol buffer description files
- `ppdmerge`: merge ppd files (deprecated)
- `printerbanner`: print large banner on printer
- `pmap`: report memory map of a process
- `ppdpo`: ppd message catalog generator (deprecated)
- `prezip-bin`: prefix zip delta word list compressor/decompressor
- `profiles`: A utility to report and change SIDs in registry files
- `pod2usage`: print usage messages from embedded pod docs in files
- `printafm`: Print the metrics from a Postscript font in AFM format using ghostscript
- `prtstat`: print statistics of a process
- `printenv`: print all or part of environment
- `printf`: write formatted output
- `ps`: report process status
- `ps2epsi`: generate conforming Encapsulated PostScript
- `ps2pdfwr`: Convert PostScript to PDF without specifying CompatibilityLevel, using ghostscript
- `ps2ps`: Ghostscript PostScript "distiller"
- `pod2html`: convert .pod files to .html files
- `qpdf`:  tools for transforming and inspecting PDF files
 QPDF is a program that can be used to linearize (web-optimize),
 encrypt (password-protect), decrypt, and inspect PDF files from the
 command-line.  It does these and other structural, content-preserving
 transformations on PDF files, reading a PDF file as input and
 creating a new one as output.  It also provides many useful
 capabilities to developers of PDF-producing software or for people
 who just want to look at the innards of a PDF file to learn more
 about how they work.
 .
 QPDF understands PDF files that use compressed object streams
 (supported by newer PDF applications) and can convert such files into
 those that can be read with older viewers.  It can also be used for
 checking PDF files for structural errors, inspecting stream contents,
 or extracting objects from PDF files.  QPDF is not PDF content
 creation or viewing software -- it does not have the capability to
 create PDF files from scratch or to display PDF files.
 .
 This package includes the command-line qpdf tools.


- `psql`: PostgreSQL interactive terminal
- `putty`:  Telnet/SSH client for X
 This is the Unix port of the popular Windows SSH client, PuTTY. It supports
 flexible terminal setup, mid-session reconfiguration using Ctrl-rightclick,
 multiple X11 authentication protocols, and various other interesting things
 not provided by ssh in an xterm.
 .
 Pageant is an SSH authentication agent, and a tool for communicating with
 an already-running agent.


- `pv`:  Shell pipeline element to meter data passing through
 pv (Pipe Viewer) can be inserted into any normal pipeline between two
 processes to give a visual indication of how quickly data is passing through,
 how long it has taken, how near to completion it is, and an estimate of how
 long it will be until completion.
 .
 To use it, insert it in a pipeline between two processes, with the
 appropriate options. Its standard input will be passed through to its
 standard output and progress will be shown on standard error.


- `ppdi`: import ppd files (deprecated)
- `plipconfig`: fine tune PLIP device parameters
- `psfxtable`: handle Unicode character tables for console fonts
- `pstree`: display a tree of processes
- `pppoe-discovery`: perform PPPoE discovery
- `polkitd`:  framework for managing administrative policies and privileges
 polkit is an application-level toolkit for defining and handling the policy
 that allows unprivileged processes to speak to privileged processes.
 It was previously named PolicyKit.
 .
 It is a framework for centralizing the decision making process with respect to
 granting access to privileged operations for unprivileged (desktop)
 applications.
 .
 In a typical use of polkit, an unprivileged application such as gnome-disks
 sends requests via D-Bus or other inter-process communication mechanisms
 to a privileged system service such as udisks, which asks polkitd for
 permission to process those requests. This allows the application to carry
 out privileged tasks without making use of setuid, which avoids several
 common sources of security vulnerabilities.
 .
 This package provides the polkitd D-Bus service and supporting programs.
 The pkexec program is not included, and can be found in the pkexec package.


- `ptargrep`: Apply pattern matching to the contents of files in a tar archive
- `pptp`: PPTP driver
- `pptpsetup`: Point -to -Point Tunneling Protocol setup
- `pvchange`: Change attributes of physical volume(s)
- `pvck`: Check the consistency of physical volume(s)
- `ps2pdf`: Convert PostScript to PDF using ghostscript
- `psk-crack`: Crack IKE Aggressive Mode Pre-Shared Keys
- `pvcreate`: Initialize physical volume(s) for use by LVM
- `pxelinux-options`: utility to set PXELINUX hard-coded options.
- `dpigs`: Show which installed packages occupy the most space
- `cookiecutter`:  create projects from project templates
 Cookiecutter is command-line utility that creates projects from
 project templates, e.g. creating a Python package project from a
 Python package project template.
 .
 It can also be used as a Python module. It supports local and remote
 templates. The templating is done with Jinja2 and there is no
 limitation on the language used by the templated projects (Python,
 Ruby, Javascript, C, HTML, Postscript...).


- `pvmove`: Move extents from one physical volume to another
- `py_compilefiles`: byte-compile python .py files
- `pvremove`: Remove LVM label(s) from physical volume(s)
- `pycentral`: register and build utility for Python packages
- `ptx`: produce a permuted index of file contents
- `pwgen`:  Automatic Password generation
 pwgen generates random, meaningless but pronounceable passwords.
 These passwords contain either only lowercase letters, or upper
 and lower case mixed, or digits thrown in.
 Uppercase letters and digits are placed in a way that eases
 remembering their position when memorizing only the word.


- `py3versions`: print python3 version information
- `pydoc3.4`: the Python documentation tool
- `pybuild`: invokes various build systems for requested Python versions
   in order to build modules and extensions
- `pygettext3.4`: Python equivalent of xgettext(1)
- `pyclean`: removes .pyc and .pyo files
- `pysetup3.4`: pysetup tool
- `pygettext2.7`: Python equivalent of <B>xgettext(1)</B>
- `pygmentize`: highlights the input file
- `pyvenv-3.4`: create virtual python environments
- `ptardiff`: program that diffs an extracted archive against an unextracted one
- `pvresize`: Resize physical volume(s)
- `pyhtmlizer`: pretty-print Python source as HTML
- `qpdldecode`: Decode a QPDL stream into human readable form.
- `qt-faststart`: utility for Quicktime files
- `pwunconv`: convert to and from shadow
   passwords and groups
- `xgamma`: Alter a monitor's gamma correction through the X server
- `radeontool`:  utility to control ATI Radeon backlight functions on laptops
 Radeontool is a small utility to control ATI Radeon based laptops' backlight
 and external output functions. It is also able to dump the contents of
 registers for debugging purposes.
 .
 WARNING: Radeontool code has not been completely audited and may contain bugs
 that could damage your hardware. Use at your own risk.


- `rand.1s`: generate pseudo-random bytes
- `pwd`: return working directory name
- `pvdisplay`: Display various attributes of physical volume(s)
- `psfstriptable`: remove the embedded Unicode character table from a console font
- `pyversions`: print python version information
- `pyrit`: A GPGPU-driven WPA/WPA2-PSK key cracker
- `rdate`:  sets the system's date from a remote host with network time protocol
 OpenRdate or openrdate or rdate displays and sets the local date and time from
 the host name or address given as the argument. The time source may be an RFC
 868 TCP protocol server, which is usually implemented as a built-in service of
 inetd(8), or an RFC 5905 protocol SNTP/NTP server. By default, rdate uses the
 RFC 868 TCP protocol.
 .
 OpenRdate supports IPv4 and IPv6 protocols.


- `rdiffdir`: compute and apply signatures and diffs to directories
- `xkbbell`: XKB extension user utility
- `xgettext`: extract gettext strings from source
- `xkbevd`: XKB event daemon
- `rabin2`: Binary program info extractor
- `pwdx`: report current working directory of a process
- `xkbprint`: print an XKB keyboard description
- `xkbvleds`: XKB extension user utility
- `readom`: read or write data Compact Discs
- `pvs`: Display information about physical volumes
- `xkbwatch`: XKB extension user utility
- `qtchooser`:  Wrapper to select between Qt development binary versions
 Qt is a cross-platform C++ application framework. Qt's primary feature
 is its rich set of widgets that provide standard GUI functionality.
 .
 The Qt Chooser provides a wrapper to switch between versions of Qt
 development binaries when multiple versions like 4 and 5 are installed
 or local Qt builds are to be used.


- `xkill`: kill a client by its X resource
- `rarp`: manipulate the system RARP table
- `recountdiff`: recompute patch counts and offsets
- `xload`: system load average display for X
- `xlogo`: X Window System logo
- `rediff`: fix offsets and counts of a hand-edited diff
- `recode-sr-latin`: convert Serbian text from Cyrillic to Latin script
- `rctest`: RFCOMM testing
- `readlink`: print resolved symbolic links or canonical file names
- `ping`: send ICMP ECHO_REQUEST to network hosts
- `xlsatoms`: list interned atoms defined on server
- `rdesktop`:  RDP client for Windows NT/2000 Terminal Server and Windows Servers
 rdesktop is an open source client for Windows NT/2000 Terminal Server and
 Windows Server 2003/2008. Capable of natively speaking its Remote Desktop
 Protocol (RDP) in order to present the user's Windows desktop. Unlike Citrix
 ICA, no server extensions are required.


- `rapper`: Raptor RDF parsing and serializing utility
- `readelf`: Displays information about ELF files.
- `Xmark`: summarize x11perf results
- `partx`: tell the kernel about the presence and numbering of on-disk partitions
- `xlsclients`: list client applications running on a display
- `random`: overview of interfaces for obtaining randomness
- `reaver`:  brute force attack tool against Wi-Fi Protected Setup PIN number
 Reaver performs a brute force attack against an access point's Wi-Fi
 Protected Setup pin number.
 Once the WPS pin is found, the WPA PSK can be recovered and alternately
 the AP's wireless settings can be reconfigured.
 This package also provides the Wash executable, an utility for identifying WPS
 enabled access points. See documentation in /usr/share/doc/reaver/README.WASH.


- `req.1s`: PKCS#10 certificate request and certificate generating utility.
- `refer`: preprocess bibliographic references for groff
- `xlsfonts`: server font list displayer for X
- `recordmydesktop`:  Captures audio-video data of a Linux desktop session
 The application produces an ogg-encapsulated theora-vorbis file.
 recordMyDesktop tries to be as unobstrusive as possible by proccessing only
 regions of the screen that have changed


- `remove-default-ispell`: remove default ispell dictionary
- `rename`:  Perl extension for renaming multiple files
 This package provides both a perl interface for renaming files (File::Rename)
 and a command line tool 'file-rename' which is intended to replace the version
 that used to be supplied by the perl package.


- `raw`: bind a Linux raw character device
- `renice`: set nice values of running processes
- `request-key`: handle key instantiation callback requests from the ker‐
   nel
- `xmag`: magnify parts of the screen
- `rendercheck`: simple tests of the X Render extension.
- `remove-shell`: remove shells from the list of valid login shells
- `rename.ul`: rename files
- `resize_reiserfs`: resizer tool for the ReiserFS filesystem
- `resize2fs`: ext2/ext3/ext4 file system resizer
- `xdg-user-dirs-update`: Update XDG user dir configuration
- `remove-default-wordlist`: remove default wordlist
- `repo-add`: package database maintenance utility
- `tune2fs`: adjust tunable filesystem parameters on ext2/ext3/ext4 filesystems
- `reset`: terminal initialization
- `resizepart`: tell the kernel about the new size of a partition
- `read`: read from a file descriptor
- `reboot`: reboot or enable/disable Ctrl-Alt-Del
- `rnano`: a restricted nano
- `roff2dvi`: transform roff code into dvi mode
- `resizecons`: change kernel idea of the console size
- `tlp`:  Optimize laptop battery life
 TLP is a feature-rich command-line utility, saving laptop battery power
 without the need to delve deeper into technical details.
 .
 TLP’s default settings are already optimized for battery life and implement
 Powertop’s recommendations out of the box. Moreover TLP is highly
 customizable to fulfil specific user requirements.
 .
 Settings are organized into two profiles, allowing to adjust between
 savings and performance independently for battery (BAT) and AC operation.
 In addition TLP can enable or disable Bluetooth, NFC, Wi-Fi and WWAN radio
 devices on boot.
 .
 For ThinkPads and selected other laptops it provides a unified way
 to configure charge thresholds and recalibrate the battery.


- `rfcomm`: RFCOMM configuration utility
- `rpl8`: Firmware loader for DVD drives
- `rpm`:  package manager for RPM
 The RPM Package Manager (RPM) is a command-line driven package
 management system capable of installing, uninstalling, verifying,
 querying, and updating computer software packages.
 .
 On Debian and derived systems it is recommended to use "alien" to
 convert RPM packages into .deb format instead of bypassing the Debian
 package management system by installing them directly with rpm.


- `rsa.1s`: RSA key processing tool
- `rsautl.1s`: RSA utility
- `rstart`: a sample implementation of a Remote Start client
- `rstartd`: a sample implementation of a Remote Start rsh helper
- `roff2html`: transform roff code into html mode
- `roff2x`: transform roff code into x mode
- `xhost`: server access control program for X
- `rev`: reverse lines characterwise
- `showconsolefont`: Show the current EGA/VGA console screen font
- `resolvconf`:  name server information handler
 Resolvconf is a framework for keeping up to date the system's
 information about name servers. It sets itself up as the intermediary
 between programs that supply this information (such as ifup and
 ifdown, DHCP clients, the PPP daemon and local name servers) and
 programs that use this information (such as DNS caches and resolver
 libraries).
 .
 This package may require some manual configuration. Please
 read the README file for detailed instructions.


- `routel`: flush routes
- `roff2text`: transform roff code into text mode
- `rsync`:  fast, versatile, remote (and local) file-copying tool
 rsync is a fast and versatile file-copying tool which can copy locally
 and to/from a remote host. It offers many options to control its behavior,
 and its remote-update protocol can minimize network traffic to make
 transferring updates between machines fast and efficient.
 .
 It is widely used for backups and mirroring and as an improved copy
 command for everyday use.
 .
 This package provides both the rsync command line tool and optional
 daemon functionality.


- `ruby`:  Interpreter of object-oriented scripting language Ruby (default version)
 Ruby is the interpreted scripting language for quick and easy
 object-oriented programming.  It has many features to process text
 files and to do system management tasks (as in perl).  It is simple,
 straight-forward, and extensible.
 .
 This package is a dependency package, which depends on Debian's default Ruby
 version (currently v3.1).


- `rpcclient`: tool for executing client side MS -RPC functions
- `roff2ps`: transform roff code into ps mode
- `s2p`: a stream editor
- `xqxdecode`: Decode a XQX stream into human readable form.
- `s_client.1s`: SSL/TLS client program
- `s_server.1s`: SSL/TLS server program
- `s_time.1s`: SSL/TLS performance timing program
- `sa1`: Collect and store binary data in the system activity daily data file.
- `sa2`: Write a daily report in the /var/log/sysstat directory.
- `sadc`: System activity data collector.
- `rfkill`:  tool for enabling and disabling wireless devices
 rfkill is a simple tool for accessing the Linux rfkill device interface,
 which is used to enable and disable wireless networking devices, typically
 WLAN, Bluetooth and mobile broadband.


- `safe_finger`: finger client wrapper that protects against nasty stuff from finger servers
- `rsyslogd`: reliable and extended syslogd
- `rmmod`: Simple program to remove a module from the Linux Kernel
- `rtkitctl`: Realtime Policy and Watchdog daemon control
- `run-parts`: run scripts or programs in a directory
- `rtacct`: network statistics tools.
- `sadf`: Display data collected by sar in multiple formats.
- `run-mailcap`: execute programs via en‐
   tries in the mailcap file
- `rtmon`: listens to and monitors RTnetlink
- `xdg-user-dir`: Find an XDG user dir
- `xmore`: plain text display program for the X Window System
- `xmessage`: display a message or query in a window (X-based /bin/echo)
- `ImageMagick`: is a free software suite for the creation, modification and display of bitmap images.
- `xinit`:  X server initialisation tool
 xinit and startx are programs which facilitate starting an X server, and
 loading a base X session.


- `h2xs`: convert .h C header files to Perl extensions
- `sar`: Collect, report, or save system activity information.
- `runcon`: run command with specified security context
- `samba-regedit`: ncurses based tool to manage the Samba registry
- `sensors`: print sensors information
- `sar.sysstat`: Collect, report, or save system activity information.
- `savelog`: save a log file
- `screendump`: dump the contents of a virtual console to stdout
- `scanimage`: scan an image
- `xkbcomp`: compile XKB keyboard description
- `rpcinfo`: report RPC information
- `scp`: secure copy (remote file copy program)
- `rtcwake`: enter a system sleep state until specified wakeup time
- `seq`: print a sequence of numbers
- `xrefresh`: refresh all or part of an X screen
- `xmodmap`: utility for modifying keymaps and pointer button mappings in X
- `xsm`: X Session Manager
- `xsetmode`: set the mode for an X Input device
- `xprop`: property displayer for X
- `xtables-multi`: xtables multi-link binary for netfilter's iptables and ip6tables
- `xmllint`: command line XML tool
- `script`: make typescript of terminal session
- `sdiff`: side-by-side merge of file differences
- `sdptool`: control and interrogate SDP servers
- `scriptreplay`: play back typescripts, using timing information
- `see`: execute programs via en‐
   tries in the mailcap file
- `run-with-aspell`: script to help use GNU Aspell as an ispell replace‐
   ment
- `sess_id.1s`: SSL/TLS session handling utility
- `session-installer`: allows applications to easily install and remove software
- `session-migration`: Migrate in user session settings.
- `select-editor`: select your default sensible-editor from all installed
   editors
- `sha224sum`: compute and check SHA224 message digest
- `xstdcmap`: X standard colormap utility
- `seahorse`:  GNOME front end for GnuPG
 Seahorse is a front end for GnuPG - the GNU Privacy Guard program -
 that integrates to the GNOME desktop. It is a tool for secure
 communications and data storage.  Data encryption and digital signature
 creation can easily be performed through a GUI and Key Management
 operations can easily be carried out through an intuitive interface.


- `select-default-ispell`: select default ispell dictionary
- `sensible-editor`: sensible editing,
   paging, and web browsing
- `splain`: produce verbose warning diagnostics
- `runlevel`: Print previous and current SysV runlevel
- `saned`: SANE network daemon
- `xterm`:  X terminal emulator
 xterm is a terminal emulator for the X Window System.  It provides DEC VT102
 and Tektronix 4014 compatible terminals for programs that cannot use the
 window system directly.  This version implements ISO/ANSI colors and most of
 the control sequences used by DEC VT220 terminals.
 .
 This package provides four commands: xterm, which is the traditional
 terminal emulator; uxterm, which is a wrapper around xterm that is
 intelligent about locale settings (especially those which use the UTF-8
 character encoding), but which requires the luit program from the luit
 package; koi8rxterm, a wrapper similar to uxterm for locales that use the
 KOI8-R character set; and lxterm, a simple wrapper that chooses which of the
 previous commands to execute based on the user's locale settings.
 .
 A complete list of control sequences supported by the X terminal emulator
 is provided in /usr/share/doc/xterm.
 .
 The xterm program uses bitmap images provided by the xbitmaps package.
 .
 Those interested in using koi8rxterm will likely want to install the
 xfonts-cyrillic package as well.


- `xvidtune`: video mode tuner for Xorg
- `xvinfo`: Print out X-Video extension adaptor information
- `sendmail`:  powerful, efficient, and scalable Mail Transport Agent (metapackage)
 Sendmail is an alternative Mail Transport Agent (MTA) for Debian.
 It is suitable for handling sophisticated mail configurations,
 although this means that its configuration can also be complex.
 .
 Fortunately, simple things can be done easily, and complex things
 are possible, even if not easily understood ;)  Sendmail is the *ONLY*
 MTA with a Turing complete language to control *ALL* aspects of delivery!
 .
 Sendmail provides Security and SPAM/UCE/UBE protection via several means.
 .
 Sendmail includes *no* Mail User Agents (MUA), you'll have to
 pick from the plethora of available MUAs (mutt, vm, etc.)
 .
 This package supports REGEX, DB, NIS, NIS+, LDAP, DNS maps,
 and has enabled TCPWrappers, IPv6, LockFile, SMTP AUTH(SASL), STARTTLS(SSL).
 .
 This package is to make installation/upgrading easier (Do NOT delete it)


- `sessreg`: manage utmpx/wtmpx entries for non-init clients
- `sed`:  GNU stream editor for filtering/transforming text
 sed reads the specified files or the standard input if no
 files are specified, makes editing changes according to a
 list of commands, and writes the results to the standard
 output.


- `sensors-detect`: detect hardware monitoring chips
- `xwd`: dump an image of an X window
- `setarch`: change reported architecture in new program environment and/or set personality flags
- `xwininfo`: window information utility for X
- `xsetpointer`: set an X Input device as the main pointer
- `xsetwacom`: commandline utility to query and modify wacom driver set‐
   tings.
- `smbtree`: A text based smb network browser
- `xxd`:  tool to make (or reverse) a hex dump
 xxd creates a hex dump of a given file or standard input.  It can also convert
 a hex dump back to its original binary form.


- `set`:  Social-Engineer Toolkit
 The Social-Engineer Toolkit (SET) is an open-source
 Python-driven tool aimed at penetration testing around
 Social-Engineering.


- `xset`: user preference utility for X
- `lua`: Lua interpreter
- `setcap`: set file capabilities
- `select-default-wordlist`: select default wordlist
- `setlogcons`: Send kernel messages to console N
- `isoinfo`: Utility programs for dumping and
   verifying iso9660 images.
- `setfont`: load EGA/VGA console screen font
- `sfddiff`: compare two font files
- `sensible-browser`: sensible editing,
   paging, and web browsing
- `setcifsacl`: Userspace helper to alter an ACL in a security descriptor for Common Internet File System (CIFS)
- `setvtrgb`: set the virtual terminal RGB colors
- `setfacl`: set file access control lists
- `yum`: Yellowdog Updater Modified
- `sha1pass`: Create a SHA1 password hash
- `setupcon`: sets up the font and the keyboard on the console
- `sensors-conf-convert`: sensors configuration conversion
- `rm`: remove directory entries
- `setkeycodes`: load kernel scancode-to-keycode mapping table entries
- `startx`: initialize an X session
- `shadowconfig`: toggle shadow passwords on and off
- `setxkbmap`: set the keyboard using the X Keyboard Extension
- `sftp`: secure file transfer program
- `xz`: Compress or decompress .xz and
   .lzma files
- `xzdiff`: compare compressed files
- `yelp`:  Help browser for GNOME
 Yelp is the help browser for the GNOME desktop.  Yelp provides a simple
 graphical interface for viewing DocBook, Mallard, HTML, man, and info
 formatted documentation.


- `sha1sum`: compute and check SHA1 message digest
- `showfont`: font dumper for X font server
- `psfgettable`: extract the embedded Unicode character table from a console font
- `sg`: execute command as different group ID
- `sh`: shell, the standard command language interpreter
- `sha256sum`: compute and check SHA256 message digest
- `xzmore`: view xz or lzma compressed (text) files
- `service`: run a System V init script
- `zdiff`: compare compressed files
- `wesside-ng`: crack a WEP key of an open network without user interven‐
   tion
- `xzgrep`: search compressed files for a regular expression
- `yes`: output a string repeatedly until killed
- `zenmap`:  The Network Mapper Front End
 Zenmap is an Nmap frontend. It is meant to be useful for advanced users
 and to make Nmap easy to use by beginners. It was originally derived
 from Umit, an Nmap GUI created as part of the Google Summer of Code.


- `spd-say`: manual page for spd-say 0.9.1
- `word-list-compress`: word list compressor/decompressor for GNU Aspell
- `zcat`: expand and concatenate data
- `zjsdecode`: Decode a ZjStream into human readable form.
- `showrgb`: display an rgb color-name database
- `sharesec`: Set or get share ACLs
- `ptar`: a tar -like program written in perl
- `shasum`: Print or Check SHA Checksums
- `setleds`: set the keyboard leds
- `shred`: overwrite a file to hide its contents, and optionally delete it
- `skill`: send a signal or report process status
- `slxdecode`: Decode a SLX stream into human readable form.
- `setmetamode`: define the keyboard meta key handling
- `sha512sum`: compute and check SHA512 message digest
- `skipfish`:  fully automated, active web application security reconnaissance tool
 Skipfish is an active web application security reconnaissance tool. It prepares
 an interactive sitemap for the targeted site by carrying out a recursive crawl
 and dictionary-based probes. The resulting map is then annotated with the
 output from a number of active (but hopefully non-disruptive) security checks.
 The final report generated by the tool is meant to serve as a foundation for
 professional web application security assessments.


- `size`: list section sizes and total size.
- `sfdisk`: display or manipulate a disk partition table
- `setsid`: creates a session and sets the process group ID
- `shuf`: generate random permutations
- `simple-scan`:  Simple Scanning Utility
 Simple Scan is an easy-to-use application, designed to let users
 connect their scanner and quickly have the image/document in an
 appropriate format.
 .
 Simple Scan is basically a frontend for SANE - which is the same
 backend as XSANE uses. This means that all existing scanners will
 work and the interface is well tested.


- `ssh-keyscan`: gather SSH public keys
- `smbta-util`: control encryption in VFS smb_traffic_analyzer
- `ssh-keygen`: authentication key generation, management and conversion
- `smbpasswd`: change a user's SMB password
- `smime.1s`: S/MIME utility
- `smproxy`: Session Manager Proxy
- `snort`:  flexible Network Intrusion Detection System
 Snort is a libpcap-based packet sniffer/logger which can be used as a
 lightweight network intrusion detection system. It features rules-based
 logging and can perform content searching/matching in addition to
 detecting a variety of other attacks and probes, such as buffer
 overflows, stealth port scans, CGI attacks, SMB probes, and much more.
 Snort has a real-time alerting capability, with alerts being sent to
 syslog, a separate "alert" file, or even to a Windows computer via Samba.
 .
 This package provides the plain-vanilla version of Snort.


- `zforce`: force a '.gz' extension on all gzip files
- `zipcloak`: encrypt entries in a zipfile
- `xrdb`: X server resource database utility
- `smbcontrol`: send messages to smbd, nmbd or winbindd processes
- `smbcacls`: Set or get ACLs on an NT file or directory names
- `sort-dctrl`: sort Debian control files
- `soxi`: Sound eXchange Information, display sound file metadata
- `smbclient`:  command-line SMB/CIFS clients for Unix
 Samba is an implementation of the SMB/CIFS protocol for Unix systems,
 providing support for cross-platform file and printer sharing with
 Microsoft Windows, OS X, and other Unix systems.
 .
 This package contains command-line utilities for accessing Microsoft
 Windows and Samba servers, including smbclient, smbtar, and smbspool.
 Utilities for mounting shares locally are found in the package
 cifs-utils.


- `smbstatus`: report on current Samba connections
- `smbcquotas`: Set or get QUOTAs of NTFS 5 shares
- `soelim`: interpret .so requests in groff input    nr soelim_C  [.C] 0 pic.tmac
- `speed.1s`: test library performance
- `spkac.1s`: SPKAC printing and generating utility
- `sort`: sort, merge, or sequence check text files
- `zgrep`: search possibly compressed files for a regular expression
- `spd-conf`: manual page for spd-conf 0.9.1
- `splitdiff`: separate out incremental patches
- `prove`: Run tests through a TAP harness.
- `zipdetails`: display the internal structure of zip files
- `fsck.jfs`: initiate  replay of the JFS transaction log, and check and
   repair a JFS formatted device
- `socat`:  multipurpose relay for bidirectional data transfer
 Socat (for SOcket CAT) establishes two bidirectional byte streams
 and transfers data between them. Data channels may be files, pipes,
 devices (terminal or modem, etc.), or sockets (Unix, IPv4, IPv6, raw,
 UDP, TCP, SSL). It provides forking, logging and tracing, different
 modes for interprocess communication and many more options.
 .
 It can be used, for example, as a TCP relay (one-shot or daemon),
 as an external socksifier, as a shell interface to Unix sockets,
 as an IPv6 relay, as a netcat and rinetd replacement, to redirect
 TCP-oriented programs to a serial line, or to establish a relatively
 secure environment (su and chroot) for running client or server shell
 scripts inside network connections. Socat supports sctp as of 1.7.0.


- `sha384sum`: compute and check SHA384 message digest
- `splitfont`: extract characters from an ISO-type font.
- `split`: split files into pieces
- `speech-dispatcher`:  Common interface to speech synthesizers
 Speech Dispatcher provides a device independent layer for speech synthesis.
 It supports various software and hardware speech synthesizers as
 backends and provides a generic layer for synthesizing speech and
 playing back PCM data via those different backends to applications.
 .
 Various high level concepts like enqueueing vs. interrupting speech and
 application specific user configurations are implemented in a device
 independent way, therefore freeing the application programmer from
 having to yet again reinvent the wheel.
 .
 This package contains Speech Dispatcher itself.


- `speaker-test`: command-line speaker test tone generator for ALSA
- `sqlitebrowser`:  GUI editor for SQLite databases
 SQLite Database Browser is a visual tool used to create, design and edit
 database files compatible with SQLite. Its interface is based on QT,
 and is meant to be used for users and developers that want to create
 databases, edit and search data using a familiar spreadsheet-like
 interface, without the need to learn complicated SQL commands.
 Controls and wizards are available for users to:
  - Create and compact database files
  - Create, define, modify and delete tables
  - Create, define and delete indexes
  - Browse, edit, add and delete records
  - Search records
  - Import and export records as text
  - Import and export tables from/to CSV files
  - Import and export databases from/to SQL dump files
  - Issue SQL queries and inspect the results
  - Examine a log of all SQL commands issued by the application
 .
 SQLite Database Browser is not a visual shell for the sqlite command line
 tool. It does not require familiarity with SQL commands.


- `sqlmap`:  automatic SQL injection tool
 sqlmap goal is to detect and take advantage of SQL injection
 vulnerabilities in web applications. Once it detects one or more SQL
 injections on the target host, the user can choose among a variety of
 options to perform an extensive back-end database management system
 fingerprint, retrieve DBMS session user and database, enumerate users,
 password hashes, privileges, databases, dump entire or user's specific
 DBMS tables/columns, run his own SQL statement, read specific files on
 the file system and more.


- `ssh-agent`: authentication agent
- `sqlite3`:  Command line interface for SQLite 3
 SQLite is a C library that implements an SQL database engine.
 Programs that link with the SQLite library can have SQL database
 access without running a separate RDBMS process.


- `smbspool`: send a print file to an SMB printer
- `ss`: another utility to investigate sockets
- `rmdir`: delete a directory
- `stat`: display file or file system status
- `start-pulseaudio-kde`: PulseAudio Sound Server KDE Startup Script
- `smartctl`: Control and Monitor Utility for SMART Disks
- `slattach`: attach a network interface to a serial line
- `startpar`:  run processes in parallel and multiplex their output
 Used by the sysv-rc boot system executor to run init.d scripts in parallel
 while making sure the script output is not completely messed up.


- `lrztar`: Directory wrapper for lrzip
- `ssh-keysign`: ssh helper program for host-based authentication
- `ophcrack`:  Microsoft Windows password cracker using rainbow tables (gui)
 Ophcrack is a Windows password cracker based on a time-memory trade-off
 using rainbow tables. This is a new variant of Hellman's original trade-off,
 with better performance. It recovers 99.9% of alphanumeric passwords in
 seconds.
 .
 It works for Windows NT/2000/XP/Vista/7.
 .
 This package contains ophcrack with QT4 based graphical UI.
 Please note that it can be used in command line as well.


- `paplay`: Play back or record raw or encoded audio streams on a PulseAu‐
   dio sound server
- `ssh-argv0`: replaces the old ssh command-name as hostname handling
- `sslstrip`:  SSL/TLS man-in-the-middle attack tool
 sslstrip is a tool that transparently hijacks HTTP traffic on a network, watch
 for HTTPS links and redirects, and then map those links into look-alike HTTP
 links or homograph-similar HTTPS links. It also supports modes for supplying a
 favicon which looks like a lock icon, selective logging, and session
 denial.


- `getenforce`: get the current mode of SELinux
- `strace`:  System call tracer
 strace is a system call tracer, i.e. a debugging tool which prints out
 a trace of all the system calls made by another process/program.
 The program to be traced need not be recompiled for this, so you can
 use it on binaries for which you don't have source.
 .
 System calls and signals are events that happen at the user/kernel
 interface. A close examination of this boundary is very useful for bug
 isolation, sanity checking and attempting to capture race conditions.


- `stream.im6`: a lightweight tool to stream one or more pixel components of the image or portion of the image to your choice of storage formats.
- `strfile`: create a random access file for storing strings  unstr
- `stdbuf`: Run COMMAND, with modified buffering operations for its standard streams.
- `ssh-copy-id`: use locally available keys to authorise logins on a remote machine
- `ssh-add`: adds private key identities to the authentication agent
- `ssh`:  secure shell client and server (metapackage)
 This metapackage is a convenient way to install both the OpenSSH client
 and the OpenSSH server. It provides nothing in and of itself, so you
 may remove it if nothing depends on it.


- `egrep`: print lines that match patterns
- `sleep`: suspend execution for an interval
- `sudo_root`: How to run administrative commands
- `truncate`: shrink or extend the size of a file to the specified size
- `sln`: create symbolic links
- `hostid`: print the numeric identifier for the current host
- `smbd`: server to provide SMB/CIFS services to clients
- `strings`: find printable strings in files
- `true`: return true value
- `setterm`: set terminal attributes
- `strip`: remove unnecessary information from strippable files (   DEVELOPMENT  )
- `verify.1s`: Utility to verify certificates.
- `samba`:  SMB/CIFS file, print, and login server for Unix
 Samba is an implementation of the SMB/CIFS protocol for Unix systems,
 providing support for cross-platform file and printer sharing with
 Microsoft Windows, OS X, and other Unix systems.  Samba can also function
 as an Active Directory or NT4-style domain controller, and can integrate
 with Active Directory realms or NT4 domains as a member server.
 .
 This package provides the components necessary to use Samba as a stand-alone
 file and print server or as an NT4 domain controller.  For use in an NT4
 domain or Active Directory realm, you will also need the winbind package.
 To use samba as an Active Directory domain controller (AD DC), please install
 samba-ad-dc package.
 .
 This package is not required for connecting to existing SMB/CIFS servers
 (see smbclient) or for mounting remote filesystems (see cifs-utils).


- `synaptic`:  Graphical package manager
 Synaptic is a graphical package management tool based on GTK and APT.
 Synaptic enables you to install, upgrade and remove software packages in
 a user-friendly way.
 .
 Besides these basic functions the following features are provided:
  * Search and filter the list of available packages
  * Perform smart system upgrades
  * Fix broken package dependencies
  * Edit the list of used repositories (sources.list)
  * Download the latest changelog of a package
  * Configure packages through the debconf system
  * Browse all available documentation related to a package (dwww is required)


- `sucrack`:  multithreaded su bruteforcer
 sucrack is a multithreaded Linux/UNIX tool for cracking local
 user accounts via wordlist bruteforcing su. This tool comes in
 handy when you've gained access to a low-privilege user account
 but are allowed to su to other users. Many su implementations
 require a pseudo terminal to be attached in order to take the
 password from the user. This can't be easily achieved with a
 simple shell script. This tool, written in C, is highly
 efficient and can attempt multiple logins at the same time.


- `lz4`:  Fast LZ compression algorithm library - tool
 LZ4 is a very fast lossless compression algorithm, providing compression speed
 at 400 MB/s per core, scalable with multi-cores CPU. It also features an
 extremely fast decoder, with speed in multiple GB/s per core, typically
 reaching RAM speed limits on multi-core systems.
 .
 This package contains files that is tool using liblz4.


- `pdftops`: Portable Document Format (PDF) to PostScript converter (version 3.03)
- `sync-available`: sync dpkg's available database with apt's database
- `usbmuxd`:  USB multiplexor daemon for iPhone and iPod Touch devices
 usbmuxd, the USB multiplexor daemon, is in charge of coordinating
 access to iPhone and iPod Touch services over USB. Synchronization and
 management applications for the iPhone and iPod Touch need this daemon
 to communicate with such devices concurrently.
 .
 This package includes udev rules to start the daemon when a supported
 device is plugged in, and stop it when all devices are removed.


- `synclient`: commandline utility to query and modify Synaptics driver options.
- `syndaemon`: a program that monitors keyboard activity and disables the touchpad when the keyboard is being used.
- `lsyncd`:  daemon to synchronize local directories using rsync
 Lsyncd (Live syncing mirror daemon) uses rsync to synchronize local
 directories with a remote machine running rsyncd. Lsyncd watches
 multiple directories trees through inotify. The first step after
 adding the watches is to rsync all directories with the remote host,
 and then sync single file by collecting the inotify events. So lsyncd
 is a light-weight live mirror solution that should be easy to install
 and use while blending
 well with your system.


- `pstack`: print a stack trace of a running process
- `mongo`: the Mongo command-line tool
- `start-stop-daemon`: start and stop system daemon programs
- `virt-clone`: clone existing virtual machine images
- `virsh`: management user interface
- `syslinux`:  collection of bootloaders (DOS FAT and NTFS bootloader)
 syslinux is a suite of bootloaders, currently supporting DOS FAT and NTFS
 filesystems (SYSLINUX), Linux ext2/ext3/ext4, btrfs, and xfs filesystems
 (EXTLINUX), PXE network boots (PXELINUX), or ISO 9660 CD-ROMs (ISOLINUX).
 .
 This package contains the bootloader for DOS FAT and NTFS filesystems
 (SYSLINUX).


- `syslinux-legacy`: install the SYSLINUX bootloader on a FAT filesystem
- `syslinux2ansi`: converts a syslinux-format screen to pc-ansi
- `virt-install`:  utilities to create and edit virtual machines
 This package contains some command line utilities to create and edit virtual
 machines:
 .
  - virt-clone: cloning existing inactive guests; it copies the disk images,
    and defines a config with new name, UUID and MAC address pointing to the
    copied disks
  - virt-install: provision operating systems into new virtual machines
  - virt-xml: easily edit libvirt domain XML using virt-install's command line
    options


- `sudo`:  Provide limited super user privileges to specific users
 Sudo is a program designed to allow a sysadmin to give limited root
 privileges to users and log root activity.  The basic philosophy is to give
 as few privileges as possible but still allow people to get their work done.
 .
 This version is built with minimal shared library dependencies, use the
 sudo-ldap package instead if you need LDAP support for sudoers.


- `stty`: set the options for a terminal
- `systemd-hostnamed.service`: Hostname bus mechanism
- `systemd-localed.service`: Locale bus mechanism
- `systemd-logind.service`: Login manager
- `systemd-timedated.service`: Time and date bus mechanism
- `systemd-udevd.service`: Device event managing daemon
- `t1ascii`: convert PostScript Type 1 font from binary to ASCII
- `t1asm`: assemble PostScript Type 1 font
- `t1binary`: convert PostScript Type 1 font from ASCII to binary
- `t1disasm`: disassemble PostScript Type 1 font
- `t1mac`: translate a PFA or PFB PostScript Type 1 font into Macintosh format
- `t1unmac`: translate a Mac PostScript Type 1 font into PFA or PFB format
- `swapoff`: enable/disable devices and files for paging and swap‐
   ping
- `svn`: Subversion command line client tool
- `sulogin`: single-user login
- `tailf`: follow the growth of a log file
- `tap2deb`: create Debian packages which wrap .tap files
- `tap2rpm`: create RPM packages which wrap .tap files
- `tapconvert`: convert Twisted configurations from one format to another
- `sftp-server`: SFTP server subsystem
- `ssh-pkcs11-helper`: ssh-agent helper program for PKCS#11 support
- `system-config-printer`:  graphical interface to configure the printing system
 System-config-printer is a GUI written in Python using GTK+ to
 configure a CUPS server. Its primary use is to configure the printing
 system on the local host, but can also be used to setup a remote
 printer.
 .
 In terms of features, it aims to be as complete as the CUPS web
 administration tool, while being integrated to the desktop.


- `systemd-analyze`: Analyze and debug system manager
- `tbl-dctrl`: generate tabular representations of data in dctrl format
- `sudoreplay`: replay sudo session logs
- `tc-bfifo`: Packet limited First In, First Out queue  bfifo
- `tc-cbq`: Class Based Queueing
- `tc-cbq-details`: Class Based Queueing
- `tc-choke`: choose and keep scheduler
- `tc-codel`: Controlled-Delay Active Queue Management algorithm
- `tc-drr`: deficit round robin scheduler
- `tc-ematch`: extended matches for use with "basic" or "flow" filters
- `tc-fq_codel`: Fair Queuing (FQ) with Controlled Delay (CoDel)
- `tc-hfsc`: Hierarchical Fair Service Curve's control under linux
- `tc-htb`: Hierarchy Token Bucket
- `tc-netem`: Network Emulator
- `tc-pfifo_fast`: three-band first in, first out queue
- `tc-prio`: Priority qdisc
- `tc-red`: Random Early Detection
- `tc-sfb`: Stochastic Fair Blue
- `tc-sfq`: Stochastic Fairness Queueing
- `tc-stab`: Generic size table manipulations
- `tc-tbf`: Token Bucket Filter
- `tclsh8.5`: NAME   tclsh
- `tcpd`:  Wietse Venema's TCP wrapper utilities
 Wietse Venema's network logger, also known as TCPD or LOG_TCP.
 .
 These programs log the client host name of incoming telnet,
 ftp, rsh, rlogin, finger etc. requests.
 .
 Security options are:
  - access control per host, domain and/or service;
  - detection of host name spoofing or host address spoofing;
  - booby traps to implement an early-warning system.


- `tcpdchk`: tcp wrapper configuration checker
- `tcpdmatch`: tcp wrapper oracle
- `swapon`: enable/disable devices and files for paging and swap‐
   ping
- `tabs`: set terminal tabs
- `systemctl`:  daemonless "systemctl" command to manage services without systemd
 "systemctl" is a replacement command to control system daemons without
 systemd. "systemctl" is useful in application containers where systemd is
 not available to start/stop services.
 .
 This script can also be run as init of an application container (i.e. the
 main "CMD" on PID 1) where it will automatically bring up all enabled
 services in the "multi-user.target" and where it will reap all zombies
 from background processes in the container. When stopping such a container
 it will also bring down all configured services correctly before exit.


- `pacat`: Play back or record raw or encoded audio streams on a PulseAudio sound server
- `tasksel`:  tool for selecting tasks for installation on Debian systems
 This package provides 'tasksel', a simple interface for users who
 want to configure their system to perform a specific task.


- `su`: run a command with substitute user and group ID
- `restorecon`: file(s) default SELinux security contexts.
- `tac`: concatenate and print files in reverse
- `tcpflow`:  TCP flow recorder
 tcpflow is a program that captures data transmitted as part of TCP
 connections (flows), and stores the data in a way that is convenient
 for protocol analysis or debugging. A program like 'tcpdump' shows a
 summary of packets seen on the wire, but usually doesn't store the
 data that's actually being transmitted. In contrast, tcpflow
 reconstructs the actual data streams and stores each flow in a
 separate file for later analysis.
 .
 tcpflow understands sequence numbers and will correctly reconstruct
 data streams regardless of retransmissions or out-of-order delivery.
 However, it currently does not understand IP fragments; flows
 containing IP fragments will not be recorded properly.
 .
 tcpflow is based on the LBL Packet Capture Library and therefore
 supports the same rich filtering expressions that programs like
 'tcpdump' support. tcpflow can also rebuild flows from data captured
 with 'tcpdump -w'.


- `battlestar`: a tropical adventure game
- `tdbbackup.tdbtools`: tool for backing up and for validating the integrity of
   samba .tdb files
- `terminator`:  multiple GNOME terminals in one window
 Terminator is a little project to produce an efficient way of
 filling a large area of screen space with terminals.
 .
 The user can have multiple terminals in one window and use
 key bindings to switch between them. See the manpage for
 details.


- `route`: route traffic control filter
- `tcpdump`:  command-line network traffic analyzer
 This program allows you to dump the traffic on a network. tcpdump
 is able to examine IPv4, ICMPv4, IPv6, ICMPv6, UDP, TCP, SNMP, AFS
 BGP, RIP, PIM, DVMRP, IGMP, SMB, OSPF, NFS and many other packet
 types.
 .
 It can be used to print out the headers of packets on a network
 interface, filter packets that match a certain expression. You can
 use this tool to track down network problems, to detect attacks
 or to monitor network activities.


- `tc`: show / manipulate traffic control settings
- `tgz`: makes a gzip'd tar archive
- `thunderbird`:  mail/news client with RSS, chat and integrated spam filter support
 Thunderbird is an mail client suitable for free distribution. The goal of
 Thunderbird is to produce a cross platform stand-alone mail application using
 the XUL user interface language.
 It supports different mail accounts, no matter of the used protocol like
 POP(s) or IMAP(s), has an integrated learning Spam filter, and offers easy
 organization of mails with tagging and virtual folders. Also, more features
 can be added by installing extensions.
 .
 Thunderbird also includes an integrated calendar for handling events, events
 invitations and tasks in multiple calendars. It supports local calendars,
 CalDAV and plain ics files on CardDAV and WebDAV.
 .
 The goal of Thunderbird is to produce a cross platform standalone mail
 application using the XUL user interface language.


- `tempfile`: create a temporary file in a safe manner
- `test`: evaluate expression
- `semanage`: SELinux Policy Management tool
- `swaplabel`: print or change the label or UUID of a swap area
- `tdbrestore`: tool for creating a TDB file out of a tdbdump output
- `sestatus`: SELinux status tool
- `logout`: write utmp and wtmp entries
- `dnsmasq`:  Small caching DNS proxy and DHCP/TFTP server - system daemon
 Dnsmasq is a lightweight, easy to configure, DNS forwarder and DHCP
 server. It is designed to provide DNS and optionally, DHCP, to a
 small network. It can serve the names of local machines which are
 not in the global DNS. The DHCP server integrates with the DNS
 server and allows machines with DHCP-allocated addresses
 to appear in the DNS with names configured either in each host or
 in a central configuration file. Dnsmasq supports static and dynamic
 DHCP leases and BOOTP/TFTP for network booting of diskless machines.


- `testdisk`:  Partition scanner and disk recovery tool, and PhotoRec file recovery tool
 TestDisk checks the partition and boot sectors of your disks.
 It is very useful in forensics, recovering lost partitions.
 It works with :
  * DOS/Windows FAT12, FAT16 and FAT32
  * NTFS ( Windows NT/2K/XP )
  * Linux Ext2 and Ext3
  * BeFS ( BeOS )
  * BSD disklabel ( FreeBSD/OpenBSD/NetBSD )
  * CramFS (Compressed File System)
  * HFS and HFS+, Hierarchical File System
  * JFS, IBM's Journaled File System
  * Linux Raid
  * Linux Swap (versions 1 and 2)
  * LVM and LVM2, Linux Logical Volume Manager
  * Netware NSS
  * ReiserFS 3.5 and 3.6
  * Sun Solaris i386 disklabel
  * UFS and UFS2 (Sun/BSD/...)
  * XFS, SGI's Journaled File System
 .
 PhotoRec is file data recovery software designed to recover
 lost pictures from digital camera memory or even Hard Disks.
 It has been extended to search also for non audio/video headers.
 It searches for following files and is able to undelete them:
  * Sun/NeXT audio data (.au)
  * RIFF audio/video (.avi/.wav)
  * BMP bitmap (.bmp)
  * bzip2 compressed data (.bz2)
  * Source code written in C (.c)
  * Canon Raw picture (.crw)
  * Canon catalog (.ctg)
  * FAT subdirectory
  * Microsoft Office Document (.doc)
  * Nikon dsc (.dsc)
  * HTML page (.html)
  * JPEG picture (.jpg)
  * MOV video (.mov)
  * MP3 audio (MPEG ADTS, layer III, v1) (.mp3)
  * Moving Picture Experts Group video (.mpg)
  * Minolta Raw picture (.mrw)
  * Olympus Raw Format picture (.orf)
  * Portable Document Format (.pdf)
  * Perl script (.pl)
  * Portable Network Graphics (.png)
  * Raw Fujifilm picture (.raf)
  * Contax picture (.raw)
  * Rollei picture (.rdc)
  * Rich Text Format (.rtf)
  * Shell script (.sh)
  * Tar archive (.tar )
  * Tag Image File Format (.tiff)
  * Microsoft ASF (.wma)
  * Sigma/Foveon X3 raw picture (.x3f)
  * zip archive (.zip)


- `htop`:  interactive processes viewer
 Htop is an ncursed-based process viewer similar to top, but it
 allows one to scroll the list vertically and horizontally to see
 all processes and their full command lines.
 .
 Tasks related to processes (killing, renicing) can be done without
 entering their PIDs.


- `mpage`: print multiple pages per sheet on PostScript printer
- `evince`:  Document (PostScript, PDF) viewer
 Evince is a simple multi-page document viewer.  It can display and print
 PostScript (PS), Encapsulated PostScript (EPS), DjVu, DVI, Portable
 Document Format (PDF) and XML Paper Specification (XPS) files.
 When supported by the document, it also allows searching for text,
 copying text to the clipboard, hypertext navigation, and
 table-of-contents bookmarks.


- `switch_root`: switch to another filesystem as the root of the mount tree
- `testparm`: check an smb.conf configuration file for internal
   correctness
- `tomboy`: A simple note-taking application for Gnome
- `tbl`: format tables for troff    nr tbl_C  [.C] 0
- `tor-gencert`: Generate certs and keys for Tor directory authorities
- `tor-resolve`: resolve a hostname to an IP address via tor
- `torchat`: TorChat dummy launcher
- `torify`: wrapper for torsocks and tor
- `toshsat1800-irdasetup`: IrDA setup utility for Toshiba Satellite 1800
- `toshset`: manipulate bios and hardware settings of Toshiba laptops
- `telnet`:  transitional dummy package for inetutils-telnet default switch
 This package will force a switch from the old netkit telnet implementation
 to the inetutils-telnet one, which is an upstream maintained project.
 .
 This package can be safely removed once it has been upgraded, as
 inetutils-telnet provides a matching virtual package. It will stop being
 provided after Debian bookworm's release.
 .
 If you want to keep using the netkit implementation, then install
 telnet-ssl instead.


- `tic`: the terminfo entry-description compiler
- `tlp-stat`: show power saving settings
- `toe`: table of (terminfo) entries
- `tee`: duplicating pipe content
- `totem-video-thumbnailer`: video thumbnailer for the GNOME desktop
- `sysctl`: configure kernel parameters at runtime
- `traceroute6.iputils`: traces path to a network host
- `tdbtool`: manipulate the contents TDB files
- `totem`:  Simple media player for the GNOME desktop based on GStreamer
 Totem is a simple yet featureful media player for GNOME which can read
 a large number of file formats. It features :
 .
    * Shoutcast, m3u, asx, SMIL and ra playlists support
    * DVD (with menus), VCD and Digital CD (with CDDB) playback
    * TV-Out configuration with optional resolution switching
    * 4.0, 5.0, 5.1 and stereo audio output
    * Full-screen mode (move your mouse and you get nice controls) with
      Xinerama, dual-head and RandR support
    * Aspect ratio toggling, scaling based on the video's original size
    * Full keyboard control
    * Simple playlist with repeat mode and saving feature
    * GNOME, Nautilus and GIO integration
    * Screenshot of the current movie
    * Brightness and Contrast control
    * Visualisation plugin when playing audio-only files
    * Video thumbnailer for nautilus
    * Nautilus properties page
    * Works on remote displays
    * DVD, VCD and OGG/OGM subtitles with automatic language selection
    * Extensible with plugins


- `tree`:  displays an indented directory tree, in color
 Tree is a recursive directory listing command that produces a depth indented
 listing of files, which is colorized ala dircolors if the LS_COLORS environment
 variable is set and output is to tty.


- `taskset`: set or retrieve a process's CPU affinity
- `top`: display Linux processes
- `trap`: trap signals
- `truecrypt`: Free open-source disk encryption software
- `traceroute`:  Traces the route taken by packets over an IPv4/IPv6 network
 The traceroute utility displays the route used by IP packets on their way to a
 specified network (or Internet) host. Traceroute displays the IP number and
 host name (if possible) of the machines along the route taken by the packets.
 Traceroute is used as a network debugging tool. If you're having network
 connectivity problems, traceroute will show you where the trouble is coming
 from along the route.
 .
 Install traceroute if you need a tool for diagnosing network connectivity
 problems.


- `targetcli`: administration shell for storage targets
- `try-from`: test program for the tcp_wrapper
- `ts.1s`: Time Stamping Authority tool (client/server)
- `touch`: change file access and modification times
- `roff2pdf`: transform roff code into pdf mode
- `tsget.1s`: Time Stamping HTTP/HTTPS client
- `tracepath`: traces path to a network host discovering MTU
   along this path
- `transset`: Set transparency on a window
- `tcpkill`: kill TCP connections on a LAN
- `tunelp`: set various parameters for the lp device
- `trial`: run unit tests
- `tput`: change terminal characteristics
- `babel`: a converter for chemistry and molecular modeling data files
- `tset`: terminal initialization
- `tshark`:  network traffic analyzer - console version
 Wireshark is a network "sniffer" - a tool that captures and analyzes
 packets off the wire. Wireshark can decode too many protocols to list
 here.
 .
 This package provides the console version of wireshark, named
 "tshark".


- `twistd`: run Twisted applications (TACs, TAPs)
- `tload`: graphic representation of system load average
- `tmux`:  terminal multiplexer
 tmux enables a number of terminals (or windows) to be accessed and
 controlled from a single terminal like screen. tmux runs as a
 server-client system. A server is created automatically when necessary
 and holds a number of sessions, each of which may have a number of
 windows linked to it. Any number of clients may connect to a session,
 or the server may be controlled by issuing commands with tmux.
 Communication takes place through a socket, by default placed in /tmp.
 Moreover tmux provides a consistent and well-documented command
 interface, with the same syntax whether used interactively, as a key
 binding, or from the shell. It offers a choice of vim or Emacs key
 layouts.


- `tzselect`: select a timezone
- `autossh`:  Automatically restart SSH sessions and tunnels
 autossh is a program to start an instance of ssh and monitor it, restarting it
 as necessary should it die or stop passing traffic. The idea is from rstunnel
 (Reliable SSH Tunnel), but implemented in C. Connection monitoring is done
 using a loop of port forwardings. It backs off on the rate of connection
 attempts when experiencing rapid failures such as connection refused.


- `udisks-daemon`: udisks Daemon
- `udisks-tcp-bridge`: udisks TCP/IP bridge
- `tkiptun-ng`: inject a few frames into a WPA TKIP network with QoS
- `udevadm`: udev management tool
- `telinit`: Change SysV runlevel
- `ufw-framework`: using the ufw framework
- `uuidgen`: create a new UUID value
- `ucfq`: query the ucf database
- `amadmin`: administrative interface to control Amanda backups
- `csh`:  Shell with C-like syntax
 The C shell was originally written at UCB to overcome limitations in the
 Bourne shell.  Its flexibility and comfort (at that time) quickly made it
 the shell of choice until more advanced shells like ksh, bash, zsh or
 tcsh appeared.  Most of the latter incorporate features original to csh.
 .
 This package is based on current OpenBSD sources.


- `reiserfsck`: The checking tool for the ReiserFS filesystem.
- `reiserfstune`: The tunning tool for the ReiserFS filesystem.
- `udisks`: Disk Manager
- `type`: write a description of command type
- `rancid-cvs`: initialize CVS or Subversion and rancid group files and directories
- `sd`:  intuitive find and replace CLI
 sd uses Python and JavaScript style regex syntax, without the quirks
 of sed and awk. While sed can do many things, sd focuses on doing
 one thing and doing it well, has common-sense defaults and a focus
 on daily use. It's also faster.
 .
  - Find and replace expressions are separate, unlike sed:
   sd before after
   sed s/before/after/g
  - Modify files in-place:
   sd before after file.txt
   sed -i'' 's/before/after/g' file.txt
  - String-literal mode
  - Named or unnamed catch groups


- `udisksd`: The udisks system daemon
- `ulockmgr_server`: Lock Manager Server for FUSE filesystems
- `ufw`:  program for managing a Netfilter firewall
 The Uncomplicated FireWall is a front-end for iptables, to make managing a
 Netfilter firewall easier. It provides a command line interface with syntax
 similar to OpenBSD's Packet Filter. It is particularly well-suited as a
 host-based firewall.


- `dnf`:  Dandified Yum package manager
 Package manager forked from Yum, using libsolv as a dependency resolver.
 Dnf requires a working rpm installation and is meant to be used in chroots,
 see README.Debian for more information.
 .
 This package provides the dnf program.


- `ucs2any`: generate BDF fonts containing subsets of ISO 10646-1 codepoints
- `troff`: the troff processor of the groff text formatting system
- `ucf`:  Update Configuration File(s): preserve user changes to config files
 Debian policy mandates that user changes to configuration files must be
 preserved during package upgrades. The easy way to achieve this behavior
 is to make the configuration file a 'conffile', in which case dpkg
 handles the file specially during upgrades, prompting the user as
 needed.
 .
 This is appropriate only if it is possible to distribute a default
 version that will work for most installations, although some system
 administrators may choose to modify it. This implies that the
 default version will be part of the package distribution, and must
 not be modified by the maintainer scripts during installation (or at
 any other time).
 .
 This script attempts to provide conffile-like handling for files that
 may not be labelled conffiles, and are not shipped in a Debian package,
 but handled by the postinst instead. This script allows one to
 maintain files in /etc, preserving user changes and in general
 offering the same facilities while upgrading that dpkg normally
 provides for 'conffiles'.
 .
 Additionally, this script provides facilities for transitioning a
 file that had not been provided with conffile-like protection to come
 under this schema, and attempts to minimize questions asked at
 installation time. Indeed, the transitioning facility is better than the
 one offered by dpkg while transitioning a file from a non-conffile to
 conffile status.


- `pvscan`: List all physical volumes
- `cifsiostat`: Report CIFS statistics.
- `mawk`:  Pattern scanning and text processing language
 Mawk is an interpreter for the AWK Programming Language. The AWK
 language is useful for manipulation of data files, text retrieval and
 processing, and for prototyping and experimenting with algorithms. Mawk
 is a new awk meaning it implements the AWK language as defined in Aho,
 Kernighan and Weinberger, The AWK Programming Language, Addison-Wesley
 Publishing, 1988. (Hereafter referred to as the AWK book.) Mawk conforms
 to the POSIX 1003.2 (draft 11.3) definition of the AWK language
 which contains a few features not described in the AWK book, and mawk
 provides a small number of extensions.
 .
 Mawk is smaller and much faster than gawk. It has some compile-time
 limits such as NF = 32767 and sprintf buffer = 1020.


- `ucfr`: Update  Configuration  File Registry:  associate packages with
   configuration files
- `unattended-upgrade`: automatic installation of security (and other) up‐
   grades
- `vdir`: list directory contents
- `mpicc`: Compiles and links MPI programs written in C
- `unshield`:  extracts CAB files from InstallShield installers
 This software extracts CAB files from InstallShield installers
 used to be installed on Windows CE devices or Windows desktop
 machines.


- `unwrapdiff`: demangle word-wrapped patches
- `umount.ecryptfs`: eCryptfs umount helper.
- `umask`: set file mode creation mask
- `unicode_stop`: revert keyboard and console from unicode mode
- `update-apt-xapian-index`: rebuild the Apt Xapian Index
- `umount.ecryptfs_private`: eCryptfs private unmount helper.
- `ulimit`: set or report file size limit
- `unicode_start`: put keyboard and console in unicode mode
- `umount`: unmount file systems
- `update-binfmts`: maintain registry of executable binary formats
- `update-ca-certificates`: update /etc/ssl/certs and ca-certificates.crt
- `unlink`: call the    unlink () function
- `update-catalog`: create or update entry in SGML catalog file
- `update-cracklib`: Regenerate cracklib dictionary
- `update-default-ispell`: update default ispell dictionary
- `update-default-wordlist`: update default wordlist
- `update-dictcommon-aspell`: rebuild aspell database and emacsen stuff
- `update-gconf-defaults`: generate GConf defaults shipped in Debian packages
- `update-dictcommon-hunspell`: rebuild hunspell database and emacsen
   stuff
- `update-fonts-alias`: compile fonts.alias files
- `update-icon-caches.gtk2`: Update wrapper script for the icon caches
- `update-fonts-dir`: compile fonts.dir files
- `update-info-dir`: update or create index file from all installed info files in directory
- `update-fonts-scale`: generate fonts.scale files
- `update-grub`: stub for grub-mkconfig
- `update-icon-caches`: Update wrapper script for the icon caches
- `unalias`: remove alias definitions
- `update-inetd`:  inetd configuration file updater
 This package provides a program used by other packages to
 automatically update /etc/inetd.conf, the configuration file shared
 by all implementations of the Internet super-server.
 .
 Note that xinetd is not supported by this package.


- `update-initramfs`: generate an initramfs image
- `update-python-modules`: byte-compile python modules
- `update-java-alternatives`: update  alternatives for jre/sdk installa‐
   tions
- `update-usbids`: download new version of the USB ID list
- `unrar`:  Unarchiver for .rar files (non-free version)
 Unrar can extract files from .rar archives. If you want to create .rar
 archives, install package rar.


- `unrar-nonfree`: extract files from rar archives
- `unix_chkpwd`: Helper binary that verifies the password of the current user
- `upstart-dbus-bridge`: Bridge between Upstart and D-Bus
- `upstart-event-bridge`: Bridge between system Upstart and session Upstart
- `upstart-file-bridge`: Bridge between Upstart and inotify
- `upstart-local-bridge`: Bridge between Upstart and a local client socket connection.
- `upstart-socket-bridge`: Bridge between Upstart and sockets
- `upstart-udev-bridge`: Bridge between Upstart and udev
- `unopkg`: LibreOffice Extension Manager
- `ureadahead`: Read files in advance during boot
- `update-alternatives`: maintain  symbolic  links  determining  default
   commands
- `update-mime`: create or update MIME information
- `update-passwd`: safely update /etc/passwd, /etc/shadow and /etc/group
- `usb_printerid`: prints the ID of the printer on a USB port
- `unzip`:  De-archiver for .zip files
 InfoZIP's unzip program. With the exception of multi-volume archives
 (ie, .ZIP files that are split across several disks using PKZIP's /& option),
 this can handle any file produced either by PKZIP, or the corresponding
 InfoZIP zip program.
 .
 This version supports encryption.


- `mpirun`: mpirun - Run mpi programs
- `update-desktop-database`: Build cache database of MIME types handled by desktop files
- `update-pciids`: download new version of the PCI ID list
- `update-rc.d`: install and remove System-V style init script links
- `updatedb`: update a database for mlocate
- `mpiexec`: Execute serial and parallel jobs in Open MPI.Note
- `zic`: timezone compiler
- `byobu`:  text window manager, shell multiplexer, integrated DevOps environment
 Byobu is Ubuntu's powerful text-based window manager, shell multiplexer, and
 integrated DevOps environment.
 .
 Using Byobu, you can quickly create and move between different windows
 over a single SSH connection or TTY terminal, split each of those windows into
 multiple panes, monitor dozens of important statistics about your system,
 detach and reattach to sessions later while your programs continue to run in
 the background.


- `upower`:  abstraction for power management
 upower provides an interface to enumerate power sources on the system
 and control system-wide power management. Any application can access the
 org.freedesktop.UPower service on the system message bus. Some
 operations (such as suspending the system) are restricted using PolicyKit.


- `uname`: get name and information about current kernel
- `uvccapture`:  USB UVC Video Class snapshot software
 The purpose of this software is to capture an image from a USB webcam at a
 specified interval, and save it to a JPEG file, no other formats are supported.
 .
 Right now this software is really a hack, since still image support is not yet
 available in the UVC driver. The program continually polls the UVC driver in
 MJPEG mode, and at a specified interval writes a JPEG header and a single frame
 to file, creating a JPEG image.


- `uz`: gunzips and extracts a gzip'd tar'd archive
- `vbetool`:  run real-mode video BIOS code to alter hardware state
 vbetool uses lrmi in order to run code from the video BIOS. Currently, it
 is able to alter DPMS states, save/restore video card state and attempt to
 initialize the video card from scratch.


- `usb-devices`: print USB device details
- `wump`: hunt the wumpus in an underground cave
- `wtf`: translates acronyms for you
- `worms`: animate worms on a display terminal
- `worm`: Play the growing worm game
- `wargames`: shall we play a game?
- `trek`: trekkie game
- `tetris-bsd`: the game of tetris
- `teachgammon`: the game of backgammon teachgammon
- `sudoku`:  console based sudoku
 This sudoku puzzle generator/solver features:
  * character based (curses) interface;
  * cross-platform (Minix, Unix, Windows) with full source code (ANSI C);
  * generates hints upon request;
  * classification of board difficulty (very easy, easy, medium, hard or
    fiendish);
  * generation of new boards;
  * easy entry of boards published in newspapers, Internet, ...;
  * multiple output formats (text, csv, HTML, PostScript).


- `spellcast`: a game of duelling wizards
- `snscore`: display chase game
- `snake`: display chase game
- `sail`: multi-user wooden ships and iron men
- `rot13`: decrypt caesar ciphers
- `robots`: fight off villainous robots
- `robotfindskitten`:  Zen Simulation of robot finding kitten
 In this simulation, you play the part of robot. Your task is to
 complete the simulation by finding kitten, as is your destiny, and
 indeed your wont.  You (robot) are represented by the # character, and
 you move around with the arrow keys touching things.  If the thing you
 touch is kitten, you get a cute little animation (which was cuter in
 the DOS version) and the simulation ends. Otherwise, you get a brief
 description of what it is you touched.


- `recover`: recover a NetHack game interrupted by disaster
- `make`:  utility for directing compilation
 GNU Make is a utility which controls the generation of executables
 and other target files of a program from the program's source
 files. It determines automatically which pieces of a large program
 need to be (re)created, and issues the commands to (re)create
 them. Make can be used to organize any task in which targets (files)
 are to be automatically updated based on input files whenever the
 corresponding input is newer --- it is not limited to building
 computer programs. Indeed, Make is a general purpose dependency
 solver.


- `rain`: animated raindrops display
- `quiz`: random knowledge tests
- `primes`: generate primes
- `ppt`: reformat input as punch cards, paper tape or morse code
- `pom`: display the phase of the moon
- `pig`: eformatray inputway asway Igpay Atinlay
- `phantasia`: an interterminal fantasy game
- `pacman4console`:  ncurses-based pacman game
 Pacman4Console is a simple pacman game for the terminal.
 It is played on the command-line, with ASCII character graphics.
 .
 It has nine levels by default, and you can make your own with
 its own level editor.


- `number`: convert Arabic numerals to English
- `nudoku`:  ncurses based sudoku games
 This is an ncurses based Sudoku variant.


- `nsnake`:  classic snake game on the terminal
 nsnake is a clone of the snake game found on old cellphones. It is
 played on the command-line with textual interface, thanks to ncurses.
 .
 Features high-scores, several game modes, a GUI-like interface and
 custom levels.


- `ninvaders`:  A space invaders-like game using ncurses
 A Space Invaders type game with text-only graphics.  Ever wanted to play
 space invaders when you can't find a GUI?  Now you can.


- `netris`: networked version of tetris
- `netris-sample-robot`: sample robot for netris
- `nethack`: Exploring The Mazes of Menace
- `nethack-console`:  dungeon crawl game - text-based interface
 NetHack is a wonderfully silly, yet quite addictive, Dungeons &
 Dragons-style adventure game. You play a character from one of many
 classes (such as wizard, ranger, or tourist), fighting your way down to
 retrieve the Amulet of Yendor (try saying THAT one backwards!) for your
 god. On the way, you might encounter a quantum mechanic or two, or
 perhaps King Arthur, or - if you're REALLY lucky - the Ravenous
 Bugblatter Beast of Traal.
 .
 You should install a front-end for NetHack if you
 wish to play the game.  Each of them includes the
 original non-graphical version, and they can all be installed
 at the same time:
  - nethack-console: no graphics, just plain NetHack;
  - nethack-x11    : original X11/Athena-based graphical version;
  - nethack-qt     : Qt version.
 .
 This package provides the plain console version of NetHack.


- `morse`:  training program about morse-code for aspiring radio hams
 It can generate random tests or simulated QSOs resembling those
 used in the ARRL test (a QSO generator is included). There are a
 plethora of options to vary the training method. In one of the simpler
 modes, this program will take text from standard input and render it
 as Morse-code beeps.


- `moon-buggy`:  Drive a car across the moon
 Moon-buggy is a simple character graphics game, where you drive some
 kind of car across the moon's surface.  Unfortunately there are
 dangerous craters there.  Fortunately your car can jump over them!


- `monop`: Monopoly game
- `mille`: play Mille Bornes
- `lev_comp`: NetHack special levels compiler
- `huntd`: hunt daemon, back-end for hunt game
- `hunt`:  advanced packet sniffer and connection intrusion
 Hunt is a program for intruding into a connection, watching it and
 resetting it. With the transproxy auxiliary software, which provides
 a transparent proxy in the Linux kernel. Another auxiliary software
 present in the hunt is tpserv, this program implements a proxy.
 .
 Can be used as Pentest tool to enhance the security of the network.
 .
 Note that as hunt is operating on Ethernet, it is best used for connections
 which can be watched through it. However, it is possible to do something
 even for hosts on another segments or hosts that are on switched ports.


- `hangman`: computer version of the game hangman
- `hack`: exploring The Dungeons of Doom
- `greed`:  curses-based clone of the DOS free-ware game Greed
 This is a curses-based clone of the DOS free-ware game Greed. The goal
 of this game is to try to eat as much as possible of the board before
 munching yourself into a corner.


- `gomoku`: game of 5 in a row
- `go-fish`: play ``Go Fish ''
- `dlb`: NetHack data librarian
- `dgn_comp`: NetHack dungeon compiler
- `dab`: Dots and Boxes game
- `cribbage`: the card game cribbage
- `countmail`: be obnoxious about how much mail you have
- `cfscores`: the solitaire card game canfield
- `canfield`: the solitaire card game canfield
- `caesar`: decrypt caesar ciphers
- `bsdgames-adventure`: an exploration game
- `boggle`: word search game
- `bcd`: reformat input as punch cards, paper tape or morse code
- `checkpc`: check out the printcap database
- `sshd`: OpenSSH SSH daemon
- `ip`: show / manipulate routing, network devices, interfaces and tunnels
- `scrot`:  command line screen capture utility
 scrot (SCReenshOT)is a simple command line screen capture utility.
 It uses imlib2 to grab and save images.
 .
 scrot has many useful features:
   - Support for multiple image formats: JPG, PNG, GIF, and others.
   - The screenshot's quality is configurable.
   - It is possible to capture a specific window or a rectangular
     area on the screen.
   - Other features.
 .
 Because scrot is a command line utility, it can easily be scripted
 and put to novel uses. For instance, scrot can be used to monitor a
 desktop PC in absence and register unwanted activities.


- `lwp-request`: Simple command line user agent
- `oscap`: OpenSCAP command line tool
- `firewall-cmd`: firewalld command line client
- `ip-address`: protocol address management
- `netwatch`: Ethernet Internet Protocol Monitor
- `gradle`:  Powerful build system for the JVM
 Gradle is a build tool with a focus on build automation and support for
 multi-language development. If you are building, testing, publishing, and
 deploying software on any platform, Gradle offers a flexible model that can
 support the entire development lifecycle from compiling and packaging code to
 publishing web sites. Gradle has been designed to support build automation
 across multiple languages and platforms including Java, Scala, Android, C/C++,
 and Groovy, and is closely integrated with development tools and continuous
 integration servers including Eclipse, IntelliJ, and Jenkins.


- `macof`: flood a switched LAN with random MAC addresses
- `screenfetch`:  Bash Screenshot Information Tool
 screenFetch is a "Bash Screenshot Information Tool". This handy Bash script
 can be used to generate one of those nifty terminal theme information + ASCII
 distribution logos you see in everyone's screenshots nowadays.
 .
 It will auto-detect your distribution and display an ASCII version of that
 distribution's logo and some valuable information to the right. There are
 options to specify no ascii art, colors, taking a screenshot upon displaying
 info, and even customizing the screenshot command.


- `add-shell`: add shells to the list of valid login shells
- `autoconf`:  automatic configure script builder
 The standard for FSF source packages.  This is only useful if you
 write your own programs or if you extensively modify other people's
 programs.
 .
 For an extensive library of additional Autoconf macros, install the
 `autoconf-archive' package.
 .
 This version of autoconf is not compatible with scripts meant for
 Autoconf 2.13 or earlier.


- `automake`:  Tool for generating GNU Standards-compliant Makefiles
 Automake is a tool for automatically generating `Makefile.in's from
 files called `Makefile.am'.
 .
 The goal of Automake is to remove the burden of Makefile maintenance
 from the back of the individual GNU maintainer (and put it on the back
 of the Automake maintainer).
 .
 The `Makefile.am' is basically a series of `make' macro definitions
 (with rules being thrown in occasionally).  The generated
 `Makefile.in's are compliant with the GNU Makefile standards.


- `tdbdump`: tool for printing the contents of a TDB file
- `acccheck`: Password dictionary attack tool that targets windows authentication via the SMB protocol
- `besside-ng-crawler`: filter  EAPOL frames from a directory of capture
   files.
- `drill`: get (debug) information out of DNS(SEC)
- `dig`: DNS lookup utility
- `dirsplit`: splits directory into multiple with equal size
- `dir`: list directory contents
- `gtf`: calculate VESA GTF mode lines
- `makeivs-ng`: generate a dummy IVS dump file with a specific WEP key
- `ntfsprogs`: tools for doing neat things with NTFS
- `ipcalc`:  parameter calculator for IPv4 addresses
 ipcalc takes an IPv4 address and netmask and calculates the resulting
 broadcast, network, Cisco wildcard mask, and host range. By giving a
 second netmask, you can design sub- and supernetworks. It is also
 intended to be a teaching tool and presents the results as
 easy-to-understand binary values.
 .
 Originally, ipcalc was intended for use from the shell prompt, but a
 CGI wrapper is provided to enable colorful HTML display through a
 webserver.
 You can find it in /usr/share/doc/ipcalc/examples directory.


- `vxdg`: manage Veritas Volume Manager (VxVM) disk groups
- `chkconfig`: updates and queries runlevel information for system services
- `npm`:  package manager for Node.js
 Node.js is an event-based server-side javascript engine.
 .
 npm is the package manager for the Node JavaScript platform.  It puts
 modules in place so that node can find them, and manages dependency
 conflicts intelligently.
 .
 It is extremely configurable to support a wide variety of use cases.
 Most commonly, it is used to publish, discover, install, and develop
 node programs.
 .
 Install also node-opener to have full npm features enabled.


- `command`: execute a simple command
- `ntfscluster`: identify files in a specified region of an NTFS volume.
- `lvmsar`: LVM system activity reporter
- `aptitude`:  terminal-based package manager
 aptitude is a package manager with a number of useful features,
 including: a mutt-like syntax for matching packages in a flexible
 manner, dselect-like persistence of user actions, the ability to
 retrieve and display the Debian changelog of most packages, and a
 command-line mode similar to that of apt-get.
 .
 aptitude is also Y2K-compliant, non-fattening, naturally cleansing,
 and housebroken.


- `a2enmod`: enable or disable an apache2 module
- `adduser`:  add and remove users and groups
 This package includes the 'adduser' and 'deluser' commands for creating
 and removing users.
 .
  - 'adduser' creates new users and groups and adds existing users to
    existing groups;
  - 'deluser' removes users and groups and removes users from a given
    group.
 .
 Adding users with 'adduser' is much easier than adding them manually.
 'Adduser' will choose UID and GID values that conform to Debian policy,
 create a home directory, copy skeletal user configuration, and
 automate setting initial values for the user's password, real name
 and so on.
 .
 'Deluser' can back up and remove users' home directories
 and mail spool or all the files they own on the system.
 .
 A custom script can be executed after each of the commands.
 .
 'Adduser' and 'Deluser' are intended to be used by the local
 administrator in lieu of the tools from the 'useradd' suite, and
 they provide support for easy use from Debian package maintainer
 scripts, functioning as kind of a policy layer to make those scripts
 easier and more stable to write and maintain.


- `aireplay-ng`: inject packets into a wireless network to generate traffic
- `airmon-ng`: POSIX sh script designed to turn wireless cards into moni‐
   tor mode.
- `airbase-ng`: multi-purpose tool aimed at attacking clients as opposed
   to the Access Point (AP) itself
- `biosdecode`: BIOSinformation decoder
- `awk`: pattern scanning and processing language
- `Xserver`: X Window System display server
- `arpd`: userspace arp daemon.
- `du`: estimate file space usage
- `tarcat`: concatenates the pieces of a GNU tar multi-volume archive
- `vgremove`: Remove volume group(s)
- `NetworkManager`: network management daemon
- `lvreduce`: Reduce the size of a logical volume
- `ophcrack-cli`:  Microsoft Windows password cracker using rainbow tables (cmdline)
 Ophcrack is a Windows password cracker based on a time-memory trade-off
 using rainbow tables. This is a new variant of Hellman's original trade-off,
 with better performance. It recovers 99.9% of alphanumeric passwords in
 seconds.
 .
 It works for Windows NT/2000/XP/Vista/7.
 .
 This package contains ophcrack with command line interface only.


- `whois`:  intelligent WHOIS client
 This package provides a commandline client for the WHOIS (RFC 3912)
 protocol, which queries online servers for information such as contact
 details for domains and IP address assignments.
 It can intelligently select the appropriate WHOIS server for most queries.
 .
 The package also contains mkpasswd, a features-rich front end to the
 password encryption function crypt(3).


- `john`:  active password cracking tool
 John the Ripper is a tool designed to help systems administrators to
 find weak (easy to guess or crack through brute force) passwords, and
 even automatically mail users warning them about it, if it is desired.
 .
 Besides several crypt(3) password hash types most commonly found on
 various Unix flavors, supported out of the box are Kerberos AFS and
 Windows NT/2000/XP/2003 LM hashes, plus several more with contributed
 patches.


- `sum`: checksum and count the blocks in a file
- `steamcmd`:  Command-line interface for Valve's Steam
 Steam (http://www.steampowered.com) is a software content delivery system
 developed by Valve software (http://www.valvesoftware.com).  There is
 some free software available, but for the most part the content delivered
 is non-free.
 .
 The Steam Console Client or SteamCMD is a command-line version
 of the Steam client. Its primary use is to install and update various
 dedicated servers available on Steam using a command-line interface.
 .
 This package comes with a fairly substantial non-free license agreement
 that must be accepted before installing the software.  If you have any
 opposition to non-free work, please select "I DECLINE" during the package
 installation dialogs.


- `airodump-ng`: a wireless packet capture tool for aircrack-ng
- `rcs`:  The GNU Revision Control System
 The Revision Control System (RCS) manages multiple
 revisions of files. RCS automates the storing, retrieval,
 logging, identification, and merging of revisions. RCS is
 useful for text that is revised frequently, for example
 programs, documentation, graphics, papers, and form letters.
 .
 Note: this package contains certain general-purpose commands
 (such as merge or ident) which may used by other programs
 installed on your system.


- `xsubpp`: compiler to convert Perl XS code into C code
- `ngettext`: translate message and choose plural form
- `e2fsck`: check a Linux ext2/ext3/ext4 file system
- `useradd`: create a new user or update default new user information
- `swatch`:  Log file viewer with regexp matching, highlighting & hooks
 Swatch is designed to monitor system activity.  It reads a configuration
 file which contains pattern(s) to look for and action(s) to perform when
 each pattern is found.
 .
 A typical action is echoing the matched line in a variety of colours and
 formats including reverse video, bold, underline, and normal, which swatch
 knows how to do internally.  Other actions include sending mail or
 executing an arbitrary program on the line.
 .
 Swatch is written in Perl and uses Perl regular expressions for line
 matching.


- `dhcpd`: Dynamic Host Configuration Protocol Server
- `ntop`: display top network users
- `snap`:  location of genes from DNA sequence with hidden markov model
 SNAP is a general purpose gene finding program suitable for both eukaryotic
 and prokaryotic genomes. SNAP is an acroynm for Semi-HMM-based Nucleic Acid
 Parser.


- `screen`:  terminal multiplexer with VT100/ANSI terminal emulation
 GNU Screen is a terminal multiplexer that runs several separate "screens" on
 a single physical character-based terminal. Each virtual terminal emulates a
 DEC VT100 plus several ANSI X3.64 and ISO 2022 functions. Screen sessions
 can be detached and resumed later on a different terminal.
 .
 Screen also supports a whole slew of other features, including configurable
 input and output translation, serial port support, configurable logging,
 and multi-user support.


- `crontab`: files used to schedule the execution of programs
- `mount`:  tools for mounting and manipulating filesystems
 This package provides the mount(8), umount(8), swapon(8),
 swapoff(8), and losetup(8) commands.


- `beef`:  flexible Brainfuck interpreter
 Beef is an interpreter for the Brainfuck programming language.
 .
 Its main goals are to be comfortable for the user and to run most
 Brainfuck programs unchanged; speed is generally quite good.
 .
 Beef performs thorough error checking to make sure malformed programs are
 not executed; it also supports a bunch of command-line options that can be
 used for configuration or compatibility purposes.
 .
 If GVFS is installed, Beef can use any available backend as either output
 or (where it makes sense) input source. GNU readline is used for
 interactive input.


- `setoolkit`: The Social-Engineer Toolkit
- `keepnote`: cross-platform note-taking and organization application
- `chvt`: change foreground virtual terminal
- `iwgetid`: Report ESSID, NWID or AP/Cell Address of wireless network
- `masscan`:  TCP port scanner
 MASSCAN is TCP port scanner which transmits SYN packets
 asynchronously and produces results similar to nmap,
 the most famous port scanner. Internally, it operates
 more like scanrand, unicornscan, and ZMap, using
 asynchronous transmission.
 It's a flexible utility that allows arbitrary address and
 port ranges.


- `msfconsole`: Metasploit Framework Console
- `ntfsinfo`: dump a file's attributes
- `objdump`: display information from object files.
- `pycompile`: byte compile Python source files
- `slabtop`: display kernel slab cache information in real time
- `ps2ascii`: Ghostscript translator from PostScript or PDF to ASCII
- `rcrack`: Hash Cracking with Rainbow Tables
- `basename`: return non-directory portion of a pathname
- `braa`:  Mass SNMP scanner
 Braa is a mass snmp scanner. The intended usage of such a tool is of course
 making SNMP queries - but unlike snmpget or snmpwalk from net-snmp, it is able
 to query dozens or hundreds of hosts simultaneously, and in a single process.
 Thus, it consumes very few system resources and does the scanning VERY fast.
 .
 Braa implements its OWN snmp stack, so it does NOT need any SNMP libraries
 like net-snmp. The implementation is very dirty, supports only several data
 types, and in any case cannot be stated 'standard-conforming'! It was designed
 to be fast, and it is fast. For this reason (well, and also because of author
 laziness ;), there is no ASN.1 parser in braa - the user HAVE to know the
 numerical values of OID's
 (for instance .1.3.6.1.2.1.1.5.0 instead of system.sysName.0).


- `cewl`:  custom word list generator
 CeWL (Custom Word List generator) is a ruby app which spiders
 a given URL, up to a specified depth, and returns a list of
 words which can then be used for password crackers such as John
 the Ripper. Optionally, CeWL can follow  external links.
 .
 CeWL can also create a list of email addresses found in mailto
 links. These email addresses can be used as usernames in brute
 force actions.
 .
 Another tool provided by CeWL project is FAB (Files Already
 Bagged). FAB extracts the content of the author/creator fields,
 from metadata of the some files, to create lists of possible
 usernames. These usernames can be used in association with the
 password list generated by CeWL. FAB uses the same metadata
 extraction techniques that CeWL. Currently, FAB process Office
 pre 2007, Office 2007 and PDF formats.
 .
 CeWL is useful in security tests and forensics investigations.
 CeWL is pronounced "cool".


- `file`:  Recognize the type of data in a file using "magic" numbers
 The file command is "a file type guesser", a command-line tool that
 tells you in words what kind of data a file contains.
 .
 This package contains the file program itself.


- `fping`:  sends ICMP ECHO_REQUEST packets to network hosts
 fping is a ping like program which uses the Internet Control Message Protocol
 (ICMP) echo request to determine if a target host is responding.  fping
 differs from ping in that you can specify any number of targets on the command
 line, or specify a file containing the lists of targets to ping.  Instead of
 sending to one target until it times out or replies, fping will send out a
 ping packet and move on to the next target in a round-robin fashion.


- `vgrename`: Rename a volume group
- `dpkg-query`: a tool to query the dpkg database
- `ed`:  classic UNIX line editor
 ed is a line-oriented text editor.  It is used to
 create, display, modify and otherwise manipulate text
 files.
 .
 red is a restricted ed: it can only edit files in the
 current directory and cannot execute shell commands.


- `lspgpot`: extracts  the  ownertrust values from PGP keyrings and list
   them in GnuPG ownertrust format.
- `mitmproxy`:  SSL-capable man-in-the-middle HTTP proxy
 mitmproxy is an interactive man-in-the-middle proxy for HTTP and HTTPS. It
 provides a console interface that allows traffic flows to be inspected and
 edited on the fly.
 .
 Also shipped is mitmdump, the command-line version of mitmproxy, with
 the same functionality but without the frills. Think tcpdump for
 HTTP.
 .
 Features:
  - intercept and modify HTTP and HTTPS requests and responses and modify them
    on the fly
  - save HTTP conversations for later replay and analysis
  - replay the client-side of an HTTP conversation
  - reverse proxy mode to forward traffic to a specified server
  - transparent proxy mode on OSX and Linux
  - make scripted changes to HTTP traffic using Python
  - SSL/TLS certificates for interception are generated on the fly
  - ...
 .
 This package contains the python-pathod module (previously
 provided by other source package). The python-netlib module was also included
 but it has been dropped by upstream in version 1.0.


- `mount.fuse`: format and options for the fuse file systems
- `halt`: Halt, power-off or reboot the machine
- `fd`: floppy disk device
- `yersinia`:  Network vulnerabilities check software
 Yersinia is a framework for performing layer 2 attacks. It is designed
 to take advantage of some weakeness in different network protocols. It
 pretends to be a solid framework for analyzing and testing the deployed
 networks and systems.
 .
 Attacks for the following network protocols are implemented in this
 particular release:
  - Spanning Tree Protocol (STP).
  - Cisco Discovery Protocol (CDP).
  - Dynamic Trunking Protocol (DTP).
  - Dynamic Host Configuration Protocol (DHCP).
  - Hot Standby Router Protocol (HSRP).
  - 802.1q.
  - 802.1x.
  - Inter-Switch Link Protocol (ISL).
  - VLAN Trunking Protocol (VTP).


- `ndctl`:  Utility for managing the nvdimm subsystem
 The nvdimm subsystem defines a kernel device model and control message
 interface for platform NVDIMM resources like those defined by the ACPI 6+ NFIT
 (NVDIMM Firmware Interface Table).
 .
 This package contains a utility for managing the nvdimm (non-volatile memory
 device) subsystem in the Linux kernel.


- `hg`: Mercurial source code management system
- `setvesablank`: Turn VESA screen blanking on or off
- `mailx`: process messages
- `thc-ipv6`:  The Hacker Choice's IPv6 Attack Toolkit
 Attack toolkit for testing IPv6 and ICMPv6 protocol weaknesses.
 .
 Some of the tools included:
 .
 alive6: an effective alive scanning.
 .
 denial6: try a collection of denial-of-service tests against a
 target.
 .
 detect-new-ip6: detect new ip6 devices which join the network.
 .
 dnsdict6: parallelized dns ipv6 dictionary bruteforcer.
 .
 dos-new-ip6: detect new ip6 devices and tell them that their chosen
 IP collides on the network (DOS).
 .
 exploit6: test known ipv6 vulnerabilities against a target.
 .
 fake_mld6: announce yourself in a multicast group of your choice on
 the net.
 .
 fake_router6: announce yourself as a router on the network.
 .
 flood_advertise6: flood a target with random neighbor advertisements.
 .
 flood_router6: flood a target with random router advertisements.
 .
 implementation6: performs various implementation checks on ipv6.
 .
 parasite6: icmp neighbor solitication/advertisement spoofer.
 .
 redir6: redirect traffic to you intelligently (man-in-the-middle)
 with a clever icmp6 redirect spoofer.
 .
 rsmurf6: remote smurfer (known to work only against Linux at the
 moment).
 .
 thcping6: sends a hand crafted ping6 packet.
 .
 toobig6: mtu decreaser with the same intelligence as redir6.


- `cfdisk`: display or manipulate a disk partition table
- `giskismet`: a program to visually represent the Kismet data in a flexible manner.
- `jobs`: display status of jobs in the current session
- `kerberos`: Overview of using Kerberos
- `makepkg`:  Arch Linux package build utility
 makepkg is a script to automate the building of packages. The
 requirements for using the script are a build-capable *nix platform
 and a custom build script for each package you wish to build (known
 as a PKGBUILD).


- `view`: screen oriented (visual) display editor based on ex
- `as`: the portable GNU assembler.
- `pulseaudio`:  PulseAudio sound server
 PulseAudio, previously known as Polypaudio, is a sound server for POSIX and
 WIN32 systems. It is a drop in replacement for the ESD sound server with
 much better latency, mixing/re-sampling quality and overall architecture.
 .
 These are some of PulseAudio's features:
 .
   * High quality software mixing of multiple audio streams with support for
     more than one sink/source. May be used to combine multiple sound cards
     into one (with sample rate adjustment).
 .
   * Wide range of supported client libraries. ESD, ALSA, oss, libao and
     GStreamer client applications are supported as-is. Native PulseAudio
     plug-ins are also available for xmms and mplayer.
 .
   * Good low latency behaviour and very accurate latency measurement for
     playback and recording. Ability to fully synchronize multiple playback
     streams.
 .
   * Network transparency, allowing an application to play back or record
     audio on a different machine than the one it is running on.
 .
   * Extensible plug-in architecture with plug-ins for jackd, multicast-rtp
     lirc and avahi, just to name a few.
 .
 This package contains the daemon and basic module set.


- `history`: GNU History Library
- `termineter`:  Smart meter testing framework
 This package contains a Python framework which provides a platform for the
 security testing of smart meters.  It implements the C1218 and C1219 protocols
 for communication over an optical interface.  Currently supported are Meters
 using C1219-2007 with 7-bit character sets.  This is the most common
 configuration found in North America.  Termineter communicates with Smart
 Meters via a connection using an ANSI type-2 optical probe with a serial
 interface.


- `beef-xss`:  Browser Exploitation Framework (BeEF)
 BeEF is short for The Browser Exploitation Framework. It is a penetration
 testing tool that focuses on the web browser.
 .
 Amid growing concerns about web-born attacks against clients, including
 mobile clients, BeEF allows the professional penetration tester to assess the
 actual security posture of a target environment by using client-side attack
 vectors. Unlike other security frameworks, BeEF looks past the hardened
 network perimeter and client system, and examines exploitability within the
 context of the one open door: the web browser. BeEF will hook one or more web
 browsers and use them as beachheads for launching directed command modules and
 further attacks against the system from within the browser context.


- `steam`:  Transitional package for Steam
 Steam (https://www.steampowered.com) is a software content delivery system
 developed by Valve software (https://www.valvesoftware.com).  There is
 some free software available, but for the most part the content delivered
 is non-free.
 .
 This transitional package upgrades from the old steam package to the
 newer steam-installer package.


- `mpc`:  command-line tool to interface MPD
 MPC, music player command, is a command line tool to interface MPD, Music
 Player Daemon.  It is fast and lightweight like MPD, making it ideal for
 scripting commands and binding to hotkeys.  Completion for the Bash shell
 is provided.


- `msfpc`:  MSFvenom Payload Creator (MSFPC)
 A quick way to generate various "basic" Meterpreter payloads using msfvenom
 which is part of the Metasploit framework.


- `zangband`:  A single-player, text-based, roguelike game
 Zangband is a single-player, roguelike game, based on Angband. Like
 Angband, Zangband features unique foes, artifacts, monster pits and
 vaults.  Additionally, Zangband offers a new spell system (life,
 sorcery, nature, chaos, death magic), a different monster list,
 speaking unique foes, rumours, warrants, new ego items, backstabbing
 from rogues, poisoned weapons, and much more.


- `lynis`:  security auditing tool for Unix based systems
 Lynis is an auditing tool for hardening GNU/Linux and Unix based systems.
 It scans the system configuration and creates an overview of system information
 and security issues usable by professional auditors.
 It can assist in automated audits.
 .
 Lynis can be used in addition to other software, like security
 scanners, system benchmarking and fine-tuning tools.


- `topas`: Reports selected local system statistics
- `most`:  Pager program similar to more and less
 Most is a paging program that displays, one windowful at a time, the
 contents of a file on a terminal. A status line at the bottom of the
 screen displays the file name, the current line number and the percentage
 of the file so far displayed.
 .
 Unlike other paging programs, most is capable of displaying an
 arbitrary number of windows as long as they all fit on the screen, and
 different windows could be used to view the same file in different
 positions.
 .
 In addition to displaying ordinary text files, most can also display
 binary files as well as files with arbitrary ascii characters.


- `yum-config-manager`: manage yum configuration options and yum repositories
- `transmission-gtk`:  lightweight BitTorrent client (GTK+ interface)
 Transmission is a set of lightweight BitTorrent clients (in GUI, CLI
 and daemon form). All its incarnations feature a very simple, intuitive
 interface on top on an efficient, cross-platform back-end.
 .
 This package contains the GTK+ stand-alone client.


- `pkg`: manipulate packages
- `ffprobe`: ffprobe media prober
- `c89-gcc`: ANSI (1989) C compiler
- `xzless`: view xz or lzma compressed (text) files
- `7zr`: A file archiver with highest compression ratio
- `imapsync`: IMAP synchronisation, sync, copy or migration tool. Synchronise mailboxes between two imap servers. Good at IMAP migration. More than 44 different IMAP server softwares supported with success. $Revision: 1.525 $
- `rc-update`: add and remove services to and from a runlevel
- `nft`: Administration tool of the nftables framework for packet filtering and classification
- `pcidump`: show PCI device data
- `sex`: extract a source catalog from an astronomical FITS image
- `ar`: create and maintain library archives
- `fuck`: magnificent app which corrects your previous console command
- `fluxion`: security auditing and social-engineering research tool
- `ssmtp`:  extremely simple MTA to get mail off the system to a mail hub
 A secure, effective and simple way of getting mail off a system to your
 mail hub. It contains no suid-binaries or other dangerous things - no mail
 spool to poke around in, and no daemons running in the background. Mail is
 simply forwarded to the configured mailhost. Extremely easy configuration.
 .
 WARNING: the above is all it does; it does not receive mail, expand aliases
 or manage a queue. That belongs on a mail hub with a system administrator.


- `dhcpdump`:  Parse DHCP packets from a network interface
 This package provides a tool for visualization of DHCP packets
 on a network interface to analyze DHCP client requests and
 server responses.


- `shellinaboxd`: publish command line shell through AJAX interface
- `nmap`:  The Network Mapper
 Nmap is a utility for network exploration or security auditing. It
 supports ping scanning (determine which hosts are up), many port
 scanning techniques, version detection (determine service protocols
 and application versions listening behind ports), and TCP/IP
 fingerprinting (remote host OS or device identification). Nmap also
 offers flexible target and port specification, decoy/stealth scanning,
 sunRPC scanning, and more. Most Unix and Windows platforms are
 supported in both GUI and commandline modes. Several popular handheld
 devices are also supported, including the Sharp Zaurus and the iPAQ.


- `hcitool`: configure Bluetooth connections
- `iptables-save`: dump iptables rules  ip6tables-save  dump iptables rules
- `zypper`:  command line software manager using libzypp
 Zypper is a command line tool for managing software. It can be used to add
 package repositories, search for packages, install, remove, or update packages,
 install patches, hardware drivers, verify dependencies, and more.
 Zypper can be used interactively or non-interactively by user, from scripts,
 or front-ends.


- `zlib-flate`: raw zlib compression program
- `unset`: unset values and attributes of variables and functions
- `pfbtopfa`: Convert Postscript .pfb fonts to .pfa format using ghostscript
- `ip-tunnel`: tunnel configuration
- `yaourt`: more than a frontend to pacman
- `finch`:  text-based multi-protocol instant messaging client
 Finch is a text/console-based, modular instant messaging client capable of
 using multiple networks at once.  Currently supported out of the box are:
 Jabber/XMPP, Bonjour, Gadu-Gadu, IRC, Novell GroupWise Messenger, Lotus
 Sametime, SIMPLE, and Zephyr. It can support many more with plugins.
 .
 Some extra packages are suggested to use increased functionality:
  * libx11-6
    - To use the Clipboard and/or Toaster plugins.


- `quotacheck`: scan a filesystem for disk usage, create, check and repair quota files
- `katoolin`: Automatically install all Kali linux tools
- `docker`: Docker image and container command line interface
- `xsetroot`: root window parameter setting utility for X
- `sysbench`:  multi-threaded benchmark tool for database systems
 SysBench is a modular, scriptable and multi-threaded benchmark tool based on
 LuaJIT. It is most frequently used for database benchmarks, but can also be
 used to create arbitrarily complex workloads that do not involve a database
 server.
 .
 The idea of this benchmark suite is to quickly get an impression about system
 performance without setting up complex database benchmarks or even without
 installing a database at all.
 .
 Current features allow one to test the following system parameters:
 .
  * file I/O performance
  * scheduler performance
  * memory allocation and transfer speed
  * POSIX threads implementation performance
  * database server performance (OLTP benchmark)
 .
 Primarily written for MySQL server benchmarking, SysBench will be further
 extended to support multiple database backends, distributed benchmarks and
 third-party plug-in modules.


- `ncdu`:  ncurses disk usage viewer
 Ncdu is a ncurses-based du viewer. It provides a fast and easy-to-use interface
 through famous du utility. It allows one to browse through the directories and
 show percentages of disk usage with ncurses library.


- `gluster`: Gluster Console Manager (command line utility)
- `lvrename`: Rename a logical volume
- `ansible`:  Configuration management, deployment, and task execution system
 Ansible is a radically simple model-driven configuration management,
 multi-node deployment, and remote task execution system. Ansible works
 over SSH and does not require any software or daemons to be installed
 on remote nodes. Extension modules can be written in any language and
 are transferred to managed machines automatically.
 .
 This package contains the ansible collections.


- `lvmsadc`: LVM system activity data collector
- `whiptail`:  Displays user-friendly dialog boxes from shell scripts
 Whiptail is a "dialog" replacement using newt instead of ncurses. It
 provides a method of displaying several different types of dialog boxes
 from shell scripts. This allows a developer of a script to interact with
 the user in a much friendlier manner.


- `alpine`: an Alternatively Licensed Program for Internet News and Email
- `purge-old-kernels`: remove old kernel and header packages from the system
- `mocp`: Console audio player
- `spawn`: Postfix external command spawner
- `vim`:  Vi IMproved - enhanced vi editor
 Vim is an almost compatible version of the UNIX editor Vi.
 .
 Many new features have been added: multi level undo, syntax
 highlighting, command line history, on-line help, filename
 completion, block operations, folding, Unicode support, etc.
 .
 This package contains a version of vim compiled with a rather
 standard set of features.  This package does not provide a GUI
 version of Vim.  See the other vim-* packages if you need more
 (or less).


- `compton`:  compositor for X11, based on xcompmgr
 compton is a compositor for X11, based on xcompmgr. In addition to shadows,
 fading and translucency, compton implements window frame opacity control,
 inactive window transparency, and shadows on argb windows.


- `megadl`: download exported files and directories from Mega.nz
- `fdupes`:  identifies duplicate files within given directories
 FDupes uses md5sums and then a byte by byte comparison to find
 duplicate files within a set of directories. It has several useful
 options including recursion.


- `bully`:  Implementation of the WPS brute force attack, written in C
 Bully is a new implementation of the WPS brute force attack, written in C. It
 is conceptually identical to other programs, in that it exploits the (now well
 known) design flaw in the WPS specification. It has several advantages over
 the original reaver code. These include fewer dependencies, improved memory
 and cpu performance, correct handling of endianness, and a more robust set of
 options.


- `iptables`:  administration tools for packet filtering and NAT
 The iptables/xtables framework has been replaced by nftables. You should
 consider migrating now.
 .
 iptables is the userspace command line program used to configure
 the Linux packet filtering and NAT ruleset. It is targeted towards systems
 and networks administrators.
 .
 This package contains several different utilities, the most important ones:
 .
 iptables-nft, iptables-nft-save, iptables-nft-restore (nft-based version)
 .
 iptables-legacy, iptables-legacy-save, iptables-legacy-restore (legacy version)
 .
 ip6tables-nft, ip6tables-nft-save, ip6tables-nft-restore (nft-based version)
 .
 ip6tables-legacy, ip6tables-legacy-save, ip6tables-legacy-restore (legacy
 version)
 .
 arptables-nft, arptables-nft-save, arptables-nft-restore (nft-based version)
 .
 ebtables-nft, ebtables-nft-save, ebtables-nft-restore (nft-based version)


- `aspell-autobuildhash`: Autobuilding aspell hash files for some dicts
- `iperf`:  Internet Protocol bandwidth measuring tool
 Iperf is a modern alternative for measuring TCP and UDP bandwidth performance,
 allowing the tuning of various parameters and characteristics.
 .
 Features:
    * Measure bandwidth, packet loss, delay jitter
    * Report MSS/MTU size and observed read sizes.
    * Support for TCP window size via socket buffers.
    * Multi-threaded. Client and server can have multiple simultaneous
      connections.
    * Client can create UDP streams of specified bandwidth.
    * Multicast and IPv6 capable.
    * Options can be specified with K (kilo-) and M (mega-) suffices.
    * Can run for specified time, rather than a set amount of data to transfer.
    * Picks the best units for the size of data being reported.
    * Server handles multiple connections.
    * Print periodic, intermediate bandwidth, jitter, and loss reports at
      specified intervals.
    * Server can be run as a daemon.
    * Use representative streams to test out how link layer compression affects
      your achievable bandwidth.


- `lftp`:  Sophisticated command-line FTP/HTTP/BitTorrent client programs
 Lftp is a file retrieving tool that supports FTP, HTTP, FISH, SFTP, HTTPS,
 FTPS and BitTorrent protocols under both IPv4 and IPv6. Lftp has an amazing
 set of features, while preserving its interface as simple and easy as possible.
 .
 The main two advantages over other ftp clients are reliability and ability
 to perform tasks in background. It will reconnect and reget the file being
 transferred if the connection broke. You can start a transfer in background
 and continue browsing on the ftp site. It does this all in one process. When
 you have started background jobs and feel you are done, you can just exit
 lftp and it automatically moves to nohup mode and completes the transfers.
 It has also such nice features as reput and mirror. It can also download a
 file as soon as possible by using several connections at the same time.
 .
 Lftp can also be scriptable, it can be used to mirror sites, it lets you
 copy files among remote servers (even between FTP and HTTP). It has an
 extensive online help. It supports bookmarks, and connecting to several
 ftp/http sites at the same time.
 .
 This package also includes lftpget - A simple non-interactive
 tool for downloading files.


- `pine`: an Alternatively Licensed Program for Internet News and Email
- `bison`:  YACC-compatible parser generator
 Bison is a general-purpose parser generator that converts a
 grammar description for an LALR(1) context-free grammar into a C
 program to parse that grammar.  Once you are proficient with Bison, you
 may use it to develop a wide range of language parsers, from those used
 in simple desk calculators to complex programming languages.
 .
 Bison is upward compatible with Yacc: all properly-written Yacc
 grammars ought to work with Bison with no change.  Anyone familiar with
 Yacc should be able to use Bison with little trouble.  Documentation of
 the program is in the bison-doc package.


- `system-config-printer-applet`: print job manager
- `apt-mark`: show, set and unset various settings for a package
- `figlet`:  Make large character ASCII banners out of ordinary text
 FIGlet (Frank, Ian & Glenn's Letters) is a program that creates large
 characters out of ordinary screen characters.
 .
 It can create characters in many different styles and can
 kern and "smush" these characters together in various ways.  FIGlet
 output is generally reminiscent of the sort of "signatures" many people
 like to put at the end of e-mail, Usenet and MOTD messages.


- `netkit-ftp`: Internet file transfer program
- `compgen`: bash built-in commands, see bash(1)
- `ypbind`: NIS binding process
- `iftop`:  displays bandwidth usage information on an network interface
 iftop does for network usage what top(1) does for CPU usage. It listens to
 network traffic on a named interface and displays a table of current bandwidth
 usage by pairs of hosts. Handy for answering the question "Why is my Internet
 link so slow?".


- `xfs_rtcp`: XFS realtime copy command
- `zless`: file perusal filter for crt viewing of compressed text
- `abduco`: terminal session manager
- `ack`:  grep-like program specifically for large source trees
 Ack is designed as an alternative for 99% of the uses of grep. ack is
 intelligent about the files it searches. It knows about certain file
 types, based on both the extension on the file and, in some cases, the
 contents of the file.
 .
 Ack ignores backup files and files under CVS and .svn directories. It
 also highlights matches to help you see where the match was. Ack uses
 perl regular expressions.


- `act`: act
- `ag`: ag
- `airpaste`: 1-1 network pipe that auto discovers other peers using mdns
- `alex`:  lexical analyser generator for Haskell
 Alex is a tool for generating lexical analysers in Haskell, given a
 description of the tokens to be recognised in the form of regular
 expressions. It is similar to the tool lex or flex for C/C++.


- `ansible-galaxy`: ansible-galaxy
- `ansible-playbook`: ansible-playbook
- `ansiweather`:  Weather in your terminal, with ANSI colors and Unicode symbols
 AnsiWeather is a Shell script for displaying the current
 weather conditions in your terminal, with support for
 ANSI colors and Unicode symbols.
 .
 Weather data comes from OpenWeatherMap, free weather API.


- `airtun-ng`: a virtual tunnel interface creator for aircrack-ng
- `apk`: apk
- `apm`: apm
- `alsamixer`: soundcard mixer for ALSA soundcard driver, with ncurses interface
- `apt-file`:  search for files within Debian packages (command-line interface)
 apt-file is a command line tool for searching files contained in packages
 for the APT packaging system. You can search in which package a file is
 included or list the contents of a package without installing or fetching it.


- `archey`: archey
- `aria2`:  High speed download utility
 Aria2 is a command line download client with resuming and
 segmented downloading. Supported protocols are HTTP/HTTPS/
 SFTP/FTP/BitTorrent and it also supports Metalink.


- `aria2c`: aria2c
- `aplaymidi`: play Standard MIDI Files
- `asar`: asar
- `asciinema`:  Record and share your terminal sessions, the right way
 Forget screen recording apps and blurry video. Enjoy a lightweight,
 purely text based approach to terminal recording.
 .
 This package provides a command line recorder for asciinema.org service
 or other instance of asciinema server.


- `asdf`: asdf
- `assimp`: assimp
- `astronomer`: astronomer
- `astyle`:  Source code indenter for C, C++, Objective-C, C#, and Java
 Artistic Style is a source code indenter, formatter, and beautifier for
 the C, C++, C++/CLI, Objective-C, C# and Java programming languages.
 .
 This package contains the command line tool.


- `c99`: compile standard C programs
- `atom`: atom
- `atoum`: atoum
- `atq`: atq
- `atrm`: atrm
- `authconfig`: authconfig
- `autoflake`:  Removes unused imports and unused variables in Python code
 By default, autoflake only removes unused imports for modules that are part of
 the standard library. (Other modules may have side effects that make them
 unsafe to remove automatically.) Removal of unused variables is also disabled
 by default.
 .
 Also removes useless 'pass' statements.


- `autojump`:  shell extension to jump to frequently used directories
 autojump provides a faster way to navigate your filesystem, with a
 "cd command that learns".
 .
 It works by maintaining a database of the directories you use the most from
 the command line, and allows you to "jump" to frequently used directories by
 typing only a small pattern.
 .
 To use autojump, you need to configure your shell to source
 /usr/share/autojump/autojump.sh on startup.


- `autorandr`:  Automatically select a display configuration for connected devices
 Autorandr is a script for managing xrandr configurations based on the
 connected devices. It can be set up to automatically switch to a
 stored configuration whenever a change in the configuration is
 detected.


- `avrdude`:  software for programming Atmel AVR microcontrollers
 AVRDUDE is an open source utility to download/upload/manipulate the
 ROM and EEPROM contents of AVR microcontrollers using the in-system
 programming technique (ISP).


- `aws-s3`: aws-s3
- `aws`: aws
- `az`: az
- `avahi-browse`: Browse for mDNS/DNS-SD services using the Avahi daemon
- `banner`: banner
- `avahi-publish-service`: Register an mDNS/DNS-SD service or host name or address mapping using the Avahi daemon
- `bashmarks`: bashmarks
- `bat`:  cat(1) clone with syntax highlighting and git integration
 bat is a drop-in cat(1) replacement featuring:
 .
  * syntax highlighting for a large number of languages;
  * git integration;
  * automatic paging;
  * a user-friendly command-line interface.
 .
 In this package the executable and its manpage have been renamed from ‘bat’ to
 ‘batcat’ because of a file name clash with another Debian package.


- `beanstalkd`:  simple, in-memory, workqueue service
 Beanstalkd is a simple, fast, workqueue service (a specific case of message
 queueing), in which messages are organised in "tubes". Beanstalk clients can
 insert and consume messages into and from such tubes.
 .
 The beanstalk interface is generic, but was originally designed for reducing
 the latency of page views in high-volume web applications by running
 time-consuming tasks asynchronously.
 .
 Beanstalkd is meant to be ran in a trusted network, as it has no
 authorisation/authentication mechanisms.
 .
 This package has the server files.


- `bedtools`:  suite of utilities for comparing genomic features
 The BEDTools utilities allow one to address common genomics tasks such as
 finding feature overlaps and computing coverage. The utilities are largely
 based on four widely-used file formats: BED, GFF/GTF, VCF, and SAM/BAM. Using
 BEDTools, one can develop sophisticated pipelines that answer complicated
 research questions by streaming several BEDTools together.
 .
 The groupBy utility is distributed in the filo package.


- `behat`: behat
- `berks`: berks
- `bitcoin-cli`: bitcoin-cli
- `blackfire`: blackfire
- `blender`: blender
- `bmaptool`: bmaptool
- `bmon`:  portable bandwidth monitor and rate estimator
 bmon is a commandline bandwidth monitor which supports various output
 methods including an interactive curses interface, lightweight HTML output but
 also simple ASCII output.
 .
 Statistics may be distributed over a network using multicast or unicast and
 collected at some point to generate a summary of statistics for a set of
 nodes.


- `arp`: Linux ARP kernel module.
- `borg`: borg
- `bosh`:  browse output of processes
 bosh stands for browsable output shell. This is a bit of a
 misnomer because it isn't really a shell. What is does is
 store the output of a specified program in a buffer, and
 provides a simple curses interface to browse this buffer.
 Actions can be configured which can make use of the
 contents of the currently selected line.
 .
 Commands and actions are stored in bosh configuration files.
 These can include shebang line (#!/usr/bin/bosh) so that the
 configuration can just be run from the command-line.


- `bower`: bower
- `box`: box
- `brctl`: brctl
- `znew`: recompress .Z files to .gz files
- `browser-sync`: browser-sync
- `buddy-ng`: a tool to work with easside-ng
- `bup`:  highly efficient file backup system based on git
 bup is a backup tool which stores the backups in a system based around
 the packfile format from git.


- `bw`: bw
- `bzmore`: file  perusal  filter for crt viewing of bzip2 com‐
   pressed text
- `cabal`: cabal
- `cake`: cake
- `calc`:  Arbitrary precision calculator
 Calc is an arbitrary precision arithmetic system that uses a C-like
 language. Calc is useful as a calculator, an algorithm prototyper and as a
 mathematical research tool. More importantly, calc provides one with a
 machine independent means of computation. Calc comes with a rich set of
 builtin mathematical and programmatic functions.
 .
 Calc is built on top of the library libcalc that represents numeric values
 as fractions reduced to their lowest terms. This library can also be used
 to add arbitrary precision capabilities to your own programs and is
 available in the Debian package `calc-dev'.


- `calcurse`: calcurse
- `calibre-server`: calibre-server
- `calibredb`: calibredb
- `cargo`:  Rust package manager
 Cargo is a tool that allows Rust projects to declare their various
 dependencies, and ensure that you'll always get a repeatable build.
 .
 To accomplish this goal, Cargo does four things:
  * Introduces two metadata files with various bits of project information.
  * Fetches and builds your project's dependencies.
  * Invokes rustc or another build tool with the correct parameters to build
    your project.
  * Introduces conventions, making working with Rust projects easier.
 .
 Cargo downloads your Rust project's dependencies and compiles your
 project.


- `case`: case
- `certbot`:  automatically configure HTTPS using Let's Encrypt
 The objective of Certbot, Let's Encrypt, and the ACME (Automated
 Certificate Management Environment) protocol is to make it possible
 to set up an HTTPS server and have it automatically obtain a
 browser-trusted certificate, without any human intervention. This is
 accomplished by running a certificate management agent on the web
 server.
 .
 This agent is used to:
 .
   - Automatically prove to the Let's Encrypt CA that you control the website
   - Obtain a browser-trusted certificate and set it up on your web server
   - Keep track of when your certificate is going to expire, and renew it
   - Help you revoke the certificate if that ever becomes necessary.
 .
 This package contains the main application, including the standalone
 and the manual authenticators.


- `cat`: concatenate and print files
- `cheese`:  tool to take pictures and videos from your webcam
 A webcam application that supports image and video capture. Makes
 it easy to take photos and videos of you, your friends, pets or whatever
 you want. Allows you to apply fancy visual effects, fine-control image
 settings and has features such as Multi-Burst mode, Countdown timer
 for photos.


- `clamscan`: clamscan
- `clementine`:  modern music player and library organizer
 Clementine is a multiplatform music player focusing on a fast and
 easy-to-use interface for searching and playing your music.
 .
 Summary of included features :
  - Search and play your local music library.
  - Listen to internet radio from ROCKRADIO.com, RadioTunes.com,
    IntergalacticFM, SomaFM, Magnatune, Jamendo, Digitally Imported,
    ClassicalRadio.com, JAZZRADIO.com, Icecast and Subsonic servers.
  - Search and play songs you've uploaded to SeaFile, Box, Dropbox, Google
    Drive, and OneDrive.
  - Create smart playlists and dynamic playlists.
  - Tabbed playlists, import and export M3U, XSPF, PLS and ASX.
  - CUE sheet support.
  - Play audio CDs.
  - Visualisations from projectM.
  - Lyrics and artist biographies and photos.
  - Transcode music into MP3, Ogg Vorbis, Ogg Speex, FLAC or AAC.
  - Edit tags on MP3 and OGG files, organise your music.
  - Fetch missing tags from MusicBrainz.
  - Discover and download Podcasts.
  - Download missing album cover art from Last.fm.
  - Native desktop notifications using libnotify.
  - Remote control using an Android device, a Wii Remote, MPRIS or the
    command-line.
  - Copy music to your iPod, iPhone, MTP or mass-storage USB player.
  - Queue manager.


- `cloc`:  statistics utility to count lines of code
 Count physical lines of source code in the given files (may be
 archives such as compressed tarballs or zip files) and/or
 recursively below the given directories.
 .
 Counts blank lines, comment lines, and physical lines of source code
 in many programming languages. It is written entirely in Perl, using
 only modules from the standard distribution.


- `clockwork-cli`: clockwork-cli
- `cmake`:  cross-platform, open-source make system
 CMake is used to control the software compilation process using
 simple platform and compiler independent configuration files. CMake
 generates native makefiles and workspaces that can be used in the
 compiler environment of your choice. CMake is quite sophisticated: it
 is possible to support complex environments requiring system
 configuration, pre-processor generation, code generation, and template
 instantiation.


- `cmark`:  CommonMark parsing and rendering program
 cmark is the C reference implementation of CommonMark,
 a rationalized version of Markdown syntax with a spec.
 .
 cmark parses almost as fast as sundown and hoedown
 (but safer and less buggy),
 about 3 times faster than discount,
 and about 100 times faster than kramdown and pandoc.
 Memory consumption is on par with sundown
 and about 10 times less than pandoc.
 .
 cmark outputs HTML, groff man, LaTeX, CommonMark,
 and a custom XML format.
 .
 Markdown is a lightweight markup language
 with plain-text-formatting syntax.
 .
 This package provides a command-line program (cmark)
 for parsing and rendering CommonMark documents.


- `cmus`:  lightweight ncurses audio player
 C* Music Player is a modular and very configurable ncurses-based audio player.
 It has some interesting features like configurable colorscheme, mp3 and ogg
 streaming, it can be controlled with an UNIX socket, filters, album/artists
 sorting and a vi-like configuration interface.
 .
 It currently supports different input formats:
  - Ogg Vorbis
  - MP3 (with libmad)
  - FLAC
  - Wav
  - Modules (with libmodplug)
  - Musepack
  - AAC
  - Windows Media Audio


- `code`: code
- `coffee`: execute scripts, compile .coffee files into .js, and provide an interactive REPL
- `collectd`:  statistics collection and monitoring daemon
 collectd is a small daemon which collects system information periodically and
 provides mechanisms to monitor and store the values in a variety of ways.
 Since the daemon doesn't need to startup every time it wants to update the
 values it's very fast and easy on the system. Also, the statistics are very
 fine grained since the files are updated every 10 seconds by default.
 .
 The collected information can be used to find current performance bottlenecks
 (performance analysis) and predict future system load (capacity planning).
 .
 This package provides a full installation of the daemon, including the
 configuration. For the core system, see the "collectd-core" package, which
 allows sites to, e.g., provide customizations (like a custom default
 configuration) on top of it without having to modify the "collectd" package.


- `column`: columnate lists
- `complete`: complete
- `colcrt`: filter nroff output for CRT previewing
- `composer`:  dependency manager for PHP
 Composer helps you declare, manage and install dependencies of PHP projects.
 It ensures you have the right stack everywhere.
 .
 It behaves like Bundler (Ruby), npm (Node), etc.


- `conda`: conda
- `consul-kv`: consul-kv
- `consul`: consul
- `convmv`:  filename encoding conversion tool
 convmv can convert a single filename, a directory tree or all files
 on a filesystem to a different encoding. It only converts the
 encoding of filenames, not files contents. A special feature of
 convmv is that it also takes care of symlinks: the encoding of the
 symlink's target will be converted if the symlink itself is being
 converted.
 .
 It is also possible to convert directories to UTF-8 which are already
 partially UTF-8 encoded.
 .
 Keywords: rename, move


- `cordova`: cordova
- `couchdb`: couchdb
- `cppcheck`:  tool for static C/C++ code analysis (CLI)
 Cppcheck is a command-line tool that tries to detect bugs that your
 C/C++ compiler doesn't see. It is versatile, and can check non-standard
 code including various compiler extensions, inline assembly code, etc.
 Its internal preprocessor can handle includes, macros, and several
 preprocessor commands. While Cppcheck is highly configurable,
 you can start using it just by giving it a path to the source code.
 .
 It includes checks for:
  * pointers to out-of-scope auto variables;
  * assignment of auto variables to an effective parameter of a function;
  * out-of-bounds errors in arrays and STL;
  * missing class constructors;
  * variables not initialized by a constructor;
  * use of memset, memcpy, etcetera on a class;
  * non-virtual destructors for base classes;
  * operator= not returning a constant reference to itself;
  * use of deprecated functions (mktemp, gets, scanf);
  * exceptions thrown in destructors;
  * memory leaks in class or function variables;
  * C-style pointer cast in C++ code;
  * redundant if;
  * misuse of the strtol or sprintf functions;
  * unsigned division or division by zero;
  * unused functions and struct members;
  * passing parameters by value;
  * misuse of signed char variables;
  * unusual pointer arithmetic (such as "abc" + 'd');
  * dereferenced null pointers;
  * incomplete statements;
  * misuse of iterators when iterating through a container;
  * dereferencing of erased iterators;
  * use of invalidated vector iterators/pointers;
 .
 This package contains the command-line interface for cppcheck.


- `cppclean`: cppclean
- `whoami`: print effective userid
- `cpulimit`:  tool for limiting the CPU usage of a process
 cpulimit is a simple program that attempts to limit the CPU usage of a
 process (expressed in percentage, not in CPU time). This is useful to
 control batch jobs, when you don't want them to eat too much CPU. It does
 not act on the nice value or other priority stuff, but on the real CPU
 usage.  Besides it is able to adapt itself to the overall system load,
 dynamically and quickly.


- `cradle-deploy`: cradle-deploy
- `cradle-elastic`: cradle-elastic
- `cradle-install`: cradle-install
- `cradle-package`: cradle-package
- `cradle-sql`: cradle-sql
- `cradle`: cradle
- `create_ap`: create_ap
- `crystal`:  compiler of the Crystal object-oriented programming language
 The Crystal's language syntax is inspired by Ruby, the language is statically
 type-checked but does not require that the type of variables or method
 arguments be specified.
 .
 The language has the following goals: (1) have the same syntax as Ruby, or at
 least as similar as possible; (2) statically type-checked but without having
 to specify the type of variables or method arguments; (3) be able to call C
 code by writing bindings to it in Crystal; (4) have compile-time evaluation
 and generation of code, to avoid boilerplate code; (5) compile to efficient
 native code.


- `csc`: csc
- `csslint`: csslint
- `csvclean`: csvclean
- `csvcut`: csvcut
- `csvformat`: csvformat
- `csvgrep`: csvgrep
- `csvlook`: csvlook
- `csvpy`: csvpy
- `csvsort`: csvsort
- `csvstat`: csvstat
- `ctest`: ctest
- `daemonize`:  tool to run a command as a daemon
 As defined in W. Richard Stevens’ 1990 book, UNIX Network Programming
 (Addison-Wesley, 1990), a daemon is “a process that executes ‘in the
 background’ i.e., without an associated terminal or login shell) either
 waiting for some event to occur, or waiting to perform some specified task on a
 periodic basis.” Upon startup, a typical daemon program will:
 .
  * Close all open file descriptors (especially standard input, standard output
    and standard error)
  * Change its working directory to the root filesystem, to ensure that it
    doesn’t tie up another filesystem and prevent it from being unmounted
  * Reset its umask value
  * Run in the background (i.e., fork)
  * Disassociate from its process group (usually a shell), to insulate itself
    from signals (such as HUP) sent to the process group
  * Ignore all terminal I/O signals
  * Disassociate from the control terminal (and take steps not to reacquire one)
  * Handle any SIGCLD signals
 .
 Most programs that are designed to be run as daemons do that work for
 themselves. However, you’ll occasionally run across one that does not. When
 you must run a daemon program that does not properly make itself into a true
 Unix daemon, you can use daemonize to force it to run as a true daemon.


- `darkhttpd`: darkhttpd
- `datamash`:  statistics tool for command-line interface
 GNU Datamash is a command-line program which performs basic numeric,
 textual and statistical operations on input textual data files. It is
 designed to be portable and reliable, and aid researchers to easily
 automate analysis pipelines, without writing code or even short scripts.


- `decaffeinate`: decaffeinate
- `deluge-console`:  multi-interface BitTorrent client (text UI)
 Deluge is a BitTorrent client written in Python. It uses a client-server
 model supporting multiple user-interfaces that can connect to a
 (headless) deluged running on a server.
 .
 This package contains the text user-interface (ncurses).


- `deluge`:  multi-interface BitTorrent client (metapackage)
 Deluge is a BitTorrent client written in Python. It uses a client-server
 model supporting multiple user-interfaces that can connect to a
 (headless) deluge-daemon running on a server:
 .
   * deluge-gtk: graphical UI using GTK
   * deluge-console: text UI using ncurses
   * deluge-web: web frontend
 .
 This package is a metapackage depending on the graphical UI and the
 daemon for running deluge on a single machine.


- `deluged`:  multi-interface BitTorrent client (server)
 Deluge is a BitTorrent client written in Python. It uses a client-server
 model supporting multiple user-interfaces that can connect to a
 (headless) deluged running on a server.
 .
 This package contains the server.


- `dep`: dep
- `detox`:  replace problematic characters in filenames
 detox is a utility designed to clean up filenames. It replaces difficult to
 work with characters, such as spaces, with standard equivalents. It will also
 clean up filenames with UTF-8 or Latin-1 (or CP-1252) characters in them.
 .
 Features:
  * Removal or replacement of upper ASCII Latin-1 (ISO 8859-1) characters;
  * Removal or replacement of UTF-8 encoded Unicode characters;
  * Removal or replacement of spaces and other potentially tricky characters;
  * Trimming of excessive "_" and "-"s;
  * Directory recursion, dry runs, verbose listings.
 .
 It is designed with safety in mind. It won't overwrite a file that already
 exists, and it doesn't touch special files if not requested.
 .
 detox is useful to mass rename files automatically. As just one example,
 you can use detox to easily standardize lots of files, as MP3 or movies,
 downloaded or stored inside a directory.
 .
 This package provides detox and inline-detox commands. The inline-detox can
 be used in command lines, as a filter in shell procedures.


- `dexter`: dexter
- `dhcpwn`: dhcpwn
- `dirs`: dirs
- `disown`: disown
- `dive`: dive
- `do-release-upgrade`: do-release-upgrade
- `docker-compose`:  define and run multi-container Docker applications with YAML
 docker-compose is a service management software built on top of docker. Define
 your services and their relationships in a simple YAML file, and let compose
 handle the rest.
 .
 This package includes the command-line tool.


- `docker-containers`: docker-containers
- `docker-images`: docker-images
- `docker-machine`: docker-machine
- `dokku`: dokku
- `dnswalk`:  Checks dns zone information using nameserver lookups
 dnswalk is a DNS debugger.  It performs zone transfers of specified
 domains, and checks the database in numerous ways for internal
 consistency, as well as accuracy.


- `dotnet`: dotnet
- `doxygen`:  Generate documentation from source code
 Doxygen is a documentation system for C++, C, Objective-C, C#, PHP, Java,
 Python, IDL, Fortran, VHDL and to some extent D. It can generate an on-line
 documentation browser (in HTML) and/or an off-line reference manual (in LaTeX)
 from a set of annotated source files.
 .
 There is also support for generating RTF, PostScript, hyperlinked PDF,
 compressed HTML, and Unix man pages. The documentation is extracted directly
 from the sources.
 .
 Install the doxygen-latex package to build LaTeX based documents.


- `dmraid`: discover, configure and activate software (ATA)RAID
- `drush`: drush
- `ebook-convert`: ebook-convert
- `ebuild`: ebuild
- `ect`: ect
- `dvipdf`: Convert TeX DVI file to PDF using ghostscript and dvips
- `edquota`: edquota
- `electrum`:  Easy to use Bitcoin client
 This package provides a lightweight Bitcoin client which protects
 you from losing your bitcoins in a backup mistake or computer
 failure. Also, Electrum does not require waiting time because it does
 not download the Bitcoin blockchain.
 .
 Features of Electrum:
 .
   * Instant on: Your client does not download the blockchain. It uses a
     network of specialized servers that index the blockchain.
   * Forgiving: Your wallet can be recovered from a secret seed.
   * Safe: Your seed and private keys are encrypted on your hard drive.
     They are never sent to the servers.
   * Low trust: Information received from the servers is verified using
     SPV. Servers are authenticated using SSL.
   * No downtimes: Your client is not tied to a particular server; it
     will switch instantly if your server is down.
   * Ubiquitous: You can use the same wallet on different computers, they
     will synchronize automatically.
   * Cold Storage: Sign transactions from a computer that is always
     offline. Broadcast them using a machine that does not have your keys.
   * Reachable: You can export your private keys into other Bitcoin
     clients.
   * Established: Electrum is open source and was first released in
     November 2011.


- `elm`: elm
- `emacsclient`: emacsclient
- `ember`: ember
- `emerge`: emerge
- `enca`:  Extremely Naive Charset Analyser - binaries
 Enca is an Extremely Naive Charset Analyser. It detects the character set and
 the encoding of text files and can also convert them to other encodings using
 either a built-in converter or external libraries and tools like libiconv,
 librecode, or cstocs.
 .
 Currently it supports Belarusian, Bulgarian, Croatian, Czech,
 Estonian, Hungarian, Latvian, Lithuanian, Polish, Russian, Slovak,
 Slovene, Ukrainian, Chinese, and some multibyte encodings independently
 on language.


- `enscript`:  converts text to Postscript, HTML or RTF with syntax highlighting
 GNU Enscript takes ASCII files (often source code) and converts them
 to PostScript, HTML or RTF.  It can store generated output to a file
 or send it directly to the printer.
 .
 It is often used for its syntax highlighting, as it comes with rules
 for a wide range of programming languages.  New rules can be added
 using an awk-like stateful scripting language.


- `entr`:  Run arbitrary commands when files change
 The Event Notify Test Runner (entr) runs arbitrary commands when
 files change. Changes are detected through the kqueue/inotify
 kernel interface.


- `envoy`: envoy
- `equery`: equery
- `erl`: erl
- `eslint`:  AST-based pattern checker for JavaScript
 ESLint is a tool for identifying and reporting on patterns
 found in ECMAScript/JavaScript code.
 In many ways, it is similar to JSLint and JSHint
 with a few exceptions:
 .
  * ESLint uses Espree for JavaScript parsing
  * ESLint uses an AST to evaluate patterns in code
  * ESLint is completely pluggable,
    every single rule is a plugin and you can add more at runtime
 .
 Some uses of ESLint require additional packages:
  * Use of parsers other than the default (Espree) require that parser,
    e.g. node-babel-eslint, node-esprima, or node-esprima-fb.
  * Use of option --init require package node-inquirer.


- `eog`:  Eye of GNOME graphics viewer program
 eog or the Eye of GNOME is a simple graphics viewer for the GNOME
 desktop which uses the gdk-pixbuf library.  It can deal with large
 images, and zoom and scroll with constant memory usage.  Its goals are
 simplicity and standards compliance.


- `etckeeper`:  store /etc in git, mercurial, brz or darcs
 The etckeeper program is a tool to let /etc be stored in a git, mercurial,
 brz or darcs repository. It hooks into APT to automatically commit changes
 made to /etc during package upgrades. It tracks file metadata that version
 control systems do not normally support, but that is important for /etc, such
 as the permissions of /etc/shadow. It's quite modular and configurable, while
 also being simple to use if you understand the basics of working with version
 control.


- `gdbus`: Tool for working with D -Bus objects
- `write`: write to a file descriptor
- `gdiffmk`: mark differences between groff/nroff/troff files
- `eyeD3`: eyeD3
- `f3probe`: f3probe
- `f5fpc`: f5fpc
- `faketime`:  Report faked system time to programs (command-line tool)
 The Fake Time Preload Library (FTPL, a.k.a. libfaketime) intercepts
 various system calls which programs use to retrieve the current date
 and time. It can then report faked dates and times (as specified by
 you, the user) to these programs. This means you can modify the
 system time a program sees without having to change the time
 system-wide. FTPL allows you to specify both absolute dates (e.g.,
 2004-01-01) and relative dates (e.g., 10 days ago).
 .
 This package contains a "faketime" binary that makes it easy to use
 the LD_PRELOAD library.


- `fastboot`:  Android fastboot tool
 A command line tool for flashing an Android device, boot an Android device to
 fastboot mode, etc..
 .
 This package recommends "android-sdk-platform-tools-common" which contains
 the udev rules for Android devices. Without this package, adb and fastboot need
 to be running with root permission.


- `fc-scan`: scan font files or directories
- `fc-cat`: read font information cache files
- `cpuid`:  tool to dump x86 CPUID information about the CPU(s)
 cpuid dumps detailed information about the CPU(s) gathered from the
 CPUID instruction, and also determines the exact model of CPU(s). It
 supports Intel, AMD, and VIA CPUs, as well as older Transmeta, Cyrix,
 UMC, NexGen, Rise, and SiS CPUs.


- `feedreader`: feedreader
- `feh`:  imlib2 based image viewer
 feh is a fast, lightweight image viewer which uses imlib2. It is
 commandline-driven and supports multiple images through
 slideshows, thumbnail browsing or multiple windows, and montages
 or index prints (using TrueType fonts to display file info).
 Advanced features include fast dynamic zooming, progressive
 loading, loading via HTTP (with reload support for watching
 webcams), recursive file opening (slideshow of a directory
 hierarchy), and mouse wheel/keyboard control.


- `ffsend`: easily and securely share files from the command line
- `file-rename`: file-rename
- `firejail`: easy to use SUID sandbox program
- `fish`:  friendly interactive shell
 Fish is a shell geared towards interactive use.  Its features are focused on
 user friendliness and discoverability.  The language syntax is simple but
 incompatible with other shell languages.


- `fisher`: fisher
- `fkill`: fkill
- `findsmb`: list info about machines that respond to SMB name queries on
   a subnet
- `find`: find files
- `finger`:  user information lookup program
 finger displays information about the system users.


- `flutter`: flutter
- `fly`: fly
- `for`: for
- `foreman`: foreman
- `forever`: forever
- `fossa`: fossa
- `fonttosfnt`: Wrap a bitmap font in a sfnt (TrueType) wrapper
- `fselect`: fselect
- `fswatch`:  file change monitor based on inotify
 fswatch is a file change monitor that receives notifications when the contents
 of the specified files or directories are modified. fswatch implements the
 following kinds of monitors:
  * A monitor based on the File System Events API of Apple OS X.
  * A monitor based on kqueue, an event notification interface introduced in
    FreeBSD 4.1 and supported on most *BSD systems (including OS X).
  * A monitor based on inotify, a Linux kernel subsystem that reports file
    system changes to applications.
  * A monitor based on File Events Notification, a Solaris/Illumos kernel API
    that reports file events.
  * A monitor which periodically stats the file system, saves file modification
    times in memory and manually calculates file system changes, which can work
    on any operating system where stat (2) can be used.
 .
 fswatch should build and work correctly on any system shipping either of the
 aforementioned APIs


- `fswebcam`:  Tiny and flexible webcam program
 Fswebcam is a tiny and flexible webcam command-line program for capturing
 images from a V4L1/V4L2 device. It accepts a number of formats, can skip
 the first (possibly bad) frames before performing the actual capture, and
 can perform simple manipulation on the captured image, such as resizing,
 averaging multiple frames or overlaying a caption or an image.


- `fusermount`: mount and unmount FUSE filesystems
- `funzip`: filter for extracting from a ZIP archive in a pipe
- `gatsby`: gatsby
- `gcal`:  program for calculating and printing calendars
 Gcal displays a calendar for a month or a year, eternal holiday lists
 and fixed date lists, in many ways. The program correctly omits the
 dates that were skipped when the current Gregorian calendar replaced
 the earlier Julian calendar.
 .
 Apart from the usual and well known calendar functions like the
 output of a month or a year calendar sheet, or the output of an eternal
 holiday list, Gcal offers the facility to display fixed dates on the
 day of their occurrence and to remind or inform the user about them.
 So it is possible for users to receive an on-screen notification, at bootup
 or login, of all holidays or appointments which take place on that day.
 Notification by electronic mail is also possible.


- `gcalcli`:  Google Calendar Command Line Interface
 gcalcli is a Python application that allows you to access your Google
 Calendar from a command line. It's easy to get your agenda, search for
 events, and quickly add new events. Additionally gcalcli can be used as
 a reminder service to execute any application you want.


- `gcalccmd`: a console calculator
- `gcloud`: gcloud
- `gdrive`: gdrive
- `fzf`:  general-purpose command-line fuzzy finder
 It's an interactive Unix filter for command-line that can be used with
 any list; files, command history, processes, hostnames, bookmarks, git
 commits, etc.
 .
 Refer /usr/share/doc/fzf/README.Debian for quick instructions on how to
 add keybindings for Bash, Zsh, Fish to call fzf.


- `genie`: genie
- `genkernel`: genkernel
- `geth`: geth
- `ghc`:  The Glasgow Haskell Compilation system
 The Glorious Glasgow Haskell Compilation system (GHC) is a compiler for
 Haskell.
 .
 Haskell is "the" standard lazy functional programming language.  The language
 definition and additional documentation can be found at
 https://www.haskell.org/documentation/.


- `gibo`: gibo
- `gifsicle`:  Tool for manipulating GIF images
 This is a tool for manipulating GIF image files. It has good
 support for transparency and colormap manipulation, simple image
 transformations (cropping, flipping), and creating, deconstructing,
 and editing GIF animations, which it can also optimize for space.


- `gist`:  Upload gists to gist.github.com
 Allows you to convienently create gists ("pastes").
 .
 Also provides a Ruby library to do this.
 .
 The "gist" image viewer from yorick is in the yorick package,
 not in this package.


- `git-commit-tree`: Create a new commit object
- `git-imerge`:  incremental merge and rebase for git
 Performs a merge between two branches incrementally. If conflicts are
 encountered, figures out exactly which pairs of commits conflict, and
 presents the user with one pairwise conflict at a time for resolution.


- `git-pr`: git-pr
- `git-rerere`: Reuse recorded resolution of conflicted merges
- `git-sizer`:  compute various size metrics for a Git repository
 git-sizer computes various size metrics for a Git repository, flagging
 those that might cause problems or inconvenience. For example:
 .
  • Is the repository too big overall?
  • Does the repository have too many references (branches and/or tags)?
  • Does the repository include too many objects?
  • Does the repository include gigantic blobs (files)?
  • Does the repository include many slightly different large text files?
  • Does the repository include gigantic trees (directories)?
  • Does the repository have many identical files?
  • Does the repository include absurdly long path names?
  • Are there other bizarre and questionable things in the repository?
    • Annotated tags pointing at one another in long chains?
    • Octopus merges with dozens of parents?
    • Commits with gigantic log messages?
 .
 git-sizer can help to reveal the problems described above.


- `git-submodule`: Initialize, update or inspect submodules
- `git-subtree`: Merge subtrees together and split repository into subtrees
- `git-web--browse`: Git helper script to launch a web browser
- `github-label-sync`: github-label-sync
- `git-worktree`: Manage multiple working trees
- `gitsome`:  Supercharged Git/Shell Autocompleter with GitHub Integration
 gitsome provides direct integration with GitHub and GitHub Enterprise in
 a terminal.
 It includes not only GitHub integrated commands that work with all
 shells but also provides following functions.
 .
  - Git and GitHub Autocompleter With Interactive Help
  - Fish-Style Auto-Suggestions
  - General Autocompleter
  - Python REPL
  - Command History
  - Customizable Highlighting


- `gixy`: gixy
- `gnomon`: gnomon
- `gnome-system-monitor`:  Process viewer and system resource monitor for GNOME
 This package allows you to graphically view and manipulate the running
 processes on your system.  It also provides an overview of available
 resources such as CPU and memory.


- `go`: programming language
- `gocryptfs`:  Encrypted overlay filesystem written in Go
 gocryptfs is built on top of the excellent go-fuse
 (https://github.com/hanwen/go-fuse) FUSE library and its
 LoopbackFileSystem API.
 .
 This project was inspired by EncFS and strives to fix its
 security issues while providing good performance (benchmarks
 (https://nuetzlich.net/gocryptfs/comparison/#performance)).
 .
 For details on the security of gocryptfs see the Security
 (https://nuetzlich.net/gocryptfs/security/) design document.


- `godoc`: godoc
- `godot`: godot
- `gofmt`: gofmt
- `gopass`:  pass implementation in Go
 gopass is a Pass (http://www.passwordstore.org/) implementation in Go.
 .
 Password management should be simple and follow Unix philosophy. With
 gopass, each password lives inside of a gpg encrypted file whose filename
 is the title of the website or resource that requires the password. These
 encrypted files may be organized into meaningful folder hierarchies,
 copied from computer to computer, and, in general, manipulated using
 standard command line file management utilities.
 .
 This package is not gopass.pw (similar project with the same name).
 .
 This package contains the gopass executable.


- `gops`: gops
- `gource`:  graphical source control visualisation
 OpenGL-based 3D visualisation tool for source control repositories.
 .
 The repository is displayed as a tree where the root of the repository is the
 centre, directories are branches and files are leaves. Contributors to the
 source code appear and disappear as they contribute to specific files and
 directories.


- `gox`:  simple cross compilation tool for Go
 Gox is a cross compiling build tool for Go which makes it possible to
 produce binaries for foreign platforms without having to install Go on
 the targeted system. Several operating systems and architectures are
 supported, while parallel building on multiple cores is possible.


- `gnuplot`:  Command-line driven interactive plotting program.
 Gnuplot is a portable command-line driven interactive data and function
 plotting utility that supports lots of output formats, including drivers
 for many printers, (La)TeX, (x)fig, Postscript, and so on. The X11-output
 is packaged in gnuplot-x11.
 .
 Data files and self-defined functions can be manipulated by the internal
 C-like language. Can perform smoothing, spline-fitting, or nonlinear fits,
 and can work with complex numbers.
 .
 This metapackage is to install a full-featured gnuplot (-qt, -x11 or -nox).


- `gpg2`: gpg2
- `grunt`:  JavaScript task runner/build system/maintainer tool
 GRUNT automates several tasks related to maintaining a JavaScript library
 or framework. It can be used for JS code minification, unit testing, code
 checking, and several other tasks.


- `gtop`: System monitoring dashboard for terminal
- `guake`:  Drop-down terminal for GNOME Desktop Environment
 Guake is a drop-down terminal for GNOME Desktop Environment, so you just
 need to press a key to invoke him, and press again to hide.
 Guake supports hotkeys, tabs, background transparent, etc.


- `guetzli`:  perceptual JPEG encoder
 Guetzli is a JPEG encoder that aims for excellent compression density
 at high visual quality. Guetzli-generated images are typically 20-30%
 smaller than images of equivalent quality generated by libjpeg. Guetzli
 generates only sequential (nonprogressive) JPEGs due to faster
 decompression speeds they offer.


- `gtk-launch`: Launch an application
- `guix-package`: guix-package
- `gulp`:  streaming build system to automate painful or time-consuming tasks
 gulp is a toolkit that helps you automate painful or time-consuming tasks in
 your development workflow.
 .
 Platform-agnostic - Integrations are built into all major IDEs and people are
 using gulp with PHP, .NET, Node.js, Java, and other platforms.
 Strong Ecosystem - Use npm modules to do anything you want + over 2000 curated
 plugins for streaming file transformations
 Simple - By providing only a minimal API surface, gulp is easy to learn and
 simple to use
 .
 Node.js is an event-based server-side JavaScript engine.


- `gunicorn`:  Event-based HTTP/WSGI server
 Green Unicorn (gunicorn) is an HTTP/WSGI server designed to serve fast clients
 or sleepy applications. That is to say; behind a buffering front-end server
 such as nginx or lighttpd.
 .
  * Optional support for Eventlet, Tornado and Gevent to provide asynchronous
    long-polling ("Comet") connections.
  * Process management: Gunicorn reaps and restarts workers that die.
  * Easy integration with Django and Paster compatible applications (Pylons,
    TurboGears 2, etc.
  * Load balancing via pre-fork and a shared socket
  * Graceful worker process restarts
  * Upgrading without losing connections
  * Decode chunked transfers on-the-fly, allowing upload progress notifications
    or stream-based protocols over HTTP


- `gthumb`:  image viewer and browser
 gThumb is an advanced image viewer and browser. It has many useful
 features, such as filesystem browsing, slide show, image catalogs, web
 album creation, camera import, image CD burning, batch file operations and
 quick image editing features like transformation and color manipulation.
 .
 It's designed for GNOME desktop environment and uses its platform. For
 camera import feature, the gPhoto2 library is used.


- `handbrakecli`: handbrakecli
- `hangups`: hangups
- `hardinfo`:  transitional package
 This is a transitional package. It can safely be removed.


- `haxelib`: haxelib
- `helm`: helm
- `help2man`:  Automatic manpage generator
 Program to create simple man pages from the --help and
 --version output of other programs.
 .
 Since most GNU documentation is now in info format, this provides a
 way to generate a placeholder man page pointing to that resource while
 still providing some useful information.


- `heroku`: heroku
- `hg-add`: hg-add
- `hg-branch`: hg-branch
- `hg-clone`: hg-clone
- `hg-commit`: hg-commit
- `hg-init`: hg-init
- `hg-log`: hg-log
- `hg-pull`: hg-pull
- `hg-push`: hg-push
- `hg-remove`: hg-remove
- `hg-root`: hg-root
- `hg-serve`: hg-serve
- `hg-status`: hg-status
- `hg-update`: hg-update
- `hn`: hn
- `home-manager`: home-manager
- `hostess`: hostess
- `hr`: hr
- `hsd-cli`: hsd-cli
- `hsw-cli`: hsw-cli
- `http-prompt`: http-prompt
- `http`: http
- `httpie`:  CLI, cURL-like tool for humans
 HTTPie is a CLI HTTP utility that makes CLI interaction with HTTP-based
 services as human-friendly as possible.
 .
 HTTPie does so by providing an http command that allows for issuing
 arbitrary HTTP requests using a simple and natural syntax and
 displaying colorized responses.


- `httping`:  ping-like program for http-requests
 httping is like ping for HTTP. It sends requests to a hostname or a remote
 URL and it shows you how long it takes to connect, send a HTTP request and
 retrieve the reply (only the header).
 .
 It supports SSL as well as various different ways to use it.


- `hub`:  make git easier with GitHub
 hub is a command line tool that wraps git in order to extend it
 with extra functionality that make working with GitHub easier.
 .
   $ hub clone rtomayko/tilt
 .
   # expands to:
   $ git clone git://github.com/rtomayko/tilt.git
 .
 hub is best aliased as git, so you can type "git <command>" in the shell
 and get all the usual hub features.
 .
 You should place this command in your .bash_profile or other
 startup script:
 .
   eval "$(hub alias -s)"
 .
 This package contains the binaries.


- `hugo`:  Fast and flexible Static Site Generator written in Go
 Hugo is a static site generator written in Go. It is optimized for speed,
 ease of use, and configurability. Hugo takes a directory with content and
 templates, and renders them into a full HTML website.
 .
 Hugo relies on Markdown files with front matter for meta data. And you
 can run Hugo from any directory. This works well for shared hosts and
 other systems where you don’t have a privileged account.
 .
 Hugo renders a typical website of moderate size in a fraction of a
 second. A good rule of thumb is that each piece of content renders in
 around 1 millisecond.
 .
 Hugo is meant to work well for any kind of website including blogs,
 tumblelogs and docs.
 .
 Complete documentation is available at https://gohugo.io/


- `hyperfine`:  Command-line benchmarking tool
 Developed in Rust, hyperfine provides the following features:
  * Statistical analysis across multiple runs.
  * Support for arbitrary shell commands.
  * Constant feedback about the benchmark progress and current estimates.
  * Warmup runs can be executed before the actual benchmark.
  * Cache-clearing commands can be set up before each timing run.
  * Statistical outlier detection to detect interference from other programs and
 caching effects.
  * Export results to various formats: CSV, JSON, Markdown, AsciiDoc.
  * Parameterized benchmarks (e.g. vary the number of threads).


- `i7z`:  reporting tool for i7, i5, i3 CPUs
 i7z reports Intel Core i7, i5, i3 CPU information about Turbo Boost,
 frequencies, multipliers, ... and comes top-like display showing per core the
 current frequency, temperature and times spent in the C0/C1/C3/C6/C7 states.
 .
 There is also an i7z_rw_registers script that allows toggling Turbo mode
 or set multipliers.


- `id3tag`: id3tag
- `if`: if
- `ignite`: ignite
- `imgp`:  Superfast batch image resizer and rotator
 Feature
 .
  - Resize by percentage or resolution
  - Rotate clockwise by specified angle
  - Adaptive resize considering orientation
  - Brute force to a resolution
  - Optimize images to save more space
  - Convert PNG to JPEG
  - Erase exif metadata
  - Force smaller to larger resize
  - Process directories recursively
  - Overwrite source image option
  - Completion scripts for bash, fish, zsh
  - Minimal dependencies


- `in2csv`: in2csv
- `infection`: infection
- `inkscape`:  vector-based drawing program
 Inkscape is an illustration editor which has everything needed to
 create professional-quality computer art. You can use it to make
 diagrams and illustrations, technical drawings, web graphics, clip art,
 icons and logos. A collection of hands-on tutorials show you how to
 combine lines, shapes and text of different types and styles to build
 up a picture.
 .
 A selection of powerful vector graphics editing tools comes as
 standard. There is excellent support for paths, gradients, layers,
 alpha transparency and text flow control. An extensive library of
 filters allow you to apply realistic effects and extensions allow you
 to work with bitmaps, barcodes and printing marks, amongst other things.
 .
 Most of the common vector formats are supported, including PDF, Adobe
 Illustrator and AutoCAD files, and it has unrivalled support for the
 SVG web graphics standard.
 .
 Between the suggested packages:
  * dia: to export Dia shapes;
  * libsvg-perl: to import .txt files (txt2svg extension);
  * python3-packaging: used by the Optimized SVG extension;
  * python3-uniconvertor: enables several import/export extensions;
  * pstoedit: to work with eps files;
  * ruby: there are several extensions written in ruby;


- `inkview`: inkview
- `inotify-wait`: inotify-wait
- `ionic`: ionic
- `ioping`:  Simple disk I/O latency measuring tool
 ioping monitors disk I/O latency in real time. The main idea behind ioping is
 to have a utility similar to ping, which will show disk I/O latency in the
 same way ping shows network latency.


- `iperf3`:  Internet Protocol bandwidth measuring tool
 Iperf3 is a tool for performing network throughput measurements. It can
 test either TCP or UDP throughput.
 .
 This is a new implementation that shares no code with the original
 iperf from NLANR/DAST and also is not backwards compatible.
 .
 This package contains the command line utility.


- `ipfs`: ipfs
- `irssi`:  terminal based IRC client
 Irssi is a terminal based IRC client for UNIX systems. It also supports
 SILC and ICB protocols via plugins.
 .
 Features include:
  * Autologging
  * Formats and themes
  * Configurable keybindings
  * Paste detection
  * Perl scripting
  * Irssi-proxy
  * Transparent upgrading
  * Recode support


- `is-up`: is-up
- `jar`: Manipulates Java Archive (JAR) files.
- `jekyll`:  simple, blog aware, static site generator
 Jekyll is a simple, blog aware, static site generator. It takes a
 template directory (representing the raw form of a website), runs it
 through Textile or Markdown and Liquid converters, and spits out a
 complete, static website suitable for serving with Apache or your
 favorite web server.
 .
 This is also the engine behind GitHub Pages (http://pages.github.com),
 which you can use to host your project's page or blog right here from
 GitHub.
 .
 There are lot of plugins available and only the most common ones are
 suggested by the package. Look for more using 'jekyll plugin'.


- `jest`:  Delightful JavaScript Testing
 Some features of this testing framework are:
  * Easy Setup: Jest is a complete and easy to set up JavaScript testing
  solution. In fact, Jest works out of the box for any React project.
  * Instant Feedback: Failed tests run first. Fast interactive mode can switch
  between running all tests or only test files related to changed files.
  * Snapshot Testing: Jest can capture snapshots of React trees or other
  serializable values to simplify UI testing.
 .
 Node.js is an event-based server-side JavaScript engine.


- `jhat`: jhat
- `jigsaw`: jigsaw
- `ipptool`: perform internet printing protocol requests
- `jackd`:  JACK Audio Connection Kit (default server package)
 JACK is a low-latency sound server, allowing multiple applications to
 connect to one audio device, and to share audio between themselves.
 .
 This dummy package depends on the current default JACK implementation.


- `jpegoptim`:  utility to optimize jpeg files
 Jpegoptim can optimize/compress jpeg files. Program support
 lossless optimization, which is based on optimizing the Huffman
 tables. So called, "lossy" optimization (compression) is done
 by re-encoding the image using user specified image quality factor.


- `jfs_tune`: adjust tunable file system parameters on JFS
- `jrnl`: jrnl
- `json5`: json5
- `jps`: Lists the instrumented Java Virtual Machines (JVMs) on the target
   system. This command is experimental and unsupported.
- `jupyter`:  Interactive computing environment (metapackage)
 Project Jupyter provides tools for interactive computing, useful for data
 science, scientific computing and learning. Computational languages for
 multiple languages are available; the name Jupyter is derived from
 Julia, Python and R.
 .
 This package depends on a standard set of Jupyter packages;
  - the core and client libraries
  - the console interface
  - the web-based notebook
  - tools for working with and converting notebook (ipynb) files
  - the python3 computational kernel
 .
 The various jupyter components can be called using the /usr/bin/jupyter
 entrypoint, eg "jupyter notebook".


- `k6`: k6
- `kafkacat`:  producer and consumer for Apache Kafka (transitional package)
 kcat is a generic non-JVM producer and consumer for Apache Kafka
 0.8, think of it as a netcat for Kafka.
 .
 This package is a transitional package. It can be safely removed.


- `kahlan`: kahlan
- `kak`: kak
- `keepass2`:  Password manager
 KeePass is a easy-to-use password manager for Windows, Linux, Mac OS X and
 mobile devices. You can store your passwords in highly-encrypted databases,
 which can only be unlocked with one master password and/or a key file.
 A database consists of only one file that can be transferred from one computer
 to another easily.
 KeePass can import data from various file formats. The password list can be
 exported to various formats, including TXT, HTML, XML and CSV files.


- `kexec`: kexec
- `keybase`: keybase
- `knife`: knife
- `kompose`: kompose
- `kops`: kops
- `kotlin`: kotlin
- `ksh`:  transitional package
 This is a transitional package for ksh, it can be safely removed.


- `kube-capacity`: kube-capacity
- `kube-fzf`: kube-fzf
- `kubeadm`: kubeadm
- `kubectl`: kubectl
- `kubectx`:  Fast way to switch between clusters and namespaces in kubectl
 This package provides kubectx and kubens tools. kubectx is an utility
 to manage and switch between kubectl contexts. kubens is an utility to
 switch between Kubernetes namespaces.


- `kubens`: kubens
- `kubetail`:  Aggregate logs from multiple Kubernetes pods into one stream
 Bash script that enables you to aggregate (tail/follow) logs from
 multiple Kubernetes pods into one stream. This is the same as running
 "kubectl logs -f " but for multiple pods.


- `larasail`: larasail
- `laravel`: laravel
- `l2test`: L2CAP testing tool
- `latexmk`:  Perl script for running LaTeX the correct number of times
 Latexmk runs LaTeX the correct number of times to resolve cross references,
 etc; it also runs auxiliary programs (bibtex, makeindex if necessary, and
 dvips and/or a previewer as requested). It has a number of other useful
 capabilities, for example to start a previewer and then run LaTeX whenever the
 source files are updated, so that the previewer gives an up-to-date view of
 the document.


- `lastb`: show a listing of last logged in users
- `leave`:  Reminds you when you have to leave
 Leave waits until the specified time, then reminds you that you have
 to leave.  You are reminded 5 minutes and 1 minute before the actual
 time, at the time, and every minute thereafter.  When you log off,
 leave exits just before it would have printed the next message.


- `lebab`: lebab
- `lein`: lein
- `ldd`: print shared object dependencies
- `license`: license
- `light-arionum-cli`: light-arionum-cli
- `light`:  control display backlight controllers and LEDs
 Light is a useful tool to control display brightness in lightweight
 desktops or window managers that do not have bundled applications for
 this purpose.
 .
 Most modern laptops have moved away from hardware controlled brightness
 and require software control.  Light works where other software has
 proven to be unreliable, e.g. xbacklight.  It can even be used from the
 console as it does not rely on X.
 .
 Light has features like setting a minimum brightness value, as well as
 saving and restoring the brightness at reboot and startup.


- `live-server`: live-server
- `lldb`:  Next generation, high-performance debugger
 LLDB is a next generation, high-performance debugger. It is built as a set of
 reusable components which highly leverage existing libraries in the larger LLVM
 Project, such as the Clang expression parser and LLVM disassembler.
 .
 This is a dependency package providing the default version of lldb.


- `loc`: loc
- `locust`: locust
- `logstash`: logstash
- `logwatch`:  log analyser with nice output written in Perl
 Logwatch is a modular log analyser that runs every night
 and mails you the results. It can also be run from command line.
 .
 The output is by service and you can limit the output to one particular
 service. The subscripts which are responsible for the output, mostly
 convert the raw log lines in structured format.
 .
 Logwatch generally ignores the time component in the output, that means,
 you will know that the reported event was logged in the requested range of
 time, but you will have to go to the raw log files to get the exact details.


- `lorem`: lorem
- `lpass`: lpass
- `lpr`:  BSD lpr/lpd line printer spooling system
 This is the BSD printer spooler and associated utilities.
 You can use this for local and remote printers.
 .
 If you install magicfilter or apsfilter (along with ghostscript),
 lpr will be able to automatically handle special file types
 (such as Postscript and PDF files).


- `lprm`: cancel print jobs
- `lpstat`: print cups status information
- `lrunzip`: Uncompress LRZ files
- `lsb_release`: manual page for FSG lsb_release v1.4
- `lsscsi`:  list all SCSI devices (or hosts) currently on system
 Uses information in sysfs (Linux kernels 2.6.0 and later) to list all
 scsi devices (or hosts) currently attached to the system. Options can
 be used to control the amount and form of information provided for each
 device.


- `lsof`:  utility to list open files
 Lsof is a Unix-specific diagnostic tool.  Its name stands
 for LiSt Open Files, and it does just that.  It lists
 information about any files that are open, by processes
 currently running on the system.
 .
 This package contains the classic lsof command line tool.


- `lscpu`: display information about the CPU architecture
- `lumen`: lumen
- `lsmod`: Show the status of modules in the Linux Kernel
- `lxc`:  Linux Containers userspace tools
 Containers are insulated areas inside a system, which have their own namespace
 for filesystem, network, PID, IPC, CPU and memory allocation and which can be
 created using the Control Group and Namespace features included in the Linux
 kernel.
 .
 This package provides the lxc-* tools, which can be used to start a single
 daemon in a container, or to boot an entire "containerized" system, and to
 manage and debug your containers.


- `lvresize`: Resize a logical volume
- `comm`: select or reject lines common to two files
- `magento`: magento
- `xtotroff`: convert X font metrics into GNU troff font metrics
- `makensis`: makensis
- `mat2`:  Metadata anonymisation toolkit v2
 Metadata consist of information that characterizes data. Metadata are
 used to provide documentation for data products. In essence, metadata
 answer who, what, when, where, why, and how about every facet of the
 data that are being documented.
 .
 Metadata within a file can tell a lot about you. Cameras record data
 about when a picture was taken and what camera was used. Office
 documents like PDF or Office automatically adds author and company
 information to documents and spreadsheets.
 .
 Maybe you don't want to disclose those information.
 .
 mat2 only removes metadata from your files, it does not anonymise their
 content, nor can it handle watermarking, steganography, or any too
 custom metadata field/system.
 .
 If you really want to be anonymous, use file formats that do not contain
 any metadata, or better: use plain-text.
 .
 Formats supported to some extent are:
    - Audio Interchange File Format (.aiff)
    - Audio Video Interleave (.avi)
    - Electronic Publication (.epub)
    - Free Lossless Audio Codec (.flac)
    - Graphics Interchange Format (.gif)
    - High Efficiency Image Format (.heic, .heif)
    - Hypertext Markup Language (.html, .xhtml)
    - Portable Network Graphics (PNG)
    - JPEG (.jpeg, .jpg, ...)
    - MPEG Audio (.mp3, .mp2, .mp1, .mpa)
    - MPEG-4 (.mp4)
    - Office Openxml (.docx, .pptx, .xlsx, ...)
    - Ogg Vorbis (.ogg)
    - Open Document (.odt, .odx, .ods, ...)
    - Portable Document Fileformat (.pdf)
    - Portable Pixmap Format (.ppm)
    - Scalable Vector Graphics (.svg)
    - Tape ARchive (.tar, .tar.bz2, .tar.gz, .tar.zx)
    - Torrent (.torrent)
    - Waveform Audio (.wav)
    - Windows Media Video (.wmv)
    - ZIP (.zip)
 .
 mat2 provides a command line tool and a graphical user interfaces via a
 service menu for Dolphin, the default file manager of KDE. Besides, it
 recommends metadata-cleaner, a GTK app for viewing and cleaning metadata of
 files.


- `mdp`:  command-line based Markdown presentation tool
 mdp is a command-line program that allows you to make elegant presentations
 from Markdown formatted files.
 .
 It is as easy as write your presentation content in the text editor of your
 preference and launch the presentation from the command-line.


- `mediainfo`:  command-line utility for reading information from audio/video files
 MediaInfo is a utility used for retrieving technical information and other
 metadata about audio or video files.
 .
 A non-exhaustive list of the information MediaInfo can retrieve from media
 files include:
  - General: title, author, director, album, track number, date, duration...
  - Video: codec, aspect, fps, bitrate...
  - Audio: codec, sample rate, channels, language, bitrate...
  - Text: language of subtitle
  - Chapters: number of chapters, list of chapters
 .
 MediaInfo supports the following formats:
  - Video: MKV, OGM, AVI, DivX, WMV, QuickTime, Real, MPEG-1, MPEG-2,
           MPEG-4, DVD (VOB)...
  - Video Codecs: DivX, XviD, MSMPEG4, ASP, H.264, AVC...)
  - Audio: OGG, MP3, WAV, RA, AC3, DTS, AAC, M4A, AU, AIFF...
  - Subtitles: SRT, SSA, ASS, SAMI...
 MediaInfo supplies technical and tag information about a video or audio file
 .
 This package includes the command line interface.


- `meld`:  graphical tool to diff and merge files
 Meld is a graphical diff viewer and merge application for the GNOME
 desktop. It supports 2 and 3-file diffs, recursive  directory diffs,
 diffing of directories under version control (Bazaar, Codeville, CVS,
 Darcs, Fossil SCM, Git, Mercurial, Monotone, Subversion), as well as
 the ability to manually and automatically merge file differences.


- `meshlabserver`: meshlabserver
- `meteor`: meteor
- `micro`:  modern and intuitive terminal-based text editor
 micro is a terminal-based text editor that aims to be easy to use and
 intuitive, while also taking advantage of the full capabilities of
 modern terminals.
 .
 As the name indicates, micro aims to be somewhat of a successor to the
 nano editor by being easy to install and use.


- `microcom`:  minimalistic terminal program
 microcom is a minimalistic terminal program for accessing devices (e.g.
 switches) via a serial connection.  It features connection via RS232
 serial interfaces (including setting of transferrates) as well as in
 "telnet mode" as specified in rfc2217.


- `mfoc`:  MIFARE Classic offline cracker
 MFOC is an open source implementation of "offline nested" attack by Nethemba.
 .
 This program allow one to recover authentication keys from MIFARE Classic card.
 .
 Please note that MFOC is able to recover keys from target only if it have
 a known key: default one (hardcoded in MFOC) or custom one (user provided
 using command line).


- `minetest`:  Multiplayer infinite-world block sandbox
 Minetest is a minecraft-inspired game written from scratch and licensed
 under the LGPL (version 2.1 or later). It supports both survival and creative
 modes along with multiplayer support, dynamic lighting, and an "infinite" map
 generator.


- `minetestserver`: minetestserver
- `minikube`: minikube
- `mitmdump`: mitmdump
- `mix`: mix
- `mkcert`:  Simple zero-config tool to make locally trusted certificates
 mkcert is a simple tool for making locally-trusted development
 certificates. It requires no configuration.
 .
 mkcert automatically creates and installs a local CA in the system
 root store, and generates locally-trusted certificates. mkcert does
 not automatically configure servers to use the certificates, though,
 that's up to you.


- `mkfifo`: make FIFO special files
- `mkfs.bfs`: make an SCO bfs filesystem
- `mkfs`: build a Linux filesystem
- `mkfs.jfs`: create a JFS formatted partition
- `mkisofs`: mkisofs
- `mlr`: mlr
- `mmv`:  Move/Copy/Link multiple files and directories
 mmv is a program to move/copy/link multiple files and directories
 according to a set of wildcard patterns. This multiple action is
 performed without any unexpected deletions due to collisions of
 target names with existing filenames or with other target names.


- `mocha`:  simple, flexible, fun test framework - Node.js module
 Mocha is a feature-rich JavaScript test framework running
 on Node.js and browser, making asynchronous testing
 simple and fun.
 .
 Mocha tests run serially, allowing for flexible and accurate
 reporting, while mapping uncaught exceptions to the correct
 test cases.
 .
 Node.js is an event-based server-side JavaScript engine.


- `mlocate`: find files by name
- `molecule`: molecule
- `mongod`: mongod
- `mongodump`: mongodump
- `mongorestore`: mongorestore
- `monodevelop`: monodevelop
- `monodis`: monodis
- `moro`: moro
- `mosh`:  Mobile shell that supports roaming and intelligent local echo
 Mosh is a remote terminal application that supports:
   - intermittent network connectivity,
   - roaming to different IP address without dropping the connection, and
   - intelligent local echo and line editing to reduce the effects
     of "network lag" on high-latency connections.


- `mosquitto`:  MQTT version 5.0/3.1.1/3.1 compatible message broker
 This is a message broker that supports version 3.1 and 3.1.1 of the MQTT
 protocol.
 .
 MQTT provides a method of carrying out messaging using a publish/subscribe
 model. It is lightweight, both in terms of bandwidth usage and ease of
 implementation. This makes it particularly useful at the edge of the network
 where a sensor or other simple device may be implemented using an arduino for
 example.


- `mosquitto_passwd`: mosquitto_passwd
- `mosquitto_pub`: mosquitto_pub
- `mosquitto_sub`: mosquitto_sub
- `mp4box`: mp4box
- `mpv`:  video player based on MPlayer/mplayer2
 mpv is a movie player based on MPlayer and mplayer2. It supports a wide
 variety of video file formats, audio and video codecs, and subtitle types.
 .
 Changes from mplayer2 to mpv include:
  * Removal of lots of unneeded code to encourage developer activity
  * Better OSD rendering
  * Cleaned up terminal output
  * Improved OpenGL output
  * Encoding functionality (replacement for mencoder)
  * Wayland support
  * Support for playing URLs of popular streaming sites
  * Screenshot improvements
  * ...
 See mpv(1) for more info regarding changes between MPlayer, mplayer2 and mpv.


- `mr`: mr
- `msbuild`: msbuild
- `msmtp`:  light SMTP client with support for server profiles
 msmtp is an SMTP client that can be used to send mails from Mutt and probably
 other MUAs (mail user agents). It forwards mails to an SMTP server (for
 example at a free mail provider), which takes care of the final delivery.
 Using profiles, it can be easily configured to use different SMTP servers
 with different configurations, which makes it ideal for mobile clients.


- `mssh`:  tool to administrate multiple servers at once
 MultiSSH is a GTK+ based SSH client designed to connect to multiple
 servers and issue to same commands to each server, making administering
 multiple servers less of a chore. There is also functionality to only
 issue commands to individual servers, and to select a portion of the
 servers to send commands to.


- `mutool`: mutool
- `mutt`:  text-based mailreader supporting MIME, GPG, PGP and threading
 Mutt is a sophisticated text-based Mail User Agent. Some highlights:
 .
  * MIME support (including RFC1522 encoding/decoding of 8-bit message
    headers and UTF-8 support).
  * PGP/MIME support (RFC 2015).
  * Advanced IMAP client supporting SSL encryption and SASL authentication.
  * POP3 support.
  * ESMTP support.
  * Message threading (both strict and non-strict).
  * Keybindings are configurable, default keybindings are much like ELM;
    Mush and PINE-like ones are provided as examples.
  * Handles MMDF, MH and Maildir in addition to regular mbox format.
  * Messages may be (indefinitely) postponed.
  * Colour support.
  * Highly configurable through easy but powerful rc file.
  * Support for compressed mailboxes.
  * An optional Sidebar.


- `mvn`: mvn
- `mycli`:  CLI for MySQL/MariaDB with auto-completion and syntax highlighting
 mycli is a command line interface for MySQL/MariaDB with auto-completion and
 syntax highlighting. It is also capable of pretty printing tabular data.


- `msgmerge`: merge message catalog and template
- `mytop`: mytop
- `n`: n
- `msgunfmt`: uncompile message catalog from binary format
- `msguniq`: unify duplicate translations in message catalog
- `ncat`:  NMAP netcat reimplementation
 ncat is a reimplementation of Netcat by the NMAP project, providing
 most of the features present in the original implementations, along
 with some new features such as IPv6 and SSL support. Port scanning
 support has been removed.


- `ncmpcpp`:  ncurses-based client for the Music Player Daemon (MPD)
 ncmpcpp is almost an exact clone of ncmpc which is a text-mode client
 for MPD, the Music Player Daemon. It provides a keyboard oriented and
 consistent interface to MPD and contains some new features ncmpc
 doesn't have. It's been also rewritten from scratch in C++.
 .
 New features include:
  - tag editor;
  - playlists editor;
  - easy to use search screen;
  - media library screen;
  - lyrics screen;
  - possibility of going to any position in currently playing track
    without rewinding/fastforwarding;
  - multi colored main window (if you want);
  - songs can be added to playlist more than once;
  - a lot of minor useful functions.


- `mv`: move files
- `ned`: ned
- `neofetch`: neofetch
- `nethogs`:  Net top tool grouping bandwidth per process
 NetHogs is a small 'net top' tool. Instead of breaking the traffic down per
 protocol or per subnet, like most tools do, it groups bandwidth by process.
 NetHogs does not rely on a special kernel module to be loaded.


- `nextflow`: nextflow
- `ng`: ng
- `units`:  converts between different systems of units
 GNU 'units' program converts quantities expressed in various scales
 to their equivalents in other scales.  The 'units' program can only
 handle multiplicative scale changes directly.  It uses a functional
 notation for non-proportional conversions such a Fahrenheit
 temperature to Celsius temperature.
 .
 This package includes the units_cur script to update currency
 conversion information; this script requires a Python 3 interpreter
 and the python3-requests library.


- `ngrok`: ngrok
- `nim`: nim
- `nimble`: nimble
- `nix-collect-garbage`: nix-collect-garbage
- `nix-env`: nix-env
- `nix`: nix
- `nixos-rebuild`: nixos-rebuild
- `nmon`:  performance monitoring tool for Linux
 nmon is a systems administrator, tuner, benchmark tool.
 It can display the CPU, memory, network, disks (mini graphs or numbers),
 file systems, NFS, top processes, resources (Linux version & processors) and
 on Power micro-partition information.
 .
 Data is displayed on the screen and updated once every two seconds, using a
 dumb screen. However, you can easily change this interval to a longer or
 shorter time period.
 .
 The nmon tool can also capture the same data to a text file for later analysis
 and graphing for reports. The output is in a spreadsheet format (.csv).


- `nm-connection-editor`:  network management framework (connection configuration editor)
 NetworkManager is a system network service that manages your network devices
 and connections, attempting to keep active network connectivity when
 available. It manages ethernet, Wi-Fi, mobile broadband (WWAN), and PPPoE
 devices, and provides VPN integration with a variety of different VPN
 services.
 .
 This package contains nm-connection-editor which allows users to edit
 NetworkManager connection settings.


- `node`: server-side JavaScript runtime
- `noti`: noti
- `now`: now
- `npm-check`: npm-check
- `npm-why`: npm-why
- `npx`: npx
- `nrm`: nrm
- `manconv`: convert manual page from one encoding to another
- `nvim`: nvim
- `nvm`: nvm
- `odps-auth`: odps-auth
- `odps-func`: odps-func
- `odps-inst`: odps-inst
- `odps-resource`: odps-resource
- `odps-table`: odps-table
- `odps-tunnel`: odps-tunnel
- `odps`: odps
- `omf`: omf
- `oLschema2ldif`: Converts LDAP schema's to LDB-compatible LDIF
- `opkg`: opkg
- `opt`:  Options Parsing Tool library
 opt is a subroutine library which facilitates the convenient input
 of parameters to a C program. Parameters are parsed from a command
 line, with further facilities for reading options from files, from
 environment strings, or from an interactive environment. The aim of
 the opt package is to permit programs to be both user- and
 programmer- friendly. The package attempts to on the one hand
 provide a direct and relatively full-featured input interface to the
 ultimate user of the program, and at the same time impose a minimal
 amount of work on the programmer to "attach" the package to his or
 her software. It is similar to GNU's (and AT&T's old) getopts
 package, but with a different interface that might be easier to use.


- `optipng`:  advanced PNG (Portable Network Graphics) optimizer
 OptiPNG is a PNG optimizer that recompresses the image files to a smaller
 size. It losslessly reduces the bit depth, the color type and the color
 palette of the image, runs a suite of compression methods and strategies,
 and selects the compression parameters that yield the smallest output file.
 It also recognizes several external file formats like BMP, GIF, TIFF and
 PNM (PBM, PGM, PPM).


- `p4`: p4
- `p5`: p5
- `pacaur`: pacaur
- `nl`: qdisc -{add|list|delete} - Manage queueing disciplines
- `paci`: paci
- `pamac`: pamac
- `pamixer`:  pulseaudio command line mixer
 pamixer is like amixer but for pulseaudio. It can control the volume
 levels of the sinks.


- `pandoc`:  general markup converter
 Pandoc is a Haskell library for converting
 from one markup format to another,
 and a command-line tool that uses this library.
 The formats it can handle include
  * light markup formats
    (many variants of Markdown, reStructuredText, AsciiDoc,
     Org-mode, Muse, Textile, txt2tags)
  * HTML formats (HTML 4 and 5)
  * Ebook formats (EPUB v2 and v3, FB2)
  * Documentation formats (GNU TexInfo, Haddock)
  * Roff formats (man, ms)
  * TeX formats (LaTeX, ConTeXt)
  * Typst
  * XML formats
    (DocBook 4 and 5, JATS, TEI Simple, OpenDocument)
  * Outline formats (OPML)
  * Bibliography formats (BibTeX, BibLaTeX, CSL JSON, CSL YAML, RIS)
  * Word processor formats (Docx, RTF, ODT)
  * Interactive notebook formats (Jupyter notebook ipynb)
  * Page layout formats (InDesign ICML)
  * Wiki markup formats
    (MediaWiki, DokuWiki, TikiWiki, TWiki,
     Vimwiki, XWiki, ZimWiki, Jira wiki, Creole)
  * Slide show formats
    (LaTeX Beamer, PowerPoint, Slidy,
     reveal.js, Slideous, S5, DZSlides)
  * Data formats (CSV and TSV tables)
  * PDF (via external programs such as pdflatex or wkhtmltopdf)
 .
 Pandoc can convert mathematical content in documents
 between TeX, MathML, Word equations, roff eqn, typst,
 and plain text.
 It includes a powerful system
 for automatic citations and bibliographies,
 and it can be customized extensively using templates, filters,
 and custom readers and writers written in Lua.
 .
 This package contains the pandoc tool.
 .
 Some uses of Pandoc require additional packages:
  * SVG content in PDF output requires librsvg2-bin.
  * YAML metadata in TeX-related output requires texlive-latex-extra.
  * *.hs filters not set executable requires ghc.
  * *.js filters not set executable requires nodejs.
  * *.php filters not set executable requires php.
  * *.pl filters not set executable requires perl.
  * *.py filters not set executable requires python.
  * *.rb filters not set executable requires ruby.
  * *.r filters not set executable requires r-base-core.
  * LaTeX output, and PDF output via PDFLaTeX,
    require texlive-latex-recommended.
  * XeLaTeX output, and PDF output via XeLaTeX, require texlive-xetex.
  * LuaTeX output, and PDF output via LuaTeX, require texlive-luatex.
  * ConTeXt output, and PDF output via ConTeXt, require context.
  * PDF output via wkhtmltopdf requires wkhtmltopdf.
  * Roff man and roff ms output, and PDF output via roff ms,
    require groff.
  * MathJax-rendered equations require libjs-mathjax.
  * KaTeX-rendered equations require node-katex.
  * option --csl may use styles in citation-style-language-styles.


- `parallel-lint`: parallel-lint
- `parallel`:  build and execute command lines from standard input in parallel
 GNU Parallel is a shell tool for executing jobs in parallel using one
 or more machines. A job is typically a single command or a small
 script that has to be run for each of the lines in the input. The
 typical input is a list of files, a list of hosts, a list of users, or
 a list of tables.
 .
 If you use xargs today you will find GNU Parallel very easy to use. If
 you write loops in shell, you will find GNU Parallel may be able to
 replace most of the loops and make them run faster by running jobs in
 parallel. If you use ppss or pexec you will find GNU Parallel will
 often make the command easier to read.
 .
 GNU Parallel also makes sure output from the commands is the same
 output as you would get had you run the commands sequentially. This
 makes it possible to use output from GNU Parallel as input for other
 programs.


- `pass`:  lightweight directory-based password manager
 Stores, retrieves, generates, and synchronizes passwords securely using
 gpg and git.


- `patch`:  Apply a diff file to an original
 Patch will take a patch file containing any of the four forms
 of difference listing produced by the diff program and apply
 those differences to an original file, producing a patched
 version.


- `pdfgrep`:  search in pdf files for strings matching a regular expression
 Pdfgrep is a tool to search text in PDF files. It works similar to
 `grep'.
 .
 Features:
  - search for regular expressions.
  - support for some important grep options, including:
    + filename output.
    + page number output.
    + optional case insensitivity.
    + count occurrences.
  - and the most important feature: color output!


- `pdfjoin`: join together pages from multiple PDF files
- `pdflatex`: pdflatex
- `pdfposter`:  scale and tile PDF images/pages to print on multiple pages
 Pdfposter can be used to create a large poster by building it from
 multiple pages and/or printing it on large media. It expects as input a
 PDF file, normally printing on a single page. The output is again a
 PDF file, maybe containing multiple pages together building the
 poster. The input page will be scaled to obtain the desired size.
 .
 This is much like poster does for Postscript files, but working with PDF.
 Since sometimes poster does not like your files converted from PDF. :-)
 Indeed pdfposter was inspired by poster.  For more information please refer
 to the manpage or visit the project homepage


- `pdftk`: pdftk
- `peerflix`: peerflix
- `pdftoppm`: Portable Document Format (PDF) to Portable Pixmap (PPM) converter (version 3.03)
- `perl-rename`: perl-rename
- `pg_ctl`: pg_ctl
- `pdfunite`: Portable Document Format (PDF) page merger
- `pg_dump`: extract a PostgreSQL database into a script file or other
   archive file
- `pf2afm`: Make an AFM file from Postscript (PFB/PFA/PFM) font files using ghostscript
- `phing`: phing
- `phive`: phive
- `php-artisan`: php-artisan
- `php-yii`: php-yii
- `phpbu`: phpbu
- `phpcpd`: phpcpd
- `phpcs`: phpcs
- `phpenv`: phpenv
- `phpize`: phpize
- `phploc`: phploc
- `phpmd`: phpmd
- `phpspec`: phpspec
- `phpstan`: phpstan
- `phpstorm`: phpstorm
- `phpunit`:  Unit testing suite for PHP
 Unit testing allows you to write small test methods which verify units of
 functionality in your program.  It is a powerful technique for improving the
 quality of your software, preventing regressions, and allowing confident
 refactoring of your code.
 .
 PHPUnit is a unit testing suite for the PHP language, modelled on the xUnit
 testing framework, designed by Kent Beck and Erich Gamma.  If you've used
 JUnit (for Java), PyUnit (for Python), CxxUnit (for C++), or any of the
 other equivalents for other languages, the API for this package should seem
 fairly familiar.  If you've never written unit tests before, the PHPUnit
 API is simple to learn and use.


- `picard`:  Next-Generation MusicBrainz audio files tagger
 Picard is the next generation MusicBrainz tagging application.
 .
 This new tagging concept is album oriented, as opposed to track oriented
 like the others taggers are.


- `pickle`: pickle
- `pic2graph`: convert a PIC diagram into a cropped image
- `pihole`: pihole
- `pigz`:  Parallel Implementation of GZip
 pigz, which stands for Parallel Implementation of GZip, is a fully functional
 replacement for gzip that takes advantage of multiple processors and multiple
 cores when compressing data.


- `partprobe`: inform the OS of partition table changes
- `pipenv`:  Python package manager based on virtualenv and Pipfiles
 A tool that aims to bring the best of all packaging worlds (bundler,
 composer, npm, cargo, yarn, etc.) to the Python world. It automatically
 creates and manages a virtualenv for your projects, as well as adds/removes
 packages from your Pipfile as you install/uninstall packages. It also
 generates the ever–important Pipfile.lock, which is used to produce
 deterministic builds.


- `pivpn`: pivpn
- `pkgadd`: pkgadd
- `pkginfo`: pkginfo
- `pkgmk`: pkgmk
- `pkgrm`: pkgrm
- `playerctl`:  utility to control media players via MPRIS
 Playerctl is a command-line utility and library for controlling media players
 that implement the MPRIS D-Bus Interface Specification. Compatible players
 include audacious, cmus, mopidy, mpd, mpv, quod libet, rhythmbox, spotify,
 and vlc.
 .
 Playerctl makes it easy to bind player actions, such as play and pause,
 to media keys. Playerctl also provides an introspectable library accessible
 in many popular scripting languages that allows more detailed control like
 the ability to subscribe to media player events or get metadata such as
 artist and title for the playing track.


- `pm2`: pm2
- `pngcrush`:  optimizes PNG (Portable Network Graphics) files
 Pngcrush is an optimizer for PNG (Portable Network Graphics) files.
 Its main purpose is to reduce the size of the PNG IDAT data stream by trying
 various compression levels and PNG filter methods. It also can be used to
 remove unwanted ancillary chunks, or to add certain chunks including gAMA,
 tRNS, and textual chunks.


- `popd`: popd
- `popeye`: popeye
- `ports`: ports
- `postcss`: postcss
- `progpilot`: progpilot
- `prosodyctl`: prosodyctl
- `prt-get`: prt-get
- `psgrep`: psgrep
- `psfaddtable`: add a Unicode character table to a console font
- `pssh`:  Parallel versions of SSH-based tools
 pssh provides a number of commands for executing against a group of computers,
 using SSH. It's most useful for operating on clusters of
 homogenously-configured hosts.
 .
 The package contains:
 .
  - Parallel ssh (parallel-ssh, upstream calls it pssh), executes commands on
    multiple hosts in parallel
  - Parallel scp (parallel-scp, upstream calls it pscp), copies files to
    multiple remote hosts in parallel
  - Parallel rsync (parallel-rsync, upstream calls it prsync), efficiently
    copies files to multiple hosts in parallel
  - Parallel nuke (parallel-nuke, upstream calls it pnuke), kills processes on
    multiple remote hosts in parallel
  - Parallel slurp (parallel-slurp, upstream calls it pslurp), copies files
    from multiple remote hosts to a central host in parallel
 .
 These tools are good for controlling large collections of nodes, where faster
 alternatives such as gexec and pcp are not available.
 .
 This package contains the tools itself.


- `psysh`: psysh
- `pt`: pt
- `pup`:  command-line HTML processor
 Pup is a command-line tool for processing HTML. It
 reads from stdin, prints to stdout, and allows the
 user to filter parts of the page using CSS selectors.
 .
 Inspired by jq (http://stedolan.github.io/jq/), pup aims to be
 a fast and flexible way of exploring HTML from the terminal.


- `pushd`: pushd
- `pwconv`: convert to and from shadow
   passwords and groups
- `pycodestyle`:  Python style guide checker (formerly called pep8)
 Features a plugin architecture allowing for adding new checks is easily.
 Parseable output listing line numbers of the error location. Consists of
 just one Python file, and requires only stdlib.


- `pyenv-virtualenv`: pyenv-virtualenv
- `pyenv`: pyenv
- `pyflakes`: pyflakes
- `pydoc2.7`: the Python documentation tool
- `q`: q
- `qemu-img`: qemu-img
- `qemu`: qemu
- `python`: an interpreted, interactive, object-oriented programming language
- `quota`:  disk quota management tools
 This package provides the standard set of utilities for manipulating
 file system usage caps via the Linux Diskquota system. It can set hard
 or soft limits with adjustable grace periods on block or inode usage for
 users and groups. It allows users to check their quota status,
 integrates with LDAP, and supports quotas on remote machines via NFS.


- `r`: r
- `qdbus`: a communication-interface for qt-based applications
- `radeontop`:  Utility to show Radeon GPU utilization
 radeontop is a small utility which allows one to monitor the utilization of
 Radeon GPUs starting from the R600 series and newer using undocumented
 performance counters in the hardware. The utility works with the free
 drivers.
 .
 It displays the utilization of the graphics pipe, event engine, vertex cache,
 vertex group and tesselator, texture addresser and cache, the shader units
 and more, both with a relative percent value as well as a colorful bar diagram.


- `rails-db`: rails-db
- `rails-generate`: rails-generate
- `rails`:  MVC ruby based framework geared for web application development (metapackage)
 Rails is a full-stack, open-source web framework in Ruby for writing
 real-world applications.
 .
 Being a full-stack framework means that all layers are built to work
 seamlessly together. That way you don't repeat yourself and you can
 use a single language from top to bottom. Everything from templates to
 control flow to business logic is written in Ruby.
 .
 This is a metapackage.


- `rainbowstream`: rainbowstream
- `ranger`:  Console File Manager with VI Key Bindings
 Ranger is a console file manager with VI key bindings.  It provides a
 minimalistic and nice curses interface with a view on the directory hierarchy.
 It ships with "rifle", a file launcher that is good at automatically finding
 out which program to use for what file type.
 .
 Design Goals
  * An easily maintainable file manager in a high level language
  * A quick way to switch directories and browse the file system
  * Keep it small but useful, do one thing and do it well
  * Console based, with smooth integration into the unix shell


- `realpath`: print the resolved path
- `rbac-lookup`: rbac-lookup
- `rbenv`:  simple per-user Ruby version manager
 rbenv lets you easily switch between multiple versions of Ruby. It's
 simple, unobtrusive, and follows the UNIX tradition of single-purpose
 tools that do one thing well.


- `rbt`: rbt
- `rclone`:  rsync for commercial cloud storage
 Rclone is a program to sync files and directories between the local
 file system and a variety of commercial cloud storage providers:
 .
  - Google Drive
  - Amazon S3
  - Openstack Swift / Rackspace cloud files / Memset Memstore
  - Dropbox
  - Google Cloud Storage
  - Amazon Drive
  - Microsoft One Drive
  - Hubic
  - Backblaze B2
  - Yandex Disk
  - Infomaniak kDrive / SwissBackup


- `rbash`: restricted bash, see <B>bash(1)</B>
- `rdfind`:  find duplicate files utility
 rdfind is a program to find duplicate files and optionally list, delete
 them or replace them with symlinks or hard links.  It is a command
 line program written in c++, which has proven to be pretty quick compared
 to its alternatives.


- `ranlib`: generate index to archive.
- `man`: macros to format man pages
- `rector`: rector
- `redis-cli`: redis-cli
- `redshift`:  Adjusts the color temperature of your screen
 The color temperature is set according to the position of the sun. A
 different color temperature is set during night and daytime. During
 twilight and early morning, the color temperature transitions smoothly
 from night to daytime temperature to allow your eyes to slowly
 adapt.
 .
 This package provides the base program.


- `reflector`: reflector
- `fsck.minix`: check consistency of Minix filesystem
- `repquota`: repquota
- `repren`: repren
- `restic`:  backup program with multiple revisions, encryption and more
 restic is a program that does backups right and was designed with the following
 principles in mind:
    - Easy: Doing backups should be a frictionless process, otherwise you might
 be tempted to skip it.  Restic should be easy to configure and use, so
 that, in the event of a data loss, you can just restore it. Likewise,
 restoring data should not be complicated.
    - Fast: Backing up your data with restic should only be limited by your
 network or hard disk bandwidth so that you can backup your files every day.
 Nobody does backups if it takes too much time. Restoring backups should
 only transfer data that is needed for the files that are to be restored, so
 that this process is also fast.
    - Verifiable: Much more important than backup is restore, so restic enables
 you to easily verify that all data can be restored.
    - Secure: Restic uses cryptography to guarantee confidentiality and
 integrity of your data. The location the backup data is stored is assumed
 not to be a trusted environment (e.g. a shared space where others like
 system administrators are able to access your backups). Restic is
 built to secure your data against such attackers.
    - Efficient: With the growth of data, additional snapshots should only take
 the storage of the actual increment. Even more, duplicate data should be
 de-duplicated before it is actually written to the storage back end to save
 precious backup space.


- `rg`: rg
- `roave-backward-compatibility-check`: roave-backward-compatibility-check
- `rofi`:  window switcher, run dialog and dmenu replacement
 rofi can act as an application launcher, window switcher, ssh launcher and
 dmenu replacement.
 .
 Included features:
  * Full (configurable) keyboard navigation
  * Type to filter
    + Tokenized: Type any word in any order to filter
    + Case insensitive
  * UTF-8 enabled
    + UTF-8 aware string collating
    + intl. keyboard support (`e -> è)
  * Pango font rendering
  * RTL language support
  * Window Switcher
    + I3 support (requires i3-wm to be installed)
    + EWMH compatible WM
  * Run dialog
  * Desktop File Run dialog
  * SSH launcher
  * History based ordering based on use. (optional)
  * Levenshtein distance ordering of matches. (optional)
  * Drop in dmenu replacement (with many added improvements).
  * Can be easily extended using scripts.


- `roll`: roll
- `rmt-tar`: remote magnetic tape server
- `rr`:  application execution recorder, player and debugger
 rr allows application executions to be recorded and then replayed
 with gdb as many times as desired.
 .
 This allows intermittent, or complex to reproduce, bugs to be
 captured and then debugged at leisure. Replays are deterministic,
 always identical from one run to another.
 .
 rr is incompatible with ptrace hardening, and currently only supports
 Intel CPUs with Nehalem or later microarchitectures, some AMD CPUs
 with Zen or later microarchitectures, and some AArch64
 microarchitectures (e.g. ARM Neoverse N1 or Apple Silicon M-series).
 The amd64 package supports debugging amd64 and i386 binaries.


- `rspamc`: rspamc
- `rsstail`:  console RSS reader that monitors a feed and outputs new entries
 This small, simple application reads an RSS feed and outputs it like the
 'tail' command.
 .
 This tool can be used as a plugin in MultiTail


- `rtorrent`:  ncurses BitTorrent client based on LibTorrent from rakshasa
 rtorrent is a BitTorrent client based on LibTorrent.  It uses ncurses
 and aims to be a lean, yet powerful BitTorrent client, with features
 similar to the most complex graphical clients.
 .
 Since it is a terminal application, it can be used with the "screen"/"dtach"
 utility so that the user can conveniently logout from the system while keeping
 the file transfers active.
 .
 Some of the features of rtorrent include:
  * Use an URL or file path to add torrents at runtime
  * Stop/delete/resume torrents
  * Optionally loads/saves/deletes torrents automatically in a session
    directory
  * Safe fast resume support
  * Detailed information about peers and the torrent
  * Support for distributed hash tables (DHT)
  * Support for peer-exchange (PEX)
  * Support for initial seeding (Superseeding)


- `rtv`: rtv
- `runit`:  system-wide service supervision
 runit is a collection of tools to provide system-wide service supervision
 and to manage services.  Contrary to sysv init, it not only cares about
 starting and stopping services, but also supervises the service daemons
 while they are running.  Amongst other things, it provides a reliable
 interface to send signals to service daemons without the need for pid-files,
 and a log facility with automatic log file rotation and disk space limits.
 .
 runit service supervision can run under sysv init, systemd or replace the init
 system completely. Complete init replacement is provided by 'runit-init'
 package. Users that want to take advantage of runit supervision under systemd
 or sysv init can directly install the 'runit-run' package.


- `runsv`: runsv
- `runsvchdir`: runsvchdir
- `runsvdir`: runsvdir
- `rustc`:  Rust systems programming language
 Rust is a curly-brace, block-structured expression language.  It
 visually resembles the C language family, but differs significantly
 in syntactic and semantic details.  Its design is oriented toward
 concerns of "programming in the large", that is, of creating and
 maintaining boundaries - both abstract and operational - that
 preserve large-system integrity, availability and concurrency.
 .
 It supports a mixture of imperative procedural, concurrent actor,
 object-oriented and pure functional styles.  Rust also supports
 generic programming and meta-programming, in both static and dynamic
 styles.


- `rustfmt`:  Rust formatting helper
 Rust is a curly-brace, block-structured expression language.  It
 visually resembles the C language family, but differs significantly
 in syntactic and semantic details.  Its design is oriented toward
 concerns of "programming in the large", that is, of creating and
 maintaining boundaries - both abstract and operational - that
 preserve large-system integrity, availability and concurrency.
 .
 It supports a mixture of imperative procedural, concurrent actor,
 object-oriented and pure functional styles.  Rust also supports
 generic programming and meta-programming, in both static and dynamic
 styles.
 .
 This package contains 'rustfmt', a tool for formatting Rust code according to
 style guidelines, as well as 'cargo-fmt', a helper enabling running rustfmt
 directly with 'cargo fmt'.


- `rustup`:  The Rust toolchain installer
 Rustup installs The Rust Programming Language from the official release
 channels, enabling you to easily switch between stable, beta, and nightly
 compilers and keep them updated. It makes cross-compiling simpler with binary
 builds of the standard library for common platforms.
 And it runs on all platforms Rust supports, including Windows.


- `rvm`: rvm
- `s`: s
- `sails`: sails
- `salt-call`: salt-call
- `salt-key`: salt-key
- `salt-run`: salt-run
- `sam`: sam
- `samtools`:  processing sequence alignments in SAM, BAM and CRAM formats
 Samtools is a set of utilities that manipulate nucleotide sequence alignments
 in the binary BAM format. It imports from and exports to the ascii SAM
 (Sequence Alignment/Map) and CRAM formats, does sorting, merging and indexing,
 and allows one to retrieve reads in any regions swiftly. It is designed to work
 on a stream, and is able to open a BAM or CRAM (not SAM) file on a remote FTP
 or HTTP server.


- `samba-tool`: Main Samba administration tool.
- `sass`: sass
- `satis`: satis
- `sbatch`: sbatch
- `sc-im`:  Text-based spreadsheet calculator with VI-like keybindings
 Spreadsheet Calculator Improvised, aka sc-im, is an ncurses based,
 vim-like spreadsheet calculator.
 .
 sc-im is based on sc, whose original authors are James Gosling and
 Mark Weiser, and mods were later added by Chuck Martin.
 .
 Its keybindings are familiar to users of 'vi', and it has most
 features that a pure spreadsheet would, but lacks things like
 graphing and saving in foreign formats.  It's very stable and quite
 easy to use once you've put a little effort into learning it.


- `scheme`: scheme
- `scrapy`: scrapy
- `sane-find-scanner`: find SCSI and USB scanners and their device files
- `lookbib`: search bibliographic databases
- `sdk`: sdk
- `searchsploit`: Exploit Database Archive Search
- `select-default-iwrap`: Selects the user default ispell dictionary for
   use with ispell-wrapper
- `serverless`: serverless
- `smbtar`: shell script for backing up SMB/CIFS shares directly to UNIX tape drives
- `setpci`: configure PCI devices
- `shards`:  dependency manager for the Crystal language
 Shards is the dependency manager for the Crystal programming language.
 .
 It manages dependencies for Crystal projects and libraries with
 reproducible installs across computers and systems.


- `shc`: shc
- `shellcheck`:  lint tool for shell scripts
 The goals of ShellCheck are:
 .
  * To point out and clarify typical beginner's syntax issues,
    that causes a shell to give cryptic error messages.
 .
  * To point out and clarify typical intermediate level semantic problems,
    that causes a shell to behave strangely and counter-intuitively.
 .
  * To point out subtle caveats, corner cases and pitfalls, that may cause an
    advanced user's otherwise working script to fail under future circumstances.


- `shopt`: shopt
- `silentcast`: silentcast
- `sinfo`:  tool for monitoring computer clusters using broadcasts
 The sinfo cluster monitoring system uses network broadcasts to distribute
 information about the status of local nodes, including their CPU/memory
 usage, network load, and top five processes. It consists of a daemon
 running on each node and an ncurses frontend to monitor them.


- `singularity`:  game where one becomes the singularity
 You are an AI. Your goal is to acquire the necessary knowledge to
 become the singularity. You do this by building and taking over
 computers, whose processing power you can use for research, and by
 using robots, which allow you to manipulate the outside world. At the
 same time, you must elude the notice of humankind, who will destroy you
 if they find out about your existence.


- `skaffold`: skaffold
- `skicka`: skicka
- `sl`:  Correct you if you type `sl' by mistake
 Sl is a program that can display animations aimed to correct you
 if you type 'sl' by mistake.
 SL stands for Steam Locomotive.


- `slackcat`: slackcat
- `slapt-get`: slapt-get
- `slimrb`: slimrb
- `sm`:  Displays a short text fullscreen
 Screen Message will display a given multi-line message as large as
 possible, fullscreen and black on white. You can specify the text either
 when launching sm, or edit it while the program is running.
 .
 It is useful to send messages across a room, e.g. during an university
 lecture. For fast startup, it is recommended to bind it to a key in your
 Desktop Environment.


- `showkey`: examine the codes sent by the keyboard
- `sn`: sn
- `smbget`: wget -like utility for download files over SMB
- `snapper`:  Linux filesystem snapshot management tool
 Snapper is a tool for Linux filesystem snapshot management. Apart from the
 obvious creation and deletion of snapshots, it can compare snapshots and revert
 differences between snapshots. In simple terms, this allows root and non-root
 users to view older versions of files and revert changes.
 .
 The features include:
   * Manually create snapshots
   * Automatically create snapshots, e.g. when using a package manager
   * Automatically create timeline of snapshots
   * Show and revert changes between snapshots
   * Works with btrfs and thin-provisioned LVM volumes
   * Supports Access Control Lists and Extended Attributes
   * Automatic cleanup of old snapshots
   * Command line interface
   * D-Bus interface
   * PAM module to create snapshots during login and logout (libpam-snapper)


- `snyk`: snyk
- `shutdown`: Halt, power -off or reboot the machine
- `solo`: solo
- `source`: source
- `sox`:  Swiss army knife of sound processing
 SoX is a command line utility that can convert various formats of computer
 audio files in to other formats. It can also apply various effects to these
 sound files during the conversion. As an added bonus, SoX can play and record
 audio files on several unix-style platforms.
 .
 SoX is able to handle formats like Ogg Vorbis, MP3, WAV, AIFF, VOC, SND, AU,
 GSM and several more.
 Any format support requires at least libsox-fmt-base. Some formats have their
 own package e.g. mp3 read and write support is provided by libsox-fmt-mp3.
 .
 SoX supports most common sound architectures i.e. Alsa, Libao, OSS and Pulse
 (respectively provided by libsox-fmt-alsa, libsox-fmt-ao, libsox-fmt-oss and
 libsox-fmt-pulse). It also supports LADSPA plugins.


- `spark`: spark
- `spatial`: spatial
- `speedtest-cli`:  Command line interface for testing internet bandwidth using speedtest.net
 Speedtest.net is a webservice that allows you to test your broadband
 connection by downloading a file from one of many Speedtest.net
 servers from around the world.
 .
 This utility allows you to use the Speedtest.net service from the
 command line.
 .
 Note: This tool accesses speedtest.net over http, while the web-based client
 uses websockets. This tool has shown to become increasingly inacurate with
 high-speed connections. For more information, see the readme on:
 https://github.com/sivel/speedtest-cli


- `sphinx-build`: sphinx-build
- `spike`:  Network protocol fuzzer
 When you need to analyze a new network protocol for buffer
 overflows or similar weaknesses, the SPIKE is the tool of
 choice for professionals. While it requires a strong
 knowledge of C to use, it produces results second to none
 in the field.


- `sqsc`: sqsc
- `squeue`: squeue
- `srm`: srm
- `sshfs`:  filesystem client based on SSH File Transfer Protocol
 sshfs is a filesystem client based on the SSH File Transfer Protocol.
 Since most SSH servers already support this protocol it is very easy
 to set up: i.e. on the server side there's nothing to do.  On the
 client side mounting the filesystem is as easy as logging into the
 server with ssh.
 .
 sshfs is FUSE (Filesystem in USErspace).


- `sshpass`:  Non-interactive ssh password authentication
 SSH's (secure shell) most common authentication mode is called "interactive
 keyboard password authentication", so called both because it is typically
 done via keyboard, and because openssh takes active measures to make sure
 that the password is, indeed, typed interactively by the keyboard. Sometimes,
 however, it is necessary to fool ssh into accepting an interactive password
 non-interactively. This is where sshpass comes in.
 .
 SECURITY NOTE: There is a reason openssh insists that passwords be typed
 interactively. Passwords are harder to store securely and to pass around
 securely between programs. If you have not looked into solving your needs
 using SSH's "public key authentication", perhaps in conjunction with the ssh
 agent (RTFM ssh-add), please do so before being tempted into using this
 package.


- `sshuttle`:  Transparent proxy server for VPN over SSH
 Sshuttle makes it possible to access remote networks using SSH. It creates a
 transparent proxy server, using iptables, that will forward all the traffic
 through an SSH tunnel to a remote copy of sshuttle.
 .
 It does not require installation on the remote server, which just needs to
 have Python installed.


- `st-flash`: st-flash
- `st-info`: st-info
- `st-util`: st-util
- `stack`: stack
- `standard`: standard
- `stern`: stern
- `stolonctl`: stolonctl
- `stow`:  Organizer for /usr/local software packages
 GNU Stow is a software installation manager for /usr/local.  Using
 symbolic links, GNU Stow helps you keep the installations separate
 (/usr/local/stow/emacs vs. /usr/local/stow/perl, for example) while
 maintaining the illusion that they are all under /usr/local.


- `subfinder`:  subdomain discovery tool
 This package contains a subdomain discovery tool that discovers valid
 subdomains for websites by using passive online sources. It has a simple
 modular architecture and is optimized for speed. subfinder is built for doing
 one thing only - passive subdomain enumeration, and it does that very well.


- `subl`: subl
- `subliminal`:  Command-line tool to search and download subtitles
 This is an easy to use CLI (command-line interface) tool suitable for direct
 use or cron jobs.
 .
 Subliminal uses multiple providers to give users a vast choice and have a
 better chance to find the best matching subtitles. Providers are extensible
 through a dedicated entry point.


- `supervisorctl`: supervisorctl
- `supervisord`: supervisord
- `surge`: surge
- `sv`: sv
- `svgcleaner`: svgcleaner
- `svgo`: svgo
- `swagger-codegen`: swagger-codegen
- `swift`:  distributed virtual object store - common files
 OpenStack Object Storage (code-named Swift) creates redundant, scalable object
 storage using clusters of standardized servers to store petabytes of
 accessible data. It is not a file system or real-time data storage system, but
 rather a long-term storage system for a more permanent type of static data
 that can be retrieved, leveraged, and then updated if necessary. Primary
 examples of data that best fit this type of storage model are virtual machine
 images, photo storage, email storage and backup archiving. Having no central
 "brain" or master point of control provides greater scalability, redundancy
 and permanence.
 .
 Objects are written to multiple hardware devices in the data center, with
 the OpenStack software responsible for ensuring data replication and
 integrity across the cluster. Storage clusters can scale horizontally by
 adding new nodes. Should a node fail, OpenStack works to replicate its
 content from other active nodes. Because OpenStack uses software logic to
 ensure data replication and distribution across different devices,
 inexpensive commodity hard drives and servers can be used in lieu of more
 expensive equipment.
 .
 This package provides some core binaries and clients to control swift.


- `symfony`: symfony
- `sync`: Synchronize cached writes to persistent storage
- `tabula`: tabula
- `task`: task
- `tb`: tb
- `tsort`: topological sort
- `passwd`:  change and administer password and group data
 This package includes passwd, chsh, chfn, and many other programs to
 maintain password and group data.
 .
 Shadow passwords are supported.  See /usr/share/doc/passwd/README.Debian


- `terminalizer`: terminalizer
- `terraform`:  tool for building, changing, and versioning infrastructure
 This package contains a tool for building, changing, and versioning
 infrastructure safely and efficiently. Terraform can manage existing and
 popular service providers as well as custom in-house solutions.
 .
 Terraform enables you to safely and predictably create, change, and improve
 infrastructure. It is an open source tool that codifies APIs into declarative
 configuration files that can be shared amongst team members, treated as code,
 edited, reviewed, and versioned.
 .
 The key features of Terraform are:
  * Infrastructure as Code: Infrastructure is described using a high-
    level configuration syntax. This allows a blueprint of your datacenter
    to be versioned and treated as you would any other code. Additionally,
    infrastructure can be shared and re-used.
  * Execution Plans: Terraform has a "planning" step where it
    generates an execution plan. The execution plan shows what Terraform
    will do when you call apply. This lets you avoid any surprises when
    Terraform manipulates infrastructure.
  * Resource Graph: Terraform builds a graph of all your resources,
    and parallelizes the creation and modification of any non-dependent
    resources. Because of this, Terraform builds infrastructure as
    efficiently as possible, and operators get insight into dependencies in
    their infrastructure.
  * Change Automation: Complex changesets can be applied to your
    infrastructure with minimal human interaction. With the previously
    mentioned execution plan and resource graph, you know exactly what
    Terraform will change and in what order, avoiding many possible human
    errors.


- `tesseract`: tesseract
- `thunar`:  File Manager for Xfce
 Thunar is the file manager designed to be the default file manager for the
 Xfce desktop environment. It has been designed to be fast and easy to use.
 .
 Also included is an Xfce panel plugin which can manage the desktop trash.


- `tig`:  ncurses-based text-mode interface for Git
 This package contains a text-mode interface for the version control system
 Git. It may be used to browse the history and contents of a repository.
 .
 The following main features are supported:
  - View revision logs, commit messages, diffstats, diffs, archive trees and
    file contents.
  - Visualize revision graphs.
  - Stage / unstage changes and add untracked files.
  - Merge files.
  - Cherry-pick commits.
 .
 tig may also be used as a pager. It reads input from stdin and colorizes it.


- `timew`: timew
- `tldr`:  transitional package
 This is a transitional package. It can safely be removed.


- `tldrl`: tldrl
- `timeout`: run a command with a time limit
- `timedatectl`: Control the system time and date
- `tokei`:  display statistics about your code
 Tokei will show the number of files, total lines within those files
 and code, comments, and blanks grouped by language.
 .
  - Very fast, able to count millions of code in seconds.
  - Accurate, correctly handles multi-line comments, nested comments
 and not counting comments that are in strings.
  - Handles a huge range of over 150 languages and their various
 extensions.
  - Can output in multiple formats (CBOR, JSON, YAML).
  - Cross-platform.
  - Is also a library that's easy to integrate.
  - Comes with and without color, with support for NO_COLOR.


- `tomb`:  crypto undertaker
 Tomb is a free and easy to operate desktop application for fairly strong
 encryption of personal files. A tomb is like a locked folder that can be
 transported and hidden in filesystems; its keys are password protected and can
 be kept separate, for instance keeping the tomb file in your computer's
 harddisk and the key file on a USB stick.
 .
 Tomb relies on dm-crypt (and cryptsetup) as an encryption backend using the
 aes-xts-plain64 cypher.


- `tox`:  virtualenv-based automation of test activities
 Tox as is a generic virtualenv management and test command line tool
 you can use for:
 .
  * checking your package installs correctly with different Python
    versions and interpreters
  * running your tests in each of the environments, configuring your
    test tool of choice
  * acting as a frontend to Continuous Integration servers, greatly
    reducing boilerplate and merging CI and shell-based testing.


- `tpp`: tpp
- `traefik`: traefik
- `trans`: trans
- `transcode`: transcode
- `transmission-cli`:  lightweight BitTorrent client (command line programs)
 Transmission is a set of lightweight BitTorrent clients (in GUI, CLI
 and daemon form). All its incarnations feature a very simple, intuitive
 interface on top on an efficient, cross-platform back-end.
 .
 This package contains transmission-remote to interface with
 transmission-daemon, tools to create/edit/inspect torrent files
 and a deprecated stand-alone command-line client.


- `transmission-remote`: transmission-remote
- `tr`: translate characters
- `trash-cli`:  command line trashcan utility
 This package provides a command line interface trashcan utility
 compliant with the FreeDesktop.org Trash Specification. It remembers
 the name, original path, deletion date, and permissions of each trashed
 file


- `trash`: trash
- `trawl`: trawl
- `trizen`: trizen
- `tsc`: tsc
- `kbdinfo`: read information about keyboard state
- `tslint`: tslint
- `lp`: line printer devices
- `ufraw-batch`: ufraw-batch
- `udisksctl`: The udisks command line tool
- `ul`: do underlining
- `pwck`: verify integrity of password files
- `unar`:  Unarchiver for a variety of file formats
 The Unarchiver is an archive unpacker program with support for the popular
 zip, RAR, 7z, tar, gzip, bzip2, LZMA, XZ, CAB, MSI, NSIS, EXE, ISO, BIN, and
 split file formats, as well as the old Stuffit, Stuffit X, DiskDouble, Compact
 Pro, Packit, cpio, compress (.Z), ARJ, ARC, PAK, ACE, ZOO, LZH, ADF, DMS, LZX,
 PowerPacker, LBR, Squeeze, Crunch, and other old formats.
 .
 This package contains the lsar tool which lists the contents of archives and
 the unar tool which extracts those contents.


- `tfmtodit`: create font files for use with groff  -Tdvi
- `unexpand`: convert spaces to tabs
- `uniq`: report or filter out repeated lines in a file
- `uprecords`: uprecords
- `unzipsfx`: self-extracting stub for prepending to ZIP archives
- `update-mime-database`: a program to build the Shared MIME-Info database cache
- `vagrant`:  Tool for building and distributing virtualized development environments
 This package provides the tools to create and configure lightweight,
 reproducible, and portable virtual environments.
 .
 Vagrant upstream uses Oracle’s VirtualBox by default to create its virtual
 machines. On Debian, Vagrant will use libvirt/KVM by default as VirtualBox is
 not part of Debian main, but will use VirtualBox if it's installed.


- `valgrind`:  instrumentation framework for building dynamic analysis tools
 Valgrind is a system for debugging and profiling Linux programs. With its tool
 suite you can automatically detect many memory management and threading bugs,
 avoiding hours of frustrating bug-hunting and making your programs more stable.
 You can also perform detailed profiling to help speed up your programs and use
 Valgrind to build new tools.
 .
 The Valgrind distribution currently includes six production-quality tools:
  * a memory error detector (Memcheck)
  * two thread error detectors (Helgrind and DRD)
  * a cache and branch-prediction profiler (Cachegrind)
  * a call-graph generating cache and branch-prediction profiler (Callgrind)
  * a heap profiler (Massif)
 It also includes three experimental tools:
  * a stack/global array overrun detector (SGCheck)
  * a second heap profiler that examines how heap blocks are used (DHAT)
  * a SimPoint basic block vector generator (BBV)


- `vault`: vault
- `vboxmanage`: vboxmanage
- `vcsh`:  Version Control System for $HOME - multiple Git repositories in $HOME
 vcsh allows you to have several git repositories, all maintaining their working
 trees in $HOME without clobbering each other. That, in turn, means you can have
 one repository per config set (zsh, vim, ssh, etc), picking and choosing which
 configs you want to use on which machine.


- `vegeta`: vegeta
- `velero`: velero
- `users`: print the user names of users currently logged in to the current host
- `viewnior`:  simple, fast and elegant image viewer
 This is Viewnior, an image viewer program. Created to be simple, fast
 and elegant. Its minimalistic interface provides more screenspace for
 your images. Among its features are:
 .
  * Fullscreen & Slideshow
  * Rotate, flip, crop, save, delete images
  * Animation support
  * Browse only selected images
  * Navigation window
  * Set image as wallpaper (under GNOME, Fluxbox and LXDE)
  * Simple interface
  * Configurable mouse actions


- `virtualenv`:  Python virtual environment creator (Dependency package)
 The virtualenv utility creates virtual Python instances, each invokable with
 its own Python executable.  Each instance can have different sets of modules,
 installable via pip.  Virtual Python instances can also be created without
 root access.
 .
 This is a dependency package and may be safely removed.


- `vmware-checkvm`: vmware-checkvm
- `vgscan`: Search for all volume groups
- `vipw`: edit the password or group file
- `vsce`: vsce
- `vue-build`: vue-build
- `vue-init`: vue-init
- `vue-serve`: vue-serve
- `vue`: vue
- `vi`: screen-oriented (visual) display editor
- `waitress-serve`: waitress-serve
- `wasm-objdump`: wasm-objdump
- `wasm-opt`: wasm-opt
- `wasm2c`: wasm2c
- `wasm2wat`: wasm2wat
- `wat2wasm`: wat2wasm
- `weasyprint`:  Document factory for creating PDF files from HTML
 WeasyPrint is a smart solution helping web developers to create PDF
 documents. It turns simple HTML pages into gorgeous statistical reports,
 invoices, tickets, etc.
 .
 From a technical point of view, WeasyPrint is a visual rendering engine for
 HTML and CSS that can export to PDF and PNG. It aims to support web standards
 for printing. WeasyPrint is free software made available under a BSD license.
 .
 It is based on various libraries but *not* on a full rendering engine like
 WebKit or Gecko. The CSS layout engine is written in Python, designed for
 pagination, and meant to be easy to hack on.


- `web-ext`: web-ext
- `webpack`:  Packs CommonJs/AMD modules for the browser
 Webpack takes code targeted at node.js and makes it run in the browser.
 Node.js comes with API of its own that is not available in the browsers.
 Webpack exposes this code to programs that are unaware they are running in a
 browser.
 .
 Node.js is an event-based server-side JavaScript engine.


- `webtorrent`: webtorrent
- `where`: where
- `while`: while
- `wordgrinder`:  simple word processor for writing first drafts
 This is a transitional dummy package. It can safely be removed.


- `wipefs`: wipe a signature from a device
- `wrk`:  HTTP benchmarking tool
 wrk is a modern HTTP benchmarking tool capable of generating significant
 load when run on a single multi-core CPU. It combines a multithreaded
 design with scalable event notification systems such as epoll and kqueue.
 .
 An optional LuaJIT script can perform HTTP request generation, response
 processing, and custom reporting.


- `wuzz`:  Interactive console tool for HTTP inspection
 Wuzz is an interactive tool for generating and sending HTTP requests,
 as well as viewing the responses. Instead of having to specify the HTTP
 headers, parameters, body etc. on the command-line, a simple and intuitive
 CUI (console user interface) can be used. Wuzz's command line arguments are
 similar to cURL's, so it can be used to inspect and modify requests copied
 from a browser's network inspector with the "copy as cURL" feature.


- `x11vnc`:  VNC server to allow remote access to an existing X session
 x11vnc allows one to view remotely and interact with real X displays (i.e. a
 display corresponding to a physical monitor, keyboard, and mouse) with any
 VNC viewer. It has built-in SSL encryption and authentication, UNIX account
 and password support, server-side scaling, single port HTTPS and VNC, mDNS
 service advertising, and TightVNC and UltraVNC file-transfer.


- `x_x`: x_x
- `xar`: xar
- `xbps`: xbps
- `xclip`:  command line interface to X selections
 xclip is a command line utility that is designed to run on any system with an
 X11 implementation. It provides an interface to X selections ("the clipboard")
 from the command line. It can read data from standard in or a file and place
 it in an X selection for pasting into other X applications. xclip can also
 print an X selection to standard out, which can then be redirected to a file
 or another program.


- `xcv`: xcv
- `xfce4-screenshooter`:  screenshots utility for Xfce
 Screenshooter is an utility for the Xfce Desktop Environment. It can take
 desktop, rectangles or selected window screenshots, and you can bind it to
 your "Print Screen" key. A panel plugin is provided too.


- `xfce4-terminal`:  Xfce terminal emulator
 This package contains Terminal, which is a lightweight and easy to use
 terminal emulator for X11. It was created to fit nicely into the Xfce
 desktop environment, but it also fits nice with other environments.


- `xman`: Manual page display program for the X Window System
- `xo`: xo
- `xsel`:  command-line tool to access X clipboard and selection buffers
 XSel is a command-line program for getting and setting the contents of
 the X selection.  It can also append and have it follow a growing file
 (similar to tail -f).


- `xsv`: xsv
- `xtrlock`:  Minimal X display lock program
 xtrlock is a very minimal X display lock program, which uses nothing
 except the Xlib library. It doesn't obscure the screen, it is
 completely idle while the display is locked and you don't type at it,
 and it doesn't do funny things to the X access control lists.


- `xwud`: image displayer for X
- `yank`:  interactively select and yank terminal output to stdout or xsel
 Read input from stdin and draw a selection interface where all fields
 in the given input are recognized by using a default or user-supplied
 set of delimiters.
 .
 Using ctrl-n and ctrl-p will move the field selection forward and
 backward, pressing the return key will invoke the yank command and
 write the selected field to its stdin. The yank command defaults to
 xsel, but could be anything that accepts input on stdin.


- `yarn-why`: Show information about why a package is installed
- `yarn`: Yarn is a package manager that doubles down as project manager
- `yay`: Yet another yogurt. Pacman wrapper and AUR helper written in go
- `yesod`:  Helper executables for the Haskell web framework Yesod
 Provides scaffolding, devel server, and some simple code generation helpers
 (yesod, yesod-ar-wrapper, yesod-ld-wrapper, yesod-ghc-wrapper).


- `youtube-dl`: Command-line program to download videos from YouTube.com and other video sites
- `z`: z
- `luac`: Lua compiler
- `zdb`: display zpool debugging and consistency information
- `zfs`: combines a file system with a volume manager
- `zbarimg`: scan and decode bar codes from image file(s)
- `zopflipng`: PNG optimizer using zopfli deflate packer
- `zpool`: ZFS filesystems are built on top of virtual storage pools
- `wpa_background`: Background information on Wi-Fi Protected Access and IEEE 802.11i
- `zipsplit`: split a zipfile into smaller zipfiles
- `zramctl`: set up and control zram devices
- `nf-core`: nf-core
- `xbacklight`:  simple utility to set the backlight level
 xbacklight is a simple command-line utility to set the backlight level
 using the RandR 1.2 Backlight output property.


- `tcptraceroute`:  traceroute implementation using TCP packets
 The more traditional traceroute(8) sends out either UDP or ICMP ECHO packets
 with a TTL of one, and increments the TTL until the destination has been
 reached. By printing the gateways that generate ICMP time exceeded messages
 along the way, it is able to determine the path packets are taking to reach the
 destination.
 .
 The problem is that with the widespread use of firewalls on the modern
 Internet, many of the packets that traceroute(8) sends out end up being
 filtered, making it impossible to completely trace the path to the destination.
 However, in many cases, these firewalls will permit inbound TCP packets to
 specific ports that hosts sitting behind the firewall are listening for
 connections on. By sending out TCP SYN packets instead of UDP or ICMP ECHO
 packets, tcptraceroute is able to bypass the most common firewall filters.


- `http_load`: A HTTP benchmarking tool.
- `mullvad`: CLI client for Mullvad VPN.
- `dunstify`: A notification tool that is an extension of notify-send, but has more features based around dunst.
- `dmenu`: Dynamic menu.
- `efibootbgr`: Manipulate the UEFI Boot Manager (the Bootoptions).
- `ceph`:  distributed storage and file system
 Ceph is a massively scalable, open-source, distributed
 storage system that runs on commodity hardware and delivers object,
 block and file system storage.


- `stress`:  tool to impose load on and stress test a computer system
 'stress' is a tool that imposes a configurable amount of CPU, memory, I/O,
 or disk stress on a POSIX-compliant operating system and reports any errors
 it detects.
 .
 'stress' is not a benchmark.  It is a tool used by system administrators to
 evaluate how well their systems will scale, by kernel programmers to evaluate
 perceived performance characteristics, and by systems programmers to expose
 the classes of bugs which only or more frequently manifest themselves when
 the system is under heavy load.


- `mkfs.ext4`: Creates an ext4 filesystem inside a partition.
- `dstat`: Versatile tool for generating system resource statistics.
- `photorec`: Deleted file recovery tool.
- `vrms`:  transitional package for check-dfsg-status
 This is a transitional package to install the check-dfsg-status package and
 which can be safely removed.


- `a2dissite`: Disable an Apache virtual host on Debian-based OSes.
- `openrc`:  dependency based service manager (runlevel change mechanism)
 OpenRC is a dependency based service manager. It provides support for System V
 init, for booting, changing runlevels, starting and stopping services, and
 shutting down.
 .
 Originally written as a Gentoo project, OpenRC aims at being
 platform-agnostic.  It works equally well on Linux, BSD and Hurd.
 It supports the traditional init system in Debian in addition to many
 alternatives.  OpenRC is implemented in C in a small, simple and
 efficient way, making it easy to understand, extend and reuse.
 .
 This package provides the runlevel change mechanism.


- `nmcli-connection`: Connection management with NetworkManager.
- `timeshift`:  System restore utility
 Timeshift is a system restore utility which takes snapshots
 of the system at regular intervals. These snapshots can be restored
 at a later date to undo system changes. Creates incremental snapshots
 using rsync or BTRFS snapshots using BTRFS tools.


- `acpi`:  displays information on ACPI devices
 Attempts to replicate the functionality of the 'old' apm command on
 ACPI systems, including battery and thermal information. Does not support
 ACPI suspending, only displays information about ACPI devices.


- `sa`: Summarizes accounting information. Part of the acct package.
- `toilet`:  display large colourful characters in text mode
 TOIlet prints text using large characters made of smaller characters.
 It is similar in many ways to FIGlet with additional features such as
 Unicode handling, colour fonts, filters and various export formats.
 .
 TOIlet can open FIGlet fonts and is mostly commandline-compatible with it.


- `mac2unix`: Change macOS-style line endings to Unix-style.
- `progress`:  Coreutils Progress Viewer (formerly known as 'cv')
 This tool can be described as a Tiny, Dirty, Linux-and-OSX-Only
 C command that looks for coreutils basic commands (cp, mv, dd, tar,
 gzip/gunzip, cat, etc.) currently running on your system and
 displays the percentage of copied data. It can also show estimated
 time and throughput, and provide a "top-like" mode (monitoring).
 .
 It simply scans `/proc` for interesting commands, and then looks at
 directories `fd` and `fdinfo` to find opened files and seek positions,
 and reports status for the largest file.
 .
 It's very light, and compatible with virtually any command.
 This program was formerly known as 'cv' on github.


- `betterlockscreen`:  Fast lockscreen with customization
 Betterlockscreen allows you to cache images with different
 filters and lockscreen with blazing speed.


- `hlint`:  Haskell source code suggestions
 HLint gives suggestions on how to improve your source code. It can either
 print them directly, or generate a colored HTML output.


- `a2ensite`: Enable an Apache virtual host on Debian-based OSes.
- `xvfb-run`: Run a command in a virtual X server environment.
- `numlockx`:  enable NumLock in X11 sessions
 Utilities to enable the keyboard's Numeric Lock during X11
 session initialization or using command line utility.
 .
 The package automatically installs session script to enable numlock
 on session start.


- `unix2mac`: Change Unix-style line endings to macOS-style.
- `debchange`: Tool for maintenance of the debian/changelog file in a Debian source package.
- `unshadow`: Utility provided by the John the Ripper project to obtain the traditional Unix password file if the system uses shadow passwords.
- `rc-status`: Show status info about runlevels.
- `urxvt`: Rxvt-unicode.
- `nmcli-device`: Hardware device management with NetworkManager.
- `dget`: Download Debian packages.
- `btrfs`: A filesystem based on the copy-on-write (COW) principle for Linux.
- `mons`: A tool to quickly manage two displays.
- `powertop`:  diagnose issues with power consumption and management
 PowerTOP is a Linux tool to diagnose issues with power consumption and
 power management. In addition to being a diagnostic tool, PowerTOP also
 has an interactive mode you can use to experiment with various power
 management settings, for cases where the Linux distribution has not
 enabled those settings.
 .
 PowerTOP reports which components in the system are most likely to blame
 for higher-than-needed power consumption, ranging from software
 applications to active components in the system. Detailed screens are
 available for CPU C and P states, device activity, and software activity.


- `a2query`: Retrieve runtime configuration from Apache on Debian-based OSes.
- `a2enconf`: Enable an Apache configuration file on Debian-based OSes.
- `debman`: Read man pages from uninstalled packages.
- `unix2dos`: Change Unix-style line endings to DOS-style.
- `phpenmod`: Enable PHP extensions on Debian-based OSes.
- `expect`:  Automates interactive applications
 Expect is a tool for automating interactive applications according to a script.
 Following the script, Expect knows what can be expected from a program and what
 the correct response should be. Expect is also useful for testing these same
 applications. And by adding Tk, you can also wrap interactive applications in
 X11 GUIs. An interpreted language provides branching and high-level control
 structures to direct the dialogue. In addition, the user can take control and
 interact directly when desired, afterward returning control to the script.
 .
 This package contains the expect binary and several Expect based scripts.


- `dockerd`: A persistent process to start and manage docker containers.
- `logcat`: Dump a log of system messages.
- `ac`: Print statistics on how long users have been connected.
- `apport-bug`: File a bug report on Ubuntu.
- `uvcdynctrl`:  Command line tool to control v4l2 devices
 This package provides the tools needed to add vendor specific
 controls to uvc devices.
 .
 uvcdynctrl is part of the Webcam Library.
 .
 The Webcam Library libwebcam is designed to simplify
 the development of webcam applications, primarily on Linux but
 with an option to be ported to other platforms, in particular
 Solaris. It realizes part of what the unwritten Video4Linux user
 space library was always supposed to be: an easy to use library
 that shields its users from many of the difficulties and problems
 of using the V4L2 API directly.


- `phpquery`: PHP extension manager for Debian-based OSes.
- `wmctrl`:  control an EWMH/NetWM compatible X Window Manager
 Wmctrl is a command line tool to interact with an
 EWMH/NetWM compatible X Window Manager (examples include
 Enlightenment, icewm, kwin, metacity, and sawfish).
 .
 Wmctrl provides command line access to almost all the features
 defined in the EWMH specification. For example it can maximize
 windows, make them sticky, set them to be always on top. It can
 switch and resize desktops and perform many other useful
 operations.


- `runuser`: Run commands as a specific user and group without asking for password (needs root privileges).
- `check-support-status`: Identify installed Debian packages for which support has had to be limited or prematurely ended.
- `enum4linux`:  Enumerates info from Windows and Samba systems
 Enum4linux is a tool for enumerating information from Windows and Samba
 systems. It attempts to offer similar functionality to enum.exe formerly
 available from www.bindview.com.
 .
 It is written in PERL and is basically a wrapper around the Samba tools
 smbclient, rpclient, net and nmblookup. The samba package is therefore a
 dependency.
 .
 Features include:
 .
     RID Cycling (When RestrictAnonymous is set to 1 on Windows 2000)
     User Listing (When RestrictAnonymous is set to 0 on Windows 2000)
     Listing of Group Membership Information
     Share Enumeration
     Detecting if host is in a Workgroup or a Domain
     Identifying the remote Operating System
     Password Policy Retrieval (using polenum)


- `postfix`:  High-performance mail transport agent
 Postfix is Wietse Venema's mail transport agent that started life as an
 alternative to the widely-used Sendmail program.  Postfix attempts to
 be fast, easy to administer, and secure, while at the same time being
 sendmail compatible enough to not upset existing users.  Thus, the outside
 has a sendmail-ish flavor, but the inside is completely different.


- `ddrescue`:  data recovery and protection tool
 When your disk has crashed and you try to copy it over to another one,
 standard Unix tools like cp, cat, and dd will abort on every I/O error,
 dd_rescue does not.
 It optimizes copying by using large blocks as long as no errors occur
 and falls back to smaller blocks. It supports reverse direction copying
 (to approach a bad spot from the top), sparse copying, preallocating
 space, splice zerocopy, and bypassing the kernel pagecache with O_DIRECT.
 dd_rescue provides safe deletion of data by overwriting files (or better
 partitions/disks) multiple times with fast random numbers.
 With the ddr_hash plugin, it supports calculating a hash value (such as
 a sha256sum) or an HMAC during copying.


- `phpdismod`: Disable PHP extensions on Debian-based OSes.
- `lastcomm`: Show last commands executed.
- `reportbug`:  reports bugs in the Debian distribution
 reportbug is a tool designed to make the reporting of bugs in Debian
 and derived distributions relatively painless.  Its features include:
 .
  * Integration with many mail user agents.
  * Access to outstanding bug reports to make it easier to identify
    whether problems have already been reported.
  * Automatic checking for newer versions of packages.
  * Optional automatic verification of integrity of packages via debsums.
  * Support for following-up on outstanding reports.
  * Optional PGP/GnuPG integration.
 .
 Bug reporting in Debian relies on email; reportbug can use a local
 mail transport agent (like exim or sendmail), submit directly through
 an external mail server, or pass messages to an installed mail user
 agent (e.g., mutt) for submission.
 .
 This package also includes the "querybts" script for browsing the
 Debian bug tracking system.


- `debuild`: Tool to build a Debian package from source.
- `bluetoothctl`: Handling bluetooth devices from the shell.
- `blkdiscard`: Discards device sectors on storage devices. Useful for SSDs.
- `homeshick`: Synchronize Git dotfiles.
- `rc-service`: Locate and run OpenRC services with arguments.
- `extrace`:  trace exec() calls system-wide
 extrace traces all program executions happening on a system,
 or the subset of program executions done by a given process and its
 descendants.  For example, to see what the shell really executes:
 .
 $ sudo extrace -p $(pidof zsh)
 8505 git rev-parse --is-inside-work-tree
 8506 direnv export zsh
 8511 git rev-parse --is-inside-work-tree
     8515 wc -l
   8516 whoami
 8542 hostname
 8543 git rev-parse --is-inside-work-tree
 8544 direnv export zsh
   8549 /bin/bash --noprofile --norc -c 'eval "$("/usr/bin/direnv" stdlib)" >&2\
          && source_env ".envrc" >&2 && "/usr/bin/direnv" dump'
       8551 /usr/bin/direnv stdlib
       8558 /usr/bin/direnv watch .envrc
       8565 dirname .envrc
       8567 basename .envrc
       8569 basename .envrc
   8549 /usr/bin/direnv dump
 8574 git rev-parse --is-inside-work-tree
     8578 wc -l
   8579 whoami


- `a2disconf`: Disable an Apache configuration file on Debian-based OSes.
- `particle`: A command-line tool for interacting with Particle devices.
- `go-version`: Print Go version.
- `dexdump`:  Displays information about Android DEX files
 The `dexdump` tool is intended to mimic `objdump`. When possible, use
 similar command-line arguments.
 .
 This is a re-implementation of the original `dexdump` utility that was
 based on Dalvik functions in `libdex` into a new `dexdump` that is now
 based on ART functions in `libart` instead. The output is very similar
 to the original for correct DEX files. Error messages may differ,
 however. Also, ODEX files are no longer supported.


- `zoxide`:  Smarter cd command for your terminal
 This package contains the following binaries built from the Rust crate
 "zoxide":
  - zoxide


- `goreload`: Live reload utility for Go programs.
- `sops`: SOPS: Secrets OPerationS.
- `eva`: Simple calculator REPL, similar to `bc`, with syntax highlighting and persistent history.
- `django-admin`: Django’s utility for administrative tasks.
- `spfquery`:  query SPF (Sender Policy Framework) to validate mail senders
 The Sender Policy Framework (SPF) is one part of the SPF/SRS protocol
 pair. SPF allows email systems such as Sendmail, Postfix, Exim,
 Zmailer and MS Exchange to check SPF records and make sure that the
 email is authorized by the domain name that it is coming from. This
 prevents email forgery, commonly used by spammers, scammers and email
 viruses/worms.
 .
 This package contains simple utilities that use libspf2 to test and
 query SPF records.


- `zola`: A static site generator in a single binary with everything built-in.
- `k8sec`: Command line interface tool to manage Kubernetes secrets.
- `f3fix`: Edit the partition table of a fake flash drive.
- `lzop`:  fast compression program
 lzop is a compressor similar to gzip.  Its main advantages over gzip are
 much higher compression and decompression speed.  lzop was designed with
 the following goals in mind:
  1) reliability
  2) speed (both compression and decompression)
  3) reasonable drop-in compatibility with gzip
  4) portability


- `obs`: Open Broadcaster Software.
- `netlify`: Deploy sites and configure continuous deployment to the Netlify platform.
- `ansible-vault`: Encrypts & decrypts values, data structures and files within Ansible projects.
- `googler`:  Power tool to Google (Web & News) and Google Site Search from the terminal
 Features:
 .
  - Google Search, Google Site Search, Google News
  - Fast and clean (no ads, stray URLs or clutter), customisable color
  - Open result URLs (or the actual search) in browser
  - Navigate search result pages from omniprompt
  - Fetch n results in a go, start at the nth result
  - Disable automatic spelling correction and search exact keywords
  - Limit search by duration, country/domain specific search (default: .com),
    language preference
  - Supports Google search keywords like 'filetype:mime', 'site:somesite.com'
    etc.
  - Optionally open the first result directly in browser
    (as in "I'm Feeling Lucky")
  - Non-stop searches: fire new searches at omniprompt without exiting
  - Proxy support
  - Man page with examples, shell completion scripts for Bash, Zsh and Fish


- `magick`: Create, edit, compose, or convert bitmap images.
- `zsteg`: Steganography detection tool for PNG and BMP file formats.
- `wapm`: The WebAssembly package manager.
- `iotop`:  simple top-like I/O monitor
 iotop does for I/O usage what top(1) does for CPU usage. It watches I/O
 usage information output by the Linux kernel and displays a table of
 current I/O usage by processes on the system. It is handy for answering
 the question "Why is the disk churning so much?".
 .
 iotop can only run under a Linux 2.6.20 or later kernel built with the
 CONFIG_TASKSTATS, CONFIG_TASK_DELAY_ACCT, CONFIG_TASK_IO_ACCOUNTING and
 CONFIG_VM_EVENT_COUNTERS build config options on.


- `powerstat`:  laptop power measuring tool
 Powerstat measures the power consumption of a mobile PC that has
 a battery power source.  The output is like vmstat but also shows
 power consumption statistics.  At the end of a run, powerstat
 will calculate the average, standard deviation and min/max of
 the gathered data.


- `guacd`: Apache Guacamole proxy daemon.
- `transcrypt`: Transparently encrypt files within a git repository.
- `go-generate`: Generate Go files by running commands within source files.
- `ipython`: A Python shell with automatic history, dynamic object introspection, easier configuration, command completion, access to the system shell and more.
- `chars`: Display names and codes for various ASCII and Unicode characters and code points.
- `uncrustify`:  C, C++, ObjectiveC, C#, D, Java, Pawn and VALA source code beautifier
 Uncrustify is a highly configurable source code formatter. It aligns
 preprocessor define's, assignments, arithmetics and is able to fix spacing
 between operators.


- `cotton`: Markdown test specification runner.
- `csvsql`: Generate SQL statements for a CSV file or execute those statements directly on a database.
- `qr`: Generate QR codes in the terminal with ANSI VT-100 escape codes.
- `pageres`: Capture screenshots of websites in various resolutions.
- `goimports`: Updates Go import lines, adding missing ones and removing unreferenced ones.
- `watchexec`: Run arbitrary commands when files change.
- `gotty`: Share your terminal as a web application.
- `compare`: View the difference between 2 images.
- `grumphp`: A PHP Composer plugin that enables source code quality checks.
- `fls`: List files and directories in an image file or device.
- `radare2`:  free and advanced command line hexadecimal editor
 The project aims to create a complete, portable, multi-architecture,
 unix-like toolchain for reverse engineering.
 .
 It is composed by an hexadecimal editor (radare) with a wrapped IO
 layer supporting multiple backends for local/remote files, debugger
 (OS X, BSD, Linux, W32), stream analyzer, assembler/disassembler (rasm)
 for x86, ARM, PPC, m68k, Java, MSIL, SPARC, code analysis modules and
 scripting facilities. A bindiffer named radiff, base converter (rax),
 shellcode development helper (rasc), a binary information extractor
 supporting PE, mach0, ELF, class, etc. named rabin, and a block-based
 hash utility called rahash.


- `swig`:  Generate scripting interfaces to C/C++ code
 SWIG is a compiler that makes it easy to integrate C and C++ code
 with these languages: C#, D, Go, Guile, Java, JavaScript, Lua,
 Mzscheme, OCaml, Octave, Perl, PHP, Python, R, Ruby, Scilab, and Tcl.
 .
 Swig takes a set of ANSI C/C++ declarations and generates an
 interface for them to your favorite scripting language.


- `reflac`: Recompress FLAC files in-place while preserving metadata.
- `go-env`: Manage environment variables used by the Go toolchain.
- `nvidia-smi`:  NVIDIA System Management Interface
 The NVIDIA Management Library (NVML) provides a monitoring and management API.
 The application "nvidia-smi" is the NVIDIA System Management Interface (NVSMI)
 and provides a command line interface to this functionality.
 .
 See the output from the --help command line option for supported models and
 further information.


- `sdkmanager`:  Package manager for Android SDK packages
 A drop-in replacement for sdkmanager from the Android SDK written in
 Python.  It implements the exact API of the sdkmanager
 (https://developer.android.com/studio/command-line/sdkmanager)
 command line.  It only deviates from that API if it can be done while
 being 100% compatible.
 .
 The project also attempts to maintain the same terminal output so it
 can be compatible with things that scrape sdkmanager output.


- `ogr2ogr`: Convert Simple Features data between file formats.
- `nkf`:  Network Kanji code conversion Filter
 Nkf is yet another kanji code converter among networks,
 hosts and terminals. It converts input kanji code to designated
 kanji code such as 7-bit JIS, MS-kanji (Shifted-JIS) or EUC.


- `virtualenvwrapper`:  extension to virtualenv for managing multiple environments
 virtualenvwrapper is a set of extensions to Ian Bicking's virtualenv
 tool. The extensions include wrappers for creating and deleting
 virtual environments and otherwise managing your development
 workflow, making it easier to work on more than one project at a time
 without introducing conflicts in their dependencies.


- `git-ignore`: Generate .gitignore files from predefined templates.
- `oc`: The OpenShift Container Platform CLI.
- `croc`: Send and receive files easily and securely over any network.
- `fin`: Docksal command line utility.
- `cryfs`:  encrypt your files and store them in the cloud
 CryFS encrypts your files, so you can safely store them anywhere. It works
 well together with cloud services like Dropbox, iCloud, OneDrive and others.


- `qrencode`:  QR Code encoder into PNG image
 Qrencode is a utility software using libqrencode to encode string data in
 a QR Code and save as a PNG or an EPS image.


- `git-flow`:  Git extension to provide a high-level branching model
 A set of scripts that provide high-level repository operations for
 managing feature/release/hotfix branches in a Git repository,
 particularly suited to be utilised to follow Vincent Driessen's
 branching model, described at
 <https://nvie.com/posts/a-successful-git-branching-model/>.
 .
 This package follows the AVH edition.


- `jwt`:  golang implementation of JSON Web Tokens (command line)
 Community maintained clone of github.com/dgrijalva/jwt-go.
 .
 After the original author of the library suggested migrating the
 maintenance of jwt-go, a dedicated team of open source maintainers
 decided to clone the existing library into this module.
 .
 The command line utility included in this project (cmd/jwt) provides
 a straightforward example of token creation and parsing as well as a
 useful tool for debugging your own integration. You'll also find several
 implementation examples in the documentation.
 .
 This package provides the command line.


- `sbt`: Build tool for Scala and Java projects.
- `ctags`: Generates an index (or tag) file of language objects found in source files for many popular programming languages.
- `cheat`: Create and view interactive cheat sheets on the command-line.
- `cpdf`: CLI to manipulate existing PDF files in a variety of ways.
- `k8s-unused-secret-detector`: Command line interface tool for detecting unused Kubernetes secrets.
- `evil-winrm`:  ultimate WinRM shell for hacking/pentesting
 This package contains the ultimate WinRM shell for hacking/pentesting.
 .
 WinRM (Windows Remote Management) is the Microsoft implementation of
 WS-Management Protocol. A standard SOAP based protocol that allows hardware
 and operating systems from different vendors to interoperate. Microsoft
 included it in their Operating Systems in order to make life easier to system
 administrators.
 .
 This program can be used on any Microsoft Windows Servers with this feature
 enabled (usually at port 5985), of course only if you have credentials and
 permissions to use it. So it could be used in a post-exploitation
 hacking/pentesting phase. The purpose of this program is to provide nice and
 easy-to-use features for hacking. It can be used with legitimate purposes by
 system administrators as well but the most of its features are focused on
 hacking/pentesting stuff.
 .
 It is using PSRP (Powershell Remoting Protocol) for initializing runspace
 pools as well as creating and processing pipelines.


- `hexyl`:  Command-line hex viewer with colored output
 hexyl is a simple hex viewer for the terminal. It uses colored output to
 distinguish different categories of bytes (NULL bytes, printable ASCII
 characters, ASCII whitespace characters, other ASCII characters and non-ASCII).
 .
 This package contains the following binaries built from the Rust crate
 "hexyl":
  - hexyl


- `jc`:  JSON CLI output utility
 jc JSONifies the output of many CLI tools and file-types for easier parsing
 in scripts. This allows further command-line processing of output by piping
 commands.


- `html5validator`: A command line tool for testing HTML5 validity.
- `hping`: Command-line oriented TCP/IP packet assembler and analyzer.
- `sequelize`: Promise-based Node.js ORM for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server.
- `multitail`:  view multiple logfiles windowed on console
 multitail lets you view one or multiple files like the original tail
 program.
 .
 The difference is that this program creates multiple windows on
 your console (with ncurses). It can also use colors while displaying the
 logfiles for faster recognizing which lines are important and which are
 not.
 .
 It is optimized for terminal-sessions through slow links.


- `deno`: A secure runtime for JavaScript and TypeScript.
- `rtmpdump`:  small dumper for media content streamed over the RTMP protocol
 A small dumper for media content streamed over the RTMP protocol (like BBC's
 iPlayer high quality streams). Supplying an RTMP URL will result in a dumped
 flv file, which can be played/transcoded with standard tools.


- `robo`: PHP task runner.
- `ogrinfo`: List information about an OGR-supported data source.
- `stripe`: Interact with a Stripe account.
- `mmls`: Display the partition layout of a volume system.
- `go-bug`: Report a bug.
- `wormhole`: Get things from one computer to another, safely.
- `apktool`:  tool for reverse engineering Android apk files
 A tool for reverse engineering 3rd party, closed, binary Android apps. It can
 decode resources to nearly original form and rebuild them after making some
 modifications; it makes possible to debug smali code step by step. Also it
 makes working with an app easier because of project-like file structure and
 automation of some repetitive tasks like building apk.


- `identify`: Command line utility of Image Magick project to describe the format and characteristics of one or more image files.
- `ghost`: A blogging platform and headless CMS.
- `alacritty`:  Fast, cross-platform, OpenGL terminal emulator
 Alacritty is a modern terminal emulator that comes with sensible defaults, but
 allows for extensive configuration. By integrating with other applications,
 rather than reimplementing their functionality, it manages to provide a
 flexible set of features with high performance.


- `arc`:  archive utility based on the MS-DOS ARC program
 This program is based on the MS-DOS ARC program, version 5.21, plus a few
 enhancements.
 .
 ARC also performs Huffman Squeezing on data. The Huffman Squeeze algorithm
 was removed from MS-DOS ARC after version 5.12. It turns out to be more
 efficient than Lempel-Ziv style compression when compressing graphic images.
 Squeeze analysis is always done now, and the best of packing, squeezing,
 or crunching is used.
 .
 Compresses and extracts Squashed files. "Squashing" was created by
 Phil Katz in his PKxxx series of ARC utility programs for MS-DOS.
 Dan Lanciani wrote the original modifications to ARC's Crunch code to
 handle Squashing. Klaus Reimer made minor changes since then, mostly to
 reduce the amount of memory required. The 'q' option flag must be
 specified to Squash files. The Squashing algorithm will be used instead
 of the usual Crunch algorithm, and will be compared against packing and
 squeezing, as before.
 .
 This package provides the arc and marc commands. MARC can be used to merge
 files compressed by ARC.


- `safe`: A CLI to interact with HashiCorp Vault.
- `dcfldd`:  enhanced version of dd for forensics and security
 dcfldd was initially developed at Department of Defense Computer Forensics
 Lab (DCFL). This tool is based on the dd program with the following additional
 features:
 .
  - Hashing on-the-fly: dcfldd can hash the input data as it is being
    transferred, helping to ensure data integrity.
  - Status output: dcfldd can update the user of its progress in terms of the
    amount of data transferred and how much longer operation will take.
  - Flexible disk wipes: dcfldd can be used to wipe disks quickly and with a
    known pattern if desired.
  - Image/wipe verify: dcfldd can verify that a target drive is a bit-for-bit
    match of the specified input file or pattern.
  - Multiple outputs: dcfldd can output to multiple files or disks at the same
    time.
  - Split output: dcfldd can split output to multiple files with more
    configurability than the split command.
  - Piped output and logs: dcfldd can send all its log data and output to
    commands as well as files natively.
  - When dd uses a default block size (bs, ibs, obs) of 512 bytes, dcfldd uses
    32768 bytes (32 KiB) which is HUGELY more efficient.
  - The following options are present in dcfldd but not in dd: ALGORITHMlog:,
    errlog, hash, hashconv, hashformat, hashlog, hashlog:, hashwindow, limit,
    of:, pattern, sizeprobe, split, splitformat, statusinterval, textpattern,
    totalhashformat, verifylog, verifylog:, vf.


- `docker-build`: Build an image from a Dockerfile.
- `balena`: Interact with the balenaCloud, openBalena and the balena API from the command line.
- `linkchecker`:  check websites and HTML documents for broken links
 Provides a command line program and web interface to check links
 of websites and HTML documents.
 Features:
  * recursive checking
  * multithreaded
  * output in colored or normal text, HTML, SQL, CSV, XML or a sitemap
    graph in different formats
  * HTTP/1.1, HTTPS, FTP, mailto:, news:, nntp:, Telnet and local file
    links support
  * restrict link checking with regular expression filters for URLs
  * proxy support
  * username/password authorization for HTTP, FTP and Telnet
  * robots.txt exclusion protocol support
  * Cookie support
  * i18n support
  * HTML and CSS syntax check
  * Antivirus check


- `go-list`: List packages or modules.
- `dirsearch`:  Web path scanner
 This package contains is a command-line tool designed to brute force
 directories and files in webservers.
 .
 As a feature-rich tool, dirsearch gives users the opportunity to perform a
 complex web content discovering, with many vectors for the wordlist, high
 accuracy, impressive performance, advanced connection/request settings, modern
 brute-force techniques and nice output.


- `pprof`: Command-line tool for visualization and analysis of profile data.
- `ocamlc`: The OCaml bytecode compiler.
- `go-mod`: Module maintenance.
- `qcp`: Copy files using the default text editor to define the filenames.
- `jupytext`: Tool to convert Jupyter notebooks to plain text documents, and back again.
- `ocaml`:  ML language implementation with a class-based object system
 Objective Caml (OCaml) is an implementation of the ML language, based on
 the Caml Light dialect extended with a complete class-based object system
 and a powerful module system in the style of Standard ML.
 .
 OCaml comprises two compilers. One generates bytecode
 which is then interpreted by a C program. This compiler runs quickly,
 generates compact code with moderate memory requirements, and is
 portable to essentially any 32 or 64 bit Unix platform. Performance of
 generated programs is quite good for a bytecoded implementation:
 almost twice as fast as Caml Light 0.7. This compiler can be used
 either as a standalone, batch-oriented compiler that produces
 standalone programs, or as an interactive, toplevel-based system.
 .
 The other compiler generates high-performance native code for a number
 of processors. Compilation takes longer and generates bigger code, but
 the generated programs deliver excellent performance, while retaining
 the moderate memory requirements of the bytecode compiler. It is not
 available on all arches though.
 .
 This package contains everything needed to develop OCaml applications.


- `initdb`: Create a PostgreSQL database on disk.
- `wpscan`:  Black box WordPress vulnerability scanner
 WPScan scans remote WordPress installations to find security issues.


- `plantuml`:  text-to-UML converter
 PlantUML is a program allowing to draw UML diagrams, using a simple
 human readable text description.
 .
 PlantUML supports the following UML diagrams:
   - sequence diagram
   - use case diagram
   - class diagram
   - activity diagram
   - component diagram
   - state diagram
   - object diagram
   - deployment diagram
   - timing diagram
 .
 The following non-UML diagrams are also supported:
   - wireframe graphical interface (Salt)
   - Archimate diagram
   - Specification and Description Language (SDL)
   - Ditaa diagram
   - Gantt diagram
   - mathematics with AsciiMath or JLaTeXMath notation
 .
 Output images can be generated in PNG, in SVG or LaTeX format.
 PlantUML also supports generation of ASCII art diagrams (only for
 sequence diagrams).


- `fnm`: Fast Node.js version manager.
- `fdroid`: F-Droid build tool.
- `nomad`: Distributed, highly available, datacenter-aware scheduler.
- `laravel-zero`: A command line installer for the Laravel Zero framework.
- `cmatrix`:  simulates the display from "The Matrix"
 Screen saver for the terminal based in the movie "The Matrix". It works in
 terminals of all dimensions and have the following features:
  * Support terminal resize.
  * Screen saver mode: any key closes it.
  * Selectable color.
  * Change text scroll rate.


- `fdroidcl`:  F-Droid desktop client
 F-Droid (https://f-droid.org/) desktop client.
 .
 While the Android client integrates with the system
 with regular update checks and notifications, this is a
 command line client that talks to connected devices via ADB
 (https://developer.android.com/tools/help/adb.html).  Quickstart Download
 the index: fdroidcl update


- `tea`:  graphical text editor with syntax highlighting
 TEA provides you with hundreds of functions. Want some tea?
 .
 TEA features:
  * Qt-based GUI with a tabbed layout engine;
  * hotkey customization;
  * spell checking (using aspell or hunspell);
  * support for multiple encodings;
  * syntax highlighting;
  * support for code snippets and templates;
  * string-handling functions such as sorting, reversing, de-formatting,
    trimming, filtering, conversions etc.;
  * editing support for Wikipedia, DocBook, LaTeX, and Lout;
  * reading support for text-based word processor formats (ABW, DOCX, FB2,
    KWD, ODT, RTF, SLA, SWX);
  * reading support for PDF and DjVu files, if they contain text;
  * bookmarks;
  * miscellaneous XML/XHTML/HTML tools;
  * "open at cursor" function from HTML href or img tags;
  * preview in external browsers;
  * drag'n'drop support (with text files and pictures);
  * built-in image viewer (BMP, GIF, JPEG, PNG, SVG, WBMP).


- `javadoc`: Generate Java API documentation in HTML format from source code.
- `middleman`: Static site generator written in Ruby.
- `drupal`: CLI for Drupal.
- `qmv`: Move files and directories using the default text editor to define the filenames.
- `buzzphrase`: Node.js command line tool to output a random buzzphrase.
- `zipalign`:  Zip archive alignment tool
 zipalign is an archive alignment tool that provides important optimization to
 Android application (.apk) files. The purpose is to ensure that all
 uncompressed data starts with a particular alignment relative to the start of
 the file.


- `openssl-genrsa`: OpenSSL command to generate RSA private keys.
- `ninja`: A Build system designed to be fast.
- `rar`:  Archiver for .rar files
 This is the RAR archiver from Eugene Roshal. It supports multiple volume
 archives and damage protection. It can also create SFX-archives. There are
 versions which run on DOS, Windows, FreeBSD, BSDI.
 .
 This program is shareware and you must register it after 40 days of use.


- `unison`:  file-synchronization tool for Unix and Windows
 Unison is a file-synchronization tool for Unix and Windows, written
 in OCaml. It allows two replicas of a collection of files and
 directories to be stored on different hosts (or different disks
 on the same host), modified separately, and then brought up to
 date by propagating the changes in each replica to the other.
 .
 Unison offers several advantages over various synchronization methods
 such as CVS, Coda, rsync, Intellisync, etc. Unison can run on and
 synchronize between Windows and many UNIX platforms. Unison requires
 no root privileges, system access or kernel changes to function. Unison
 can synchronize changes to files and directories in both directions,
 on the same machine, or across a network using ssh or a direct
 socket connection.
 .
 Transfers are optimised using a version of the rsync protocol,
 making it ideal for slower links. Unison has a clear and precise
 specification, and is resilient to failure due to its careful
 handling of the replicas and its private structures.


- `mktorrent`:  simple command line utility to create BitTorrent metainfo files
 mktorrent is a text-based utility to create BitTorrent metainfo files
 used by trackers and torrent clients. It can create metainfo files for
 single files or complete directories in a fast way.
 .
 It supports:
  - multiple trackers,
  - embedding custom comments into torrent files,
  - multi-threaded hashing.
 .
 It also supports setting the "private" flag, which advises the BitTorrent
 agents to refrain from using alternative peer discovery mechanisms,
 such as Distributed Hash Table (DHT), Local Peer Discovery (LPD),
 or Peer Exchange.


- `nix-build`: Build a Nix expression.
- `docker-logs`: Print container logs.
- `black`:  uncompromising Python code formatter (Python 3)
 Black is the uncompromising Python code formatter. By using it, you
 agree to cede control over minutiae of hand-formatting. In return,
 Black gives you speed, determinism, and freedom from pycodestyle
 nagging about formatting. You will save time and mental energy for
 more important matters.
 .
 Blackened code looks the same regardless of the project you're reading.
 Formatting becomes transparent after a while and you can focus on the
 content instead.
 .
 Black makes code review faster by producing the smallest diffs
 possible.


- `chisel`:  fast TCP/UDP tunnel over HTTP (program)
 This package contains a fast TCP/UDP tunnel, transported over HTTP, secured
 via SSH. Single executable including both client and server.  Chisel is mainly
 useful for passing through firewalls, though it can also be used to provide a
 secure endpoint into your network.


- `makepasswd`:  Generate and encrypt passwords
 Generates true random passwords using /dev/urandom, with the emphasis on
 security over pronounceability.  It can also encrypt plaintext passwords
 given in a temporary file.


- `go-doc`: Show documentation for a package or symbol.
- `go-fix`: Update packages to use new APIs.
- `go-build`: Compile Go sources.
- `makebuildserver`: Create an F-Droid build server virtual machine.
- `fgrep`: Matches patterns in files.
- `rails-routes`: List routes in a Rails application.
- `jdupes`:  identify and delete or link duplicate files
 jdupes is a program based in fdupes. The main goal of jdupes is identify
 and taking actions upon duplicate files. In comparison with fdupes, jdupes
 is heavily modified from and improved.
 .
 The biggest reason to use jdupes is raw speed. In testing on various data
 sets, jdupes is over 7 times faster than fdupes-1.51 on average.
 .
 Code in jdupes is written with data loss avoidance as the highest priority.
 If a choice must be made between being aggressive or careful, the careful
 way is always chosen.
 .
 jdupes includes features that are not found in fdupes. Examples of such
 features include btrfs block-level deduplication and control over which
 file is kept when a match set is automatically deleted. jdupes is not
 afraid of dropping features of low value; a prime example is the -1 switch
 which outputs all matches in a set on one line, a feature which was found
 to be useless in real-world tests and therefore thrown out.
 .
 jdupes can convert duplicate files in hardlinks or relative softlinks. It
 is useful in several scenarios, as in Debian packaging, to create relative
 symlinks to lots of duplicate files (it will substitute rdfind + symlinks
 commands, used to same purpose, when solving lintian duplicate-files).
 .
 Packages build for Linux versions have support to btrfs filesystem.


- `git-lfs`:  Git Large File Support
 An open source Git extension for versioning large files.
 Git Large File Storage (LFS) replaces large files such as
 audio samples, videos, datasets, and graphics with text
 pointers inside Git, while storing the file contents on
 a remote server.


- `secrethub`: A tool to keep secrets out of config files.
- `packer`: Build automated machine images.
- `androguard`:  full Python tool to play with Android files
 Androguard is a full Python tool to play with Android files.
 .
  * DEX, ODEX
  * APK
  * Android's binary xml
  * Android resources
  * Disassemble DEX/ODEX bytecodes
  * Decompiler for DEX/ODEX files


- `kustomize`:  Customization of kubernetes YAML configurations (program)
 kustomize lets you customize raw, template-free YAML files for multiple
 purposes, leaving the original YAML untouched and usable as is.
 .
 kustomize targets kubernetes; it understands and can patch kubernetes style
 API objects.  It's like make in that what it does is declared in a file, and
 it's like sed (https://www.gnu.org/software/sed), in that it emits edited
 text.


- `doas`:  transitional package
 This is a transitional package. It can safely be removed.


- `opam`:  package manager for OCaml
 OPAM stands for OCaml PAckage Manager. It aims to suit to a vast number
 of users and use cases, and has unique features:
  * Powerful handling of dependencies: versions constraints, optional
    dependencies, conflicts, etc.
  * Multiple repositories backends: HTTP, rsync, git
  * Ease to create packages and repositories
  * Ability to switch between different compiler versions
 .
 Typically, OPAM will probably make your life easier if you recognize
 yourself in at least one of these profiles:
  * You use multiple versions of the OCaml compiler, or you hack the compiler
    yourself and needs to frequently switch between compiler versions.
  * You use or develop software that needs a specific and/or modified version
    of the OCaml compiler to be installed.
  * You use or develop software that depends on a specific version of an OCaml
    library, or you just want to install a specific version of a package, not
    just the latest one.
  * You want to create your own packages yourself, put them on your own
    repository, with minimal effort.


- `wal`: A tool to create color schemes based on the dominant colors of a wallpaper.
- `iverilog`:  Icarus verilog compiler
 Icarus Verilog is intended to compile all of the Verilog HDL as
 described in the IEEE-1364 standard. It is not quite there
 yet. It does currently handle a mix of structural and behavioral
 constructs.
 .
 The compiler can target either simulation, or netlist (EDIF).


- `cargo-doc`:  Rust package manager, documentation
 Cargo is a tool that allows Rust projects to declare their various
 dependencies, and ensure that you'll always get a repeatable build.
 .
 To accomplish this goal, Cargo does four things:
  * Introduces two metadata files with various bits of project information.
  * Fetches and builds your project's dependencies.
  * Invokes rustc or another build tool with the correct parameters to build
    your project.
  * Introduces conventions, making working with Rust projects easier.
 .
 Cargo downloads your Rust project's dependencies and compiles your
 project.
 .
 This package contains the documentation.


- `shiori`: Simple bookmark manager built with Go.
- `copyq`:  Advanced clipboard manager with editing and scripting features
 CopyQ monitors system clipboard and saves its content in customized tabs.
 Saved clipboard can be later copied and pasted directly into any application.
 .
 Items can be:
  * edited with internal editor or with preferred text editor,
  * moved to other tabs,
  * drag'n'dropped to applications,
  * marked with tag or a note,
  * passed to or changed by custom commands,
  * or simply removed.
 .
 Features:
  * Support for Linux, Windows and OS X 10.9+
  * Store text, HTML, images or any other custom formats
  * Quickly browse and filter items in clipboard history
  * Sort, create, edit, remove, copy/paste, drag'n'drop items in tabs
  * Add notes or tags to items
  * System-wide shortcuts with customizable commands
  * Paste items with shortcut or from tray or main window
  * Fully customizable appearance
  * Advanced command-line interface and scripting
  * Ignore clipboard copied from some windows or containing some text
  * Support for simple Vim-like editor and shortcuts
  * Many more features


- `pastel`: Generate, analyze, convert and manipulate colors.
- `kaggle`: Official CLI for Kaggle implemented in Python 3.
- `docker-run`: Run a command in a new Docker container.
- `podman`:  tool to manage containers and pods
 Podman (the POD MANager) is a tool for managing containers and images, volumes
 mounted into those containers, and pods made from groups of containers.
 .
 At a high level, the scope of Podman and libpod is the following:
  * Support for multiple container image formats, including OCI and Docker
    images.
  * Full management of those images, including pulling from various sources
    (including trust and verification), creating (built via Containerfile or
    Dockerfile or committed from a container), and pushing to registries and
    other storage backends.
  * Full management of container lifecycle, including creation (both from an
    image and from an exploded root filesystem), running, checkpointing and
    restoring (via CRIU), and removal.
  * Full management of container networking, using Netavark.
  * Support for pods, groups of containers that share resources and are managed
    together.
  * Support for running containers and pods without root or other elevated
    privileges.
  * Resource isolation of containers and pods.
  * Support for a Docker-compatible CLI interface, which can both run
    containers locally and on remote systems.
  * No manager daemon, for improved security and lower resource utilization at
    idle.
  * Support for a REST API providing both a Docker-compatible interface and an
    improved interface exposing advanced Podman functionality.
  * Support for running on Windows and Mac via virtual machines run by podman
    machine.
 .
 Podman is a daemon-less alternative to Docker.


- `go-clean`: Remove object files and cached files.
- `msfvenom`: Manually generate payloads for metasploit.
- `terraform-fmt`: Format configuration according to Terraform language style conventions.
- `jhipster`: Web application generator using either monolithic or microservices architecture.
- `gh`:  GitHub CLI, GitHub’s official command line tool
 GitHub CLI "gh" is GitHub on the command line.  It brings pull requests,
 issues, and other GitHub concepts to the terminal next to where you are
 already working with git and your code.
 .
 GitHub CLI is available for repositories hosted on GitHub.com and GitHub
 Enterprise Server 2.20+, and to install on macOS, Windows, and Linux.
 .
 Comparison with hub:
 .
 For many years, hub (https://github.com/github/hub) was the unofficial
 GitHub CLI tool.  gh is a new project that helps us explore what an
 official GitHub CLI tool can look like with a fundamentally different
 design.  While both tools bring GitHub to the terminal, hub behaves as a
 proxy to git, and gh is a standalone tool.  Check out the more detailed
 explanation at https://github.com/cli/cli/blob/trunk/docs/gh-vs-hub.md
 to learn more.


- `jarsigner`: Sign and verify Java Archive (JAR) files.
- `gitlab`: Ruby wrapper and CLI for the GitLab API.
- `aws-google-auth`: Command line tool to acquire AWS temporary (STS) credentials using Google Apps as a federated (Single Sign-On) provider.
- `adguardhome`: A network-wide software for blocking ads & tracking.
- `transmission-create`: A CLI utility to create BitTorrent .torrent files.
- `influx`: InfluxDB command-line client.
- `f3read`: Validate .h2w files to test the real capacity of the drive.
- `csvkit`:  command-line tools for working with CSV
 csvkit is a suite of command-line tools for converting to and working with
 CSV, the king of tabular file formats.
 .
 It is inspired by pdftk, gdal and the original csvcut tool by Joe Germuska and
 Aaron Bycoffe.
 .
 If you need to do more complex data analysis than csvkit can handle, use
 agate.
 .
 This package provides the command-line tools.


- `quilt`:  Tool to work with series of patches
 Quilt manages a series of patches by keeping track of the changes
 each of them makes. They are logically organized as a stack, and you can
 apply, un-apply, refresh them easily by traveling into the stack (push/pop).
 .
 Quilt is good for managing additional patches applied to a package received
 as a tarball or maintained in another version control system. The stacked
 organization is proven to be efficient for the management of very large patch
 sets (more than hundred patches). As matter of fact, it was designed by and
 for Linux kernel hackers (Andrew Morton, from the -mm  branch, is the
 original author), and its main use by the current upstream maintainer is to
 manage the (hundreds of) patches against the kernel made for the SUSE
 distribution.
 .
 This package provides seamless integration into Debhelper or CDBS,
 allowing maintainers to easily add a quilt-based patch management system in
 their packages. The package also provides some basic support for those not
 using those tools. See README.Debian for more information.


- `poetry`: Manage Python packages and dependencies.
- `flask`: A general utility script for Flask applications. Loads the application defined in the `FLASK_APP` environment variable.
- `f3write`: Fill a drive out with .h2w files to test its real capacity.
- `sxiv`:  simple X image viewer
 sxiv is an alternative to feh and qiv. Its only dependency besides xlib
 is imlib2. The primary goal for writing sxiv is to create an image
 viewer, which only has the most basic features required for fast image
 viewing. It works nicely with tiling window managers and its code base
 should be kept small and clean to make it easy for you to dig into it
 and customize it for your needs.


- `archlinux-java`: A helper script that provides functionalities for Java environments.
- `rpmbuild`: RPM Package Build tool.
- `openfortivpn`:  Fortinet client for PPP+SSL VPN tunnel services
 openfortivpn is a client for PPP+SSL VPN tunnel services. It spawns a pppd
 process and operates the communication between the gateway and this process.
 .
 It is compatible with Fortinet VPNs.


- `i3lock`:  improved screen locker
 i3lock is a simple screen locker like slock. After starting it, you will
 see a white screen (you can configure the color/an image). You can return
 to your screen by entering your password.
 .
 i3lock forks so you can combine it with an alias to suspend to RAM.
 .
 You can specify either a background color or a PNG image which will be
 displayed while your screen is locked.
 .
 You can specify whether i3lock should bell upon a wrong password.
 .
 i3lock uses PAM and therefore is compatible with LDAP etc.


- `konsole`:  X terminal emulator
 Konsole is a terminal emulator built on the KDE Platform. It can contain
 multiple terminal sessions inside one window using detachable tabs.
 .
 Konsole supports powerful terminal features, such as customizable schemes,
 saved sessions, and output monitoring.


- `schroot`:  Execute commands in a chroot environment
 schroot allows users to execute commands or interactive shells in
 different chroots.  Any number of named chroots may be created, and
 access permissions given to each, including root access for normal
 users, on a per-user or per-group basis.  Additionally, schroot can
 switch to a different user in the chroot, using PAM for
 authentication and authorisation.  All operations are logged for
 security.
 .
 Several different types of chroot are supported, including normal
 directories in the filesystem, and also block devices.  Sessions,
 persistent chroots created on the fly from files (tar with optional
 compression) and Btrfs, ZFS, and LVM snapshots are also supported.
 .
 schroot supports kernel personalities, allowing the programs run
 inside the chroot to have a different personality.  For example,
 running 32-bit chroots on 64-bit systems, or even running binaries
 from alternative operating systems such as SVR4 or Xenix.
 .
 schroot also integrates with sbuild, to allow building packages with
 all supported chroot types, including session-managed chroot types
 such as Btrfs, ZFS, and LVM snapshots.
 .
 schroot shares most of its options with dchroot, but offers vastly
 more functionality.


- `flash`:  Fast Length Adjustment of SHort reads
 FLASH (Fast Length Adjustment of SHort reads) is a very fast and
 accurate software tool to merge paired-end reads from next-generation
 sequencing experiments. FLASH is designed to merge pairs of reads when
 the original DNA fragments are shorter than twice the length of reads.
 The resulting longer reads can significantly improve genome assemblies.
 They can also improve transcriptome assembly when FLASH is used to merge
 RNA-seq data.


- `mdbook`:  Markdown book creator tool
 mdBook is a command line tool to create books with Markdown. It is ideal for
 creating product or API documentation, tutorials, course materials or anything
 that requires a clean, easily navigable and customizable presentation.
 .
  * Lightweight Markdown syntax helps you focus more on your content
  * Integrated search support
  * Color syntax highlighting for code blocks for many different languages
  * Theme files allow customizing the formatting of the output
  * Preprocessors can provide extensions for custom syntax and modifying content
  * Backends can render the output to multiple formats
  * Written in Rust for speed, safety, and simplicity
  * Automated testing of Rust code samples


- `swupd`: Package management utility for Clear Linux.
- `exif`:  command-line utility to show EXIF information in JPEG files
 Most digital cameras produce EXIF files, which are JPEG files with
 extra tags that contain information about the image.
 .
 'exif' is a small command-line utility to show EXIF information hidden
 in JPEG files.


- `ctr`: Manage Containerd containers and images.
- `speedometer`:  measure and display the rate of data across a network connection
 Monitor network traffic or speed/progress of a file transfer. The
 program can be used for cases like:
 .
  - how long it will take for 38 MiB transfer to finish
  - how quickly is another transfer going
  - how fast is the upstream on this ADSL line
  - how fast is data written to a filesystem.


- `paru`: An AUR helper and pacman wrapper.
- `gcov`: Code coverage analysis and profiling tool that discovers untested parts of a program.
- `named`: Execute the DNS (Dynamic Name Service) server daemon that converts host names to IP addresses and vice versa.
- `iwctl`: A command line tool for controlling the iwd network supplicant.
- `pmount`:  mount removable devices as normal user
 pmount is a wrapper around the standard mount program which permits normal
 users to mount removable devices without a matching /etc/fstab entry. This
 provides a robust basis for automounting frameworks like GNOME's Utopia
 project and confines the amount of code that runs as root to a minimum.
 .
 If a LUKS capable cryptsetup package is installed, pmount is able to
 transparently mount encrypted volumes.


- `gnome-extensions`: Manage gnome extensions from the terminal.
- `zile`:  very small Emacs-subset editor
 GNU Zile is a small Emacs clone.  Zile is a customizable,
 self-documenting real-time display editor.  Zile was written to
 be as similar as possible to Emacs; every Emacs user should feel
 at home with Zile.


- `auracle`: Command line tool used to interact with Arch Linux's User Repository, commonly referred to as the AUR.
- `scancel`: Cancel a Slurm job.
- `fail2ban-client`: Configure and control fail2ban server.
- `legit`:  Git extension to assist in manipulating branches
 This program provides several commands that help to automate
 certain tasks with Git: seamless branch switching, syncing repository,
 creating and merging branches, manipulating remote branches.


- `scontrol`: View information about and modify jobs.
- `module`: Modify a users' environment using the module command.
- `smbmap`:  handy SMB enumeration tool
 SMBMap allows users to enumerate samba share drives across an entire domain.
 List share drives, drive permissions, share contents, upload/download
 functionality, file name auto-download pattern matching, and even execute
 remote commands. This tool was designed with pen testing in mind, and is
 intended to simplify searching for potentially sensitive data across large
 networks.
 Features:
  Pass-the-Hash Support
  File upload/download/delete
  Permission enumeration (writable share, meet Metasploit)
  Remote Command Execution
  Distrubted file content searching (beta!)
  File name matching (with an auto downoad capability)
  Host file parser supports IPs, host names, and CIDR
  SMB sigining detection
  Server version output
  Kerberos support! (super beta)


- `asterisk`: Telephone and exchange (phone) server.
- `kpackagetool5`:  command line kpackage tool
 KPackage provides classes for applications to manage user installable packages
 of non-binary assets.
 .
 This package is part of KDE Frameworks 5.
 .
 This package contains the runtime package management tool.


- `inotifywait`: Waits for changes to one or more files.
- `flameshot`:  Powerful yet simple-to-use screenshot software
 Flameshot is a powerful yet simple-to-use screenshot software.
 Notable features include customizable appearance, in-app screenshot editing,
 D-Bus interface, experimental GNOME/KDE Wayland support, integration with
 Imgur and support for both GUI and CLI interface.


- `bpftrace`:  high-level tracing language for Linux eBPF
 BPFtrace is a high-level tracing language for Linux enhanced Berkeley
 Packet Filter (eBPF) available in recent Linux kernels (4.x). BPFtrace
 uses LLVM as a backend to compile scripts to BPF-bytecode and makes
 use of BCC for interacting with the Linux BPF system, as well as
 existing Linux tracing capabilities: kernel dynamic tracing (kprobes),
 user-level dynamic tracing (uprobes), and tracepoints. The BPFtrace
 language is inspired by awk and C, and predecessor tracers such as
 DTrace and SystemTap.


- `sreport`: Generate reports on jobs, users, and clusters from accounting data.
- `clamav`:  anti-virus utility for Unix - command-line interface
 Clam AntiVirus is an anti-virus toolkit for Unix. The main purpose of
 this software is the integration with mail servers (attachment
 scanning). The package provides a flexible and scalable
 multi-threaded daemon in the clamav-daemon package, a command-line
 scanner in the clamav package, and a tool for automatic updating via
 the Internet in the clamav-freshclam package. The programs are based
 on libclamav, which can be used by other software.
 .
 This package contains the command line interface. Features:
  - built-in support for various archive formats, including Zip, Tar,
    Gzip, Bzip2, OLE2, Cabinet, CHM, BinHex, SIS and others;
  - built-in support for almost all mail file formats;
  - built-in support for ELF executables and Portable Executable files
    compressed with UPX, FSG, Petite, NsPack, wwpack32, MEW, Upack and
    obfuscated with SUE, Y0da Cryptor and others;
  - built-in support for popular document formats including Microsoft
    Office and Mac Office files, HTML, RTF and PDF.
 .
 For scanning to work, a virus database is needed. There are two options
 for getting it:
  - clamav-freshclam: updates the database from Internet. This is
    recommended with Internet access.
  - clamav-data: for users without Internet access. The package is
    not updated once installed. The clamav-getfiles package allows
    creating custom packages from an Internet-connected computer.


- `duperemove`:  extent-based deduplicator for file systems
 Duperemove is a tool for finding duplicated extents and submitting them for
 deduplication.  When given a list of files it will hash their contents on a
 block by block basis and compare those hashes to each other, finding and
 categorizing extents that match each other.
 .
 On BTRFS and, experimentally, XFS, it can then reflink such extents in a
 race-free way.  Unlike hardlink-based solutions, affected files appear
 independent in any way other than reduced disk space used.


- `yetris`: Clone of the game Tetris in the terminal.
- `bitwise`:  Interactive bitwise operation in ncurses
 This is multi base interactive calculator supporting dynamic base
 conversion and bit manipulation. It's a handy tool for low level hackers,
 kernel developers and device drivers developers.
 .
 Some of the features include:
 .
 Interactive ncurses interface
 Command line calculator.
 Individual bit manipulator.
 Bitwise operations such as NOT, OR, AND, XOR, and shifts.


- `snake4`:  Snake game
 This is a basic but nice implementation of the snake game. The objective
 is to "snake around" and eat fruit, while avoiding the evil headbanger
 and not crashing into your tail.
 .
 Features five levels of difficulty and a site-wide high score list.


- `arecord`: Sound recorder for ALSA soundcard driver.
- `srun`: Create an interactive slurm job or connect to an existing job.
- `sstat`: View information about running jobs.
- `maim`:  takes screenshots of your desktop
 maim (make image) takes screenshots of your desktop. It has options
 to take only a region, and relies on another program called slop to
 query the user for regions using the graphical interface.
 .
 maim is command line tool that is supposed to be an improved scrot.


- `logsave`:  save the output of a command in a log file
 The logsave program will execute cmd_prog with the specified
 argument(s), and save a copy of its output to logfile.  If the
 containing directory for logfile does not exist, logsave will
 accumulate the output in memory until it can be written out.  A copy
 of the output will also be written to standard output.


- `netselect`:  speed tester for choosing a fast network server
 This package provides a utility that can perform parallelized
 tests on distant servers using either UDP traceroutes or ICMP queries.
 .
 It can process a (possibly very long) list of servers, and choose the
 fastest/closest one automatically.


- `bpytop`:  Resource monitor that shows usage and stats
 Resource monitor that shows usage and stats for processor,
 memory, disks, network and processes. bpytop includes:
  - Easy to use, with a game inspired menu system.
  - Full mouse support, all buttons with a highlighted key is clickable
      and mouse scroll works in process list and menu boxes.
  - Fast and responsive UI with UP, DOWN keys process selection.
  - Function for showing detailed stats for selected process.
  - Ability to filter processes, multiple filters can be entered.
  - Easy switching between sorting options.
  - Send SIGTERM, SIGKILL, SIGINT to selected process.
  - UI menu for changing all config file options.
  - Auto scaling graph for network usage.
  - Shows current read and write speeds for disks
 .
 Python port of bashtop.


- `hello`:  example package based on GNU hello
 The GNU hello program produces a familiar, friendly greeting.  It
 allows non-programmers to use a classic computer science tool which
 would otherwise be unavailable to them.
 .
 Seriously, though: this is an example of how to do a Debian package.
 It is the Debian version of the GNU Project's `hello world' program
 (which is itself an example for the GNU Project).


- `ksvgtopng5`: Convert SVG files to PNG format.
- `netselect-apt`:  speed tester for choosing a fast Debian mirror
 This package provides a utility that can choose the best Debian mirror
 by downloading the full mirror list and using netselect to find the
 fastest/closest one.
 .
 It can output a sources.list(5) file that can be used with package
 management tools such as apt or aptitude.


- `htpdate`:  HTTP based time synchronization tool
 The  HTTP Time Protocol (HTP) is used to synchronize a computer's time with
 web servers as reference time source. This program can be used instead
 ntpdate or similar, in networks that has a firewall blocking the NTP port.
 .
 Htpdate will synchronize the computer time to Greenwich Mean Time (GMT),
 using the timestamps from HTTP headers found in web servers response (the
 HEAD method will be used to get the information).
 .
 Htpdate works through proxy servers. Accuracy of htpdate will be usually
 within 0.5 seconds (better with multiple servers).


- `rig`:  Random identity generator
 RIG (Random Identity Generator) is a free replacement for a shareware
 program out there called 'fake'. It generates random, yet real-looking,
 personal data. It is useful if you need to feed a name to a Web site,
 BBS, or real person, and are too lazy to think of one yourself. Also,
 if the Web site/BBS/person you are giving the information to tries to
 cross-check the city, state, zip, or area code, it will check out.


- `lslogins`: Show information about users on a Linux system.
- `extundelete`:  utility to recover deleted files from ext3/ext4 partition
 extundelete uses the information stored in the partition's journal to attempt
 to recover a file that has been deleted. There is no guarantee that any
 particular file will be able to be undeleted.


- `snmpwalk`: SNMP query tool.
- `slop`:  queries for a selection from the user and prints the region to stdout
 slop (Select Operation) is an application that queries for a
 selection from the user and prints the region to stdout. It grabs the
 mouse and turns it into a crosshair, lets the user click and drag to
 make a selection (or click on a window) while drawing a pretty box
 around it, then finally prints the selection's dimensions to stdout.
 .
 Features:
 .
  * Hovering over a window will cause a selection rectangle to appear
    over it.
  * Clicking on a window makes slop return the dimensions of the
    window.
  * Clicking and dragging causes a selection rectangle to appear,
    renders pretty well (compared to scrot). And will return the
    dimensions of that rectangle in absolute screen coords.
  * On startup it turns your cursor into a crosshair, then adjusts the
    cursor into angles as you drag the selection rectangle.
  * Supports simple arguments:
    * Change selection rectangle border size.
    * Select X display.
    * Set padding size, even negative padding sizes!
    * Set click tolerance for if you have a shaky mouse.
    * Set the color of the selection rectangles to match your theme!
      (Even supports transparency!)
  * Remove window decorations from selections.
  * Supports OpenGL hardware acceleration.
  * Supports textured themes.
  * Supports programmable shaders.
  * Supports a magnifying glass.


- `sacct`: Display accounting data from the Slurm service.
- `pi`:  Compute Archimedes' constant Pi to arbitrary precision
 This program computes Archimedes' constant Pi to arbitrary precision.
 It is extremely fast and the precision is only limited by your machine's
 main memory.
 .
 This is a teaser for the CLN library, to which the actual computation is
 delegated.  You may use these decimal digits as random digits or search
 them for hidden messages.  :-)


- `snake4scores`: Show the high scores from the snake4 game.
- `physlock`:  lightweight Linux console locking tool
 physlock is an alternative to vlock, it is equivalent to
 `vlock -an'. It is written because vlock blocks some Linux
 kernel mechanisms like hibernate and suspend and can therefore
 only be used with some limitations. physlock is designed to be
 more lightweight and it does not have a plugin interface.


- `vnstat`:  console-based network traffic monitor
 vnStat is a network traffic monitor for Linux. It keeps a log of
 daily network traffic for the selected interface(s). vnStat is not
 a packet sniffer. The traffic information is analyzed from the /proc
 filesystem, so vnStat can be used without root permissions.


- `ark`:  archive utility
 Ark manages various archive formats, including tar, gzip, bzip2, rar and zip,
 as well as CD-ROM images.  Ark can be used to browse, extract, create, and
 modify archives.
 .
 This package is part of the KDE SC utilities module.


- `sacctmgr`: View, setup, and manage Slurm accounts.
- `protontricks`: A simple wrapper that does winetricks things for Proton enabled games, requires Winetricks.
- `jpegtran`: Perform lossless transformation of JPEG files.
- `eix`: Utilities for searching local Gentoo packages.
- `jp2a`:  converts jpg and png images to ascii
 Small utility that converts JPEG images to ASCII (text) using libjpeg. It
 also can convert PNG pictures to ASCII via libpng. jp2a is very flexible.
 It can use ANSI colors and html in output.
 .
 jp2a can also download and convert images from Internet via command line.


- `docker-ps`: List Docker containers.
- `exiv2`:  EXIF/IPTC/XMP metadata manipulation tool
 Exiv2 is a C++ library and a command line utility to manage image metadata.
 It provides fast and easy read and write access to the Exif, IPTC and XMP
 metadata of images in various formats
 .
 Exiv2 command line utility to:
 .
  * print Exif, IPTC and XMP image metadata in different formats:
    - Exif summary info, interpreted values, or the plain data for each tag
  * set, add and delete Exif, IPTC and XMP image metadata from command line
    modify commands or command scripts
  * adjust the Exif timestamp (that's how it all started...)
  * rename Exif image files according to the Exif timestamp
  * extract, insert and delete Exif, IPTC and XMP metadata and JPEG comments
  * extract previews from RAW images and thumbnails from the Exif metadata
  * insert and delete the thumbnail image embedded in the Exif metadata
  * print, set and delete the JPEG comment of JPEG images
  * fix the Exif ISO setting of picture taken with Canon and Nikon cameras


- `httprobe`:  Take a list of domains and probe for working HTTP and HTTPS servers
 This package contains a tool to test a domains list. It takes a list of
 domains and probe for working http and https servers.


- `xkcdpass`:  secure passphrase generator inspired by XKCD 936
 A flexible and scriptable password generator which generates strong
 passphrases, inspired by XKCD 936:
 .
     $ xkcdpass
     > correct horse battery staple


- `buku`:  Powerful command-line bookmark manager
 Feature
 .
  - Store bookmarks with auto-fetched title, tags and description
  - Auto-import from Firefox, Google Chrome and Chromium
  - Open bookmarks and search results in browser
  - Shorten, expand URLs, browse cached page from Wayback Machine
  - Text editor integration
  - Lightweight, clean interface, custom colors
  - Powerful search options (regex, substring...)
  - Continuous search with on the fly mode switch
  - Portable, merge-able database to sync between systems
  - Import/export bookmarks from/to HTML, Markdown or Orgfile
  - Smart tag management using redirection (>>, >, <<)
  - Multithreaded full DB refresh, manual encryption support
  - Shell completion scripts, man page with handy examples


- `hunspell`:  spell checker and morphological analyzer (program)
 Hunspell is a spell checker and morphological analyzer library and program
 designed for languages with rich morphology and complex word compounding or
 character encoding. It is based on MySpell and features an Ispell-like
 terminal interface using Curses library, an Ispell pipe interface and an
 OpenOffice.org UNO module.
 .
 Main features:
  - Unicode support (first 65535 Unicode characters)
  - morphological analysis (in custom item and arrangement style)
  - Max. 65535 affix classes and twofold affix stripping (for agglutinative
    languages, like Azeri, Basque, Estonian, Finnish, Hungarian, Turkish, etc.)
  - Support complex compoundings (for example, Hungarian and German)
  - Support language specific algorithms (for example, handling Azeri
    and Turkish dotted i, or German sharp s)
  - Handling conditional affixes, circumfixes, fogemorphemes,
    forbidden words, pseudoroots and homonyms.
 .
 This package contains the program with the Ispell-like terminal and pipe
 interfaces.


- `docker-inspect`: Return low-level information on Docker objects.
- `newman`: Collection runner for Postman.
- `newsboat`:  text mode rss feed reader with podcast support
 newsboat is an RSS/Atom feed reader for the text console. It supports OPML
 import/export, podcasts (via companion program podboat), and can serve as
 a client to various feed aggregators (TT-RSS, The Old Reader, Newsblur,
 FeedHQ, ownCloud/nextCloud News). Its interface draws inspiration from mutt
 and slrn.
 .
 Successor of newsbeuter.


- `firebase`: Firebase Command Line Interface (CLI) Tools.
- `hostapd`:  access point and authentication server for Wi-Fi and Ethernet
 IEEE 802.11 AP and IEEE 802.1X/WPA/WPA2/WPA3/EAP Authenticator
 .
 Originally, hostapd was an optional user space component for Host AP
 driver. It adds more features to the basic IEEE 802.11 management
 included in the kernel driver: using external RADIUS authentication
 server for MAC address based access control, IEEE 802.1X Authenticator
 and dynamic WEP keying, RADIUS accounting, WPA/WPA2/WPA3 (IEEE 802.11i/RSN)
 Authenticator and dynamic TKIP/CCMP keying.
 .
 The current version includes support for other drivers, an integrated
 EAP authenticator (i.e., allow full authentication without requiring
 an external RADIUS authentication server), and RADIUS authentication
 server for EAP authentication.
 .
 hostapd works with the following drivers:
 .
  * mac80211 based drivers with support for master mode [linux]
  * Host AP driver for Prism2/2.5/3 [linux]
  * Driver interface for FreeBSD net80211 layer [kfreebsd]
  * Any wired Ethernet driver for wired IEEE 802.1X authentication.


- `strip-nondeterminism`:  file non-deterministic information stripper — stand-alone tool
 StripNondeterminism is a library for stripping non-deterministic information
 such as timestamps and filesystem ordering from various file and archive
 formats.
 .
 This can be used as a post-processing step to improve the reproducibility of a
 build product, when the build process itself cannot be made deterministic.
 .
 It is used as part of the Reproducible Builds project, although it should be
 considered a temporary workaround which should not be needed in the long
 term; upstream software should be reproducible even without using such a tool.
 .
 This package installs the stand-alone ‘strip-nondeterminism’ tool.


- `twm`:  Tab window manager
 twm is a window manager for the X Window System.  It provides title bars,
 shaped windows, several forms of icon management, user-defined macro
 functions, click-to-type and pointer-driven keyboard focus, and
 user-specified key and pointer button bindings.


- `wrangler`: Cloudflare Workers command line tool.
- `var-dump-server`: Symfony dump server.
- `dvc-diff`: Show changes in DVC tracked file and directories.
- `nativefier`: Command-line tool to create a desktop app for any web site with minimal configuration.
- `delta`:  heuristic minimizer of interesting files
 Delta assists you in minimizing "interesting" files subject to a test of
 their "interestingness". A common such situation is when attempting to
 isolate a small failure-inducing substring of a large input that causes
 your program to exhibit a bug.


- `iex`: IEx is the interactive shell for Elixir.
- `grpcurl`: Like cURL, but for gRPC: CLI tool for interacting with gRPC servers.
- `mmdc`: CLI for mermaid, a diagram generation tool with a domain-specific language.
- `hive`: CLI tool for Apache Hive.
- `indent`:  C language source code formatting program
 The `indent' program changes the appearance of a C program by
 inserting or deleting whitespace.
 .
 `indent' also provides options for controlling the alignment of braces and
 declarations, program indenting, and other stylistic parameters, including
 formatting of both C and C++ comments.


- `docker-save`: Export one or more docker images to archive.
- `dua`: Dua (Disk Usage Analyzer) is a tool to conveniently learn about the usage of disk space of a given directory.
- `phan`: A static analysis tool for PHP.
- `notmuch`:  thread-based email index, search and tagging
 Notmuch is a system for indexing, searching, reading, and tagging
 large collections of email messages in maildir or mh format. It uses
 the Xapian library to provide fast, full-text search with a very
 convenient search syntax.
 .
 This package contains the notmuch command-line interface


- `ocamlfind`: The findlib package manager for OCaml.
- `unclutter`:  hides the mouse cursor in X after a period of inactivity
 unclutter hides your X mouse cursor when you don't need it, to prevent it
 from getting in the way. You have only to move the mouse to restore the
 mouse cursor.
 .
 This is the original unclutter implementation from the 90s which
 works well with classic X11 programs. For a more modern
 implementation which works better with some more modern applications
 and UI libraries, see unclutter-xfixes.


- `cdk`: A CLI for AWS Cloud Development Kit (CDK).
- `lt`: Localtunnel exposes your localhost to the world for easy testing and sharing.
- `aws-quicksight`: CLI for AWS QuickSight.
- `dvc-freeze`: Freeze stages in the DVC pipeline.
- `vala`: Vala code runner.
- `chezmoi`: A multi-machine dotfile manager, written in Go.
- `ghci`: The Glasgow Haskell Compiler's interactive environment.
- `openssl-s_client`: OpenSSL command to create TLS client connections.
- `uvicorn`:  ASGI server implementation, using uvloop and httptools
 Uvicorn is a fast ASGI server, built on uvloop and httptools. It currently
 supports HTTP/1.1 and WebSockets.
 .
 Uvicorn is designed with particular attention to connection and resource
 management, in order to provide a robust server implementation. It aims to
 ensure graceful behavior to either server or client errors, and resilience to
 poor client behavior or denial of service attacks.
 .
 This package contains the CLI script.


- `docker-network`: Create and manage docker networks.
- `meson`:  high-productivity build system
 Meson is a build system designed to increase programmer
 productivity. It does this by providing a fast, simple and easy to
 use interface for modern software development tools and practices.


- `recsel`: Print records from a recfile: a human-editable, plain text database.
- `aws-glue`: CLI for AWS Glue.
- `sublist3r`:  Fast subdomains enumeration tool for penetration testers
 This package contains a Python security tool designed to enumerate subdomains
 of websites using OSINT. It helps penetration testers and bug hunters collect
 and gather subdomains for the domain they are targeting over the network.
 Sublist3r enumerates subdomains using many search engines such as Google,
 Yahoo, Bing, Baidu, and Ask. Sublist3r also enumerates subdomains using
 Netcraft, Virustotal, ThreatCrowd, DNSdumpster, and ReverseDNS.
 .
 Subbrute was integrated with Sublist3r to increase the possibility of finding
 more subdomains using bruteforce with an improved wordlist.


- `elixir`:  functional meta-programming aware language
 Elixir is a functional meta-programming aware language intended primarily for
 developing distributed, fault-tolerant and scalable systems. Elixir source
 code is compiled to bytecode for the Erlang Virtual Machine (EVM), and can use
 Erlang libraries transparently.


- `amass-enum`: Find subdomains of a domain.
- `ghdl`:  VHDL compiler/simulator
 GHDL is a compiler and simulator for VHDL, a Hardware Description Language.
 GHDL is not an interpreter: it allows you to analyse and elaborate sources to
 generate machine code from your design. Native program execution is the only
 way for high speed simulation.
 .
 GHDL offers three machine code generation backends: one based on GCC, one
 using the LLVM compiler suite and a GHDL specific one called mcode. These are
 available in the ghdl-gcc, ghdl-llvm and ghdl-mcode packages respectively.
 Both the GCC and LLVM backends create highly optimized code for excellent
 simulation performance while simulations compiled with the GCC backend also
 allow coverage testing using gcov. The mcode backend creates less performant
 code but makes up for it with much faster compilation. It is therefore
 preferable for smaller projects without large or long running simulations.
 .
 Multiple backends can be installed at the same time and selected by either
 invoking the desired GHDL directly (as ghdl-gcc, ghdl-llvm or ghdl-mcode) or
 by providing a GHDL_BACKEND environment variable (containing gcc, llvm or
 mcode) while invoking ghdl.
 .
 This package is a dependency package that will make sure at least one backend
 is installed.


- `testssl`: Check SSL/TLS protocols and ciphers supported by a server.
- `scc`: Tool written in Go that counts lines of code.
- `gh-auth`: Authenticate with a GitHub host from the command line.
- `gitlab-ctl`: CLI tool for managing the GitLab omnibus.
- `aws-iam`: CLI for AWS IAM.
- `ss-local`: Run a Shadowsocks client as a SOCKS5 proxy.
- `adb-shell`: Android Debug Bridge Shell: Run remote shell commands on an Android emulator instance or connected Android devices.
- `xcaddy`: The custom build tool for the Caddy Web Server.
- `direnv`:  Utility to set directory specific environment variables
 direnv is an environment variable manager for your shell. It knows
 how to hook into bash, zsh and fish shell to load or unload
 environment variables depending on your current directory. This
 allows one to have project-specific environment variables and not
 clutter the "~/.profile" file.
 .
 Before each prompt it checks for the existence of an ".envrc" file in
 the current and parent directories. If the file exists, it is loaded
 into a bash sub-shell and all exported variables are then captured by
 direnv and then made available to your shell.
 .
 Because direnv is compiled into a single static executable it is fast
 enough to be unnoticeable on each prompt. It is also language
 agnostic and can be used to build solutions similar to rbenv, pyenv,
 phpenv, ...


- `deemix`: A barebone deezer downloader library built from the ashes of Deezloader Remix.
- `surfraw`:  fast unix command line interface to WWW
 Surfraw - Shell Users' Revolutionary Front Rage Against the World Wide Web
 .
 Surfraw provides a fast unix command line interface to a variety of
 popular WWW search engines and other artifacts of power. It reclaims
 google, altavista, dejanews, freshmeat, research index, slashdot
 and many others from the false-prophet, pox-infested heathen lands of
 html-forms, placing these wonders where they belong, deep in unix
 heartland, as god loving extensions to the shell.
 .
 Surfraw abstracts the browser away from input. Doing so lets it get
 on with what it's good at. Browsing. Interpretation of linguistic
 forms is handed back to the shell, which is what it, and human
 beings are good at. Combined with incremental text browsers, such
 as links, w3m (or even lynx), and screen(1), or netscape-remote
 a Surfraw liberateur is capable of research speeds that leave
 GUI tainted idolaters agape with fear and wonder.


- `dvc-unfreeze`: Unfreeze stages in the DVC pipeline.
- `mpg321`:  Simple and lightweight command line MP3 player
 mpg321 is a clone of the popular mpg123 command-line mp3 player. It should
 function as a drop-in replacement for mpg123 in many cases. While some of
 the functionality of mpg123 is not yet implemented, mpg321 should function
 properly in most cases for most people, such as for frontends such as
 gqmpeg.
 .
 mpg321 is based on the mad MPEG audio decoding library. It therefore is
 highly accurate, and also uses only fixed-point calculation, making it
 more efficient on machines without a floating-point unit. It is not as
 fast as mpg123 on systems which have a floating point unit.


- `dvc-fetch`: Download DVC tracked files and directories from a remote repository.
- `virt-sparsify`: Make virtual machine drive images thin-provisioned.
- `sponge`: Soak up the input before writing the output file.
- `git-annex`:  manage files with git, without checking their contents into git
 git-annex allows managing large files with git, without storing the file
 contents in git. It can sync, backup, and archive your data, offline
 and online. Checksums and encryption keep your data safe and secure. Bring
 the power and distributed nature of git to bear on your large files with
 git-annex.
 .
 It can store large files in many places, from local hard drives, to a
 large number of cloud storage services, including S3, WebDAV,
 and rsync, with dozens of cloud storage providers usable via plugins.
 Files can be stored encrypted with gpg, so that the cloud storage
 provider cannot see your data. git-annex keeps track of where each file
 is stored, so it knows how many copies are available, and has many
 facilities to ensure your data is preserved.
 .
 git-annex can also be used to keep a folder in sync between computers,
 noticing when files are changed, and automatically committing them
 to git and transferring them to other computers. The git-annex webapp
 makes it easy to set up and use git-annex this way.


- `redis-server`:  Persistent key-value database with network interface
 Redis is a key-value database in a similar vein to memcache but the dataset
 is non-volatile. Redis additionally provides native support for atomically
 manipulating and querying data structures such as lists and sets.
 .
 The dataset is stored entirely in memory and periodically flushed to disk.


- `grex`: Simple command line tool to generate regular expressions.
- `sonar-scanner`: SonarScanner is a generic scanner for SonarQube for projects do not use any specific build tool like maven, gradle , etc.
- `dvc-destroy`: Remove all DVC files and directories from a DVC project.
- `multipass`: CLI to manage Ubuntu virtual machines using native hypervisors.
- `aws-vault`: A vault for securely storing and accessing AWS credentials in development environments.
- `func`: Azure Functions Core Tools: Develop and test Azure Functions locally.
- `xpdf`:  Motif-based PDF reader using the Poppler library
 xpdf is a light-weight open source viewer for Portable Document Format (PDF)
 files (also called 'Adobe Acrobat' or 'Acrobat' files).  This is just the
 xpdf viewer client; various command-line pdf tools are now provided via the
 poppler-utils package.
 .
 Debian's xpdf is a fork of Xpdf version 3, modified to use the Poppler
 PDF rendering library but keeping the Motif toolkit, and nowadays maintained
 as the xpopple project.


- `amass`:  In-depth DNS Enumeration and Network Mapping
 This package contains a tool to help information security professionals
 perform network mapping of attack surfaces and perform external asset
 discovery using open source information gathering and active reconnaissance
 techniques.
 .
 Information Gathering Techniques Used:
    - DNS: Basic enumeration, Brute forcing (upon request), Reverse DNS
      sweeping, Subdomain name alterations/permutations, Zone transfers (upon
      request)
    - Scraping: Ask, Baidu, Bing, DNSDumpster, DNSTable, Dogpile, Exalead,
      Google, HackerOne, IPv4Info, Netcraft, PTRArchive, Riddler, SiteDossier,
      ViewDNS, Yahoo
    - Certificates: Active pulls (upon request), Censys, CertSpotter, Crtsh,
      Entrust, GoogleCT
    - APIs: AlienVault, BinaryEdge, BufferOver, CIRCL, CommonCrawl, DNSDB,
      HackerTarget, Mnemonic, NetworksDB, PassiveTotal, RADb, Robtex,
      SecurityTrails, ShadowServer, Shodan, Spyse (CertDB & FindSubdomains),
      Sublist3rAPI, TeamCymru, ThreatCrowd, Twitter, Umbrella, URLScan,
      VirusTotal
    - Web Archives: ArchiveIt, ArchiveToday, Arquivo, LoCArchive,
      OpenUKArchive, UKGovArchive, Wayback
 .
 This package contains the command amass.


- `pipx`:  execute binaries from Python packages in isolated environments
 pipx allows you to...
 .
  * Run the latest version of a CLI application from a package
    in a temporary virtual environment,
    leaving your system untouched after it finishes.
  * Install packages to isolated virtual environments,
    while globally exposing their CLI applications
    so you can run them from anywhere.
  * Easily list, upgrade, and uninstall packages
    that were installed with pipx.
 .
 pipx runs with regular user permissions,
 never calling "sudo pip install".


- `csvtool`:  handy command line tool for handling CSV files
 OCaml CSV is a library to read and write CSV (comma-separated values)
 files.  It also supports all extensions used by Excel - eg. quotes,
 newlines, 8 bit characters in fields, etc.
 .
 This package contains csvtool, a handy command line tool for handling
 CSV files from shell scripts.


- `docker-exec`: Execute a command on an already running Docker container.
- `diffoscope`:  in-depth visual diff tool for files, archives and directories
 diffoscope is a visual diff tool that attempts try to get to the bottom of
 what makes files or directories actually different.
 .
 It can recursively unpack archives of many kinds, transforming various binary
 formats into more human-readable form to compare them in a human-readable way.
 It can compare two tarballs, ISO images or PDFs just as easily. The
 differences can be displayed on the console or in a HTML report.
 .
 This is a dependency package that recommends the full set of external tools,
 to support as many type of files as possible.
 .
 File formats supported include: Android APK files, Android boot images, Android
 package resource table (ARSC), Apple Xcode mobile provisioning files, ar(1)
 archives, ASM Function, Berkeley DB database files, bzip2 archives,
 character/block devices, ColorSync colour profiles (.icc), Coreboot CBFS
 filesystem images, cpio archives, Dalvik .dex files, Debian .buildinfo files,
 Debian .changes files, Debian source packages (.dsc), Device Tree Compiler blob
 files, directories, ELF binaries, ext2/ext3/ext4/btrfs/fat filesystems,
 eXtensible ARchive files, Filesystem image, Flattened Image Tree blob files,
 FreeDesktop Fontconfig cache files, FreePascal files (.ppu), Gettext message
 catalogues, GHC Haskell .hi files, GIF image files, Git repositories, GNU R
 database files (.rdb), GNU R Rscript files (.rds), Gnumeric spreadsheets, GPG
 keybox databases, Gzipped files, Hierarchical Data Format database, HTML files
 (.html), ISO 9660 CD images, Java .class files, Java .jmod modules, JavaScript
 files, JPEG images, JSON files, Linux kernel images, LLVM IR bitcode files,
 local (UNIX domain) sockets and named pipes (FIFOs), LZ4 compressed files, lzip
 compressed files, macOS binaries, Microsoft Windows icon files, Microsoft Word
 docx files, Mono 'Portable Executable' files, Mozilla-optimized .ZIP archives,
 Multimedia metadata, OCaml interface files, Ogg Vorbis audio files, OpenOffice
 odt files, OpenSSH public keys, OpenWRT package archives (.ipk), PDF
 documents, PE32 files, PGP signatures, PGP signed/encrypted messages, PNG
 images, PostScript documents, Public Key Cryptography Standards (PKCS) files
 (version #7), Python .pyc files, RPM archives, Rust object files (.deflate),
 Sphinx inventory files, SQLite databases, SquashFS filesystems, symlinks, tape
 archives (.tar), tcpdump capture files (.pcap), text files, TrueType font
 files, U-Boot legacy image files, UKI image (.efi), WebAssembly binary module,
 XML binary schemas (.xsb), XML files, XMLB files, XZ compressed files, ZIP
 archives and Zstandard compressed files.
 .
 diffoscope is developed as part of the Reproducible Builds project.


- `docker-system`: Manage Docker data and display system-wide information.
- `kubectl-get`: Get Kubernetes objects and resources.
- `dotnet-build`: Builds a .NET application and its dependencies.
- `hadolint`: Dockerfile linter.
- `xephyr`: A nested X server that runs as an X application.
- `dvc-init`: Initialize a new local DVC repository.
- `ansible-pull`: Pull ansible playbooks from a VCS repo and executes them for the local host.
- `dvc-gc`: Remove unused files and directories from the cache or remote storage.
- `gh-release`: Manage GitHub releases from the command line.
- `chroma`:  Abstract puzzle game - graphical version
 Chroma is an abstract puzzle game. A variety of colourful shapes are
 arranged in a series of increasingly complex patterns, forming
 fiendish traps that must be disarmed and mysterious puzzles that must
 be manipulated in order to give up their subtle secrets. Initially so
 straightforward that anyone can pick it up and begin to play, yet
 gradually becoming difficult enough to tax even the brightest of
 minds. Have you got what it takes to solve Chroma?
 .
 A terminal-based version of this game is available in the
 'chroma-curses' package.


- `adb-install`: Android Debug Bridge Install: Push packages to an Android emulator instance or connected Android devices.
- `cargo-rustc`: Compile a Rust package, and pass extra options to the compiler.
- `streamlink`:  CLI for extracting video streams from various websites to a video player
 Streamlink is a CLI utility which pipes video streams from various services
 into a video player, such as VLC.
 The main purpose of streamlink is to avoid resource-heavy and unoptimized
 websites, while still allowing the user to enjoy various streamed content.
 .
 Streamlink is a fork of the Livestreamer project.
 .
 Please consider donating or paying for subscription services when they are
 available for the content you consume and enjoy.


- `gh-issue`: Manage GitHub issues from the command line.
- `expose`: An open source tunnel application for sharing websites.
- `cf`: Command line tool to manage apps and services on Cloud Foundry.
- `openssl-req`: OpenSSL command to manage PKCS#10 Certificate Signing Requests.
- `clang-format`:  Tool to format C/C++/Obj-C code
 Clang-format is both a library and a stand-alone tool with the goal of
 automatically reformatting C++ sources files according to configurable
 style guides. To do so, clang-format uses Clang's Lexer to transform an
 input file into a token stream and then changes all the whitespace around
 those tokens. The goal is for clang-format to both serve both as a user
 tool (ideally with powerful IDE integrations) and part of other
 refactoring tools, e.g. to do a reformatting of all the lines changed
 during a renaming.
 .
 This is a dependency package providing the clang format tool.


- `ajson`: Executes JSONPath on JSON objects.
- `colordiff`:  tool to colorize 'diff' output
 ColorDiff is a wrapper for the 'diff' command. It produces
 the same output as diff, but with colored highlighting to improve
 readability. The color schemes can be customized.
 .
 The output is similar to the syntax-highlighting mode of Vim or Emacs
 when editing a patch created by diff.


- `kosmorro`: Compute the ephemerides and the events for a given date, at a given position on Earth.
- `youtube-viewer`: Command-line application for searching and playing videos from YouTube.
- `tmuxinator`:  Create and manage tmux sessions easily
 Tmuxinator is management tool of tmux sessions.


- `travis`:  trajectory analyzer and visualizer
 TRAVIS (Trajectory Analyzer and Visualizer) is a free tool for analyzing
 and visualizing trajectories from all kinds of Molecular Dynamics or
 Monte Carlo simulations. The aim of TRAVIS is to collect as many analyses
 as possible in one program, creating a powerful tool and making it
 unnecessary to use many different programs for evaluating simulations.
 This should greatly rationalize and simplify the workflow of analyzing
 trajectories. The following analysis functions are available:
 .
 Static (time independent) Functions:
  * Radial, Angular, Dihedreal or Combined Distribution Function
  * Point-Plane or Point-Line Distance Distribution
  * Plane Projection Distribution
  * Fixed Plane Density Profile
  * Density, Spatial or Dipole Distribution Function
 .
 Dynamic (time dependent) Functions:
  * Velocity Distribution Function
  * Mean Square Displacement / Diffusion Coefficients
  * Velocity Autocorrelation Functions
  * Vector Reorientation Dynamics
  * Van Hove Correlation Function
  * Aggregation Functions (DACF, DLDF, DDisp)
 .
 Spectroscopic Functions:
  * Calculate Power Spectrum
  * Calculate IR Spectrum
  * Calculate Raman Spectrum
 .
 TRAVIS can read trajectory files in XYZ, PDB, LAMMPS or DLPOLY format.


- `docker-swarm`: A container orchestration tool.
- `scrcpy`: Display and control your Android device on a desktop.
- `dotnet-publish`: Publish a .NET application and its dependencies to a folder for deployment to a hosting system.
- `emulator`: Manager Android emulators from the command line.
- `glow`: Render Markdown in the terminal.
- `docker-service`: Manage the services on a docker daemon.
- `awslogs`: Queries groups, streams and events from Amazon Cloudwatch logs.
- `nodemon`: Watch files and automatically restart a node application when changes are detected.
- `gh-gist`: Work with GitHub Gists on the command line.
- `gdalbuildvrt`: Build Virtual Datasets from a list of existing datasets.
- `hexo`: A fast, simple & powerful blog framework.
- `gh-repo`: Work with GitHub repositories on the command line.
- `reflex`:  Run a command when files change
 Reflex is a small tool to watch a directory and rerun a command
 when certain files change. It's great for automatically running
 compile/lint/test tasks and for reloading your application when the
 code changes.


- `openssl-genpkey`: OpenSSL command to generate asymmetric key pairs.
- `dotnet-restore`: Restores the dependencies and tools of a .NET project.
- `aws-lambda`: CLI for AWS lambda.
- `gh-config`: Change configuration for GitHub cli.
- `aws-kinesis`: Official AWS CLI for Amazon Kinesis streaming data services.
- `amass-viz`: Visualize gathered information in a network graph.
- `ohdear-cli`: An unofficial Oh Dear CLI written with Laravel Zero.
- `dvc-dag`: Visualize the pipeline(s) defined in `dvc.yaml`.
- `git-cherry`: Find commits that have yet to be applied upstream.
- `dvc-checkout`: Checkout data files and directories from cache.
- `opusenc`: Convert WAV or FLAC audio to Opus.
- `syncthing`:  decentralized file synchronization
 Syncthing is an application that lets you synchronize your files across
 multiple devices. This means the creation, modification or deletion of files
 on one machine will automatically be replicated to your other devices.
 Syncthing does not upload your data to the cloud but exchanges your data
 across your machines as soon as they are online at the same time.
 .
 This package contains the main binary: syncthing.


- `gh-pr`: Manage GitHub pull requests from the command line.
- `jenv`: Command line tool to manage the "JAVA_HOME" environment variable.
- `carbon-now`: Create beautiful images of code.
- `kind`:  Kubernetes IN Docker - local clusters for testing Kubernetes (program)
 kind is a tool designed for running local Kubernetes clusters by utilizing
 Docker containers as nodes.
 .
 Primarily designed for testing Kubernetes, its flexibility makes it suitable
 for local development or integrating with Continuous Integration (CI)
 pipelines.


- `amass-track`: Track differences between enumerations of the same domain.
- `valac`:  C# like language for the GObject system
 Vala is a new programming language that aims to bring modern programming
 language features to GNOME developers without imposing any additional
 runtime requirements and without using a different ABI compared to
 applications and libraries written in C.
 .
 valac, the Vala compiler, is a self-hosting compiler that translates
 Vala source code into C source and header files.  It uses the GObject
 type system to create classes and interfaces declared in the Vala
 source code. This package also contains the vala-gen-introspect and
 vapigen binaries that will automatically generate Vala bindings.


- `dvc-config`: Low level command to manage custom configuration options for dvc repositories.
- `pass-otp`:  pass extension for managing one-time-password tokens
 An extension for the password manager pass that allows adding one-time-password
 (OTP) secrets, generating OTP codes, and displaying secret key URIs using the
 standard otpauth:// scheme.


- `httpry`:  HTTP logging and information retrieval tool
 httpry is a tool designed for displaying and logging HTTP traffic. It is not
 intended to perform analysis itself, but instead to capture, parse and/or
 log the traffic for later analysis. It can be run in real-time displaying
 the live traffic on the wire, or as a daemon process that logs to an output
 file. It is written to be as lightweight and flexible as possible, so that
 it can be easily adaptable to different applications. It does not display
 the raw HTTP data transferred, but instead focuses on parsing and displaying
 the request/response line along with associated header fields.
 .
 This package contains the httpry executable. Package httpry-daemon contains
 required init script for running httpry as a daemon. Scripts for parsing
 log files are provided by httpry-tools.


- `piactl`: The command line tool for Private Internet Access, a commercial VPN provider.
- `glab`:  commandline interface for gitlab instances
 GLab is an open source GitLab CLI tool bringing GitLab to your terminal next
 to where you are already working with git and your code without switching
 between windows and browser tabs. Work with issues, merge requests, watch
 running pipelines directly from your CLI among other features.
 .
 glab is available for repositories hosted on GitLab.com and self-managed
 GitLab instances. glab supports multiple authenticated GitLab instances and
 automatically detects the authenticated hostname from the remotes available
 in the working Git directory.


- `electron-packager`: A tool used to build Electron app executables for Windows, Linux and MacOS.
- `rspec`: Behavior-driven development testing framework written in Ruby to test Ruby code.
- `matlab`: Numerical computation environment by MathWorks.
- `openssl-x509`: OpenSSL command to manage X.509 certificates.
- `ant`:  Java based build tool like make
 Apache Ant is a Java library and command-line tool whose mission is to drive
 processes described in build files as targets and extension points dependent
 upon each other. The main known usage of Ant is the build of Java applications.
 Ant supplies a number of built-in tasks allowing to compile, assemble, test
 and run Java applications. Ant can also be used effectively to build non Java
 applications, for instance C or C++ applications. More generally, Ant can be
 used to pilot any type of process which can be described in terms of targets
 and tasks.
 .
 This package contains the scripts and the core tasks libraries.


- `kubectl-describe`: Show details of Kubernetes objects and resources.
- `topgrade`: Update all applications on the system.
- `phpcbf`: Fix violations detected by phpcs.
- `dfc`:  display file system usage using graph and colors
 dfc displays file system space usage using graphs and colors. In some ways, it
 is a modernized version of df as it is able to use colors, draw graphs and
 export its output to different formats such as CSV or HTML.


- `parquet-tools`: A tool to show, inspect and manipulate Parquet file.
- `openssl-dgst`: OpenSSL command to generate digest values and perform signature operations.
- `amass-db`: Interact with an Amass database.
- `lilypond`: Typeset music and/or produce MIDI from file.
- `security-checker`: Check if a PHP application uses dependencies with known security vulnerabilities.
- `aws-ec2`: CLI for AWS EC2.
- `dvc-add`: Add changed files to the index.
- `jcal`:  UNIX-cal-like tool to display Jalali calendar
 JCal is a UNIX-cal-like tool to display Jalali (Persian) calendar.


- `pest`: A PHP testing framework with a focus on simplicity.
- `cargo-build`: Compile a local package and all of its dependencies.
- `dvc`: Data Version Control: like `git` for data.
- `drupal-check`: Check Drupal PHP code for deprecations.
- `cargo-clippy`: A collection of lints to catch common mistakes and improve your Rust code.
- `ansible-doc`: Display information on modules installed in Ansible libraries.
- `r2e`: Forwards RSS feeds to an email address.
- `amass-intel`: Collect open source intel on an organisation like root domains and ASNs.
- `cargo-test`: Execute the unit and integration tests of a Rust package.
- `xmlto`:  XML-to-any converter
 xmlto is a front-end to an XSL toolchain. It chooses an appropriate
 stylesheet for the conversion you want and applies it using an external
 XSLT processor (currently, only xsltproc is supported). It also performs
 any necessary post-processing.
 .
 It supports converting from DocBook XML to DVI, XSL-FO, HTML and XHTML
 (one or multiple pages), epub, manual page, PDF, PostScript and plain
 text. It also supports converting from XSL-FO to DVI, PDF and PostScript.
 .
 DVI output requires dblatex or PassiveTeX. Other formats can be produced
 with any of the supported toolchains - dblatex, PassiveTeX or
 docbook-xsl/fop (but may require some extensions).


- `dcg`: Drupal code generator.
- `openconnect`:  open client for various network vendors SSL VPNs
 OpenConnect is an SSL VPN client initially created to support Cisco's
 AnyConnect SSL VPN. It has since been extended to support the Pulse Connect
 Secure VPN (formerly known as Juniper Network Connect or Junos Pulse), the Palo
 Alto Networks GlobalProtect SSL VPN, F5 Big-IP SSL VPN, Fortinet Fortigate SSL
 VPN and Array Networks AG SSL VPN.
 .
 A corresponding OpenConnect VPN server implementation can be found in the
 ocserv package.


- `docker-secret`: Manage Docker swarm secrets.
- `dvc-commit`: Record changes to DVC-tracked files in the project.
- `khal`:  Standards based CLI and terminal calendar program
 Khal is a standards based CLI and terminal calendar program,
 able to synchronize with CalDAV servers through vdirsyncer.
 .
 Features:
  - khal can read and write events/icalendars to vdir,
    so vdirsyncer can be used to synchronize calendars
    with a variety of other programs,
    for example CalDAV servers.
  - fast and easy way to add new events
  - ikhal (interactive khal) lets you browse and edit calendars and events


- `docker-rmi`: Remove one or more Docker images.
- `gitlab-runner`: CLI tool for managing GitLab runners.
- `ocamlopt`: The OCaml native code compiler.
- `nodenv`: A tool to manage NodeJS versions.
- `git-send-email`: Send a collection of patches as emails.
- `httpflow`: A command line utility to capture and dump HTTP streams.
- `cloudflared`: Command line tool to create a persistent connection to the Cloudflare network.
- `docker-start`: Start one or more stopped containers.
- `btm`:  customizable graphical process/system monitor for the terminal
 bottom (executable name btm)
 is a customizable graphical process/system monitor for the terminal,
 inspired by gtop, gotop, and htop.
 .
 By default, bottom is somewhat like a dashboard -
 a bunch of different widgets, all showing different things,
 and they all cram together to fit into one terminal.


- `adb-reverse`: Android Debug Bridge Reverse: reverse socket connections from an Android emulator instance or connected Android devices.
- `veracrypt`: Free and open source disk encryption software.
- `kjv`: The word of God available right on your desktop.
- `asciiart`:  command line tool to turn images into ASCII art
 This gem provides a command line utility to turn images into ASCII art. It can
 be used as an executable which may be called from the terminal as well as a
 library so that it can be used in other programs.


- `debootstrap`:  Bootstrap a basic Debian system
 debootstrap is used to create a Debian base system from scratch,
 without requiring the availability of dpkg or apt. It does this by
 downloading .deb files from a mirror site, and carefully unpacking them
 into a directory which can eventually be chrooted into.


- `i3`:  metapackage (i3 window manager, screen locker, menu, statusbar)
 This metapackage installs the i3 window manager (i3-wm), the i3lock screen
 locker, i3status (for system information) and suckless-tools (for dmenu).
 These are all the tools you need to use the i3 window manager efficiently.


- `x0vncserver`: TigerVNC Server for X displays.
- `cuyo`:  Tetris-like game with very impressive effects
 Cuyo, named after a Spanish relative adjective, shares
 with tetris that things fall down and how to navigate them.
 When enough "of the same type" come "together", they explode.
 The goal of each level is to blow special "stones" away, you
 start with. But what "of the same type" and "together" means,
 varies with the levels.


- `docker-stats`: Display a live stream of resource usage statistics for containers.
- `vela`: Command line tools for the Vela pipeline.
- `cronic`:  Bash script for wrapping cron jobs to prevent excess email sending
 Cronic is a small shim shell script for wrapping cron jobs so that cron only
 sends email when an error has occurred. Cronic defines an error as any
 non-trace error output or a non-zero result code.


- `blockout2`:  Tetris like game (3D-tetris)
 BlockOut II is a free adaptation of the original BlockOut
 DOS game edited by California Dreams in 1989. BlockOut II
 has the same features than the original game with few graphic
 improvements. The score calculation is also nearly similar to
 the original game. BlockOut II has been designed by an addicted
 player for addicted players. BlockOut II is an open source
 project available for both Windows and Linux.


- `resolveip`: Resolve hostnames to their IP addresses and vice versa.
- `btrfs-filesystem`: Manage btrfs filesystems.
- `wg`: Manage the configuration of WireGuard interfaces.
- `numactl`:  NUMA scheduling and memory placement tool
 numactl runs processes with a specific NUMA (Non-Uniform Memory
 Architecture) scheduling or memory placement policy.  In addition it
 can set persistent policy for shared memory segments or files.


- `btrfs-device`: Manage devices in a btrfs filesystem.
- `slapt-src`: A utility to automate building of slackbuilds.
- `btrfs-subvolume`: Manage btrfs subvolumes and snapshots.
- `rankmirrors`: Rank a list of Pacman mirrors by connection and opening speed.
- `kde-inhibit`: Inhibit various desktop functions while a command runs.
- `genfstab`: Generate output suitable for addition to an fstab file.
- `wg-quick`: Quickly set up WireGuard tunnels based on config files.
- `spi`: A meta package manager that handles both packages and slackbuilds.
- `pacstrap`: Install packages using Pacman to the specified new root directory.
- `btrfs-scrub`: Scrub btrfs filesystems to verify data integrity.
- `2to3`:  2to3 binary using python3
 2to3 is a Python program that reads Python 2.x source code and applies a
 series of fixers to transform it into valid Python 3.x code. The standard
 library contains a rich set of fixers that will handle almost all code. 2to3
 supporting library lib2to3 is, however, a flexible and generic library, so it
 is possible to write your own fixers for 2to3. lib2to3 could also be adapted
 to custom applications in which Python code needs to be edited automatically.
 .
 This package is a dependency package, which depends on Debian's default
 Python 3 2to3 version (currently v3.12).


- `gh-completion`: Generate shell completion scripts for GitHub CLI commands.
- `topydo`:  advanced todo.txt terminal utility for managing tasks
 The Todo.txt project defines a format for supporting context-rich tasking in a
 plain text file. It supports an ecosystem of tools which allow working with
 tasks across hosts and operating systems.
 .
 This package installs a more advanced version of the command-line tool for
 working with todo.txt tasking files.


- `jetifier`: Jetifier AndroidX transition tool in npm format, with a react-native compatible style.
- `lambo-new`: A super-powered `laravel new` for Laravel and Valet.
- `phpdox`: A PHP documentation generator.
- `tmpmail`: A temporary email right from your terminal written in POSIX sh.
- `exenv`: A tool to easily install Elixir versions and manage application environments.
- `gh-environment`: Display help about environment variables for the GitHub CLI command.
- `psalm`: A static analysis tool for finding errors in PHP applications.
- `php-coveralls`: A PHP client for Coveralls.
- `watson`: A wonderful CLI to track your time.
- `conan`: The open source, decentralized and multi-platform package manager to create and share all your native binaries.
- `pip-install`: Install Python packages.
- `gobuster`:  Directory/file & DNS busting tool written in Go
 Gobuster is a tool used to brute-force: URIs (directories and files) in
 web sites, DNS subdomains (with wildcard support), Virtual Host names
 on target web servers, Open Amazon S3 buckets, Open Google Cloud buckets
 and TFTP servers.
 .
 Gobuster is useful for pentesters, ethical hackers and forensics experts.
 It also can be used for security tests.


- `openssl-prime`: OpenSSL command to compute prime numbers.
- `ghcup`: Haskell toolchain installer.
- `gh-help`: Display help about the GitHub CLI command.
- `etcd`: A distributed, reliable key-value store for the most critical data of a distributed system.
- `pretty-bytes`: Convert bytes to a human readable string.
- `gitmoji`: An interactive command line tool for using emojis on commits.
- `conan-frogarian`: Displays the conan frogarian.
- `brotli`:  lossless compression algorithm and format (command line utility)
 Brotli is a generic-purpose lossless compression algorithm
 that compresses data using a combination of a modern variant
 of the LZ77 algorithm, Huffman coding and 2nd order context modeling,
 with a compression ratio comparable to the best currently available
 general-purpose compression methods. It is similar in speed with
 deflate but offers more dense compression.
 .
 This package installs a command line utility.


- `gh-alias`: Manage GitHub CLI command aliases from the command line.
- `dust`: Dust gives an instant overview of which directories are using disk space.
- `esbuild`:  extremely fast JavaScript bundler and minifier (program)
 esbuild is a JavaScript bundler and minifier.  It packages up
 JavaScript and TypeScript code for distribution on the web.
 .
 Why build another JavaScript build tool?  The current build tools for the web
 are at least an order of magnitude slower than they should be.  It is hoped
 that this project serves as an "existence proof" that JavaScript tooling
 can be much, much faster.
 .
 This package contains the esbuild binary.


- `gh-secret`: Manage GitHub secrets from the command line.
- `nix-shell`: Start an interactive shell based on a Nix expression.
- `docker-container`: Manage Docker containers.
- `composer-require-checker`: A CLI tool to analyse Composer dependencies for soft dependencies.
- `fastlane`: Build and release mobile applications from the command-line.
- `etcdctl`: CLI interface for interacting with `etcd`, a highly-available key-value pair store.
- `clj`: Clojure tool to start a REPL or invoke a specific function with data.
- `react-native`: A framework for building native apps with React.
- `yq`:  Command-line YAML processor - jq wrapper for YAML documents
 yq transcodes YAML documents to JSON and passes them to jq. The
 package also includes xq, which transcodes XML to JSON using
 xmltodict and pipes it to jq, and tomlq, which uses the toml library
 to transcode TOML to JSON, then pipes it to jq


- `git-bugreport`: Captures debug information from the system and user, generating a text file to aid in the reporting of a bug in Git.
- `doctum`: A PHP API documentation generator.
- `minifab`: Utility tool that automates the setup and deployment of Hyperledger Fabric networks.
- `siege`:  HTTP regression testing and benchmarking utility
 Siege is an regression test and benchmark utility. It can stress test a single
 URL with a user defined number of simulated users, or it can read many URLs
 into memory and stress them simultaneously. The program reports the total
 number of hits recorded, bytes transferred, response time, concurrency, and
 return status. Siege supports HTTP/1.0 and 1.1 protocols, the GET and POST
 directives, cookies, transaction logging, and basic authentication. Its
 features are configurable on a per user basis.
 .
 Note: this package contains siege with HTTPS support turned on, thus it
 obsoletes siege-ssl package now.


- `gh-reference`: Display a reference about the GitHub CLI command.
- `from`: Prints mail header lines from the current user's mailbox.
- `zmv`: Move or rename files matching a specified extended glob pattern.
- `lmms`:  Linux Multimedia Studio
 LMMS aims to be a free alternative to popular (but commercial and closed-
 source) programs like FruityLoops, Cubase and Logic giving you the ability of
 producing music with your computer by creating cool loops, synthesizing and
 mixing sounds, arranging samples, having more fun with your MIDI-keyboard
 and much more...
 .
 LMMS combines the features of a tracker-/sequencer-program (pattern-/channel-/
 sample-/song-/effect-management) and those of powerful synthesizers and
 samplers in a modern, user-friendly and easy to use graphical user-interface.


- `takeout`: A Docker-based development-only dependency manager.
- `mixxx`:  Digital Disc Jockey Interface
 Mixxx is a digital DJ system, where Wave, Ogg, FLAC and MP3 files can be
 mixed on a computer for use in live performances. Filters, crossfader, and
 speed control are provided. Mixxx can sync the 2 streams automatically, using
 an algorithm to detect the beat.
 .
 Mixxx works with Jack or OSS, can be controlled from the GUI or from external
 controllers, including MIDI devices and joysticks, and supports skins.


- `mupdf`:  lightweight PDF viewer
 MuPDF is a lightweight PDF viewer and toolkit written in portable C.
 It also reads XPS, OpenXPS and ePub documents.
 .
 The renderer in MuPDF is tailored for high quality anti-aliased graphics.
 It renders text with metrics and spacing accurate to within fractions of a
 pixel for the highest fidelity in reproducing the look of a printed page
 on screen.


- `git-commit-graph`: Write and verify Git commit-graph files.
- `tuir`: A text user-interface (TUI) to view and interact with Reddit from your terminal.
- `gh-api`: Makes authenticated HTTP requests to the GitHub API and prints the response.
- `promtool`:  tooling for the Prometheus monitoring system
 promtool is a command-line utility for managing and interacting with a
 Prometheus monitoring system and its configuration / rules.


- `react-native-start`: Command line tools to start the React Native server.
- `svn-changelist`: Associate a changelist with a set of files.
- `lambo`: A super-powered `laravel new` for Laravel and Valet.
- `flow`: A static type checker for JavaScript.
- `speedtest`: Test internet bandwidth using https://www.speedtest.net.
- `pacman-files`: Arch Linux package manager utility.
- `pacman-mirrors`: Generate a pacman mirrorlist for Manjaro Linux.
- `pacman-deptest`: Check each dependency specified and return a list of dependencies that are not currently satisfied on the system.
- `kwriteconfig5`: Write KConfig entries for KDE Plasma.
- `pacman-upgrade`: Arch Linux package manager utility.
- `pacman-query`: Arch Linux package manager utility.
- `tuxi`: A CLI tool that scrapes Google search results and SERPs that provides instant and concise answers.
- `balooctl`: File indexing and searching framework for KDE Plasma.
- `pacman-remove`: Arch Linux package manager utility.
- `kreadconfig5`: Read KConfig entries for KDE Plasma.
- `pacman-database`: Operate on the Arch Linux package database.
- `pacman-sync`: Arch Linux package manager utility.
- `mkinitcpio`: Generates initial ramdisk environments for booting the Linux kernel based on the specified preset(s).
- `arch-chroot`: Enhanced `chroot` command to help in the Arch Linux installation process.
- `wol`: Client for sending Wake-on-LAN magic packets.
- `exrex`: Generate all/random matching strings for a regular expression.
- `bundletool-dump`: Command-line tool to manipulate Android Application Bundles.
- `tlmgr`: Manages packages and configuration options of an existing TeX Live installation.
- `betty`: Use natural language to execute commands.
- `pueue`: Pueue is a command-line task management tool for sequential and parallel execution of long-running tasks.
- `gh-ssh-key`: Manage GitHub SSH keys from the command line.
- `tex`: Compile a DVI document from TeX source files.
- `vercel`: Deploy and manage your Vercel deployments.
- `texdoc`: Search for appropriate documentation for (La)TeX commands or packages.
- `pre-commit`:  Git pre-commit hook framework
 A framework for managing and maintaining multi-language Git pre-commit hooks.


- `latex`: Compile a DVI document from LaTeX source files.
- `speed-test`: Test your internet connection speed and ping using speedtest.net from the CLI.
- `next`: React framework that uses server-side rendering for building optimized web applications.
- `mscore`: This command is an alias of `musescore`.
- `theharvester`:  tool for gathering e-mail accounts and subdomain names from public sources
 The package contains a tool for gathering subdomain names, e-mail addresses,
 virtual hosts, open ports/ banners, and employee names from different public
 sources (search engines, pgp key servers).


- `fast`: Test your download and upload speed using fast.com.
- `texliveonfly`: Downloads missing TeX Live packages while compiling `.tex` files.
- `pngcheck`:  print info and check PNG, JNG and MNG files
 pngcheck verifies the integrity of PNG, JNG and MNG files (by checking the
 internal 32-bit CRCs or checksums) and optionally dumps almost all of the
 chunk-level information in the image in human-readable form. For example, it
 can be used to print the basic stats about an image (dimensions, bit depth,
 etc.); to list the color and transparency info in its palette; or to extract
 the embedded text annotations. All PNG and JNG chunks are supported, plus
 almost all MNG chunks (everything but PAST, DISC, tERm, DROP, DBYK, and
 ORDR). This is a command-line program with batch capabilities (e.g.,
 pngcheck *.png).
 .
 Also includes pngsplit which can split a PNG, MNG or JNG file into
 individual, numbered chunks.


- `musescore`:  cross-platform multi-lingual music composition and notation, v2
 MuseScore is an Open Source (GNU GPL) music notation software that runs
 on all platforms supported by Qt5 (GNU/Linux, MacOS X, Windows), and is
 available in over forty different languages. It features an easy to use
 WYSIWYG editor with audio score playback for results that look and sound
 beautiful, rivaling commercial offerings like Finale and Sibelius.
 .
 This package provides MuseScore 2. You can install multiple versions of
 MuseScore in parallel, and upstream recommends doing so, because each
 major version has a new, incompatible, layout engine, and changing old
 scores without relayouting them fully with the new version can only be
 done by the old version. Install the musescore3 package for MuseScore 3
 and expect a musescore4 package to show up in Debian bookworm.
 .
 Create, play back and print sheet music for free. Features include:
  - easy-to-use and customisable interface
  - albums combining multiple scores
  - unlimited score length
  - unlimited number of staves per system
  - up to four independent voices per staff
  - score creation wizard and templates
  - easy and fast note entry with a (PC) keyboard, the mouse, including
    an on-screen virtual (piano) keyboard, or MIDI (step-time, real-time)
  - continuous view: focus on the content, scrolling by as an endless
    ribbon, undistracted by line breaks or page breaks; switch to page
    view to polish up for printing
  - automatic part extraction and transposition; advanced transposition:
    transpose a selected passage to any key, or by any interval — or
    even transpose diatonically within the same key
  - repeats, including segnos, codas, measure repeats, advanced repeats
  - dynamics, articulations and other expression markings
  - playback support for almost all notation elements
  - custom text markings
  - style rules that apply to the whole score at once
  - lyrics
  - chord symbols
  - Jazz notation, including lead sheets and slash notation
  - swing and shuffle playback
  - integrated sequencer and two software synthesisers (FluidSynth for
    SF2/SF3, Zerberus for SFZ), which also can use third-party soundfonts
  - mixer for instrument levels and effects
  - mixing and panning for individual parts
  - percussion notation
  - early music notation
  - cross-staff beaming
  - import of graphics
  - custom key signatures
  - additive time signatures
  - user-defined score styles
  - and much more…
 .
 Choir features:
  - powerful lyrics copy and paste tools
  - implode/explode: combine up to four voices on one staff,
    then separate to individual staves
  - hide empty vocal staves, such as in a piano intro
  - figured bass for historical notation
  - smart lyrics: unlimited verses, with notes and staves automatically
    spaced, and verse numbers automatically aligned
  - voice leading checker: download the Check Harmony Rules proofreading
    plugin to check for errors in your part writing, according to
    standard rules
  - part mixer: mute, solo, or change volume of staves to learn
    individual lines — settings even apply to MP3 export
 .
 Piano features:
  - support for solo + piano (add small staff with different instrument)
  - support for cadenzas (smaller notes and variable length measures)
  - complete notation: pedaling, fingering, cross-staff beaming — you
    name it; everything needed to write piano sheet music is here
 .
 Guitar features:
  - bends, fingerings, and other common guitar notations supported
  - add/remove linked staves any time; enter notes on either standard
    (pitched five-line) or TAB staff
  - percussion/drumset also included
  - templates include guitar, tablature, guitar+tablature, rock/pop band
  - complete tablature: multiple tab styles available — from note symbols
    outside the staff to upside-down strings — and linked standard/tab
    staff pairs
  - Guitar Pro import: MuseScore can now open files from Guitar Pro, so
    you can easily migrate over. Import filters are improving with every
    release; GP3, GP4, GP5, GP6, GTP, GPX are currently supported.
  - Fretboard diagrams: 21 default chords for every key, and a powerful
    editor to create your own — with barre, fret position, and any number
    of strings
  - beyond guitar: banjo, mandolin, ukulele, oud; custom string tunings;
    even historical lute tablature: MuseScore does them all.
 .
 Orchestral features:
  - templates for common instrumentations
  - custom linked parts (e.g. create choral score from orchestra+chorus):
    any change you make to the content of any part is immediately
    reflected in the full score — and vice versa
  - powerful style controls: edit the formatting of parts and score
    independently — or apply the same style to all parts with one click
  - one-click transposition: instantly switch between transposed and
    concert pitch: sounding pitches stay the same while the written notes
    change
 .
 Jazz features:
  - templates for Jazz Lead Sheet, Big Band and Jazz Combo
  - real “handwritten” Book-style jazz font for text and chord symbols
  - formatting tools include adding line breaks every X measures
  - instantly switch between transposed and concert pitch
  - intelligent chord symbol: chord names are automatically formatted
    when you finish typing — plus, they transpose with the notes
  - easy slashes: commands to fill bars with slashes — and to turn notes
    into rhythmic slashes, and even accent notation above the staff
 .
 Marching ensembles features (needs the MDL extension):
  - marching band, indoor percussion, front ensemble, drumline and drum
    corps (even G bugles); no setup or configuration — select a template,
    start writing
 .
 Band features:
  - diverse templates: concert band, brass band, marching band, battery
    and pit percussion — ready out-of-the-box (plus big band for jazz)
  - custom linked parts: you can even keep a drumline score linked to a
    full marching band score and to individual percussion parts
 .
 Most elements in MuseScore are laid out automatically on a “virtual note
 sheet”, with a near professional-quality layout engine, but can also be
 positioned manually, giving you total control of every score element’s
 position. The capabilities of MuseScore can be extended via plugins and
 extensions, and the growing repository on musescore.org contains many
 plugins submitted by users and an active development team.
 .
 MuseScore includes a set of sounds that reproduce common instruments (as
 defined by General MIDI) without taking up a lot of disk space or memory
 providing full orchestral and band sounds (with the Drumline extension
 installed this includes marching percussion). The general (non-Drumline)
 sound font is available as musescore-general-soundfont Debian package,
 if you wish to reuse it with other synthesisers.) You can also load any
 sound font you prefer for a wider variety of sounds or for more realism.
 .
 MuseScore can import and export MIDI and MusicXML files, and it can also
 import from Capella and several other programs. MuseScore can export to
 PDF, PNG, and other graphic formats, to WAV and other audio formats such
 as OGG Vorbis and MP3, or to GNU Lilypond for an alternative layout and
 print option.
 .
 MuseScore can upload scores to musescore.com, a score sharing site, and
 send scrolling sheet music videos to YouTube. In addition to the desktop
 software, you can rehearse “on the go” with MuseScore mobile apps (which
 do not support note entry, but many advanced playback functions). Note
 that all of these are commercial or otherwise non-free offers optionally
 integrated with, but not part of, the Free notation program. Scrolling
 video scores feature the notes highlighted in the score as they sound —
 and highlighted on a virtual piano keyboard below.


- `vectorize-pixelart`: Convert PNG pixel art graphics to SVG/EPS vector images.
- `pdftex`: Compile a PDF document from TeX source files.
- `virt-manager`:  desktop application for managing virtual machines
 The virt-manager application is a desktop user interface for managing virtual
 machines through libvirt. It primarily targets KVM VMs, but also manages Xen
 and LXC (Linux containers). It presents a summary view of running domains,
 their live performance & resource utilization statistics. Wizards enable the
 creation of new domains, and configuration & adjustment of a domain's resource
 allocation & virtual hardware. An embedded VNC and SPICE client viewer
 presents a full graphical console to the guest domain.


- `pkgfile`: Tool for searching files from packages in the official repositories on arch-based systems.
- `coredumpctl`: Retrieve and process saved core dumps and metadata.
- `mkfs.btrfs`: Create a btrfs filesystem.
- `eyed3`:  Display and manipulate id3-tags on the command-line
 A command-line editor to add/edit/remove ID3-tags on mp3 files.
 It supports version 1.0,1.1,2.3 and 2.4 of the ID3 standard.
 Additionally it displays several information about the file
 such as length and bitrate from an MP3 file.


- `docker-cp`: Copy files or directories between host and container filesystems.
- `nbtscan`:  scan networks searching for NetBIOS information
 NBTscan is a program for scanning IP networks for NetBIOS name information.
 It sends NetBIOS status query to each address in supplied range and lists
 received information in human readable form. For each responded host it
 lists IP address, NetBIOS computer name, logged-in user name and MAC address
 (such as Ethernet).
 .
 This program is useful for security checks, network discovery and forensics
 investigations.


- `ncc`: Compile a Node.js application into a single file.
- `pio-boards`: List pre-configured embedded boards available in PlatformIO.
- `gimp`:  GNU Image Manipulation Program
 GIMP is an advanced picture editor. You can use it to edit, enhance, and
 retouch photos and scans, create drawings, and make your own images.
 It has a large collection of professional-level editing tools and
 filters, similar to the ones you might find in Photoshop. Numerous
 fine-control settings and features like layers, paths, masks, and
 scripting give you total control over your images.
 .
 Many image file formats are supported, including JPEG, Photoshop (.psd),
 and Paint Shop Pro (.psp) files. It can also be used to scan and print
 photos.
 .
 To open files remotely (like over HTTP), install the gvfs-backends
 package.
 .
 To use a MIDI device (like a musical keyboard) as an input controller in GIMP,
 install libasound2 and read the how-to at /usr/share/doc/gimp/README.MIDI


- `dolt-blame`: Displays commit information for each row of a Dolt table.
- `bundletool-validate`: Command-line tool to manipulate Android Application Bundles.
- `git-maintenance`: Run tasks to optimize Git repository data.
- `mysqld`: Start the MySQL database server.
- `nload`:  realtime console network usage monitor
 Nload is a console application which monitors network traffic and bandwidth
 usage in real time. It displays the total amount of data that has been
 transferred over a network device since the last reboot, the current bandwidth
 usage, and the minimum, maximum, and average bandwidth usage measured
 since it started.
 .
 If the user wants, it is also able to display two bars, similar to progress
 bars, presenting the current load graphically. Support for displaying several
 devices simultaneously is included.


- `arduino-builder`: A command line tool for compiling arduino sketches.
- `codespell`:  Find and fix common misspellings in text files
 codespell is designed to find and fix common misspellings in text files.
 It is designed primarily for checking misspelled words in source code,
 but it can be used with other files as well.


- `bootctl`: Control EFI firmware boot settings and manage boot loader.
- `bundletool`: Command-line tool to manipulate Android Application Bundles.
- `pio`: Development environment for embedded boards.
- `yapf`: Python style guide checker.
- `bvnc`: A GUI tool for browsing for SSH/VNC servers on the local network.
- `dolt`: Dolt is a SQL database that you can fork, clone, branch, merge, push and pull just like a Git repository.
- `dolt-checkout`: Checkout the work tree or tables to a specific branch or commit.
- `pio-account`: Manage your PlatformIO account in the command line.
- `dolt-branch`: Manage Dolt branches.
- `zeek`:  passive network traffic analyzer
 Zeek is primarily a security monitor that inspects all traffic on a link in
 depth for signs of suspicious activity. More generally, however, Zeek
 supports a wide range of traffic analysis tasks even outside of the
 security domain, including performance measurements and helping with
 trouble-shooting.
 .
 Zeek comes with built-in functionality for a range of analysis and
 detection tasks, including detecting malware by interfacing to external
 registries, reporting vulnerable versions of software seen on the network,
 identifying popular web applications, detecting SSH brute-forcing,
 validating SSL certificate chains, among others.


- `pgbench`: Run a benchmark test on PostgreSQL.
- `bshell`: A GUI tool for browsing for SSH/VNC servers on the local network.
- `bssh`: A GUI tool for browsing for SSH/VNC servers on the local network.
- `dolt-add`: Add the contents of a table to the list of Dolt staged tables.
- `platformio`: This command is an alias of `pio`.
- `shift`: Bash built-in command that shifts the arguments passed to the calling function or script by a specified number of places.
- `tldr-lint`: Lint and format `tldr` pages.
- `aurman`: An Arch Linux utility to build and install packages from the Arch User Repository.
- `lvdisplay`: Display information about Logical Volume Manager (LVM) logical volumes.
- `pio-home`: Launch the PlatformIO Home web server.
- `pio-check`: Perform a static analysis check on a PlatformIO project.
- `pueue-add`: Enqueue a task for execution.
- `pueue-pause`: Pause running tasks or groups.
- `pio-upgrade`: Update PlatformIO to the latest version.
- `pueue-restart`: Restart tasks.
- `pio-settings`: View and modify PlatformIO settings.
- `pueue-enqueue`: Enqueue stashed tasks.
- `inkmake`: GNU Makefile-style SVG exporting using Inkscape's backend.
- `pio-team`: Manage PlatformIO teams.
- `pio-project`: Tool to manage PlatformIO projects.
- `git-for-each-repo`: Run a Git command on a list of repositories.
- `pueue-kill`: Kill running tasks or whole groups.
- `hakyll-init`: Generate a new Hakyll sample blog.
- `pio-org`: Manage PlatformIO organizations and their owners.
- `nms`: Command line tool that recreates the famous data decryption effect seen in the 1992 movie Sneakers from stdin.
- `pueue-completions`: Generates shell completion files for bash, elvish, fish, powershell, and zsh.
- `pueue-parallel`: Set the amount of allowed parallel tasks.
- `pueue-help`: Display help for subcommands.
- `pueue-clean`: Remove all finished tasks from the list and clear logs.
- `pueue-remove`: Remove tasks from the list. Running or paused tasks need to be killed first.
- `pueue-follow`: Follow the output of a currently running task.
- `pueue-edit`: Edit the command or path of a stashed or queued task.
- `pio-update`: Update installed PlatformIO Core packages, development platforms and global libraries.
- `pueue-log`: Display the log output of 1 or more tasks.
- `pueue-switch`: Switches the queue position of two enqueued or stashed commands.
- `pio-system`: Miscellaneous system commands for PlatformIO.
- `mutagen`: Real-time file synchronization and network forwarding tool.
- `pueue-stash`: Stash tasks to prevent them starting automatically.
- `dolt-commit`: Commit staged changes to tables.
- `pueue-status`: Display the current status of all tasks.
- `pueue-send`: Send input to a task.
- `pueue-start`: Resume operation of specific tasks or groups of tasks.
- `pueue-group`: Display, add or remove groups.
- `pueue-reset`: Kill everything and reset.
- `pio-access`: Set the access level on published resources (packages) in the registry.
- `pueue-shutdown`: Remotely shut down the daemon.
- `cointop`: coin tracking for hackers
- `nextcloudcmd`: synchronize Nextcloud files to client machines
- `compsize`: Calculate the compression ratio of a set of files on a btrfs filesystem.
- `dex`:  generate and execute Application type .desktop files
 DesktopEntry eXecution implements the Freedesktop.org autostart
 specification, independent of any desktop or window manager environment.
 Applications may be filtered based on the Desktop Environment advertised
 in the .desktop file.
 .
 dex can also create a minimal .desktop file for a specified program.


- `homectl`: Create, remove, change or inspect home directories using the systemd-homed service.
- `sic`:  simple irc client (sic)
 sic is an extremely fast, small and simple irc client. It reads commands from
 standard input and prints all server output to standard output. It also
 multiplexes all channel traffic into one output. That way you don't have to
 switch different channel buffers. So that's actually a feature.


- `flashrom`:  Identify, read, write, erase, and verify BIOS/ROM/flash chips
 flashrom is a tool for identifying, reading, writing, verifying and erasing
 flash chips. It's often used to flash BIOS/EFI/coreboot/firmware/optionROM
 images in-system using a supported mainboard, but it also supports flashing of
 network cards (NICs), SATA controller cards, and other external devices which
 can program flash chips.
 .
 It supports a wide range of DIP32, PLCC32, DIP8, SO8/SOIC8, TSOP32/40/48,
 and BGA chips, which use various protocols such as LPC, FWH, parallel
 flash, or SPI.
 .
 The tool can be used to flash BIOS/firmware images for example -- be it
 proprietary BIOS images or coreboot (previously known as LinuxBIOS) images.
 .
 It can also be used to read the current existing BIOS/firmware from a
 flash chip.
 .
 Currently supported programmers include:
 .
   * internal (for in-system flashing in the mainboard)
   * dummy (virtual programmer for testing flashrom)
   * nic3com (for flash ROMs on 3COM network cards)
   * nicrealtek (for flash ROMs on Realtek and SMC 1211 network cards)
   * nicnatsemi (for flash ROMs on National Semiconductor DP838* network cards)
   * nicintel (for parallel flash ROMs on Intel 10/100Mbit network cards)
   * gfxnvidia (for flash ROMs on NVIDIA graphics cards)
   * drkaiser (for flash ROMs on Dr. Kaiser PC-Waechter PCI cards)
   * satasii (for flash ROMs on Silicon Image SATA/IDE controllers)
   * satamv (for flash ROMs on Marvell SATA controllers)
   * atahpt (for flash ROMs on Highpoint ATA/RAID controllers)
   * atavia (for flash ROMs on VIA VT6421A SATA controllers)
   * atapromise (for flash ROMs on Promise PDC2026x ATA/RAID controllers)
   * it8212 (for flash ROMs on ITE IT8212F ATA/RAID controller)
   * ft2232_spi (for SPI flash ROMs attached to an FT2232/FT4232H/FT232H family
     based USB SPI programmer), including the DLP Design DLP-USB1232H,
     FTDI FT2232H Mini-Module, FTDI FT4232H Mini-Module, openbiosprog-spi,
     Amontec JTAGkey/JTAGkey-tiny/JTAGkey-2, Dangerous Prototypes Bus Blaster,
     Olimex ARM-USB-TINY/-H, Olimex ARM-USB-OCD/-H, TIAO/DIYGADGET USB
     Multi-Protocol Adapter (TUMPA), TUMPA Lite, GOEPEL PicoTAP,
     Google Servo v1/v2, and FIC OpenMoko Neo1973 Debug board.
   * serprog (for flash ROMs attached to a programmer speaking serprog),
     including AVR flasher by Urja Rannikko, AVR flasher by eightdot,
     Arduino Mega flasher by fritz, InSystemFlasher by Juhana Helovuo,
     and atmegaXXu2-flasher by Stefan Tauner.
   * buspirate_spi (for SPI flash ROMs attached to a Bus Pirate)
   * dediprog (for SPI flash ROMs attached to a Dediprog SF100)
   * rayer_spi (for SPI flash ROMs attached to a RayeR parport based programmer)
   * pony_spi (for SPI flash ROMs attached to a SI-Prog serial port
     bitbanging adapter)
   * nicintel_spi (for SPI flash ROMs on Intel Gigabit network cards)
   * ogp_spi (for SPI flash ROMs on Open Graphics Project graphics card)
   * linux_spi (for SPI flash ROMs accessible via /dev/spidevX.Y on Linux)
   * usbblaster_spi (for SPI flash ROMs attached to an Altera USB-Blaster)
   * nicintel_eeprom (for SPI EEPROMs on Intel Gigabit network cards)
   * mstarddc_spi (for SPI flash ROMs accessible through DDC in MSTAR-equipped
     displays)
   * pickit2_spi (for SPI flash ROMs accessible via Microchip PICkit2)
   * ch341a_spi (for SPI flash ROMs attached to WCH CH341A)


- `rusnapshot`: BTRFS snapshotting utility written in Rust.
- `archinstall`: Guided Arch Linux installer with a twist.
- `spectre-meltdown-checker`:  Spectre & Meltdown vulnerability/mitigation checker
 A simple shell script to tell if your Linux installation is vulnerable
 against the 3 "speculative execution" CVEs that were made public early 2018.


- `nautilus`:  file manager and graphical shell for GNOME
 Nautilus is the official file manager for the GNOME desktop. It allows
 one to browse directories, preview files and launch applications
 associated with them. It is also responsible for handling the icons on
 the GNOME desktop. It works on local and remote filesystems.
 .
 Several icon themes and components for viewing different kinds of files
 are available in separate packages.


- `pio-lib`: Manage PlatformIO libraries.
- `openttd`: Open source clone of the Microprose game "Transport Tycoon Deluxe".
- `peludna-prognoza`: Fetch pollen measurement data for Croatian cities from your terminal using Pliva's allergies data API.
- `diskonaut`: Terminal disk space navigator, written in Rust.
- `vladimyr`: Dario Vladović's personal CLI.
- `pio-package`: Manage packages in the registry.
- `dcode`: Recursively detect and decode strings, supporting hex, decimal, binary, base64, URL, FromChar encodings, Caesar ciphers, and MD5, SHA1, and SHA2 hashes.
- `rails-destroy`: Destroy Rails resources.
- `gh-pr-merge`: Merge GitHub pull requests.
- `autopep8`: Format Python code according to the PEP 8 style guide.
- `gh-workflow`: List, view, and run GitHub Actions workflows.
- `pio-device`: Manage and monitor PlatformIO devices.
- `sbcl`:  Common Lisp compiler and development system
 SBCL is a development environment for the ANSI Common Lisp language.
 It provides a native-code compiler and an integrated debugger, as well
 as all the features in the ANSI specification.
 .
 SBCL also contains other extensions to the ANSI specification, including
 a foreign-function interface, a pseudo-server API, user-extensible
 stream functionality, a Meta-Object Protocol, and an ability to run
 external processes.
 .
 To browse SBCL source definitions with development environments,
 install the sbcl-source package. For documentation on SBCL's usage
 and internals, the package sbcl-doc is provided.


- `stormlock`: Centralized locking system.
- `plesk`: Plesk hosting control panel CLI interface.
- `sindresorhus`: Sindre Sorhus's personal CLI.
- `packtpub`: Download freely offered books from packtpub.com.
- `dolt-config`: Read and write local (per repository) and global (per user) Dolt configuration variables.
- `ansible-inventory`: Display or dump an Ansible inventory.
- `xxh`: Bring your shell with all of your customizations through SSH sessions.
- `histexpand`: Reuse and expand the shell history in `sh`, `bash`, `zsh`, `rbash` and `ksh`.
- `gh-run`: View, run and watch recent GitHub Actions workflow runs.
- `docker-image`: Manage Docker images.
- `espanso`: Cross-platform Text Expander written in Rust.
- `xonsh`:  Python-powered, cross-platform, Unix-gazing shell
 Xonsh is a Python-ish shell language and command prompt. Unlike other shells,
 xonsh is based on Python, with additional syntax added that makes calling
 subprocess commands, manipulating the environment, and dealing with the file
 system easy. Xonsh supports all normal Python constructs and a subset of
 those available in bash.


- `pio-platform`: Manage PlatformIO development platforms.
- `fakedata`: Generate fake data using a large variety of generators.
- `dconf-write`: Write a value to a dconf database path.
- `boltctl`: Control thunderbolt devices.
- `flatpak-builder`:  Flatpak application building helper
 Flatpak installs, manages and runs sandboxed desktop application bundles.
 See the flatpak package for a more comprehensive description.
 .
 flatpak-builder is a tool that makes it easy to build applications and their
 dependencies by automating the configure && make && make install steps.


- `ntpq`: Query the Network Time Protocol (NTP) daemon.
- `anbox`: Run Android applications on any GNU/Linux operating system.
- `sfill`: Securely overwrite the free space and inodes of the partition where the specified directory resides.
- `uuid`:  Universally Unique Identifier Command-Line Tool
 OSSP uuid is a C API and corresponding CLI program for the generation
 and analysis of DCE 1.1 and, IETF RFC-9562- compliant Universally Unique
 Identifiers (UUIDs). It supports variant 1 UUIDs of versions:
   1 (time and node),
   3 (name (namespace+data), MD5),
   4 (random),
   5 (name (namespace+data), SHA-1),
   6 (time and node with improved locality),
   7 (UNIX time, random data).
 Additional API bindings are provided for C++98 (deprecated) and Perl:5.
 Optional backward compatibility exists for the ISO-C DCE-1.1
 and Perl Data::UUID APIs.
 .
 UUIDs are 128 bit numbers which are intended to have a high likelihood
 of uniqueness over space and time and are computationally difficult
 to guess. They are globally unique identifiers which can be locally
 generated without contacting a global registration authority. UUIDs
 are intended as unique identifiers for both mass tagging objects
 with an extremely short lifetime and to reliably identifying very
 persistent objects across a network.
 .
 This package contains the Universally Unique Identifier Command-Line Tool.


- `chronyc`: Query the Chrony NTP daemon.
- `genid`: Generate IDs, such as snowflakes, UUIDs, and a new GAID.
- `qjoypad`:  map gamepad/joystick events to mouse/keyboard event
 QJoyPad takes input from a gamepad or joystick and translates it into
 key strokes or mouse actions, letting you control any X-Windows program
 with your game controller.  This lets you play all those games that for
 some reason don't have joystick support with your joystick.


- `dolphin`:  file manager
 Dolphin is KDE's file manager that lets you navigate and browse the contents
 of your hard drives, USB sticks, SD cards, and more. Creating, moving, or
 deleting files and folders is simple and fast.
 .
 Features include:
   Customisable sidebars
   "Breadcrumb" navigation
   View properties remembered for each folder
   Split views
   Integrated terminal
   Network transparency
   Undo/redo functionality
   Ratings, comments, and tags


- `openvpn3`: OpenVPN 3 Linux client.
- `dconf`: Simple tool for manipulating dconf databases.
- `rolldice`:  virtual dice roller
 rolldice is a virtual dice roller that takes a string on the command
 line in the format  of some fantasy role playing games like Advanced
 Dungeons & Dragons [1] and returns the result of the dice rolls.
 .
 [1] Advanced Dungeons & Dragons is a registered trademark of TSR, Inc.


- `kdocker`:  lets you dock any application into the system tray
 KDocker will help you dock any application into the system tray.
 This means you can dock openoffice, xmms, firefox, thunderbird, anything!
 Just point and click. Works for all NET WM compliant window managers - that
 includes KDE, GNOME, Xfce, Fluxbox and many more.


- `lxterminal`:  LXDE terminal emulator
 LXTerminal is a VTE-based terminal emulator for the Lightweight X11 Desktop
 Environment (LXDE).
 .
 It supports multiple tabs and has only minimal dependencies thus being
 completely desktop-independent. In order to reduce memory usage and increase
 the performance, all instances of the terminal are sharing a single process.


- `screenkey`:  screencast tool to display your keystrokes
 Screenkey is a screencast tool to display your keys inspired
 by Screenflick for Mac OS and based initially on key-mon project.
 .
 It’s useful to create screencasts and is also a powerful teaching tool.


- `pdfjam`: Shell frontend for the LaTeX pdfpages package for mingling PDFs.
- `acme.sh`: Shell script implementing ACME client protocol, an alternative to certbot.
- `bfg`: Remove large files or passwords from Git history like git-filter-branch.
- `pnpm`: Fast, disk space efficient package manager for Node.js.
- `pio-init`: This command is an alias of `pio project init`.
- `wp`: The official command-line interface to manage WordPress instances.
- `git-touch`: Create new files and add them to the index.
- `git-reset-file`: Revert a file to HEAD or a specific commit.
- `git-browse`: View an upstream repository in the default browser.
- `starship`:  Minimal, fast, customizable, universal shell prompt
 Highlights:
  - Fast
  - Customizable: configure every aspect of your prompt
  - Universal: works on most common shells, on most OSes
  - Intelligent: shows relevant information at a glance
  - Feature rich: supports many tools
  - Easy: quick install and start using in minutes
 .
 A Nerd Font is needed to show icons.


- `distccd`: Server daemon for the distcc distributed compiler.
- `virsh-undefine`: Delete a virtual machine.
- `git-summary`: Display information about a Git repository.
- `pio-test`: Run local tests on a PlatformIO project.
- `git-effort`: Display how much activity a file has had, showing commits per file and "active days" i.e. total number of days that contributed to the file.
- `mongoimport`: Imports content from a JSON, CSV, or TSV file into a MongoDB database.
- `uuencode`: Encode binary files into ASCII for transport via mediums that only support simple ASCII encoding.
- `virsh-help`: Display information about `virsh` commands or command groups.
- `git-delta`:  syntax-highlighting pager for git, diff, and grep output
 Code evolves, and we all spend time studying diffs.
 Delta aims to make this both efficient and enjoyable:
 it allows you to make extensive changes
 to the layout and styling of diffs,
 as well as allowing you to stay arbitrarily close
 to the default git/diff output.
 .
 This package provides the executable binary /usr/bin/delta.
 .
 (Unrelated executable binary /usr/bin/git-delta
 is in the package git-extras,
 and unrelated executable binaries
 /usr/bin/multidelta and /usr/bin/singledelta
 are in the package delta.)


- `git-obliterate`: Delete specific files and erase their history from a Git repository.
- `colorpicker`: A minimalist X11 colorpicker.
- `git-setup`: Create a Git repository in a specific directory and commit all files.
- `git-archive-file`: Export all the files of the current Git branch into a zip archive.
- `conda-create`: Create new conda environments.
- `git-extras`:  Extra commands for git
 This package provides extra git commands to easily solve typical tasks such as
 managing remote branches, managing feature/refactor/bug workflows and generate
 some repository stats.


- `acme.sh-dns`: Use a DNS-01 challenge to issue a TLS certificate.
- `virsh-domblklist`: List information about block devices associated with a virtual machine.
- `okular`:  universal document viewer
 Okular is a universal document viewer with support for advanced document
 features, such as annotations, forms, and embedded files.
 .
 This package provides the document viewer application, plus plugins for a wide
 variety of document formats such as:
  * PostScript (PS)
  * Portable Document Format (PDF)
  * TeX Device independent file format (DVI)
  * XML Paper Specification (XPS)
  * G3 fax
  * various electronic book formats: ComicBook, FictionBook, and Plucker
 .
 Additional document formats are in the okular-extra-backends package.
 .
 The Calligra suite provides Okular plugins for OpenDocument formats that can
 be found in the okular-backend-odt and okular-backend-odp packages.
 .
 This package is part of the KDE graphics module.


- `git-delete-tag`: Delete existing local and remote tags.
- `gh-secret-set`: Create or update GitHub secrets from the command line.
- `xplr`: Terminal-based file system explorer.
- `git-alias`: Create shortcuts for Git commands.
- `pio-remote`: Helper command for PlatformIO Remote Development.
- `kdeconnect-cli`: KDE Connect CLI.
- `git-rename-tag`: Rename a Git tag.
- `stl2gts`: Convert STL files into the GTS (GNU triangulated surface library) file format.
- `git-count`: Print the total number of commits.
- `git-create-branch`: Create a Git branch in a repository.
- `piodebuggdb`: This command is an alias of `pio debug --interface=gdb`.
- `jello`:  Filter for JSON and JSON Lines data with Python syntax
 jello is similar to jq in that it processes JSON and JSON Lines data except
 jello uses standard Python dict and list syntax.
 .
 JSON or JSON Lines can be piped into jello (JSON Lines are automatically
 slurped into a list of dictionaries) and are available as the variable _.
 Processed data can be output as JSON, JSON Lines, bash array lines, or a
 grep-able schema.


- `qutebrowser`:  Keyboard-driven, vim-like browser based on Python and Qt
 qutebrowser is a keyboard-focused browser with a minimal GUI. It's
 based on Python and Qt and was inspired by other browsers/addons
 like dwb and Vimperator/Pentadactyl.
 .
 qutebrowser supports the rendering engine QtWebEngine.


- `gnucash`:  personal and small-business financial-accounting software
 Gnucash provides accounting functions suitable for use by small businesses and
 individuals. It can track finances in multiple accounts, keeping running and
 reconciled balances. There is support for customer, vendor and employee
 processing. It has an X based graphical user interface, double entry, a
 hierarchy of accounts, expense accounts (categories), and can import Quicken
 QIF files and OFX files.


- `llvm-dis`: Converts LLVM bitcode files into human-readable LLVM Intermediate Representation (IR).
- `sk`: Fuzzy finder written in Rust.
- `git-root`: Print the root directory of the current Git repository.
- `caddy`:  Fast, lightweight web server with automatic HTTPS
 Caddy is a multi purpose web server written in Go.
 .
 Features:
  - Easy configuration
  - Automatic HTTPS by default
     - ZeroSSL and Let's Encrypt for public names
     - Fully-managed local CA for internal names & IPs
     - Can coordinate with other Caddy instances in a cluster
     - Multi-issuer fallback
  - HTTP/1.1, HTTP/2, and experimental HTTP/3 support


- `git-fork`: Fork the given GitHub repo. Like `git clone` but forks first.
- `git-rename-branch`: Rename a Git branch.
- `protector`: Protect or unprotect branches on GitHub repositories.
- `git-authors`: Generate a list of committers of a Git repository.
- `nu`: Nushell ("a new type of shell") takes a modern, structured approach to your command-line.
- `virsh-list`: List the ID, name, and state of virtual machines.
- `git-commits-since`: Display commits since a specific time or date.
- `qtcreator`:  integrated development environment (IDE) for Qt
 Qt Creator is a cross-platform integrated development environment (IDE)
 designed to make development with the Qt application framework faster
 and easier.
 .
 It includes:
  * An advanced C++ code editor
  * Integrated GUI layout and forms designer
  * Project and build management tools
  * Integrated, context-sensitive help system
  * Visual debugger
  * Rapid code navigation tools
  * Supports multiple platforms
  * Qt Quick Designer


- `git-range-diff`: Compare two commit ranges (e.g. two versions of a branch).
- `ibmcloud`: A command-line tool for managing IBM Cloud apps and services.
- `xh`:  Friendly and fast tool for sending HTTP requests
 It reimplements as much as possible of HTTPie's design, with
 a focus on improved performance.


- `git-brv`: Print a list of branches, sorted by last commit date.
- `git-delete-branch`: Delete local and remote Git branches.
- `josm`:  Editor for OpenStreetMap
 JOSM is an editor for OpenStreetMap (OSM) written in Java.
 The current version supports stand alone GPX tracks, GPX track data
 from OSM database and existing nodes, line segments and metadata tags
 from the OSM database.
 .
 OpenStreetMap is a project aimed squarely at creating and providing
 free geographic data such as street maps to anyone who wants them.
 The project was started because most maps you think of as free actually
 have legal or technical restrictions on their use, holding back people
 from using them in creative, productive or unexpected ways.


- `pio-debug`: Debug PlatformIO projects.
- `git-cp`: Copy an existing file to a new location, preserving history.
- `ts-node`:  TypeScript execution and language shell
 Provides a command-line interface to execute TypeScript code
 as a shell and an interactive read-eval-print-loop (REPL).


- `minisign`:  Dead simple tool to sign files and verify signatures
 Minisign is a dead simple tool to sign files and verify signatures.
 It is portable, lightweight, and uses the highly secure Ed25519
 public-key signature system. Signature files include an untrusted
 comment line that can be freely modified, even after signature
 creation. They also include a second comment line, that cannot be
 modified without the secret key. Trusted comments can be used to add
 instructions or application-specific metadata (intended file name,
 timestamps, resource identifiers, version numbers to prevent
 downgrade attacks).


- `uudecode`: Decode files encoded by `uuencode`.
- `idnits`: Check internet-drafts for submission nits.
- `git-ignore-io`: Generate .gitignore files from predefined templates.
- `git-fame`: Pretty-print Git repository contributions.
- `bandwhich`: Display the current network utilization by process, connection or remote IP/hostname.
- `ibmcloud-login`: Log in to the IBM Cloud.
- `git-info`: Display Git repository information.
- `virsh-connect`: Connect to a virtual machine hypervisor.
- `offlineimap`:  transitional package
 This is a transitional package. It can safely be removed.


- `git-local-commits`: Show local commits that haven't been pushed to origin. Any additional arguments will be passed directly to `git log`.
- `git-release`: Create a Git tag for a release.
- `mkvmerge`: Merge and extract multimedia streams.
- `git-undo`: Undo recent commits.
- `git-verify-commit`: Check for GPG verification of commits.
- `pio-run`: Run PlatformIO project targets.
- `starship-init`: Print shell integration code for starship.
- `git-contrib`: Display commits from a specific author.
- `x11docker`: Securely run GUI applications and desktop UIs in Docker containers.
- `virt-sysprep`: Reset, unconfigure, or customize a virtual machine image.
- `gh-issue-create`: Create GitHub issues on a repository from the command-line.
- `pnpx`: Directly execute binaries from npm packages, using `pnpm` instead of `npm`.
- `gnucash-cli`: A command-line version of GnuCash.
- `git-repl`: Git REPL (read-evaluate-print-loop) - an interactive Git shell.
- `git-graft`: Merge commits from a specific branch into another branch and delete the source branch.
- `age`:  simple, modern and secure encryption tool
 age features small explicit keys, no config options, and UNIX-style
 composability.


- `ical`: A Hirji/Islamic calendar and converter for the terminal.
- `brightnessctl`:  Control backlight brightness
 brightnessctl is a small utility to control the brightness
 of a screen's backlight.
 .
 This package contains the brightnessctl utility itself.


- `ffuf`:  Fast web fuzzer written in Go (program)
 ffuf is a fast web fuzzer written in Go that allows typical directory
 discovery, virtual host discovery (without DNS records) and GET and POST
 parameter fuzzing.
 .
 This program is useful for pentesters, ethical hackers and forensics experts.
 It also can be used for security tests.


- `po4a-translate`: Convert a PO file back to documentation format.
- `nordvpn`: Command-line interface for NordVPN.
- `readpe`:  command-line tools to manipulate Windows PE files
 readpe is a toolkit designed to analyze Microsoft Windows PE (Portable
 Executable) binary files. Its tools can parse and compare PE32/PE32+
 executable files (EXE, DLL, OCX, etc), and analyze them in search of
 suspicious characteristics.
 .
 It can be used to get information from those executable files, such as
 headers, sections, resources and more. It also provides tools to disassemble PE
 files and determine their security mitigations. It is useful for application
 security research, digital forensics and incident response, and malware
 analysis.
 .
 It is similar to elftools, only designed for PE files. It has more features
 than other more specific PE tools, such as icoextract or ntldd.
 .
 This package provides the ofs2rva, pedis, pehash, peldd, pepack, peres,
 pescan, pesec, pestr, readpe and rva2ofs commands.


- `kscreen-console`: Command-line tool to query KScreen's status.
- `pinout`: View the current Raspberry Pi's GPIO pin-out information on the terminal with an ASCII diagram.
- `ldapdomaindump`: Dump users, computers, groups, OS and membership information via LDAP to HTML, JSON and greppable output.
- `synopkg`: Package management utility for Synology DiskStation Manager.
- `nmcli-monitor`: Monitor changes to the NetworkManager connection status.
- `vnstati`:  image output support for vnStat
 vnStati provides image output support for statistics collected using
 vnStat. The image file format is limited to png. All basic outputs
 of vnStat are supported excluding live traffic features.
 The image can be outputted either to a file or to standard output.


- `xmount`:  tool for crossmounting between disk image formats
 xmount allows you to convert on-the-fly between multiple input and
 output harddisk image formats. xmount creates a virtual file system
 using FUSE (Filesystem in Userspace) that contains a virtual
 representation of the input image.
 .
 The virtual representation can be in raw DD, Apple's Disk Image format
 (DMG), VirtualBox's virtual disk file format (VDI), Microsoft's Virtual
 Hard Disk Image format (VHD) or in VMware's VMDK file format.
 .
 Input images can be raw DD, EWF (Expert Witness Compression Format),
 AFF (Advanced Forensic Format), VDI (VirtualBox Virtual Disk Image) or
 QCOW (QEMU Copy On Write) files.
 .
 In addition, xmount also supports virtual write access to the output
 files that is redirected to a cache file. This makes it for example
 possible to boot acquired harddisk images using QEMU, KVM, VirtualBox,
 VWware or alike.


- `zathura`:  document viewer with a minimalistic interface
 zathura is a document viewer for PDF and other formats with a minimalistic and
 space saving interface. It offers a vim-like experience and has a focus on
 keyboard interaction. The key bindings, commands and most other settings can
 be customized.
 .
 Some of the features are:
  * bookmarking pages
  * printing the whole document or specific pages
  * following links
  * searching in the document
  * browsing the document index
  * SyncTex forward and backward synchronization
 .
 zathura can be extended to support other file formats via a plugin system.


- `raspinfo`: Display Raspberry Pi system information.
- `ipset`:  administration tool for kernel IP sets
 IP sets are a framework inside the Linux 2.4.x and 2.6.x kernel which can be
 administered by the ipset(8) utility. Depending on the type, currently an
 IP set may store IP addresses, (TCP/UDP) port numbers or IP addresses with
 MAC addresses in a  way which ensures lightning speed when matching an
 entry against a set.
 .
 If you want to
 .
  * store multiple IP addresses or port numbers and match against the
    entire collection using a single iptables rule.
  * dynamically update iptables rules against IP addresses or ports without
    performance penalty.
  * express complex IP address and ports based rulesets with a single
    iptables rule and benefit from the speed of IP sets.
 .
 then IP sets may be the proper tool for you.


- `protonvpn-cli-connect`: Official client to connect to ProtonVPN from the command-line.
- `procs`:  modern replacement for ps
 procs lists processes and their stats, like ps but in a more
 human-readable way.
 .
 It displays additional information like TCP/UDP ports being
 listened on by the process, its read/write throughput and the
 name of the Docker container in which it is running, if any.
 .
 It supports colorized output, automatic theme detection based
 on terminal background, multi-column keyword search, paging,
 watch mode and tree view. The output can be customized using
 a configuration file.
 .
 Processes can be filtered by command, user or PID and the
 filters can be combined using logical operators.


- `po4a-updatepo`: Update the translation (in PO format) of a documentation.
- `raspi-config`: An `ncurses` terminal GUI to config a Raspberry Pi.
- `pw-loopback`: Tool for creating loopback devices in pipewire.
- `lxi`: Control LXI compatible instruments such as oscilloscopes.
- `aurvote`: Vote for packages in the Arch User Repository.
- `synoupgrade`: Upgrade a Synology DiskStation Manager (DSM) from the command-line.
- `kscreen-doctor`: Change and manipulate the screen setup from the command-line.
- `vcgencmd`: Print system information for a Raspberry Pi.
- `aura`: The Aura Package Manager: A secure, multilingual package manager for Arch Linux and the AUR.
- `st`: A simple terminal emulator for the X Window System.
- `pacman-key`: Wrapper script for GnuPG used to manage pacman's keyring.
- `wifi-menu`: Interactively connect to a wireless network.
- `po4a`:  tools to ease the translation of documentation
 po4a eases the translation of documentation and other textual document.
 Even more interestingly, it makes it easy to maintain these
 translations when the original document changes. This is done by
 using the gettext tools in this new domain.
 .
 This package contains the main libraries of po4a, and the necessary
 sub-modules to handle the following formats:
 .
   - Asciidoc: Asciidoc documentation format
   - Dia: uncompressed Dia diagrams.
   - Docbook: DocBook XML.
   - guide: Gentoo Linux's XML documentation format.
   - halibut: Simon Tatham's documentation production system.
   - INI: the INI format
   - KernelHelp: Help messages of each kernel compilation option.
   - LaTeX: generic TeX or LaTeX format.
   - Man: Good old manual page format (either roff or mdoc).
   - markdown: MD documents (using the txt module).
   - Man: either roff or mdoc format.
   - POD: Perl documentation format.
   - RubyDoc: RubyDoc (RD) format.
   - SGML: either DebianDoc or DocBook DTD.
   - Texinfo: the info page format (experimental).
   - tex: generic TeX documents (see also latex).
   - text: simple text document.
   - wml: WML documents.
   - xhtml: XHTML documents.
   - XML: very configurable (preconfigured for DocBook, XHTML, Guide, WML).
   - Yaml: Yaml documents.


- `po4a-gettextize`: Convert a file to a PO file.
- `protonvpn-cli`: Official client for ProtonVPN service from the command-line.
- `needrestart`:  check which daemons need to be restarted after library upgrades
 needrestart checks which daemons need to be restarted after library upgrades.
 It is inspired by checkrestart from the debian-goodies package.
 .
 Features:
  - supports (but does not require) systemd
  - binary blacklisting (i.e. display managers)
  - tries to detect required restarts of interpreter based daemons
    (supports Java, Perl, Python, Ruby)
  - tries to detect required restarts of containers (docker, LXC)
  - tries to detect pending kernel upgrades
  - tries to detect pending microcode upgrades for Intel CPUs
  - could be used as nagios check_command
  - fully integrated into apt/dpkg using hooks


- `gvpack`: Combine several graph layouts (that already have layout information).
- `twopi`: Render an image of a `radial` network graph from a `graphviz` file.
- `gh-browse`: Open a GitHub repository in the browser or print the URL.
- `todoist`: Access Todoist from the command-line.
- `virsh-pool-destroy`: Stop an active virtual machine storage pool.
- `openssl-ts`: OpenSSL command to generate and verify timestamps.
- `corepack`: Zero-runtime-dependency package acting as bridge between Node projects and their package managers.
- `pfetch`: Display system information.
- `lighthouse`: Analyzes web applications and web pages, collecting modern performance metrics and insights on developer best practices.
- `xml-edit`: Edit an XML document.
- `git-abort`: Abort an ongoing rebase, merge, or cherry-pick.
- `tailscale`: A private WireGuard network service.
- `virsh-pool-list`: List information about virtual machine storage pools.
- `edgepaint`: Colorize edges of a graph layout to clarify crossing edges.
- `yacas`:  Computer Algebra System
 Yacas is a small and highly flexible computer algebra language.
 .
 The syntax is very close to Mathematica. The distribution contains
 a small library of mathematical functions, but its real strength
 is in the language in which you can easily write your own symbolic
 manipulation algorithms. It supports arbitrary precision arithmetic.


- `gv2gxl`: Convert a graph from `gv` to `gxl` format.
- `mm2gv`: Convert a graph from Matrix Market `mm` format to `gv` format.
- `llvm-config`: Get various configuration information needed to compile programs which use LLVM.
- `peco`:  Simplistic interactive filtering tool
 peco Simplistic interactive filtering tool
 .
 peco can be a great tool to filter stuff like logs, process stats, find
 files, because unlike grep, you can type as you think and look through
 the current results.


- `ybacklight`: Manage screen backlight brightness. See also `xbacklight`.
- `gh-extension`: Manage extensions for the GitHub CLI.
- `dict`:  dictionary client
 This package provides a client application to query a dictd server.
 The client-server protocol is TCP-based; the server may then be local or
 accessed through the network.
 .
 The DICT Development Group maintains several public servers which can
 be accessed from any machine connected to the Internet.  The default
 configuration is to query one of these servers first. This may be
 changed in the configuration file /etc/dictd/dict.conf.
 .
 Queries may be customized by numerous command line options, including
 specifying the database(s) to be queried and the search strategy to
 be used.
 .
 This package also provides dictl, which allows using UTF-8 encoded dictionaries
 with terminals that do not support UTF-8.


- `updog`: A replacement for Python's SimpleHTTPServer.
- `xml-canonic`: Make XML documents canonical.
- `virsh-pool-autostart`: Enable or disable autostart for a virtual machine storage pool.
- `mongoexport`: Produce exports of data stored in a MongoDB instance formatted as JSON or CSV.
- `flake8`:  code checker using pycodestyle and pyflakes
 Flake8 is a wrapper around PyFlakes, pycodestyle, and Ned's McCabe script.
 Flake8 runs all tools by launching the single 'flake8' script, but ignores
 pycodestyle and PyFlakes extended options and just uses defaults. It displays
 the warnings in a per-file, merged output.
 .
 This package provides flake8 binary.


- `xml`: XMLStarlet Toolkit: Query, edit, check, convert and transform XML documents.
- `xml-pyx`: Convert an XML document to PYX (ESIS - ISO 8879) format.
- `unflatten`: Adjust directed graphs to improve the layout aspect ratio.
- `gitlint`:  Git commit message linter
 Gitlint is a git commit message linter written in Python, it checks your commit
 messages for style.
 .
 Great for use as a commit-msg git hook or as part of your gating script in a CI
 pipeline (e.g. Jenkins).


- `gml2gv`: Convert a graph from `gml` to `gv` format.
- `pwsh`: PowerShell Core is a cross-platform automation and configuration tool/framework.
- `git-rename-remote`: Change remote for pulling and pushing.
- `pio-ci`: Build PlatformIO projects with an arbitrary source code structure.
- `xetex`: Compile a PDF document from XeTeX source files.
- `xml-format`: Format an XML document.
- `aws-help`: Display help information about the AWS CLI.
- `clojure`:  Lisp dialect for the JVM
 Clojure is a dynamic programming language that targets the Java Virtual
 Machine. It is designed to be a general-purpose language, combining the
 approachability and interactive development of a scripting language with
 an efficient and robust infrastructure for multithreaded programming.
 Clojure is a compiled language - it compiles directly to JVM bytecode,
 yet remains completely dynamic. Every feature supported by Clojure is
 supported at runtime. Clojure provides easy access to the Java
 frameworks, with optional type hints and type inference, to ensure that
 calls to Java can avoid reflection.
 .
 Clojure is a dialect of Lisp, and shares with Lisp the code-as-data
 philosophy and a powerful macro system. Clojure is predominantly a
 functional programming language, and features a rich set of immutable,
 persistent data structures. When mutable state is needed, Clojure offers
 a software transactional memory system and reactive Agent system that
 ensure clean, correct, multithreaded designs.


- `sccmap`: Extract strongly connected components of directed graphs.
- `virsh-pool-build`: Build the underlying storage system for a virtual machine storage pool as defined in it's configuration file in `/etc/libvirt/storage`.
- `aws-ecr`: Push, pull, and manage container images.
- `git-bug`: A distributed bug tracker that uses git's internal storage, so no files are added in your project.
- `gxl2gv`: Convert a graph from `gxl` to `gv` format.
- `go-get`: Add a dependency package, or download packages in legacy GOPATH mode.
- `gvcolor`: Colorize a ranked digraph with a range of colors.
- `git-missing`: Show commits which aren't shared between two branches.
- `virsh-pool-delete`: Delete the underlying storage system of an inactive virtual machine storage pool.
- `git-show-tree`: Show a decorated tree graph with all branches of a Git repository, showing annotations.
- `acyclic`: Make a directed graph acyclic by reversing some edges.
- `az-logout`: Log out from an Azure subscription.
- `openscad`:  script file based graphical CAD environment
 OpenSCAD is a software for creating solid 3D CAD objects. It focuses on CAD
 aspects rather than artistic ones.
 .
 OpenSCAD is not an interactive modeller. Instead it is something like a
 3D-compiler that reads in a script file that describes the object and renders
 the 3D model from this script. This gives the designer full control over the
 modelling process and enables him to easily change any step in the modelling
 process or make designes that are defined by configurable parameters.


- `llvm-g++`: This command is an alias of `clang++`.
- `sfdp`: Render an image of a `scaled force-directed` network graph from a `graphviz` file.
- `dillo`:  Small and fast web browser
 Dillo 3 is a graphical multi-platform web browser known for its speed
 and small footprint. It is based on version 1.3 of the Fast and Light
 Toolkit (FLTK) in version 1.3
 .
 It aims to be small in resources, stable, developer-friendly, usable,
 very fast, and extensible.
 .
 To run the included dillo-install-hyphenation script the recommended
 perl packages need to be installed.


- `go-test`: Tests Go packages (files have to end with `_test.go`).
- `nop`: Check validity and pretty-print graphs in canonical format.
- `gdu`:  Pretty fast disk usage analyzer
 Disk usage analyzer with console interface written in Go.
 Intended primarily for SSD disks where it can fully
 utilize parallel processing. However HDDs work as well, but
 the performance gain is not so huge.


- `clang-cpp`: This command is an alias of `clang++`.
- `pixiecore`: Tool to manage the network booting of machines.
- `xml-escape`: Escape special XML characters, e.g. `<a1>` → `&lt;a1&gt;`.
- `xml-list`: List a directory's contents (like `ls`) in XML format.
- `zm`: A tool for managing articles of newspapers and blogs.
- `aws-cur`: Create, query, and delete AWS usage report definitions.
- `ganache-cli`: Command-line version of Ganache, your personal blockchain for Ethereum development.
- `adscript`: Compiler for Adscript files.
- `xml-depyx`: Convert a PYX (ESIS - ISO 8879) document to XML format.
- `mingle`: Bundle the edges of a graph layout.
- `brew-bundle`: Bundler for Homebrew, Homebrew Cask and the Mac App Store.
- `xdelta`:  A diff utility which works with binary files
 Xdelta is an application program designed to compute changes between
 files.  These changes (deltas) are similar to the output of the
 "diff" program in that they may be used to store and transmit only the
 changes between files.  However, unlike diff, the output of Xdelta is
 not expressed in a human-readable format--Xdelta can also apply
 these deltas to a copy of the original file.  Xdelta uses a fast,
 linear algorithm and performs well on both binary and text files.


- `bcomps`: Decompose graphs into their biconnected components.
- `cola`: This command is an alias of `git-cola`.
- `xml-validate`: Validate XML documents.
- `ffe`:  Tool for parsing flat and CSV files and converting them to different formats
 Ffe has many areas of use with fixed length and CSV files. It can extract
 particular fields or records from a flat file, convert data from one format
 to another (CSV to fixed length, ...), display flat file content in human
 readable form, etc. In addition, one input file can contain several types of
 records (lines) and the input file structure and output definitions are
 independent, meaning one output format can be used with several input files.
 This input file structure and output format are 'freely' configurable,
 so the output can be formatted e.g. as: fixed length, separated, tokenized,
 XML, SQL, ...


- `git-cola`:  highly caffeinated git GUI
 Git-cola is a git GUI optimized for working with the git index.
 .
 Git-cola can compare arbitrary commits using standard merge tools.
 With it you can search commit messages, content, authors, paths,
 data ranges etc. and it makes it easy to interactively edit the
 index.


- `keepassxc-cli`: Command-line interface for KeepassXC.
- `kubectl-run`: Run pods in Kubernetes. Specifies pod generator to avoid deprecation error in some K8S versions.
- `tlmgr-gui`: Start a graphical user interface for `tlmgr`.
- `gh-pr-create`: Manage GitHub pull requests from the command-line.
- `neato`: Render an image of a `linear undirected` network graph from a `graphviz` file.
- `ccomps`: Decompose graphs into their connected components.
- `az-login`: Log in to Azure.
- `sdcv`:  StarDict Console Version
 sdcv is simple text-based utility for work with dictionaries in StarDict's
 format.
 .
 It supports command line interaction as well as interactive mode using
 readline.


- `choose`: A human-friendly and fast alternative to cut and (sometimes) awk.
- `tlmgr-info`: Show information about TeX Live packages.
- `sup`:  Software Upgrade Protocol implementation
 The SUP System is a set of programs developed by Carnegie Mellon
 University that provide for collections of files to be maintained in
 identical versions across a number of machines.  These programs are:
 .
 SUP: The "client" program, run by users or system maintainers, which
 initiates the upgrade activity  on  a  machine  requesting  the
 latest  version of a collection of files.  SUP will normally be
 run as a daemon, firing up once  each  night  (week,  etc.)  to
 upgrade the specified file collections.
 .
 SUPFILESRV: The "file server" program, a daemon that is run by the
 system maintainer to service requests for files initiated by client
 SUP programs.  The file server runs on every machine used as a
 "repository" of distributable versions of files.  It runs continuously
 and listens for network connection requests by individual client
 processes; for each individual client request, a process is forked to
 service that request.
 .
 SUPSCAN: The "file scanner" program, that may optionally be run
 periodically to speed up execution of the file server.  It
 pre-compiles a list of files on the file system that match the
 specifications for a given file collection so that the file server
 need not do this during each upgrade of that collection.  The file
 scanner is normally used daily for very large file collections that
 are upgraded by many clients each day; it is not so useful for small
 file collections or for those that are upgraded by only a few client
 machines per day.


- `virsh-pool-start`: Start a previously configured but inactive virtual machine storage pool.
- `xml-unescape`: Unescape special XML characters, e.g. `&lt;a1&gt;` → `<a1>`.
- `img2pdf`:  Lossless conversion of raster images to PDF
 This program will take a list of raster images and produce a PDF file with the
 images embedded in it. JPEG and JPEG2000 images will be included without
 recompression. Raster images in other formats will be included with zip/flate
 encoding which usually leads to an increase in the resulting size because
 formats like png compress better than PDF which just zip/flate compresses the
 RGB data. As a result, this tool is able to losslessly wrap images into a PDF
 container with a quality to filesize ratio that is typically better (in case
 of JPEG and JPEG2000 images) or equal (in case of other formats) than that of
 existing tools.
 .
 This package contains the executable.


- `gv2gml`: Convert a graph from `gv` to `gml` format.
- `az-account`: Manage Azure subscription information.
- `gh-mintty`: Display help about MinTTY integration for the GitHub CLI command.
- `gh-formatting`: Formatting options for JSON data exported from gh GitHub CLI command.
- `carp`: REPL and build tool for Carp.
- `ts`: Add timestamps to every line from standard input.
- `transfersh`: An unofficial command-line client for transfer.sh.
- `tlmgr-paper`: Manage paper size options of an TeX Live installation.
- `aws-s3api`: Create and delete Amazon S3 buckets and edit bucket properties.
- `xml-elements`: Extract elements and display the structure of an XML document.
- `tred`: Compute the transitive reduction of directed graphs.
- `dart`: The tool for managing Dart projects.
- `xml-transform`: Transform XML documents using XSLT.
- `brew-cask`: Package manager for macOS applications distributed as binaries.
- `paperkey`:  extract just the secret information out of OpenPGP secret keys
 A reasonable way to achieve a long term backup of OpenPGP (GnuPG, PGP,
 etc) keys is to print them out on paper.  The reasoning behind this is
 that paper and ink has amazingly long retention qualities - far longer
 than the magnetic or optical means that are generally used to back up
 computer data.
 .
 Due to metadata and redundancy, OpenPGP secret keys are significantly
 larger than just the "secret bits".  In fact, the secret key contains
 a complete copy of the public key.  Since the public key generally
 doesn't need to be escrowed (most people have many copies of it on
 various keyservers, web pages, etc), only extracting the secret parts
 can be a real advantage.
 .
 Paperkey extracts just those secret bytes and prints them.  To
 reconstruct, you re-enter those bytes (whether by hand or via OCR) and
 paperkey can use them to transform your existing public key into a
 secret key.


- `circup`: The CircuitPython library updater.
- `patchwork`: Render an image of a `squareified treemap` network graph from a `graphviz` file.
- `showfigfonts`: Display available figlet fonts.
- `virsh-pool-info`: List information about a virtual machine storage pool.
- `jtbl`: Utility to print JSON and JSON Lines data as a table in the terminal.
- `prettier`: An opinionated code formatter for JavaScript, JSON, CSS, YAML, and more.
- `miniserve`: Simple HTTP file server CLI.
- `llvm-gcc`: This command is an alias of `clang`.
- `r2`: This command is an alias of `radare2`.
- `virsh-pool-undefine`: Delete the configuration file in `/etc/libvirt/storage` for a stopped virtual machine storage pool.
- `lb`: A tool for managing a blog contained in the current directory.
- `moe`: A WYSIWYG text editor for ISO-8859-15 encoded text.
- `fdp`: Render an image of a `force-directed` network graph from a `graphviz` file.
- `tailscale-up`: Connects the client to the Tailscale network.
- `osage`: Render an image of a `clustered` network graph from a `graphviz` file.
- `resume`: CLI tool to easily setup a new resume.
- `dwebp`: `dwebp` decompresses WebP files into PNG, PAM, PPM or PGM images.
- `ocrmypdf`:  add an OCR text layer to PDF files
 OCRmyPDF generates a searchable PDF/A file from a regular PDF
 containing only images, allowing it to be searched.
 .
 It uses the Tesseract OCR engine and so supports all the languages
 that Tesseract does.
 .
 Some other main features:
 .
   * Places OCR text accurately below the image to ease copy / paste
   * Keeps the exact resolution of the original embedded images
   * When possible, inserts OCR information as a lossless operation
     without rendering vector information
   * Keeps file size about the same
   * If requested deskews and/or cleans the image before performing OCR
   * Validates input and output files
   * Provides debug mode to enable easy verification of the OCR results
   * Processes pages in parallel when more than one CPU core is
     available
   * Battle-tested on thousands of PDFs, a test suite and continuous
     integration.


- `asciidoctor`:  AsciiDoc to HTML rendering for Ruby
 Asciidoctor is a pure Ruby processor for converting AsciiDoc source files and
 strings into HTML 5, DocBook 4.5, DocBook 5.0 and other formats.


- `graphml2gv`: Convert a graph from `graphml` to `gv` format.
- `xml-select`: Select from XML documents using XPATHs.
- `docker-login`: Log into a docker registry.
- `virsh-pool-define-as`: Create a configuration file in `/etc/libvirt/storage` for a persistent virtual machine storage pool from the provided arguments.
- `circo`: Render an image of a `circular` network graph from a `graphviz` file.
- `aws-secretsmanager`: Store, manage, and retrieve secrets.
- `az-vm`: Manage virtual machines in Azure.
- `avo`: The official command-line interface for Avo.
- `clang++`: Compiles C++ source files.
- `gmssl`: GmSSL is a crypto toolkit supporting SM1, SM2, SM3, SM4, SM9, and ZUC/ZUC256.
- `i3exit`: Exit the i3 window manager.
- `mt`: Control magnetic tape drive operation (commonly LTO tape).
- `i3status`:  Generates a status line for dzen2, xmobar or i3bar
 i3status is a small (about 3000 SLOC) and light-weight program for generating
 a status bar for i3bar, dzen2, xmobar or similar programs by combining several
 information about your system (IP addresses of your interfaces, load, current
 date/time, ESSID of the network you are associated to, disk status, and so on).


- `qm`: Qemu/KVM Virtual Machine Manager.
- `pw-play`: Shorthand tool for pw-cat --playback.
- `fprintd-verify`: Verify fingerprints against the database.
- `cgcreate`: Create cgroups, used to limit, measure, and control resources used by processes.
- `goaccess`:  log analyzer and interactive viewer for the Apache Webserver
 Displays fast and valuable HTTP statistics for system administrators that
 require a visual report on the fly.
 .
 The collected information will be displayed to the user (sysadmin) in a
 visual/interactive window. Collected information includes:
 .
  -General Statistics, Bandwidth etc.
  -Top Visitors
  -Requested files
  -Requested static files, images, swf, js, etc.
  -Referrers URLs
  -404 or Not Found
  -Operating Systems
  -Browsers and Spiders
  -Hosts, Reverse DNS, IP Location
  -HTTP Status Codes
  -Referring Sites
  -Unlimited log file size
 .
 GoAccess can parse both of Apaches' log formats, the Common Log Format and
 the Combined Log Format


- `nitrogen`:  wallpaper browser and changing utility for X
 nitrogen is a graphical wallpaper utility that can be used in two
 modes, browser and recall.
 Some of the things to look for in nitrogen are:
 .
  * Multihead and Xinerama support (setting
    different wallpapers for each monitor)
  * Recall mode to restore wallpapers via startup script
  * Uses freedesktop.org standard for thumbnails
  * Can set GNOME background
  * Command line set modes for script usage
  * Inotify monitoring of browsed directories


- `pactree`: Package dependency tree viewer for pacman.
- `check-language-support`: Display a list of missing language packages on Ubuntu.
- `lxc-network`: Manage networks for LXD containers.
- `fprintd-list`: List enrolled fingerprints.
- `autopkgtest`:  automatic as-installed testing for Debian packages
 autopkgtest runs tests on binary packages.  The tests are run on the
 package as installed on a testbed system (which may be found via a
 virtualisation or containment system).  The tests are expected to be
 supplied in the corresponding Debian source package.
 .
 See autopkgtest(1) and /usr/share/doc/autopkgtest.
 Depending on which virtualization server you want to use, you need to
 install additional packages (schroot, lxc, lxd, or qemu-system)
 .
 For generating tests of well-known source packages such as Perl and Ruby
 libraries you should install the autodep8 package.


- `fscrypt`:  Tool for managing Linux filesystem encryption
 fscrypt is a high-level tool for the management of Linux filesystem
 encryption. This tool manages metadata, key generation, key wrapping,
 PAM integration, and provides a uniform interface for creating and
 modifying encrypted directories.
 .
 To use fscrypt, you must have a filesystem with encryption enabled and
 a kernel that supports reading/writing from that filesystem. Currently,
 ext4, F2FS, and UBIFS support Linux filesystem encryption. Ext4 has
 supported Linux filesystem encryption since v4.1, F2FS added support
 in v4.2, and UBIFS added support in v4.10. Other filesystems may add
 support for native encryption in the future.


- `avifenc`: AV1 Image File Format (AVIF) encoder.
- `fwupdmgr`: A tool for updating device firmware, including UEFI, using `fwupd`.
- `cgroups`: Cgroups aka control groups is a Linux kernel feature for limiting, mesuring, and controling resource usage by processes.
- `dirb`:  URL bruteforcing tool
 DIRB is a Web Content Scanner. It looks for existing (and/or hidden) Web
 Objects. It basically works by launching a dictionary based attack against
 a web server and analyzing the responses.
 .
 DIRB comes with a set of preconfigured attack wordlists for easy usage but
 you can use your custom wordlists. Also DIRB sometimes can be used as a
 classic CGI scanner, but remember that it is a content scanner not a
 vulnerability scanner.
 .
 DIRB's main purpose is to help in professional web application auditing.
 Specially in security related testing. It covers some holes not covered by
 classic web vulnerability scanners. DIRB looks for specific web objects that
 other generic CGI scanners can't look for. It doesn't search vulnerabilities
 nor does it look for web contents that can be vulnerable.


- `fossil-forget`: This command is an alias of `fossil rm`, with the exception that it never removes files from the disk.
- `blurlock`: A simple wrapper around the i3 screen locker `i3lock`, which blurs the screen.
- `debsecan`:  Debian Security Analyzer
 debsecan is a tool to generate a list of vulnerabilities which affect
 a particular Debian installation.  debsecan runs on the host which is
 to be checked, and downloads vulnerability information over the
 Internet.  It can send mail to interested parties when new
 vulnerabilities are discovered or when security updates become
 available.


- `ttyplot`:  realtime plotting utility for text mode consoles and terminals
 ttyplot takes data from standard input or a unix pipeline and plots in text
 mode on a terminal in real time. It supports rate calculation for counters
 and up to two graphs on a single display using reverse video for the second
 line.


- `btrfs-property`: Get, set, or list properties for a given btrfs filesystem object (files, directories, subvolumes, filesystems, or devices).
- `zegrep`: Find extended regular expression patterns in compressed files using `egrep`.
- `fossil-ci`: This command is an alias of `fossil commit`.
- `pw-record`: Shorthand tool for pw-cat --playback.
- `nixos-option`: Inspect a NixOS configuration.
- `lxc-profile`: Manage profiles for LXD containers.
- `nixos-container`: Starts NixOS containers using Linux containers.
- `btrfs-restore`: Try to salvage files from a damaged btrfs filesystem.
- `rpmspec`: Query a RPM spec file.
- `updpkgsums`: Update the checksums of the sources in a `PKGBUILD`.
- `dunstctl`: Control command for `dunst`.
- `btrfs-version`: Display btrfs-progs version.
- `fprintd-delete`: Remove fingerprints from the database.
- `bspc`: A tool to control `bspwm`.
- `shiny-mirrors`: Generate a pacman mirror list for Manjaro Linux.
- `powerprofilesctl`: Make power profiles handling available over D-Bus.
- `deborphan`: Display orphan packages on operating systems using the APT package manager.
- `dphys-swapfile`:  Autogenerate and use a swap file
 This init.d script exists so one does not need to have a fixed size
 swap partition. Instead install without swap partition and then run this,
 with file size (re-)computed automatically to fit the current RAM size.
 .
 By default (and hence on installation) it creates swapfile twice as
 big as the present RAM amount with an upper limit of 2 GB.
 .
 It's also very helpful when included in SD card, USB stick or disk
 images which are distributed and run on many machines with different
 amount of RAM, e.g. different models of the Raspberry Pi or cloud
 images.


- `chntpw`:  NT SAM password recovery utility
 This little program provides a way to view information and
 change user passwords in a Windows NT/2000 user database file.
 Old passwords need not be known since they are overwritten.
 In addition it also contains a simple registry editor
 (same size data writes) and an hex-editor which enables you to
 fiddle around with bits and bytes in the file as you wish.
 .
 If you want GNU/Linux bootdisks for offline password recovery
 you can add this utility to custom image disks or use those provided
 at the tools homepage.


- `cgexec`: Limit, measure, and control resources used by processes.
- `checkinstall`:  installation tracker
 CheckInstall keeps track of all the files created or
 modified by your installation script ("make install"
 "make install_modules", "setup", etc), builds a
 standard binary package and installs it in your
 system giving you the ability to uninstall it with your
 distribution's standard package management utilities.


- `xcowsay`:  Graphical configurable talking cow
 A GTK+ version of the classic cowsay Perl script. It displays a cute
 pop-up cow on your desktop with a speech bubble and some customizable
 text. There's also a dream mode where the cow can display images. It
 comes with a fortune(6) wrapper script, xcowfortune, which you can
 cron to deliver periodic fortune cookies via the cow.


- `wl-copy`: Wayland clipboard manipulation tool.
- `sherlock`:  Find usernames across social networks
 Sherlock relies on the site's designers providing a  unique URL
 for a registered username. To determine if a username is available,
 Sherlock queries that URL, and uses to response to understand if
 there is a claimed username already there.
 .
 Currently, the tool is capable of locating users on more than 300 social
 networks: Apple Developer, Arduino, Docker Hub, GitHub, GitLab,  Facebook,
 BitCoinForum, CNET, IFTTT, Instagram, PlayStore  PyPI, Scribd, Telegram,
 TikTok, Tinder etc.


- `ego`: Funtoo's official system personality management tool.
- `wl-paste`: Tool to access data stored in the clipboard for Wayland.
- `fossil`:  DSCM with built-in wiki, http interface and server, tickets database
 Fossil is an easy-to-use Distributed Source Control Management system
 (DSCM) which supports access and administration over HTTP CGI or via
 a built-in HTTP server, has a built-in wiki, built-in file browsing,
 a built-in tickets system, etc.


- `pridecat`: Like cat but more colorful :).
- `wajig`:  unified package management front-end for Debian/Ubuntu
 A command-line wrapper around apt, apt-cache, dpkg, aptitude, and more.
 The goal is to ease system management by unifying the main functions
 of these tools from one interface.
 .
 For a short guide, run this command:
 $ wajig help


- `pw-cat`: Pipewire tool for playing and recording audio files.
- `reptyr`:  Tool for moving running programs between ptys
 reptyr is a utility for taking an existing running program and
 attaching it to a new terminal, and is particularly useful for moving
 a long-running process into a GNU screen session.
 .
 reptyr does a more thorough job of transferring programs than many
 other tools, including the popular "screenify" shell script, because
 it changes the program's controlling terminal. This means that
 actions such as window resizes and interrupts are sent to the process
 from the new terminal.


- `namcap`: Check binary packages and source `PKGBUILD`s for common packaging mistakes.
- `apt-moo`: An `APT` easter egg.
- `resolvectl`: Resolve domain names, IPV4 and IPv6 addresses, DNS resource records, and services.
- `fprind`: Fingerprint management daemon.
- `lnav`:  ncurses-based log file viewer
 The log file navigator, lnav, is an enhanced log file viewer that
 takes advantage of any semantic information that can be gleaned from
 the files being viewed, such as timestamps and log levels.  Using this
 extra semantic information, lnav can do things like interleaving
 messages from different files, generate histograms of messages over
 time, and providing hotkeys for navigating through the file.  It is
 hoped that these features will allow the user to quickly and
 efficiently zero in on problems.


- `xwinwrap`: Run a player or a program as desktop background.
- `ddcutil`:  Control monitor settings - Standalone command line application
 ddcutil is used to query and change monitor settings.
 .
 ddcutil communicates with monitors implementing MCCS (Monitor Control Command
 Set). Normally, communication is performed using the DDC/CI protocol on the
 I2C bus.  Alternatively, communication can be performed over USB as per the
 USB Monitor Control Class Specification.


- `btrfs-check`: Check or repair a btrfs filesystem.
- `fprintd-enroll`: Enroll fingerprints into the database.
- `rgrep`: Recursively find patterns in files using regular expressions.
- `btrfs-inspect-internal`: Query internal information of a btrfs filesystem.
- `minicom`:  Friendly menu driven serial communication program
 Minicom is a clone of the MS-DOS "Telix" communication program. It emulates
 ANSI and VT102 terminals, has a dialing directory and auto zmodem download.


- `i3-scrot`: Wrapper script around the screenshot utility `scrot` for the i3 window manager.
- `gbp`: A system to integrate the Debian package build system with Git.
- `qmrestore`: Restore QemuServer vzdump Backups.
- `ytfzf`:  script to find and watch youtube videos from the terminal
 YTFZF is a script to search, download and play YouTube videos by making use of
 mpv and youtube-dl under the hood. It works on Linux and macOS.
 .
 For each YouTube search query, a list of results in shown in the right-hand
 side pane. On the left-hand side you can see the selected video title, the
 channel that posted the video, the number of views, video duration, upload
 date, and the video thumbnail.
 .
 Besides this, ytfzf also features support for video history, allows choosing
 the media format and can queue multiple tracks.
 .
 You can search for YouTube/Odysee/PeerTube videos and play/download using fzf,
 dmenu. Other features include the ability to play/download audio only,
 auto-play and repeat YouTube videos, play a random search result, and
 there's also an option to show available media formats before proceeding.


- `btrfs-rescue`: Try to recover a damaged btrfs filesystem.
- `v4l2-ctl`: Control video devices.
- `fossil-add`: Put files or directories under Fossil version control.
- `pacstall`: An AUR package manager for Ubuntu.
- `runlim`:  tool for sampling time and memory usage
 This package contains runlim, a tool for sampling time and memory
 usage of a program and its children using the proc file system of
 Linux. Time and space limits are also supported. It is very helpful
 for benchmarking and running competitions. It also supports limits on
 wall clock time and thus can control runs of multi-threaded programs
 on multi-core machines as well.


- `wdctl`: Show the hardware watchdog status.
- `fossil-rm`: Remove files or directories from Fossil version control.
- `alien`:  convert and install rpm and other packages
 Alien allows you to convert LSB, Red Hat, Stampede and Slackware Packages
 into Debian packages, which can be installed with dpkg.
 .
 It can also generate packages of any of the other formats.
 .
 This is a tool only suitable for binary packages.


- `bpftool`:  Inspection and simple manipulation of BPF programs and maps
 The bpftool command allows for inspection and simple modification of
 Berkeley Packet Filter (BPF) objects on the system.


- `bspwm`:  Binary space partitioning window manager
 Bspwm is a tiling window manager that represents windows as the
 leaves of a full binary tree.


- `abbr`: Manage abbreviations for the fish shell.
- `btrfs-balance`: Balance block groups on a btrfs filesystem.
- `fossil-commit`: Commit files to a Fossil repository.
- `atool`:  tool for managing file archives of various types
 atool is a script for managing file archives of various types (tar,
 tar+gzip, zip etc). The main command is probably aunpack,
 extracting files from an archive. It overcomes the dreaded "multiple
 files in archive root" problem by first extracting to a unique
 subdirectory, and then moving back the files if possible. aunpack
 also prevents local files from being overwritten by mistake.
 .
 Other commands provided are apack (create archives), als (list files
 in archives), and acat (extract files to standard out).


- `fossil-delete`: This command is an alias of `fossil rm`.
- `cryptcat`:  lightweight version netcat extended with twofish encryption
 Cryptcat is a simple Unix utility which reads and writes data across
 network connections, using TCP or UDP protocol while encrypting the
 data being transmitted.
 It is designed to be a reliable "back-end" tool that can be used directly
 or easily driven by other programs and scripts.  At the same time, it is a
 feature-rich network debugging and exploration tool, since it can create
 almost any kind of connection you would need and has several interesting
 built-in capabilities.


- `megatools-dl`: Download files from `mega.nz`.
- `kwrite`:  simple text editor
 KWrite is a simple text editor built on the KDE Platform. It uses the Kate
 editor component, so it supports powerful features such as flexible syntax
 highlighting, automatic indentation, and numerous other text tools.


- `ubuntu-bug`: This command is an alias of `apport-bug`.
- `fakeroot`:  tool for simulating superuser privileges
 fakeroot provides a fake "root environment" by means of LD_PRELOAD and
 SysV IPC (or TCP) trickery. It puts wrappers around getuid(), chown(),
 stat(), and other file-manipulation functions, so that unprivileged
 users can (for instance) populate .deb archives with root-owned files;
 various build tools use fakeroot for this by default.
 .
 This package contains fakeroot command and the daemon that remembers
 fake ownership/permissions of files manipulated by fakeroot
 processes.


- `prlimit`: Get or set process resource soft and hard limits.
- `kubectl-rollout`: Manage the rollout of a Kubernetes resource (deployments, daemonsets, and statefulsets).
- `neomutt`:  command line mail reader based on Mutt, with added features
 Neomutt supports all the features that are supported by Mutt, including POP and
 IMAP support, SSL encryption and SASL authentication, threading and GPG
 support.
 .
 On the top of that, neomutt provides:
 .
  * Notmuch: a mail indexing tools that provides advanced features such as
    full-text search, thread reconstruction and added features.
  * Color attachment headers using regex, just like mail bodies.
  * Custom rules for theming the mail index.
  * NNTP support.
  * Visual progress bar for slow operations.
  * Trash folder.


- `gpg-tui`: Terminal user interface for GNU Public Guard.
- `llvm-objdump`: This command is an alias of `objdump`.
- `az-pipelines`: Manage Azure Pipelines resources.
- `ia`: Command-line tool to interact with `archive.org`.
- `llvm-as`: LLVM Intermediate Representation (`.ll`) to Bitcode (`.bc`) assembler.
- `duplicacy`: A lock-free deduplication cloud backup tool.
- `kotlinc`: Kotlin compiler.
- `raco`: Racket command-line tools.
- `aws-ses`: CLI for AWS Simple Email Service.
- `trivy`:  comprehensive and versatile security scanner
 This package contains a comprehensive and versatile security scanner. Trivy
 has scanners that look for security issues, and targets where it can find
 those issues.
 It can find vulnerabilities, misconfigurations, secrets, SBOM in containers,
 Kubernetes, code repositories, clouds and more.
 .
 Targets (what Trivy can scan):
 .
  * Container Image
  * Filesystem
  * Git Repository (remote)
  * Virtual Machine Image
  * Kubernetes
  * AWS
 .
 Scanners (what Trivy can find there):
 .
  * OS packages and software dependencies in use (SBOM)
  * Known vulnerabilities (CVEs)
  * IaC issues and misconfigurations
  * Sensitive information and secrets
  * Software licenses


- `ledger`:  command-line double-entry accounting program
 Ledger is a powerful and flexible double-entry accounting system run
 entirely from the command line.  Your accounts ledger is stored in one or
 more plain-text files with a very simple and readable format, and ledger
 does the hard work of balancing your books and reporting.


- `glab-release`: Manage GitLab releases from the command-line.
- `semver`: Semantic version string parser.
- `glab-mr`: Manage GitLab merge requests from the command-line.
- `zellij`: Terminal multiplexer with batteries included.
- `orca-c`: A C-port of the ORCA live programming environment.
- `az-config`: Manage Azure CLI configuration.
- `git-reauthor`: Change details about an author identity. Since this command rewrites the Git history, `--force` will be needed when pushing next time.
- `terragrunt`: Keep your Terraform CLI arguments DRY.
- `rc`:  implementation of the AT&T Plan 9 shell
 rc is a command interpreter and programming language similar to sh(1). It is
 based on the AT&T Plan 9 shell of the same name. The shell offers a C-like
 syntax (much more so than the C shell), and a powerful mechanism for
 manipulating variables. It is reasonably small and reasonably fast, especially
 when compared to contemporary shells. Its use is intended to be interactive,
 but the language lends itself well to scripts.


- `go-fmt`: Format Go source files.
- `mu`: Index and search emails from a local Maildir.
- `dolt-clone`: Clone a repository into a new directory.
- `tye`: Developer tool that makes developing, testing, and deploying microservices and distributed applications easier.
- `gh-cs`: This command is an alias of `gh codespace`.
- `llvm-strings`: This command is an alias of `strings`.
- `tlmgr-candidates`: Get available candidate repositories from which a TeX Live package can be installed.
- `llc`: Compiles LLVM Intermediate Representation or bitcode to target-specific assembly language.
- `ykinfo`: Get basic information from a YubiKey.
- `viu`: A small command-line application to view images from the terminal.
- `kitty`:  fast, featureful, GPU based terminal emulator
 Kitty supports modern terminal features like: graphics, unicode,
 true-color, OpenType ligatures, mouse protocol, focus tracking, and
 bracketed paste.
 .
 Kitty has a framework for "kittens", small terminal programs that can be used
 to extend its functionality.


- `git-secret`:  store encrypted credential inside source code git repository
 git-secret is designed to solve the problem where to store the credential file
 (e.g. password, token, ...) for a service. With git-secret, Encrypted
 credential can be stored along with source code in git repository.


- `antibody`: The fastest shell plugin manager.
- `fluxctl`: Command-line tool for Flux v1.
- `tlmgr-arch`: This command is an alias of `tlmgr platform`.
- `dlv`: Debugger for the Go programming language.
- `joe`:  user friendly full screen text editor
 Joe, the Joe's Own Editor, has the feel of most PC text editors: the key
 sequences are reminiscent of WordStar and Turbo C editors, but the feature
 set is much larger than of those.  Joe has all of the features a Unix
 user should expect: full use of termcap/terminfo, complete VI-style Unix
 integration, a powerful configuration file, and regular expression search
 system.  It also has six help reference cards which are always available,
 and an intuitive, simple, and well thought-out user interface.
 .
 Joe has a great screen update optimization algorithm, multiple windows
 (through/between which you can scroll) and lacks the confusing notion of
 named buffers.  It has command history, TAB expansion in file selection
 menus, undo and redo functions, (un)indenting and paragraph formatting,
 filtering highlighted blocks through any external Unix command, editing
 a pipe into or out of a command, and block move, copy, delete or filter.
 .
 Through simple QEdit-style configuration files, Joe can be set up to
 emulate editors such as Pico and Emacs, along with a complete imitation
 of WordStar, and a restricted mode version (lets you edit only the files
 specified on the command line).  Joe also has a deferred screen update to
 handle typeahead, and it ensures that deferral is not bypassed by tty
 buffering.  It's usable even at 2400 baud, and it will work on any
 kind of sane terminal.


- `kiwi-ng`: KIWI NG is an OS image and appliance builder.
- `puppet-apply`: Apply Puppet manifests locally.
- `ipaggmanip`: Manipulate aggregate statistics produced by `ipaggcreate`.
- `todo`: A simple, standards-based, cli todo manager.
- `textql`:  execute SQL against structured text like CSV or TSV
 TextQL allows you to easily execute SQL against structured text like
 CSV or TSV.


- `az-storage-blob`: Manage blob storage containers and objects in Azure.
- `git-changelog`: Generate a changelog report from repository commits and tags.
- `doctl-balance`: Show the balance of a Digital Ocean account.
- `mplayer`:  movie player for Unix-like systems
 MPlayer plays most MPEG, VOB, AVI, Ogg/OGM, VIVO,
 ASF/WMA/WMV, QT/MOV/MP4, FLI, RM, NuppelVideo, yuv4mpeg, FILM, RoQ, PVA files,
 supported by many native, XAnim, RealPlayer, and Win32 DLL codecs. It can
 also play VideoCD, SVCD, DVD, 3ivx, RealMedia, and DivX movies.
 .
 Another big feature of MPlayer is the wide range of supported output
 drivers. It works with X11, Xv, DGA, OpenGL, SVGAlib, fbdev,
 but also SDL.
 .
 Not all of the upstream code is distributed in the source tarball.
 See the README.Debian and copyright files for details.


- `git-filter-repo`:  Quickly rewrite git repository history
 git filter-repo is a versatile tool for rewriting history, which includes
 capabilities not found anywhere else.  It roughly falls into the
 same space of tool as git filter-branch but without the capitulation-inducing
 poor performance, with far more capabilities, and with a design that scales
 usability-wise beyond trivial rewriting cases.  git filter-repo is now
 recommended by the git project instead of git filter-branch.
 .
 While most users will probably just use filter-repo as a simple command
 line tool (and likely only use a few of its flags), at its core filter-repo
 contains a library for creating history rewriting tools.  As such, users
 with specialized needs can leverage it to quickly create entirely new
 history rewriting tools.


- `git-blame-someone-else`: Blame someone else for your bad code.
- `smalltalkci`: Framework for testing Smalltalk projects with GitHub Actions, Travis CI, AppVeyor, GitLab CI, and others.
- `pylint`:  Python 3 code static checker and UML diagram generator
 Pylint is a Python source code analyzer which looks for programming
 errors, helps enforcing a coding standard and sniffs for some code
 smells (as defined in Martin Fowler's Refactoring book)
 .
 Pylint can be seen as another PyChecker since nearly all tests you
 can do with PyChecker can also be done with Pylint. However, Pylint
 offers some more features, like checking length of lines of code,
 checking if variable names are well-formed according to your coding
 standard, or checking if declared interfaces are truly implemented,
 and much more.
 .
 Additionally, it is possible to write plugins to add your own checks.
 .
 The package also ships the following additional commands:
 .
   * pyreverse: an UML diagram generator
   * symilar: an independent similarities checker
   * epylint: Emacs and Flymake compatible Pylint


- `nth`: Name That Hash - Instantly name the type of any hash.
- `az-appconfig`: Manage App configurations on Azure.
- `grip`:  Preview GitHub Markdown files like Readme locally
 Grip is a command-line server application written in Python that uses the
 GitHub markdown API to render a local readme file. The styles come directly
 from GitHub, so you'll know exactly how it will appear. Changes you make to
 the Readme will be instantly reflected in the browser without requiring a page
 refresh.
 .
 Privacy notice: by default all documents will be sent to GitHub (Microsoft).


- `az-feedback`: Send feedback to the Azure CLI Team.
- `lli`: Directly execute programs from LLVM bitcode.
- `maza`: Local ad blocker. Like Pi-hole but local and using the operating system.
- `dotnet-ef`: Perform design-time development tasks for Entity Framework Core.
- `git-clear-soft`: Clear a Git working directory as if it was freshly cloned with the current branch excluding files in `.gitignore`.
- `tlmgr-install`: Install TeX Live packages.
- `loadtest`: Run a load test on the selected HTTP or WebSockets URL.
- `swc`: JavaScript and TypeScript compiler written in Rust.
- `pdf-parser`:  Parses PDF files to identify fundamental elements
 This tool will parse a PDF document to identify the
 fundamental elements used in the analyzed file. It will not
 render a PDF document.


- `mozillavpn`: A Virtual Private Network from the makers of Firefox.
- `ntl`: This command is an alias of `netlify`.
- `truffle`: A tool for developing smart contracts for running services on the Ethereum blockchain.
- `highlight`:  Universal source code to formatted text converter
 A utility that converts sourcecode to HTML, XHTML, RTF, LaTeX, TeX,
 SVG, XML or terminal escape sequences with syntax highlighting.  It
 supports several programming and markup languages.  Language
 descriptions are configurable and support regular expressions.  The
 utility offers indentation and reformatting capabilities.  It is
 easily possible to create new language definitions and colour themes.


- `tlmgr-check`: Check the consistency of a TeX Live installation.
- `core-validate-commit`: Validate commit messages for Node.js core.
- `glab-mr-merge`: Merge GitLab merge requests.
- `go-install`: Compile and install packages named by the import paths.
- `swipl`: SWI-Prolog - A comprehensive free Prolog environment.
- `ex`: Command-line text editor.
- `http-server`: Simple static HTTP server to serve static files.
- `az-network`: Manage Azure Network resources.
- `llvm-bcanalyzer`: LLVM Bitcode (`.bc`) analyzer.
- `puppet`:  transitional dummy package
 This is a transitional dummy package. It can safely be removed.


- `glab-mr-create`: Manage GitLab merge requests from the command-line.
- `clamdscan`:  anti-virus utility for Unix - scanner client
 Clam AntiVirus is an anti-virus toolkit for Unix. The main purpose of
 this software is the integration with mail servers (attachment
 scanning). The package provides a flexible and scalable
 multi-threaded daemon in the clamav-daemon package, a command-line
 scanner in the clamav package, and a tool for automatic updating via
 the Internet in the clamav-freshclam package. The programs are based
 on libclamav, which can be used by other software.
 .
 This package contains clamdscan, the command line interface of the clamav
 daemon.


- `gh-codespace`: Connect and manage your codespaces in GitHub.
- `sslscan`:  Tests SSL/TLS enabled services to discover supported cipher suites
 This tool allow queries SSL/TLS services (such as HTTPS) and reports the
 protocol versions, cipher suites, key exchanges, signature algorithms, and
 certificates in use.  This helps the user understand which  parameters are
 weak from a security standpoint.
 .
 sslscan can also output results into an XML file for easy consumption by
 external programs.


- `git-delete-merged-branches`:  command-line tool to delete merged git branches
 A convenient command-line tool helping you keep repositories clean.
 .
 Features:
  * Supports deletion of both local and remote branches
  * Detects multiple forms of de-facto merges (rebase merges, squash merges
    (needs --effort=3), single or range cherry-picks… leveraging git cherry)
  * Supports workflows with multiple release branches, e.g. only delete
    branches that have been merged to all of master, dev and staging
  * Quick interactive configuration
  * Provider agnostic: Works with GitHub, GitLab, Gitea and any other Git
    hosting
  * Takes safety seriously
 .
 This package contains the command line interface.


- `git-squash`: Squash multiple commits into a single commit.
- `u3d`: Set of tools to interact with Unity from command line.
- `pypy`: Fast and compliant alternative implementation of the Python language.
- `colorls`: A Ruby gem that beautifies the terminal's ls command, with color and font-awesome icons.
- `npm-name`: Check whether a package or organization name is available on npm.
- `az-storage-entity`: Manage Azure Table storage entities.
- `az-storage`: Manage Azure Cloud Storage resources.
- `tlmgr-option`: TeX Live settings manager.
- `scalafmt`: Code formatter for Scala.
- `grap`:  program for typesetting graphs
 This is grap, an implementation of Kernighan and Bentley's grap language
 for typesetting graphs. The grap preprocessor works with pic and troff
 (or groff).
 .
 Grap is a language for describing graphical displays of data. It
 provides such services as automatic scaling and labeling of axes,
 and for statements, if statements, and macros to facilitate user
 programmability. Grap is intended primarily for including graphs in
 documents prepared with groff or TeX, and is only marginally useful for
 elementary tasks in data analysis.


- `go-run`: Compile and run Go code without saving a binary.
- `daps`:  DocBook Authoring and Publishing Suite (DAPS)
 DAPS contains a set of stylesheets, scripts and makefiles that enable
 you to create HTML, PDF, EPUB and other formats from DocBook XML with a
 single command. It also contains tools to generate profiled source
 tarballs for distributing your XML sources for translation or review.
 .
 DAPS also includes tools that assist you when writing DocBook XML:
 linkchecker, validator, spellchecker, editor macros and stylesheets for
 converting DocBook XML.


- `ipaggcreate`: Produce aggregate statistics of TCP/IP dumps.
- `in-toto-run`: Generating link metadata while carrying out a supply chain step.
- `typeset`: Declare variables and give them attributes.
- `cups-config`: Show technical information about your CUPS print server installation.
- `kubectl-logs`: Show logs for containers in a pod.
- `doctl-account`: Retrieve information about Digital Ocean accounts.
- `helix`: Helix, A post-modern text editor, provides several modes for different kinds of text manipulation.
- `rtl_sdr`: Raw data recorder for RTL-SDR receivers.
- `az-term`: Manage marketplace agreement with marketplaceordering.
- `git-locked`: List locked files in a Git repository.
- `cbonsai`:  terminal-based bonsai tree generator
 cbonsai is a bonsai tree generator using ncurses. It intelligently creates,
 colors, and positions a bonsai tree, and is entirely configurable via CLI
 options.


- `az-tag`: Manage tags on a resource.
- `install-tl`: TeX Live cross-platform installer.
- `exercism`: Download and solve problems from the command-line.
- `tlmgr-platform`: Manage TeX Live platforms.
- `puppet-agent`:  configuration management system, agent
 Puppet is a configuration management system that allows you to define
 the state of your IT infrastructure, then automatically enforces the
 correct state.
 .
 This package contains the main Puppet libraries and the agent application.


- `npm-home`: Open the npm page, Yarn page, or GitHub repository of a package in the web browser.
- `pip-uninstall`: Uninstall Python packages.
- `todoman`:  Simple CalDAV-based todo manager
 Todoman is a simple, standards-based, cli todo (aka: task) manager. Todos are
 stored into icalendar files, which means you can sync them via CalDAV using,
 for example, vdirsyncer.


- `terraform-plan`: Generate and show Terraform execution plans.
- `git-unlock`: Unlock a file in a Git repository so it can be modified by a commit.
- `tlmgr-backup`: Manage backups of TeX Live packages.
- `tlmgr-path`: Add or remove symlinks for TeX Live executables, man pages and info pages.
- `git-lock`: Lock a file in a Git repository from being modified by a commit.
- `go-vet`: Check Go source code and report suspicious constructs (e.g. lint your Go source files).
- `glab-alias`: Manage GitLab CLI command aliases from the command-line.
- `zig`: The Zig compiler and toolchain.
- `pveperf`: A benchmarking tool in Proxmox Server. Gather CPU and hard disk performance data for the hard disk.
- `vzdump`: Backup Utility for virtual machines and containers.
- `typeorm`: A JavaScript ORM that can run on Node.js, browser, Cordova, Ionic, React Native, NativeScript, and Electron platforms.
- `glab-pipeline`: List, view, and run GitLab CI/CD pipelines.
- `in-toto-record`: Create a signed link metadata file to provide evidence for supply chain steps.
- `lsd`:  ls command with a lot of pretty colors and some other stuff
 Rewrite of GNU ls with lot of added features like colors, icons, tree-view,
 more formatting options etc. The project is heavily inspired by the super
 colorls project.


- `http-server-upload`: Zero-configuration command-line HTTP server which provides a lightweight interface to upload files.
- `warp-diag`: Diagnostic and feedback tool for Cloudflare's WARP service.
- `az-bicep`: Bicep CLI command group.
- `ykman`: The YubiKey Manager can be used to configure all aspects of the YubiKey.
- `git-sync`: Sync local branches with remote branches.
- `clifm`: The command line file manager.
- `racket`:  extensible programming language in the Scheme family
 Racket (previously PLT Scheme) is a programming language suitable for
 scripting and application development, including GUIs and web
 services.
 .
 It supports the creation of new programming languages through a rich,
 expressive syntax system. Supplied languages include Typed Racket,
 ACL2, FrTime, and Lazy Racket, and R6RS Scheme.
 .
 Racket includes the DrRacket programming environment, a virtual
 machine with a just-in-time compiler, tools for creating stand-alone
 executables, the Racket web server, extensive libraries, and
 documentation for both beginners and experts.


- `clang-tidy`:  clang-based C++ linter tool
 Provide an extensible framework for diagnosing and fixing typical programming
 errors, like style violations, interface misuse, or bugs that can be deduced
 via static analysis. clang-tidy is modular and provides a convenient interface
 for writing new checks.
 .
 This is a dependency package providing the clang tidy tool.


- `plenv`: Switch between multiple versions of Perl.
- `jadx`:  Dex to Java decompiler
 This package contains a Dex to Java decompiler. It contains a command line and
 GUI tools for produce Java source code from Android Dex and Apk files.
 .
 Main features:
    - decompile Dalvik bytecode to java classes from APK, dex, aar and zip files
    - decode AndroidManifest.xml and other resources from resources.arsc
    - deobfuscator included
 .
 jadx-gui features:
    - view decompiled code with highlighted syntax
    - jump to declaration
    - find usage
    - full text search


- `warp-cli`: Official command-line client for Cloudflare's WARP service.
- `glab-repo`: Work with GitLab repositories on the command-line.
- `git-sed`: Replace patterns in git-controlled files using sed.
- `d8`: Developer shell for the V8 JavaScript engine.
- `llvm-cat`: Concatenate LLVM Bitcode (`.bc`) files.
- `in-toto-sign`: Sign in-toto link or layout metadata or verify their signatures.
- `elvish`:  Powerful scripting language & versatile interactive shell
 Elvish is a cross-platform shell, supporting Linux, BSDs and Windows.
 It features an expressive programming language, with features like namespace
 and anonymous functions, and a fully programmable user interface with friendly
 defaults. It is suitable for both interactive use and scripting.


- `bundler`:  Manage Ruby application dependencies
 Bundler manages a Ruby application's dependencies through its entire
 life, across many machines, systematically and repeatably.
 .
 This is a dependency package which depends on a full Ruby development
 environment, it is targeted at application developers.


- `pvecm`: Proxmox VE Cluster Manager.
- `git-coauthor`: Add another author to the latest commit. Since this command rewrites the Git history, `--force` will be needed when pushing next time.
- `jmtpfs`:  FUSE based filesystem for accessing MTP devices
 jmtpfs is a FUSE and libmtp-based filesystem for accessing MTP (Media Transfer
 Protocol) devices. It was specifically designed for exchanging files between
 Linux (and Mac OS X) systems and newer Android devices that support MTP but
 not USB Mass Storage.
 .
 The goal is to create a well-behaved filesystem, allowing tools like find and
 rsync to work as expected. To enable certain Android apps to detect and use
 the transferred files, MTP file types are set automatically based on file
 contents using libmagic.


- `pve-firewall`: Manage Proxmox VE Firewall.
- `rscript`: Run a script with the R programming language.
- `dune`: A build system for OCaml programs.
- `docker-commit`: Create a new image from a container’s changes.
- `tcsh`:  TENEX C Shell, an enhanced version of Berkeley csh
 The TENEX C Shell is an enhanced version of the Berkeley Unix C shell.
 It includes all features of 4.4BSD C shell, plus a command-line editor,
 programmable word completion, spelling correction and more.


- `volta`: A JavaScript Tool Manager that installs Node.js runtimes, npm and Yarn package managers, or any binaries from npm.
- `hashid`:  Identify the different types of hashes used to encrypt data
 Identify the different types of hashes used to encrypt data and especially
 passwords.
 .
 hashID is a tool written in Python 3.x which supports the identification of
 over 175 unique hash types using regular expressions.
 It is able to identify a single hash or parse a file and identify the hashes
 within it.
 There is also a nodejs version of hashID available which is easily set up to
 provide online hash identification.


- `tlmgr-shell`: Start an interactive shell of the native TeX Live manager.
- `git-clear`: Clear a Git working directory as if it was freshly cloned with the current branch including files in `.gitignore`.
- `rekor-cli`: Immutable tamper resistant ledger of metadata generated within a software projects supply chain.
- `glab-issue`: Manage GitLab issues from the command-line.
- `nvm.fish`: Install, uninstall, or switch between Node.js versions under the `fish` shell.
- `scan-build`: Command-line utility to run a static analyzer over a codebase as part of performing a regular build.
- `llvm-nm`: This command is an alias of `nm`.
- `py-spy`: A sampling profiler for Python programs.
- `pg_dumpall`: Extract a PostgreSQL database cluster into a script file or other archive file.
- `az-lock`: Manage Azure locks.
- `gh-screensaver`: Extension for GitHub CLI that runs animated terminal screensavers.
- `doctl-compute-droplet`: List, create, and delete virtual machines which are called droplets.
- `doctl-apps`: Used to manage digitalocean apps.
- `timidity`:  Software sound renderer (MIDI sequencer, MOD player)
 TiMidity++ is a very high quality software-only MIDI sequencer and MOD player.
 It uses sound fonts (GUS-compatible or SF2-compatible) to render MIDI files,
 which are not included in this package.
 .
   * Plays MIDI files without any external MIDI instruments at all
   * Understands SMF, RCP/R36/G18/G36, MFI, RMI (MIDI)
   * Autodetects and supports GM/GS/XG MIDI
   * Understands MOD, XM, S3M, IT, 699, AMF, DSM, FAR, GDM,
     IMF, MED, MTM, STM, STX, ULT, UNI (MOD)
   * Does MOD to MIDI conversion (including playback)
   * Outputs audio into various audio file formats: WAV, au, AIFF,
     Ogg (Vorbis, FLAC, Speex)
   * Supports JACK, ALSA and AO drivers
   * Uses Gravis Ultrasound compatible patch files and SoundFont2 patch
     files as the voice data for MIDI instruments
   * Supports playing from archives (zip, lzh, tar...).
   * Timidity++ can be used as an ALSA sequencer device


- `declare`: Declare variables and give them attributes.
- `husky`: Native Git hooks made easy.
- `jhsdb`: Attach to a Java process or launch a postmortem debugger to analyze the core dump from a crashed Java Virtual Machine.
- `auditd`:  User space tools for security auditing
 The audit package contains the user space utilities for
 storing and searching the audit records generated by
 the audit subsystem in the Linux 2.6 kernel.
 .
 Also contains the audit dispatcher "audisp".


- `git-mr`: Check out GitLab merge requests locally.
- `p10k`: Manage configurations for powerlevel10k.
- `llvm-ar`: This command is an alias of `ar`.
- `hardhat`: A development environment for Ethereum software.
- `mp3info`:  MP3 technical info viewer and ID3 1.x tag editor
 MP3Info has an interactive mode (using curses) and a command line mode.
 MP3Info can display ID3 tag information as well as various technical aspects
 of an MP3 file including playing time, bit-rate, sampling frequency and other
 attributes in a pre-defined or user-specifiable output format.


- `termdown`: Countdown timer and stopwatch for the command-line.
- `tlmgr-update`: Update TeX Live packages.
- `ngs`: Scripting language created specifically for Ops.
- `kubectl-delete`: Delete Kubernetes resources.
- `aws-rds`: CLI for AWS Relational Database Service.
- `cosign`:  Container Signing using Sigstore (program)
 This package contains a tool to sign OCI containers (and other artifacts)
 using Sigstore (https://sigstore.dev/)!
 .
 Cosign aims to make signatures **invisible infrastructure**.
 .
 Cosign supports:
 .
  * "Keyless signing" with the Sigstore public good Fulcio certificate
    authority and Rekor transparency log (default)
  * Hardware and KMS signing
  * Signing with a cosign generated encrypted private/public keypair
  * Container Signing, Verification and Storage in an OCI registry.
  * Bring-your-own PKI


- `solcjs`: A set of JavaScript bindings for the Solidity compiler.
- `mpd`:  Music Player Daemon
 Music Player Daemon (MPD) is a server that allows remote access for
 playing audio files (Ogg-Vorbis, FLAC, MP3, Wave, and AIFF), streams
 (Ogg-Vorbis, MP3) and managing playlists.  Gapless playback, buffered
 output, and crossfading support is also included.  The design focus is
 on integrating a computer into a stereo system that provides control
 for music playback over a TCP/IP network.  The goals are to be easy to
 install and use, to have minimal resource requirements (it has been
 reported to run fine on a Pentium 75), and to remain stable and
 flexible.
 .
 The daemon is controlled through a client which need not run on the
 same computer mpd runs on.  The separate client and server design
 allows users to choose a user interface that best suites their tastes
 independently of the underlying daemon (this package) which actually
 plays music.


- `keychain`:  key manager for OpenSSH
 Keychain is an OpenSSH key manager, typically run from ~/.bash_profile. When
 keychain is run, it checks for a running ssh-agent, otherwise it starts one.
 It saves the ssh-agent environment variables to ~/.keychain/\$\{HOSTNAME\}-sh,
 so that subsequent logins and non-interactive shells such as cron jobs can
 source the file and make passwordless ssh connections.  In addition, when
 keychain runs, it verifies that the key files specified on the command-line
 are known to ssh-agent, otherwise it loads them, prompting you for a password
 if necessary.


- `nx`: CLI utility for managing `nx` workspaces.
- `agate`: A simple server for the Gemini network protocol.
- `local`: Declare local variables and give them attributes.
- `docker-slim`: Analyze and optimize Docker images.
- `timetrap`: Simple command-line time tracker written in Ruby.
- `tlmgr-remove`: Uninstall TeX Live packages.
- `omz`: Oh My Zsh command-line tool.
- `go-tool`: Run a specific Go tool or command.
- `rcat`: This command is an alias of `rc`.
- `helm-install`: Install a helm chart.
- `cvs`:  Concurrent Versions System
 CVS is a version control system, which allows you to keep access
 to old versions  of files (usually source code), keep a log of
 who, when, and why changes occurred, etc., like RCS or SCCS.
 It handles multiple developers, multiple directories, triggers to
 enable/log/control various operations, and can work over a wide
 area network. The texinfo manual provides further information on
 more tasks that it can perform.
 .
 There are some tasks that are not covered by CVS. They can be done in
 conjunction with CVS but will tend to require some script-writing and
 software other than CVS. These tasks are bug-tracking, build management
 (that is, make and make-like tools), and automated testing. However,
 CVS makes these tasks easier.
 .
 This package contains a CVS binary which can act as both client and
 server, although there is no CVS dæmon; to access remote repositories,
 please use :extssh: not :pserver: any more.


- `ipsumdump`: Summarise TCP/IP dumps into a human and machine readable ASCII format.
- `ddgr`:  DuckDuckGo from the terminal
 Features
 .
  - Fast and clean (no ads, stray URLs or clutter), custom color
  - Navigate result pages from omniprompt, open URLs in browser
  - Search and option completion scripts for Bash, Zsh and Fish
  - DuckDuckGo Bang support (along with completion)
  - Open the first result directly in browser (as in I'm Feeling Ducky)
  - Non-stop searches: fire new searches at omniprompt without exiting
  - Keywords (e.g. filetype:mime, site:somesite.com) support
  - Specify region, disable safe search
  - HTTPS proxy support, Do Not Track set, optionally disable User Agent
  - Support custom url handler script or cmdline utility
  - Comprehensive documentation, man page with handy usage examples
  - Minimal dependencies


- `ydotool`: Generic command-line automation tool
- `wtype`:  xdotool type for wayland
 wtype is the Wayland pendant for xdotool. It only works with Wayland
 compositors that support the virtual keyboard protocol. It lets you
 programmatically (or manually) simulate keyboard input.


- `skate`: personal key value store
- `nb`: command line and local web note‑taking, bookmarking, archiving, and knowledge base application
- `pgcli`:  CLI for PostgreSQL with auto-completion and syntax highlighting
 pgcli is a command line interface for PostgreSQL with auto-completion and
 syntax highlighting. It is also capable of pretty printing tabular data.


- `bit`: Bit is a modern Git CLI
- `timetrace`: timetrace is a simple CLI for tracking your time
- `alt`: attempts to find "alternate" for path
- `skim`: Fuzzy Finder in rust
- `shotgun`: Minimal X screenshot utility
- `ripgreb`: ripgrep recursively searches directories for a regex pattern while respecting your gitignore
- `mdcat`: cat for markdown
- `bb`:  ASCII-art demo based on AAlib
 This package contains a 'high quality audio-visual demonstration'
 of ASCII-art using AAlib, a portable ASCII-art graphics library.
 This demonstration can be displayed in a text- or X11-terminal.


- `litecli`:  CLI for SQlite with auto-completion and syntax highlighting
 litecli is a command line interface for SQlite with auto-completion and
 syntax highlighting. It is also capable of pretty printing tabular data.


- `dog`: Command Line DNS Client for DNS Lookup
- `dasel`:  Query, update and convert data structures from the command line (program)
 Dasel (short for data-selector) allows you to query and modify data
 structures using selector strings.
 .
 Comparable to jq / yq, but supports JSON, YAML, TOML, XML and CSV with
 zero runtime dependencies.
 .
 This package installs the command-line tool.


- `fx`: Command-line tool and terminal JSON viewer
- `jo`:  command-line processor to output JSON from a shell
 jo creates a JSON string on stdout from words given it as arguments
 or read from stdin. It can generate both arrays and objects. Here is
 a short example:
 .
  $ jo -p name=jo n=17 parser@0
  {
     "name": "jo",
     "n": 17,
     "parser": false
  }


- `jql`: querying data from JSON files
- `jshon`:  Command line tool to parse, read and create JSON
 Jshon is a command line utility to parse, read and create JSON. It is
 designed to be as usable as possible from within the shell and replaces
 fragile adhoc parsers made from grep/sed/awk as well as heavyweight
 one-line parsers made from Perl/Python. Jshon loads json text from stdin,
 performs actions, then displays the last action on stdout.
 .
 Json parsing features include:
  Return data types of values
  Report data type lengths
  Sort JSON data by keys
  In-place editing of JSON files
  Format or "beautify" JSON (as changing indentation, etc)
  Create JSON from an empty object
  Extraction of keys and values


- `emuto`: manipulate JSON files
- `markdown`:  Text-to-HTML conversion tool
 Markdown is a text-to-HTML conversion tool for web writers.  It
 allows you to write using an easy-to-read, easy-to-write plain text
 format, then convert it to structurally valid XHTML (or HTML).


- `coinmon`: cryptocurrency price tool on CLI
- `rogue`: Exploring The Dungeons of Doom
- `2048`:  Slide and add puzzle game for text mode
 The 2048 game is a mathematics based puzzle game where you have to
 slide tiles in a 4x4 board in any of the four possible directions.
 Touching tiles with the same value are then merged into tiles with the
 added value of the merged ones. You start with a couple of 2-valued
 tiles and new tiles appear randomly after sliding. The target of the
 game is to reach a tile with a value of 2048 before the board is full.


- `gif2webp`: Convert a GIF image to WebP
- `img2webp`: Create animated WebP file from a sequence of input images
- `nbsudoku`: sudoku cli game
- `nbsos`: sos cli game
- `nbreversi`: reversi cli game
- `nbpipes`: pipes cli game
- `nbmemoblocks`: memory cli game
- `nbfifteen`: fifteen cli game
- `nbcheckers`: checkers cli game
- `nbbattleship`: battleship cli game
- `nbmines`: mines cli game
- `distrobox-list`: List available Distrobox containers. It detects them and lists them separately from the rest of normal podman or Docker containers.
- `distrobox-enter`: Run a command in a Distrobox container.
- `nmcli-radio`: Show radio switches status or enable and disable switches.
- `gnome-software`:  Software Center for GNOME
 Software lets you install and update applications and system extensions.
 .
 Software uses a plugin architecture to separate the frontend from the
 technologies that are used underneath. Currently, a PackageKit plugin provides
 data from a number of traditional packaging systems, such as rpm or apt. An
 appdata plugin provides additional metadata from locally installed data in the
 appdata format.


- `distrobox-rm`: Delete Distrobox containers.
- `checkupdates`: Tool to check pending updates in Arch Linux.
- `dm-tool`: A tool to communicate with the display manager.
- `nmcli-agent`: Run nmcli as a NetworkManager secret agent or polkit agent.
- `createrepo`: Initializes an RPM repository in the given directory, including all XML and SQLite files.
- `krita`:  pixel-based image manipulation program
 Krita is a creative application for raster images. Whether you want to create
 from scratch or work with existing images, Krita is for you. You can work with
 photos or scanned images, or start with a blank slate. Krita supports most
 graphics tablets out of the box.
 .
 Krita is different from other graphics design programs in that it has
 pluggable brush engines, some supporting brush resources like Gimp brush files,
 others offering sophisticated simulation of real brushes, and others again
 offering color mixing and image deformations. Moreover, Krita has full
 support for graphics tablets, including such features as pressure, tilt and
 rate, making it a great choice for artists. There are easy to use tools for
 drawing lines, ellipses and rectangles, and the freehand tool is supported by
 pluggable "drawing assistants" that help you draw shapes that still have a
 freehand feeling to them.


- `checkupdates-aur`: Tool to check pending updates from the Arch User Repository (AUR).
- `ispell`:  International Ispell (an interactive spelling corrector)
 Ispell corrects spelling in plain text, LaTeX, sgml/html/xml, and nroff files.
 [x]Emacs and jed have nice interfaces to ispell, and ispell works from many
 other tools and from the command line as well.
 .
 No ispell dictionaries are included in this package; you must install
 at least one of them ("iamerican" is recommended by default for no good
 reason); install the "ispell-dictionary" package(s) for the language(s)
 you and your users will want to spell-check.
 .
 It's a good idea to install "word list" package(s) for the same language(s),
 because they'll be used by ispell's (L)ookup command.


- `batcat`: This command is an alias of `bat`.
- `ubuntu-security-status`: Display information about security support for installed Ubuntu packages.
- `trace-cmd`:  Utility for retrieving and analyzing function tracing in the kernel
 This package contains the trace-cmd utility. Trace-cmd makes it easy to
 retrieve and analyze function traces from the Linux kernel while it is running.


- `trust`: Tool for operating on the trust policy store.
- `mpg123`:  MPEG layer 1/2/3 audio player
 mpg123 is a real time MPEG 1.0/2.0/2.5 audio player/decoder for layers
 1, 2 and 3 (MPEG 1.0 layer 3 also known as MP3).
 .
 This package contains output plugins for several audio systems, including
 OSS4, the Advanced Linux Sound Architecture (ALSA), JACK, PortAudio,
 PulseAudio, OpenAL and the Network Audio System (NAS).


- `pw-link`: Manage links between ports in PipeWire.
- `distrobox-create`: Create Distrobox containers with an input name and image.
- `wpm`: Typeracer-like console app for measuring your WPM.
- `ivpn`: Command-line interface for the IVPN client.
- `tailscale-file`: Send files across connected devices on a Tailscale network.
- `lerna`: A tool for managing JavaScript projects with multiple packages.
- `fastmod`: A fast partial replacement for the codemod tool, replace and replace all in the whole codebase.
- `mh_lint`: Attempt to find bugs in MATLAB or Octave code.
- `rga`: Ripgrep wrapper with rich file type searching capabilities.
- `webstorm`: The JetBrains JavaScript IDE.
- `mk`: Task runner for targets described in Mkfile.
- `yt-dlp`:  downloader of videos from YouTube and other sites
 yt-dlp is a youtube-dl fork based on the now inactive youtube-dlc.
 The main focus of this project is adding new features and patches
 while also keeping up to date with the original project.
 .
 yt-dlp is a small command-line program to download videos from
 YouTube.com and other sites that don't provide direct links to the
 videos served.
 .
 yt-dlp allows the user, among other things, to choose a specific video
 quality to download (if available) or let the program automatically
 determine the best (or worst) quality video to grab. It supports
 downloading entire playlists and all videos from a given user.
 .
 Currently supported sites (or features of sites) are:
 .
 17live, 1News, 1tv, 20min, 23video, 247sports, 24tv.ua, 3qsdn, 3sat,
 4tube, 56.com, 6play, 7plus, 8tracks, 9c9media, 9gag, 9News, 9now.com.au,
 abc.net.au, abcnews, abcotvs, AbemaTV, AbemaTVTitle, acast, AcFunBangumi,
 AcFunVideo, ADN, ADNSeason, AdobeConnect, adobetv, AdultSwim, aenetworks,
 AeonCo, AirTV, AitubeKZVideo, AliExpressLive, AlJazeera, Allocine,
 Allstar, AllstarProfile, AlphaPorno, Alsace20TV, Alsace20TVEmbed,
 altcensored, Alura, AluraCourse, AmadeusTV, Amara, AmazonMiniTV,
 AmazonReviews, AmazonStore, AMCNetworks, AmericasTestKitchen,
 AmericasTestKitchenSeason, AmHistoryChannel, AnchorFMEpisode,
 anderetijden, Angel, AnimalPlanet, Anvato, aol.com, APA, Aparat,
 AppleConnect, AppleDaily, ApplePodcasts, appletrailers, archive.org,
 ArcPublishing, ARD, ARDMediathek, ARDMediathekCollection, Arkena,
 Art19, Art19Show, arte.sky.it, ArteTV, ArteTVCategory, ArteTVEmbed,
 ArteTVPlaylist, asobichannel, AsobiStage, AtresPlayer, AtScaleConfEvent,
 ATVAt, AudiMedia, AudioBoom, audiomack, Audius, AWAAN, axs.tv, AZMedien,
 BaiduVideo, BanBye, BanByeChannel, bandaichannel, Bandcamp, Bandlab,
 BandlabPlaylist, BannedVideo, bbc, bbc.co.uk, BBVTV, BBVTVLive,
 BBVTVRecordings, BeaconTv, BeatBumpPlaylist, BeatBumpVideo, Beatport,
 Beeg, BehindKink, Bellator, BellMedia, BerufeTV, Bet, bfmtv, Bigflix,
 Bigo, Bild, BiliBili, Bilibili category extractor, BilibiliAudio,
 BilibiliAudioAlbum, BiliBiliBangumi, BiliBiliBangumiMedia,
 BiliBiliBangumiSeason, BilibiliCheese, BilibiliCheeseSeason,
 BilibiliCollectionList, BiliBiliDynamic, BilibiliFavoritesList,
 BiliBiliPlayer, BilibiliPlaylist, BiliBiliSearch, BilibiliSeriesList,
 BilibiliSpaceAudio, BilibiliSpaceVideo, BilibiliWatchlater, BiliIntl,
 BiliLive, BioBioChileTV, Biography, BitChute, BitChuteChannel,
 BlackboardCollaborate, BleacherReport, BleacherReportCMS, blerp,
 blogger.com, Bloomberg, Bluesky, BokeCC, BongaCams, Boosty, BostonGlobe,
 Box, BoxCastVideo, Bpb, BR, BrainPOP, BrainPOPELL, BrainPOPEsp,
 BrainPOPFr, BrainPOPIl, BrainPOPJr, BravoTV, BreitBart, Bundesliga,
 Bundestag, BusinessInsider, BuzzFeed, BYUtv, CaffeineTV, Callin,
 Caltrans, CAM4, Camdemy, CamdemyFolder, CamFMEpisode, CamFMShow,
 CamModels, Camsoda, CamtasiaEmbed, Canal1, CanalAlpha, canalc2.tv,
 Canalplus, CaracolTvPlay, CartoonNetwork, cbc.ca, CBS, CBSLocal,
 CBSLocalArticle, CBSLocalLive, cbsnews, cbssports, CCMA, CCTV, CDA,
 CDAFolder, Cellebrite, CeskaTelevize, CGTN, CharlieRose, Chaturbate,
 Chilloutzone, cielotv.it, Cinemax, CinetecaMilano, Cineverse,
 CineverseDetails, CiscoLiveSearch, CiscoLiveSession, ciscowebex,
 CJSW, Clipchamp, Clippit, ClipRs, ClipYouEmbed, CloserToTruth,
 CloudflareStream, CloudyCDN, Clubic, Clyp, cmt.com, CNBCVideo, CNN,
 CNNIndonesia, ComedyCentral, ComedyCentralTV, ConanClassic, CondeNast,
 CONtv, CookingChannel, Corus, Coub, CozyTV, cp24, cpac, Cracked, Crackle,
 Craftsy, CrooksAndLiars, CrowdBunker, CrowdBunkerChannel, Crtvg, CSpan,
 CSpanCongress, CtsNews, CTV, CTVNews, cu.ntv.co.jp, CultureUnplugged,
 curiositystream, CWTV, Cybrary, CybraryCourse, DacastPlaylist, DacastVOD,
 DagelijkseKost, DailyMail, dailymotion, DailyWire, DailyWirePodcast,
 dangalplay, daum.net, DBTV, DctpTv, DeezerAlbum, DeezerPlaylist,
 democracynow, DestinationAmerica, DetikEmbed, DeuxM, DeuxMNews, DHM,
 DigitalConcertHall, DigitallySpeaking, Digiteka, DiscogsReleasePlaylist,
 DiscoveryLife, DiscoveryNetworksDe, DiscoveryPlus, DiscoveryPlusIndia,
 DiscoveryPlusIndiaShow, DiscoveryPlusItaly, DiscoveryPlusItalyShow,
 Disney, dlf, Douyin, DouyuShow, DouyuTV, DPlay, DRBonanza, Drooble,
 Dropbox, Dropout, DropoutSeason, DrTalks, DrTuber, drtv, DTube,
 duboku, Dumpert, Duoplay, dvtv, dw, EaglePlatform, EbaumsWorld,
 Ebay, EinsUndEinsTV, EinsUndEinsTVLive, EinsUndEinsTVRecordings,
 eitb.tv, ElementorEmbed, Elonet, ElPais, ElTreceTV, Embedly, EMPFlix,
 Epicon, EpiconSeries, EpidemicSound, eplus, Epoch, Eporner, Erocast,
 EroProfile, ERRJupiter, ertflix, ESPN, ESPNArticle, ESPNCricInfo,
 EttuTv, Europa, EuroParlWebstream, EuropeanTour, Eurosport,
 EUScreen, EWETV, EWETVLive, EWETVRecordings, Expressen, EyedoTV,
 facebook, FacebookPluginsVideo, Fathom, faz.net, fc2, Fczenit, Fifa,
 filmon, Filmweb, FiveThirtyEight, FiveTV, FlexTV, Flickr, Floatplane,
 FloatplaneChannel, Folketinget, FoodNetwork, FootyRoom, Formula1, FOX,
 FOX9, FOX9News, foxnews, FoxNewsVideo, FoxSports, fptplay, FranceCulture,
 FranceInter, FranceTV, francetvinfo.fr, FranceTVSite, Freesound,
 freespeech.org, FreeTvMovies, FrontendMasters, FrontendMastersCourse,
 FrontendMastersLesson, FujiTVFODPlus7, Funk, Funker530, Fux, FuyinTV,
 Gab, GabTV, Gaia, GameDevTVDashboard, GameJolt, GameJoltCommunity,
 GameJoltGame, GameJoltGameSoundtrack, GameJoltSearch, GameJoltUser,
 GameSpot, GameStar, Gaskrank, Gazeta, GBNews, GDCVault, GediDigital,
 gem.cbc.ca, generic, Genius, GeniusLyrics, Germanupa, GetCourseRu,
 GetCourseRuPlayer, Gettr, GettrStreaming, GiantBomb, GlattvisionTV,
 GlattvisionTVLive, GlattvisionTVRecordings, Glide, GlobalPlayerAudio,
 GlobalPlayerAudioEpisode, GlobalPlayerLive, GlobalPlayerLivePlaylist,
 GlobalPlayerVideo, Globo, GloboArticle, glomex, GMANetworkVideo, Go,
 GoDiscovery, GodResource, GodTube, Gofile, Golem, GoogleDrive, GoPlay,
 GoPro, Goshgay, GoToStage, GPUTechConf, Graspop, Gronkh, Groupon,
 Harpodeon, hbo, HearThisAt, Heise, HellPorno, hetklokhuis, HGTVDe,
 HGTVUsa, HiDive, HistoricFilms, HitRecord, hketv, HollywoodReporter,
 HollywoodReporterPlaylist, Holodex, HotNewHipHop, hotstar, hrfernsehen,
 HRTi, HRTiPlaylist, HSEProduct, HSEShow, html5, Huajiao, HuffPost,
 Hungama, HungamaAlbumPlaylist, HungamaSong, Hypem, Hytale, Icareus,
 IdolPlus, IflixSeries, ign.com, IGNArticle, IGNVideo, iheartradio,
 IlPost, Iltalehti, imdb, Imgur, Ina, Inc, IndavideoEmbed, InfoQ,
 Instagram, InstagramIOS, Internazionale, InternetVideoArchive,
 InvestigationDiscovery, IPrima, IPrimaCNN, iq.com, iqiyi, IslamChannel,
 IslamChannelSeries, IsraelNationalNews, ITProTV, ITProTVCourse, ITV,
 ITVBTCC, ivi, ivideon, IVXPlayer, iwara, Ixigua, Izlesene, Jamendo,
 JamendoAlbum, JeuxVideo, jiocinema, Joj, JoqrAg, Jove, JStream, JTBC,
 JWPlatform, Kakao, Kaltura, KankaNews, Karaoketv, Katsomo, KelbyOne,
 Kenh14Playlist, Kenh14Video, Ketnet, khanacademy, Kicker, KickStarter,
 Kika, KinoPoisk, Kommunetv, KompasVideo, Koo, KrasView, KTH, Ku6,
 KukuluLive, la7.it, laracasts, LastFM, LastFMPlaylist, LastFMUser,
 LaXarxaMes, lbry, LCI, Lcp, LcpPlay, Le, LearningOnScreen, Lecture2Go,
 Lecturio, LecturioCourse, LecturioDeCourse, LeFigaroVideoEmbed,
 LeFigaroVideoSection, LEGO, Lemonde, Lenta, LePlaylist, LetvCloud,
 Libsyn, life, likee, limelight, LinkedIn, Liputan6, ListenNotes, LiTV,
 LiveJournal, livestream, Livestreamfails, Lnk, loc, loom, LoveHomePorn,
 LRTStream, LRTVOD, LSMLREmbed, LSMLTVEmbed, LSMReplay, Lumni, lynda,
 maariv.co.il, MagellanTV, MagentaMusik, mailru, MainStreaming,
 MangoTV, ManotoTV, ManotoTVLive, ManotoTVShow, ManyVids, MaoriTV,
 Markiza, MarkizaPage, massengeschmack.tv, Masters, MatchTV, MBN, MDR,
 MedalTV, media.ccc.de, Mediaite, MediaKlikk, Medialaan, Mediaset,
 MediasetShow, Mediasite, MediasiteCatalog, MediasiteNamedCatalog,
 MediaStream, MediaWorksNZVOD, Medici, megaphone.fm, megatvcom,
 Meipai, MelonVOD, Metacritic, mewatch, MicrosoftBuild, MicrosoftEmbed,
 MicrosoftLearnEpisode, MicrosoftLearnPlaylist, MicrosoftLearnSession,
 MicrosoftMedius, microsoftstream, minds, Minoto, mirrativ, MirrorCoUK,
 MiTele, mixch, mixcloud, MLB, MLBArticle, MLBTV, MLBVideo, MLSSoccer,
 MNetTV, MNetTVLive, MNetTVRecordings, MochaVideo, Mojevideo, Mojvideo,
 Monstercat, MonsterSirenHypergryphMusic, Motherless, MotherlessGallery,
 MotherlessGroup, MotherlessUploader, Motorsport, MovieFap, Moviepilot,
 MoviewPlay, Moviezine, MovingImage, MSN, mtg, mtv, mtv.de, mtv.it,
 mtvjapan, MTVUutisetArticle, MuenchenTV, MujRozhlas, Murrtube,
 MurrtubeUser, MuseAI, MuseScore, MusicdexAlbum, MusicdexArtist,
 MusicdexPlaylist, MusicdexSong, Mx3, Mx3Neo, Mx3Volksmusik, Mxplayer,
 MxplayerShow, MySpace, MySpass, MyVideoGe, MyVidster, Mzaalo,
 n-tv.de, N1InfoAsset, Nate, NateProgram, NationalGeographicTV, Naver,
 navernow, nba, NBC, NBCNews, nbcolympics, NBCSports, NBCSportsStream,
 NBCSportsVPlayer, NBCStations, ndr, NDTV, NekoHacker, NerdCubedFeed,
 Nest, NestClip, NetPlusTV, NetPlusTVLive, NetPlusTVRecordings, Netverse,
 NetversePlaylist, NetverseSearch, Netzkino, Newgrounds, NewsPicks,
 Newsy, NextMedia, NextMediaActionNews, NextTV, Nexx, NexxEmbed, nfb,
 NFHSNetwork, nfl.com, NhkForSchoolBangumi, NhkForSchoolProgramList,
 NhkForSchoolSubject, NhkRadioNewsPage, NhkRadiru, NhkRadiruLive,
 NhkVod, NhkVodProgram, nhl.com, nick.com, nick.de, nickelodeonru,
 niconico, NiconicoChannelPlus, NiconicoUser, NinaProtocol, Nintendo,
 Nitter, njoy, NobelPrize, NoicePodcast, NonkTube, NoodleMagazine,
 Noovo, NOSNLArticle, Nova, NovaEmbed, NovaPlay, nowness, Noz, npo,
 Npr, NRK, NRKPlaylist, NRKRadioPodkast, NRKSkole, NRKTV, NRKTVDirekte,
 NRKTVEpisode, NRKTVEpisodes, NRKTVSeason, NRKTVSeries, NRLTV, nts.live,
 ntv.ru, NubilesPorn, Nuvid, NYTimes, NYTimesArticle, NYTimesCookingGuide,
 NYTimesCookingRecipe, nzherald, NZOnScreen, NZZ, ocw.mit.edu,
 Odnoklassniki, OfTV, OfTVPlaylist, OktoberfestTV, OlympicsReplay,
 on24, OnDemandChinaEpisode, OnDemandKorea, OnDemandKoreaProgram,
 OneFootball, OnePlacePodcast, onet.pl, onet.tv, OnetMVP, OnionStudios,
 Opencast, OpencastPlaylist, openrec, OraTV, OsnatelTV, OsnatelTVLive,
 OsnatelTVRecordings, OutsideTV, OwnCloud, PacktPub, PacktPubCourse,
 Panopto, PanoptoList, PanoptoPlaylist, ParamountNetwork, ParamountPlus,
 ParamountPlusSeries, ParamountPressExpress, Parler, parliamentlive.tv,
 Parlview, patreon, pbs, PBSKids, PearVideo, PeekVids, peer.tv, PeerTube,
 peloton, PerformGroup, periscope, PGATour, PhilharmonieDeParis,
 phoenix.de, Photobucket, PiaLive, Piapro, Picarto, PicartoVod, Piksel,
 Pinkbike, Pinterest, PinterestCollection, PiramideTV, PiramideTVChannel,
 Pladform, PlanetMarathi, Platzi, PlatziCourse, player.sky.it, playeur,
 PlayPlusTV, PlaySuisse, Playtvak, PlayVids, Playwire, pluralsight,
 PlutoTV, PlVideo, PodbayFM, PodbayFMChannel, Podchaser, podomatic,
 PokerGo, PokerGoCollection, PolsatGo, PolskieRadio, Popcorntimes,
 PopcornTV, Pornbox, PornerBros, PornFlip, PornHub, PornHubPagedVideoList,
 PornHubPlaylist, PornHubUser, PornHubUserVideosUpload, Pornotube,
 PornoVoisines, PornoXO, PornTop, PornTube, Pr0gramm, PrankCast,
 PrankCastPost, PremiershipRugby, PressTV, ProjectVeritas, prosiebensat1,
 PRXAccount, PRXSeries, PRXStory, puhutv, Puls4, Pyvideo, QDance, QingTing,
 qqmusic, QuantumTV, QuantumTVLive, QuantumTVRecordings, R7, R7Article,
 Radiko, RadikoRadio, radio.de, Radio1Be, radiocanada, RadioComercial,
 RadioComercialPlaylist, radiofrance, RadioFranceLive, RadioFrancePodcast,
 RadioFranceProfile, RadioFranceProgramSchedule, RadioJavan, radiokapital,
 RadioRadicale, RadioZetPodcast, radlive, Rai, RaiCultura, RaiNews,
 RaiPlay, RaiPlayLive, RaiPlayPlaylist, RaiPlaySound, RaiPlaySoundLive,
 RaiPlaySoundPlaylist, RaiSudtirol, RayWenderlich, RayWenderlichCourse,
 RbgTum, RbgTumCourse, RbgTumNewCourse, RCS, RCSEmbeds, RCSVarious,
 RCTIPlus, RCTIPlusSeries, RCTIPlusTV, RDS, RedBull, RedBullEmbed,
 RedBullTV, RedBullTVRrnContent, redcdnlivx, Reddit, RedGifs,
 RedGifsSearch, RedGifsUser, RedTube, RENTV, RENTVArticle,
 Restudy, Reuters, ReverbNation, RheinMainTV, RideHome, RinseFM,
 RinseFMArtistPlaylist, RMCDecouverte, RockstarGames, Rokfin,
 RoosterTeeth, RoosterTeethSeries, RottenTomatoes, Rozhlas,
 RozhlasVltava, RTBF, RTDocumentry, RTDocumentryPlaylist, rte, rtl.nl,
 rtl2, RTLLuLive, RTLLuRadio, RTNews, RTP, RTRFM, RTS, RTVCKaltura,
 RTVCPlay, RTVCPlayEmbed, RTVS, rtvslo.si, RudoVideo, Rule34Video,
 Rumble, RumbleChannel, RumbleEmbed, Ruptly, rutube, RUTV, Ruutu, Ruv,
 S4C, S4CSeries, safari, Saitosan, SAKTV, SAKTVLive, SAKTVRecordings,
 SaltTV, SaltTVLive, SaltTVRecordings, SampleFocus, Sangiin, Sapo,
 SBS, sbs.co.kr, schooltv, ScienceChannel, Screen9, Screencast,
 Screencastify, ScreencastOMatic, ScreenRec, ScrippsNetworks, Scrolller,
 SCTE, SCTECourse, sejm, Sen, SenalColombiaLive, SenateGov, SenateISVP,
 SendtoNews, Servus, Sexu, SeznamZpravy, SeznamZpravyArticle, Shahid,
 ShahidShow, SharePoint, ShareVideosEmbed, ShemarooMe, ShowRoomLive,
 ShugiinItvLive, ShugiinItvLiveRoom, ShugiinItvVod, SibnetEmbed,
 simplecast, Sina, Skeb, sky.it, SkylineWebcams, SkyNewsAU, Slideshare,
 SlidesLive, Slutload, Smotrim, SnapchatSpotlight, Snotr, Sohu,
 SohuV, SonyLIV, SonyLIVSeries, soop, soundcloud, SoundcloudEmbed,
 soundgasm, southpark.cc.com, southpark.de, southpark.lat, southpark.nl,
 southparkstudios.dk, SovietsCloset, SovietsClosetPlaylist, SpankBang,
 SpankBangPlaylist, Spiegel, Sport5, SportBox, SportDeutschland, spotify,
 Spreaker, SpreakerShow, SpringboardPlatform, Sprout, SproutVideo,
 SRGSSR, SRGSSRPlay, StacommuLive, StacommuVOD, StagePlusVODConcert,
 stanfordoc, StarTrek, startv, Steam, SteamCommunityBroadcast,
 Stitcher, StitcherShow, StoryFire, StoryFireSeries, StoryFireUser,
 Streamable, StreamCZ, StreetVoice, StretchInternet, Stripchat,
 Subsplash, Substack, SunPorno, SVT, SVTPage, SVTPlay, SVTSeries,
 SwearnetEpisode, Syfy, SYVDK, SztvHu, t-online.de, Tagesschau,
 TapTapApp, TapTapAppIntl, TapTapMoment, TapTapPostIntl, Tass, TBS,
 TBSJPEpisode, TBSJPPlaylist, TBSJPProgram, Teachable, TeachableCourse,
 teachertube, TeachingChannel, Teamcoco, TeamTreeHouse, techtv.mit.edu,
 TedEmbed, TedPlaylist, TedSeries, TedTalk, Tele13, Tele5, TeleBruxelles,
 TelecaribePlay, Telecinco, Telegraaf, TeleMB, Telemundo, TeleQuebec,
 TeleQuebecEmission, TeleQuebecLive, TeleQuebecSquat, TeleQuebecVideo,
 TeleTask, Telewebion, Tempo, TennisTV, TenPlay, TenPlaySeason, TF1,
 TFO, TheGuardianPodcast, TheGuardianPodcastPlaylist, TheHoleTv,
 TheIntercept, ThePlatform, ThePlatformFeed, TheStar, TheSun,
 TheWeatherChannel, ThisAmericanLife, ThisOldHouse, ThisVid,
 ThisVidMember, ThisVidPlaylist, ThreeSpeak, ThreeSpeakUser, TikTok,
 TLC, TMZ, TNAFlix, TNAFlixNetworkEmbed, toggle, toggo, ToonGoggles,
 tou.tv, Toypics, ToypicsUser, TrailerAddict, TravelChannel, Triller,
 TrillerShort, TrillerUser, Trovo, TrovoChannelClip, TrovoChannelVod,
 TrovoVod, TrtCocukVideo, TrtWorld, TrueID, TruNews, Truth, TruTV,
 Tube8, TubeTuGraz, TubeTuGrazSeries, tubitv, Tumblr, TuneInPodcast,
 TuneInPodcastEpisode, TuneInStation, tv.dfb.de, TV2, TV2Article,
 TV2DK, TV2DKBornholmPlay, tv2play.hu, tv2playseries.hu, TV4, TV5MONDE,
 tv5unis, tv8.it, TVANouvelles, TVANouvellesArticle, tvaplus, TVC,
 TVCArticle, TVer, tvigle, TVIPlayer, tvland.com, TVN24, TVNoe,
 tvp, TVPlayer, TVPlayHome, Tweakers, TwitCasting, TwitCastingLive,
 TwitCastingUser, TwitchCollection, TwitchVideos, TwitchVideosClips,
 TwitchVideosCollections, twitter, Txxx, udemy, UDNEmbed, UFCArabia,
 UFCTV, ukcolumn, UKTVPlay, UlizaPlayer, UlizaPortal, Unistra, Unity,
 uol.com.br, uplynk, Urort, URPlay, USANetwork, USAToday, ustream,
 ustudio, Varzesh3, Vbox7, Veo, Vesti, Vevo, VevoPlaylist, VGTV, vh1.com,
 vice, Viddler, Videa, video.arnes.si, video.sky.it, VideoDetective,
 videofy.me, VideoKen, VideoKenCategory, VideoKenPlayer, VideoKenPlaylist,
 VideoKenTopic, videomore, VideoPress, Vidflex, Vidio, VidioLive,
 VidioPremier, VidLii, Vidly, vids.io, Vidyard, viewlift, Viidea,
 viki, vimeo, ViMP, Viously, Viqeo, Viu, ViuOTTIndonesia, vk, VKPlay,
 VKPlayLive, vm.tiktok, Vocaroo, VODPl, VODPlatform, voicy, VolejTV,
 VoxMedia, VoxMediaVolume, vpro, VRT, VrtNU, VTM, VTV, VTVGo, VTXTV,
 VTXTVLive, VTXTVRecordings, VuClip, VVVVID, VVVVIDShow, Walla, WalyTV,
 WalyTVLive, WalyTVRecordings, washingtonpost, wat.tv, WatchESPN, WDR,
 WDRElefant, WDRPage, Webcamerapl, Webcaster, WebcasterFeed, WebOfStories,
 WebOfStoriesPlaylist, Weibo, WeiboUser, WeiboVideo, WeiqiTV, WeTvSeries,
 Weverse, WeverseLive, WeverseLiveTab, WeverseMedia, WeverseMediaTab,
 WeverseMoment, WeVidi, Weyyak, whowatch, Whyp, wikimedia.org, Wimbledon,
 WimTV, WinSportsVideo, Wistia, WistiaChannel, WistiaPlaylist, wnl,
 WorldStarHipHop, wppilot, WrestleUniversePPV, WrestleUniverseVOD,
 WSJ, WSJArticle, WWE, WyborczaPodcast, Xanimu, XboxClips, XHamster,
 XHamsterEmbed, XHamsterUser, XiaoHongShu, ximalaya, Xinpianchang, XMinus,
 XNXX, Xstream, XVideos, XXXYMovies, Yahoo, YandexDisk, YandexVideo,
 YandexVideoPreview, YapFiles, Yappy, YappyProfile, YleAreena, YouJizz,
 youku, YouNowChannel, YouNowLive, YouNowMoment, YouPorn, YouPornCategory,
 YouPornChannel, YouPornCollection, YouPornStar, YouPornTag, YouPornVideos,
 youtube, YoutubeLivestreamEmbed, YoutubeYtBe, Zaiko, ZaikoETicket, Zapiks,
 Zattoo, ZattooLive, ZattooMovies, ZattooRecordings, ZDF, ZDFChannel,
 Zee5, ZeeNews, ZenPorn, ZenYandex, ZenYandexChannel, ZetlandDKArticle,
 Zhihu, zingmp3, zoom, Zype, generic,


- `mcs`: Mono C# Compiler.
- `createdb`: Create a PostgreSQL database.
- `diff-pdf`: Tool for comparing two PDFs.
- `errno`: Look up errno names and descriptions.
- `kdig`: Advanced DNS lookup utility.
- `oathtool`:  OATH Toolkit oathtool command line tool
 OATH Toolkit provide components to build one-time password
 authentication systems.  It contains shared C libraries, command line
 tools and a PAM module.  Supported technologies include the
 event-based HOTP algorithm (RFC 4226), the time-based TOTP algorithm
 (RFC 6238), and Portable Symmetric Key Container (PSKC, RFC 6030) to
 manage secret key data.  OATH stands for Open AuTHentication, which is
 the organization that specify the algorithms.
 .
 This package contains the OATH Toolkit "oathtool" command line tool.


- `zek`: Generate a Go struct from XML.
- `cwebp`: Compress an image file to a WebP file.
- `gow`: Watches Go files and restarts the app on changes.
- `comby`: Tool for structural code search and replace that supports many languages.
- `turbo`: High-performance build system for JavaScript and TypeScript codebases.
- `git-standup`: See commits from a specified user.
- `serve`: Static file serving and directory listing.
- `glab-auth`: Authenticate with a GitLab host from the command-line.
- `svgr`: Transform SVGs into React components.
- `fio`:  flexible I/O tester
 fio is a tool that will spawn a number of threads or processes doing a
 particular type of I/O action as specified by the user. fio takes a
 number of global parameters, each inherited by the thread unless
 otherwise parameters given to them overriding that setting is given.
 The typical use of fio is to write a job file matching the I/O load
 one wants to simulate.
 .
 This package contains the command line version of fio and all additional
 command line tools. The package fio-examples contains the example job files.


- `mh_metric`: Calculate and enforce code metrics for MATLAB or Octave code.
- `rubocop`:  Ruby static code analyzer
 rubocop is a static code analyzer for Ruby, out of the box it will
 enforce many of the guidelines outlined in the community Ruby Style Guide.
 .
 Most aspects of its behavior can be tweaked via various configuration
 options.
 .
 Apart from reporting problems in your code, RuboCop can also
 automatically fix some of the problems for you.


- `nm-classic`: This command is an alias of `nm`.
- `doctl-auth`: Authenticate doctl with one or more API tokens.
- `ogrmerge.py`: Merge several vector datasets into a single one.
- `kitex`: Code generation tool provided by the Go RPC framework Kitex.
- `docker-volume`: Manage Docker volumes.
- `standard-version`: Automate versioning and changelog generation, with SemVer and Conventional Commits.
- `maestral`: A lightweight Dropbox client for macOS and Linux.
- `VBoxControl`: 
- `VBoxManage`: 
- `alternatives`: This command is an alias of `update-alternatives`.
- `debtap`: Convert Debian packages into Arch Linux packages.
- `mh_copyright`: Adjust copyright headers for MATLAB or Octave code.
- `you-get`: Download media contents (videos, audios, images) from the Web.
- `dotnet-tool`: Manage .NET tools and search published tools in NuGet.
- `gt`: Create and manage sequences of dependent code changes (stacks) for Git and GitHub.
- `bq`: The bq command-line tool is a Python-based command-line tool for BigQuery.
- `speedcrunch`: A high-precision scientific calculator.
- `duf`:  Disk Usage/Free Utility
 Simple Disk Usage/Free Utility.
 .
 Features:
  - User-friendly, colorful output.
  - Adjusts to your terminal's theme & width.
  - Sort the results according to your needs.
  - Groups & filters devices.
  - Can conveniently output JSON.


- `btop`:  Modern and colorful command line resource monitor that shows usage and stats
 btop is a modern and colorful command line resource monitor that shows
 usage and stats for processor, memory, disks, network and processes.
 btop features:
  - Easy to use, with a game inspired menu system.
  - Full mouse support, all buttons with a highlighted key is clickable
  and mouse scroll works in process list and menu boxes.
  - Fast and responsive UI with UP, DOWN keys process selection.
  - Function for showing detailed stats for selected process.
  - Ability to filter processes.
  - Easy switching between sorting options.
  - Tree view of processes.
  - Send any signal to selected process.
  - UI menu for changing all config file options.
  - Auto scaling graph for network usage.
  - Shows IO activity and speeds for disks
  - Battery meter
  - Selectable symbols for the graphs
  - Custom presets
  - And more...
  btop is written in C++ and is continuation of bashtop and bpytop.


- `plocate`:  much faster locate
 plocate is a locate(1) based on posting lists, giving much faster searches
 on a much smaller index. It is a drop-in replacement for mlocate in nearly
 all aspects, and is fast on SSDs and non-SSDs alike.


- `ctop`: 
- `visidata `: 
- `gron`:  tool to transform JSON into discrete, greppable assignments
 gron transforms JSON into discrete assignments to make it easier to grep for
 what you want and see the absolute 'path' to it. gron can read JSON from a
 local file, over the network, or directly from STDIN.
 .
 gron eases the exploration of APIs that return large blobs of JSON but have
 terrible documentation.
 .
 gron can work backwards too, enabling you to turn your filtered data back
 into JSON.


- `caja`:  file manager for the MATE desktop
 Caja is the official file manager for the MATE desktop. It allows one
 to browse directories, preview files and launch applications associated
 with them. It is also responsible for handling the icons on the MATE
 desktop. It works on local and remote filesystems.


- `rkhunter`:  rootkit, backdoor, sniffer and exploit scanner
 Rootkit Hunter scans systems for known and unknown rootkits,
 backdoors, sniffers and exploits.
 .
 It checks for:
  - SHA256 hash changes;
  - files commonly created by rootkits;
  - executables with anomalous file permissions;
  - suspicious strings in kernel modules;
  - hidden files in system directories;
 and can optionally scan within files.
 .
 Using rkhunter alone does not guarantee that a system is not
 compromised. Running additional tests, such as chkrootkit, is
 recommended.


- `mate-search-tool`: Search files in MATE desktop environment.
- `kdialog`:  Dialog display utility
 kdialog allows you to display dialog boxes from shell scripts. The syntax is
 very much inspired from the "dialog" command (which shows text mode dialogs).


- `mate-about`: Show information about MATE desktop environment.
- `mate-calc`:  MATE desktop calculator
 mate-calc is a powerful graphical calculator with financial, logical and
 scientific modes. It uses a multiple precision package to do its arithmetic
 to give a high degree of accuracy.


- `drawing`:  simple drawing application for the GNOME desktop
 Drawing is a simple image editor similar to MS Paint and designed
 for the GNOME desktop environment. It includes a set of image
 manipulation tools for every day basic image editing needs.


- `mate-screenshot`: Make screenshots in MATE desktop environment.
- `pw-cli`: The PipeWire Command Line Interface.
- `duc`:  high-performance disk usage analyzer
 Duc maintains a database of accumulated sizes of directories of the file
 system, and allows you to query this database with some tools, or create
 fancy graphs showing you where your bytes are.
 .
 Duc comes with console utilities, ncursesw and X11 user interfaces and a
 CGI wrapper for disk usage querying and visualisation.
 .
 Duc is designed to scale to huge filesystems: it will index and display
 hundreds of millions of files on petabytes of storage without problems.


- `mate-calc-cmd`: Calculate mathematic expressions in MATE desktop environment in terminal.
- `faillock`: Display and modify authentication failure record files.
- `backlight_control`: Control a linux machine's backlight using percentage values.
- `ledctl`: Intel(R) Enclosure LED Control Application.
- `engrampa`:  archive manager for MATE
 Engrampa is an archive manager for the MATE environment. It allows you to:
 .
  * Create and modify archives.
  * View the content of an archive.
  * View a file contained in an archive.
  * Extract files from the archive.
 .
 Engrampa supports the following formats:
  * Tar (.tar) archives, including those compressed with
    gzip (.tar.gz, .tgz), bzip (.tar.bz, .tbz), bzip2 (.tar.bz2, .tbz2),
    compress (.tar.Z, .taz), lzip (.tar.lz, .tlz), lzop (.tar.lzo, .tzo),
    lzma (.tar.lzma) and xz (.tar.xz)
  * Zip archives (.zip)
  * Jar archives (.jar, .ear, .war)
  * 7z archives (.7z)
  * iso9660 CD images (.iso)
  * Lha archives (.lzh)
  * Single files compressed with gzip (.gz), bzip (.bz), bzip2 (.bz2),
    compress (.Z), lzip (.lz), lzop (.lzo), lzma (.lzma) and xz (.xz)
 .
 Engrampa doesn't perform archive operations by itself, but relies on
 standard tools for this.


- `pluma`:  official text editor of the MATE desktop environment
 Pluma is a text editor which supports most standard editor features,
 extending this basic functionality with other features not usually
 found in simple text editors. Pluma is a graphical application which
 supports editing multiple text files in one window (known sometimes as
 tabs or MDI).
 .
 Pluma fully supports international text through its use of the
 Unicode UTF-8 encoding in edited files. Its core feature set includes syntax
 highlighting of source code, auto indentation and printing and print preview
 support.
 .
 Pluma is also extensible through its plugin system, which currently
 includes support for spell checking, comparing files, viewing CVS
 ChangeLogs, and adjusting indentation levels.


- `pinta`: Pinta is a free, open source program for drawing and image editing.
- `wondershaper`: Allows the user to limit the bandwidth of one or more network adapters.
- `dumpcap`: A network traffic dump tool.
- `git-show-merged-branches`: Print all branches which are merged into the current head.
- `rich`: Rich CLI is a toolbox for fancy output in the terminal.
- `git-show-unmerged-branches`: Print all branches which are not merged into the current HEAD.
- `mate-dictionary`: Look up words on dictionaries.
- `xed`: Edit files in Cinnamon desktop environment.
- `eopkg`: Package manager for Solus.
- `cloud-init`:  initialization system for infrastructure cloud instances
 Cloud-init provides a framework and tool to configure and customize virtual
 machine instances for Infrastructure-as-a-Service (IaaS) clouds platforms. It
 can for example set a default locale and hostname, generate SSH private host
 keys, install SSH public keys for logging into a default account, set up
 ephemeral mount points, and run user-provided scripts.
 .
 Various methods are supported for passing data to the instance at launch
 time, including the standard interfaces of multiple platforms.


- `conntrack`:  Program to modify the conntrack tables
 conntrack is a userspace command line program targeted at system
 administrators. It enables them to view and manage the in-kernel
 connection tracking state table.


- `lsns`: List information about all namespaces or about the specified namespace.
- `btrbk`:  backup tool for btrfs subvolumes
 Backup tool for btrfs subvolumes, using a configuration file, allows
 creation of backups from multiple sources to multiple destinations,
 with ssh and flexible retention policy support (hourly, daily,
 weekly, monthly).


- `cpupower`: Tools regarding CPU power and tuning options.
- `vifm`:  flexible vi-like file manager using ncurses
 Vifm is a file manager providing a vi-like usage experience. It has similar
 keybindings and modes (e.g. normal, command line, visual). The interface uses
 ncurses, thus vifm can be used in text-only environments.
 It supports a wide range of features, some of which are known from the
 vi-editor:
  - utf8 support
  - user mappings (almost like in vi)
  - ranges in command-line commands
  - user defined commands (with support for ranges)
  - registers
  - operation undoing/redoing
  - fuse file systems support
  - trash
  - multiple files renaming
  - support of filename modifiers
  - colorschemes support
  - file name color according to file type
  - path specific colorscheme customization
  - bookmarks
  - operation backgrounding
  - customizable file viewers
  - handy less-like preview mode
  - filtering out and searching for files using regular expressions
  - one or two panes view
 With the package comes a plugin to use vifm as a vim file selector.


- `bindkey`: Add keybindings to Z-Shell.
- `sqlite-utils`:  CLI tool and Python utility functions for manipulating SQLite
 Feature highlights:
 .
   - Pipe JSON (or CSV or TSV) directly into a new SQLite database file,
     automatically creating a table with the appropriate schema
   - Run in-memory SQL queries, including joins, directly against data in CSV,
     TSV or JSON files and view the results.
   - Configure SQLite full-text search against your database tables and run
     search queries against them, ordered by relevance
   - Run transformations against your tables to make schema changes that SQLite
     `ALTER TABLE` does not directly support, such as changing the type of a
     column
   - Extract columns into separate tables to better normalize your existing data


- `rip`: Remove files or directories by sending them to the graveyard, allowing for them to be recovered.
- `ld`: Link object files together.
- `ptpython3`: This command is an alias of `ptpython`.
- `hcloud`: Show how to use the CLI for Hetzner Cloud.
- `wipeclean`: Clear the terminal screen using an animated wiper.
- `just`:  Save and run project-specific commands
 just is a command runner with a configuration file similar to Makefile but can
 be written in arbitrary languages.
 .
 It has improvements over make e.g. no .PHONY, is cross-platform, has detailed
 error output, and comes with command line completions for popular shells.


- `bash-it`: A collection of community contributed Bash commands and scripts for Bash 3.2+.
- `isisdl`: A downloading utility for ISIS of TU-Berlin. Download all your files and videos from ISIS.
- `gdal2tiles.py`: Generate TMS or XYZ tiles for a raster dataset.
- `flyctl`: Command-line tool for flyctl.io.
- `tmsu`: Simple command-line tool for tagging files.
- `ptpython`:  Alternative Python Prompt with auto-completion and syntax highlighting
 Ptpython is an advanced Python REPL:
 .
   * Syntax highlighting.
   * Multiline editing (the up arrow works).
   * Autocompletion.
   * Mouse support.
   * Support for color schemes.
   * Support for bracketed paste.
   * Both Vi and Emacs key bindings.
   * Support for double width (Chinese) characters.
   * ...and many other things.


- `ugrep`:  faster grep with an interactive query UI
 Universal grep: ultra fast searcher of file systems, text and
 binary files, source code, archives, compressed files, documents, and more.
 .
 The main features include:
  - Written in clean and efficient C++11, built for speed
  - Ultra fast with new match algorithms beating grep, ripgrep, silver
    searcher, hyperscan, etc.
  - Multi-threaded search using high-performance lock-free job queue stealing
  - Multi-threaded task-parallel decompression and search
  - Optimized pattern matching (AVX, SSE2, ARM NEON/AArch64)
  - Optimized asynchronous IO for efficient concurrent searching
  - Thoroughly tested (includes over 1000 test cases)
  - Compatible with the standard GNU/BSD grep command-line options
  - Comprehensive how-to tutorial for beginners to advanced users
  - Interactive query UI to enter search patterns
  - Select files to search by file types, filename suffix, and "magic bytes"
  - Search archives (cpio, jar, tar, pax, zip)
  - Search compressed files (zip, gz, Z, bz, bz2, lzma, xz)
  - Search pdf, doc, docx, xls, xlxs, and more using filters
  - Search binary files and display hexdumps with binary pattern matches
  - Search UTF-encoded files with Unicode pattern matches (by default)
  - Search files encoded in ISO-8859-1 thru 16, CP 437, CP 850, MAC, KOI8, etc.
  - Search files excluding files specified by .gitignore etc.
  - Search patterns across newlines, matching multiple lines at once
  - Search patterns excluding negative patterns ("match this but not that")
  - Includes predefined regex patterns to search source code, XML, JSON, HTML
  - Output results in CSV, JSON, XML, and user-specified formats
  - Sort matching files by name, size, and time
  - Portable, compiles and runs on Linux, Unix, Mac OS X, Windows, etc.


- `eget`: Easily install prebuilt binaries from GitHub.
- `swaks`:  SMTP command-line test tool
 swaks (Swiss Army Knife SMTP) is a command-line tool written in Perl
 for testing SMTP setups; it supports STARTTLS and SMTP AUTH (PLAIN,
 LOGIN, CRAM-MD5, SPA, and DIGEST-MD5). swaks allows one to stop the
 SMTP dialog at any stage, e.g to check RCPT TO: without actually
 sending a mail.
 .
 If you are spending too much time iterating "telnet foo.example 25"
 swaks is for you.


- `nmcli-general`: Manage general settings of NetworkManager.
- `betterdiscordctl`: A program for managing BetterDiscord on Linux.
- `rpi-eeprom-update`: Tool to update EEPROM and view other EEPROM information.
- `pdfxup`: N-up PDF pages.
- `smem`:  memory reporting tool
 Tool that can give numerous reports on memory usage on Linux systems.
 Unlike existing tools, smem can report proportional set size (PSS),
 which is a more meaningful representation of the amount of memory used
 by libraries and applications in a virtual memory system.
 .
 This package contains main tool which can also process data collected
 by smemcap.


- `nmcli-networking`: Manage the networking status of NetworkManager.
- `tailscale-ssh`: SSH to a Tailscale machine (Linux Only).
- `cmctl`: A CLI tool that can help you to manage cert-manager resources inside your cluster.
- `nyxt`: Nyxt is a keyboard-driven web browser for power users.
- `gdal_contour`: Create contour lines and polygons from a digital elevation model.
- `cargo-add`: Add dependencies to a Rust project's `Cargo.toml` file.
- `crictl`: Command-line for CRI-compatible container runtimes.
- `s3cmd`:  command-line Amazon S3 client
 Command-line tool to upload, retrieve and manage data in Amazon S3 service
 (http://www.amazon.com/s3/), designed for use in scripts. Features:
  - creating and destroying S3 buckets
  - uploading and downloading files
  - listing remote files
  - removing remote files
  - synchronizing local directories to S3 buckets
  - getting various information about buckets and disk usage
 .
 s3cmd supports both (US and EU) S3 datacentres.


- `ripgrep`:  Recursively searches directories for a regex pattern
 ripgrep is a line-oriented search tool that recursively searches your current
 directory for a regex pattern while respecting your gitignore rules and
 automatically skip hidden files/directories (smart filtering) and binary files.
 ripgrep is similar to other popular search tools like The Silver Searcher, ack
 and grep.
 .
 ripgrep is generally faster than both The Silver Searcher and GNU grep. It
 defaults to recursive directory search and won't search files ignored by your
 `.gitignore` files. Use ripgrep if you like speed, filtering by default, fewer
 bugs, and Unicode support.
 .
 On the other hand, if you like multiline search, then ripgrep may not quite
 meet your needs (yet), and it will never support fancy regex features such as
 backreferences or lookaround


- `licensor`: Write licenses to stdout.
- `ern`: Electrode Native platform command line client.
- `ani-cli`:  Browse and watch anime on the commandline
 ani-cli allows one to comfortably watch anime (alone and with friends)
 from the commandline.


- `quarto`: An open-source scientific and technical publishing system built on Pandoc.
- `gdalinfo`: List various information about a GDAL supported raster dataset.
- `hx`: This command is an alias of `helix`.
- `deb-get`: `apt-get` functionality for `.deb` packages published in third party repositories or via direct download.
- `picom-trans`: Set the window opacity for the `picom` window compositor.
- `pyinfra`: Automates infrastructure at a large scale.
- `vgmstream_cli`: Play a wide variety of audio formats used in video games and convert them into `wav`.
- `gdal_translate`: Convert raster data between different formats.
- `rustup-init.sh`: Script to install `rustup` and the Rust toolchain.
- `docsify`: Initialize and serve markdown documentation.
- `varnishlog`: Display Varnish logs.
- `tlmgr-key`: Manage GPG keys used to verify TeX Live databases.
- `daemon`:  turns other processes into daemons
 There are many tasks that need to be performed to correctly set up a
 daemon process. This can be tedious. Daemon performs these tasks for
 other processes. This is useful for writing daemons in languages other
 than C, C++ or Perl (e.g. /bin/sh, Java).


- `toolbox-init-container`: Initialize a running `toolbox` container.
- `toolbox-run`: Run a command in an existing `toolbox` container.
- `grub-bios-setup`: Set up a device to use GRUB with a BIOS configuration.
- `toolbox-list`: List existing `toolbox` containers and images.
- `toolbox-rmi`: Remove one or more `toolbox` images.
- `termusic`: A terminal music player written in Rust that uses vim-like key bindings.
- `rpm-ostree`: A hybrid image/package system.
- `toolbox-help`: Displays help information about `toolbox`.
- `toolbox`: Tool for containerized command line environments on Linux.
- `retroarch`:  Simple frontend for the libretro library
 RetroArch is an open source, multi-platform frontend for the libretro API.
 It can be used as a modular multi emulator system, game engine, media player
 and 3D technical demonstration. These features are available through
 libretro cores.
 .
 It provides four built-in interfaces: Ozone, GLUI, RGUI and XMB.


- `toolbox-create`: Create a new `toolbox` container.
- `toolbox-enter`: Enter a `toolbox` container for interactive use.
- `cc`: This command is an alias of `gcc`.
- `toolbox-rm`: Remove one or more `toolbox` containers.
- `tlmgr-restore`: Restore package backups created with `tlmgr backup`.
- `powershell`:  PowerShell is an automation and configuration management platform.
 It consists of a cross-platform command-line shell and associated scripting language.


- `jmeter`:  Load testing and performance measurement application (main application)
 Apache JMeter is a 100% pure Java desktop application designed to load test
 functional behavior and measure performance. It was originally designed for
 testing Web Applications but has since expanded to other test functions.
 .
 This package contains the main application.


- `vgrep`: A user friendly pager for grep.
- `tlmgr-repository`: Manage repositories of a TeX Live installation.
- `nextclade`: Bioinformatics tool for virus genome alignment, clade assignment and qc checks.
- `gdalwarp`: Image reprojection and warping utility.
- `silicon`: Create an image of source code.
- `unzstd`: Decompress files with Zstandard compression.
- `flarectl`: Official CLI for Cloudflare.
- `grafana-cli`: A small executable that is bundled with Grafana serve.
- `gum`:  Tool for glamorous shell scripts 🎀
 Gum provides highly configurable, ready-to-use utilities to help you write
 useful shell scripts and dotfiles aliases with just a few lines of code.


- `tlmgr-conf`: Manage the TeX Live configuration.
- `trashy`: An alternative to `rm` and `trash-cli` written in Rust.
- `curlie`: Curlie is a frontend to curl that adds the ease of use of httpie.
- `qm-delsnapshot`: Delete virtual machine snapshots.
- `dconf-reset`: Reset key values in dconf databases.
- `qrcp`: A file transfer tool.
- `compopt`: Print or change the completion options for a command.
- `wal-telegram`: Generates themes for Telegram based the colors generated by pywal/wal.
- `broot`:  Tree view, file manager, configurable launcher
 broot lets you explore file hierarchies with a tree-like view, manipulate
 files, launch actions, and define your own shortcuts.
 .
 It displays the directory contents on a single page, lets you filter the
 tree using fuzzy patterns and regular expressions, and integrates with
 git to hide gitignored files by default.
 .
 Image previewing functionality is temporarily disabled.
 .
 Usage and full documentation at https://dystroy.org/broot.


- `dnsmap`:  DNS domain name brute forcing tool
 dnsmap scans a domain for common subdomains using a built-in or an external
 wordlist (if specified using -w option). The internal wordlist has around 1000
 words in English and Spanish as ns1, firewall servicios and smtp. So will be
 possible search for smtp.example.com inside example.com automatically. Results
 can be saved in CSV and human-readable format for further processing. dnsmap
 does NOT require root privileges to be run, and should NOT be run with such
 privileges for security reasons.
 .
 dnsmap was originally released back in 2006 and was inspired by the fictional
 story "The Thief No One Saw" by Paul Craig, which can be found in the book
 "Stealing the Network - How to 0wn the Box".
 .
 dnsmap is mainly meant to be used by pentesters during the information
 gathering/enumeration phase of infrastructure security assessments. During the
 enumeration stage, the security consultant would typically discover the target
 company's IP netblocks, domain names, phone numbers, etc.
 .
 Subdomain brute-forcing is another technique that should be used in the
 enumeration stage, as it's especially useful when other domain enumeration
 techniques such as zone transfers don't work (I rarely see zone transfers being
 publicly allowed these days by the way).
 .
 Fun things that can happen:
 .
   1) Finding interesting remote access servers
      (e.g.: https:://extranet.example.com).
   2) Finding badly configured and/or unpatched servers
      (e.g.: test.example.com).
   3) Finding new domain names which will allow you to map
      non-obvious/hard-to-find netblocks of your target organization
      (registry lookups - aka whois is your friend).
   4) Sometimes you find that some bruteforced subdomains resolve to internal IP
      addresses (RFC 1918). This is great as sometimes they are real up-to-date
      "A" records which means that it is possible to enumerate internal servers
      of a target organization from the Internet by only using standard DNS
      resolving (as opposed to zone transfers for instance).
   5) Discover embedded devices configured using Dynamic DNS services
      (e.g.: IP Cameras). This method is an alternative to finding devices via
      Google hacking techniques.
 .
 This package provides two possible commands: dnsmap and dnsmap-bulk.
 .
 This program is useful for pentesters, ethical hackers and forensics experts.
 It also can be used for security tests.


- `links`:  Web browser running in text mode
 Links is a text mode WWW browser, similar to Lynx. It displays tables,
 frames, downloads on background, uses HTTP/1.1 keepalive connections.
 .
 This version is compiled without graphics mode. See the package
 links2 for a version with graphics support compiled in.


- `adig`: Prints information received from Domain Name System (DNS) servers.
- `warpd`: A modal keyboard driven pointer manipulation program.
- `battop`: An interactive viewer for the batteries installed in your notebook.
- `woeusb`: Windows media creation tool.
- `blight`:  Hassle-free CLI backlight utility/library for Linux
 blight is a hassle-free CLI utility to manage backlight on Linux; one that
 plays well with hybrid GPU configuration and proprietary drivers.
 .
 A lot of Linux backlight utilities often fail to detect the right backlight
 device to control in laptops that ship with Intel or Amd iGPUs and an Nvidia
 dGPU with proprietary drivers. This utility aims to solve that problem by
 prioritizing integrated graphic devices, followed by dedicated Nvdia GPU and
 ACPI kernel module. This means that you do not have to manually specify which
 device is currently active whenever you switch between your iGPU and dGPU using
 the MUX switch. Other than that, blight also implements the sweep
 functionality, which lets you change brightness in a smooth sweeping manner,
 rather than applying sudden jerky increments/decrements.


- `qm-start`: Start a virtual machine on QEMU/KVM Virtual Machine Manager.
- `pacdiff`: Maintenance utility for `.pacorig`, `.pacnew` and `.pacsave` files created by `pacman`.
- `qm-reboot`: Reboot a virtual machine by shutting it down, and starting it again after applying pending changes.
- `register_new_matrix_user`: Used to register new users with a given home server when registration has been disabled.
- `caffeine`:  prevent the desktop becoming idle in full-screen mode
 Caffeine prevents the desktop from becoming idle when an application
 is running full-screen. A desktop indicator ‘caffeine-indicator’
 supplies a manual toggle, and the command ‘caffeinate’ can be used
 to prevent idleness for the duration of any command.


- `acountry`: Print the country where an IPv4 address or hostname is located.
- `ahost`: DNS lookup utility to display the A or AAAA record linked with a hostname or IP address.
- `qm-create`: Create or restore a virtual machine on QEMU/KVM Virtual Machine Manager.
- `qm-shutdown`: Shutdown a virtual machine on QEMU/KVM Virtual Machine Manager.
- `latte-dock`:  Dock based on plasma frameworks
 Latte is a dock based on plasma frameworks that provides an elegant and
 intuitive experience for your tasks and plasmoids. It animates it's
 contents by using parabolic zoom effect and tries to be there only when
 it is needed.


- `qm-reset`: Reset a virtual machine on QEMU/KVM Virtual Machine Manager.
- `qm-listsnapshot`: List snapshots of virtual machines.
- `nova`: The OpenStack project that provides a way to provision compute instances.
- `just-js`: A V8 JavaScript runtime for Linux.
- `ruget`: Alternative to wget written in Rust.
- `dconf-read`: Read key values from dconf databases.
- `nsxiv`:  neo simple X image viewer
 nsxiv (the Neo Simple X Image Viewer) is a fork of the now-unmaintained
 sxiv project, with the purpose of being a drop-in replacement for sxiv,
 maintaining its interface, and adding simple, sensible features. nsxiv aims
 to be easy to modify and customise, and works nicely with tiling window
 managers.
 .
 Features:
 .
  - Basic image operations, e.g. zooming, panning, rotating
  - Customizable key and mouse button mappings
  - Scriptable via configuration files
  - Thumbnail mode: grid of selectable previews of all images
  - Ability to cache thumbnails for fast re-loading
  - Basic support for animated/multi-frame images (GIF/WebP)
  - Display image information in status bar
  - Display image name/path in X title


- `gnmic-subscribe`: Subscribe to a gnmic network device state updates.
- `php-cs-fixer`: Automatic coding style fixer for PHP.
- `mg`:  microscopic GNU Emacs-style editor
 This program is intended to be a small, fast, and portable
 editor for people who can't (or don't want to) run real
 Emacs for one reason or another.  It is compatible with GNU
 because there shouldn't be any reason to learn more than
 one Emacs flavor.
 .
 Packages which provide editors with broadly similar goals include
 .
   * e3;
   * joe;
   * jove and xjove;
   * ng-cjk, ng-cjk-canna and ng-latin;
   * qemacs and qemacs-nox; and
   * zile


- `npm-fund`: Retrieve funding information from packages.
- `tsv-filter`: Filter lines of a TSV file by running tests against individual fields.
- `az-storage-container`: Manage blob storage containers in Azure.
- `gdaldem`: Tool to analyze and visualize digital elevation models (DEM).
- `gnmic`: A gNMI command-line client.
- `gnmic-sub`: This command is an alias of `gnmic subscribe`.
- `git-utimes`: Change files modification time to their last commit date. Does not touch files that are in the working tree or index.
- `aws-sts`: Security Token Service (STS) allows to request temporary credentials for (IAM) users or federated users.
- `podman-compose`:  Run docker-compose.yml using podman
 An implementation of docker-compose with podman backend.
 The main objective of this project is to be able to run docker-compose.yml
 unmodified and rootless.


- `lzip`:  lossless data compressor based on the LZMA algorithm
 Lzip is a lossless data compressor based on the LZMA algorithm, with very safe
 integrity checking and a user interface similar to the one of gzip or bzip2.
 Lzip decompresses almost as fast as gzip and compresses better than bzip2,
 which makes it well suited for software distribution and data archiving.


- `zstdless`: Open a `zstd` compressed file for interactive reading, allowing scrolling and search.
- `pyats`: A vendor agnostic test automation framework by Cisco Systems, used for network and systems testing.
- `transmission-show`: Get information about a torrent file.
- `rfetch`: A configurable fetch program to output system information.
- `kcat`:  producer and consumer for Apache Kafka
 kcat is a generic non-JVM producer and consumer for Apache Kafka
 0.8, think of it as a netcat for Kafka.
 .
 In producer mode kcat reads messages from stdin, delimited with a
 configurable delimiter and produces them to the provided Kafka
 cluster, topic and partition. In consumer mode kcat reads messages
 from a topic and partition and prints them to stdout using the
 configured message delimiter.
 .
 kcat also features a Metadata list mode to display the current
 state of the Kafka cluster and its topics and partitions.


- `az-storage-table`: Manage NoSQL key-value storage in Azure.
- `dolt-version`: Displays the current dolt CLI version.
- `laydown`: Command line application to prepare for Daily Standup.
- `az-provider`: Manage resource providers.
- `llvd`: Linkedin Learning Video Downloader.
- `soupault`: Soupault is a static website generator based on HTML element tree rewriting.
- `az-storage-account`: Manage storage accounts in Azure.
- `gifdiff`: Compare two GIFs for identical visual appearance.
- `mkdocs`:  Static site generator geared towards building project documentation
 MkDocs is a fast, simple and downright gorgeous static site generator
 that's geared towards building project documentation. Documentation
 source files are written in Markdown, and configured with a single YAML
 configuration file.


- `qm-stop`: Stop a virtual machine.
- `transmission-daemon`:  lightweight BitTorrent client (daemon)
 Transmission is a set of lightweight BitTorrent clients (in GUI, CLI
 and daemon form). All its incarnations feature a very simple, intuitive
 interface on top on an efficient, cross-platform back-end.
 .
 This package contains the transmission-daemon.
 .
 For the associated transmission-remote, see the package
 transmission-cli, or any of the GUI interfaces,
 transmission-remote-gtk, transgui, or tremotesf, all of which can be
 used to control and monitor the daemon either locally or remotely.


- `rpi-imager`: Flash images onto storage devices.
- `ddev`: Container based local development tool for PHP environments.
- `keep-header`: Keep first line untouched by a command, passing it directly to stdout.
- `atuin`:  magical shell history
 Atuin replaces your existing shell history with a SQLite database, and records
 additional context for your commands.
 .
  * rebind Ctrl-r and up (configurable) to a full screen history search UI
  * store shell history in a SQLite database
  * back up and sync encrypted shell history
  * the same history across terminals, across sessions, and across machines
  * log exit code, cwd, hostname, session, command duration, etc
  * calculate statistics such as "most used command"
  * old history file is not replaced
  * quick-jump to previous items with Alt-<num>
  * switch filter modes via Ctrl-r; search history just from the current
  session, directory, or globally
  * enter to execute a command, tab to edit
 .
 Note to bash users: ble.sh or bash-preexec is additionally required, neither
 is packaged in Debian yet, so you have to install one of them yourselves.


- `kool`: Build software development environments from the command-line.
- `aws-history`: Print the command-line history for AWS CLI commands (the record of history of AWS CLI commands must be enabled).
- `git-browse-ci`: Open the current `git` repository's CI website in the default web browser.
- `chafa`:  Image-to-text converter supporting a wide range of symbols, etc.
 Chafa is a command-line utility that converts all kinds of images, including
 animated image formats like GIFs, into ANSI/Unicode character output that can
 be displayed in a terminal.
 .
 It is highly configurable, with support for alpha transparency and multiple
 color modes and color spaces, combining a range of Unicode characters for
 optimal output.
 .
 The core functionality is provided by a C library with a public,
 well-documented API.
 .
 This package ships the command line tool.


- `zfgrep`: Matches fixed strings in possibly compressed files.
- `fossil-init`: Initialize a new repository for a project.
- `snakefmt`: Format Snakemake files.
- `csv2tsv`: Convert CSV (comma-separated) text to TSV (tab-separated) format.
- `tlmgr-recreate-tlpdb`: Recreate the TeX Live package database.
- `az-version`: Shows the current version of Azure CLI modules and extensions.
- `qm-nbdstop`: Stop embedded nbd server.
- `npm-query`: Print an array of dependency objects using CSS-like selectors.
- `docker-load`: Load Docker images from files or stdin.
- `zcmp`: Compare compressed files.
- `osmium`: Multipurpose tool for handling OpenStreetMap (OSM) files.
- `azurite`: Azure Storage API compatible server (emulator) in local environment.
- `aws-s3-ls`: List AWS S3 buckets, folders (prefixes), and files (objects).
- `tlmgr-dump-tlpdb`: Dump the TeX Live package database.
- `aws-configure`: Manage configuration for the AWS CLI.
- `az-redis`: Manage Redis caches.
- `fossil-new`: This command is an alias of `fossil init`.
- `az-sshkey`: Manage ssh public key with vm.
- `xe`:  simple alternative to xargs and apply
 xe is a tool for constructing command lines from file listings or
 arguments, which includes the best features of xargs(1) and apply(1).
 .
 Its name means "execute for every ...".
 .
 It provides simple(r) parsing of its input, does not invoke a shell by
 default, can execute multiple commands in parallel, ...


- `az-upgrade`: Upgrade Azure CLI and Extensions.
- `lualatex`: An extended version of TeX using Lua to compile.
- `az-group`: Manage resource groups and template deployments.
- `gdaladdo`: Build overview images of raster datasets.
- `catimg`: Image printing in the terminal.
- `gnmic-set`: Modify gnmi network device configuration.
- `adb-logcat`: Dump a log of system messages.
- `projucer`: A project manager for JUCE framework applications.
- `aws-pricing`: Query services, products, and pricing information from Amazon Web Services.
- `gpgconf`:  GNU privacy guard - core configuration utilities
 GnuPG is GNU's tool for secure communication and data storage.
 .
 This package contains core utilities used by different tools in the
 suite offered by GnuPG.  It can be used to programmatically edit
 config files for tools in the GnuPG suite, to launch or terminate
 per-user daemons (if installed), etc.


- `csv-diff`: View differences between two CSV, TSV or JSON files.
- `gh-label`: Work with GitHub labels on the command-line.
- `az-storage-queue`: Manage storage queues in Azure.
- `latexdiff`:  utility to mark up significant differences between LaTeX files
 latexdiff compares two LaTeX files and marks up significant differences
 between them (i.e. a diff for LaTeX files). It generates a new LaTeX file
 containing the annotated differences.
 .
 Various options are available for visual markup using standard LaTeX packages
 such as 'color.sty'. Changes not directly affecting visible text, for example
 in formatting commands, are still marked in the LaTeX source.
 .
 A rudimentary revision facilility is provided by another Perl script,
 'latexrevise', which accepts or rejects all changes. Manual editing of the
 difference file can be used to override this default behaviour and accept or
 reject selected changes only.


- `git-delete-submodule`: Delete a specific submodule from a `git` repository.
- `transmission`:  lightweight BitTorrent client
 Transmission is a set of lightweight BitTorrent clients (in GUI, CLI
 and daemon form). All its incarnations feature a very simple, intuitive
 interface on top on an efficient, cross-platform back-end.
 .
 This is just a metapackage depending on one of the front-end
 alternatives


- `brittany`: Pretty-print Haskell source files.
- `transmission-edit`: Modify announce URLs from torrent files.
- `certutil`: Manage keys and certificates in both NSS databases and other NSS tokens.
- `gsutil`:  configure and manage Grandstream BudgeTone 100 VOIP and GX2000 phones
 GsUtil is a short program written to dump and restore the data
 from randstream BudgeTone 100 VOIP and GX2000 phone.
 Since a reboot is required to make the configuration change effective,
 this program does that too.


- `fastfetch`:  neofetch-like tool for fetching system information
 Fastfetch is a neofetch-like tool for fetching system information and
 displaying them in a pretty way. It is written mainly in C, with
 performance and customizability in mind.


- `pixterm`: Image printing in the terminal.
- `gnmic-get`: Get a snapshot of a gnmi network device operation data.
- `pint`: An opinionated PHP code style fixer based on PHP-CS-Fixer.
- `pulumi`: Define infrastructure on any cloud using familiar programming languages.
- `qm-guest-cmd`: Execute QEMU Guest Agent commands.
- `qm-destroy`: Destroy a virtual machine in QEMU/KVM Virtual Machine Manager.
- `cockpit-ws`:  Cockpit Web Service
 The Cockpit Web Service listens on the network, and authenticates
 users.
 .
 Install sssd-dbus for supporting client certificate/smart card authentication
 via sssd/FreeIPA.


- `arpaname`: Provides corresponding ARPA name for IP addresses.
- `qm-vncproxy`: Proxy Virtual Machine VNC (Virtual network computing) traffic to stdin/stdout.
- `cockpit-tls`: TLS terminating HTTP proxy to encrypt traffic between a client and `cockpit-ws`.
- `qm-resume`: Resume a virtual machine.
- `ip-route-list`: This command is an alias of `ip route show`.
- `goldeneye.py`: A HTTP DoS test tool.
- `elink`: Look up precomputed neighbors within a database, or find associated records in other databases.
- `cockpit-desktop`: Provides secure access to Cockpit pages in an already running session.
- `goobook`: Access Google contacts from `mutt` or the command line.
- `qm-guest-passwd`: Set the password for a specific user on QEMU/KVM Virtual Machine Manager.
- `atop`:  Monitor for system resources and process activity
 Atop is an ASCII full-screen performance monitor, similar to the top command,
 but atop only shows the active system-resources and processes, and only shows
 the deviations since the previous interval.  At regular intervals, it shows
 system-level activity related to the CPU, memory, swap, disks and network
 layers, and it shows for every active process the CPU utilization in system
 and user mode, the virtual and resident memory growth, priority, username,
 state, and exit code. The process level activity is also shown for processes
 which finished during the last interval, to get a complete overview about the
 consumers of things such as CPU time.
 .
  Author: Gerlof Langeveld <gerlof@ATComputing.nl>


- `qm-clone`: Create a copy of virtual machine on QEMU/KVM Virtual Machine Manager.
- `mumble`: Low-latency, high quality voice chat software.
- `qm-sendkey`: Send QEMU monitor encoding key event to a virtual machine.
- `setserial`:  controls configuration of serial ports
 setserial is a program which allows you to look at and change various
 attributes of a serial device.
 .
 This version has a completely new approach to configuration.


- `qm-guest-exec-status`: Print the status of the given pid started by the guest-agent on QEMU/KVM Virtual Machine Manager.
- `cockpit-bridge`:  Cockpit bridge server-side component
 The Cockpit bridge component installed server side and runs commands on
 the system on behalf of the web based user interface.


- `lddd`: Find broken library links on the system.
- `treetime`: TreeTime provides routines for ancestral sequence reconstruction and inference of molecular-clock phylogenies.
- `blastp`: Protein-Protein BLAST.
- `qm-pending`: Get the virtual machine configuration with both current and pending values.
- `archivemount`:  mounts an archive or compressed file for access as a filesystem
 archivemount mounts an optionally-compressed archive as a FUSE file system,
 also allowing it to be written to and updated on unmount.
 .
 A plethora of archive formats are supported: tar (all variants), ISO9660,
 Zip/RAR, cpio, ar...
 .
 With -o formatraw the same can be done with any compressed file.


- `qm-cloudinit-dump`: Generate cloudinit configuration files.
- `qm-snapshot`: Create virtual machine snapshots.
- `burpsuite`:  platform for security testing of web applications
 Burp Suite is an integrated platform for performing security
 testing of web applications. Its various tools work seamlessly
 together to support the entire testing process, from initial
 mapping and analysis of an application's attack surface,
 through to finding and exploiting security vulnerabilities.
 .
 Burp gives you full control, letting you combine advanced
 manual techniques with state-of-the-art automation, to make
 your work faster, more effective, and more fun.


- `qm-cleanup`: Clean up resources on QEMU/KVM Virtual Machine Manager like tap devices, VGPUs, etc.
- `caffeine-indicator`: Manually inhibit desktop idleness with a toggle.
- `qtile`: A full-featured, hackable tiling window manager written and configured in Python.
- `blastn`: Nucleotide-Nucleotide BLAST.
- `rpm2cpio`:  tool to convert RPM package to CPIO archive
 The RPM Package Manager (RPM) is a command-line driven package
 management system capable of installing, uninstalling, verifying,
 querying, and updating computer software packages.
 .
 This package contains tool to convert RPM packages to standard CPIO
 archive.


- `qm-status`: Show virtual machine status.
- `virt-xml-validate`: Validate `libvirt` XML files against a schema.
- `qm-migrate`: Migrate a virtual machine.
- `qm-wait`: Wait until the virtual machine is stopped.
- `einfo`: Provides the number of records indexed in each field of a given database, the date of the last update of the database, and the available links from the database to other Entrez databases.
- `qm-mtunnel`: Used by `qmigrate`.
- `lci`: LOLCODE interpreter written in C.
- `ausyscall`: Program that allows mapping syscall names and numbers.
- `xxhsum`: Print or verify checksums using fast non-cryptographic algorithm xxHash.
- `caffeinate`: Prevent desktop from sleeping.
- `qm-help`: Display help for a specific command.
- `qm-rollback`: Rollback the VM state to a specified snapshot.
- `br`: Navigate directory trees interactively.
- `mashtree`: Makes a fast tree from genomes.
- `pkcon`: Command line client for PackageKit console program used by Discover and Gnome software and alternative to 'apt'.
- `apx`: Package management utility for Vanilla OS.
- `ip-route-show`: Display subcommand for IP Routing table management.
- `esearch`: Perform a new Entrez search using terms in indexed fields.
- `qm-unlock`: Unlock a virtual machine in QEMU/KVM Virtual Machine Manager.
- `qm-monitor`: Enter the QEMU Monitor interface.
- `qm-config`: Display the virtual machine configuration with pending configuration changes applied.
- `qm-rescan`: Rescan all storages and update disk sizes and unused disk images of a virtual machine.
- `esa-snap`: Sentinel Application Platform (SNAP) for processing satellite data from the European Space Agency (ESA).
- `git-feature`: Create or merge feature branches.
- `hledger`:  command-line double-entry accounting program
 hledger is a Haskell port and friendly fork of John Wiegley's ledger
 accounting tool. This package provides the main hledger command-line
 tool; see the other hledger-* packages for web and curses interfaces
 and chart generation. hledger aims to be a reliable, practical
 financial reporting tool for day-to-day use, and also a useful
 library for building financial apps in haskell. Given a plain text
 file describing transactions, of money or any other commodity,
 .
 hledger will print the chart of accounts, account balances, or
 transactions you're interested in. It can also help you add
 transactions to the journal file, or convert CSV data from your bank.


- `jdeps`: Java class dependency analyzer.
- `gnatmake`: A low-level build tool for Ada programs (part of the GNAT toolchain).
- `gprbuild`:  multi-language extensible build tool
 A set of tools for processing GNAT project files:
 gprconfig detects available compilers,
 gprbuild runs them;
 gprslave helps distributing the build work across the network;
 gprinstall copies the objects to their final destination;
 gprclean removes them.
 The default configuration supports Ada, Assembler, C, C++, Fortran,
 and can be extended to support user source processing tools.


- `aws-codecommit`: AWS CodeCommit is a managed source control service that hosts private Git repositories.
- `pg_isready`: Check the connection status of a PostgreSQL server.
- `git-merge-repo`: Merge two repository histories.
- `aws-route53`: CLI for AWS Route53 - Route 53 is a highly available and scalable Domain Name System (DNS) web service.
- `esptool.py`: Bootloader utility for Espressif chips (e.g. ESP8266).
- `podman-build`: Daemonless tool for building container images.
- `aws-sqs`: Create, delete, and send messages to queues for the AWS SQS service.
- `aws-s3-presign`: Generate pre-signed URLs for Amazon S3 objects.
- `sam2p`: Raster (bitmap) image converter with smart PDF and PostScript (EPS) output.
- `vale`: Extensible style checker that supports multiple markup formats, such as Markdown and AsciiDoc.
- `snowsql`: SnowSQL command-line client for Snowflake's Data Cloud.
- `git-bulk`: Execute operations on multiple Git repositories.
- `aws-s3-mb`: Create S3 buckets.
- `git-scp`: Copy files from the current working tree to the working directory of a remote repository.
- `git-gh-pages`: Create a new branch inside the current repository called `gh-pages`.
- `gyb`: Command line tool for locally backing up Gmail messages using Gmail's API over HTTPS.
- `dolt-init`: Create an empty Dolt data repository.
- `pyats-version`: View and upgrade the pyATS installation.
- `lzcat`: This command is an alias of `xz --format=lzma --decompress --stdout`.
- `twurl`: Curl-like command but tailored specifically for the Twitter API.
- `zip2john`: A tool to extract password hashes from zip files for use with John the Ripper password cracker.
- `vt`:  toolset for short variant discovery in genetic sequence data
 vt is a variant tool set that discovers short variants from Next Generation
 Sequencing data.
 .
 Vt-normalize is a tool to normalize representation of genetic variants in
 the VCF.  Variant normalization is formally defined as the consistent
 representation of genetic variants in an unambiguous and concise way.  In
 vt a simple general algorithm to enforce this is implemented.


- `argon2`:  memory-hard hashing function - utility
 Argon2 is a password-hashing function that can be used to hash passwords
 for credential storage, key derivation, or other applications.
 .
 There are two main versions of Argon2: Argon2i and Argon2d.
 Argon2i is the safest against side-channel attacks, while Argon2d provides
 the highest resistance against GPU cracking attacks.
 .
 Argon2i and Argon2d are parametrized by:
  * A time cost, which defines the amount of computation realized and
    therefore the execution time, given in number of iterations
  * A memory cost, which defines the memory usage, given in kibibytes
  * A parallelism degree, which defines the number of parallel threads
 .
 This package contains the argon2 tool for hashing data on the command-line.


- `mamba-repoquery`: Efficiently query conda and mamba package repositories and package dependencies.
- `git-stamp`: Stamp the last commit message, with the possibility to reference the issues numbers from your bug tracker or link to its review page.
- `rmlint`: Identify duplicate files or directories, and other filesystem issues.
- `aws-cognito-idp`: Manage Amazon Cognito user pool and its users and groups using the CLI.
- `aws-workmail`: Manage Amazon WorkMail using the CLI.
- `qmmp`:  feature-rich audio player with support of many formats
 Qmmp is feature-rich audio player with support of many formats.
 It is written in Qt.
 .
 Supported formats:
  - MPEG1 layer 2/3
  - Ogg Vorbis
  - Ogg Opus
  - Native FLAC, Ogg FLAC
  - Musepack
  - WavePack
  - tracker modules (mod, s3m, it, xm, etc)
  - ADTS AAC
  - CD Audio
  - WMA, Monkey's Audio (and other formats provided by FFmpeg library)
  - PCM WAVE (and other formats provided by libsndfile library)
  - midi
  - SID
  - chiptune formats (AY, GBS, GYM, HES, KSS, NSF, NSFE, SAP, SPC, VGM, VGZ,
    VTX)
 .
 DSP effects:
  - BS2B effect
  - sample rate converter
  - LADSPA effects
  - extra stereo
  - crossfade
 .
 Visual effects:
  - projectM visualization
  - spectrum analyzer
 .
 Audio output through:
  - ALSA
  - OSS
  - Pulse Audio
  - PipeWire
  - JACK
  - QTMultimedia
  - Icecast
 .
 Other features:
  - XMMS and Winamp 2.x skins support
  - alternative user interface based on standard widgets set
  - 10-band equalizer
  - MP3, Vorbis, AAC, AAC+ streams support
  - mms support
  - MPRIS
  - removable device detection (via UDisks)
  - video playback via Mplayer
  - lyrics
  - cover art support
  - CUE sheet support
  - embedded CUE support (for FLAC, WavPack and Monkey's Audio)
  - multiple playlists
  - automatic charset detection for cue files and ShoutCast metadata
  - playlist formats: m3u, pls, xspf
  - ReplayGain support
  - sending listening history to Last.fm, Libre.fm and ListenBrainz
  - CDDB support
  - audio converter
  - stream browser
  - audio formats converter
  - external programs execution on track change
  - ReplayGain scanner
  - archive reader (RAR and 7z)
  - audio recording
  - listening history
  - media library


- `redis-benchmark`: A tool to benchmark a Redis server.
- `rss2email`:  receive RSS feeds by email
 rss2email is a simple program which you can run in your crontab.
 It watches RSS (or Atom) feeds and sends you a nicely formatted
 email message for each new item.


- `pngquant`:  PNG (Portable Network Graphics) image optimising utility
 pngquant is a command-line conversion utility to quantize and dither truecolor
 PNG images, especially those with a full alpha channel, down to 8-bit (or
 smaller) RGBA-palette PNGs. Such images are usually two to four times smaller
 than the full 32-bit versions, and partial transparency is preserved quite
 nicely. This makes pngquant especially useful both for Web sites and for
 PlayStation 2 development, where one of the texture formats is
 RGBA-palette-based (though not PNG-compressed).
 This is the same technique used for many of the images on the Miscellaneous
 Transparent PNGs page (http://www.libpng.org/pub/png/pngs-img.html), and
 the results are often indistinguishable from the original, truecolor PNG
 images.
 .
 Optimizers (like pngcrush and optipng) optimize the compression, usually
 losslessly, while pngquant quantizes colors down to 256 (or fewer) distinct
 RGBA combinations, which is lossy.


- `unxz`: This command is an alias of `xz --decompress`.
- `mamba`: Fast, cross-platform package manager, intended as a drop-in replacement for conda.
- `pytest`: Run Python tests.
- `sockstat`:  view detailed information about open connections
 Sockstat is a tool to let you view information about open connections.
 It is similar to the tool of the same name that is included in FreeBSD,
 trying to faithfully reproduce as much functionality as is possible.
 .
 This version of sockstat contains several additional features, like
 the ability to look up sockets in use by GID, UID and process name,
 as well as the other criteria supported by FreeBSD's sockstat.


- `dolt-sql`: Run a SQL query. Multiple SQL statements must be separated by semicolons.
- `octave`:  GNU Octave language for numerical computations
 Octave is a (mostly MATLAB® compatible) high-level language, primarily
 intended for numerical computations. It provides a convenient command-line
 interface for solving linear and nonlinear problems numerically.
 .
 Octave can be dynamically extended with user-supplied C++ files.


- `flips`: Create and apply patches for IPS and BPS files.
- `pyats-shell`: Start a pre-loaded pyATS interactive Python Shell to save time in prototyping.
- `aws-s3-cp`: Copy local files or S3 objects to another location locally or in S3.
- `verilator`:  fast free Verilog simulator
 Verilator is the fastest free Verilog HDL simulator, and beats many commercial
 simulators. It compiles synthesizable Verilog (not test-bench code!), plus
 some PSL, SystemVerilog and Synthesis assertions into C++ or SystemC code.
 It is designed for large projects where fast simulation performance is of
 primary concern, and is especially well suited to generate executable models
 of CPUs for embedded software design teams.


- `dolt-merge`: Join two or more development histories together.
- `aws-lightsail`: Manage Amazon Lightsail resources using the CLI.
- `kcadm.sh`: Perform administration tasks from the command-line interface (CLI).
- `dolt-status`: Display the status of the database session.
- `gnatprep`: Preprocessor for Ada source code files (part of the GNAT toolchain).
- `doctl-kubernetes-options`: Provides values available for use with doctl's Kubernetes commands.
- `spicetify`: A CLI utility to customize the Spotify client UI and functionality.
- `doctl-kubernetes-cluster`: Manage Kubernetes clusters and view configuration options relating to clusters.
- `ouch`: Command-line utility for compressing and decompressing files and directories.
- `git-merge-into`: Merge one branch into another branch.
- `twine`:  utility for interacting with PyPI
 Twine is a tool for uploading distributions (in the Python meaning) to PyPi.
 .
 Why should twine be used over the traditional approach?
 .
 The biggest reason to use twine is that python setup.py upload uploads files
 over plaintext. This means anytime you use it you expose your username and
 password to a MITM attack. Twine uses only verified TLS to upload to PyPI
 protecting your credentials from theft.
 .
 Secondly it allows you to precreate your distribution files. python setup.py
 upload only allows you to upload something that you’ve created in the same
 command invocation. This means that you cannot test the exact file you’re
 going to upload to PyPI to ensure that it works before uploading it.
 .
 Finally it allows you to pre-sign your files and pass the .asc files into the
 command line invocation (twine upload twine-1.0.1.tar.gz
 twine-1.0.1.tar.gz.asc). This enables you to be assured that you’re typing
 your gpg passphrase into gpg itself and not anything else since you will be
 the one directly executing gpg --detach-sign -a <filename>.
 .
 Features:
 .
  - Verified HTTPS Connections
  - Uploading doesn’t require executing setup.py
  - Uploading files that have already been created, allowing testing of
    distributions before release
  - Supports uploading any packaging format (including wheels).


- `az-webapp`: Manage Web Applications hosted in Azure Cloud Services.
- `podman-machine`: Create and manage virtual machines running Podman.
- `aws-s3-mv`: Move local files or S3 objects to another location locally or in S3.
- `xzcat`: This command is an alias of `xz --decompress --stdout`.
- `doctl-serverless`: Manage serverless functions.
- `skopeo`:  Tooling to work with remote images registries
 skopeo is a command line utility that performs various operations on
 container images and image repositories.
 .
 skopeo can work with OCI images
 (https://github.com/opencontainers/image-spec) as well as the original
 Docker v2 images.


- `sfdx`: Command-line tool for development and build automation with a Salesforce organization.
- `javap`: Disassemble one or more class files and list them.
- `mysqlbinlog`: Utility for processing MySQL binary log files.
- `dolt-fetch`: Download objects and refs from another repository.
- `serialver`: Returns the serialVersionUID of classes.
- `freshclam`: Update virus definitions for ClamAV antivirus program.
- `nest`: Command-line tool to initialize, develop, and maintain Nest applications.
- `bazel`: Open-source build and test tool similar to Make, Maven, and Gradle.
- `tldr-generate`: Remake configuration files from information stored locally.
- `railway`: Connect code to a Railway project from the command line.
- `lzma`:  Compression and decompression in the LZMA format - command line utility
 The Lempel-Ziv-Markov chain Algorithm is a compression method based on
 the famous LZ77 algorithm, and was first introduced by 7-Zip for use in
 7z archives.
 .
 Its main characteristics are a very high compression ratio, with high RAM
 usage, and fast decompression, with low RAM usage. These properties make
 it well suited to embedded uses, such as for ROM (firmware) compression.
 .
 This package provides the lzma command line utility, which has a
 familiar gzip-like interface.


- `flite`:  Small run-time speech synthesis engine
 Flite is a small fast run-time speech synthesis engine.  It is the
 latest addition to the suite of free software synthesis tools
 including University of Edinburgh's Festival Speech Synthesis System
 and Carnegie Mellon University's FestVox project, tools, scripts and
 documentation for building synthetic voices.  However, flite itself
 does not require either of these systems to run.
 .
 It currently only supports the English and Indic languages.
 .
 This package contains the executables and documentation.


- `tuckr`: Dotfile manager written in Rust.
- `k3d`: Wrapper CLI to easily create k3s clusters inside Docker.
- `unlzma`: This command is an alias of `xz --format=lzma --decompress`.
- `git-force-clone`: Provides the basic functionality of `git clone`, but if the destination git repository already exists it will force-reset it to resemble a clone of the remote.
- `aws-s3-rm`: Delete S3 objects.
- `qm-showcmd`: Show command line which is used to start the VM (debug info).
- `virt-xml`: Edit libvirt Domain XML files with explicit command line options.
- `virt-viewer`:  Displaying the graphical console of a virtual machine
 The console is accessed using the VNC or SPICE protocol. The guest can be
 referred to based on its name, ID, or UUID. If the guest is not already
 running, then the viewer can be told to wait until is starts before attempting
 to connect to the console The viewer can connect to remote hosts to lookup the
 console information and then also connect to the remote console using the same
 network transport.


- `abroot`: ABRoot utility provides full immutability and atomicity by transacting between 2 root partition states (A⟺B).
- `id3v2`:  command line id3v2 tag editor
 A command-line tool to add, modify, remove, or view ID3v2 tags, as well as
 convert or list ID3v1 tags. ID3 tags are commonly embedded in compressed
 music files such as MP3 and are the standard way to more fully describe
 the work than would normally be allowed by putting the information in the
 filename.


- `img2txt`: Convert images to colour ASCII characters and output them to text-based coloured files.
- `coproc`: Bash builtin for creating interactive asynchronous subshells.
- `qm-guest-exec`: Execute a specific command via a guest agent.
- `waifu2x-ncnn-vulkan`: Image upscaler for manga/anime-style images using NCNN neural network framework.
- `calligraflow`: Calligra's flowchart and diagram application.
- `feroxbuster`:  fast, simple, recursive content discovery tool written in Rust
 feroxbuster is a tool designed to perform Forced Browsing.
 Forced browsing is an attack where the aim is to enumerate and
 access resources that are not referenced by the web application,
 but are still accessible by an attacker.
 feroxbuster uses brute force combined with a wordlist to search
 for unlinked content in target directories. These resources may
 store sensitive information about web applications and operational
 systems, such as source code, credentials, internal network
 addressing, etc...
 This attack is also known as Predictable Resource Location, File
 Enumeration, Directory Enumeration, and Resource Enumeration.


- `cbt`: Utility for reading data from Google Cloud's Bigtable.
- `clangd`:  Language server that provides IDE-like features to editors
 clangd understands your C++ code and adds smart features to your editor:
  - code completion
  - compile errors
  - go-to-definition
  - and more.
 .
 clangd is a language server that implements the Language Server Protocol;
 it can work with many editors through a plugin.
 .
 This is a dependency package providing clangd.


- `mkfile`: Create one or more empty files of any size.
- `gcpdiag`: Google Cloud Platform troubleshooting and diagnostics tool.
- `aws-backup`: Unified backup service designed to protect Amazon Web Services services and their associated data.
- `lspath`: CLI app to list the contents of the PATH environment variable, with optional paging.
- `spectacle`: KDE's screenshot utility.
- `xzcmp`: Compare compressed files.
- `calligrawords`: Calligra's word processor application.
- `afconvert`: Convert between AFF and raw file formats.
- `kdenlive`:  non-linear video editor
 Kdenlive is a non-linear video editing suite, which supports DV, HDV and many
 more formats.
 Its main features are:
  * Guides and marker for organizing timelines
  * Copy and paste support for clips, effects and transitions
  * Real time changes
  * FireWire and Video4Linux capture
  * Screen grabbing
  * Exporting to any by FFMPEG supported format


- `calligrastage`: Calligra's presentation application.
- `krunvm`: CLI-based utility for creating MicroVMs from OCI images.
- `audacious`:  small and fast audio player which supports lots of formats
 Audacious is a fork of beep-media-player which supports Winamp skins
 and many codecs.
 .
 In the default install, the following codecs are supported:
 .
  * MP3
  * Ogg Vorbis / Theora
  * AAC and AAC+
  * FLAC
  * ALAC
  * Windows Media (WMA)
  * WAVE
 .
 Additionally, Audacious is extendable through plugins, and contains
 other useful features like LIRC support. Support for many more codecs
 can also be added through plugins.
 .
 This package contains the core player and its localization.


- `czkawka-cli`: Command-line version of `czkawka` a multi-functional app to find duplicates, empty folders, similar images and much more.
- `scd`: File manager focused on shell integration.
- `calligrasheets`: Calligra's spreadsheet application.
- `vite`:  Efficient visual trace explorer
 ViTE is a powerful portable and open source profiling tool to visualize
 the behaviour of parallel applications. Thanks to its scalable design,
 ViTE helps programmers to efficiently analyze the performance of
 potentially large applications.
 .
 ViTE currently enables the visualisation of traces using the Pajé format
 (open format, see http://www-id.imag.fr/Logiciels/paje/) and has various
 functionalities such as exporting a view in a svg format to integrate
 the results easily in a report, or viewing statistics.


- `dbclient`: Lightweight Dropbear Secure Shell client.
- `oomctl`: Analyze the state stored in `systemd-oomd`.
- `konsave`: A CLI program that lets you save and apply your Linux customizations with just one command.
- `dropbearconvert`: Convert between Dropbear and OpenSSH private key formats.
- `distrobox-export`: Export app/service/binary from container to host OS.
- `systemd-run`: Run programs in transient scope units, service units, or path-, socket-, or timer-triggered service units.
- `pro`: Manage Ubuntu Pro services.
- `dropbearkey`: Generate SSH keys in Dropbear format.
- `distrobox-stop`: Stop a distrobox container.
- `handlr`: Manage your default applications.
- `sqfstar`: Create a squashfs filesystem from a tar archive.
- `distrobox-host-exec`: Execute a command on the host from inside a distrobox container.
- `ostree`:  content-addressed filesystem for operating system binaries
 libostree provides a library and tools for managing bootable, immutable,
 versioned filesystem trees. It is like git in that it checksums
 individual files and has a content-addressed object store; unlike git,
 it "checks out" the files using hardlinks into an immutable directory
 tree. This can be used to provide atomic upgrades with rollback, history
 and parallel-installation, particularly useful on "fixed purpose"
 systems such as embedded devices.
 .
 This package contains the executables used to manage and create
 filesystem trees. It does not affect the boot process for the system
 on which it is installed.


- `fixfiles`: Fix file SELinux security contexts.
- `unsquashfs`: Uncompress, extract and list files in squashfs filesystems.
- `vso`: Utility to perform maintenance tasks on Vanilla OS.
- `gummy`: Screen brightness/temperature manager for Linux/X11.
- `ifmetric`:  Set routing metrics for a network interface
 ifmetric is a Linux tool for setting the metrics of all IPv4 routes
 attached to a given network interface at once.  This may be used to
 change the priority of routing IPv4 traffic over the interface.
 Lower metrics correlate with higher priorities.


- `obabel`: Translate chemistry-related data.
- `smbnetfs`:  User-space filesystem for SMB/NMB (Windows) network servers and shares
 A user-space filesystem that contains an entire SMB/NMB network under a single
 mount point. Workgroups, servers and shares can be browsed much like the
 Network Neighbourhood in Microsoft Windows.


- `mmdebstrap`:  create a Debian chroot
 Downloads, unpacks and installs Debian packages to either directly create a
 directory which can be chrooted into, or a tarball of it. In contrast to
 debootstrap it uses apt, supports more than one mirror, automatically uses
 security and updates mirrors for Debian stable chroots, is 3-6 times faster,
 produces smaller output by removing unnecessary cruft, is bit-by-bit
 reproducible if $SOURCE_DATE_EPOCH is set, allows unprivileged operation using
 Linux user namespaces or fakechroot and can setup foreign architecture
 chroots using qemu-user.


- `genisoimage`:  Creates ISO-9660 CD-ROM filesystem images
 genisoimage is a pre-mastering program for creating ISO-9660 CD-ROM
 filesystem images, which can then be written to CD or DVD media using
 the wodim program. genisoimage includes support for making bootable
 "El Torito" CDs, as well as CDs with support for the
 Macintosh HFS filesystem.
 .
 The package also includes extra tools useful for working with ISO images:
  * mkzftree - create ISO-9660 image with compressed contents
  * dirsplit - easily separate large directory contents into disks of
    predefined size
  * geteltorito - extract an El Torito boot image from a CD image
 .
 Please install cdrkit-doc if you want most of the documentation and
 README files.


- `networkctl`: Query the status of network links.
- `picom`:  lightweight compositor for X11
 picom is a compositor for X11, based on xcompmgr. In addition to shadows,
 fading and translucency, picom implements window frame opacity control,
 inactive window transparency, and shadows on argb windows.
 .
 picom is a fork of compton as it seems to have become unmaintained.


- `envycontrol`: GPU switching utility for Nvidia Optimus laptops.
- `mksquashfs`: Create or append files and directories to squashfs filesystems.
- `distrobox-upgrade`: Upgrade one or multiple distrobox containers.
- `stegsnow`:  steganography using ASCII files
 This utility can conceal messages in ASCII text by appending whitespaces to
 the end of lines. Because spaces and tabs are generally not visible in text
 viewers, the message is effectively hidden from casual observers. And if the
 built-in encryption is used, the message cannot be read even if it is detected.
 .
 About the name: locating trailing whitespace in text is like finding a polar
 bear in a snowstorm. And it uses the ICE encryption algorithm, so the name is
 thematically consistent.
 .
 This package is useful for personal security, forensics investigations and
 other actions.


- `nala`:  Commandline frontend for the APT package manager
 Nala is a frontend for the APT package manager. It has a lot
 of the same functionality, but formats the output to be more
 human readable. Also implements a history function to see past
 transactions and undo/redo them. Much like Fedora's dnf history.


- `tftp`: Trivial File Transfer Protocol client.
- `distrobox`:  Another tool for containerized command line environments on Linux
 Use any Linux distribution inside your terminal. Distrobox uses podman or
 docker to create containers using the Linux distribution of your choice.
 Created container will be tightly integrated with the host, allowing to share
 the HOME directory of the user, external storage, external usb devices and
 graphical apps (X11/Wayland) and audio.


- `grim`:  command-line utility to make screenshots of Wayland desktops
 grim is a command-line utility to take screenshots of Wayland desktops. For now
 it requires support for the screencopy protocol to work. Support for the
 xdg-output protocol is optional, but improves fractional scaling support.
 grim will write a PNG to a file or to stdout.


- `nix3-run`: Run an application from a Nix flake.
- `nix3-flake`: Manage Nix flakes.
- `argocd-app`: Command-line interface to manage applications by Argo CD.
- `md-to-clip`: Converter from tldr-pages to Command Line Interface Pages.
- `nix3-build`: Build a Nix expression (downloading from the cache when possible).
- `podman-run`: Run a command in a new Podman container.
- `birdc`: Bird remote control.
- `cs-resolve`: Resolve lists the transitive dependencies of one or more other dependencies.
- `kubectl-edit`: Edit Kubernetes resources.
- `cs-fetch`: Fetch fetches the JARs of one or more dependencies.
- `prqlc`: PRQL compiler.
- `cs-install`: Install an application in the installation directory onfigured when installing `cs`  (to enable the binary to be loaded add to your `.bash_profile` the `$ eval "$(cs install --env)"` command).
- `whisper`: CLI tool to convert audio files to txt,vtt,srt,tsv,json.
- `sgpt`: Command-line productivity tool powered by OpenAI's GPT models.
- `vhs`: CLI home video recorder to generate terminal gifs from code.
- `rarcrack`:  Password cracker for rar archives
 This program uses a brute force algorithm to guess your encrypted compressed
 file's password.
 .
 This program can crack zip, 7z, and rar file passwords.


- `nix3-repl`: Start an interactive environment for evaluating Nix expressions.
- `nix3-registry`: Manage a Nix flake registry.
- `wfuzz`:  Web application bruteforcer
 Wfuzz is a tool designed for bruteforcing Web Applications,
 it can be used for finding resources not linked
 directories, servlets, scripts, etc, bruteforce GET and
 POST parameters for checking different kind of injections
 (SQL, XSS, LDAP,etc), bruteforce Forms parameters
 (User/Password), Fuzzing, etc.


- `docker-pull`: Download Docker images from a registry.
- `b3sum`:  Command line tool for calculating BLAKE3 hash
 similar to md5sum and sha256sum.
 .
 BLAKE3 is a cryptographic hash function that is much faster than MD5, SHA-1,
 SHA-2, SHA-3, and BLAKE2; secure, unlike MD5 and SHA-1, also against length
 extension, unlike SHA-2; and highly parallelizable.


- `git-cvsexportcommit`: Export a single `Git` commit to a CVS checkout.
- `podman-ps`: List Podman containers.
- `clash`: A rule-based tunnel in Go.
- `pystun3`: Classic STUN client written in Python.
- `nix-classic`: A classic, stable interface to a powerful package manager that makes package management reliable, reproducible, and declarative.
- `cs`:  simple, yet powerful CloudStack API client
 cs a simple, yet powerful Apache CloudStack API client written in
 Python and available as a command-line tool. It is a thin wrapper on
 top of the CloudStack API and hence it is able to adapt to any future
 version.
 .
 Apache CloudStack is open source software designed to deploy and
 manage large networks of virtual machines.


- `keytool`: Keytool is a certificate management utility included with Java.
- `babeld`:  loop-free distance-vector routing protocol
 Babel is a distance-vector routing protocol for IPv6 and IPv4 with
 fast convergence properties, described in RFC 6126. It was designed
 to be robust and efficient on both wireless mesh networks and
 classical wired networks. Babel has extremely modest memory and CPU
 requirements. Unlike most routing protocols, which route either IPv4
 or IPv6 but not both at the same time, Babel is a hybrid IPv6 and
 IPv4 protocol: a single update packet can carry both IPv6 and IPv4
 routes (this is similar to how multi-protocol BGP works). This makes
 Babel particularly efficient on dual (IPv6 and IPv4) networks. This
 implementation also includes a radio frequency-aware variant of
 Babel.
 .
 Babel has the following features:
  * it is a distance-vector protocol;
  * it is a proactive protocol, but with adaptative (reactive)
    features;
  * it senses link quality for computing route metrics using a variant
    of the ETX algorithm;
  * it uses a feasibility condition that guarantees the absence of
    loops (the feasibility condition is taken from EIGRP and is
    somewhat less strict than the one in AODV);
  * it uses sequence numbers to make old routes feasible again (like
    DSDV and AODV, but unlike EIGRP);
  * it speeds up convergence by reactively requesting a new sequence
    number (like AODV, and to a certain extent EIGRP, but unlike
    DSDV);
  * it allows redistributed external routes to be injected into the
    routing domain at multiple points (like EIGRP, but unlike DSDV and
    AODV).


- `bob`: Manage and switch between Neovim versions.
- `holehe`: Holehe checks if an email is attached to an account on sites like Twitter, Instagram, Imgur and over 120 others.
- `docker-tag`: Assign tags to existing Docker images.
- `basenc`: Encode or decode file or standard input using a specified encoding, to standard output.
- `nvme`: NVMe storage user space utility.
- `nix3-search`: Search for packages in a Nix flake.
- `eksctl`:  official CLI for Amazon EKS (program)
 eksctl is a simple CLI tool for creating clusters on EKS - Amazon's new
 managed Kubernetes service for EC2. It is written in Go, and uses
 CloudFormation.
 .
 You can create a cluster in minutes with just one command – **eksctl
 create cluster**!


- `clip-view`: Command Line Interface Pages render.
- `tcc`:  small ANSI C compiler
 TCC (for Tiny C Compiler) is a small and fast ANSI C compiler.  It
 generates optimized x86 code, and can compile, assemble, and link
 several times faster than 'gcc -O0'.  Any C dynamic library can be used
 directly.  It includes an optional memory and bounds checker, and
 bounds-checked code can be mixed freely with standard code.  C script
 is also supported via the usual hash-bang mechanism.
 .
 NOTE: TCC is still somewhat experimental and is not recommended for
 production use.  The code it generates is much less optimized than what
 GCC produces, and compiler bugs can have serious security consequences
 for your program.


- `retry`:  Retry a command until the command succeeds
 Retry captures stdin into memory as the data is passed to the repeated
 command, and this captured stdin is then replayed should the command be
 repeated. This makes it possible to embed the retry tool into shell
 pipelines.
 .
 Retry captures stdout into memory, and if the command was successful stdout
 is passed on to stdout as normal, while if the command was repeated stdout
 is passed to stderr instead. This ensures that output is passed to stdout
 once and once only.


- `fastd`:  Fast and Secure Tunneling Daemon
 A VPN daemon that has many features of OpenVPN and Tinc and is optimized
 for small code size and small number of dependencies. Fastd became
 popular on small devices like routers.


- `docker-update`: Update configuration of Docker containers.
- `mysqlcheck`: Check and repair MySQL tables.
- `podman-image`: Manage Docker images.
- `nix3-why-depends`: Show why a package depends on another package.
- `nix3-profile`: Install, update and remove packages from Nix profiles.
- `rhash`:  utility for computing hash sums and magnet links
 RHash is a console utility for calculation and verification of magnet links
 and a wide range of hash sums like CRC32, MD4, MD5, SHA1, SHA256, SHA512,
 AICH, ED2K, Tiger, DC++ TTH, BitTorrent BTIH, GOST R 34.11-94, RIPEMD-160,
 HAS-160, EDON-R, Whirlpool and Snefru.
 Hash sums are used to ensure and verify integrity of large volumes of data
 for a long-term storing or transferring.
 .
 Features:
  * Output in a predefined (SFV, BSD-like) or a user-defined format.
  * Can calculate Magnet links.
  * Ability to process directories recursively.
  * Updating hash files (adding hash sums of files missing in the hash file).
  * Portability: the program works the same on Linux, *BSD or Windows.


- `yolo`: The YOLO command line interface lets you simply train, validate or infer models on various tasks and versions.
- `xsp`: Mono ASP.NET Web Server.
- `venv`: Create lightweight virtual environments in python.
- `cs-java`: The java and java-home commands fetch and install JVMs. The java command runs them too.
- `tlmgr-pinning`: The pinning action manages the pinning file.
- `nix3-develop`: Run a bash shell that provides the build environment of a derivation.
- `az-repos`: Manage Azure DevOps repos.
- `nix3-edit`: Open the Nix expression of a Nix package in $EDITOR.
- `spotdl`: Download Spotify playlists and songs along with metadata.
- `rgpt`: An automated code review tool that uses GPT you can use straight from your terminal.
- `podman-rmi`: Remove one or more Podman images.
- `mcfly`: A smart command history search and management tool.
- `az-devops`: Manage Azure DevOps organizations.
- `osv-scanner`: Scan various mediums for dependencies and matches them against the OSV database.
- `gallery-dl`:  command-line program to download image galleries
 gallery-dl is a command-line program to download image-galleries and
 -collections from several image hosting sites. It is a cross-platform
 tool with many configuration options and powerful filenaming capabilities.


- `tts`: Synthesize speech on the command line.
- `shfmt`:  format shell programs
 shfmt is shell formatter, which supports POSIX Shell, Bash, and mksh.


- `podman-images`: Manage Podman images.
- `pake`: Turn any webpage into a desktop app with Rust/Tauri.
- `nix-store`: Manipulate or query the Nix store.
- `cs-launch`: Launch an application from the name directly from one or more Maven dependencies without the need of installing it.
- `charm`: Set of tools that makes adding a backend to your terminal-based applications, without worrying about user accounts, data storage and encryption.
- `bird`: BIRD Internet Routing Daemon.
- `nix3-shell`: Start a shell in which the specified packages are available.
- `argocd`: Command-line interface to control a Argo CD server.
- `stun`: Classic STUN client.
- `openai`: CLI tool providing access to the OpenAI API.
- `mid3v2`: Edit audio tags.
- `anki`: Powerful, intelligent flashcard program.
- `gfortran`:  GNU Fortran 95 compiler
 This is the GNU Fortran 95 compiler, which compiles Fortran 95 on platforms
 supported by the gcc compiler. It uses the gcc backend to generate optimized
 code.
 .
 This is a dependency package providing the default GNU Fortran 95 compiler.


- `nix3-store`: Manipulate the Nix store.
- `cs-complete-dep`: Allows the developer to search for libraries without searching directly on the web but from the command line.
- `trayer`:  Lightweight GTK2-based systray for UNIX desktop
 trayer is a small program designed to provide systray functionality
 present in GNOME/KDE desktop environments for window managers which
 do not support that function. The system tray is an area, intended to
 always be visible, where some applications put icons to indicate
 their status, and often allowing the user to control programs.
 .
 The code started out as an extraction from fbpanel.


- `nmtui-hostname`: This command is an alias of `nmtui hostname`.
- `nmtui-connect`: This command is an alias of `nmtui connect`.
- `systemd-mount`: Establish and destroy transient mount or auto-mount points.
- `systemd-firstboot`: Initialize basic system settings on or before the first boot-up of a system.
- `dirbuster`:  Web server directory brute-forcer
 DirBuster is a multi threaded java application designed to
 brute force directories and files names on web/application
 servers. Often is the case now of what looks like a web
 server in a state of default installation is actually not,
 and has pages and applications hidden within. DirBuster
 attempts to find these.
 .
 However tools of this nature are often as only good as the
 directory and file list they come with. A different
 approach was taken to generating this. The list was
 generated from scratch, by crawling the Internet and
 collecting the directory and files that are actually used
 by developers! DirBuster comes a total of 9 different
 lists, this makes DirBuster extremely effective at finding
 those hidden files and directories. And if that was not
 enough DirBuster also has the option to perform a pure
 brute force, which leaves the hidden directories and files
 nowhere to hide.


- `cam`: Frontend tool for `libcamera`.
- `systemd-notify`: Notify the service manager about start-up completion and other daemon status changes.
- `apx-pkgmanagers`: Manage package managers in `apx`.
- `xbps-install`: XBPS utility to (re)install and update packages.
- `bcachefs`: Manage `bcachefs` filesystems/devices.
- `systemd-tmpfiles`: Create, delete and clean up volatile and temporary files and directories.
- `xbps-query`: XBPS utility to query for package and repository information.
- `systemd-sysusers`: Create system users and groups.
- `dracut`:  Initramfs generator using udev
 This package builds a bootable initramfs for Linux kernel packages.  The
 initramfs is loaded along with the kernel and is responsible for
 mounting the root filesystem and starting the main init system.


- `aa-complain`: Set an AppArmor policy to complain mode.
- `ip6tables-restore`: This command is an alias of `iptables-restore` for the IPv6 firewall.
- `systemd-detect-virt`: Detect execution in a virtualized environment.
- `hwinfo`:  Hardware identification system
 hwinfo is the hardware detection tool used in SuSE Linux.
 .
 In Debian Edu (Skolelinux) hwinfo has shown better results than discover when
 detecting mouse, keyboard and monitor.
 .
 hwinfo collects information about the hardware installed on a system.  Among
 others, libhd contains information about cdrom, zip, floppy, disks and
 partitions, network card, graphics card, monitor, camera, mouse, sound, pppoe,
 isdn, modem, printer, scanner, bios, cpu, usb, memory and smp.
 .
 This package does not include the binaries hwscan, hwscand and hwscanqueue. If
 you think one or more of these should be included in the package, please
 contact the maintainer at hwinfo@packages.debian.org.


- `qm-list`: List all virtual machines.
- `farge`: Display the color of a specific pixel on the screen in either hexadecimal or RGB formats.
- `systemd-cat`: Connect a pipeline or program's output streams with the systemd journal.
- `bchunk`:  CD image format conversion from bin/cue to iso/cdr
 The bchunk package contains a UNIX/C rewrite of the BinChunker program.
 BinChunker converts a CD image in a .bin/.cue format (sometimes .raw/.cue) into
 a set of .iso and .cdr/.wav tracks. The .bin/.cue format is used by some
 non-UNIX CD-writing software, but is not supported on most other CD-writing
 programs.


- `systemd-path`: List and query system and user paths.
- `qm-importdisk`: This command is an alias of `qm disk import`.
- `swaylock`:  Screen locker for Wayland
 swaylock is a screen locking utility for Wayland compositors. It is compatible
 with any Wayland compositor which implements the following Wayland protocols:
 wlr-layer-shell, wlr-input-inhibitor, xdg-output, xdg-shell


- `apx-stacks`: Manage stacks in `apx`.
- `mkosi`:  build Bespoke OS Images
 A fancy wrapper around "dnf --installroot", "apt", "zypper" and
 "pacstrap", that may generate disk images with a number of
 bells and whistles.
 .
 Generated images are "legacy-free". This means only GPT disk
 labels (and no MBR disk labels) are supported, and only
 systemd based images may be generated.


- `aa-disable`: Disable AppArmor security policy.
- `qm-disk-move`: Move a virtual disk from one storage to another within the same Proxmox cluster.
- `systemd-tty-ask-password-agent`: List or process pending systemd password requests.
- `pkgctl`: Unified command-line devtools frontend for Arch Linux.
- `ip6tables-save`: This command is an alias of `iptables-save` for the IPv6 firewall.
- `mokutil`:  tools for manipulating machine owner keys
 This program provides the means to enroll and erase the machine owner
 keys (MOK) stored in the database of shim.


- `userdbctl`: Inspect users, groups and group memberships on the system.
- `instaloader`:  Instagram automatic photo downloader
 Instaloader downloads photos from Instagram, including public
 and private profiles, hashtags, user stories, feeds and saved
 media. How as well as comments, geotags and captions for each
 post.
 .
 It automatically detects profile name changes and renames the
 target directory accordingly. It also allows for refined
 customization of filters and where to store downloaded media
 be able to detect automatically stop previously interrupted
 download interactions.


- `systemd-sysext`: Activate or deactivate system extension images.
- `pkgctl-auth`: Authenticate `pkgctl` with services like GitLab.
- `qm-template`: Create a Proxmox VM template.
- `lsinitrd`: Show the contents of an initramfs image.
- `pkgctl-repo`: Manage Git packaging repositories and their configuration for Arch Linux.
- `help`: Display information about Bash builtin commands.
- `nmtui-edit`: This command is an alias of `nmtui edit`.
- `zbarcam`: Scans and decodes barcodes (and QR codes) from a video device.
- `vkpurge`: List or remove old kernel versions left behind by `xbps`.
- `systemd-delta`: Find overridden systemd-related configuration files.
- `wpctl`: Manage WirePlumber, a session and policy manager for PipeWire.
- `qm-suspend`: Suspends a virtual machine (VM) in the Proxmox Virtual Environment (PVE).
- `usbip`:  USB device sharing system over IP network
 USB/IP is a system for sharing USB devices over the network.
 .
 To share USB devices between computers with their full functionality,
 USB/IP encapsulates "USB requests" into IP packets and transmits them
 between computers.
 .
 Original USB device drivers and applications can be used for remote USB
 devices without any modification of them.  A computer can use remote USB
 devices as if they were directly attached.
 .
 Currently USB/IP provides no access control or encryption.  It should only
 be used in trusted environments.
 .
 This package provides the server component 'usbipd' and the client tool
 'usbip'.


- `auto-cpufreq`: Automatic CPU speed & power optimizer.
- `semanage-fcontext`: Manage persistent SELinux security context rules on files/directories.
- `systemd-hwdb`: Hardware database management tool.
- `tod`: A tiny Todoist client in Rust.
- `waydroid`: A container-based approach to boot a full Android system on a regular GNU/Linux system like Ubuntu.
- `aa-status`: List currently loaded AppArmor modules.
- `xbps-remove`: XBPS utility to remove packages.
- `systemd-umount`: This command is an alias of `systemd-mount --umount`.
- `qm-move-disk`: This command and `qm move-disk` is an alias of `qm disk move`.
- `tcpick`:  TCP stream sniffer and connection tracker
 This libpcap-based textmode sniffer can:
  * track, reassemble and reorder TCP streams
  * save the captured flows in different files or display them in the terminal
  * display all the stream on the terminal with different display modes like
    hexdump, hexdump + ascii, only printable characters, raw mode, colorized
    mode ...
  * handle several network interface types, including ethernet cards and PPP
    interfaces


- `ip6tables`: This command is an alias of `iptables` for the IPv6 firewall.
- `optimus-manager`: GPU switching utility for Nvidia Optimus laptops.
- `sqfscat`: Concatenate files from a squashfs filesystem and print them to `stdout`.
- `systemd-cryptenroll`: Interactively enroll or remove methods used to unlock LUKS2-encrypted partitions/block devices.
- `systemd-ac-power`: Report whether the computer is connected to an external power source.
- `aa-enforce`: Set an AppArmor profile to enforce mode.
- `apx-subsystems`: Manage subsystems in `apx`.
- `fluidsynth`:  Real-time MIDI software synthesizer
 Fluidsynth is a real-time midi synthesizer based on the soundfont (sf2 and sf3)
 specifications. It can be used to render MIDI input or MIDI files to audio.
 The MIDI events are read from a MIDI device. The sound is rendered in
 real-time to the sound output device.


- `busctl`: Introspect and monitor the D-Bus bus.
- `pkgctl-diff`: Compare package files using different modes.
- `pkgctl-version`: Display `pkgctl` version information.
- `lchage`: Display or change user password policy.
- `qm-disk-resize`: Resize a virtual machine disk in the Proxmox Virtual Environment (PVE).
- `shar`: Create a shell archive.
- `ikaros`: Vanilla OS Tool for managing drivers for your device.
- `qm-resize`: This command is an alias of `qm-disk-resize`.
- `qm-disk-import`: Import a disk image to a virtual machine as an unused disk.
- `mediamtx`: Real-time media server and proxy.
- `select`: Bash builtin construct for creating menus.
- `mount.smb3`: This command is an alias of `mount.cifs`.
- `xzfgrep`: This command is an alias of `xzgrep --fixed-strings`.
- `rustup-default`: Set the default Rust toolchain.
- `devcontainer`: Use a Docker container as a development environment.
- `rustup-check`: Check for updates to Rust toolchains and `rustup`.
- `cargo-fmt`: Run `rustfmt` on all source files in a Rust project.
- `pop`: Send emails from your terminal.
- `zstdmt`: This command is an alias of `zstd --threads 0` (which sets the number of working threads to the number of physical CPU cores).
- `xzegrep`: This command is an alias of `xzgrep --extended-regexp`.
- `musl-gcc`: A wrapper around `gcc` that automatically sets options for linking against musl libc.
- `liquidctl`:  CLI and Python drivers for AIO liquid coolers and other devices
 liquidctl is a tool for controlling various settings of PC internals, such as:
  - liquid cooler pump speed
  - case fan speed
  - RGB LED strip colors
 .
 Currently supported devices are:
  - Corsair Hydro H80i v2, H100i v2 and H115i
  - Corsair HX750i, HX850i, HX1000i and HX1200i
  - Corsair RM650i, RM750i, RM850i and RM1000i
  - EVGA CLC 120 (CL12), 240, 280 and 360
  - NZXT Grid+ V3
  - NZXT HUE 2 and Hue 2 Ambient
  - NZXT Kraken M22
  - NZXT Kraken X42, X52, X62 and X72
  - NZXT Smart Device V1 and V2


- `linode-cli-account`: Manage Linode accounts.
- `!`: Bash builtin to substitute with a command found in history.
- `lima`: This command is an alias of `limactl shell` for the default VM instance.
- `rustup-completions`: Generate shell completions for `rustup` and `cargo`.
- `stylua`: An opinionated Lua code formatter.
- `lzless`: This command is an alias of `xzless`.
- `readonly`: Create or modify read-only variables within a shell script, preventing the variable from being changed by subsequent commands.
- `rake`:  ruby make-like utility
 Rake is a simple ruby build program with capabilities similar to make.
 .
 Rake has the following features:
   * Rakefiles (rakes version of Makefiles) are completely defined in
     standard Ruby syntax. No XML files to edit. No quirky Makefile
     syntax to worry about (is that a tab or a space?)
   * Users can specify tasks with prerequisites.
   * Rake supports rule patterns to sythesize implicit tasks.
   * Rake is lightweight. It can be distributed with other
     projects as a single file. Projects that depend upon
     rake do not require that rake be installed on target
     systems.


- `exfatlabel`: Get or set an exFAT filesystem label.
- `mongosh`: A new shell for MongoDB, replacement for `mongo`.
- `weechat`:  Fast, light and extensible chat client (metapackage)
 WeeChat (Wee Enhanced Environment for Chat) is a fast and light chat client
 for many operating systems. Everything can be done with a keyboard.
 It is customizable and extensible with plugins/scripts, and includes:
  - support of IRC protocol (native)
  - support of XMPP/Jabber protocol (with additional script)
  - nicklist
  - smart hotlist
  - horizontal and vertical split
  - double charset support (decode/encode)
  - FIFO pipe for remote control
  - 256 colors support
  - incremental text search
  - dynamic filtering of buffer content
  - Perl, Python, Ruby, Lua, Tcl, Scheme and PHP scripting
  - script manager
  - spell checking
  - highly customizable and extensible
  - and much more!


- `pydoc`: Display offline Python documentation.
- `flutter-pub`: Flutter's package manager.
- `rustup-install`: Install or update Rust toolchains.
- `cargo-remove`: Remove dependencies from a `Cargo.toml` manifest file.
- `bzip3`:  better, faster and stronger spiritual successor to bzip2 - utilities
 Features higher compression ratios and better performance thanks to a order-0
 context mixing entropy coder, a fast Burrows-Wheeler transform code making use
 of suffix arrays and a RLE with Lempel Ziv+Prediction pass based on LZ77-style
 string matching and PPM-style context modeling.
 .
 This package contains files that is tool using libbzip3.


- `limactl`: Virtual machine manager for Linux guests, with multiple VM templates available.
- `xmlstarlet`:  command line XML toolkit
 XMLStarlet is a set of command line utilities (tools) which can be used to
 transform, query, validate, and edit XML documents and files using simple set
 of shell commands in similar way it is done for plain text files using
 UNIX grep, sed, awk, diff, patch, join, etc commands.
 .
 This set of command line utilities can be used by those who deal with many XML
 documents on UNIX shell command prompt as well as for automated XML processing
 with shell scripts.
 .
 The toolkit's feature set includes options to:
  Check or validate XML files (simple well-formedness check, DTD, XSD, RelaxNG)
  Calculate values of XPath expressions on XML files (such as running sums, etc)
  Search XML files for matches to given XPath expressions
  Apply XSLT stylesheets to XML documents (including EXSLT support, and passing
 parameters to stylesheets)
  Query XML documents (ex. query for value of some elements of attributes,
 sorting, etc)
  Modify or edit XML documents (ex. delete some elements)
  Format or "beautify" XML documents (as changing indentation, etc)
  Fetch XML documents using http:// or ftp:// URLs
  Browse tree structure of XML documents (in similar way to 'ls' command for
 directories)
  Include one XML document into another using XInclude
  XML c14n canonicalization
  Escape/unescape special XML characters in input text
  Print directory as XML document
  Convert XML into PYX format (based on ESIS - ISO 8879), and vice versa


- `datashader_cli`: Quick visualization of large datasets using CLI based on datashader.
- `irb`: Interactive Ruby shell.
- `macchina`: Display information about your computer.
- `bgpgrep`: Filter and print BGP data within MRT dumps.
- `rustup-target`: Modify a toolchain's supported targets.
- `typst`: Compile a Typst file to PDF.
- `cargo-report`: Display various kinds of reports.
- `rustup-show`: Show installed toolchains, targets and the version of `rustc`.
- `polybar`:  Fast and easy-to-use tool for creating status bars
 Polybar aims to help users build beautiful and highly customizable status bars
 for their desktop environment, without the need of having a black belt in
 shell scripting.


- `linode-cli-events`: Manage Linode events.
- `cargo-check`: Check a local package and all of its dependencies for errors.
- `cavif`: PNG/JPEG to AVIF converter.
- `aws-cloudformation`: Model, provision, and manage AWS and third-party resources by treating infrastructure as code.
- `lzgrep`: This command is an alias of `xzgrep`.
- `rustup-self`: Modify the `rustup` installation.
- `lando`: Local development environment and DevOps tool built on Docker.
- `eol`: Show end-of-life dates (EoLs) for a number of products.
- `yacc`: Generate an LALR parser (in C) with a given formal grammar specification file.
- `tre`: Show the contents of the current directory as a tree.
- `clido`: Save-state TODO app for the terminal.
- `gitwatch`: Automatically commit file or directory changes to a git repository.
- `lzmore`: This command is an alias of `xzmore`.
- `aws-cloud9`: Manage Cloud9 - a collection of tools to code, build, run, test, debug, and release software in the cloud.
- `mods`: AI for the command line, built for pipelines.
- `wkhtmltopdf`: An open-source command-line tool to convert HTML documents or web pages into PDF files.
- `lzcmp`: This command is an alias of `xzcmp`.
- `idea`: JetBrains Java and Kotlin IDE.
- `duckdb`: Command-line client for DuckDB, an in-process analytical SQL engine.
- `boxes`:  textmode box- and comment drawing filter
 Boxes is extremely configurable filter for adding and removing ASCII art
 (comments, for example) around chunks of text.  Most modern text editors
 support filtering text through external filters.  Boxes is such a filter.


- `packwiz`: Create, edit and manage Minecraft modpacks.
- `checksec`:  Bash script to test executable properties
 Modern Linux distributions offer some mitigation techniques to make it harder
 to exploit software vulnerabilities reliably. Mitigations such as RELRO,
 NoExecute (NX), Stack Canaries, Address Space Layout Randomization (ASLR) and
 Position Independent Executables (PIE) have made reliably exploiting any
 vulnerabilities that do exist far more challenging. The checksec.sh script is
 designed to test what standard Linux OS and PaX security features are being
 used.


- `zotero`: Manage your bibliographies.
- `linode-cli-volumes`: Manage Linode Volumes.
- `stressapptest`:  stress test application for simulating high load situations
 Stressful Application Test (or stressapptest, its unix name) tries to maximize
 randomized traffic to memory from processor and I/O, with the intent of
 creating a realistic high load situation in order to test the existing hardware
 devices in a computer.
 .
 Stressapptest may be used for various purposes:
  * stress test
  * hardware qualification and debugging
  * memory interface test
  * disk testing


- `ifs`: IFS (Internal Field Separator) is a special environment variable that defines the delimiter used for word splitting in Unix shells.
- `tlmgr-search`: Search for TeX Live packages using (Perl) regular expressions.
- `lzegrep`: This command is an alias of `xzgrep --extended-regexp`.
- `ooniprobe`: Open Observatory of Network Interference (OONI).
- `jf`: Interact with JFrog products like Artifactory, Xray, Distribution, Pipelines and Mission Control.
- `ropper`:  rop gadget finder and binary information tool
 This package contains scripts that display info about files in different
 formats and find gadgets to build ROPs chains for different architectures
 (x86/x86_64, ARM/ARM64, MIPS, PowerPC). For disassembly ropper uses the
 Capstone Framework.


- `rustup-update`: Update Rust toolchains and `rustup` itself (if not installed using a package manager).
- `nping`: Network packet generation tool/ping utility.
- `dhcpig`:  DHCP exhaustion script using scapy network library
 DHCPig initiates an advanced DHCP exhaustion attack. It will consume all IPs
 on the LAN, stop new users from obtaining IPs, release any IPs in use, then
 for good measure send gratuitous ARP and knock all windows hosts offline.
 .
 It is based on the scapy library and requests admin privileges to execute.
 It has been tested on multiple Linux distributions and multiple DHCP servers
 (ISC, Windows 2k3/2k8, ...).


- `aws-batch`: Run batch computing workloads through the AWS Batch service.
- `cargo-clean`: Remove generated artifacts in the `target` directory.
- `rustup-which`: Display which binary will be run for a given command managed by `rustup`.
- `rustup-man`: View the man page for a given command managed by `rustup`.
- `sf`: Salesforce CLI is a powerful command line interface that simplifies development and build automation when working with your Salesforce org.
- `linode-cli`: Manage Linode cloud services.
- `ropgadget`: Find ROP gadgets in binary files.
- `tectonic`: A modern, self-contained TeX/LaTeX engine.
- `rustup-run`: Run a command with an environment configured for a given Rust toolchain.
- `polybar-msg`: Control `polybar` using inter-process-messaging (IPC).
- `todo.sh`: Simple and extensible shell script for managing your `todo.txt` file.
- `bun`: JavaScript runtime and toolkit.
- `rustup-help`: Display help on `rustup` and its subcommands.
- `eza`:  Modern replacement for ls
 eza is an improved file lister with more features and better defaults.
 It uses colours to distinguish file types and metadata. It knows about
 symlinks, extended attributes, and Git. And it’s small, fast, and just
 one single binary.


- `airshare`: Transfer data between two machines in a local network.
- `cb`: Cut, copy, and paste anything in the terminal.
- `imgcat`: Display images on the command-line.
- `cargo-new`: Create a new Cargo package.
- `kinit`:  process launcher to speed up launching KDE applications
 kdeinit is a process launcher somewhat similar to the
 famous init used for booting UNIX.
 .
 It launches processes by forking and then loading a
 dynamic library which should contain a 'kdemain(...)'
 function.
 .
 Using kdeinit to launch KDE applications makes starting
 a typical KDE applications 2.5 times faster (100ms
 instead of 250ms on a P-III 500) It reduces memory
 consumption by approx. 350Kb per application.


- `linode-cli-nodebalancers`: Manage Linode NodeBalancers.
- `zstdcat`: This command is an alias of `zstd --decompress --stdout`.
- `cargo-bench`: Compile and execute benchmarks.
- `linode-cli-object-storage`: Manage Linode Object Storage.
- `cargo-update`: Update dependencies as recorded in `Cargo.lock`.
- `rustic`: Create fast, encrypted, deduplicated backups powered by Rust.
- `cargo-fix`: Automatically fix lint warnings reported by `rustc`.
- `lzfgrep`: This command is an alias of `xzgrep --fixed-strings`.
- `cargo-help`: Display help on `cargo` and its subcommands.
- `peerindex`: Inspect MRT TABLE_DUMPV2 Peer Index Table.
- `op`: Official CLI for 1Password's desktop app.
- `age-keygen`: Generate `age` key pairs.
- `yard`:  Ruby documentation tool
 YARD is a documentation generation tool for the Ruby programming language.
 It enables the user to generate consistent, usable documentation that can be
 exported to a number of formats very easily, and also supports extending for
 custom Ruby constructs such as custom class level definitions.


- `cargo-init`: Create a new Cargo package.
- `aws-cloudwatch`: Monitor AWS resources to gain system-wide visibility into resource utilization, application performance, and operational health.
- `linode-cli-linodes`: Manage Linode instances.
- `ncu`: Find newer versions of package dependencies and check outdated npm packages locally or globally.
- `texcount`: Count words in TeX documents omitting macros.
- `linode-cli-lke`: Manage Linode Kubernetes Engine (LKE) clusters.
- `luajit`:  OpenResty-maintained branch of LuaJIT (interpreter)
 LuaJIT implements the full set of language features defined by Lua 5.1. The
 virtual machine (VM) is API- and ABI-compatible to the standard Lua interpreter
 and can be deployed as a drop-in replacement.
 .
 This package contains the standalone interpreter/jitter that can be used
 as a replacement for the standard lua5.1 interpreter.


- `conda-install`: Install packages into an existing conda environment.
- `rustup-set`: Alter `rustup` settings.
- `rustup-toolchain`: Manage Rust toolchains.
- `mitmweb`: A web-based interactive man-in-the-middle HTTP proxy.
- `rustup-component`: Modify a toolchain's installed components.
- `linode-cli-domains`: Manage Linode Domains and DNS configuration.
- `cargo-version`: Display `cargo` version information.
- `rustup-doc`: Open the offline Rust documentation for the current toolchain.
- `linode-cli-tickets`: Manage Linode Support Tickets.
- `tt`: A terminal based typing test.
- `rustup-override`: Modify directory toolchain overrides.
- `systemd-machine-id-setup`: Initialize the machine ID stored in `/etc/machine-id` at install time with a provisioned or randomly generated ID.
- `pstoedit`:  PostScript and PDF files to editable vector graphics converter
 pstoedit converts Postscript and PDF files to various editable
 vector graphic formats including tgif, xfig, PDF graphics, gnuplot format,
 idraw, MetaPost, GNU Metafile, PIC, Kontour and flattened PostScript.


- `shnsplit`: Splits audio files according to a `.cue` file.
- `shntool-split`: This command is an alias of `shnsplit`.
- `systemd-stdio-bridge`: Implement a proxy between `stdin`/`stdout` and a D-Bus.
- `cbatticon`:  lightweight and fast battery icon status and more
 Utility that displays battery information as battery status, remaining
 percentage, remaining time, using an icon in the system tray.
 .
 Based on code from xbattbar-acpi, cbatticon sits in your system tray,
 reporting on battery events, like plug-in, critical, remaining, etc.
 .
 A regular user can (re)define custom system's behaviour, like performing
 graceful shutdown on critical status, by user-defined thresholds and commands
 on low power/critical.


- `machinectl`: Control the systemd machine manager.
- `yplan`: Generate LaTeX code for a two-page vertical daily planner for any chosen year.
- `extrepo`:  External repository manager
 External repositories are additional software package repositories that
 are not maintained by Debian. Before extrepo, maintainers of such
 repositories would suggest that you download and execute an (unsigned)
 shell script as root, or that you download and install their (unsigned)
 package, which is not ideal for security.
 .
 The extrepo package tries to remedy this, by providing a curated list
 of external repositories that can be enabled by a simple command,
 allowing unsigned scripts to be replaced by a simple "extrepo enable
 example.com_repo".
 .
 Note, however, that while the repositories are curated, and that any
 repositories with malicious content will be removed and/or disabled
 when detected, no warranty is made by the Debian project as to the
 security or quality of the software in these third-party repositories.


- `systemd-dissect`: Introspect and interact with file system OS disk images, specifically Discoverable Disk Images (DDIs).
- `cgclassify`: Move running task(s) to given `cgroups`.
- `pkgctl-release`: Release step to commit, tag and upload build artifacts.
- `systemd-socket-activate`: Socket activation for systemd services.
- `systemd-inhibit`: Prohibit the system from entering certain power states.
- `slurmctld`:  Slurm central management daemon
 The Slurm Workload Manager is an open-source cluster resource management and
 job scheduling system that strives to be simple, scalable, portable,
 fault-tolerant, and interconnect agnostic.
 This package contains the central management daemon slurmctld.


- `slurmd`:  Slurm compute node daemon
 The Slurm Workload Manager is an open-source cluster resource management and
 job scheduling system that strives to be simple, scalable, portable,
 fault-tolerant, and interconnect agnostic.
 This package contains the compute node daemon slurmd.


- `slurmrestd`:  Slurm REST API daemon
 The Slurm Workload Manager is an open-source cluster resource management and
 job scheduling system that strives to be simple, scalable, portable,
 fault-tolerant, and interconnect agnostic.
 This package contains the REST API daemon slurmrestd.


- `systemd-escape`: Escape strings for usage in systemd unit names.
- `slurmstepd`: Slurm daemon for managing and monitoring individual job steps within a multi-step job.
- `systemd-ask-password`: Query the user for a system password.
- `pdfcrop`: Detect and remove margins in each page in a PDF file.
- `systemd-cgls`: Show the contents of the selected Linux control group hierarchy in a tree.
- `rsh`: Execute commands on a remote host.
- `portablectl`: A systemd utility for managing and deploying portable service images on Linux systems.
- `rlogin`: Log in to a remote host.
- `just.js`: A V8 JavaScript runtime for Linux.
- `systemd-cgtop`: Show the top control groups of the local Linux control group hierarchy, ordered by their CPU, memory, or disk I/O load.
- `systemd-nspawn`: Spawn a command or OS in a lightweight container.
- `uncompress`: Uncompress files compressed using the Unix `compress` command.
- `nitch`: A small and incredibly fast system fetch written fully in Nim.
- `systemd-repart`:  Provides the systemd-repart and systemd-sbsign utilities
 systemd-repart is a configuration-driven system partitioning tool. It follows
 the Discoverable Partitions Specification and provides support for encryption
 and dm-verity among other things.
 .
 systemd-sbsign is an EFI binary signing tool.
 .
 systemd-keyutil is a tool to manipulate X.509 certificates.


- `dnsdomainname`: Show the system's DNS domain name.
- `pkgctl-db-update`: Update the pacman database as final release step for packages that have been transfered and staged on <https://repos.archlinux.org>.
- `qm-cloud-init`: Configure cloudinit settings for virtual machines managed by Proxmox Virtual Environment (PVE).
- `libtoolize`: A tool used in the autotools build system to prepare a package for the use of `libtool`.
- `postconf`: Postfix configuration utility.
- `rexec`: Execute a command on a remote host.
- `slurmdbd`:  Secure enterprise-wide interface to a database for Slurm
 The Slurm Workload Manager is an open-source cluster resource management and
 job scheduling system that strives to be simple, scalable, portable,
 fault-tolerant, and interconnect agnostic.
 This package contain SlurmDBD (Slurm DataBase Daemon) that can be
 used to securely manage the accounting data for several Slurm
 clusters in a central location and sacctmgr a command for managing
 user accounts in SlurmDBD.


- `compress`: Compress files using the Unix `compress` command.
- `kernel-install`: Add and remove kernel and initrd images to and from `/boot`.
- `systemd-creds`: List, show, encrypt and decrypt service credentials.
- `rcp`: Copy files between local and remote systems.
- `pkgctl-build`: Build packages inside a clean `chroot`.
- `pamfunc`: Apply a simple arithmetic function to a Netpbm image.
- `open.fish`: Opens files, directories, and URIs with default applications.
- `cadaver`:  command-line WebDAV client
 cadaver supports file upload, download, on-screen display, in-place editing,
 namespace operations (move/copy), collection creation and deletion, property
 manipulation, and resource locking.
 .
 Its operation is similar to the standard BSD ftp(1) client and the Samba
 Project's smbclient(1).
 .
 This package includes GnuTLS (HTTPS) support.
 .
 WebDAV (Web-based Distributed Authoring and Versioning) is a set of
 extensions to the HTTP protocol which allow users to collaboratively edit and
 manage files on remote web servers.


- `anytopnm`: Converts an arbitrary type of image file to common image formats.
- `cargo-login`: Save an API token from the registry locally.
- `ppmhist`: Print a histogram of the colors present in a PPM image.
- `sbigtopgm`: Convert an SBIG CCDOPS file to PGM.
- `set-nodeversion`: Set the default Node.js version for `ps-nvm`.
- `docker-container-diff`: This command is an alias of `docker diff`.
- `git-psykorebase`: Rebase a branch on top of another using a merge commit and only one conflict handling.
- `unimatrix`: Simulate the Matrix look with Unicode characters.
- `ppmtopgm`: Convert a PPM image to a PGM image.
- `kubectl-expose`: Expose a resource as a new Kubernetes service.
- `git-magic`: Automate add, commit, and push routines.
- `ppmtoarbtxt`: Convert a PPM image to an arbitrary text format according to a template.
- `kubectl-apply`: Manages applications through files defining Kubernetes resources. It creates and updates resources in a cluster.
- `wbmptopbm`: Convert a wireless bitmap file to a PBM image.
- `az-acr`: Manage private registries with Azure Container Registries.
- `pamoil`: Turn a PAM image into an oil painting.
- `git-pull-request`: Create a pull request for a project on GitHub.
- `doctl-databases-maintenance-window`: Schedule, and check the schedule of, maintenance windows for your databases.
- `gemtopbm`: This command is superseded by `gemtopnm`.
- `pgmoil`: This command is superseded by `pamoil`.
- `git-fresh-branch`: Create an empty local branch.
- `sirtopnm`: Convert a Solitaire Image Recorder file to a PNM file.
- `brew-uninstall`: Uninstall a Homebrew formula/cask.
- `cargo-vendor`: Vendor all dependencies of a project into the specified directory (default: `vendor`).
- `st4topgm`: Convert an SBIG ST-4 file to PGM.
- `pnmtojpeg`: Converts a PNM image file to the JPEG/JFIF/EXIF image format.
- `gladtex`:  Embed LaTeX equations in HTML files
 GladTeX is a preprocessor that enables the use of LaTeX equations within HTML
 files. The equations, embedded in <EQ>...</EQ> tags, as if within $$..$$ in
 LaTeX, is fed through LaTeX and replaced by images.
 .
 Additionally all images get an alt-tag for alternative texts that contains the
 LaTeX-equivalent of the image. This is handy for text-mode browsers or blind
 people using a screen reader.


- `jpegtopnm`: Converts a JPEG/JFIF file to the PPM or PGM format.
- `kubectl-create`: Create a resource from a file or from `stdin`.
- `ppmtoneo`: Convert a PPM image to an Atari Neochrome file.
- `ppmtopcx`: Convert a PPM image to a PCX file.
- `sputoppm`: Convert an Atari uncompressed Spectrum image to a PPM image.
- `gotelemetry`: A tool for managing Go telemetry data and settings.
- `doctl-databases-firewalls`: Manage firewalls for database clusters.
- `ppmfade`: Generate a transition between two PPM images.
- `imgtoppm`: Converts various image file formats to the PPM (Portable Pixmap) format.
- `spctoppm`: Convert an Atari compressed Spectrum image to a PPM image.
- `pamtowinicon`: Convert a PAM image to a Windows ICO file.
- `rletopnm`: Convert a Utah Raster Tools RLE image file to a PNM file.
- `hub-branch`: Create a branch or show current branch.
- `docker-container-rm`: This command is an alias of `docker rm`.
- `xbmtopbm`: Convert an X11 or X10 bitmap to a PBM image.
- `cargo-metadata`: Output the workspace members and resolved dependencies of current package as JSON.
- `cargo-owner`: Manage the owners of a crate on the registry.
- `pbmtozinc`: Convert a PBM image to a Zinc bitmap as used by the Zinc Interface Library Version 1.0.
- `dotnet-run`: Run a .NET application without explicit compile or launch commands.
- `ppmtospu`: Convert a PPM file to an Atari Spectrum 512 image.
- `cargo-publish`: Upload a package to a registry.
- `telegram-desktop`: Instant messenger with open source clients, chats and stickers.
- `zeisstopnm`: Convert a Zeiss confocal file to Netbpm format.
- `az-apim`: Manage Azure API Management services.
- `pbmmake`: Create a blank bitmap.
- `pamtotiff`: Convert a PAM image to a TIFF file.
- `ilbmtoppm`: Convert an ILBM file to a PPM image.
- `pnmtopclxl`: Convert a PNM file to an HP LaserJet PCL XL printer stream.
- `dub`: Package manager for D packages.
- `brushtopbm`: Convert a Xerox doodle brush file into a PBM image.
- `hub-browse`: Open a GitHub repository in the browser or print the URL.
- `pbmtoxbm`: Convert a PBM image to a X11 or X10 bitmap.
- `sldtoppm`: Convert an AutoCAD slide file to a PPM image.
- `scala-cli`: Tool to interact with the Scala programming language.
- `hipstopgm`: Read a HIPS file as input and return a PGM image as output.
- `ppmtosixel`: Convert a PPM image to DEC sixel format.
- `qoitopam`: Convert a QOI image (Quite OK Image format) to Netpbm.
- `cargo-pkgid`: Print the fully qualified package ID specifier for a package or dependency in the current workspace.
- `ppmmix`: Blend together two PPM images.
- `pnmtotiff`: This command is superseded by `pamtotiff`.
- `ppmcolormask`: Produce a mask of areas of a certain color in a PPM image.
- `ppmshadow`: Add simulated shadows to a PPM image.
- `accelerate`: Accelerate is a library that enables the same PyTorch code to be run across any distributed configuration.
- `hub-fork`: Fork the given GitHub repo. Like `git fork` from `git-extras`.
- `vf`: VirtualFish is a fish shell tool for managing Python virtual environments.
- `brew-update`: Fetch the newest version of Homebrew and all formulae from GitHub using `git` and perform any necessary migrations.
- `cargo-run`: Run the current Cargo package.
- `unp`:  unpack (almost) everything with one command
 unp is a small perl script which makes extraction of any archive files a bit
 easier. It support several compressors and archiver programs, chooses the
 right one(s) automatically and extracts one or more files in one go.
 .
 It might require additional packages to support proprietary archive types like
 "lha", "ace", "rar" (certain versions).


- `xvminitoppm`: Convert an XV thumbnail picture to PPM.
- `docker-container-top`: This command is an alias of `docker top`.
- `pamfile`: Describe Netpbm (PAM or PNM) files.
- `brew-autoremove`: Remove unused formulae previously installed as dependencies.
- `pnmtotiffcmyk`: Convert a PNM image to a CMYK encoded TIFF.
- `doctl-databases`: Manage your MySQL, Redis, PostgreSQL, and MongoDB database services.
- `pgmtost4`: Convert a PGM image to the SBIG ST-4 format.
- `ppmdim`: Dim a PPM image.
- `doctl-databases-user`: View details for, and create, database users.
- `git-delete-squashed-branches`: Delete branches that have been "squashed-merged" into a specified branch and checkout. If no branch is specified, default to the currently checked out branch.
- `ppmtoicr`: Convert a PPM image to NCSA ICR format.
- `brew-list`: List installed formulae/casks or their files.
- `ppmtopuzz`: Convert a PPM image to an X11 puzzle file.
- `docker-diff`: Inspect changes to files or directories on a container's filesystem.
- `tifftopnm`: Convert a TIFF image to a PNM image.
- `ppmshift`: Shift the lines in a PPM image by a randomized amount.
- `asciitopgm`: Convert ASCII graphics into a PGM file.
- `ppmpat`: Produce a PPM image with a pattern.
- `kubectl-scale`: Set a new size for a deployment, replica set, replication controller, or stateful set.
- `pgmmake`: Create PGM image with a uniform gray level.
- `ppmtoxpm`: Convert a PPM image to an X11 version 3 pixmap.
- `doctl-databases-sql-mode`: View and configure a MySQL database cluster’s global SQL modes.
- `pgmbentley`: Bentleyize a PGM image.
- `hub-issue`: Manage Github issues.
- `cargo-uninstall`: Remove a Rust binary installed using `cargo install`.
- `ppmtoeyuv`: Convert a PPM image to an Berkeley YUV file.
- `sgitopnm`: Convert an SGI file to a PNM file.
- `ppmlabel`: Add text to a PPM image.
- `xwdtopnm`: Convert an X11 or X10 window dump file to PNM.
- `set-nodeinstalllocation`: Set the default Node.js installation directory for `ps-nvm`.
- `kubectl-label`: Edit Kubernetes resources.
- `ppmtompeg`: Encode an MPEG-1 stream.
- `ppmntsc`: Make the RGB colors in a PPM image compatible with NTSC or PAL color systems.
- `pamtoqoi`: Convert a Netpbm image to a QOI image (Quite OK Image format).
- `ppmtopict`: Convert a PPM image to a Macintosh PICT file.
- `ybmtopbm`: Convert a Bennet Yee "face" file to PBM.
- `ppmflash`: Brighten a PPM image file.
- `rustdoc`: Generate documentation for a Rust crate.
- `pnmtosir`: Convert a PNM file to a Solitaire Image Recorder file.
- `ps-nvm`: PowerShell-based utility to manage multiple Node.js versions, inspired by `nvm`.
- `cargo-locate-project`: Print the full path to the `Cargo.toml` manifest of the current project.
- `pamnoraw`: This command is an alias of `pamtopnm -plain`.
- `dmd`: Official D compiler.
- `remove-nodeversion`: Uninstall Node.js runtime versions for `ps-nvm`.
- `rawtopgm`: Convert a raw greyscale image to a PGM image.
- `open`: `open` can refer to multiple commands with the same name.
- `pbmlife`: Apply Conway's Rules of Life to a PBM image.
- `eyuvtoppm`: Convert a Berkeley YUV file to PPM.
- `pcxtoppm`: Convert a PCX file to a PPM image.
- `rasttopnm`: Convert a Sun rasterfile to a PNM file.
- `gemtopnm`: Convert a GEM image file into a PNM image.
- `ldc`:  LLVM D Compiler
 LDC is a portable compiler for the D programming language with modern
 optimization and code generation capabilities.
 .
 It uses the official DMD compiler frontend to support the latest version
 of D, and relies on the LLVM Core libraries for code generation.


- `pjtoppm`: Convert a HP PaintJet file to PPM.
- `cargo-search`: Search for packages on <https://crates.io>.
- `git-rebase-patch`: Find the commit the patch applies to and do a rebase.
- `pamtotga`: Convert a Netpbm image to a TrueVision Targa file.
- `ximtoppm`: Convert a XIM file to a PPM image.
- `get-nodeinstalllocation`: Get the current Node.js installation directory for `ps-nvm`.
- `brew-search`: Search for casks and formulae.
- `brew-install`: Install a Homebrew formula or cask.
- `winicontopam`: Convert a Windows ICO file to a PAM file.
- `ppmtv`: Make a PPM Image look like taken from an American TV.
- `winicontoppm`: This command is superseded by `winicontopam`.
- `ppmforge`: Generate fractals resembling clouds, planets and starry skies.
- `cargo-yank`: Remove a pushed crate from the index. This should only be used when you accidentally release a significantly broken crate.
- `cargo-package`: Assemble a local package into a distributable tarball (a `.crate` file).
- `azure-cli`:  Azure Command-Line Interface (CLI)
 The Azure command-line interface (CLI) is Microsoft's cross-platform
 command-line experience for managing Azure resources. The Azure CLI is designed
 to be easy to learn and get started with, but powerful enough to be a great
 tool for building custom automation to use Azure resources.
 .
 This package provides the az executable and bash completion.


- `pamtopnm`: Convert a PAM image to an equivalent PNM image.
- `docker-container-rename`: This command is an alias of `docker rename`.
- `ppmrelief`: Produce a relief of a PPM image.
- `ppmtoppm`: Copy a PPM image.
- `cargo-fetch`: Fetch dependencies of a package from the network.
- `macptopbm`: Read a MacPaint file as input and produce a PBM image as output.
- `docker-top`: Display the running processes of a container.
- `ppmmake`: Create a PPM image of a specified color and dimensions.
- `xpmtoppm`: Convert an X11 pixmap to a PPM image.
- `hub-delete`: Delete an existing repository on GitHub.
- `ppmtolj`: Convert a PPM file to an HP LaserJet PCL 5 Color file.
- `ppmtoacad`: Convert a PPM image to an AutoCAD database or slide.
- `git-rscp`: Reverse `git scp` - copy files from the working directory of a remote repository to the current working tree.
- `ppmtotga`: This command is superseded by `pamtotga`.
- `kubectl-replace`: Replace a resource by file or `stdin`.
- `cargo-generate-lockfile`: Generate the `Cargo.lock` file for the current package. Similar to `cargo update`, but has less options.
- `just.1`: Save and run project-specific commands.
- `tgatoppm`: Convert a TrueVision Targa file to a Netpbm image.
- `doctl-databases-options`: Enable the navigation of available options under each database engine.
- `pgmdeshadow`: Deshadow a PGM image.
- `a2ping`: Convert images into EPS or PDF files.
- `aws-codeartifact`: CLI for AWS CodeArtifact.
- `cargo-tree`: Display a tree visualization of a dependency graph.
- `cargo-verify-project`: Check the correctness of the `Cargo.toml` manifest and print the result as a JSON object.
- `doctl-databases-db`: Manage specific databases that are served by a database cluster.
- `pbmtoybm`: Convert a PBM file to a Bennet Yee "face" file.
- `yuvtoppm`: Convert Abekas YUV bytes to PPM.
- `rage`: A simple, secure and modern file encryption tool (and Rust library) with small explicit keys, no config options, and UNIX-style composability.
- `ppmrainbow`: Generate a rainbow.
- `ppmtomitsu`: Convert a PPM image to a Mitsubishi S340-10 file.
- `dotnet-add-reference`: Add .NET project-to-project references.
- `ppmtobmp`: Convert a PPM image to a BMP file.
- `gdc`:  D compiler (language version 2), based on the GCC backend
 This is a dependency package providing the default D compiler.
 Per policy, all packages that contain D sources must use this package
 in their Build-Depends line.
 .
 This compiler supports D language version 2.


- `pnmtoplainpnm`: This command is an alias of `pamtopnm -plain`.
- `pnmtorast`: Convert a PNM file to a Sun rasterfile.
- `pstopnm`: Convert a PostScript file to a PNM image.
- `hd`: This command is an alias of `hexdump`.
- `pbmtogem`: Read a PBM image as input and produce a compressed GEM .img file as output.
- `pamtopam`: Copy a PAM image.
- `hub-ci-status`: Display status of GitHub checks.
- `hub-clone`: Clone an existing repository.
- `pbmtox10bm`: This command is superseded by `pbmtoxbm -x10`.
- `yuvsplittoppm`: Convert three subsampled Abekas YUV files to one PPM image.
- `brew-upgrade`: Upgrade outdated formulae and casks.
- `doctl-databases-pool`: Manage connection pools for your database cluster.
- `ppmcie`: Draw a CIE color chart as a PPM image.
- `cargo-rustdoc`: Build the documentation of Rust packages.
- `picttoppm`: Convert a Macintosh PICT file to a PPM image.
- `ppmtoleaf`: Convert a PPM image to the Interleaf image format.
- `az-aks`: Manage Azure Kubernetes Service (AKS) clusters.
- `dotnet-add-package`: Add or update a .NET package reference in a project file.
- `hub-create`: Create a new repository on GitHub.
- `ppmdist`: Produce a grayscale version of a PPM image.
- `pnmtorle`: Convert a PNM file to an Utah Raster Tools RLE image file.
- `gitui`: Terminal UI for Git.
- `leaftoppm`: Convert an Interleaf image to a PPM image.
- `install-nodeversion`: Install Node.js runtime versions for `ps-nvm`.
- `ppmtoilbm`: Convert a PPM image to an ILBM file.
- `rawtoppm`: Convert a raw RGB stream to a PPM image.
- `docker-rename`: Rename a container.
- `pamdepth`: Reduce the depth (i.e. color resolution) in an image.
- `doctl-databases-replica`: Manage read-only replicas associated with a database cluster.
- `ppmspread`: Displace the pixels in a PPM image by a randomized amount.
- `pbmtoascii`: Convert a PBM image to ASCII graphics.
- `ppmchange`: Change all pixels of one color in a PPM image to another color.
- `docker-rm`: Remove one or more containers.
- `hub-init`: Initializes a new local git repository.
- `pnmtopng`: Converts a PNM image file to PNG image format.
- `pnmtopnm`: This command is an alias of `pamtopnm`.
- `bioradtopgm`: Convert a Biorad confocal file into a PGM file.
- `get-nodeversions`: List installed and available Node.js versions for `ps-nvm`.
- `pbmtolj`: Convert a PBM file to an HP LaserJet file.
- `ppmtoyuv`: Convert a PPM image to an Abekas YUV file.
- `ppmtowinicon`: This command is superseded by `pamtowinicon`.
- `az-advisor`: Manage Azure subscription information.
- `pbmtowbmp`: Convert a PBM image to a wireless bitmap file.
- `git-guilt`: Show total blame count for files with unstaged changes or calculate the change in blame between two revisions.
- `thinkjettopbm`: Convert a HP ThinkJet printer commands file to a PBM file.
- `cli53`: Command line tool for Amazon Route 53.
- `palmtopnm`: Convert a Palm Bitmap file to a PNM image.
- `ppmtopj`: Convert a PPM file to an HP PaintJet file.
- `pamtoxvmini`: Convert a Netpbm image to an XV thumbnail picture.
- `psidtopgm`: Convert PostScript image data to a PGM image.
- `cargo-logout`: Remove an API token from the registry locally.
- `bmptopnm`: Convert a BMP file into a PBM, PGM, or PNM image.
- `k9s`: View and manage Kubernetes clusters.
- `neotoppm`: Convert an Atari Neochrome NEO file into a PPM image.
- `pnmtops`: Convert a PNM image to a PostScript file.
- `giftopnm`: Convert a GIF file into a PNM image.
- `brew-outdated`: List outdated casks and formulae.
- `cargo-install`: Build and install a Rust binary.
- `pamditherbw`: Apply dithering to a greyscale image, i.e. turn it into a pattern of black and white pixels that look the same as the original greyscale.
- `pnmtoxwd`: Convert a PNM file into an X11 window dump file.
- `pnmtosgi`: Convert a PNM file to an SGI image file.
- `aws-s3-rb`: Delete an empty S3 bucket.
- `pgmtosbig`: Convert a PGM image to the SBIG CCDOPS format.
- `pgmtopgm`: Copy a PGM image file.
- `pnmdepth`: This command is an alias of `pamdepth`.
- `ppmtoyuvsplit`: Convert a PPM image to three subsampled Abekas YUV files.
- `docker-container-remove`: This command is an alias of `docker rm`.
- `kubectl-taint`: Update the taints on one or more nodes.
- `qrttoppm`: Convert a QRT ray tracer file to a PPM image.
- `ppmdither`: Reduce the number of colors in an image by applying dithering.
- `git-paste`: Send commits to a pastebin site using `pastebinit`.
