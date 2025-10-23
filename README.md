# 🏥 Analyse des Coûts d'Assurance Médicale

## 📋 Description du Projet

Ce projet analyse les coûts d'assurance médicale en fonction de divers facteurs démographiques et de style de vie tels que l'âge, le sexe, l'IMC, le nombre de personnes à charge, les habitudes tabagiques et la région de résidence.

**Hackathon Subject 2**: Analyzing Medical Insurance Costs

---

## 🎯 Objectifs

- Analyse exploratoire des données (EDA)
- Prétraitement des données
- Exploration des caractéristiques
- Créer visualisations graphiques à l'aide de Matplotlib et Seaborn
- Analyser les variation régionales des coûts (bonus)

---

## 📁 Structure du Projet

```
README.md                           # fichier README
requirements.txt                    # Dépendances Python
hackaton.py                         
```

---

## 🚀 Installation

### Prérequis

- Python 3.11+
- pip

### Installation des dépendances

```bash
pip install -r requirements.txt
```

Les packages requis sont :
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 💻 Utilisation

### Option 1 : Exécution du programme


python3 hackaton.py

Cette commande exécute le fichier python du projet


## 📊 Étapes de l'Analyse

### 1️⃣ Analyse Exploratoire des données (EDA)


**Objectifs**:
- Effectuer une analyse complète de l'ensemble de données pour comprendre la répartition des variables et identifier toute corrélation entre des caractéristiques telles que l'âge, l'IMC, le statut de tabagisme et les frais médicaux (charges).
- Utilisez des statistiques et des visualisations descriptives pour résumer les données et mettre en évidence les tendances ou les valeurs aberrantes intéressantes.


### 2️⃣ Prétraitement des données

**Objectifs**:

- Gérer les données manquantes et effectuer tout nettoyage de données nécessaire.
- Application d'une normalisation sur les valeurs age, bmi, et charges
- Encoder les valeurs numériques des colonnes sex, smoker, et region

---

### 3️⃣ Exploration des caractéristiques

**Objectifs**:
- Explorez l'impact des différentes caractéristiques sur les coûts médicaux, en vous concentrant sur des variables clés telles que l'IMC, le statut de tabagisme et le nombre de personnes à charge.
- Étudiez les interactions potentielles entre les variables et la façon dont elles influencent les frais d'assurance à l'aide d'une matrice de corrélation et de graphiques.
- Tester les interactions entre variables
- Effectuer des tests statistiques (t-test)


### 4️⃣ Visualisations (Matplotlib & Seaborn)


**Objectifs**:
- Utilisez Matplotlib et Seaborn pour créer des visualisations qui communiquent efficacement vos résultats. Les exemples peuvent inclure des diagrammes de dispersion, des diagrammes de boîtes, des cartes thermiques et des graphiques à barres.

**Types de visualisations créées**:
- **Boxplot** - Frais selon le statut de fumeur / Frais par nombre d'enfants et cigarette / Distribution des frais médicaux par région (Trié par moyenne)
- **lineplot** - Age vs Frais
- **scatterplot** - IMC vs Frais
- **Violinplot** - Charges moyennes par région / Comparaison des frais médicaux par genre Homme/Femme /  Distribution des frais médicaux par fumeur
- **Jointplots** - Âge vs Charges
- **Heatmap** - Matrice de corrélation
- **Barplots** - Charges moyennes par région / fumeur par région


### 5️⃣ Regional Analysis (BONUS)


**Objectifs**:
- Comparer les charges entre les 4 régions (northeast, southeast, southwest, northwest)
- Identifier les facteurs régionaux


## 🛠️ Technologies Utilisées

- **Python 3.11** - Langage de programmation
- **pandas** - Manipulation de données
- **numpy** - Calculs numériques
- **matplotlib** - Visualisations de base
- **seaborn** - Visualisations statistiques avancées
- **scikit-learn** - Preprocessing et normalisation

---

## 👥 Auteur

Mehdi Al-Ajhoury
Stéphane Boulanger
Emmanuel Mussche

**Data Analysis Team**  
Hackathon Subject 2 - Medical Insurance Cost Analysis  
Octobre 2025

---

## 📄 Licence

Ce projet est développé dans le cadre d'un hackathon éducatif.

**Dernière mise à jour**: Octobre 2025

