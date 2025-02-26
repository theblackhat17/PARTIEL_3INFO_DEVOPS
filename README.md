# 🚀 Projet DevOps : CI/CD avec GitHub Actions

[![Run Tests](https://github.com/theblackhat17/PARTIEL_3INFO_DEVOPS/actions/workflows/tests.yml/badge.svg?branch=master)](https://github.com/theblackhat17/PARTIEL_3INFO_DEVOPS/actions/workflows/tests.yml)  
[![Lint Code](https://github.com/theblackhat17/PARTIEL_3INFO_DEVOPS/actions/workflows/linter.yml/badge.svg?branch=master)](https://github.com/theblackhat17/PARTIEL_3INFO_DEVOPS/actions/workflows/linter.yml)

## 📌 Description
Ce projet DevOps intègre un pipeline **CI/CD** automatisé avec **GitHub Actions** pour assurer la qualité et la fiabilité du code Python. Il inclut :

- 🔹 **Tests unitaires** avec `unittest` pour garantir la robustesse du code.
- 🔹 **Linting** avec `flake8` pour s'assurer du respect des bonnes pratiques de codage.
- 🔹 **Intégration continue (CI)** pour exécuter les tests et analyser la qualité du code à chaque `push` ou `pull request`.

---

## ⚙️ Configuration & Installation

### 1️⃣ **Cloner le dépôt**
```bash
git clone https://github.com/theblackhat17/PARTIEL_3INFO_DEVOPS.git
cd PARTIEL_3INFO_DEVOPS
```

### 2️⃣ **Créer et activer un environnement virtuel**
```bash
python -m venv venv
source venv/bin/activate  # Windows : venv\Scripts\activate
```

### 3️⃣ **Installer les dépendances**
```bash
pip install -r requirements.txt
```

---

## 🧪 Exécution des tests
### 4️⃣ **Lancer les tests unitaires**
```bash
python -m unittest tests_app.py
```
Si tout se passe bien, les tests doivent être validés ✅.

---

## 🚀 Workflows GitHub Actions
### 🛠️ **Automatisation des tâches DevOps**
- **📌 `Run Tests`** : Exécute les tests unitaires automatiquement.
- **📌 `Lint Code`** : Vérifie la qualité du code Python.

Ces workflows sont déclenchés **automatiquement** à chaque `push` ou `pull request`.

---

## 📝 Auteurs & Contributions
👤 **@theblackhat17** - Développement et intégration DevOps.

🔄 Contributions bienvenues ! N'hésite pas à forker et proposer des améliorations via une `Pull Request`.

---

## 📜 Licence
Projet sous licence **MIT**. Utilisation libre et ouverte à la communauté ! 🎉
