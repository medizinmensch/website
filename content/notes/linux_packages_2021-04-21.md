+++
title = "Linux pacman packages"
date = 2021-04-21
updated =2021-04-21
+++


# Current packages 2021-11-24

```bash
expac -H M "%012m\t%-20n\t%10d" $(comm -23 <(pacman -Qqen ) <({ pacman -Qqg base-devel; expac -l '\n' '%E' base; }  | uniq))
```

```
    1.01 MiB	accountsservice     	D-Bus interface for user account query and manipulation
    0.03 MiB	acpi                	Client for battery, power, and thermal readings
    0.15 MiB	acpid               	A daemon for delivering ACPI power management events with netlink support
    5.56 MiB	alacritty           	A cross-platform, GPU-accelerated terminal emulator
   14.12 MiB	alsa-firmware       	Firmware binaries for loader programs in alsa-tools and hotplug firmware loader
    0.34 MiB	alsa-plugins        	Additional ALSA plugins
    2.21 MiB	alsa-utils          	Advanced Linux Sound Architecture - Utilities
    3.11 MiB	ant                 	Java based build tool
    6.43 MiB	apache              	A high performance Unix-based HTTP server
    3.78 MiB	apparmor            	Mandatory Access Control (MAC) using Linux Security Module (LSM)
    0.28 MiB	arandr              	Provide a simple visual front end for XRandR 1.2.
   61.22 MiB	arduino             	Arduino prototyping platform SDK
    5.91 MiB	artwork-i3          	Wallpapers for manjaro-i3
    0.24 MiB	asciinema           	Record and share terminal sessions
    0.67 MiB	atop                	A system and process level monitor
   29.46 MiB	audacity            	A program that lets you manipulate digital audio waveforms
    1.85 MiB	avahi               	Service Discovery for Linux using mDNS/DNS-SD -- compatible with Bonjour
    9.44 MiB	aws-cli             	Universal Command Line Interface for Amazon Web Services
    0.06 MiB	b43-fwcutter        	firmware extractor for the b43 kernel module
    0.83 MiB	bash-completion     	Programmable completion for the bash shell
    4.62 MiB	bat                 	Cat clone with syntax highlighting and git integration
    8.95 MiB	bdf-unifont         	GNU Unifont Glyphs
    6.76 MiB	bind                	A complete, highly portable implementation of the DNS protocol
    4.01 MiB	blueman             	GTK+ Bluetooth Manager
    7.30 MiB	bluez-utils         	Development and debugging utilities for the bluetooth protocol stack
    0.12 MiB	bmenu               	Bash scripts providing a collection of terminal applications in a simple UI
  168.42 MiB	boost               	Free peer-reviewed portable C++ source libraries (development headers)
    5.15 MiB	borg                	Deduplicating backup program with compression and authenticated encryption
    0.50 MiB	borgmatic           	Simple, configuration-driven backup software for servers and workstations
    5.05 MiB	btrfs-progs         	Btrfs filesystem utilities
    0.14 MiB	bzip2               	A high-quality data compression program
    0.19 MiB	cantarell-fonts     	Humanist sans serif font
  237.32 MiB	chromium            	A web browser built for speed, simplicity, and security
    0.38 MiB	clipit              	Lightweight GTK+ clipboard manager (fork of Parcellite)
   16.37 MiB	coreutils           	The basic file, shell and text manipulation utilities of the GNU operating system
    0.44 MiB	cpupower            	Linux kernel tool to examine and tune power saving related features of your processor
    0.22 MiB	crda                	Central Regulatory Domain Agent for wireless networks
    0.24 MiB	cronie              	Daemon that runs specified programs at scheduled times and related tools
    2.41 MiB	cryptsetup          	Userspace setup tool for transparent encryption of block devices using dm-crypt
   68.81 MiB	dbeaver             	Free universal SQL Client for developers and database administrators (community edition)
    3.59 MiB	deja-dup            	Simple backup tool, that hides the complexity of backing up the Right Way and uses duplicity as the backend
    2.26 MiB	deluge-gtk          	GTK UI for Deluge
    0.83 MiB	device-mapper       	Device mapper userspace library and tools
    0.10 MiB	dfc                 	Display file system space usage using graphs and colors
    2.84 MiB	dhclient            	A standalone DHCP client from the dhcp package
    0.47 MiB	dhcpcd              	RFC2131 compliant DHCP client daemon
    1.47 MiB	diffutils           	Utility programs used for creating patch files
  181.38 MiB	discord             	All-in-one voice and text chat for gamers that's free and secure.
    0.20 MiB	dmidecode           	Desktop Management Interface table related utilities
    0.32 MiB	dmraid              	Device mapper RAID interface
    0.80 MiB	dnsmasq             	Lightweight, easy to configure DNS forwarder and DHCP server
   29.90 MiB	docker-compose      	Fast, isolated development environments using Docker
    0.43 MiB	dosfstools          	DOS filesystem utilities
    0.05 MiB	downgrade           	Bash script for downgrading one or more packages to a version in your cache or the A.L.A.
    2.92 MiB	duplicity           	A utility for encrypted, bandwidth-efficient backups using the rsync algorithm.
    4.93 MiB	e2fsprogs           	Ext2/3/4 filesystem utilities
    0.56 MiB	ecryptfs-utils      	Enterprise-class stacked cryptographic filesystem for Linux
    0.08 MiB	efibootmgr          	Linux user-space application to modify the EFI Boot Manager
  105.49 MiB	emacs               	The extensible, customizable, self-documenting real-time display editor
    0.38 MiB	epdfview            	Lightweight PDF document viewer
    0.81 MiB	exa                 	ls replacement
    0.25 MiB	exfat-utils         	Utilities for exFAT file system
    0.53 MiB	f2fs-tools          	Tools for Flash-Friendly File System (F2FS)
    2.82 MiB	fd                  	Simple, fast and user-friendly alternative to find
   33.96 MiB	ffmpeg              	Complete solution to record, convert and stream audio and video
    0.29 MiB	ffmpegthumbnailer   	Lightweight video thumbnailer that can be used by file managers.
    0.01 MiB	filesystem          	Base Manjaro Linux files
  224.94 MiB	firefox             	Standalone web browser from mozilla.org
    1.07 MiB	flac                	Free Lossless Audio Codec
    2.02 MiB	flameshot           	Powerful yet simple to use screenshot software
    4.91 MiB	foliate             	A simple and modern GTK eBook reader
    0.83 MiB	fprintd             	D-Bus service to access fingerprint readers
    0.04 MiB	fzy                 	A better fuzzy finder
  122.34 MiB	gcc-libs            	Runtime libraries shipped by GCC
    0.05 MiB	gcolor2             	A simple GTK+2 color selector
    6.59 MiB	gconf               	An obsolete configuration database system
   10.65 MiB	gdb                 	The GNU Debugger
  111.89 MiB	gimp                	GNU Image Manipulation Program
   32.31 MiB	git                 	the fast distributed version control system
    0.18 MiB	git-crypt           	Transparent file encryption in Git
    4.19 MiB	git-delta           	Syntax-highlighting pager for git and diff output
   36.32 MiB	github-cli          	The GitHub CLI
   46.01 MiB	glibc               	GNU C Library
    4.29 MiB	gnome-keyring       	Stores passwords and encryption keys
    4.27 MiB	gnome-system-monitor	View current processes and monitor system state
    7.73 MiB	gnome-terminal      	The GNOME Terminal Emulator
    7.24 MiB	gparted             	A Partition Magic clone, frontend to GNU Parted
  121.31 MiB	gradle              	Powerful build system for the JVM
   47.85 MiB	grub                	GNU GRand Unified Bootloader (2)
    2.46 MiB	grub-theme-manjaro-dev	Manjaro Linux grub theme (devel)
    0.23 MiB	gst-libav           	Multimedia graph framework - libav plugin
    3.45 MiB	gst-plugins-bad     	Multimedia graph framework - bad plugins
    0.96 MiB	gst-plugins-base    	Multimedia graph framework - base plugins
    6.13 MiB	gst-plugins-good    	Multimedia graph framework - good plugins
    0.68 MiB	gst-plugins-ugly    	Multimedia graph framework - ugly plugins
    9.94 MiB	gstreamer           	Multimedia graph framework - core
   15.11 MiB	gthumb              	Image browser and viewer for the GNOME Desktop
    0.02 MiB	gtksourceview-pkgbuild	PKGBUILD syntax highlight support in GtkSourceView
    3.22 MiB	gufw                	Uncomplicated way to manage your Linux firewall
    5.18 MiB	gvfs                	Virtual filesystem implementation for GIO
    0.14 MiB	gvfs-afc            	Virtual filesystem implementation for GIO (AFC backend; Apple mobile devices)
    0.16 MiB	gvfs-gphoto2        	Virtual filesystem implementation for GIO (gphoto2 backend; PTP camera, MTP media player)
    0.16 MiB	gvfs-mtp            	Virtual filesystem implementation for GIO (MTP backend; Android, media player)
    0.09 MiB	gvfs-smb            	Virtual filesystem implementation for GIO (SMB/CIFS backend; Windows client)
    0.15 MiB	haveged             	Entropy harvesting daemon using CPU timings
    1.62 MiB	heaptrack           	A heap memory profiler for Linux
    5.62 MiB	hexchat             	A popular and easy to use graphical IRC (chat) client
    0.31 MiB	htop                	Interactive process viewer
   61.01 MiB	hugo                	Fast and Flexible Static Site Generator in Go
    1.19 MiB	inetutils           	A collection of common network programs
    4.55 MiB	intel-ucode         	Microcode update files for Intel CPUs
 1143.23 MiB	intellij-idea-community-edition	IDE for Java, Groovy and other programming languages with advanced refactoring features
    0.93 MiB	inxi                	Full featured CLI system information tool
    0.26 MiB	iperf3              	TCP, UDP, and SCTP network bandwidth measurement tool
    3.18 MiB	iproute2            	IP Routing Utilities
    2.41 MiB	iptables-nft        	Linux kernel packet control tool (using nft interface)
    0.41 MiB	iputils             	Network monitoring tools, including ping
    0.59 MiB	ipw2100-fw          	Intel Centrino Drivers firmware for IPW2100
    0.55 MiB	ipw2200-fw          	Firmware for the Intel PRO/Wireless 2200BG
   87.48 MiB	jdk11-openjdk       	OpenJDK Java 11 development kit
   38.32 MiB	jdk8-openjdk        	OpenJDK Java 8 development kit
    1.02 MiB	jfsutils            	JFS filesystem utilities
    0.67 MiB	jq                  	Command-line JSON processor
   23.87 MiB	keepassxc           	Cross-platform community-driven port of Keepass password manager
    0.05 MiB	keychain            	A front-end to ssh-agent, allowing one long-running ssh-agent process per system, rather than per login
   24.79 MiB	kompose             	Docker compose to Kubernetes transformation tool
    1.98 MiB	kvantum-manjaro     	Maia and Breath themes for kvantum-qt5
   12.25 MiB	leiningen           	Automate Clojure projects
    0.26 MiB	less                	A terminal based program for viewing text files
    0.01 MiB	lib32-flex          	A tool for generating text-scanning programs
    0.10 MiB	lib32-libva-vdpau-driver	VDPAU backend for VA API (32-bit)
    0.58 MiB	lib32-mesa-demos    	Mesa demos and tools (32-bit)
   11.07 MiB	lib32-mesa-vdpau    	Mesa VDPAU drivers (32-bit)
    9.33 MiB	lib32-vulkan-intel  	Intel's Vulkan mesa driver (32-bit)
    6.91 MiB	lib32-vulkan-radeon 	Radeon's Vulkan mesa driver (32-bit)
    0.04 MiB	libdvdcss           	Portable abstraction library for DVD decryption
    1.50 MiB	libgpod             	A shared library to access the contents of an iPod
   11.19 MiB	libva-mesa-driver   	VA-API implementation for gallium
    0.10 MiB	libva-vdpau-driver  	VDPAU backend for VA API
   42.47 MiB	libvirt             	API for controlling virtualization engines (openvz,kvm,qemu,virtualbox,xen,etc)
    0.41 MiB	licenses            	Standard licenses distribution package
    0.43 MiB	lightdm-settings    	A configuration tool for the LightDM display manager
    1.80 MiB	lightdm-slick-greeter	A slick-looking LightDM greeter
  715.60 MiB	linux-firmware      	Firmware files for Linux
   78.30 MiB	linux510            	The Linux510 kernel and modules
    0.11 MiB	logrotate           	Rotates system logs automatically
    0.04 MiB	lsb-release         	LSB version query program
    2.59 MiB	lsd                 	Modern ls with a lot of pretty colors and awesome icons
    6.17 MiB	lvm2                	Logical Volume Manager 2 utilities
    0.39 MiB	lxappearance        	Feature-rich GTK+ theme switcher of the LXDE Desktop
    0.20 MiB	lxinput             	Small program to configure keyboard and mouse for LXDE
    0.00 MiB	maia-console        	Maia color scheme for the console and shell dialog
    2.26 MiB	man-db              	A utility for reading man pages
    5.73 MiB	man-pages           	Linux man pages
    0.00 MiB	manjaro-alsa        	Manjaro meta package for complete ALSA support
    0.17 MiB	manjaro-application-utility	Manjaro Application Utility
    0.08 MiB	manjaro-browser-settings	Manjaro Linux settings browser defaults
    2.44 MiB	manjaro-firmware    	Extra firmwares for Manjaro Linux
    0.35 MiB	manjaro-hello       	A tool providing access to documentation and support for new Manjaro users.
    0.03 MiB	manjaro-hotfixes    	Manjaro Linux Hotfixes
    0.11 MiB	manjaro-i3-settings 	Manjaro Linux i3 settings
    0.00 MiB	manjaro-printer     	Manjaro Printer support (Meta-PKG)
    0.00 MiB	manjaro-pulse       	Manjaro meta package for complete PulseAudio support
    0.03 MiB	manjaro-ranger-settings	Manjaro Linux bspwm settings
    0.00 MiB	manjaro-release     	Manjaro's release definition
    0.70 MiB	manjaro-settings-manager-notifier	Manjaro Linux System Settings Tool (Notifier)
    0.00 MiB	manjaro-system      	Manjaro Linux System - Update script
  235.94 MiB	mariadb             	Fast SQL database server, derived from MySQL
    0.05 MiB	markdown_previewer  	Simple Markdown files previewer.
   26.68 MiB	matcha-gtk-theme    	A flat design themes for GNOME, MATE, Openbox, Unity, XFCE, Budgie
   10.24 MiB	maven               	Java project management and project comprehension tool
    0.95 MiB	mdadm               	A tool for managing/monitoring Linux md device arrays, also known as Software RAID
    0.15 MiB	memtest86+          	Advanced memory diagnostic tool
    7.76 MiB	mesa-demos          	Mesa demos and tools incl. glxinfo + glxgears
   11.51 MiB	mesa-vdpau          	Mesa VDPAU drivers
    0.24 MiB	mhwd                	Manjaro Linux Hardware Detection library and application
    0.03 MiB	mhwd-db             	Manjaro Linux Hardware Detection Database
   60.35 MiB	minikube            	A tool that makes it easy to run Kubernetes locally
    0.00 MiB	mkinitcpio-openswap 	mkinitcpio hook to open swap at boot time
    0.49 MiB	mobile-broadband-provider-info	Network Management daemon
    0.58 MiB	moc                 	An ncurses console audio player designed to be powerful and easy to use
    5.26 MiB	modemmanager        	Mobile broadband modem management service
    0.08 MiB	morc_menu           	A categorized applications menu using dmenu and bash
    0.70 MiB	mosh                	Mobile shell, surviving disconnects with local echo and line editing
    1.91 MiB	mousepad            	Simple text editor for Xfce
    0.12 MiB	mtr                 	Combines the functionality of traceroute and ping into one tool (CLI version)
    2.43 MiB	nano                	Pico editor clone with enhancements
    0.33 MiB	nanomsg             	Simple high-performance implementation of several "scalability protocols"
    0.09 MiB	ncdu                	Disk usage analyzer with an ncurses interface
    0.33 MiB	neofetch            	A CLI system information tool written in BASH that supports displaying images.
   22.16 MiB	neovim              	Fork of Vim aiming to improve user experience, plugins, and GUIs
    0.55 MiB	net-tools           	Configuration tools for Linux networking
    0.09 MiB	netctl              	Profile based systemd network management
    0.59 MiB	network-manager-applet	Applet for managing network connections
   16.50 MiB	networkmanager      	Network connection manager and user applications
    2.85 MiB	networkmanager-openconnect	NetworkManager VPN plugin for OpenConnect
    1.28 MiB	networkmanager-openvpn	NetworkManager VPN plugin for OpenVPN
    0.65 MiB	networkmanager-pptp 	NetworkManager VPN plugin for PPTP
    0.64 MiB	networkmanager-vpnc 	NetworkManager VPN plugin for VPNC
   13.16 MiB	nextcloud-client    	Nextcloud desktop client
    1.50 MiB	nfs-utils           	Support programs for Network File Systems
    0.30 MiB	ninja               	Small build system with a focus on speed
   24.09 MiB	nmap                	Utility for network discovery and security auditing
    5.95 MiB	npm                 	A package manager for javascript
    0.10 MiB	nss-mdns            	glibc plugin providing host name resolution via mDNS
    1.76 MiB	ntfs-3g             	NTFS filesystem driver and utilities
    4.46 MiB	ntp                 	Network Time Protocol reference implementation
    0.13 MiB	nvm                 	Node Version Manager - Simple bash script to manage multiple active node.js versions
   16.66 MiB	obs-studio          	Free, open source software for live streaming and recording
   16.64 MiB	okular              	Document Viewer
    0.05 MiB	openbsd-netcat      	TCP/IP swiss army knife. OpenBSD variant.
    0.06 MiB	openresolv          	resolv.conf management framework (resolvconf)
    5.90 MiB	openssh             	Premier connectivity tool for remote login with the SSH protocol
    0.08 MiB	os-prober           	Utility to detect other OSes on a set of drives
   11.21 MiB	p7zip               	Command-line file archiver with high compression ratio
    0.08 MiB	pa-applet           	PulseAudio system tray applet with volume bar
    0.04 MiB	pacgraph            	Draws a graph of installed packages to PNG/SVG/GUI/console. Good for finding bloat.
  105.97 MiB	palemoon-bin        	Open source web browser based on Firefox focusing on efficiency.
    0.69 MiB	pamac-gtk           	A Package Manager based on libalpm with AUR and Appstream support
   54.32 MiB	pandoc              	Conversion between markup formats
    0.19 MiB	patchutils          	A small collection of programs that operate on patch files
    1.07 MiB	pavucontrol         	PulseAudio Volume Control
    0.28 MiB	pax-utils           	ELF utils that can check files for security relevant properties
    0.27 MiB	pciutils            	PCI bus configuration space access library and tools
    1.36 MiB	pcmanfm             	Extremely fast and lightweight file manager
    0.63 MiB	peek                	Simple screen recorder with an easy to use interface
   58.85 MiB	perl                	A highly capable, feature-rich programming language
    0.08 MiB	perl-file-mimeinfo  	Determine file type, includes mimeopen and mimetype
    0.44 MiB	plocate             	Alternative to locate, faster and compatible with mlocate's database.
    0.33 MiB	polkit-gnome        	Legacy polkit authentication agent for GNOME
    3.98 MiB	polybar             	A fast and easy-to-use status bar
   12.33 MiB	poppler-data        	Encoding data for the poppler PDF rendering library
    0.00 MiB	powerline-fonts     	patched fonts for powerline
    0.62 MiB	powertop            	A tool to diagnose issues with power consumption and power management
    1.53 MiB	procps-ng           	Utilities for monitoring your system and its processes
    0.62 MiB	psmisc              	Miscellaneous procfs tools
    0.25 MiB	pulseaudio-bluetooth	Bluetooth support for PulseAudio
    0.03 MiB	pwgen               	Password generator for creating easily memorable passwords
   48.08 MiB	qemu                	A generic and open source machine emulator and virtualizer
    1.11 MiB	qt5-styleplugins    	Additional style plugins for Qt5
    0.88 MiB	qt5ct               	Qt5 Configuration Utility
  109.69 MiB	qtcreator           	Lightweight, cross-platform integrated development environment
    1.88 MiB	ranger              	A simple, vim-like file manager.
    0.58 MiB	reiserfsprogs       	Reiserfs utilities
    0.24 MiB	rlwrap              	Adds readline-style editing and history to programs.
    1.01 MiB	rpi-imager          	Raspberry Pi Imaging Utility
    0.57 MiB	rsync               	A fast and versatile file copying tool for remote and local files
   13.40 MiB	ruby                	An object-oriented language for quick and easy programming
    0.98 MiB	s-nail              	Environment for sending and receiving mail
    0.08 MiB	sbxkb               	Simple tray XKB indicator
    0.24 MiB	screenfetch         	CLI Bash script to show system/theme info in screenshots
    0.72 MiB	sed                 	GNU stream editor
    3.73 MiB	shadow              	Password and account management tool suite with support for shadow files and PAM
  324.60 MiB	signal-desktop      	Signal Private Messenger for Linux
   58.87 MiB	snapd               	Service and tools for management of snap packages.
    0.59 MiB	socat               	Multipurpose relay
    0.21 MiB	spectre-meltdown-checker	Spectre, Meltdown, Foreshadow, Fallout, RIDL, ZombieLoad vulnerability/mitigation checker
    0.18 MiB	speedtest-cli       	Command line interface for testing internet bandwidth using speedtest.net
    0.44 MiB	sshuttle            	Transparent proxy server that forwards all TCP packets over ssh
    1.65 MiB	strace              	A diagnostic, debugging and instructional userspace tracer
   36.73 MiB	subversion          	A Modern Concurrent Version Control System
    0.51 MiB	sysbench            	Scriptable multi-threaded benchmark tool for databases and systems
    0.09 MiB	sysfsutils          	System Utilities Based on Sysfs
    4.93 MiB	syslog-ng           	Next-generation syslogd with advanced networking and filtering capabilities
    1.58 MiB	sysstat             	a collection of performance monitoring tools (iostat,isag,mpstat,pidstat,sadf,sar)
    0.03 MiB	systemd-fsck-silent 	File system checks for SystemD (silent)
    0.00 MiB	systemd-sysvcompat  	sysvinit compat for systemd
    2.88 MiB	tar                 	Utility used to store, backup, and transport files
    1.24 MiB	tcpdump             	Powerful command-line packet analyzer
   65.98 MiB	telegram-desktop    	Official Telegram Desktop client
    2.53 MiB	terminator          	Terminal emulator that supports tabs and grids
    2.18 MiB	terminus-font       	Monospace bitmap font (for X11 and console)
   67.44 MiB	terraform           	HashiCorp tool for building and updating infrastructure as code idempotently
    3.85 MiB	timeshift           	A system restore utility for Linux
    0.05 MiB	tldr                	Command line client for tldr, a collection of simplified and community-driven man pages.
    0.43 MiB	tlp                 	Linux Advanced Power Management
    2.82 MiB	transmission-qt     	Fast, easy, and free BitTorrent client (Qt GUI)
    0.09 MiB	tree                	A directory listing program displaying a depth indented list of files
    0.56 MiB	ttf-bitstream-vera  	Bitstream Vera fonts.
   10.03 MiB	ttf-dejavu          	Font family based on the Bitstream Vera Fonts with a wider range of characters
   15.31 MiB	ttf-droid           	General-purpose fonts released by Google as part of Android
    7.78 MiB	ttf-inconsolata     	Monospace font for pretty code listings and for the terminal
    2.56 MiB	ttf-indic-otf       	Indic Opentype Fonts collection
   24.43 MiB	ttf-joypixels       	Emoji as a Service (formerly EmojiOne)
    4.16 MiB	ttf-liberation      	Font family which aims at metric compatibility with Arial, Times New Roman, and Courier New
    0.31 MiB	unzip               	For extracting and viewing files in .zip archives
    0.95 MiB	upower              	Abstraction for enumerating power devices, listening to device events and querying history and statistics
    0.31 MiB	usbutils            	A collection of USB tools to query connected USB devices
   13.67 MiB	util-linux          	Miscellaneous system utilities for Linux
    5.58 MiB	vertex-maia-themes  	Manjaro's Maia colored variant of the Vertex-themes
    0.31 MiB	vi                  	The original ex/vi text editor
   58.67 MiB	vibrancy-icons-teal 	Regular and Teal versions of the Vibrancy icon theme
    0.49 MiB	viewnior            	A simple, fast and elegant image viewer program
    3.99 MiB	vim                 	Vi Improved, a highly configurable, improved version of the vi text editor
  161.41 MiB	virtualbox          	Powerful x86 virtualization for enterprise as well as home use
   59.77 MiB	vlc                 	Multi-platform MPEG, VCD/DVD, and DivX player
    0.39 MiB	vnstat              	A console-based network traffic monitor
    0.15 MiB	volumeicon          	Volume control for the system tray
    9.99 MiB	vulkan-intel        	Intel's Vulkan mesa driver
    7.50 MiB	vulkan-radeon       	Radeon's Vulkan mesa driver
    1.93 MiB	w3m                 	Text-based Web browser as well as pager
   19.24 MiB	wallpapers-juhraya  	Community Wallpapers for the Manjarolinux 18.1 Juhraya release
    3.08 MiB	wget                	Network utility to retrieve files from the Web
    0.16 MiB	whois               	Intelligent WHOIS client
    8.83 MiB	wireshark-qt        	Network traffic and protocol analyzer/sniffer - Qt GUI
    0.32 MiB	wmutils             	A set of tools for X windows manipulation.
    5.64 MiB	wpa_supplicant      	A utility providing key negotiation for WPA wireless networks
    1.48 MiB	xarchiver           	GTK+ frontend to various command line archivers
    0.04 MiB	xautolock           	An automatic X screen-locker/screen-saver
    2.95 MiB	xboard              	Graphical user interfaces for chess
    0.03 MiB	xclip               	Command line interface to the X11 clipboard
    4.84 MiB	xcursor-chameleon-pearl	Chameleon X Cursor Theme (pearl flavour)
    1.71 MiB	xcursor-maia        	Cursor theme - part of the Manjaro Maia set
    0.15 MiB	xdg-user-dirs       	Manage user directories like ~/Desktop and ~/Music
    0.28 MiB	xdg-utils           	Command line tools that assist applications with a variety of desktop integration tasks
    0.18 MiB	xdotool             	Command-line X11 automation tool
    0.02 MiB	xf86-input-elographics	X.org Elographics TouchScreen input driver
    0.07 MiB	xf86-input-evdev    	X.org evdev input driver
    0.09 MiB	xf86-input-libinput 	Generic input driver for the X.Org server based on libinput
    0.02 MiB	xf86-input-void     	X.org void input driver
    0.16 MiB	xf86-video-amdgpu   	X.org amdgpu video driver
    0.50 MiB	xf86-video-ati      	X.org ati video driver
    2.16 MiB	xf86-video-intel    	X.org Intel i810/i830/i915/945G/G965+ video drivers
    0.22 MiB	xf86-video-nouveau  	Open Source 3D acceleration driver for nVidia cards
    1.97 MiB	xfburn              	A simple CD/DVD burning tool based on libburnia libraries
    3.60 MiB	xfce4-power-manager 	Power manager for the Xfce desktop
    5.41 MiB	xfsprogs            	XFS filesystem utilities
    3.70 MiB	xorg-server         	Xorg X server
    0.20 MiB	xorg-twm            	Tab Window Manager for the X Window System
    0.02 MiB	xorg-xbacklight     	RandR-based backlight control application
    0.02 MiB	xorg-xhost          	Server access control program for X
    0.03 MiB	xorg-xinit          	X.Org initialisation program
    0.02 MiB	xorg-xkill          	Kill a client by its X resource
    0.05 MiB	xorg-xprop          	Property displayer for X
    5.08 MiB	yarn                	Fast, reliable, and secure dependency management
    7.71 MiB	yay                 	Yet another yogurt. Pacman wrapper and AUR helper written in go.
    0.00 MiB	zensu               	A simple gksu replacment using zenity, yad, kdialog or spacefm
    0.55 MiB	zip                 	Compressor/archiver for creating and modifying zipfiles
   21.33 MiB	zola                	An opinionated static site generator
    6.22 MiB	zsh                 	A very advanced and programmable command interpreter (shell) for UNIX
```

