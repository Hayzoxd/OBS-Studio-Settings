# Hayzox's OBS Studio Guide

These are the settings I use for OBS Studio, they are by no means a template but are useful to forge your own configuration. Please restore the default settings before applying the parameters.

__General\Output:__
* Automatically check for updates on startup - Disabled
* Show confirmation dialog when starting streams - Enabled
* Show confirmation dialog when stopping streams - Enabled

__General\System Tray:__
* Always minimize to system tray instead of taskbar - Enabled

__Stream:__
* Connect Account (recommended) - Connect to Twitch
* Ignore streaming service setting recommendations - Enabled

__Output\Streaming:__
* Output Mode - Advanced
* Encoder - NVIDIA NVENC H.264 (new)
* Rescale Output - 1280x720
* Bitrate - 6 000 Kbps
* Preset - Quality
* Psycho Visual Tuning - Disabled

__Output\Recording:__
* Recording Format - mp4
* Encoder - NVIDIA NVENC H.264 (new)
* Bitrate - 40 000 Kbps
* Preset - Max Quality
* Psycho Visual Tuning - Disabled

__Output\Replay Buffer:__
* Maximum Replay Time - 90 s

__General\Output:__
* Automatically start replay buffer when streaming - Enabled
* Keep replay buffer active when stream stops - Enabled

__Audio\General:__
* Sample Rate - 44.1 kHz

__Audio\Global Audio Devices:__
* Desktop Audio - Headphones
* Mic/Auxiliary Audio - Microphone

__Video:__
* Downscale Filter - Lanczos (Sharpened scaling, 36 samples)
* Common FPS Values - 59.94

__Hotkeys\Replay Buffer:__
* Save Replay: Ctrl + S

__Advanced:__
* Color Range - Full
* Enable Browser Source Hardware Acceleration - Disabled

__Audio Mixer\Desktop Audio\Properties:__
* Use Device Timestamps - Disabled

__Advanced Audio Properties (recommendations):__
* Desktop Audio - -10.0 dB
* Mic/Aux - 0.0 dB
* Music - -35 dB
* VOIP - -6.0 dB
