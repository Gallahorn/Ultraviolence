![image](/img/UV_title.png)


# UNOFFICIAL Linux Installation Instructions
This guide will provide instructions on how to getting the list installed on Linux.  
The instructions in this guide are curtesy of Kross (Kross0280) on the Support Discord, they are not meant as a definitive guide, more like guidelines since every distribution is different and things are very dependant on your setup.

> [!CAUTION]
> **THE UV TEAM DOES NOT OFFICIALLY SUPPORT LINUX!**  
> 
> Any and all support questions regarding installs on Linux have to go to #uv-modify on discord.
>
> These guidelines are **NOT** provided by the UV dev team, they are curtesy of a discord user and put in this Readme by request for your convenience.

# Contents
- [UNOFFICIAL Linux Installation Instructions](#unofficial-linux-installation-instructions)
- [Contents](#contents)
- [Instructions](#instructions)

# Instructions
1. Run Vanilla game and accept EULA and disable the settings outlined in the Windows readme (or later disable Bloat Begone and Load Begone mods for first run).
2. Install protontricks via Flatpak or pacman.
3. Install ProtonGE using ProtonQT.
4. Install Ultraviolence using Jackify.
5. Add ModOrganizer2.exe as non-Steam game and force ProtonGE or other proton version.
6. Run protontricks and install 3dcompiler_47, dotnet7, dotnet8, dotnet9, vcrun2022 for ModOraganizer2.exe.
7. Run protontricks -> select modorganizer prefix ->  run winecfg -> add version to library overrides.
8. Set WINEDLLOVERRIDES="winmm=n,b;version=n,b" %command% for ModOrganizer in Steam.
9. Enojoy. Everything should work now.