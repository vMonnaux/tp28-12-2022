Tp windows server 2022 en autonomie
Le but de ce tp est de concevoir l’infrastructure serveur d’un client, d’estimer le temps pour chaque étape, et de peaufiner vos recherches d’informations sur internet.
Vous devrez réaliser en 4 heures l’énoncé ci-dessous et prendre des screens de chaque étapes dans un document word ou dans une archive dans l’ordre, inutile de rédiger. Toutes les étapes de configuration ne seront pas indiquées, à vous de faire preuve de réflexion. Les VM auront de base un compte Administrateur avec pour mdp Burolor57
Contexte :
1. Vous devez créer un serveur unique, pour un client nommé Bricolgirls, spécialiste du bricolage. Les serveurs devront être facilement identifiable.
2. Vous devez établir une politique de mot de passe. (Rédigez rapidement votre décision)
3. Vous devez leurs créer des partages.
4. Tout devra se faire par GPO pour limiter les interactions chez les utilisateurs finaux.
5. Une fois le serveur correctement configuré, vous devrez le migrer sur un deuxième serveur pour que celui-ci devienne « serveur principal ».
6. Une fois transféré, fournir un screen qui prouve que votre deuxième serveur est devenu « serveur principal ».
7. Il est nécessaire de pouvoir restaurer des données supprimées.
8. Il sera nécessaire de préparer la migration des partages (rédiger la méthode).
Informations :
1. Adressage réseau
Les serveurs et postes auront les accès TV suivants :
a. Kevin serveur 1 : ID : 1 400 218 624 / MDP : Burolor57
b. Kevin serveur 2 : ID : 1 400 334 054 / MDP : Burolor57 c. Kevin PC : 1 400 426 496 / MDP : bmwgnbjt
d. Patrick serveur 1 : ID : … / MDP :
e. Patrick serveur 2 : ID : … / MDP :
f. Patrick PC : ID : … / MDP :
Votre serveur principal devra faire office de serveur DHCP pour le client (la plage d’adresse devra compter 50 adresses IP avec une adresse de départ qui sera .XX).
2. Les accès :
La société Bricolgirls est constituée de 9 employés en 5 services différents : a. Direction : doit avoir son propre partage, invisible pour les autres utilisateurs, doit posséder les droits de lecture/écriture sur l’ensemble des partages
Commenté [VM1]: Direction : Emmanuel ROCHE Sylvie MALPHITE
b. Comptabilité : doit avoir son propre partage, invisible pour les autres utilisateurs, doit accéder au partage commercial c. Technique : doit avoir son propre partage, doit avoir un sous dossier planning accessible par Commerce d. Commerce : doit avoir son propre partage e. RH : doit avoir son propre partage
f. Commun
g. KOESIO (en masqué)
La direction, la comptabilité auront une imprimante personnelle, les autres services se partageront une imprimante commune.
Pour ce TP, les imprimantes devront être virtuelle.
Enfin, répondez à ces questions :
- Quels sont les rôles de votre serveur principal ?
- Quelles étapes sont nécessaires pour ne conserver que le nouveau serveur principal chez le client ?
Commenté [VM2]: Comptabilité : Sylvie PANZANNI Julie LAURE
Commenté [VM3]: Technique :
Benoit DEGIORGIS
Jonathan STOLLER
Kevin TULON
Commenté [VM4]: Commerce :
Alex FERNANDEZ Sandrine DUCHAMP
Commenté [VM5]: RH: Coralie FILHO
