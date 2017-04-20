# Subentro Comuni
La procedure di subentro dei Comuni in ANPR rappresenta l'insieme delle attività che i Comuni devono realizzare per assicurare il trasferimento dei dati anagrafici dall'APR e AIRE locali al database centrale di ANPR, cosi come previsto dal [DPCM 194/2014](http://www.normattiva.it/atto/caricaDettaglioAtto?atto.dataPubblicazioneGazzetta=2015-01-08&atto.codiceRedazionale=15G00002&currentPage=1).

Per l'utilizzo del sistema ANPR il Comune potra scegliere, in base alle proprie esigenze operative, tra:

- la Web Application ANPR (in breve WA) o la variante WA integrata;
- l'integrazione del proprio sistema gestionale attraverso i Web Services (in breve WS) esposti da ANPR.

Il sistema ANPR mette a disposizione dei Comuni le necessarie funzionalità per:

- verificare il software sviluppato dal Comune per l’estrazione dei dati dall’anagrafe comunale ed il loro invio ad ANPR (test del subentro);
- apprendere le modalità di funzionamento della Web Application (WA e WA integrata);
- verificare il funzionamento del proprio sistema gestionale integrato con i servizi di ANPR (WS);
- verificare l’allineamento delle proprie basi dati locali di servizio (WA integrata e WS).

Si rimanda alla [**Guida ad ANPR**](https://www.anpr.interno.it/portale/guida-anpr) che sintetizza le funzionalità a disposizione dei Comuni.

Indipendentemente dalla scelte dei Comuni, per assicurare il trasferimento dei dati dalla APR e AIRE locali al database centrale di ANPR, i Comuni predispongano i necessari file di subentro e inoltrano gli stessi al sistema ANPR nelle modalità indicate nel documento [**Invio del file di subentro**](https://www.anpr.interno.it/portale/documents/20182/23925/Invio+file+di+Subentro.pdf/e0c98d8d-363a-4ca3-adcf-3e9613632be4).

Le attività di subentro, in breve, prevedono l'esecuzione delle seguente azioni:

- il Comune estrare le informazioni contenute nei propri sistemi locali (APR e AIRE), predispone i file di subentro nel rispetto del formatto definito ed inoltra gli stessi al sistema ANPR tramite le funzionalità messe a disposizione dalla WA;
- completato l’invio, i dati trasmessi dal Comune sono sottoposti ai seguenti controlli  formali: (i) validazione del codice fiscale previo confronto con l'Anagrafe Tributaria e (ii) verifica di congruità  con  i  dati  contenuti  nell'ANPR  al momento del subentro.

I controlli formali realizzati dal sistema ANPR possono determinare l'evidenza di anomalie nei file trasmessi dal Comune, di specie sono previste le seguenti *severità* per le anomalie rilevate:

- **warning non bloccanti**, nel caso in cui si riscontrino difformità tra i dati trasmessi dal Comune e quelli attesi dal sistema ANPR che possono essere risolti successivamente al subentro (ad esempio Comune/provincia di registrazione atto di cessazione/annullamento matrimonio inesistente);
- **warning da rimuovere prima del subentro**, nel caso in cui si riscontrino nei dati trasmessi dal Comune situazioni che richiedono un intervento sui dati da realizzarsi prima del subentro (ad esempio Codice fiscale formalmente non corretto);
- **errori**, nel caso in cui i file inoltrati dal Comune presentano inconguenze sostanziali che rendono non accettabile i dati da parte del sistema ANPR (ad esempio totale schede soggetto dichiarato nel file incongruente con l'effettivo numero di schede soggetto inoltrate).

Per aggevolare le attività dei Comuni per la gestione delle anomalie che possono presentarsi a valle dell'inoltro dei file di subentro al sistema ANPR, si sono individuate una serie di procedure che i Comuni possono adottare per le differenti anomalie che il sistema ANPR segnalera a valle dell'esecuzione dei controlli formali previsti.

Nella [**tabella anomalie ANPR**](TAB01_ANOMALIE_ANPR.md) sono elencate le anomalie che il sistema ANPR rileva e, per ognuna di esse, si riporta il *codice anomalia* che la codifica, il *messaggio di errore* che viene indicato al Comune al riscontro della stessa, la *procedura suggerita* che il Comune può attuare per eliminare l'anomalia riscontrata. 