<table>
<tr>
<td width="140" align="center">
<img width="120" alt="A&S RTX Patcher Logo" src="https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher/raw/main/A%26S%20Patcher/assets/resources/as_rtx_simple_logo_.png" />
</td>
<td>

## A&S RTX Patcher — Patch Archive

*Binary patch files and legacy Patcher V1 source for the A&S RTX Community Patcher*

[![Main Patcher](https://img.shields.io/badge/Main_Patcher-Actions--and--Stuff--RTX--Patcher-2ea44f?style=flat-square&logo=github)](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher)
[![Discord](https://img.shields.io/discord/1432653252171661364?logo=discord&style=flat-square&label=Discord)](https://discord.gg/YrMMmN2kc7)

</td>
</tr>
</table>

---

- 📁 Stores all `.xdelta` / `.vcdiff` **binary patch files**, organized by A&S version
- 🕹️ Preserves the original **Patcher V1** source and the legacy **Patcher v2.1** Python source
- 📦 **Archived** — kept for historical reference only

> [!WARNING]
> **This repository is archived and no longer receives new patches.** New A&S RTX patches are now uploaded to the **[AS-RTX-Patch-Library →](https://github.com/Felix-Chaos/AS-RTX-Patch-Library)**. Everything here (patches, Patcher V1, Patcher v2.1) is preserved as-is for historical reference.

> [!IMPORTANT]
> This is a **companion repository**. For downloads, releases, and documentation, head to the **[Main Patcher Repo →](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher)**

---

## 📁 Repository Overview

| Repository | Description | Link |
| :--- | :--- | :---: |
| **A&S RTX Patcher** | Main patcher — Marketplace & Zip support, GUI, automated patching | [Repo](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher) |
| **AS-RTX-Patch-Library** | Current, actively updated home for all new binary patch files | [Repo](https://github.com/Felix-Chaos/AS-RTX-Patch-Library) |
| **Archive** *(this repo)* | Historical patch files and legacy patcher source — no longer updated | **This Repo** |
| **External Tools** | Brarchive extractor, and other tools for the patcher! | [Repo](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher-External_Tools) |

---

## 📋 What's in This Repository?

| Folder | Contents |
| :--- | :--- |
| `Patches/` | All `.xdelta` / `.vcdiff` patch files, organized by A&S version — historical, no longer updated |
| `Patcher V1/` | The original V1 patcher source code (`AnSRTXPatcher.py`) |
| `Patcher v2.1 Python/` | The legacy V2.1 Python patcher source, docs, and tutorial |

---

## 🗂️ Patches Archive

> [!NOTE]
> This folder is frozen. New patches are no longer added here — see the **[AS-RTX-Patch-Library →](https://github.com/Felix-Chaos/AS-RTX-Patch-Library)** for current patches.

The `Patches/` folder is the archive of all community-maintained RTX patch files up to the point this repo was archived. Each subfolder corresponds to an A&S version:

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


Each patch folder contains:
- **`decrypted.vcdiff`** — Patch for the decrypted ZIP/MCPACK source
- **`encrypted.vcdiff`** — Patch for the encrypted Marketplace source

---

## 🕹️ Patcher V1

The `Patcher V1/` folder contains the original patcher written by **Felix-Chaos**.

This is a Python-based patcher (`AnSRTXPatcher.py`) that can be built into a standalone `.exe` using the included `build_patcher.bat` and PyInstaller spec file. V1 is preserved here as a historical reference.

> [!NOTE]
> For the current, actively maintained patcher, always use the latest release from the **[main repository](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher)**.

---

## 🕹️ Patcher v2.1

The `Patcher v2.1 Python/` folder contains the legacy V2.1 Python patcher source, along with its docs and tutorial. It is preserved here as a historical reference alongside Patcher V1.

> [!NOTE]
> For the current, actively maintained patcher, always use the latest release from the **[main repository](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher)**.

---

> [!NOTE]
> **Disclaimer:** This project is community-built for personal & educational use only. It is not affiliated with or endorsed by Oreville Studios or Mojang/Microsoft. Original A&S assets are not distributed here — only binary diff files that require a valid copy of A&S to apply.
