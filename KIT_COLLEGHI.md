# Come contribuire ad Aula Tecnica
Versione 1.0. Non sono richiesti abbonamenti a modelli IA, installazioni di sviluppo
o accesso al codice del sito. L'uso dell'IA è facoltativo.

## Cosa serve
Un account GitHub gratuito per inviare la proposta, un browser e il materiale
che vuoi condividere. Puoi scrivere direttamente oppure aiutarti con un assistente
IA gratuito. I servizi gratuiti possono avere limiti d'uso: il procedimento non
richiede API, collegamenti GitHub dall'IA, Codex Cloud o funzioni a pagamento.

## 1. Prepara
Scarica il template della lezione o dell'attività pratica. Indica anno, materia,
argomento, obiettivo e autore pubblico. Usa le regole editoriali allegate.
Non inviare alla chat IA dati di studenti, verifiche future o documenti riservati.

## 2. Scrivi o chiedi aiuto all'IA
Incolla il prompt gratuito, il template e il testo delle fonti che puoi condividere.
Non è necessario caricare più file: il testo si può copiare nella chat.
Conserva il risultato in Markdown (.md) o testo (.txt). La scelta del modello è libera.

## 3. Controlla come docente
Rileggi; ricontrolla formule, dati, risultati, unità e arrotondamenti. Distingui
la traccia dalle ipotesi. Elenca i dubbi ancora aperti. Verifica la leggibilità
ed il diritto di diffondere gli allegati. La risposta dell'IA non è una verifica.

## 4. Invia da GitHub
Nel repository di proposte indicato da Aula Tecnica apri Issues → New issue →
«Proponi una lezione». Compila i campi e incolla la lezione, oppure allega il file
.md/.txt nel campo del contenuto. Aggiungi immagini o PDF autorizzati, non scansioni
integrali di libri. Puoi anche incollare il contenuto se un tipo di file non è accettato.
Non serve creare un branch, clonare il sito o conoscere JSON/UUID.

IMPORTANTE: il repository di proposte è pubblico. Testo, nome GitHub e allegati
sono leggibili prima dell'approvazione. Le «note editoriali» non sono private.
Non inviare verifiche riservate, dati di classe o materiale da mantenere segreto.

## 5. Collabora alla revisione
Lorenzo legge la proposta e può chiedere correzioni nella stessa Issue. Invia una
versione aggiornata riconoscibile. Dopo una prima revisione, Lorenzo integra il
contenuto in un branch del sito e prepara la preview. Non è immediata all'invio.

Lorenzo verifica impaginazione, calcoli e materiali e decide se pubblicare. Solo
il suo merge in main avvia la pubblicazione sul dominio. Riceverai l'URL definitivo
nella Issue quando il deploy e la pagina saranno stati controllati.
Le anteprime online possono essere pubbliche: non utilizzarle per contenuti riservati.

## Richiedere una correzione
Apri la Issue «Correggi una lezione», indica l'URL, il passaggio interessato e la
correzione proposta con motivazione e fonte. Non inviare una nuova lezione duplicata.

## Autori e riconoscimento
Indica il nome con cui desideri essere accreditato. La redazione conserva la
provenienza del contributo e la revisione del responsabile. Non sono richiesti
indirizzi email o dati personali aggiuntivi. Le modifiche ai template e alla grafica
si possono suggerire, ma sono decise dal responsabile del sito.


---


# Aula Tecnica — Regole editoriali
Versione delle regole: 1.0 — 11 novembre 2026.
Responsabile delle decisioni editoriali e tecniche: Lorenzo Cardeti.

## Scopo e permessi
Il collega propone contenuti; Lorenzo decide impaginazione, template, navigazione,
inserimento nel programma e pubblicazione. Il modello linguistico è uno strumento,
non un validatore scientifico né un soggetto autorizzato a pubblicare.

Il repository del sito resta privato. Nella prima fase i proponenti non ricevono
permessi di scrittura su quel repository. Le proposte si inviano attraverso le
Issues del repository separato di contributi. Nessuna Issue genera automaticamente
una modifica, un'anteprima o un deploy. Le proposte e gli allegati del repository
pubblico sono visibili anche prima dell'approvazione editoriale.

Queste istruzioni non sono un controllo di accesso: la separazione dei permessi è
il controllo effettivo. Anche CODEOWNERS non è un blocco dei file in assenza delle
protezioni di GitHub previste dal piano e delle opportune impostazioni.

