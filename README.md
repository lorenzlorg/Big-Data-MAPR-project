# Machine Learning models
*Progetto del corso Big Data Management and Analysis in Physics Research (Laurea magistrale Data Science)*

<p align="center">
  <img width="500" height="300" src="https://www.ionos.it/digitalguide/fileadmin/DigitalGuide/Teaser/deep-learning-vs-machine-learning-t.jpg">
</p>


## Esercizio Classificazione
L'Organizzazione mondiale della sanità ha stimato che 12 milioni di decessi si verificano in tutto il mondo, ogni anno a causa di malattie cardiache. La metà dei decessi negli Stati Uniti e in altri paesi sviluppati è dovuta a malattie cardiovascolari. La prognosi precoce delle malattie cardiovascolari può aiutare a prendere decisioni sui cambiamenti dello stile di vita nei pazienti ad alto rischio e, a sua volta, ridurre le complicanze.

In questo esercizio si chiedere di utilizzare i decision tree (e magari i boosted decision trees) per individuare i fattori di rischio delle malattie cardiache più rilevanti e prevedere il rischio complessivo utilizzando la regressione logistica.

[Codice](https://github.com/lorenzlorg/Big-Data-MAPR-project/blob/main/Esercizio%20Classificazione.ipynb)





## Esercizio serie storica
Questo secondo esercizio richiede di effettuare un'analisi di dati di serie storica.

Leggendo il dataset data/globaltemperatures.csv, caricare i dati della media della temperatura nei diversi mesi dell'anno dal 1750. Plottare la serie dati, analizarne le caratteristiche (tendenza e stagionalità) e provare a fare una regressione lineare del trend (per valutarne la tendenza). Per fare regressione lineare di una timeseries è conveniente trasformare l'indice (l'asse X) in un numero che indica il numero di periodi passati dal momento inziale.

Infine provare a usare la serie storica per produrre le temperature dei successivi 10 anni.

[Codice](https://github.com/lorenzlorg/Big-Data-MAPR-project/blob/main/Esercizio%20Serie%20Storica.html)


## Predizione di malattie cardiache

Prevedere se un paziente ha probabilità di contrarre una malattia cardiaca o meno. Abbiamo un dato che classifica se i pazienti hanno o meno malattie cardiache in base alle caratteristiche in esso contenute. Cercheremo di utilizzare questi dati per creare un modello che tenti di prevedere se un paziente ha questa malattia o meno.

Il set di dati è memorizzato nel file heart.csv e preso da https://archive.ics.uci.edu/ml/datasets/Heart+Malattiaage.

[Codice](https://github.com/lorenzlorg/Big-Data-MAPR-project/blob/main/Predizione%20di%20malattie%20cardiache.html)

*Keywords*: machine learning, time series.
