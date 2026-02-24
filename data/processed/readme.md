# Processed Data

In deze map worden alle bewerkte datasets opgeslagen die voortkomen uit de verschillende fasen van het CRISP-DM proces.

Elke dataset vertegenwoordigt een tussenstap in de data pipeline, zodat het proces reproduceerbaar en navolgbaar blijft.

## Structuur

- `df_v1_raw_clean.csv`  
  Ruwe dataset na correct inlezen en opschonen.

- `df_v2_almere_wijken.csv`  
  Dataset gefilterd op gemeente Almere en wijkniveau (WK-codes).

- `df_v3_selected.csv`  
  Dataset met alleen relevante variabelen voor analyse.

- `df_v4_structured.csv`  
  Dataset met correcte datatypes en jaarstructuur.

- `df_v5_clean_final.csv`  
  Analyseklare dataset na datakwaliteitscontrole.

- `df_v6_model_ready.csv`  
  Definitieve dataset met aangemaakte features (ratio, groei, lag) klaar voor modeling.

## Doel

Door elke stap afzonderlijk op te slaan:

- Is het proces reproduceerbaar
- Kunnen tussenstappen gecontroleerd worden
- Kunnen fouten eenvoudig worden teruggedraaid
- Blijft het CRISP-DM proces gestructureerd en transparant