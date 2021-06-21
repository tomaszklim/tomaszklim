
### Hi there 👋

<img align="right" src="https://avatars.githubusercontent.com/u/11279221?v=4" width="260">

Welcome on my Github summary page! I work in IT for almost 25 years. Previously I worked for big global companies like Wikia or Allegro Group. Since 2013, I run my own company. Below you'll find some of my projects.


### 👷 Drive Badger

[Drive Badger](https://drivebadger.com/) in an open source platform for covert data exfiltration operations, ranging from small computers to big servers, supporting any version of Windows, Linux and Mac OS, also with Bitlocker, LUKS or Apple FileVault full disk encryption.

Written in 2020 strictly for law enforcement officers, private investigators, corporate Red Teams etc. (see [legal details](https://github.com/drivebadger/drivebadger/wiki/Frequently-Asked-Questions-(legal))), as cold attack complement to my closed source [Sherlock](https://payload.pl/sherlock/) platform.

- [drivebadger/drivebadger](https://github.com/drivebadger/drivebadger) - main repository (see more Wiki links there)
- [drivebadger/hook-fstab](https://github.com/drivebadger/hook-fstab) - hook for processing `/etc/fstab` files and exfiltrating NFS and SMB shares
- [drivebadger/hook-wcxftp](https://github.com/drivebadger/hook-wcxftp) - hook for processing Total Commander `wcx_ftp.ini` files and exfiltrating FTP accounts
- [drivebadger/exclude-windows](https://github.com/drivebadger/exclude-windows) - example exclusion repository (there are 8 such repos, each with different set of exclusions) 
- [drivebadger/bitlocker-demo](https://github.com/drivebadger/bitlocker-demo) - example repository showing how to configure Bitlocker keys


### 👷 Server Farmer

[Server Farmer](https://serverfarmer.org/) is a framework for server management, created around January 2008 and still maintained. Technically, quite similar to Ansible. Business-wise, something completely different, written specifically for small software houses with multiple customers.

- [serverfarmer/serverfarmer](https://github.com/serverfarmer/serverfarmer) - main repository (there are ~80 extensions in separate repositories, only the most important ones are listed below)
- [serverfarmer/heartbeat-linux](https://github.com/serverfarmer/heartbeat-linux) - Heartbeat monitoring subproject (can be used separately)
- [serverfarmer/heartbeat-server](https://github.com/serverfarmer/heartbeat-server) - Heartbeat server part
- [serverfarmer/sf-backup](https://github.com/serverfarmer/sf-backup) - backup (client part)
- [serverfarmer/sm-backup-collector](https://github.com/serverfarmer/sm-backup-collector) - backup (server part)
- [serverfarmer/sm-farm-manager](https://github.com/serverfarmer/sm-farm-manager) - inventory and management tools
- [serverfarmer/sf-ip-allocs](https://github.com/serverfarmer/sf-ip-allocs) - includable lists of IP address ranges allocated for several ISPs, mainly from Poland - you can use it separately, as a part of your custom firewall script


### 👷 Zone Manager

Central DNS/DHCP database with replication to Amazon Route53, BIND, MikroTik routers and other DNS services. Created in 2016 (initially as an internal tool meeting HIPAA requirements for some commercial project) and still maintained.

- [zonemanager/zonemanager](https://github.com/zonemanager/zonemanager)


### 👷 Polynimbus

[Polynimbus](https://polynimbus.it/) is a multi-cloud infrastructure management tool, supporting over 10 major cloud providers. In short it does 2 things: provides an unified API to create and manage VM instances, and provides a web panel with inventory on all connected accounts. Created in 2015 and still maintained.

- [polynimbus/polynimbus](https://github.com/polynimbus/polynimbus) - main repository (to be run on the server with credentials for all connected cloud accounts)
- [polynimbus/polynimbus-panel](https://github.com/polynimbus/polynimbus-panel) - web panel (can be installed on different server)
- [polynimbus/polynimbus-backup](https://github.com/polynimbus/polynimbus-backup) - Backup subproject; fully automatic local backup for object storage (to be installed on storage server)


### 🔨 Projects related to Raspberry Pi and similar boards

Planter (also known as [Harry](https://payload.pl/harry/) or Dirty Harry) is an open source, mobile, wearable, USB evidence planter based on Raspberry Pi. Created in 2017 as a tool strictly for police officers, then redesigned and rewritten from scratch in 2019.

- [pisecurity/planter](https://github.com/pisecurity/planter) - main repository (the only one with "business logic", all the rest is use case-agnostic)
- [pisecurity/planter-drives](https://github.com/pisecurity/planter-drives) - drive management component
- [pisecurity/camera-utils](https://github.com/pisecurity/camera-utils) - photo camera (MTP/PTP devices) management component
- [pisecurity/blinkt-persistence](https://github.com/pisecurity/blinkt-persistence) - driver for Pimoroni Blinkt! LED device
- [pisecurity/bakebit-nanohat-driver](https://github.com/pisecurity/bakebit-nanohat-driver) - driver for BakeBit NanoHat OLED display device
- [pisecurity/minimal-provisioning](https://github.com/pisecurity/minimal-provisioning) - several configuration templates taken from Server Farmer, for manual installation (if Server Farmer is too much for you)
- [pisecurity/mc-black](https://github.com/pisecurity/mc-black) - black theme for Midnight Commander (the same as in Server Farmer, but Debian/Ubuntu-only, and without support for OS versions older than 2009)
- [serverfarmer/sf-thermal-utils](https://github.com/serverfarmer/sf-thermal-utils) - read CPU temperature on various computer architectures, including Raspberry Pi and clones, QNAP devices, and many others


### 🔭 Projects supporting face recognition

- [pisecurity/opencv-manager](https://github.com/pisecurity/opencv-manager) - scripts for compiling OpenCV (including contrib modules and OpenVINO support) on Raspberry Pi and other ARM platforms (see [releases](https://github.com/pisecurity/opencv-manager/releases) for details)
- [pisecurity/phpopencv-manager](https://github.com/pisecurity/phpopencv-manager) - scripts for compiling [php-opencv](https://github.com/php-opencv/php-opencv) on ARM platforms


### 📜 Published articles

- [payload.pl](https://payload.pl/) - offensive IT security magazine (polish language)
- [asperger15k.pl](https://asperger15k.pl/) - career and life success with Asperger Syndrome (polish language)


### 💬 Feedback

If you use one of my projects, I'd love to hear from you! Don't be shy and let me know what you liked and what needs being improved.

Got an issue? Open a ticket, and I'll try to help.

Want me to implement a specific feature for you? Custom extensions or payloads for Drive Badger, Planter or [Hak5](https://hak5.org/) devices? I'm open for help. Contact me and we'll discuss the details.


### 📫 How to reach me

- Twitter: https://twitter.com/PayloadPl
- LinkedIn: https://www.linkedin.com/in/tomaszklim/
- Email: opensource@tomaszklim.pl

