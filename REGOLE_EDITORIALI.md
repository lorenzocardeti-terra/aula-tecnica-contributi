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
