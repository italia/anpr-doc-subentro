# Tabella anomalie ANPR
ritorna al [*README*](README.md)

|codice anomalia | messaggio di errore | procedura suggerita|
| ------------- | ------------- | ------------- |
|EA001 | Codice fiscale formalmente non corretto | [Procedura_001](procedure/001.md) |
|EA002 | Soggetto presente in AT con  DA uguali a quelli del comune ma CF del comune assente | |
|EA003 | Soggetto presente in AT con  DA uguali a quelli del comune ma CF diverso | |
|EA029 | Codice fiscale calcolato dai  DA del comune non presente in AT | |
|EA030 | CF di un soggetto residente  in piu' comuni | |
|EA031 | CF di un soggetto residente  sia in Italia che all'estero (AIRE) | |
|EA036 | Soggetto registrato piu' volte sia con il CF base che con quello che risolve l'omocodia   | |
|EA038 | Soggetto con data di nascita non coincidente  con quella presente nel CF | |
|EA040 | Soggetto registrato piu' volte  sia con il CF collegato che con l'ultimo | |
|EA042 | Soggetto con sesso non coincidente  con quello presente nel CF | |
|EA047 | Soggetto presente  nell'archivio AIRE e nel MAE dei cittadini non residenti (IRREPERIBILI, RIMPATRIATI, DECEDUTI,  TRASFERITI) | |
|EA048 | Codice fiscale formalmente errato | |
|EC001 | Codice stato civile [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC002 | Codice relazione di parentela [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC003 | Codice legame scheda convivenza [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC004 | Codice motivo costituzione della famiglia [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC005 | Codice legame specie convivenza [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC006 | Codice motivo iscrizione ANPR [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC007 | Comune/provincia di nascita [@] ([@]) inesistente o non valido alla data di nascita | |
|EC008 | Impossibile verificare la validita' del comune di nascita per la presenza di piu' occorrenze | |
|EC009 | Codice ISTAT del comune di nascita [@] incongruente con quello [@] presente sulla tabella di riferimento [Codice-Tabella] | |
|EC030 | Stato estero di nascita [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC032 | Codice consolato di residenza [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC036 | Stato estero cittadinanza [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC042 | Comune/provincia di matrimonio [@] inesistente  | |
|EC053 | Stato estero di residenza [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC060 | Campo codice motivo iscrizione AIRE [@]  inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC061 | Campo codice Iniziativa movimenti anagrafici AIRE [@]  inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC062 | Campo codice Individuazione Comune Iscrizione AIRE [@]  inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC063 | Campo codice tipo soggiorno [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC064 | Campo codice posizione nella professione [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC065 | Campo codice condizione non professionale [@]  inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC066 | Campo codice titolo di studio [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC069 | Codice lingua [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC073 | Codice specie Toponimo [@] inesistente sulla tabella di riferimento [Codice-Tabella] | |
|EC075 | Comune/provincia di registrazione atto di nascita [@] inesistente o non valido alla data di registrazione | |
|EC078 | Comune di rilascio carta identita' [@] inesistente o non valido alla data rilascio | |
|EC081 | Comune/provincia di registrazione atto di matrimonio [@] inesistente | |
|EC087 | Comune di rilascio permesso di soggiorno [@] inesistente o non valido alla data di rilascio | |
|EC096 | Comune/provincia di registrazione atto di cessazione/annullamento matrimonio [@] inesistente | |
|EC164 | Codice stato istruttoria non presente sulla tabella di riferimento [Codice-Tabella] | |
|EC165 | Codice tipo fine unione non presente sulla tabella di riferimento [Codice-Tabella] | |
|EF003 | Scheda famiglia/convivenza duplicata in ANPR | |
|EF004 | Progressivo ordine gia' assegnato ad altro soggetto della scheda famiglia/convivenza | |
|EF008 | Intestatario della scheda famiglia/convivenza assente | |
|EF009 | Intestatario della scheda famiglia/convivenza non univoco | |
|EF010 | Scheda famiglia senza alcun soggetto associato | |
|EHR41 | I campi comune rilascio carta di identita' [@] e  codice consolato rilascio [@] devono essere valorizzati in alternativa | |
|EHR69 | Anno dell'atto di nascita [@] non  valido | |
|EHR70 | Anno dell'atto di morte [@] non  valido | |
|EHR73 | Anno dell'atto di annullamento del matrimonio [@] non valido | |
|EN001 | Nome file [@] formalmente non corretto | |
|EN002 | La dimensione del file  [@] compresso supera il valore consentito [@] | |
|EN003 | Lo stato del subentro attuale [@] non consente l'invio del file  | |
|EN007 | E' gia' presente un file con lo stesso nome [@] | |
|EN008 | Il numero progressivo [@] indicato nel nome del file supera il totale previsto [@] | |
|EN009 | Il formato del file APR decompresso non e' XML | |
|EN010 | Il formato del file AIRE decompresso non e' TXT | |
|EN011 | Totale schede soggetto [@] dichiarato nel file [@] incongruente con quello calcolato [@] | |
|EN012 | Totale schede soggetto [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@] | |
|EN017 | Totale persone di sesso femminile [@] dichiarato nel file [@] incongruente con quello calcolato [@] | |
|EN018 | Totale persone di sesso femminile [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@] | |
|EN019 | Totale persone di sesso maschile [@] dichiarato nel file [@] incongruente con quello calcolato [@] | |
|EN020 | Totale persone di sesso maschile [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@] | |
|EN021 | Totale schede famiglia [@] dichiarato nel file [@] incongruente con quello calcolato [@] | |
|EN022 | Totale schede famiglia [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@] | |
|EN023 | Totale schede convivenza [@] dichiarato nel file [@] incongruente con quello calcolato [@] | |
|EN024 | Totale schede convivenza [@] dichiarato per l'intera fornitura [@] incongruente con quello calcolato [@] | |
|EN031 | I dati del gruppo "Dati Invio" devono essere obbligatoriamente impostati quando il totale invii >1 | |
|EN032 | La data di invio del file [@] deve essere compresa tra la data di inizio e la data fine subentro pianificate | |
|EN033 | La data di inizio [@] deve essere <= della data fine [@] | |
|EN034 | Impossibile inviare altri file per un comune gia' subentrato | |
|EN035 | File piano subentro errato o incompleto [in cosa] | |
|EN036 | File inviato non coerente con il Tipo file selezionato | |
|EN037 | Esiste gia' una precedente fornitura di file attualmente in elaborazione | |
|EN038 | Il numero totale file da inviare [@] indicato nel nome del file supera il totale previsto [@] | |
|EN039 | Codice ISTAT del comune che invia il file [@] incongruente con il  codice ISTAT del comune indicato nel nome del file [@] | |
|EN040 | Esiste gia' una fornitura con progressivo [@] in stato OK | |
|EN041 | Piano di subentro gia' presente per il comune | |
|EN063 | Famiglia/convivenza del soggetto non presente nello stesso file di subentro | |
|EN064 | Grado di parentela [@] - [@] non piu' valido | |
|EN242 | Codice tipo tribunale non valido | |
|EN306 | La data del matrimonio e' obbligatoria | |
|EN347 | Codice istat utilizzato corrisponde a un codice di variazione | |
|ES007 | Soggetto gia' presente in ANPR | |
|ES008 | Data nascita [@] successiva alla data di richiesta | |
|ES009 | Data  validita' cittadinanza [@] deve essere maggiore uguale della data di nascita [@] ma non a  a quella corrente [@] | |
|ES010 | Data matrimonio [@] deve essere successiva alla data di nascita [@] ma non a  a quella corrente | |
|ES012 | Data annullamento matrimonio [@] deve essere successiva alla data di nascita [@] ma non a  a quella corrente [@] | |
|ES013 | Data formazione atto di nascita [@] deve essere coincidente o successiva a quella di nascita [@] ma non a  a quella corrente [@] | |
|ES027 | La descrizione della localita' e' obbligatoria per la residenza estera | |
|ES028 | Per la residenza estera deve essere presente almeno uno tra i seguenti campi: indirizzo, presso, contea-provincia, CAP | |
|ES048 | Occorre impostare in alternativa  il comune o la localita' estera del matrimonio | |
|ES050 | Occorre impostare in alternativa codice  comune ISTAT  o stato estero di nascita | |
|ES057 | Specificare in alternativa che il soggetto e' senza cognome o senza nome | |
|ES061 | Il cognome deve essere assente se il campo SenzaCognome e' impostato | |
|ES062 | Il nome deve essere assente se il campo SenzaNome e' impostato | |
|ES063 | La data nascita [@] deve avere solo l'anno se il campo senzaGiornoMese e' impostato a 1 | |
|ES066 | La data nascita [@] deve avere solo il mese e l'anno se il campo senzaGiorno e' impostato a 1 | |
|ES067 | Occorre impostare in alternativa il  comune o la localita' estera di decesso del coniuge | |
|ES078 | La data di decorrenza iscrizione AIRE [@] deve essere maggiore uguale 01/07/1990 ma non a  a quella corrente | |
|ES079 | Anno espatrio [@] deve essere maggiore uguale anno nascita [@] e minore uguale anno corrente | |
|ES092 | Soggetto senza scheda famiglia/convivenza associata | |


ritorna al [*README*](README.md)