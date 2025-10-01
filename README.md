This script try to mimic KDE kalarm behaviour in a way is appropiate for it's author.
This means: small CPU/memory footprint, working out of the box on any DE with bash enabled without any extra libraries, 
easy to transfer on another computer and finally pop-up alarm windows eventually with sound notification.
Still there are some dependencies requiered for windows/notification control: sqlite3, xdotool, yad, bc

For debian like systems you can install them with:
sudo apt install bc yad xdotool sqlite3
Script creates file ~/.local/share/ZKAlarm/zkalarm.db and you can copy the script and sqlite db for backup / transfer on any other computer.
If you want to attach a sound to an alarm just put a sound file named zkalarm.wav into the same location with the .db file.

ZKAlarm is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published 
by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.

You can reach me over mail at: ciniset-at-gmail-dot-com
