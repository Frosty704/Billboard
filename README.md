![header](https://user-images.githubusercontent.com/36753686/199162650-07b260bb-94d0-4bbd-be3f-fffd56edb8d4.png)

[![Download](https://img.shields.io/badge/-DOWNLOAD-brightgreen)](https://github.com/Frosty704/Billboard/releases/download/v3/Frosty.Billboard.unitypackage) 
[![Showcase Video](https://img.shields.io/badge/-Showcase%20Video-red)](https://streamable.com/e/jeu2gx) 
[![Tutorial](https://img.shields.io/badge/-Installation%20Tutorial%20Video-blue)](https://github.com/Frosty704/Billboard#video-installation) 
# About

Frosty's billboard is a container for the [KAT (KillFrenzyAvatarText)](https://github.com/killfrenzy96/KillFrenzyAvatarText)
allowing you to have a speech bubble in your hand with the ability to drop it in the world, anchoring it there, resizing it, grabbing and moving it around with your right hand or just having it move with your head like a speech bubble!


It uses 394 polygons, 3 material slots, (4 including the KAT) and 11 bits of parameter space.


# TTS-Voice-Wizard
This is best used in tandem with Wizard's TTS-Voice-Wizard, an OSC program allowing speech to text (or text to text) outputting to the KAT! https://github.com/VRCWizard/TTS-Voice-Wizard 


# Features & Showcase
Spotify output to KAT using [TTS-Voice-Wizard](https://github.com/VRCWizard/TTS-Voice-Wizard )
![image](https://user-images.githubusercontent.com/36753686/197398360-ffad9c68-876b-4680-98fd-96e8c8ec8de7.png)

### Showcase video - Links to streamable
[![Showcase](https://user-images.githubusercontent.com/36753686/199163258-6c304c18-da1d-4a83-b277-dc014a24e10b.png)](https://streamable.com/e/jeu2gx "Showcase")


### Someone have your shaders/custom animations hidden? A fallback message will show instead. 
![image](https://user-images.githubusercontent.com/36753686/197409019-9f43ed16-9dca-46ac-8b22-08860e9b564c.png)

# Requirements 
- **IMPORT THESE BEFORE IMPORTING MY PACKAGE**
- PC ONLY. KAT uses a custom shader and the board itself uses constraints which is not quest supported.
- [KillFrenzyAvatarText 1.2.7](https://github.com/killfrenzy96/KillFrenzyAvatarText/releases/tag/1.2.7) 1.3.0+ has shader changes that makes it a bit wonky.
- [VRLabs AV3 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) to make installation much easier.
- [Poiyomi 8.0](https://github.com/poiyomi/PoiyomiToonShader) 
- 11 bits of parameter space (Billboard only), 3 if you opt out for manual resizing.
- Unity 2019.4.31f and basic knowledge of Unity.
- This prefab was made with write defaults off, your avatar should too to avoid potential issues.


# Video Installation

A written step-by-step installation guide can be found at https://github.com/Frosty704/Billboard/wiki/Install

https://user-images.githubusercontent.com/36753686/198885603-8c43d992-00d9-498a-b148-f12b81fe04a5.mp4


# Extra Functionality

You can use [VRChat Hotkeys OSC](https://gitlab.com/ameliend/vrchat-hotkeys-osc/-/releases) to bind certain parameter actions to keyboard shortcuts. TTS-Voice-Wizard's STTTS keybind is CTRL+G, so I bound KAT_Visible = true and KAT_Pointer to 255 upon CTRL+G using this. This way the billboard appears when you start talking instead of waiting for any active text to appear

Here is my setup

![image](https://user-images.githubusercontent.com/36753686/199845675-70b3defd-4e18-410c-8ece-e5b1cafc785a.png)




# Discord
Need help? Questions? Comments? You can find me on the TTS Voice Wizard [Discord](https://discord.gg/8ttJKtQaMc) or add me Frosty704#4638




