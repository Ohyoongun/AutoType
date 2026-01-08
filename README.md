# AutoType
A smart macOS utility that automatically switches keyboard input sources based on the active application and window title.

# 🌐 AutoType for macOS

[![Release](https://img.shields.io/github/v/release/YOUR_USERNAME/AutoType-macOS?style=flat-square)](https://github.com/YOUR_USERNAME/AutoType-macOS/releases)
[![Platform](https://img.shields.io/badge/platform-macOS-lightgrey?style=flat-square)]()
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)]()

**Stop typing "dkssud" instead of "안녕"!** **AutoType** intelligently manages your keyboard input source based on what you are doing.

It remembers which language you used for specific Apps and even specific **Window Titles** (e.g., Safari tabs), so you never have to manually switch keyboards again.

---

<p align="center">
  <img src="./main/스크린샷 2026-01-08 오전 11.54.28" alt="App Screenshot" width="600">
</p>

## ✨ Key Features

### 🧠 Context-Aware Switching
* **App-Level:** Automatically switches to English for **Xcode**, **Terminal**, or **VSCode**.
* **Window-Level (Browser Support):** Distinguishes between tabs in browsers like **Safari** or **Chrome**.
    * Viewing *Google.com*? → Switches to **English**.
    * Viewing *Naver.com*? → Switches to **Korean** (or your local language).

### 🌍 Global Language Support
* Works with **ANY** keyboard input source installed on your Mac.
* (Korean, Japanese, Chinese, French, German, etc.)
* Simply select your **Primary (A)** and **Secondary (B)** languages in the settings.

### 🔔 Smart Feedback
* Provides a subtle **Sound Effect** when the language changes automatically.
* Visual badges indicate the current mode instantly.

### ⚡️ Quick Actions
* **Global Shortcut (F1):** Instantly converts selected typo text (e.g., `dlfjgrp` → `이렇게`) via clipboard simulation.

---

## 🚀 How to Install

1.  Go to the [**Releases**](https://github.com/YOUR_USERNAME/AutoType-macOS/releases) page.
2.  Download the latest `AutoType.zip`.
3.  Unzip and move `AutoType.app` to your **Applications** folder.
4.  **Right-click** the app and select **Open** (required for the first launch to bypass security warnings).

> **Note:** This app requires **Accessibility Permissions** to monitor active windows.
> Please allow it in: `System Settings` > `Privacy & Security` > `Accessibility`.

---

## 🛠 Tech Stack
* **Language:** Swift 5
* **UI Framework:** SwiftUI
* **Core API:** Carbon (TIS), ApplicationServices (AXUIElement), Cocoa

---

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
