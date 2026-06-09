# Key2Pad

> **Your keyboard is now an Xbox controller.**
> Play any game on Steam, Windows, or anywhere else — without buying a gamepad.

**Key2Pad** is a Windows app that turns your keyboard into a virtual Xbox 360 controller in real time. It doesn't emulate at the game level: it installs an actual virtual gamepad device that is natively recognized by Steam and any game that supports XInput.

---

## ⬇️ Download & Installation

1. Go to the [**Releases**](https://github.com/alaancuevas/key2pad-releases/releases/latest) page and download the `Key2Pad-Setup.exe` installer.
2. Run the installer. On first launch, the Setup Wizard opens automatically.
3. Key2Pad will detect if **ViGEmBus** is missing and install it with one click.
4. Select a starting profile and click **Start Playing**.

### ⚠️ Windows SmartScreen Warning
Because Key2Pad is an indie app without a paid Microsoft code-signing certificate, Windows SmartScreen may show a warning. This is a false positive.
- Click **"More info"**
- Then click **"Run anyway"**

Key2Pad does not contain malware. ViGEmBus is open-source and published by [Nefarius Software Solutions](https://github.com/nefarius/ViGEmBus).

---

## ⚡ Features

- **Ultra-low latency** — Native C++ pipeline, P95 under 8ms.
- **Game profiles** — FPS, Racing, RPG, Platformer, Fighting and more.
- **Virtual Xbox 360 gamepad** — Powered by ViGEmBus.
- **Live overlay** — See your inputs in real time on screen.
- **Per-game key mapping** — Buttons, analog sticks (deadzone + sensitivity + curve), triggers.
- **Favorites** — Star profiles for quick access.
- **Google login** — Save your license in the cloud.
- **Toggle anytime** — Press `F12` to pause/resume without closing the app.

---

## 🎮 Remote Play Together — play co-op without a controller

Steam Remote Play Together lets a friend join your local game remotely — but it requires a controller on the guest's side. Key2Pad solves this by turning the guest's keyboard into a virtual Xbox 360 gamepad, no hardware needed.

**How it works:**
1. Host starts Key2Pad and launches the game
2. Guest joins via Steam Remote Play Together
3. Key2Pad emulates a virtual controller — the guest plays with their keyboard

Key2Pad includes dedicated **Co-op / Remote Play Together** profiles optimized for this use case.

> ⚠️ Avoid use in online competitive games. Key2Pad takes no responsibility for account bans resulting from anti-cheat detection. See the [disclaimer](#️-online-game-ban-disclaimer) below.

---

## ⛔ Online game ban disclaimer

Key2Pad emulates a virtual Xbox 360 controller at the driver level. Some online games with aggressive anti-cheat systems (Easy Anti-Cheat, BattlEye, Vanguard) may detect virtual controllers and flag accounts.

**KEY2PAD TAKES NO RESPONSIBILITY FOR ANY ACCOUNT SUSPENSIONS, BANS, OR PENALTIES** resulting from the use of this software in online games. Use at your own risk in online environments.

---

## 📬 Support & Contact

- **Discord:** coming soon
- **Email:** key2pad.contact@gmail.com
- **License:** available on [Gumroad](https://key2pad.gumroad.com/l/connector)

---

## 📄 License

The source code of Key2Pad is proprietary and not publicly available.  
ViGEmBus is licensed under MIT by Nefarius Software Solutions.