## 1. Contenuti, non codice
Consegnare testo Markdown o testo semplice, formule LaTeX, tabelle e materiali
esplicitamente autorizzati alla diffusione. Non richiedere al collega JSON, UUID,
Git locale, Node, API a pagamento, Codex o un abbonamento a un assistente.
Non inserire HTML eseguibile, JavaScript, CSS, iframe, script o istruzioni di deploy.
Non proporre modifiche a layout o componenti come parte del contenuto di una lezione.

## 2. Collocazione
Indicare titolo, anno, materia, percorso Teoria/Pratica, argomento e prerequisiti.
Le eventuali nuove categorie sono proposte da approvare, non modifiche automatiche
al catalogo. Rispettare la separazione tra teoria e attività CAD. Per la Pratica,
utilizzare le tipologie di componente e poi assiemi/progetti già concordati.
Non inventare scadenze, durate o avanzamenti del cronoprogramma.

## 3. Struttura adattabile, non sezioni vuote
Titolo; breve obiettivo; prerequisiti; spiegazione essenziale; relazioni necessarie;
esempio, se utile; esercizi, se pertinenti; sintesi. Per il laboratorio: obiettivo,
materiali di riferimento, consegna, elaborati richiesti e autocontrollo.
Non imporre un numero fisso di esercizi a qualunque argomento. Omettere le sezioni
non pertinenti invece di aggiungere testo di riempimento. L'indice del sito deriva
dai titoli: l'autore non deve duplicarlo nel contenuto.

## 4. Rigore e provenienza
Distinguere dati della traccia, deduzioni, ipotesi didattiche e punti da confermare.
Quando sono fornite fonti, rispettarne terminologia e struttura, segnalando errori
presunti o incongruenze senza correggerli silenziosamente. Non inventare riferimenti,
quote, parametri, tabelle o risultati attribuendoli alla fonte. Informazioni esterne
aggiunte vanno identificate e documentate. I dati non leggibili restano da chiarire.

I calcoli devono avere una verifica indipendente del docente proponente. Registrare
le condizioni di validità delle formule, controllare dimensioni e unità e applicare
gli arrotondamenti alla fine. Un test software non certifica la fonte dei dati.

## 5. Formule
Scrivere formule in LaTeX: \( ... \) in linea e \[ ... \] per una formula autonoma.
Ogni simbolo deve avere significato e unità; usare una riga per simbolo. Il sito
renderizza KaTeX/MathML, con formule autonome allineate a sinistra e senza riquadri.
Ogni calcolo, sostituzione e risultato ha una propria riga. Non usare immagini per
formule digitabili. Non modificare la notazione del materiale senza motivazione.

## 6. Esempi e soluzioni
Per ogni passaggio fornire numero, titolo, metodo e calcoli associati. Nel sito:
metodo a sinistra; formule/calcoli a destra; corrispondenza riga per riga. Su mobile:
metodo 1, calcoli 1, metodo 2, calcoli 2. Non usare due sequenze disaccoppiate.
Gli esempi sono visibili. Le soluzioni degli esercizi sono inizialmente chiuse,
apribili singolarmente. I titoli degli esercizi sono in grassetto.
Per la Pratica autonoma non aggiungere modelli risolti né sequenze di comandi CAD
senza una richiesta esplicita del responsabile.

## 7. Immagini, grafici e tavole
Allegare originali autorizzati, con descrizione, testo alternativo, origine e ruolo.
Non rimuovere attribuzioni, alterare quote o inventare misure da un raster. Non
usare immagini generative come fonte attendibile di geometrie o quotature.
I grafici quantitativi devono derivare dai dati dichiarati, con assi e unità.
Una scheda di consultazione non va spacciata per esercizio completamente quotato.
Non caricare copie integrali di libri o materiali di cui non è autorizzata la diffusione.

## 8. Compattezza e accessibilità
Linguaggio diretto; paragrafi brevi; gerarchia di titoli coerente; niente decorazioni
superflue, emoji o duplicazioni. Lo stile è centralizzato: niente font, colori,
larghezze o impaginazioni personalizzati per una singola lezione. Tutti i contenuti
devono mantenere leggibilità desktop/mobile e navigabilità da tastiera. La verifica
su Safari/iPhone va dichiarata eseguita soltanto se realmente effettuata.

## 9. Riservatezza
Non inviare verifiche da somministrare, soluzioni riservate, nomi o dati di studenti,
PDP, voti, password, token, dati sanitari, documenti amministrativi o file privati.
L'avviso vale sia per GitHub sia per i materiali immessi nel servizio IA scelto.
Non usare un repository pubblico o una preview non protetta per bozze confidenziali.
La rimozione successiva di un allegato pubblico non garantisce che non sia stato copiato.

