+++
title = "Linux pacman packages"
date = 2021-04-21
updated =2021-04-21
+++


# Current packages 2021-04-21

```bash
expac -H M "%011m\t%-20n\t%10d" $(comm -23 <(pacman -Qqen | sort) <({ pacman -Qqg base-devel; expac -l '\n' '%E' base; } | sort | uniq)) | sort -n
```

```
   0.00 MiB	maia-console        	Maia color scheme for the console and shell dialog
   0.00 MiB	manjaro-alsa        	manjaro ALSA support (Meta-PKG)
   0.00 MiB	manjaro-printer     	Manjaro Printer support (Meta-PKG)
   0.00 MiB	manjaro-pulse       	manjaro Pulseaudio support (Meta-PKG)
   0.00 MiB	manjaro-release     	Manjaro's release definition
   0.00 MiB	manjaro-system      	Manjaro Linux System - Update script
   0.00 MiB	mkinitcpio-openswap 	mkinitcpio hook to open swap at boot time
   0.00 MiB	powerline-fonts     	patched fonts for powerline
   0.00 MiB	systemd-sysvcompat  	sysvinit compat for systemd
   0.00 MiB	zensu               	A simple gksu replacment using zenity, yad, kdialog or spacefm
   0.01 MiB	filesystem          	Base Manjaro Linux files
   0.01 MiB	lib32-flex          	A tool for generating text-scanning programs
   0.02 MiB	xf86-input-elographics	X.org Elographics TouchScreen input driver
   0.02 MiB	xf86-input-void     	X.org void input driver
   0.02 MiB	xorg-xbacklight     	RandR-based backlight control application
   0.02 MiB	xorg-xhost          	Server access control program for X
   0.02 MiB	xorg-xkill          	Kill a client by its X resource
   0.03 MiB	acpi                	Client for battery, power, and thermal readings
   0.03 MiB	manjaro-hotfixes    	Manjaro Linux Hotfixes
   0.03 MiB	manjaro-ranger-settings	Manjaro Linux bspwm settings
   0.03 MiB	mhwd-db             	Manjaro Linux Hardware Detection Database
   0.03 MiB	pwgen               	Password generator for creating easily memorable passwords
   0.03 MiB	systemd-fsck-silent 	File system checks for SystemD (silent)
   0.03 MiB	xorg-xinit          	X.Org initialisation program
   0.04 MiB	libdvdcss           	Portable abstraction library for DVD decryption
   0.04 MiB	lsb-release         	LSB version query program
   0.04 MiB	pacgraph            	Draws a graph of installed packages to PNG/SVG/GUI/console. Good for finding bloat.
   0.04 MiB	xautolock           	An automatic X screen-locker/screen-saver
   0.05 MiB	downgrade           	Bash script for downgrading one or more packages to a version in your cache or the A.L.A.
   0.05 MiB	gcolor2             	A simple GTK+2 color selector
   0.05 MiB	keychain            	A front-end to ssh-agent, allowing one long-running ssh-agent process per system, rather than per login
   0.05 MiB	markdown_previewer  	Simple Markdown files previewer.
   0.05 MiB	xorg-xprop          	Property displayer for X
   0.06 MiB	b43-fwcutter        	firmware extractor for the b43 kernel module
   0.06 MiB	gtksourceview-pkgbuild	PKGBUILD syntax highlight support in GtkSourceView
   0.06 MiB	openresolv          	resolv.conf management framework (resolvconf)
   0.07 MiB	xf86-input-evdev    	X.org evdev input driver
   0.08 MiB	efibootmgr          	Linux user-space application to modify the EFI Boot Manager
   0.08 MiB	manjaro-browser-settings	Manjaro Linux settings browser defaults
   0.08 MiB	morc_menu           	A categorized applications menu using dmenu and bash
   0.08 MiB	ncdu                	Disk usage analyzer with an ncurses interface
   0.08 MiB	os-prober           	Utility to detect other OSes on a set of drives
   0.08 MiB	pa-applet           	PulseAudio system tray applet with volume bar
   0.08 MiB	perl-file-mimeinfo  	Determine file type, includes mimeopen and mimetype
   0.08 MiB	sbxkb               	Simple tray XKB indicator
   0.09 MiB	gvfs-smb            	Virtual filesystem implementation for GIO (SMB/CIFS backend; Windows client)
   0.09 MiB	netctl              	Profile based systemd network management
   0.09 MiB	sysfsutils          	System Utilities Based on Sysfs
   0.09 MiB	tree                	A directory listing program displaying a depth indented list of files
   0.09 MiB	xf86-input-libinput 	Generic input driver for the X.Org server based on libinput
   0.10 MiB	bmenu               	Bash scripts providing a collection of terminal applications in a simple UI
   0.10 MiB	dfc                 	Display file system space usage using graphs and colors
   0.10 MiB	lib32-libva-vdpau-driver	VDPAU backend for VA API (32-bit)
   0.10 MiB	libva-vdpau-driver  	VDPAU backend for VA API
   0.10 MiB	logrotate           	Rotates system logs automatically
   0.10 MiB	nss-mdns            	glibc plugin providing host name resolution via mDNS
   0.11 MiB	manjaro-i3-settings 	Manjaro Linux i3 settings
   0.12 MiB	mtr                 	Combines the functionality of traceroute and ping into one tool (CLI version)
   0.14 MiB	bzip2               	A high-quality data compression program
   0.14 MiB	gvfs-afc            	Virtual filesystem implementation for GIO (AFC backend; Apple mobile devices)
   0.14 MiB	memtest86+          	An advanced memory diagnostic tool
   0.15 MiB	acpid               	A daemon for delivering ACPI power management events with netlink support
   0.15 MiB	haveged             	Entropy harvesting daemon using CPU timings
   0.15 MiB	volumeicon          	Volume control for the system tray
   0.15 MiB	xdg-user-dirs       	Manage user directories like ~/Desktop and ~/Music
   0.16 MiB	gvfs-gphoto2        	Virtual filesystem implementation for GIO (gphoto2 backend; PTP camera, MTP media player)
   0.16 MiB	gvfs-mtp            	Virtual filesystem implementation for GIO (MTP backend; Android, media player)
   0.16 MiB	whois               	Intelligent WHOIS client
   0.16 MiB	xf86-video-amdgpu   	X.org amdgpu video driver
   0.17 MiB	manjaro-application-utility	Manjaro Application Utility
   0.17 MiB	xdotool             	Command-line X11 automation tool
   0.18 MiB	git-crypt           	Transparent file encryption in Git
   0.18 MiB	speedtest-cli       	Command line interface for testing internet bandwidth using speedtest.net
   0.19 MiB	asciinema           	Record and share terminal sessions
   0.19 MiB	patchutils          	A small collection of programs that operate on patch files
   0.19 MiB	pulseaudio-bluetooth	Bluetooth support for PulseAudio
   0.20 MiB	dmidecode           	Desktop Management Interface table related utilities
   0.20 MiB	lxinput             	Small program to configure keyboard and mouse for LXDE
   0.20 MiB	xorg-twm            	Tab Window Manager for the X Window System
   0.21 MiB	spectre-meltdown-checker	Spectre, Meltdown, Foreshadow, Fallout, RIDL, ZombieLoad vulnerability/mitigation checker
   0.22 MiB	crda                	Central Regulatory Domain Agent for wireless networks
   0.22 MiB	xf86-video-nouveau  	Open Source 3D acceleration driver for nVidia cards
   0.23 MiB	cronie              	Daemon that runs specified programs at scheduled times and related tools
   0.23 MiB	gst-libav           	Multimedia graph framework - libav plugin
   0.24 MiB	less                	A terminal based program for viewing text files
   0.24 MiB	mhwd                	Manjaro Linux Hardware Detection library and application
   0.24 MiB	rlwrap              	Adds readline-style editing and history to programs.
   0.24 MiB	screenfetch         	CLI Bash script to show system/theme info in screenshots
   0.25 MiB	exfat-utils         	Utilities for exFAT file system
   0.26 MiB	tlp                 	Linux Advanced Power Management
   0.27 MiB	htop                	Interactive process viewer
   0.27 MiB	pciutils            	PCI bus configuration space access library and tools
   0.28 MiB	arandr              	Provide a simple visual front end for XRandR 1.2.
   0.28 MiB	pax-utils           	ELF utils that can check files for security relevant properties
   0.28 MiB	xdg-utils           	Command line tools that assist applications with a variety of desktop integration tasks
   0.29 MiB	ffmpegthumbnailer   	Lightweight video thumbnailer that can be used by file managers.
   0.30 MiB	ninja               	Small build system with a focus on speed
   0.30 MiB	vi                  	The original ex/vi text editor
   0.31 MiB	unzip               	For extracting and viewing files in .zip archives
   0.31 MiB	usbutils            	A collection of USB tools to query connected USB devices
   0.32 MiB	dmraid              	Device mapper RAID interface
   0.32 MiB	wmutils             	A set of tools for X windows manipulation.
   0.33 MiB	polkit-gnome        	Legacy polkit authentication agent for GNOME
   0.34 MiB	alsa-plugins        	Additional ALSA plugins
   0.35 MiB	manjaro-hello       	A tool providing access to documentation and support for new Manjaro users.
   0.35 MiB	vnstat              	A console-based network traffic monitor
   0.38 MiB	clipit              	Lightweight GTK+ clipboard manager (fork of Parcellite)
   0.38 MiB	epdfview            	Lightweight PDF document viewer
   0.39 MiB	iputils             	Network monitoring tools, including ping
   0.39 MiB	lxappearance        	Feature-rich GTK+ theme switcher of the LXDE Desktop
   0.41 MiB	licenses            	Standard licenses distribution package
   0.41 MiB	lightdm-settings    	A configuration tool for the LightDM display manager
   0.43 MiB	dosfstools          	DOS filesystem utilities
   0.44 MiB	plocate             	Alternative to locate, faster and compatible with mlocate's database.
   0.47 MiB	dhcpcd              	RFC2131 compliant DHCP client daemon
   0.48 MiB	borgmatic           	Simple, configuration-driven backup software for servers and workstations
   0.48 MiB	cpupower            	Linux kernel tool to examine and tune power saving related features of your processor
   0.48 MiB	mobile-broadband-provider-info	Network Management daemon
   0.49 MiB	viewnior            	A simple, fast and elegant image viewer program
   0.50 MiB	f2fs-tools          	Tools for Flash-Friendly File System (F2FS)
   0.50 MiB	xf86-video-ati      	X.org ati video driver
   0.55 MiB	ipw2200-fw          	Firmware for the Intel PRO/Wireless 2200BG
   0.55 MiB	zip                 	Compressor/archiver for creating and modifying zipfiles
   0.56 MiB	ecryptfs-utils      	Enterprise-class stacked cryptographic filesystem for Linux
   0.56 MiB	ttf-bitstream-vera  	Bitstream Vera fonts.
   0.57 MiB	rsync               	A fast and versatile file copying tool for remote and local files
   0.58 MiB	lib32-mesa-demos    	Mesa demos and tools (32-bit)
   0.58 MiB	moc                 	An ncurses console audio player designed to be powerful and easy to use
   0.58 MiB	reiserfsprogs       	Reiserfs utilities
   0.59 MiB	ipw2100-fw          	Intel Centrino Drivers firmware for IPW2100
   0.59 MiB	network-manager-applet	Applet for managing network connections
   0.61 MiB	powertop            	A tool to diagnose issues with power consumption and power management
   0.62 MiB	psmisc              	Miscellaneous procfs tools
   0.63 MiB	peek                	Simple screen recorder with an easy to use interface
   0.64 MiB	networkmanager-vpnc 	NetworkManager VPN plugin for VPNC
   0.65 MiB	networkmanager-pptp 	NetworkManager VPN plugin for PPTP
   0.67 MiB	atop                	A system and process level monitor
   0.67 MiB	cantarell-fonts     	Humanist sans serif font
   0.67 MiB	jq                  	Command-line JSON processor
   0.68 MiB	gst-plugins-ugly    	Multimedia graph framework - ugly plugins
   0.69 MiB	manjaro-settings-manager-notifier	Manjaro Linux System Settings Tool (Notifier)
   0.78 MiB	dnsmasq             	Lightweight, easy to configure DNS forwarder and DHCP server
   0.78 MiB	fprintd             	D-Bus service to access fingerprint readers
   0.78 MiB	qt5ct               	Qt5 Configuration Utility
   0.81 MiB	device-mapper       	Device mapper userspace library and tools
   0.83 MiB	bash-completion     	Programmable completion for the bash shell
   0.85 MiB	inxi                	Full featured CLI system information tool
   0.91 MiB	pavucontrol         	PulseAudio Volume Control
   0.95 MiB	gst-plugins-base    	Multimedia graph framework - base plugins
   0.95 MiB	mdadm               	A tool for managing/monitoring Linux md device arrays, also known as Software RAID
   0.96 MiB	upower              	Abstraction for enumerating power devices, listening to device events and querying history and statistics
   0.98 MiB	s-nail              	Environment for sending and receiving mail
   1.01 MiB	accountsservice     	D-Bus interface for user account query and manipulation
   1.02 MiB	jfsutils            	JFS filesystem utilities
   1.06 MiB	flac                	Free Lossless Audio Codec
   1.08 MiB	docker-compose      	Fast, isolated development environments using Docker
   1.11 MiB	inetutils           	A collection of common network programs
   1.11 MiB	qt5-styleplugins    	Additional style plugins for Qt5
   1.19 MiB	backintime-cli      	Simple backup system inspired from the Flyback Project and TimeVault. CLI version.
   1.26 MiB	networkmanager-openvpn	NetworkManager VPN plugin for OpenVPN
   1.36 MiB	pcmanfm             	Extremely fast and lightweight file manager
   1.39 MiB	diffutils           	Utility programs used for creating patch files
   1.47 MiB	nfs-utils           	Support programs for Network File Systems
   1.48 MiB	xarchiver           	GTK+ frontend to various command line archivers
   1.50 MiB	libgpod             	A shared library to access the contents of an iPod
   1.53 MiB	procps-ng           	Utilities for monitoring your system and its processes
   1.60 MiB	heaptrack           	A heap memory profiler for Linux
   1.70 MiB	mousepad            	Simple text editor for Xfce
   1.71 MiB	xcursor-maia        	Cursor theme - part of the Manjaro Maia set
   1.73 MiB	flameshot           	Powerful yet simple to use screenshot software
   1.73 MiB	ntfs-3g             	NTFS filesystem driver and utilities
   1.79 MiB	lightdm-slick-greeter	A slick-looking LightDM greeter
   1.84 MiB	avahi               	Service Discovery for Linux using mDNS/DNS-SD -- compatible with Bonjour
   1.88 MiB	ranger              	A simple, vim-like file manager.
   1.92 MiB	w3m                 	Text-based Web browser as well as pager
   1.97 MiB	xfburn              	A simple CD/DVD burning tool based on libburnia libraries
   1.98 MiB	kvantum-manjaro     	Maia and Breath themes for kvantum-qt5
   2.08 MiB	alsa-utils          	Advanced Linux Sound Architecture - Utilities
   2.16 MiB	xf86-video-intel    	X.org Intel i810/i830/i915/945G/G965+ video drivers
   2.18 MiB	terminus-font       	Monospace bitmap font (for X11 and console)
   2.25 MiB	deluge-gtk          	GTK UI for Deluge
   2.26 MiB	man-db              	A utility for reading man pages
   2.33 MiB	nano                	Pico editor clone with enhancements
   2.41 MiB	iptables            	Linux kernel packet control tool (using legacy interface)
   2.44 MiB	manjaro-firmware    	Extra firmwares for Manjaro Linux
   2.46 MiB	grub-theme-manjaro-dev	Manjaro Linux grub theme (devel)
   2.52 MiB	terminator          	Terminal emulator that supports tabs and grids
   2.55 MiB	cryptsetup          	Userspace setup tool for transparent encryption of block devices using dm-crypt
   2.56 MiB	ttf-indic-otf       	Indic Opentype Fonts collection
   2.74 MiB	networkmanager-openconnect	NetworkManager VPN plugin for OpenConnect
   2.76 MiB	duplicity           	A utility for encrypted, bandwidth-efficient backups using the rsync algorithm.
   2.82 MiB	fd                  	Simple, fast and user-friendly alternative to find
   2.82 MiB	transmission-qt     	Fast, easy, and free BitTorrent client (Qt GUI)
   2.87 MiB	dhclient            	A standalone DHCP client from the dhcp package
   2.88 MiB	tar                 	Utility used to store, backup, and transport files
   2.95 MiB	timeshift           	A system restore utility for Linux
   2.95 MiB	xboard              	Graphical user interfaces for chess
   2.96 MiB	iproute2            	IP Routing Utilities
   2.97 MiB	pamac-gtk           	A Package Manager based on libalpm with AUR and Appstream support
   2.99 MiB	wget                	Network utility to retrieve files from the Web
   3.11 MiB	ant                 	Java based build tool
   3.22 MiB	gufw                	Uncomplicated way to manage your Linux firewall
   3.43 MiB	gst-plugins-bad     	Multimedia graph framework - bad plugins
   3.45 MiB	zsh-theme-powerlevel10k	Powerlevel10k is a theme for Zsh. It emphasizes speed, flexibility and out-of-the-box experience.
   3.46 MiB	intel-ucode         	Microcode update files for Intel CPUs
   3.53 MiB	deja-dup            	Simple backup tool, that hides the complexity of backing up the Right Way and uses duplicity as the backend
   3.56 MiB	blueman             	GTK+ Bluetooth Manager
   3.57 MiB	bauh                	Graphical interface for application management (AppImage, Flatpak, Snap, AUR, Web)
   3.60 MiB	xfce4-power-manager 	Power manager for Xfce desktop
   3.65 MiB	xorg-server         	Xorg X server
   3.73 MiB	shadow              	Password and account management tool suite with support for shadow files and PAM
   3.75 MiB	apparmor            	Mandatory Access Control (MAC) using Linux Security Module (LSM)
   3.79 MiB	vim                 	Vi Improved, a highly configurable, improved version of the vi text editor
   4.13 MiB	ttf-liberation      	Font family which aims at metric compatibility with Arial, Times New Roman, and Courier New
   4.30 MiB	gnome-keyring       	Stores passwords and encryption keys
   4.46 MiB	ntp                 	Network Time Protocol reference implementation
   4.83 MiB	bat                 	Cat clone with syntax highlighting and git integration
   4.84 MiB	syslog-ng           	Next-generation syslogd with advanced networking and filtering capabilities
   4.84 MiB	xcursor-chameleon-pearl	Chameleon X Cursor Theme (pearl flavour)
   4.88 MiB	e2fsprogs           	Ext2/3/4 filesystem utilities
   4.93 MiB	btrfs-progs         	Btrfs filesystem utilities
   5.08 MiB	yarn                	Fast, reliable, and secure dependency management
   5.09 MiB	pygtk               	Python bindings for the GTK widget set
   5.11 MiB	borg                	Deduplicating backup program with compression and authenticated encryption
   5.14 MiB	gvfs                	Virtual filesystem implementation for GIO
   5.36 MiB	xfsprogs            	XFS filesystem utilities
   5.54 MiB	hexchat             	A popular and easy to use graphical IRC (chat) client
   5.55 MiB	lib32-vulkan-radeon 	Radeon's Vulkan mesa driver (32-bit)
   5.58 MiB	vertex-maia-themes  	Manjaro's Maia colored variant of the Vertex-themes
   5.64 MiB	man-pages           	Linux man pages
   5.64 MiB	wpa_supplicant      	A utility providing key negotiation for WPA wireless networks
   5.74 MiB	vulkan-radeon       	Radeon's Vulkan mesa driver
   5.75 MiB	openssh             	Premier connectivity tool for remote login with the SSH protocol
   5.91 MiB	artwork-i3          	Wallpapers for manjaro-i3
   6.00 MiB	lvm2                	Logical Volume Manager 2 utilities
   6.09 MiB	gst-plugins-good    	Multimedia graph framework - good plugins
   6.22 MiB	zsh                 	A very advanced and programmable command interpreter (shell) for UNIX
   6.28 MiB	apache              	A high performance Unix-based HTTP server
   6.59 MiB	gconf               	An obsolete configuration database system
   6.79 MiB	bind                	A complete, highly portable implementation of the DNS protocol
   6.97 MiB	bluez-utils         	Development and debugging utilities for the bluetooth protocol stack
   7.06 MiB	gparted             	A Partition Magic clone, frontend to GNU Parted
   7.23 MiB	lib32-vulkan-intel  	Intel's Vulkan mesa driver (32-bit)
   7.45 MiB	vulkan-intel        	Intel's Vulkan mesa driver
   7.74 MiB	yay                 	Yet another yogurt. Pacman wrapper and AUR helper written in go.
   7.76 MiB	mesa-demos          	Mesa demos and tools incl. glxinfo + glxgears
   7.78 MiB	ttf-inconsolata     	Monospace font for pretty code listings and for the terminal
   9.11 MiB	libva-mesa-driver   	VA-API implementation for gallium
   9.13 MiB	aws-cli             	Universal Command Line Interface for Amazon Web Services
   9.32 MiB	lib32-mesa-vdpau    	Mesa VDPAU drivers (32-bit)
   9.43 MiB	mesa-vdpau          	Mesa VDPAU drivers
   9.72 MiB	gdb                 	The GNU Debugger
   9.93 MiB	gstreamer           	Multimedia graph framework - core
  10.03 MiB	ttf-dejavu          	Font family based on the Bitstream Vera Fonts with a wider range of characters
  10.10 MiB	npm                 	A package manager for javascript
  10.39 MiB	maven               	Java project management and project comprehension tool
  10.63 MiB	modemmanager        	Mobile broadband modem management service
  11.16 MiB	p7zip               	Command-line file archiver with high compression ratio
  11.52 MiB	nextcloud-client    	Nextcloud desktop client
  12.18 MiB	leiningen           	Automate Clojure projects
  12.33 MiB	poppler-data        	Encoding data for the poppler PDF rendering library
  13.35 MiB	ruby                	An object-oriented language for quick and easy programming
  13.84 MiB	util-linux          	Miscellaneous system utilities for Linux
  14.12 MiB	alsa-firmware       	Firmware binaries for loader programs in alsa-tools and hotplug firmware loader
  15.05 MiB	gthumb              	Image browser and viewer for the GNOME Desktop
  15.31 MiB	ttf-droid           	General-purpose fonts released by Google as part of Android
  15.63 MiB	obs-studio          	Free, open source software for live streaming and recording
  15.84 MiB	okular              	Document Viewer
  15.99 MiB	coreutils           	The basic file, shell and text manipulation utilities of the GNU operating system
  16.14 MiB	matcha-gtk-theme    	A flat design themes for GNOME, MATE, Openbox, Unity, XFCE, Budgie
  16.34 MiB	networkmanager      	Network connection manager and user applications
  19.24 MiB	wallpapers-juhraya  	Community Wallpapers for the Manjarolinux 18.1 Juhraya release
  20.14 MiB	zola                	An opinionated static site generator
  20.45 MiB	neovim              	Fork of Vim aiming to improve user experience, plugins, and GUIs
  22.94 MiB	keepassxc           	Cross-platform community-driven port of Keepass password manager
  22.97 MiB	github-cli          	The GitHub CLI
  24.00 MiB	nmap                	Utility for network discovery and security auditing
  24.34 MiB	ttf-joypixels       	Emoji as a Service (formerly EmojiOne)
  29.46 MiB	audacity            	A program that lets you manipulate digital audio waveforms
  31.54 MiB	git                 	the fast distributed version control system
  32.41 MiB	ffmpeg              	Complete solution to record, convert and stream audio and video
  37.69 MiB	arduino             	Arduino prototyping platform SDK
  38.28 MiB	jdk8-openjdk        	OpenJDK Java 8 development kit
  39.60 MiB	qemu                	A generic and open source machine emulator and virtualizer
  41.78 MiB	subversion          	A Modern Concurrent Version Control System
  46.04 MiB	glibc               	GNU C Library
  49.00 MiB	grub                	GNU GRand Unified Bootloader (2)
  54.12 MiB	hugo                	Fast and Flexible Static Site Generator in Go
  57.63 MiB	perl                	A highly capable, feature-rich programming language
  58.19 MiB	vlc                 	Multi-platform MPEG, VCD/DVD, and DivX player
  58.67 MiB	vibrancy-icons-teal 	Regular and Teal versions of the Vibrancy icon theme
  59.64 MiB	snapd               	Service and tools for management of snap packages.
  86.03 MiB	qtcreator           	Lightweight, cross-platform integrated development environment
  87.30 MiB	jdk11-openjdk       	OpenJDK Java 11 development kit
 105.33 MiB	emacs               	The extensible, customizable, self-documenting real-time display editor
 105.85 MiB	palemoon-bin        	Open source web browser based on Firefox focusing on efficiency.
 111.37 MiB	gimp                	GNU Image Manipulation Program
 148.85 MiB	gcc-libs            	Runtime libraries shipped by GCC
 149.70 MiB	linux510            	The Linux510 kernel and modules
 168.28 MiB	boost               	Free peer-reviewed portable C++ source libraries - development headers
 173.46 MiB	discord             	All-in-one voice and text chat for gamers that's free and secure.
 173.99 MiB	thunderbird         	Standalone mail and news reader from mozilla.org
 217.90 MiB	chromium            	A web browser built for speed, simplicity, and security
 221.33 MiB	firefox             	Standalone web browser from mozilla.org
 234.97 MiB	mariadb             	Fast SQL database server, derived from MySQL
 327.10 MiB	signal-desktop      	Signal Private Messenger for Linux
 652.26 MiB	linux-firmware      	Firmware files for Linux (Manjaro Overlay Package)
```

