![billboardheaderredux](https://user-images.githubusercontent.com/36753686/215833211-ef44eeca-59a9-4e64-818e-374e943da44d.png)


[![Download](https://img.shields.io/badge/-DOWNLOAD-brightgreen)](https://github.com/Frosty704/Billboard/releases/download/v3.1/Frosty.Billboard.v3.1.unitypackage)
[![Showcase Video](https://img.shields.io/badge/-Showcase%20Video-red)](https://streamable.com/e/jeu2gx) 
[![Tutorial](https://img.shields.io/badge/-Installation%20Tutorial%20Video-blue)](https://github.com/Frosty704/Billboard#video-installation) 
# About

Frosty's billboard is a container for the [KAT (KillFrenzyAvatarText)](https://github.com/killfrenzy96/KillFrenzyAvatarText) making use of VRChat Avatar Dynamics and Unity Constraints you can have a speech bubble with the ability to drop it in the world, resizing it, grabbing and moving it around, posing it however you'd like, or just having it move with your head!

![Header Gif](https://user-images.githubusercontent.com/36753686/215548015-c31b936c-6808-4f33-89ae-ffe9a95e6cdc.gif)


It uses 500 polygons, 3 material slots, (4 including the KAT) and 12 bits of parameter space.


# Speech Parsers
- [TTS-Voice-Wizard](https://github.com/VRCWizard/TTS-Voice-Wizard)
 An OSC program allowing speech to text (or text to text) outputting to the KAT, making use of one of four speech recognition methods, Microsoft Azure, Vosk, Web Captioner, or System Speech.
 
 - [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)
 Another OSC program making use of [OpenAI's Whisper](https://github.com/openai/whisper) which runs locally on your GPU or CPU to transcribe speech and outputs to the  KAT
 In my experience it has great, almost Azure quality, speech recognition for free with a simple setup.

# Features & Showcase

# [Image Showcase](https://github.com/Frosty704/Billboard/wiki/1.-Home-%7C-Showcase)

# [Video Demonstration](https://youtu.be/EEFF2Bty78A)

Someone have your shaders/custom animations hidden? A fallback message will show instead. 

<img src="https://user-images.githubusercontent.com/36753686/215548765-3c273230-9181-45dd-bf76-51d7d3952314.png" width="600">

# Requirements 
- **IMPORT THESE BEFORE IMPORTING MY PACKAGE**
- [KillFrenzyAvatarText 1.2.7](https://github.com/killfrenzy96/KillFrenzyAvatarText/releases/tag/1.2.7) 1.3.0+ has shader changes that makes it a bit wonky.
- [VRLabs AV3 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) to make installation much easier.
- [Poiyomi 8.0](https://github.com/poiyomi/PoiyomiToonShader) 
- 12 bits of parameter space (Billboard only), 4 if you opt out for manual resizing.
- This prefab was made with write defaults off, your avatar should too to avoid potential issues. (or turn all write defaults on in the FX)
- PC ONLY. KAT uses a custom shader and the board itself uses constraints which is not quest supported.


# Video Installation

A written step-by-step installation guide can be found at https://github.com/Frosty704/Billboard/wiki/2.-Install

https://user-images.githubusercontent.com/36753686/198885603-8c43d992-00d9-498a-b148-f12b81fe04a5.mp4


# Discord
Need help? Questions? Comments? You can find me on the TTS Voice Wizard [Discord](https://discord.gg/8ttJKtQaMc) or DM me Frosty704#4638

# Credits
- [KillFrenzyAvatarText](https://github.com/killfrenzy96/KillFrenzyAvatarText)
- [TTSVoiceWizard](https://github.com/VRCWizard/TTS-Voice-Wizard)
- [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)
- [VRLabs World Constraint](https://github.com/VRLabs/World-Constraint)
- [Nintendofan12s](https://www.fanpop.com/clubs/nintendofan12s-fun-stuff/images/37299069/title/windows-95-notepad-photo) for the Windows 95 Notepad image
- [xxpillowprincessxx on Kofi](https://ko-fi.com/post/Windows-95-themed-border-for-webcamwindow-D1D83F6MR) for the Windows 95 window image

