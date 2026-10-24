# 💡 Light Up The Town - In-Game Mod Manager

Welcome to the **Light Up The Town Mod Manager**! This mod provides a seamless, in-game UI that allows players to browse installed mods, read detailed descriptions, check author details, and preview screenshots directly within *Light Up The Town*.

---

## ✨ Features

- **🎮 In-Game Mod Menu:** Access a dedicated, intuitive UI directly from the main game menu.
- **📜 Detailed Mod Info:** View full descriptions, version tags, and author credits for all loaded mods.
- **🖼️ Visual Previews:** Display custom preview images and screenshots to showcase mod features.
- **🌐 Multiplayer Compatible:** Fully compatible with the official [Light Up The Town Multiplayer Mod](https://github.com/BadSignal-Software/Light-Up-The-Town-Multiplayer-Mod).

---

## 👥 Authors & Credits

Maintained and developed by:

- **ShadowCanvas815**
- **Ctr1s0ftw4re**

### 🔗 Related Projects
- **Multiplayer Mod:** Check out the official multiplayer extension on [GitHub](https://github.com/BadSignal-Software/Light-Up-The-Town-Multiplayer-Mod).

> **Note:** If you download the official Multiplayer Mod, the Mod Manager comes pre-packaged with it!

---

## 🚀 Installation & Setup

### For Players
1. Download the latest release (`mod manager.zip`) from the [**Releases**](../../releases) page.
2. Extract the archive into your *Light Up The Town* mods directory (located inside the `UE4SS` folder).
3. Launch the game and look for the **Mod Manager** button on the main menu.

---

## 🛠️ Mod Developer Integration Guide

To make your mod discoverable by the Mod Manager, follow these steps:

### 1. Add `modmanager.json`
Place the `modmanager.json` inside your mod directory e.g UE4SS/LUTTNet/modmanager.json

### 2. Add Preview Images (Optional)

Create an `images` folder in the same directory as `modmanager.json`:

```text
YourModFolder/
├── modmanager.json
└── images/
    ├── preview1.png
    └── preview2.jpg

```

The Mod Manager will automatically scan this folder and display the images in the UI.

---

## 🤝 Contributing

Contributions, bug reports, and feature requests are always welcome!

Feel free to open an issue or submit a pull request on GitHub.

---

## 📄 License

This project is currently provided **without a license** (All Rights Reserved).

```
