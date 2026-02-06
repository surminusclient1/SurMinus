# SurMinus – Advanced Game Client

**SurMinus** is an advanced browser-based client for **surviv.io**, providing powerful tools and quality-of-life features to enhance gameplay control, visibility, and automation.

> ⚡ Fast • Modular • Highly Customizable

---

## ✨ Features

### 🎯 Combat

* **Aimbot** – Automatic targeting with advanced options:

  * Sticky Target
  * Wallcheck
  * Target Dot
* **Auto Fire** – Automatically fire when aiming at a valid target
* **Auto Heal** – Smart usage of bandages and med kits based on HP
* **Auto Switch** – Intelligent weapon switching
* **Melee Lock** – Improved melee precision

* **Pan Hero** – OP

### 👁 Visuals

* **ESP (Player Detection)** – Display player positions & info
* **X-Ray** – Reduced opacity for smoke & trees
* **Infinite Zoom** – Unlimited zoom control
* **Grenade Timer** – Visual grenade cook countdown
* **Map Highlights** – Highlight important locations
* **Layer Spoofer** – Manipulate render layers for visibility
* **Blur Background** – Reduce visual clutter


### 🧰 Utility

* **Auto Loot** – Automatically pick up nearby items
* **Mobile Movement** – Smooth mobile-style controls
* **Keybind System** – Fully customizable hotkeys
* **Auto Crate Break** – Automatically break supply crates within radius
---

## 📖 Installation

### Method 1: Tampermonkey Userscript (Recommended)

#### Requirements

* Tampermonkey (Chrome / Firefox / Edge / Safari)
* Latest version of your browser

#### Steps

1. **Install Tampermonkey**

   * Chrome: Tampermonkey Web Store
   * Firefox: Tampermonkey Add-ons
   * Edge / Safari: Available in respective stores

2. **Install Script**

   * Download or copy `SurMinus.user.js`
   * Open Tampermonkey Dashboard
   * Click **Create new script**
   * Paste the script
   * Save (Ctrl + S / Cmd + S)

3. **Launch**

   * Open **survev.io**
   * Press **Shift + Right Click** to open the menu

---

### Method 2: Chrome Extension

#### Steps

1. Download the latest build (`SurMinus.zip`) from **Releases**
2. Open `chrome://extensions/`
3. Enable **Developer mode**
4. Drag & drop the `.zip` file into the page
5. Open **surviv.io** and press **Shift + Right Click**

#### Updating

* Drag the updated build again
* Chrome will auto-refresh the extension

---

## 🚀 Quick Start

* **Open Menu:** `Shift + Right Click`
* **Toggle Aimbot:** `B`
* **Toggle Infinite Zoom:** `Shift + Left Click`
* **Toggle Layer Spoof:** `T`
* **Toggle Sticky Target:** `N`

> All keybinds can be customized in the in-game menu.

---

## ⚙️ Configuration

### Default Keybinds

| Key                 | Action               |
| ------------------- | -------------------- |
| Shift + Right Click | Toggle Menu          |
| B                   | Toggle Aimbot        |
| Shift + Left Click  | Toggle Infinite Zoom |
| T                   | Toggle Layer Spoof   |
| N                   | Toggle Sticky Target |

### Menu Tabs

* **Combat** – Aimbot, Auto Fire, Auto Heal, Auto Switch, Melee Lock
* **Visuals** – ESP, X-Ray, Zoom, Layer Spoof, Map Highlights
* **Misc** – Auto Loot, Mobile Movement, Blur Background, Pan Hero
* **Help** – Feature descriptions & usage tips

### Settings

* All settings are saved automatically
* Persistent across browser sessions
* Each feature is individually configurable

---

## 🐛 Troubleshooting

### Menu not opening

* Ensure Tampermonkey is enabled
* Press **Shift + Right Click** multiple times
* Refresh the page
* Disable conflicting extensions

### Aimbot not working

* Check that Aimbot is enabled
* Disable Wallcheck if target is behind walls
* Re-toggle the feature

### Settings not saving

* Ensure `localStorage` is enabled
* Clear cache and reload
* Reinstall the script

### Performance issues

* Disable X-Ray if lag occurs
* Reduce ESP render distance

### Script not loading

* Confirm you are on **survev.io**
* Update Tampermonkey
* Reinstall the script

---

## 📄 License

**Proprietary License**
Unauthorized redistribution or modification is prohibited.

---

**Version:** 4.2
**Last Updated:** February 2026
