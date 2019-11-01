# Ubuntu-18.04-and-up-Fix-for-NDI-plugin-for-OBS-Studio
Ubuntu 18.04 and up Fix for NDI plugin for OBS
Since Canonical now only provides Snap version of OBS Studio it is impossible to get the NDI plugin working on it.
There is a fix:
1. Install the official OBS-Studio
* sudo apt install ffmpeg
* sudo apt install obs-studio
* sudo apt-get install libnvidia-encode1

2.Install NDI pugin and library for OBS-Studio
* NDI for OBS-Studio download .deb files here:https://github.com/Palakis/obs-ndi/releases/tag/4.7.0
* sudo dpkg -i libndi3_4.0.0-1_amd64.deb
* sudo dpkg -i obs-ndi_4.7.0-1_amd64.deb
That's it,should work now.
Happy dual-rig streaming from 
#gimalaji_blake!

