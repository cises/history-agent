# Censimento delle digitalizzazioni dei primi volumi del BUMPI

**Data della ricognizione**: 6 agosto 2026
**Oggetto**: primi volumi/fascicoli del *Bollettino Ufficiale* del Ministero della (Pubblica) Istruzione, avvio pubblicazioni 15 novembre 1874.

## Avvertenza metodologica (limite tecnico della sessione)

In questa sessione l'ambiente di lavoro consentiva **solo interrogazioni tramite motore di ricerca** (WebSearch): l'accesso HTTP diretto a *tutti* i domini rilevanti (archive.org, books.google.com, catalog/babel.hathitrust.org, opac.sbn.it, emeroteca.braidense.it, digitale.bnc.roma.sbn.it, internetculturale.it, librinlinea.it, gazzettaufficiale.it ecc.) è stato **bloccato dal proxy di rete (HTTP 403 su ogni tentativo, sia via WebFetch sia via curl)**. Non è stato quindi possibile aprire le pagine digitalizzate né l'OCR: **le trascrizioni testuali di frontespizio e avvertenza restano da acquisire** (vedi `02-trascrizioni-da-acquisire.md`). Tutti i dati sotto riportati provengono da snippet di ricerca e da riassunti dei risultati, con URL registrato; ogni volta che il dato non è direttamente verificato sulla pagina, è marcato di conseguenza.

## 1. Quadro seriale (dato documentato, da cataloghi)

La testata è descritta in SBN/Librinlinea in **tre record seriali successivi** più le serie novecentesche:

