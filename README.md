# Locality and transferability

Code for a short paper submitted to the Association of Geographic Information Laboratories in Europe (AGILE), 2024. 
It abides by DASA (Data and Software Availability). 

Details to follow. 


## Abstract




## Procedure and outcome 

### 1. Data collection
Corpus was generated from Guardian API. Once the text was retrieved, we went through data cleaning (e.g., removing irrelevant articles). 

### 2. Locating the corpus 
2.1 spaCy text processing, 2.2 NER retrieval, 2.3 POS-based place name retrieval, 2.4 merge the place name candidates, 

2.5 geolocating using ggmap, 

2.6 assign spatial boundary (spatial boundary data was acquired from https://geoportal.statistics.gov.uk/)

### 3. Identifying the values (attached code you can find)
3.1 spaCy text processing, 3.2 selecting nouns, 

3.3 fetch pre-built lexicons from Koblet & Purves (2020) (https://doi.org/10.1016/j.landurbplan.2020.103757) and Kong et al. (2023) (https://doi.org/10.1016/j.landurbplan.2023.104692), 

3.4 apply the pre-built lexicons to nouns. 


### 4. Plot the result 
4.1 prepare spatial boundary, 

4.2 total count map (Figure 2), 

4.3 map: attractiveness (Figure 3), 4.4 map: aesthetic (Figure 4), 

4.5 map: natural elements (Figure 5), 4.6 map: mammals (Figure 6), 4.7 map: biological values (Figure 7)

4.8 scatter plot: attractiveness - aesthetic values (Figure 8a)
4.9 scatter plot: mammals - biological values (Figure 8b)

