[  this is a comment. ]::

<link href="styles.css" rel="stylesheet"></link>

### Appendices

> [Appendices](./Appendices-Top/OpSec-00-Appendices.md) | [WTF](./Appendices-Top/OpSec-01-WTF.md) | [Motivate](./Appendices-Top/OpSec-02-Motivate.md) | [Overview](./Appendices-Top/OpSec-03-Overview.md) 
> [Definitions](./Appendices-Top/OpSec-04-Definitions.md) | [Memes](./Appendices-Top/OpSec-05-Memes.md) | [Admin](./Appendices-Top/OpSec-06-Admin.md) | [TT4N](./Appendices-Top/OpSec-07-TT4N-v2.md) | [Bibliography](./Appendices-Top/OpSec-99-Bibliography.md) 

# OpSec

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

Operational Security

## Contents

**OpSec**

- Contents
- Intro
- Overview

**Devices**

- Purchase
- Disposal
- Advanced

**Privacy**

- Isolate
- Restrict
- Share
- Hide	

**Services**

- Proxy
- Core
- Message
- Storage
- Social
- E-mail
- IRC
- Funding
- Bitcoin
- Image
- Database
- Feed
- Geographic
- Other	

**Local**

- Connection
- Firewall
- Encryption
- Editor
- Files
- Hacker
- Terminal
- Anti-Virus
- Authentication
- Hash
- Compiler

**Domain**

**Search**

- Structured
- Unstructured	

**Library**

- Wikipedia
- NOLO Press
- Med Line Plus
- Linux Commands
- Git Commands
- Regex Commands

**Broken**

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

>`Favorite*Words*123*appname`

## Overview

Day-to-day use of modern interconnected devices reveal more about an individual than may be understood. When applied, this collection of operational security information will help reduce the need to search for a needle in a haystack, and will provide a first step in minimizing unintentional information sharing.

This document indirectly asks questions that many do not know to ask. This document starts with the device; covers best practices and service providers; and ends with readily available informational library.

# Devices

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

Devices are pervasive, 3+ per person…

Device owners voluntarily and freely give away personal information, visual evidence, and their day-to-day location. Some information sharing is intentional. However, just how much personal information there is only may be realized after a data breach is announced by an otherwise trusted service provider.

## Purchase

This list includes several inexpensive devices.
- (5G) Samsung Galaxy A32
- (4G) Motorola Moto E
- (4G) Motorola Moto G Fast
- (4G) Nokia 2.1

## Disposal

Do this when disposing or selling a device:
- Do not smash the device nor toss it in water
- Learn how to remove the battery
- Learn how to remove the SIM
- Learn about eSIM
- Learn how to remove the external storage (SD)

## Advanced

- Learn howcto change your device name
- Learn about access code phone numbers
- Learn how to `root` your device
  - Download the device’s root kit |
   - Recovery mode reboot your device |
   - … press volume down + power buttons |
   - Install your device’s root kit |
   - Reboot your device |
- Learn how to change the IMEI
   - Download the app and launch it |
- Learn how to backup data
- Learn how to factory reset the device
- Learn where app files are stored, delete caches
- Learn about Android “Dual” apps

# Privacy

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

Privacy protection is a habit, an often repeated To do... list. A secure device may be rendered insecure with bad operational security habits. Do good, be inconsistent.

## Isolate

- Turn OFF the device when idle
- Turn OFF location tracking (GPS, tower, etc.)
- Turn OFF Bluetooth
- Turn OFF sharing
- Turn OFF printing
- In app settings "Data Usage" disable “Background”
- In app settings "Battery" enable “Restrict”
- In app settings "Storage" clear “Cache”
- In “Accounts” manage/remove “Auto-sync” accounts

## Restrict

- Turn ON airplane mode
- Download, install, and use an anonymous VPN (Tor)
- Connect the device to public Wi-Fi
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
- Change device name in `system` settings
- Learn how to clear ALL browser data on exit
- Learn how to clear all apps’ file open history
- Learn how to clear all apps’ custom dictionaries
- Learn how to clear all editor’s clipboards
- Before deleting, save files with large `blank` content
- Leave ON airplane mode
- Keep me signed in... No
- Remember me… No
- Leave ON airplane mode