# Extra packages

(includes `yay`)
```
pacman -Qm
```


```
astyle-svn r672-1
czmq-git 20210117-1
duplicati-latest 2.0.5.112-1
electron9 9.4.3-1
js60 60.9.0-2
libfprint-vfs009x-git 1:1.90.1.r5.ge34de1d-2
linux-latest 5.10-1
mhwd-catalyst 1:15.201.1151-2
mhwd-nvidia-340xx 340.108-1
mozilla-common 1.4-6
nanomsg-git 1.1.5.r5.gaab95026-1
open-fuse-iso 1.1-1
pm2ml 2017.12-5
powerpill 2020.12.15-2
python-dbus 1.2.16-3
python-dbus-common 1.2.16-3
python-pillow-simd 1:7.0.0.post3-3
python-sip-pyqt5 4.19.19-3
python2-dbus 1.2.16-3
python2-mutagen 1.43.0-3
python3-memoizedb 2017.3.30-5
python3-xcgf 2017.3-5
python3-xcpf 2019.11-3
splatmoji-git r92.b8d14b4-1
spotify 1:1.1.56.595-1
srandrd 0.6.0-1
timeset 1.6-1
visual-studio-code-bin 1.52.1-1
xdg-su 1.2.3-2
xf86-input-keyboard 1.9.0-3
xf86-input-mouse 1.9.3-1
xorg-font-utils 7.6-6
zoom 5.5.0-1
zotero 5.0.96-1
```