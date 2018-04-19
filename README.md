# Json-server

Etapes d'installation du package JSON-SERVER :

1 - se rendre sur : https://nodejs.org/en/ et télécharger la version adéquate selon l'OS
2 - Créer un nouveau dossier C:/Users/(Nizare) intitulé jsonserver 
3 - Se positionner sur : C:Users/Nizare/jsonserver et taper la commande : npm init 
    Quand on vous demande les informations concernant le package, taper "Entrer" pour passer
4 - Tapez la commande : npm install --save json-server
5 - Ouvrir le fichier package.json se trouvant dans C:Users/Nizare/jsonserver et modifier la ligne 
"test": "echo \"Error: no test specified\" && exit 1"    par 
"json:server":"json-server --watch db.json"
6 - Dans le même dossier, mettre le fichier db.json que vous avez téléchargé 
7 - Pour lancer le serveur en local, ouvrir un cmd : npm run json:server
8 - Dans un navigateur web accédez à l'url : localhost:3000
