# Localizeflow – விரைவு தொடக்கக் கையேடு

#### [Localizeflow](https://localizeflow.com/) வழங்குகிறது

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](./README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **உள்ளகமாக கிளோன் செய்வதற்கு விருப்பமா?**

> இந்த தொகுப்பு 50+ மொழி மொழிபெயர்ப்புகளை உட்படுத்துகிறது, இது பதிவிறக்க அளவை மிகவும் அதிகரிக்கிறது. மொழிபெயர்ப்புகள் இல்லாமல் கிளோன் செய்ய sparse checkout-ஐ பயன்படுத்தவும்:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> இது நீங்கள் படிப்பை முடிக்க தேவையுள்ள அனைத்தையும் அதிக வேக பதிவிறக்கம் மூலம் தருகிறது.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow தானாகவே உங்கள் ஆவணங்களை மொழிபெயர்க்கிறது மற்றும் மூல கோப்பு மாற்றப்படும் போது புல் கோரிக்கைகளைத் திறக்கிறது.  
இந்த கையேடு GitHub செயலியை நிறுவுதல் மற்றும் உங்கள் முதல் மொழிபெயர்ப்பை 2 நிமிடங்களில் எப்படி இயக்குவது என்பதை காட்டுகிறது.


> [!NOTE]
>
> Localizeflow தற்பொழுது GitHub அடிப்படையிலான ஆவண திட்டங்களை ஆதரிக்கிறது
> (உதாரணமாக: AI for Beginners மற்றும் பல பொதுவான திறந்த மூல சேமிப்பகங்கள்).  
> 
> Astro, Docusaurus, மற்றும் Hugo போன்ற நவீன ஆவண கட்டமைப்புகளுக்கான ஆதரவு  
> தற்பொழுது செயலில் உள்ளது.


---

## GitHub செயலியில் உள்நுழைந்து நிறுவவும்

1. **[localizeflow.com](https://localizeflow.com/)** ஐ பார்வையிடவும்.
2. **Start with free trial** ஐ தேர்வுசெய்க.
   ![Select Start with free trial](../../../../translated images/ta/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **Sign in with GitHub** ஐ தேர்வுசெய்க.  
   ![Sign in with GitHub](../../../../translated images/ta/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. உங்கள் GitHub கணக்கில் உள்நுழைக.  
   ![GitHub login](../../../../translated images/ta/github-login.02bbaee0270b292e.webp)
5. Localizeflow GitHub செயலியை நிறுவ நீங்கள் விரும்பும் கணக்கை தேர்வு செய்யவும் — உங்கள் தனிப்பட்ட கணக்கு அல்லது நீங்கள் நிர்வகிக்கும் நிறுவனம்.  
   ![Select account](../../../../translated images/ta/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflow அணுக விரும்பும் சேமிப்பகங்களைத் தேர்வு செய்து **Save** என்பதை தேர்ந்தெடுக்கவும்.  
   ![Select repo and save](../../../../translated images/ta/select-repo-and-save.5a95ae288aefec6e.webp)
7. நீங்கள் Localizeflow முகப்பு பக்கத்துக்கு மறுவழிப்பயணம் செய்யபடுவீர்கள்.

> [!TIP]
> பிறகு சேமிப்பகங்களைச் சேர்க்க, தலைப்புப் பகுதியில் உங்கள் கணக்கைத் தேர்வு செய்து **+ Add more repositories** என்பதை தேர்ந்தெடுக்கவும்.  
> ![Add more repositories](../../../../translated images/ta/add-more-repo.2ca5154473aaaafb.webp)

---

## உங்கள் சேமிப்பகங்களை Localizeflow-க்கு இணைக்கவும்

1. Localizeflow முகப்பு பக்கத்தில் **+ Connect repositories** ஐ தேர்வுசெய்க.  
   ![Select connect repositories](../../../../translated images/ta/select-connect-repos.8ac6f96f77dcc62c.webp)

2. நீங்கள் இணைக்க விரும்பும் நிறுவப்பட்ட சேமிப்பகங்களில் ஒன்றைத் தேர்ந்தெடுத்து **Save** ஐ அழுத்தவும்.  
   ![Select repository](../../../../translated images/ta/select-repo.dce94db722b44cf3.webp)

3. உங்கள் இணைக்கப்பட்ட சேமிப்பகங்கள் இப்பொழுது முகப்பு பக்கம் மற்றும் சேமிப்பகங்கள் பக்கத்தில் காணப்படும்.  
   ![Connected repositories](../../../../translated images/ta/repo-connected.9e5c21ee789fdcaa.webp)

---

## தானியங்கி மொழிபெயர்ப்பைத் தொடங்கவும்

1. நீங்கள் இ刚刚 இணைத்த சேமிப்பகத்தைத் தேர்வு செய்க.  
   ![Select repository](../../../../translated images/ta/select-repo-to-detail.55e53233531f8518.webp)

2. சேமிப்பக விவரக் கோப்பில் கீழே உள்ள **Edit** ஐ தேர்வுசெய்க.  
   ![Select edit](../../../../translated images/ta/select-edit.225184c8c46d7001.webp)

3. உங்கள் மொழிபெயர்ப்பு அமைப்புகளை அமைக்கவும் — இலக்கு கிளை (இயல்புநிலை: `main`), இலக்கு மொழிகள் மற்றும் மூல மொழி (இயல்புநிலை: `en`). **Save** ஐத் தேர்ந்தெடுக்கவும்.  
   ![Configure translation settings](../../../../translated images/ta/configuration.ab55d0f8bab5711b.webp)

4. **Start & Automate** ஐ தேர்வுசெய்க.  
   Localizeflow இப்போது தானாகவே உங்கள் ஆவணங்களை மொழிபெயர்த்தும், மூல மாற்றம் ஏற்பட்டால் புல் கோரிக்கைகள் திறக்கும்.  
   ![Start & Automate](../../../../translated images/ta/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**தவிர்க்கூறுதல்**:  
இந்த ஆவணம் AI மொழிபெயர்ப்பு சேவை [Co-op Translator](https://github.com/Azure/co-op-translator) பயன்படுத்தி மொழிபெயர்க்கப்பட்டுள்ளது. நாங்கள் துல்லியத்தை உறுதி செய்ய முயற்சித்தாலும், இயந்திர மொழிபெயர்ப்புகளில் பிழைகள் அல்லது தவறுகள் இருக்கக்கூடும் என்பதை நினைவில் கொள்ளவும். முதன்மை ஆவணம் அதன் சொந்த மொழியில் தான் அதிகாரப்பூர்வமான ஆதாரமாக கருதப்பட வேண்டும். முக்கிய தகவல்களுக்கு, தொழில்முறை மனித மொழிபெயர்ப்பு பரிந்துரைக்கப்படுகிறது. இந்த மொழிபெயர்ப்பின் பயன்பாட்டால் ஏற்படும் எந்த தவறானப் புரிதல்கள் அல்லது தவறான விளக்கங்களுக்கு நாங்கள் பொறுப்பு ஏற்கவில்லை.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->