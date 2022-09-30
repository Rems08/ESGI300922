### Rémy MASSIET ESGI 2 30/09/2022

# Exercice 1

Les branches du projet disponibles sont: 

- gh-pages
- spdx-license-templates

Cependant lorsque l'on fait la commande:
```git
git clone https://github.com/github/choosealicense.com.git
```
On récupère uniquement la branche par défaut "gh-pages".

# Exercice 2
- Selon moi le numéro de la dernière pull request en date est: **1028** <br>
  Lien vers la pull request: https://github.com/github/choosealicense.com/pull/1028

- La pull request #550 contient 2 commits
- Pour le commit 8061f2f:
  - Nombre de commit: 2
  - Auteur de du commit de merge:  Mike Linksvayer

# Exercice 3

- Pour revenir en arrière sur le fichier index.html il faut faire la commande: 
```git
git reset 68ebcac180928d8c509a560b84fb427ff3025bcb
```
- Le nom du plugins javascript supprimé est: **auto-complete.min.js**
- Pour voir les changements effectués dans ce commit il faut utiliser la commande:
```bash
git diff 68ebcac180928d8c509a560b84fb427ff3025bcb
```
- Pour récupérer le plugins supprimé il faut faire un: 
```
git checkout b30306e502b99aabab256a5d2f68e8d50ba5072a /assets/vendor/javascript-auto-complete/auto-complete.min.js
```

# Exercice 4
- Pour ajouter ma licence je:
  - Créer un fichier dans le dossier "_licenses"
  - ```git add _licenses/remy-massiet-1.0```
  - ```git commit -m "Add Rémy MASSIET licence"```
- Pour vérifier si on est à jour par rapport au dépot distant on fera un: 
```git
git pull
```
- Pour envoyer mes modifications sur le repo distants je fais un:
```
git push
```