# Localizeflow – Rychlý průvodce

#### Podporováno [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](./README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Raději klonovat lokálně?**

> Tento repozitář obsahuje přes 50 jazykových překladů, což výrazně zvětšuje velikost stahování. Pro klonování bez překladů použijte sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tím získáte vše potřebné pro dokončení kurzu s mnohem rychlejším stažením.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow automaticky překládá vaši dokumentaci a otevírá pull requesty kdykoli se změní zdrojový soubor.  
Tento průvodce vám ukáže, jak nainstalovat GitHub App a spustit svůj první překlad během 2 minut.


> [!NOTE]
>
> Localizeflow momentálně podporuje dokumentační projekty založené na GitHubu
> (například: AI for Beginners a většinu standardních open-source repozitářů).  
> 
> Podpora moderních dokumentačních frameworků jako Astro, Docusaurus a Hugo  
> je aktivně vyvíjena.


---

## Přihlaste se a nainstalujte GitHub App

1. Navštivte **[localizeflow.com](https://localizeflow.com/)**.
2. Zvolte **Start with free trial**.
   ![Select Start with free trial](../../../../translated images/cs/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Vyberte **Sign in with GitHub**.  
   ![Sign in with GitHub](../../../../translated images/cs/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Přihlaste se pomocí svého GitHub účtu.  
   ![GitHub login](../../../../translated images/cs/github-login.02bbaee0270b292e.webp)
5. Vyberte účet, na který chcete nainstalovat Localizeflow GitHub App — váš osobní účet nebo některou organizaci, kterou spravujete.  
   ![Select account](../../../../translated images/cs/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Vyberte repozitáře, ke kterým chcete, aby měl Localizeflow přístup, a poté zvolte **Save**.  
   ![Select repo and save](../../../../translated images/cs/select-repo-and-save.5a95ae288aefec6e.webp)
7. Budete přesměrováni na domovskou stránku Localizeflow.

> [!TIP]
> Pro přidání dalších repozitářů později vyberte svůj účet v záhlaví a zvolte **+ Add more repositories**.  
> ![Add more repositories](../../../../translated images/cs/add-more-repo.2ca5154473aaaafb.webp)

---

## Připojte své repozitáře k Localizeflow

1. Na domovské stránce Localizeflow vyberte **+ Connect repositories**.  
   ![Select connect repositories](../../../../translated images/cs/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Vyberte jeden z nainstalovaných repozitářů, které chcete připojit, a zvolte **Save**.  
   ![Select repository](../../../../translated images/cs/select-repo.dce94db722b44cf3.webp)

3. Vaše připojené repozitáře se nyní zobrazí jak na domovské stránce, tak na stránce Repositories.  
   ![Connected repositories](../../../../translated images/cs/repo-connected.9e5c21ee789fdcaa.webp)

---

## Spusťte automatický překlad

1. Vyberte repozitář, který jste právě připojili.  
   ![Select repository](../../../../translated images/cs/select-repo-to-detail.55e53233531f8518.webp)

2. Na detailní stránce repozitáře vyberte dole **Edit**.  
   ![Select edit](../../../../translated images/cs/select-edit.225184c8c46d7001.webp)

3. Nakonfigurujte nastavení překladu — cílovou větev (výchozí: `main`), cílové jazyky a zdrojový jazyk (výchozí: `en`). Zvolte **Save**.  
   ![Configure translation settings](../../../../translated images/cs/configuration.ab55d0f8bab5711b.webp)

4. Vyberte **Start & Automate**.  
   Localizeflow nyní automaticky překládá vaši dokumentaci a otevírá pull requesty vždy, když dojde ke změně zdroje.  
   ![Start & Automate](../../../../translated images/cs/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Prohlášení o vyloučení odpovědnosti**:  
Tento dokument byl přeložen pomocí AI překladatelské služby [Co-op Translator](https://github.com/Azure/co-op-translator). Přestože usilujeme o přesnost, vezměte prosím na vědomí, že automatické překlady mohou obsahovat chyby nebo nepřesnosti. Originální dokument v jeho mateřském jazyce by měl být považován za závazný zdroj. Pro kritické informace je doporučován profesionální lidský překlad. Nejsme odpovědní za jakékoliv nedorozumění nebo nesprávné výklady vyplývající z použití tohoto překladu.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->