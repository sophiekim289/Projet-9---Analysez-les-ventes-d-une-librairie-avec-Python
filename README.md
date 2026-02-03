# Projet 9 – Analysez les ventes d'une librairie avec Python

## Contexte du projet

La librairie **Lapage** dispose d’un site e-commerce depuis **deux ans** et souhaite exploiter ses données afin de mieux comprendre ses **indicateurs financiers** et le **comportement de ses clients**.

Dans ce contexte, une mission de **Data Analyst** a été menée afin d’analyser les ventes, d’identifier des tendances significatives et de fournir des recommandations exploitables pour soutenir la prise de décision.

---

## Objectifs pédagogiques

- Analyser un jeu de données comportant des **séries temporelles** afin de mesurer des phénomènes statistiques
- Réaliser des **tests statistiques** pour tester et valider des hypothèses à partir des données

---

## Outils utilisés

- **Python**

---

## Résultats du projet

Toute analyse de données débute par une phase essentielle de **familiarisation**, d’**exploration** et de **nettoyage des données**.

Cette étape a permis d’identifier des **valeurs atypiques**, qui ont été exclues afin de ne pas biaiser les résultats et les analyses futures.  
Ces valeurs provenaient principalement de **clients BtoB**, dont les volumes d’achat étaient significativement plus élevés que ceux des clients particuliers.

### Analyse des indicateurs financiers

- Selon la **granularité temporelle**, les observations diffèrent :
  - Le **chiffre d’affaires quotidien** présente des variations marquées, avec des hausses et des baisses fréquentes
  - Le **chiffre d’affaires mensuel** permet une lecture plus nuancée des tendances globales

### Analyse du comportement des clients

- Le **genre** influence la catégorie de livres achetés.  
  Les femmes achètent davantage que les hommes, mais les **préférences de catégories restent similaires**  
  *(test du khi-deux)*

- Le **montant des achats** diffère selon l’âge :
