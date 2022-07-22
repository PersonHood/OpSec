# OpSec

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [local](#local) | [search](#search) | [guide](#guides) | [bad](#broken)

Operational Security

## Contents

OpSec
- Contents
- Intro
- Overview

Devices
- Purchase
- Disposal
- Advanced

Privacy

- Isolate
- Restrict
- Share
- Hide

Services

- Proxy
- Core
- Messaging
- Storage
- Social
- E-mail
- Funding
- Images
- Database
- Feeds
- Geographic
- Other

Local

- Connections
- Firewalls
- Encryption
- Editors
- Files
- Terminals
- Hacker
- Anti-Virus
- Authentication
- Hashes

Search

- Structured
- Unstructured Guides
- Wikipedia
- NOLO Press
- Med Line Plus
- Linux Commands
- Git Commands
- Regex Commands

Broken

- Tor is blocked
- Google Voice is blocked
- App is not anonymous

## Intro

The goal is to stay on-line with total anonymity. This is nearly impossible.

However, general anonymity is possible and it starts with Tor, e-mail providers, and following best practices.

Service providers are lightly regulated with respect to data privacy and data security. The device user may actively minimize their information sharing; it is a good defense; and, it is a preventative strategy that any individual may achieve at no financial cost.

However, you must strike a balance between convenience and cross-application anonymity. Employing any service requires creating a username and password. You may choose a system-wide unique username for all providers; a username that is a random hash; a different username per provider; or one that is also a random hash per provider.

Regardless of username, you must create a password. Where most providers mandate a minimum of password content obfuscation, go beyond the minimum. Do not re-use passwords nor write them on paper nor store them in a plain-text file.

To reduce hassles and maintain obscurity you may employ your own personal password generating system. For example:
`Favorite*Words*123*appname`

## Overview

Day-to-day use of modern interconnected devices reveal more about an individual than may be understood. When applied, this collection of operational security information will help reduce the need to search for a needle in a haystack, and will provide a first step in minimizing unintentional information sharing.

This document indirectly asks questions that many do not know to ask. This document starts with the device; covers best practices and service providers; and ends with readily available informational guides.

# Devices

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [local](#local) | [search](#search) | [guide](#guides) | [bad](#broken)

Devices are pervasive, 3+ per person…

Device owners voluntarily and freely give away personal information, visual evidence, and their day-to-day location. Some information sharing is intentional. However, just how much personal information there is only may be realized after a data breach is announced by an otherwise trusted service provider.

## Purchase

This list includes several inexpensive devices.

- Motorola Moto E (4G)
- Motorola Moto G Fast (4G)
- Samsung Galaxy A32 (5G)
- Nokia 2.1 (4G)

## Disposal

This is what needs to be done when disposing or selling a device:

- Do not smash the device nor toss it in water
- Learn how to remove the battery
- Learn how to remove the SIM
- Learn how to remove the external storage (SD)

## Advanced

- Learn how to | `root` your device
   - Download the device’s root kit
   - Recovery mode reboot your device
   - … press volume down + power buttons
   - Install your device’s root kit
   - Reboot your device
- Learn how to change the IMEI
   - Download the app and launch it
- Learn how to backup data
- Learn how to factory reset the device
- Learn where app files are stored, delete caches

# Privacy

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [local](#local) | [search](#search) | [guide](#guides) | [bad](#broken)

Privacy protection is a habit, an often repeated To do... list. A secure device may be rendered insecure with bad operational security habits. Do good, be inconsistent.

## Isolate

- Turn OFF the device when idle
- Turn OFF location tracking (GPS, tower, etc.)
- Turn OFF Bluetooth
- Turn OFF sharing
- Turn OFF printing
- In app settings "- Data Usage" disable “- Background”
- In app settings "- Battery" enable “- Restrict”
- In app settings "- Storage" clear “- Cache”

## Restrict

- Turn ON airplane mode
- Download, install, and use an anonymous VPN
- Connect the device to public Wi-- Fi
- Avoid at work device usage
- Avoid at home device usage
- Vary the times of device usage
- Vary the locations of device usage

## Share

- Turn ON airplane mode
- Provide the minimum required data on-line
- Provide false or obscured data on-line, when possible

## Hide

- Turn ON airplane mode
- Learn how to clear ALL browser data on exit
- Learn how to clear all apps’ file open history
- Learn how to clear all apps’ custom dictionaries
- Learn how to clear all editors’ clipboards
- Before deleting, save files with large | `blank` content

# Services

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [local](#local) | [search](#search) | [guide](#guides) | [bad](#broken)

Note: Most service providers have both web and app interfaces. The listed Google Play Store links are abbreviated to | `id=`.

This presumes the full URL includes:
`https://play.google.com/store/apps/details?`

Whenever possible, 2 or more app/services are listed. Try out each and pick the one that fits best.

## Proxy

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

Unlike the rest of the services and apps listed, the first two provide a low-level anonymous connection to the Internet.

Tor and Orbot are transparent services that underlay other apps. Tor is a standalone combo that supports the Firefox browser, and Orbot anonymously redirects all registered apps' Internet traffic. In general, never connect the device to the Internet through the device’s data plan. Connect through public Wi-Fi, in airplane mode, using anonymous Tor and/or Orbot.

An added layer of anonymity may be achieved by employing | `Onion` addresses in the Tor browser. An | `Onion` address is like a standard URL (https://sitename.com) recognized by Tor and directed to otherwise hidden web sites.

### Tor

| | |
| --------:|:------- |
| Play | `id=org.torproject.torbrowser` |
| Home | `https://www.torproject.com` |
| Notes | Tor combines a Firefox browser and VPN |
| | No registration nor username required |
| | Launch Tor and tap the Connect button |
| | The VPN hides your device IP and location |
| | Link to Show MyIP.com to test |

### Orbot

| | |
| --------:|:------- |
| Play | `id=org.torproject.android` |
| Home | `https://www.torproject.com` |
| Notes | Orbot combines an app launcher and VPN |
| | Orbot may run along-side Tor |
| | Set VPN mode ON |
| | Launch Orbot and tap the Start button |
| | You may register the Firefox browser app |

## Core

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

Most apps either primarily or secondarily connect to the Internet. Few fail to connect to the internet, though some apps are functional in airplane mode with Wi-Fi off. Primary connections include messaging and browsing. Secondary connections include ad delivery and spying. Most device users require a few common apps and they default to pre-installed apps, with default Settings. Always thoroughly update app Settings.

This list includes anonymous free alternative services and apps. The Settings for each service or app should be thoroughly updated. An e-mail address is nearly always required, on its own or to register under other providers. There are several free and anonymous e-mail providers, including Microsoft's Hotmail (Outlook). You may choose to employ several e-mail providers or rely on one.

Several services require two-factor authentication. A few support e-mail and a few require text messaging or one-time-pads.

### Microsoft Hotmail

| | |
| --------:|:------- |
| Play | `id=com.microsoft.office.outlook` |
| Login | `https://outlook.live.com/owa` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | `username@protonmail.com` |
| Note | Connection failure using app over Tor |

### Protonmail

| | |
| --------:|:------- |
| Play | `id=ch.protonmail.android` |
| Login | `https://account.proton.me/login` |
| User | `username@protonmail.com` |
| Auth | `Pass*Word...` |
| Recov | ` ` |
| Note | |

For texting, Google Voice is the most stable provider, though the service requires a link to an existing number.

### Google Voice

| | |
| --------:|:------- |
| Play | `id=com.google.android.apps.googlevoice` |
| Acct | `NUM-BERS` |

Google Voice offers a free phone number, supporting voice calls and texts over the Internet.

Getting a burner SIM for your device lessens exposure but increases hassle and cost.

Getting a separate burner phone and/or SIM reduces connections with your established number.

## Messaging

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

### Telegram X

| | |
| --------:|:------- |
| Play | `id=org.thunderdog.challegram` |
| Home | `https://t.me/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Text | Google Voice / { burner phone } |
| Note | Scheduled messages |

### Signal

| | |
| --------:|:------- |
| Play | `id=org.thoughtcrime.securesms` |
| Home | app only |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | Google Voice / { burner phone } |
| Pin | `NUMBER` |

### Microsoft Skype

| | |
| --------:|:------- |
| Play | `id=com.skype.raider` |
| Home | app only |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Acct | `NUMBER` |
| Note | Microsoft / Hotmail service |

### Facebook Whats App

| | |
| --------:|:------- |
| Play | `id=com.whatsapp` |
| Home | app only |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | Facebook service |

### Text Free

| | |
| --------:|:------- |
| Play | `id=com.` |
| Home | app only |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | |

### Text Me

| | |
| --------:|:------- |
| Play | `id=com.` |
| Home | app only |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Note | |

## Storage

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

The largest service provides offer "Office Suites" where files may be stored. Standalone file storage provides some advantages regarding anonymity.

### Git Hub

| | |
| --------:|:------- |
| Play | `id=com.github.android` |
| Login | `https://github.com/login` |
| Home | `https://github.com/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | The app does not support editing |

### Pastebin

| | |
| --------:|:------- |
| Play | NA |
| Login | `https://pastebin.com/login` |
| Home | `https://pastebin.com/u/username` |
| User | `username@mailinator.com` |
| Auth | `Pass*Word...` |
| Recov | |

### Bitbucket

| | |
| --------:|:------- |
| Play | `id=com.github.android` |
| Login | `https://bitbucket.org` |
| Home | `https://bitbucket.org/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | |

### Dropbox

| | |
| --------:|:------- |
| Play | `id=com.dropbox.android` |
| Login | `https://www.dropbox.com` |
| Home | `https://Dropbox.com/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | |

### Mega

| | |
| --------:|:------- |
| Play | `id=mega.privacy.android.app` |
| Login | `https://www.mega.nz` |
| Home | `https://Mega.com/username` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | `https://mega.nz/HASH` |
| Note | Auto-loads DCIM files at setup, bad ! |

## Social

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

Social, groups, communities, and forums.

Ignoring the 500lb gorilla, these services offer a balance between functionality and anonymity.

### Reddit

| | |
| --------:|:------- |
| Play | `id=com.reddit.frontpage` |
| Login | `https://www.reddit.com/login` |
| Home | `https://www.reddit.com/u/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### Tumblr

| | |
| --------:|:------- |
| Play | `id=com.tumblr` |
| Login | `https://tumblr.com/login` |
| Home | `https://username.tumblr.com` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Scheduled posts |

### Twitter

| | |
| --------:|:------- |
| Play | `id=com.twitter.android` |
| Login | `https://twitter.com/i/flow/login` |
| Home | `https://twitter.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |
| Text | Google Voice / { burner phone } |
| Note | Scheduled tweets |

### Kik

| | |
| --------:|:------- |
| Play | `id=kik.android` |
| Login | app only |
| Home | app only |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Kik QR code |

### Pinterest

| | |
| --------:|:------- |
| Play | `id=com.pinterest` |
| Login | `https://www.pinterest.com/login` |
| Home | `https://www.pinterest.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### Instagram

| | |
| --------:|:------- |
| Play | `id=com.instagram.android` |
| Login | `https://www.instagram.com/login` |
| Home | `https://www.instagram.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Broadcast to other services |

## E-mail

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

There are four types of anonymous e-mail:
- Services enabling send and receive functions, without phone verification, employing e-mail aliases to an old address
- Services enabling send and receive functions, without phone verification, for a new address
- Services enabling e-mail forwarding to an old address, with/without the Send function
- Services enabling only the receive function with security through obscurity, public drop-boxes, no login

Trade-offs: some services do not support file attachments, where links to anonymous file sharing sites may be employed.

### Tutanota

| | |
| --------:|:------- |
| Play | `id=de.tutao.tutanota` |
| Login | `https://mail.tutanota.com/login` |
| User | `username@tutanota.com` |
| Auth | `Pass*Word...` |
| TOTP | `HASH` |
| Recov | `HASH`{ locked with min. usage } |

### Mailfence

| | |
| --------:|:------- |
| Play | NA |
| Login | `https://mailfence.com/login` |
| User | `username@mailfence.com` |
| Auth | `Pass*Word...` |
| Recov | `username@hotmail.com` |

### Zoho

| | |
| --------:|:------- |
| Play | `id=com.zoho.mail` |
| Login | `https://accounts.zoho.eu/signin` |
| User | `username@zohomail.eu` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Scheduled e-mails; Web desktop UX; OTP |

### Trashmail

| | |
| --------:|:------- |
| Play | web only |
| Login | `https://trashmail.com/login` |
| User | `username@my10minutemail.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | { deleted after set time? } |

### Mailnesia

| | |
| --------:|:------- |
| Play | web only |
| Home | `https://mailnesia.com` |
| User | NA |
| Auth | NA |
| Note | public drop-box |

### Mailinator

| | |
| --------:|:------- |
| Play | web only |
| Login | `https://mailinator.com` |
| Home | NA |
| User | NA |
| Auth | NA |
| Recov | |
| Note | public drop-box |

## Funding

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

This is not an anonymous activity. However, as an anonymous user you may want to cryto-contribute.

### Patreon

| | |
| --------:|:------- |
| Play | `id=com.patreon.android` |
| Login | `https://www.patreon.com/login` |
| Home | `https://www.patreon.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Avoid app, low ratings |

### Kickstarter

| | |
| --------:|:------- |
| Play | `id=com.kickstarter.kickstarter` |
| Login | `https://www.kickstarter.com/login` |
| Home | `https://www.kickstarter.com/profile?ref=` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Avoid app, low ratings |

### Go Fund Me

| | |
| --------:|:------- |
| Play | `id=com.gofundme.gofundme` |
| Login | `https://www.gofundme.com/sign-in` |
| Home | `https://www.gofundme.com/f/causename` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Avoid app, low ratings |

## Images

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

Images may be stored wherever other files are stored, however these sites cross-sell image products and services.

### Snapfish

| | |
| --------:|:------- |
| Play | `id=com.snapfish.mobile` |
| Login | `https://www.snapfish.com/loginto` |
| Home | NA |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Text | Google Voice / { burner phone } |

### Imgur

| | |
| --------:|:------- |
| Play | `id=com.imgur.mobile` |
| Login | `https://www.imgur.com/login` |
| Home | `https://imgur.com/user/username` |
| User `@username` |
| Auth | `Pass*Word...` |
| Recov | `username@hotmail.com` |
| Text | Google Voice / { burner phone } |

## Database

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

### Mongo DB

| | |
| --------:|:------- |
| Play | `id=in.nexzone.mongodb` |
| Login | `https://account.mongodb.com/account` |
| Home | `https://cloud.mongodb.com` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | |

### Clever Cloud

| | |
| --------:|:------- |
| Play | `id=` |
| Login | `https://api.clever-cloud.com/v2/session/login` |
| Home | `https://console.clever-cloud.com` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | Google Voice / { burner phone } |

### IBM Cloud

| | |
| --------:|:------- |
| Play | `id=` |
| Login | `https://cloud.ibm.com` |
| Home | |
| User | |
| Auth | |
| Recov | |

## Feeds

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

### Aggregator

| | |
| --------:|:------- |
| Play | `id=com.tughi.aggregator` |
| Login | `https://www.aggregator.com/login` |
| Home | `https://www.aggregator.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### Feedly

| | |
| --------:|:------- |
| Play | `id=com.devhd.feedly` |
| Login | `https://www.feedly.com/login` |
| Home | `https://www.feedly.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### Feed Me

| | |
| --------:|:------- |
| Play | `id=com.seazon.feedme` |
| Login | `https://www.feedme.com/login` |
| Home | `https://www.feedne.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

## Geographic

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

### Google Earth

| | |
| --------:|:------- |
| Play | `id=com.google.earth` |
| Login | ` ` |
| Home | ` ` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | API? |

### QGIS

| | |
| --------:|:------- |
| Play | `id=com.qgis` |
| Login | ` ` |
| Home | ` ` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | API? |

### ArcGIS Earth

| | |
| --------:|:------- |
| Play | `id=com.esri.earth.phone` |
| Login | ` ` |
| Home | ` ` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | API? |

## Other

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#messaging) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) | [img](#images) | [data](#database) | [feeds](#feeds) | [geo](#geographic) | [other](#other)

### Hootsuite

| | |
| --------:|:------- |
| Play | `id=com.hootsuite.droid.full` |
| Login | `https://hootsuite.com/member/sso-complete` |
| Home | NA |
| User | `username` |
| Auth | `Pass*Word...` |
| Notes | Broadcast app manager app |
| | 30 day free *trial* |

# Local

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [local](#local) | [search](#search) | [guide](#guides) | [bad](#broken)

Note: To access Device "Developer" mode select Settings, System, Phone, 7x tap on build number.

It is recommended that you register all local apps with Orbot (VPN). Some apps may secretly call back to the mother ship.

## Connections

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### NetX

| | |
| --------:|:------- |
| Play | `id=com.tools.netgel.netx` |
| Note | Wi-Fi signal analysis and scanner |

### IP Tools

| | |
| --------:|:------- |
| Play | `id=com.ddm.iptools` |
| Note | Wi-Fi signal analysis and scanner |

### Web Tools

| | |
| --------:|:------- |
| Play | `id=com.ddm.iptools` |
| Note | Wi-Fi signal analysis and scanner |

### Wi-Fiman

| | |
| --------:|:------- |
| Play | `id=com.ubnt.usurvey` |
| Note | Wi-Fi signal analysis and scanner |

## Firewalls

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### No Root-Firewall

| | |
| --------:|:------- |
| Play | `id=app.greyshirts.firewall` |
| Notes. | IP Tables internet security, no`root` |

### Dataguard Firewall

| | |
| --------:|:------- |
| Play | `id=com.fulldive.extension.dataguard` |
| Note | IP Tables internet security, no`root` |

## Encryption

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### File Locker

| | |
| --------:|:------- |
| Play | `id=inno.filelocker` |
| Note | Encrypted vault |

### Files by Google

| | |
| --------:|:------- |
| Play | `id=com.google.android.apps.nbu.files` |
| Notes | May require Google Play Store update |
| | Encrypted vault Browse, Safe Folder, PIN |

## Editors

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### Markor

| | |
| --------:|:------- |
| Play | `id=net.gsantner.markor` |
| Note | Sophisticated code editor, regexp |

### Obsidian

| | |
| --------:|:------- |
| Play | `id=md.obsidian` |
| Note | Sophisticated code editor, plugins |

### ACode

| | |
| --------:|:------- |
| Play | `id=com.foxdebug.acodefree` |
| Note | Sophisticated code editor, Git | Hub link |

## Files

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### File-Converter

| | |
| --------:|:------- |
| Play | `id=com.icecoldapps.fileconverter` |
| Note | Extensive list of file formats supported |

### X-plore

| | |
| --------:|:------- |
| Play | `id=com.lonelycatgnames.xplore` |
| Note | Sophisticated file manager |

### Total Commander

| | |
| --------:|:------- |
| Play | `id=com.ghisler.android.totalCommander` |
| Note | Sophisticated file manager |

## Terminals

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### Termux

| | |
| --------:|:------- |
| Play | `id=com.termux` |
| Note | Linux shell, command-line access |

### Terminal Emulator

| | |
| --------:|:------- |
| Play | `id=jackpal.androidterm` |
| Note | Linux shell, command-line access |

## Hacker

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### Hackers Keyboard

| | |
| --------:|:------- |
| Play | `id=org.pocketworkstation.pckeyboard` |
| Note | Alternative keyboard for coders |

### Busy Box

| | |
| --------:|:------- |
| Play | NA |
| Note | Linux tools, shell, `root` required |

## Anti-virus

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### Norton 360 Anti-Virus

| | |
| --------:|:------- |
| Play | `id=com.symantec.mobilesecurity` |
| Note | Established anti-virus app and scanner |

### AVG Anti-Virus

| | |
| --------:|:------- |
| Play | `id=com.antivirus` |
| Note | Established anti-virus app and scanner |

### Mc Afee Security

| | |
| --------:|:------- |
| Play | `id=com.wsandroid.suite` |
| Note | Established anti-virus app and scanner |

### Anti-Virus Free

| | |
| --------:|:------- |
| Play | `id=com.Anti-Virus-Free` |
| Note | Anti-virus app and scanner |

### Avira Security

| | |
| --------:|:------- |
| Play | `id=com.avira.android` |
| Note | Anti-virus app and scanner |

## Authentication

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### Authenticator

| | |
| --------:|:------- |
| Play | `id=com.google.android.apps.authenticator2` |
| Note | one-time-pad support for other apps |

### Twilio Authy

| | |
| --------:|:------- |
| Play | `id=com.authy.authy` |
| Note | cryptographic tools |

## Hashes

>[top](#local) | [conn](#connections) | [wall](#firewalls) | [edit](#editors) | [files](#files) | [hack](#hacker) | [term](#terminals) | [virus](#anti-virus) | [auth](#authentication) | [hash](#hashes)

### Hash Droid

| | |
| --------:|:------- |
| Play | `id=com.hobbyone.hashdroid` |
| Note | cryptographic tools |

### Cryptography

| | |
| --------:|:------- |
| Play | `id=com.nitramite.cryptography` |
| Note | cryptographic tools |

# Search

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [local](#local) | [search](#search) | [guide](#guides) | [bad](#broken)

## Unstructured

### DuckDuckGo

| | |
| --------:|:------- |
| Play | `id=com.duckduckgo.mobile.android` |
| Home | `https://www.duckduckgo.com` |
| Notes | Comparable to Google search |
| | No tracking or data retention |
| | Has an Onion web address, through Tor |
| | Search “duckduckgo Onion” for the URL |

### Google Search

| | |
| --------:|:------- |
| Play | `com.google.android.googlequicksearchbox` |
| Home | `https://www.google.com` |
| Notes | Google search over Tor is anonymous |
| | Tracking/data retention to anon. exit node |
| | May have Onion web address, through Tor |
| | Search “google Onion” to get the address |

### Microsoft Bing
| | |
| --------:|:------- |
| Play | `id=com.microsoft.bing` 
| Home | `https://www.bing.com` |
| Note. | Bing search over Tor is anonymous |

### Yahoo Search

| | |
| --------:|:------- |
| Play | `id=com.yahoo.mobile.client.android.search` |
| Home | `https://search.yahoo.com` |
| Note | Yahoo! search over Tor is anonymous |

## Structured

### Wikipedia

| | |
| --------:|:------- |
| Play | `id=org.wikipedia` |
| Home | `https://en.wikipedia.com` |
| Notes | Technically not a search engine |
| | Millions of searchable articles |
| | Peer-to-peer cross referencing |
| | Extensive footnotes to print/on-line resources |
| | Multiple languages; no ads |
| | More effective than an open Internet search |

### Quora

| | |
| --------:|:------- |
| Play | `id=com.quora.android` |
| Home | `https://www.quora.com` |
| Notes | Technically not a search engine |
| | Thousands of searchable questions |
| | Peer-to-peer answered questions |
| | Multiple answers per question |
| | Related questions listed |

### Craigslist

| | |
| --------:|:------- |
| Play | `id=org.craigslist.craigslistmobile` |
| Home | `https://www.craigslist.org` |
| Note | Peer-to-peer resource searches |

# Guides

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [local](#local) | [search](#search) | [guide](#guides) | [bad](#broken)

### Wikipedia

| | |
| --------:|:------- |
| Play | `id=org.wikipedia` |
| Home | `https://en.wikipedia.com` |
| Note | Millions of searchable articles |
| Notes | Cross referenced to other articles |
| | Extensive footnotes to print/on-line resources |
| | Multiple languages; no ads |
| | More effective than an open Internet search |

### NOLO Press

| | |
| --------:|:------- |
| Play |
| Home | `https://nolo.com` |
| Notes | Hundreds of searchable legal articles |
| | Dozens of books for sale |

### Med Line Plus

| | |
| --------:|:------- |
| Play | NA |
| Home | `https://medlineplus.gov` |
| Notes | World's largest medical library, on-line |
| | US National Institutes of Health (NIH) |

### Linux Commands

| | |
| --------:|:------- |
| Play | `id=linux.command` |
| Home | app only |
| Note | Comprehensive guide to Linux commands |

### Git Commands

| | |
| --------:|:------- |
| Play | `id=com.shubham.gitcommands` |
| Home | app only |
| Note | Comprehensive guide to Git commands |

### Regex Commands

| | |
| --------:|:------- |
| Play | `id=com.techpurush.regexcheatsheet` |
| Home | app only |
| Note | Comprehensive guide to regex |

# Broken

>[top](#opsec) | [dev](#devices) | [priv](#privacy) | [svc](#services) | [local](#local) | [search](#search) | [guide](#guides) | [bad](#broken)

### Yahoo!

| | |
| --------:|:------- |
| Play | `id=com.yahoo.mobile.client.android.mail` |
| Home | `https://yahoo.com` |
| Text | Google Voice rejected |

### Flickr

| | |
| --------:|:------- |
| Play | `id=com.flickr.android` |
| Home | `https://www.flickr.com` |
| Note | login loop on app, Tor / CAPTCHA |

### Linked In

| | |
| --------:|:------- |
| Play | `id=com.linkedin.android` |
| Home | `https://www.linkedin.com` |
| Note | account restricted, photo ID required |

### Trademarks

| | |
| --------:|:------- |
| Play | NA |
| Home | `https://www.uspto.gov` |
| Note | Government photo ID required |

### Patents

| | |
| --------:|:------- |
| Play | NA |
| Home | `https://www.uspto.gov` |
| Note | Government photo ID required |

### Quora

| | |
| --------:|:------- |
| Play | `id=com.quora.android` |
| Home | `https://www.quora.com` |
| Note | Does not connect over Tor |

### Google Cloud Console

| | |
| --------:|:------- |
| Play | `id=com.google.android.apps.cloudconsole` |
| Home | `https://datastudio.google.com` |
| Note | Does not connect over Tor |

### Microsoft Authenticator

| | |
| --------:|:------- |
| Play | `id=com.azure.authenticator` |
| Home | app only |
| Note | Does not connect over Tor |

### Facebook

| | |
| --------:|:------- |
| Play | `id=com.facebook.katana` |
| Home | `https://www.facebook.com` |
| Note | Not an anonymous service |

### Tik Tok

| | |
| --------:|:------- |
| Play | `id=com.zhiliaoapp.musically` |
| Home | `https://www.tiktok.com` |
| Note | Not an anonymous service |

