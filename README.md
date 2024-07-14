<!-- EN | [中文](CN_README.md) -->

# Zenless-Zone-Model-Importer (ZZMI)
Tools and instructions for importing custom models into ZZZ.

#### DISCLAIMER: I strongly recommend only using private servers for modding. Using these tools on official ZZZ servers carries a high risk of being banned. I do not condone the use of these tools and programs on official servers, and take no responsibility for any consequences as a result if you do. 

ZZMI is a version of 3DMigoto that I have modified to be compatible with ZZZ.

 Feel free to use or modify any of the scripts on this repo as you wish, though please give credit if you use these programs in your projects. I am continuing to update this page with new features and fixes, so check back often.
<!-- 
Troubleshooting guide: [Troubleshooting](Guides/Troubleshooting.md)

For a simple walkthrough of removing a portion of a character mesh using these tools, see [Mona Walkthrough](Guides/MonaWalkthrough.md). For an intermediate walkthrough of creating custom weapons, see [Custom Weapon Modding Walkthrough](Guides/BananaWeaponWalkthrough.md). For a more advanced example of importing a custom model, see Cybertron's great video walkthrough [here](https://www.youtube.com/watch?v=7ijMOjhEvBw) and SinsOfSeven#3164 annotated transcript and troubleshooting guide [here](https://rentry.co/3dmigPlug_AnimeGame). -->

Model files for the importer are located at [ZZ-Model-Importer-Assets](https://github.com/leotorrez/ZZ-Model-Importer-Assets)

## Installation Instructions (3DMigoto)

1. Download a 3dmigoto .zip from [releases](https://github.com/SilentNightSound/GI-Model-Importer/releases) and extract it. I have provided two versions:
   - "3dmigoto-GIMI-for-development.zip" is a development version intended for creating mods which has all features turned on (including the green text at the top and bottom of the screen) but is slower
   - "3dmigoto-GIMI-for-playing-mods.zip" is a version of the program indended for playing mods which has development features turned off (no green text) but is faster

2. Double click "3DMigoto Loader.exe" to start the loader, then start up Genshin through the GenshinImpact.exe. If everything is correct so far, 3DMigoto should be injected into the game and you should see a green text overlay (only if using the "for development" version, the "for playing" version does not show the green text):

![image](https://user-images.githubusercontent.com/107697535/174324967-049b9879-c537-4bd0-b190-4ad7444fb8f1.png)

<img src="https://user-images.githubusercontent.com/107697535/174325193-1f58ab2c-86f8-4ce9-8697-6e7d140b2014.png" width="800"/>

   - Note: some people have reported an issue where the loader lists that it was unable to verify if 3dmigoto was loaded. This does not mean that 3dmigoto failed to inject - if the green text and mods show up, there are no issues and you can close the command prompt

![image](https://user-images.githubusercontent.com/107697535/175563985-1e7d1298-08d0-4334-b6e8-c69769e3877a.png)

3. Installation complete! You should now be able to load custom resources and override textures and shaders with 3DMigoto. To add mods, place them in the Mods folder (one mod per character at a time) and press F10 to load them in game:

![image](https://user-images.githubusercontent.com/107697535/175611402-c3f600ca-4136-4561-b33a-f4edf6153d1a.png)

&nbsp;
## Installation Instructions (3DMigoto Blender Plugin)

In order to modify game models, you need to also setup your Blender plugins and environment. The 3DMigoto plugin works with Blender 3.6+

1. Download and install Blender

2. Download and install the modified 3DMigoto plugin (XXMI-Tools) from [releases](https://github.com/leotorrez/XXMI-Tools/releases). You can install an add-on in Blender by going to Edit -> Preferences -> Add-Ons -> Install, then selecting the .py file. 

3. If done correctly, you should see 3dmigoto in the plugin list as well as new options in the import and export menus

<img src="https://user-images.githubusercontent.com/107697535/174328624-ccb14ded-57b2-4ac7-b0a0-0de118119174.png" width="800"/>

<img src="https://user-images.githubusercontent.com/107697535/174329025-981a1a9f-7c56-4f44-804b-1b0394b8bd33.png" width="800"/>

&nbsp;
## Usage Instructions

See [Usage Instructions](Guides/UsageInstructions.md)

Also, if you any questions about modding come join the Genshin modding discord at https://discord.gg/agmg. The only verification is that you can 3dmigoto ZZMI working by following the steps above.

&nbsp;
## Acknowledgements

Huge thank you to DarkStarSword, bo3b and Chiri for 3dmigoto and SilentNightSound for GIMI where this is based on!
