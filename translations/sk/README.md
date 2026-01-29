# Localizeflow – Rýchly sprievodca

#### Podporované spoločnosťou [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](./README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Radšej klonovať lokálne?**

> Tento repozitár obsahuje viac ako 50 jazykových prekladov, čo výrazne zvyšuje veľkosť sťahovania. Ak chcete klonovať bez prekladov, použite sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Toto vám poskytne všetko potrebné na dokončenie kurzu s oveľa rýchlejším sťahovaním.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow automaticky prekladá vašu dokumentáciu a otvára pull requesty vždy, keď sa zdrojový súbor zmení.  
Tento sprievodca vám ukáže, ako nainštalovať GitHub App a spustiť váš prvý preklad za menej ako 2 minúty.

> [!NOTE]
> 
> Localizeflow momentálne podporuje dokumentačné projekty založené na GitHub (napríklad: AI for Beginners a väčšina štandardných open-source repozitárov).  
> 
> Podpora pre moderné dokumentačné rámce ako Astro, Docusaurus a Hugo je momentálne vo vývoji.

---

## Prihláste sa a nainštalujte GitHub App

1. Navštívte **[localizeflow.com](https://localizeflow.com/)**.
2. Vyberte **Začať s bezplatnou skúšobnou verziou**.  
   ![Vyberte Začať s bezplatnou skúšobnou verziou](../../../../translated images/sk/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Vyberte **Prihlásiť sa cez GitHub**.  
   ![Prihlásiť sa cez GitHub](../../../../translated images/sk/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Prihláste sa pomocou vášho GitHub účtu.  
   ![Prihlásenie GitHub](../../../../translated images/sk/github-login.02bbaee0270b292e.webp)
5. Vyberte účet, kde chcete nainštalovať Localizeflow GitHub App — váš osobný účet alebo organizáciu, ktorú spravujete.  
   ![Vyberte účet](../../../../translated images/sk/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Vyberte repozitáre, ku ktorým chcete Localizeflow povoliť prístup, potom kliknite na **Uložiť**.  
   ![Vyberte repozitár a uložte](../../../../translated images/sk/select-repo-and-save.5a95ae288aefec6e.webp)
7. Budete presmerovaní na úvodnú stránku Localizeflow.

> [!TIP]
> Ak chcete neskôr pridať ďalšie repozitáre, vyberte svoj účet v hlavičke a zvoľte **+ Pridať ďalšie repozitáre**.  
> ![Pridať ďalšie repozitáre](../../../../translated images/sk/add-more-repo.2ca5154473aaaafb.webp)

---

## Pripojte vaše repozitáre k Localizeflow

1. Na domovskej stránke Localizeflow vyberte **+ Pripojiť repozitáre**.  
   ![Vyberte pripojiť repozitáre](../../../../translated images/sk/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Vyberte jeden z nainštalovaných repozitárov, ktorý chcete pripojiť, a kliknite na **Uložiť**.  
   ![Vyberte repozitár](../../../../translated images/sk/select-repo.dce94db722b44cf3.webp)

3. Vaše pripojené repozitáre sa teraz zobrazia na domovskej stránke aj na stránke Repozitáre.  
   ![Pripojené repozitáre](../../../../translated images/sk/repo-connected.9e5c21ee789fdcaa.webp)

---

## Spustite automatický preklad

1. Vyberte práve pripojený repozitár.  
   ![Vyberte repozitár](../../../../translated images/sk/select-repo-to-detail.55e53233531f8518.webp)

2. Na detailnej stránke repozitára vyberte **Upraviť** v spodnej časti.  
   ![Vyberte upraviť](../../../../translated images/sk/select-edit.225184c8c46d7001.webp)

3. Nakonfigurujte nastavenia prekladu — cieľovú vetvu (štandardne: `main`), cieľové jazyky a zdrojový jazyk (štandardne: `en`). Kliknite na **Uložiť**.  
   ![Nakonfigurujte nastavenia prekladu](../../../../translated images/sk/configuration.ab55d0f8bab5711b.webp)

4. Vyberte **Spustiť a automatizovať**.  
   Localizeflow teraz automaticky preloží vašu dokumentáciu a otvorí pull requesty vždy, keď sa zdroj zmení.  
   ![Spustiť a automatizovať](../../../../translated images/sk/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Zrieknutie sa zodpovednosti**:  
Tento dokument bol preložený pomocou AI prekladateľskej služby [Co-op Translator](https://github.com/Azure/co-op-translator). Aj keď sa snažíme o presnosť, berte, prosím, na vedomie, že automatizované preklady môžu obsahovať chyby alebo nepresnosti. Pôvodný dokument v jeho mateřskom jazyku by mal byť považovaný za autoritatívny zdroj. Pre kritické informácie sa odporúča profesionálny ľudský preklad. Nie sme zodpovední za žiadne nedorozumenia alebo nesprávne interpretácie vyplývajúce z použitia tohto prekladu.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->