# Services

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

Note: Most service providers have both web and app interfaces. The listed Google Play Store links are abbreviated to `id=`.

This presumes the full URL includes:

>`https://play.google.com/store/apps/details?`

Whenever possible, 2 or more app/services are listed. Try out each and pick the one that fits best.

## Proxy

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

Unlike the rest of the services and apps listed, the first two provide a low-level anonymous connection to the Internet.

Tor and Orbot are transparent services that underlay other apps. Tor is a standalone combo that supports the Firefox browser, and Orbot anonymously redirects all registered apps' Internet traffic. In general, never connect the device to the Internet through the device’s data plan. Connect through public Wi-Fi, in airplane mode, using anonymous Tor and/or Orbot.

An added layer of anonymity may be achieved by employing`Onion`addresses in the Tor browser. An`Onion`address is like a standard URL (`https://sitename.com`) recognized by Tor and directed to otherwise hidden web sites.

### Tor

| | |
| ---:| --- |
| Play | `id=org.torproject.torbrowser` |
| Home | `https://www.torproject.com` |
| Notes | Tor combines a Firefox browser and VPN |
| | No registration nor username required |
| | Launch Tor and tap the Connect button |
| | The VPN hides your device IP and location |
| | Link to ShowMyIP.com to test |

### Orbot

| | |
| ---:| --- |
| Play | `id=org.torproject.android` |
| Home | `https://www.torproject.com` |
| Notes | Orbot combines an app launcher and VPN |
| | Orbot may run along-side Tor |
| | Set VPN mode ON |
| | Launch Orbot and tap the Start button |
| | You may register the Firefox browser app |

## Core

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

Most apps either primarily or secondarily connect to the Internet. Few fail to connect to the internet, though some apps are functional in airplane mode with Wi-Fi off. Primary connections include messaging and browsing. Secondary connections include ad delivery and spying. Most device users require a few common apps and they default to pre-installed apps, with default Settings. Always thoroughly update app Settings.

This list includes anonymous free alternative services and apps. The Settings for each service or app should be thoroughly updated. An e-mail address is nearly always required, on its own or to register under other providers. There are several free and anonymous e-mail providers, including Microsoft's HotMail (Outlook). You may choose to employ several e-mail providers or rely on one.

Several services require two-factor authentication. A few support e-mail and a few require text messaging or one-time-pads.

It is recommended that you have back-up providers, at least one, in case one service provider locks your account.

### Microsoft HotMail

| | |
| ---:| --- |
| Play | `id=com.microsoft.office.outlook` |
| Login | `https://outlook.live.com/owa` |
| User | `username@hotmail.com` |
| Auth | `Pass*Word...` |
| Recov | `username@yourmail.com` |
| Note | Outlook app connection fails over Tor |

### Protonmail

| | |
| ---:| --- |
| Play | `id=ch.protonmail.android` |
| Login | `https://account.proton.me/login` |
| User | `username@yourmail.com` |
| Auth | `Pass*Word...` |
| Recov | `username@hotmail.com` |
| Note	 | |

### Google Voice

| | |
| ---:| --- |
| Play | `id=com.google.android.apps.googlevoice` |
| Acct | `NUM-BERS` |

### TextPlus

| | |
| ---:| --- |
| Play | `id=com.gogii.textplus` |
| Acct | `NUM-BERS` |

Google Voice offers a free phone number, supporting voice calls and texts over the Internet.

For recovery, Google Voice is the most stable provider, though the service requires a link to an old number.

Getting a burner SIM / eSIM for your device lessens exposure but increases hassle and cost.

Getting a separate burner phone and/or SIM / eSIM reduces connections to your old number.

## Message

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

Messaging between individuals and groups is provided in multiple contexts either stand-alone or as part of a larger system (e.g., gaming also includes messaging).

### Telegram X

| | |
| ---:| --- |
| Play | `id=org.thunderdog.challegram` |
| Home | `https://t.me/username` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | Google Voice / { burner phone } |
| Note | Scheduled messages |

### Signal

