# Localizeflow – Kiirjuhend

#### Toetatud [Localizeflow](https://localizeflow.com/) poolt

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](./README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Eelistad kloonimist lokaalselt?**

> See hoidla sisaldab üle 50 keele tõlget, mis suurendab oluliselt allalaadimise mahtu. Tõlgeteta kloonimiseks kasuta sparsent väljavõtet:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> See annab sulle kõik vajaliku kursuse lõpetamiseks palju kiiremalt.

<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow tõlgib sinu dokumentatsiooni automaatselt ning avab pull requeste iga kord, kui algfail muutub.  
See juhend näitab, kuidas paigaldada GitHubi rakendus ja käivitada esimene tõlge vähem kui 2 minutiga.


> [!NOTE]
>
> Localizeflow toetab hetkel GitHubi-põhiseid dokumentatsiooniprojekte  
> (näiteks: AI for Beginners ja enamik standardseid avatud lähtekoodiga hoidlaid).  
> 
> Toetust kaasaegsetele dokumentatsiooniraamistikule nagu Astro, Docusaurus ja Hugo  
> arendatakse aktiivselt.


---

## Logi sisse ja paigalda GitHubi rakendus

1. Mine aadressile **[localizeflow.com](https://localizeflow.com/)**.
2. Vali **Start with free trial**.  
   ![Select Start with free trial](../../translated_images/et/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Vali **Sign in with GitHub**.  
   ![Sign in with GitHub](../../translated_images/et/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Logi sisse oma GitHubi kontoga.  
   ![GitHub login](../../translated_images/et/github-login.02bbaee0270b292e.webp)
5. Vali konto, kuhu soovid Localizeflow GitHubi rakenduse installida — kas isiklik konto või organisatsioon, mida haldad.  
   ![Select account](../../translated_images/et/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Vali hoidlad, millele soovid Localizeflow'l ligipääsu anda, seejärel vali **Save**.  
   ![Select repo and save](../../translated_images/et/select-repo-and-save.5a95ae288aefec6e.webp)
7. Sind suunatakse tagasi Localizeflow avalehele.

> [!TIP]
> Hiljem saab juurde lisada hoidlasi, valides oma konto päises ja klõpsates **+ Add more repositories**.  
> ![Add more repositories](../../translated_images/et/add-more-repo.2ca5154473aaaafb.webp)

---

## Ühenda oma hoidlad Localizeflow'ga

1. Localizeflow avalehel vali **+ Connect repositories**.  
   ![Select connect repositories](../../translated_images/et/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Vali üks paigaldatud hoidlatest, mida soovid ühendada, ja vali **Save**.  
   ![Select repository](../../translated_images/et/select-repo.dce94db722b44cf3.webp)

3. Ühendatud hoidlad kuvatakse nüüd nii Avalehel kui ka Hoidlate lehel.  
   ![Connected repositories](../../translated_images/et/repo-connected.9e5c21ee789fdcaa.webp)

---

## Alusta automaatset tõlget

1. Vali äsja ühendatud hoidla.  
   ![Select repository](../../translated_images/et/select-repo-to-detail.55e53233531f8518.webp)

2. Hoidla detaillehel vali allosas **Edit**.  
   ![Select edit](../../translated_images/et/select-edit.225184c8c46d7001.webp)

3. Sea oma tõlkesätted — sihtharu (vaikimisi: `main`), sihtkeeled ja lähtekeel (vaikimisi: `en`). Vali **Save**.  
   ![Configure translation settings](../../translated_images/et/configuration.ab55d0f8bab5711b.webp)

4. Vali **Start & Automate**.  
   Localizeflow hakkab nüüd sinu dokumentatsiooni automaatselt tõlkima ja avab pull requeste iga kord, kui algfail muutub.  
   ![Start & Automate](../../translated_images/et/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Vastutusest loobumine**:
See dokument on tõlgitud tehisintellekti tõlke teenuse [Co-op Translator](https://github.com/Azure/co-op-translator) abil. Kuigi püüame tagada täpsust, palun arvestage, et automatiseeritud tõlked võivad sisaldada vigu või ebatäpsusi. Originaaldokument algkeeles tuleb pidada autoriteetseks allikaks. Olulise teabe puhul soovitatakse kasutada professionaalset inimtõlget. Me ei vastuta ühegi arusaamatuse või väärinterpreteerimise eest, mis võivad tuleneda selle tõlke kasutamisest.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->