# Template DataForGood

This file will become your README and also the index of your
documentation.

# Contributing


## Installation

- [Installation de Github Desktop](#installation-de-github-desktop)
	https://docs.github.com/en/desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop

- [Extraire le dépôt Github](#extract-github)
	https://github.com/dataforgoodfr/no-ethical-billionaire

- [Installation de Tox](#installation-de-tox)
	XXX

- *BACK* [Installation de Python](#installation-de-python)
Ce projet utilise [uv](https://docs.astral.sh/uv/) pour la gestion des dépendances Python. Il est préréquis pour l'installation de ce projet.

Une fois installé, il suffit de lancer la commande suivante pour installer la version de Python adéquate, créer un environnement virtuel et installer les dépendances du projet.

```bash
uv sync
```

A l'usage, si vous utilisez VSCode, l'environnement virtuel sera automatiquement activé lorsque vous ouvrirez le projet. Sinon, il suffit de l'activer manuellement avec la commande suivante :

```bash
source .venv/bin/activate
```

Ou alors, utilisez la commande `uv run ...` (au lieu de `python ...`) pour lancer un script Python. Par exemple:

```bash
uv run pipelines/run.py run build_database
```

- *FRONT* [Installation de React](#installation-de-react)
	https://react.dev/learn/creating-a-react-app#full-stack-frameworks

## Lancer les precommit-hook localement

[Installer les precommit](https://pre-commit.com/)

    pre-commit run --all-files

## Utiliser Tox pour tester votre code

    tox -vv
