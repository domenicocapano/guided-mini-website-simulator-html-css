# Pubblicazione su Netlify BOZZA
Progetto: guided-mini-website-simulator-html-css
## Destinatari

Questo documento è rivolto a docenti, sviluppatori o utilizzatori del progetto 
che desiderano pubblicare il simulatore online tramite Netlify.

Non è destinato agli studenti.

---

## Metodo consigliato: GitHub + Netlify

1. Creare un repository GitHub, anche privato.
2. Caricare nel repository tutti i file del pacchetto.
3. Accedere a Netlify.
4. Selezionare “Add new site” → “Import an existing project”.
5. Collegare GitHub.
6. Selezionare il repository.
7. Lasciare vuoto il comando di build.
8. Impostare come directory di pubblicazione la radice del repository.
9. Pubblicare.

Il file principale deve chiamarsi `index.html` e deve trovarsi nella radice del repository.

---

## Verifica dopo la pubblicazione

Controllare che:

- il simulatore si apra correttamente;
- il menu degli Stati funzioni;
- il pulsante dell’esempio completo apra `esempio_giappone_livello10/index.html`;
- il download delle pagine generate funzioni;
- non compaiano errori 404 relativi alla favicon.