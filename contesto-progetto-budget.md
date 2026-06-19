# Progetto: App Gestione Budget Mensile

## Cos'è
Web app personale per monitorare le spese giornaliere, basata su un budget fisso mensile che va da una data di inizio scelta dall'utente fino al 23 del mese.

## Stack tecnico
- File HTML singolo, autonomo (no build, no installazione)
- Vanilla JavaScript, niente framework
- Persistenza dati con `localStorage`
- Nessuna dipendenza esterna — deve funzionare offline

## Funzionalità già presenti
- Impostazione budget totale e data di inizio periodo
- Calcolo automatico della quota giornaliera disponibile
- Registrazione spese giornaliere con orario
- Modifica ed eliminazione di una spesa già inserita (via modal)
- Campo "Puoi spendere oggi" = quota del giorno − speso oggi (verde se positivo, rosso se negativo)
- Esportazione dei dati del periodo in `.txt` prima del reset
- Alert di previsione esaurimento budget: media di spesa giornaliera, data prevista di esaurimento, nuovo target giornaliero corretto (colori verde/giallo/rosso/critico)
- Storico giornaliero con scostamento rispetto alla quota

## Come preferisco lavorare
- Conferma sempre di aver capito la richiesta prima di implementare
- Modifiche puntuali e mirate, non redesign generali
- Output: singolo file `.html` aggiornato, pronto da scaricare
- Conversazioni in italiano

## Per iniziare
All'avvio del progetto allego l'ultimo `index.html` così si riparte da lì.
