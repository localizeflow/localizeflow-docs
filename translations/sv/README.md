# Localizeflow – Snabbstartguide

#### Stöds av [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](./README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Föredrar du att klona lokalt?**

> Detta arkiv innehåller 50+ språköversättningar vilket avsevärt ökar nedladdningsstorleken. För att klona utan översättningar, använd sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Detta ger dig allt du behöver för att slutföra kursen med en mycket snabbare nedladdning.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow översätter automatiskt din dokumentation och öppnar pull requests varje gång källfilen ändras.  
Denna guide visar hur du installerar GitHub-appen och startar din första översättning på mindre än 2 minuter.


> [!NOTE]
>
> Localizeflow stöder för närvarande GitHub-baserade dokumentationsprojekt  
> (till exempel: AI for Beginners och de flesta standard open-source repos).  
> 
> Stöd för moderna dokumentationsramverk som Astro, Docusaurus och Hugo  
> är under aktiv utveckling.


---

## Logga in och installera GitHub-appen

1. Besök **[localizeflow.com](https://localizeflow.com/)**.
2. Välj **Börja med gratis provperiod**.
   ![Select Start with free trial](../../../../translated images/sv/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Välj **Logga in med GitHub**.  
   ![Sign in with GitHub](../../../../translated images/sv/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Logga in med ditt GitHub-konto.  
   ![GitHub login](../../../../translated images/sv/github-login.02bbaee0270b292e.webp)
5. Välj det konto där du vill installera Localizeflow GitHub-appen — ditt personliga konto eller en organisation du administrerar.  
   ![Select account](../../../../translated images/sv/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Välj de repositories som du vill att Localizeflow ska få åtkomst till, och välj sedan **Spara**.  
   ![Select repo and save](../../../../translated images/sv/select-repo-and-save.5a95ae288aefec6e.webp)
7. Du kommer att omdirigeras till Localizeflows startsida.

> [!TIP]
> För att lägga till fler repositories senare, välj ditt konto i sidhuvudet och välj **+ Lägg till fler repositories**.  
> ![Add more repositories](../../../../translated images/sv/add-more-repo.2ca5154473aaaafb.webp)

---

## Anslut dina repositories till Localizeflow

1. På Localizeflows startsida väljer du **+ Anslut repositories**.  
   ![Select connect repositories](../../../../translated images/sv/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Välj en av de installerade repositories du vill ansluta och välj **Spara**.  
   ![Select repository](../../../../translated images/sv/select-repo.dce94db722b44cf3.webp)

3. Dina anslutna repositories kommer nu att visas både på startsidan och på sidan för repositories.  
   ![Connected repositories](../../../../translated images/sv/repo-connected.9e5c21ee789fdcaa.webp)

---

## Starta automatisk översättning

1. Välj repositoryt som du just anslöt.  
   ![Select repository](../../../../translated images/sv/select-repo-to-detail.55e53233531f8518.webp)

2. På repositories detaljsida väljer du **Redigera** längst ned.  
   ![Select edit](../../../../translated images/sv/select-edit.225184c8c46d7001.webp)

3. Konfigurera dina översättningsinställningar — målblansch (standard: `main`), målspråk och källspråk (standard: `en`). Välj **Spara**.  
   ![Configure translation settings](../../../../translated images/sv/configuration.ab55d0f8bab5711b.webp)

4. Välj **Starta & Automatisera**.  
   Localizeflow kommer nu automatiskt att översätta din dokumentation och öppna pull requests varje gång källfilen ändras.  
   ![Start & Automate](../../../../translated images/sv/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Ansvarsfriskrivning**:
Detta dokument har översatts med hjälp av AI-översättningstjänsten [Co-op Translator](https://github.com/Azure/co-op-translator). Även om vi strävar efter noggrannhet, var god observera att automatiska översättningar kan innehålla fel eller brister. Det ursprungliga dokumentet på dess modersmål bör betraktas som den auktoritativa källan. För viktig information rekommenderas professionell mänsklig översättning. Vi ansvarar inte för några missförstånd eller feltolkningar som kan uppstå vid användning av denna översättning.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->