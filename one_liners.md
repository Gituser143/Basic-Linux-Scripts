### Gets the gedit prefernces tab back:
    gsettings set org.gnome.settings-daemon.plugins.xsettings overrides '@a{sv} {"Gtk/ShellShowsAppMenu": <int32 0>}'


### Changes terminal line settings
    stty


### stop displaying terminal input
    stty -echo


### reset and display terminal input
    stty echo


### Describes file type
    file [file/dir]


### logs terminal commands and makes it a script, places it in directory [dir]
    script [dir]

### creates file with filname and timestamp
    touch filename`date +%d`
%d for day
%m for month
%y for years

### reports file system disk usage stats
    df 
	

### change the terminal prompt
    export PS1="Myprompt" 
	
