# Localizeflow – Pikakäyttöopas

#### Tukee [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](./README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Haluatko kloonata paikallisesti?**

> Tämä arkisto sisältää yli 50 kielikäännöstä, mikä lisää lataustiedoston kokoa merkittävästi. Jos haluat kloonata ilman käännöksiä, käytä osittaista checkoutia:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Tämä antaa sinulle kaiken tarvitun kurssin suorittamiseen huomattavasti nopeammin.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow kääntää dokumentaation automaattisesti ja avaa vetopyynnöt aina, kun lähdetiedosto muuttuu.  
Tämä opas näyttää, miten asennat GitHub-sovelluksen ja suoritat ensimmäisen käännöksen alle kahdessa minuutissa.


> [!NOTE]
>
> Localizeflow tukee tällä hetkellä GitHub-pohjaisia dokumentaatioprojekteja
> (esimerkiksi: AI for Beginners ja useimmat vakiomuotoiset avoimen lähdekoodin repositoriot).  
> 
> Tuki nykyaikaisille dokumentaatiokehyksille, kuten Astro, Docusaurus ja Hugo,  
> on aktiivisessa kehityksessä.


---

## Kirjaudu sisään ja asenna GitHub-sovellus

1. Mene **[localizeflow.com](https://localizeflow.com/)**.
2. Valitse **Aloita ilmaisella kokeilulla**.
   ![Valitse Aloita ilmaisella kokeilulla](../../../../translated_images/fi/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Valitse **Kirjaudu sisään GitHubilla**.  
   ![Kirjaudu sisään GitHubilla](../../../../translated_images/fi/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Kirjaudu sisään GitHub-tililläsi.  
   ![GitHub-kirjautuminen](../../../../translated_images/fi/github-login.02bbaee0270b292e.webp)
5. Valitse tili, johon haluat asentaa Localizeflow GitHub -sovelluksen — henkilökohtainen tilisi tai hallinnoimasi organisaatio.  
   ![Valitse tili](../../../../translated_images/fi/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Valitse ne repositoriot, joihin Localizeflow saa pääsyn, ja valitse sitten **Tallenna**.  
   ![Valitse repo ja tallenna](../../../../translated_images/fi/select-repo-and-save.5a95ae288aefec6e.webp)
7. Sinut ohjataan Localizeflow:n kotisivulle.

> [!TIP]
> Jos haluat lisätä myöhemmin lisää repositorioita, valitse otsikosta tilisi ja valitse **+ Lisää lisää repositorioita**.  
> ![Lisää lisää repositorioita](../../../../translated_images/fi/add-more-repo.2ca5154473aaaafb.webp)

---

## Yhdistä repositoriot Localizeflow'hun

1. Localizeflow:n kotisivulla valitse **+ Yhdistä repositoriot**.  
   ![Valitse yhdistä repositoriot](../../../../translated_images/fi/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Valitse yksi asennetuista repositorioista, jonka haluat yhdistää, ja valitse **Tallenna**.  
   ![Valitse repositorio](../../../../translated_images/fi/select-repo.dce94db722b44cf3.webp)

3. Yhdistetyt repositoriot näkyvät nyt sekä Kotisivulla että Repositoriot-sivulla.  
   ![Yhdistetyt repositoriot](../../../../translated_images/fi/repo-connected.9e5c21ee789fdcaa.webp)

---

## Aloita automaattinen käännös

1. Valitse juuri yhdistämäsi repositorio.  
   ![Valitse repositorio](../../../../translated_images/fi/select-repo-to-detail.55e53233531f8518.webp)

2. Repositoriokohtaisella sivulla valitse **Muokkaa** alhaalla.  
   ![Valitse muokkaa](../../../../translated_images/fi/select-edit.225184c8c46d7001.webp)

3. Määritä käännösasetukset — kohdehaara (oletus: `main`), kohdekielet ja lähdekieli (oletus: `en`). Valitse **Tallenna**.  
   ![Määritä käännösasetukset](../../../../translated_images/fi/configuration.ab55d0f8bab5711b.webp)

4. Valitse **Aloita ja automatisoi**.  
   Localizeflow kääntää nyt dokumentaation automaattisesti ja avaa vetopyynnöt aina, kun lähde muuttuu.  
   ![Aloita ja automatisoi](../../../../translated_images/fi/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Vastuuvapauslauseke**:  
Tämä asiakirja on käännetty käyttäen tekoälykäännöspalvelua [Co-op Translator](https://github.com/Azure/co-op-translator). Vaikka pyrimme tarkkuuteen, huomioithan, että automaattikäännöksissä saattaa esiintyä virheitä tai epätarkkuuksia. Alkuperäinen asiakirja sen alkuperäiskielellä on määräävä lähde. Tärkeiden tietojen osalta suositellaan ammattimaista ihmiskäännöstä. Emme ole vastuussa tämän käännöksen käytöstä mahdollisesti aiheutuvista väärinkäsityksistä tai virhetulkintojen seurauksista.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->