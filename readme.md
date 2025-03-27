# 🎯 Exercice 1 Grid CSS - Positionnement avec `grid-column`

## 📚 Objectif

Apprendre à utiliser **CSS Grid** pour positionner les éléments dans une grille en manipulant la propriété `grid-column`.

## 📦 Structure

- 4 éléments sont affichés dans une grille de 4 colonnes.
- Chaque élément est positionné avec `grid-column` pour occuper un ou plusieurs espaces spécifiques dans la grille.

## 🧠 Concepts abordés

- `display: grid`
- `grid-template-columns`
- `grid-column: start / end`
- Gestion de l'espacement avec `gap`

## 💡 Résultat attendu

- Item 1 dans la première colonne
- Item 2 sur deux colonnes (2 et 3)
- Item 3 dans la 4ème colonne
- Item 4 sur toute la ligne suivante, de la colonne 2 à 4

# 🧱 Exercice 2 CSS Grid – Mise en page avec `grid-template-areas`

## 📚 Objectif

Créer une **mise en page complète responsive** avec CSS Grid en utilisant les **zones nommées (`grid-template-areas`)**.

## 🧠 Concepts abordés

- `display: grid`
- `grid-template-areas`
- `grid-area`
- Grille responsive avec `@media screen`

## 🧩 Composition de la grille

| Zone     | Description                                |
| -------- | ------------------------------------------ |
| Header   | Bandeau du haut (3 colonnes)               |
| Sidebar  | Menu latéral (gauche) sur plusieurs lignes |
| Content1 | Premier bloc de contenu                    |
| Content2 | Deuxième bloc de contenu                   |
| Content3 | Troisième bloc de contenu                  |
| Footer   | Pied de page (3 colonnes)                  |

## 🖥 Responsive

À partir de `max-width: 768px`, la grille s’adapte :

- Les contenus se placent les uns en dessous des autres
- La sidebar reste à gauche sur plusieurs lignes
