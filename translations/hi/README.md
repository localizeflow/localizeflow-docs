# Localizeflow – त्वरित प्रारंभ गाइड

#### समर्थित द्वारा [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](./README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **स्थानीय रूप से क्लोन करना पसंद है?**

> इस रिपॉजिटरी में 50+ भाषा अनुवाद शामिल हैं जो डाउनलोड साइज़ को काफी बढ़ा देते हैं। बिना अनुवादों के क्लोन करने के लिए, sparse checkout का उपयोग करें:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
 > यह आपको तेज़ डाउनलोड के साथ कोर्स पूरा करने के लिए आवश्यक सब कुछ देता है।  
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow स्वचालित रूप से आपकी डाक्यूमेंटेशन का अनुवाद करता है और जब भी स्रोत फ़ाइल बदलती है तो पुल रिक्वेस्ट खोलता है।  
यह गाइड आपको दिखाता है कि GitHub App कैसे इंस्टॉल करें और अपनी पहली अनुवाद प्रक्रिया 2 मिनट से कम समय में कैसे चलाएं।

> [!NOTE]
>
> Localizeflow वर्तमान में GitHub-आधारित डाक्यूमेंटेशन प्रोजेक्ट्स का समर्थन करता है  
> (उदाहरण के लिए: AI for Beginners और अधिकांश स्टैण्डर्ड ओपन-सोर्स रिपॉजिटरी)।  
>
> Astro, Docusaurus, और Hugo जैसे आधुनिक डाक्यूमेंटेशन फ्रेमवर्क्स के लिए समर्थन सक्रिय विकास में है।

---

## साइन इन करें और GitHub App इंस्टॉल करें

1. **[localizeflow.com](https://localizeflow.com/)** पर जाएं।
2. **Start with free trial** चुनें।  
   ![Select Start with free trial](../../../../translated images/hi/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **Sign in with GitHub** चुनें।  
   ![Sign in with GitHub](../../../../translated images/hi/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. अपने GitHub अकाउंट से साइन इन करें।  
   ![GitHub login](../../../../translated images/hi/github-login.02bbaee0270b292e.webp)
5. उस अकाउंट का चयन करें जहाँ आप Localizeflow GitHub App इंस्टॉल करना चाहते हैं — आपका व्यक्तिगत अकाउंट या कोई संगठन जिसे आप प्रबंधित करते हैं।  
   ![Select account](../../../../translated images/hi/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. उन रिपॉजिटरीज़ का चयन करें जिन तक आप चाहते हैं कि Localizeflow को एक्सेस हो, फिर **Save** चुनें।  
   ![Select repo and save](../../../../translated images/hi/select-repo-and-save.5a95ae288aefec6e.webp)
7. आपको Localizeflow होम पेज पर रीडायरेक्ट कर दिया जाएगा।

> [!TIP]
> बाद में और रिपॉजिटरीज़ जोड़ने के लिए, हेडर में अपने अकाउंट को चुनें और **+ Add more repositories** चुनें।  
> ![Add more repositories](../../../../translated images/hi/add-more-repo.2ca5154473aaaafb.webp)

---

## अपनी रिपॉजिटरीज़ को Localizeflow से कनेक्ट करें

1. Localizeflow होम पेज पर, **+ Connect repositories** चुनें।  
   ![Select connect repositories](../../../../translated images/hi/select-connect-repos.8ac6f96f77dcc62c.webp)

2. इंस्टॉल की गई रिपॉजिटरीज़ में से किसी एक को चुनें जिसे आप कनेक्ट करना चाहते हैं और **Save** चुनें।  
   ![Select repository](../../../../translated images/hi/select-repo.dce94db722b44cf3.webp)

3. आपकी कनेक्टेड रिपॉजिटरीज़ अब होम पेज और रिपॉजिटरी पेज दोनों पर दिखाई देंगी।  
   ![Connected repositories](../../../../translated images/hi/repo-connected.9e5c21ee789fdcaa.webp)

---

## स्वचालित अनुवाद शुरू करें

1. उस रिपॉजिटरी का चयन करें जिसे आपने अभी कनेक्ट किया है।  
   ![Select repository](../../../../translated images/hi/select-repo-to-detail.55e53233531f8518.webp)

2. रिपॉजिटरी डिटेल पेज पर, नीचे **Edit** चुनें।  
   ![Select edit](../../../../translated images/hi/select-edit.225184c8c46d7001.webp)

3. अपनी अनुवाद सेटिंग्स कॉन्फ़िगर करें — लक्ष्य ब्रांच (डिफ़ॉल्ट: `main`), लक्ष्य भाषाएँ, और स्रोत भाषा (डिफ़ॉल्ट: `en`)। **Save** चुनें।  
   ![Configure translation settings](../../../../translated images/hi/configuration.ab55d0f8bab5711b.webp)

4. **Start & Automate** चुनें।  
   Localizeflow अब स्वचालित रूप से आपकी डाक्यूमेंटेशन का अनुवाद करेगा और जब भी स्रोत में बदलाव होगा पुल रिक्वेस्ट खोलेगा।  
   ![Start & Automate](../../../../translated images/hi/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**अस्वीकरण**:  
इस दस्तावेज़ का अनुवाद AI अनुवाद सेवा [Co-op Translator](https://github.com/Azure/co-op-translator) का उपयोग करके किया गया है। जबकि हम सटीकता के लिए प्रयास करते हैं, कृपया ध्यान दें कि स्वचालित अनुवादों में त्रुटियाँ या inaccuracies हो सकती हैं। मूल भाषा में दिया गया मूल दस्तावेज़ आधिकारिक स्रोत माना जाना चाहिए। महत्वपूर्ण जानकारी के लिए, पेशेवर मानव अनुवाद की सलाह दी जाती है। इस अनुवाद के उपयोग से उत्पन्न किसी भी गलतफहमी या गलत व्याख्या के लिए हम जिम्मेदार नहीं हैं।
<!-- CO-OP TRANSLATOR DISCLAIMER END -->