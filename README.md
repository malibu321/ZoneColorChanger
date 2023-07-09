# ZoneColorChanger

https://steamcommunity.com/workshop/filedetails/?id=2867708583

This is a continuation of the mod [Zone Colours](https://steamcommunity.com/sharedfiles/filedetails/?id=421443866).

Zone Color Changer is a mod for Cities Skylines which allows changing the default colors of the rico (residential, industrial, commercial, offices) zones. Useful for players with color issues like color-blindness or who don't like the default colors. 

Press Ctrl+K or click UUI Button.

The mod provides an option to change the color of each zone type, zoning panel icons are not affected. (would be a great feature) The color profile is stored in in %localappdata%\Colossal Order\Cities_Skylines\ModConfig\zone-color-changer.cfg like the original mod did.

The old mod did only save at OnLevelUnloading(), fast return to desktop and crashes would not save the profile, so three buttons (I could not figure out how to load custom sprites, I gave up) were added:

- save current (and overwrite a previously saved) color profile to the .cfg file
- load previously saved color profile from the .cfg file
- reset to default color profile (but do not save the profile)
