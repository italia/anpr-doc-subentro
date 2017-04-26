	QUESTO DOCUMENTO É UNA BOZZA DI LAVORO

# Procedura 006 - Codice inesistente su tabella di riferimento

> ritorna [*README*](../README.md) o [*Tabella anomalie ANPR*](../TAB01_ANOMALIE_ANPR.md)

In quanto segue si riporta la procedura suggerita ai Comuni per la gestione delle anomalie: 

- EC001 - Codice stato civile inesistente sulla [tabella di riferimento 01](https://anpr.readthedocs.io/en/latest/tab_stato_civile.html);
- EC002 - Codice relazione di parentela inesistente sulla [tabella di riferimento 05](https://anpr.readthedocs.io/en/latest/tab_relazione_di_parentela___famiglia.html);
- EC003 - Codice legame scheda convivenza inesistente sulla [tabella di riferimento 06](https://anpr.readthedocs.io/en/latest/tab_legame____convivenza.html);
- EC004 - Codice motivo costituzione della famiglia inesistente sulla [tabella di riferimento 26](https://anpr.readthedocs.io/en/latest/tab_motivo_costituzione_della_famiglia.html);
- EC005 - Codice legame specie convivenza inesistente sulla [tabella di riferimento 27](https://anpr.readthedocs.io/en/latest/tab_specie_della_convivenza.html);
- EC006 - Codice motivo iscrizione ANPR inesistente sulla [tabella di riferimento 07](https://anpr.readthedocs.io/en/latest/tab_motivi_di_iscrizione_in_anagrafe.html);
- EC007 - Comune/provincia di nascita inesistente o non valido alla data di nascita [**NON PRESENTE SU [https://anpr.readthedocs.io/en/latest/](https://anpr.readthedocs.io/en/latest/)**]	
- EC008 - Impossibile verificare la validita' del comune di nascita per la presenza di piu' occorrenze [**NON PRESENTE SU [https://anpr.readthedocs.io/en/latest/](https://anpr.readthedocs.io/en/latest/)**];
- EC009 - Codice ISTAT del comune di nascita incongruente con quello presente sulla tabella di riferimento [**NON PRESENTE SU [https://anpr.readthedocs.io/en/latest/](https://anpr.readthedocs.io/en/latest/)**];
- EC030 - Stato estero di nascita inesistente sulla [tabella di riferimento 02](https://anpr.readthedocs.io/en/latest/tab_stati_esteri.html);
- EC032 - Codice consolato di residenza inesistente sulla tabella di riferimento [**NON PRESENTE SU [https://anpr.readthedocs.io/en/latest/](https://anpr.readthedocs.io/en/latest/)**]);
- EC036 -  Stato estero cittadinanza inesistente sulla [tabella di riferimento 02](https://anpr.readthedocs.io/en/latest/tab_stati_esteri.html);
- EC042 - Comune/provincia di matrimonio inesistente [**NON PRESENTE SU [https://anpr.readthedocs.io/en/latest/](https://anpr.readthedocs.io/en/latest/)**]
- EC053 - Stato estero di residenza inesistente sulla [tabella di riferimento 02](https://anpr.readthedocs.io/en/latest/tab_stati_esteri.html);
- EC060 - Campo codice motivo iscrizione AIRE inesistente sulla [tabella di riferimento 19](https://anpr.readthedocs.io/en/latest/tab_motivi_iscrizione_aire.html);
- EC061 - Campo codice Iniziativa movimenti anagrafici AIRE inesistente sulla [tabella di riferimento 20](https://anpr.readthedocs.io/en/latest/tab_iniziativa_iscrizione_aire.html);
- **...**
- **ELENCO DA COMPLETARE**


## Precondizione
Per dare seguito alla presente procedura è necessario che l'ufficiale d'anagrafe disponga della risoluzione dei valori ammessi nell'APR/AIRE locale con i codice previsti nelle tabelle di riferimento adottate da ANPR. 


## Diagramma della procedura
La seguente figura sintetizza la procedura per la gestione delle anomalie.

![Swimlane diagram procedura 006](image/IMAGE_006.png)

## Descrizione azione
In quanto segue si riporta una descrizione delle azioni previsti per la presente procedura.

### AZIONE 006_001 - VERIFICA
L'ufficiale d'anagrafe verifica i dati anagrafici associati al soggetto interessato dall'errore sul sistema gestionale del Comune (APR o AIRE locale) con l'obiettivo di constatare che i dati inoltrati al sistema ANPR coincidono con quelli registrati.

### AZIONE 006_002 – NUOVO INOLTRO
Poichè i dati inoltrati al sistema ANPR non coincidono con quelli presenti nel sistema gestionale del Comune (probabilemente per problemi nella procedura di estrazione e predisposizione dei file di subentro utilizzata) è necessario provvedere nuovamente all'estrazione dei dati e alla predisposizione dei file di subentro al fine di provvedere ad eseguire l'inoltro al sistema ANPR.

### AZIONE 006_003 – IDENTIFICAZIONE CODICE
L'ufficiale di anagrafe identifica la corretta codifica del valore presente nell'APR/AIRE con il codice previsto dalla tabella di riferimento adottata da ANPR.

### AZIONE 006_004 - AGGIORNAMENTO E NUOVO INOLTRO
L'ufficiale di anagrafe, sulla base dell'identificazione effettuata, provvede ad aggironare la *schede soggetto* e/o *schede famiglia*  sul sistema gestionale del Comune o ad assicurare la corretta transcodifica nella procedura di estrazione e predisposizione dei file di subentro, per dare seguito ad una nuova estrazione dei dati e alla predisposizione dei file di subentro al fine di provvedere ad eseguire l'inoltro al sistema ANPR.


> ritorna [*README*](../README.md) o [*Tabella anomalie ANPR*](../TAB01_ANOMALIE_ANPR.md)
