#  Projet SQL – Analyse des ventes e-commerce

**Réalisé avec :** SQL Server Management Studio (SSMS)  
**Fichier source :** Données Excel (ventes)

##  Objectif

Ce projet a pour but d’analyser des données de ventes e-commerce en utilisant **SQL**.  
Les données ont été importées dans une **base de données relationnelle**, puis nettoyées, enrichies et analysées.

---

##  Étapes principales

1. **Création de la base de données**  
   → Importation des données Excel dans une table SQL (`ventes_ecommerce`)

2. **Nettoyage des données**  
   → Vérification des valeurs manquantes, doublons, incohérences (prix/quantité)

3. **Ajout d’une colonne calculée**  
   → `CA = Prix_Unitaire × Quantité`

4. **Calculs d’indicateurs clés (KPIs)**  
   - Chiffre d’affaires total  
   - Nombre de commandes  
   - Quantité totale vendue  
   - Nombre de clients uniques

5. **Analyses par regroupement**  
   - CA par ville  
   - Top produits  
   - Répartition des paiements  
   - Évolution mensuelle du CA

---

## Résultat

Ce projet permet d’obtenir une vue d’ensemble des ventes, de détecter les tendances principales, et de poser les bases pour une future visualisation dans Power BI ou Excel.

---

## Technologies utilisées

- Microsoft SQL Server  
- SQL Server Management Studio (SSMS)  
- Langage SQL  
- Données source : fichier Excel
