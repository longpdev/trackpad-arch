
# from the arch wiki

symlink the default libinput configuration (40-libinput.conf) to /etc/X11/xorg.conf.d/ where directory search order precedence over 70-synaptics.conf will take place instead:

`ln -s /usr/share/X11/xorg.conf.d/40-libinput.conf /etc/X11/xorg.conf.d/40-libinput.conf`