| Serie | BID / record | Estremi | Luogo/tipografo | Periodicità |
|---|---|---|---|---|
| *Bollettino ufficiale* [del Ministero della pubblica istruzione] | SBN **MIL0285631** (scheda Librinlinea: https://www.librinlinea.it/search/public/appl/prefer.php?bid=MIL0285631 ; anche https://biblioteche.parma.it/SebinaOpac/Opac.do?BID=MIL0285631) | Vol. 1 (15 nov. 1874) – vol. 13 (feb. 1887) | Roma : Sinimberghi, 1875–1887 ; 26 cm | mensile |
| *Bollettino ufficiale dell'istruzione* | Polo TES **TES0068850** (https://polotes.sebina.it/opac/resource/TES0068850 ; anche Polo giuridico RMG00049724, OPAC Umbria UM100100588) | Vol. 13, n. 3 (mar. 1887) – vol. 18, n. 9 (lug. 1891) | Roma : Bencini, 1887–1891 | mensile, in 3 dispense per mese: *Atti e documenti scolastici*; *Provvisioni per il personale*; *Miscellanea* |
| *Bollettino ufficiale del Ministero dell'istruzione pubblica* | SBN **MIL0069278** (https://opac.sbn.it/bid/MIL0069278 ; Librinlinea: https://www.librinlinea.it/titolo/bollettino-ufficiale-del-ministero-dell/MIL0069278) | A. 18, pt. 3, n. 1 (5 ago. 1891) – a. 50, vol. 2, n. 59 (31 dic. 1923); 32 vol. | Roma : Tip. di E. Sinimberghi | settimanale |
| (dal 1924) *Bollettino ufficiale. Ministero della Pubblica Istruzione. I. Leggi…* / *II. Atti di amministrazione* | (record collegati a MIL0069278) | dal 2 gen. 1924 | Roma | settimanale, in 2 parti separate |

Fonte principale per la storia editoriale: record Stanford SearchWorks https://searchworks.stanford.edu/view/9754902 (vedi § 3) e WorldCat https://www.worldcat.org/title/39942175.

## 2. Digitalizzazioni e riproduzioni individuate

### 2.1 HathiTrust (dato documentato, non verificato pagina per pagina)

- **Record catalografico**: *Bollettino ufficiale del Ministero dell'educazione nazionale* [titolo cumulativo assegnato dal catalogo americano], **catalog.hathitrust.org/Record/008700216** (MARC: https://catalog.hathitrust.org/Record/008700216.marc).
- La voce corrispondente dell'**Online Books Page** (Univ. of Pennsylvania) segnala: «page images at HathiTrust, **US access only**», con inizio della serie a **Roma, 1874** (http://onlinebooks.library.upenn.edu/webbin/book/lookupname?key=Italy.+Ministero+dell%27educazione+nazionale).
- **Da verificare**: quali annate siano effettivamente presenti come item digitalizzati e se il vol. I (1874–75) sia tra questi; l'accesso dichiarato «US only» limita la consultazione dall'Italia nonostante la pubblicazione sia anteriore al 1930 (è una restrizione tipica per i «government documents» esteri digitalizzati da Google).
- Record collegato utile: *Stato del personale addetto alla pubblica istruzione del Regno d'Italia*, https://catalog.hathitrust.org/Record/000047674 (appendici del Bollettino, vedi § 2.5).

### 2.2 Google Books (record individuati; livello di visualizzazione da verificare)

Record «about» reperiti nelle ricerche (l'ID non indica di per sé l'annata; il blocco di rete non ha consentito di aprirli):

| ID Google Books | Titolo nel record | URL |
|---|---|---|
| `LcQdozq2twcC` | Bollettino ufficiale del Ministero dell'istruzione pubblica | https://books.google.com/books/about/Bollettino_ufficiale_del_Ministero_dell.html?id=LcQdozq2twcC |
| `pXZR_iF3QdkC` | Bollettino ufficiale del Ministero dell'istruzione pubblica | https://books.google.com/books/about/Bollettino_ufficiale_del_Ministero_dell.html?id=pXZR_iF3QdkC |
| `idwW4qNR5hoC` | Bollettino ufficiale del Ministero dell'istruzione pubblica | https://books.google.com/books/about/Bollettino_ufficiale_del_Ministero_dell.html?id=idwW4qNR5hoC |
| `ez1QWRwBgmIC` | Bollettino ufficiale | https://books.google.com/books/about/Bollettino_ufficiale.html?id=ez1QWRwBgmIC |
| `_11GAAAAYAAJ` | Bollettino ufficiale del Ministero dell'educazione nazionale | https://books.google.com/books/about/Bollettino_ufficiale_del_Ministero_dell.html?id=_11GAAAAYAAJ |
| `Q_Vdo7awrUgC` | Bollettino ufficiale — Italia: Ministero dell'educazione nazionale | https://books.google.com/books/about/Bollettino_ufficiale.html?id=Q_Vdo7awrUgC |
| `HXOvDUJQyeIC` | Bollettino ufficiale (ebook su Google Play) | https://play.google.com/store/books/details/Bollettino_ufficiale?id=HXOvDUJQyeIC |

**Ipotesi di lavoro**: l'ID `_11GAAAAYAAJ` (suffisso `GAAAAYAAJ` tipico delle scansioni da biblioteche universitarie USA) corrisponde con ogni probabilità a uno dei volumi confluiti in HathiTrust (record 008700216); gli altri ID potrebbero derivare dal progetto Google/biblioteche italiane. L'attribuzione ID→annata va fatta aprendo i record.

### 2.3 Emeroteca digitale BNC Roma (dato documentato: la testata è digitalizzata, almeno in parte)

- La ricerca ha restituito un URL di sfoglio diretto della teca: **http://digitale.bnc.roma.sbn.it/tecadigitale/giornale/MIL0069278/1920/v.1/00000014** — dunque la BNC Roma ha digitalizzato la testata (BID MIL0069278) almeno per annate novecentesche (es. 1920).
- **Da verificare**: se la teca copra anche la prima serie 1874–1887 (BID MIL0285631). Percorso di verifica: http://digitale.bnc.roma.sbn.it/tecadigitale/emeroteca/classic e ricerca per BID `MIL0285631` / `MIL0069278`.

### 2.4 Emeroteca Braidense e Internet Culturale (esito negativo/non concluso)

- Nessun riscontro, negli snippet, della presenza del BUMPI tra le ~960 testate dell'Emeroteca Braidense (http://emeroteca.braidense.it/ ; indice: http://emeroteca.braidense.it/indice_testate.php). **Esito non conclusivo**: l'indice non è stato consultabile direttamente.
- Internet Culturale: non interrogabile in questa sessione.

### 2.5 Digitalizzazione certa di un'appendice del vol. I: Università di Torino

- **Dato documentato**: *Stato del personale addetto alla Pubblica Istruzione del Regno d'Italia al 31 decembre 1874. Appendice al Bollettino ufficiale del Ministero dell'Istruzione*, Roma, **Tipografia Sinimberghi**, 1874 [ma 1875?], 110 pp. — digitalizzato nel 2015 dall'Archivio Storico dell'Università di Torino, esposto in «L'Archivio in mostra»: **https://www.asut.unito.it/mostre/items/show/65** (licenza CC BY 3.0).
- È la prova materiale che al Bollettino si accompagnavano **appendici** con lo stato del personale (conferma indiretta della funzione amministrativo-informativa della testata).

### 2.6 Internet Archive (esito non conclusivo)

L'API `archive.org/advancedsearch.php` non è risultata raggiungibile (403 dal proxy). Le ricerche indirette non hanno fatto emergere alcun item del BUMPI su archive.org (emergono solo bollettini di altri enti: Società geologica, Comitato geologico ecc.). **Ipotesi**: la testata non è presente su Internet Archive come collezione propria; da ricontrollare con l'API quando l'accesso sarà possibile.

### 2.7 Esemplari cartacei in commercio (utili per la descrizione materiale)

| Esemplare | Dati dal venditore | URL |
|---|---|---|
| **Volume I, anno 1874–1875** | 12 fascicoli mensili rilegati in un tomo, dal 15 nov. 1874 al 15 ott. 1875; Roma, **Tipografia Sinimberghi**; **998 pp.**; mezza tela coeva, nota ms. al margine sup. della prima pagina, timbro di ex biblioteca | https://www.abebooks.it/Ministero-Pubblica-Istruzione-Bollettino-Ufficiale-Volume/30961766853/bd (Biblioteca di Babele) |
| Volume [I?], Tip. Sinimberghi | scheda gemella su Feltrinelli/IBS | https://www.lafeltrinelli.it/ministero-della-pubblica-istruzione-bollettino-libri-vintage-vari/e/2561744076020 |
| **Volume III, anno 1877** | 12 fascicoli mensili (gennaio–dicembre 1877) rilegati; Roma, **Tipografia Eredi Botta**; **908 pp.** | https://www.ibs.it/ministero-della-pubblica-istruzione-bollettino-libri-vintage-vari/e/2561744075801 |
| Anno 1887 (miscellanea) | | https://www.abebooks.com/Ministero-pubblica-istruzione-Bollettino-Ufficiale-Anno/30988134451/bd |
| Anno XXII, vol. I, 1895 | | https://www.abebooks.com/Bollettino-ufficiale-Ministero-dellIstruzione-Pubblica-Anno/30789222588/bd |

## 3. Sintesi dei dati materiali acquisiti sui primi volumi

Vedi il dettaglio e la discussione in `01-serie-editoriale-e-struttura.md`. In breve (tutti **dati documentati**, con le fonti sopra):

- **Avvio**: fascicolo I datato **15 novembre 1874** (concorde: Librinlinea MIL0285631, librai antiquari). *Discrepanza*: la nota di pubblicazione ripresa da Stanford/Online Books Page indica «**Dec. 15, 1874** – Dec. 1888 (v. I–XIV)» — da sciogliere sull'originale.
- **Periodicità dichiarata**: mensile (fascicolo il 15 di ogni mese) fino al 1887.
- **Vol. I** = annata a cavallo: 15 nov. 1874 – 15 ott. 1875, 12 fascicoli, 998 pp.; **vol. III** = anno solare 1877 (gen.–dic.), 908 pp.
- **Tipografie**: Sinimberghi (vol. I e serie SBN 1875–1887), ma Eredi Botta per il vol. III (1877): la tipografia cambiò più volte; dal 1887 Bencini; dal 1891 di nuovo E. Sinimberghi; anni 1893 Tip. Elzeviriana (parte II) e Tip. Operaia Romana Cooperativa (cfr. schede IBS).
- **Struttura interna**: la bipartizione **Parte ufficiale / Parte non ufficiale** è documentata solo **dal 3 giugno 1891 al 31 dicembre 1923** (record Stanford). Nel 1887–91 vigeva la tripartizione *Atti e documenti scolastici / Provvisioni per il personale / Miscellanea*. **Per i fascicoli 1874–1887 la struttura interna resta da descrivere sull'originale** (ipotesi: sequenza unica di atti — leggi, decreti, circolari, nomine — con appendici, come lo *Stato del personale* 1874).
- **Prezzo, abbonamento, distribuzione** (provveditorati, scuole, invii d'ufficio): **nessun dato reperito** negli snippet; da leggere sull'avvertenza del fascicolo I e sulle copertine editoriali (vedi `02-trascrizioni-da-acquisire.md`).

## 4. Piste aperte

1. Aprire il record HathiTrust 008700216 e censire gli item per annata (eventualmente via proxy USA, data la restrizione «US access only»).
2. Attribuire gli ID Google Books alle annate; verificare la «visualizzazione completa» (pubblicazione governativa pre-1900).
3. Interrogare la teca BNC Roma per MIL0285631/MIL0069278 (prima serie).
4. Scaricare il PDF della Biblioteca del Senato sui bollettini ministeriali (https://www.senato.it/sites/default/files/repository/relazioni/biblioteca/moduli/Bollettini_Ministeri.pdf) per gli estremi di raccolta.
5. La Gazzetta Ufficiale n. 276 del 19 nov. 1874 (https://www.gazzettaufficiale.it/eli/gu/1874/11/19/276/sg/pdf), uscita quattro giorni dopo il fascicolo I, è un candidato per l'annuncio/atto istitutivo → passare a `01-atti-normativi/`.
