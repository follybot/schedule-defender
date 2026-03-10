# schedule-defender
Decline meetings, frustrate co-workers, and DEFEND YOUR SCHEDULE. A browser-based game disguised as a work calendar. Single HTML file, no dependencies.
# 📅 Schedule Defender

> *Your calendar is under attack. Protect your Focus Time.*

A browser-based tower defense game disguised as a Microsoft Outlook calendar. Enemy meetings invade your week — click to decline them before they fill your schedule and destroy your sanity. Survive Friday, or it's a Performance Review.

**Single HTML file. No install. No dependencies. Just open and play.**

---

## 🎮 Play It

> *(itch.io link coming soon)*

Or clone the repo and open `schedule-defenderv013.html` directly in any modern browser.

---

## How to Play

- **Click enemy meetings** to decline them before they lock into your calendar
- **Protect the green Focus Time blocks** — if they get overrun, it's game over
- **Catch floating powerup icons** drifting across the screen:
  - ⚡ **Lightning** — doubles your click damage for 8 seconds
  - ☕ **Coffee** — slows all incoming meetings
  - 💰 **Money Bag** — chain-explodes every meeting on the calendar
- **Survive Friday** to win the week. Miss it, and face the Performance Review.

---

## Features

- 🗓️ **Authentic calendar UI** — looks exactly like a work week in Outlook
- 🌊 **5-tier wave system** — meetings escalate from "Quick Sync" to "MANDATORY ALL-HANDS (ENTIRE COMPANY + VENDORS)"
- 😰 **Friday Heartbeat** — the screen pulses red as the final day ramps up, faster as your calendar fills
- 💥 **Combo counter** — rapid declines trigger escalating combo rewards
- 🔥 **Enemy wobble** — meetings shake when they're one click from being declined
- 💰 **Cha-ching Morale Boost** — cash register sound and chain explosion when you activate the money bag powerup
- 🏆 **Personal best tracking** — high score and win streak persist between sessions
- 🔊 **Procedural audio** — all sound effects generated via Web Audio API, no audio files required
- 📱 **Share your score** — post your declined meeting count to LinkedIn, X, or Facebook

---

## Meeting Roster (Enemies)

| Tier | Waves | Examples |
|------|-------|---------|
| 1 | 1–2 | Quick Sync, Touch Base, Weekly Recurring 1:1 |
| 2 | 3–4 | Just 15 Mins PLEASE, Sally's Baby Shower, Free Donuts - Conf. B |
| 3 | 5–6 | Mandatory Fun Day, Surprise Fire Drill, Yet Another Team Offsite |
| 4 | 7–8 | URGENT 1:1 w/ CEO, Update Your Resume, Emergency All-Hands |
| 5 | 9+  | FINAL WARNING, Everyone In Conf Room NOW, Mandatory Overtime - Wknd |

---

## Tech

- Vanilla JavaScript — no frameworks, no libraries, no build step
- Web Audio API for all sound effects
- CSS animations for all visual effects
- `localStorage` for persistent high score and win streak
- Single `.html` file — everything self-contained

---

## About

Built as a satirical side project about the universal experience of a calendar that is no longer yours.

---

*© follybot. All rights reserved.*
