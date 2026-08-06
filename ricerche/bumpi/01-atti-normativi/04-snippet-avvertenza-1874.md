# Caccia agli snippet: «Avvertenza»/programma del fascicolo I del Bollettino Ufficiale (15 novembre 1874)

Data ricerca: 2026-08-06. Canale: esclusivamente snippet dei motori di ricerca (WebSearch).
Legenda: **[D]** = dato documentato (riportato testualmente o parafrasato da fonte identificata negli snippet); **[H]** = ipotesi/inferenza da verificare.

## 0. Vincoli tecnici della sessione (esiti strumentali)

- Il proxy ha bloccato con 403 **tutti** i fetch diretti tentati: abebooks.it, books.google.com, babel/catalog.hathitrust.org, archive.org, librinlinea.it, opac.sbn.it, internetculturale.it, it.wikisource.org, it.wikipedia.org, gallica.bnf.fr, europeana, openlibrary, duckduckgo, seriestoriche.istat.it, dgagaeta.cultura.gov.it, gazzettaufficiale.it, senato.it. Nessun testo di pagina è stato quindi leggibile direttamente.
- **Unico host passante: `www.googleapis.com`** (API Google Books, endpoint `books/v1/volumes`), ma con **quota giornaliera esaurita** (HTTP 429, `project_number:624717413613`). **[H] Pista operativa per una prossima sessione**: ritentare l'API Books (le quote sono giornaliere) con query a frase esatta — è l'unico canale che restituirebbe `searchInfo.textSnippet` dall'OCR dei volumi ottocenteschi.

## 1. Frammenti e dati utili recuperati dagli snippet

### 1.1 Struttura e dati editoriali del volume I (1874-75) — [D]

**Fonte**: annuncio di vendita «Ministero della Pubblica Istruzione - Bollettino Ufficiale Volume I - Anno 1874-1875», libreria Biblioteca di Babele, su AbeBooks.it — https://www.abebooks.it/Ministero-Pubblica-Istruzione-Bollettino-Ufficiale-Volume/30961766853/bd — e annuncio gemello su lafeltrinelli.it — https://www.lafeltrinelli.it/ministero-della-pubblica-istruzione-bollettino-libri-vintage-vari/e/2561744076020
**Query**: `"Bollettino ufficiale" "15 novembre 1874" ministero istruzione pubblica`; `lafeltrinelli "Ministero della Pubblica Istruzione - Bollettino Ufficiale" Sinimberghi descrizione volume 1874`

Testo della descrizione ricostruito dagli snippet (frammento in italiano riportato testualmente dal motore):

> «Volume I completo, anno 1874-1875, composto da dodici fascicoli, dal I, 15 novembre 1874, al XII, 15 ottobre 1875, rilegati in un unico tomo, del periodico mensile Ministero della Pubblica Istruzione - Bollettino Ufficiale.»

Ulteriori dati dalla stessa scheda (parafrasi del motore): volume di **998 pagine a numerazione progressiva**; stampato a **Roma, Tipografia Sinimberghi**; seconda metà dell'800, mezza tela con angoli, piatti marmorizzati, titoli in oro al dorso. (Un altro annuncio Feltrinelli per un volume successivo indica «Tipografia Eredi Botta», Roma: la tipografia cambiò negli anni.)

**Valutazione**: è il dato più solido emerso: cadenza mensile, uscita il 15 del mese, 12 fascicoli per annata (nov. 1874 – ott. 1875). Non contiene però il testo dell'Avvertenza.

### 1.2 Estremi cronologici della serie — [D] con discrepanza

