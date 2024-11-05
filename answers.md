# Answers of Axel Bonetti axelbonetti

## Basics

### Task 1

.git est un dossier :

Il permet de faire le lien entre le répo local et distant

img est un dossier : 

C'est un répertoir d'image

Fichier answer.md:

Il permet d'écrire les réponses du labo

### Task 2

git status : Un message qui s'affiche :

Untracked files:

Readme.md en rouge

Parce que le fichier a été crée mais il est toujours dans la working area

git log -online : Rien parce que cela affiche seulement la liste des commit

### Task 3

git status :

On voit un ligne : Changed to be committed avec new file: Readme.md en vert qui indique l'action effectué et le fichier concerné. Il est prêt à être commité

### Task 4

git status :

Il y a toujours la ligne : Changed to be committed

mais il y a une autre ligne : Changes not staged for commit : modified : Readme.md en rouge car les modifications sont toujours dans la working area

### Task 5

Chaîne de caractère du début : Elle correspond au l'Identifiant du commit

Head : Représente la branche sur laquelle on est actuellement

Main : le nom de la branche

Après (): Le message du commit

### Task 6

En revenant sur le commit initial : Git restaure le projet à l'état exact de ce commit. Certains fichiers et modifications récentes peuvent donc disparaître, car ils n'existaient pas encore à ce stade.
En revenant sur la branche main : Git restaure l'état le plus récent du projet, incluant toutes les modifications récentes et les fichiers créés après le commit initial.

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)