# Registro Sollevamento – pagina di prevendita

Sito statico (HTML + CSS, nessuna build) per raccogliere le prenotazioni dei Soci fondatori.

- `index.html` – pagina principale con il modulo di prenotazione
- `grazie.html` – pagina mostrata dopo l'invio
- `privacy.html` – informativa privacy (versione semplificata)
- `style.css` – stile condiviso

## Pubblicazione su Netlify (gratis)

1. Su netlify.com: *Add new site → Import an existing project → GitHub* e scegli questo repository.
2. Nessun comando di build; cartella da pubblicare: `.` (già impostata in `netlify.toml`).
3. Il modulo viene riconosciuto in automatico (`data-netlify="true"`). Le prenotazioni si vedono in *Forms*; in *Forms → Notifications* attiva l'avviso via email.

Ogni modifica caricata sul ramo `main` viene pubblicata da sola.
