# Moon Client 1.21.11

<p align="center">
<img src="https://client.moonlit.onl/icon.png" alt="moon-client-logo" width="18%"/>
</p>

<h3 align="center">Fabric Utility Mod — Fast, Clean</h3>
<p align="center">Founded and maintained by <a href="https://www.youtube.com/@melthedev"><b>MelTheDev</b></a> — Founder of <a href="https://client.moonlit.onl">Moonlit</a></p>

<div align="center">
  <a href="https://discord.gg/nvYnewCejU"><img src="https://img.shields.io/discord/689197705683140636?logo=discord" alt="Discord"></a>
  <a href="https://www.tiktok.com/@melthedev"><img src="https://img.shields.io/badge/TikTok-@melthedev-black?logo=tiktok" alt="TikTok"></a>
  <a href="https://www.youtube.com/@melthedev"><img src="https://img.shields.io/badge/YouTube-@melthedev-red?logo=youtube" alt="YouTube"></a>
  <br>
  <a href="https://client.moonlit.onl"><img src="https://img.shields.io/badge/Website-client.moonlit.onl-9B59FF?logo=googlechrome" alt="Website"></a>
</div>

---

## Links
- **Website:** https://client.moonlit.onl
- **Discord:** https://discord.gg/nvYnewCejU
- **TikTok:** https://www.tiktok.com/@melthedev
- **YouTube:** https://www.youtube.com/@melthedev

## Download

| File | Minecraft | Loader | Notes |
|------|-----------|--------|-------|
| `moon-client-1.21.11.jar` | 1.21.11 | Fabric Loader 0.18.2+ | **Recommended** — stable OpenGL + Sodium |
| `moon-client-vulkan-1.21.11.jar` | 1.21.11 | Fabric Loader 0.18.2+ | **FAILED ATTEMPT — Experimental Vulkan** — crashes on HUD/scissor, not usable — kept for archive only |

> Vulkan build is labeled as failed attempt and not supported. Use the standard jar for now.

## Installation
1. Install [Fabric Loader](https://fabricmc.net/use/) for **Minecraft 1.21.11**.
2. Put `moon-client-1.21.11.jar` in `.minecraft/mods`.
3. Launch Fabric 1.21.11 — `Right Shift` for ClickGUI.

No extra Fabric API needed (jar-in-jar). Requires **Java 21**.

## Features
- **ESP / Tracers / Radar** — range up to `5000` blocks (GUI slider), Box/Wireframe/Shader modes, tight hitbox (`deflated 0.02`)
- **Item Highlight** — empty list = highlights all items
- **Undercover** — `MessageAura`/`Spam`/`BookBot` default empty, no branded spam
- **GUI** — Dark theme, left-aligned titles, bottom accent bar, Moon blue `88,140,255`, `Moon` theme
- **Performance** — Lithium `0.21.4` compat fix, Sodium `0.8.14`, Bobby chunk caching
- **The Moon Is Lit** — title splash

## Usage Notes
- **Anarchy:** Keep `Movement` (`Speed`, `Fly`, `Timer`) off — they flag. `ESP`/`Tracers` visual only is safe. Reset the client config folder after swapping jars.
- **Vulkan:** Vulkan support was attempted and failed (shader `world_colored` GLSL and GUI `Scissor`/`MeshRenderer` reentrancy not compatible with `VulkanMod 0.6.8`). Do not use `moon-client-vulkan-1.21.11.jar` for play — it is archived as failed attempt.

## Requirements
- Minecraft 1.21.11
- Fabric Loader 0.18.2+
- Java 21+

---
*Built by **MelTheDev** for Moonlit — https://client.moonlit.onl — Questions? [Discord](https://discord.gg/nvYnewCejU)*
