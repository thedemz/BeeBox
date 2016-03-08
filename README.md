# BeeBox

Type of device controlled: ASRock BeeBox, N3150-NUC

System: Arch, HTPC (Kodi)

Remote device model nr: **04G500002000AK**

Remote device info url: http://www.asrock.com/nettop/Intel/Beebox%20Series/#Specifications

# Config Files

1. LIRC file with the codes for the remote control.
2. Kodi lircmap and keymap to control the menus in Kodi.

Place the `beebox.conf` in `/etc/lirc/lircd.conf.d`

Place the `Lircmap.xml` in `~/.kodi/userdata/`

Place the `remote.xml` in `~/.kodi/userdata/keymaps`

# Lircmap.xml Key Codes

https://github.com/xbmc/xbmc/blob/master/xbmc/input/ButtonTranslator.cpp#L1487

# VLC lirc

`Tools -> Options -> Show Settings All -> Controlb  Interface`

The overwiev of "control interface" with the check boxes. Check the *infrared remote controlinterface*

`Tools -> Options -> Show Settings All -> Controlb  Interface -> Infrared`

There is a blank Input field named "Change the lirc configuration file", enter the lirc file

`~/.lircrc`

Place the `.lircrc` and `.lirc/vlc` in your home folder like `~/.lircrc` and `~/.lirc/vlc`


![alt text](http://www.asrock.com/nettop/Accessories/Beebox%20Series.jpg "")





