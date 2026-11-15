# Vita e Materia

Notizie di biologia, comportamento animale, piante, geologia, fisica e spazio spiegate in modo semplice, con numeri, metodi e fonti.

Sito: https://zinkkko.github.io/vita-e-materia/

- `index.html`: la pagina (design e codice). Legge i dati all'avvio.
- `dati/archivio.json`: notizie (`voci`), schede del taccuino (`taccuino`), ordini di grandezza (`scala`), data dell'ultimo aggiornamento (`aggiornato`).
- `dati/foto.json`: per ogni id di notizia (e `tacc-0` ... `tacc-9`), il file della foto e i crediti (autore, licenza, pagina su Wikimedia Commons, `ill` = foto illustrativa).
- `foto/`: le foto, da Wikimedia Commons con licenza libera.
- `manifest.webmanifest`, `icone/`: nome e icona per aggiungere il sito alla schermata Home del telefono.

Ogni notizia ha `data` (data dello studio) e `aggiunta` (giorno in cui e entrata nel sito): la pagina mette in cima le ultime aggiunte e segna "da riscoprire" quelle il cui studio ha piu di 30 giorni.

Una routine di Claude aggiunge ogni mattina almeno due notizie con la loro foto (se mancano le novita, studi meno recenti non ancora presenti) e fa il commit su `main`; GitHub Pages pubblica il sito da `main`.
