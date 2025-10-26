<div align="center">

![Header](header.svg)

<p align="center">
  <strong>A single-file HTML tool for creating and editing Palworld dedicated server configuration files</strong>
</p>

[HOSTED PAGE](https://blinkzer0.github.io/Palworld-Dedicated-Server-Config-Creator/PalWorldSettingsEditor.html)

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-usage">Usage</a> •
  <a href="#-configuration-sections">Configuration</a> •
  <a href="#-contributing">Contributing</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT">
  <img src="https://img.shields.io/badge/Platform-Web-brightgreen.svg" alt="Platform: Web">
  <img src="https://img.shields.io/badge/Dependencies-None-orange.svg" alt="No Dependencies">
</p>

---

### 📄 [View Editor Preview](Palworld%20Server%20Settings%20Editor.pdf)

</div>

## 🎯 Why Use This Tool?

Palworld's server configuration file uses a **monolithic single-line format** with hundreds of parameters, making it extremely difficult to edit manually. This tool solves that problem by:

- ✨ Organizing settings into logical categories
- ✅ Providing validation for numeric ranges
- 📚 Including helpful descriptions for each parameter
- 🛡️ Preventing formatting errors
- ⚡ Saving time and reducing configuration mistakes

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎨 User Experience
- 🖥️ **User-Friendly Interface** - Clean, organized sections
- 📁 **Load Existing Configs** - Import and edit `.ini` files
- 📋 **Copy to Clipboard** - Quick export functionality
- 🔄 **Reset to Defaults** - Restore original settings
- 📱 **Responsive Design** - Works on all devices

</td>
<td width="50%">

### ⚙️ Technical Features
- 💾 **Export Configuration** - Properly formatted output
- 💡 **Interactive Tooltips** - Help for each setting
- ✅ **Input Validation** - Prevent invalid values
- 🚀 **Zero Dependencies** - Single HTML file
- 🔒 **Offline Ready** - No internet required

</td>
</tr>
</table>

## 🎮 Configuration Sections

<details open>
<summary><b>Server & Networking</b></summary>

- 🌐 **Server Information** - Name, description, passwords, ports, region
- 👥 **Multiplayer Settings** - Player limits, PvP, guilds, crossplay
- 🔌 **RCON & REST API** - Remote console and API configuration

</details>

<details>
<summary><b>Gameplay & Balance</b></summary>

- ⚔️ **Gameplay Settings** - Difficulty, XP rates, death penalties, time
- 🎲 **Randomizer Settings** - World randomization options
- 🧍 **Player Settings** - Damage, hunger, stamina, HP regeneration
- 🐾 **Pal Settings** - Spawn rates, stats, egg hatching, Palbox

</details>

<details>
<summary><b>World & Resources</b></summary>

- 🏗️ **Base & Building** - Build limits, worker counts, deterioration
- 💎 **Drops & Resources** - Collection rates, respawn speeds, drops
- 👹 **Enemy & Invader** - Enemy invasion controls
- 🏛️ **Guild Settings** - Guild management, auto-reset timers

</details>

<details>
<summary><b>Server Management</b></summary>

- 💾 **Server Management** - Auto-save, chat limits, backup settings
- 📊 **Performance** - Cull distance, container intervals

</details>

## 🚀 Quick Start

1. **Download** `PalWorldSettingsEditor.html`
2. **Open** the file in any modern web browser
3. **Configure** your server settings
4. **Generate** and copy the INI output
5. **Paste** into your server's `PalWorldSettings.ini` file

## 📖 Detailed Usage

### Creating a New Configuration

```bash
1. Open PalWorldSettingsEditor.html in any modern web browser
2. Configure your server settings using the organized form sections
3. Click "Generate INI Output" to create the configuration
4. Click "Copy to Clipboard" to copy the generated content
5. Paste into your PalWorldSettings.ini file
```

**File Locations:**
- 🪟 **Windows:** `<YourPalServerFolder>\Pal\Saved\Config\WindowsServer\PalWorldSettings.ini`
- 🐧 **Linux:** `<YourPalServerFolder>/Pal/Saved/Config/LinuxServer/PalWorldSettings.ini`

### Loading Existing Configuration

```bash
1. Click "Load from INI File"
2. Select your existing PalWorldSettings.ini file
3. All fields will be automatically populated
4. Make your changes
5. Regenerate and export the configuration
```

## 🌐 Browser Compatibility

<div align="center">

| Browser | Status |
|---------|--------|
| Chrome/Edge | ✅ Recommended |
| Firefox | ✅ Fully Supported |
| Safari | ✅ Fully Supported |
| Opera | ✅ Fully Supported |

</div>

## 📁 Project Structure

```
Palworld-Dedicated-Server-Config-Creator/
├── PalWorldSettingsEditor.html  # Main application (standalone)
├── header.svg                     # Animated header graphic
├── Palworld Server Settings Editor.pdf  # Documentation
├── README.md                      # This file
└── LICENSE                        # MIT License
```

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. 🍴 **Fork** the repository
2. 🔨 **Make changes** to `PalWorldSettingsEditor.html`
3. ✅ **Test** thoroughly in multiple browsers
4. 📝 **Submit** a pull request with a clear description

### Areas for Contribution
- 🐛 Bug fixes and improvements
- 🎨 UI/UX enhancements
- 📚 Documentation updates
- 🌍 Translations
- ✨ New features

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This is an **unofficial community tool** and is not affiliated with, endorsed by, or connected to Pocketpair or Palworld.

> **⚠️ Important:** Always backup your server configuration files before making changes!

---

<div align="center">

**Made with ❤️ for the Palworld Community**

[Report Bug](../../issues) • [Request Feature](../../issues) • [Documentation](Palworld%20Server%20Settings%20Editor.pdf)

</div>
