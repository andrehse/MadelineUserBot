# MadelineUserBot

Sto utilizzando la base di @peppelg1.
(https://github.com/peppelg/TGUserbot)

---------------------------------------

Comandi disponibili:

!echo "Quello che vuoi!"
!join "Link o username"
!leave (utilizzabile solo dal gruppo)
!chiamami (Ti chiamerà e metterà della musica)
!storm "Link o username"
!nome "Nome"
!username "Username"

(Per ora questi sono i comandi disponbili!)

---------------------------

Supporto telegram:

Andrea (creatore comandi): @biologiq
Giuseppe (creatore base): @peppelg
Daniil (creatore MadelineProto + php.sh): @danogentili

---------------------------------

Come installarlo:

1) Iniziamo con i comandi basilari:

sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git
sudo apt-get install curl

2) Installare PHP 7.0:

cd /var
wget http://daniil.it/php.sh
sudo chmod 777 
./php.sh

3) Scaricare la base

https://github.com/peppelg/TGUserbot/archive/test.zip
unzip test.zip
rm test.zip
mv /var/test/ /root/MadelineUserBot
cd root
cd MadelineUserBot

4) Configurare l'userbot.

php start.php

Vi uscirà:
Loading settings...
Sto caricando MadelineProto...
MadelineProto caricato!
Inserisci il numero di telefono: "NUMERO"
Inserisci il codice ricevuto: "CODICE"
etc....

5) Configurazioni aggiuntive

nano 









