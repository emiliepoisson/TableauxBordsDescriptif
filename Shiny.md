# Shiny 🐍

## 📋 Présentation

Shiny est un framework pour créer des app web directement en Python, sans écrire de HTML/CSS/JS.

---

## 🔧 Qu'est-ce qu'un framework ?

Un framework est :
un ensemble d'outils et de règles qui aide à créer une application plus facilement, sans repartir de zéro.
Il fournit : une structure, des composants prêts à l'emploi, une façon standard de travailler

| Sans framework | Avec un framework |
|----------------|-------------------|
| on doit gérer nous mêmes le site web, les boutons, l'affichage, les mises à jour… | on utilise les outils déjà faits (boutons, tableaux, graphiques) |

---

## ✨ Ce que Shiny permet de créer

Shiny permet de créer :
- des tableaux interactifs
- des tableaux de bord (dashboards)
- des outils de visualisation de données
- des applications de démonstration ou d'analyse

---

## 🏗️ Architecture de Shiny

Shiny fonctionne avec deux parties :

### L'interface utilisateur (UI), c'est ce que l'utilisateur voit :
- boutons
- menus déroulants
- curseurs
- tableaux
- graphiques

### Le serveur (server), c'est le code Python :
- il fait les calculs
- il traite les données
- il met à jour les résultats

---

## 🔄 Système réactif

Quand l'utilisateur agit sur l'interface, Shiny met automatiquement à jour les résultats.

Shiny est basé sur un système réactif : Quand une donnée change, tout ce qui en dépend est recalculé automatiquement.
Exemple : l'utilisateur change un filtre, le tableau se met à jour et le graphique se met à jour.

---

## 👥 Utilisation collaborative

Shiny permet plusieurs personnes peuvent ouvrir la même application : 
- chacun a sa propre session
- tous voient les mêmes données de base

### Ce que Shiny ne permet pas directement : 
- modifier un tableau à plusieurs en même temps
- collaboration temps réel comme Google Sheets

Shiny est surtout un outil de consultation et d'analyse, pas d'édition collaborative.

---

## 💰 Tarification

Est-ce que Shiny est payant ?

**Shiny pour Python est gratuit (open source)**
on peut l'utiliser et l'héberger soi-même

Il existe des solutions payantes (entreprise) pour :
- gérer les utilisateurs
- sécuriser l'accès
- faciliter le déploiement
