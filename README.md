# Key2Pad

> Turn your keyboard into a gamepad.

**Key2Pad** is a Windows desktop app that maps keyboard input to a virtual Xbox 360 controller in real time, with ultra-low latency. Built for PC gamers who want to play controller-only games using their keyboard.

---

## ⬇️ Download

Go to the [**Releases**](https://github.com/alaancuevas/key2pad-releases/releases/latest) page to download the latest version.

**System requirements:**
- Windows 10 or Windows 11 (64-bit)
- Administrator privileges (required for driver installation)
- ~50MB free disk space

---

## ⚡ Features

- **Ultra-low latency** — Native C++ pipeline, P95 under 8ms
- **Game profiles** — FPS, Racing, RPG, Platformer, Fighting and more
- **Virtual Xbox 360 gamepad** — Powered by ViGEmBus
- **Live overlay** — See your inputs in real time on screen
- **Per-game key mapping** — Buttons, analog sticks (deadzone + sensitivity), triggers
- **Favorites** — Star profiles for quick access
- **Google login** — Save your license in the cloud
- **Toggle anytime** — Press `F12` to pause/resume without closing the app

---

## 🛠 Installation

1. Download `Key2Pad-Setup.exe` from the [Releases](https://github.com/alaancuevas/key2pad-releases/releases/latest) page.
2. Run the installer. On first launch, the Setup Wizard opens automatically.
3. Key2Pad will detect if **ViGEmBus** is missing and install it with one click.
4. Select a starting profile and click **Start Playing**.

### ⚠️ Windows SmartScreen warning

Because Key2Pad is an indie app without a paid Microsoft code-signing certificate, Windows SmartScreen may show a warning. This is a false positive.

To proceed:
- Click **"More info"**
- Then click **"Run anyway"**

Key2Pad does not contain malware. ViGEmBus is open-source and published by [Nefarius Software Solutions](https://github.com/nefarius/ViGEmBus).

---

## 🎮 About ViGEmBus

ViGEmBus is an open-source virtual controller driver by **Nefarius Software Solutions**. It allows Windows to recognize software-created Xbox 360 controllers. It is trusted by DS4Windows, Ryujinx, and thousands of other gaming utilities.

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