- «The official bulletin ran from volume 1 (November 15, 1874) through volume 13 (February 1887), published in Rome by Sinimberghi» — sintesi del motore basata sui cataloghi OPAC (opac.sbn.it MIL0069278; pologiuridico.giustizia.it RMG00061700; polotes.sebina.it TES0068850). Query: `"Questo Bollettino" ministero "pubblica istruzione" 1874 avvertenza` e successive.
- **Discrepanza [D]**: una sintesi (query `"Bollettino ufficiale" Bonghi 1874 storia educazione pdf "fascicolo I"`, fonte apparente: catalogo HathiTrust/Stanford SearchWorks, https://catalog.hathitrust.org/Record/008700216 e https://searchworks.stanford.edu/view/9754902) afferma: «first series ran from **December 15, 1874** to December 1888 (volumes I-XIV)». **[H]** Probabile imprecisione del record catalografico americano (o della sintesi del motore); il 15 novembre 1874 è confermato da più fonti indipendenti.
- [D] Continuazioni: «Bollettino ufficiale dell'istruzione» (1887-1891), poi di nuovo «Bollettino ufficiale del Ministero dell'istruzione pubblica» dal 5 agosto 1891 al 31 dicembre 1923; dal 1924 diviso in due parti (leggi/regolamenti e disposizioni generali). Fonti: OPAC giustizia.it RMG00061700 e RMG00049724.

### 1.3 L'Appendice al volume I: «Stato del personale» — [D]

**Fonte**: Archivio Storico dell'Università di Torino, mostra virtuale — https://www.asut.unito.it/mostre/items/show/65
**Query**: `"Questo Bollettino" ministero "pubblica istruzione" 1874 avvertenza`; `asut.unito.it "Appendice al Bollettino ufficiale" 1874 stato del personale`

> «Stato del personale addetto alla Pubblica Istruzione del Regno d'Italia al 31 Decembre 1874 : Appendice al Bollettino ufficiale del Ministero dell'Istruzione», Roma, Tipografia Sinimberghi, 1874 [rectius 1875], **110 pagine**.

Conferma che il Bollettino nacque anche come strumento di pubblicità dello stato del personale ministeriale — coerente con la funzione amministrativa dichiarata. **[H]**

### 1.4 Il R.D. 15 novembre 1874, n. 2215 (Museo d'istruzione e di educazione) — [D]

**Fonte**: Wikipedia it., «Museo della Scuola e dell'Educazione "Mauro Laeng"» — https://it.wikipedia.org/wiki/Museo_della_Scuola_e_dell'Educazione_%22Mauro_Laeng%22
**Query**: `"Museo d'istruzione e di educazione" "15 novembre 1874"`

Sintesi del motore (parafrasi fedele): «Il 15 novembre 1874 fu istituito con **Regio Decreto n. 2215**, su proposta di **Ruggiero Bonghi** (ministro della Pubblica Istruzione) e **Gaspare Finali** (ministro di Agricoltura, Industria e Commercio), il Museo d'istruzione e di educazione, con sede presso il liceo-ginnasio "Ennio Quirino Visconti" in piazza del Collegio Romano».

**[H]** La coincidenza di data col fascicolo I (15 novembre 1874) rende molto plausibile che il decreto sia stato pubblicato nel fascicolo I o nei primissimi fascicoli del Bollettino; **nessuno snippet ha però confermato la presenza del R.D. 2215 nel fascicolo I**. Il testo del decreto («è istituito…») non è emerso in alcuno snippet. Un volume utile alla verifica: «Storia del Museo d'Istruzione e di Educazione», Edizioni Anicia — https://www.edizionianicia.it/prodotto/storia-del-museo-d-istruzione-e-di-educazione/ (fetch bloccato).

### 1.5 Contesto: circolare Bonghi del 20 novembre 1874 — [D]

**Fonte**: emersa nella sintesi della query `Bonghi "Bollettino ufficiale" ministero istruzione 1874 istituì programma primo fascicolo` (fonte apparente: saggio in PDF su dsrivista.unibo.it o art.torvergata.it).

> Il ministro Bonghi, con **circolare del 20 novembre 1874**, ordinò agli istituti d'istruzione secondaria del Regno di stampare una relazione annuale che consentisse ai cittadini di conoscerne le caratteristiche e di apprezzare l'attività e la diligenza degli insegnanti.

Cinque giorni dopo il fascicolo I: conferma il clima di «pubblicità degli atti» in cui il Bollettino nacque. **[H]** La circolare è con ogni probabilità pubblicata nel fascicolo II (15 dicembre 1874).

### 1.6 Repertori e localizzazioni per il reperimento del testo — [D]

- HathiTrust, Catalog Record 008700216 (serie del Bollettino; volumi digitalizzati, accesso da verificare) — https://catalog.hathitrust.org/Record/008700216
- Google Books, schede della serie: id `LcQdozq2twcC`, `JjfyouSI6isC`, `d7aHEYsGOOcC`, `Fa8FoAg90-8C` (Bollettino Min. istruzione pubblica); `_11GAAAAYAAJ`, `nGWlQS_SE0kC` (serie educazione nazionale).
- Biblioteca del Senato, elenco raccolte bollettini ministeriali (PDF): https://www.senato.it/sites/default/files/repository/relazioni/biblioteca/moduli/Bollettini_Ministeri.pdf
- Gazzetta Ufficiale del Regno, **n. 276 del 19 novembre 1874** (scansione PDF): https://www.gazzettaufficiale.it/eli/gu/1874/11/19/276/sg/pdf — emersa cercando l'annunzio del Bollettino in GU (query `"Gazzetta Ufficiale del Regno" novembre 1874 "Bollettino ufficiale del Ministero della istruzione pubblica" annunzio abbonamento lire`). **[H]** Numero candidato (a 4 giorni dal fascicolo I) per un eventuale annuncio/avviso; contenuto NON verificato (fetch bloccato; scansione immagine non ricercabile).
- Collezione celerifera delle leggi 1874: schede Google Books id `768oAAAAYAAJ`, `8J0oAAAAYAAJ` (nessuno snippet testuale sul Bollettino).
- Saggio «Ruggiero Bonghi» (Pubblicazioni degli Archivi di Stato, Saggi 80): https://dgagaeta.cultura.gov.it/public/uploads/documents/Saggi/5a2650ce46370.pdf — fetch bloccato; **[H]** candidato forte a citare l'istituzione del Bollettino.

## 2. Testo dell'«Avvertenza»: esito

**NESSUNO snippet ha restituito testo verbatim dell'Avvertenza/programma del fascicolo I, né di un atto o annuncio istitutivo.** In particolare non è emersa alcuna occorrenza 1874 della formula sul valore legale («forza di partecipazione», attestata a fine secolo come «partecipazione esecutiva»): la questione se essa risalga alla prima serie resta **aperta**.

## 3. Esiti negativi (query provate, da NON ripetere sullo stesso canale)

Tutte via WebSearch; risultati = solo le solite schede OPAC/librerie, nessun testo d'epoca:

1. `"Questo Bollettino" ministero "pubblica istruzione" 1874 avvertenza` — negativo (solo cataloghi).
2. `"forza di partecipazione" bollettino ministero istruzione 1874` — negativo.
3. `"forza di partecipazione esecutiva" bollettino` — negativo (solo diritto amministrativo odierno).
4. `"avranno forza di partecipazione" ministero` — negativo (concorsi odierni).
5. `"Il Ministero ha divisato" bollettino istruzione` — negativo.
6. `"gli atti più importanti del Ministero" istruzione bollettino 1874` — negativo.
7. `"L'Istitutore" 1874 "bollettino ufficiale" ministero nuovo` — negativo (nessuna rivista coeva indicizzata).
8. `"avvertenza" "bollettino ufficiale" 1874 pubblica istruzione primo fascicolo Bonghi` — negativo.
9. `"Collezione celerifera" 1874 bollettino istruzione ministero` — negativo (solo schede GB della Celerifera).
10. `"si pubblica" "d'ogni mese" bollettino ufficiale istruzione 1874` — negativo (GU 1888/1898 fuori tema).
11. `"regio decreto" "2215" "15 novembre 1874" museo istruzione educazione Bonghi` — parzialmente utile (v. § 1.4), niente testo del decreto.
12. `"15 novembre 1874, n. 2215" museo istruzione "è istituito"` — negativo sul testo; utile per fonti ACS/Anicia.
13. `"primo numero del Bollettino" ministero istruzione Bonghi 1874` — negativo.
14. `"Bollettino ufficiale del Ministero dell'istruzione pubblica" nascita 1874 storia rivista amministrazione scolastica` — negativo (dato curioso [D]: molti fascicoli contenevano una «Tavola necrologica»).
15. `Chiosso "stampa pedagogica" "Bollettino ufficiale" ministero pubblica istruzione 1874` — negativo (la voce di Chiosso non è indicizzata).
16. `"tien luogo" OR "terrà luogo" "di partecipazione" bollettino ufficiale istruzione ministero` — negativo.
17. `archive.org "bollettino ufficiale" ministero istruzione pubblica 1874 1875 full text` — negativo: nessuna digitalizzazione IA del vol. I individuata.
18. `"ha cominciato a pubblicare" OR "incominciò a pubblicarsi" bollettino ufficiale ministero istruzione 1874` — negativo.
19. `perché fu istituito il Bollettino ufficiale ... Bonghi circolare atti ufficiali` — negativo.
20. `"Bollettino Ufficiale del Ministero della Pubblica Istruzione" Bonghi fondato scopo ... museo` — negativo.
21. `"Bollettino" "ministero" istruzione "1874" "avvertenza premessa" OR "avvertenza al primo" OR "programma della pubblicazione"` — negativo.
22. `"bollettino ufficiale" istruzione 1874 "regie università" "provveditori" sommario fascicolo novembre decreti circolari nomine` — negativo.
23. `"Bollettino ufficiale" Bonghi 1874 storia educazione pdf "fascicolo I"` — parzialmente utile (circolare 20.11.1874; saggio ACS su Bonghi; discrepanza «December 15, 1874»).

## 4. Valutazione finale

1. **Recuperato [D]**: l'intera struttura editoriale del fascicolo I e del volume I (12 fascicoli mensili, 15.11.1874–15.10.1875, 998 pp., Tip. Sinimberghi, Roma, con Appendice «Stato del personale» di 110 pp.); gli estremi della serie (1874–1887, poi continuazioni); il R.D. 15.11.1874 n. 2215 (Museo d'istruzione e di educazione, proponenti Bonghi e Finali) datato lo stesso giorno del fascicolo I; la circolare Bonghi del 20.11.1874 sulle relazioni annuali degli istituti secondari.
2. **Non recuperato**: il testo (anche parziale) dell'«Avvertenza»/programma del fascicolo I; qualunque annuncio istitutivo in Gazzetta Ufficiale; l'origine 1874 della formula «forza di partecipazione». Il web indicizzato dai motori interrogabili non contiene OCR del volume I né letteratura secondaria che ne citi l'Avvertenza.
3. **[H] Piste operative concrete per la prossima sessione**: (a) ritentare l'API Google Books su `www.googleapis.com` (unico host passante; quota giornaliera oggi esaurita) con frasi esatte: «Questo Bollettino», «forza di partecipazione», «Bollettino ufficiale del Ministero della istruzione pubblica» + 1874; (b) GU n. 276 del 19.11.1874 (e numeri adiacenti 10–20.11.1874) su gazzettaufficiale.it da consultare fuori proxy; (c) HathiTrust Record 008700216 (verificare se il vol. I 1874-75 è full view da rete non bloccata); (d) saggio ACS «Ruggiero Bonghi» (Saggi 80) e «Storia del Museo d'Istruzione e di Educazione» (Anicia) come letteratura che quasi certamente tocca l'istituzione del Bollettino.
