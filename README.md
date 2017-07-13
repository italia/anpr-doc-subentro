# Buone pratiche per le attività di pre-subentro dei Comuni in ANPR


La procedura di subentro dei Comuni in ANPR rappresenta l'insieme delle attività che i Comuni devono realizzare per assicurare il trasferimento dei dati anagrafici dall'APR e AIRE locali al database centrale di ANPR, cosi come previsto dal [DPCM 194/2014](http://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.del.presidente.del.consiglio.dei.ministri:2014-11-10;194!vig=).

Per agevolare le attività dei Comuni nella gestione delle anomalie, sono state individuate le procedure operative che i Comuni debbono adottare. Tali procedure sono di ausilio, in particolare,  durante la fase di pre-subentro che consente al comune di simulare il subentro vero e proprio  per rilevare, preliminarmente al subentro, la presenza di eventuali criticità nella base dati. I passaggi delle  procedure nelle quali si indica di ripetere l’invio dopo aver sanato le anomalie sono riferite ESCLUSIVAMENTE a tale fase di pre-subentro: si ricorda che il subentro è un’operazione non ripetibile; le residue anomalie (o eventuali errori di estrazione) saranno sanate esclusivamente con i servizi di ANPR.

Nella [**tabella anomalie ANPR**](TAB01_ANOMALIE_ANPR.md) sono elencate le anomalie che il sistema ANPR rileva e, per ognuna di esse, si riporta il *codice anomalia* che la codifica, il *messaggio di errore* che viene indicato al Comune al riscontro della stessa, la *severità* associata all'anomalia, la *procedura suggerita* che il Comune può attuare per eliminare l'anomalia riscontrata. 

Tali anomalie derivano da controlli formali sui dati trasmessi dal Comune; nel dettaglio sono previste le seguenti severità per le anomalie rilevate:

- **warning non bloccanti**, si riscontrano difformità tra i dati trasmessi dal Comune e quelli attesi dal sistema ANPR, ma queste possono essere risolte successivamente al subentro (ad esempio: comune di registrazione dell'atto di annullamento di un matrimonio non indicato);
- **warning da rimuovere prima del subentro**, si riscontrano difformità tra i dati trasmessi dal Comune e quelli attesi dal sistema ANPR che richiedono un intervento sui dati da realizzarsi prima del subentro (ad esempio Codice fiscale formalmente non corretto);
- **errori**, i file inoltrati dal Comune presentano incongruenze tali da rendere non accettabili i dati da parte del sistema ANPR (ad esempio totale schede soggetto dichiarato nel file incongruente con l'effettivo numero di schede soggetto inoltrate).

Relativamente alle anomalie segnalate dal sistema ANPR come **warning non bloccanti**, l’esperienza maturata ad oggi dai Comuni subentrati suggerisce che la decisione di posticipare la correzione tenga presente anche del differente impegno, in termini organizzativi e di impegno necessario, che il Comune dovrà destinare alla bonifica dei dati in caso di correzione realizzata dopo il subentro. 
A titolo esemplificativo si consideri la circostanza di disallineamento della denominazione dei Comuni indicanti il luogo di matrimonio che preservi il codice Belfiore (condizione che preserva anche il codice fiscale) tra l’APR locale e le tabelle di codifica dei Comuni utilizzate da ANPR; in questo caso provvedere alla correzione delle anomalie degli errori prima del subentro, troverà il vantaggio di poter utilizzare procedure automatiche implementate ad uopo, permettendo di ridurre il tempo uomo impegnato se realizzate successivamente e singolarmente dopo il subentro.

Si precisa che la correzione del nominativo dei Comuni potrà avvenire solo contestualmente al subentro: infatti, INA SAIA non ha recepito integralmente la nuova tabella dei Comuni, per cui se le correzioni vengono effettuate in precedenza, si rischia di avere dei messaggi di errore a fronte delle trasmissioni dati giornaliere, dovuti all’incongruenza dei dati del Comune di nascita.


In sintesi le azioni di verifica realizzate da ANPR, fatti salvi gli errori che afferiscono la creazione del file che determinato lo scarto dell’interno invio, i controlli formali riguardano:

- il contenuto delle schede individuali, famiglia e convivenza, la coerenza dei vari attributi tra loro, la correttezza rispetto ai valori ammessi per i campi codificati;
- la validazione del codice fiscale, eseguita dall’Agenzia delle Entrate.


Nel ricordare che l'obiettivo ultimo del subentro è quello di assicurare che i dati presenti nelle APR locali siano trasferiti al sistema ANPR e nel contempo si assicuri l'allineamento dei codici fiscali associati ai soggetti così come attribuiti dall'Agenzia delle Entrate, si evidenzia che in caso di disallineamento tra il codice fiscale registrato dall'APR e quello attribuito dall'Agenzia delle Entrate, l'ufficiale di anagrafe deve dare seguito ai necessari accertamenti al fine di verificare che i dati registrati nell'APR o nell'AIRE locali corrispondano alle informazioni registrate sugli Atti dello stato civile. Nel caso in cui la correzione dei dati anagrafici in possesso dell'Agenzia delle Entrate determini la necessità di mutare il codice fiscale attribuito al cittadino, si suggerisce che l'ufficiale d'anagrafe, per sanare la circostanza rilevata, convochi il cittadino indicandogli le seguenti possibilità:

- applicazione dell'[articolo 36](http://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legge:2000-10-03;396%7Eart36) del DPR 396 del 3 novembre 2000 "Regolamento per la revisione e la semplificazione dell'ordinamento dello stato civile";
- applicazione dell'[articolo 89](http://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legge:2000-10-03;396%7Eart89) del DPR 396 del 3 novembre 2000 "Regolamento per la revisione e la semplificazione dell'ordinamento dello stato civile";
- invito al cittadino a rivolgersi all'Agenzia delle Entrate per una nuova assegnazione di codice fiscale.




