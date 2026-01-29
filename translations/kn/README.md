# Localizeflow – ವೇಗವಾದ ಪ್ರಾರಂಭ ಮಾರ್ಗದರ್ಶಿ

#### [Localizeflow](https://localizeflow.com/) ಮೂಲಕ ಬೆಂಬಲಿತವಾಗಿದೆ

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](./README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **ಸ್ಥಳೀಯವಾಗಿ ಕ್ಕ್ಲೋನ್ ಮಾಡಲು ಇಚ್ಛಿಸುವಿರಾ?**

> ಈ ರೆಪೊಸಿಟರಿಯು 50+ ಭಾಷಾ ಅನುವಾದಗಳನ್ನು ಒಳಗೊಂಡಿದೆ, ಇದು ಡೌನ್ಲೋಡ್ ಗಾತ್ರವನ್ನು ಬಹಳಷ್ಟು ಹೆಚ್ಚಿಸುತ್ತದೆ. ಅನುವಾದಗಳನ್ನು ಹೊರತುಪಡಿಸಿ ಕ್ಲೋನ್ ಮಾಡಲು sparse checkout ಬಳಸಿ:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> ಇದು ನಿಮ್ಮ ಕೋರ್ಸ್ ಪೂರ್ಣಗೊಳಿಸಲು ಬೇಕಾದ ಎಲ್ಲವನ್ನೂ ಬಹುಶೀಘ್ರ ಡೌನ್ಲೋಡ್ ಆಗುವಂತೆ ನೀಡುತ್ತದೆ.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow ಸ್ವಯಂಚಾಲಿತವಾಗಿ ನಿಮ್ಮ ದಾಖಲೆಗಳ ಅನುವಾದ ಮಾಡುತ್ತದೆ ಮತ್ತು ಮೂಲ ಫೈಲ್ ಬದಲಾಗಿದೆ ತಕ್ಷಣ ಪುಲ್ ರಿಕ್ವೆಸ್ಟ್ ತೆಗೆಯುತ್ತದೆ.  
ಈ ಮಾರ್ಗದರ್ಶಿ GitHub ಆಪ್ ಅನ್ನು ಸ್ಥಾಪಿಸುವುದು ಮತ್ತು 2 ನಿಮಿಷಗಳ ಒಳಗೆ ನಿಮ್ಮ ಮೊದಲ ಅನುವಾದವನ್ನು ನಡೆಸುವುದನ್ನು ತೋರಿಸುತ್ತದೆ.


> [!NOTE]
>
> Localizeflow ಈಗಾಗಲೇ GitHub ಆಧಾರಿತ ದಾಖಲೆ ಯೋಜನೆಗಳನ್ನು ಬೆಂಬಲಿಸುತ್ತದೆ  
> (ಉದಾಹರಣೆಗೆ: AI for Beginners ಮತ್ತು ಹೆಚ್ಚಿನ ಮಾನಕ open-source ರೆಪೊಗಳು).  
> 
> Astro, Docusaurus, ಹಾಗೂ Hugo ಮುಂತಾದ ಆಧುನಿಕ ದಾಖಲೆ ಚಟ್ರಗಳು ಬೆಂಬಲ ಈಗಾಗಲೇ ಅಭಿವೃದ್ಧಿಯಲ್ಲಿದೆ.


---

## ಸೈನ್ ಇನ್ ಆಗಿ GitHub ಆಪ್ ಅನ್ನು ಸ್ಥಾಪಿಸಿ

1. **[localizeflow.com](https://localizeflow.com/)** ಗೆ ಭೇಟಿ ನೀಡಿ.
2. **Start with free trial** ಆಯ್ಕೆಮಾಡಿ.  
   ![Select Start with free trial](../../../../translated images/kn/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **Sign in with GitHub** ಆಯ್ಕೆಮಾಡಿ.  
   ![Sign in with GitHub](../../../../translated images/kn/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. ನಿಮ್ಮ GitHub ಖಾತೆಯಿಂದ ಸೈನ್ ಇನ್ ಆಗಿ.  
   ![GitHub login](../../../../translated images/kn/github-login.02bbaee0270b292e.webp)
5. Localizeflow GitHub ಆಪ್ ಅನ್ನು ಸ್ಥಾಪಿಸಲು ನೀವು ಬಳಸಬೇಕಾದ ಖಾತೆಯನ್ನು ಆಯ್ಕೆಮಾಡಿ — ನಿಮ್ಮ ವೈಯಕ್ತಿಕ ಖಾತೆ ಅಥವಾ ನೀವು ನಿರ್ವಹಿಸುವ ಸಂಸ್ಥೆಯ ಖಾತೆ.  
   ![Select account](../../../../translated images/kn/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflow ತಲುಪಿಸಲು ಇಚ್ಛಿಸುವ ರೆಪೊಸಿಟರಿಗಳನ್ನು ಆಯ್ಕೆಮಾಡಿ, ನಂತರ **Save** ಆಯ್ಕೆಮಾಡಿ.  
   ![Select repo and save](../../../../translated images/kn/select-repo-and-save.5a95ae288aefec6e.webp)
7. ನೀವು Localizeflow ಮುಕಪುಟಕ್ಕೆ ಮರುನಿರ್ದೇಶಿತವಾಗುತ್ತೀರಿ.

> [!TIP]
> ನಂತರ ಇನ್ನಷ್ಟು ರೆಪೊಸಿಟರಿಗಳನ್ನು ಸೇರಿಸಲು, ಹೆಡರ್ ನಲ್ಲಿ ನಿಮ್ಮ ಖಾತೆಯನ್ನು ಆಯ್ಕೆಮಾಡಿ ಮತ್ತು **+ Add more repositories** ಅನ್ನು ಆಯ್ಕೆಮಾಡಿ.  
> ![Add more repositories](../../../../translated images/kn/add-more-repo.2ca5154473aaaafb.webp)

---

## ನಿಮ್ಮ ರೆಪೊಸಿಟರಿಗಳನ್ನು Localizeflow ಗೆ ಸಂಪರ್ಕಿಸಿ

1. Localizeflow ಮುಕಪುಟದಲ್ಲಿ, **+ Connect repositories** ಆಯ್ಕೆಮಾಡಿ.  
   ![Select connect repositories](../../../../translated images/kn/select-connect-repos.8ac6f96f77dcc62c.webp)

2. ನೀವು ಸಂಪರ್ಕಿಸಲು ಬಯಸುವ ಸ್ಥಾಪಿತ ರೆಪೊಸಿಟರಿಗಳಲ್ಲಿ ಒಂದನ್ನು ಆಯ್ಕೆಮಾಡಿ ಮತ್ತು **Save** ಕ್ಲಿಕ್ ಮಾಡಿ.  
   ![Select repository](../../../../translated images/kn/select-repo.dce94db722b44cf3.webp)

3. ನಿಮ್ಮ ಸಂಪರ್ಕಿಸಿದ ರೆಪೊಸಿಟರಿಗಳು ಈಗ ಮುಖಪುಟ ಮತ್ತು ರೆಪೊಸಿಟರಿ ಪುಟ ಎರಡನ್ನೂ ತೋರಿಸುವವು.  
   ![Connected repositories](../../../../translated images/kn/repo-connected.9e5c21ee789fdcaa.webp)

---

## ಸ್ವಯಂಚಾಲಿತ ಅನುವಾದವನ್ನು ಪ್ರಾರಂಭಿಸಿ

1. ನೀವು ಈಗಾ ಸಂಪರ್ಕಿಸಿದ ರೆಪೊಸಿಟರಿಯನ್ನು ಆಯ್ಕೆಮಾಡಿ.  
   ![Select repository](../../../../translated images/kn/select-repo-to-detail.55e53233531f8518.webp)

2. ಆ ರೆಪೊಸಿಟರಿ ವಿವರ ಪುಟದಲ್ಲಿ, ಕೆಳಭಾಗದಲ್ಲಿ **Edit** ಆಯ್ಕೆಯನ್ನು ಮಾಡಿ.  
   ![Select edit](../../../../translated images/kn/select-edit.225184c8c46d7001.webp)

3. ನಿಮ್ಮ ಅನುವಾದ ಹೊಂದಾಣಿಕೆಯನ್ನು ಮಾಡಿಕೊಳ್ಳಿ — ಗುರಿ ಶಾಖೆ (ಪೂರ್ವನಿರ್ಧಾರ: `main`), ಗುರಿ ಭಾಷೆಗಳು ಮತ್ತು ಮೂಲ ಭಾಷೆ (ಪೂರ್ವನಿರ್ಧಾರ: `en`). **Save** ಆಯ್ಕೆಮಾಡಿ.  
   ![Configure translation settings](../../../../translated images/kn/configuration.ab55d0f8bab5711b.webp)

4. **Start & Automate** ಆಯ್ಕೆಮಾಡಿ.  
   Localizeflow ಈಗ ಸ್ವಯಂಚಾಲಿತವಾಗಿ ನಿಮ್ಮ ದಾಖಲೆಗಳನ್ನು ಅನುವಾದಿಸುತ್ತದೆ ಮತ್ತು ಮೂಲ ಬದಲಾವಣೆಯಾದಾಗ ಪುಲ್ ರಿಕ್ವೆಸ್ಟ್ ತೆಗೆಯುತ್ತದೆ.  
   ![Start & Automate](../../../../translated images/kn/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**ವಿಧಿವಿಘ್ನ**:  
ಈ ಡಾಕ್ಯುಮೆಂಟ್ ಅನ್ನು AI ಅನುವಾದ ಸೇವೆ [Co-op Translator](https://github.com/Azure/co-op-translator) ಬಳಸಿ ಅನುವದಿಸಲಾಗಿದೆ. ನಾವು ಶುದ್ಧತೆಯನ್ನು ಬದುಕಲು ಪ್ರಯತ್ನಿಸುತ್ತೇವೆ, ಆದಾಗ್ಯೂ ಸ್ವಯಂಚಾಲಿತ ಅನುವಾದಗಳಲ್ಲಿ ದೋಷಗಳು ಅಥವಾ ತಪ್ಪುಗಳಿರಬಹುದು ಎಂಬುದು ಗಮನದಲ್ಲಿಡಿ. ಮೂಲ ಭಾಷೆಯಲ್ಲಿ ಇರುವ ಅಸಲಿ ಡಾಕ್ಯುಮೆಂಟ್ ಅನ್ನು ಅಧಿಕೃತ ಮೂಲವಾಗಿ ಪರಿಗಣಿಸಬೇಕು. ಮಹತ್ವಪೂರ್ಣ ಮಾಹಿತಿಗಾಗಿ, ವೃತ್ತಿಪರ ಮಾನವ ಅನುವಾದವನ್ನು ಶಿಫಾರಸು ಮಾಡಲಾಗುತ್ತದೆ. ಈ ಅನುವಾದದ ಬಳಕೆಯಿಂದ ಉಂಟಾಗುವ ಯಾವುದೇ ತಪ್ಪುಬೋಧನೆಗಳಿಗೆ ಅಥವಾ ತಪ್ಪು ಅರ್ಥayaanಕ್ಕೆ ನಾವು ಜವಾಬ್ದಾರಿಸುತ್ತಿಲ್ಲ.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->