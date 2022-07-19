# OpSec

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [apps](#local-apps) | [search](#search) | [guide](#guides)

Operational Security

## Contents

- OpSec
   - Contents
   - Intro
- Overview
- Devices
   - Disposal
   - Advanced
- Privacy
   - Best Practices
- Services
   - Tor Browser
   - Tor Orbot
   - Core Apps
   - Messaging
   - Files
   - Social
   - E-mail
   - Images
   - Database
   - GIS
- Search
   - DuckDuckGo
   - Google
   - Wikipedia
   - Quora
- Guides
   - Wikipedia
   - NOLO Legal Press
   - NIH Med Line Plus

## Intro

The goal is to stay on-line with total anonymity. This is nearly impossible. However, general anonymity is possible and it starts with Tor, an e-mail provider, and following best practices.

While all of the topics listed are covered a dozen times over in dozens of on-line locations, and more than one individual or organization has collected related information into a single repository, the manner of presentation and challenges in finding the information prevent the average device user from gaining practical knowledge.

Compounding the problem, service providers are lightly regulated with respect to data privacy and data security. The device user may actively minimize information sharing as a good defense and as a preventative strategy that any individual may achieve at no financial cost.

You must strike a balance between convenience and cross-application anonymity. Employing any service requires creating a username and password, except for the VPN and drop-boxes.

You may choose a system-wide unique username for all providers; a username that is a random hash; a different username per provider; …that is also a random hash.

Regardless of username, you must create a password.

Most providers mandate minimum password content obfuscation. It is best practice to go beyond the minimum. It is best practice to not re-use passwords nor write them on paper nor store them in a plain-text file.

To reduce hassles and maintain best practices you may employ a personal password generating system, for example:

>`Favorite\*Words\*123\*appname'

If you have forgotten the password pieces then it is time to retire.

Day-to-day use of modern interconnected devices reveal more about an individual than may be understood. When applied, this collection of operational security information will help reduce the need to search for a needle in a haystack, and will provide a first step in minimizing unintentional information sharing.

# Overview

This document indirectly asks questions that many do not know to ask. The document starts with the device and covers practices and service providers to on-line data repositories.

# Devices

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [apps](#local-apps) | [search](#search) | [guide](#guides)

Devices are pervasive.

Device owners voluntarily and freely give away personal information, visual evidence, and day-to-day location information. Some information leakage may be intentional. Often awareness of how much personal information is out there is only realized after a data breach is announced by an otherwise trusted service provider.

## Disposal

This is what needs to be done when disposing of, or selling, a device:
- Do not smash the device nor toss it in the water
- Learn how to remove the battery
- Learn how to remove the SIM
- Learn how to remove the external storage (SD)

## Advanced

Skip this section unless you are more than a casual device user.
- Learn how to `root` the device
- Learn how to change the IMEI
- Be prepared to ‘factory reset’ the device
- Learn where app files are stored, delete ‘cache’ files

# Privacy

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [apps](#local-apps) | [search](#search) | [guide](#guides)

Privacy protection is a habit, an often repeated “To do...” list. A secure device is rendered insecure with bad operational security habits.
- Turn OFF the device when idle
- Turn OFF GPS and Tower location tracking
- Turn OFF Bluetooth
- Turn OFF sharing
- Turn OFF printing
- Turn ON airplane mode
- In App settings "Data Usage" disable background usage
- In app settings "Storage" clear cache
- Download, install, and use an anonymous VPN
- Connect the device to public Wi-Fi, in airplane mode
- Avoid at work and at home device usage
- Vary the time of day of device usage, presuming device is off between uses
- Vary the location of device usage, presuming device is off between uses
- Provide the minimum required data on-line
- Provide false or obscured data on-line when possible
- Learn how to clear ALL browser data on exit
- Learn how to clear the file open history in all apps
- Learn how to clear the device editor’s clipboard
- Learn how to clear all app’s custom dictionaries
- Before deleting, save the file with large `blank` content

# Services

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [apps](#local-apps) | [search](#search) | [guide](#guides)

***

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

Note: Most service providers have both web and app interfaces. The Google Play store links are abbreviated to id=..., presuming the full URL includes: 

> `https://play.google.com/store/apps/details?`

# Proxy

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

Unlike the rest of the services and apps listed, the first two provide a low-level anonymous connection to the Internet.

Tor and Orbot are transparent services that underlay other apps. Tor is a standalone combo that supports the Firefox browser, and Orbot anonymously redirects all registered apps' Internet traffic.

In general, never connect the device to the Internet through the device’s data plan. Connect through public Wi-Fi, in airplane mode, using anonymous Tor and/or Orbot.

## Tor

| | |
| -----:|:----- |
| Play | `id=org.torproject.torbrowser` |
| Main | `https://www.torproject.com` |
| Note | Tor combines a Firefox browser and VPN |
| Note | No registration nor username required |
| Note | Tap on the Connect button |
| Note | The VPN hides your device IP and location |
| Note | Link to ShowMyIP.com to test |

## Orbot

| | |
| -----:|:----- |
| Play | `id=org.torproject.android` |
| Main | `https://www.torproject.com` |
| Note | Orbot combines an app launcher and VPN |
| Note | Orbot may run along-side Tor. |
| Note | Set VPN mode ON |
| Note | Launch Orbot and activate it - tap ‘Start’ |
| Note | You must select Settings and add apps |
| Note | You may select the Firefox browser app |

## Core Apps

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

There are millions of services & apps.

Most apps either primarily or secondarily connect to the Internet. Few fail to connect to the internet, though some apps are functional in airplane mode with Wi-Fi off. Primary connections include messaging and browsing. Secondary connections include ad delivery and spying. 

Most device users require a few common apps and they default to pre-installed apps, with default ‘Settings’. Always thoroughly update app ‘Settings’.

This list includes anonymous free alternative services (non-app) and apps. The ‘Settings’ for each service or app should be thoroughly updated.

An e-mail address is nearly always required, on its own or to register under other providers. There are several free and anonymous e-mail providers, including Microsoft's Hotmail (Outlook). You may choose to employ several e-mail providers or rely on one.

Several services require two-factor authentication. A few support e-mail and a few require text messaging or one-time-pads. For texting, Google Voice is the most stable voice and texting provider, though it requires a link to an existing mobile number (burner number).

### Hotmail

| | |
| -----:|:----- |
| Play | `id=com.microsoft.office.outlook` |
| Main | `https://outlook.live.com/owa` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | `username@someothermail.com` |
| Note | Tor-related connection failure using app |

### Google Voice

| | |
| -----:|:----- |
| Play | `id=com.google.android.apps.googlevoice` |
| Acct | `NUMBER` |

Google Voice offers a free phone number supporting voice calls and texts over the Internet.

Unfortunately, the number is associated with the device’s phone number. Getting a burner SIM for the device lessens exposure but increases hassle and cost. Getting a separate burner phone reduces hassle but increases cost. There are several dual-SIM phones available. Using a SIM-less burner phone reduces cost, and hassle, but eliminates non-VOIP voice calling and texting and entails Wi-Fi dependency.

## Messaging

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

### Telegram X

| | |
| -----:|:----- |
| Play | `id=org.thunderdog.challegram` |
| Main | `https://web.telegram.org/k` |
| Home | `https://t.me/username` |
| Tiny | `https://t.me` |
| Text | *Google Voice* |
| Note | Scheduled messages |

### Signal

| | |
| -----:|:----- |
| Play | `id=org.thoughtcrime.securesms` |
| Main | `https://signal.com` |
| Home | ` ` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Text | *Google Voice* |
| Pin | `NUMBER` |
| Note | Learning curve |

### Skype

| | |
| -----:|:----- |
| Play | id=`com.skype.raider` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Acct | `NUMBER` |
| Note | Microsoft / Hotmail service |
| Note | New number $9/m, Skype to land-line $4/m |

### WhatsApp

| | |
| -----:|:----- |
| Play | id=`com.whatsapp` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | Facebook service |

## Files

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

Attachments, drop-boxes, and directories.

The largest service provides offer "Office Suites" where files may be stored. Standalone file storage provides some advantages regarding anonymity.

Sharing files anonymously may occur directly or indirectly. Some web-mail services allow attachments. Some forums and discussion groups support posting images and videos.

Several providers operate like a drop-box. Old-school ftp servers mimic local file systems, supporting anonymous logins.

### Github

| | |
| -----:|:----- |
| Play | `id=com.github.android` |
| Login | `https://github.com/login` |
| Home | `https://github.com/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |

### Pastebin

| | |
| -----:|:----- |
| Login | `https://pastebin.com/login` |
| Home | `https://pastebin.com/u/username` |
| User | `username@mailinator.com` |
| Auth | `Pass*Word...` |

### Bitbucket

| | |
| -----:|:----- |
| Play | `id=com.github.android` |
| Main | `https://bitbucket.org` |
| Home | `https://bitbucket.org/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |

### Dropbox

| | |
| -----:|:----- |
| Play | `id=com.dropbox.android` |
| Main | `https://www.Dropbox.com` |
| Home | `https://Dropbox.com/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Anon | `https://www.dropbox.com/s/HASH/file.jpg` |

### Mega

| | |
| -----:|:----- |
| Play | `id=mega.privacy.android.app` |
| Main | `https://www.Mega.nz` |
| Home | `https://Mega.com/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | `https://mega.nz/HASH` |
| Note | Auto-loads DCIM files at setup, bad ! |

## Social

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

Social, groups, communities, and forums.

Ignoring the 500lb gorilla, these services offer a balance between functionality and anonymity.

Two of these services require a mobile number (Google Voice). Two providers support scheduled posts.

### Reddit

| | |
| -----:|:----- |
| Play | `id=com.reddit.frontpage` |
| Main | `https://www.reddit.com` |
| Login | `https://www.reddit.com/login` |
| Home | `https://www.reddit.com/u/username` |
| User | `username` |
| Auth | `Pass*Word...` |

### Tumblr

| | |
| -----:|:----- |
| Play | `id=com.tumblr` |
| Main | `https://tumblr.com` |
| Login | `https://tumblr.com/login` |
| Home | `https://username.tumblr.com` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | Scheduled posts |

### Twitter

| | |
| -----:|:----- |
| Play | `id=com.Twitter.android` |
| Main | `https://twitter.com` |
| Login | `https://twitter.com/i/flow/login` |
| Util | `https://tweetdeck.twitter.com` |
| Home | `https://twitter.com/username` |
| Anon | `https://t.co/HASH` |
| User | `usernameb` |
| Auth | `Pass*Word...` |
| Text | *Google Voice* |
| Note | Scheduled tweets |

### Pinterest

| | |
| -----:|:----- |
| Play | `id=com.pinterest` |
| Main | `https://www.pinterest.com` |
| Login | `https://www.pinterest.com/login` |
| Home | `https://www.pinterest.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |

### Instagram

| | |
| -----:|:----- |
| Play | `id=com.instagram.android` |
| Main | `https://www.instagram.com` |
| Login | `https://www.instagram.com/login` |
| Home | `https://www.instagram.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Text | *Google Voice* |
| Note | Broadcast to other services |

## E-mail

>[top](#services) | [proxy](#proxy) | [core](core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

There are four types of anonymous e-mail:
- Web-mail enabling all functions, without phone verification, employing e-mail aliases to an existing address
- Web-mail enabling send and receive functions, without phone verification, for a new stand-alone address
- Web-mail enabling e-mail forwarding to a second e-mail address, with or without the ‘Send’ function
- Web-mail enabling only the receive function with security through obscurity, public drop-boxes, no login

Trade-offs... some services support file attachments, some do not, where links to anonymous file sharing sites are employed instead. Some require phone verification, but accept Google Voice. Some services are sandboxed within their**** domain. Some expire after a few days or delete e-mail after a few days. Some services rely on CAPTCHA during login. Some have apps that work over a VPN.

Advanced users may combine two or more services: double-forwarding e-mails or ‘sharing’ a drop-box where ‘drafts’ are composed but never sent, requiring regular visits to the site.

These e-mail address providers do not require a mobile phone number nor an existing e-mail address. Note: Hotmail is listed under Core Apps. 

Two providers do not require authentication nor do they provide privacy (drop-boxes).

### Protonmail

| | |
| -----:|:----- |
| Play | `id=ch.Protonmail.android` |
| Main | `https://protonmail.com` |
| Login | `https://account.proton.me/login` |
| User | `username@protonmail.com` |
| Auth | `Pass*Word...` |

### Tutanota

| | |
| -----:|:----- |
| Play | `id=de.tutao.tutanota` |
| Main | `https://mail.tutanota.com` |
| Login | `https://mail.tutanota.com/login` |
| User | `username@tutanota.com` |
| Auth | `Pass*Word...` |
| TOTP | `HASH` |
| Recov | `HASH` |

### Zoho

| | |
| -----:|:----- |
| Play | `id=com.zoho.mail` |
| Main | `https://www.zoho.com` |
| Login | `https://accounts.zoho.eu/signin` |
| Home | `https://mail.zoho.eu/zm` |
| User | `username@zohomail.eu` |
| Auth | `Pass*Word...` |
| Acct | `NUMBER` |
| Note | Scheduled e-mails |
| Note | Web desktop UX |
| Note | OTP support |

### Mailfence

| | |
| -----:|:----- |
| Main | `https://mailfence.com` |
| Login | `https://mailfence.com/login` |
| User | `username@mailfence.com` |
| Auth | `Pass*Word...` |
| Recov | `username@hotmail.com` |

### Trashmail

| | |
| -----:|:----- |
| Main | `https://trashmail.com` |
| User | `username@my10minutemail.com` |
| Auth | `Pass*Word...` |

### Mailnesia

| | |
| -----:|:----- |
| Main | `https://mailnesia.com` |
| Note | *public drop-box* |

### Mailinator

| | |
| -----:|:----- |
| Main | `https://mailinator.com` |
| Note | *public drop-box* |

## Images

>[top](#services) | [proxy](#proxy) | [core](core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

There is cross-over between image file sharing and social media image sharing and image album hosting and file storage.

### Snapfish

| | |
| -----:|:----- |
| Play | `id=com.snapfish.mobile` |
| Main | `https://www.snapfish.com` |
| Home | ` ` |
| Login | `https://www.snapfish.com/loginto` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Text | *Google Voice* |

### Imgur

| | |
| -----:|:----- |
| Play | `id=com.imgur.mobile` |
| Main | `https://www.imgur.com` |
| Home | `https://imgur.com/user/username` |
| Login | `https://www.imgur.com/login` |
| Anon | `https://imgur.com/gallery/HASH` |
| User | `@username` |
| Auth | `Pass*Word...` |
| Recov | `username@hotmail.com` |
| Text | *Google Voice* |

## Database

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

### Mongo DB

| | |
| -----:|:----- |
| Play | `id=in.nexzone.mongodb` |
| Main | `https://cloud.mongodb.com` |
| Login | `https://account.mongodb.com/account` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Acct | `HASH` |

### Clever Cloud

| | |
| -----:|:----- |
| Play | `id=` |
| Main | `https://console.clever-cloud.com` |
| Login | `https://api.clever-cloud.com/v2/session/login` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Acct | `HASH` |
| Note | Linked to GitHub |
| Text | *Google Voice* |
| Note | Some testing |

### Google Data Studio

| | |
| -----:|:----- |
| Play | `id=` |
| Main | `https://datastudio.google.com` |
| Note | Not tested |

### IBM Cloud

| | |
| -----:|:----- |
| Play | `id=` |
| Main | `https://cloud.ibm.com` |
| Note | Not tested |

## GIS

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

### QGIS

| | |
| -----:|:----- |
| Play | `id=com.qgis` |
| Main | ` ` |
| Home | ` ` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | Not tested |

### Google Earth

| | |
| -----:|:----- |
| Play | `id=com.google.Earth` |
| Main | ` ` |
| Home | ` ` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | Not tested |

### ArcGIS Field Maps

| | |
| -----:|:----- |
| Play | `id=com.esri.fieldmaps` |
| Main | ` ` |
| Home | ` ` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | Not tested |

### ArcGIS Earth

| | |
| -----:|:----- |
| Play | `id=com.esri.earth.phone` |
| Main | ` ` |
| Home | ` ` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | Not tested |

# Local Apps

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

Note: To access Device "Developer" mode - select Settings, System, Phone, 7x tap on build number

## Connections

>[top](#local-apps) | [conn](#connections) | [util](#utilities) | [virus](#anti-virus) | [crypt](#cryptography)

### NetX

| | |
| -----:|:----- |
| Play | `id=com.tools.netgel.netx` |
| Note | Some testing |
| Note | Wi-Fi signal analysis and scanner |

### IP Tools

| | |
| -----:|:----- |
| Play | `id=com.ddm.iptools` |
| Note | Some testing |
| Note | Wi-Fi signal analysis and scanner |

### Web Tools

| | |
| -----:|:----- |
| Play | `id=com.ddm.iptools` |
| Note | Some testing |
| Note | Wi-Fi signal analysis and scanner |

### Wi-Fiman

| | |
| -----:|:----- |
| Play | `id=com.ubnt.usurvey` |
| Note | Some testing |
| Note | Wi-Fi signal analysis and scanner |

### NoRoot-Firewall

| | |
| -----:|:----- |
| Play | `id=app.greyshirts.firewall` |
| Note | Not tested |
| Note | IP Tables internet security |

### Dataguard Firewall

| | |
| -----:|:----- |
| Play | `id=com.fulldive.extension.dataguard` |
| Note | No `root` required |
| Note | Not tested |
| Note | IP Tables internet security |

## Utilities

>[top](#local-apps) | [conn](#connections) | [util](#utilities) | [virus](#anti-virus) | [crypt](#cryptography)

### Markor

| | |
| -----:|:----- |
| Play | `id=net.gsantner.markor` |
| Note | Sophisticated program editor, regexp |

### Obsidian

| | |
| -----:|:----- |
| Play | `id=md.obsidian` |
| Note | Sophisticated program editor |

### ACode

| | |
| -----:|:----- |
| Play | `id=com.foxdebug.acodefree` |
| Note | Sophisticated program editor |
| Note | Links to GitHub |

### File-Converter

| | |
| -----:|:----- |
| Play | `id=com.icecoldapps.fileconverter` |
| Note | Extensive list of file formats supported |

### Category-Files

| | |
| -----:|:----- |
| Play | `id=` |
| Note | Sophisticated file manager |

### Termux

| | |
| -----:|:----- |
| Play | `id=com.termux` |
| Note | Linux shell, command-line access |

### Terminal Emulator

| | |
| -----:|:----- |
| Play | `id=jackpal.androidterm` |
| Note | Linux shell, command-line access |

### Hackers Keyboard

| | |
| -----:|:----- |
| Play | `id=org.pocketworkstation.pckeyboard` |
| Note | Some testing |
| Note | Alternative keyboard for programmers |

### BusyBox

| | |
| -----:|:----- |
| Note | Linux shell and tools|
| Note | `root` required |
| Note | Not tested |

## Anti-virus

>[top](#local-apps) | [conn](#connections) | [util](#utilities) | [virus](#anti-virus) | [crypt](#cryptography)

### Norton 360 Anti-Virus

| | |
| -----:|:----- |
| Play | `id=com.symantec.mobilesecurity` |
| Note | Established anti-virus app and scanner |

### AVG Anti-Virus

| | |
| -----:|:----- |
| Play | `id=com.antivirus` |
| Note | Established anti-virus app and scanner |

### McAfee Security

| | |
| -----:|:----- |
| Play | `id=com.wsandroid.suite` |
| Note | Established anti-virus app and scanner |

### Anti-Virus Free

| | |
| -----:|:----- |
| Play | `id=com.Anti-Virus-Free` |
| Note | Anti-virus app and scanner |

### Avira Security

| | |
| -----:|:----- |
| Play | `id=com.avira.android` |
| Note | Anti-virus app and scanner |

## Cryptography

>[top](#local-apps) | [conn](#connections) | [util](#utilities) | [virus](#anti-virus) | [crypt](#cryptography)

### Files by Google

| | |
| -----:|:----- |
| Play | `id=com.google.android.apps.nbu.files` |
| Note | May require update from Play Store |
| Note | Encrypted vault - Browse, Safe Folder, PIN |

### File Locker

| | |
| -----:|:----- |
| Play | `id=inno.filelocker` |
| Note | Ecrypted vault |

### Authenticator

| | |
| -----:|:----- |
| Play | `id=com.google.android.apps.authenticator2` |
| Note | Not tested |
| Note | one-time-pad support for other apps |

### Hash Droid

| | |
| -----:|:----- |
| Play | `id=com.hobbyone.hashdroid` |
| Note | Not tested |
| Note | cryptographic tools |

### Cryptography

| | |
| -----:|:----- |
| Play | `id=com.nitramite.cryptography` |
| Note | Not tested |
| Note | cryptographic tools |

### Authy

| | |
| -----:|:----- |
| Play | `id=com.authy.authy` |
| Note | Not tested |
| Note | cryptographic tools |

# Other

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

## Git Commands

| | |
| -----:|:----- |
| Play | `id=com.shubham.gitcommands` |
| Note | Comprehensive guide to command-line Git |

## Linux Commands

| | |
| -----:|:----- |
| Play | `id=linux.command` |
| Note | Comprehensive guide to command-line Linux |

## Trademarks

| | |
| -----:|:----- |
| Main | `https://uspto.gov` |
| Login | `https://account.uspto.gov` |
| Acct | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Text | *Google Voice* |
| Note | mailing address info required |
| Note | Government photoID required |
| Note | E-file only |
| Note | Lawyer recommended / required |

## Patents

| | |
| -----:|:----- |
| Main | `https://????.gov` |
| Login | `https://account.????.gov` |
| Acct | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Text | *Google Voice* |
| Note | mailing address info required |
| Note | Government photoID required |
| Note | E-file only |
| Note | Lawyer recommended / required |

# Broken

>[top](#services) | [proxy](#proxy) | [core](#core-apps) | [msg](#messaging) | [file](#files) | [soc](#social) | [mail](#e-mail) | [img](#images) | [data](#database) | [gis](#gis) | [local](#local-apps) | [other](#other) | [bad](#broken)

These apps failed to launch or are otherwise not worth your time.

## LinkedIn

| | |
| -----:|:----- |
| Play | `id=com.linkedin.android` |
| Main | `https://www.linkedin.com` |
| Login | `https://www.linkedin.com/login` |
| Home | `https://www.linkedin.com/in/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | account restricted, photo ID to unlock |
| Text | *Google Voice* |

## Yahoo!

| | |
| -----:|:----- |
| Play | `id=com.yahoo.mobile.client.android.mail` |
| Main | `https://yahoo.com` |
| User | `username@yahoo.com` |
| Auth | `Pass*Word*...` |
| Text | *Google Voice* rejected |

## AOL

| | |
| -----:|:----- |
| Note | Owned by Yahoo! |

## Flickr

| | |
| -----:|:----- |
| Play | `id=com.flickr.android` |
| Main | `https://www.flickr.com` |
| Login | `https://www.flickr.com/login` |
| User | `@username` |
| Auth | `Pass*Word...` |
| Recov | `username@hotmail.com` |
| Text | *Google Voice* |
| Note | login loop on app |

## Quora

| | |
| -----:|:----- |
| Play | `id=ccom.quora.android` |
| Main | `https://www.quora.com` |
| Home | `https://www.quora.com/profile/username` |
| Login | `https://www.quora.com/login` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | Tor-related login problems |

## Google Cloud Console

| | |
| -----:|:----- |
| Play | `id=com.google.android.apps.cloudconsole` |
| Main | `https://datastudio.google.com` |
| Note | Tor-related connection failure |

## Microsoft Authenticator

| | |
| -----:|:----- |
| Play | `id=com.azure.authenticator` |
| Note | one-time-pad support for other apps |
| Note | Tor-related connection failure |

## Facebook

| | |
| -----:|:----- |
| Note | Not an anonymous service |

## TikTok

| | |
| -----:|:----- |
| Note | Not an anonymous service |

## Google Docs

| | |
| -----:|:----- |
| Note | Not an anonymous service |
| Note | Linked to mobile number |

# Search

>[[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [apps](#local-apps) | [search](#search) | [guide](#guides)

## Unstructured

### DuckDuckGo

- `https://www.duckduckgo.com`
- Comparable to Google search
- No tracking or data retention
- Has an ‘onion’ web address, through Tor
- Search ‘duckduckgo onion’ to get the address

### Google

- `https://www.google.com`
- Google search over Tor is anonymous
- Tracking or data retention to an anon. exit node
- May have an ‘onion’ web address, through Tor
- Search ‘google onion’ to get the address

## Structured

### Wikipedia

- `https://en.wikipedia.com`
- Technically not a search engine
- Millions of searchable articles 
- Cross referenced to other articles
- Extensive footnotes to print/on-line resources
- Multiple languages
- No ads
- More effective than an open Internet search

### Quora

- `https://www.quora.com`
- Technically not a search engine
- Thousands of searchable questions 
- Answered by peers
- Multiple answers per question
- Related questions listed

# Guides

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [apps](#local-apps) | [search](#search) | [guide](#guides)

## Wikipedia

- `https://en.wikipedia.com`
- Millions of searchable articles 
- Cross referenced to other articles
- Extensive footnotes to print/on-line resources
- Multiple languages
- No ads
- More effective than an open Internet search

## NOLO Press

- `https://nolo.com`
- Hundreds of searchable legal articles
- Dozens of books for sale

## Med Line Plus

- `https://medlineplus.gov`
- World's largest medical library, on-line
- US National Library of Medicine (NLM)
- US National Institutes of Health (NIH).
