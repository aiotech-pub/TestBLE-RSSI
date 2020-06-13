# TestBLE-RSSI
Repository che contiene informazione, dati, applicazioni e programmi utili per il test del RSSI di dispositivi Bluetooth/BLE

## FOGLIO ELETTRONICO
Il foglio elettronico consente di raccogliere con semplicità i dati misurati. Per ogni test sono presenti campi per 10 misure. Non è obbligatorio eseguire 10 misure per ogni test, se ne possono eseguire anche di meno purché si effettui lo stesso numero di misure per ogni test. I campi MEDIA e MEDIANA sono calcolati automaticamente.
- MEDIA: coincide con la media aritmetica
- MEDIANA: è il valore che occupa la posizione cenrtale in una serie di dati ordinati. Nel caso il numero di dati sia pari la mediana è ottenuta come media aritmetica dei 2 valori centrali.
Il motivo per cui sono previsti 10 campi per le misure è che RSSI non è costante nel tempo e nel caso del Bluetooth/BLE in cui le potenze in gioco sono molto basse è maggiormente variabile.

## UPLOAD DEI DATI
Una volta eseguite le misure potete fare l'upload dei dati - preferibilmente in formato CSV con il carattere ; (punto e virgola) come separatore dei campi. In questo modo, alla fine, mi sarà più semplice raccogliere i dati, analizzarli e pubblicare i risultati. Per favore date un nome univoco al vostro file dati così da non sovrascrivere quelli pubblicati da altri. Suggerisco di usare il formato mm-20200613.csv dove mm sono le proprie iniziali (nome e cognome) seguite da un - di separazione e la data nel formato annomesegiorno senza separatori. In caso di omonimia si deve interporre un progressivo dopo le iniziali.
Esempio:
  mm-1-202500613.csv
  
