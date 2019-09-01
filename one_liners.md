# Gets the gedit prefernces tab back:
    gsettings set org.gnome.settings-daemon.plugins.xsettings overrides '@a{sv} {"Gtk/ShellShowsAppMenu": <int32 0>}'


# Changes terminal line settings
    stty


# stop displaying terminal input
    stty -echo


# reset and display terminal input
    stty echo


# Describes file type
    file [file/dir]

