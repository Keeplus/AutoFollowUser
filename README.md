# 👁️ AutoFollowUser — BetterDiscord

```
 █████╗ ██╗   ██╗████████╗ ██████╗     ███████╗ ██████╗ ██╗     ██╗      ██████╗ ██╗    ██╗
██╔══██╗██║   ██║╚══██╔══╝██╔═══██╗    ██╔════╝██╔═══██╗██║     ██║     ██╔═══██╗██║    ██║
███████║██║   ██║   ██║   ██║   ██║    █████╗  ██║   ██║██║     ██║     ██║   ██║██║ █╗ ██║
██╔══██║██║   ██║   ██║   ██║   ██║    ██╔══╝  ██║   ██║██║     ██║     ██║   ██║██║███╗██║
██║  ██║╚██████╔╝   ██║   ╚██████╔╝    ██║     ╚██████╔╝███████╗███████╗╚██████╔╝╚███╔███╔╝
╚═╝  ╚═╝ ╚═════╝    ╚═╝    ╚═════╝     ╚═╝      ╚═════╝ ╚══════╝╚══════╝ ╚═════╝  ╚══╝╚══╝
```

> **Automatically follow your friends into voice channels — Fixed & Updated for 2026**

---

## ✦ What is it ?

**AutoFollowUser** is a [BetterDiscord](https://betterdiscord.app/) plugin that lets you **automatically follow a user** whenever they switch voice channels — on the same server or any other.

No more manually joining every time. Right-click → Follow. Done.

---

## ⚡ Features

- 🎯 **One-click follow** — right-click any user and hit `Follow this user ✅`
- 🔁 **Auto-switch** — instantly follows the user across any voice channel
- 🌐 **Cross-server support** — works even when the user moves to a different server
- 🔕 **Toggle on/off** — right-click again to unfollow at any time
- 🔔 **Live notifications** — toast alerts on every channel switch
- 🛠️ **No module conflicts** — fully compatible with custom Discord modules (stereo patch, etc.)
- 🔄 **Auto-update** — always stays up to date via GitHub

---

## 📦 Installation

1. Make sure [BetterDiscord](https://betterdiscord.app/) is installed
2. Download [`AutoFollowUser.plugin.js`](https://raw.githubusercontent.com/Keeplus/AutoFollowUser/main/AutoFollowUser.plugin.js)
3. Move it to your BetterDiscord plugins folder :

```
%appdata%\BetterDiscord\plugins\
```

4. Open Discord → Settings → Plugins → Enable **AutoFollowUser** ✅

---

## 🚀 Usage

1. **Right-click** on any user in a voice channel or server
2. Click **`Follow this user ✅`**
3. You will now automatically follow them into every voice channel they join
4. To stop, right-click the same user and click **`UnFollow this user ❌`**

---

## 🔄 Auto-Update

This plugin supports **automatic updates** via BetterDiscord's built-in updater.

Whenever a new version is pushed to this repo, BetterDiscord will notify you and offer to update automatically. No manual download needed.

---

## 🛡️ Compatibility

| Discord Version | Status |
|---|---|
| Latest (2026) | ✅ Working |
| Custom voice modules | ✅ Compatible |
| BetterDiscord 1.x | ✅ Supported |

---

## 📝 Changelog

### v1.8.0 — 2026
- ✅ Full rewrite — no longer depends on `discord_voice` internal modules
- ✅ Fixed dispatcher access via `VoiceStateStore._dispatcher`
- ✅ Fixed `guildId` resolution via `ChannelStore`
- ✅ Cross-server follow now working
- ✅ Auto-update support added
- ✅ Toast notifications on every channel switch

### v1.1.2 — Original
- Initial release by d3v.me

---

## 👤 Author

Made with ❤️ by **[Keeplus](https://github.com/Keeplus)**

---

## ⚠️ Disclaimer

This plugin is intended for personal use only.
Use responsibly and respect other users' privacy.
