# Mini-application Python + Docker — JokeAPI

Ce projet présente une petite application Python qui récupère une blague depuis
le service public JokeAPI. Aucune clé ou authentification n’est nécessaire.

---

## Contenu du projet
- **app.py** : script principal utilisant `requests`.
- **requirements.txt** : dépendances Python.
- **Dockerfile** : image minimale pour exécuter le script dans un conteneur.
- **README.md** : documentation du projet.

---

## Prérequis (exécution locale)
- Python **3.10+**
- `pip`
- Accès Internet

---

## Installation et lancement en local

```bash
python -m venv .venv
# Activation :
source .venv/bin/activate          # Linux/macOS
# ou
.\.venv\Scripts\activate           # Windows

pip install -r requirements.txt
