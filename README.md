
##  Deploiement de l'Application

Tout d'abord, j'ai créé le fichier index.html avec le code source.

Ensuite j'ai créé le repository git https://github.com/Tenbra/MEP06.git


### Test en local:

Le fichier Dockerfile permet de créer l'image docker de notre projet. Nous l'avons créé avec une image NGINX de base :
Ensuite, nous sl'avons build avec la commande : `docker build -t mep06 .`
Pour le run nous avons utilisé la commande : `docker run -d -p 8080:80` 
Efin, pour verifier sur un navigateur, nous avons recherche http://localhost:8080


### Test sur mogenius:

Nous avons créé un compte sur Mogenuis
Ensuite, nous avons créé un nouveau projet avec l'option "Bring your own code"
Dans la parti git, nous avons collé le lien de notre projet git.
Et lancé la creation de l'image
Ala fin de la creation, notre application etait accessible depuis le lien : mep06-prod-mep06-l6pppt.mo1.mogenius.io:80