| | |
| ---:| --- |
| Play | `id=org.thoughtcrime.securesms` |
| Home | app only |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | Google Voice / { burner phone } |
| Pin | `NUMBER` |

### Microsoft Skype

| | |
| ---:| --- |
| Play | `id=com.skype.raider` |
| Home | app only |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Acct | `NUMBER` |

### Facebook WhatsApp

| | |
| ---:| --- |
| Play | `id=com.whatsapp` |
| Home | app only |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |

## Storage

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

The largest service provides offer "Office Suites" where files may be stored. Standalone file storage provides some advantages regarding anonymity.

### GitHub

| | |
| ---:| --- |
| Play | `id=com.github.android` |
| Login | `https://github.com/login` |
| Home | `https://github.com/username` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov	 | |
| Note | The app does not support editing |

### Pastebin

| | |
| ---:| --- |
| Play | NA |
| Login | `https://pastebin.com/login` |
| Home | `https://pastebin.com/u/username` |
| User | `username@mailinator.com` |
| Auth | `Pass*Word...` |
| Recov	 | |

### GitLab

| | |
| ---:| --- |
| Play | web only |
| Login | `https://gitlab.com/users/sign_in` |
| Home | `https://gitlab.com/username` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | `https://mega.nz/HASH` |
| Note | |

### Bitbucket

| | |
| ---:| --- |
| Play | `id=com.github.android` |
| Login | `https://bitbucket.org` |
| Home | `https://bitbucket.org/username` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |

### Dropbox

| | |
| ---:| --- |
| Play | `id=com.dropbox.android` |
| Login | `https://www.Dropbox.com` |
| Home | `https://Dropbox.com/username` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |

### Mega

| | |
| ---:| --- |
| Play | `id=mega.privacy.android.app` |
| Login | `https://www.Mega.nz` |
| Home | `https://Mega.com/username` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | `https://mega.nz/HASH` |
| Note | Auto-loads DCIM files at setup, bad ! |

## Social

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

Social, groups, communities, and forums.

Ignoring the 500lb gorilla, these services offer a balance between functionality and anonymity.

### Reddit

| | |
| ---:| --- |
| Play | `id=com.reddit.frontpage` |
| Login | `https://www.reddit.com/login` |
| Home | `https://www.reddit.com/u/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### Tumblr

| | |
| ---:| --- |
| Play | `id=com.tumblr` |
| Login | `https://tumblr.com/login` |
| Home | `https://username.tumblr.com` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Scheduled posts |

### Twitter

| | |
| ---:| --- |
| Play | `id=com.twitter.android` |
| Login | `https://twitter.com/i/flow/login` |
| Home | `https://twitter.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | Google Voice / { burner phone } |
| Note | Scheduled tweets |

### Pinterest

| | |
| ---:| --- |
| Play | `id=com.pinterest` |
| Login | `https://www.pinterest.com/login` |
| Home | `https://www.pinterest.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### Instagram

| | |
| ---:| --- |
| Play | `id=com.instagram.android` |
| Login | `https://www.instagram.com/login` |
| Home | `https://www.instagram.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |
| Notes | Owned by Meta / Facebook |
| | Broadcasts to other services - best not to |

### Kik

| | |
| ---:| --- |
| Play | `id=kik.android` |
| Login | app only |
| Home | app only |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Kik QR code |

## E-mail

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

There are four types of anonymous e-mail:

- Services enabling send and receive functions, without phone verification, employing e-mail aliases to an old address
- Services enabling send and receive functions, without phone verification, for a new address
- Services enabling e-mail forwarding to an old address, with/without the Send function
- Services enabling only the receive function with security through obscurity, public drop-boxes, no login

Trade-offs: some services do not support file attachments, where links to anonymous file sharing sites may be employed.

### Tutanota

| | |
| ---:| --- |
| Play | `id=de.tutao.tutanota` |
| Login | `https://mail.tutanota.com/login` |
| User | `username@tutanota.com` |
| Auth | `Pass*Word...` |
| TOTP | `HASH` |
| Recov | `HASH` |

### Zoho

