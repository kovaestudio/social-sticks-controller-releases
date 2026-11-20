# Social Sticks Sim Controller — Windows downloads

This repository contains Windows installers and update packages only. Application source is maintained privately.

Download the Setup.exe from [the latest release](https://github.com/kovaestudio/social-sticks-controller-releases/releases/latest). Exit old portable controllers before installing. Install under the Windows account used for the simulator and pair the bay once.

Installed controllers download future releases automatically. They install between 04:00 and 06:00 UK time only when the local bay session is idle, the PC has had no input for ten minutes. The PC must be signed in, running and online to receive updates. Pairing persists across updates.

Windows acceptance tests have verified installation, stable sign-in startup, background access to the public update feed, and the updater applying/restarting a newer installed version with bay data preserved. Use 0.3.1 or newer; this corrects startup registration from 0.3.0. If 0.3.0 is already installed and running, Check for updates can apply the correction without reinstallation. First venue pilot testing remains separate from these isolated Windows tests. Installers currently are not Authenticode signed.

## Staff timers (0.3.3 onward)

Staff select actual playing minutes: **55 minutes**, **115 minutes**, **175 minutes**, or a custom number, then press **Start session**. The timer runs exactly the selected minutes. A warning appears with five minutes left; staff can add a full 15 minutes. Booking integration is deferred and sessions do not auto-start from schedules. Legacy cached bookings are inactive and do not block extensions or updates. Active staff timers still block update installation.
