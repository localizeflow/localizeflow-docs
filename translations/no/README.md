# Localizeflow – Rask startguide

#### Støttet av [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](./README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Foretrekker du å klone lokalt?**

> Dette depotet inkluderer over 50 språköversettelser som øker nedlastingsstørrelsen betydelig. For å klone uten oversettelser, bruk sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Dette gir deg alt du trenger for å fullføre kurset med mye raskere nedlasting.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow oversetter automatisk dokumentasjonen din og åpner pull-forespørsler når kildfilen endres.  
Denne guiden viser deg hvordan du installerer GitHub-appen og kjører din første oversettelse på under 2 minutter.


> [!NOTE]
>
> Localizeflow støtter for øyeblikket dokumentasjonsprosjekter basert på GitHub  
> (for eksempel: AI for Beginners og de fleste standard åpen kildekode-repoer).  
> 
> Støtte for moderne dokumentasjonsrammeverk som Astro, Docusaurus og Hugo  
> er under aktiv utvikling.


---

## Logg inn og installer GitHub-appen

1. Besøk **[localizeflow.com](https://localizeflow.com/)**.
2. Velg **Start med gratis prøveperiode**.
   ![Select Start with free trial](../../../../translated images/no/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Velg **Logg inn med GitHub**.  
   ![Sign in with GitHub](../../../../translated images/no/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Logg inn med GitHub-kontoen din.  
   ![GitHub login](../../../../translated images/no/github-login.02bbaee0270b292e.webp)
5. Velg konto der du vil installere Localizeflow GitHub-appen — din personlige konto eller en organisasjon du administrerer.  
   ![Select account](../../../../translated images/no/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Velg repositoryene du vil at Localizeflow skal ha tilgang til, og velg deretter **Lagre**.  
   ![Select repo and save](../../../../translated images/no/select-repo-and-save.5a95ae288aefec6e.webp)
7. Du vil bli omdirigert til Localizeflow sin hjemmesiden.

> [!TIP]
> For å legge til flere repositoryer senere, velg kontoen din i overskriften og velg **+ Legg til flere repositoryer**.  
> ![Add more repositories](../../../../translated images/no/add-more-repo.2ca5154473aaaafb.webp)

---

## Koble repositoryene dine til Localizeflow

1. På Localizeflow sin hjemmeside, velg **+ Koble til repositoryer**.  
   ![Select connect repositories](../../../../translated images/no/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Velg et av de installerte repositoryene du vil koble til og velg **Lagre**.  
   ![Select repository](../../../../translated images/no/select-repo.dce94db722b44cf3.webp)

3. Dine tilkoblede repositoryer vises nå både på Hjem-siden og på Repository-siden.  
   ![Connected repositories](../../../../translated images/no/repo-connected.9e5c21ee789fdcaa.webp)

---

## Start automatisk oversettelse

1. Velg repositoryen du nettopp koblet til.  
   ![Select repository](../../../../translated images/no/select-repo-to-detail.55e53233531f8518.webp)

2. På detaljsiden for repositoryen, velg **Rediger** nederst.  
   ![Select edit](../../../../translated images/no/select-edit.225184c8c46d7001.webp)

3. Konfigurer oversettelsesinnstillingene dine — målgren (standard: `main`), målspråk og kildespråk (standard: `en`). Velg **Lagre**.  
   ![Configure translation settings](../../../../translated images/no/configuration.ab55d0f8bab5711b.webp)

4. Velg **Start & Automatiser**.  
   Localizeflow vil nå automatisk oversette dokumentasjonen din og åpne pull-forespørsler når kilden endres.  
   ![Start & Automate](../../../../translated images/no/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Ansvarsfraskrivelse**:
Dette dokumentet er oversatt ved hjelp av AI-oversettelsestjenesten [Co-op Translator](https://github.com/Azure/co-op-translator). Selv om vi streber etter nøyaktighet, vennligst vær oppmerksom på at automatiserte oversettelser kan inneholde feil eller unøyaktigheter. Det originale dokumentet på opprinnelig språk bør betraktes som den autoritative kilden. For kritisk informasjon anbefales profesjonell menneskelig oversettelse. Vi er ikke ansvarlige for eventuelle misforståelser eller feiltolkninger som følge av bruk av denne oversettelsen.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->