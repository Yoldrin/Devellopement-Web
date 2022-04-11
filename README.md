# Devellopement-Web

Installation de Laravel avec Docker
En premier lieu il faut installer WLS version 2 et une distribution Linux.

Il faut l'activer sur Docker:
![161767507-2bb60ebc-d9ae-4e86-8e7f-538e85a0b9fd](https://user-images.githubusercontent.com/33723826/162697444-42bb668a-2eb2-4d5e-aa43-7e9de880568b.png)

Pour installer laravel executer la commande suivante:
curl -s "https://laravel.build/minimalist-blog-laravel" | bash

Puis une fois l'instalaltion terminée executer les commande suivante pour vous rendre dans le dossier de larevel et l'executer:

cd minimalist-blog-laravel 
Puis:

./vendor/bin/sail up -d



Si a l'éxecution composer ne ce lance pas suite a des problèmes de droits lancer cette commande pour les modifier:

chmod -R 666 ../minimalist-blog-laravel

Suite a une grosse modification il faut penser a recompiler le code de l'application, pour ce faire vous pouvez utiliser cette commande :

npm run dev

Après toute les modification il faut penser a bien gérer le Git si il y'en a un.

Quelques rappel de commande git
Récuperer le code dépot distant: git pull

Quand le code est récupéré pour récupéré tout les éléments modifié :
git add *

Pousser sur le dépot distant : git pull
