# MPD addon (OSFM)

A clone of Poeschl's MPD [add-on](https://github.com/Poeschl-HomeAssistant-Addons/mpd).

Key changes:

* Disable audio - to work with the audio-plugin-disabled custom version of the HA supervisor.
* Replace legacy "devices: /dev/snd"  mapping (broken) with "raw_devices: /dev/snd" mapping (from our custom HA supervisor)
* Disable "image" (temporary)
