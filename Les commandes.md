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
  * mv peu également etre utilisé pour renomé un fichier
* **cp \<fichier_source\> \<fichier_destination\>** : permet de copier un fichier
  * **cp -r \<dossier_source\> \<dossier_destination\>** : permet de copier un dossier et son contenue
* **grep \<regex || string\> \<fichier\>** : Permet de faire une recherche dans un fichier grace a un *String* ou *Regex*
* **man \<command\>** : Permet de vous afficher la documentation
* **whereis \<string\>** : Permet de rechercher un fichiers exécutables
* **apt-get update** : met à jour la liste des paquets disponibles
  * **apt-get upgrade** : met à jour les paquets déjà installés sur votre machine
  * **apt-get install \<paquet1\> \<paquet2\> ...** : installer un ou plusieurs paquets
  * **apt-get remove \<paquet1\> \<paquet2\> ...** : supprimer les paquets SANS les fichiers de configuration0
  * **apt-get purge \<paquet1\> \<paquet2\> ...** : supprimer les paquets ET les fichiers de configuration
  * **apt-get autoclean** : permet de supprimer les paquets "vieux" et "non utilisés". Conserve les versions à jour des paquets.
* **su \<username\>** : permet de changer d'utilisateur
* **shutdown -h now** : permet d'arrêter la machine
  * **shutdown -r now** : permet de redemarrer la machine
    * **reboot** : permet de redemarrer la machine
      * **reboot -f** : permet de forcer le redemarrage la machine
* **which \<command\>** : permet de localiser les fichiers liés aux commandes

[<- Retour][l]

[l]:https://github.com/Chakyu23/Shell/blob/main/README.md
