# About
![billboardheaderredux2](https://user-images.githubusercontent.com/36753686/235922298-06560e71-f736-4e84-9e72-04796e7ba5fd.png)


[![Downloadv4](https://img.shields.io/badge/DOWNLOAD-V4(MAY%20BE%20BUGGY)-orange)](https://github.com/Frosty704/Billboard/releases/tag/main-v4)
[![Tutorial](https://img.shields.io/badge/-Installation%20Tutorial%20Video-blue)](https://www.youtube.com/watch?v=ydBXFQ7-eQU) 


## Frosty's billboard is a speech bubble prefab for the [KAT (KillFrenzyAvatarText)](https://github.com/killfrenzy96/KillFrenzyAvatarText) making use of VRChat Avatar Dynamics and Unity Constraints, making it easier to converse as a mute without being a global broadcast via the in-game chatbox

It uses:
- 500 polygons
- 4 material slots
- 14 bits of parameter space
- 6 constraints

Required parameter space for the KAT text system will depend on how fast you want the text to render,
- At the least,  you ideally want 4, for most users 8, and 16 if you have the parameter space to spare
  - 4 (41 bits)
  - 8 (73 bits)
  - 16 (137 bits)
  


![headergif](https://user-images.githubusercontent.com/36753686/236354169-58335675-8ccc-4672-805b-977ed39163c5.gif)



# Recommended OSC Speech to Text programs

## [TTS-Voice-Wizard](https://github.com/VRCWizard/TTS-Voice-Wizard)
 An OSC program allowing speech to text, speech to text to speech, and text to text
 making use of one of five speech recognition methods, 
   - Microsoft Azure
   - OpenAI's Whisper 
   - Vosk 
   - Web Captioner
   - System Speech.
   - Emote Support
   - Many more cool & quality of life features such as chatbox media integration
 
 ##
 
 ## [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)
   An OSC program making use of OpenAI's Whisper which runs locally on your GPU or CPU to transcribe speech with low latency
   - Simple setup
   - Intuitive SteamVR binding system, press to transcribe, hold to clear
   - Emote support
   - Realtime speech to text

# Features & Showcase

- Speech to Text & emotes using [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)

![1_stt](https://user-images.githubusercontent.com/36753686/223066845-2eddf954-c953-4dd4-816c-e0fbb5684ec0.gif)


- Hold it in your hand and drop it in the world, grab with a fist or thumbs up!

![lefthandgrab](https://user-images.githubusercontent.com/36753686/236354267-9cea9674-2851-42f4-b93f-885036ac58a5.gif)

- Resizing
<img src="https://user-images.githubusercontent.com/36753686/216971720-44d1eed9-4c7f-467c-b0b8-2ba693de8cee.gif" width="640" height="360">

- Drop it anywhere and have it follow you
<img src="https://user-images.githubusercontent.com/36753686/216971704-204f0a05-6ced-48b5-84be-612ec9d53a53.gif" width="640" height="360">
 
- Typing Dots indicator with [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT) and [TTS-Voice-Wizard](https://github.com/VRCWizard/TTS-Voice-Wizard)

![typingdotsindicator](https://user-images.githubusercontent.com/36753686/236354712-a617f28c-75c1-4591-86de-860f6feb9fcc.gif)

 - Customizability made easy!
<img src="https://user-images.githubusercontent.com/36753686/216710639-160766ef-c096-4c22-9faf-93d7e5dc267c.gif" width="640" height="360">

![w11 mats](https://user-images.githubusercontent.com/36753686/236354192-58036f1f-5e04-4ee3-891c-3e78bd6fae45.gif)

 - Someone have your shaders/custom animations hidden? A fallback message will show instead. 

<img src="https://user-images.githubusercontent.com/36753686/215548765-3c273230-9181-45dd-bf76-51d7d3952314.png" width="640" height="360">

# Requirements 
- **IMPORT THESE BEFORE IMPORTING MY PACKAGE**
- [KillFrenzyAvatarText 1.3.2](https://github.com/killfrenzy96/KillFrenzyAvatarText/releases/tag/1.3.2)
- [VRLabs AV3 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) to make installation much easier.
- [Poiyomi 8.1](https://github.com/poiyomi/PoiyomiToonShader/releases) Specific version used is 8.1.163
- 14 bits of parameter space (Not including the KAT system parameter requirement)
- This prefab was made with write defaults off, your avatar should too to avoid potential issues. (or turn all write defaults on in the FX)
- PC ONLY. KAT uses a custom shader and the board itself uses constraints which is not quest supported.


# [Video Installation](https://www.youtube.com/watch?v=ydBXFQ7-eQU)


# Discord
Need help? Questions? Comments? You can find me at:

TTS Voice Wizard [<img src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a6ca814282eca7172c6_icon_clyde_white_RGB.svg"  width="20" height="20"> Discord](https://discord.gg/8ttJKtQaMc)

I5UCC's (TextboxSTT) [<img src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a6ca814282eca7172c6_icon_clyde_white_RGB.svg"  width="20" height="20"> Discord](https://discord.gg/rqcWHje3hn) 

and or DM me Frosty704#4638

Feel free to join the [group!](https://vrc.group/FROSTY.8688) would love to meet anyone using my prefab


# Credits
- [KillFrenzyAvatarText](https://github.com/killfrenzy96/KillFrenzyAvatarText)
- [TTSVoiceWizard](https://github.com/VRCWizard/TTS-Voice-Wizard)
- [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)
- [VRLabs World Constraint](https://github.com/VRLabs/World-Constraint)
- [Nintendofan12s](https://www.fanpop.com/clubs/nintendofan12s-fun-stuff/images/37299069/title/windows-95-notepad-photo) for the Windows 95 Notepad image
- [xxpillowprincessxx on Kofi](https://ko-fi.com/post/Windows-95-themed-border-for-webcamwindow-D1D83F6MR) for the Windows 95 window image

