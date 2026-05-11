<table>
<tr>
<td width="180" align="center">
<img width="160" alt="Actions & Stuff RTX Patcher Logo" src="./A&S Patcher/assets/resources/as_rtx_simple_logo_.png" />
</td>
<td>

## A&S Minecraft RTX Community Patcher

*Community-built patching tool for RTX-compatible Actions & Stuff on Bedrock Edition*

[![Release](https://img.shields.io/github/v/release/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher?style=flat-square&color=blue&label=Release)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases)
[![Stars](https://img.shields.io/github/stars/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher?style=flat-square&color=yellow)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/stargazers)
[![Issues](https://img.shields.io/github/issues/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher?style=flat-square)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/issues)
[![Pylint](https://img.shields.io/github/actions/workflow/status/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/pylint.yml?label=Pylint&style=flat-square&color=blue)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/actions/workflows/pylint.yml)
[![Discord](https://img.shields.io/discord/1432653252171661364?logo=discord&style=flat-square&label=Discord)](https://discord.gg/YrMMmN2kc7)

[![Download Latest](https://img.shields.io/badge/⬇_Download-Latest_Release-2ea44f?style=for-the-badge&logo=github)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/latest)

</td>
</tr>
</table>

---

- 🔧 Converts the **Actions & Stuff** Marketplace pack into an **RTX-compatible version**
- 💡 Adds full **BetterRTX lighting**, reflections, and **PBR materials**
- 📦 Supports **Marketplace auto-detect**, `.zip`, and `.mcpack` input formats
- 🔒 Does **not redistribute** any original pack assets — your copy, your patch

---

## ⚠️ Important Notice

This is a **community-driven RTX enhancement project** for _Actions & Stuff_ by **Oreville Studios**.  
The patcher **applies fixes and RTX enhancements to your own copy** of A&S — it does **not** distribute any part of the original resource pack.

We kindly ask all users **not to share their patched copies** of A&S Enhanced for RTX publicly.

---

## 📁 Repository Overview

| Component | Description | Link | Status |
| :--- | :--- | :---: | :---: |
| **A&S RTX Patcher V2** | Main patcher executable (Marketplace & Zip support) | [Source](./A%26S%20Patcher) | ✅ Active |
| **Patch Archive** | All binary patch files (`.xdelta` / `.vcdiff`) and the legacy V1 patcher source | [Repo](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher-Archive) | 📦 Updated |
| **External Tools** | Brarchive extractor, patch creator v2, and CI/CD helpers — tools not required in the main branch | [Repo](https://github.com/Felix-Chaos/Actions-and-Stuff-RTX-Patcher-External_Tools) | 🧰 Active |
| **Documentation** | How-to guides and setup instructions | [Docs](./docs) | 📚 Updated |
| **Tools** | Utilities for creating patches or building the patcher | [Tools](./A%26S%20Patcher/tools) | 🧰 Included |


---

## ⚙️ Requirements

| Requirement | Details |
| :--- | :--- |
| [**BetterRTX**](https://bedrock.graphics/) | Must be installed |
| [**Actions & Stuff**](https://www.minecraft.net/en-us/marketplace/pdp/oreville-studios/actions--stuff-1.6/61c7a786-d7ad-49e0-a710-817121cd9795) | Marketplace, `.zip`, or `.mcpack` format |

---

## 🚀 How to Use

### Standard Usage

1. Download **A&S RTX Patcher V2** from the [Releases Page](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/latest).
2. Run the `.exe` and choose:
   - **Marketplace Mode** — Auto-detects your installed pack.
   - **ZIP/MCPACK Mode** — Manually select your pack file *(toggle Advanced Mode to see this option)*.
3. Click **Start** to begin patching.

### In-Game Configuration

- **Disable "Mob Dithering"** in Video Settings to fix visual glitches.
- **Load Order** (Top → Bottom):
  1. **A&S RTX** *(Use this!)*
  2. **RTX Pack** *(Kelly's / Vanilla RTX / etc.)*
  3. *Other Resource Packs*
  4. **Actions & Stuff** *(Original)* **[Optional — Not Recommended]**

### 🛠️ Advanced Mode

Toggle **Advanced Mode** (bottom switch) to unlock:

- **Manual Inputs** — Override source or patch files
- **Version Selection** — Force a specific patch version
- **Open Folder** — Quickly access the generated `.mcpack`

---

### 🧰 Building from Source

Want to make your own patcher?  
Browse this repository — every tool and script includes a short README with setup steps and required dependencies.

---

## 💾 Downloads

<div align="center">

[![Latest Stable](https://img.shields.io/badge/Download-Latest_Release-2ea44f?style=for-the-badge&logo=github)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/latest)
[![V2 Beta](https://img.shields.io/badge/Download-V2_Beta-orange?style=for-the-badge&logo=github)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/V2.0.4b)

</div>

<details>
<summary><strong>📂 Older Versions & History</strong></summary>

<br>

<details>
<summary><strong>↳ Minecraft GDK (Modern — V1.21.120+)</strong></summary>

> _For modern Minecraft installations (Xbox App / GDK)_

- [A&S RTX Patcher v1.0.4 (for A&S 1.8)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/1.0.4)
- [A&S RTX Patcher v1.0.3 (for A&S 1.7)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/1.0.3)

</details>

<br>

<details>
<summary><strong>↳ Minecraft UWP (Legacy — Pre-1.21.120)</strong></summary>

> _For older/legacy Minecraft installations_

- [A&S RTX Patcher v1.0.2 (for A&S 1.7)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/1.0.2)
- [A&S RTX Patcher v1.0.1 (for A&S 1.6)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/U_N_v1.0.1)
- [A&S RTX Patcher v0.1.13 (for A&S 1.4)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/0.1.13)

</details>

<br>

### ⚗️ Experimental Builds

- [Beta v2.0.4b (for A&S 1.9)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/V2.0.4b)
- [Beta v2.0.3b (for A&S 1.9)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/V2.0.3b)
- [Beta v2.0.2b (for A&S 1.9)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/V2.0.2b)
- [Beta v2.0.1b (for A&S 1.9)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/V2.0.1b)
- [U_0.1.1 Universal Patcher (for 1.6 from 1.4 patch)](https://github.com/Felix-Chaos/A-S-Minecraft-RTX-Community-Patcher/releases/tag/U_0.1.1)

### 🕹️ Legacy Versions

- v1.07 (A&S 1.3) — _Outdated_
- v1.08 (A&S 1.3.1) — _Outdated_

</details>

---

## 📚 Resources & Community

<div align="center">

[![FAQ](https://img.shields.io/badge/📖_FAQ-Discord-5865F2?style=flat-square)](https://discord.com/channels/691547840463241267/1360688874388455504/1376325634246049792)
[![BetterRTX](https://img.shields.io/badge/💬_BetterRTX-Discord-5865F2?style=flat-square)](https://discord.gg/5kK4EMRbd3)
[![ChaosDev](https://img.shields.io/badge/🎮_ChaosDev-Discord-5865F2?style=flat-square)](https://discord.gg/YrMMmN2kc7)
[![Thread](https://img.shields.io/badge/📢_Project_Thread-Discord-5865F2?style=flat-square)](https://discord.com/channels/691547840463241267/1360688874388455504)

</div>

---

## 🙌 Contributors

| Name / Handle | Role | Contact |
| :--- | :--- | :--- |
| **@J4vi3r6003** | Patch development, subpacks, bug fixes | Discord: `error90099900#0000` |
| **@Felix-Chaos** | Project maintenance, patcher updates, releases | [GitHub](https://github.com/Felix-Chaos) · Discord: `felixchaos` |
| **Demente Parker** | Original creator, source files provider | Discord: `demente_parker` · [Ko-fi](https://ko-fi.com/dementeparker) |
| **Community Testers** | Bug reporting, testing, feedback | Various Discord contributors |

> Contributions welcome! Open a PR or join the [BetterRTX Discord](https://discord.gg/5kK4EMRbd3) / [ChaosDev Projects](https://discord.gg/YrMMmN2kc7).

---

## 👤 Original Creator & Support

This project is a **community fork** maintained for public development.  
The **original creator** who made the source files available is **Demente Parker**.

- Discord: `demente_parker` · ID: `498173069517651998`
- 💙 Support him on Ko-fi: [ko-fi.com/dementeparker](https://ko-fi.com/dementeparker)

> Donations go **directly to the original creator**. This repository is **non-profit** and exists solely for community collaboration.

---

## 🧠 Tools Used

- [**xdelta3**](https://github.com/jmacd/xdelta) — Binary patch creation and application
- [**Blockbench**](https://www.blockbench.net/) — Model editing & RTX material setup

---

## ⚖️ Disclaimer

This patcher is provided by the community for **educational and personal use only**.  
It is **not affiliated with or endorsed** by Oreville Studios or Mojang/Microsoft.  
All original assets remain property of their respective owners.

> 🤖 **Note**: The V2 overhaul of this project, including the code refactoring, UI improvements, and automated build system, was developed with the assistance of **Google DeepMind's AI models** to accelerate development for the community.

---

<div align="center">

⭐ **Thank you for being part of the A&S RTX community!**  
Your support, testing, and feedback keep this project alive — together we make RTX shine brighter. 💎

</div>
