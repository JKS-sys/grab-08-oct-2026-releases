<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/icon-dark.png">
  <img src="assets/icon-light.png" alt="Grab icon" width="128" height="128">
</picture>

# Grab

**Download video, audio and subtitles — up to 24K, with the audio always merged.**
**Transcribe on your own machine. Ask AI about what was said.**

By **Jagadeesh Kumar S** · version **1.0.5** · [ipconfig.co.network](https://ipconfig.co.network)

<img src="assets/icon-light.png" alt="Light icon" width="64"> &nbsp; <img src="assets/icon-dark.png" alt="Dark icon" width="64">

<sub>The app icon, light (default) and dark.</sub>

</div>

## Download

| Platform | Download | Notes |
|---|---|---|
| 🍎 **macOS** Apple Silicon | [Grab_1.0.5_aarch64.dmg](https://github.com/JKS-sys/grab-08-oct-2026-releases/releases/latest/download/Grab_1.0.5_aarch64.dmg) | M1 and later |
| 🍎 **macOS** Intel | [Grab_1.0.5_x64.dmg](https://github.com/JKS-sys/grab-08-oct-2026-releases/releases/latest/download/Grab_1.0.5_x64.dmg) | macOS 10.15+ |
| 🪟 **Windows** x64 | [Grab_1.0.5_x64-setup.exe](https://github.com/JKS-sys/grab-08-oct-2026-releases/releases/latest/download/Grab_1.0.5_x64-setup.exe) | Windows 10 and 11 |
| 🪟 **Windows** ARM64 | [Grab_1.0.5_arm64-setup.exe](https://github.com/JKS-sys/grab-08-oct-2026-releases/releases/latest/download/Grab_1.0.5_arm64-setup.exe) | Snapdragon laptops |
| 🐧 **Linux** x64 | [.deb](https://github.com/JKS-sys/grab-08-oct-2026-releases/releases/latest/download/Grab_1.0.5_amd64.deb) · [.AppImage](https://github.com/JKS-sys/grab-08-oct-2026-releases/releases/latest/download/Grab_1.0.5_amd64.AppImage) | Ubuntu, Debian, Mint… |
| 🐧 **Linux** ARM64 | [.deb](https://github.com/JKS-sys/grab-08-oct-2026-releases/releases/latest/download/Grab_1.0.5_arm64.deb) | Raspberry Pi 5, ARM laptops |
| 💻 **ChromeOS** | the Linux **.deb** | Settings → Developers → Linux, then open the file |
| 😈 **FreeBSD** x64 | [tarball](https://github.com/JKS-sys/grab-08-oct-2026-releases/releases/latest/download/Grab_1.0.5_freebsd_amd64.tar.gz) | unpack, run `./grab` |

**macOS first launch:** drag Grab to Applications, then run once in Terminal:
```sh
xattr -cr /Applications/Grab.app
```
Grab updates itself after that, on every platform except FreeBSD.

## See it in motion

### 1. Start-up

<img src="assets/demo-start.webp" alt="Start-up — animated demo" width="900">

The logo draws itself inside two orbiting rings, sparks fly, the tagline types out and "By Jagadeesh Kumar S" springs in letter by letter.

### 2. Paste, pick 24K, download

<img src="assets/demo-download.webp" alt="Paste, pick 24K, download — animated demo" width="900">

Paste a link, choose a quality cap (here 24K), press Download. Jobs queue, progress with a glowing head, merge the audio and land with a green tick — then Open it or Show it in its folder.

### 3. Grab AI

<img src="assets/demo-ai.webp" alt="Grab AI — animated demo" width="900">

One click asks the free built-in AI; the answer streams in with coloured code. The Models tab finds every local AI on this computer and pulls new ones.

### 4. A tour in colour

<img src="assets/demo-tour.webp" alt="A tour in colour — animated demo" width="900">

Each section has its own colour and its own note. The theme changes with a circle that grows from the click. Press ? for every shortcut.

### 5. Owner Panel

<img src="assets/demo-owner.webp" alt="Owner Panel — animated demo" width="900">

Revenue at a glance, then mint 25 activation codes in one go and manage Razorpay subscriptions — in its own window, on the owner's Mac only.

## What it looks like

### Start-up

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/splash-2-dark.webp">
  <img src="assets/splash-2-light.webp" alt="Start-up" width="900">
</picture>

The logo draws itself, sparks fly, the tagline types out and "By Jagadeesh Kumar S" springs in letter by letter, with its own sound. Any key skips it.

### About Grab

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/about-dialog-dark.webp">
  <img src="assets/about-dialog-light.webp" alt="About Grab" width="900">
</picture>

From the menu bar on macOS (Grab → About Grab): the app, its version and its creator, Jagadeesh Kumar S. Every action also has a menu item with its shortcut.

### Downloads

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/downloads-dark.webp">
  <img src="assets/downloads-light.webp" alt="Downloads" width="900">
</picture>

Paste one link or a hundred. Pick the format and a quality cap from 480p to 24K; the audio is always merged in. Live jobs show speed, time left and a dancing equaliser.

### Subtitles only

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/subtitles-dark.webp">
  <img src="assets/subtitles-light.webp" alt="Subtitles only" width="900">
</picture>

Every subtitle language a video has: the creator's own, auto-generated and auto-translated, each labelled. Tick the ones you want and get just those files as SRT, VTT or ASS.

### Open what you downloaded

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/finished-dark.webp">
  <img src="assets/finished-light.webp" alt="Open what you downloaded" width="900">
</picture>

Every finished download has Open and Show in folder, the full path, a filter, search, Copy link and Retry failed. Drop links anywhere on the window to queue them; ⌘O opens the download folder.

### More options

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/options-dark.webp">
  <img src="assets/options-light.webp" alt="More options" width="900">
</picture>

Codec, audio bitrate, clip a section, playlist ranges, one file per chapter, skip what you already have, size limits, cookies from your browser, and a dry run of the exact command.

### Grab AI (⌘J)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/ai-chat-dark.webp">
  <img src="assets/ai-chat-light.webp" alt="Grab AI (⌘J)" width="900">
</picture>

Free built-in AI that knows what is in your queue. Also GitHub Copilot, GitHub Models, every local model and any online provider. Replies stream, code is coloured.

### Every local AI

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/ai-models-dark.webp">
  <img src="assets/ai-models-light.webp" alt="Every local AI" width="900">
</picture>

Ollama, LM Studio, Jan, llama.cpp, GPT4All, KoboldCpp, vLLM, Msty and AnythingLLM are found by themselves. Start Ollama and pull a model with one click.

### Library

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/library-dark.webp">
  <img src="assets/library-light.webp" alt="Library" width="900">
</picture>

Every video you downloaded, each with Open and Show in folder, its file type in colour, transcribed on your own machine with whisper.cpp, searchable by what was said. Summaries, chapters and quotes with AI.

### Subscriptions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/subs-dark.webp">
  <img src="assets/subs-light.webp" alt="Subscriptions" width="900">
</picture>

Follow channels and feeds; new uploads queue themselves with the format you chose for that feed.

### Settings

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/settings-formats-dark.webp">
  <img src="assets/settings-formats-light.webp" alt="Settings" width="900">
</picture>

Every option in plain words, each field in its own colour, and the yt-dlp command shown exactly as Grab will run it.

### Sound

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/settings-sound-dark.webp">
  <img src="assets/settings-sound-light.webp" alt="Sound" width="900">
</picture>

Every sound is synthesised as it plays, in ten packs, with no audio files in the app. Each section has its own note.

### Privacy and permissions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/settings-privacy-dark.webp">
  <img src="assets/settings-privacy-light.webp" alt="Privacy and permissions" width="900">
</picture>

Every permission and choice Grab asks about, in one place, remembered once answered. Crash reports kept on this computer: view, add, edit, delete, send, export as .md or .txt.

### After a crash

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/crash-review-dark.webp">
  <img src="assets/crash-review-light.webp" alt="After a crash" width="900">
</picture>

Grab shows what happened and asks once: Send, Always send, Not now or Never ask. Your home folder is replaced with ~ before anything leaves the computer.

### Shortcuts

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/shortcuts-dark.webp">
  <img src="assets/shortcuts-light.webp" alt="Shortcuts" width="900">
</picture>

Press ? anywhere for every keyboard shortcut, each in its own colour.

### Grab Pro

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/plan-dark.webp">
  <img src="assets/plan-light.webp" alt="Grab Pro" width="900">
</picture>

₹20 a month or ₹220 a year through Razorpay: UPI, cards, net banking. Grab unlocks itself the moment payment clears. Activation and lifetime codes work too.

### Crash reports in the Owner Panel

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/owner-crashes-dark.webp">
  <img src="assets/owner-crashes-light.webp" alt="Crash reports in the Owner Panel" width="900">
</picture>

Every report users chose to send: read, mark seen, fixed or ignored, add notes, create, delete one, many or all, and export as Markdown or text.

### Owner Panel

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/owner-overview-dark.webp">
  <img src="assets/owner-overview-light.webp" alt="Owner Panel" width="900">
</picture>

On the owner's Mac only, in its own window: revenue, codes (mint, revoke, restore, unbind) and Razorpay subscriptions (pause, resume, cancel, invoices).

## Free and Pro

Free Grab downloads, saves subtitles, transcribes locally and includes the free built-in AI, up to 10 downloads a day.
**Grab Pro** is ₹20 a month or ₹220 a year (UPI, cards, net banking through Razorpay) and removes every limit.

## What Grab does not do

It does not break DRM. Encrypted streaming services — Prime Video, Netflix, Disney+ Hotstar and the like — are out of scope.
Cookies from your browser only reach what your own account can already watch.

---

<div align="center"><sub>Made by Jagadeesh Kumar S · <a href="mailto:JKS.sys@icloud.com">JKS.sys@icloud.com</a> · <a href="https://www.youtube.com/@JKS-sys">youtube.com/@JKS-sys</a></sub></div>
