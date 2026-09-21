<h1 align="center">Daniel Mattox</h1>

<p align="center"><strong>I build software, and I run everything I ship.</strong></p>

<p align="center">
  <a href="https://danielmattox.com"><img src="https://img.shields.io/badge/Hire%20me-danielmattox.com-2f4f7f?style=for-the-badge" alt="danielmattox.com" /></a>
  <a href="https://hyperspacemediagroup.com"><img src="https://img.shields.io/badge/Studio-Hyperspace%20Media%20Group-1b2a4a?style=for-the-badge" alt="Hyperspace Media Group" /></a>
  <a href="https://hyperspacemediagroup.com/status"><img src="https://img.shields.io/badge/Live-status%20board-2e7d5b?style=for-the-badge" alt="Status board" /></a>
  <a href="mailto:me@danielmattox.com"><img src="https://img.shields.io/badge/Email-me%40danielmattox.com-6b4e9e?style=for-the-badge" alt="Email" /></a>
</p>

Building software since 2001, starting with RPG Maker games and Geocities pages and never stopping. These days that means production apps with real users: native mobile builds, payment flows that take real money, and the servers underneath them, which I also operate.

Everything below is deployed and reachable today, or openly marked as not. Nothing here is aspirational.

## What I have shipped

These are products of my own studio, [Hyperspace Media Group](https://hyperspacemediagroup.com). I designed, built, shipped and still run every one of them.

| Product | What it is | Status |
| --- | --- | --- |
| **[Plyr2](https://plyr2.app)** | A dating app for gamers. Native iOS and Android through TestFlight, with game-title search, profile anthems, photo moderation, phone verification and over-the-air bundle updates. | Live |
| **[Journey](https://journey.hyperspacemediagroup.com)** | Booking and payments for one-person businesses. Real availability, card charged up front, automatic email and text confirmations, and an admin dashboard the owner controls. Running two live businesses. | Live |
| **[Moodiverse](https://apps.apple.com/us/app/moodiverse-digital-mood-ring/id6511244597)** | A digital mood ring. Entries grow into a 3D constellation you can rotate, with charts and a calendar. Private notes are encrypted under a key only the writer holds. Version 3 on the App Store, plus a [web version](https://web.moodiverse.app). | Live |
| **[Super Partner](https://superpartner.app)** | Route settlement for vending and amusement operators. Collections, meters, commission splits and inventory, worked out to the cent, with a full import and re-settlement of the legacy system's history so an operator can audit it before trusting it. | Live |
| **[STLibrarian](https://stlibrarian.com)** | A media library for 3D printing. Scans a folder of STLs, renders every model, groups the files that are one object, and measures what each will cost in resin. Nothing is moved, renamed or uploaded. | Live |
| **LOS** | A hex strategy game in Godot whose opponents are behaviour trees, so it plays itself. A headless harness has been running whole matches for weeks, and every balance number came out of those matches. | In development |

## What you can hire me for

Fixed prices, paid up front, on a real calendar slot. No quote to wait for and no discovery call first.

| What you get | Price | Book it |
| --- | --- | --- |
| **Architecture consulting, one hour.** One decision, settled today. Which database, whether this scales, why the bill is what it is. | $175 | [danielmattox.com](https://danielmattox.com) |
| **Architecture consulting, two hours.** A whole system: data model, hosting, auth, payments, background jobs, deployment. You leave with a written recommendation you can hand to whoever builds it. | $300 | [danielmattox.com](https://danielmattox.com) |
| **One-hour code debugging.** You screen-share, I read your actual code, and we fix the actual thing. | $75 | [learning.dantheman.fyi](https://learning.dantheman.fyi) |
| **Two-hour mentorship deep-dive.** A subject taken to the bottom, or a full honest review of code you have written. | $140 | [learning.dantheman.fyi](https://learning.dantheman.fyi) |
| **Journey, the booking system.** Hosted, self-hosted, or on revenue share, set up for your business. | from $499 | [See Journey](https://journey.hyperspacemediagroup.com) |

A mutual NDA is available at no charge during booking if your work needs one. Twenty-three verified client reviews are on [danielmattox.com](https://danielmattox.com), quoted word for word, typos intact.

## The part a GitHub profile cannot show you

Code is the easy half. The other half is whether the thing is still up on Sunday morning, and that half I do myself:

- **More than fifty containers** on hardware I own, serving **three dozen domains** behind a single nginx reverse proxy with automated TLS renewal.
- **Blue and green deploys with rollback**, so a release never takes a service down and a bad one is a switch away from undone.
- **A public [status board](https://hyperspacemediagroup.com/status)** that probes 7 production services over the open internet every 60 seconds and keeps 30 days of history. It is not hand-written, and I do not control what it says. That is the point of it.
- **The data layer and the chores**: MongoDB, MySQL, Redis, S3-compatible object storage, a self-hosted Forgejo, backups and cron.
- **App store reality**: iOS and Android submissions, store review, TestFlight, over-the-air bundle updates, push notifications, phone verification. The parts that only bite after release, which is where most of the actual work is.

When you ask me what happens in production, the answer comes from operating it rather than from reading about it.

## Stack

- **Frontend** &nbsp;React, React Native, Vite, Capacitor, PWAs, and plain HTML and CSS when that is the right answer
- **Backend** &nbsp;Node, Express, MongoDB, MySQL, Redis, S3-compatible storage
- **Payments and comms** &nbsp;Stripe, transactional email, SMS, calendar invites
- **Infrastructure** &nbsp;Linux, Docker, nginx, Let's Encrypt, blue/green deploys, backups, cron
- **Games** &nbsp;Godot, GDScript, Unity, C#
- **Also** &nbsp;Python, Electron, Arduino

## And I make games

Not the day job, and not a portfolio piece either. These are the ones that got finished, which for a side project is the whole difficulty.

- **[Where From](https://wherefrom.danielmattox.com)** is playable right now. A construction deck for Welcome To..., for phones: it replaces the 81 physical cards while you keep playing on the paper score sheets you already own. Installs to the home screen and deals a hand with no signal at all. React, Vite, PWA, Capacitor.
- **[RedWater](https://apps.apple.com/us/app/redwater/id6670454843)** is on the App Store. Small on purpose: the interesting part was never the mechanic, it was carrying a Unity build all the way to a public listing and keeping it there.
- **LOS** is the current one, and the most fun of them. See above.

## Why this profile looks quiet

Most of what I build is private or lives on my own Forgejo instance, so the repository list here is a poor sample of the work. The links above are the real portfolio: things with users, uptime and card payments behind them.

What is public here is worth a look, though:

- **[snes.css](https://github.com/dmattox10/snes.css)** is a retro CSS framework built on the aesthetics of 16-bit consoles. It dresses the kayak half of [dantheman.fyi](https://dantheman.fyi).
- **[stlibrarian-releases](https://github.com/dmattox10/stlibrarian-releases)** holds the public STLibrarian builds, which anybody can download and run today.
- **[SpriteSheet-Viewer](https://github.com/dmattox10/SpriteSheet-Viewer)**, **[TrafficLightStarter](https://github.com/dmattox10/TrafficLightStarter)** and the rest are the small tools and teaching pieces I keep in the open.

## Away from the keyboard

I guide kayak tours. Manatees at Crystal River, alligators and cypress on the Hillsborough, downtown Tampa from the water. One guide, one guest at a time, on rivers I have paddled for years. It is the best part of most weeks, and it is unrelated to the software in every way but one: the booking on [that site](https://adventure.dantheman.fyi) is Journey, which I wrote. Taking my own deposits through it is how it gets tested before anybody else runs a business on it.

<br/>

<p align="center">
  <em>If you want to check any of the above before you talk to me, start with the <a href="https://hyperspacemediagroup.com/status">status board</a>. It answers on its own.</em>
</p>
