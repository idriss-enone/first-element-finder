# Build a First Element Finder - Recherche du premier élément

## Objectif

Créer une fonction JavaScript capable de parcourir un tableau et de retourner le **premier élément** qui satisfait une condition donnée (fonction de test).

---

## Description du projet

La fonction `findElement` reçoit :
- un **tableau**
- une **fonction de test** (truth test)

La fonction applique la fonction de test à chaque élément du tableau, dans l’ordre.
- ✅ Si un élément passe le test → la fonction retourne cet élément 
- ❌ Si aucun élément ne passe le test → la fonction retourne `undefined`

---

## Fonction attendue

```js

function findElement(arr, func)

```

---

## Fonctionnement

1. La fonction parcourt le tableau élément par élément
2. Pour chaque élément, elle applique la fonction de test fournie
3. Dès qu’un élément valide la condition (`func(element) === true`), la fonction le retourne
4. L’itération s’arrête immédiatement après la première correspondance
5. Si aucun élément ne passe le test, la fonction retourne `undefined`

---


## Exemples 

```js

findElement([1, 3, 5, 8], num => num % 2 === 0);
// → 8

findElement([1, 3, 5], num => num % 2 === 0);
// → undefined

```
---

## Compétences développées
  
À travers ce projet, les compétences suivantes ont été développées :

### Programmation JavaScript

- Création et utilisation de fonctions
- Manipulation des tableaux (`array`)
- Utilisation des boucles (`for`)
- Fonctions de rappel (callbacks)
- Retour de valeurs (`return`, `undefined`)

### Manipulation des données

- Parcours d’un tableau
- Application d’une fonction de test
- Détection du premier élément valide
- Arrêt anticipé d’une boucle
  
### Logique algorithmique

- Analyse séquentielle des données
- Validation de conditions logiques
- Optimisation par arrêt de boucle
- Gestion des cas limites (aucune correspondance)

### Bonnes pratiques de développement

- Code clair et lisible
- Nommage explicite des fonctions et variables
- Respect du principe de responsabilité unique
- Tests simples avec console.log

### Utilisation de Git (conceptuellement) 

- Création du projet
- Ajout progressif des fonctionnalités
- Messages de commit clairs et explicites
- Suivi de l’évolution du code


### Lecture et compréhension de code 

- Compréhension des fonctions de rappel
- Analyse du comportement des boucles
- Comparaison entre boucle classique et méthodes natives
- Capacité à expliquer son raisonnement

### Compétences transversales

- Résolution de problèmes
- Rigueur et logique
- Autonomie dans l’apprentissage
- Capacité à documenter son travail (README)

---

## Technologies utilisées

| Technologie | Description |
|--------------|-------------|
| **JavaScript (ES6+)** | Langage utilisé pour le script |
| **Node.js** | Environnement d’exécution |
| **VS Code** | Éditeur de code utilisé |

---

##  Lancer le projet

1. **Cloner le dépôt GitHub :**
   ```bash
   git clone https://github.com/idriss-enone/first-element-finder.git 

2. **Ouvrir le projet :**

  - Ouvrir le dossier dans **VS Code**.
  - Ouvrir le fichier `script.js`.

3. **Exécuter le code :**
    - Via la console du navigateur dans une page HTML liée au script ;
    - Ou via Node.js :
      ```bash
      node script.js

---

## Auteur

Projet réalisé par **Idriss Enone** dans le cadre d’un apprentissage en JavaScript.

---