| | |
| ---:| --- |
| Play | `id=com.zoho.mail` |
| Login | `https://accounts.zoho.eu/signin` |
| User | `username@zohomail.eu` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Scheduled e-mails; Web desktop UX; OTP |

### Mailfence

| | |
| ---:| --- |
| Play	| web only |
| Login | `https://mailfence.com/login` |
| User | `username@mailfence.com` |
| Auth | `Pass*Word...` |
| Recov | `username@yourmaiL.com` |

### Trashmail

| | |
| ---:| --- |
| Play	| web only |
| Login | `https://trashmail.com/login` |
| User | `username@my10minutemail.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | { deleted after set time? } |

### Mailnesia

| | |
| ---:| --- |
| Play	| web only |
| Home | `https://mailnesia.com` |
| User | NA |
| Auth | NA |
| Note | public drop-box |

### Mailinator

| | |
| ---:| --- |
| Play	| web only |
| Login | 	NA |
| Home | `https://mailinator.com` |
| User | NA |
| Auth | NA |
| Recov | NA |
| Note | public drop-box |

## Funding

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

This is not an anonymous activity. However, as an anonymous user you may want to crypto-contribute.

### Patreon

| | |
| ---:| --- |
| Play | `id=com.patreon.android` |
| Login | `https://www.patreon.com/login` |
| Home | `https://www.patreon.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | Avoid app, low ratings |

### Kickstarter

| | |
| ---:| --- |
| Play | `id=com.kickstarter.kickstarter` |
| Login | `https://www.kickstarter.com/login` |
| Home | `https://www.kickstarter.com/profile?ref=` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### GoFundMe

| | |
| ---:| --- |
| Play | `id=com.gofundme.gofundme` |
| Login | `https://www.gofundme.com/sign-in` |
| Home | `https://www.gofundme.com/f/causename` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

## Bitcoin

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

### Binance

| | |
| ---:| --- |
| Play | `id=com.binance.dev`` |
| Login | `https://www.binance.us/en/login` |
| Home | NA |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### BitPay

| | |
| ---:| --- |
| Play | `id=com.bitpay.wallet`` |
| Login | `https://bitpay.com/dashboard/login` |
| Home | `https://www.bitpay.com/username |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### Coinbase

| | |
| ---:| --- |
| Play | `id=com.coinbase.android` |
| Login | `https://www.coinbase.com/sign-in` |
| Home | NA |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

## IRC

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

Internet Relay Chat was first introduced in 1988 and it still has a loyal following; a text-only “texting” service.

### AndroIRC

| | |
| ---:| --- |
| Play | `id=com.androirc` |
| Login | IRC only |
| Home | app only |
| Nick | `username` |
| Auth | `Pass*Word` |
| Recov | `username@yourmail.com` |
| Notes |  `irc.freenode.net |
| |  `irc.oftc.net` |
| | `/msg NickServ REGISTER Pass*Word... username@yourmail.com` |
| | `/msg NickServ IDENTIFY username Pass*Word` |
| Text | Google Voice / { burner phone } |

### CoreIRC

| | |
| ---:| --- |
| Play | `id=co.aureolin.coreirc.lite` |
| Login | IRC server only |
| Home | app only |
| Nick | `username` |
| Auth | `Pass*Word` |
| Recov | `username@yourmail.com` |
| Notes |  `irc.freenode.net |
| |  `irc.oftc.net` |
| | `/msg NickServ REGISTER Pass*Word... username@yourmail.com` |
| | `/msg NickServ IDENTIFY username Pass*Word` |

## Image

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

Image may be stored wherever other files are stored, however these sites cross-sell image products and services.

### Snapfish

| | |
| ---:| --- |
| Play | `id=com.snapfish.mobile` |
| Login | `https://www.snapfish.com/loginto` |
| Home | NA |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Text | Google Voice / { burner phone } |

### Imgur

| | |
| ---:| --- |
| Play | `id=com.imgur.mobile` |
| Login | `https://www.imgur.com/login` |
| Home | `https://imgur.com/user/username` |
| User | `@username` |
| Auth | `Pass*Word...` |
| Recov | `username@yourmaiL.com` |
| Text | Google Voice / { burner phone } |

