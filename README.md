# LOGZ_Admin

Private binary administration plugin for **Counter-Strike 2** powered by **CounterStrikeSharp**.

LOGZ_Admin is built for communities that want a cleaner, more organized, and more flexible admin system with custom ranks, formatted chat, permission handling, moderation tools, and MySQL-backed ban support.

---

## ✨ Features

- Admin group system
- Custom prefixes and rank formatting
- Colored admin chat display
- Permission-based access
- Admin priority support
- MySQL ban integration
- JSON-based configuration
- Online version check
- Lightweight and practical for live servers

---

## 📦 Release Type

This repository provides **binary releases only**.

- ✅ Compiled `.dll` release files
- ✅ Ready to deploy on supported CS2 servers
- ❌ Source code is **not included**

---

## 🛠 Requirements

Before using LOGZ_Admin, make sure your server has:

- **Counter-Strike 2 Dedicated Server**
- **Metamod:Source**
- **CounterStrikeSharp**
- Correct plugin and config folder structure
- MySQL database access if you use the ban system

---

## Required / Recommended Plugins
For full functionality, we recommend installing the following plugin as well:
- [LOGZ_AdminMenu](https://github.com/MartyCSGO/LOGZ_AdminMenu) | Recommended | Quick menu for commands in LOGZ_Admin |

## 📥 Installation

1. Download the latest release ZIP
2. Extract the archive
3. Upload `LOGZ_Admin.dll` to your CounterStrikeSharp plugins directory
4. Upload or edit the configuration files if needed
5. Restart the server or reload the plugin

---

## ⚙️ Configuration

LOGZ_Admin supports configuration for:

- admin groups
- admin accounts
- permissions
- rank formatting
- MySQL connection
- moderation-related options

Make sure your database credentials and server settings are correctly configured before production use.

---

## 💬 Commands

Below are the main commands available in LOGZ_Admin.

### Admin Info
- `css_logzadmin_whoami`  
  Shows your current admin group, permissions, and basic information.

- `css_logzadmin_reload`  
  Reloads plugin configuration files.

- `css_logz_admins`
- `css_admins`  
  Shows online admins and their configured groups.

### Moderation Commands
- `css_logz_kick`
- `css_kick`  
  Kick a player from the server.

- `css_logz_ban`
- `css_ban`  
  Ban a player from the server.

- `css_logz_unban`
- `css_unban`  
  Remove an active ban by SteamID64.

- `css_logz_slay`
- `css_slay`  
  Slay one or more players.

- `css_logz_map`
- `css_map`  
  Change the current map.

- `css_logz_respawn`
- `css_respawn`  
  Respawn one or more players.

- `css_logz_hp`
- `css_hp`  
  Set HP for one or more players.

- `css_logz_armor`
- `css_armor`  
  Set armor for one or more players.

- `css_logz_rr`
- `css_rr`  
  Restart the round or match.

- `css_logz_spec`
- `css_spec`  
  Move one or more players to spectator.

- `css_logz_setteam`
- `css_setteam`  
  Move one or more players to T / CT / SPEC.

### Notes
- Some commands may require specific permissions or admin groups.
- Command availability depends on your configuration.
- Some aliases may behave the same and are included for flexibility.

---

## 👥 Admin Groups

The plugin supports configurable admin groups such as:

- Founder
- Owner
- Co-Owner
- Administrator
- Moderator
- Helper
- VIP
- Custom groups defined by your server

Each group can have:
- prefix
- chat color
- priority
- permissions
- formatting rules

---

## 🎨 Chat and Rank Formatting

LOGZ_Admin supports:
- colored prefixes
- custom rank tags
- admin name formatting
- chat identity styling
- permission-based display logic

This allows each server to create its own administration style and hierarchy.

---

## 🗄 MySQL Integration

The plugin supports MySQL for moderation-related systems such as bans.

Examples of usage:
- saving ban entries
- loading moderation data
- persistent punishment storage

Make sure your MySQL credentials are valid before running the plugin on a live server.

---

## 🔄 Version Check

The plugin includes a version check system and can display messages such as:

- `Plugin is up to date`
- `Plugin is outdated`

This helps keep your live server aligned with the latest release version.

---

## 📌 Notes

- This repository is intended for **release distribution**
- Source code is private
- New releases may include:
  - compatibility fixes
  - performance improvements
  - new features
  - game update support

For best stability, always use the latest release.

---

## 👤 Author

**Marty**

---

## 🔒 Repository Notice

This repository contains **binary release files only**.  
The **source code is private** and is not distributed here.
