---
titolo: "Budget Giornaliero — App web per la gestione delle spese quotidiane"
anno: 2026
tipo: progetto
stato: completo
tags: [budget-personale, spese-giornaliere, webapp, finanza-personale, javascript]
output: index.html
disciplina: altro
contesto: personale
lingua: it
---

Applicazione web a singolo file (HTML/CSS/JS) per tenere traccia delle spese giornaliere rispetto a un budget mensile prefissato. L'app calcola automaticamente la quota spendibile ogni giorno, tiene uno storico delle spese, prevede la data di esaurimento del budget e permette di esportare il riepilogo del periodo.

## Funzionalità principali

- Definizione di un periodo contabile con data di inizio e budget totale
- Calcolo automatico della quota giornaliera redistribuita sul saldo residuo
- Registrazione spese con ora, modifica e cancellazione
- Alert previsione esaurimento budget (verde / giallo / rosso)
- Storico giornaliero con delta rispetto alla quota
- Esportazione del periodo come file `.txt`
- Dati persistiti in `localStorage` del browser

## Struttura

```
060_Budget_giornaliero/
├── README.md       ← questo file
└── index.html      ← app completa (output finale)
```

---

⚠️ **NOTE DI RIORGANIZZAZIONE**

La cartella contiene un solo file funzionale (`index.html`) che è al tempo stesso sorgente e output. Per allinearla alla struttura standard suggerita, si potrebbe considerare:

- Creare una cartella `output/` e copiare lì la versione "rilasciata" dell'app (es. `output/budget-giornaliero-v1.html`)
- Usare `assets/` per eventuali screenshot o icone future
- Usare `_archivio/` per versioni precedenti dell'app

Non è necessario se il progetto rimane un singolo file auto-contenuto.
