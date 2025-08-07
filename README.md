# github_actions

Ce dépôt est un projet d’apprentissage et de mise en œuvre des **GitHub Actions** pour l’intégration et le déploiement continus (CI/CD) sur des projets Python.

### Objectifs du projet

* **Mettre en place des workflows CI/CD automatisés avec GitHub Actions.**
* **Automatiser l’exécution de tests unitaires** (avec `pytest`) à chaque push sur le dépôt.
* **Contrôler la qualité du code** avec `flake8` pour s’assurer du respect des bonnes pratiques Python (PEP8).
* **S’initier aux concepts DevOps** : jobs, runners, environnement virtuel GitHub, et variables d’environnement.
* **Apprendre à structurer un projet professionnel** avec des tests et un workflow d’intégration continue.

### Fonctionnalités du dépôt

* Un fichier de test Python (`file__test.py`) contenant plusieurs fonctions testées avec Pytest.
* Un workflow GitHub Actions (`control_tests.yaml`) qui :

  * Installe automatiquement les dépendances de test.
  * Exécute les tests unitaires sur chaque commit ou push.
  * Contrôle la conformité du code avec Flake8.

### Structure

```
.
├── .github/workflows/control_tests.yaml   # Définition du workflow CI
├── file__test.py                         # Fichier de tests unitaires
├── README.md                             # Ce fichier de présentation
```

### Compétences mises en œuvre

* **Automatisation des tests** avec GitHub Actions.
* **Mise en place de CI/CD** sur projet Python.
* **Tests unitaires** avec Pytest.
* **Linting et contrôle qualité** avec Flake8.
* **Travail collaboratif et gestion de version** avec Git et GitHub.
