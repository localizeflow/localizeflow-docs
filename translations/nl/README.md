# Localizeflow – Quick Start Guide

#### Ondersteund door [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](./README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Liever lokaal clonen?**

> Deze repository bevat meer dan 50 taalvertalingen, wat de downloadgrootte aanzienlijk vergroot. Om te clonen zonder vertalingen, gebruik sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Dit geeft je alles wat je nodig hebt om de cursus te voltooien met een veel snellere download.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow vertaalt automatisch je documentatie en opent pull requests wanneer het bronbestand wijzigt.  
Deze gids laat je zien hoe je de GitHub-app installeert en je eerste vertaling uitvoert in minder dan 2 minuten.


> [!NOTE]
>
> Localizeflow ondersteunt momenteel GitHub-gebaseerde documentatieprojecten  
> (bijvoorbeeld: AI for Beginners en de meeste standaard open source repos).  
> 
> Ondersteuning voor moderne documentatiekaders zoals Astro, Docusaurus en Hugo  
> is in actieve ontwikkeling.


---

## Meld je aan en installeer de GitHub-app

1. Bezoek **[localizeflow.com](https://localizeflow.com/)**.
2. Selecteer **Start met gratis proefperiode**.
   ![Select Start with free trial](../../../../translated images/nl/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Selecteer **Aanmelden met GitHub**.  
   ![Sign in with GitHub](../../../../translated images/nl/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Meld je aan met je GitHub-account.  
   ![GitHub login](../../../../translated images/nl/github-login.02bbaee0270b292e.webp)
5. Kies het account waarop je de Localizeflow GitHub-app wilt installeren — je persoonlijke account of een organisatie die je beheert.  
   ![Select account](../../../../translated images/nl/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Selecteer de repositories waartoe je wilt dat Localizeflow toegang heeft en kies vervolgens **Opslaan**.  
   ![Select repo and save](../../../../translated images/nl/select-repo-and-save.5a95ae288aefec6e.webp)
7. Je wordt doorgestuurd naar de Localizeflow-startpagina.

> [!TIP]
> Om later meer repositories toe te voegen, selecteer je je account in de header en kies je **+ Meer repositories toevoegen**.  
> ![Add more repositories](../../../../translated images/nl/add-more-repo.2ca5154473aaaafb.webp)

---

## Verbind je repositories met Localizeflow

1. Selecteer op de Localizeflow-startpagina **+ Repositories verbinden**.  
   ![Select connect repositories](../../../../translated images/nl/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Kies een van de geïnstalleerde repositories die je wilt verbinden en selecteer **Opslaan**.  
   ![Select repository](../../../../translated images/nl/select-repo.dce94db722b44cf3.webp)

3. Je verbonden repositories verschijnen nu op zowel de Startpagina als de Pagina Repositories.  
   ![Connected repositories](../../../../translated images/nl/repo-connected.9e5c21ee789fdcaa.webp)

---

## Start automatische vertaling

1. Selecteer de repository die je zojuist verbonden hebt.  
   ![Select repository](../../../../translated images/nl/select-repo-to-detail.55e53233531f8518.webp)

2. Selecteer op de detailpagina van de repository onderaan **Bewerken**.  
   ![Select edit](../../../../translated images/nl/select-edit.225184c8c46d7001.webp)

3. Configureer je vertalingsinstellingen — doelbranch (standaard: `main`), doeltalen en brontaal (standaard: `en`). Selecteer **Opslaan**.  
   ![Configure translation settings](../../../../translated images/nl/configuration.ab55d0f8bab5711b.webp)

4. Selecteer **Start & Automate**.  
   Localizeflow zal nu automatisch je documentatie vertalen en pull requests openen wanneer de bron verandert.  
   ![Start & Automate](../../../../translated images/nl/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Disclaimer**:
Dit document is vertaald met behulp van de AI-vertalingsdienst [Co-op Translator](https://github.com/Azure/co-op-translator). Hoewel we streven naar nauwkeurigheid, dient u er rekening mee te houden dat automatische vertalingen fouten of onnauwkeurigheden kunnen bevatten. Het originele document in de oorspronkelijke taal moet als de gezaghebbende bron worden beschouwd. Voor cruciale informatie wordt professionele menselijke vertaling aanbevolen. Wij zijn niet aansprakelijk voor enige misverstanden of verkeerde interpretaties die voortvloeien uit het gebruik van deze vertaling.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->