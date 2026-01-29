# Localizeflow – छिटो सुरु गर्न मार्गदर्शन

#### [Localizeflow](https://localizeflow.com/) द्वारा समर्थित

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](./README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **स्थानीय रूपमा क्लोन गर्न प्राथमिकता दिनुहुन्छ?**

> यो रेपोजिटरीमा ५० भन्दा बढी भाषा अनुवादहरू समावेश छन् जसले डाउनलोड आकार धेरै बढाउँछ। अनुवाद बिना क्लोन गर्न, sparse checkout प्रयोग गर्नुहोस्:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> यसले तपाईंलाई कोर्स पूरा गर्न आवश्यक सबै कुरा दिन्छ एक धेरै छिटो डाउनलोडको साथ।
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow ले स्वचालित रूपमा तपाईंको डक्युमेन्टेसन अनुवाद्छ र स्रोत फाइल परिवर्तन हुँदा पुल अनुरोधहरू खोल्छ।  
यस मार्गदर्शिकाले GitHub App कसरी इन्स्टल गर्ने र २ मिनेटभन्दा कम समयमा पहिलो अनुवाद कसरी चलाउने देखाउँछ।


> [!NOTE]
>
> Localizeflow अहिले GitHub-आधारित डक्युमेन्टेसन प्रोजेक्टहरूलाई समर्थन गर्छ  
> (जस्तै: AI for Beginners र धेरै मानक open-source रेपोजिटरीहरू)।  
> 
> Astro, Docusaurus, र Hugo जस्ता आधुनिक डक्युमेन्टेसन फ्रेमवर्कहरूको लागि समर्थन  
> सक्रिय विकास अवस्थामा छ।


---

## साइन इन गर्नुहोस् र GitHub App इन्स्टल गर्नुहोस्

1. **[localizeflow.com](https://localizeflow.com/)** भ्रमण गर्नुहोस्।
2. **Start with free trial** चयन गर्नुहोस्।  
   ![Select Start with free trial](../../../../translated images/ne/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **Sign in with GitHub** चयन गर्नुहोस्।  
   ![Sign in with GitHub](../../../../translated images/ne/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. तपाईंको GitHub खाताबाट साइन इन गर्नुहोस्।  
   ![GitHub login](../../../../translated images/ne/github-login.02bbaee0270b292e.webp)
5. त्यो खाता चयन गर्नुहोस् जहाँ तपाईं Localizeflow GitHub App इन्स्टल गर्न चाहनुहुन्छ — तपाईंको व्यक्तिगत खाता वा तपाईंले व्यवस्थापन गर्ने संगठन।  
   ![Select account](../../../../translated images/ne/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. तपाईं चाहनुहुने रेपोजिटरीहरू चयन गर्नुहोस् जुन Localizeflow ले पहुँच गर्न सक्छ, र त्यसपछि **Save** चयन गर्नुहोस्।  
   ![Select repo and save](../../../../translated images/ne/select-repo-and-save.5a95ae288aefec6e.webp)
7. तपाईंले Localizeflow होम पेजमा पुनः निर्देशन हुनुहुनेछ।

> [!TIP]
> पछि थप रेपोजिटरीहरू थप्न, शीर्षमा तपाईंको खाता चयन गर्नुहोस् र **+ Add more repositories** रोज्नुहोस्।  
> ![Add more repositories](../../../../translated images/ne/add-more-repo.2ca5154473aaaafb.webp)

---

## तपाईंका रेपोजिटरीहरूलाई Localizeflow सँग जडान गर्नुहोस्

1. Localizeflow होम पेजमा, **+ Connect repositories** चयन गर्नुहोस्।  
   ![Select connect repositories](../../../../translated images/ne/select-connect-repos.8ac6f96f77dcc62c.webp)

2. तपाईंले जडान गर्न चाहनु भएको इन्स्टल गरिएको रेपोजिटरीहरू मध्ये एउटा चयन गर्नुहोस् र **Save** चयन गर्नुहोस्।  
   ![Select repository](../../../../translated images/ne/select-repo.dce94db722b44cf3.webp)

3. तपाईंका जडान गरिएका रेपोजिटरीहरू अब होम पेज र रेपोजिटरी पेज दुवैमा देखिनेछन्।  
   ![Connected repositories](../../../../translated images/ne/repo-connected.9e5c21ee789fdcaa.webp)

---

## स्वचालित अनुवाद सुरु गर्नुहोस्

1. तपाईंले भर्खर जडान गरेको रेपोजिटरी चयन गर्नुहोस्।  
   ![Select repository](../../../../translated images/ne/select-repo-to-detail.55e53233531f8518.webp)

2. रेपोजिटरी डिटेल पेजमा, तल **Edit** चयन गर्नुहोस्।  
   ![Select edit](../../../../translated images/ne/select-edit.225184c8c46d7001.webp)

3. तपाईंको अनुवाद सेटिङहरू कन्फिगर गर्नुहोस् — लक्ष्य शाखा (पूर्वनिर्धारित: `main`), लक्ष्य भाषा, र स्रोत भाषा (पूर्वनिर्धारित: `en`)। त्यसपछि **Save** चयन गर्नुहोस्।  
   ![Configure translation settings](../../../../translated images/ne/configuration.ab55d0f8bab5711b.webp)

4. **Start & Automate** चयन गर्नुहोस्।  
   Localizeflow अब स्वचालित रूपमा तपाईंको डक्युमेन्टेसन अनुवाद गर्नेछ र स्रोत परिवर्तन हुँदा पुल अनुरोधहरू खोल्नेछ।  
   ![Start & Automate](../../../../translated images/ne/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**अस्वीकरण**:  
यो दस्तावेज़ AI अनुवाद सेवा [Co-op Translator](https://github.com/Azure/co-op-translator) को प्रयोग गरी अनुवाद गरिएको हो। हामी शुद्धतामा प्रयासरत छौं, तर कृपया जानकार हुनुहोस् कि स्वचालित अनुवादमा त्रुटि वा अशुद्धता हुन सक्छ। मूल दस्तावेज आफ्नो मूल भाषामा अधिकारिक स्रोत मानिनु पर्छ। महत्वपूर्ण जानकारीका लागि व्यावसायिक मानव अनुवाद सिफारिस गरिन्छ। यस अनुवादको प्रयोगबाट उत्पन्न कुनै पनि गलतफहमी वा गलत व्याख्याका लागि हामी जिम्मेवार छैनौं।
<!-- CO-OP TRANSLATOR DISCLAIMER END -->