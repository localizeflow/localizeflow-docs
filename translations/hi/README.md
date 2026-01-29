# Localizeflow – त्वरित प्रारंभ गाइड

#### समर्थित द्वारा [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](./README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **स्थानीय रूप से क्लोन करना पसंद करते हैं?**

> यह रिपोजिटरी 50+ भाषा अनुवाद शामिल करता है जो डाउनलोड आकार को काफी बढ़ा देता है। अनुवाद बिना क्लोन करने के लिए, sparse checkout का उपयोग करें:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> यह आपको तेज़ डाउनलोड के साथ कोर्स पूरा करने के लिए सब कुछ देता है।
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow स्वचालित रूप से आपकी दस्तावेज़ीकरण का अनुवाद करता है और जब भी स्रोत फ़ाइल बदलती है तो पुल अनुरोध खोलता है।  
यह गाइड आपको दिखाता है कि कैसे GitHub ऐप इंस्टॉल करें और अपनी पहली अनुवाद प्रक्रिया 2 मिनट से भी कम समय में चलाएँ।


> [!NOTE]
>
> Localizeflow वर्तमान में GitHub-आधारित दस्तावेज़ीकरण परियोजनाओं का समर्थन करता है  
> (उदाहरण: AI for Beginners और अधिकांश मानक ओपन-सोर्स रिपोज)।  
> 
> आधुनिक दस्तावेज़ीकरण फ्रेमवर्क जैसे Astro, Docusaurus, और Hugo के लिए समर्थन  
> सक्रिय विकास में है।


---

## साइन इन करें और GitHub ऐप इंस्टॉल करें

1. जाएँ **[localizeflow.com](https://localizeflow.com/)**।
2. चुनें **Start with free trial**।  
   ![Start with free trial चुनें](../../../../translated_images/hi/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. चुनें **Sign in with GitHub**।  
   ![GitHub से साइन इन करें](../../../../translated_images/hi/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. अपने GitHub खाते से साइन इन करें।  
   ![GitHub लॉगिन](../../../../translated_images/hi/github-login.02bbaee0270b292e.webp)
5. वह खाता चुनें जहाँ आप Localizeflow GitHub ऐप इंस्टॉल करना चाहते हैं — आपका व्यक्तिगत खाता या कोई संगठन जिसे आप प्रबंधित करते हैं।  
   ![खाता चुनें](../../../../translated_images/hi/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. उन रिपोजिटरीज़ का चयन करें जिन्हें आप Localizeflow को एक्सेस देना चाहते हैं, फिर **Save** चुनें।  
   ![रिपोजिटरी चुनें और सहेजें](../../../../translated_images/hi/select-repo-and-save.5a95ae288aefec6e.webp)
7. आपको Localizeflow मुख्य पृष्ठ पर पुनः निर्देशित किया जाएगा।

> [!TIP]
> बाद में अधिक रिपोजिटरी जोड़ने के लिए, हेडर में अपना खाता चुनें और **+ Add more repositories** चुनें।  
> ![अधिक रिपोजिटरी जोड़ें](../../../../translated_images/hi/add-more-repo.2ca5154473aaaafb.webp)

---

## अपनी रिपोजिटरी को Localizeflow से कनेक्ट करें

1. Localizeflow होम पेज पर, चुनें **+ Connect repositories**।  
   ![Connect repositories चुनें](../../../../translated_images/hi/select-connect-repos.8ac6f96f77dcc62c.webp)

2. एक इंस्टॉल की गई रिपोजिटरी चुनें जिसे आप कनेक्ट करना चाहते हैं, और चुनें **Save**।  
   ![रिपोजिटरी चुनें](../../../../translated_images/hi/select-repo.dce94db722b44cf3.webp)

3. आपकी कनेक्ट की गई रिपोजिटरी अब होम पेज और रिपोजिटरी पेज दोनों पर दिखाई देंगी।  
   ![कनेक्ट की गई रिपोजिटरी](../../../../translated_images/hi/repo-connected.9e5c21ee789fdcaa.webp)

---

## स्वचालित अनुवाद शुरू करें

1. उस रिपोजिटरी का चयन करें जिसे आपने अभी कनेक्ट किया है।  
   ![रिपोजिटरी चुनें](../../../../translated_images/hi/select-repo-to-detail.55e53233531f8518.webp)

2. रिपोजिटरी विवरण पेज पर, नीचे **Edit** चुनें।  
   ![Edit चुनें](../../../../translated_images/hi/select-edit.225184c8c46d7001.webp)

3. अपनी अनुवाद सेटिंग्स कॉन्फ़िगर करें — लक्षित ब्रांच (डिफ़ॉल्ट: `main`), लक्षित भाषाएं, और स्रोत भाषा (डिफ़ॉल्ट: `en`)। **Save** चुनें।  
   ![अनुवाद सेटिंग्स कॉन्फ़िगर करें](../../../../translated_images/hi/configuration.ab55d0f8bab5711b.webp)

4. चुनें **Start & Automate**।  
   Localizeflow अब स्वचालित रूप से आपकी दस्तावेज़ीकरण का अनुवाद करेगा और जब भी स्रोत बदलेगा तो पुल अनुरोध खोलेगा।  
   ![Start & Automate](../../../../translated_images/hi/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**अस्वीकरण**:  
इस दस्तावेज़ का अनुवाद एआई अनुवाद सेवा [Co-op Translator](https://github.com/Azure/co-op-translator) का उपयोग करके किया गया है। जबकि हम सटीकता के लिए प्रयासरत हैं, कृपया ध्यान दें कि स्वचालित अनुवाद में त्रुटियाँ या गलतियाँ हो सकती हैं। मूल दस्तावेज़ अपनी मूल भाषा में अधिकृत स्रोत माना जाना चाहिए। महत्वपूर्ण जानकारी के लिए, पेशेवर मानव अनुवाद की सलाह दी जाती है। इस अनुवाद के उपयोग से उत्पन्न किसी भी गलतफहमी या गलत व्याख्या के लिए हम जिम्मेदार नहीं हैं।
<!-- CO-OP TRANSLATOR DISCLAIMER END -->