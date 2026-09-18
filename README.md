# Pastafresca013 — download e aggiornamenti

Gestionale da installare e usare anche senza Internet. La versione **1.5.3 per Mac Apple Silicon (M1 e successivi)** collega l’eliminazione delle fatture al magazzino: annulla i carichi e rimuove i prodotti creati soltanto da fatture annullate, senza altre scorte o collegamenti. Conserva il logo ufficiale, ricette base riutilizzabili, grammi ed eliminazione protetta dei prodotti inutilizzati.

**[Scarica Pastafresca013 per Mac Apple Silicon](https://github.com/lorenzofulgosi92-ai/pastafresca013-aggiornamenti/releases/download/v1.5.3/Pastafresca013-1.5.3-mac-arm64.zip)**

[Dettagli e istruzioni della versione 1.5.3](https://github.com/lorenzofulgosi92-ai/pastafresca013-aggiornamenti/releases/tag/v1.5.3)

## Hai già la versione 1.4.2, 1.5.1 o 1.5.2?

Accedi come amministratore, apri **Impostazioni → Aggiorna** e segui la richiesta di riavvio. Il programma scarica la nuova versione, crea un backup e si riapre aggiornato. Non devi scaricare ZIP o sostituire manualmente l’app.

Il pacchetto da 779 MB mantiene assistente, PDF e OCR offline. Il precedente pacchetto 1.5.0 resta sospeso.

## Prima installazione o versioni precedenti alla 1.4.2

1. Se usi già una vecchia versione, crea un backup completo da Impostazioni e chiudi il programma.
2. Apri il file scaricato e sposta **Pastafresca013** nella cartella **Applicazioni**.
3. Apri il programma da Applicazioni. Gli account e l’archivio già presenti rimangono sul computer.

## Documenti e fatture

In **Documenti**, **Elimina** mostra i prodotti e le quantità coinvolti. Dopo conferma, sposta la fattura nel **Cestino**, annulla i suoi carichi e rimuove dal magazzino i prodotti creati soltanto da fatture annullate, senza altre scorte o collegamenti. Per prodotti preesistenti o usati altrove sottrae solo la quantità della fattura, conservando gli altri acquisti e i collegamenti. **Ripristina** recupera anche le quantità, con conferma e senza doppi carichi. Originali e movimenti rimangono consultabili nello storico.

Per le fatture già eliminate nella 1.5.2 usa **Documenti → Cestino → Rimuovi prodotti dal magazzino**. L’installazione non cambia automaticamente le scorte. Quantità insufficienti, inventari successivi o un prodotto omonimo al ripristino fermano l’operazione con un avviso preciso, senza modifiche parziali.

Da **Documenti → Carica fattura**, scegli PDF, scansioni o fotografie. Il riepilogo mostra prodotti caricati, quantità aggiunte e righe da verificare. Solo le righe che superano tutti i controlli aggiornano il magazzino: le altre mostrano originale, motivo e campi da correggere.

Per riprovare una fattura già salvata, aprila e scegli **Rileggi fattura**. Il comando è disponibile solo se non ci sono righe già caricate; sostituisce la lettura corrente e conserva quella precedente nello storico. Controlla e conferma l’intestazione proposta quando richiesto: un fornitore letto senza etichetta esplicita richiede verifica prima dei carichi.

La lettura comprende le tabelle PDF grafiche, le intestazioni italiane e olandesi, le confezioni esplicite e gli sconti verificabili. Il glossario alimentare controllato comprende italiano, olandese, inglese, francese, tedesco e spagnolo; parole o lingue sconosciute richiedono verifica manuale. Marchi, codici e nomi commerciali espliciti rimangono invariati. Le confezioni vengono convertite soltanto quando quantità e contenuti sono espliciti.

I carichi sono collegati a fattura e riga; i duplicati già elaborati non vengono caricati nuovamente, anche se il documento è nel cestino. Non usare questo flusso per merce già ricevuta tramite un ordine o movimento manuale.

## Aggiornamenti e verifiche

Serve Internet per cercare e scaricare aggiornamenti. Il lavoro nel gestionale, la lettura PDF e l’OCR restano disponibili offline.

Il pacchetto è firmato Developer ID, notarizzato da Apple e accettato da Gatekeeper. Firma del manifesto e integrità dello ZIP sono verificate prima dell’installazione. I 136 test del gestionale sono passati senza errori o esclusioni.

Il collaudo nativo completo ha verificato sostituzione e riapertura usando i moduli aggiornamento della 1.5.2, conservazione di archivio, accesso, documenti e backup fittizi e integrità di tutte le 274 risorse offline. Nel motore reale del programma, senza Internet, i due PDF grafici di prova hanno prodotto dieci righe ciascuno dopo la conferma del fornitore. Il PDF parzialmente illeggibile è passato all’OCR e ha lasciato entrambe le righe in attesa, senza carichi. Per entrambi i PDF grafici sono stati verificati anche rimozione dei dieci prodotti, annullamento delle quantità, ripristino esatto e protezione dai doppi invii.

Questa versione include soltanto Mac Apple Silicon. I nuovi installer Intel e Windows richiedono preparazione e collaudo.

I dati del ristorante, gli account locali e i backup non vengono caricati in questo repository. Le fatture vengono elaborate sul dispositivo. Gli installer sono allegati alle release.

Conservare le licenze di terze parti incluse nell’app. Built with Llama.
