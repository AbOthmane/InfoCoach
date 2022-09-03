
![preview](preview.png)

Suivez les instructions ci-dessous pour construire le code nodejs ci-joint. Ce code affichera un "Hello World" dans votre navigateur.  


----


## Instruction 

### Configuration de l'environnement de programmation 

Vous devez avoir **git**, **nodejs** dans votre ordinateur pour accomplir cette tâche.


### Aller au Repository local

Si vous n'avez pas le Repository local, clonez-le depuis le répertoire remote.

``bash
$ git clone https://github.com/AbOthmane/InfoCoach
```

Aller au top du référentiel local

```bash
$ cd InfoCoach # aller dans le répertoire local
```


### Mise à jour du Repository local

Veuillez mettre à jour le répertoire local sur votre ordinateur.

```bash
$ git checkout main # fait de la branche principale la branche courante
$ git fetch origin main # télécharge la branche principale depuis le répertoire distant
$ git reset --hard origin/main # réinitialise la branche principale locale comme le répertoire remote
```



### Configuration et bibliothèque Express

La bibliothèque **express**` est nécessaire pour faire fonctionner le serveur. 


### Création d'une branche

Pour faire cette tâche, vous devez être dans la branche `task00`.  Vous pouvez toujours vérifier la branche en cours par

``bash
$ git branch -a # liste toutes les branches, en montrant la branche courante 
```

Vous êtes probablement dans la branche `main`. Créons la branche `task00` et définissons-la comme branche courante.

```bash
$ git branch task00 # créer la branche task0
$ git checkout task00 # bascule dans la branche task0
$ git branch -a # vérifiez que vous êtes dans la branche task0
```

### Soumettre

Enfin, vous soumettez le document en le poussant dans la branche `task00` du répertoire distant. 

```bash
cd InfoCoach # allez au Top de votre répertoire.
git status # vérifiez les changements
git add .   # mettre en scène les changements
git status # Vérifier les changements mis en scène
git commit -m "task00 finished" # le commentaire peut être n'importe quoi
git push --set-upstream origin task00 # met à jour la branche task0 du répertoire distant
```

est arrivé sur la page web GitHub `https://github.com/ACG-2022S/InfoCoach` . Si tout semble bon sur cette page, faites une pull request. 

![](../doc/pullrequest.png)


----
