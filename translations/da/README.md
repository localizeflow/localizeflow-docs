# Localizeflow – Kom hurtigt i gang guide

#### Understøttet af [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](./README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Foretrækker du at klone lokalt?**

> Dette repository inkluderer 50+ sprogoversættelser, hvilket markant øger downloadstørrelsen. For at klone uden oversættelser, brug sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Dette giver dig alt, du behøver for at gennemføre kurset med en meget hurtigere download.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow oversætter automatisk din dokumentation og åbner pull requests, hver gang kildefilen ændres.  
Denne guide viser dig, hvordan du installerer GitHub-appen og kører din første oversættelse på under 2 minutter.


> [!NOTE]
>
> Localizeflow understøtter i øjeblikket GitHub-baserede dokumentationsprojekter
> (for eksempel: AI for Beginners og de fleste standard open source repos).  
> 
> Support for moderne dokumentationsframeworks som Astro, Docusaurus og Hugo  
> er under aktiv udvikling.


---

## Log ind og installér GitHub App'en

1. Besøg **[localizeflow.com](https://localizeflow.com/)**.
2. Vælg **Start with free trial**.
   ![Vælg Start with free trial](../../../../translated_images/da/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Vælg **Sign in with GitHub**.  
   ![Log ind med GitHub](../../../../translated_images/da/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Log ind med din GitHub-konto.  
   ![GitHub login](../../../../translated_images/da/github-login.02bbaee0270b292e.webp)
5. Vælg den konto, hvor du vil installere Localizeflow GitHub App'en — din personlige konto eller en organisation, du administrerer.  
   ![Vælg konto](../../../../translated_images/da/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Vælg de repositories, som Localizeflow skal have adgang til, og vælg derefter **Save**.  
   ![Vælg repo og gem](../../../../translated_images/da/select-repo-and-save.5a95ae288aefec6e.webp)
7. Du vil blive omdirigeret til Localizeflow startside.

> [!TIP]
> For at tilføje flere repositories senere, vælg din konto i toppen og vælg **+ Add more repositories**.  
> ![Tilføj flere repositories](../../../../translated_images/da/add-more-repo.2ca5154473aaaafb.webp)

---

## Forbind dine repositories til Localizeflow

1. På Localizeflow startside, vælg **+ Connect repositories**.  
   ![Vælg connect repositories](../../../../translated_images/da/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Vælg et af de installerede repositories, du vil forbinde, og vælg **Save**.  
   ![Vælg repository](../../../../translated_images/da/select-repo.dce94db722b44cf3.webp)

3. Dine tilknyttede repositories vil nu fremgå på både start- og repositories-siden.  
   ![Tilknyttede repositories](../../../../translated_images/da/repo-connected.9e5c21ee789fdcaa.webp)

---

## Start automatisk oversættelse

1. Vælg det repository, du netop har tilknyttet.  
   ![Vælg repository](../../../../translated_images/da/select-repo-to-detail.55e53233531f8518.webp)

2. På repository-detaljesiden, vælg **Edit** nederst.  
   ![Vælg edit](../../../../translated_images/da/select-edit.225184c8c46d7001.webp)

3. Konfigurer dine oversættelsesindstillinger — målgren (standard: `main`), målsprog og kildesprog (standard: `en`). Vælg **Save**.  
   ![Konfigurer oversættelsesindstillinger](../../../../translated_images/da/configuration.ab55d0f8bab5711b.webp)

4. Vælg **Start & Automate**.  
   Localizeflow vil nu automatisk oversætte din dokumentation og åbne pull requests, hver gang kildeteksten ændres.  
   ![Start & Automate](../../../../translated_images/da/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Ansvarsfraskrivelse**:  
Dette dokument er blevet oversat ved hjælp af AI-oversættelsestjenesten [Co-op Translator](https://github.com/Azure/co-op-translator). Selvom vi bestræber os på nøjagtighed, skal du være opmærksom på, at automatiske oversættelser kan indeholde fejl eller unøjagtigheder. Det oprindelige dokument på dets modersmål bør betragtes som den autoritative kilde. For kritisk information anbefales professionel menneskelig oversættelse. Vi påtager os intet ansvar for misforståelser eller fejltolkninger, der måtte opstå som følge af brugen af denne oversættelse.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->