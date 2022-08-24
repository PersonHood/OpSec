[  this is a comment. ]::

<link href="styles.css" rel="stylesheet"/>

> [Appendices](./Appendices-Top/OpSec-00-Appendices.md) | [WTF](./Appendices-Top/OpSec-01-WTF.md) | [Motivate](./Appendices-Top/OpSec-02-Motivate.md) | [Overview](./Appendices-Top/OpSec-03-Overview.md) 
> [Definitions](./Appendices-Top/OpSec-04-Definitions.md) | [Memes](./Appendices-Top/OpSec-05-Memes.md) | [Admin](./Appendices-Top/OpSec-06-Admin.md) 
> [TT4N](./Appendices-Top/OpSec-07-TT4N.md) | [Hosts](./Appendices-Top/OpSec-08-Hosts.md) | [Bibliography](./Appendices-Top/OpSec-99-Bibliography.md) 

# PreOpSec

*A semi-satiracle guide to secure device management.*

**tl;dr**

- Do **not** get one.

>[top](#preopsec) 
| [Before Device](#before-device) 
| [No Joke](#no-joke) 
| [Social](#social) 
| [Activation](#activation) 
| [System](#system) 
| [Configuration](#configuration) 
| [Traffic](#traffic) 
| [Habit](#habit) 
| [Usage](#usage) 
| [Data](#data) 
| [Info](#info) 
| [Subterfuge](#subterfuge) 
| [Word!](#word) 

## Contents

- Global Nav Bar
- Local Title
- Local Nav Bar
- *This*
- Intro
- Overview
- Before Device

## Intro

The *device* usage goal is to stay on-line and maintain **total anonymity**. 

Most *every* object today is a (interconnected) *device*.

**Total anonymity** is nearly **impossible**.

> Is a refrigerator, TV remote, and phone all treated equally? 

They should be.

- most device traffic is *incoming*
  - sensing
  - reading
  - monitoring
  - listening
  - spying
  - read-only devices are *great*
- many devices enable *outgoing* traffic
  - requesting - not bad...
  - reporting
  - informing
  - outing
  - write-capable devices are dangerous
- write-only storage is **awesome**

Devices should have owner-configurable *out-going* traffic filtering baked-in, publicized, with owner training *required*. No Apps required! 

> Limited `root`-level access permitted to device owners. 
>**Ref:** IP Tables
>>*No more* App-level owner tracking issues!

So, why are *experts* so focused on the *income* when the threat is *outgo*, and the **real** problem is *operator error*?

Each and every **NNN** elements, listed below, *continously* presents a point of *attack* compounded by *operator error*. 

>Problems not often solved by techology are accellerated by IT.

One *failure* at *any* time is fatal.

> And, a *pattern* of failures is a sign of total *idiocy* 
> - why even bother
> - IMHO
>    - Not that you are a *total* idiot 
>    - *intentionally*
>    - of course, IMHO

## Overview

Day-to-day use of modern interconnected devices reveals more about an individual than may be generally understood. 

> Who knows you snacked at 1:04AM? 
> Who knows you pooped at 1:15AM?
> - A hacker in Timbuctoo knows
> - Are you a *person of interest* in a warranted law efforcement investigation? 
>   - They too know
> - The kids don't know, unless they downloaded an App for that...
>   - Parental *controls* HaH! 
>   - Who are the best hackers? 
>      - 12 year-old kids in basements!
>      - before hormones take over
>   - "At least they aren't on drugs" 
>      - like I was at that age 
>      - besides *social media*
>    - who has time for *drugs*, anyways
>      - except, a sponsored *TikTack* 
>      - could go **viral**

This section indirectly asks questions that many do **not** know to ask, **nor** really want to know the answer.

This section starts *before* the device.

A few (dozen) *recommendations*:

> **NSFW**

## Before Device

- No Frills
- No Hand-holding
- No Lack of Answers Online

### No Joke

>Layer 0.1 BD

- No Devices
- No Battery in Devices
- No Devices you *can not* turn off
- No *Foreign* Chip Sets *(HaH!)*
- No *Foreign* Devices *(HaH!)*
  - Apple
  - Google
  - Samsung
  - Motorola
  - LG
  - Hitachi 
  - Hawaie **SP?**
- No Interconnected Devices
  - Vacuum Cleaner
  - Toilet Seat
  - Refrigerator
  - Wrist Watch
- No USB Cables
- No Unrooted Devices
- Make a bunch of copper *Faraday* cages
   - one per device
      - in your purse
      - in your pocket
      - in your glove compartment
      - in your night stand
      - in any desk draw
   - no joke

### Social

>Layer 0.2 BD

- No Device Purchases Mailed
- No In-person Device Registration
- No Device Seller's Friends & Family Plans
- No Recommending Device Sellers
- No Reviewing Device Sellers
- No Idiocy, "I've got a secret..."
- No Telling Anything to Anyone, Blabbing
- No "Secrets" when two+ people know
- No "But..."s, especially BFFs!
   - Gossip
   - Hater
   - Revenge
   - Rat
   - Informant

### Activation

>Layer 0.3 BD

- No Carrier SIM - IP Video, Voice, Texting, Apps
- No Burner SIM with Provider Accounts
- No Burner SIM with Affiliate Accounts
- No Single SIM - several
- No Money Back - 100% *Doomed* to fail
   - No last chance
   - Did you power up yet?
- No Static IMEI
- No Default Device Name
- No Carrier Friends & Family Plans
- No Recommending Carriers to Friends
- No Reviewing Carriers
- No Money Back - 100% *Doomed* to fail
   - power up yet?

### System

>Layer 0.1 AD

- No, no don't (*sigh*) - Power-up
- No Commercial OS Repos
   - ignoring *No USB cables*
- No OS Repos with Bloatware
- No Proprietary Apps 
   - *FOSS only*
- No *Trust me* Software

### Configuration

>Layer 1.0

- See 0.3 BD
- No Location Tracking, towers
- No Bluetooth - neighbors
- No GPS location
- No Shared Printers
- No e-Sharing Anything
- No texting a friend
- No selfies, **def** 
- No idiocy
   - like that needs to be said
   - still reading?

### Traffic

>Layer 1.1

- No udp
- No tcp
- No Standard tcp Ports
- No Unspoofed Incoming tcp Ports
   - `portspoof` project at GitHub
   - back-hack the assholes and *black hats*
- No Unfiltered Outgoing tcp Ports
   - IP Tables
- No udp
- No Unencrypted tcp Port Services
   - nn ssh
   - 80 https
   - nn sftp / ssh
   - nn telnet proxied
- No udp
- No bragging or publshing *white papers*

### Habit

>Layer 2.0

- No Home WiFi
- No Work WiFi
- No Unproxied Connections
- No Unencrypted VPNs
- No Paid Public VPNs
- No Dedicated Personal VPNs
- Not The Same Bat Time
- Not The Same Bat Place

### Usage 3.0

>Layer 0

- No Apps
- No Apps Unproxied
- No Websites
- No Websites Not Over Tor
- No Non-Onion Websites Over Tor
- No Lazy Tor / Orbot usage - New ID, Country

### Data

>Layer 3.1

- No *Remember me*
- No *Stay signed in*
- No Retained Form Fields
- No Uncleared Data on Exit
- No Uncleared Caches on Exit
- No Uncleared History on Exit
- No Saved Bookmarks
- No Saved Contacts
- No Saved Usage Activity
- No Saved Usage History
- No Shared Data
- No Saved Files
- No Unmasked Deleted Files

### Info

>Layer 4.0

- No giving out personal info
- No real info
- No repeating *fake* info
- No hinting, teasing
- No long speechs
- No Fessing up to info given
   - Fifth Amendment
   - Miranda Rights, sorta still
   - Do **not** run
      - see all of the above
   - Tell them **Q** sent you
      - **Not!**
- No self-defense, even if you are a lawyer
   
### Subterfuge

>Layer 9.9

- Do *everything* **wrong** 
   - with at *least* one Device
   - keep'in it real! clean!
   - keep moving, nothing to see here...
- "Who *is* that man behind the curtain?"
   - "His name is Zaphod, ruler... universe"
   - "You should ignore him, gets into trouble"
      - "If anyone asks, **42** wink |{ ;--}>"
- "Nice *goatie*"
   - "Thanks" 

## Word!

> *"Be safe out there"*

> - *High-five* to all my *homies*
>    - straight *outa* Brooklyn! 
>       - **Not**!

***

Copyleft 2022 - edit, excerpt, **re**publish
