# Goonmaker

Ground-Up rebuild of Fapinator 9000 (https://github.com/PupBrutus/Fapinator9000) code based around popper trainer/hypno/gooning emulation


Requirements: 
=========
VVVV 64bit atleast v34.106 https://vvvv.org/downloads

VVVV 64bit add-on pack: https://vvvv.org/downloads

VVVV 64bit DX11 add-on pack: https://vvvv.org/contribution/directx11-nodes 


TIPS
=========

For those unfamiliar with VVVV you will use a right-click (or left click if using left-handed mouse) to interact with the in-program controls. I would reccomend running through the hello-world for VVVV as it will explain what you're seeing alot more: https://vvvv.org/documentation/tutorial-hello-world

It might not run perfectly on the first-run VVVV is very particular like that. First load the application and specify your video directory with the VideoDir box at the top of the window then save, and reload the application. Specify a trippy video as well if you'd like to try that.

I do re-encode most of my own videos using either Adobe Media Encoder or https://handbreak.fr - Depending on your system using HD porn with settings that force it to skip/change video often can cause the application to crash, but usually MPG4 at 720 or less works just fine. . You can grab my encoding preset: https://github.com/PupBrutus/Fapinator9000/blob/master/HandbreakEncodingPreset.plist 

You will need to specify your audio-source if you intend to use the beat-detection - here is a quick link explaining how to activate the stereo mix option: https://vvvv.org/documentation/accessing-stereo-mix 


HOTKEYS
=========

Be sure to enable hot-keys for primary in-session controls (disabled by default)

Current Hotkeys
Numpad1 - Manually skip to new video
Numpad2 - Manually to new time in current video
Numpad3 - Cycles magnification options ( Normal, 125%, 150%, 200%)

Numpad4 - Slow playback (33%)
Numpad5 - Normalize playback speed (100%)
Numpad6 – Fast forward playback speed (250%)

Numpad7 - Allows auto skipping to new videos (otherwise will stay only in currently playing video)
Numpad8 - Allows auto skipping inside video (random timed based skipping)
Numpad9 - Allows beat-sensitive skipping inside video (beat based skipping)

Numpad0 - Reset poppers system (helpful if its looping)
Numpad+ - Trigger poppers hit manually

HOME key - Toggles full-screen
Insert key - Toggle play/pause


By default the video skipping is all disabled so use the hot-keys to enable the switching there or use manual video skipping hot-keys


Poppers system
=========
Poppers can be dangerous - be smart and play safe. I cannot be responsible for the mis-use of this program. 

The poppers system is still a beta feature, it will sometimes start to loop (offering hit after hit) pressing the num-pad 0 key will reset the system and it should return to functioning normally. There are three main options for the popper system, min time between hits, max time between hits and the % of single hits. Setting it as 60 min, 90 max and 70% single hit will mean that it will wait a minimum of 60 seconds and a maximum of 90 seconds before offering a hit (at a random time between them), and it will be a 70% chance of being a single hit. 

Currently the poppers hits are based on the Timeliner functions, which doesn’t allow me to programmably specify the number of hits, instead it functions as a playback of recorded values over time. If you need to adjust any of the timings just right-click the Timeliner function and you can drag around the keyframes to make it work (but it is a bit particular so it can break easily). I plan to add additional hit sequences in later. https://vvvv.org/documentation/timeliner-(animation)
I’m very open to suggestions if you can find a better method however... this is a pain... 

If you have any ideas/suggestions please feel free to raise an issue or pull request.

