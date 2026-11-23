# Hello UI Dialer (Flashable Root Module)

A system-integrated, flashable ZIP module of the **Motorola Hello UI Dialer** built for rooted AOSP-based custom ROMs.

While the original non-rooted APK port by **AndroPort World (APW)** lets you install the app, several core calling features remain broken without system-level permissions. This module converts it into a rooted, flashable ZIP to fix those broken features and deliver a complete, native dialer experience on AOSP.

---

## 📥 Download
Grab the latest `.zip` file from the **[Releases](../../releases)** page.

*(You can directly flash the downloaded `.zip` file—no manual extraction or APK installation needed.)*

---

## 🔍 The Changes Done In My Project!

### ❌ What's Unstable on the APW Non-Rooted APK
Because the original port is a standard non-rooted `.apk` without system integration, the following core features do not work properly:
* **Incoming Call View** – Broken
* **Ongoing Call View** – Broken
* **Favourites Option** – Broken
* **Call Log** – Broken
* **Voicemail** – Broken
* **Call Recording** – Broken

### ✅ What's Fixed in This Rooted Module (ZIP)
By integrating the dialer directly into the system via a flashable module, all of the above issues are resolved:
* **Incoming Call View** – Fully working
* **Ongoing Call View** – Fully working
* **Favourites Option** – Fully working
* **Call Log** – Fully working
* **Voicemail** – Fully working
* **Call Recording** – Fully working

---

## 🚀 What's Fixed & Improved in Version 2.0 (Latest Release)
* **Contact Search Fixed** – Searching through your saved contacts now works smoothly.
* **Dialpad Search Fixed** – Number/name search directly from the dialpad is now fixed.
* **Improved App Performance** – Faster loading, smoother animations, and better overall stability.
* **Ongoing Video Call UI Improved** – Visual and layout improvements for ongoing video calls. *(Note: Video calling has not been tested, so full functionality cannot be guaranteed.)*

---

## 📲 Installation Instructions
1. Head over to the **[Releases Page](https://github.com/YOUR_USERNAME/YOUR_REPO/releases/latest)** and download the latest `.zip` file.
2. Open **Magisk**, **KernelSU**, or **KernelSU-Next**.
3. Navigate to the **Modules** tab and tap **Install from storage**.
4. Select the downloaded `.zip` file to flash it directly.
5. Reboot your device and set Hello UI Dialer as your default phone app if prompted.

---

## 🧪 Tested Environment
* **Device:** Motorola Moto G54 5G
* **ROM:** PixelOS (AOSP 17)
* **Android Version:** Android 17 QPR2
* **Tested By:** Procelight

---

## ⚠️ Troubleshooting & Notes
- **Calls not showing up / InCallUI not appearing:** Ensure the app is set as the **Default Phone App** and reboot once after granting permissions.
- **Replacing Google Dialer:** You can disable Google Dialer in Settings if you don't want duplicate Phone apps.
- **Bootloop Safety:** If anything goes wrong, boot into Safe Mode or remove the module folder from `/data/adb/modules/` via custom recovery.

---

## 🙏 Credits
* **AndroPort World (APW)** – Original credit for the non-rooted Hello UI Dialer APK. This project builds upon their port to create a rooted, flashable ZIP module with full system-level fixes.


---
