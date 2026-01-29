# Localizeflow – Greito pradžios vadovas

#### Palaikoma [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](./README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Norite klonuoti lokaliai?**

> Šiame saugykloje yra daugiau nei 50 kalbų vertimų, todėl atsisiuntimo dydis žymiai padidėja. Norėdami klonuoti be vertimų, naudokite ribotą atsisiuntimą (sparse checkout):
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tai suteikia viską, ko reikia kursui užbaigti, su daug greitesniu atsisiuntimu.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow automatiškai išverčia jūsų dokumentaciją ir sukuria pull užklausas, kai tik keičiasi šaltinio failas.  
Šis vadovas parodo, kaip įdiegti GitHub programėlę ir atlikti pirmą vertimą per mažiau nei 2 minutes.


> [!NOTE]
>
> Šiuo metu Localizeflow palaiko dokumentacijos projektus, pagrįstus GitHub
> (pavyzdžiui: AI for Beginners ir dauguma standartinių atvirojo kodo saugyklų).  
> 
> Palaikymas modernioms dokumentacijos sistemoms, tokioms kaip Astro, Docusaurus ir Hugo,  
> yra aktyvioje kūrimo stadijoje.


---

## Prisijunkite ir įdiekite GitHub programėlę

1. Aplankykite **[localizeflow.com](https://localizeflow.com/)**.
2. Pasirinkite **Start with free trial**.
   ![Pasirinkite Start with free trial](../../../../translated images/lt/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Pasirinkite **Sign in with GitHub**.  
   ![Prisijungti per GitHub](../../../../translated images/lt/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Prisijunkite naudodami savo GitHub paskyrą.  
   ![GitHub prisijungimas](../../../../translated images/lt/github-login.02bbaee0270b292e.webp)
5. Pasirinkite paskyrą, kurioje norite įdiegti Localizeflow GitHub programėlę — savo asmeninę paskyrą arba organizaciją, kuriai vadovaujate.  
   ![Pasirinkite paskyrą](../../../../translated images/lt/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Pasirinkite saugyklas, prie kurių norite suteikti Localizeflow prieigą, tada pasirinkite **Save**.  
   ![Pasirinkite saugyklą ir išsaugokite](../../../../translated images/lt/select-repo-and-save.5a95ae288aefec6e.webp)
7. Būsite nukreipti į Localizeflow pagrindinį puslapį.

> [!TIP]
> Norėdami vėliau pridėti daugiau saugyklų, pasirinkite savo paskyrą antraštėje ir pasirinkite **+ Add more repositories**.  
> ![Pridėti daugiau saugyklų](../../../../translated images/lt/add-more-repo.2ca5154473aaaafb.webp)

---

## Prijunkite savo saugyklas prie Localizeflow

1. Localizeflow pagrindiniame puslapyje pasirinkite **+ Connect repositories**.  
   ![Pasirinkite prijungti saugyklas](../../../../translated images/lt/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Pasirinkite vieną iš įdiegtų saugyklų, kurias norite prijungti, ir spauskite **Save**.  
   ![Pasirinkite saugyklą](../../../../translated images/lt/select-repo.dce94db722b44cf3.webp)

3. Jūsų prijungtos saugyklos dabar bus matomos tiek pagrindiniame, tiek Saugyklų puslapyje.  
   ![Prijungtos saugyklos](../../../../translated images/lt/repo-connected.9e5c21ee789fdcaa.webp)

---

## Pradėkite automatinį vertimą

1. Pasirinkite ką tik prijungtą saugyklą.  
   ![Pasirinkite saugyklą](../../../../translated images/lt/select-repo-to-detail.55e53233531f8518.webp)

2. Saugyklos detalių puslapyje pasirinkite **Edit** apačioje.  
   ![Pasirinkite redaguoti](../../../../translated images/lt/select-edit.225184c8c46d7001.webp)

3. Suformuokite vertimo nustatymus — tikslinį šaką (numatytoji: `main`), tikslines kalbas ir šaltinio kalbą (numatytoji: `en`). Paspauskite **Save**.  
   ![Suformuokite vertimo nustatymus](../../../../translated images/lt/configuration.ab55d0f8bab5711b.webp)

4. Paspauskite **Start & Automate**.  
   Localizeflow dabar automatiškai išvers jūsų dokumentaciją ir sukurs pull užklausas, kai tik keisis šaltinis.  
   ![Start & Automate](../../../../translated images/lt/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Atsakomybės atsisakymas**:
Šis dokumentas buvo išverstas naudojant dirbtinio intelekto vertimo paslaugą [Co-op Translator](https://github.com/Azure/co-op-translator). Nors siekiame tikslumo, prašome atkreipti dėmesį, kad automatizuoti vertimai gali turėti klaidų ar netikslumų. Originalus dokumentas jo gimtąja kalba turi būti laikomas autoritetingu šaltiniu. Kritiniais atvejais rekomenduojamas profesionalus žmogaus atliktas vertimas. Mes neprisiimame atsakomybės už bet kokius nesusipratimus ar klaidingas interpretacijas, kylančias iš šio vertimo naudojimo.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->