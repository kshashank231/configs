### Clean old boot entries in linux


1. `sudo apt-get install efibootmgr`
2. `sudo efibootmgr`

        This will show all entries in order
3. `sudo efibootmgr -b 0005 -B`

        -b tells ehich entry to edit
        -B tells to delete 0005 from bios


### Software to install in ubuntu desktop

- barrier
- brave
- code
- git
- nvm
- unzip
- curl
- net-tools
- sudo apt install openssh-server (allow ssh port sudo ufw allow ssh )

