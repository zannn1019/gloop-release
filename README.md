<div align="center">

<img src="images/icon.png" width="96" alt="Gloop's icon: a black pill with two glowing eyes">

# Gloop

**A little liquid creature that lives in the notch at the top of your Windows screen.**

Music, your calendar, notifications, clipboard history, meeting transcripts and an AI assistant,
one hover away, in a blob that wobbles, blinks and follows your cursor with its eyes.

[![Latest release](https://img.shields.io/github/v/release/zannn1019/gloop-release?label=download&color=4FB4FF)](https://github.com/zannn1019/gloop-release/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/zannn1019/gloop-release/total?color=8D92A0)](https://github.com/zannn1019/gloop-release/releases)
![Windows 10 and 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0B0C10)

<img src="images/tour.gif" width="700" alt="Gloop opening from the top of the screen and moving through its Music, Today, Clipboard and Meetings pages, then showing a meeting that's starting with a Join button">

### [⬇ Download Gloop for Windows](https://github.com/zannn1019/gloop-release/releases/latest)

</div>

---

## What it does

<table>
<tr>
<td width="50%" valign="top">

### 🎵 Music
What's playing in Spotify, YouTube, your browser or any player, with the cover, a progress bar
and controls. Gloop bounces to the beat and sings along with synced lyrics.

<img src="images/music.png" alt="The Music page: cover art, song title, progress bar and play controls">

</td>
<td width="50%" valign="top">

### 📅 Today
Your Google Calendar at a glance: a strip of the day, what's next, and **Join** for Meet, Zoom
and Teams calls. A heads-up pops out a few minutes before each one.

<img src="images/today.png" alt="The Today page: a timeline of the day and a list of events with Join buttons">

</td>
</tr>
<tr>
<td valign="top">

### 📋 Clipboard history
Everything you copy, searchable: text, links, colors, code, pictures and files. Pin the things
you paste every day. Opens with **Win + V**. Passwords from password managers are never kept.

<img src="images/clipboard.png" alt="The Clipboard page: pinned items and recent copies">

</td>
<td valign="top">

### 🎙️ Meeting transcripts
When a call starts, Gloop offers to write it down, with who said what. It runs on your PC (no
cloud needed), works with English and Indonesian, and saves to Word or text.

<img src="images/meetings.png" alt="A meeting transcript with colored speaker names and timestamps">

</td>
</tr>
<tr>
<td valign="top">

### 🔔 Notifications
Messages from WhatsApp, Teams, Discord, your browser and Gmail slide out of the notch, and
wait in the bell until you've seen them.

<img src="images/inbox.png" alt="The Notifications page with messages from Gmail and Discord">

</td>
<td valign="top">

### 💧 Water, Shelf and more
Water reminders, a shelf to drop files on and drag them out later, screenshots you can drag
straight into a chat, a control center, battery and earbuds pop-ups, and a cat when you dock
him on the taskbar.

<img src="images/water.png" alt="The Water page: a bottle and buttons to log a glass">

</td>
</tr>
</table>

### ✨ Ask Gloop
Double-click him (or press **Win + Space**) and ask anything. He can open apps, set timers, turn
on Do not disturb, control your music, read your recent notifications and look at your screen.
Works with Claude, Gemini, OpenAI or a model on your own PC.

<p align="center"><img src="images/ask.png" width="540" alt="Ask Gloop answering how long to boil an egg, with buttons to set a timer"></p>

### Pop-ups that stay out of your way

<p align="center">
<img src="images/calendar-join.png" width="560" alt="A meeting starting now, with Join and Join and transcribe buttons"><br>
<img src="images/notification.png" width="520" alt="A new Gmail message sliding out of the notch"><br>
<img src="images/recording.png" width="360" alt="A small recording pill with the time and Pause and Stop buttons">
</p>

---

## Install

1. **[Download `Gloop-win-Setup.exe`](https://github.com/zannn1019/gloop-release/releases/latest)** from the latest release.
2. Run it. Gloop installs just for you (no admin needed), appears at the top of your screen and
   starts with Windows from now on.
3. That's it. Gloop updates itself when a new version comes out.

> **"Windows protected your PC"?** Gloop isn't code-signed yet, so Windows SmartScreen may warn
> about it the first time. Click **More info › Run anyway**.

**Needs:** Windows 10 (version 2004 or later) or Windows 11, 64-bit. Nothing else to install.

---

## Getting started

| To… | Do this |
|---|---|
| Open him | Hover over or click the notch |
| Switch pages | Click the icons at the bottom, or scroll |
| Ask Gloop | Double-click him, or press **Win + Space** |
| Clipboard history | **Win + V** |
| Search apps | Tap the **Windows** key on its own (tap it twice for the normal Start menu) |
| Move him | Drag him anywhere: glue him to any edge, or leave him floating |
| Keep a file for later | Drop it on him (it goes on the Shelf) |
| Settings | Right-click him › **Settings**, or use the tray icon |

Don't need something? **Settings › Features** turns any part of Gloop off.

---

## Setting things up

<details>
<summary><b>Ask Gloop (the AI assistant)</b></summary>

<br>

Gloop uses your own AI account, so you choose the service and nothing is shared with anyone else.

1. Right-click Gloop › **Settings › Ask Gloop**.
2. Pick a service and paste its key:
   - **Gemini**: free key at [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
   - **Claude**: key at [console.anthropic.com](https://console.anthropic.com/)
   - **OpenAI**, or any OpenAI-compatible service (OpenRouter, Groq…): key from that service
   - **Ollama**: free and fully offline, using a model running on your own PC
3. Double-click Gloop and ask away.

Keys are stored encrypted for your Windows account.

</details>

<details>
<summary><b>Meeting transcripts</b></summary>

<br>

1. Right-click Gloop › **Settings › Meetings**.
2. Choose **On this PC** and download a speech model once (**Fast**, about 200 MB, or **Better**,
   about 400 MB, which handles Indonesian well). Or choose **Gemini** to use your Gemini key.
3. When Zoom, Teams, Meet or Discord starts a call, Gloop asks if you want a transcript. Nothing
   is recorded unless you say yes. Please let the people on the call know.

</details>

<details>
<summary><b>Gmail and Google Calendar</b></summary>

<br>

Google asks every app that reads your mail or calendar to have its own key, so for now you
create a free one yourself. It takes about 5 minutes, once:

1. Go to [console.cloud.google.com](https://console.cloud.google.com/) and create a project.
2. **APIs & Services › Library**: turn on **Gmail API** and **Google Calendar API**.
3. **OAuth consent screen**: choose **External**, fill in the app name, and add your own Google
   address under **Test users**.
4. **Credentials › Create credentials › OAuth client ID** › **Desktop app**, then **Download
   JSON**.
5. In Gloop: **Settings › Pop-ups › Gmail › Connect**, pick that file, and sign in. Then
   **Settings › Calendar › Connect** (or the Today tab).

Google will say the app isn't verified, because it's your own; click **Continue**. Gloop only
asks to *read* your mail and calendar, and you can remove its access any time at
[myaccount.google.com/permissions](https://myaccount.google.com/permissions).

</details>

---

## Privacy

- **Hidden from screenshots and screen sharing** by default, so Gloop never shows up in your
  calls or captures (Settings › Privacy).
- **Clipboard history stays in memory** and disappears when Gloop closes. Only text you pin is
  saved. Copies that apps mark as private (passwords, codes) are never kept.
- **Meeting audio and transcripts stay on your PC**, unless you choose Gemini to transcribe.
- **API keys are encrypted** for your Windows account.
- **No accounts, no tracking, no analytics.** Gloop only talks to the services you connect.

---

## Questions

<details>
<summary><b>Gloop disappeared when I opened a game or a video.</b></summary>
<br>
That's on purpose: he hides while something is fullscreen. Turn it off in Settings › General.
</details>

<details>
<summary><b>How do I get the normal Start menu back?</b></summary>
<br>
Tap the Windows key twice, or turn off <b>App launcher</b> in Settings › Features.
</details>

<details>
<summary><b>He moved and I want him back at the top.</b></summary>
<br>
Right-click him › <b>Move back to the top</b>.
</details>

<details>
<summary><b>How do I check for updates?</b></summary>
<br>
Gloop checks every few hours. To check now, click the version number at the bottom of Settings.
</details>

<details>
<summary><b>How do I uninstall it?</b></summary>
<br>
Windows Settings › Apps › Installed apps › <b>Gloop</b> › Uninstall.
</details>

---

<div align="center">

Found a bug or have an idea? [Open an issue](https://github.com/zannn1019/gloop-release/issues).

Made with care by [zannn1019](https://github.com/zannn1019).

</div>
