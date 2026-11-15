# Vita e Materia

Notizie di biologia, comportamento animale, piante, fisica e spazio spiegate in modo semplice, con numeri, metodi e fonti.

Sito: https://zinkkko.github.io/vita-e-materia/

- `index.html`: la pagina (design e codice). Legge i dati all'avvio.
- `dati/archivio.json`: notizie (`voci`), schede del taccuino (`taccuino`), ordini di grandezza (`scala`), data dell'ultimo aggiornamento (`aggiornato`).
- `dati/foto.json`: per ogni id di notizia (e `tacc-0` ... `tacc-9`), il file della foto e i crediti (autore, licenza, pagina su Wikimedia Commons, `ill` = foto illustrativa).
- `foto/`: le foto, da Wikimedia Commons con licenza libera.

Una routine di Claude aggiunge ogni mattina le notizie nuove con la loro foto e fa il commit su `main`; GitHub Pages pubblica il sito da `main`.
