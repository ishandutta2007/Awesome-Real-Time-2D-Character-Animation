# Awesome-Real-Time-2D-Character-Animation

# Top Real-Time 2D Character Animation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Live Puppeteering, Webcam Motion Capture & Self-Hosted Rigging Pipelines*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Real-Time 2D Character Animation**. These tools bring illustrated characters to life by mapping live input — webcam, microphone, or manual controls — onto rigged 2D artwork, enabling VTubing, live streaming, interactive presentations, and rapid animation prototyping.

**Examples** include Inochi2D, ChibiRigKit, OpenToonz, Synfig Studio, and Adobe Character Animator (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, browser-native rigging, and transparent puppet standards — ideal for VTubers, indie animators, and developers who want real-time 2D animation without subscription fees or proprietary file formats.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Adobe Character Animator** — **The reference commercial real-time puppeteering tool.** Uses webcam and microphone input to drive a 2D puppet's facial expressions, lip sync, and body movement with no keyframing required [citation:1]. **Included with Creative Cloud subscriptions.** **Best for Adobe users** wanting the most polished live puppeteering experience with deep integration into Premiere Pro and After Effects, accepting cloud dependency and subscription cost.

- **Toon Boom Harmony** — **The studio-grade 2D animation standard.** Professional cutout and traditional animation with rigging, deformation, and real-time preview. **Subscription or perpetual licensing** at premium pricing. **Best for professional studios** producing broadcast-quality 2D animation where Harmony's rigging depth and pipeline integrations are non-negotiable.

- **Live2D Cubism** — **The VTuber rigging standard.** Deforms layered 2D art with mesh warping and parameter-driven animation for real-time facial tracking. **Free for non-commercial use; paid tiers for commercial deployment.** **Best for VTubers and game developers** wanting the most widely supported 2D puppet format with extensive tracking software compatibility.

- **Reallusion Cartoon Animator** — **The accessible 2D animation suite with real-time puppeteering.** 2D bone rigging, facial capture, and motion library for indie animators. **One-time purchase** with optional pipeline add-ons. **Best for indie animators** wanting a middle ground between Character Animator's live capture and Harmony's studio tooling.

## Open-Source GitHub Projects

- **Inochi2D** — **The reference open-source 2D puppet animation standard.** BSD 2-Clause licensed, **1,420+ GitHub stars** [citation:6]. **A toolkit and ecosystem for real-time 2D puppet animation** for game development, virtual avatars, and multimedia applications [citation:9]. **Works by deforming 2D meshes created from layered art at runtime based on parameters**, creating the illusion of 3D depth and movement in 2D artwork . **Two official tools**: **Inochi Creator** for rigging layered 2D art via warping meshes, physics, dynamic masking, and real-time lighting, and **Inochi Session** for livestreaming and teleconferencing by mapping external tracking data to a puppet's rigging [citation:9]. **The reference implementation requires OpenGL 3.1** and is written in D . **Alternative implementations**: **inochi2d-c** for non-D languages, and **Inox2D** (pure Rust implementation of the spec) . **Funded by NLnet's NGI0 Entrust program** with plans for Inochi2D 0.9 making it viable in Godot, Unity, and the web via WASM/WebGL/WebGPU [citation:9]. **Best for VTubers, game developers, and riggers** wanting an open standard for 2D puppets without restrictive licensing, accepting that the ecosystem is still maturing and documentation is being written [citation:10].

- **ChibiRigKit** — **The browser-based single-image to 2D character toolkit.** **Beta-stage, open-source** [citation:2]. **Takes a single PNG illustration and automates the tedious parts of rigging** — generating parts and variants for eyes, mouth, hair, and body [citation:2]. **Real-time tracking**: camera-based face tracking and microphone-driven lip sync [citation:2]. **Manual animation**: blinking, gaze, head yaw/pitch/roll, hair and clothing sway with simple physics for long hair [citation:2]. **Recording and export**: record and replay custom motions, WebM recording, and export finished characters as HTML + ZIP [citation:2]. **OBS integration**: real-time reflection into OBS Browser Source on the same machine without transmitting camera or microphone data to the server — the server binds only to `127.0.0.1` [citation:2]. **Requirements**: Python 3.12+, Node.js 22+, Chrome/Chromium, and Codex CLI for automatic rigging (not needed for playback or tracking) [citation:2]. **Best for VTubers and streamers** wanting a quick path from a single illustration to a live, trackable character in the browser, accepting that it is still beta [citation:2].

- **OpenToonz** — **The studio-grade open-source animation suite.** BSD-3-Clause licensed, the open-source descendant of Toonz — the software Studio Ghibli used to develop [citation:8]. **Vector and raster workflows, effects, particles, motion tracking, and a scripting layer** [citation:8]. **The most powerful free 2D animation tool** for serious animators, but **the learning curve has surprised generations of new users** — the UI is idiosyncratic and documentation is scattered [citation:8]. **Best for serious animators on a zero budget** willing to invest in learning a studio-grade toolset [citation:8].

- **Synfig Studio** — **The open-source 2D vector animation suite.** GPL-licensed, **industrial-grade 2D vector animation software** [citation:4]. **Eliminates the need for frame-by-frame animation** through vector tweening, with a **bone system** for character rigging, **multiple layer types** (geometry, gradients, filters, distortions, transformations, fractals), and **parameter linking via mathematical expressions** [citation:4]. **Supports spatial and temporal resolution independence, HDRI, and a plugin system** [citation:4]. **Available on Windows, Linux, and macOS**, with version 1.5.3 current as of December 2025 [citation:4]. **Best for 2D animation and motion graphics** (explainers, character animation) where vector tweening and bones matter, accepting that real-time live puppeteering is not its primary focus [citation:4].

### Additional Strong Open-Source Options

- **Pencil2D** — **The beginner-friendly hand-drawn animation app.** GPL-2.0 licensed, **designed with "no learning curve" as its principle** [citation:8]. **Bitmap and vector layers, onion skinning, and a simple timeline** [citation:8]. **Feature ceiling is low** — no cutout rigs, no effects, no real-time tracking [citation:8]. **Best for teaching animation fundamentals in an afternoon** [citation:8].
- **Krita** — **The free painting app with a growing animation timeline.** GPL-3.0 licensed, **exceptional brush engine with onion skinning** and export to PNG sequences or MP4 [citation:8]. **Not a rig-based real-time tool** — its timeline suits short sequences rather than live puppeteering [citation:8]. **Best for animators who also paint** and want a capable free tool for hand-drawn frame-by-frame work [citation:8].
- **Glaxnimate** — **The simple vector animation tool with real-time preview.** GPL-3.0 licensed, **available on Linux, macOS, Windows, and FreeBSD** . **Best for simple vector animation** where a lightweight tool suffices.

**Frameworks for building custom systems**: Combine **Inochi2D** for an open-standard 2D puppet pipeline with planned game engine and web support, **ChibiRigKit** for single-image to live browser character in minutes, **OpenToonz** for studio-grade traditional and cutout animation, **Synfig Studio** for vector tweening and bone rigging, and **Krita** or **Pencil2D** for hand-drawn frame-by-frame work — to build a real-time 2D animation stack tailored to your need for live puppeteering versus traditional animation, and browser-native versus desktop deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Real-time 2D character animation tools differ significantly in rigging model, tracking capability, and deployment platform. **Adobe Character Animator is the most polished commercial live-puppeteering tool** [citation:1], but requires a Creative Cloud subscription. **Inochi2D is the reference open-source 2D puppet standard** with Inochi Creator and Inochi Session, but its documentation is still being written and the ecosystem is maturing [citation:9][citation:10]. **ChibiRigKit is beta-stage** — it works but is still evolving [citation:2]. **OpenToonz and Synfig are traditional animation tools**, not real-time live puppeteering platforms — they excel at frame-by-frame and vector tweening respectively, but do not map webcam input to a puppet in real time [citation:4][citation:8]. **Pencil2D and Krita are frame-by-frame animation tools**, not rig-based real-time systems [citation:8].
- Self-hosted open-source solutions require proper GPU drivers (OpenGL 3.1 for Inochi2D), Python/Node.js runtime for ChibiRigKit, and awareness that webcam-based tracking quality depends on lighting and camera hardware.

---

**Made for VTubers, indie animators, and developers choosing real-time 2D animation tools they can own and control.**
Let's make real-time 2D character animation more open, standard-driven, and live-trackable.
