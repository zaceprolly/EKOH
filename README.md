<p align="center">
  <img src="icon.png" width="120" alt="EKOH icon">
</p>

<h1 align="center">EKOH</h1>

<p align="center">
  A voice assistant for Android that works offline.<br>
  Say “EKOH”, then tell it what to do. Nothing you say ever leaves your phone.
</p>

<p align="center">
  <a href="https://github.com/zaceprolly/EKOH/releases/latest/download/EKOH.apk">
    <img src="https://img.shields.io/badge/Download-EKOH.apk-5B3FD1?style=for-the-badge" alt="Download EKOH.apk" height="48">
  </a>
</p>

<p align="center">
  Free. No account, no ads, no tracking. Android 10 or newer.
</p>

<p align="center">
  <b>Phone says “App blocked to protect your device”?</b> Download EKOH Lite instead:
</p>

<p align="center">
  <a href="https://github.com/zaceprolly/EKOH/releases/latest/download/EKOH-Lite.apk">
    <img src="https://img.shields.io/badge/Download-EKOH%20Lite.apk-0F7B6C?style=for-the-badge" alt="Download EKOH Lite.apk" height="48">
  </a>
</p>

<p align="center">
  <sub>Install one or the other, not both. <a href="#ekoh-lite-vs-ekoh">What's the difference?</a></sub>
</p>

<p align="center">
  <a href="https://www.virustotal.com/gui/file/edebc628f9b0ea54beae30ce22d54363628ed985fedc62b87c37a4c52fc550db"><img src="https://img.shields.io/badge/VirusTotal-no%20engine%20flags%20it-2E7D32?style=flat-square" alt="VirusTotal: no engine flags it"></a>
</p>

---

## Install in 3 steps

