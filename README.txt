SAQQARA & DAHSHUR — AUDIOGUIDA v2

Migliorie:
- “Visitato” è un vero toggle: può essere segnato e annullato in qualsiasi momento.
- Contatore dei punti visitati.
- “Azzera visitati” per ricominciare da zero.
- Audioguida divisa in 3 capitoli per punto: Contesto / Da osservare / Foto.
- Selezione manuale del capitolo e lettura con Speech Synthesis.
- GPS con rilevamento di ingresso nel raggio del punto.
- Avviso visivo quando entri nel raggio di un nuovo punto; non parte audio automaticamente, scelta più affidabile su iPhone.
- Vibrazione breve quando supportata dal browser.
- Marker visitati evidenziati e marker vicino alla posizione evidenziato.
- Stato Visitato salvato in localStorage, quindi resta anche chiudendo la pagina.
- PWA/service worker.

INSTALLAZIONE GITHUB PAGES
1. Sostituisci i file del repository con quelli di questa cartella.
2. Mantieni index.html, manifest.webmanifest e sw.js nella root pubblicata.
3. Dopo il deploy apri la pagina in Safari su iPhone.
4. Concedi la posizione quando richiesto.
5. Aggiungi alla schermata Home per usarla come web app.

NOTA OFFLINE
L'app e lo stato Visitato vengono messi in cache. La mappa usa le tile OpenStreetMap remote: per una vera mappa offline completa servirebbe incorporare un dataset di mappe locale (ad esempio vector tiles/PMTiles) invece delle tile OSM remote. Non ho fatto una falsa promessa di “offline completo”.

AUDIO
Per massima compatibilità iOS la versione usa la voce del dispositivo tramite Speech Synthesis. L'audio non parte automaticamente all'arrivo GPS: Safari può limitare l'autoplay; l'avviso “Apri punto” richiede un tap e poi “Ascolta”.
