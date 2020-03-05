💻 Site internet de Malea : https://www.malea.dev

Pour développer
------
En local, le plus simple est de créer un serveur web qui sert le fichier index.html :
* Ouvrir un terminal dans le répertoire du repo git
* `python -m SimpleHTTPServer 8000`
* Naviguer sur `http://localhost:8000/`

Pour déployer
-------
Nous utilisons _github pages_, avec notre domaine malea.dev branché dessus.  
Chaque `git push` sur `master` déclenche un déploiement en PROD.
