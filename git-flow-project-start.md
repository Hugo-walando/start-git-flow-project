# Notes pour start projet avec gitflow et github

- Fork on GitHub
- Clone ur forked project
- `git flow init` : Initialise le repo avec git flow
- `git remote add upstream` : Ajoute une remote pour lire le repo principal
- Créer les branches dont on a besoin et les pull pour synchroniser
- `git switch develop`
- `git pull upstream develop` : Synchronise la branche develop avant de commencer à travailler
- `git flow feature start [nom]` : Créer sa branche
- Après avoir fais ses modifications:
- `git flow feature finish [nom]` : Terminer sa feature et merge sur la develop
- `git pull upstream develop` : Synchronise la branche develop avant d'envoyer ses modifs
- Si Conflicts : Les réglers , Si non : `git push origin develop`
- Créer sa pull request dans Contribute.
