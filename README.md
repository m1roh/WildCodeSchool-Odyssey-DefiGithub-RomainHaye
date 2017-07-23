# WildCodeSchool-Odyssey-DefiGithub-RomainHaye
Dépot pour le défi github pour la candidature à la WildCodeSchool

1/ Pour la première parte de ce défi j'ai choisi de vous présenter TalAlter : Issue And PullRequest Genrator

https://github.com/TalAter/open-source-templates.git

Je pense que le nom parle de lui même, l'originalité repose dans sa présentation, je vous invite à visiter la page du projet…


2/ Les étapes à suivre pour faire un commit depuis la console
(je considère que l'utilisateur à déjà un compte sur Github et Git installé et configuré)

- Si ce n'est déjà fait cloner le dépôt Github sur lequel on souhaite travailler, ou le créer puis le cloner - Copie du lien du dépôt sur Github puis commande -- git clone lien du dépôt -- dans la console -, puis ce placer dans le dossier que l'on vient de récupérer -- cd nomDuDossier --

- Ou alors : - créer un dossier -- mkdir nomDuDossier --
             - ce positionner dessus -- cd nomDuDossier -- 
             - initialiser le dossier comme repository -- git init nomDuDossier--

- Faire toute les modifications voulues dans ce répertoire de travail - ajout(s), modifications(s), suppression(s) de fichier(s)

- Il faut bien penser à indexer le(s) fichier(s) dans le répertoire de travail -- git add nomDuFichier -- , ou plus simple -- git add . -- qui indexe tous les fichiers présents dans  le répertoire

- Si l'on souhaite que certain(s) fichier(s) soi(en)t ignoré(s) le(s) mettre dans un sous-dossier .gitignore

- Lorsque l'on veut enregistrer le dossier dans un état donné et pouvoir y revenir par la suite il faut faire un commit -- git commit -m "Description du commit" -- (Le message n'est pas obligatoire mais pratique pour savoir les modifications apportées par le commit)  

- Lorsque l'on veut tout envoyer sur Github, il ne reste plus qu'à faire la commande -- git push origin master -- (origin master pour branche principale, on peut travailler sur plusieurs branche à la fois sans que celles-ci ne s'impactent entre elles)