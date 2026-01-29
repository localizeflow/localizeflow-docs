# Localizeflow – Hitri vodič za začetek

#### Podprto s strani [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](./README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Raje klonirati lokalno?**

> Ta repozitorij vključuje več kot 50 jezikovnih prevodov, kar precej poveča velikost prenosa. Če želite klonirati brez prevodov, uporabite sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tako prejmete vse, kar potrebujete za dokončanje tečaja, z veliko hitrejšim prenosom.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow samodejno prevaja vašo dokumentacijo in odpre pull requeste ob vsaki spremembi izvorne datoteke.  
Ta vodič vam pokaže, kako namestiti aplikacijo GitHub in zagnati vaš prvi prevod v manj kot 2 minutah.


> [!NOTE]
>
> Localizeflow trenutno podpira dokumentacijske projekte, ki temeljijo na GitHubu  
> (na primer: AI for Beginners in večina standardnih odprtokodnih repozitorijev).  
> 
> Podpora za moderne dokumentacijske okvire, kot so Astro, Docusaurus in Hugo,  
> je v aktivnem razvoju.


---

## Prijava in namestitev aplikacije GitHub

1. Obiščite **[localizeflow.com](https://localizeflow.com/)**.  
2. Izberite **Start with free trial**.  
   ![Izberite Start with free trial](../../../../translated images/sl/select-start-with-free-trial.6c2e287133ff9c8b.webp)  
3. Izberite **Sign in with GitHub**.  
   ![Prijava z GitHub](../../../../translated images/sl/select-sign-in-with-github.f2850ffdd49cc894.webp)  
4. Prijavite se z vašim GitHub računom.  
   ![GitHub prijava](../../../../translated images/sl/github-login.02bbaee0270b292e.webp)  
5. Izberite račun, kjer želite namestiti aplikacijo Localizeflow na GitHubu — vaš osebni račun ali organizacijo, ki jo upravljate.  
   ![Izberite račun](../../../../translated images/sl/select-which-account-to-use.7050f5ed0b773bb0.webp)  
6. Izberite repozitorije, do katerih želite, da ima Localizeflow dostop, nato kliknite **Save**.  
   ![Izberite repozitorij in shrani](../../../../translated images/sl/select-repo-and-save.5a95ae288aefec6e.webp)  
7. Preusmerjeni boste na domačo stran Localizeflow.

> [!TIP]
> Če želite kasneje dodati več repozitorijev, izberite vaš račun v glavi in izberite **+ Add more repositories**.  
> ![Dodaj več repozitorijev](../../../../translated images/sl/add-more-repo.2ca5154473aaaafb.webp)

---

## Povežite vaše repozitorije z Localizeflow

1. Na domači strani Localizeflow izberite **+ Connect repositories**.  
   ![Izberite connect repositories](../../../../translated images/sl/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Izberite enega izmed nameščenih repozitorijev, ki jih želite povezati, in kliknite **Save**.  
   ![Izberite repozitorij](../../../../translated images/sl/select-repo.dce94db722b44cf3.webp)

3. Vaši povezani repozitoriji se bodo zdaj prikazali tako na domači strani kot na strani Repozitoriji.  
   ![Povezani repozitoriji](../../../../translated images/sl/repo-connected.9e5c21ee789fdcaa.webp)

---

## Začetek samodejnega prevajanja

1. Izberite repozitorij, ki ste ga pravkar povezali.  
   ![Izberite repozitorij](../../../../translated images/sl/select-repo-to-detail.55e53233531f8518.webp)

2. Na strani z informacijami o repozitoriju izberite **Edit** na dnu strani.  
   ![Izberite Edit](../../../../translated images/sl/select-edit.225184c8c46d7001.webp)

3. Nastavite vaše prevajalske nastavitve — ciljno vejo (privzeto: `main`), ciljne jezike in izvorni jezik (privzeto: `en`). Izberite **Save**.  
   ![Nastavitev prevajalskih možnosti](../../../../translated images/sl/configuration.ab55d0f8bab5711b.webp)

4. Izberite **Start & Automate**.  
   Localizeflow bo zdaj samodejno prevajal vašo dokumentacijo in odpiral pull requeste vsakič, ko se izvorna datoteka spremeni.  
   ![Start & Automate](../../../../translated images/sl/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Omejitev odgovornosti**:  
Ta dokument je bil preveden z uporabo storitve za avtomatski prevod AI [Co-op Translator](https://github.com/Azure/co-op-translator). Čeprav si prizadevamo za natančnost, vas opozarjamo, da avtomatizirani prevodi lahko vsebujejo napake ali netočnosti. Izvirni dokument v maternem jeziku velja za verodostojen vir. Za pomembne informacije priporočamo strokovni človeški prevod. Ne odgovarjamo za morebitne nesporazume ali napačne interpretacije, ki izhajajo iz uporabe tega prevoda.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->