## Database

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

Cloud database servers may be of use in application development. A few providers offer limited free accounts.

### MongoDB

| | |
| ---:| --- |
| Play | `id=in.nexzone.mongodb` |
| Login | `https://account.mongodb.com/account` |
| Home | `https://cloud.mongodb.com` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |

### Clever-Cloud

| | |
| ---:| --- |
| Play | `id=` |
| Login | `https://api.clever-cloud.com/v2/session/login` |
| Home | `https://console.clever-cloud.com` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | Google Voice / { burner phone } |

### IBM Cloud

| | |
| ---:| --- |
| Play | `id=` |
| Login | `https://cloud.ibm.com` |
| Home | |
| User | |
| Auth | |
| Recov | |

## Feed

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

Really Simple Syndication (RSS) feeds were released in 1999, 10 years after IRC; another text-only texting service.

### Aggregator

| | |
| ---:| --- |
| Play | `id=com.tughi.aggregator` |
| Login | `https://www.aggregator.com/login` |
| Home | `https://www.aggregator.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### Feedly

| | |
| ---:| --- |
| Play | `id=com.devhd.feedly` |
| Login | `https://www.feedly.com/login` |
| Home | `https://www.feedly.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

### FeedMe

| | |
| ---:| --- |
| Play | `id=com.seazon.feedme` |
| Login | `https://www.feedme.com/login` |
| Home | `https://www.feedne.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | |

## Geographic

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

Simple mapping plus application programmer interfaces, useful for application development.

### Google Earth

| | |
| ---:| --- |
| Play | `id=com.google.Earth` |
| Login | `` |
| Home | `` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | API? |

### QGIS

| | |
| ---:| --- |
| Play | `id=com.qgis` |
| Login | `` |
| Home | `` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | API? |

### ArcGIS Earth

| | |
| ---:| --- |
| Play | `id=com.esri.earth.phone` |
| Login | `` |
| Home | `` |
| User | `username@yourmaiL.com` |
| Auth | `Pass*Word...` |
| Recov | |
| Note | API? |

## Other

>[top](#services) | [proxy](#proxy) | [core](#core) | [msg](#message) | [save](#storage) | [soc](#social) | [mail](#e-mail) | [fund](#funding) |
| [coin](#bitcoin) | [irc](#irc) | [img](#image) | [data](#database) | [feed](#feed) | [geo](#geographic) | [other](#other) |

There are millions of other services available. These two didn’t fit in elsewhere and have some utility vs entertaining.

### Hootsuite

| | |
| ---:| --- |
| Play | `id=com.hootsuite.droid.full` |
| Login | `https://hootsuite.com/member/sso-complete` |
| Home | NA |
| User | `username` |
| Auth | `Pass*Word...` |
| Notes | Broadcast app manager app |
| | 30 day free trial |

### Wikipedia

| | |
| ---:| --- |
| Play | `id=org.wikipedia` |
| Login | `https://en.wikipedia.com/login` |
| Home | `https://en.m.wikipedia.org/wiki/User:username` |
| Recov | |
| Notes | Sign in as an`editor` |
| | Millions of searchable articles |

### WordPress

| -----:|:----- |
| Login | `https://www.wordpress.com/login` |
| Home | `https://www.wordpress.com/username` |
| User | `username` |
| Auth | `Pass*Word...` |
| Note | app **fails** to connect over Tor |

### MailChimp

| -----:|:----- |
| Login | `https://login.mailchimp.com/` |
| Home | `https://us17.admin.mailchimp.com/account/profile/` |
| User | `username` |
| Auth | `Pass*Word...` |
| Notes | Links to Twitter |
| | *Google Voice* |

# Local

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

Note: To access Device "Developer" mode - select Settings, System, Phone, 7x tap on build number.

It is recommended that you register all local apps with Orbot (VPN). Some apps may secretly call back to the mother ship.

## Connection

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

A few apps that give you access to connectivity info.

### NetX

| | |
| ---:| --- |
| Play | `id=com.tools.netgel.netx` |
| Note | Wi-Fi signal analysis and scanner |

### IP Tools

