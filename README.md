# Partiel DEVOPS - Exemple avec Python et GitHub Actions

Ce dépôt contient un projet Python simple avec :

- Des fonctions simples
- Des tests unitaires pour valider le comportement de la fonction.

## Installation

1. Clonez ce dépôt :

   ```bash
   git clone https://github.com/<votre-organisation>/<votre-repo>.git
   cd <votre-repo>

   ```
2. Installez les dépendances :
   ``pip install -r requirements.txt``
3. Exécutez les tests localement :
   ``pytest``
4. Ajouter un .gitignore pour ne pas commit __pycache__ et autre dossiers non pertinents à commit
5. Creez un github workflow pour éxécuter des tests et  un github workflow pour éxécuter le linter
6. Ajouter des badges de réussite d'execution de vos tests et de votre linter dans le readme (voir ***GITHUB_BADGES_GUIDE.md***)
7. Améliorer le code pour réussir le linter
8. Rendre le lien de votre répository contenant les github actions que vous aurez implémenté.

***Attention à bien mettre votre repository en PUBLIC !***


![Tests](https://github.com/JosCousin/PARTIEL_3INFO_DEVOPS/actions/workflows/Test.yml/badge.svg)

![Tests](https://github.com/JosCousin/PARTIEL_3INFO_DEVOPS/actions/workflows/Test.yml/badge.svg)
