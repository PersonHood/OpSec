# OpSec

[top](#opsec) 
| [dev](#devices) 
| [priv](#privacy) 
| [serv](#services) 
| [search](#search) 
| [guide](#guides) 

Day-to-day use of modern interconnected devices reveal more about an individual than may be understood. 

Collecting, editing, and publishing operational security information will reduce the need to search for a needle in a haystack, and will provide a first step in minimizing unintentional information sharing.

- Overview
- Devices
   - Disposal
   - Advanced
- Privacy
   - Best Practices
   - Tor Orbot VPN
   - Tor Browser
- Services
   - VOIP
   - E-mail
   - Groups
   - Files
- Search
   - DuckDuckGo
   - Google
   - Wikipedia
   - Quora
- Guides
   - Wikipedia
   - NOLO Legal Press
   - NIH Med Line Plus

## Overview

This document indirectly asks questions that many do not know to ask. 

While all of the topics listed are covered a dozen times over in dozens of on-line locations, and more than one individual or organization has collected related information into a single repository, the manner of presentation and challenges in finding the information prevent the average device user from gaining practical knowledge.

Compounding the problem, service providers are lightly regulated with respect to data privacy and data security. The device user may minimize information sharing as a good defense and as a preventative strategy that any individual may achieve at no financial cost.

## Devices

[top](#opsec) 
| [dev](#devices) 
| [priv](#privacy) 
| [serv](#services) 
| [search](#search) 
| [guide](#guides) 

Devices are pervasive.

Device owners voluntarily and freely give away personal information, visual evidence, and day-to-day location information. Some information leakage may be intentional. Often awareness of how much personal information is out there is only realized after a data breach is announced by an otherwise trusted service provider.

### Disposal 

This is what needs to be done when disposing of, or selling, a device:

- Do not smash the device or toss it in the water
- Learn how to remove the battery
- Learn how to remove the SIM
- Learn how to remove the external storage chip (SD card)

### Advanced

Skip this section unless you are more than a casual device user.

- Learn how to `root` the device
- Learn how to change the IMEI
- Be prepared to ‘factory reset’ the device
- Learn where app files are stored, delete ‘cache’ files

## Privacy

[top](#opsec) 
| [dev](#devices) 
| [priv](#privacy) 
| [serv](#services) 
| [search](#search) 
| [guide](#guides) 

### Best Practices

Privacy protection is a habit, an often repeated “To do...” list. A secure device is rendered insecure with bad operational security habits.

- Turn OFF the device when idle
- Turn OFF GPS and Tower location tracking
- Turn OFF Bluetooth
- Turn OFF sharing
- Turn OFF printing
- Turn ON airplane mode
- Download, install, and use an anonymous VPN
- Connect the device to public WiFi hot-spots in airplane mode
- Avoid at work and at home device usage
- Vary time of day of device usage, presuming device is off between uses
- Vary location of device usage, presuming device is off between uses
- Provide the minimum required data on-line
- Provide false or obscured data on-line when possible
- Learn how to clear ALL browser data on exit
- Learn how to clear the file open history in all apps
- Learn how to clear the device editor’s clipboard
- Learn how to clear all app’s custom dictionaries
- Before deleting, save the file with large `blank` content

### Tor Orbot

Never connect the device to the Internet through the device’s data plan. Connect through a public WiFi hot-spot in airplane mode using the anonymous Tor Orbot VPN.

- Download, install, and start the Tor Orbot app and tap ‘Start’
- Register other apps using Orbot ‘Settings’
- Test by launching a browser from Tor Orbot and link to ShowMyIP.com
- Tor Orbot offers a more polished user interface v Tor Browser’s built-in VPN
- Tor Orbot may launch any browser, or app, mimicking Tor Browser services
- Performance is not as good as a direct connection vs VPN
- Performance may be improved by selecting a country from the ‘Settings’

### Tor Browser

An anonymous browser and VPN

- Download, install, and start the Tor Browser app and tap ‘Connect’
- Test by linking to ShowMyIP.com
- The Tor Browser is a version of FireFox
- Performance is not as good as a direct connection vs VPN
- Tor Browser does not have a method for the user to select a country
- Tor Browser may work along side Tor Orbot

## Services

[top](#opsec) 
| [dev](#devices) 
| [priv](#privacy) 
| [serv](#services) 
| [search](#search) 
| [guide](#guides) 

There are millions of services & apps.

 [voip](#voip)
 | [e-mail](#e-mail)
 | [groups](#groups)
 | [files](#files)

Most apps either primarily or secondarily connect to the Internet. Few fail to connect to the internet, though some apps are functional in airplane mode with WiFi off. Primary connections include messaging and browsing. Secondary connections include ad delivery and spying. Most device users require a few common apps and default to pre-installed apps, with default ‘Settings’. Always thoroughly update app ‘Settings’.

This list includes anonymous free alternative services (non-app) and apps. The ‘Settings’ for each service or app should be thoroughly updated.

### VOIP

[serv](#services) 
| [voip](#voip)
| [e-mail](#e-mail)
| [groups](#groups)
| [files](#files)

Google Voice offers a free phone number supporting voice calls and texts over the Internet.

Unfortunately, the number is associated with the device’s phone number. Getting a burner SIM for the device lessens exposure but increases hassle and cost. Getting a separate burner phone reduces hassle but increases cost. Using a SIM-less burner phone reduces cost, and hassle, but eliminates non-VOIP voice calling and texting and entails WiFi dependency.

### E-Mail

[serv](#services) 
| [voip](#voip)
| [e-mail](#e-mail)
| [groups](#groups)
| [files](#files)

There are four types of anonymous e-mail:

- Web-mail enabling all functions, without phone verification, employing e-mail aliases to an existing address
- Web-mail enabling send and receive functions, without phone verification, for a new stand-alone address
- Web-mail enabling e-mail forwarding to a second e-mail address, with or without the ‘Send’ function
- Web-mail enabling only the receive function with security through obscurity, public drop-boxes, no login

Trade-offs... some services support file attachments, some do not, where links to anonymous file sharing sites are employed instead. Some require phone verification, but accept Google Voice. Some services are sandboxed within the domain. Some expire after a few days or delete e-mail after a few days. Some services rely on CAPTCHA during login. Some have apps that work over a VPN.

Advanced users may combine two or more services: double-forwarding e-mails or ‘sharing’ a drop-box where ‘drafts’ are composed but never sent, requiring regular visits to the site.

#### Hotmail

- https://outlook.live.com/owa
- `username@hotmail.com`
   - phone number not required
   - ‘recovery’ email required, HotMail accepted
   - Microsoft Outlook in the cloud
   - Has an App, Outlook

#### Protonmail

- https://protonmail.com
- https://account.proton.me/login
- `username@protonmail.com`  
   - Has an App

#### Zoho

- https://www.zoho.com
- `username@zohomail.eu`
   - acct: 00000000000
   - Has an App

#### Trashmail

- https://trashmail.com
- `username@my10minutemail.com`
   - `username@hotmail.com`
   - disposable e-mail account
   - forwards e-mail

#### Mailnesia

- https://mailnesia.com
- `username@mailnesia.com`
   - public e-mail account, drop-box
   - no login

#### Mailinator

- https://mailinator.com
- `username@mailinator.com`
   - public e-mail account, drop-box
   - no login

### Groups

[serv](#services) 
| [voip](#voip)
| [e-mail](#e-mail)
| [groups](#groups)
| [files](#files)

Groups, communities, and forums.

#### Reddit

- https://www.reddit.com/login
- https://www.reddit.com/u/username
     - `username@hotmail.com`
     - Has an App
- One of the oldest discussion groups, mostly for text postings
- Permanent links to categories (r/Topic) and users (u/username)
- Thousands of topics, communities
- No login to read, login to post

#### Tumblr

- https://tumblr.com/login
- https://username.tumblr.com/   
   - `username@hotmail.com`
   - Has an App
- Similar to Pinterest with text and image postings
- No login to read, login to post

#### Pinterest

- https://www.pinterest.com/login/
- https://www.pinterest.com/username
   - `username@hotmail.com`
   - Has an App
- Users create ‘Boards’ (topics) and post images and text

#### Twitter

- https://twitter.com/i/flow/login
- https://twitter.com/username
   - phone number required
   - Google Voice accepted
   - Has an App

### Files

[serv](#services) 
| [voip](#voip)
| [e-mail](#e-mail)
| [groups](#groups)
| [files](#files)

Attachments, drop-boxes, and directories 

Sharing files anonymously may occur directly or indirectly. Some web-mail services allow attachments. Some forums and discussion groups support posting images and videos.

Several providers operate like a drop-box. Old-school ftp servers mimic local file systems, supporting anonymous logins.

#### Github

- https://github.com/
- https://github.com/username/
   - `username@hotmail.com`
   - Has an App
- An old school coder’s website used to manage application development
- Incidentally also a file sharing service with version control baked in
- Supports the ‘Markdown’ text formatting syntax, and HTML
- Any file type may be uploaded
- Permanent links per file, per repository (project), and per user
- Avoid uploading files over Tor. Copy/Paste text into text boxes.

#### Pastebin

- https://pastebin.com
- https://pastebin.com/u/username
   - `username@hotmail.com`
- One of the oldest drop-box services, mostly for text files
- No login. The home page displays an input box and ‘Paste’ button
- System generated permanent links per file
- Permanent link per registered user
- Avoid uploading files over Tor. Copy/Paste text into text boxes.

## Search

[top](#opsec) 
| [dev](#devices) 
| [priv](#privacy) 
| [serv](#services) 
| [search](#search) 
| [guide](#guides) 

### DuckDuckGo

- https://www.duckduckgo.com
- Comparable to Google search
- No tracking or data retention
- Has an ‘onion’ web address, through Tor
   - Search ‘duckduckgo onion’ to get the address

### Google

- https://www.google.com
- Google search over Tor is anonymous
- Tracking or data retention to an anonymous IP exit node
- May have an ‘onion’ web address, through Tor
   - Search ‘google.onion’ to get the address

### Wikipedia

- https://en.wikipedia.com
- Technically not a search engine
- Millions of searchable articles cross referenced to other Articles
- Extensive footnotes to print and on-line resources
- Multiple languages
- No ads
- More effective than an open search of the Internet

### Quora

- https://www.quora.com
- Technically not a search engine
- Thousands of searchable questions answered by peers
- Multiple answers per question
- Related questions listed

## Guides

[top](#opsec) 
| [dev](#devices) 
| [priv](#privacy) 
| [serv](#services) 
| [search](#search) 
| [guide](#guides) 

### Wikipedia

- https://en.wikipedia.com
- Millions of searchable articles cross referenced to other articles
- Extensive footnotes to print and on-line resources
- Multiple languages
- No ads

### NOLO Press

- https://nolo.com
- Hundreds of searchable legal articles
- Dozens of books for sale

### Med Line Plus

- https://medlineplus.gov/
- World's largest medical library, on-line
- US National Library of Medicine (NLM)
- US National Institutes of Health (NIH).

