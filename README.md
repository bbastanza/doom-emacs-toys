# Doom Emacs Toys

I have recently fell in love with Doom Emacs. Here are a couple of goodies to get you started.

The theme can be configured by creating a themes directory inside your .doom.d directory(.doom.d/themes).
In there you can place the tonight-theme.el file. Next open up your .doom.d/config.el

Change the line that says (setq doom-theme 'doom-one) to (setq doom-theme 'tonight)

Save the file and restart doom emacs.

The icon can be set by editing you emacs26.desktop file. Navigate to /usr/share/applications directory. 

Use sudo emacs to open the file in doom emacs. Change the icon line to the path where you have the icon. Icon=/path/to/icon 
Save the file and wait a few seconds to see your icon updated.

Link to doom emacs github:
https://github.com/hlissner/doom-emacs

I modified the doom-tomorrow-night theme to be the tonight theme. Here is a link to the origional doom themes:
https://github.com/hlissner/emacs-doom-themes
