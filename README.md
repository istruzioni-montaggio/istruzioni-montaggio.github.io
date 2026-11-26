# Video di montaggio

Pagine pubblicate con GitHub Pages: **https://istruzioni-montaggio.github.io/**

| Prodotto | Pagina (indirizzo del QR code nel libretto) |
|---|---|
| Tavolo Levante (anche Libeccio, Maestrale, Panca Gradisca, Panca Volpina) | https://istruzioni-montaggio.github.io/levante/ |

## Struttura
- `index.html` – elenco dei video
- `levante/index.html` – pagina del video con l’elenco dei passi cliccabile
- `levante/libretto-tavolo-levante.pdf` – il libretto di istruzioni (lo stesso stampato nella confezione)
- `video/` – video 720p (riproduzione), 1080p (download) e immagine di anteprima
- `assets/` – stile, icona e font Barlow (licenza SIL OFL, vedi `assets/fonts/OFL-LICENSE.txt`)

## Aggiornare un video o un libretto senza cambiare il QR code
Sostituire i file in `video/` (o il PDF nella cartella del prodotto) mantenendo gli stessi nomi (e, se cambiano i tempi dei passi, aggiornare i `data-t` nella pagina): l’indirizzo stampato nel libretto resta valido.

## Diritti
La licenza MIT del repository copre solo il codice delle pagine (HTML/CSS/JS). Video, libretti PDF, immagini, nomi dei prodotti e marchi restano di proprietà del produttore: tutti i diritti riservati.
