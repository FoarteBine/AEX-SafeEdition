<div align="center">
  <img src="https://raw.githubusercontent.com/FoarteBine/AEX/refs/heads/main/assets/aex.jpg.webp" alt="AEX Logo" width="290" style="border-radius: 16px; box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);" />
  <h1> AEX Safe Edition </h1>
  <p><b>Next-Gen Expansion Framework for Infinity Yield.</b></p>
  
  <p>
    <img src="https://img.shields.io/badge/Platform-Roblox-000000?style=for-the-badge&logo=roblox&logoColor=white" alt="Platform">
    <img src="https://img.shields.io/badge/Language-Lua%20%2F%20Luau-2C2D72?style=for-the-badge&logo=lua&logoColor=white" alt="Language">
    <img src="https://img.shields.io/badge/Edition-Safe-2ea44f?style=for-the-badge" alt="Edition">
    <img src="https://img.shields.io/badge/Architecture-Modular-0366d6?style=for-the-badge" alt="Architecture">
  </p>
</div>

---

## System Overview

**AEX Safe Edition** is an enterprise-grade modification and redesign of the Infinity Yield framework, engineered with a strict focus on security and reliability. In this edition, potentially unstable or intrusive components (such as `jerk`, `bang`, and the external plugin hub system) have been completely removed. 

The framework bridges the gap between raw performance and aesthetic refinement, implementing a complete visual overhaul, optimized core subsystems, and an expanded command library tailored for high-efficiency operation.

## Repository
* **GitHub:** [FoarteBine/AEX-SafeEdition](https://github.com/FoarteBine/AEX-SafeEdition)

## Authors 
* **FoarteBine** - Main AEX developer, visual designer.
* **Distendo** - AEX developer, mainly fun/useful scripts.

---

## Core Architectural Enhancements

| Subsystem | Traditional Infinity Yield | AEX Safe Edition |
| :--- | :--- | :--- |
| **Visual Interface** | Legacy layout with rigid structural constraints | Modernized visual hierarchy, fluid spacing, and custom typography |
| **Command Library** | Standard utility and trolling suite | Cleaned and filtered command set with removed unsafe/intrusive elements |
| **Security & Hub** | External plugin loading and legacy hooks | Stripped external plugin hub, `jerk`, and `bang` modules for maximum safety |
| **Core Performance** | Standard runtime overhead | Refactored execution loops ensuring minimal footprint and high responsiveness |

---

## Quick Implementation

Execute the loadstring below within your target environment to initialize AEX Safe Edition:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/FoarteBine/AEX-SafeEdition/refs/heads/main/source"))()
