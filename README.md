<div align="center">

<img src="screenshots/logo.png" alt="PixelyChat logo" width="120" height="120">

# PixelyChat

### Less juggling. More streaming.

PixelyChat pulls your Twitch, YouTube, Kick, and TikTok chat into one unified feed —
moderated, spoken aloud, translated on the fly, with on-screen alerts, Channel Point/TikTok gift rewards, stream and action widgets, themes, AI Chat, and Companion — an on-stream AI co-host.

Built by a streamer who'd rather be playing than managing five chat windows.

[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-6f42c1)](#-download)
[![Latest release](https://img.shields.io/github/v/release/pixieontv/pixelychat-releases?label=latest%20release&color=9146FF)](https://github.com/pixieontv/pixelychat-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/pixieontv/pixelychat-releases/total?color=00f2fe)](https://github.com/pixieontv/pixelychat-releases/releases)
[![Discord](https://img.shields.io/badge/Discord-Join%20the%20community-5865F2?logo=discord&logoColor=white)](https://discord.gg/NjC9cUgdfQ)
[![Free forever](https://img.shields.io/badge/price-free%20forever-brightgreen)](#-faq)

[Website](https://www.pixelychat.com) · [Download](#-download) · [What's new](https://www.pixelychat.com/news/) · [Features](#-features) · [Screenshots](#-screenshots) · [Manual](https://www.pixelychat.com/manual/) · [FAQ](#-faq) · [Support](#-support--community)

</div>

---

## About

PixelyChat is a desktop app for live streamers. It connects to **Twitch, YouTube, Kick, and TikTok** and merges all four chats into a single feed — readable in-app, moderated, read aloud with text-to-speech, shown as themed on-screen alerts and Channel Point/TikTok gift rewards, enhanced with stream widgets and action widgets, backed by a chat bot with commands and AI Chat, and extended by Companion, an optional on-stream AI co-host with a 2D avatar, voice, captions, and event reactions. Everything can be brought into OBS/Streamlabs through PixelyChat's local browser-source overlays, and PixelyChat works together with Elgato Stream Deck and Streamer.bot. The app is available in 11 languages.

It's made by **PixieOnTV**, a variety gaming streamer who got tired of multi-platform chat tools either missing what she needed or requiring a computer science degree to configure. She built it for her own stream first — then figured other streamers fighting the same chat chaos might want it too.

> This repository hosts **built releases only**. PixelyChat's source lives in a private repository while it's under active development; this page exists so anyone can download and follow along with new versions.

---

## 🖼 Screenshots

<table>
<tr>
<td width="50%" valign="top">
<img src="screenshots/quick-admin.webp" alt="PixelyChat dashboard with quick admin tools" width="100%">

**Dashboard & Quick Admin**<br>Viewer counts, activity and uptime for every platform. Delete messages, block users and edit your stream title without leaving the app.
</td>
<td width="50%" valign="top">
<img src="screenshots/accounts.webp" alt="Account connection screen" width="100%">

**Account Setup**<br>Log in to each platform once. No stream keys, no copying channel IDs.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="screenshots/dashboard.webp" alt="PixelyChat dashboard chat" width="100%">

**Unified Dashboard Chat**<br>All four platforms in one feed, with filters, sending to any platform and live activity counts.
</td>
<td width="50%" valign="top">
<img src="screenshots/translate.webp" alt="Translation settings" width="100%">

**Live Translation**<br>Chat in other languages is translated into yours automatically. No API key, no signup.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="screenshots/tts.webp" alt="Text-to-speech settings" width="100%">

**Text-to-Speech**<br>Chat read aloud in natural voices, with volume, speed, ignore lists and raid protection.
</td>
<td width="50%" valign="top">
<img src="screenshots/chat-styles.webp" alt="Chat Style Library with installable community chat styles" width="100%">

**Chat Styles & Style Library**<br>Built-in chat styles plus free community styles you install with one click.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="screenshots/overlays.webp" alt="Overlay URL generator" width="100%">

**One-Click OBS/Streamlabs Overlays**<br>Copy one URL into a Browser Source. Every style change updates live.
</td>
<td width="50%" valign="top">
<img src="screenshots/on-screen-chat.webp" alt="On-Screen Chat with Twitch, YouTube, Kick and TikTok messages on top of a game" width="100%">

**On-Screen Chat**<br>Chat and events on top of your game with one monitor. Only you see it, your viewers don't.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="screenshots/alerts.webp" alt="PixelyChat themed on-screen alerts setup" width="100%">

**On-Screen Alerts**<br>Follows, subs, gifts, raids and more, with themes, sounds and media on all four platforms.
</td>
<td width="50%" valign="top">
<img src="screenshots/rewards.webp" alt="PixelyChat Rewards tab with custom Channel Point and TikTok gift rewards" width="100%">

**Rewards for Channel Points & TikTok Gifts**<br>Turn redemptions and gifts into on-screen reactions with visuals, sounds and read-aloud text.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="screenshots/widgets.webp" alt="PixelyChat Widgets editor with stream goals, stats, activity feeds, announcements, and Now Playing" width="100%">

**Stream Widgets**<br>Goals, live stats, activity feeds, announcements and Now Playing, all in one editor.
</td>
<td width="50%" valign="top">
<img src="screenshots/visual-shoutout.webp" alt="A Visual Shoutout card with a clip playing on stream" width="100%">

**Visual Shoutout & Break Screens**<br>!so shows a card with a creator's clip. Starting Soon and Be Right Back play music and your own clips.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="screenshots/spin-wheel.webp" alt="PixelyChat Spin Wheel" width="100%">

**Spin Wheel**<br>Reusable wheels, spun from the Dashboard, a chat command, an alert or a reward.
</td>
<td width="50%" valign="top">
<img src="screenshots/stream-deck.webp" alt="Stream Deck keys for PixelyChat Action Widgets" width="100%">

**Stream Deck & Streamer.bot**<br>Start Action Widgets from Stream Deck keys, and run Streamer.bot actions on stream events.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="screenshots/bot-commands.webp" alt="PixelyChat chat bot custom command builder" width="100%">

**A Chat Bot That's Actually Fun**<br>!so, !8ball, !dadjoke and more out of the box, plus your own commands, cooldowns and greetings.
</td>
<td width="50%" valign="top">
<img src="screenshots/bot-ai-chat.webp" alt="PixelyChat AI chat bot settings" width="100%">

**AI Chat With Personality**<br>@mention your bot and it replies in character: Friendly, Funny, Sassy, Hype or your own.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="screenshots/companion.webp" alt="PixelyChat Companion editor with avatar, reactions, voice, and stream preview" width="100%">

**Companion, Your AI Co-Host**<br>A 2D avatar with voice and captions that reacts to your stream.
</td>
<td width="50%" valign="top">
<img src="screenshots/companion-interaction.webp" alt="Companion Interaction settings with talk hotkey and speech recognition" width="100%">

**Talk to Your Companion**<br>Press a hotkey, say something, and your Companion answers out loud. Speech recognition runs on your PC.
</td>
</tr>
</table>

---

## ✨ Features

- **Unified chat** — every message, from every platform, in a single feed
- **Four platforms at once** — Twitch, YouTube, Kick, and TikTok, all connected simultaneously
- **On-screen event alerts** — themed alerts for follows, subs, gifts, raids, and more, with customizable sounds and media
- **Custom rewards for Channel Points & TikTok gifts** — turn Twitch/Kick Channel Point redemptions and TikTok gifts into their own on-screen reactions, with visuals, sounds, and read-aloud text
- **Stream widgets** — add goals, live stats, activity feeds, announcements, and Now Playing to OBS/Streamlabs from one multistream-friendly editor
- **Action widgets** — run Countdown, Stopwatch, Game Queue, Hype, Spin Wheel, Visual Shoutout, Starting Soon, Be Right Back, and Media Player widgets with independent horizontal/vertical positioning
- **Visual Shoutout** — !so pops up a card with the creator's name, avatar, game, and one of their Twitch clips
- **Starting Soon & Be Right Back** — full-screen break screens with music and clips from your own Twitch channel
- **Media Player** — play your own sounds, images, and videos on stream from the Dashboard, a hotkey, a chat command, or a reward
- **Theme Library** — free themes from PixelyChat and the community restyle your alerts, rewards, widgets, and stream scenes in one click
- **Chat Style Library** — install free community chat styles for your chat overlay
- **On-Screen Chat** — chat and events on top of your game, visible only to you, so you can stream with one monitor
- **Stream Deck plugin** — start and stop Action Widgets from Elgato Stream Deck keys, with live status and timers on every key
- **Streamer.bot integration** — run your Streamer.bot actions on follows, subs, gifts, raids, and more from all four platforms
- **Spin Wheel** — create reusable templates with custom results and trigger them manually from the Dashboard or automatically from Bot Commands, Alerts, and Rewards
- **Chat bot with custom commands** — !so, !8ball, and more out of the box, plus your own commands, cooldowns, access levels, greetings, shoutouts, and event automation
- **AI Chat** — @mention the bot and it replies using Friendly, Funny, Sassy, Hype, or your own custom personality; hosted AI replies are included
- **Companion** — an optional on-stream AI co-host with a 2D avatar, voice, captions, and event reactions that shares the same personality as AI Chat; talk to it with a hotkey
- **Quick admin** — delete messages, block users, and update stream title & category for Twitch, Kick, and YouTube from the Dashboard
- **Live translation** — automatic, no API key required, original text preserved alongside it
- **Text-to-speech** — natural voices, per-user/bot ignore lists, spam/raid protection
- **Instant OBS & Streamlabs overlays** — chat overlay and dedicated alerts overlay, one URL each, live-updating styles
- **External emote support** — 7TV, BTTV, and FrankerFaceZ render alongside native emotes
- **11 languages** — English, Arabic, Chinese (Simplified and Traditional), French, German, Indonesian, Japanese, Korean, Portuguese (Brazil), and Spanish
- **Live viewer & message stats** — side-by-side per-platform activity on the Dashboard
- **Lightweight by design** — runs quietly in the background so your CPU/GPU stays free for your game and encoder
- **Local-first by design** — chat state, settings, and stored login tokens stay on your computer, and browser-source overlays are served locally; network-backed features only contact the relevant platform/provider when needed

---

## 📥 Download


**Windows, macOS & Linux:**

[![Windows](https://img.shields.io/badge/-Windows-0078D6?logo=windows&logoColor=white)](https://github.com/pixieontv/pixelychat-releases/releases/latest)
[![macOS](https://img.shields.io/badge/-macOS-000000?logo=apple&logoColor=white)](https://github.com/pixieontv/pixelychat-releases/releases/latest)
[![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)](https://github.com/pixieontv/pixelychat-releases/releases/latest)

**➡️ Grab the latest version from the [Releases page](https://github.com/pixieontv/pixelychat-releases/releases/latest).**

No payment, no account, no catch — every feature is free and stays free.

---

## ❓ FAQ

**Does PixelyChat support Kick chat?**
Yes — Kick is fully supported alongside Twitch, YouTube, and TikTok. Kick chat shows up in your unified feed, gets read aloud by TTS, triggers alerts, and appears in your overlay exactly like the other platforms.

**Is PixelyChat safe to use with my YouTube/Google account?**
Yes. PixelyChat uses the official Google OAuth 2.0 flow — you sign in through Google's own page, and PixelyChat never sees your password.

**Does PixelyChat collect or sell my data?**
PixelyChat does not sell your data. Core app data such as settings and stored login tokens stays on your computer. Features that use platform APIs, AI, translation, or other network services send only the data needed for that request to the relevant provider. To count how many people use PixelyChat, the app sends one anonymous ping a day with a random install id, your OS, the app version, and the app language — no names, accounts, or IP addresses are stored. See the [Privacy Policy](https://www.pixelychat.com/privacy) for details.

**Is it really free?**
Yes — every feature is free and stays free. [Donations](https://streamelements.com/pixieontv/tip) are appreciated but never required.

**How do you make money if it's free?**
This is a personal project, not a company. It's supported by [donations](https://streamelements.com/pixieontv/tip) and by [sponsors](https://www.pixelychat.com/sponsors.html) — companies that support development and are shown on the website. No ads in the app, no selling data, and sponsors have no say over the roadmap. Everything the app does today stays free.

**How do the OBS/Streamlabs overlays work?**
PixelyChat runs a small local web server on your own machine. Point a Browser Source at the URL it gives you for chat, alerts, widgets, or Companion — no separate cloud overlay service is required.

**Does it moderate my chat?**
Yes — PixelyChat includes built-in mod tools so you can delete messages and block or timeout users directly from the unified chat. You can still use your platform's native tools or bots like Nightbot/StreamElements/Streamer.bot alongside it if you prefer.

**Does it support on-screen alerts?**
Yes — themed event alerts for follows, subs, gifts, raids, and more, with customizable themes, sounds, and media. Add a second Browser Source for the alerts overlay (same setup flow as the chat overlay).

**Can I turn Channel Points or TikTok gifts into on-screen rewards?**
Yes — map a Twitch/Kick Channel Point redemption or a specific TikTok gift to its own custom on-screen reaction: a visual, a sound, and optional read-aloud text. Build from bundled presets or upload your own media, and set a point cost per platform.

**What is Companion?**
Companion is PixelyChat's optional on-stream AI co-host. It shares the personality selected for AI Chat and can react with a 2D avatar, voice, captions, and event-driven responses. Common reactions can use local response libraries so AI is reserved for moments that actually need generation.

**Can I read chat while playing with only one monitor?**
Yes — turn on On-Screen Chat under Setup → Overlays. Chat and events appear on top of your game, only you can see them, and your mouse and keyboard stay with the game. It works with windowed and borderless fullscreen games.

**Does PixelyChat work with Stream Deck and Streamer.bot?**
Yes. The PixelyChat plugin for Elgato Stream Deck starts and stops your Action Widgets with one key, and Streamer.bot can run your own actions when stream events happen in PixelyChat. Both are set up under Setup → Integrations.

**Can Spin Wheel be triggered automatically?**
Yes. Spin Wheel is an Action Widget, so you can play it manually from the Dashboard or trigger it from Bot Commands, Alerts, and Rewards. Templates let you keep different wheel setups for different parts of your stream.

---

## 💬 Support & Community

| | |
|---|---|
| 🐛 **Support / bug reports** | [support@pixelychat.com](mailto:support@pixelychat.com) |
| 💬 **Discord community** | [discord.gg/NjC9cUgdfQ](https://discord.gg/NjC9cUgdfQ) |
| 🔗 **Links / socials** | [beacons.ai/pixieontv](https://beacons.ai/pixieontv) |
| 💜 **Support development** | [Donate](https://streamelements.com/pixieontv/tip) |
| 🤝 **Become a sponsor** | [pixelychat.com/sponsors](https://www.pixelychat.com/sponsors.html) · [sponsors@pixelychat.com](mailto:sponsors@pixelychat.com) |

---

<div align="center">

Not affiliated with Twitch, YouTube, Kick, or TikTok.

</div>
