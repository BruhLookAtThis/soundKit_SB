-----------------------------------------------------
-----------------------------------------------------
PRE-RELEASE v0.0.0a

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
INITIAL RELEASE v0.0.1

For General
- Initial Release
