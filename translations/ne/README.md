<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T11:10:54+00:00",
  "source_file": "README.md",
  "language_code": "ne"
}
-->
# Localizeflow – छिटो सुरु गर्ने मार्गदर्शिका

#### [Localizeflow](https://localizeflow.com/) द्वारा समर्थित

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](./README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow ले तपाईंको कागजातलाई स्वचालित रूपमा अनुवाद गर्छ र स्रोत फाइल परिवर्तन हुँदा पुल अनुरोधहरू खोल्छ।  
यो मार्गदर्शिकाले तपाईंलाई GitHub App कसरी स्थापना गर्ने र २ मिनेट भित्र पहिलो अनुवाद कसरी चलाउने देखाउँछ।


> [!NOTE]
>
> Localizeflow हाल GitHub-आधारित कागजात परियोजनाहरूलाई समर्थन गर्दछ  
> (उदाहरणका लागि: AI for Beginners र अधिकांश मानक खुला स्रोत रिपोजिटोरीहरू)।  
> 
> Astro, Docusaurus, र Hugo जस्ता आधुनिक कागजात फ्रेमवर्कहरूको समर्थन सक्रिय विकासमा छ।


---

## साइन इन गर्नुहोस् र GitHub App स्थापना गर्नुहोस्

1. **[localizeflow.com](https://localizeflow.com/)** मा जानुहोस्।
2. **Start with free trial** चयन गर्नुहोस्।  
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. **Sign in with GitHub** चयन गर्नुहोस्।  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. आफ्नो GitHub खाताबाट साइन इन गर्नुहोस्।  
   ![GitHub login](/images/github-login.png)
5. जहाँ तपाईं Localizeflow GitHub App स्थापना गर्न चाहनुहुन्छ त्यो खाता चयन गर्नुहोस् — तपाईंको व्यक्तिगत खाता वा तपाईंले व्यवस्थापन गर्ने संस्था।  
   ![Select account](/images/select-which-account-to-use.png)
6. Localizeflow ले पहुँच पाउन चाहने रिपोजिटोरीहरू चयन गर्नुहोस्, त्यसपछि **Save** चयन गर्नुहोस्।  
   ![Select repo and save](/images/select-repo-and-save.png)
7. तपाईंलाई Localizeflow होम पेजमा पुनः निर्देशित गरिनेछ।

> [!TIP]
> पछि थप रिपोजिटोरीहरू थप्न, हेडरमा आफ्नो खाता चयन गर्नुहोस् र **+ Add more repositories** चयन गर्नुहोस्।  
> ![Add more repositories](/images/add-more-repo.png)

---

## आफ्नो रिपोजिटोरीहरूलाई Localizeflow सँग जडान गर्नुहोस्

1. Localizeflow होम पेजमा, **+ Connect repositories** चयन गर्नुहोस्।  
   ![Select connect repositories](/images/select-connect-repos.png)

2. जडान गर्न चाहने स्थापना गरिएको रिपोजिटोरीहरू मध्ये एक चयन गर्नुहोस् र **Save** चयन गर्नुहोस्।  
   ![Select repository](/images/select-repo.png)

3. तपाईंका जडान गरिएका रिपोजिटोरीहरू अब होम पेज र रिपोजिटोरी पेज दुवैमा देखिनेछन्।  
   ![Connected repositories](/images/repo-connected.png)

---

## स्वचालित अनुवाद सुरु गर्नुहोस्

1. तपाईंले भर्खर जडान गर्नुभएको रिपोजिटोरी चयन गर्नुहोस्।  
   ![Select repository](/images/select-repo-to-detail.png)

2. रिपोजिटोरी विवरण पेजमा, तल **Edit** चयन गर्नुहोस्।  
   ![Select edit](/images/select-edit.png)

3. आफ्नो अनुवाद सेटिङहरू कन्फिगर गर्नुहोस् — लक्ष्य शाखा (पूर्वनिर्धारित: `main`), लक्ष्य भाषा, र स्रोत भाषा (पूर्वनिर्धारित: `en`)। **Save** चयन गर्नुहोस्।  
   ![Configure translation settings](/images/configuration.png)

4. **Start & Automate** चयन गर्नुहोस्।  
   Localizeflow अब स्वचालित रूपमा तपाईंको कागजात अनुवाद गर्नेछ र स्रोत परिवर्तन हुँदा पुल अनुरोधहरू खोल्नेछ।  
   ![Start & Automate](/images/select-automate.png)