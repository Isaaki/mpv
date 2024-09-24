## MPV
- Copy mpv config folder to the config directory
	- Windows the config directory is located at `%appdata%\\roaming\\mpv`
	- Linux there is multiple directories it could be
		- ~/.var/app/io.mpv.Mpv   (flatpak)
		- ~/snap/mpv
		- ~/snap/mpv-wayland
		- ~/.config/mpv           (this is the default config if not flatpak or snap)
- Install [subliminal](https://github.com/davidde/mpv-autosub) for [autosub](https://github.com/davidde/mpv-autosub) to work
- *(optional)* Install [thumbfast](https://github.com/po5/thumbfast) for thumbnail previews

### Links
- [uosc](https://github.com/tomasklaen/uosc)
- [copy-paste-url.lua](https://github.com/Isaaki/mpv-scripts)
- [autosub.lua](https://github.com/davidde/mpv-autosub)
	- With this [PR](https://github.com/davidde/mpv-autosub/pull/25) merged for http support (useful for Stremio)
- [thumbfast.lua](https://github.com/po5/thumbfast)
