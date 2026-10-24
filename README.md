# 💡 Light Up The Town - In-Game Mod Manager

Welcome to the **Light Up The Town Mod Manager**! This mod adds a seamless, in-game UI to *Light Up The Town*, allowing players to browse installed mods, view rich metadata, and inspect visual previews without leaving the game.

---

## ✨ Features

- **🎮 In-Game Mod Menu:** Access a dedicated, intuitive UI directly from the main menu.
- **📜 Rich Mod Details:** View names, authors, version tags, dependencies, game compatibility, and detailed markdown/text descriptions.
- **🖼️ Visual Previews & Captions:** Display custom preview images complete with titles and context captions.
- **🌐 Multiplayer Ready:** Designed out of the box to work alongside the [Light Up The Town Multiplayer Mod](https://github.com/BadSignal-Software/Light-Up-The-Town-Multiplayer-Mod).

---

## 👥 Authors & Credits

Developed and maintained by:

- **ShadowCanvas815**
- **Ctr1s0ftw4re**

### 🔗 Related Projects
- **Multiplayer Mod:** Check out the official multiplayer extension on [GitHub](https://github.com/BadSignal-Software/Light-Up-The-Town-Multiplayer-Mod).

> 💡 **Note:** The official Multiplayer Mod already includes the Mod Manager by default!

---

## 🚀 Installation & Setup

### For Players
1. Download the latest release (`mod manager.zip`) from the [**Releases**](../../releases) page.
2. Extract the contents directly into your *Light Up The Town* mods folder (inside the `UE4SS` directory).
3. Launch the game and click the new **Mod Manager** button on the main menu!

---

## 🛠️ Mod Developer Integration Guide

To make your mod visible in the Mod Manager, follow these steps:

### 1. File Structure
Place `modmanager.json` inside your mod's root directory under `UE4SS`:

```text
UE4SS/
└── Mods/
    └── YourModName/
        ├── modmanager.json
        └── images/
            ├── preview1.png (e.g bean1.png)
            └── preview2.jpg

```

---

### 2. Configure `modmanager.json`

Create or copy from this repo, a `modmanager.json` file in your mod's folder using the template below, the one below is just an example from the multiplayer mod:

```json
{
  "name": "LUTTNet",
  "version": "0.0.16",
  "author": "ShadowCanvas815 & CtrlSoftware",
  "description": "Multiplayer for Light Up The Town.",
  "long_description": "Syncs placed lights and decorations between players over a local bridge.",
  "tags": ["multiplayer", "network"],
  "dependencies": ["UE4SS 3.0.1", "Python 3"],
  "game_version": "1.1.1",
  "images": [
    {
      "file": "images/bean1.png",
      "title": "A picture of bean",
      "caption": "A picture of bean captured from another POV."
    }
  ]
}

```

#### Field Reference

| Key | Type | Description |
| --- | --- | --- |
| `name` | String | The display title of your mod. |
| `version` | String | Current release version tag. |
| `author` | String | Mod creator name(s). |
| `description` | String | A brief summary shown in list views. |
| `long_description` | String | Expanded explanation shown on the detail panel. |
| `tags` | Array | Categorization tags (e.g., `["multiplayer", "utility"]`). |
| `dependencies` | Array | Required frameworks or mods (e.g., `["UE4SS 3.0.1"]`). |
| `game_version` | String | Target game version compatibility. |
| `images` | Array | List of image objects containing `file`, `title`, and `caption`. |

---

## 🤝 Contributing

Contributions, bug reports, and feature requests are welcome!

Feel free to open an issue or submit a pull request on GitHub.

---

## 📄 License

This project is currently provided **without a license** (All Rights Reserved).

```

```
