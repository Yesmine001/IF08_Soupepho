# IF08 - Soupepho
Page web statique et responsive affichant la recette d'une soupe Pho de Marmiton avec des données nutritionnelles dynamiques issues de l'API OpenFoodFacts.

## Site en ligne
http://www.orkidees.com/IF08/soupepho

## Technologies utilisées
- HTML5 / CSS3
- Bootstrap 5.3 
- JavaScript (API Fetch)
- OpenFoodFacts API v2

## Structure du projet

- `index.html` – Page principale
- `css/style.css` – Styles personnalisés
- `js/main.js` – Logique Javascript
- `data/` – Fichiers de données JSON (titres, étapes, codes-barres)

## Lancer le projet en local
Aucune compilation nécessaire. Deux options :

**Option 1 – ouverture directe :**
Ouvrez `index.html` dans votre navigateur.
Attention : l'API OFF peut être bloquée par CORS sur certains navigateurs.

**Option 2 – serveur local (recommandé) :**
```bash
npx serve .
# puis ouvrez http://localhost:3000
```

## Bonnes pratiques
- Tous les identifiants et noms de classes sont en anglais
- Pour les styles en ligne : utilisez css/style.css
- Pour les scripts en ligne : utilisez js/main.js
- Messages de commit en anglais, à l’impératif (ex. : Add recipe)
- Un seul sujet par commit : ne pas regrouper des modifications non liées
-  Toujours effectuer un pull avant de pousser : git pull origin main

## Nommage des branches (en anglais)
feature/nom-de-votre-fonctionnalité 
fix/ce-que-vous-corrigez
Exemples : `feature/recipe-steps`, `fix/api-timeout`
