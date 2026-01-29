# Localizeflow – వేగవంతమైన ప్రారంభ మార్గదర్శకం

#### మద్దతు చేసినది [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](./README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **స్థానికంగా క్లోన్ చేయాలని ఇష్టపడుతున్నారా?**

> ఈ రిపాజిటరీ 50+ భాషా అనువాదాలు కలిగి ఉంది, ఇది డౌన్లోడ్ పరిమాణాన్ని గణనీయంగా పెంచుతుంది. అనువాదాలు లేకుండా క్లోన్ చేయడానికి, sparse checkout ఉపయోగించండి:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> ఇది కోర్సును పూర్తి చేసుకోవడానికి అవసరమైన ప్రతిదీ చాలా వేగంగా డౌన్లోడ్ అవుతుంది.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow మీ డాక్యుమెంటేషన్‌ను ఆటోమేటిక్‌గా అనువదించి, మూల ఫైల్ మారినప్పుడు పుల్ల్ రిక్వెస్ట్‌లను తెరిచిపెడుతుంది.  
ఈ గైడ్ మీకు GitHub యాప్‌ను ఎలా ఇన్స్టాల్ చేయాలో, 2 నిమిషాల్లో మీ మొదటి అనువాదాన్ని ఎలా నిర్వహించాలో చూపిస్తుంది.


> [!NOTE]
>
> Localizeflow ప్రస్తుతానికి GitHub-ఆధారిత డాక్యుమెంటేషన్ ప్రాజెక్టులకు మద్దతు ఇస్తుంది  
> (ఉదాహరణకు: AI for Beginners మరియు ఎక్కువామైన ఓపెన్-సోర్స్ రిపోలు).  
> 
> Astro, Docusaurus, Hugo వంటి ఆధునిక డాక్యుమెంటేషన్ ఫ్రేమ్‌వర్క్‌లకు మద్దతు  
> సక్రియ అభివృద్ధిలో ఉంది.


---

## సైన్ ఇన్ చేసి GitHub యాప్ ఇన్‌స్టాల్ చేయండి

1. **[localizeflow.com](https://localizeflow.com/)** సందర్శించండి.
2. **Start with free trial** ఎంచుకోండి.  
   ![Select Start with free trial](../../../../translated images/te/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **GitHub తో సైన్ ఇన్ చేయండి** ఎంచుకోండి.  
   ![Sign in with GitHub](../../../../translated images/te/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. మీ GitHub ఖాతాతో సైన్ ఇన్ అవ్వండి.  
   ![GitHub login](../../../../translated images/te/github-login.02bbaee0270b292e.webp)
5. Localizeflow GitHub యాప్ ఇన్‌స్టాల్ చేయాలనుకునే ఖాతాను (మీ వ్యక్తిగత ఖాతా లేదా మీరు నిర్వహించే సంస్థ) ఎంచుకోండి.  
   ![Select account](../../../../translated images/te/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflowకి యాక్సెస్ ఇవ్వాలనుకునే రిపాజిటరీలను ఎంచుకొని, **Save** ఎంచుకోండి.  
   ![Select repo and save](../../../../translated images/te/select-repo-and-save.5a95ae288aefec6e.webp)
7. మీరు Localizeflow హోమ్ పేజీకి రీడైరెక్ట్ చేయబడతారు.

> [!TIP]
> తరువాత మరిన్ని రిపాజిటరీలను జోడించడానికి, హెడ్డర్‌లో మీ ఖాతాను ఎంచుకొని **+ Add more repositories** ఎంచుకోండి.  
> ![Add more repositories](../../../../translated images/te/add-more-repo.2ca5154473aaaafb.webp)

---

## మీ రిపాజిటరీలను Localizeflowతో కనెక్ట్ చేయండి

1. Localizeflow హోమ్ పేజీలో **+ Connect repositories** ఎంచుకోండి.  
   ![Select connect repositories](../../../../translated images/te/select-connect-repos.8ac6f96f77dcc62c.webp)

2. మీరు కనెక్ట్ చేయదలచిన ఇన్స్టాల్ చేసిన రిపాజిటరీలను ఎంచుకొని **Save** ఎంచుకోండి.  
   ![Select repository](../../../../translated images/te/select-repo.dce94db722b44cf3.webp)

3. మీరు కనెక్ట్ చేసిన రిపాజిటరీలు హోమ్ పేజీ మరియు రిపాజిటరీ పేజీ రెండింటిలో కూడా కనిపిస్తాయి.  
   ![Connected repositories](../../../../translated images/te/repo-connected.9e5c21ee789fdcaa.webp)

---

## ఆటోమేటిక్ అనువాదం ప్రారంభించండి

1. మీరు తాజాగా కనెక్ట్ చేసిన రిపాజిటరీని ఎంచుకోండి.  
   ![Select repository](../../../../translated images/te/select-repo-to-detail.55e53233531f8518.webp)

2. రిపాజిటరీ వివరాలు పేజీలో, కింద భాగంలో **Edit** ఎంచుకోండి.  
   ![Select edit](../../../../translated images/te/select-edit.225184c8c46d7001.webp)

3. మీ అనువాద సెట్టింగ్స్‌ను అమర్చండి — లక్ష్య బ్రాంచ్ (డిఫాల్ట్: `main`), లక్ష్య భాషలు, మరియు మూల భాష (డిఫాల్ట్: `en`). **Save** ఎంచుకోండి.  
   ![Configure translation settings](../../../../translated images/te/configuration.ab55d0f8bab5711b.webp)

4. **Start & Automate** ఎంచుకోండి.  
   Localizeflow ఇప్పుడు మీ డాక్యుమెంటేషన్‌ను ఆటోమేటిక్‌గా అనువదించి, మూలం మారినప్పుడు పుల్ల్ రిక్వెస్ట్‌లను తెరిచిపెడుతుంది.  
   ![Start & Automate](../../../../translated images/te/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**మార్గదర్శక సూచన**:  
ఈ దస్త్రం AI అనువాద సేవ [Co-op Translator](https://github.com/Azure/co-op-translator) ఉపయోగించి అనువదించబడింది. సరైనత కోసం మేము ప్రయత్నించినప్పటికీ, ఆటోమేటెడ్ అనువాదాల్లో పొరపాట్లు లేదా తప్పులుండే అవకాశం ఉందని దయచేసి గమనించండి. సొంత భాషలో ఉన్న అసలు దస్త్రం అధికారిక మూలంగా పరిగణించబడాలి. ముఖ్య సమాచారం కోసం, ప్రొఫెషనల్ మానవ అనువాదాన్ని సూచించబడుతుంది. ఈ అనువాదం వాడకంతో కలిగే ఏదైనా అంతరాల్లో లేదా తప్పుగా అర్థం చేసుకోవడంపై మేము బాధ్యత వహించము.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->