| | |
| ---:| --- |
| Play | `id=com.ddm.iptools` |
| Note | Wi-Fi signal analysis and scanner |

### Web Tools

| | |
| ---:| --- |
| Play | `id=com.ddm.iptools` |
| Note | Wi-Fi signal analysis and scanner |

### WiFiman

| | |
| ---:| --- |
| Play | `id=com.ubnt.usurvey` |
| Note | Wi-Fi signal analysis and scanner |

## Firewall

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

Without`root`firewall apps are limited to proxying.

### NoRoot Firewall

| | |
| ---:| --- |
| Play | `id=app.greyshirts.firewall` |
| Notes | IP Tables internet security, no `root`  |

### Dataguard Firewall

| | |
| ---:| --- |
| Play | `id=com.fulldive.extension.dataguard` |
| Note | IP Tables internet security, no `root`  |

## Encryption

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

Places a selected file in an encrypted folder (vault).

### File Locker

| | |
| ---:| --- |
| Play | `id=inno.filelocker` |
| Note | Encrypted vault |

### Files by Google

| | |
| ---:| --- |
| Play | `id=com.google.android.apps.nbu.files` |
| Note | Encrypted vault - Browse, Safe Folder, PIN |

## Authentication

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

### Authenticator

| | |
| ---:| --- |
| Play | `id=com.google.android.apps.authenticator2` |
| Note | one-time-pad support for other apps |

### Twilio Authy

| | |
| ---:| --- |
| Play | `id=com.authy.authy` |
| Note | cryptographic tools |

## Hash

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

### Hash Droid

| | |
| ---:| --- |
| Play | `id=com.hobbyone.hashdroid` |
| Note | cryptographic tools |

### Cryptography

| | |
| ---:| --- |
| Play | `id=com.nitramite.cryptography` |
| Note | cryptographic tools |

## Editor

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

A few apps that enable you to edit “doc” and “txt” files.

### Markor

| | |
| ---:| --- |
| Play | `id=net.gsantner.markor` |
| Note | Sophisticated code editor, regexp |

### Obsidian

| | |
| ---:| --- |
| Play | `id=md.obsidian` |
| Note | Sophisticated code editor, plugins |

### ACode

| | |
| ---:| --- |
| Play | `id=com.foxdebug.acodefree` |
| Note | Sophisticated code editor, GitHub link |

### - - - -

