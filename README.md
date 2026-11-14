# Hello-UI-Dialer-Module
Magisk / KernelSU module to install Motorola Hello UI Dialer on AOSP custom ROMs.

# Motorola Hello UI Dialer (Magisk / KernelSU Module)

A systemless module that brings **Motorola's Hello UI Dialer (Phone & Contacts)** to AOSP-based custom ROMs, replacing Google Dialer with clean UI and built-in call recording support (without announcement).

---

## ✨ Features
- Official Motorola Hello UI Phone & InCallUI interface
- Clean, ad-free Material You experience
- Built-in Call Recording support (device & region dependent)
- Works systemlessly via Magisk, KernelSU, and APatch

---

## 📋 Requirements
- **Root:** Magisk v24.0+, KernelSU / KernelSU Next, or APatch
- **OS:** Android 13 / 14 / 15 / 16+ (AOSP / Pixel-based custom ROMs recommended)
- **Architecture:** `arm64-v8a`
- *Note: Not recommended for heavily modified OEM skins (OneUI, HyperOS, ColorOS) due to package conflicts.*

---

## 📥 Download
Grab the latest `.zip` file from the **[Releases](../../releases)** page.

---

## 🛠️ Installation Guide
1. Download the latest `Hello-UI-Dialer.zip` from **Releases**.
2. Open **Magisk** / **KernelSU** / **APatch** → go to **Modules** → **Install from storage**.
3. Select the downloaded `.zip` file and wait for flashing to complete.
4. **Reboot** your device.
5. Go to **Settings > Apps > Default apps > Phone app** and select **Phone** (Hello UI Dialer).
6. Long-press the Phone app icon → **App info > Permissions** and allow all required permissions (Phone, Contacts, Call logs, Microphone).

---

## ⚠️ Troubleshooting & Notes
- **Calls not showing up / InCallUI not appearing:** Ensure the app is set as the **Default Phone App** and reboot once after granting permissions.
- **Replacing Google Dialer:** You can disable Google Dialer in Settings if you don't want duplicate Phone apps.
- **Bootloop Safety:** If anything goes wrong, boot into Safe Mode or remove the module folder from `/data/adb/modules/` via custom recovery.

---

## 🙏 Credits
- Motorola Mobility for the original Hello UI Phone APK
- Custom ROM & Android porting community

