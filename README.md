# CampusLink - Systeme de Supervision et Gestion de Campus

> Plateforme web interne de gestion des ressources, de supervision du parc informatique et de suivi des incidents pour les infrastructures d'Ynov Campus.

---

## Sommaire

1. [A propos du projet](#a-propos-du-projet)
2. [Architecture et Stack Technique](#architecture-et-stack-technique)
3. [Arborescence du Projet](#arborescence-du-projet)
4. [Guide d'Installation et de Demarrage](#guide-dinstallation-et-de-demarrage)
5. [Fonctionnalites Principales](#fonctionnalites-principales)
6. [Guide de Contribution et Workflow Git](#guide-de-contribution-et-workflow-git)
7. [Licence et Auteur](#licence-et-auteur)

---

## A propos du projet

**CampusLink** est un projet de type fil rouge developpe dans le cadre de la formation en securite des systemes d'information a Ynov Campus. L'objectif est de concevoir un tableau de bord d'administration centralise, hautement performant, ergonomique et dote d'une interface en mode sombre avec des accents turquoise, inspiree des standards des outils de supervision reseau et SOC (Security Operations Center).

---

## Architecture et Stack Technique

Le projet repose sur une approche minimaliste zero-dependency (sans frameworks lourds ni bibliotheques tierces superflues) pour garantir des performances optimales, une legerete de chargement maximale et une securite accrue.

*   **Structure et Balisage :** HTML5 Semantique (Accessibilite et conformite W3C).
*   **Mise en page et Design System :** CSS3 
*   **Interactivite et Logique : gestion dynamique des formulaires, des filtres et des retours utilisateur.
*   **Controle de version :** Git et GitHub (`dylan21317/fil-rouge-campuslink`).

---

## Arborescence du Projet

```text
fil-rouge-campuslink/
│
├── index.html              # Tableau de bord principal (Vue d'ensemble)
├── salles.html             # Supervision de l'etat des salles et 
├── equipements.html        # Suivi du parc informatique et des equipements 
├── incidents.html          # Centre de signalement et de suivi des pannes
├── README.md               # Documentation technique du projet
└── css/
    └── style.css           # Feuille de style globale et personnalisation UI