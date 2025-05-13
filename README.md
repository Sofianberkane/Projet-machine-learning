# Analyse de réplicats transcriptomiques de cellules

Ce projet Jupyter analyse trois réplicats de données transcriptomiques issues de cellules cancéreuses du sein de la lignée MDA-MB231. L'objectif principal est d'évaluer la **répétabilité des mesures** en utilisant des techniques de **réduction de dimension** (PCA) et de **classification** (K-means).

## 📁 Contenu du projet

Le notebook est structuré en plusieurs parties :

1. **Test et vérification des données**
   - Chargement des réplicats
   - Contrôle du format, des dimensions et de l'intégrité des valeurs

2. **Réduction de dimension (PCA)**
   - Application de la normalisation (centrage-réduction)
   - Visualisation de la variance expliquée
   - Comparaison des réplicats et données concaténées

3. **Classification (K-means)**
   - Détermination du nombre optimal de clusters via la wcSSE
   - Analyse des clusters sur données séparées et concaténées

4. **Affichage des résultats**
   - Représentation des données sur les premiers plans principaux
   - Visualisation des clusters et des répartitions

## ⚙️ Dépendances

Ce projet utilise Python avec les bibliothèques suivantes :

- `numpy`
- `matplotlib`
- `sklearn`
- `pandas`

Pour installer les dépendances :
```bash
pip install numpy matplotlib scikit-learn pandas se
