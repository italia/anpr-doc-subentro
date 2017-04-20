# Procedura 004

> ritorna [*README*](../README.md) o [*Tabella anomalie ANPR*](../TAB01_ANOMALIE_ANPR.md)

In quanto segue si riporta la procedura suggerita ai Comuni per la gestione delle anomalie: 

- EA038 - Soggetto con data di nascita non coincidente con quella presente nel *codice fiscale*;
- EA042 - Soggetto con sesso non coincidente con quella presente nel *codice fiscale*; 


## Precondizione
Per dare seguito alla presente procedura è necessario che l'ufficiale d'anagrafe disponga:

- accesso al sistema gestionale del Comune (APR o AIRE locale) con diritti di lettura e aggiornamento delle schede soggetto;
- accesso al sistema *SIATEL v2.0 - PuntoFisco* reso disponibile dall'Agenzia delle Entrate. 

## Diagramma della procedura
La seguente figura sintetizza la procedura per la gestione delle anomalie.

![Swimlane diagram procedura 004](image/IMAGE_004.png)

## Descrizione azione
In quanto segue si riporta una descrizione delle azioni previsti per la presente procedura.

### AZIONE 004_001
L'ufficiale di anagrafe verifica, tramite il sistema *SIATEL v2.0 - PuntoFisco* reso disponibile dall'Agenzia delle entrate, l'attribuzione dello stesso da parte dell'Agenzia delle entrate.

### AZIONE 004_002
L'ufficiale di anagrafe, a valle del riscontro che il *codice fiscale* conosciuto dall'Agenzia delle entrate non presente l'anomalia segnalata, provvede ad aggiornare il *codice fiscale* sul sistema gestionale del Comune per dare seguito ad una nuova estrazione dei dati e alla predisposizione dei file di subentro al fine di provvedere ad eseguire l'inoltro al sistema ANPR.

### AZIONE 004_003
L'ufficiale di anagrafe convoca il cittadino per verificare se lo stesso è in possesso di un *codice fiscale* correttamente generato dall'Agenzia delle entrate.

### AZIONE 004_004
L'ufficiale di anagrafe, a valle del positivo riscontro con il cittadino, provvede ad aggiornare il *codice fiscale* sul sistema gestionale del Comune per dare seguito ad una nuova estrazione dei dati e alla predisposizione dei file di subentro al fine di provvedere ad eseguire l'inoltro al sistema ANPR.


### AZIONE 004_005
L'ufficiale di anagrafe provvede, attraverso le funzionalità rese disponibili dal sistema *SIATEL v2.0 - PuntoFisco* reso disponibile dall'Agenzia delle entrate, alla variazione del *codice fiscale* del cittadino.
**L'ufficiale di anagrafe comunica al cittadino il nuovo codice fiscale** 

### AZIONE 004_006
L'ufficiale di anagrafe aggiorna il *codice fiscale* sul sistema gestionale del Comune per dare seguito ad una nuova estrazione dei dati e alla predisposizione dei file di subentro al fine di provvedere ad eseguire l'inoltro al sistema ANPR.

## Riferimenti di interesse
Nello specifico della presente procedure risultano di interesse:

- [regole di codifica](http://www.agenziaentrate.gov.it/wps/content/Nsilib/Nsi/Home/CosaDeviFare/Richiedere/Codice+fiscale+e+tessera+sanitaria/Richiesta+TS_CF/SchedaI/Informazioni+codificazione+pf/) codice fiscale;


> ritorna [*README*](../README.md) o [*Tabella anomalie ANPR*](../TAB01_ANOMALIE_ANPR.md)
