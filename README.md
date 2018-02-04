# Goonmaker

Ground-Up rebuild of Fapinator 9000 (https://github.com/PupBrutus/Fapinator9000) code based around popper trainer/hypno/gooning video effecting/compositing


Requirements: 
=========
* VVVV 64bit atleast v34.106 https://vvvv.org/downloads
	* Once downloaded and extracted run Setup.exe to install all VVVV's pre-reqs	
* DX-11 Runtime installed: https://www.microsoft.com/en-us/download/details.aspx?id=48145 
	* I've included a copy of the installers in the pre-reqs folder	
* Addon-ons - I've included all required VVVV plugins/addons in the "Addon-Pack-Custom" folder. 
	* Simply copy the "addonpack" and "packs" folders into the root VVVV directory (vvvv_VERSION_Number/packs and vvvv_VersionNumber/addonpack)
* VLC Video player 64 bit version - https://www.videolan.org/vlc/ (direct package link: https://get.videolan.org/vlc/2.2.8/win64/vlc-2.2.8-win64.exe) 
	* if you have the 32 bit version you may need to remove it and install the 64 bit version
	
TIPS
=========

* For those unfamiliar with VVVV you will use a right-click (or left click if using left-handed mouse) to interact with any visual controls (buttons, toggles) or double click to interact with numarical controls in the program. I would reccomend running through the hello-world for VVVV as it will explain what you're seeing alot more: https://vvvv.org/documentation/tutorial-hello-world

* When you first load the VVVV application you should see the "intro file" with "Helo new user..." simple middle click (scroll wheel click) and select "Open" from the context menu and open the Goonmaker.v4p file. 

* To save your current configuration press your middle mouse button (your scroll wheel) and you should get the larger menu with the option to save. 

* If you see any of Red colored nodes when you first start it means that you're missing pre-reqs. Be sure that all runtimes are installed correctly and you've copied over the Addon-Pack-Custom sub-folders.

* It might not run perfectly on the first-run VVVV is very particular like that. First load the application and specify your video directory with the VideoDir box at the top of the window then save, and reload the application (CTRL+R). 

* I do re-encode most of my own videos using either Adobe Media Encoder or https://handbreak.fr - Depending on your system using HD porn with settings that force it to skip/change video often can cause the application to crash, but usually MPG4 at 720 or less works just fine. . You can grab my encoding preset: https://github.com/PupBrutus/Fapinator9000/blob/master/HandbreakEncodingPreset.plist 

* You will need to specify your audio-source if you intend to use the beat-detection - here is a quick link explaining how to activate the stereo mix option: https://vvvv.org/documentation/accessing-stereo-mix 


HOTKEYS
=========

Be sure to enable hot-keys for primary in-session controls (disabled by default)

Current Hotkeys
Numpad1 - Jumps to new BG porn file
Numpad2 - Jumps to new time in current BG porn file
Numpad3 - Removes UI

Numpad7 - Toggles auto skipping to new video
Numpad8 - Toggles timer based skipps  BG porn
Numpad9 - Toggles beat-sensitive skips inside BG porn

HOME key - Toggles full-screen
Insert key - Toggle play/pause

By default the video skipping is all disabled so use the hot-keys or toggles to enable the switching there or use manual video skipping hot-keys

