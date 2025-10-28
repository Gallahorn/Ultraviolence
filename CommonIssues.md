![image](/img/UV_title.png)


<p align="center">
[ <a href="https://github.com/Gallahorn/Ultraviolence/blob/main/README.md">Getting Started</a> ]
[ <a href="https://github.com/Gallahorn/Ultraviolence/blob/main/Installation.md">Installation</a> ]
[ <a href="https://github.com/Gallahorn/Ultraviolence/blob/main/PostInstall.md">After Install</a> ]
[ <a href="https://github.com/Gallahorn/Ultraviolence/blob/main/ModSetup.md">Mod Setup</a> ]
[ <a href="https://github.com/Gallahorn/Ultraviolence/blob/main/AdvancedFeatures.md">Advanced Features</a> ]
[ <a href="https://github.com/Gallahorn/Ultraviolence/blob/main/Gameplay.md">Gameplay</a> ]
[ Common Issues ]
</p>

# Common Issues
This page documents common issues encountered during installation and gameplay.  
If you are looking for a specific issue, please use the search function and the table of contents.


# Contents
- [Common Issues](#common-issues)
- [Contents](#contents)
- [Installation](#installation)
  - [I'm stuck at the main menu screen](#im-stuck-at-the-main-menu-screen)
  - [Cannot open instance 'Portable'](#cannot-open-instance-portable)
  - [FileNotFoundError \[WinError3\]](#filenotfounderror-winerror3)
- [Gameplay](#gameplay)
  - [Where is my HUD? Where is 3rd person in driving? How does XY work?](#where-is-my-hud-where-is-3rd-person-in-driving-how-does-xy-work)
  - [I have weird visual effects on my screen](#i-have-weird-visual-effects-on-my-screen)
  - [My difficulty seems to be incorrect](#my-difficulty-seems-to-be-incorrect)
  - [Game crashes during loading / saving in flashback scenes](#game-crashes-during-loading--saving-in-flashback-scenes)


# Installation
This section lists problems that can occur during the installation of the modlist.


## I'm stuck at the main menu screen
... but the main menu isn't showing.

This occurs because you skipped a step in the [Installation](Installation.md) section of the readme.  
You **__NEED__** to start the vanilla game first before starting the modlist in MO2.  

Please refer to the linked section above and make sure you follow **__ALL THE STEPS__**.


## Cannot open instance 'Portable'
If you get an error like this:  
![Image](/img/commonissues/commonissues_specialcharacters.png)

Make sure not to use any special characters in your folder name except for dashes (-).  
Wabbajack can't handle characters like [ ] in folder names.


## FileNotFoundError [WinError3] 
If you get an error like this:  
![Image](img/commonissues/commonissues_winerror3.png)

Your Wabbajack install didn't finish correctly (even if it reported no problems).  
Run Wabbajack again and point it to the same folders you did last time.


# Gameplay
This section lists problem that can occur during the gameplay in Ultraviolence.


## Where is my HUD? Where is 3rd person in driving? How does XY work?
You have been sent here because you asked for support about or reported an **__intended feature__** as a bug.

The mechanic you are describing is not a bug, it is **__the modlist working as intended__**.  
So there is no setting to change, no mod to deactivate, no but to avoid.

Instead, have a careful read of our [Gampelay File](Gameplay.md).  
It will tell you exactly how the dozens of heavily gameplay alterings mods work.

> [!TIP]
> If you still have questions that were not clarified in the Gameplay document, please feel free to ask.  
> But be aware that you will be sent back to the readme if you ask questions which are answered there.  
> We know it's a long file and a lot to read, but it's a big modlist, and we can't read and understand it for you.  
> Help us help you here. Thanks.


## I have weird visual effects on my screen
There is a ton of mods that could cause this. This list integrates a variety of survival-style mods, you will need to balance many factors, such as cyberware-load, humanity, basic needs like hunger, thirst, etc.

Screen effects like flickering etc. commonly indicate a bad physical or mental state of your V.  
Please read our [Gampelay File](Gameplay.md) carefully, it will answer your questions or give you clues what you could look at to improve your situation.


## My difficulty seems to be incorrect
The modlist is engineered for VERY HARD difficulty only.  
So you must remain at VERY HARD at all times.

> [!WARNING]
> If you lower your difficulty, your game might become even harder, because the mods are not tuned to those difficulties.


## Game crashes during loading / saving in flashback scenes
If you have issues loading saves during "Johnny sections" of the game, there is a workaround for it.

- Make a backup of "Ultraviolence Loadorder"  
![Image](/img/commonissues/commonissues_backup_loadorder.png)
- Disable Hyst Angel body  
![Image](/img/commonissues/commonissues_disable_angelbody.png)
- Your save should load fine now
- After you done with the "Johnny section", you need to enable Angel body again (see screenshot above).
- After you enabled angel body, find the backup on the top of the left panel and righ click. 
- Select "Restore Backup", then click yes to overwrite.  
![Image](/img/commonissues/commonissues_restore_loadorder.png)