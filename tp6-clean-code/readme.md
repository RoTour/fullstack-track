# TP 6 - Parcours Fullstack - Clean Code

*Durée : 1 à 2 semaines*

__Languages__ : Typescript (TS)

__Objectif du TP__ : Faire un site web qui utilise une api, en utilisant Typescript et ESLint afin d'avoir un code à la
fois robuste et propre.

__Notions visées__ :

- Découvrir TS pour ne plus jamais revenir au JS
- Utiliser des requêtes api en TS
- Savoir configurer un linter

__Indications__ :

- Typescript est un **superset** de javascript, c'est-à-dire qu'il ne s'agit pas d'un nouveau langage, mais d'une
  amélioration de javascript. Il permet les avantages suivants :
    - Des variables typées pour éviter des crashs pendant l'exécution des scripts (les erreurs arrivent pendant la
      compilation en non plus pendant l'exécution du script)
    - Une autocomplétion beaucoup plus précise proposée par les IDE


- ESLint est un système permettant d'avoir un code propre et uniforme sur tout le projet. Cela peut paraître très
  pénible de prime abord, mais au bout de quelque temps d'utilisation votre code sera beaucoup plus précis et propre.

__Énoncé__ :

- Faire un front permettant d'afficher les familiers (pets) de dofus (en utilisant l'api DOFAPI : https://fr.dofus.dofapi.fr/ )
- Arborescence :
    - Les fichiers de config (tsconfig, eslintrc etc) doivent se trouver à la racine du projet (à côté du package.json)
    - Les fichiers de l'application devront être dans un dossier nommé exactement "src"
    - Ne pas oublier le .gitignore (les fichiers de config ne doivent **pas** être ignorés)
- Config :
    - ESLint : lors de l'initialisation, sélectionner l'option
        - "To check syntax, find problems, and enforce code style"
        - "JavaScript modules (import/export)"
        - "None of these"
        - Typescript: Yes
        - Browser
        - Use popular style guide
        - Airbnb
        - JSON
        - installer la dépendance
- Étapes (à titre indicatif, la liste n'est pas exhaustive) :
    - Npm init
    - Setup typescript
    - Setup ESLint (doit être activé dans les paramètres de webstorm - selectionner configuration automatique avec le
      fichier .eslintrc)
    - Interface

__Tips__

- Utiliser le package npm **axios** pour les requêtes http

__Indications habituelles__ :

- **Ne pas se lancer tête baisée dans le tp** : prenez le temps de découvrir les technos, comprendre à quoi ça sert,
  comment ça marche etc
- Bien rechercher en amont les différents outils notions dont vous pourriez avoir besoin pour réaliser le tp
- Faire des **commits** avec des messages **propres** :)

Have fun :)
