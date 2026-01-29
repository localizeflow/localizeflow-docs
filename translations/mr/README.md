# Localizeflow – जलद प्रारंभ मार्गदर्शक

#### [Localizeflow](https://localizeflow.com/) द्वारे समर्थित

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](./README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **स्थानिक प्रतिकृती प्राधान्य देता?**

> या रेपॉजिटरीमध्ये ५०+ भाषा भाषांतरांचा समावेश आहे ज्यामुळे डाउनलोडचा आकार स्पष्टपणे वाढतो. भाषांतरांशिवाय क्लोन करण्यासाठी, sparse checkout वापरा:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> यामुळे आपल्याला कोर्स पूर्ण करण्यासाठी आवश्यक असलेले सर्वकाही खूप जलद डाउनलोडसह मिळेल.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow आपले दस्तऐवजीकरण स्वयंचलितपणे भाषांतरित करते आणि स्रोत फाइल बदलल्यावर पुन्हा पुश रिक्वेस्ट उघडते.  
हा मार्गदर्शक दाखवतो की GitHub App कसे स्थापित करावे आणि २ मिनिटांमध्ये आपले पहिले भाषांतर कसे चालवावे.


> [!NOTE]
>
> Localizeflow सध्या GitHub-आधारित दस्तऐवजीकरण प्रकल्पांना समर्थन देतो  
> (उदाहरणार्थ: AI for Beginners आणि बहुतेक मानक open-source रेपॉजिटरीज).  
> 
> Astro, Docusaurus, आणि Hugo सारख्या आधुनिक दस्तऐवजीकरण फ्रेमवर्कसाठी समर्थन  
> सध्या सक्रिय विकासात आहे.


---

## GitHub App मध्ये साइन इन करा आणि स्थापित करा

1. भेट द्या **[localizeflow.com](https://localizeflow.com/)**.
2. निवडा **Start with free trial**.  
   ![Select Start with free trial](../../../../translated images/mr/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. निवडा **Sign in with GitHub**.  
   ![Sign in with GitHub](../../../../translated images/mr/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. आपले GitHub खाते वापरून साइन इन करा.  
   ![GitHub login](../../../../translated images/mr/github-login.02bbaee0270b292e.webp)
5. ते खाते निवडा जेथे आपण Localizeflow GitHub App स्थापित करू इच्छिता — आपले वैयक्तिक खाते किंवा आपण व्यवस्थापित करणारी संस्था.  
   ![Select account](../../../../translated images/mr/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflow ला प्रवेश द्यायच्या रेपॉजिटरीज निवडा, नंतर **Save** निवडा.  
   ![Select repo and save](../../../../translated images/mr/select-repo-and-save.5a95ae288aefec6e.webp)
7. आपण Localizeflow च्या मुखपृष्ठावर पुनर्निर्देशित केले जाल.

> [!TIP]
> नंतर अधिक रेपॉजिटरीज जोडण्यासाठी, हेडरमध्ये आपले खाते निवडा आणि **+ Add more repositories** निवडा.  
> ![Add more repositories](../../../../translated images/mr/add-more-repo.2ca5154473aaaafb.webp)

---

## आपले रेपॉजिटरीज Localizeflow शी जोडा

1. Localizeflow च्या मुखपृष्ठावर, निवडा **+ Connect repositories**.  
   ![Select connect repositories](../../../../translated images/mr/select-connect-repos.8ac6f96f77dcc62c.webp)

2. जोडायच्या आधीच स्थापित रेपॉजिटरीजपैकी एक निवडा आणि **Save** निवडा.  
   ![Select repository](../../../../translated images/mr/select-repo.dce94db722b44cf3.webp)

3. आपली जोडलेली रेपॉजिटरीज आता दोन्ही मुखपृष्ठावर आणि रेपॉजिटरीज पृष्ठावर दिसतील.  
   ![Connected repositories](../../../../translated images/mr/repo-connected.9e5c21ee789fdcaa.webp)

---

## स्वयंचलित भाषांतर सुरू करा

1. नुकतीच जोडलेली रेपॉजिटरी निवडा.  
   ![Select repository](../../../../translated images/mr/select-repo-to-detail.55e53233531f8518.webp)

2. रेपॉजिटरी तपशील पृष्ठावर, खालच्या बाजूला **Edit** निवडा.  
   ![Select edit](../../../../translated images/mr/select-edit.225184c8c46d7001.webp)

3. आपले भाषांतर सेटिंग्ज कॉन्फिगर करा — लक्ष्य शाखा (पूर्वनिर्धारित: `main`), लक्ष्य भाषा, आणि स्रोत भाषा (पूर्वनिर्धारित: `en`). नंतर **Save** निवडा.  
   ![Configure translation settings](../../../../translated images/mr/configuration.ab55d0f8bab5711b.webp)

4. निवडा **Start & Automate**.  
   Localizeflow आता आपले दस्तऐवजीकरण स्वयंचलितपणे भाषांतरित करेल आणि स्रोत बदलल्यावर पुन्हा पुश रिक्वेस्ट उघडेल.  
   ![Start & Automate](../../../../translated images/mr/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**अस्वीकरण**:
हा दस्तऐवज AI अनुवाद सेवा [Co-op Translator](https://github.com/Azure/co-op-translator) वापरून अनुवादित केला आहे. आम्ही अचूकतेसाठी प्रयत्न करतो, तरी कृपया लक्षात ठेवा की स्वयंचलित अनुवादांमध्ये चुका किंवा अपूर्णता असू शकतात. मूळ दस्तऐवज त्याच्या मूळ भाषेत अधिकृत स्रोत म्हणून मानला जावा. महत्त्वाच्या माहिती साठी व्यावसायिक मानवी अनुवाद शिफारसीय आहे. या अनुवादाच्या वापरामुळे झालेल्या कोणत्याही गैरसमज किंवा चुकीच्या अर्थलाभाबद्दल आम्ही जबाबदार नाही.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->