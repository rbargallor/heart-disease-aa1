# Estudi comparatiu de models d'aprenentatge automàtic per a la detecció de cardiopaties
 Projecte de l'assignatura AA1 (Aprenentatge Automàtic 1) del GCED - UPC

### Descripció

La medicina preventiva és clau en la reducció de morts per cardiopaties. Aquest projecte té com a objectiu avaluar diferents models d’aprenentatge automàtic per a la seva detecció. 
<br>El dataset utilitzat ha estat obtingut a partir del [Heart Disease de UCI Machine Learning](https://archive.ics.uci.edu/dataset/45/heart+disease) i conté 76 variables de 617 pacients relacionades amb problemes cardíacs. <br>Després de preprocessar degudament les dades, els següents models supervisats han estat ajustats amb els millors paràmetres segons la F2-score: QDA, LDA, Naive Bayes, Regressió Logística, KNN, Random Forest, Gradient Boosting i SVC. Tenint en compte les mètriques i propietats dels models, Gradient Boosting és el model amb millors resultats. <br>Posteriorment, s’han seleccionat les característiques de major rellevància per al model. En el test s’ha obtingut un F2-score de 0.8923 i una accuracy de 0.8381.


### Contingut

Aquest repositori conté el document en format pdf de l'estudi, així com el codi utilitzat per dur a terme l'estudi i les dades abans i després de ser tractades a la carpeta data/

### Prerequisits

Per poder executar i reproduir el codi utilizat per l'estudi és necessari disposar de:

```
python3
pandas
numpy 
matplotlib
seaborn
sklearn
```

### Execució

El fitxer del codi és AA1Colab.ipynb i es disposa de l'arxiu de dades tractades a la carpeta data/<br>
És recomanable executar l'arxiu en un entorn de Jupiter Notebbok o equivalent.

## Autors


* **Roger Bargalló Roselló** - *2n GCED* - [Github](https://github.com/rbargallor)
* **Laia Mogas Pladevall** - *2n GCED* - [Github](https://github.com/laiamp)

## Llicència
Aquest projecte està sota la llicència APACHE 2.0
