# Diagnostic Égalité F/H KNIME

## Résumé du projet :
Automatisation du diagnostic égalité femmes-hommes via workflow KNIME pour un cabinet de conseil (150+ salariés). L'objectif était de créer un processus reproductible calculant l'index légal égalité F/H et 5 indicateurs clés (écarts salariaux ETP par CSP, taux promotions, répartition F/H, ancienneté), avec anonymisation RGPD et génération automatique de graphiques pour présentation en plénière.

## Tâches réalisées :
Collecte et préparation des données : Import données SIRH (salariés, postes, rémunérations, temps de travail), vérification qualité (valeurs manquantes, doublons, types), jointures multi-tables.
Anonymisation conforme RGPD : Suppression identifiants directs (nom, prénom), génération ID anonymes, transformation date de naissance en tranches d'âge, application K-anonymat (groupes minimum 5 personnes).
Calculs d'indicateurs égalité F/H : Salaire équivalent temps plein (ETP), écarts de rémunération par CSP, taux de promotion par genre, répartition F/H par catégorie, calcul score index légal /100.
Workflow KNIME automatisé : Architecture ETL complète (import → nettoyage → anonymisation → calculs → visualisations → export CSV), commentaires exhaustifs sur chaque nœud, génération automatique de 5+ graphiques.

## Compétences et outils mobilisés :
Outils : KNIME Analytics Platform (workflow ETL, visualisations), nœuds (File Reader, Rule Engine, GroupBy, Joiner, Math Formula, Bar/Pie Charts).
Expertise : ETL/Data wrangling, anonymisation RGPD, calculs statistiques RH, conformité réglementaire (index égalité), automatisation reporting.

## Livrables :
Workflow KNIME commenté (.knwf)
Fichier CSV anonymisé prêt pour Tableau
Présentation plénière (méthodologie, score 78/100, recommandations)
Documentation anonymisation RGPD
