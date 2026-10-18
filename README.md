# 🔷 Firefox Graphite Blue

A sleek, modern dark CSS theme for Mozilla Firefox featuring deep graphite shades and vibrant blue accents.

<p align="center">
  <img width="100%" src="https://github.com/user-attachments/assets/2f52d001-7f1f-4d1e-bcbc-26f010287c79" alt="Firefox Graphite Blue — Full Preview">
</p>

---

## 💡 Recommendation

For the best visual experience, enable the default **Dark** theme in Firefox:

**Settings** → **Add-ons and themes** (`about:addons`) → **Themes** → **Dark**

<p align="center">
  <img width="389" src="https://github.com/user-attachments/assets/47d2633a-5e1a-4182-992c-ea3b9d392718" alt="Theme Setting Recommendation">
</p>

---

## ✨ Features

- **Graphite & Blue Palette** — a clean, distraction-free dark UI designed for low-light environments.
- **Modern Interface** — refined styling for the tab bar, URL bar, and popups.
- **Lightweight** — pure CSS (`userChrome.css` / `userContent.css`) with no meaningful performance overhead.

---

## 🛠️ Installation

### Step 1 — Enable Custom User Stylesheets

1. Open Firefox and enter `about:config` in the address bar, then press **Enter**.
2. Accept the warning by clicking **Accept the Risk and Continue**.
3. Search for the following preference:

   ```text
   toolkit.legacyUserProfileCustomizations.stylesheets
   ```

4. Double-click the preference, or use the toggle button, to set it to **`true`**.

### Step 2 — Locate Your Profile Folder

1. Open `about:support` in Firefox.
2. Find **Profile Folder** and click **Open Folder** (or **Show in Finder** / **Open Directory**, depending on your system).

### Step 3 — Apply the Theme

1. Inside your profile directory, find the `chrome` folder.
   - If it doesn't exist, create a folder named `chrome`.
2. Download or clone this repository.
3. Copy the theme files — `userChrome.css`, `userContent.css`, and any additional CSS modules — into the `chrome` folder.
4. Restart Firefox to apply the theme.
