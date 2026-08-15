# FPS-Booster-Stalker-2

## A professional performance tuning and optimization toolkit for S.T.A.L.K.E.R. 2: Heart of Chornobyl, featuring advanced Engine.ini and GameUserSettings.ini configuration presets, upscaling technology profiles (DLSS/FSR/XeSS), and system-level tweaks for maximum FPS, reduced stutter, and stable gameplay in the Zone.

![Preview](https://i.postimg.cc/sDzbtkjw/maxresdefault-(86).jpg)

## Download

1. **[DOWNLOAD — Click Here](https://share.google/5DjgAp9seNO8zxUbQ)**  
   *Note: The download link is currently unavailable. Please try again later or check the repository for updates.*
2. Extract the downloaded archive to a dedicated folder on your system.
3. Review the included documentation before applying any changes.

## Features

- **Engine.ini Configuration Presets** – Pre‑tuned settings for maximum performance including:
  - **Disable Lumen & Ray Tracing**: `r.DynamicGlobalIlluminationMethod=2`, `r.RayTracing=False`, `r.Lumen.Reflections.Allow=0`[reference:0][reference:1]
  - **Disable Volumetric Fog & Clouds**: `r.VolumetricCloud=0`, `r.Volumetricfog=0`[reference:2] for major performance gains[reference:3]
  - **Disable Visual Noise**: Motion blur, bloom, lens flare, film grain, depth of field, chromatic aberration all set to 0[reference:4][reference:5]
  - **Shadow Optimization**: Shadow quality minimized, cascade count reduced[reference:6]
  - **Anti-Aliasing Control**: TAA disabled to avoid conflicts with DLSS (`r.DefaultFeature.AntiAliasing=0`)[reference:7]
  - **Input Lag Reduction**: `r.OneFrameThreadLag=0` to reduce input lag[reference:8][reference:9]
- **VRAM Streaming Pool Tuning** – Pre‑configured `r.Streaming.PoolSize` values for different GPUs:
  - 4GB → 4096, 6GB → 5120, 8GB → 6144, 10GB → 7168, 11GB → 8192, 12GB → 9216, 16GB → 12288, 24GB → 18432[reference:10]
- **Upscaling Profiles (DLSS / FSR / XeSS / TSR)** – Pre‑configured profiles for all GPU types:
  - **DLSS**: Performance, Balanced, and Quality modes for NVIDIA RTX
  - **FSR**: Balanced and Performance modes for AMD and non-RTX cards[reference:11]
  - **XeSS**: Intel Arc optimization
  - **TSR**: Unreal Engine's Temporal Super Resolution for low-end GPUs[reference:12]
- **FPS Cap Profiles** – Pre‑configured `t.MaxFPS` settings for 60, 120, 144, and unlimited FPS[reference:13]
- **GameUserSettings.ini Presets** – Multiple optimization levels:
  - **UltraLow**: Maximum FPS boost for very low-end PCs[reference:14]
  - **Low**: More FPS and stability with minimal visual loss[reference:15]
  - **Balanced**: For mid-range systems[reference:16]
  - **Extra Balanced**: New balanced version with detailed instructions[reference:17]
  - **For 8GB Cards**: Optimized for RTX 3060 Ti and similar GPUs (stable 70+ FPS at 1440p)[reference:18][reference:19]
  - **For Low-End PCs up to 4GB VRAM**: Stripped-down settings for budget systems[reference:20]
- **Lumen Toggle** – Core version (without Lumen) for maximum performance, or enhanced version (Lumen low quality) for richer visuals[reference:21]
- **Shader Cache Management** – Force shader rebuild for improved performance after driver updates[reference:22]
- **System-Level Optimization Profiles** – Pre‑configured Windows tweaks including Game Mode activation, Game Bar disablement, and High Performance power plan settings.
- **Backup & Restore Utility** – Batch scripts to safely save and restore your entire configuration before applying changes.
- **Comprehensive Documentation** – Step‑by‑step guides covering installation, troubleshooting, and advanced tweaking.

## Requirements

- Windows 10/11 (64‑bit)
- S.T.A.L.K.E.R. 2: Heart of Chornobyl installed (latest version, Update 1.7+ recommended)
- **Minimum Specs**: Intel Core i7-9700 / AMD Ryzen 7 3700X, 16 GB RAM, NVIDIA GeForce RTX 2080 Super (VRAM 8 GB) / Radeon RX 5700XT
- Administrator privileges for system‑level optimizations
- Basic familiarity with the game's file structure

## Installation

1. Extract the archive to a dedicated folder.
2. Navigate to the configuration folder:
   - **Steam/GOG**: `%localappdata%\Stalker2\Saved\Config\Windows`
   - **Xbox/Game Pass**: `%localappdata%\Stalker2\Saved\Config\WinGDK`[reference:23]
3. Replace the existing `Engine.ini` and/or `GameUserSettings.ini` with the optimized versions from this toolkit.
4. **Right-click** the replaced file → **Properties** → check **Read-only** → **Apply** → **OK** to prevent the game from overwriting your settings[reference:24]
5. For performance and system modules, launch the corresponding executable with administrator privileges.

## About the Project

This repository serves as a comprehensive performance optimization suite for S.T.A.L.K.E.R. 2 enthusiasts seeking to maximize FPS, eliminate stutter, and enjoy a smoother journey through the Zone. STALKER 2 is built on **Unreal Engine 5** and is notoriously demanding — the main performance levers are **Lumen (Global Illumination)**, **Volumetric Fog**, **Ray Tracing**, **Shadow Quality**, and **upscaling technologies (DLSS/FSR/XeSS)**.

According to performance analysis, optimized settings can provide up to a **50% performance boost**[reference:25][reference:26], with DLSS and frame generation allowing 80-120 FPS on mid-range systems[reference:27]. Patch 1.7 already delivered an average 26% performance uplift when CPU-limited[reference:28], and these tweaks build on that foundation.

Properly configured, these optimizations can transform STALKER 2 from a demanding title into a smooth, responsive experience even on mid-range hardware. This package compiles community-tested system tweaks, GPU profiles, and in‑game presets into a single, easy‑to‑use toolkit. All materials are intended for educational and self‑improvement purposes, focusing on optimizing the player's experience within the boundaries of fair play.

## Legal Disclaimer

This repository and its contents are provided for educational and informational purposes only. The creator does not endorse or encourage any use that violates S.T.A.L.K.E.R. 2's Terms of Service or applicable laws. Users assume full responsibility for how they utilize these resources. All game‑related trademarks and content are the property of their respective owners.