1. On your phone, tap **[Download EKOH.apk](https://github.com/zaceprolly/EKOH/releases/latest/download/EKOH.apk)** (about 140 MB).
2. Open the downloaded file. If Android asks, allow your browser to **install unknown apps**, then tap **Install**.
3. Open **EKOH**. The setup walks you through each permission and says why it's needed.

If Android shows **“Restricted setting”** when you turn on EKOH's accessibility service: open
**Settings › Apps › EKOH**, tap the three-dot menu, choose **Allow restricted settings**, then try again.
(Android does this for every app installed outside the Play Store.)

## EKOH Lite vs EKOH

In India, Google Play Protect blocks downloaded apps that use accessibility, which EKOH uses to press
buttons on the screen for you. If your phone shows **“App blocked to protect your device”**, install
**[EKOH Lite](https://github.com/zaceprolly/EKOH/releases/latest/download/EKOH-Lite.apk)** instead.
It has its own icon (with LITE under the mascot) and pops up over other apps the same way.
Install one or the other, not both.

| | EKOH | EKOH Lite |
|---|:---:|:---:|
| Wake word “EKOH” and the floating blob | Yes | Yes |
| Phone calls and WhatsApp calls | Yes | Yes |
| Timers, alarms and reminders | Yes | Yes |
| Opening apps, camera, maps and texts | Yes | Yes |
| Play, pause and next for music | Yes | Yes |
| Time, date, battery and sums, out loud | Yes | Yes |
| Offline, with EKOH's own built-in voice | Yes | Yes |
| Quick Access: your apps under EKOH from the power button | Yes | Yes |
| Several things in one command | Yes | Yes |
| Maths, simple to advanced, with the answer in a pop-up | Yes | Yes |
| Call it any name you like (“Jarvis”), and wake it with that name | Yes | Yes |
| Screenshots by voice | Yes | Yes (tap Start each time) |
| Google results in a pop-up, directions by voice | Yes | Yes |
| Automatic updates (the only use of the internet, can be off) | Yes | Yes |
| Reads Google's answer out loud, trip time, “Should I start the navigation?” | Yes | No |
| Answer, mute and hang up WhatsApp calls by voice | Yes | No |
| Split screen | Yes | No |
| Mute, speaker and hang up by voice during calls | Yes | No |
| WhatsApp group calls | Yes | No |
| Spotify plays by itself | Yes | Opens the search |
| Back, close app, recent apps, lock screen | Yes | No |
| Connecting Bluetooth headphones by voice | Yes | No |
| Pausing listening during videos and games | Yes | No |
| Installs when Play Protect blocks accessibility apps | No | Yes |

If you ask EKOH Lite for something only the full version can do, it tells you.

## Updates

EKOH updates itself. Once a day it asks GitHub whether there's a new version, downloads it and installs it.
Android asks you to confirm the first time. Every update must be signed with EKOH's own key, or EKOH
won't install it. Your settings stay.

This is the only thing EKOH uses the internet for. Switch it off in **Settings › Automatic updates** and
EKOH never goes online at all. **Settings › Check for updates now** checks straight away.

**Coming from 1.1.2 or older?** Install 1.2.0 once by hand from the download button above. Android switches
EKOH's accessibility service off when an update adds new permissions, as 1.2.0 does, so turn
**EKOH call controls** back on afterwards in phone **Settings › Accessibility**.

## What you can say

| Say | What happens |
|---|---|
| “Call Mom” · “Call Mom on speaker” | Phone call |
| “WhatsApp call Rahul” · “Video call Rahul” · “Group call” | WhatsApp calls |
| “Hang up” · “Mute” · “Speaker on” · “Answer” | Call controls |
| “Set a timer for 5 minutes” · “Wake me up at 6:30” | Timers and alarms |
| “Remind me to call Dad at 8” | Reminders |
| “Play Kanye West on Spotify” · “Play a playlist” · “Play my liked songs” | Music |
| “Pause” · “Next” · “Volume up” | Music controls |
| “Open YouTube” · “Open Spotify and play” · “Take a selfie” | Apps and camera |
| “Navigate to India Gate” · “Stop navigation” | Directions in Google Maps |
| “Search best phones under 20000” · “Tell me about Diwali” | Google results in a pop-up |
| “Split screen Spotify and YouTube” | Two apps side by side |
| “Text Mom saying I'm on my way” | Opens your messages with the text ready |
| “What time is it?” · “How much battery?” | Spoken answers |
| “What's 3 square plus 4 square?” · “15% of 2000” · “Solve 2x + 3 = 11” | Maths, answer in a pop-up |
| “Open Instagram and call Dad” · “Turn on the torch, then set a timer for 5 minutes” | Several things at once |
| “EKOH, stop listening” | Stops background listening (hold the power button to turn it back on) |

You can also hold the power button to talk to EKOH. Turn on **Quick Access** (end of setup, or Settings) and your
favourite apps appear in a bar under EKOH too: tap one to open it.

## Privacy

| | |
|---|---|
| Internet access | **Only for automatic updates**, and only while they're on. Nothing about you is sent: it's a plain download from GitHub. Turn updates off and EKOH never goes online. |
| Google search | Opens in your browser, the same as searching there yourself. You can switch it off. |
| Wake word | A small model inside the app. |
| Speech to text | Android's on-device speech engine. |
| Voice | EKOH's own voice, built into the app and made on your phone. |
| Account, ads, analytics | None. There is no server. |

The green dot at the top of your screen shows when EKOH is using the microphone, so you always know.
EKOH lets go of the microphone when the screen is off, while you watch videos or play games, and
whenever another app needs it.

**Scanned clean:** [VirusTotal report](https://www.virustotal.com/gui/file/edebc628f9b0ea54beae30ce22d54363628ed985fedc62b87c37a4c52fc550db): no antivirus engine flags EKOH.

If Play Protect warns you anyway: in India, Google automatically warns about every app downloaded from a
browser that uses accessibility or notification access (EKOH uses them to press call buttons and control
music). Tap **More details › Install anyway**.

**Check it yourself:** watch your phone's traffic with a no-root packet logger such as
[PCAPdroid](https://github.com/emanuele-f/PCAPdroid). With automatic updates off, EKOH never appears. With
them on, you'll only see api.github.com and github.com, once a day.

## Your accent

During setup, **Teach EKOH your voice** asks you to say the wake word three times so it learns how
you say it. EKOH can also use Android's **English (India)** speech pack for Indian accents and names.

## Good to know

- Works best on phones with Google's speech services (most Android phones).
- Phones without Android's own speech engine (many OnePlus, Motorola, Samsung and budget phones) are fine:
  EKOH switches to Google's offline speech or its own built-in offline model by itself.
- Web answers come from Google in your browser. The full EKOH reads them out; EKOH Lite shows them.
- “Stop navigation” needs notification access, which is optional. Everything else works without it.

## Verify the download

Every release lists the SHA-256 checksum of `EKOH.apk` in its notes, and you can look it up on
[VirusTotal](https://www.virustotal.com/gui/file/edebc628f9b0ea54beae30ce22d54363628ed985fedc62b87c37a4c52fc550db).
