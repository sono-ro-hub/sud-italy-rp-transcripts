# Sud Italy RP — Ticket Transcripts

## GitHub Pages

1. Crea un repository pubblico su GitHub.
2. Carica tutto il contenuto di questa cartella.
3. Vai in **Settings → Pages**.
4. Seleziona **Deploy from a branch**.
5. Seleziona `main` e `/ (root)`.
6. Salva e aspetta il deploy.

La home sarà:

`https://TUO-USERNAME.github.io/NOME-REPOSITORY/`

## Struttura

- `index.html` — pagina principale.
- `transcripts/` — pagine HTML dei transcript.
- `assets/` — eventuali immagini/CSS futuri.

## Collegamento al bot

Il bot dovrà creare un file:

`transcripts/ID_TICKET.html`

e pubblicarlo nel repository GitHub. Il link finale sarà:

`https://TUO-USERNAME.github.io/NOME-REPOSITORY/transcripts/ID_TICKET.html`

GitHub Pages è statico: il bot deve quindi pubblicare/aggiornare i file nel repository tramite GitHub API o tramite una procedura CI/CD.
