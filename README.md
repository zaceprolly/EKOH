<p align="center">
  <img src="icon.png" width="120" alt="EKOH icon">
</p>

<h1 align="center">EKOH</h1>

<p align="center">
  A voice assistant for Android that works completely offline.<br>
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

1. On your phone, tap **[Download EKOH.apk](https://github.com/zaceprolly/EKOH/releases/latest/download/EKOH.apk)** (about 80 MB).
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
| Fully offline: no internet, no tracking | Yes | Yes |
| Mute, speaker and hang up by voice during calls | Yes | No |
| WhatsApp group calls | Yes | No |
| Spotify plays by itself | Yes | Opens the search |
| Back, close app, recent apps, lock screen, screenshot | Yes | No |
| Connecting Bluetooth headphones by voice | Yes | No |
| Pausing listening during videos and games | Yes | No |
| Installs when Play Protect blocks accessibility apps | No | Yes |

If you ask EKOH Lite for something only the full version can do, it tells you.

## Updates

EKOH never goes online, so it can't check for updates itself. Two easy ways:

- **One tap:** in EKOH, open **Settings › Get the latest version**. It downloads the newest version; open the file to update.
  Your settings stay.
- **Automatic alerts:** install the free, open-source **[Obtainium](https://github.com/ImranR98/Obtainium)** app, then tap
  **[Add EKOH to Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://add/https://github.com/zaceprolly/EKOH)**
  (or EKOH › Settings › Automatic update alerts). Obtainium tells you when a new EKOH is out and installs it.
  If it asks which file to use, pick `EKOH.apk` (or `EKOH-Lite.apk` if you use Lite).

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
| “Open YouTube” · “Take a selfie” · “Navigate to India Gate” | Apps, camera, maps |
| “Text Mom saying I'm on my way” | Opens your messages with the text ready |
| “What time is it?” · “How much battery?” · “What is 25 times 4?” | Spoken answers |
| “EKOH, stop listening” | Stops background listening (hold the power button to turn it back on) |

You can also hold the power button to talk to EKOH.

## Privacy

| | |
|---|---|
| Internet access | **None.** EKOH doesn't have Android's internet permission, so Android blocks every connection it could make. |
| Wake word | A small model inside the app. |
| Speech to text | Android's on-device speech engine, which itself has no internet access. |
| Voice | Offline voices on your phone. |
| Account, ads, analytics | None. There is no server. |

The green dot at the top of your screen shows when EKOH is using the microphone, so you always know.
EKOH lets go of the microphone when the screen is off, while you watch videos or play games, and
whenever another app needs it.

**Scanned clean:** [VirusTotal report](https://www.virustotal.com/gui/file/edebc628f9b0ea54beae30ce22d54363628ed985fedc62b87c37a4c52fc550db): no antivirus engine flags EKOH.

If Play Protect warns you anyway: in India, Google automatically warns about every app downloaded from a
browser that uses accessibility or notification access (EKOH uses them to press call buttons and control
music). Tap **More details › Install anyway**.

**Check it yourself:** Settings › Apps › EKOH › Permissions has no network permission. Or watch your
phone's traffic with a no-root packet logger such as [PCAPdroid](https://github.com/emanuele-f/PCAPdroid):
EKOH never appears.

## Your accent

During setup, **Teach EKOH your voice** asks you to say the wake word three times so it learns how
you say it. EKOH can also use Android's **English (India)** speech pack for Indian accents and names.

## Good to know

- Works best on phones with Google's speech services (most Android phones).
- Phones without Android's own speech engine (many OnePlus, Motorola, Samsung and budget phones) are fine:
  EKOH switches to Google's offline speech or its own built-in offline model by itself.
- No weather or web answers: those need the internet, which EKOH deliberately doesn't have.

## Verify the download

Every release lists the SHA-256 checksum of `EKOH.apk` in its notes, and you can look it up on
[VirusTotal](https://www.virustotal.com/gui/file/edebc628f9b0ea54beae30ce22d54363628ed985fedc62b87c37a4c52fc550db).
