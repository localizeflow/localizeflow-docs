# Localizeflow – Guida rapida

#### Supportato da [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](./README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Preferisci clonare localmente?**

> Questo repository include traduzioni in oltre 50 lingue che aumentano significativamente la dimensione del download. Per clonare senza traduzioni, usa sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Questo ti dà tutto il necessario per completare il corso con un download molto più veloce.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow traduce automaticamente la tua documentazione e apre pull request ogni volta che il file sorgente cambia.  
Questa guida ti mostra come installare l'app GitHub e avviare la tua prima traduzione in meno di 2 minuti.


> [!NOTE]
>
> Localizeflow supporta attualmente progetti di documentazione basati su GitHub  
> (per esempio: AI for Beginners e la maggior parte dei repository open-source standard).  
> 
> Il supporto per framework di documentazione moderni come Astro, Docusaurus e Hugo  
> è in fase di sviluppo attivo.


---

## Accedi e installa l'app GitHub

1. Visita **[localizeflow.com](https://localizeflow.com/)**.
2. Seleziona **Inizia con la prova gratuita**.
   ![Seleziona Inizia con la prova gratuita](../../../../translated images/it/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Seleziona **Accedi con GitHub**.  
   ![Accedi con GitHub](../../../../translated images/it/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Accedi con il tuo account GitHub.  
   ![Accesso GitHub](../../../../translated images/it/github-login.02bbaee0270b292e.webp)
5. Scegli l'account su cui vuoi installare l'app Localizeflow GitHub — il tuo account personale o un'organizzazione che gestisci.  
   ![Seleziona account](../../../../translated images/it/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Seleziona i repository a cui vuoi che Localizeflow acceda, quindi scegli **Salva**.  
   ![Seleziona repository e salva](../../../../translated images/it/select-repo-and-save.5a95ae288aefec6e.webp)
7. Verrai reindirizzato alla pagina principale di Localizeflow.

> [!TIP]
> Per aggiungere più repository in seguito, seleziona il tuo account nell'intestazione e scegli **+ Aggiungi altri repository**.  
> ![Aggiungi altri repository](../../../../translated images/it/add-more-repo.2ca5154473aaaafb.webp)

---

## Collega i tuoi repository a Localizeflow

1. Nella pagina principale di Localizeflow, seleziona **+ Collega repository**.  
   ![Seleziona collega repository](../../../../translated images/it/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Scegli uno dei repository installati che vuoi collegare e seleziona **Salva**.  
   ![Seleziona repository](../../../../translated images/it/select-repo.dce94db722b44cf3.webp)

3. I tuoi repository collegati appariranno ora sia nella pagina Home che nella pagina Repository.  
   ![Repository collegati](../../../../translated images/it/repo-connected.9e5c21ee789fdcaa.webp)

---

## Avvia la traduzione automatica

1. Seleziona il repository che hai appena collegato.  
   ![Seleziona repository](../../../../translated images/it/select-repo-to-detail.55e53233531f8518.webp)

2. Nella pagina dei dettagli del repository, seleziona **Modifica** in fondo.  
   ![Seleziona modifica](../../../../translated images/it/select-edit.225184c8c46d7001.webp)

3. Configura le impostazioni di traduzione — branch di destinazione (default: `main`), lingue di destinazione e lingua di origine (default: `en`). Seleziona **Salva**.  
   ![Configura impostazioni di traduzione](../../../../translated images/it/configuration.ab55d0f8bab5711b.webp)

4. Seleziona **Avvia e automatizza**.  
   Localizeflow tradurrà automaticamente la tua documentazione e aprirà pull request ogni volta che la sorgente cambia.  
   ![Avvia e automatizza](../../../../translated images/it/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Disclaimer**:
Questo documento è stato tradotto utilizzando il servizio di traduzione automatica [Co-op Translator](https://github.com/Azure/co-op-translator). Pur impegnandoci per garantire l’accuratezza, si prega di notare che le traduzioni automatiche possono contenere errori o inesattezze. Il documento originale nella sua lingua nativa deve essere considerato la fonte autorevole. Per informazioni critiche, si raccomanda una traduzione professionale effettuata da un traduttore umano. Non ci assumiamo alcuna responsabilità per eventuali malintesi o interpretazioni errate derivanti dall’uso di questa traduzione.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->