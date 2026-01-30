# 🔥 MeltedFN Account Insights

MeltedFN is a high-performance, multi-threaded **Fortnite account insights tool** designed to display detailed account statistics directly in your terminal.

⚠️ **Authorized use only:** This tool is intended for use with accounts you own or accounts you have explicit permission to access/test. Do not use it to access accounts without authorization.

## 🛒 How to Get Access
This software requires a valid **License Key** to operate.
**Note:** Keys are **HWID Locked** to one device. You cannot share your key.

To purchase a subscription or get support, join our official Discord server:

👉 https://discord.gg/jv8n9Um6DY

---

## 🚀 Features
* **Fast Processing:** Multi-threaded processing for responsive performance.
* **Complete Cosmetic Capture:** Captures cosmetics including Skins, Backblings, Pickaxes, Emotes, Gliders, Sprays, Toys, Wraps, Banners, Loading Screens, Cars, Jam Tracks, Instruments, and Kicks.
* **Deep Account Info:** Shows V-Bucks, Linked Accounts (PSN/XBL/Switch), STW Power Level/Edition, and Email Verification status (where available via official endpoints).
* **Custom Wishlist:** Define specific cosmetics (e.g., "Travis Scott", "Black Knight") to highlight via the config.
* **Visual Dashboard:** Real-time stats, CPM, and counters directly in your terminal.
* **Discord RPC:** Show your status on your Discord profile.

---

## ⚙️ Configuration Guide (config.ini)

Before running, configure the `config.ini` file. Open it with any text editor. You can control what is displayed on screen and what is saved to files.

### 1. General Settings
```ini
[General]
threads               = 70    ; Concurrent worker threads
save_stats            = true  ; Save output to Results folder
```

### 2. Custom Tracker (Wishlist)
Define specific cosmetics you want to highlight.

```ini
[CustomTracker]
# Items found here will show a [WISHLIST] tag in white text on the console.
items = black knight, travis, galaxy, ikonik, renegade raider, leon s. kennedy
```

### 3. Dashboard Display (On-Screen)
Control exactly what data appears on the live console.

```ini
[DashboardDisplay]
# --- Account Details ---
show_email       = true
show_2fa         = true
show_vbucks      = true
show_last_played = true

# --- Cosmetic Counters (Stats) ---
show_stat_skins          = true
show_stat_emotes         = true
show_stat_pickaxes       = true
show_stat_cars           = true
show_stat_jamtracks      = true
show_stat_instruments    = true
show_stat_kicks          = true
# ... (and all other categories)
```

### 4. Dashboard Exclusives
Control which Rare/Exclusive item names are printed to the console when found.

```ini
[DashboardExclusives]
show_exclusive_skins     = true
show_exclusive_emotes    = true
show_exclusive_cars      = true
show_exclusive_jamtracks = true
show_exclusive_kicks     = true
# ... (Set to false to hide specific rare categories from the screen)
```

### 5. File Export Settings (Results Folder)
Controls what data is written to the text files inside the `Results/` folder.

```ini
[FileExports]
# --- Toggle Item Counts ---
show_skin_count       = true
show_vbucks_count     = true
show_car_count        = true
show_kicks_count      = true
show_instrument_count = true
# ...

# --- Toggle Item Lists (The actual names) ---
show_skin_names       = true
show_emote_names      = true
show_pickaxe_names    = true
show_jamtrack_names   = true
show_kicks_names      = true
# ...

# --- Account Info ---
show_epic_email       = true
show_2fa              = true
show_connections      = true
show_last_played      = true
```

---

## 📝 How to Use
1. Open `MeltedFN.exe`.
2. The tool will verify your license key automatically (HWID check).
3. Sign in with an account you own or have explicit permission to access using the tool’s supported login flow.
4. View results in the terminal and in the `Results/` folder (if enabled).

---

## ⚠️ Troubleshooting
**License Error?**  
Ensure you copied the key exactly as provided. Keys are locked to your Hardware ID.

**Stuck or failing to fetch data?**  
Check your internet connection and confirm any required official services are reachable.

**Closing**  
When finished, press **[Enter]** on the completion screen to exit safely.

---

© 2026 MeltedFN  
Developed for Educational Purposes Only
