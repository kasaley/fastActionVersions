<p align="center">
  <img src="docs/logo.png" width="128" height="128" alt="FastAction icon">
</p>

<h1 align="center">FastAction</h1>

<p align="center">
  Your MacBook notch, turned into a quick-action panel.<br>
  Music, screenshots, clipboard, snippets and a translator — one hover away.
</p>

<p align="center">
  <a href="https://github.com/kasaley/fastActionVersions/releases/latest"><b>⬇︎ Download the latest version</b></a>
</p>

<p align="center">
  macOS 15 or later · Apple silicon and Intel · English, Русский, Español, Deutsch, Français
</p>

<p align="center"><b>English</b> · <a href="README.ru.md">Русский</a></p>

![The FastAction panel under the notch, playing music](docs/screenshots/en/music.png)

## Features

### A panel that lives in the notch

- Hover over the notch — or click it, if you prefer — and the panel slides out.
- Move the pointer away, click outside or press <kbd>Esc</kbd> to close it.
- It stays pinned to the notch while you swipe between desktops and never pops up in Mission Control.
- While music plays, the album art and a small equalizer sit right next to the closed notch.

### Now Playing

Control whatever is playing: Music, Spotify, a browser or any other player that reports to macOS.
Play, pause, skip and scrub through the track; click the app name to jump to the player.

### Screenshot shelf

![Screenshot shelf](docs/screenshots/en/shelf.png)

- Screenshots (<kbd>⌘⇧3</kbd>, <kbd>⌘⇧4</kbd>) and screen recordings (<kbd>⌘⇧5</kbd>) land on the shelf instead of your desktop.
- Search by name, date or **the text inside a screenshot** — recognized on your Mac.
- Drag a screenshot straight into any app; hover and click ✕ to move it to the Trash.

### Clipboard history

![Clipboard history](docs/screenshots/en/clipboard.png)

- Everything you copy — text, images and files — with search.
- Click an item to copy it again, or have it pasted into the active app right away.
- History is cleared automatically: every day, week or month, at the time you choose.
- Passwords from password managers are never saved.

### Snippets and frequently copied

![Snippets and frequently copied items](docs/screenshots/en/snippets.png)

Keep the texts you paste all the time — your email, phone number, links — one click away.
What you copy most often appears here on its own, and you can pin it as a snippet.

### Calendar

![Upcoming events](docs/screenshots/en/calendar.png)

- Your next week of meetings, each in the colour of its calendar.
- A meeting with a Zoom, Meet, Teams or Webex link gets a **Join** button.
- Click an event to read the details in the panel, or open it in Calendar from the row.
- A few minutes before a meeting the notch pops out with a reminder and a sound — you choose how early.

### Mail

![Unread mail](docs/screenshots/en/mail.png)

- Unread messages from Apple Mail, newest first.
- Click one to read it in the panel; hover a row to open it in Mail or mark it as read.
- New mail pops out of the notch, and the Mail tab keeps a dot until you look.

### Notifications in the notch

![A meeting reminder in the notch](docs/screenshots/en/alert.png)

The notch stretches into a small banner, plays a sound and gives the trackpad a gentle tap.
Hover it while it is up and the right tab opens straight away. Sound and trackpad feedback are yours to configure.

### On-device translator

![Translator](docs/screenshots/en/translate.png)

The language is detected as you type. Translation runs entirely on your Mac through Apple Translation:
no internet connection and no API keys.

### Keyboard shortcuts

![Shortcut hints on the tabs](docs/screenshots/en/shortcuts.png)

While the panel is open, <kbd>⌘1</kbd>…<kbd>⌘9</kbd> switch tabs — hold <kbd>⌘</kbd> to see the hints.
The panel's shortcuts take priority over the app underneath, and when it's closed they work in your apps as usual.
Any tab can get its own shortcut.

### Make it yours

- Reorder tabs, hide the ones you don't need, and choose which panel elements to show.
- Open the panel on hover or on click, with an optional delay.
- Five interface languages, switched instantly.
- Trackpad feedback and the alert sound can be changed or turned off.
- Open at login and automatic updates.

## Installation

1. Download `FastAction-<version>.dmg` from the [latest release](https://github.com/kasaley/fastActionVersions/releases/latest).
2. Open it and drag **FastAction** to **Applications**.
3. Launch FastAction from Applications. Its icon appears in the menu bar.

> [!NOTE]
> FastAction isn't notarized by Apple yet, so on the first launch macOS may say it can't verify the developer.
> Click **Done**, open **System Settings → Privacy & Security** and click **Open Anyway**. This is needed only once.

## Updates

FastAction checks for updates once a day and installs them in a couple of clicks.
To check right now, click the menu bar icon and choose **Check for Updates…**
Automatic checks and installs can be changed in **Settings → General → Updates**.

## Privacy

- Your clipboard history, snippets and screenshots stay on your Mac. There are no accounts and no analytics;
  the only network request is the daily update check to GitHub.
- Text recognition and translation run on-device.
- Saving screenshots to the shelf changes the macOS screenshot folder; turning it off restores the previous one.
- **Accessibility** access is optional and needed only for pasting a picked item right away.

## Requirements

- macOS 15 Sequoia or later.
- Designed for MacBooks with a notch. On other displays FastAction shows a small virtual notch at the top center.
- The translator uses Apple language packs, downloaded on first use.

## Troubleshooting

**The panel doesn't open.** Make sure FastAction is running (its icon is in the menu bar) and check
**Settings → General → Open panel**: it may be set to open on click. The panel doesn't open in Mission Control by design.

**Music doesn't show up.** The player has to report to the macOS Now Playing service — the same one that powers the media keys.

**Calendar or Mail asks for permission.** Calendar access is requested when you open the tab;
Mail needs Automation access in **System Settings → Privacy & Security → Automation**.
FastAction never launches Mail on its own.

**The translator asks to download languages.** Click **Download**, or add them in
**System Settings → General → Language & Region → Translation Languages**.

**Screenshots still go to the desktop.** Open the **Shelf** tab and click **Turn On**.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/kasaley/fastActionVersions/issues).

## Coming next

A plugin API and a plugin store, so anyone can add their own tabs to the notch.
