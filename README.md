# About
![billboardheaderredux3 copy](https://github.com/Frosty704/Billboard/assets/36753686/fe102ccf-64d5-4490-9ac5-c187cad653cf)
![VRChat_2023-09-15_05-33-16 125_2560x1440](https://github.com/Frosty704/Billboard/assets/36753686/f083a185-4c65-4800-8cd6-19efa9fd50b4)


# What/who is this for?
[![Downloadv4](https://img.shields.io/badge/DOWNLOAD-Billboard_V4-brightgreen)](https://github.com/Frosty704/Billboard/releases/download/main-v4/Frosty.Billboard.V4_Release3.unitypackage)
[![Tutorial](https://img.shields.io/badge/-Installation%20Tutorial%20Video-blue)](https://www.youtube.com/watch?v=ydBXFQ7-eQU)

Frosty's billboard is a ready-to-go speech bubble prefab for the [KAT (KillFrenzyAvatarText)](https://github.com/killfrenzy96/KillFrenzyAvatarText), making it easier to converse as a mute for more direct conversation (no big chatbox above your head!)

- Paired with free speech-to-text OSC apps such as [TTS-Voice-Wizard](https://github.com/VRCWizard/TTS-Voice-Wizard) or [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)

- Makes extensive use of VRChat's avatar dynamics, allowing you to drop the bubble in the world, and pick it back up with either hand seamlessly

- Focuses on being easy to customize to your liking and looking good while staying optimized (1 material for the board itself)

- Focuses on being easy as possible to setup <sup>until i can code an autoinstall script</sup>

- I made this because I don't believe in paying to talk

# Requirements and Performance
- A program able to output to the KAT, such as [TTS-Voice-Wizard](https://github.com/VRCWizard/TTS-Voice-Wizard), [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT), [KatOscApp](https://github.com/killfrenzy96/KatOscApp/releases)
- [KillFrenzyAvatarText 1.3.2](https://github.com/killfrenzy96/KillFrenzyAvatarText/releases/tag/1.3.2)
- [VRLabs AV3 Manager](https://github.com/VRLabs/Avatars-3.0-Manager/releases/) for installation
- [Poiyomi 8.1](https://github.com/poiyomi/PoiyomiToonShader/releases) 
- 55 bits of parameter space _**minimum**_, (ideally 87 for not painfully slow writing speed)
- The animator uses Write Defaults off (as does KAT), It is a bad idea to mix WD on and WD off (stuff will break)
  - Either make a reset layer and use write default off logic <sub>the correct option</sub>, or turn on all write defaults with something like [VRLabs AV3 Manager](https://github.com/VRLabs/Avatars-3.0-Manager)
- PC only

Performance:
- 500 polygons
- 4 material slots
- 55 bits of parameter space minimum
- 6 constraints

Required parameter space will depend on how fast you want the text to render
- At _**minimum**_ you want 4, for most users 8, and 16 if you have the parameter space to spare
  - 4 (55 bits) 
  - 8 (87 bits) **Most recommended**
  - 16 (151 bits)

![headergif](https://user-images.githubusercontent.com/36753686/236354169-58335675-8ccc-4672-805b-977ed39163c5.gif)


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

 - Customizability made easy! [More examples here](https://github.com/Frosty704/Billboard/wiki/1.-Home-%7C-Showcase)
<img src="https://user-images.githubusercontent.com/36753686/216710639-160766ef-c096-4c22-9faf-93d7e5dc267c.gif" width="640" height="360">

![w11 mats](https://user-images.githubusercontent.com/36753686/236354192-58036f1f-5e04-4ee3-891c-3e78bd6fae45.gif)

 - Someone have your shaders or custom animations hidden? No worries, a fallback message will show instead. 

<img src="https://user-images.githubusercontent.com/36753686/215548765-3c273230-9181-45dd-bf76-51d7d3952314.png" width="640" height="360">

# Discord
Need help? Questions? Comments? You can find me at:

TTS Voice Wizard [<img src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a6ca814282eca7172c6_icon_clyde_white_RGB.svg"  width="20" height="20"> Discord](https://discord.gg/8ttJKtQaMc)

I5UCC's (TextboxSTT) [<img src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/636e0a6ca814282eca7172c6_icon_clyde_white_RGB.svg"  width="20" height="20"> Discord](https://discord.gg/rqcWHje3hn) 

and or DM me frosty704

# Todo
update world constraint to [WorldSync](https://github.com/JuzoVR/WorldSync)

actual showcase and usage ingame tutorial

full video tutorial on how to make it work with ttsvoicewizard and textboxstt

longterm auto install script

# Credits
- [KillFrenzyAvatarText](https://github.com/killfrenzy96/KillFrenzyAvatarText)
- [TTSVoiceWizard](https://github.com/VRCWizard/TTS-Voice-Wizard)
- [VRCTextboxSTT](https://github.com/I5UCC/VRCTextboxSTT)
- [VRLabs World Constraint](https://github.com/VRLabs/World-Constraint)
- [Nintendofan12s](https://www.fanpop.com/clubs/nintendofan12s-fun-stuff/images/37299069/title/windows-95-notepad-photo) for the Windows 95 Notepad image
- [xxpillowprincessxx on Kofi](https://ko-fi.com/post/Windows-95-themed-border-for-webcamwindow-D1D83F6MR) for the Windows 95 window image

