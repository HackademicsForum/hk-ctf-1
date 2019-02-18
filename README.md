# CTF Hackademics #1

Vous trouverez ici un export du container Docker du premier CTF Hackademics. 
Plus d'infos : https://hackademics.fr/forum/ctf/76257-r%C3%A9sultats-premier-ctf-hackademics

## Utilisation 

Téléchargez l'export : https://github.com/HackademicsForum/hk-ctf-1/releases/download/1.0/ctf-hk-1.tar
Lancez les commandes suivantes :
````
docker load < ctf-hk-1.tar 
docker run -d ctf-hk-1 /bin/sh -c "/root/start.sh && tail -f /dev/null"
docker ps 
# Récupérer l'id du container 
docker inspect <container id> | grep "IPAddress"
````
Les ports 80 et 22 sont utilisés par ce container...

## Solution 

Lien de la solution : https://hackademics.fr/forum/ctf/76257-r%C3%A9sultats-premier-ctf-hackademics?p=76437#post76437
