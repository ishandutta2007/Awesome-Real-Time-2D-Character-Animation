# 🎭 Awesome Real-Time 2D Character Animation 🚀

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Real-Time 2D Character Animation Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Real-Time-2D-Character-Animation/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Real-Time-2D-Character-Animation?style=flat-square&logo=github&color=gold" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Real-Time-2D-Character-Animation/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Real-Time-2D-Character-Animation?style=flat-square&logo=github&color=blue" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Real-Time-2D-Character-Animation/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License: MIT" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Real-Time-2D-Character-Animation/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Overview & SEO Summary

A curated directory and engineering landscape of **Real-Time 2D Character Animation**, **Live Puppeteering**, **Webcam Facial Motion Capture (Mocap)**, **Mesh Deformation Rigging**, and **VTuber Runtimes**.

These technologies bridge digital illustration and live performance by taking continuous inputs — webcam vision streams, audio speech phonemes, or MIDI/keyboard triggers — and interpolating them in real time across parametric 2D meshes, skeletal bone rigs, and physics pendulums. Whether deploying studio-scale broadcast rigs, browser-native WebGL avatars, or self-hosted open-source VTuber pipelines, this list maps commercial standards and open-source alternatives.

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ Architectural Taxonomy: How Real-Time 2D Works](#️-architectural-taxonomy-how-real-time-2d-works)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Community](#-support--community)
- [⭐ Star History](#-star-history)
- [📜 Disclaimer & License](#-disclaimer--license)

---

## 📊 Sector Overview & Market Dynamics

The global **2D animation and real-time character animation software market** is currently valued at approximately **$1.85 Billion to $2.40 Billion**, projected to surpass **$4.60 Billion by 2032** with a compound annual growth rate (CAGR) of ~8.7%. This expansion is propelled by the exponential rise of the virtual streamer (VTuber) economy, live interactive broadcasts, gaming avatars, and real-time generative digital humans.

The market displays a **moderately fragmented** dynamic characterized by distinct sub-segments rather than a pure winner-take-all monopoly:
- **Studio & Broadcast Animation**: Legacy giants like Adobe (Character Animator) and Francisco Partners / Integrated Media Technologies (Toon Boom) command high-margin professional creative suites and enterprise production workflows.
- **Anime & VTuber Rigging**: Live2D Cubism remains the entrenched commercial format standard across Japan and international gaming/streaming ecosystems.
- **Open-Source Counter-Ecosystem**: Rapidly increasing licensing costs, closed file formats, and vendor lock-in have spurred a decentralized open-source movement spearheaded by projects like Inochi2D, Open-LLM-VTuber, and OpenToonz, delivering royalty-free open runtimes for Godot, Unity, and WebAssembly.

---

## 🏢 SaaS & Commercial Platforms

The table below compiles leading commercial platforms, sorted in descending order by **Company Size (Revenue / Valuation)**.

| 🎨 Product / Platform | 🏢 Company Size (Valuation / Revenue) | ⚙️ Real-Time 2D Capabilities | 💳 Starting Tier Pricing | 🎁 Free Tier / Trial Limit | 🎯 Target Use Case |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Adobe Character Animator](https://www.adobe.com/products/character-animator.html)** | **~$220B+ Market Cap** / **$21.4B Annual Revenue** (Adobe Inc., NASDAQ: ADBE) | • Webcam & audio-driven live puppeteering<br>• Real-time eye gaze, blink, & viseme tracking<br>• Adobe Creative Cloud roundtrip pipeline | **$59.99 / month** (Creative Cloud All Apps annual plan, paid monthly); or **$89.99 / month** (month-to-month); **$19.99 / mo** for Students | **7-day free trial** of full CC Pro suite; **Starter Mode is free forever** but locked to ~50 pre-built puppet templates and direct MP4 export (custom rigging & timeline editing disabled) | Professional live broadcast puppeteering, corporate explainers, and Adobe After Effects integrations |
| **[Toon Boom Harmony](https://www.toonboom.com/products/harmony)** | **~$112M Acquisition Valuation** ($147.5M CAD) / Francisco Partners parent AUM >$45B; **~$35M Annual Rev** | • High-end deformers (Envelope, Curve, Bone)<br>• Advanced node-based rigging composites<br>• Real-time OpenGL animation preview | **$27.00 / month** (Harmony Essentials, billed annually) or **$34.50 / month** (monthly); Advanced at **$67.50 / mo**; Premium at **$123.50 / mo** | **21-day free trial** with complete access to all toolsets across Essentials, Advanced, and Premium; exports and renders contain a visible watermark; non-commercial testing only | Feature-film, television series production, and cut-out / traditional hybrid studio pipelines |
| **[Cartoon Animator 5](https://www.reallusion.com/cartoon-animator/)** | **~$20M Annual Revenue** (Reallusion Inc., Private) | • Smart bone rigging and spring dynamics<br>• 2D Motion LIVE webcam / iPhone facial mocap<br>• PSD-to-puppet layered automated converter | **$149.00 one-time** perpetual workstation license (Standard); **$299.00 one-time** for Pro / Pipeline Suite; Mocap plug-in from **$99.00 one-time** | **30-day free trial** with full feature set, sample characters, and motion library; all rendered video exports are watermarked during the trial period | Indie animators, commercial video creators, and YouTube content producers wanting turn-key mocap |
| **[Live2D Cubism](https://www.live2d.com/en/)** | **~$15M Annual Revenue** (Live2D Inc., backed by Sony Music / Aniplex) | • Parametric mesh warping of layered 2D art<br>• Physics curves, sway simulations, & eye tracking<br>• Industry-standard `.moc3` runtime runtime | **¥1,573 / month** (~**$10.50 / mo** billed annually) or **¥2,299 / month** (~**$15.30 / mo** monthly) for Individual; Business tier at **¥7,260 / mo** (~**$48.40 / mo**) | **Free Forever Tier (Cubism FREE)**: Hard-capped at 30 art meshes, 2 deformer hierarchy depths, 2 parameters per deformer, 1 model file per project, commercial use restricted to entities <¥10M revenue; **42-day free trial** of Cubism PRO | De facto global standard for 2D VTuber avatars, mobile visual novels, and Live2D interactive game assets |
| **[VTube Studio](https://denchisoft.com/)** | **~$3M Annual Revenue** (DenchiSoft, Leading Indie Studio) | • Real-time iOS ARKit & webcam face tracking<br>• Live2D parameter mapping with custom hotkeys<br>• Physics-based prop attachments & hand tracking | **$14.99 one-time** DLC (VTube Studio PRO - Remove Watermark on Steam, iOS, and Android) | **Free Forever Tier**: Complete feature access including tracking algorithms, custom expressions, item drops, and OBS spout integration; displays a floating watermark mascot logo on output feed | Live VTuber streaming, interactive Twitch/YouTube broadcasts, and real-time live avatar puppeteering |

---

## 💻 Open-Source GitHub Projects

The following repositories provide open-source codebases, libraries, editors, and runtimes for real-time 2D puppet rigging, facial motion tracking, and traditional animation. **Sorted in descending order by GitHub Stars_Count**.

1. **[Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber)** [![GitHub_Stars](https://img.shields.io/github/stars/Open-LLM-VTuber/Open-LLM-VTuber?style=social&color=white)](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber/stargazers)  
   *Hands-free voice interaction, voice interruption, and Live2D 2D character avatar running locally across platforms.*  
   Integrates local LLMs, TTS engines, speech recognition, and Live2D parameter engines for autonomous, interactive, real-time 2D digital assistants and streaming companions.

2. **[live2d-widget](https://github.com/stevenjoezhang/live2d-widget)** [![GitHub_Stars](https://img.shields.io/github/stars/stevenjoezhang/live2d-widget?style=social&color=white)](https://github.com/stevenjoezhang/live2d-widget/stargazers)  
   *Web-based real-time Live2D character animation widget for browser integration.*  
   Brings interactive, mouse-tracking, and scripted 2D puppets directly to web applications, blogs, and dashboards with minimal bundle size and broad model format support.

3. **[Krita](https://github.com/KDE/krita)** [![GitHub_Stars](https://img.shields.io/github/stars/KDE/krita?style=social&color=white)](https://github.com/KDE/krita/stargazers)  
   *Professional free and open-source raster painting suite with integrated 2D frame animation timeline.*  
   Features onion skinning, audio track synchronization, raster timeline scrubbing, and high-performance brush engines. Excellent for hand-drawn frame sequences and asset prep for 2D puppets.

4. **[OpenToonz](https://github.com/opentoonz/opentoonz)** [![GitHub_Stars](https://img.shields.io/github/stars/opentoonz/opentoonz?style=social&color=white)](https://github.com/opentoonz/opentoonz/stargazers)  
   *Studio-grade open-source 2D animation production software based on the legendary Toonz platform.*  
   Used extensively by Studio Ghibli. Combines traditional hand-drawn vector/raster pipelines with the "Plastic Tool" for mesh deformation, skeleton bone rigging, node-based compositing effects, and automatic line-work cleanup.

5. **[hexo-helper-live2d](https://github.com/EYHN/hexo-helper-live2d)** [![GitHub_Stars](https://img.shields.io/github/stars/EYHN/hexo-helper-live2d?style=social&color=white)](https://github.com/EYHN/hexo-helper-live2d/stargazers)  
   *Seamless integration plugin for deploying interactive real-time Live2D characters into websites.*  
   Supports physics sway, customizable hit areas, touch gestures, and voice synthesis hooks across static site generators and web frontends.

6. **[EasyVTuber](https://github.com/yuyuyzl/EasyVtuber)** [![GitHub_Stars](https://img.shields.io/github/stars/yuyuyzl/EasyVtuber?style=social&color=white)](https://github.com/yuyuyzl/EasyVtuber/stargazers)  
   *Real-time 2D VTuber puppeteering from single anime illustrations.*  
   Based on Talking-Head-Anime neural models and webcam computer vision. Allows creators to drive head yaw, pitch, roll, blinking, and mouth shapes instantly from a single character portrait without manual rigging.

7. **[Synfig Studio](https://github.com/synfig/synfig)** [![GitHub_Stars](https://img.shields.io/github/stars/synfig/synfig?style=social&color=white)](https://github.com/synfig/synfig/stargazers)  
   *Industrial-grade open-source 2D vector animation suite with skeletal rigging.*  
   Eliminates manual frame-by-frame tweening through parametric vector interpolation. Offers a comprehensive bone rigging system, cut-out animation workflows, distortion layers, and mathematical expression linking.

8. **[OpenSeeFace](https://github.com/emilianavt/OpenSeeFace)** [![GitHub_Stars](https://img.shields.io/github/stars/emilianavt/OpenSeeFace?style=social&color=white)](https://github.com/emilianavt/OpenSeeFace/stargazers)  
   *Robust, lightweight real-time facial landmark tracking and expression pipeline.*  
   Runs directly on CPU/GPU via regular webcams. Powers tracking backends across numerous open-source 2D/3D VTuber tools, providing high-precision eye gaze, pupil dilation, 3D head pose, and mouth visemes.

9. **[Talking Head Anime](https://github.com/pkhungurn/talking-head-anime-demo)** [![GitHub_Stars](https://img.shields.io/github/stars/pkhungurn/talking-head-anime-demo?style=social&color=white)](https://github.com/pkhungurn/talking-head-anime-demo/stargazers)  
   *Real-time neural animation of 2D anime character portraits from a single static image.*  
   Uses deep learning models to warp and synthesize anime facial expressions, head rotations, and eye movements in real time based on facial tracking inputs.

10. **[Inochi2D](https://github.com/Inochi2D/inochi2d)** [![GitHub_Stars](https://img.shields.io/github/stars/Inochi2D/inochi2d?style=social&color=white)](https://github.com/Inochi2D/inochi2d/stargazers)  
    *The reference open-source standard and runtime for real-time 2D puppet animation.*  
    Features runtime parameter-driven 2D mesh deformation, dynamic physics pendulums, real-time lighting shaders, and non-proprietary file formats. Multi-language bindings available in C (`inochi2d-c`) and Rust (`Inox2D`).

11. **[Pencil2D](https://github.com/pencil2d/pencil)** [![GitHub_Stars](https://img.shields.io/github/stars/pencil2d/pencil?style=social&color=white)](https://github.com/pencil2d/pencil/stargazers)  
    *Lightweight, intuitive cross-platform traditional 2D animation app.*  
    Focuses on zero-friction hand-drawn animation with bitmap and vector drawing layers, onion skinning, and rapid keyframe sequencing. Ideal for animating sprite sheets and hand-drawn character loops.

12. **[Inochi Creator](https://github.com/Inochi2D/inochi-creator)** [![GitHub_Stars](https://img.shields.io/github/stars/Inochi2D/inochi-creator?style=social&color=white)](https://github.com/Inochi2D/inochi-creator/stargazers)  
    *Official open-source GUI rigging and puppet editor for the Inochi2D ecosystem.*  
    Imports layered PSD art files, generates triangulated deformation meshes, configures physics drivers for hair/clothing sway, sets up dynamic depth layers, and exports standardized `.inp` puppet files.

13. **[Inochi Session](https://github.com/Inochi2D/inochi-session)** [![GitHub_Stars](https://img.shields.io/github/stars/Inochi2D/inochi-session?style=social&color=white)](https://github.com/Inochi2D/inochi-session/stargazers)  
    *Real-time livestreaming and broadcast puppeteering tool for Inochi2D puppets.*  
    Connects webcam motion trackers (OpenSeeFace, VMC protocols), microphone lip-sync algorithms, and hotkeys to puppet parameters for live streaming and OBS integration.

14. **[open-vt](https://github.com/erodozer/open-vt)** [![GitHub_Stars](https://img.shields.io/github/stars/erodozer/open-vt?style=social&color=white)](https://github.com/erodozer/open-vt/stargazers)  
    *Open-source desktop 2D VTuber software and runtime.*  
    Provides camera tracking, expression switching, and lightweight local rendering for creators seeking a clean, tracker-integrated alternative to commercial 2D live streaming applications.

15. **[Umamo](https://github.com/umamoorg/umamo)** [![GitHub_Stars](https://img.shields.io/github/stars/umamoorg/umamo?style=social&color=white)](https://github.com/umamoorg/umamo/stargazers)  
    *Cross-platform open-source 2D puppet rigging editor.*  
    Engineered with first-class pen, tablet, and touch support. Designed as a modern, open-source alternative to proprietary rigging tools with intuitive mesh deformation tools.

16. **[Glaxnimate](https://github.com/mbasaglia/glaxnimate)** [![GitHub_Stars](https://img.shields.io/github/stars/mbasaglia/glaxnimate?style=social&color=white)](https://github.com/mbasaglia/glaxnimate/stargazers)  
    *Fast vector graphics animation program with real-time preview.*  
    Supports Lottie, SVG, Rive, and vector tweening. Integrates with video editors (Kdenlive, Shotcut) to deliver real-time vector overlays and interactive animated character graphics.

17. **[ChibiRigKit](https://github.com/milkc0de/ChibiRigKit)** [![GitHub_Stars](https://img.shields.io/github/stars/milkc0de/ChibiRigKit?style=social&color=white)](https://github.com/milkc0de/ChibiRigKit/stargazers)  
    *Browser-based single-image automated 2D rigging toolkit.*  
    Ingests a single PNG illustration and automatically partitions eye, mouth, hair, and body layers. Integrates real-time webcam face tracking, mic lip-sync, and direct OBS browser-source streaming over localhost.

---

## 🛠️ Architectural Taxonomy: How Real-Time 2D Works

```mermaid
flowchart LR
    subgraph Inputs ["🎯 1. Live Input Capture"]
        A1["📹 Webcam Feed\n(60 FPS RGB)"]
        A2["🎙️ Microphone\n(PCM Audio)"]
        A3["⌨️ Controller / MIDI\n(Hotkeys)"]
    end

    subgraph Tracking ["🧠 2. Real-Time Landmark Extraction"]
        B1["OpenSeeFace / MediaPipe\n(468 Facial Landmarks)"]
        B2["Lip Sync Viseme Engine\n(Phonemes to A/I/U/E/O)"]
        B3["Expression Classifier\n(Smile, Blink, Surprised)"]
    end

    subgraph RigEngine ["⚡ 3. 2D Mesh & Rigging Runtime"]
        C1["Inochi2D / Live2D Core"]
        C2["Parametric Mesh Warping\n(Triangulated 2D Mesh)"]
        C3["Physics Simulation\n(Pendulums, Hair, Sway)"]
    end

    subgraph Output ["📺 4. Live Display & Broadcast"]
        D1["OBS Studio / Spout2 / NDI"]
        D2["WebGL / Browser Canvas"]
        D3["Game Engine (Unity / Godot)"]
    end

    A1 --> B1
    A2 --> B2
    A3 --> B3

    B1 --> C1
    B2 --> C1
    B3 --> C1

    C1 --> C2 --> C3
    C3 --> D1
    C3 --> D2
    C3 --> D3
```

---

## 🤝 How to Contribute

Contributions are warmly welcomed! Help expand this ecosystem by submitting high-quality open-source tools, runtimes, and tracking pipelines.

1. 🍴 **Fork the repository** on GitHub.
2. 🌿 **Create a new branch**: `git checkout -b feature/add-new-animation-tool`.
3. 📝 **Add your entry** to `README.md`:
   - Follow the established formatting conventions (alphabetical or star/revenue sorted).
   - Ensure specific pricing and free tier/trial limits for SaaS entries.
   - For open-source tools, include the standard stargazer social badge format.
4. 🚀 **Commit your changes**: `git commit -m "feat: add NewTool to open-source section"`.
5. 📤 **Submit a Pull Request** with a concise description of why the tool is beneficial to the real-time 2D animation community.

---

## 💖 Support & Community

If this curated repository saved you hours of research or assisted your VTuber / 2D animation pipeline, please consider supporting the project!

- ⭐ **Star this repository** to help other creators, animators, and developers discover it.
- 🍴 **Fork and share** with your local animation communities, streaming groups, and discords.
- ☕ **Sponsor the Maintainer**: Support ongoing curation, open-source tooling, and maintenance via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Real-Time-2D-Character-Animation&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Real-Time-2D-Character-Animation&type=date&legend=top-left)

---

## 📜 Disclaimer & License

- **Disclaimer**: This compilation is community-curated for informational, educational, and developer reference purposes. Product names, trademarks, and logos belong to their respective copyright holders. Listed pricing and tiers reflect publicly available rates as of 2026.
- **License**: Distributed under the [MIT License](LICENSE). Listed open-source projects maintain their own respective licenses (BSD, GPL, Apache, MIT).

---

<p align="center">
  <b>Built with ❤️ for VTubers, Animators, Riggers, and Open-Source Developers worldwide.</b>
</p>
