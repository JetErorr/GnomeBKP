# GnomeBKP
x (apt) = can be installed with [ sudo apt install <x> ] 

Files required->

==Zsh shell
	==chsh -s /new/term
	==oh-my-zsh (github search) // for theming
	==fonts-powerline (apt) // for glyphs in zsh themes
==i3 (apt)
	==i3-gaps (search for github repo) // for gaps between i3 tiles
==rofi
==neofetch (apt) // for quick info
==scrot (apt) // for screenshots, bind to PrntScrn in the i3 config
==lxappearance (apt)
==tilda (apt) // terminal emulator
==htop

==Auto script maker
	==PATH="$HOME/Scripts:PATH"
	==export PATH
	==. .bashrc
	==. .zshrc
==Made flex // Text displays with 
	==toilet (apt)
	==figlet (apt) (optional) fonts and
	==lolcat (apt)
==Enabled Touchpad 'Tap' (i3 config)
	==xinput
==CTRL+GRAVE shows past notifications

=pipes.sh
==cmatrix
x=glitchlock
=gotop

=pavucontrol
=alsamixer
x=conky
=youtube-dl
=ncmpcpp
=horst
=httping
=tree
=mc

=for_window class=["^.*"] border pixel 0
 Alexa, set a bomb for 3am tomorrow

=polybar

=For brightness
	=Make the file /usr/share/X11/xorg.conf.d/20-intel.conf
	=Add the following to it (not the hashes)
#
Section "Device"
        Identifier  "card0"
        Driver      "intel"
        Option      "Backlight"  "intel_backlight"
        BusID       "PCI:0:2:0"
EndSection
#
	=Logout and back in, the buttons should work right away,
	=If the buttons don't work, check if they are bound properly

=axel
=wget
=aria2c

