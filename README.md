# 🚗 Prédicteur de Gamme de Prix - Véhicules d'Occasion

Cette application utilise un modèle de Machine Learning (Gradient Boosting Classifier) entraîné pour catégoriser le prix de revente d'un véhicule d'occasion en deux catégories : **Prix Standard** ou **Prix Élevé** (basé sur la valeur médiane des prix de vente).

## 📦 Contenu du projet
- **`app.py`** : Code de l'application interactive Streamlit.
- **`requirements.txt`** : Dépendances Python requises.
- **`list_items.joblib`** : Modèle de Machine Learning, encodeurs de variables et scaler pré-entraînés.
- **`.gitignore`** : Fichiers exclus du suivi Git.
- **`README.md`** : Guide d'installation et d'utilisation.

## 🛠️ Installation et exécution en local

1. **Cloner ou télécharger** les fichiers du projet.
2. **Créer un environnement virtuel** Python (optionnel mais recommandé) :
   ```bash
   python -m venv venv
   source venv/bin/activate  # Sur Mac/Linux
   venv\Scripts\activate     # Sur Windows
   ```
3. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt
   ```
4. **Lancer l'application** :
   ```bash
   streamlit run app.py
   ```

## 🚀 Déploiement sur Streamlit Community Cloud

1. Poussez ces fichiers vers un nouveau dépôt public sur votre compte **GitHub**.
2. Allez sur [share.streamlit.io](https://share.streamlit.io) et connectez-vous avec votre compte GitHub.
3. Cliquez sur **"Create app"**.
4. Sélectionnez votre dépôt, la branche `main`, et définissez `app.py` comme chemin du fichier principal (*Main file path*).
5. Cliquez sur **"Deploy!"** et votre application sera en ligne !
