# Awesome DaVinci Resolve [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) plugins, tools, and resources.

Community-curated by [/r/colorists](https://reddit.com/r/colorists) and [/r/davinciresolve](https://reddit.com/r/davinciresolve).

## Contents

- [AI & Automation Tools](#ai-automation-tools)
- [Audio Plugins](#audio-plugins)
- [DCTLs](#dctls)
- [OFX/Video Effects & VFX Suites](#ofx-video-effects-vfx-suites)
- [Templates, Macros, & Scripts](#templates-macros-scripts)
- [Workflow & Integration Tools](#workflow-integration-tools)
- [Community Attribution](#community-attribution)
- [Contributing](#contributing)

## AI & Automation Tools

*AI-powered tools for automating editing, captions, and footage search.*

- [AutoCut](https://www.autocut.com/en) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Automates captions, adds zooms, B-roll matching, removes silences/repetitions. Auto-edits podcasts.
- [BadWords](https://gitlab.com/badwords/BadWords) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Basically its a free local text based editor that lives right inside Davinci. Free alternative to AutoCut but with a bit of different of other features, 100% local and free How it works: u drop your raw video on a timeline and open BadWords. You choose audio lang, whisper model (bigger = better) and you can even add your custom filler words, then your audio gets shown as text in GUI and you can edit it then edits you made on text will be mapped on timeline. I think the coolest part is u can paste your written script into the app and it will compare it with what you actually said in recording and highlight exactly where you messed up repeated a line or went off script. It also finds all the awkward pauses (silence) automatically *(by Szymon Wolarz)* `Windows, Linux`
- [BadWords](https://github.com/veritus-git/BadWords) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — An open-source DaVinci Resolve plugin that automates the tedious rough-cutting of podcasts and dialogue-heavy videos. Powered by 100% local, offline AI, it transcribes audio to automatically detect silences, retakes, and filler words. Instead of manually scrubbing through hours of footage, you simply review the text transcript. With one click, BadWords auto-assembles a brand new, clean timeline directly inside Resolve, saving you massive amounts of editing time. *(by veritus)* `macOS, Windows, Linux`
- [FireCut](https://firecut.ai/pricing/davinci-resolve) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Great list! FireCut launched a free tier last week :) https://firecut.ai/pricing/davinci-resolve/ `macOS, Windows, Linux` `20+`
- [Jumper](https://getjumper.io) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — AI-based search tool for project footage to find specific visual moment or spoken word.
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

- [Asim Siddiqui/XtremeStuff](https://github.com/xtremestuff/resolve-dctl) ![Free/shareware](https://img.shields.io/badge/Cost-Free%2Fshareware-brightgreen) — DCTL provider. *(by Asim Siddiqui)*
- [Baldavenger DCTLs](https://github.com/baldavenger) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Free, open source DCTLs related to color science. *(by Paul Dore / Baldavenger)*
- [Colorist Foundry Filmverse](https://coloristfoundry.com/store) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider.
- [Henry Bobeck (UltimateSaturation)](https://henrybobeck.com/dctl/UltimateSaturation) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider. *(by Henry Bobeck)*
- [Henry Bobeck DCTLs](https://henrybobeck.com/dctl) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — The current list links to one specific DCTL by Henry Bobeck, I'm just suggesting to link to the main page instead for full context :) *(by Henry Bobeck)* `macOS, Windows, Linux` `19.1+`
- [HotGlueBanjo](https://github.com/hotgluebanjo) ![Free/shareware](https://img.shields.io/badge/Cost-Free%2Fshareware-brightgreen) — DCTL provider.
- [Iridescent Color](https://iridescentcolor.com/shop) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider.
- [Jed Smith](https://github.com/jedypod) ![Free/shareware](https://img.shields.io/badge/Cost-Free%2Fshareware-brightgreen) — DCTL provider.
- [Kaur Hendrikson](https://store.kaurh.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider. Noted as "excellent". Has demo/trial versions available.
- [Moaz Elgabry](https://github.com/MoazElgabry/DCTLs) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Look development and grading tools for resolve (Filmic contrast, Ratio shaper, Localized contrast, hue curve) *(by Moaz Elgabry)* `macOS, Windows, Linux`
- [Mononodes](https://mononodes.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — "Awesome DCTL's and Plugins" including Film Emulations, Hue Twist, and Utility DCTLS. Noted as "excellent".
- [Nx Color](https://nxcolor.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL Tools including ChromaDrift, Liquid Glass, CanvasFlow, and ShadowCast (Realtime 2D GI).
- [PixelTools](https://pixeltoolspost.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL plugins and PowerGrade presets. Noted as "excellent". Has demo/trial versions available. *(by u/jbowdach)*
- [Ravengrade](https://ravengrade.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider.
- [Ravi Shankar DCTLs](https://store.ravishankar.xyz) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider. *(by Ravi Shankar)*
- [Salamifish](https://salamifish.com/demos) ![Offers Demos](https://img.shields.io/badge/Cost-Offers%20Demos-orange) — DCTL provider.
- [Sven Hegen](https://svenhegen.com/dctls) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — DCTL provider.
- [Thatcher Freeman](https://github.com/thatcherfreeman/utility-dctls) ![Free/shareware](https://img.shields.io/badge/Cost-Free%2Fshareware-brightgreen) — Utility DCTL provider. Noted as "excellent". Has demo/trial versions available.

## OFX/Video Effects & VFX Suites

*OpenFX plugins for visual effects, film emulation, grain, diffusion, and color.*

- [Akascape](https://www.akascape.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Trendy visual effect plugins: Pixelsorting, Datamosh Fuse, Rutt Etra, VHS, Glitch.
- [Blewtoof](https://blewtoof.mov) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Effects plugins including CRT Machine, Mixed Media, Camcorder, and Superchrome.
- [Boris FX (Continuum/Sapphire)](https://borisfx.com/products/continuum) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Industry standard suite for VFX, color, and effects. *(by Boris FX)*
- [CineMatch](https://www.cinematch.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Camera matching plugin made by FilmConvert. *(by FilmConvert)*
- [Colourlab.ai (Look Designer)](https://www.colourlab.ai) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Look creators, grain, and AI grading. Used for color correction and film emulation.
- [Contour lookdev](https://procolor.ist/contour-official) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Look development tool.
- [CorridorKey-Runtime](https://github.com/alexandremendoncaalvaro/CorridorKey-Runtime) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Native AI keying runtime and OFX plugin for DaVinci Resolve. Built in collaboration with Corridor Digital; supports Windows (NVIDIA RTX) and macOS (Apple Silicon). *(by Alexandre Alvaro)* `macOS, Windows` `20`
- [Dehancer Pro](https://www.dehancer.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Specialized grain and film emulation.
- [Digital Anarchy (Beauty Box)](http://www.digitalanarchy.com/beautyVID/main.html) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Beauty and deflicker effects. Beautybox is highly recommended. *(by Digital Anarchy)*
- [Film Convert (Nitrate)](http://www.filmconvert.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Film emulation and grain.
- [Filmworkz](https://filmworkz.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Restoration tools from Digital Vision. *(by Digital Vision)*
- [FXHome Ignite Pro](https://hitfilm.com/ignite-pro) ![Discontinued](https://img.shields.io/badge/Cost-Discontinued-lightgrey) — VFX and color suite. (Note: DISCONTINUED).
- [Gyroflow](https://gyroflow.xyz) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Reads camera gyro data to stabilize footage. Free and Open Source!
- [Genesis film emulation](https://procolor.ist/genesis) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Film emulation tool.
- [Greyscale Labs (Nano, Serum, Scalar)](https://greyscalelabs.com/nano) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Nano (Diffusion), Serum (Skin Refinement), and Scalar (Color-Control/uprez/debanding). *(by Greyscale Labs)*
- [Hazy digital diffusion](https://www.filmconvert.com/plugin/hazy) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Diffusion plugin.
- [Invizipro film grain](https://www.invizipro.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Film grain tool.
- [Kromatika DigiDiff diffusion](https://www.kromatica.co/pages/digidiff) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Diffusion plugin.
- [Livegrain](http://www.live-grain.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — High-end film grain. Noted as expensive, but used in Hollywood.
- [Maxon (Red Giant Universe)](https://www.redgiant.com/universe) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — VFX and effects suite. *(by Maxon)*
- [Neat Video NR](http://www.neatvideo.com/overview.html) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Industry standard video noise reduction.
- [NewBlue](https://www.newbluefx.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Mostly for titling, but some other tools. Common for AVID systems.
- **NodeMill LensNode** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Lens Simulations.
- [NTSC-RS](https://ntsc.rs) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Provides a VHS Effect in OpenFX.
- [RE:vision Effects](https://revisionfx.com/products/for/resolve) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Includes Twixtor (for speed warps) and ReelSmart Motion Blur.
- [RetouchForMe](https://retouch4.me/videoretouching) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Beauty effects.
- [Reverator film emulation](https://www.reverator.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Film emulation tool.
- [Textuler](https://textuler.io/features) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Ultimate plugin for creating chat & text bubbles, advanced text, and UI elements.
- **TimeInPixel (Nobe tools)** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Color Assistance Tools: Nobe OmniScope, Nobe Display, False Color Nobe.
- [VideoVillage (Filmbox/Scatter)](https://videovillage.co/filmbox) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — FilmBox (Film Emulation) and Scatter (Diffusion). Also makes Lattice (LUT builder). *(by VideoVillage)* `macOS only`
- [framechart](https://framechart.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Animated chart generation tool from .csv data files. *(by DonData)*

## Templates, Macros, & Scripts

*Ready-made templates, Fusion macros, scripts, and preset packs.*

- [AEScripts (BeatEdit / ShotList Creator)](https://aescripts.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Offers scripts like BeatEdit for rhythm and ShotList Creator. *(by AEScripts)*
- **Art3studios** ![Some free](https://img.shields.io/badge/Cost-Some%20free-blue) — Offers "some nice free preset things with titles".
- [AUTOBlanking](https://dimitr1e.gumroad.com/l/AUTOBlanking?layout=profile) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — AUTOBlanking is a DaVinci Resolve effect template that automates the BlankingFill process. It detects the black borders of your source footage and automatically fits the picture into your timeline format using a single reference frame as its guide. No configuration needed — it works from the frame you insert it on. Fine-tune the result with Margin to expand the fit beyond the detected borders, and Position to offset the blanking along its axis. 2 automation modes: Fill automatically fills the blanking area with your source image content, Warp stretches the edges of your image to fill the blanking area. 20 style presets included across Dark, Bright, Color and Stylized categories. *(by Dimitrie)* `macOS, Windows` `20+ Free or Studio`
- [B-Roll Fade & Finish PRO](https://alejandrourman.com/store) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — A faster way to crop, stylise and animate overlaid B-roll clips through an intuitive, keyframe-free workflow. *(by Alejandro Urman)* `macOS, Windows` `DaVinci Resolve 20`
- [Chris Boustedt](https://www.chrisboustedt.com/products/chriss-boustedts-edit-like-tom-noske-asset-pack) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Clean preset packs for simple animations (e.g., The Minimal Preset Pack). *(by Chris Boustedt)*
- **DrFusion MotionCurves PRO Script** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Script/macro tool. *(by DrFusion)*
- [Editors Lab](https://editorslab.store) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Creative hub for presets and plugins (e.g., AuthenticVHS, Motion Sweet).
- [Essentials Preset Pack](https://gregeditsvideo.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — 21 DaVinci Resolve presets for saving time editing *(by Greg Edits Video)* `macOS, Windows, Linux` `18.5`
- [European Filmmaker (Asset Blaster)](https://www.europeanfilmmaker.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Asset Blaster transforms assets, animates titles, and adds visual effects. *(by European Filmmaker)*
- **Jayaretv** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Templates & Tools provider.
- [Map Engine](https://davincikit.com/product/map-engine) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Lua Map Animation script for Fusion; similar to GeoLayers. Supports Geo Shapes through GeoJSONs, custom Map Styles, OpenStreetMap-powered location search and map routing and more. *(by Kai Engels)* `macOS, Windows` `18.6+`
- [Meta Fide](https://www.metafide.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Various scripts and Fusion tools, including project setup and ASCII converters.
- **Motion VFX** ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — High-quality, native Resolve templates and packs (e.g., McamRig).
- [MrAlexTech (Magic Suite)](https://www.mralextech.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Creator offering tools like MagicAnimate, Magic Subtitle, and MagicZoomPro. *(by MrAlexTech)*
- [MrJustinEdits](https://mrjustinedits.com/en-gbp) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Offers effects like Paper Animator Pro v2 and Easy Camera Shake. *(by MrJustinEdits)*
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

*Encoder plugins, MAM/PAM integrations, stabilization, and utility tools.*

- [Auto Import](https://github.com/ChristyKail/resolve_auto_import) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — This tool is mainly designed for DIT and dailies work, where you need to quickly import the contents of a camera card (or multiple camera cards) into a DaVinci Resolve bin, and create a timeline of all clips per camera card. This tool allows you to select any number of camera rolls at the Finder level, and quickly import them into Resolve using a Finder QuickAction. *(by Christy Kail)* `macOS` `Tested with 19.0.3 and later`
- **BMD's x264 Encoder** ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Provided uncompiled by default; requires manual compilation. *(by BMD)* `Studio Required`
- [ChopChop](https://www.chopchopsystems.com) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Tool to sync, organize footage, and build sync maps in 60 seconds.
- [EditShare Flow Panel](https://editshare.com/editshares-flow-panel-for-davinci-resolve-studio-creates-gateway-to-wider-media-ecosystem-and-remote-proxy-editing) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Workflow Integration for Media Asset Management (MAM) in enterprise environments. *(by EditShare)* `Studio Required`
- [Main Concept](https://www.mainconcept.com/blackmagic-plugins) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — Encoder plugin for specialized deliverables (e.g., AS-11 UK DPP) and 8K HEVC. `Studio Required`
- [Primestream Xchange](https://primestream.com/news/press-release/xchange-mam-pam-and-davinci-resolve-17-now-integrated) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — MAM/PAM workflow integration for use in enterprise environments. *(by Primestream)* `Studio Required`
- [Studio Network Solutions (ShareBrowser)](https://www.studionetworksolutions.com/sns-unveils-sharebrowser-workflow-integration-plugin-for-davinci-resolve) ![Paid](https://img.shields.io/badge/Cost-Paid-orange) — ShareBrowser MAM workflow integration plugin. `Studio Required`
- [Toolbox](https://github.com/VilleOlof/Toolbox) ![Free](https://img.shields.io/badge/Cost-Free-brightgreen) — Various Utilities for Common Tasks. *(by u/VilleOlof)*
- [Voukoder](https://www.voukoder.org) ![Free/Paid](https://img.shields.io/badge/Cost-Free%2FPaid-blue) — Encoder plugin. Codecs may not be licensed for commercial use. `Windows-only` `Studio Required`

## Community Attribution

This awesome list is curated and maintained with contributions from:

- **[/r/colorists](https://reddit.com/r/colorists)** — Professional colorists and color grading enthusiasts sharing their expertise
- **[/r/davinciresolve](https://reddit.com/r/davinciresolve)** — DaVinci Resolve users of all levels contributing resources and tips

### Special Thanks

We extend our gratitude to all community members who have suggested resources, provided feedback, and helped maintain the quality of this list.

## Contributing

Want to add a resource? Please read our [Contributing Guidelines](CONTRIBUTING.md) — the [easiest way is through our submission form.](https://docs.google.com/forms/d/e/1FAIpQLSdpbb2pSkkbMkLUFJxnVvlaH-FyO8IMRVxVgL2Lh6okBAqe1Q/viewform)

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
