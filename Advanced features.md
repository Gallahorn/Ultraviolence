![Loading screen 4](https://github.com/Gallahorn/Ultraviolence/assets/13502434/17f09e42-3cac-4ff8-bf04-130578da4acd)
<br>
<br>
<br>
<br>

## Quicklinks

- [Install with GOG version](https://github.com/Gallahorn/Ultraviolence/blob/main/Advanced%20features.md#installation-with-gog-version)
- [How to update the list](#how-to-update-the-list)
- [How to use tattoos and body overlays](#how-to-use-tattoos-and-body-overlays)
- [Resetting mods](#resetting-mods)
- [How to unlock romance options](#how-to-unlock-romance-options)
- [How to use paired poses](#how-to-use-paired-poses)
- [Important Keybinds!!!](#keybinds)
- [Optional Keybinds and Mod Configurations](#optional-keybinds-and-mod-configurations)

<br>
<br>
<br>
<br>

# Installation with GOG version.

## Make sure you have all DLC installed.
    If you dont have REDmod go to the store and "buy" it its free.
    Then launch the game once and login to Redlauncher if prompted for it.
![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/2c140828-c499-485b-a7e6-79618879d2f9)

## Enable modding.
    Then you need to enable modding under Features section in GOG.
![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/51e78720-5059-4467-8538-a31c693ba24d)

## Then continue from [here](https://github.com/Gallahorn/Ultraviolence/tree/main?tab=readme-ov-file#make-sure-you-read-everything-here-and-do-everything).

<br>
<br>
<br>
<br>

![Updatelist](https://github.com/Gallahorn/Ultraviolence/assets/13502434/ebfd59a4-3064-4ebf-b6b5-08c28908265f)




# How to update the list:

## Before you update your list
Before you update your list you will need to backup some files from overwrite. The files you need to backup are found in:
- (modlist-path)\overwrite\bin\x64\plugins\cyber_engine_tweaks\mods\StealthRunner\sessions
- (modlist-path)\overwrite\bin\x64\plugins\cyber_engine_tweaks\mods\stocks\data\persistent

These should be backed up in a way that preserves their place in the modlist file paths and will survive the overwriting when Wabbajack updates the list. Create an empty mod inside MO2, and name it like so (the `[NODELETE]` part of the name ensures Wabbajack will not overwrite this folder. Right click on the "Ultraviolence Settings" separator and select `All mods->Create Empty Mod Inside`:

![empty-mod-creation](https://github.com/user-attachments/assets/a8d6f545-625b-4717-a431-feb65445e0db)

![name-create-mod](https://github.com/user-attachments/assets/a934864d-0351-4154-9763-06cf157a3291)

![empty-mod-result](https://github.com/user-attachments/assets/50533a67-640b-462e-9023-1380f3e7aae1)

Next, create a folder structure inside this mod that duplicates the paths of the data you need to back up. Right click on the mod you've created, and select `Open in Explorer`. Then just create new folders inside to match the expected path. The full structure should look like this:

![folder-structure-cropped](https://github.com/user-attachments/assets/7c4a2582-50f0-4372-bb77-bb3de4b18908)

Now you're ready to move the files from overwrite to the mod you've made. Open the overwrite directory in the same way you did with your mod, right click on "overwrite" and select `Open in Explorer`. Navigate down to the `StealthRunner\sessions` and `stocks\data\persistent` folders, and you should see that they are populated with many *.lua script files. The easiest thing to do is simply copy the `sessions` and `persistent` folders into their matching place in your mod.

The end result is that both folders in your mod should now be populated with the same folders and scripts you saw in overwrite.

![overwrite-contents](https://github.com/user-attachments/assets/d858de78-724a-41de-a64b-7ff51fdf9c2f)

![mod-copy-result](https://github.com/user-attachments/assets/65f66bc1-318e-49c4-90cf-9ae0c0403b17)

Finally, once you are certain you've backed up what you need (and any character presets you've made!), you can clear out the overwrite folder.

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/a222e637-437e-4553-b28c-d71fe3168342)

## After that you will need to go do [Step 1](https://github.com/Gallahorn/Ultraviolence/blob/main/README.md#1-make-sure-you-have-a-clean-cyberpunk-installation) in the main readme. Please keep in mind that Step 1 ensures you have a clean installation, and includes instructions for backing up your saves.

    Very important to do this step to make sure your game folder is clean.

## Updating your list

    To update your list you just need to start Wabbajack like normal and install the list with overwrite checked
    and the install paths pointing to the right folder same with the download folder.
![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/08397dfc-23be-4725-af9d-167c0050d5d2)

## After you updated the list you might need to re-order your tattoos or overlays again. Check below for instructions.

## If using an existing save, go back to V's original H10 apartment, to reactivate and make sure Lizzies Braindance and Romance messages Extended are working.
After each update, go back to the H10 (V's original apartment) and you should see a popup about Lizzies Braindances, and other mods that activate upon entering this zone, _if those mods have updated_. Enter the apartment, turn on the TV, and you should receive messages about Judy Romance Messages Extended and Panam Romance Messages Extended. If this doesn't happen, leave the apartment and re-enter just to be sure, but it is also the case that these messages will not display if none of the mods have updated with the list update.



<br>
<br>
<br>
<br>

![Tattoos and Overlays](https://github.com/Gallahorn/Ultraviolence/assets/13502434/e76f3427-2c73-49a4-95e8-240ed4b454c1)




# How to use Tattoos and Body overlays

    The list currently supports VTK overlays but you can only have ONE active at the time
    and to change it you will need to do the following steps.

## 1. Ensure you are using the default vanilla skin option

    For overlays, the vanilla version of UNIVERSAL SKIN TONE must be selected; other options
    produce visual errors when used with overlays.
    
![image](https://github.com/user-attachments/assets/d95a1d84-1eb0-4cf5-8a02-bebee5aa993b)

## 2. Find the tattoo you like and check it in MO2

    For any mod, you can right-click, and select 'Visit on Nexus' to view the mod on Nexus.
    The name of the mod will correspond to a specific file from the mod's page.

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/9019a472-52e4-406b-9185-51a906a20f3f)

## 3. Open Red4-conflicts and resolve load order

![image](https://github.com/user-attachments/assets/e88584c3-7a5f-4221-a5a1-f010b93d0b65)


        You will need to go to the bottom of the left panel and find your overlays
        and drag them up to the top like in the second image. 
        Currently you can only move the files one at the time.
        The overlays should sit above most files, especially any body or head related files.
        After you moved each of the files, you can close Red4-conflicts and start the game.
        The overlays will always be present on your V, like a layer of skin texture underneath
        tattoo options applied in character creator.
        
![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/c5d6e099-b669-496e-b159-8d13eb372831)

![image](https://github.com/user-attachments/assets/648dc25d-35c1-46ef-bb90-2fc88bfec59d)

<br>
<br>
<br>
<br>

![Resetting](https://github.com/Gallahorn/Ultraviolence/assets/13502434/6f7252a3-0070-414c-93ba-38d630247f1a)

# Resetting mods

## How to reset Lizzies Braindance.

        Sometimes after an update you will need to reset Lizzie's Braindance

        Reseting mod
        If you can't find the NPC for BD inside the Lizzie's, use this CET command to reset the quest:

        Game.GetQuestsSystem():SetFactStr("lizzies_bds_reset", 1)

        Then save the game and load the newly created savegame. NPC should be available again.

        If you don't have any options with the NPC, use this command:

        Game.GetQuestsSystem():SetFactStr("lizzies_bds_active", 0)


<br>
<br>
<br>
<br>

![Romance](https://github.com/Gallahorn/Ultraviolence/assets/13502434/ea4d9da6-6cc8-424a-9dc2-b9d9dcbf2654)

# How to Unlock Romance Options

    To Unlock Non-Canon Romances the list uses "Non-Canon Romances Enchanced
    to use it go to the mod menu and then select NCRE menu and select the partners you want to unlock.
    
<br>

![image](https://github.com/user-attachments/assets/364e8c47-212a-4318-ba0c-eb25b3761e64)

<br>
<br>
<br>
<br>

![paired](https://github.com/Gallahorn/Ultraviolence/assets/13502434/b0ded6ab-bd70-488c-b2b9-26eba7be7a0f)

<br>

# How to use paired poses

    First open Photomode and place your V and pick a pose mod that supports pair poses. 
    Normally they are named FF,MF,MBF pick the right one for the right npc you are planing on pairing with.
    FF  = Female/Female
    MF  = Male/Female
    MBF = Malebig/female
    
<br>

![image](https://github.com/user-attachments/assets/090d1271-048d-4474-ac7c-31467ffcd02a)


<br>

    Then you click the Characters menu and pick the npc you want to pair with
    
<br>

![image](https://github.com/user-attachments/assets/64dc59d7-0fcb-403f-a2c5-51d9f4d1d665)


<br>

    Then you find the same pose pack and find the paired pose for the V pose you picked.
    the paired poses are named a bit different from pack to pack so you will need to 
    figure that one out.
    Then match the position to the same numbers as V are positioned and they should match up.

<br>

![image](https://github.com/user-attachments/assets/fd79c7e7-97f0-4792-b529-c11d5b3b8255)


<br>

![Cyberpunk2077 2025-01-24 20-19-23](https://github.com/user-attachments/assets/53077ebe-a278-4ecf-aff8-5a9194aa38d7)

<br>

<br>
<br>
<br>

![Keybinds](https://github.com/Gallahorn/Ultraviolence/assets/13502434/77c608e3-c92a-4e06-b075-c0d46e12b45f)




# Keybinds

## Keybinds Already in Place That You Should Know

    LimitedHud - 
    
        F6 to show/hide minimap 
        F8 to show/hide UI after your settings.

    Advanced Driving Controls -
        
        This mod makes the driving a lot smoother and more controller like.
    
        Cars:
            
        Accelerate slower with just W.
        Acclerate Faster With LShift.
        Brake slower with S.
        Brake faster with LCTRL.

        Bikes:
            
        Accelerate slower with just W.
        Acclerate Faster With LShift.
        Brake slower with S.
        Brake faster with LCTRL.
        Lean Forward with UP. (You need to rebind to UP, as LShift doesn't work anymore)
        Lean Backward with DOWN  (You need to rebind to DOWN, as LCTRL doesn't work anymore)

  <!--  Huditor - 
    
        Make sure you turn on the HUD and minimap with the LimitedHud keys before
        trying to move the HUD around.
              
        Shift-U and then arrowkeys left and right to select different objects. 
        Scroll to make them bigger/smaller.
        Drag around with the mouse to move them.
        X to reset all the Widgets.
    -->
<!--    Enchanced Vehicle System

        F1 - Double Tap to toggle power state.
             Hold to turn engine on/off
             Hold Longer after engine stop to trigger headlight shutoff

        F1+1 - Multi tap to toggle single light settings
               1. Headlights 
               2. Tail lights 
               3. Utility lights 
               4. Blinker lights 
               5. Reverse lights 
               6. interior lights
               
               Hold Toggle all lights
        

        F2 - Open doors
             Multi tap toggle single door
             1. Driver 
             2. Front Passanger 
             3. Back Left 
             4. Back Right
             
             Hold Toggle all doors

        F2+2 - Multi tap to toggle hood/trunk/spoiler
               1. Hood 
               2. Trunk 
               3. Spoiler
               
               Hold Toggle hood and trunk

        F3 - Multitap to toggle windows
             1. Driver 
             2. Front Passanger 
             3. Back Left 
             4. Back Right
             
             Hold toggle all windows

        F4 - Press Toggle interior lights
             Hold toggle crystal dome.

        Crystal Coat Key (default key Y)
             2. Toggle crystal coat on/off
             3. Display Color Menu

             Hold Display Color Menu 
        -->

## Keybinds You Must Set or are Recommended to Set

Cyber Engine Tweaks includes an overlay with multiple menus for mods like LUT Switcher, Apearnce Mod Manager, and Ultraplus, among many others. When you start the list for the first time, Cyber Engine Tweaks will ask you to assign a keybind to toggle the menu overlay. We recommend binding this to the 'Enter / Return / Line Break' key.

    CET (Cyber Engine Tweaks) - 
    
        Should pop up so you can pick it when the game starts.
    
    Flashlight - 
    
        Keybind it to what you want in CET Bindings. Suggested keybind: 'L'.

![cet-keybind-menu](https://github.com/user-attachments/assets/2922cb8f-158c-4aa7-83cd-d8032fa8f037)

## Optional Keybinds and Mod Configurations

Use CET for most mod related keybinds. Keep in mind that there are two mod configuration menus in the ESC menu, 'Mods' and 'Mod Settings'. Settings for any mod will be in one of these three places.

### Flashlight

Some of the graphical mods change the lighting you might be used to from Vanilla, and depending on your choice of LUT, certain areas of the game may be very dark. The flashlight can be toggled with a binding you set in CET. The flashlight can also be configured for greater brightness, angle, and its color can be changed. Flashlight settings are found in `ESC->Mods->Flashlight` (if you don't see it, scroll on the top through the tabs).

![flashlight-settings](https://github.com/user-attachments/assets/b140d443-4f97-47ed-a3d6-6af0b05880da)

### LUT Switcher

LUT Switcher, found in CET, allows you to select from the many different LUTs available, and bind hotkeys for switching in game and photo mode. LUT Switcher's own instructions are also attached to the panel in CET.

![lut-instructions](https://github.com/user-attachments/assets/40c7b422-5852-47b5-8d1f-e07cbd5baba4)

Use the star icons to set favorite LUTs from the listed selections available. Follow the instructions for assigning keys and secondary/menu/photo specific LUTs.

![lut-favorites](https://github.com/user-attachments/assets/31e18a94-71e6-44e9-8014-088aee84ffdf)

- Left click a LUT to activate it
- Right click to set a secondary LUT
- Middle click to set a LUT used only in menus
- You can set the LUT switcher keybinds in CET like so, according to these suggestions or to your preference.

![lut-switcher-bindings](https://github.com/user-attachments/assets/82ad5441-e26b-4784-a171-e7b8e0cff18c)

### Main Quest Tracker

Do you get annoyed when after completing a side objective or reaching a custom map marker, the game will automatically select the main quest marker again? Then this mod and setting are for you. Open CET, and find the collapsed panel for Main Quest Tracker (usually nested and floating near the top of the screen). Check the first box to prevent automatic re-tracking. Other settings pictured may be useful to you.

![quest-tracking-toggle](https://github.com/user-attachments/assets/63466c36-65c5-48c7-8bfd-cb178a26b40e)

The main tracking function toggle can also be set in CET; by default, it should be `Numpad 5`.

![quest-tracking-keybind](https://github.com/user-attachments/assets/212b2528-8085-464d-8c6f-4ddf4d13fe24)

### Ultra+ (Ultra Plus Best Performance and Visuals for Everyone)

Ultraplus is a graphical enhancement/configuration tool that provides rendering options beyond what is available in the vanilla Cyberpunk 2077 settings menu. It will not magically make your game faster. It may cause crashes. The results are subjective, situational, and you must tailor the settings to what works for your machine. That said, from our limited testing, it seems pretty stable and performant. Ultraplus is mostly targeted towards ray and path tracing options, but also includes optimizations for rasterization only configurations as well.

The best option is to start be reading the mod page, which has extensive explanation and help for how to configure it. Read the stickied posts for support, and FAQ. For those running ray-tracing, also read the associated article on choosing and configuring path tracing options.

- [Ultra Plus Mod Page](https://www.nexusmods.com/cyberpunk2077/mods/10490)
- [Path Tracing Choices Article](https://www.nexusmods.com/cyberpunk2077/articles/1027)

Please note that Ultraplus will not necessarily enhance performance, but it does allow you to fine tune towards your performance limit, and has a frame rate target option that the mod uses to dynamically tweak settings when it has more or less overhead available. Start with a configuration that matches your current settings, and work from there.

To configure Ultraplus, open CET using the `Enter` key, and look for the Ultraplus configuration panel. Select options according to your current configuration, target preferences, and GPU RAM. For most changes, you must exit CET, open the game graphics settings, and simply hit `Apply` to finalize the Ultraplus changes.

![ultra-plus-example](https://github.com/user-attachments/assets/43fe3c38-d6bf-45e3-a55f-b74be9498de7)

### Upscaler Options for AMD and older NVIDIA hardware

[FSR3 Frame Gen for Cyberpunk 2077 (DLSS Enabler 2077 Edition)](https://www.nexusmods.com/cyberpunk2077/mods/14726?tab=description)

Please read the mod page description carefully.

If running Cyberpunk 2077 on AMD or older NVIDIA hardware, two optional mods in the list can unlock more options for upscaling and frame generation that would otherwise not be an option for your GPU. Enable one of these appropriate for your GPU.

![image-upscaler-mods](https://github.com/user-attachments/assets/3ad17dd5-1d0c-4fe3-b563-da2640e82571)

IMPORTANT STEP FOR AMD GPUS: In the AMD version of the mod, there is a registry file that must be run. This only needs to be run once; the change will be permanent (and benign) unless reversed. Open the mod folder and run `DisableNvidiaSignatureChecks.reg`. If for some reason you need to reverse this, run `RestoreNvidiaSignatureChecks.reg`.

With the mod properly enabled, you should now have greater choice of upscaler and frame generation options.

![image-graphics-upscaler-frame-gen-settings](https://github.com/user-attachments/assets/b27d0c26-76cf-4610-98ae-e13eca232a2d)

<br>
<br>
<br>
<br>



