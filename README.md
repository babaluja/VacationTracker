# Gestione Ferie Aziendali

Un'applicazione mobile per la gestione delle ore di ferie aziendali, con interfaccia minimale e design corporate-styled.

## Funzionalità

- Gestione dipendenti (aggiunta, modifica, eliminazione)
- Tracciamento ore di ferie disponibili e utilizzate
- Statistiche con visualizzazione grafica
- Supporto per diversi tipi di contratto e ruoli lavorativi
- Tema chiaro e scuro

## Tecnologie utilizzate

- Frontend: React, TailwindCSS, shadcn/ui
- Backend: Node.js, Express
- Database: PostgreSQL
- ORM: Drizzle

## Installazione

```bash
# Clona il repository
git clone https://github.com/tuousername/gestione-ferie-app.git
cd gestione-ferie-app

# Installa le dipendenze
npm install

# Avvia l'applicazione in modalità sviluppo
npm run dev
```

## Requisiti di sistema

- Node.js 18+
- PostgreSQL

## Struttura del progetto

- `/client`: Interfaccia utente React
- `/server`: API backend Express
- `/shared`: Schemi e tipi condivisi tra client e server

## Note di rilascio

### Versione 1.0.0
- Implementazione iniziale dell'applicazione
- Supporto per la gestione completa dei dipendenti
- Dashboard con statistiche
- Tema chiaro e scuro