![billboardheaderredux](https://user-images.githubusercontent.com/36753686/215833211-ef44eeca-59a9-4e64-818e-374e943da44d.png)


[![Download](https://img.shields.io/badge/-DOWNLOAD-brightgreen)](https://github.com/Frosty704/Billboard/releases/download/v3.1/Frosty.Billboard.v3.1.unitypackage)
[![Showcase Video](https://img.shields.io/badge/-Showcase%20Video-red)](https://www.youtube.com/watch?v=EEFF2Bty78A) 
[![Tutorial](https://img.shields.io/badge/-Installation%20Tutorial%20Video-blue)](https://www.youtube.com/watch?v=c032JMb9ef0) 
# About

Frosty's billboard is a container for the [KAT (KillFrenzyAvatarText)](https://github.com/killfrenzy96/KillFrenzyAvatarText) making use of VRChat Avatar Dynamics and Unity Constraints you can have a speech bubble with the ability to drop it in the world, resizing it, grabbing and moving it around, posing it however you'd like, or just having it move with your head!

It uses 500 polygons, 4 material slots, and 12 bits of parameter space.

![Header Gif](https://user-images.githubusercontent.com/36753686/215548015-c31b936c-6808-4f33-89ae-ffe9a95e6cdc.gif)


# Speech Parsers
- [TTS-Voice-Wizard](https://github.com/VRCWizard/TTS-Voice-Wizard)
 An OSC program allowing speech to text (or text to text) outputting to the KAT, making use of one of four speech recognition methods, Microsoft Azure, Vosk, Web Captioner, or System Speech.
  - It also supports emotes replacing the original set of Japanese Hiragana, as seen in some screenshots
 
 - [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)
 Another OSC program making use of [OpenAI's Whisper](https://github.com/openai/whisper) which runs locally on your GPU or CPU to transcribe speech and outputs to the   KAT (also supports text to text)
   - In my experience it has great, almost Azure quality, speech recognition for free with a simple setup.

# Features & Showcase

 - # [Image Showcase](https://github.com/Frosty704/Billboard/wiki/1.-Home-%7C-Showcase)

 - # [Video Demonstration](https://youtu.be/EEFF2Bty78A)

- Speech to Text using [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)
<img src="https://user-images.githubusercontent.com/36753686/216971733-6301f273-8c52-4b9c-a8ff-d9d440a2e3d0.gif" width="640" height="360">

- Hold it in your hand!
<img src="https://user-images.githubusercontent.com/36753686/216971730-91ce1221-bc68-4af0-b51b-da25ce69a4ac.gif" width="640" height="360">

- Resizing
<img src="https://user-images.githubusercontent.com/36753686/216971720-44d1eed9-4c7f-467c-b0b8-2ba693de8cee.gif" width="640" height="360">

- Drop it in the world and grab with a fist or thumbs up
<img src="https://user-images.githubusercontent.com/36753686/216971712-3f53efe3-8692-4365-af1c-473c26e6f12c.gif" width="640" height="360">

- Drop it anywhere and have it follow you
<img src="https://user-images.githubusercontent.com/36753686/216971704-204f0a05-6ced-48b5-84be-612ec9d53a53.gif" width="640" height="360">
 
 - Customizability made easy!
<img src="https://user-images.githubusercontent.com/36753686/216710639-160766ef-c096-4c22-9faf-93d7e5dc267c.gif" width="640" height="360">

 - Even AudioLink if you want!

https://user-images.githubusercontent.com/36753686/216976742-8a8fc908-cbd8-4d6a-8e37-fb3a487e5f71.mp4

 - Someone have your shaders/custom animations hidden? A fallback message will show instead. 

<img src="https://user-images.githubusercontent.com/36753686/215548765-3c273230-9181-45dd-bf76-51d7d3952314.png" width="640" height="360">

# Requirements 
- **IMPORT THESE BEFORE IMPORTING MY PACKAGE**
- [KillFrenzyAvatarText 1.2.7](https://github.com/killfrenzy96/KillFrenzyAvatarText/releases/tag/1.2.7) 1.3.0+ has shader changes that makes it a bit wonky.
- [VRLabs AV3 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) to make installation much easier.
- [Poiyomi 8.0](https://github.com/poiyomi/PoiyomiToonShader) 
- 12 bits of parameter space (Billboard only), 4 if you opt out for manual resizing.
- This prefab was made with write defaults off, your avatar should too to avoid potential issues. (or turn all write defaults on in the FX)
- PC ONLY. KAT uses a custom shader and the board itself uses constraints which is not quest supported.


# [Video Installation](https://www.youtube.com/watch?v=c032JMb9ef0)


# Discord
Need help? Questions? Comments? You can find me on the TTS Voice Wizard [Discord](https://discord.gg/8ttJKtQaMc) or DM me Frosty704#4638

# Credits
- [KillFrenzyAvatarText](https://github.com/killfrenzy96/KillFrenzyAvatarText)
- [TTSVoiceWizard](https://github.com/VRCWizard/TTS-Voice-Wizard)
- [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)
- [VRLabs World Constraint](https://github.com/VRLabs/World-Constraint)
- [Nintendofan12s](https://www.fanpop.com/clubs/nintendofan12s-fun-stuff/images/37299069/title/windows-95-notepad-photo) for the Windows 95 Notepad image
- [xxpillowprincessxx on Kofi](https://ko-fi.com/post/Windows-95-themed-border-for-webcamwindow-D1D83F6MR) for the Windows 95 window image

