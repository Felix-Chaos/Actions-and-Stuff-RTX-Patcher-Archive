# 📦 A&S RTX — Patches & Patcher V1 Archive

> **This is the patch archive repository for the A&S Minecraft RTX Community Patcher.**
> It stores all binary patch files that are regularly updated, plus the original **Patcher V1** source code by Felix-Chaos.

---

## 🔗 Main Project

The primary patcher (V2, actively maintained) lives here:

### ➡️ [Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher)

Head there for **downloads, releases, documentation, and support**.

---

## 📋 What's in This Repository?

| Folder | Contents |
| :--- | :--- |
| `Patches/` | All `.xdelta` / `.vcdiff` patch files, organized by A&S version — updated regularly |
| `Patcher V1/` | The original V1 patcher source code (`AnSRTXPatcher.py`) by **Felix-Chaos** |

---

## 🗂️ Patches Archive

The `Patches/` folder is the living archive of all community-maintained RTX patch files. Each subfolder corresponds to an A&S version:

```
Patches/
├── Actions & Stuff for RTX 1.6/
├── Actions & Stuff for RTX 1.8/
├── Actions & Stuff for RTX 1.9.1/
├── Actions & Stuff for RTX 1.9.1 v2/
├── Actions & Stuff for RTX 1.9.1.2/
├── Actions & Stuff for RTX 1.9b1/
├── Actions & Stuff for RTX 1.9b2/
├── Actions & Stuff for RTX 1.9b3/
└── ... (more added with each A&S update)
```

> **⚠️ Do not unzip the patch files.** They are consumed directly by the patcher tool.

Each patch folder contains:
- **`decrypted.vcdiff`** — Patch for the decrypted ZIP/MCPACK source
- **`encrypted.vcdiff`** — Patch for the encrypted Marketplace source

---

## 🕹️ Patcher V1

The `Patcher V1/` folder contains the original patcher written by **Felix-Chaos** (not Demente Parker).

This is a Python-based patcher (`AnSRTXPatcher.py`) that can be built into a standalone `.exe` using the included `build_patcher.bat` and PyInstaller spec file. V1 is preserved here as a historical reference and for users who need a lightweight alternative to V2.

> **For the current, actively maintained patcher, always use V2 from the [main repository](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher).**

---

## ℹ️ Relationship to the Main Repo

```
Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher  ← Main patcher (V2), releases, docs

Felix-Chaos/A-S-Patcher-Patches                  ← THIS REPO (patch file archive)
```

This is a companion archive that keeps all patch files in one place, separate from the main patcher repository. Patches are maintained and updated here independently. You can always grab the latest patch files manually from this repo if needed.

---

## ⚖️ Disclaimer

This project is community-built for personal & educational use only. It is not affiliated with or endorsed by Oreville Studios or Mojang/Microsoft. Original A&S assets are not distributed here — only binary diff files that require a valid copy of A&S to apply.
