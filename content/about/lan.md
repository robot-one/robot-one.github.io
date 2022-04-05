---
title: LAN
date: 2022-04-05T22:21:38+01:00
lastmod: 2022-04-05T22:21:38+01:00
draft: false
---
Chances are if we are on the same Local Area Network (LAN), I'm serving something. For your convenience, here are the services you can access (you'll have to ask me for the passwords in person; no way I'm putting them in cleartext on the web):

## My LAN
These are served from my Raspberry Pi homeserver, and currently only accessible on my home network.

- [qBittorrent server](http://raspberrypi:8080/) - a torrent client with which we can remotely download public domain media via the Bittorrent, without leaving our PCs on for hours. [Homepage](https://www.qbittorrent.org/download.php)
- [filebrowser](http://raspberrypi:8081/) - access downloaded torrents or files stored on the homeserver's Network Attached Storage (NAS) via any web browser. Looks like Google Drive, but is fully self-hosted. [GitHub Repository](https://github.com/filebrowser/filebrowser)
- [Aria2Ng server](http://raspberrypi:80) - Don't feel like leaving your PC on all night for that big download? Remotely download media to the NAS, by torrents and many other protocols, too. [GitHub Repository](https://github.com/mayswind/AriaNg)
- [WireguardUI](http://raspberrypi:8082/) - still not fully functional, a frontend for the Wireguard VPN protocol, so that eventually I can host my own VPN. [GitHub Repository](https://github.com/EmbarkStudios/wg-ui)
- [AdGuard Home](http://raspberrypi:81/) - **[Currently Disabled]** Network-wide ad blocker and DNS server. Not something the end user needs to worry about, save that they won't see advertising. [GitHub Repository](https://github.com/AdguardTeam/AdGuardHome) 
- [Navidrome](http://raspberrypi:8083/) - **[Currently Disabled]** Spotify replacement, but fully self-hosted with my own music. [Homepage](https://www.navidrome.org/)
- Samba (SMB) access to the 500GB NAS is also enabled. You can access it from `Windows Explorer >> My Computer (This PC) >> Add a network location` or the equivalent on MacOS/iOS/Linux/Android.
- SSH (command line) and SFTP (filesystem) access are also enabled, accessible via the appropriate clients, e.g. [WinSCP] 

## Your LAN
These are served from my PC, and you can access them as long as we're both connected.

- [Cerberus FTP Server](http://vortigern:80) - file server.
- [LanXChange](https://lanxchange.com/) - Apple Airdrop alternative. We can both run the clients and share individual files easily between PC, Mac, Linux, Android.
- [filebrowser](http://vortigern:8081) - I also occasionally run filebrowser to turn my PC into a "Google Drive".
