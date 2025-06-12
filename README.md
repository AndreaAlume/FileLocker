# FileLocker

## Descrizione

FileLocker offre un livello di difesa essenziale per le tue risorse digitali. Questo software intuitivo ti consente di mettere in sicurezza i tuoi file, bloccandoli dietro una serie di procedure di sicurezza proprietarie. È specificamente progettato per prevenire infezioni da malware, la propagazione di worm e altre intrusioni malevole, assicurando l'integrità e la riservatezza dei tuoi dati più preziosi.

## Feautures da sviluppare

### Sicurezza e protezione

1. **Crittografia file:** questa funzionalità permetterà di criptare i file con AES, tenendo in considerazione dell'elevato consumo di risorse per file di medie-grandi dimensioni verrà valutato se integrare AES a 128, 192 o 256 bit considerando di chiedere all'utente quale sia **il livello di sicurezza** che il file necessita di avere.

2. **Protezione file:** per la protezione dei file si tengano in considerazione tre possibilità da implementare:

    - **Accesso con PIN:** un semplice pin di 8 cifre
    - **Accesso con password:** una password che rispetti gli standard minimi di sicurezza (lunghezza > 8 caratteri - caratteri speciali - numeri e maiuscole)
    - **Accesso con dati biometrici:** se supportato l'accesso dei file sarà effettuato con dati biometrici come impronta digitale o riconoscimento facciale.

3. **Timeout automatico:** bloccare i file dopo un determinato periodo di inattività.

4. **Antimanomissione:** avvisa con una notifica in caso qualcuno tenta di aprire o modificare un file.

### Gestione file

1. **Organizzazione file per cartelle:** permetterà all'utente di orginizzare internamente le cartelle per categoria senza però modificare i percorsi effettivi dei file permettendo di selezionare il grado di sicurezza che si vuole ottenere.

> Ad esempio ci potrebbe essere una collezione chiamata **Dati sensibili** nella quale potrebbero esserci foto della carta d'identità o altro; e a questi file verrà applicato il sistema di sicurezza massimo.

2. **Cronologia accessi:** verranno registrati gli accessi e i tentativi di sblocco la data e l'orario di quest'ultimi.

3. **Accesso temporaneo programmato:** permetterà di scegliere il tempo massimo di accesso ad un file a uno o più utenti.

4. **Backup (m/a):** permetterà all'utente di effeturare dei backup (crittografati) periodicamente o aciclicamente.

5. **Distruzione irreversibile:** in caso di attacco esplicito i file verranno immediatamente cancellati e distrutti in maniera conclusiva.

### Multiutente e collaborazione

1. **Permessi utenti:** dare l'accesso a determinati file e solo a certi utenti

2. **Modalità visualizzazione:** dare la possibilità a certi utenti di visualizzare soltanto il contenuto dei file.

### Modalità avanzate

1. **Modalità "Panic":** Nasconde o cripta all'itstante tutti i file se viene rilevato un intruso o se una minaccia tenta di causare danni.

2. **File esca:** verranno generati dei file clone che fungeranno da "esca" nel caso in cui una minaccia tenterà di manometterli.

3. **Notifiche intelligenti:**

4. **Sistema di tagging:**

---

## Tecnologie utlizzate

