script for automatically start the numpad in bootmode on Linux

STEP ONE:
create a .sh file with the command 
nano numlock_activate.sh

STEP TWO:
copy following code in the file (.sh file is also in the git-tree of this instruction)

#!/bin/bash

#activate numpad / numlock
numlockx on

exit 0


STEP THREE:
leave the file with CTRL+S and CTRL+X

STEP FOUR:
type in this command "chmod +x numlock_activate.sh"
the command gives execution permissions to the script

STEP FIVE:
move the script into the autostart-folder
For GNOME-BASED environment 
mv numlock_activate.sh ~/.config/autostart/

For KDE-BASED environment
mv numlock_activate.sh ~/.kde/Autostart/

now, numpad must be activated on boot


when you have questions, contact me on X / Twitter ( @06druese08 )

