# Prédiction du Prix des Voitures avec le Machine Learning

## Description  
Ce projet utilise des techniques de **Machine Learning** pour prédire le prix d’un véhicule en fonction de ses caractéristiques (année de fabrication, kilométrage, type de carburant, etc.).  
Nous comparons plusieurs modèles pour identifier celui offrant la meilleure précision.  

## 🎯 Objectifs  
- Explorer et analyser les données du marché automobile.  
- Nettoyer et préparer les données pour la modélisation.  
- Entraîner plusieurs modèles de Machine Learning et comparer leurs performances.  
- Évaluer la précision des modèles avec des métriques adaptées.  

## 📂 Dataset  
Le dataset utilisé provient de [Kaggle](https://www.kaggle.com/) et contient les informations suivantes :  
✔ **Année de fabrication**  
✔ **Prix**  
✔ **Kilométrage**  
✔ **Type de carburant**  
✔ **Puissance du moteur**  
✔ **Nombre de portes et de sièges**  

## Technologies utilisées  
- Python
- Pandas & NumPy (Manipulation des données)  
- Seaborn & Matplotlib (Visualisation)  
- Scikit-Learn (Modèles de Machine Learning)  

## Exploration des Données  
Les analyses exploratoires ont permis de dégager plusieurs tendances :  
- **Les voitures récentes sont en moyenne plus chères** 📈  
- **Le type de carburant influence le prix** : les voitures Diesel sont généralement plus coûteuses.  
- **Le kilométrage est un facteur clé** : plus une voiture a de kilomètres, plus son prix diminue.  

## Modélisation & Comparaison des Modèles  
Deux modèles de régression ont été entraînés :  
1️⃣ **Decision Tree Regressor**  
2️⃣ **Random Forest Regressor**

 **Le modèle Random Forest offre les meilleures performances en minimisant l’erreur moyenne absolue.**  

## Conclusion
**Objectifs atteints** : Un modèle permettant d’estimer le prix d’un véhicule avec une bonne précision.  

## Installation & Utilisation  
### **Cloner le projet**  
```bash
git clone https://github.com/MomoAy/CarPricePrediction.git
cd CarPricePrediction
pip -r requirements.txt
