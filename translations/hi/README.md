<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T10:48:03+00:00",
  "source_file": "README.md",
  "language_code": "hi"
}
-->
# Localizeflow – त्वरित प्रारंभ गाइड

#### समर्थित द्वारा [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](./README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow स्वचालित रूप से आपके दस्तावेज़ों का अनुवाद करता है और जब भी स्रोत फ़ाइल बदलती है तो पुल अनुरोध खोलता है।  
यह गाइड आपको दिखाता है कि GitHub ऐप कैसे इंस्टॉल करें और 2 मिनट से कम समय में अपना पहला अनुवाद कैसे चलाएं।


> [!NOTE]
>
> Localizeflow वर्तमान में GitHub-आधारित दस्तावेज़ परियोजनाओं का समर्थन करता है  
> (उदाहरण के लिए: AI for Beginners और अधिकांश मानक ओपन-सोर्स रिपोज)।  
> 
> Astro, Docusaurus, और Hugo जैसे आधुनिक दस्तावेज़ फ्रेमवर्क के लिए समर्थन  
> सक्रिय विकास में है।


---

## साइन इन करें और GitHub ऐप इंस्टॉल करें

1. जाएं **[localizeflow.com](https://localizeflow.com/)**।
2. चुनें **Start with free trial**।  
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. चुनें **Sign in with GitHub**।  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. अपने GitHub खाते से साइन इन करें।  
   ![GitHub login](/images/github-login.png)
5. वह खाता चुनें जहाँ आप Localizeflow GitHub ऐप इंस्टॉल करना चाहते हैं — आपका व्यक्तिगत खाता या कोई संगठन जिसे आप प्रबंधित करते हैं।  
   ![Select account](/images/select-which-account-to-use.png)
6. वे रिपोजिटरी चुनें जिन्हें आप चाहते हैं कि Localizeflow एक्सेस करे, फिर **Save** चुनें।  
   ![Select repo and save](/images/select-repo-and-save.png)
7. आपको Localizeflow होम पेज पर पुनः निर्देशित किया जाएगा।

> [!TIP]
> बाद में अधिक रिपोजिटरी जोड़ने के लिए, हेडर में अपने खाते का चयन करें और **+ Add more repositories** चुनें।  
> ![Add more repositories](/images/add-more-repo.png)

---

## अपने रिपोजिटरी को Localizeflow से कनेक्ट करें

1. Localizeflow होम पेज पर, चुनें **+ Connect repositories**।  
   ![Select connect repositories](/images/select-connect-repos.png)

2. उन इंस्टॉल किए गए रिपोजिटरी में से एक चुनें जिन्हें आप कनेक्ट करना चाहते हैं और **Save** चुनें।  
   ![Select repository](/images/select-repo.png)

3. आपके कनेक्ट किए गए रिपोजिटरी अब होम पेज और रिपोजिटरी पेज दोनों पर दिखाई देंगे।  
   ![Connected repositories](/images/repo-connected.png)

---

## स्वचालित अनुवाद शुरू करें

1. उस रिपोजिटरी का चयन करें जिसे आपने अभी कनेक्ट किया है।  
   ![Select repository](/images/select-repo-to-detail.png)

2. रिपोजिटरी विवरण पेज पर, नीचे **Edit** चुनें।  
   ![Select edit](/images/select-edit.png)

3. अपने अनुवाद सेटिंग्स कॉन्फ़िगर करें — लक्ष्य शाखा (डिफ़ॉल्ट: `main`), लक्ष्य भाषाएँ, और स्रोत भाषा (डिफ़ॉल्ट: `en`)। फिर **Save** चुनें।  
   ![Configure translation settings](/images/configuration.png)

4. चुनें **Start & Automate**।  
   Localizeflow अब स्वचालित रूप से आपके दस्तावेज़ का अनुवाद करेगा और जब भी स्रोत बदलेगा तो पुल अनुरोध खोलेगा।  
   ![Start & Automate](/images/select-automate.png)