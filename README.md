# pterodactilscript
This script should be ran on a properly setup server not under root.

curl -Lo install.sh https://github.com/Damigeana/pterodactilscript.git
bash install.sh -i [nginx] [apache]
i.e. bash install.sh -i nginx

You will be prompted for email, FDQN, time zone, and portal password.

This will install all of the necesary files and update the system including SSL.
