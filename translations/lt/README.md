# Localizeflow – Greito Pradžios Vadovas

#### Remia [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](./README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Norite klonuoti vietoje?**

> Ši saugykla apima daugiau nei 50 kalbų vertimus, kurie žymiai padidina atsisiuntimo dydį. Norėdami klonuoti be vertimų, naudokite ne visą atsisiuntimą (sparse checkout):
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tai suteiks jums viską, ko reikia kursui užbaigti, ir leis atsisiųsti daug greičiau.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow automatiškai verčia jūsų dokumentaciją ir atidaro pull request'us kiekvieną kartą, kai keičiasi šaltinio failas.  
Šis vadovas parodo, kaip įdiegti GitHub programėlę ir atlikti pirmąjį vertimą per mažiau nei 2 minutes.


> [!NOTE]
>
> Localizeflow šiuo metu palaiko dokumentacijos projektus, pagrįstus GitHub
> (pavyzdžiui: AI for Beginners ir dauguma standartinių atvirojo kodo saugyklų).  
> 
> Tolimesnis palaikymas šiuolaikiniams dokumentacijos karkasams, tokiems kaip Astro, Docusaurus ir Hugo,  
> yra aktyviame kūrime.


---

## Prisijunkite ir įdiekite GitHub programėlę

1. Apsilankykite **[localizeflow.com](https://localizeflow.com/)**.
2. Pasirinkite **Start with free trial**.
   ![Select Start with free trial](../../translated_images/lt/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Pasirinkite **Sign in with GitHub**.  
   ![Sign in with GitHub](../../translated_images/lt/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Prisijunkite su savo GitHub paskyra.  
   ![GitHub login](../../translated_images/lt/github-login.02bbaee0270b292e.webp)
5. Pasirinkite paskyrą, kurioje norite įdiegti Localizeflow GitHub programėlę — savo asmeninę paskyrą arba organizaciją, kuriai vadovaujate.  
   ![Select account](../../translated_images/lt/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Pasirinkite saugyklas, prie kurių Localizeflow turėtų turėti prieigą, tada pasirinkite **Save**.  
   ![Select repo and save](../../translated_images/lt/select-repo-and-save.5a95ae288aefec6e.webp)
7. Būsite nukreipti į Localizeflow pagrindinį puslapį.

> [!TIP]
> Norėdami vėliau pridėti daugiau saugyklų, pasirinkite savo paskyrą antraštėje ir pasirinkite **+ Add more repositories**.  
> ![Add more repositories](../../translated_images/lt/add-more-repo.2ca5154473aaaafb.webp)

---

## Prijunkite savo saugyklas prie Localizeflow

1. Localizeflow pagrindiniame puslapyje pasirinkite **+ Connect repositories**.  
   ![Select connect repositories](../../translated_images/lt/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Pasirinkite vieną iš įdiegtų saugyklų, kurias norite prijungti, ir pasirinkite **Save**.  
   ![Select repository](../../translated_images/lt/select-repo.dce94db722b44cf3.webp)

3. Jūsų prijungtos saugyklos dabar bus matomos tiek pagrindiniame puslapyje, tiek puslapyje Repositories.  
   ![Connected repositories](../../translated_images/lt/repo-connected.9e5c21ee789fdcaa.webp)

---

## Pradėkite automatinį vertimą

1. Pasirinkite ką tik prijungtą saugyklą.  
   ![Select repository](../../translated_images/lt/select-repo-to-detail.55e53233531f8518.webp)

2. Saugyklos detalės puslapyje apačioje pasirinkite **Edit**.  
   ![Select edit](../../translated_images/lt/select-edit.225184c8c46d7001.webp)

3. Konfigūruokite vertimo nustatymus — tikslinę šaką (numatytoji: `main`), tikslines kalbas ir šaltinio kalbą (numatytoji: `en`). Pasirinkite **Save**.  
   ![Configure translation settings](../../translated_images/lt/configuration.ab55d0f8bab5711b.webp)

4. Pasirinkite **Start & Automate**.  
   Localizeflow dabar automatiškai verčia jūsų dokumentaciją ir atidaro pull request'us kiekvieną kartą, kai keičiasi šaltinis.  
   ![Start & Automate](../../translated_images/lt/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Atsakomybės apribojimas**:
Šis dokumentas buvo išverstas naudojant dirbtinio intelekto vertimo paslaugą [Co-op Translator](https://github.com/Azure/co-op-translator). Nors stengiamės užtikrinti tikslumą, prašome atkreipti dėmesį, kad automatiniai vertimai gali turėti klaidų ar netikslumų. Originalus dokumentas jo gimtąja kalba laikomas autoritetingu šaltiniu. Kritinei informacijai rekomenduojama naudoti profesionalų žmogaus atliktą vertimą. Mes neatsakome už jokius nesusipratimus ar neteisingus aiškinimus, kylančius dėl šio vertimo naudojimo.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->