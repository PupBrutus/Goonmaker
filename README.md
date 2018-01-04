# Goonmaker
Ground-Up rebuild of Fapinator 9000 (https://github.com/PupBrutus/Fapinator9000) code based around popper trainer/hypno/gooning emulation

Requirements: 
VVVV 64bit atleast v34.106 https://vvvv.org/downloads
VVVV 64bit add-on pack: https://vvvv.org/downloads
VVVV 64bit DX11 add-on pack: https://vvvv.org/contribution/directx11-nodes 

It might not run perfectly on the first-run VVVV is very perticular like that. 

For those unfamiliar with VVVV you will use a right-click (or left click if using left-handed mouse) to interact with the in-program controls

First load the application and specify your video directory with the VideoDir box at the top of the window then save, and reload the application. Specify a trippy video as well if you'd like to try that. 

You will need to specify your audio-source if you intend to use the beat-detection - here is a quick link explaining how to activate the stereo mix option: https://vvvv.org/documentation/accessing-stereo-mix 

Be sure to enable hot-keys for primary in-session controls (disabled by default)

By default the video skipping is all disabled so use the hot-keys to enable the switching there or use manual video skipping hot-keys

Enable the poppers system (currently limited to 1 hit and 3 hit sequences via timeliner... I'm just lazy and haven't added more yet) 
The poppers system is still a beta test feature, it will sometimes start to loop (offering hit after hit) pressing the num-pad 0 key will reset the system and it will function normally. There are three main options for the popper system, min time between hits, max time between hits and the % of single hits. Setting it as 60 min, 90 max and 70% single hit will mean that it will wait a minimum of 60 seconds and a maximum of 90 seconds before offering a hit (random time), and it will be a 70% chance of being a single hit. 

If you have any ideas/suggestions please feel free to raise an issue or pull request. 
