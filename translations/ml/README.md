# Localizeflow – വേഗത്തിലുള്ള ആരംഭം മാർഗ്ഗനിർദ്ദേശം

#### [Localizeflow](https://localizeflow.com/) നാൽ പിന്തുണമ്പെടുന്നു

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](./README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **പ്രാദേശികമായി ക്ലോൺ ചെയ്യാൻ ആഗ്രഹിക്കുകയാണോ?**

> ഈ റിപോസിറ്ററിയിൽ 50+ ഭാഷാ വിവർത്തനങ്ങൾ ഉൾപ്പെടുത്തിയതിനാൽ ഡൗൺലോഡ് വലുപ്പം വളരെ കൂടുതലാണ്. വിവർത്തനങ്ങളില്ലാതെ ക്ലോൺ ചെയ്യാൻ sparse checkout ഉപയോഗിക്കുക:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> ഇത് കോഴ്‌സ് പൂർത്തിയാക്കാനുള്ള എല്ലാ ആവശ്യങ്ങളുടെ വലിയ വേഗത്തിലുള്ള ഡൗൺലോഡുമായി നൽകുന്നു.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow നിങ്ങളുടെ ഡോക്യുമെന്റേഷനുകൾ സ്വയം വിവർത്തനം ചെയ്യുകയും സോഴ്‌സ് ഫയൽ മാറ്റം വന്നാൽ പുള്ള് റിക്ക്വസ്റ്റ് തുറക്കുകയും ചെയ്യുന്നു.  
ഈ മാർഗ്ഗനിർദ്ദേശം GitHub ആപ്പ് ഇൻസ്റ്റാൾ ചെയ്യാനും 2 മിനിറ്റിൽ നിങ്ങളുടെ ആദ്യ വിവർത്തനം നടത്താനും കാണിക്കുന്നു.


> [!NOTE]
>
> Localizeflow നിലവിൽ GitHub-അധിഷ്ഠിത ഡോക്യുമെന്റേഷൻ പ്രോജക്ടുകൾ പിന്തുണയ്ക്കുന്നു  
> (ഉദാഹരണം: AI for Beginners மற்றும் കൂടുതലായിട്ടുള്ള സാധാരണ ഓപ്പൺ-സോഴ്സ് റെപ്പോസ്).  
> 
> Astro, Docusaurus, Hugo പോലുള്ള ആധുനിക ഡോക്യുമെന്റേഷൻ ഫ്രെയിംവർക്ക്‌മാർക്ക് പിന്തുണ സജീവ വികസനത്തിലാണ്.


---

## സൈൻ ഇൻ ചെയ്ത് GitHub ആപ്പ് ഇൻസ്റ്റാൾ ചെയ്യുക

1. **[localizeflow.com](https://localizeflow.com/)** സന്ദർശിക്കുക.
2. **Start with free trial** തിരഞ്ഞെടുക്കുക.  
   ![Select Start with free trial](../../../../translated images/ml/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **Sign in with GitHub** തിരഞ്ഞെടുക്കുക.  
   ![Sign in with GitHub](../../../../translated images/ml/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. നിങ്ങളുടെ GitHub അക്കൗണ്ടിൽ സൈൻ ഇൻ ചെയ്യുക.  
   ![GitHub login](../../../../translated images/ml/github-login.02bbaee0270b292e.webp)
5. Localizeflow GitHub ആപ്പ് ഇൻസ്റ്റാൾ ചെയ്യാനാഗ്രഹിക്കുന്ന അക്കൗണ്ട് തിരഞ്ഞെടുക്കുക — നിങ്ങളുടെ വ്യക്തിഗത അക്കൗണ്ടോ നിങ്ങളുടെ നിയന്ത്രണത്തിലുള്ള ഓർഗനൈസേഷൻ ആണോ.  
   ![Select account](../../../../translated images/ml/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflow ആക്‌സസ് ചെയ്യേണ്ട റെപ്പോസിറ്ററികൾ തിരഞ്ഞെടുക്കുക, പിന്നെ **Save** അമർത്തുക.  
   ![Select repo and save](../../../../translated images/ml/select-repo-and-save.5a95ae288aefec6e.webp)
7. നിങ്ങൾ Localizeflow ഹോം പേജിലേക്ക് തിരിച്ച് കൊണ്ടുപോകപ്പെടും.

> [!TIP]
> പിന്നീട് കൂടുതൽ റെപ്പോസിറ്ററികൾ ചേർക്കാൻ, ഹെഡറിൽ നിങ്ങളുടെ അക്കൗണ്ട് തിരഞ്ഞെടുക്കുകയും **+ Add more repositories** തിരഞ്ഞെടുക്കുകയും ചെയ്യുക.  
> ![Add more repositories](../../../../translated images/ml/add-more-repo.2ca5154473aaaafb.webp)

---

## നിങ്ങളുടെ റെപ്പോസിറ്ററികൾ Localizeflow-യ്ക്ക് കണക്റ്റുചെയ്യുക

1. Localizeflow ഹോം പേജിൽ **+ Connect repositories** തിരഞ്ഞെടുക്കുക.  
   ![Select connect repositories](../../../../translated images/ml/select-connect-repos.8ac6f96f77dcc62c.webp)

2. ഇൻസ്റ്റാൾ ചെയ്ത റെപ്പോസിറ്ററികളിൽ നിന്നൊന്ന് തിരഞ്ഞെടുക്കുക, പിന്നെ **Save** അമർത്തുക.  
   ![Select repository](../../../../translated images/ml/select-repo.dce94db722b44cf3.webp)

3. നിങ്ങളുടെ കണക്റ്റുചെയ്‌ത റെപ്പോസിറ്ററികൾ ഹോം പേജിലും റെപ്പോസിറ്ററികൾ പേജിലുമായി കാണപ്പെടും.  
   ![Connected repositories](../../../../translated images/ml/repo-connected.9e5c21ee789fdcaa.webp)

---

## സ്വയമേവ അന്വർത്ഥമായ വിവർത്തനം ആരംഭിക്കുക

1. ഇപ്പോൾ നിങ്ങള്ക്ക് കണക്റ്റുചെയ്‌ത റെപ്പോസിറ്ററി തിരഞ്ഞെടുക്കുക.  
   ![Select repository](../../../../translated images/ml/select-repo-to-detail.55e53233531f8518.webp)

2. റെപ്പോസിറ്ററി വിശദാംശ പേജിൽ കീഴിൽ **Edit** തിരഞ്ഞെടുക്കുക.  
   ![Select edit](../../../../translated images/ml/select-edit.225184c8c46d7001.webp)

3. നിങ്ങളുടെ വിവർത്തന സെറ്റിങ്ങുകൾ ക്രമീകരിക്കുക — ലക്ഷ്യം ബ്രാഞ്ച് (ഡിഫോൾട്ട്: `main`), ലക്ഷ്യമിടുന്ന ഭാഷകൾ, സോഴ്‌സ് ഭാഷ (ഡിഫോൾട്ട്: `en`). **Save** തിരഞ്ഞെടുക്കുക.  
   ![Configure translation settings](../../../../translated images/ml/configuration.ab55d0f8bab5711b.webp)

4. **Start & Automate** തിരഞ്ഞെടുക്കുക.  
   Localizeflow ഇപ്പോൾ നിങ്ങളുടെ ഡോക്യുമെന്റേഷൻ സ്വയം വിവർത്തനം ചെയ്ത് സോഴ്‌സ് മാറ്റം വരുന്ന പള്ളുകൾ തുറക്കും.  
   ![Start & Automate](../../../../translated images/ml/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**ഡിസ്‌ക്ലെയിമർ**:  
ഈ ദസ്താവേച് AI തർജുമാ സേവനം [Co-op Translator](https://github.com/Azure/co-op-translator) ഉപയോഗിച്ച് വിവർത്തനം ചെയ്തിരിക്കുന്നു. ഞങ്ങൾ കൃത്യതയ്ക്ക് ശ്രമിക്കുകയുണ്ടായിരുന്നെങ്കിലും, സ്വയംഭരണ തർജുമാക്കൾയിൽ പിശകുകൾ അല്ലെങ്കിൽ അപൂർവമായ തെറ്റുകൾ ഉണ്ടാകാവുന്നതാണ്. ഇതിന്റെ സ്വന്തം ഭാഷയിലെ മൗലിക ദസ്താവേച് മതിയായ ഉറവിടമായി ആശ്രയിക്കേണ്ടതാണ്. വലിയ പ്രാധാന്യമുള്ള വിവരങ്ങൾക്ക്, പ്രൊഫഷണൽ മനുഷ്യ തർജുമാ നിർദ്ദേശിക്കപ്പെടുന്നു. ഈ തർജുമയുടെ ഉപയോഗത്തിൽനിന്നു ഒരുപോലും തെറ്റു മനസ്സിലാക്കലുകൾ അല്ലെങ്കിൽ ദുർവ്യാഖ്യാനങ്ങൾ സംഭവിച്ചാൽ ഞങ്ങൾക്ക് യാതൊരു ഉത്തരവാദിത്വവും വരില്ല.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->