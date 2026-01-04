# MarGui-Project

Questa repository contiene il codice del progetto di `Laboratorio di informatica applicata` in particolare l'applicativo TickerTracker

## TickerTracker

TickerTracker è un esempio applicativo del modello che abbiamo sviluppato come progetto finale
* l'idea è che questo tool possa servire da ausilo per trader e investitori per confrontare le loro idee di trading con un modello di Machine Learning, in modo da capire se le loro intuizioni sono valide o meno
* l'applicativo consente di monitorare l'andamento di un ticker azionario (In questo caso è fornito un modello per AAPL) e confrontare le previsioni del modello con i dati reali di mercato, mostrando grafici e cosa pesa il modello in quell giorno e i 4 precedenti
* **NON è uno strumento finanziario** e non deve essere usato da solo per prendere decisioni di investimento

### Installazione
Viene fornito un'applicazione funzionante, è necessario avere installato docker e eseguire questi due comandi nella cartella `TickerTracker`:
```bash
docker build -t 'tickertracker' . # Costruisce l'immagine docker
```
```bash
docker run -p 5000:5000 tickertracker # Esegue il container alla porta 5000
```