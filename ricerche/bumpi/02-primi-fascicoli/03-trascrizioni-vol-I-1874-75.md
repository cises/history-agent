# Trascrizioni dal vol. I (1874–75) — tentativo di acquisizione dal Drive dell'utente

**Data del tentativo**: 6 agosto 2026.
**Esito**: NEGATIVO — nessuna trascrizione ottenuta. Questo file documenta il tentativo, le cause tecniche del fallimento e le vie d'uscita, per non ripetere a vuoto la procedura.

**AVVERTENZA METODOLOGICA**: questo file non contiene alcuna trascrizione testuale dal volume. Tutto quanto segue è documentazione del tentativo di accesso, non contenuto della fonte.

## 1. File bersaglio (verificati, esistenti nel Drive)

| File | ID Drive | Dimensione | Note |
|---|---|---|---|
| `BUMPI_1874-1875_I.pdf` | `135jmLblgEn-qWJWOd1KGGSSk8HNZ-QFW` | 76.491.727 byte (~76 MB) | PDF, proprietario florindo.palladino@unimol.it, cartella `1F5B8iZ05ANL1rWRpS5--lZ8aKnDq4jCV` |
| `BUMPI_1876_II.pdf` (ripiego) | `1-2cGzIZSjbOgti1MEoYuZssDeddB4qSU` | 67.048.736 byte (~67 MB) | idem |

I metadati confermano l'inventario in `04-inventario-drive-utente.md`: i file esistono e sono raggiungibili a livello di metadati.

## 2. Tentativi effettuati e cause del fallimento

1. **Lettura del contenuto via connettore Drive** (`read_file_content`) sul vol. I: restituito contenuto **vuoto** (`fileContent: ""`). Ritentato una seconda volta: identico. Stessa cosa sul vol. II (1876). Anche il campo `contentSnippet` dei metadati è vuoto per entrambi. Interpretazione più probabile: i PDF sono **scansioni prive di strato testuale OCR** (o troppo grandi perché il connettore ne tenti l'estrazione), quindi l'estrattore di testo non ha nulla da restituire.
2. **Download del binario via connettore Drive** (`download_file_content`) sul vol. I: rifiutato con errore esplicito «File too large for download, over limit of **10 MB**». Entrambi i volumi (67–76 MB) superano il limite; nessuna annata della cartella (30–135 MB, v. inventario) rientra nel limite.
3. **Download diretto via HTTPS** (`https://drive.google.com/uc?export=download&id=…`): bloccato dal proxy di rete dell'ambiente con **HTTP 403 al CONNECT** verso `drive.google.com:443` (stessa classe di blocco già documentata per archive.org, Google Books ecc. in `02-trascrizioni-da-acquisire.md`). Non aggirabile da questa sessione.

Conclusione: da questo ambiente il contenuto dei PDF del Drive è **strutturalmente irraggiungibile** finché (a) i file non hanno OCR incorporato leggibile dal connettore, oppure (b) non è disponibile un canale di download per file >10 MB.

## 3. Conseguenze per la ricerca

- I bersagli di trascrizione elencati in `02-trascrizioni-da-acquisire.md` (frontespizio del vol. I, eventuale avvertenza/programma del fascicolo I del 15 nov. 1874, eventuale atto istitutivo riprodotto, indicazioni su periodicità/abbonamento/distribuzione, indice e struttura del fascicolo) restano **tutti da acquisire**.
- **Nessun dato nuovo** è emerso su atti istitutivi, periodicità o distribuzione: `01-atti-normativi/00-sintesi.md` non è stato modificato.
- Restano validi, come dati di seconda mano da riverificare sull'esemplare, quelli già acquisiti in `01-serie-editoriale-e-struttura.md` (12 fascicoli, 15 nov. 1874 – 15 ott. 1875, 998 pp., Tip. Sinimberghi).

## 4. Vie d'uscita praticabili (in ordine di semplicità)

1. **Estrarre localmente le prime carte**: chiedere all'utente (o a una sessione con accesso al file) di produrre un PDF ridotto delle prime 20–30 pagine del vol. I (frontespizio, avvertenza, fascicolo I, indice) — ad es. con `pdftk`/`qpdf`/anteprima — e caricarlo nel Drive: un estratto di poche pagine di scansione starebbe sotto i 10 MB e sarebbe scaricabile con il connettore; l'OCR si può poi eseguire in sessione (tesseract, lingua ita).
2. **OCR a monte**: far passare il PDF da Google Drive/Google Docs OCR o da Acrobat e ricaricare la versione con strato testuale; a quel punto `read_file_content` dovrebbe restituire testo (da verificare: potrebbe comunque troncare un volume di ~1.000 pagine, ma le prime pagine basterebbero).
3. **Screenshot/immagini**: anche 3–5 immagini (JPEG/PNG) del frontespizio e delle prime pagine del fascicolo I caricate nel Drive sarebbero leggibili direttamente dal connettore (che supporta `image/png`, `image/jpeg`).
4. In subordine, le piste esterne già censite in `02-trascrizioni-da-acquisire.md` §2 (HathiTrust, Google Books, teca BNC Roma, GU 19 nov. 1874), che però richiedono una rete senza il blocco proxy attuale.
