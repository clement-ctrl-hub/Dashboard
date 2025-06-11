# Dashboard
Tableau de board réaliser dans le cadre de mes projets personnels.
# Dashboard Power BI — Ventes d'un concessionnaire automobile

Ce projet Power BI propose une visualisation complète des performances commerciales d’un concessionnaire auto. Il permet d’analyser les ventes selon plusieurs dimensions (temps, type de véhicule, sexe du client, région).

## Objectifs du tableau de bord

- Suivre les indicateurs clés (KPI) :
  - Total des ventes
  - Nombre de ventes
  - Marge totale
  - Revenu net
- Analyser les ventes par :
  - Année-Mois
  - Type de véhicule
  - Sexe du client
  - Région du vendeur
  - Ville
- Identifier les meilleurs vendeurs
- Suivre l'évolution mensuelle des ventes

## 📁 Fichier inclus

- `rapport_ventes.pbix` : fichier Power BI complet

## Modèle de données

Le modèle suit une architecture en étoile :
- **Table de faits** : `ventes`
- **Tables de dimensions** :
  - `clients`
  - `voitures`
  - `vendeurs`
  - `calendrier` (générée en DAX)

## Transformations Power Query

- Vérification des types de données
- Création de la table calendrier
- Fusion de colonnes pertinentes si nécessaire
- Nettoyage des doublons
- Formatage des dates et des valeurs monétaires

## Aperçu du rapport

![Aperçu du dashboard](chemin/vers/capture.png)

## Auteur

Clément Amegadjaka

---

