-----------------------------------------------------
-----------------------------------------------------
PRE-RELEASE 0.0.0a

For SMT
- Set Option 0 to only extract the 'Game/Sound' and 'Game/L10N' folders from base game files
  These are the only relevant files for audio modding
- Added support for BINK files, which would not play in FModel (at the time of writing)
- Changed Option 2 to process files in '1-Put-Your-CUSTOM-Files-Here'
  Removed the old folder out of the equation to reduce clutter/confusion
- Added Option 102/103 for Test/Silence functions
- Added function to Option 0 to auto-delete CUE files
  While they can be replaced and will work ingame, these are not audio files
  They come with issues I simply will not be troubleshooting
  An example is ignoring volume levels. Turning SFX, Music, and Music to 0 wont mute them.
  They all, theoretically, have legitimate audio files that can take their place
- Added capability to add prefixes to files, separated from the base name by a hyphen
- Added function to Option 0 to auto-remove the 'SoundAssets' folder
  This folder contains no actual audio files, and is therefore irrelevant
  (Could change in the future? I doubt it, but Ill readd it if it does)

NOTE: Considering adding support to auto-delete the 'Haptic' folder as well
      The files in there dont seem like they come into play, based off listening to them in bulk
      Have not tested replacing them tho, so I cant say for sure

-----------------------------------------------------
-----------------------------------------------------
PRE-RELEASE v0.0.0b

For SMT
- Switched Option 0 from using Zentools to using retoc
  Zentools took 13 minutes to extract just the sound files
  Retoc took 1 minute to extract ALL the game files (only the sound stuff is kept ofc)
  No-brainer switch lol
- Added function to Option 0 to auto-remove the 'L10N/LANGUAGE/Art' folder
  This folder contains no actual audio files, and is therefore irrelevant
  (Could change in the future? I doubt it, but Ill readd it if it does)
- Added Custom Filename Prefix ability, similar to my Marvel Rivals SMT/CVS Suffix feature
  This allows users to place custom names at the front of files
  Custom name must be separated from the base name using a hyphen
  Example: Base game file name = 'super_jump'
           Prefixd custom name = 'LEAP-super_jump'
  Added this for organization purposes, thats...pretty much it lol         
- 

-----------------------------------------------------
-----------------------------------------------------
INITIAL RELEASE 0.0.1

For General
- Initial Release

-----------------------------------------------------
-----------------------------------------------------
UPDATE 0.0.2

For SMT
- Added DLC file support to Options 1, 102, 103
- (Actually dont know if this is new but) Option 2 can (now?) convert FModel-extracted sound files
  Aka .uasset files that dont have a .uexp companion
- Shortened the names of folders in the 0_EXTRAS folder

NOTES
- Not extensively tested, just wanted to push this out real fast

-----------------------------------------------------
-----------------------------------------------------
UPDATE 0.0.3

For SMT
- Removed Option 0.2.
  It was not working in the script I uploaded, and I threw away the script that it was working in
  Dont care to re-add it plus its the processing time is 4+ hours on a high-end PC
- The former Option 0.1 is now (reverted to being) the default function for Option 0
- (Didnt mention this in the last updated) But Option 2 now brings up a folder selector
  This is so users can choose which folders to convert uasset/uexps to wav files without moving folders/files around
  You can select any folder for this, in case you have uasset/uexps in a different folder than 0-BASE-GAME-Files-Will-Be-Here
- Replaced TEST .wav files with .ogg files to decrease download size (Silent file is still a .wav)
  Originally I was concerned that audio quality would be bad with ogg, buuuut its a test file. Quality is almost irrelevant
- Removed Sound Asset json processing from Option 0
  Didnt work as intended, accidentally left it in the previous update

NOTES
- Not extensively tested

-----------------------------------------------------
-----------------------------------------------------
UPDATE 0.0.4

For SMT
- Fixed Option 2s folder selector. Script can now select a folder that contains subfolders and convert all (eligible) files inside each folder.
- Option 2 now uses a more modern File Explorer windows for their selection steps
- Changed all text files to .md format

NOTES
- Not extensively tested

-----------------------------------------------------
-----------------------------------------------------
UPDATE 0.0.5 (Not released yet, bug fixing smh)

For SMT
- Changed Option 0 to no longer use 0-PAKS folder. Instead, users will navigate to their games Paks folder, and select it
  This is done to save space and time, as before, users needed to copy the pak files, which may have been met with insufficient space warnings
  
NOTES
- Not extensively tested

