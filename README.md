![newgithub](https://user-images.githubusercontent.com/36753686/215336131-2fde0b7c-8810-4cd3-a4fc-da05f9bb432d.png)

[![Download](https://img.shields.io/badge/-DOWNLOAD-brightgreen)](https://github.com/Frosty704/Billboard/releases/download/v3.1/Frosty.Billboard.v3.1.unitypackage)
[![Showcase Video](https://img.shields.io/badge/-Showcase%20Video-red)](https://streamable.com/e/jeu2gx) 
[![Tutorial](https://img.shields.io/badge/-Installation%20Tutorial%20Video-blue)](https://github.com/Frosty704/Billboard#video-installation) 
# About

Frosty's billboard is a container for the [KAT (KillFrenzyAvatarText)](https://github.com/killfrenzy96/KillFrenzyAvatarText) making use of VRChat Avatar Dynamics and Unity Constraints you can have a speech bubble with the ability to drop it in the world, resizing it, grabbing and moving it around, posing it however you'd like, or just having it move with your head!

![Header Gif](https://user-images.githubusercontent.com/36753686/215548015-c31b936c-6808-4f33-89ae-ffe9a95e6cdc.gif)


It uses 500 polygons, 3 material slots, (4 including the KAT) and 12 bits of parameter space.


# TTS-Voice-Wizard
This is meant to be used in tandem with Wizard's TTS-Voice-Wizard, an OSC program allowing speech to text (or text to text) outputting to the KAT! https://github.com/VRCWizard/TTS-Voice-Wizard 


# Features & Showcase

Picture Showcase-
https://github.com/Frosty704/Billboard/wiki/1.-Home-%7C-Showcase

Video Features Showcase-
https://streamable.com/e/jeu2gx

### Someone have your shaders/custom animations hidden? A fallback message will show instead. 

![image](https://user-images.githubusercontent.com/36753686/215548765-3c273230-9181-45dd-bf76-51d7d3952314.png)



# Requirements 
- **IMPORT THESE BEFORE IMPORTING MY PACKAGE**
- [KillFrenzyAvatarText 1.2.7](https://github.com/killfrenzy96/KillFrenzyAvatarText/releases/tag/1.2.7) 1.3.0+ has shader changes that makes it a bit wonky.
- [VRLabs AV3 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) to make installation much easier.
- [Poiyomi 8.0](https://github.com/poiyomi/PoiyomiToonShader) 
- 12 bits of parameter space (Billboard only), 4 if you opt out for manual resizing.
- Unity 2019.4.31f and basic knowledge of Unity.
- This prefab was made with write defaults off, your avatar should too to avoid potential issues. (or turn all write defaults on in the FX)
- PC ONLY. KAT uses a custom shader and the board itself uses constraints which is not quest supported.


# Video Installation

A written step-by-step installation guide can be found at https://github.com/Frosty704/Billboard/wiki/2.-Install

https://user-images.githubusercontent.com/36753686/198885603-8c43d992-00d9-498a-b148-f12b81fe04a5.mp4


# Extra Functionality

You can use [VRChat Hotkeys OSC](https://gitlab.com/ameliend/vrchat-hotkeys-osc/-/releases) to bind certain parameter actions to keyboard shortcuts. TTS-Voice-Wizard's STTTS keybind is CTRL+G, so I bound KAT_Visible = true and KAT_Pointer to 255 upon CTRL+G using this. This way the billboard appears when you start talking instead of waiting for any active text to appear and typing dots reappear once you STT again.

Here is my setup

![image](https://user-images.githubusercontent.com/36753686/215336215-178e3a7d-a309-455a-b9d5-c4c92ae651aa.png)

and using OVR Advanced Settings controller press -> key

![image](https://user-images.githubusercontent.com/36753686/215336225-4302b7f1-71cf-4ba1-8f3f-13859d117e89.png)



# Discord
Need help? Questions? Comments? You can find me on the TTS Voice Wizard [Discord](https://discord.gg/8ttJKtQaMc) or DM me Frosty704#4638




