# Détection de Fraude Bancaire 💳🔍

Projet de Data Science et Machine Learning pour détecter des transactions bancaires frauduleuses.

## 🚀 Objectifs
- Construire un modèle capable de distinguer les transactions normales des fraudes.
- Comparer plusieurs algorithmes de Machine Learning.
- Créer une interface simple pour tester le modèle.

## 🛠️ Technologies utilisées
- **Python** (pandas, numpy, matplotlib, seaborn)
- **Machine Learning :**
  - Régression Logistique
  - XGBoost
- **Techniques :**
  - SMOTE (Synthetic Minority Oversampling Technique) pour gérer le déséquilibre des classes
- **Interface :**
  - Streamlit (application web interactive)

## 📊 Résultats
- Régression Logistique : très bon rappel (recall) sur la détection des fraudes.
- XGBoost : excellent compromis entre précision et rappel.
- SMOTE : améliore la représentation des fraudes pour l’entraînement.

## 🖥️ Interface
Une application Streamlit permet de tester le modèle en direct :
- Importer une transaction (ou saisir les valeurs).
- Obtenir la prédiction : **Fraude** ou **Transaction normale**.

## 👨‍💻 Auteur
Projet réalisé par **oussama jarroud**, étudiant en Master Data Science & IA.
