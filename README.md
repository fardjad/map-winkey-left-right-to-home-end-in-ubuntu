# Map WinKey+Left/Right to Home and End keys in Ubuntu

## Description

This repository contains required config files to map 
WinKey(Super)+Left/Right to Home and End keys. 

## Installation

1. Clone the repository and copy/create a symlink to **.xkb** to/in your $HOME 
directory
2. Copy/Create a symlink to **01-xkb** to/in **/etc/X11/Xsession.d/** and do 
`sudo chown root:root /etc/X11/Xsession.d/01-xkb`

3. Restart X session

## Credits

http://unix.stackexchange.com/questions/65434/map-superleftright-to-home-end
http://madduck.net/docs/extending-xkb/

