# Ubuntu-18.04-and-up-Fix-for-NDI-plugin-for-OBS-Studio
Ubuntu 18.04 and up Fix for NDI plugin for OBS 

Ubuntu 18.04 and up Fix for NDI plugin for OBS Since Canonical now only provides Snap version of OBS Studio it is impossible to get the NDI plugin working on it. There is a fix:

1. Install the official OBS-Studio from the Ternminal:

    * sudo apt install ffmpeg
    * sudo apt install obs-studio
 
    Install NDI pugin and library for OBS-Studio:

2. NDI for OBS-Studio download .deb files here:https://github.com/Palakis/obs-ndi/releases/tag/4.7.1
    * sudo dpkg -i libndi3_4.0.0-1_amd64.1.deb
    * sudo dpkg -i obs-ndi_4.7.1-1_amd64.deb Another option on Ubuntu is just to point and click them and the files will install automatically,but beware they will not work with the Snap unofficial version of OBS-Studio! That's it,should work now. Happy dual-rig streaming from #gimalaji_blake!