| | |
| ---:| --- |
| Play | `id=com.---- |
| Note | Sophisticated code editor |

## Terminal

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

Command-line Linux interface.

### Termux

| | |
| ---:| --- |
| Play | `id=com.termux` |
| Note | Linux shell, command-line access |

### Terminal Emulator

| | |
| ---:| --- |
| Play | `id=jackpal.androidterm` |
| Note | Linux shell, command-line access |

## Hacker

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

Two hacker-ish tools.

### Hacker’s Keyboard

| | |
| ---:| --- |
| Play | `id=org.pocketworkstation.pckeyboard` |
| Note | Alternative keyboard for coders |

### BusyBox
| | |
| ---:| --- |
| Play | 	NA |
| Note | Linux tools, shell, `root` required |

## Files

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

### File Converter

| | |
| ---:| --- |
| Play | `id=com.icecoldapps.fileconverter` |
| Note | Extensive list of file formats supported |

### X-plore

| | |
| ---:| --- |
| Play | `id=com.lonelycatgnames.xplore` |
| Note | Sophisticated file manager |

### Total Commander

| | |
| ---:| --- |
| Play | `id=com.ghisler.android.TotalCommander` |
| Note | Sophisticated file manager |

## Anti-virus

>[top](#local) | [conn](#connection) | [wall](#firewall) | [edit](#editor) | [files](#files) |
| [hack](#hacker) | [term](#terminal) | [virus](#anti-virus) | [code](#compiler) | [auth](#authentication) | [hash](#hash)

Don’t download unknown files from unknown sources.

### Avira Security

| | |
| ---:| --- |
| Play | `id=com.avira.android` |
| Note | Anti-virus app and scanner |

### AntiVirus Free

| | |
| ---:| --- |
| Play | `id=com.Anti-Virus-Free` |
| Note | Anti-virus app and scanner |

### AVG AntiVirus

| | |
| ---:| --- |
| Play | `id=com.antivirus` |
| Note | Established anti-virus app and scanner |

### Norton 360 AntiVirus

| | |
| ---:| --- |
| Play | `id=com.symantec.mobilesecurity` |
| Notes | Established anti-virus app and scanner |
| | Free **trial** |

### McAfee Security

| | |
| ---:| --- |
| Play | `id=com.wsandroid.suite` |
| Note | Established anti-virus app and scanner |
| | Free **trial** |

# Compiler

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

## OnePercent Java Compile

| | |
| ---:| --- |
| Play | `id=club.onepercent.java_compiler` |
| Note | Edit, Compile, Install APK |

## OnePercent PHP Compiler

| | |
| ---:| --- |
| Play | `id=club.onepercent.php_compiler` |
| Note | Edit, Compile, Install APK |

## QuarksBytes Java IDE

| | |
| ---:| --- |
| Play | `id=org.quarksjava.java_ide` |
| Note | Edit, Compile, Install APK |

## QuarksBytes PERL IDE

| | |
| ---:| --- |
| Play | `id=org.quarksperl.perl_ide` |
| Note | Edit, Compile, Install APK |

## Code Runner

| | |
| ---:| --- |
| Play | `id=yavuzomar.coderunner` |
| Note | Edit, Compile, Install APK |

## Code Assist

| | |
| ---:| --- |
| Play | `id=com.tyron.code` |
| Note | Edit, Compile, Install APK |

## Java Compiler

| | |
| ---:| --- |
| Play | `id=com.techbajao.javacompiler` |
| Note | Edit, Compile, Install APK |

# Domain

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

## NameCheap

| -----:|:----- |
| Login | `https://www.namecheap.com/myaccount/login` |
| Home | `https://www.namecheap.com` |
| User | `username` |
| Auth | `Pass*Word...` |
| Recov | `username@yourmail.com` |
| PIN | NUMBER |
| Note | **fails** to auth over Tor, use app |

## GoDaddy

| -----:|:----- |
| Login | `https://account.godaddy.com` |
| Home | `https://www.godaddy.com` |
| User | `username@yourmail.com` |
| Auth | `Pass*Word...` |
| Recov | NUMBER |
| Acct | NUMBER |
| Notes | **fails** to connect over Tor |
| | Login works with Chrome over Orbot |

## Domain.com

| -----:|:----- |
| Login | `https://www1.domain.com/secure/login.bml` |
| Home | `https://www.domain.com` |
| User | `username@yourmail.com` |
| Auth | `Pass*Word...` |
| Recov | Buy first, no acct |

# Search

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

## Unstructured

### DuckDuckGo

| | |
| ---:| --- |
| Play | `id=com.duckduckgo.mobile.android` |
| Home | ` https://www.duckduckgo.com` |
| Notes | Comparable to Google search |
| | No tracking or data retention |
| | Has an Onion web address, through Tor |
| | Search “duckduckgo Onion” for the URL |

### Google Search

| | |
| ---:| --- |
| Play | `com.google.android.googlequicksearchbox` |
| Home | ` https://www.google.com` |
| Notes | Google search over Tor is anonymous |
| | Tracking/data retention to anon. exit node |
| | May have Onion web address, through Tor |
| | Search “google Onion” to get the address |

### Microsoft Bing

| | |
| ---:| --- |
| Play | `id=com.microsoft.bing` |
| Home | ` https://www.bing.com` |
| Note | Bing search over Tor is anonymous |

### Yahoo Search

| | |
| ---:| --- |
| Play | `id=com.yahoo.mobile.client.android.search` |
| Home | ` https://search.yahoo.com` |
| Note | Yahoo! search over Tor is anonymous |

## Structured

### Wikipedia

| | |
| ---:| --- |
| Play | `id=org.wikipedia` |
| Home | ` https://en.wikipedia.com` |
| Notes | Technically not a search engine |
| | Millions of searchable articles |
| | Peer-to-peer cross referenced articles |
| | Extensive footnotes to print/on-line resources |
| | Multiple languages; no ads |
| | More effective than an open Internet search |

