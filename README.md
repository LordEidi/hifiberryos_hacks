# HifiberryOS Hacks
Hacks for the HifiberryOS

## Auto Play
If you like to listen to Internet Radio and would love your HifiberryOS client to automatically play your stream right after booting, then do this:

- Copy run_radio.sh into the /root folder.
- Copy autoplay_radio.service into this place: /etc/systemd/system/autoplay_radio.service
- Copy a playlist into this folder (and call it radio.m3u): /library/playlists/radio.m3u
- Then enable the autoplay service: systemctl enable autoplay_radio.service

And reboot. Your first item on your playlist will start to play right after the reboot.
