# Saqqara & Dahshur — Audioguida GPS

Webapp/PWA in italiano pensata per iPhone.

## Funzioni
- mappa OpenStreetMap
- posizione GPS del telefono
- punti di interesse di Saqqara e Dahshur
- selezione manuale dei monumenti
- evidenziazione del punto più vicino entro un raggio GPS
- audioguida tramite Speech Synthesis del browser, senza file audio esterni
- stato "Visitato" salvato localmente
- PWA installabile sulla schermata Home

## Uso su iPhone
Il GPS del browser richiede HTTPS. Non aprire semplicemente index.html da File.
Carica questa cartella su un hosting statico HTTPS (GitHub Pages, Netlify, Cloudflare Pages, ecc.).
Apri l'URL in Safari -> Condividi -> Aggiungi alla schermata Home.

La mappa usa tile OpenStreetMap e quindi richiede connessione per la cartografia. I testi e la logica dell'app sono locali e la PWA può essere caricata offline; per una vera mappa offline servirebbe un pacchetto cartografico dedicato.

## Nota
Le coordinate dei monumenti sono state impostate usando fonti cartografiche pubbliche e, dove disponibile, dati del Ministero egiziano. Il GPS è un ausilio per selezionare il punto più vicino, non una guida di sicurezza o di navigazione all'interno dell'area archeologica.
