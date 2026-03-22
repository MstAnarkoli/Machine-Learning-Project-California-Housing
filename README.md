# Individuell inlämningsuppgift – Machine Learning 

## Projektbeskrivning
Målet med uppgiften är att bygga en reproducerbar maskininlärningsmodell som kan förutsäga och 
uppskatta bostadsvärdet baserat på tillhandahållen information. Modellen ska fungera som ett 
beslutsstöd för kommuner och fastighetsaktörer genom att ge en snabb värdering av 
bostadsområden baserat på deras egenskaper. 

---

# Hur man kör projektet

1. Klona repot


2. Öppna projektet i t.ex. VS Code eller Jupyter.

3. Installera beroenden (om de saknas):



4. Säkerställ att följande filen finns i projektmappen:
- `housing.csv`


5. Kör notebooken:



Notebooken kan köras från början till slut med **"Restart & Run All"**.


# Metod

Data preprocessing (SimpleImputer, StandardScaler, OneHotEncoder)
- Feature engineering
- Models:
  - Linear Regression
  - Decision Tree
  - Random Forest (final model)
- Cross-validation & GridSearchCV
- PCA and KMeans for analysis

## Results
- Bäst Model: Random Forest
- RMSE ≈ 50,216

