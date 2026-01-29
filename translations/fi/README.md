# Localizeflow – Pikakäyttöopas

#### Tuottaa [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](./README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Haluatko mieluummin kloonata paikallisesti?**

> Tässä arkistossa on yli 50 käännöstä, jotka lisäävät merkittävästi latauskokoa. Jos haluat kloonata ilman käännöksiä, käytä sparse checkout -toimintoa:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tämä antaa sinulle kaiken tarvittavan kurssin suorittamiseen huomattavasti nopeammalla latauksella.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow kääntää automaattisesti dokumentaation ja avaa pull requestit aina, kun lähdetiedosto muuttuu.  
Tämä opas näyttää, kuinka asennat GitHub-sovelluksen ja suoritat ensimmäisen käännöksesi alle kahdessa minuutissa.


> [!NOTE]
>
> Localizeflow tukee tällä hetkellä GitHub-pohjaisia dokumentaatioprojekteja
> (esimerkiksi: AI for Beginners ja useimmat tavalliset avoimen lähdekoodin repositoriot).  
> 
> Tuki moderneille dokumentaatiokehikoille kuten Astro, Docusaurus ja Hugo  
> on aktiivisessa kehityksessä.


---

## Kirjaudu sisään ja asenna GitHub-sovellus

1. Mene osoitteeseen **[localizeflow.com](https://localizeflow.com/)**.
2. Valitse **Start with free trial**.
   ![Select Start with free trial](../../../../translated images/fi/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Valitse **Sign in with GitHub**.  
   ![Sign in with GitHub](../../../../translated images/fi/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Kirjaudu sisään GitHub-tililläsi.  
   ![GitHub login](../../../../translated images/fi/github-login.02bbaee0270b292e.webp)
5. Valitse tili, johon haluat asentaa Localizeflow GitHub -sovelluksen — henkilökohtainen tilisi tai hallinnoimasi organisaatio.  
   ![Select account](../../../../translated images/fi/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Valitse repositoriot, joihin haluat Localizeflow'n pääsevän käsiksi, ja valitse sitten **Save**.  
   ![Select repo and save](../../../../translated images/fi/select-repo-and-save.5a95ae288aefec6e.webp)
7. Sinut ohjataan Localizeflow'n kotisivulle.

> [!TIP]
> Voit lisätä myöhemmin lisää repositorioita valitsemalla tilisi yläreunasta ja valitsemalla **+ Add more repositories**.  
> ![Add more repositories](../../../../translated images/fi/add-more-repo.2ca5154473aaaafb.webp)

---

## Yhdistä repositoriosi Localizeflow'hun

1. Localizeflow'n kotisivulla valitse **+ Connect repositories**.  
   ![Select connect repositories](../../../../translated images/fi/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Valitse yksi asennetuista reposta, jonka haluat yhdistää, ja valitse **Save**.  
   ![Select repository](../../../../translated images/fi/select-repo.dce94db722b44cf3.webp)

3. Yhdistetyt repositoriosi näkyvät nyt sekä kotisivulla että Repositories-sivulla.  
   ![Connected repositories](../../../../translated images/fi/repo-connected.9e5c21ee789fdcaa.webp)

---

## Aloita automaattinen käännös

1. Valitse juuri yhdistetty repositoriosi.  
   ![Select repository](../../../../translated images/fi/select-repo-to-detail.55e53233531f8518.webp)

2. Repostorion yksityiskohtasivulla valitse alhaalta **Edit**.  
   ![Select edit](../../../../translated images/fi/select-edit.225184c8c46d7001.webp)

3. Määritä käännösasetuksesi — kohdehaara (oletus: `main`), kohdekielet ja lähdekieli (oletus: `en`). Valitse **Save**.  
   ![Configure translation settings](../../../../translated images/fi/configuration.ab55d0f8bab5711b.webp)

4. Valitse **Start & Automate**.  
   Localizeflow alkaa nyt automaattisesti kääntää dokumentaatiosi ja avaa pull requestit aina, kun lähdetiedosto muuttuu.  
   ![Start & Automate](../../../../translated images/fi/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Vastuuvapauslauseke**:  
Tämä asiakirja on käännetty käyttämällä tekoälypohjaista käännöspalvelua [Co-op Translator](https://github.com/Azure/co-op-translator). Pyrimme tarkkuuteen, mutta huomioithan, että automaattikäännöksissä voi esiintyä virheitä tai epätarkkuuksia. Alkuperäinen asiakirja sen omalla kielellä on virallinen lähde. Tärkeissä tiedoissa suositellaan ammattimaista ihmis käännöstä. Emme ota vastuuta tämän käännöksen käytöstä johtuvista väärinkäsityksistä tai tulkinnoista.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->