<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T10:56:24+00:00",
  "source_file": "README.md",
  "language_code": "hu"
}
-->
# Localizeflow – Gyors kezdő útmutató

#### Támogatja a [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](./README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

A Localizeflow automatikusan lefordítja a dokumentációdat, és pull requesteket nyit, amikor a forrásfájl megváltozik.  
Ez az útmutató megmutatja, hogyan telepítsd a GitHub alkalmazást, és hogyan futtasd az első fordítást 2 percen belül.


> [!NOTE]
>
> A Localizeflow jelenleg GitHub-alapú dokumentációs projekteket támogat  
> (például: AI for Beginners és a legtöbb szabványos nyílt forráskódú repo).  
> 
> A modern dokumentációs keretrendszerek, mint az Astro, Docusaurus és Hugo támogatása  
> aktív fejlesztés alatt áll.


---

## Jelentkezz be és telepítsd a GitHub alkalmazást

1. Látogass el a **[localizeflow.com](https://localizeflow.com/)** oldalra.
2. Válaszd a **Start with free trial** lehetőséget.
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. Válaszd a **Sign in with GitHub** lehetőséget.  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. Jelentkezz be a GitHub fiókoddal.  
   ![GitHub login](/images/github-login.png)
5. Válaszd ki azt a fiókot, ahová telepíteni szeretnéd a Localizeflow GitHub alkalmazást — a személyes fiókodat vagy egy általad kezelt szervezetet.  
   ![Select account](/images/select-which-account-to-use.png)
6. Válaszd ki azokat a repozitóriumokat, amelyekhez a Localizeflownak hozzáférést szeretnél adni, majd válaszd a **Save** gombot.  
   ![Select repo and save](/images/select-repo-and-save.png)
7. Átirányítanak a Localizeflow kezdőlapjára.

> [!TIP]
> Ha később további repozitóriumokat szeretnél hozzáadni, válaszd ki a fiókodat a fejlécben, majd kattints a **+ Add more repositories** lehetőségre.  
> ![Add more repositories](/images/add-more-repo.png)

---

## Csatlakoztasd a repozitóriumaidat a Localizeflow-hoz

1. A Localizeflow kezdőlapján válaszd a **+ Connect repositories** lehetőséget.  
   ![Select connect repositories](/images/select-connect-repos.png)

2. Válaszd ki az egyik telepített repozitóriumot, amelyet csatlakoztatni szeretnél, majd válaszd a **Save** gombot.  
   ![Select repository](/images/select-repo.png)

3. A csatlakoztatott repozitóriumaid most megjelennek a Kezdőlap és a Repozitóriumok oldalon is.  
   ![Connected repositories](/images/repo-connected.png)

---

## Indítsd el az automatikus fordítást

1. Válaszd ki az imént csatlakoztatott repozitóriumot.  
   ![Select repository](/images/select-repo-to-detail.png)

2. A repozitórium részletező oldalán válaszd az alul található **Edit** gombot.  
   ![Select edit](/images/select-edit.png)

3. Állítsd be a fordítási beállításokat — célág (alapértelmezett: `main`), cél nyelvek és forrásnyelv (alapértelmezett: `en`). Válaszd a **Save** gombot.  
   ![Configure translation settings](/images/configuration.png)

4. Válaszd a **Start & Automate** lehetőséget.  
   A Localizeflow mostantól automatikusan lefordítja a dokumentációdat, és pull requesteket nyit, amikor a forrás megváltozik.  
   ![Start & Automate](/images/select-automate.png)