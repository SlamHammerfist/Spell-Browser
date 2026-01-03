# Spellbook Manager

Spellbook Manager is a lightweight, intuitive enhancement for the DnD5e Compendium Browser for FoundryVTT that streamlines how spellcasters learn new spells. It adds clean UI tools, automatic known‑spell detection, and class‑aware spell selection — all without modifying system data or overriding core sheets.

---

## ✨ Features

### 🔍 Smart Spell Browsers
- **Cantrip Browser** and **Leveled Spell Browser** buttons appear directly on the character sheet.
- Automatically filters the Compendium Browser to the correct spell level range.
- Applies class filters automatically (Wizard, Bard, Sorcerer, etc.).

### 🎒 Known Spell Detection
- Spells already known by the actor are:
  - tinted for visibility  
  - marked with a **Known** badge  
  - have their selection checkbox removed  

---

## 📦 Installation

### Option 1: Manual Download
1. Download the ZIP from [GitHub](https://github.com/SlamHammerfist/Spell-Browser/archive/refs/heads/main.zip)
2. Extract into your `modules` folder

### Option 2: Manifest Link
1. Paste this into FoundryVTT's "Install Module" field:
   ```json
   https://raw.githubusercontent.com/SlamHammerfist/Spell-Browser/refs/heads/main/module.json
2. Enable Spell Browser in your world

## 🧭 Usage
- Open a spellcasting character sheet.
- Click Learn Cantrip or Learn Spell.
- The Compendium Browser opens automatically:
- filtered to the correct spell levels
- filtered to the actor’s class
- Select spells and confirm — they are added to the actor instantly.

## 🛠 Compatibility
- System: DnD5e 5.x
- Foundry: v13+
- Works with all compendium sources

## 📄 License
MIT License — free to use, modify, and extend.

