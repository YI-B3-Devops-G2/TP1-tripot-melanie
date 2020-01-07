read me 
# B3 Devops - TP 1
## Info
mail: melanie.tripot@ynov.com
github_username: Mtripot



prerequis

    installations 

        Creation d'un machine virtuelle sous virtualbox, ubuntu server 64 bit
        installation de node js , openssh-server, nginx sur la vm 
            apt-get install -y nodejs 
            apt-get install -y nginx
            apt-get install -y openssh-server


        puis creation d'un script d'automatisation avec vagrant 
         #!/usr/bin/env bash

        apt-get update
        apt-get install -y apache2
        if ! [ -L /var/www ]; then
        rm -rf /var/www
        ln -fs /vagrant /var/www
        fi
        apt-get install -y nodejs 
        apt-get install -y nginx
        apt-get install -y openssh-server"
