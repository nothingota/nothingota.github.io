<div align="center">

<img src="firmware.png" width="120" alt="Nothing Firmware logo" />

# Nothing Firmware

### Every Nothing OS & CMF update. Real-time. One tap away.

A community-built Android app that tracks the latest **Nothing OS** firmware, changelogs, build fingerprints and OTA packages for every Nothing and CMF phone, with instant alerts and a home screen widget.

<br>

<a href="https://play.google.com/store/apps/details?id=com.techiboy.nothingfirmware">
  <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" width="230" alt="Get it on Google Play" />
</a>

<br><br>

![Version](https://img.shields.io/badge/version-1.0.3-D71921?style=flat-square)
![Android](https://img.shields.io/badge/Android-14%2B-3DDC84?style=flat-square&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-2.x-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Material%203-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Not affiliated](https://img.shields.io/badge/Independent-Not%20affiliated%20with%20Nothing-000000?style=flat-square)

<br>

</div>

---

## 💡 Why this app?

Nothing rolls out OTAs in waves, and finding the **right build**, its **changelog** and the **full OTA package** usually means digging through forums and Telegram channels. **Nothing Firmware** puts all of it in one clean, Nothing-styled app, and pings you the moment a new build drops.

---

## ✨ Features

| | Feature | What it does |
|---|---|---|
| 🔔 | **Instant alerts** | Push notifications (via Firebase Cloud Messaging) the moment a new firmware or Nothing app update is published. Pick exactly which devices and apps you care about. |
| 📱 | **Your device, auto-detected** | The app recognises your phone, shows your installed build and highlights newer releases for *your* model. |
| 📝 | **Full changelogs** | Readable, card-style changelogs for every release: new features, bug fixes, security patch level and notes. |
| 📦 | **OTA package downloads** | Direct download of the official OTA package, with a built-in **installation guide** and a custom OTA folder picker. |
| 🧬 | **Build fingerprints** | Copy source and target fingerprints for every regional variant (Global, EEA, IND, JPN, TUR, Pro...). |
| 🛡️ | **Wrong-device warning** | Warns you before downloading a package that doesn't match your phone. |
| 🧩 | **Home screen widget** | Pin the latest builds to your home screen. Resizable, scrollable, and refreshes automatically. |
| 🧰 | **Nothing apps tracker** | Tracks updates for Nothing's own apps (Launcher, Weather, Gallery, Glyph Composer, Essential Space, Games, Widgets and more). |
| 🎨 | **Themes & looks** | Light / Dark / Auto, black & white filter, and multiple UI styles (e.g. *Firmware Classic*, card-style headings). |
| 🔊 | **Voice & sound alerts** | Optional firmware sound, custom alert tone with an audio trimmer, and spoken update titles in multiple voice styles. |
| 📳 | **Haptics** | Tactile feedback on taps and selections, toggleable. |
| 🔁 | **Auto-sync engine** | Pulls the latest manifest in the background, so the list is always current. |

---

## 📱 Supported Devices

| Device | Codename | OTA & Changelog |
|---|---|---|
| Nothing Phone (1) | `Spacewar` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-Spacewar"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| Nothing Phone (2) | `Pong` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-Pong"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| Nothing Phone (2a) | `Pacman` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-Pacman"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| Nothing Phone (2a) Plus | `PacmanPro` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-PacmanPro"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| Nothing Phone (3) | `Metroid` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-Metroid"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| Nothing Phone (3a) / (3a) Pro | `Asteroids` | <a href="https://github.com/nothingota/nothingota.github.io/releases?page=2#release-Asteroids"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| Nothing Phone (3a) Lite | `Galaxian` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-Galaxian"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| Nothing Phone (4a) | `Frogger` | <a href="https://github.com/nothingota/nothingota.github.io/releases?page=2#release-Frogger"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| Nothing Phone (4a) Pro | `FroggerPro` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-FroggerPro"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| Nothing Phone (4b) | `SuperContra` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-SuperContra"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| CMF Phone 1 | `Tetris` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-Tetris"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |
| CMF Phone 2 Pro | `Galaga` | <a href="https://github.com/nothingota/nothingota.github.io/releases#release-Galaga"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/ffffff"><img src="https://cdn.simpleicons.org/github/181717" width="18" alt="GitHub"></picture>&nbsp;Releases</a> |

> New devices are added to the feed as soon as Nothing releases an OTA for them.

---

## 🧰 Tracked Nothing Apps

Besides system firmware, the app also watches Nothing's own apps and alerts you when a new update lands.

| App | Package | Download |
|---|---|---|
| Nothing Launcher | `com.nothing.launcher` | <a href="https://play.google.com/store/apps/details?id=com.nothing.launcher"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Nothing Gallery | `com.nothing.gallery` | <a href="https://play.google.com/store/apps/details?id=com.nothing.gallery"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Nothing Weather | `com.nothing.weather` | <a href="https://play.google.com/store/apps/details?id=com.nothing.weather"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Nothing Community Widgets | `com.nothing.communitywidgets` | <a href="https://play.google.com/store/apps/details?id=com.nothing.communitywidgets"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Essential Space | `com.nothing.ntessentialspace` | <a href="https://play.google.com/store/apps/details?id=com.nothing.ntessentialspace"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Nothing Widgets | `com.nothing.hearthstone` | <a href="https://play.google.com/store/apps/details?id=com.nothing.hearthstone"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Nothing Wallpaper | `com.nothing.wallpaper` | <a href="https://play.google.com/store/apps/details?id=com.nothing.wallpaper"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Essential Apps | `com.nothing.essentialapps` | <a href="https://play.google.com/store/apps/details?id=com.nothing.essentialapps"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Games | `com.nothing.games` | <a href="https://play.google.com/store/apps/details?id=com.nothing.games"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Glyph Composer | `com.nothing.glyph.composer` | <a href="https://play.google.com/store/apps/details?id=com.nothing.glyph.composer"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Essential Search | `com.nothing.essential.search` | <a href="https://play.google.com/store/apps/details?id=com.nothing.essential.search"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Nothing Icon Pack | `com.nothing.icon` | <a href="https://play.google.com/store/apps/details?id=com.nothing.icon"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Nothing Account | `com.nothing.user.center` | <a href="https://play.google.com/store/apps/details?id=com.nothing.user.center"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |
| Nothing X | `com.nothing.smartcenter` | <a href="https://play.google.com/store/apps/details?id=com.nothing.smartcenter"><img src="https://cdn.simpleicons.org/googleplay/34A853" width="18" alt="Play Store">&nbsp;Play Store</a> |

---

## ⚙️ How it works

```
┌──────────────────────┐      ota.json / apps.json      ┌────────────────────┐
│  Firmware feed       │ ─────────────────────────────▶ │  Nothing Firmware  │
│  (GitHub Pages)      │                                │  Android app       │
└──────────────────────┘                                └─────────┬──────────┘
          ▲                                                       │
          │ new build detected                                    │ shows cards, changelog,
          │                                                       │ OTA download, widget
┌─────────┴────────────┐   FCM topics: all_otas / all_apps        │
│  Notification server │ ────────────────────────────────────────▶ 🔔 Instant alert
└──────────────────────┘
```

The app reads two JSON manifests hosted on GitHub Pages:

- `https://nothingota.github.io/Firmware/ota.json` → firmware releases per device codename
- `https://nothingota.github.io/Firmware/apps.json` → Nothing app updates

<details>
<summary><b>📄 Firmware entry format (click to expand)</b></summary>

```json
{
  "Metroid": [
    {
      "title": "Nothing Phone (3)",
      "version": "Nothing OS C5.0-260924-2115",
      "codename": "Metroid",
      "source_fingerprint": "Nothing/Metroid/Metroid:16/.../2608141733:user/release-keys",
      "fingerprint": "Nothing/Metroid/Metroid:17/.../2609242115:user/release-keys|Nothing/MetroidEEA/...",
      "ota_url": "https://android.googleapis.com/packages/ota-api/package/<hash>.zip",
      "changelog": "<h3>Nothing OS 5.0</h3> ...",
      "extracted_at": "2026-10-12 10:10:33 UTC"
    }
  ]
}
```

| Field | Meaning |
|---|---|
| `version` | Nothing OS build string |
| `source_fingerprint` | Build you must be on to apply this (incremental) OTA |
| `fingerprint` | Resulting build fingerprint(s), pipe-separated per region |
| `ota_url` | Official OTA package link |
| `changelog` | Official changelog (HTML) |
| `extracted_at` | When the build was detected |

</details>

---

## 🧱 Tech stack

- **Language:** Kotlin
- **UI:** Jetpack Compose + Material 3 (custom Nothing-style dot-matrix design)
- **Networking:** OkHttp + Kotlin Coroutines
- **Images:** Coil
- **Push:** Firebase Cloud Messaging (topic-based)
- **Widget:** `AppWidgetProvider` + `RemoteViewsService` (scrollable list)
- **Min SDK:** 34 (Android 14) · **Target SDK:** 37

---

## 🚀 Installing an OTA the right way

1. Tap your device in the app and open the latest build.
2. Check that **Installed Build** matches the package's *source fingerprint*.
3. Tap **Download Package**.
4. Follow the in-app **Installation Guide** (Settings → System → System Update → local install / OTA folder).
5. Reboot when prompted.

> ⚠️ Always **back up your data** before flashing a major update (e.g. Nothing OS 4 → 5). You flash packages at your own risk.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a branch: `git checkout -b feature/awesome-idea`
3. Commit: `git commit -m "Add awesome idea"`
4. Push and open a **Pull Request**

Found a bug or a wrong changelog? Open an [issue](../../issues) or use **Settings → Feedback & Bugs** inside the app.

---

<div align="center">

**Unofficial · Independent project**

Not affiliated with or endorsed by Nothing Technology Limited.
*Nothing*, *CMF*, *Glyph* and related names and logos are trademarks of their respective owners.
Firmware packages are served from official Nothing/Google OTA servers. The app only links to them.

<br>

Made with ❤️ by **TechiBoy Studios**

</div>
