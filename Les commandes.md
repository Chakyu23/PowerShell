# Les commandes de base

## qu'est ce qu'une Commande ?

### liste de commande générique 

* **ls** : Permet d'affiché La majeur partie des fichié d'un dossier, mais ne montre pas les fichier caché
  * **ls -al** : Montre **tous** les fiché, y compris les dossier caché, ainsi que les dossier
* **cd \<dossier\>** : permet d'allé dans un dossier
  * **cd /** : permet d'accédé a la racine du système
  * **cd** : permet d'accédé au dossier personnel de l'utilisateur
* **nano** : Permet d'accédé a un éditeur de fichier, en bas de l'écran, la touche CTRL y'est représenté par le symbole (^)
* **source \<fichier\>** : permet d'actualisé un fichier
* **sudo \<action\>** : permet l'éxécution d'un fichier en changeant d'utilisateur
* **mkdir \<nom\>** : permet de crér un dossier dans le dossier actuel
* **rm \<quelque chose\>** : permet de supprimer des éléments
  * **rm -r \<dossier\>** : permet de suprimé un dossier contenant encore d'autres éléments
  * **rm -rf \<dossier\>** : en rajoutant un -f cela permet de forcé la suppression des fichier
* **touch \<nom\>** : permet de créé un nouveau fichier
* **cat \<fichier\>** : affiche le contenue d'un fichier
* **mv \<source\> \<destination\>** : Permet de déplacer un élément 
astuce : mv est également utilisé pour renommer des fichiers. Par exemple, si un fichier s'appelle "toto" et que l'on souhaite le renommer "tata", il suffira d'utiliser la commande mv de la sorte : mv toto tata
cp : Permet de copier des éléments
cp <fichier_source> <fichier_destination> : Copie le fichier source en fichier de destination
cp -r <dossier_source> <dossier_destination> : Copie le dosser source en dossier de destination (le "-r" permet de signifier la reccursivité)
grep <regex || string> <fichier> : Permet d'effectuer une recherche dans un fichier, a partir d'une regex, ou d'une string
man <command> : Permet de vous afficher la documentation de la commande renseignée
whereis <string> : Permet de rechercher tous les fichiers nommés <string> parmis les fichiers exécutables de l'OS.
apt-get <command> : Gestionnaire de paquets de l'OS
apt-get update : met à jour la liste des paquets disponibles
apt-get upgrade : met à jour les paquets déjà installés sur votre machine
apt-get install <paquet1> <paquet2> ... : installer un ou plusieurs paquets
apt-get remove <paquet1> <paquet2> ... : supprimer les paquets SANS les fichiers de configuration
apt-get purge <paquet1> <paquet2> ... : supprimer les paquets ET les fichiers de configuration
apt-get autoclean : permet de supprimer les paquets "vieux" et "non utilisés". Conserve les versions à jour des paquets.
su <username> : permet de se connecter en tant qu'un autre utilisateur
shutdown -h now : permet d'arrêter la machine
shutdown -r now : permet de redemarrer la machine
reboot : permet de redemarrer la machine
reboot -f : permet de forcer le redemarrage la machine
which <command> : permet de localiser les fichiers liés aux commandes
