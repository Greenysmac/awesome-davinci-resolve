# Awesome DaVinci Resolve [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) plugins, tools, and resources.

Community-curated by [/r/colorists](https://reddit.com/r/colorists) and [/r/davinciresolve](https://reddit.com/r/davinciresolve).

## How entries are chosen

For GitHub-hosted tools, we include a repository if it has **10 or more stars**, or **at least 2 stars and activity within roughly the last two years**. Community submissions (via the form or a pull request) are always included regardless of stars. Non-GitHub resources (vendor sites, stores) are judged on relevance rather than stars.

If a tool isn't listed yet, it hasn't been rejected on merit — it may simply be below this threshold for now and will be reconsidered on a future pass. Please still submit it; maintainer discretion always wins over the automatic threshold. Star counts and "updated" notes reflect the most recent sync and will drift over time.

## Contents

- [AI & Automation Tools](#ai-automation-tools)
- [Audio Plugins](#audio-plugins)
- [DCTLs](#dctls)
- [OFX/Video Effects & VFX Suites](#ofx-video-effects-vfx-suites)
- [Templates, Macros, & Scripts](#templates-macros-scripts)
- [Workflow & Integration Tools](#workflow-integration-tools)
- [Subtitles & Captions](#subtitles-captions)
- [Gen Media](#gen-media)
- [Linux](#linux)
- [Hardware & Control Surfaces](#hardware-control-surfaces)
- [Database & Project Server Tools](#database-project-server-tools)
- [Development Resources](#development-resources)
- [Community Attribution](#community-attribution)
- [Contributing](#contributing)

## AI & Automation Tools

*AI-powered tools for automating editing, captions, and footage search.*

- [arkiv](https://github.com/vulture-s/arkiv) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Open-source AI metadata layer with semantic footage search (English, Chinese, Japanese) and a DaVinci Resolve plugin: import clips with rating-based color (GOOD/NG/Review) and drop frame markers from search hits. ExifTool integration; 100% local, MIT licensed. *(by vulture-s)* `macOS, Windows, Linux` <sub>(⭐ 71 · updated 2026-09)</sub>
- [AutoCut](https://www.autocut.com/en) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Automates captions, adds zooms, B-roll matching, removes silences/repetitions. Auto-edits podcasts.
- [BadWords](https://github.com/veritus-git/BadWords) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Free, offline text-based editing plugin for DaVinci Resolve. Transcribes audio with verbatim accuracy to catch stutters, compares your recording against your written script to highlight retakes and bloopers, and automatically cuts silence to build a clean timeline with one click. *(by Szymon Wolarz aka veritus)* `macOS, Windows, Linux` <sub>(⭐ 31 · updated 2026-09-06)</sub>
- [FireCut](https://firecut.ai/pricing/davinci-resolve) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Great list! FireCut launched a free tier last week :) https://firecut.ai/pricing/davinci-resolve/ `macOS, Windows, Linux` `20+`
- [Jumper](https://getjumper.io) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — AI-based search tool for project footage to find specific visual moment or spoken word.
- [metafootage](https://github.com/WDegan/metafootage-davinci-resolve) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — Generate footage keywords and descriptions using Gemini or OpenAI. Selected frames are sent to the provider; API usage may cost extra. *(by WDegan)* `macOS, Windows, Linux` <sub>(⭐ 4 · updated 2026-02)</sub>
- [StoryToolkit AI](https://github.com/octimot/StoryToolkitAI) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Transcripts/translations powered by NVIDIA+AI. Similar to ScriptSync for Avid. *(by octimot)*
- [Tagger for Resolve](https://tagger.mov) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Tagger is a AI powered keyword generator that makes your footage searchable via smart bins. *(by Paco Higham)* `macOS` `19`

## Audio Plugins

*VST/AU audio plugins for mixing, mastering, noise reduction, and effects.*

- [Alex Audio Butler](https://alexaudiobutler.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Automated mixing/mastering. Popular for web content creators.
- [Auburn Sounds](https://www.auburnsounds.com/index.html) ![Offers free](https://img.shields.io/badge/Cost-Offers%20free-blue) — Gates, dynamics, voice modulation, and spatialization. Cross-platform; offers free versions.
- [GPU Audio](https://www.gpu.audio) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Startup offering GPU-accelerated Audio plugins.
- [igorski.nl](https://www.igorski.nl/download) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — More music-based, but does offer some effects and reverbs.
- [iZotope (RX suite)](https://www.izotope.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — RX suite is an industry standard for noise reduction. Other audio effects available. *(by iZotope)*
- [kiloHearts](https://kilohearts.com/download) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Full of useful plugins (EQ, Gain, Compressor,...) with a friendly UI, the essential is free, what is showcased as Paid is mostly for music producers *(by KiloHearts AB)* `macOS, Windows` `Any`
- [Native Instruments](https://www.native-instruments.com/en) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — More for music production and synths. Other audio effects available.
- [TBProAudio](https://www.tbproaudio.de) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — EQs, Meters, and limiters.
- [Valhalla DSP](https://valhalladsp.com/plugins) ![Some free](https://img.shields.io/badge/Cost-Some%20free-blue) — Various reverb plugins. Some free, some paid.
- [Various Free Plugins](https://archlinux.org/groups/x86_64/vst-plugins) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Reverbs, synths, and more (Suggested by /u/solonovamax). *(by u/solonovamax)*
- [ViatorDSP](https://www.patreon.com/ViatorDSP/posts) ![Many free](https://img.shields.io/badge/Cost-Many%20free-blue) — Lo-Fi/EQ Plugins. Many available for free.
- [Waves](https://www.waves.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — EQs, compressors, cleanup tools, reverbs, meters.

## DCTLs

*DaVinci Color Transform Language plugins for color science and grading.*

- [AgX-Resolve](https://github.com/sobotka/AgX-Resolve) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — AgX picture-formation / display transform for Resolve (not a film-look LUT). *(by sobotka)* <sub>(⭐ 110 · updated 2025-09)</sub>
- [Asim Siddiqui/XtremeStuff](https://github.com/xtremestuff/resolve-dctl) ![Free/shareware](https://img.shields.io/badge/Cost-Free%2Fshareware-brightgreen) — DCTL provider. *(by Asim Siddiqui)*
- [Baldavenger DCTLs](https://github.com/baldavenger) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Free, open source DCTLs related to color science. *(by Paul Dore / Baldavenger)*
- [CinePrint35](https://www.tombolles.net/cineprint35) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Film-emulation PowerGrades with native Resolve nodes. Free Resolve can use grades with the Studio-only Grain node disabled. *(by Tom Bolles)* `macOS, Windows`
- [Colorist Foundry Filmverse](https://coloristfoundry.com/store) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider.
- [DCTL (2499 DRT & Fuses)](https://github.com/JuanPabloZambrano/DCTL) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Creative and technical DCTLs and Fusion Fuses, including the 2499 display rendering transform. *(by JuanPabloZambrano)* `macOS, Windows` <sub>(⭐ 320 · updated 2025-11)</sub>
- [DCTL (diagnostics)](https://github.com/caryknoop/DCTL) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Diagnostic tools for marking and analyzing image changes through nodes. *(by caryknoop)* <sub>(⭐ 30 · updated 2025)</sub>
- [DCTL-MLAA](https://github.com/olduvai-jp/DCTL-MLAA) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Morphological anti-aliasing in DCTL and Fuse forms. *(by olduvai-jp)* `macOS, Windows` <sub>(⭐ 13 · updated 2026-03)</sub>
- [dctl-utils](https://github.com/ra100/dctl-utils) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Skin-tone indicator DCTL with hue, saturation, and luminance tolerances. *(by ra100)* <sub>(⭐ 19 · updated 2024)</sub>
- [DELUTS Universe DCTLs](https://jamesmiller.sellfy.store/p/davinci-resolve-studio-dctl) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Studio DCTL collection for color, lens effects, film texture, and utilities. Test the demo for GPU compatibility. *(by James Miller)* `macOS, Windows, Linux` `Studio`
- [Faded-Balancer-DCTL](https://github.com/fabiocolor/Faded-Balancer-DCTL) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Rebalances faded film scans. *(by fabiocolor)* `macOS, Windows` <sub>(⭐ 22 · updated 2026-08)</sub>
- [gamut-compress](https://github.com/jedypod/gamut-compress) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Out-of-gamut color handling; includes DCTL and Fusion implementations. *(by jedypod)* <sub>(⭐ 110 · updated 2022)</sub>
- [Henry Bobeck (UltimateSaturation)](https://henrybobeck.com/dctl/UltimateSaturation) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider. *(by Henry Bobeck)*
- [Henry Bobeck DCTLs](https://henrybobeck.com/dctl) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — The current list links to one specific DCTL by Henry Bobeck, I'm just suggesting to link to the main page instead for full context :) *(by Henry Bobeck)* `macOS, Windows, Linux` `19.1+`
- [HotGlueBanjo](https://github.com/hotgluebanjo) ![Free/shareware](https://img.shields.io/badge/Cost-Free%2Fshareware-brightgreen) — DCTL provider.
- [Iridescent Color](https://iridescentcolor.com/shop) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider.
- [Jed Smith](https://github.com/jedypod) ![Free/shareware](https://img.shields.io/badge/Cost-Free%2Fshareware-brightgreen) — DCTL provider.
- [Kaur Hendrikson](https://store.kaurh.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider. Noted as "excellent". Has demo/trial versions available.
- [LCS-DCTLs](https://github.com/LCS-VSP/LCS-DCTLs) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Creative color-science DCTL collection. *(by LCS-VSP)* <sub>(⭐ 23 · updated 2024)</sub>
- [LUT Tuner](https://cutpointlabs.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — A focused .cube LUT editor for manually adjusting the LUT response curve. Can also convert a LUT into a tunable DCTL approximation for Resolve, with fit metrics (mean, p95, max RMSE) and export of the .cube LUT, the DCTL, or both. *(by Cutpoint Labs LLC)* `macOS` `21`
- [Moaz Elgabry](https://github.com/MoazElgabry/DCTLs) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Look development and grading tools for resolve (Filmic contrast, Ratio shaper, Localized contrast, hue curve) *(by Moaz Elgabry)* `macOS, Windows, Linux`
- [Mononodes](https://mononodes.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — "Awesome DCTL's and Plugins" including Film Emulations, Hue Twist, and Utility DCTLS. Noted as "excellent".
- [NamiColor](https://github.com/Wavechaser/NamiColor) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Linearizes film scans and aligns channels for scene-referred grading. Studio required. *(by Wavechaser)* `macOS, Windows` <sub>(⭐ 122 · updated 2024)</sub>
- [Nx Color](https://nxcolor.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL Tools including ChromaDrift, Liquid Glass, CanvasFlow, and ShadowCast (Realtime 2D GI).
- [open-display-transform](https://github.com/jedypod/open-display-transform) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Scene-linear, wide-gamut image rendering for SDR/HDR (OpenDRT); includes Resolve Studio DCTLs. *(by jedypod)* <sub>(⭐ 517 · updated 2026-03)</sub>
- [photographic-dctls](https://github.com/mikaelsundell/photographic-dctls) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Photographic color-science experiments: LogC, Cineon, negative inversion, and tone/color transforms. *(by mikaelsundell)* `macOS, Windows` <sub>(⭐ 78 · updated 2026-06)</sub>
- [PixelTools](https://pixeltoolspost.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL plugins and PowerGrade presets. Noted as "excellent". Has demo/trial versions available. *(by u/jbowdach)*
- [protune-transforms](https://github.com/xtremestuff/protune-transforms) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — GoPro Protune and GP-Log transforms for managed color workflows. *(by xtremestuff)* `macOS, Windows, Linux, iPadOS` <sub>(⭐ 176 · updated 2026-06)</sub>
- [Ravengrade](https://ravengrade.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider.
- [Ravi Shankar DCTLs](https://store.ravishankar.xyz) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider. *(by Ravi Shankar)*
- [RenderHub DCTLs](https://github.com/Senthil360/RenderHub-DCTLs) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — A collection of DCTLs to help with contrast shaping, hue adjustments, and look development. *(by Senthil Manikandan)* `macOS, Windows, Linux`
- [resolve_DCTLs](https://github.com/mitkunz/resolve_DCTLs) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Grading DCTLs including Technicolor-style RGB mixing, film saturation, adjustable grey cards, and letterboxing. GPL-3.0. *(by mitkunz)* <sub>(⭐ 21 · updated 2025)</sub>
- [Salamifish](https://salamifish.com/demos) ![Offers Demos](https://img.shields.io/badge/Cost-Offers%20Demos-orange) — DCTL provider.
- [Sven Hegen](https://svenhegen.com/dctls) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider.
- [Tetra-DCTLOFX](https://github.com/npeason/Tetra-DCTLOFX) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Tetrahedral color manipulation through Resolve's DCTL effect interface. *(by npeason)* <sub>(⭐ 197 · updated 2021)</sub>
- [Thatcher Freeman](https://github.com/thatcherfreeman/utility-dctls) ![Free/shareware](https://img.shields.io/badge/Cost-Free%2Fshareware-brightgreen) — Utility DCTL provider. Noted as "excellent". Has demo/trial versions available. <sub>(⭐ 412 · updated 2026-09)</sub>
- [V-Log-Alchemy](https://github.com/shenmintao/V-Log-Alchemy) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Film-look and color tools aimed at Panasonic V-Log footage. *(by shenmintao)* <sub>(⭐ 357 · updated 2026-08)</sub>

## OFX/Video Effects & VFX Suites

*OpenFX plugins for visual effects, film emulation, grain, diffusion, and color.*

- [AE Fusion 3D Bridge](https://aescripts.com/ae-fusion-3d-bridge) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Transfers supported 3D layouts, cameras, and baked animation between After Effects and Fusion/Resolve. *(by aescripts)* `macOS, Windows` <sub>(updated 2026-08)</sub>
- [Akascape](https://www.akascape.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Trendy visual effect plugins and Fuses. Paid Gumroad catalog (Pixelsorting, Datamosh, Rutt Etra, VHS, Glitch, SupaScale AI upscaler, SuperModulation, SuperPolygons, and more). Also maintains free open-source Fuses on GitHub (Rembg, RemObj, Style Transfer) listed separately.
- [Amalgam](https://aescripts.com/amalgam) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Frequency-based image blending OFX. Compatibility lists Resolve 16-21; macOS confirmed. *(by aescripts)* `macOS` `16-21` <sub>(updated 2026-09)</sub>
- [Anchor Point Corners](https://github.com/neezr/Anchor-Point-Corners-for-DaVinci-Resolve) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Set Fusion anchor points to corners and edges. Studio. *(by neezr)* `macOS, Windows, Linux` <sub>(⭐ 6 · updated 2026-05)</sub>
- [Auto-Rename for DaVinci Resolve](https://github.com/neezr/Auto-Rename-for-DaVinci-Resolve) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Auto-rename Fusion MediaIn, Background, Text, and MultiMerge nodes based on their contents. *(by neezr)* `macOS, Windows, Linux` <sub>(⭐ 17 · updated 2026-05)</sub>
- [BaldavengerPlugins](https://github.com/baldavenger/BaldavengerPlugins) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — OpenFX image-processing and grading plugins. *(by baldavenger)* `macOS, Windows, Linux` <sub>(⭐ 148 · updated 2020)</sub>
- [Blewtoof](https://blewtoof.mov) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Effects plugins including CRT Machine, Mixed Media, Camcorder, and Superchrome.
- [boilify](https://github.com/Microck/boilify) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Line-boil OpenFX effect for hand-drawn jitter. Resolve Studio 20+. *(by Microck)* `macOS, Windows, Linux` `20+` <sub>(⭐ 8 · updated 2026-08)</sub>
- [Boris FX (Continuum/Sapphire)](https://borisfx.com/products/continuum) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Industry standard suite for VFX, color, and effects. *(by Boris FX)*
- [Boris FX SynthEyes](https://borisfx.com/products/syntheyes) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Camera/object tracking and matchmoving with Fusion/Resolve scene export. Standalone pipeline companion. *(by Boris FX)* `macOS, Windows, Linux` <sub>(updated 2026-05)</sub>
- [CineMatch](https://www.cinematch.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Camera matching plugin made by FilmConvert. *(by FilmConvert)*
- [Colourlab.ai (Look Designer)](https://www.colourlab.ai) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Look creators, grain, and AI grading. Used for color correction and film emulation.
- [Contour lookdev](https://procolor.ist/contour-official) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Look development tool.
- [CorridorKey-Runtime](https://github.com/alexandremendoncaalvaro/CorridorKey-Runtime) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Native AI keying runtime and OFX plugin for DaVinci Resolve. Built in collaboration with Corridor Digital; supports Windows (NVIDIA RTX) and macOS (Apple Silicon). *(by Alexandre Alvaro)* `macOS, Windows` `20` <sub>(⭐ 745 · updated 2026-08)</sub>
- [davinci-shortform-overlays](https://github.com/Creative-Crafter/davinci-shortform-overlays) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Fusion generator with switchable TikTok, Shorts, and Reels safe-zone overlays; distributed as a .drfx template. *(by Creative-Crafter)* `macOS, Windows, Linux` <sub>(⭐ 5 · updated 2026-08)</sub>
- [Dec18 Plugin Manager](https://github.com/Dec18studios/Dec18-Plugin-Manager) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — Plugin download/update manager with hash checks and backups; individual plugins have separate licenses. *(by Dec18studios)* `macOS, Windows, Linux` <sub>(⭐ 6 · updated 2026-08)</sub>
- [Dehancer Pro](https://www.dehancer.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Specialized grain and film emulation.
- [Digital Anarchy (Beauty Box)](http://www.digitalanarchy.com/beautyVID/main.html) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Beauty and deflicker effects. Beautybox is highly recommended. *(by Digital Anarchy)*
- [DMC-BaldavengerOFX (macOS arm64)](https://github.com/Demystify-Color/DMC-BaldavengerOFX-MacOSarm64) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Baldavenger OpenFX collection rebuilt as macOS universal binaries. *(by Demystify-Color)* `macOS` <sub>(⭐ 13 · updated 2026)</sub>
- [Film Convert (Nitrate)](http://www.filmconvert.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Film emulation and grain.
- [Filmworkz](https://filmworkz.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Restoration tools from Digital Vision. *(by Digital Vision)*
- [framechart](https://framechart.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — OFX plugin that generates animated charts (line, bar, race charts, and more) from .csv data files. *(by DonData)*
- [FuAlign](https://github.com/brunocbreis/FuAlign) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Align and distribute visual elements in Fusion compositions. *(by brunocbreis)* `macOS, Windows` <sub>(⭐ 33 · updated 2021)</sub>
- [FXHome Ignite Pro](https://hitfilm.com/ignite-pro) ![Discontinued](https://img.shields.io/badge/Cost-Discontinued-lightgrey) — VFX and color suite. (Note: DISCONTINUED).
- [Gaussian Splatting for DaVinci Resolve](https://aescripts.com/gaussian-splatting-for-davinci-resolve) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Import, manipulate, and GPU-render Gaussian-splat PLY scenes, including depth output. Resolve 18-21. *(by aescripts)* `18-21` <sub>(updated 2026-02)</sub>
- [Genesis film emulation](https://procolor.ist/genesis) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Film emulation tool.
- [Greyscale Labs (Nano, Serum, Scalar)](https://greyscalelabs.com/nano) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Nano (Diffusion), Serum (Skin Refinement), and Scalar (Color-Control/uprez/debanding). *(by Greyscale Labs)*
- [gyroflow-plugins](https://github.com/gyroflow/gyroflow-plugins) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Gyro-data-driven stabilization via OpenFX and other plugin formats (the OFX plugin form of Gyroflow). *(by gyroflow)* `macOS, Windows, Linux` <sub>(⭐ 122 · updated 2026-09)</sub>
- [Hazy digital diffusion](https://www.filmconvert.com/plugin/hazy) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Diffusion plugin.
- [Invizipro film grain](https://www.invizipro.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Film grain tool.
- [Kromatika DigiDiff diffusion](https://www.kromatica.co/pages/digidiff) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Diffusion plugin.
- [lenscorrect-ofx](https://github.com/murtazatunio/lenscorrect-ofx) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Lensfun/DNG-based lens distortion, vignetting, and lateral chromatic-aberration correction OpenFX. *(by murtazatunio)* `macOS` <sub>(⭐ 9 · updated 2026-08)</sub>
- [Livegrain](http://www.live-grain.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — High-end film grain. Noted as expensive, but used in Hollywood.
- [Maxon (Red Giant Universe)](https://www.redgiant.com/universe) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — VFX and effects suite. *(by Maxon)*
- [Neat Video NR](http://www.neatvideo.com/overview.html) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Industry standard video noise reduction.
- [NewBlue](https://www.newbluefx.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Mostly for titling, but some other tools. Common for AVID systems.
- **NodeMill LensNode** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Lens Simulations.
- [NTSC-RS](https://ntsc.rs) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Provides a VHS Effect in OpenFX. <sub>(⭐ 2552 · updated 2026-09)</sub>
- [purzos-ofx](https://github.com/purzbeats/purzos-ofx) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Purzos collection of retro, analog, glitch, CRT, and VHS OpenFX effects. MIT. *(by purzbeats)* `macOS, Windows, Linux` <sub>(⭐ 23 · updated 2026-08)</sub>
- [QR-coder](https://github.com/nikita-petrovich/OFX-QRCoder) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Generate QR codes right in DaVinci Resolve or other OpenFX compatible software. *(by nikita-petrovich)* `macOS`
- [RE:vision Effects](https://revisionfx.com/products/for/resolve) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Includes Twixtor (for speed warps) and ReelSmart Motion Blur.
- [Rembg-Fuse](https://github.com/Akascape/Rembg-Fuse) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — AI background removal inside Fusion using external Python/model dependencies. *(by Akascape)* <sub>(⭐ 208 · updated 2026-07)</sub>
- [RemObj-Fuse](https://github.com/Akascape/RemObj-Fuse) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Masked object removal / inpainting using LaMa. Supports Free and Studio. *(by Akascape)* <sub>(⭐ 20 · updated 2026-07)</sub>
- [RetouchForMe](https://retouch4.me/videoretouching) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Beauty effects.
- [Reverator film emulation](https://www.reverator.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Film emulation tool.
- [Shaderfuse](https://github.com/nmbr73/Shaderfuse) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Shadertoy-style GPU shaders converted into Fusion Fuses. *(by nmbr73)* `macOS, Windows` <sub>(⭐ 78 · updated 2026-09)</sub>
- [Simple LUT Generator](https://github.com/Lo1s-pgn/Simple-LUT-Generator) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — LUT generator that runs in the Color page of DaVinci Resolve. Automatically adapts to the resolution of your source to generate the largest grid possible. Useful for DITs or colorists exporting an in-camera LUT on set. *(by Loïs Plagnard)* `macOS, Windows, Linux`
- [spektrafilm OFX](https://spektrafilm.114c.de) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Beta spectral film-emulation OFX with negative, print, and scan stages. Install requires Resolve Studio. *(by spektrafilm)* `macOS, Windows, Linux` `Studio` <sub>(updated 2026-09)</sub>
- [Super-Style-Transfer-Fuse](https://github.com/Akascape/Super-Style-Transfer-Fuse) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Neural artistic style transfer inside Fusion. *(by Akascape)* <sub>(⭐ 3 · updated 2026-08)</sub>
- [Tangenten](https://tangenten.gumroad.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Motion graphics and character animation tools: Puppet Pin, physics simulation, generative fill, and more. *(by Tangenten)* `macOS, Windows, Linux`
- [Tetrahedral Interpolation for Fusion](https://github.com/EmberLightVFX/Tetrahedral-Interpolation-for-Fusion) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Fusion implementation of tetrahedral color manipulation. *(by EmberLightVFX)* `macOS, Windows, Linux` <sub>(⭐ 32 · updated 2020)</sub>
- [Textuler](https://textuler.io/features) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Ultimate plugin for creating chat & text bubbles, advanced text, and UI elements.
- **TimeInPixel (Nobe tools)** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Color Assistance Tools: Nobe OmniScope, Nobe Display, False Color Nobe.
- [VideoVillage (Filmbox/Scatter)](https://videovillage.co/filmbox) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — FilmBox (Film Emulation) and Scatter (Diffusion). Also makes Lattice (LUT builder). *(by VideoVillage)* `macOS only`

## Templates, Macros, & Scripts

*Ready-made templates, Fusion macros, scripts, and preset packs.*

- [AEScripts (BeatEdit / ShotList Creator)](https://aescripts.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Offers scripts like BeatEdit for rhythm and ShotList Creator. *(by AEScripts)*
- **Art3studios** ![Some free](https://img.shields.io/badge/Cost-Some%20free-blue) — Offers "some nice free preset things with titles".
- [Chris Boustedt](https://www.chrisboustedt.com/products/chriss-boustedts-edit-like-tom-noske-asset-pack) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Clean preset packs for simple animations (e.g., The Minimal Preset Pack). *(by Chris Boustedt)*
- **DrFusion MotionCurves PRO Script** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Script/macro tool. *(by DrFusion)*
- [Editors Lab](https://editorslab.store) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Creative hub for presets and plugins (e.g., AuthenticVHS, Motion Sweet).
- [EditorScripts](https://github.com/oliwiergesla/editorscripts) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — A free, open-source toolkit of Lua scripts for DaVinci Resolve Studio 20+ that streamline workflows for editors and colourists. *(by Oliwier Gesla)* `macOS, Windows` `Resolve Studio 20+`
- [Essentials Preset Pack](https://gregeditsvideo.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — 21 DaVinci Resolve presets for saving time editing *(by Greg Edits Video)* `macOS, Windows, Linux` `18.5`
- [European Filmmaker (Asset Blaster)](https://www.europeanfilmmaker.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Asset Blaster transforms assets, animates titles, and adds visual effects. *(by European Filmmaker)*
- **Jayaretv** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Templates & Tools provider.
- [Map Engine](https://davincikit.com/product/map-engine) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Lua Map Animation script for Fusion; similar to GeoLayers. Supports Geo Shapes through GeoJSONs, custom Map Styles, OpenStreetMap-powered location search and map routing and more. *(by Kai Engels)* `macOS, Windows` `18.6+`
- [Marker Madness Suite](https://resolve-tools.com) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Marker utility: browse, filter, batch rename, recolor, nudge, promote, and copy markers across timelines and projects. Exports CSV shot lists with thumbnails, generates shot-change reports, and exchanges markers with Premiere Pro and Avid Media Composer. *(by resolve-tools)* `macOS, Windows, Linux` `21+`
- [Meta Fide](https://www.metafide.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Various scripts and Fusion tools, including project setup and ASCII converters.
- **Motion VFX** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — High-quality, native Resolve templates and packs (e.g., McamRig).
- [MrAlexTech (Magic Suite)](https://www.mralextech.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Creator offering tools like MagicAnimate, Magic Subtitle, and MagicZoomPro. *(by MrAlexTech)*
- [MrJustinEdits](https://mrjustinedits.com/en-gbp) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Offers effects like Paper Animator Pro v2 and Easy Camera Shake. *(by MrJustinEdits)*
- [MultiFrame for DaVinci Resolve](https://iamkoltunov.gumroad.com/l/multiframe-for-davinci-resolve) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — Lua/Fusion script that turns 2-50 selected Media Pool items into editable multi-image layouts (grids, stacked, hero, focus, editorial, and more). Generates an editable Fusion node graph with layout and animation controls in the Edit page Inspector. Free edition supported; free Trial covers 2-3 items. *(by iamkoltunov)* `macOS, Windows` `21+ (Free or Studio)`
- [NeoEditFX](https://neoeditfx.com) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — Plugin and preset packs for the Edit page: keyframe-free text animation and titles, stylized caption presets, effects plugins, motion tools (zoom, shake, facecam), and an animated text highlighter. Works in Free and Studio. Includes a free Starter Pack. *(by Victor Grubbe)* `macOS, Windows` `20+`
- [Orson Lord (Snap Captions)](https://orsonlord.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Captions with animations and templates. *(by Orson Lord)*
- [PeeJ](https://peejent-shop.fourthwall.com/en-gbp) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Full of Tools, Title Packs, Macros etc.
- [Puppet Pin Tool](https://tangenten.gumroad.com/l/PuppetPinTool) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — This is a fuse script i made for the davinci fusion page that mimics the 'puppet pin' effect found in adobe after effects and other programs. Also works as a rigging and animation tool for 2d characters using inverse and forward kinematic joints. Great for animating images in a natural way without awkward distortions. *(by Tangenten (https://tangenten.gumroad.com/))* `macOS, Windows, Linux` `20+ (Free or Studio)`
- **Ryan Osborne** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Creator found on buymeacoffee.
- [StirlingSupplyCo](https://stirlingsupply.co/en-gbp/collections/plugins-and-presets) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Repository of Tools and effects, including EASY Locked-On Stabilization and Master Tracker.
- [Sualvi](https://store.sualvi.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Various Micro Tools and Effects.
- [TheResolve.Store](https://theresolve.store/#) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Offers asset packs including RESOLVEX Transitions and KINETICX Titles.
- **VideoHive/Envato Market** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Extensive collection of macros, editable titles, and plugins for common trendy effects.
- [WeSuckLess Reactor 3 for Fusion](https://www.steakunderwater.com/wesuckless/viewforum.php?f=32) ![Free/donation](https://img.shields.io/badge/Cost-Free%2Fdonation-brightgreen) — Package manager for Fusion tools and macros. Free to install, suggested donation for some tools.
- [X-Session](https://www.xsession.shop/home) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Pro-Grade Presets (e.g., Auto SFX, Motion Sweet).

## Workflow & Integration Tools

*Encoder plugins, MAM/PAM integrations, MCP servers, stabilization, and utility tools.*

- [AfterEffects to DaVinci Resolve](https://github.com/IgorRidanovic/AfterEffects_to_DaVinci_Resolve) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Brings After Effects renders into Resolve workflows. *(by IgorRidanovic)* `Windows` <sub>(⭐ 39 · updated 2019)</sub>
- [ARISDA Bridge](https://arisdabridge.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Companion app for Resolve Studio that fixes the Edit-page timecode freeze during playback (Scripting API + MIDI) and adds frame-accurate LTC timecode on the Fairlight page. Includes automatic per-project work-time tracking with multilingual PDF invoicing and a standalone Studio Clock. No extra hardware required. *(by ARISDA)* `Windows` `Studio 21 (Windows 11)`
- [Assetszy](https://github.com/islamifty/assetszy-release) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Enterprise workflow plugin: search, preview, and import premium stock videos, photos, transparent vectors, audio, SFX, and YouTube downloads directly into the media pool and timeline. Also includes auto-transcription and styled subtitles. *(by Iftekharul Islam)* `macOS, Windows` `Studio (19 to 21+)`
- [Auto Import](https://github.com/ChristyKail/resolve_auto_import) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — This tool is mainly designed for DIT and dailies work, where you need to quickly import the contents of a camera card (or multiple camera cards) into a DaVinci Resolve bin, and create a timeline of all clips per camera card. This tool allows you to select any number of camera rolls at the Finder level, and quickly import them into Resolve using a Finder QuickAction. *(by Christy Kail)* `macOS` `Tested with 19.0.3 and later`
- [Blender to Resolve Bridge](https://superhivemarket.com/products/blender-to-resolve-bridge) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Blender render handoff with bins, timeline settings, and color transforms. Windows 10/11, Blender 4.2+, Resolve 19. *(by superhive)* `Windows` `19`
- **BMD's x264 Encoder** ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Provided uncompiled by default; requires manual compilation. *(by BMD)* `Studio Required`
- [Cheetah Video Proxy Generator](https://fractale.itch.io/cheetah-video-proxy-generator) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Creates H.264/H.265, DNxHR, and ProRes proxies for Resolve, including portrait-aware sizing. macOS needs separate FFmpeg. *(by Fractale)* `macOS, Windows` <sub>(updated 2024)</sub>
- [ChopChop](https://www.chopchopsystems.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Tool to sync, organize footage, and build sync maps in 60 seconds.
- [cutmaster-ai](https://github.com/CelaviiHQ/cutmaster-ai) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — MCP toolkit and Resolve workflow panel. The public toolkit is separate from the paid CutMaster Studio macOS app. *(by CelaviiHQ)* `macOS, Windows, Linux` <sub>(⭐ 3 · updated 2026-08)</sub>
- [CutMatch](https://cutpointlabs.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Standalone macOS app for trailer, marketing, and conform editors who need to rebuild source-based conforms from finished reference videos. Visually matches a reference export to source media and exports a conform-ready CMX3600 EDL. *(by Cutpoint Labs LLC)* `macOS` `No specific Resolve version required`
- [DaVinci Resolve DRP Font Auditor & Mapper](https://github.com/mrchrisster/davinci-font-auditor) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Desktop utility to audit, scan, and map font family usage across timelines directly from a DaVinci Resolve project (.drp) file, completely offline, without opening Resolve. *(by Mrchrisster)* `macOS, Windows, Linux` `Tested on 20`
- [davinci-mcp-professional](https://github.com/hoyt-harness/davinci-mcp-professional) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — MCP automation organized around Resolve workflows/domains. 'Professional' is the project name, not a paid license. *(by hoyt-harness)* `macOS, Windows, Linux` <sub>(⭐ 24 · updated 2026-09)</sub>
- [davinci-resolve-cli](https://github.com/Poechant/davinci-resolve-cli) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Command-line control of Resolve projects, media, timelines, and rendering. Resolve 18+; Studio recommended. *(by Poechant)* `macOS, Windows, Linux` `18+` <sub>(⭐ 51 · updated 2026-06)</sub>
- [davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — AI-client access to media, timeline, rendering, and other Resolve operations through MCP. Studio workflow. *(by samuelgursky)* `macOS, Windows, Linux` <sub>(⭐ 2414 · updated 2026-09)</sub>
- [davinci-resolve-mcp](https://github.com/apvlv/davinci-resolve-mcp) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Another Resolve/Fusion MCP implementation; capabilities differ from the other servers. *(by apvlv)* <sub>(⭐ 77 · updated 2026-04)</sub>
- [DaVinci-Resolve-Scripts](https://github.com/X-Raym/DaVinci-Resolve-Scripts) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Free scripts for editing, markers, properties, and project workflows. *(by X-Raym)* `macOS, Windows, Linux` <sub>(⭐ 94 · updated 2025)</sub>
- [DaVinci-Resolve-Utilities](https://github.com/jjsawdon/DaVinci-Resolve-Utilities) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Proxy/cache utilities, YouTube chapter export, and project-template helpers. *(by jjsawdon)* `macOS, Windows, Linux` <sub>(⭐ 44 · updated 2025)</sub>
- [DaVinciResolve-ClipLister](https://github.com/IgorRidanovic/DaVinciResolve-ClipLister) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Export bin clip metadata as CSV or HTML. *(by IgorRidanovic)* <sub>(⭐ 32 · updated 2019)</sub>
- [DaVinciResolve-DynamicText](https://github.com/IgorRidanovic/DaVinciResolve-DynamicText) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Dynamic title/text scripting. *(by IgorRidanovic)* <sub>(⭐ 25 · updated 2020)</sub>
- [DaVinciResolve-metadata](https://github.com/deric/DaVinciResolve-metadata) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Synchronize camera EXIF metadata into the Resolve Media Pool using ExifTool. *(by deric)* `macOS, Windows, Linux` <sub>(⭐ 70 · updated 2025)</sub>
- [DaVinciResolveScript](https://github.com/fukco/DaVinciResolveScript) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Metadata and workflow scripting tools. *(by fukco)* `macOS, Windows` <sub>(⭐ 57 · updated 2026)</sub>
- [EditShare Flow Panel](https://editshare.com/editshares-flow-panel-for-davinci-resolve-studio-creates-gateway-to-wider-media-ecosystem-and-remote-proxy-editing) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Workflow Integration for Media Asset Management (MAM) in enterprise environments. *(by EditShare)* `Studio Required`
- [ffmpeg_encoder_plugin](https://github.com/EdvinNilsson/ffmpeg_encoder_plugin) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — FFmpeg-powered export/encoding plugin for Resolve Studio. *(by EdvinNilsson)* `macOS, Windows, Linux` `Studio` <sub>(⭐ 230 · updated 2026-08)</sub>
- [ffmpeg-extract-clips-davinci-resolve-edl](https://github.com/ctsrc/ffmpeg-extract-clips-davinci-resolve-edl) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Rust/FFmpeg utility that extracts source clip ranges from a Resolve EDL. *(by ctsrc)* <sub>(⭐ 16 · updated 2025)</sub>
- [Font Scanner and Installer for DaVinci Resolve](https://github.com/MansiVisuals/Font-Scanner-and-Installer-for-DaVinci-Resolve) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Locate/install fonts for Resolve workflows. Fully tested on macOS; basic Windows/Linux support. *(by MansiVisuals)* `macOS, Windows, Linux` <sub>(⭐ 5 · updated 2025)</sub>
- [footbrake](https://github.com/veryqiang/footbrake) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — GUI for media/timeline automation, rendering, transcoding, and XML/AAF workflows. Archived; legacy macOS/Resolve 16. *(by veryqiang)* `macOS` <sub>(⭐ 13 · updated 2019)</sub>
- [GyroFlow](https://gyroflow.xyz) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Reads camera gyro data to stabilize footage. Free and open source. <sub>(⭐ 122 · updated 2026-09-01)</sub>
- [Main Concept](https://www.mainconcept.com/blackmagic-plugins) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Encoder plugin for specialized deliverables (e.g., AS-11 UK DPP) and 8K HEVC. `Studio Required`
- [multicam-logger](https://github.com/FranzWegner/multicam-logger) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Logs camera switching into edit lists for post-production workflows. *(by FranzWegner)* <sub>(⭐ 38 · updated 2023)</sub>
- [PostFlows script suite](https://postflows.github.io) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Directory of free MIT-licensed Resolve Studio scripts for text/fonts, markers, media bins, timelines, batch rename, VFX markers, title management, conform, and more (Studio 20+). Individual tool repos are consolidated here. *(by postflows)* `macOS, Windows` `Studio 20+` <sub>(updated 2026)</sub>
- [Primestream Xchange](https://primestream.com/news/press-release/xchange-mam-pam-and-davinci-resolve-17-now-integrated) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — MAM/PAM workflow integration for use in enterprise environments. *(by Primestream)* `Studio Required`
- [proxima](https://github.com/in03/proxima) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Queues, distributes, encodes, and automatically links proxy media across workers. *(by in03)* `macOS, Windows, Linux` <sub>(⭐ 74 · updated 2026-09)</sub>
- [RefreshResolveMedia](https://github.com/horshack-dpreview/RefreshResolveMedia) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Force Resolve to refresh stale media after files are edited outside Resolve. *(by horshack-dpreview)* `macOS, Windows` <sub>(⭐ 14 · updated 2025)</sub>
- [resolve-advanced-importer](https://github.com/heyJordanParker/resolve-advanced-importer) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Watch a folder and import new media into a selected Resolve bin. *(by heyJordanParker)* <sub>(⭐ 16 · updated 2021)</sub>
- [resolve-bulk-exporter](https://github.com/austinwitherspoon/resolve-bulk-exporter) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Queue multiple timelines for bulk export using the Resolve Python API. *(by austinwitherspoon)* `Windows` <sub>(⭐ 13 · updated 2021)</sub>
- [resolve-claude-mcp](https://github.com/barckley75/resolve-claude-mcp) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Claude/MCP integration for Resolve automation. Tested on Apple Silicon; transcription and screenshots are macOS-only. *(by barckley75)* `macOS` <sub>(⭐ 350 · updated 2026-06)</sub>
- [resolve-otio](https://github.com/eric-with-a-c/resolve-otio) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — OpenTimelineIO interoperability with Resolve. *(by eric-with-a-c)* `macOS, Windows, Linux` <sub>(⭐ 27 · updated 2021)</sub>
- [resolve-scripts](https://github.com/thatcherfreeman/resolve-scripts) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Everyday Resolve/Fusion automation: timeline, metadata, render, relinking, and other helpers. *(by thatcherfreeman)* `macOS, Windows, Linux` <sub>(⭐ 17 · updated 2026)</sub>
- [ResolveOFX_NDIOutput](https://github.com/lightsailvr/ResolveOFX_NDIOutput) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — NDI HDR network-video output through OpenFX. Resolve 17+; building from source requires the NDI Advanced SDK. *(by lightsailvr)* `macOS, Windows` `17+` <sub>(⭐ 5 · updated 2026-09)</sub>
- [Shutter Encoder](https://www.shutterencoder.com) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Standalone FFmpeg-based media prep and delivery companion: DNxHR/ProRes conversion, rewrap, subtitles, cut detection, EDL export, QC. Not a Resolve plugin. *(by Paul Pacifico)* `macOS, Windows, Linux`
- [Studio Network Solutions (ShareBrowser)](https://www.studionetworksolutions.com/sns-unveils-sharebrowser-workflow-integration-plugin-for-davinci-resolve) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — ShareBrowser MAM workflow integration plugin. `Studio Required`
- [SynCut](https://syncut.io) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — Finds commercially-licensed music whose beats land on the cuts you already made. Reads your open Resolve timeline, detects cuts and tempo, and scores a licensed catalog to surface tracks that fit the edit. Mac now; Premiere Pro in beta. `macOS` `18 or later`
- [Toolbox](https://github.com/VilleOlof/Toolbox) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Various Utilities for Common Tasks. *(by u/VilleOlof)* <sub>(⭐ 61 · updated 2025)</sub>
- [unofficial-davinci-mcp](https://github.com/wassermanproductions/unofficial-davinci-mcp) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — MCP integration with live Studio control and a Free-edition interchange workflow using FCPXML/LUTs. Studio 21 verified upstream. *(by wassermanproductions)* `macOS, Linux` <sub>(⭐ 32 · updated 2026-08)</sub>
- [Useful.Resolve](https://github.com/ambustion/Useful.Resolve) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Colorist workflow helpers including gallery still capture at markers. Legacy Python 3.6-era setup. *(by ambustion)* <sub>(⭐ 23 · updated 2022)</sub>
- [videoflo](https://github.com/tonyflo/videoflo) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Python helpers for organizing and automating YouTube video production in Resolve. *(by tonyflo)* <sub>(⭐ 95 · updated 2023)</sub>
- [Voukoder](https://www.voukoder.org) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — Encoder plugin. Codecs may not be licensed for commercial use. `Windows-only` `Studio Required`
- [VSE OTIO Export](https://github.com/tin2tin/VSE_OTIO_Export) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Blender Video Sequence Editor timeline export through OpenTimelineIO. *(by tin2tin)* `Windows` <sub>(⭐ 32 · updated 2024)</sub>

## Subtitles & Captions

*Transcription, subtitle, caption, and dialogue-cleanup tools (AI and otherwise).*

- [auto-editor](https://github.com/WyattBlue/auto-editor) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Standalone automatic editing with NLE timeline-export workflows; not a native Resolve plugin. *(by WyattBlue)* <sub>(⭐ 5164 · updated 2026-09)</sub>
- [auto-silence-cut](https://github.com/YourAverageMo/auto-silence-cut) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Automatic silence cutting with an editable Resolve workflow. *(by YourAverageMo)* `macOS, Windows` <sub>(⭐ 24 · updated 2025)</sub>
- [auto-subs](https://github.com/tmoroney/auto-subs) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Local transcription and styled/animated subtitle workflows, with standalone and Resolve integration. *(by tmoroney)* `macOS, Windows, Linux` <sub>(⭐ 4137 · updated 2026-09)</sub>
- [automarker-clay](https://github.com/acrilique/automarker-clay) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Music-tempo beat detection and timeline markers for Resolve, Premiere Pro, and After Effects. Successor to AutoMarker. *(by acrilique)* `macOS, Windows, Linux` <sub>(⭐ 10 · updated 2026)</sub>
- [autotitles-community](https://github.com/ikm-san/autotitles-community) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — CLI/API subtitle-to-Fusion-title workflow for Studio. Free for commercial video work, but not open source. *(by ikm-san)* <sub>(⭐ 0 · updated 2026)</sub>
- [clautter](https://github.com/Nusscookie/clautter) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — AI-assisted talking-head cleanup. Beta; plugin is free (paid installer planned). *(by Nusscookie)* `macOS, Windows, Linux` <sub>(⭐ 1 · updated 2026)</sub>
- [DaVinci Sub Translator / Sub Tool / TTS (Ko-fi)](https://ko-fi.com/s/706feb3730) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — A creator's Ko-fi suite of subtitle tools: subtitle editing/search-replace, online/LLM translation of subtitle tracks, and text-to-speech from timeline text or subtitles (Microsoft/MiniMax/OpenAI voices). External provider costs may apply. *(by Ko-fi creator)*
- [DaVinci-Gate](https://github.com/randyrektor/DaVinci-Gate) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Analyze per-speaker podcast silence and rebuild gated audio tracks after preview. Requires Resolve 20+ and FFmpeg. *(by randyrektor)* `macOS, Windows, Linux` `20+` <sub>(⭐ 10 · updated 2026)</sub>
- [DaVinci-Resolve-TTS](https://github.com/2445868686/DaVinci-Resolve-TTS) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — Text-to-speech integrations with external voice providers; provider usage can cost money. *(by 2445868686)* `macOS, Windows` <sub>(⭐ 19 · updated 2025)</sub>
- [DaVinci-Resolve-Whisper](https://github.com/2445868686/DaVinci-Resolve-Whisper) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Whisper transcription through local or cloud-backed workflows. *(by 2445868686)* `macOS, Windows` <sub>(⭐ 10 · updated 2025)</sub>
- [fast-autocut](https://github.com/abhirup780/fast-autocut) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Silence removal that builds a new timeline while retaining externally recorded audio sync. Windows, Resolve Studio 18.5+, Python, FFmpeg. *(by abhirup780)* `Windows` `Studio 18.5+` <sub>(⭐ 1 · updated 2026)</sub>
- [HushCut](https://github.com/oliwoli/HushCut) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Silence-based editing helper for Resolve workflows. *(by oliwoli)* `macOS, Windows, Linux` <sub>(⭐ 19 · updated 2025)</sub>
- [Resolve-OpenCaptions](https://github.com/david-ca6/Resolve-OpenCaptions) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Converts subtitles into editable Text+ clips; supports Free and Studio. *(by david-ca6)* `macOS, Windows, Linux` <sub>(⭐ 30 · updated 2026-08)</sub>
- [resolve-text-index](https://github.com/postflows/resolve-text-index) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Search, edit, and CSV round-trip Text+, MultiText, and subtitle text. Studio 20+; optional LanguageTool spell-check. *(by postflows)* `macOS, Windows` `Studio 20+` <sub>(⭐ 2 · updated 2026)</sub>
- [resolve-textplus-srt-importer](https://github.com/JiginJayaprakash/resolve-textplus-srt-importer) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Imports SRT subtitles as styled Fusion Text+ clips. *(by JiginJayaprakash)* <sub>(⭐ 2 · updated 2026)</sub>
- [snap-captions](https://github.com/cutbypham/snap-captions) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Community Snap Captions distribution and additional caption styles. *(by cutbypham)* <sub>(⭐ 27 · updated 2025)</sub>
- [squawk](https://github.com/in03/squawk) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Whisper subtitle integration that renders timeline audio, transcribes it, and imports subtitles. Resolve 18; archived / no longer maintained. *(by in03)* `18` <sub>(⭐ 40 · updated 2025)</sub>
- [srt_to_textplus](https://github.com/atmosfar/srt_to_textplus) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Generate animated Fusion TextPlus titles from SRT subtitles. Legacy Python 2.7 workflow. *(by atmosfar)* <sub>(⭐ 12 · updated 2020)</sub>

## Gen Media

*Generative AI media tools, including ComfyUI integrations.*

- [comfyUI_DaVinciResolve](https://github.com/barckley75/comfyUI_DaVinciResolve) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — ComfyUI nodes connecting generative AI workflows to Resolve. *(by barckley75)* <sub>(⭐ 46 · updated 2024)</sub>

## Linux

*Installation, compatibility, codec, and troubleshooting tools for Resolve on Linux.*

- [autoresolvedeb](https://github.com/psygreg/autoresolvedeb) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Automates downloading and repackaging Resolve via MakeResolveDeb. *(by psygreg)* `Linux` <sub>(⭐ 29 · updated 2026)</sub>
- [davinci-helper](https://github.com/H3rz3n/davinci-helper) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Linux companion utilities for Resolve. Fedora family; Debian support planned. *(by H3rz3n)* `Linux` <sub>(⭐ 313 · updated 2025)</sub>
- [davinci-linux-aac-codec](https://github.com/Toxblh/davinci-linux-aac-codec) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — AAC encoding plugin for Resolve Studio on Linux. *(by Toxblh)* `Linux` `Studio` <sub>(⭐ 117 · updated 2025)</sub>
- [davinci-resolve-checker](https://github.com/Ashark/davinci-resolve-checker) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Checks system configuration and hardware suitability for Resolve. *(by Ashark)* `Linux` <sub>(⭐ 174 · updated 2026)</sub>
- [davinci-resolve-linux](https://github.com/flolu/davinci-resolve-linux) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Setup instructions and import/export workarounds (Debian/Ubuntu). *(by flolu)* `Linux` <sub>(⭐ 263 · updated 2025)</sub>
- [davincibox](https://github.com/zelikos/davincibox) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Containerized Resolve dependencies using Distrobox/Podman; aimed at atomic/image-based distributions. *(by zelikos)* `Linux` <sub>(⭐ 980 · updated 2026-08)</sub>
- [davinconv](https://github.com/gohny/davinconv) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — FFmpeg Bash conversion helper for preparing footage for Resolve on Linux. *(by gohny)* `Linux` <sub>(⭐ 24 · updated 2025)</sub>
- [drwrap](https://github.com/fedsfarm/drwrap) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Resolve wrapper for codec conversion, clipboard, and drag-and-drop workarounds. Tested on Arch/Hyprland with Studio 21. *(by fedsfarm)* `Linux` <sub>(⭐ 26 · updated 2026)</sub>
- [dvcp-vaapi](https://github.com/nowrep/dvcp-vaapi) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — VAAPI video encoder plugin for Resolve on Linux. *(by nowrep)* `Linux` <sub>(⭐ 39 · updated 2025)</sub>
- [fedora-resolve](https://github.com/yioannides/fedora-resolve) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Fedora installation scripts. Maintainer warns the method may be obsolete. *(by yioannides)* `Linux` <sub>(⭐ 26 · updated 2026)</sub>
- [resolve (container scripts)](https://github.com/fat-tire/resolve) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Container scripts for building and running Resolve on Linux (x86-64 with NVIDIA). *(by fat-tire)* `Linux` <sub>(⭐ 298 · updated 2025)</sub>
- [Resolve-Linux-Studio-AAC-FDK-Encoder-plugin](https://github.com/hexitnz/Resolve-Linux-Studio-AAC-FDK-Encoder-plugin) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — FDK-based AAC audio encoding on Linux. Studio required. *(by hexitnz)* `Linux` `Studio` <sub>(⭐ 29 · updated 2026)</sub>
- [resolve-tumbleweed](https://github.com/Chillsmeit/resolve-tumbleweed) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — openSUSE Tumbleweed fixes. Maintainer no longer uses that distribution. *(by Chillsmeit)* `Linux` <sub>(⭐ 21 · updated 2026)</sub>
- [VSTForResolveLinux](https://github.com/JaySNL/VSTForResolveLinux) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Experimental VST2/VST3/CLAP bridge for Resolve Studio 21 on Linux. May crash Resolve; see latency limitations. *(by JaySNL)* `Linux` `Studio 21` <sub>(⭐ 8 · updated 2026-09)</sub>

## Hardware & Control Surfaces

*Control-surface, MIDI, and Speed Editor tools, plus DIY editing hardware.*

- [AutoHotKey_Bome_MIDI_2_Key](https://github.com/RudyB24/AutoHotKey_Bome_MIDI_2_Key) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Maps incoming MIDI messages to Resolve keyboard shortcuts. *(by RudyB24)* `Windows` <sub>(⭐ 21 · updated 2023)</sub>
- [blackmacro-hardware](https://github.com/KipJM/blackmacro-hardware) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Configurable DIY editing keyboard based on Raspberry Pi Pico 2W. *(by KipJM)* <sub>(⭐ 23 · updated 2026)</sub>
- [blackmacro-lib](https://github.com/KipJM/blackmacro-lib) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — USB Speed Editor emulation firmware for custom microcontroller/macropad projects. AGPLv3. *(by KipJM)* <sub>(⭐ 12 · updated 2026)</sub>
- [DiSE](https://github.com/shaise/DiSE) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — DIY speed-editor hardware for Resolve and other video-editing applications. *(by shaise)* <sub>(⭐ 60 · updated 2022)</sub>
- [micro-color-panel-controller](https://github.com/ra100/micro-color-panel-controller) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Prototype support for using the Blackmagic Micro Color Panel outside Resolve. Requires the physical panel. MIT. *(by ra100)* `macOS, Windows, Linux` <sub>(⭐ 10 · updated 2025)</sub>
- [speed-editor-client](https://github.com/JamesBalazs/speed-editor-client) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Go HID client for using the Speed Editor outside Resolve, with a volume-control example. Requires the physical controller. *(by JamesBalazs)* `macOS, Windows, Linux` <sub>(⭐ 9 · updated 2026)</sub>
- [SpeedEditorCheatSheet](https://github.com/derwok/SpeedEditorCheatSheet) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Printable Speed Editor reference/cheat sheet. *(by derwok)* <sub>(⭐ 41 · updated 2024)</sub>
- [Unbound editor device customizer](https://github.com/PuzzleEmptyM/Unbound-editor-device-customizer) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Remaps controller buttons and jog-wheel actions outside Resolve. Windows/macOS builds. *(by PuzzleEmptyM)* `macOS, Windows` <sub>(⭐ 43 · updated 2026)</sub>
- [XTouchMini DaVinci Resolve MIDI Adapter](https://github.com/fashberg/XTouchMini-Davinci-Resolve-Midi-Adapter) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Uses a Behringer X-Touch Mini to control Resolve through Windows hotkeys. *(by fashberg)* `Windows` <sub>(⭐ 30 · updated 2020)</sub>

## Database & Project Server Tools

*Tools for Resolve's PostgreSQL project database and collaboration servers.*

- [davinci-resolve-postgresql-workflow-tools](https://github.com/sethgoldin/davinci-resolve-postgresql-workflow-tools) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Automatic project-database backups and maintenance for Resolve's PostgreSQL project server. *(by sethgoldin)* `macOS, Linux` <sub>(⭐ 101 · updated 2023)</sub>
- [Docker-Davinci-Resolve-Project-Server](https://github.com/elliotmatson/Docker-Davinci-Resolve-Project-Server) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Containerized PostgreSQL project server with automatic backups (hosts the shared project database, not the Resolve client). *(by elliotmatson)* `macOS, Windows, Linux` <sub>(⭐ 313 · updated 2026-08)</sub>
- [Resolve-backup-Postgres](https://github.com/IgorRidanovic/Resolve-backup-Postgres) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — PostgreSQL backup scripts for Resolve project databases. *(by IgorRidanovic)* `macOS, Windows, Linux` <sub>(⭐ 25 · updated 2018)</sub>
- [ResolveCollaboration](https://github.com/jonnyhyman/ResolveCollaboration) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Utilities extending older live-collaboration workflows for Resolve's shared database. *(by jonnyhyman)* `macOS, Windows` <sub>(⭐ 36 · updated 2021)</sub>
- [ResolveDB_backup](https://github.com/walter-arrighetti/ResolveDB_backup) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Scheduled PostgreSQL project-server backups. Requires server administration and matching PostgreSQL config. *(by walter-arrighetti)* `macOS, Windows, Linux` <sub>(⭐ 13 · updated 2020)</sub>

## Development Resources

*Scripting libraries, API references, and developer tooling for building Resolve tools.*

- [davinci-resolve-api](https://github.com/diop/davinci-resolve-api) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Community Python API documentation. Reference, not the latest official SDK. *(by diop)* <sub>(⭐ 98 · updated 2019)</sub>
- [Davinci-Resolve-Functions-Toolkit](https://github.com/FusionPixelStudio/Davinci-Resolve-Functions-Toolkit) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — VS Code toolkit with Resolve API snippets and scripting templates for Lua, Python, and JavaScript. *(by FusionPixelStudio)* <sub>(⭐ 11 · updated 2025)</sub>
- [dctl-matrix-maker](https://github.com/ctcwired/dctl-matrix-maker) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Python color-matrix solver using paired ColorChecker images; generates a DCTL. Requires colour-science. *(by ctcwired)* <sub>(⭐ 20 · updated 2024)</sub>
- [dctl-text-rendering](https://github.com/thatcherfreeman/dctl-text-rendering) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — DCTL text-rendering example and Python font-header generator for tool developers. *(by thatcherfreeman)* <sub>(⭐ 11 · updated 2025)</sub>
- [dctl-tutorial](https://github.com/thatcherfreeman/dctl-tutorial) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — DCTL programming tutorial notes and supporting code. *(by thatcherfreeman)* <sub>(⭐ 29 · updated 2025)</sub>
- [fusionscript-stubs](https://github.com/czukowski/fusionscript-stubs) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Python type stubs providing IDE completion for the Fusion scripting API. *(by czukowski)* <sub>(⭐ 16 · updated 2026)</sub>
- [openfx-template](https://github.com/gingray/openfx-template) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — C++ OpenFX starter template for plugin developers. *(by gingray)* `macOS` <sub>(⭐ 16 · updated 2020)</sub>
- [pybmd](https://github.com/WheheoHu/pybmd) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Python wrapper around the Resolve API. *(by WheheoHu)* `macOS, Windows` <sub>(⭐ 34 · updated 2026)</sub>
- [pydavinci](https://github.com/pedrolabonia/pydavinci) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Higher-level Python package for scripting Resolve. *(by pedrolabonia)* <sub>(⭐ 181 · updated 2026)</sub>
- [pysion](https://github.com/brunocbreis/pysion) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Python framework for generating Fusion compositions from dictionaries and reusable constructs. *(by brunocbreis)* <sub>(⭐ 26 · updated 2024)</sub>
- [Spicy-Acorn Fusion Fuse libraries](https://github.com/Spicy-Acorn) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — A set of Fusion Fuse libraries for developers: JSON, matrix math, vector math, numeric, and string operations (fusionjson, fusionmatrix, fusionvector, fusionnumber, fusiontext). Some require the lua-matrix / FusionMatrix dependency. *(by Spicy-Acorn)* <sub>(⭐ 11 · updated 2020)</sub>

## Community Attribution

This awesome list is curated and maintained with contributions from:

- **[/r/colorists](https://reddit.com/r/colorists)** — Professional colorists and color grading enthusiasts sharing their expertise
- **[/r/davinciresolve](https://reddit.com/r/davinciresolve)** — DaVinci Resolve users of all levels contributing resources and tips

### Special Thanks

We extend our gratitude to all community members who have suggested resources, provided feedback, and helped maintain the quality of this list.

## Contributing

Want to add a resource? Please read our [Contributing Guidelines](CONTRIBUTING.md) — the easiest way is through our submission form.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.