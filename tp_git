Détail du TP Git

1- Initier un nouveau repository local Git de test, pas besoin de le garder, en local via la ligne de commande git
Dans le terminal vscode (plus rapide pour aller direct dans le repo) ou depuis un terminal (/!\ a bien choisir son chemin pour le repo)

``` Commandes : 
mkdir test-repo       # Crée un nouveau dossier pour le repository
cd test-repo          # Accédez au dossier
git init              # Initialise un repository Git local
echo "Hello World" > README.md  # Ajoute un fichier README.md pour tester
git add .             # Ajoute tous les fichiers au staging
git commit -m "Initial commit"  # Crée un premier commit
```


git remote add origin https://github.com/<votre-utilisateur>/<nom-du-repository>.git  # Remplacez par votre URL GitHub
git branch -M main        # Renomme la branche principale en `main` si nécessaire
git push -u origin main   # Pousse le contenu vers GitHub

La commande git branch permet de gérer les branches dans un repository Git. Voici ses principales utilisations :

Lister les branches existantes : git branch

Créer une nouvelle branche : git branch <nom-de-la-branche>

Supprimer une branche : git branch -d <nom-de-la-branche>

Renommer une branche : git branch -m <ancien-nom> <nouveau-nom>

4. Comment modifier le remote en cas d’erreur ?
Si vous avez ajouté une mauvaise URL pour le remote, vous pouvez la modifier avec les commandes suivantes :

bash
git remote set-url origin https://github.com/<votre-utilisateur>/<nouvelle-url>.git  # Remplace l'URL existante

5. Comment vérifier le remote ?
Utilisez la commande suivante pour afficher les remotes configurés et leurs URLs :

bash
git remote -v

6. Supprimer le repository
Supprimer le repository local :
Pour supprimer le dossier local, exécutez simplement :

bash
cd ..          # Revenez au dossier parent
rm -rf test-repo  # Supprimez le dossier et son contenu
