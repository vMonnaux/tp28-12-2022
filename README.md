Tp windows server 2022 en autonomie

Le but de ce tp est de concevoir la construction de l’infrastructure serveur d’un client, d’estimer le temps pour chaque étape, et de peaufiner vos recherches d’informations sur internet.

Vous devrez réaliser en 4 heures l’énoncé ci-dessous et prendre des screens de chaque étapes dans un document word ou dans une archive dans l’ordre, inutile de rédiger.
Toutes les étapes de configuration ne seront pas indiquées, à vous de faire preuve de jugeotte.

Contexte :
Vous devez créer un serveur active directory autonome, pour un client nommé Bricolgirls, spécialiste du bricolage.
Tout devra se faire par GPO pour limiter les interactions chez les utilisateurs finaux.
Une fois le serveur correctement configuré, vous devrez le migrer sur un deuxième serveur.
Adressage réseau :
1. Le réseau devra être créer en 192.168.1.x/24

La société Bricolgirls est constituée de 15 employés en 5 services différents :
1.	Direction : doit avoir son propre partage, invisible pour les autres utilisateurs, doit posséder les droits de lecture/écriture sur l’ensemble des partages
2.	Comptabilité : doit avoir son propre partage, invisible pour les autres utilisateurs, doit accéder au partage commercial 
3.	Technique : doit avoir son propre partage, doit avoir un sous dossier planning accessible par Commerce
4.	Commerce : doit avoir son propre partage
5.	RH : doit avoir son propre partage
6.	Commun :
7.	KOESIO : masqué 
La direction, la comptabilité auront une imprimante personnelle, les autres services se partageront une imprimante commune.



