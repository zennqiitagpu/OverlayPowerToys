<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/57dd6299-ded7-4c71-95a9-a7f4c201aaaf" />

# Overlay PowerToys

A floating toolkit for Android that stays on top of other apps. Take notes, sketch ideas, do quick calculations, or browse the web without leaving what you're doing.

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/zennqiitagp)

## What is it?

Overlay PowerToys is a floating toolkit that stays on top of any Android app. Access notes, drawings, a calculator, and a browser without leaving your current screen.

✏️ **Text Memo** – Jot down notes, save locally, or export.

🎨 **Handwriting** – Sketch with custom brushes and export as PNG.

🔢 **Calculator** – Quick math with history.

🌐 **Browser** – Tabbed browsing in a floating window, now with favorites and site-data controls.

Minimize to a draggable widget anytime. Built with Jetpack Compose for Android 10+.

---

## Product Description

### Take notes without switching apps

The text editor lets you write quick notes while doing other things. Copy/paste works as expected, and you can save multiple notes to come back to later. When you need a note outside the app, export it to user-visible storage.

<img width="324" height="720" alt="image" src="https://github.com/user-attachments/assets/16d61fed-9012-4cc4-8606-4e9928297149" />

### Sketch and annotate

The drawing canvas gives you a pen, color picker, and eraser. Adjust brush size, draw what you need, and save your work. You can export drawings as PNG with transparent, solid, or (Android 11+) captured-behind background modes.

<img width="324" height="720" alt="image" src="https://github.com/user-attachments/assets/6d06413c-af38-426a-8707-2bad28c3fb5a" />

### Quick calculations

A built-in calculator is available for fast math while you stay in context. It supports standard operations (+, −, ×, ÷, %) and keeps calculator history for quick recall.

<img width="324" height="720" alt="image" src="https://github.com/user-attachments/assets/8beedcde-196b-488e-a445-712c2c7bbba3" />

### Browse the web in-overlay

The browser is built for quick reference while you work:

- Tabs with clear public/private indicators
- Private-by-default new-tab toggle
- Persistent browsing history (with per-item and clear-all delete)
- Star-based favorites (save/remove per URL, plus favorites list)
- Site data management (per-origin clear + clear all)
- File downloads and in-overlay file uploads

<img width="324" height="720" alt="image" src="https://github.com/user-attachments/assets/efa39527-9a4d-4858-be7c-98fa56c75793" />

### Stays out of the way

When you don't need the full panel, minimize it to a small floating widget. Drag it anywhere, tap to reopen, or close it when done.

<img width="324" height="720" alt="image" src="https://github.com/user-attachments/assets/e239f32c-7718-4cdb-91b4-1cea99bf1cd1" />

---

## Getting Started

1. Open the app and tap **Enable Overlay**.
2. Grant **Draw over other apps** when prompted.
3. On Android 13+, allow notifications.
4. Tap the pinned notification anytime to open the overlay.

### Optional: Background capture for drawings

If you want drawing export with captured background (what is behind the overlay baked into the PNG), enable:

**Android Settings → Accessibility → Overlay PowerToys**

---

## Browser Privacy Notes

- Private tabs are excluded from app-level browser history.
- In private mode, address-bar input and WebView input apply best-effort anti-learning behavior for IME, and Autofill is disabled for private WebViews.
- Site data (cookies/storage) can be managed manually from **Site data** (per-origin or clear all).
- Due to Android WebView API limitations, per-site data deletion is origin-based best effort.
