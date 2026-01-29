# Localizeflow – Quick Start Guide

#### Ondersteund door [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](./README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Lokale kloon liever?**

> Deze repository bevat meer dan 50 vertaallingen, waardoor de downloadgrootte aanzienlijk toeneemt. Om te klonen zonder vertalingen, gebruik sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Hiermee krijg je alles wat je nodig hebt om de cursus te voltooien met een veel snellere download.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow vertaalt je documentatie automatisch en opent pull requests telkens wanneer het bronbestand verandert.  
Deze gids laat je zien hoe je de GitHub App installeert en je eerste vertaling uitvoert in minder dan 2 minuten.


> [!NOTE]
>
> Localizeflow ondersteunt momenteel documentatieprojecten op basis van GitHub
> (bijvoorbeeld: AI for Beginners en de meeste standaard open-source repositories).  
> 
> Ondersteuning voor moderne documentatiekaders zoals Astro, Docusaurus en Hugo  
> is in actieve ontwikkeling.


---

## Aanmelden en de GitHub App installeren

1. Bezoek **[localizeflow.com](https://localizeflow.com/)**.
2. Selecteer **Begin met gratis proefperiode**.
   ![Select Start with free trial](../../../../translated_images/nl/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Selecteer **Aanmelden met GitHub**.  
   ![Sign in with GitHub](../../../../translated_images/nl/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Meld je aan met je GitHub-account.  
   ![GitHub login](../../../../translated_images/nl/github-login.02bbaee0270b292e.webp)
5. Kies het account waarop je de Localizeflow GitHub App wilt installeren — je persoonlijke account of een organisatie die je beheert.  
   ![Select account](../../../../translated_images/nl/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Selecteer de repositories waar Localizeflow toegang toe moet krijgen en kies vervolgens **Opslaan**.  
   ![Select repo and save](../../../../translated_images/nl/select-repo-and-save.5a95ae288aefec6e.webp)
7. Je wordt doorgestuurd naar de startpagina van Localizeflow.

> [!TIP]
> Om later meer repositories toe te voegen, selecteer je je account in de header en kies je **+ Meer repositories toevoegen**.  
> ![Add more repositories](../../../../translated_images/nl/add-more-repo.2ca5154473aaaafb.webp)

---

## Verbind je repositories met Localizeflow

1. Selecteer op de startpagina van Localizeflow **+ Verbind repositories**.  
   ![Select connect repositories](../../../../translated_images/nl/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Kies een van de geïnstalleerde repositories die je wilt verbinden en selecteer **Opslaan**.  
   ![Select repository](../../../../translated_images/nl/select-repo.dce94db722b44cf3.webp)

3. Je verbonden repositories verschijnen nu zowel op de startpagina als op de pagina Repositories.  
   ![Connected repositories](../../../../translated_images/nl/repo-connected.9e5c21ee789fdcaa.webp)

---

## Begin met automatische vertaling

1. Selecteer de repository die je zojuist hebt verbonden.  
   ![Select repository](../../../../translated_images/nl/select-repo-to-detail.55e53233531f8518.webp)

2. Selecteer op de detailpagina van de repository onderaan **Bewerken**.  
   ![Select edit](../../../../translated_images/nl/select-edit.225184c8c46d7001.webp)

3. Stel je vertaalsinstellingen in — doeltak (standaard: `main`), doeltalen en brontaal (standaard: `en`). Selecteer **Opslaan**.  
   ![Configure translation settings](../../../../translated_images/nl/configuration.ab55d0f8bab5711b.webp)

4. Selecteer **Start & Automate**.  
   Localizeflow zal nu je documentatie automatisch vertalen en pull requests openen wanneer de bron verandert.  
   ![Start & Automate](../../../../translated_images/nl/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Disclaimer**:  
Dit document is vertaald met behulp van de AI-vertalingsdienst [Co-op Translator](https://github.com/Azure/co-op-translator). Hoewel we streven naar nauwkeurigheid, kan de automatische vertaling fouten of onnauwkeurigheden bevatten. Het originele document in de oorspronkelijke taal dient als gezaghebbende bron te worden beschouwd. Voor belangrijke informatie wordt professionele menselijke vertaling aanbevolen. Wij zijn niet aansprakelijk voor eventuele misverstanden of verkeerde interpretaties die voortvloeien uit het gebruik van deze vertaling.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->