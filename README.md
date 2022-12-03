Pour améliorer notre connaissence sur l’utilisation de la plateforme Mogenius, on a testé ses fonctionnalités avec le déploiement d’une page webn. Pour cela j'ai  :
-	Créer une page web , et un fichier DockerFile (contient les commandes qu’on peut appeler sur la ligne de commande pour assembler notre image). Et on push le code sur github.
-	Pour héberger notre application(page web), on a créé un compte sur Mogenius pour pouvoir créer un cloudSpace en liaison avec notre compte github tout en spécifiant le port 80 pour HTTPS. Une fois la liaison établie, c’est Mongenius qui se charge du build de docker en exécutant les commandes spécifiées dans le fichier DockerFile.
-	Finalement, on peut lancer notre application en utilisant l’external hostname.ui
