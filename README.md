# 🌍 India Population Visualization  

Une application interactive de visualisation de la population des États indiens, développée avec **Streamlit** et **Plotly**.  
L'application permet de visualiser divers paramètres démographiques sur une carte grâce à une interface simple et épurée.  

---

## 🚀 Fonctionnalités  

- **Sélection de l'État** : Visualisez la population d'un État spécifique ou de l'Inde entière.  
- **Paramètres de visualisation** :  
  - **Paramètre primaire** : La taille des points représente ce paramètre (ex. densité de population).  
  - **Paramètre secondaire** : La couleur des points représente ce paramètre (ex. revenu moyen).  
- **Carte interactive** :  
  - Visualisation via **Plotly Mapbox**.  
  - Zoom et navigation interactifs.  
  - Les points sont centrés sur les districts.  

---

## 🛠️ Installation  

### Prérequis  
- Python 3.x  
- Pip (gestionnaire de paquets)  

### Installation des dépendances  
```bash
pip install streamlit pandas plotly
streamlit run app.py
