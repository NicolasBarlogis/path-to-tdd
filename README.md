# Path to everyday TDD
Source d'information sur le plan de formation "Path to every day TDD", fait avec le moteur de template Hugo.

## Cloner le repo
Le repo utilise un sous-module git.
Utiliser directement l'option recurse-submodules:
```
git clone --recurse-submodules git@github.com:NicolasBarlogis/path-to-tdd.git
```

À défaut, vous pouvez tirer le dossier concerné après coup:
```
git clone git@github.com:NicolasBarlogis/path-to-tdd.git
cd themes/docport/
git submodule init
git submodule update
```

# Lancer le serveur
À la racine du projet, lancer:
```
hugo server -D
```