### Quora

| | |
| ---:| --- |
| Play | `id=com.quora.android` |
| Home | ` https://www.quora.com` |
| Notes | Technically not a search engine |
| | Thousands of searchable questions |
| | Peer-to-peer answered questions |
| | Multiple answers per question |
| | Related questions listed |

### Craigslist

| | |
| ---:| --- |
| Play | `id=org.craigslist.craigslistmobile` |
| Home | ` https://www.craigslist.org` |
| Notes | Peer-to-peer resource searches |

# Library

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

### Wikipedia

| | |
| ---:| --- |
| Play | `id=org.wikipedia` |
| Home | ` https://en.wikipedia.com` |
| Note | Millions of searchable articles |
| Notes | Cross referenced to other articles |
| | Extensive footnotes to print/on-line resources |
| | Multiple languages; no ads |
| | More effective than an open Internet search |

### NOLO Press

| | |
| ---:| --- |
| Play | web only |
| Home | ` https://nolo.com` |
| Notes | Hundreds of searchable legal articles |
| | Dozens of books for sale |

### Med Line Plus

| | |
| ---:| --- |
| Play | web only |
| Home | ` https://medlineplus.gov` |
| Notes | World's largest medical library, on-line |
| | US National Institutes of Health (NIH) |

### Linux Commands

| | |
| ---:| --- |
| Play | `id=linux.command` |
| Home | app only |
| Note | Comprehensive guide to Linux commands |

### Git Commands

| | |
| ---:| --- |
| Play | `id=com.shubham.gitcommands` |
| Home | app only |
| Note | Comprehensive guide to Git commands |

### Regex Commands

| | |
| ---:| --- |
| Play | `id=com.techpurush.regexcheatsheet` |
| Home | app only |
| Note | Comprehensive guide to regex |

### Java Keywords

| | |
| ---:| --- |
| Play | `id=com.` |
| Home | app only |
| Note | Comprehensive guide to Java programming |

# Broken

>[top](#appendices) | [devices](#devices) | [privacy](#privacy) | [services](#services) | [local](#local) | [compile](#compiler) 
>[domain](#domain) | [search](#search) | [library](#library) | [broken](#broken)

A growing list of apps that don’t work anonymously, but it would be nice if they did.

### Yahoo!

| | |
| ---:| --- |
| Play | `id=com.yahoo.mobile.client.android.mail` |
| Home | ` https://yahoo.com` |
| Text | Google Voice rejected |

### Flickr

| | |
| ---:| --- |
| Play | `id=com.flickr.android` |
| Home | ` https://www.flickr.com` |
| Note | login loop on app, Tor / CAPTCHA |

### LinkedIn

| | |
| ---:| --- |
| Play | `id=com.linkedin.android` |
| Home | ` https://www.linkedin.com` |
| Note | account restricted, photo ID required |

### Trademarks

| | |
| ---:| --- |
| Play	| web only |
| Home | ` https://www.uspto.gov` |
| Note | Government photo ID required |

### Patents

| | |
| ---:| --- |
| Play	| web only |
| Home | ` https://www.uspto.gov` |
| Note | Government photo ID required |

### Quora

| | |
| ---:| --- |
| Play | `id=com.quora.android` |
| Home | `https://www.quora.com` |
| Note | Does not connect over Tor |

### Google Cloud Console

| | |
| ---:| --- |
| Play | `id=com.google.android.apps.cloudconsole` |
| Home | `https://datastudio.google.com` |
| Note | Does not connect over Tor |

### Microsoft Authenticator

| | |
| ---:| --- |
| Play | `id=com.azure.authenticator` |
| Home | app only |
| Note | Does not connect over Tor |

### Facebook

| | |
| ---:| --- |
| Play | `id=com.facebook.katana` |
| Home | ` https://www.facebook.com` |
| Note | Not an anonymous service |

### TikTok

| | |
| ---:| --- |
| Play | `id=com.zhiliaoapp.musically` |
| Home | ` https://www.tiktok.com` |
| Note | Not an anonymous service |

