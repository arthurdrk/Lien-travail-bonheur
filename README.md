# Analyse du Bonheur avec SAS

## 📌 Présentation du Projet
Ce projet explore les liens entre le bonheur et divers facteurs liés au travail, notamment le salaire, le temps de travail et le niveau de responsabilité. À partir des données de l'**European Social Survey (ESS) - Vague 6 (2012)**, une analyse statistique a été réalisée avec **SAS** pour construire un indice synthétique du bonheur et un indicateur de "qualité de l'emploi".

## 📊 Objectifs
- Analyser les corrélations entre le bonheur et différents facteurs professionnels.
- Construire un **indice synthétique du bonheur** pour surmonter les biais des réponses subjectives.
- Définir un **indice de qualité de l'emploi**, intégrant le salaire, l'équilibre pro/perso et l'autonomie.
- Présenter les résultats sous forme de **visualisations statistiques** (boîtes de Tukey, heatmaps, distributions, etc.).

## 📁 Structure du Projet
```
📂 Projet-Bonheur-SAS/
│── 📜 README.md           # Documentation du projet
│── 📜 mémoire_sas.pdf     # Mémoire détaillant l'étude
│── 📜 code_sas.sas        # Code SAS utilisé pour l'analyse
│── 📜 ess_data.csv        # Données de l'ESS (échantillon filtré pour la France)
│── 📂 graphs/             # Graphiques générés
│── 📂 reports/            # Rapports et exports de résultats
```

## 🚀 Installation & Exécution
### 📌 Prérequis
- **SAS** (logiciel ou SAS OnDemand for Academics)
- Fichier de données ESS (fourni dans le projet)

### ▶️ Exécution du Code
1. **Importer les données** : Vérifiez que `ess_data.csv` est bien placé dans le répertoire de travail.
2. **Lancer le script SAS** : Exécutez `code_sas.sas` dans votre environnement SAS.
3. **Visualiser les résultats** : Les analyses et graphiques seront générés dans le dossier `graphs/`.

## 📊 Méthodologie
1. **Analyse initiale** : Étude des relations entre bonheur et facteurs professionnels.
2. **Construction de l'indice synthétique du bonheur** (agrégation de 15 variables en 4 catégories : Sens, Motivation, Énergie, Satisfaction).
3. **Création de l'indice de qualité de l'emploi** (salaire, équilibre pro/perso, autonomie au travail).
4. **Interprétation des résultats** : Corrélations, régressions et visualisations.

## 📈 Résultats Clés
- Le bonheur augmente avec le **revenu**, mais ne montre pas de plateau clair.
- L'**équilibre travail/vie personnelle** a un effet significatif sur le bien-être.
- Une **plus grande autonomie au travail** est corrélée à un niveau de bonheur plus élevé.
- L'**indice de qualité de l'emploi** est modérément corrélé au bonheur (`r = 0.36`).

## 📚 Références
- **European Social Survey (ESS) - Vague 6 (2012)**
- **Kahneman & Deaton (2010)** : "High income improves evaluation of life but not emotional well-being"
- **Killingsworth (2021)** : "Experienced well-being rises with income, even above $75,000 per year"

## 🛠 Améliorations Possibles
- Intégration de **données supplémentaires** (facteurs sociaux, santé, etc.).
- Comparaisons **internationales** sur la relation travail-bonheur.
- Développement d'une **interface interactive** pour visualiser les analyses.

📌 *Ce projet est open-source ! Contributions et discussions bienvenues.* 🎉

