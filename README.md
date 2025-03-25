# Projet AI Prediction - Classification du Cancer du Côlon

## 🔬 Description
Ce projet applique des algorithmes de classification supervisée sur un jeu de données d'expression génique du cancer du côlon (provenant de Kaggle) pour classer les échantillons en deux catégories : **"normal"** et **"cancer"**. L'objectif est de développer un modèle capable d'automatiser la détection de cette maladie à partir des profils d'expression génique.

---

## 🔧 Prérequis
- Python 3.x
- Jupyter Notebook
- Bibliothèques : `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

Installez les dépendances avec :
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🔍 Installation
1. Clonez le référentiel :
```bash
git clone https://github.com/ihssane2002/Projet-AI_prediction.git
```
2. Accédez au projet :
```bash
cd Projet-AI_prediction
```
3. Lancez le notebook :
```bash
jupyter notebook Projet_AI_Prediction.ipynb
```

---

## 📉 Utilisation
1. **Préparation des données** : Nettoyage, standardisation, et division des données en ensembles d'entraînement et de test.
2. **Exploration** : Analyse de la distribution des classes et visualisation des données (histogrammes, boxplots, pairplots).
3. **Modélisation** : Entraînement de plusieurs algorithmes de classification :
   - Régression Logistique
   - Support Vector Machine (SVM)
   - k-Nearest Neighbors (k-NN)
   - Arbre de Décision
   - Forêt Aléatoire
4. **Evaluation** : Utilisation de la matrice de confusion, du rapport de classification, et de la précision globale pour comparer les modèles.
5. **Interprétation** : Identification des gènes les plus influents pour la classification.

---

## 📊 Modèles Utilisés
- **Régression Logistique** : Simple et efficace pour des données linéairement séparables.
- **SVM** : Utilisation d'un noyau RBF pour capturer des relations complexes.
- **k-NN** : Classifie les échantillons selon leurs plus proches voisins.
- **Arbre de Décision** : Facile à interpréter mais sujet au surapprentissage.
- **Forêt Aléatoire** : Combine plusieurs arbres pour améliorer la robustesse.

---

## 📊 Résultats
- Les modèles ont atteint une précision de **100%** pour la Régression Logistique, SVM, et k-NN.
- Les gènes **SLC7A5**, **RNF43**, et **UGP2** se sont révélés les plus importants dans la classification.
- L'approche multi-modèle a permis de valider la robustesse des prédictions.

---

## 👨‍💼 Auteur
- **Ihssane BAMMAD**



