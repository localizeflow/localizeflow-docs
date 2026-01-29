# Localizeflow – Kiire algusjuhend

#### Toetatud [Localizeflow](https://localizeflow.com/) poolt

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](./README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Eelistad kloonimist lokaalselt?**

> See hoidla sisaldab 50+ keele tõlget, mis suurendab oluliselt allalaadimise mahtu. Tõlgeteta kloonimiseks kasuta sparse checkout'i:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> See annab sulle kõik vajaliku kursuse läbimiseks palju kiirema allalaadimisega.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow tõlgib automaatselt sinu dokumentatsiooni ja avab pull requeste iga kord, kui lähtefaili muudetakse.  
See juhend näitab sulle, kuidas installida GitHubi rakendus ja teha oma esimene tõlge vähem kui kahe minutiga.


> [!NOTE]
>
> Localizeflow toetab praegu GitHubi-põhiseid dokumentatsiooniprojekte  
> (näiteks: AI for Beginners ja enamik standardsest avatud lähtekoodiga hoidlatest).  
>  
> Toetus kaasaegsetele dokumentatsiooniraamistikele nagu Astro, Docusaurus ja Hugo  
> on aktiivses arenduses.


---

## Logi sisse ja installi GitHubi rakendus

1. Mine aadressile **[localizeflow.com](https://localizeflow.com/)**.
2. Vali **Alusta tasuta prooviperioodiga**.  
   ![Vali Alusta tasuta prooviperioodiga](../../../../translated images/et/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Vali **Logi sisse GitHubiga**.  
   ![Logi sisse GitHubiga](../../../../translated images/et/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Logi sisse oma GitHubi kontoga.  
   ![GitHubi sisselogimine](../../../../translated images/et/github-login.02bbaee0270b292e.webp)
5. Vali konto, kuhu soovid Localizeflow GitHubi rakenduse installida — oma isiklik konto või organisatsioon, mida haldad.  
   ![Vali konto](../../../../translated images/et/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Vali hoidlad, millele soovid Localizeflow'l ligipääsu anda, seejärel klõpsa **Salvesta**.  
   ![Vali hoidla ja salvesta](../../../../translated images/et/select-repo-and-save.5a95ae288aefec6e.webp)
7. Sind suunatakse Localizeflow avalehele.

> [!TIP]
> Hiljem rohkemate hoidlate lisamiseks vali ülemises ribas oma konto ja vali **+ Lisa rohkem hoidlaid**.  
> ![Lisa rohkem hoidlaid](../../../../translated images/et/add-more-repo.2ca5154473aaaafb.webp)

---

## Ühenda oma hoidlad Localizeflow'ga

1. Localizeflow avalehel vali **+ Ühenda hoidlad**.  
   ![Vali Ühenda hoidlad](../../../../translated images/et/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Vali üks juba installitud hoidlatest, mida soovid ühendada, ja vali **Salvesta**.  
   ![Vali hoidla](../../../../translated images/et/select-repo.dce94db722b44cf3.webp)

3. Sinu ühendatud hoidlad kuvatakse nüüd nii avalehel kui ka hoidlates lehel.  
   ![Ühendatud hoidlad](../../../../translated images/et/repo-connected.9e5c21ee789fdcaa.webp)

---

## Alusta automaatset tõlget

1. Vali hoidla, mille just ühendasid.  
   ![Vali hoidla](../../../../translated images/et/select-repo-to-detail.55e53233531f8518.webp)

2. Hoidla detailide lehel klõpsa allosas **Muuda**.  
   ![Vali muuda](../../../../translated images/et/select-edit.225184c8c46d7001.webp)

3. Sea oma tõlkesätted — sihtharu (vaikimisi: `main`), sihtkeeled ja lähtekeel (vaikimisi: `en`). Vali **Salvesta**.  
   ![Seadista tõlkesätted](../../../../translated images/et/configuration.ab55d0f8bab5711b.webp)

4. Vali **Alusta ja automatiseeri**.  
   Localizeflow hakkab nüüd automaatselt tõlkima sinu dokumentatsiooni ja avab pull requestid iga kord, kui lähtefail muutub.  
   ![Alusta ja automatiseeri](../../../../translated images/et/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Vastutusest loobumine**:
See dokument on tõlgitud AI tõlketeenuse [Co-op Translator](https://github.com/Azure/co-op-translator) abil. Kuigi püüame tagada täpsust, palun pidage meeles, et automatiseeritud tõlked võivad sisaldada vigu või ebatäpsusi. Originaaldokument selle emakeeles tuleks lugeda autoriteetseks allikaks. Tähtsa teabe puhul soovitame kasutada professionaalset inimtõlget. Me ei vastuta selle tõlke kasutamisest tulenevate arusaamatuste ega valesti mõistmiste eest.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->