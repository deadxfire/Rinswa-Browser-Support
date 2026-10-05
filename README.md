# 🌐 Rinswa Browser — Official Web & Support Portal

<div align="center">
  <img src="Glossy%20Multicolour%20Ribbon%20R%20Emblem.png" alt="Rinswa Logo" width="120" height="120">
  <br>
  <h3>The Next-Generation Cyber-Glass Web Browser</h3>
  <p>
    Built on modern Gecko with uncompromising aesthetics, built-in uBlock Origin, and zero telemetry.
  </p>

  [![Latest Release](https://img.shields.io/badge/Release-v1.0.4%20Stable-0284c7?style=for-the-badge&logo=github)](https://github.com/deadxfire/Rinswa-browser/releases/tag/v1.0.4)
  [![License](https://img.shields.io/badge/License-MPL%202.0-7c3aed?style=for-the-badge)](https://github.com/deadxfire/Rinswa-browser/blob/main/LICENSE)
  [![Platform](https://img.shields.io/badge/Platform-Windows%20x64-059669?style=for-the-badge&logo=windows)](https://github.com/deadxfire/Rinswa-browser/releases/tag/v1.0.4)
  [![Live Site](https://img.shields.io/badge/Live%20Portal-Online-2563eb?style=for-the-badge&logo=google-chrome)](https://deadxfire.github.io/Rinswa-Browser-Support/)
</div>

---

## 🔗 Live Portal Links

| Resource | URL | Description |
| :--- | :--- | :--- |
| **Official Homepage** | [deadxfire.github.io/Rinswa-Browser-Support](https://deadxfire.github.io/Rinswa-Browser-Support/) | Showcase, interactive browser simulator, feature comparisons, and build pipeline. |
| **Help & Support Center** | [deadxfire.github.io/Rinswa-Browser-Support/support.html](https://deadxfire.github.io/Rinswa-Browser-Support/support.html) | FAQs, themes, installation, troubleshooting diagnostics, shortcuts, and license terms. |
| **Main Browser Repository** | [github.com/deadxfire/Rinswa-browser](https://github.com/deadxfire/Rinswa-browser) | Core Gecko engine fork, branding assets, build scripts, and source code. |
| **Latest Release (v1.0.4)** | [github.com/deadxfire/Rinswa-browser/releases/tag/v1.0.4](https://github.com/deadxfire/Rinswa-browser/releases/tag/v1.0.4) | Standalone Windows installer and portable archive downloads. |
| **Bug Reports & Issues** | [github.com/deadxfire/Rinswa-browser/issues](https://github.com/deadxfire/Rinswa-browser/issues) | Submit bug reports, UI feedback, or feature requests. |

---

## 📦 Verified Release v1.0.4 Downloads & Checksums

All official binaries are compiled and signed for modern 64-bit Windows architectures.

| Asset Package | Target Architecture | Size | Direct Download Link | Cryptographic SHA-256 Checksum |
| :--- | :--- | :--- | :--- | :--- |
| **Standalone Installer** | Windows 10 / 11 (64-bit) | ~96.7 MB | [Download `.exe`](https://github.com/deadxfire/Rinswa-browser/releases/download/v1.0.4/rinswa-1.0.4.en-US.win64.installer.exe) | `2cf0547e6c4013c21f92f3379e9f4373c478008228119e8cbff003834105592c` |
| **Portable Zip Archive** | Windows 10 / 11 (64-bit) | ~153 MB | [Download `.zip`](https://github.com/deadxfire/Rinswa-browser/releases/download/v1.0.4/rinswa-1.0.4.en-US.win64.zip) | `24bc2901b4c7efd47e7590d2b25c9cb7729740feea79e73cff14445aa01430bb` |

### Integrity Verification

To verify binary integrity before installation, run the following in PowerShell or Command Prompt:

```powershell
certutil -hashfile rinswa-1.0.4.en-US.win64.installer.exe SHA256
```

---

## 🌟 Key Features of Rinswa Browser

- **✨ Cyber-Glass Aesthetic & Universal Themes:** Stunning glassy ribbons and frosted panels. Version 1.0.4 includes high-contrast support across bright Windows Light themes and custom AMO themes.
- **🛡️ Built-in uBlock Origin Adblocker:** Provisioned directly at the engine distribution level for instant protection with zero manual setup.
- **📑 All Tabs Manager & Tab Groups:** Dedicated dropdown displaying full tab titles, sound badges, close buttons, and color-coded tab grouping.
- **🚫 Zero Telemetry & Privacy Hardened:** All telemetry pings, Pocket integration, crash reporter beacons, and sponsored recommendations are permanently severed in source code.
- **🌄 Dynamic Alpine Sunset Wallpapers:** Signature new tab background with customizable themes and zero sponsored clutter.
- **🔄 Semantic Update Engine:** Advanced version comparison suppresses redundant update prompts when the browser is already up to date.
- **📜 Integrated Rinswa License:** Official licensing terms and author attribution accessible natively at `about:license`.

---

## 🗂️ Portal Architecture & Files

```text
Rinswa-Browser-Support/
├── index.html                           # Main product landing page & interactive simulator
├── support.html                         # Professional white-theme documentation & support portal
├── 404.html                             # In-browser redirect handler for help queries
├── README.md                            # Repository documentation & resource guide
├── Glossy Multicolour Ribbon R Emblem.png # Primary high-res Rinswa emblem
├── Rinswa Alpine Sunset Wallpaper.png   # Official Alpine Sunset vector wallpaper
├── logo.png                             # Browser brand logo
└── assets/                              # Static styling, vector icons, and documentation media
```

---

## 🛠️ Local Development & Preview

To run and preview the portal locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/deadxfire/Rinswa-Browser-Support.git
   cd Rinswa-Browser-Support
   ```

2. **Start a local HTTP server:**
   ```bash
   # Python 3
   python -m http.server 8080

   # Or Node.js / npx
   npx serve .
   ```

3. **Open in browser:**
   - Landing Page: `http://localhost:8080/index.html`
   - Support Center: `http://localhost:8080/support.html`

---

## 🤝 Community & Support

- **Bug Reports & Feature Requests:** [GitHub Issues](https://github.com/deadxfire/Rinswa-browser/issues)
- **Discussions & Community:** [GitHub Discussions](https://github.com/deadxfire/Rinswa-browser/discussions)
- **Developer Profile:** [github.com/deadxfire](https://github.com/deadxfire)

---

## ⚖️ License & Attribution

- **Creator & Lead Developer:** **Arindam Makar** ([@deadxfire](https://github.com/deadxfire))
- **Source Code License:** [Mozilla Public License 2.0 (MPL 2.0)](https://github.com/deadxfire/Rinswa-browser/blob/main/LICENSE)
- *Gecko™ and Firefox™ are trademarks of the Mozilla Foundation. Rinswa Browser is an independent open-source project.*