## 10. Autori e fonti
L'autore umano rivede e si assume la responsabilità del contenuto proposto. Indicare
il nome pubblico desiderato e l'eventuale uso dell'IA; non pubblicare email personali.
Separare le fonti editoriali dalla lezione: identificazione dell'opera/documento,
pagina o sezione consultata, URL se disponibile e passaggi da verificare. Nella
pagina pubblica evitare la sezione generica «Fonti e ipotesi» non richiesta, ma
mantenere accanto alle formule le ipotesi necessarie e le attribuzioni dovute.
Non presentare come consultato un documento non effettivamente letto.

## 11. Approvazione e versioni
Ogni proposta porta versione delle regole/template e data. Le modifiche chieste
dal revisore restano nella stessa Issue, con una versione aggiornata riconoscibile.
Lorenzo conserva una fotografia del testo e degli allegati revisionati, con hash,
perché una Issue può essere modificata dopo la lettura. L'approvazione riguarda
il contenuto e il commit esaminati, non tutte le future modifiche della proposta.
Ogni variazione successiva all'anteprima richiede una nuova verifica.

## 12. Cosa decide esclusivamente Lorenzo
Regole, template canonici, schema delle lezioni, parser, renderer, CSS, design,
navigazione, catalogo e cronoprogrammi, configurazioni di build, accessi, CI,
Cloudflare, DNS, approvazione finale e merge in main. I colleghi possono suggerire
miglioramenti in una Issue; non modificano direttamente questi elementi del sito.


---


# Prompt per un assistente IA gratuito
Copia il testo seguente nella chat che utilizzi. Sotto aggiungi il template,
le fonti che puoi legittimamente condividere e i dati della lezione.
Non serve un collegamento dell'assistente a GitHub.

---
Prepara una proposta di lezione per Aula Tecnica in italiano, usando il template
e le regole editoriali forniti sotto. Non generare codice del sito: restituisci
Markdown leggibile, da copiare nella proposta GitHub.

Argomento: [specificare]
Anno e materia: [specificare]
Percorso: [Teoria / Pratica]
Obiettivi: [specificare]
Prerequisiti: [specificare]
Materiali forniti: [elenco]

Prima identifica quali dati e fonti sono effettivamente disponibili. Basa il
contenuto sulle fonti fornite e conserva la loro terminologia e impostazione.
Non inventare numeri, quote, riferimenti o citazioni. Se qualcosa non è leggibile
o manca, scrivi «da confermare» e spiega precisamente cosa manca. Non correggere
silenziosamente una fonte: separa la sua indicazione dalla tua osservazione.
Eventuali conoscenze esterne aggiunte vanno indicate come tali e verificate.

Utilizza formule LaTeX e una tabella simbolo/significato/unità. Ogni sostituzione,
calcolo e risultato va su una riga propria. Ogni esempio numerico e soluzione
deve essere una sequenza di passaggi con due campi associati: «Metodo» e «Calcoli».
Non creare due elenchi indipendenti: il sito li mostrerà affiancati riga per riga.

Negli esercizi separa traccia e soluzione: sul sito la soluzione sarà chiusa
inizialmente. Non fornire procedure CAD risolte per attività assegnate come autonome.
Per ogni materiale grafico proposto indica descrizione, origine, testo alternativo
e dati necessari, senza creare misure o immagini tecniche plausibili ma non verificate.

Sii compatto senza saltare i passaggi del ragionamento. Nessun riempitivo, emoji,
HTML, script, CSS o istruzione Git. Non dichiarare che hai modificato il sito,
aperto una pull request, controllato la build o pubblicato file se non lo hai fatto.

Restituisci:
1. La proposta nel template.
2. Le fonti effettivamente consultate.
3. I dati/risultati da ricontrollare dal docente prima dell'invio.

Se la risposta è troppo lunga, dividila in sezioni numerate mantenendo lo stesso
ordine, senza troncare formule e senza inventare ciò che manca. Il docente farà
la revisione finale: non chiedergli di acquistare abbonamenti o usare API.
---


---


# Proposta di lezione — [TITOLO]

## Scheda
- Versione template: 1.0
- Nome autore da mostrare sul sito: [nome pubblico, senza email]
- Anno: [1–5]
- Materia: [nome]
- Percorso: [Teoria oppure Pratica]
- Argomento / componente: [nome]
- Tipo proposta: [nuova lezione / modifica di lezione esistente]
- URL lezione esistente, se pertinente: [facoltativo]
- Obiettivo in 1–3 frasi: [...]
- Prerequisiti: [...]
- Uso IA: [nessuno / strumento usato e parti assistite]