# Extra packages

(includes `yay`)
```
pacman -Qm
```


```
arena-chess-gui 3.10-1
astyle-svn r672-1
bauh 0.9.19-1
czmq-git 20210117-1
duplicati-latest 2.0.5.114-6
infracost 0.9.4-3
js60 60.9.0-2
lens-bin 5.2.5-1
lib32-libcanberra-gstreamer 0.30+2+gc0620e4-3
libcanberra-gstreamer 0.30+2+gc0620e4-3
libfprint-vfs009x-git 1:1.90.1.r5.ge34de1d-2
libglade 2.6.4-8
libopenaptx 0.2.0-1
linux-latest 5.10-1
linux512 5.12.19-1
linux512-virtualbox-host-modules 6.1.26-1
linux59 5.9.16-1
mhwd-catalyst 1:15.201.1151-2
mhwd-nvidia-340xx 340.108-1
minecraft-launcher 921-1
mozilla-common 1.4-6
open-fuse-iso 1.1-1
pm2ml 2017.12-5
polyglot-winboard-git 1:r44.5904a29-2
potato 6-1
powerpill 2020.12.15-2
pygtk 2.24.0-16
python-pillow-simd 1:7.0.0.post3-3
python-sip-pyqt5 4.19.19-3
python2-gobject2 2.28.7-7
python2-mutagen 1.43.1-1
python3-memoizedb 2017.3.30-5
python3-xcgf 2017.3-5
python3-xcpf 2019.11-3
siji-git r23.c691f20-2
splatmoji-git r92.b8d14b4-1
spotify 1:1.1.56.595-1
srandrd 0.6.0-2
stockfish 1:14-1
tcptrack 1.4.3-1
terraform-ls 0.20.1-1
terraformer 0.8.14-1
timeset 1.6-1
tor-browser 10.5.6-2
visual-studio-code-bin 1.57.1-1
vorta 0.8.1-1
xdg-su 1.2.3-2
xf86-input-keyboard 1.9.0-3
xf86-input-mouse 1.9.3-1
xorg-font-utils 7.6-6
xxh-git 0.8.7.r28.g5b76eeb-1
yed 1:3.21.1-1
zoom 5.7.0-1
zotero 5.0.96.2-3
```


# Reasonable Packages:

alacritty ant aws-cli bash-completion bat blueman bluez-utils bmenu borg chromium dbeaver deluge-gtk discord docker-compose emacs exa fd ffmpeg firefox flac flameshot foliate fzy gimp git git-crypt git-delta github-cli gparted gradle htop hugo intellij-idea-community-edition iproute2 iputils jq keepassxc keychain less logrotate lsd man-db man-pages mariadb maven minikube ncdu neofetch neovim nextcloud-client ninja npm nvm obs-studio okular openssh p7zip pandoc pcmanfm plocate polybar powerline-fonts powertop pwgen ranger rpi-imager rsync screenfetch sed signal-desktop snapd spectre-meltdown-checker speedtest-cli sshuttle tar tcpdump telegram-desktop terminator terminus-font terraform tldr tree ttf-bitstream-vera ttf-dejavu ttf-droid ttf-inconsolata ttf-indic-otf ttf-joypixels ttf-liberation unzip vi vim vlc wget yarn yay zip zola zsh powerpill srandrd visual-studio-code-bin zoom zotero