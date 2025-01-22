# Guide : Ajouter des Badges GitHub Actions dans un README

## Étape 1 : Localiser les workflows GitHub Actions

1. Allez dans votre dépôt GitHub.
2. Cliquez sur l'onglet **Actions** dans la barre de navigation.
3. Vous verrez la liste des workflows configurés (par exemple, "Run Tests" et "Lint Code").

---

## Étape 2 : Générer le badge pour chaque workflow

1. **Sélectionnez un workflow :**
   - Cliquez sur le nom du workflow (par exemple, "Run Tests").

2. **Générez le badge :**
   - Dans l'interface du workflow, cliquez sur l'icône **"..."** (trois points) en haut à droite.
   - Sélectionnez **Create status badge**.

3. **Copiez le code Markdown généré :**
   - Un bloc de code vous sera proposé, ressemblant à ceci :
     ```markdown
     ![Tests](https://github.com/<votre-utilisateur>/<votre-repo>/actions/workflows/test.yml/badge.svg)
     ```
   - Remplacez `<votre-utilisateur>` et `<votre-repo>` par le nom de votre organisation ou utilisateur GitHub et le nom de votre dépôt.

4. Répétez cette opération pour tous les workflows (par exemple, "Lint Code").

---

## Étape 3 : Ajouter les badges dans le fichier `README.md`

1. **Ouvrez ou créez un fichier `README.md`** à la racine de votre dépôt.
2. Ajoutez les badges dans une section dédiée, comme ceci :

### Exemple de contenu pour `README.md` :
```markdown
# Mon Projet Python

![Tests](https://github.com/<votre-utilisateur>/<votre-repo>/actions/workflows/test.yml/badge.svg)
![Lint](https://github.com/<votre-utilisateur>/<votre-repo>/actions/workflows/lint.yml/badge.svg)

## Description

Ce projet Python inclut :

- Une fonction pour effectuer des opérations simples.
- Des tests unitaires pour garantir la fiabilité du code.
- Un linter pour assurer la qualité du code.

## Workflows GitHub Actions

- **Tests** : Vérifie que les tests unitaires passent correctement.
- **Lint** : Vérifie la qualité du code avec un linter.

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/<votre-utilisateur>/<votre-repo>.git
   cd <votre-repo>