## CONTENUTO PER GLI STUDENTI

### 1. Introduzione e obiettivo
[Testo essenziale; non ripetere il titolo.]

### 2. Concetti e metodo
[Spiegazione rigorosa basata sulle fonti fornite.]

### 3. Relazioni e simboli, se pertinenti
\[
[formula generale]
\]

| Simbolo | Significato | Unità |
|:---|:---|:---|
| \( ... \) | ... | ... |

[Condizioni di validità e ipotesi indispensabili accanto alla formula.]

### 4. Esempio svolto, se pertinente
**Dati assegnati:** [...]
**Da determinare:** [...]

#### Passaggio 1 — [titolo operativo]
**Metodo:** [Cosa fare e perché.]
**Calcoli:**
\[
[formula generale]
\]
\[
[sostituzione numerica]
\]
\[
[risultato con unità]
\]
**Controllo / note:** [Se necessari.]

#### Passaggio 2 — [titolo operativo]
**Metodo:** [...]
**Calcoli:**
\[
[calcolo]
\]
**Risultato:** [...]

### 5. Esercizi, se pertinenti
**Esercizio 1 — [titolo]**
**Traccia:** [Dati completi e richieste.]

#### Soluzione esercizio 1 — da mostrare chiusa nel sito
[Stessa struttura per passaggi: Metodo + Calcoli + Risultato.]

### 6. Sintesi / autocontrollo
[Controlli ragionati, non semplice ripetizione dei paragrafi.]

## SOLO REVISIONE EDITORIALE — NON COPIARE AUTOMATICAMENTE NEL SITO
ATTENZIONE: questa sezione non è riservata se viene inviata in una Issue pubblica.
Serve a distinguere note per il revisore da contenuto della lezione, non a proteggerle.

### Fonti effettivamente consultate
- [Titolo, autore/ente, edizione/data, pagina/sezione, URL se disponibile.]

### Ipotesi e dubbi ancora aperti
- [Indicare esplicitamente ciò che non è verificato.]

### Controlli numerici effettuati dall'autore
- [Elenco dei controlli; non scrivere «verificato» senza averlo fatto.]

### Materiali allegati
| File | Descrizione / uso | Testo alternativo | Provenienza e autorizzazione |
|:---|:---|:---|:---|
| [nome] | [esercizio / consultazione / grafico] | [...] | [...] |

### Conferme
- Ho riletto e controllato la proposta.
- Non sono inclusi dati personali di studenti o verifiche riservate.
- Autorizzo la revisione e l'eventuale pubblicazione del mio contributo su Aula Tecnica.
- Sono consapevole che la proposta e gli allegati GitHub sono pubblici prima della revisione.


---


# Proposta di attività pratica — [COMPONENTE / TITOLO]

## Scheda
- Versione template: 1.0
- Nome pubblico autore: [...]
- Anno e materia: [...]
- Percorso: Pratica — CAD e messa in tavola
- Categoria: [Alberi / Ruote dentate / Pulegge / altro componente / Assiemi e progetti]
- Obiettivo: [...]
- Prerequisiti: [...]
- Uso IA: [nessuno / impiego dichiarato]

## CONTENUTO PER GLI STUDENTI

### Obiettivo dell'attività
[Competenze da esercitare, senza tutorial dei comandi se il lavoro è autonomo.]

### Materiali di riferimento
Per ogni tavola indicare titolo, file allegato, descrizione, testo alternativo,
qualità/leggibilità e se costituisce esercizio quotato o scheda di consultazione.
Non imporre automaticamente lo svolgimento di tutte le tavole della raccolta.

### Proposte di esercitazione
**Tavola 1 — [titolo]**
[Componenti da modellare; viste/sezioni da leggere; richieste di documentazione.]

### Consegna
[Formato nativo del modello e della messa in tavola, PDF ed eventuale breve nota
sulle ipotesi; non aggiungere scadenze o richieste di assieme non assegnate.]

### Autocontrollo
[Geometria, quote, prescrizioni, corrispondenza modello/tavola, leggibilità e cartiglio.]

### Dati non definiti
[Chiarimenti da ottenere dal docente, senza dedurre misure dai pixel.]

## NOTE PER IL REVISORE
Queste note sono pubbliche se inviate su GitHub: non includere materiale riservato.
- Fonti e attribuzioni: [...]
- Autorizzazione alla diffusione dei materiali: [...]
- Eventuali richiami storici nelle tavole: [...]
- Parti da chiarire: [...]
- Autorizzo la revisione e l'eventuale pubblicazione su Aula Tecnica: [sì/no].
