# 📊 Voorspelling Jeugdpopulatie Almere (2019–2025)

## Projectbeschrijving

De gemeente Almere wil beter kunnen inspelen op toekomstige zorgbehoeften van jongeren.  
In dit project ontwikkelen wij een voorspellend model dat het aantal jongeren per wijk voorspelt in de leeftijdscategorieën:

- 0–15 jaar  
- 15–25 jaar  

Het model gebruikt historische CBS-data van 2019–2025 om trends te analyseren en toekomstige ontwikkelingen te voorspellen.


## Doel van het Project

- Inzicht krijgen in demografische ontwikkelingen per wijk  
- Trends in jeugdgroei analyseren  
- Een voorspellend model bouwen  
- Evalueren hoe betrouwbaar de voorspellingen zijn  
- De gemeente ondersteunen bij beleidsplanning  


## Methodologie (CRISP-DM)

Het project volgt de CRISP-DM methodologie:

1. **Business Understanding**  
   Probleemdefinitie en doelstellingen bepalen.

2. **Data Understanding**  
   Dataset analyseren, trends ontdekken en datakwaliteit controleren.

3. **Data Preparation**  
   Data opschonen, relevante variabelen selecteren en model-klaar maken.

4. **Modeling**  
   Een voorspellend model bouwen (lineaire regressie).

5. **Evaluation**  
   Modelprestaties beoordelen met MAE, RMSE en R².


## Projectstructuur

```
├── data/
│   ├── raw/              # Originele datasets
│   └── processed/        # Opgeschoonde datasets
│
├── notebooks/
├── final/
│   └── Gemeente_notebook.ipynb
├── individual/
│   ├── Noah_notebook.ipynb
│   ├── Bo_notebook.ipynb
│   ├── Wail_notebook.ipynb
│   ├── Faysel_notebook.ipynb
│   └── Ismael_notebook.ipynb
│
├── README.md
└── .gitignore
```

## Dataset

Gebruikte data:

- CBS wijkdata Almere (2019–2025)


## Conclusie

Dit project levert een eerste voorspellend prototype op dat inzicht geeft in de ontwikkeling van het aantal jongeren per wijk in Almere.
Het model kan worden uitgebreid met aanvullende variabelen en langere historische tijdreeksen voor verbeterde nauwkeurigheid.