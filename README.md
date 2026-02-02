# Premier-depot-eleves
Exercice avec GitHub et Git pour la 2e semaine de E43

## Exercices à faire
* Commencer par ouvrir le fichier .ioc, __retirer le périphérique UART1__, puis générer le code
* Tester que le projet compile toujours
* Ajouter votre changement dans le fichier .ioc à la scène (staging) avec ```git add``` 
* Faire un premier commit, soit avec GitHub à la ligne de commande, soit avec GitHub Desktop, avec le message suivant : ```Mon premier commit de E43!```
Avec la ligne de commande, on peut ajouter un message avec un commit de la façon suivante : 
```
git commit -m"Le message"
```
Notez l'espace entre le 'commit' et le '-m', ainsi que l'absence d'espace entre le '-m' et le reste du message
* Dans le fichier ```usermain.c```, ajoutez une fonction qui imprime votre nom, caractère par caractère, sur le UART2
* Ajouter ce changement à la scène, puis faites un commit avec un message court, mais descriptif de votre ajout. Ici, pas besoin de phrases complètes, seulement des bons mots-clés cohérents font le travail.
* Poussez ce travail sur le dépôt distant
* Créez un nouveau fichier .c, à côté de vos autres fichiers sources. Nommez le comme vous voulez.
* Faites la même chose avec un .h
* Prenez la définition de cette fonction que vous avez écrite, puis placez la dans ce nouveau fichier .c. Faites la même chose avec la déclaration dans le .h
* Assurez-vous que votre code fonctionne toujours

Note : Pendant ce processus, vous pouvez ajouter des fichiers dans le staging et faire des commits comme vous pensez.