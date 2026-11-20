# Social Sticks Sim Controller — Windows downloads

This repository contains Windows installers and update packages only. Application source is maintained privately.

Install Setup once from [the latest release](https://github.com/kovaestudio/social-sticks-controller-releases/releases/latest) under the Windows account used for the simulator. Select the venue and simulator once in Bay settings. Existing installations receive future releases through Check for updates or the automatic idle 04:00–06:00 UK maintenance window. Pairing persists across updates.

## Staff timers

Select actual playing minutes: **55 minutes**, **115 minutes**, **175 minutes**, or custom minutes, then press Start session. The timer runs exactly the chosen minutes. Booking integration is deferred; sessions do not auto-start from schedules. Active staff timers block update installation.

## Adverts and warnings (0.3.5 onward)

Adverts come forward when triggered, then release topmost priority when staff switch away. The advert toolbar and tray can open the controller. Close, Escape and Dismiss hide adverts safely; an unusable browser/window is recreated when needed. The five-minute warning is a compact six-second corner notice that does not activate its window. Adverts appear at zero, not at the five-minute warning.

Windows regression tests verify repeated close/reopen with live JavaScript execution, actual native foreground/topmost handoff, compact non-activating warning dismissal, timer expiry after adverts were dismissed, and disposed-browser recovery. Installed startup and public update-feed acceptance also pass. GSPro-specific exclusive fullscreen behavior remains a venue check.

The PC must remain signed in and the controller running to receive updates. If an older controller paused after a disposed-object error, exit it from the tray and reopen once before checking for updates while idle. Installers currently are not Authenticode signed.
