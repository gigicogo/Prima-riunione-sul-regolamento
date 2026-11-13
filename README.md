# La prima riunione sull’IA

Un’attività di avvio per il corso IA del Comune di Genova. Il partecipante prepara una **proposta di mandato da discutere con chi decide**, scegliendo quattro formulazioni e affrontando un imprevisto. La modalità iniziale è individuale; si può scegliere anche il lavoro in gruppi di 4–5.

Durata: **10 minuti di lavoro**, poi confronto in aula. Per la restituzione è disponibile un timer separato da 60 secondi.

## Che cosa cambia nella versione 2

- Alternative plausibili, con più formulazioni valide e risposte parzialmente adeguate.
- Motivazione finale breve, da leggere con il docente.
- Criticità separate dal punteggio: un 23/25 può ancora richiedere il riesame della gestione dell’imprevisto.
- Prime decisioni registrate conservate insieme alle revisioni.
- Timer automatico, pausa e ripresa. Il tempo guida non blocca la consegna.
- Imprevisto dopo cinque minuti di tempo attivo, oppure prima se si completano le quattro decisioni.
- Salvataggio nel browser e ripresa dopo un aggiornamento della pagina.
- Scheda HTML stampabile, copia completa della proposta, esportazione Markdown e JSON.

## Provarla

Apri `index.html` in un browser moderno. Non occorrono installazioni, servizi IA, chiavi API o account. La pagina è autosufficiente e funziona anche offline. Le risposte non sono inviate al docente: indica ai partecipanti il canale del corso per restituire la scheda.

Il salvataggio dipende dalle impostazioni del browser. Per un uso in aula uniforme è preferibile l’indirizzo GitHub Pages; scaricare la scheda resta il modo per conservare e restituire il risultato.

## Aggiornare il sito esistente su GitHub Pages

Repository di riferimento: https://github.com/gigicogo/Prima-riunione-sul-regolamento

1. Sostituisci **`index.html`** nella cartella principale del repository con quello contenuto in questo pacchetto.
2. Puoi aggiornare anche il `README.md` con questo testo.
3. Attendi la conclusione della pubblicazione di GitHub Pages, quindi riapri il sito con un aggiornamento completo della pagina.

L’indirizzo pubblico resta quello del repository: https://gigicogo.github.io/Prima-riunione-sul-regolamento/

Se GitHub Pages non è ancora configurato: **Settings → Pages → Deploy from a branch → main → /(root) → Save**.

Conserva **`docente/GUIDA_DOCENTE.html`** fuori dal repository pubblico destinato ai partecipanti: contiene le soluzioni e la lettura del punteggio. Come per ogni applicazione statica, il codice e i criteri di valutazione restano tecnicamente ispezionabili; questa è un’attività didattica guidata, non una piattaforma per esami sorvegliati.

## Il contesto

L’ente fittizio ha già un ambiente istituzionale autorizzato per testi pubblici, ma non ha ancora ricostruito tutti gli altri utilizzi dell’IA. La direzione chiede una proposta per i primi trenta giorni. I funzionari preparano gli elementi e rendono visibili le decisioni aperte; autorizzare nuovi impieghi e adottare le regole spetta ai soggetti competenti.

L’imprevisto riguarda un documento interno già inserito in un chatbot non autorizzato. Il partecipante deve distinguere gestione immediata dell’evento e lavoro sulle regole, senza dichiarare automaticamente una violazione o considerare risolto il problema con la cancellazione della chat.

Tutti i fatti e gli uffici del caso sono fittizi. Non descrivono strumenti, procedure o incidenti reali del Comune di Genova. Le condizioni dell’ambiente sono una premessa del laboratorio, non un’autorizzazione per impieghi reali.

## Dati e scheda finale

Il codice o alias è facoltativo. I progressi restano nel browser, con una chiave distinta da quella della precedente applicazione e dalle altre esercitazioni del corso. Un nuovo tentativo sostituisce quello conservato per questa versione: scarica prima la scheda se vuoi mantenerlo.

La scheda comprende proposta, due risposte all’imprevisto, motivazione, questione aperta, profilo, criticità aperte e recuperate, prime decisioni e revisioni. Il docente valuta il significato della motivazione: il software ne controlla soltanto la compilazione minima.

## Progetto

Pagina statica in un solo HTML, con CSS e JavaScript incorporati e nessuna dipendenza di rete per il funzionamento. Le modifiche a questa versione sono predisposte come file da caricare sul repository; il pacchetto non pubblica automaticamente il sito.

Ideazione didattica: **Gianluigi Cogo**. Versione **2.0.0**, 12 novembre 2026.
