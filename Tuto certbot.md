# Tuto Certbot

Prérequis : Serveur (évidement) et enregistrement dns fait 

Installation : 
```sudo apt install certbot```


Méthode 1 : Déploiement Automatique, la plus rapide, il suffit de suivre les étapes 

Utilisez la commande suivante pour générer et installer automatiquement le certificat :
   ```sudo certbot --apache```
   ou 
   ```sudo certbot --nginx```

Méthode 2 : Challenge DNS Manuel

Cette méthode est utile si votre serveur n'est pas accessible via HTTP ou si vous avez besoin de certificats wildcard
````sudo certbot certonly --manual --preferred-challenges dns -d "votre_domaine" -d "*.votre_domaine"```

En suivant les instructions il faudra faire un enregsitrement particulier de DNS 