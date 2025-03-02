# Linear_Regression_of_Flight_Prices

## Introduzione
Questo progetto si concentra sull'analisi dei dati relativi ai voli aerei effettuati tra le principali città dell'India tra l'11 Febbraio e il 31 Marzo 2022. L'obiettivo principale è applicare l'algoritmo di Regressione Lineare per prevedere il Prezzo dei voli (variabile target) in base a diverse variabili indipendenti, tra cui compagnia aerea, durata del volo, giorni di anticipo, classe del volo, e altre caratteristiche.

## Struttura del progetto
- Caricamento e Ispezione dei Dati: Il dataset è caricato in un DataFrame utilizzando Apache Spark e vengono esplorate le variabili presenti.
- Pulizia dei Dati: Rimozione di valori nulli, duplicati, e variabili non rilevanti per l'analisi, con trasformazioni su variabili quantitative e categoriali.
- Visualizzazione dei Dati: Analisi grafica per comprendere la distribuzione delle variabili e le relazioni tra di esse.
- Trasformazione dei Dati: Scaling delle variabili quantitative e encoding delle variabili categoriche per prepararle all'algoritmo di regressione.
- Costruzione del Modello: Applicazione di modelli di regressione lineare per prevedere il prezzo dei voli, utilizzando variabili indipendenti selezionate.
- Valutazione del Modello: Analisi delle performance del modello con i valori di R^2 e R^2 aggiustato, per valutare la sua accuratezza.

## Tecnologie utilizzate
- Apache Spark
- Pandas, Matplotlib, Seaborn (per la visualizzazione dei dati)
- PySpark MLlib (per l'analisi e la regressione lineare)
