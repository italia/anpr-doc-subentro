# Tabella anomalie ANPR

> ritorna [*README*](README.md)


|codice anomalia | messaggio di errore | severità | procedura suggerita|
| ------------- | ------------- | ------------- | ------------- |
|	EA001	|	Codice fiscale formalmente non corretto	| warning da rimuovere prima del subentro | [Procedura 001](procedure/PROCEDURA_001.md) |
|	EA002	|	Soggetto presente in AT con  DA uguali a quelli del comune ma CF del comune assente	| warning non bloccante | [Procedura_002](procedure/PROCEDURA_002.md) |
|	EA003	|	Soggetto presente in AT con  DA uguali a quelli del comune ma CF diverso	| warning non bloccante | [Procedura_002](procedure/PROCEDURA_002.md) |
|	EA029	|	Codice fiscale calcolato dai  DA del comune non presente in AT	| warning non bloccante | [Procedura_003](procedure/PROCEDURA_003.md) |
|	EA030	|	CF di un soggetto residente  in piu' comuni	| warning non bloccante | [Procedura_005](procedure/PROCEDURA_005.md) |
|	EA031	|	CF di un soggetto residente  sia in Italia che all'estero (AIRE)	| warning da rimuovere prima del subentro | [Procedura_005](procedure/PROCEDURA_005.md) |
|	EA036	|	Soggetto registrato piu' volte sia con il CF base che con quello che risolve l'omocodia  	| warning non bloccante | [Procedura_005](procedure/PROCEDURA_005.md) |
|	EA038	|	Soggetto con data di nascita non coincidente  con quella presente nel CF	| warning da rimuovere prima del subentro | [Procedura_004](procedure/PROCEDURA_004.md)  |
|	EA040	|	Soggetto registrato piu' volte  sia con il CF collegato che con l'ultimo	| warning non bloccante | [Procedura_005](procedure/PROCEDURA_005.md) |
|	EA042	|	Soggetto con sesso non coincidente  con quello presente nel CF	| warning da rimuovere prima del subentro | [Procedura_004](procedure/PROCEDURA_004.md) |
|	EA047	|	Soggetto presente  nell'archivio AIRE e nel MAE dei cittadini non residenti (IRREPERIBILI, RIMPATRIATI, DECEDUTI,  TRASFERITI)	| warning non bloccante | NON APPLICATA: in attesa di collegamento con MAE |
|	EA048	|	Codice fiscale formalmente errato	| warning da rimuovere prima del subentro | [Procedura_001](procedure/PROCEDURA_001.md) |
|	EC001	|	Codice stato civile [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC002	|	Codice relazione di parentela [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC003	|	Codice legame scheda convivenza [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC004	|	Codice motivo costituzione della famiglia [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC005	|	Codice legame specie convivenza [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC006	|	Codice motivo iscrizione ANPR [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC007	|	Comune/provincia di nascita [@] ([@]) inesistente o non valido alla data di nascita	| warning non bloccante | |
|	EC008	|	Impossibile verificare la validita' del comune di nascita per la presenza di piu' occorrenze	| warning non bloccante | |
|	EC009	|	Codice ISTAT del comune di nascita [@] incongruente con quello [@] presente sulla tabella di riferimento [Codice-Tabella]	| warning non bloccante | |
|	EC030	|	Stato estero di nascita [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning non bloccante | |
|	EC032	|	Codice consolato di residenza [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC036	|	Stato estero cittadinanza [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning non bloccante | |
|	EC042	|	Comune/provincia di matrimonio [@] inesistente 	| warning non bloccante | |
|	EC053	|	Stato estero di residenza [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning non bloccante | |
|	EC060	|	Campo codice motivo iscrizione AIRE [@]  inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC061	|	Campo codice Iniziativa movimenti anagrafici AIRE [@]  inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC062	|	Campo codice Individuazione Comune Iscrizione AIRE [@]  inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC063	|	Campo codice tipo soggiorno [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC064	|	Campo codice posizione nella professione [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning non bloccante | |
|	EC065	|	Campo codice condizione non professionale [@]  inesistente sulla tabella di riferimento [Codice-Tabella]	| warning non bloccante | |
|	EC066	|	Campo codice titolo di studio [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning non bloccante | |
|	EC069	|	Codice lingua [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC073	|	Codice specie Toponimo [@] inesistente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EC075	|	Comune/provincia di registrazione atto di nascita [@] inesistente o non valido alla data di registrazione	| warning non bloccante | |
|	EC078	|	Comune di rilascio carta identita' [@] inesistente o non valido alla data rilascio	| warning non bloccante | |
|	EC081	|	Comune/provincia di registrazione atto di matrimonio [@] inesistente	| warning non bloccante | |
|	EC087	|	Comune di rilascio permesso di soggiorno [@] inesistente o non valido alla data di rilascio	| warning non bloccante | |
|	EC096	|	Comune/provincia di registrazione atto di cessazione/annullamento matrimonio [@] inesistente	| warning non bloccante | |
|	EC164	|	Codice stato istruttoria non presente sulla tabella di riferimento [Codice-Tabella]	| warning non bloccante | |
|	EC165	|	Codice tipo fine unione non presente sulla tabella di riferimento [Codice-Tabella]	| warning da rimuovere prima del subentro | |
|	EF003	|	Scheda famiglia/convivenza duplicata in ANPR	| warning da rimuovere prima del subentro | |
|	EF004	|	Progressivo ordine gia' assegnato ad altro soggetto della scheda famiglia/convivenza	| warning non bloccante | |
|	EF008	|	Intestatario della scheda famiglia/convivenza assente	| warning da rimuovere prima del subentro | |
|	EF009	|	Intestatario della scheda famiglia/convivenza non univoco	| warning da rimuovere prima del subentro | |
|	EF010	|	Scheda famiglia senza alcun soggetto associato	| warning non bloccante | |
|	EHR41	|	I campi comune rilascio carta di identita' [@] e  codice consolato rilascio [@] devono essere valorizzati in alternativa	| warning non bloccante | |
|	EHR69	|	Anno dell'atto di nascita [@] non  valido	| warning da rimuovere prima del subentro | |
|	EHR70	|	Anno dell'atto di morte [@] non  valido	| warning da rimuovere prima del subentro | |
|	EHR73	|	Anno dell'atto di annullamento del matrimonio [@] non valido	| warning da rimuovere prima del subentro | |
|	EN001	|	Nome file [@] formalmente non corretto	| errore | |
|	EN002	|	La dimensione del file  [@] compresso supera il valore consentito [@]	| errore | |
|	EN003	|	Lo stato del subentro attuale [@] non consente l'invio del file 	| errore | |
|	EN007	|	E' gia' presente un file con lo stesso nome [@]	| errore | |
|	EN008	|	Il numero progressivo [@] indicato nel nome del file supera il totale previsto [@]	| errore | |
|	EN009	|	Il formato del file APR decompresso non e' XML	| errore | |
|	EN010	|	Il formato del file AIRE decompresso non e' TXT	| errore | |
|	EN011	|	Totale schede soggetto [@] dichiarato nel file [@] incongruente con quello calcolato [@]	| errore | |
|	EN012	|	Totale schede soggetto [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@]	| errore | |
|	EN017	|	Totale persone di sesso femminile [@] dichiarato nel file [@] incongruente con quello calcolato [@]	| errore | |
|	EN018	|	Totale persone di sesso femminile [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@]	| errore | |
|	EN019	|	Totale persone di sesso maschile [@] dichiarato nel file [@] incongruente con quello calcolato [@]	| errore | |
|	EN020	|	Totale persone di sesso maschile [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@]	| errore | |
|	EN021	|	Totale schede famiglia [@] dichiarato nel file [@] incongruente con quello calcolato [@]	| errore | |
|	EN022	|	Totale schede famiglia [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@]	| errore | |
|	EN023	|	Totale schede convivenza [@] dichiarato nel file [@] incongruente con quello calcolato [@]	| errore | |
|	EN024	|	Totale schede convivenza [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@]	| errore | |
|	EN031	|	I dati del gruppo "Dati Invio" devono essere obbligatoriamente impostati quando il totale invii >1	| errore | |
|	EN032	|	La data di invio del file [@] deve essere compresa tra la data di inizio e la data fine subentro pianificate	| errore | |
|	EN033	|	La data di inizio [@] deve essere <= della data fine [@]	| errore | |
|	EN034	|	Impossibile inviare altri file per un comune gia' subentrato | errore | |
|	EN035	|	File piano subentro errato o incompleto [in cosa]	| errore | |
|	EN036	|	File inviato non coerente con il Tipo file selezionato	| errore | |
|	EN037	|	Esiste gia' una precedente fornitura di file attualmente in elaborazione | errore | |
|	EN038	|	Il numero totale file da inviare [@] indicato nel nome del file supera il totale previsto [@]	| errore | |
|	EN039	|	Codice ISTAT del comune che invia il file [@] incongruente con il  codice ISTAT del comune indicato nel nome del file [@]	| errore | |
|	EN040	|	Esiste gia' una fornitura con progressivo [@] in stato OK	| errore | |
|	EN041	|	Piano di subentro gia' presente per il comune	| errore | |
|	EN063	|	Famiglia/convivenza del soggetto non presente nello stesso file di subentro	| warning non bloccante | |
|	EN064	|	Grado di parentela [@] - [@] non piu' valido	| warning non bloccante | |
|	EN242	|	Codice tipo tribunale non valido	| warning da rimuovere prima del subentro | |
|	EN306	|	La data del matrimonio e' obbligatoria	| warning da rimuovere prima del subentro | |
|	EN347	|	Codice istat utilizzato corrisponde a un codice di variazione	| warning non bloccante | |
|	ES007	|	Soggetto gia' presente in ANPR	| warning da rimuovere prima del subentro | |
|	ES008	|	Data nascita [@] successiva alla data di richiesta	| warning da rimuovere prima del subentro | |
|	ES009	|	Data  validita' cittadinanza [@] deve essere maggiore uguale della data di nascita [@] ma non a  a quella corrente [@]	| warning da rimuovere prima del subentro | |
|	ES010	|	Data matrimonio [@] deve essere successiva alla data di nascita [@] ma non a  a quella corrente	| warning da rimuovere prima del subentro | |
|	ES012	|	Data annullamento matrimonio [@] deve essere successiva alla data di nascita [@] ma non a  a quella corrente [@]	| warning da rimuovere prima del subentro | |
|	ES013	|	Data formazione atto di nascita [@] deve essere coincidente o successiva a quella di nascita [@] ma non a  a quella corrente [@]	| warning da rimuovere prima del subentro | |
|	ES027	|	La descrizione della localita' e' obbligatoria per la residenza estera	| warning non bloccante | |
|	ES028	|	Per la residenza estera deve essere presente almeno uno tra i seguenti campi: indirizzo, presso, contea-provincia, CAP	| warning non bloccante | |
|	ES048	|	Occorre impostare in alternativa  il comune o la localita' estera del matrimonio	| warning non bloccante | |
|	ES050	|	Occorre impostare in alternativa codice  comune ISTAT  o stato estero di nascita	| warning non bloccante | |
|	ES057	|	Specificare in alternativa che il soggetto e' senza cognome o senza nome | warning da rimuovere prima del subentro | |
|	ES061	|	Il cognome deve essere assente se il campo SenzaCognome e' impostato	| warning da rimuovere prima del subentro | |
|	ES062	|	Il nome deve essere assente se il campo SenzaNome e' impostato	| warning da rimuovere prima del subentro | |
|	ES063	|	La data nascita [@] deve avere solo l'anno se il campo senzaGiornoMese e' impostato a 1	| warning da rimuovere prima del subentro | |
|	ES066	|	La data nascita [@] deve avere solo il mese e l'anno se il campo senzaGiorno e' impostato a 1	| warning da rimuovere prima del subentro | |
|	ES067	|	Occorre impostare in alternativa il  comune o la localita' estera di decesso del coniuge	| warning non bloccante | |
|	ES078	|	La data di decorrenza iscrizione AIRE [@] deve essere maggiore uguale 01/07/1990 ma non a  a quella corrente	| warning da rimuovere prima del subentro | |
|	ES079	|	Anno espatrio [@] deve essere maggiore uguale anno nascita [@] e minore uguale anno corrente	| warning da rimuovere prima del subentro | |
|	ES092	|	Soggetto senza scheda famiglia/convivenza associata	| errore | |

	Legenda
		@
			placeholder sostituito con valore rilevato nel file di subentro

		Codice-Tabella
			placeholder sostituito con il riferimento alla tabella di codifica da utilizzare

		CF
			abbreviazione di Codice Fiscale

		AT
			abbreviazione di Anagrafe Tributaria

		DA
			abbreviazione di Dati Anagrafici

		MAE
			abbreviazione di Ministero degli Affari Esteri

		AIRE
			abbrezione di Anagrafe Italiani Residenti all'Estero

> ritorna [*README*](README.md)