# Localizeflow – ക്വിക്ക് സ്റ്റാർട്ട് ഗൈഡ്

#### [Localizeflow](https://localizeflow.com/) ആണ് പിന്തുണയ്ക്കുന്നത്

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](./README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **പ്രാദേശികമായി ക്ലോൺ ചെയ്യണമെന്ന് ആഗ്രഹിക്കുന്നുവോ?**

> ഈ റീപ്പോസിറ്ററിയിൽ 50-ത്തിലധികം ഭാഷാ വിവർത്തനങ്ങൾ ഉൾപ്പെടുത്തിയിരിക്കുന്നത് ഡൗൺലോഡ് സൈസ് വളരെ വർദ്ധിപ്പിക്കുന്നു. വിവർത്തനങ്ങൾ ഇല്ലാതെ ക്ലോൺ ചെയ്യാൻ sparse checkout ഉപയോഗിക്കുക:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> ഇത് കോഴ്സ് തീർത്തു നിർത്താൻ ആവശ്യമായ ദ്രുത ഡൗൺലോഡിനായി എല്ലാം നൽകും.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow നിങ്ങളുടെ ഡോക്യുമെന്റേഷൻ സ്വയം വിവർത്തനം ചെയ്ത്, സോഴ്സ് ഫയൽ മാറ്റം വന്നപ്പോൾ പുൽ റിക്വസ്റ്റ് തുറക്കുന്നു.  
ഈ ഗൈഡ് GitHub അപ്ലിക്കേഷൻ ഇൻസ്റ്റാൾ ചെയ്ത്, 2 മിനിറ്റിനുള്ളിൽ ആദ്യമായുള്ള വിവർത്തനം എങ്ങനെ നടത്താമെന്ന് കാണിക്കുന്നു.


> [!NOTE]
>
> Localizeflow നിലവിൽ GitHub-അടിസ്ഥാനമാക്കിയ ഡോക്യുമെന്റേഷൻ പ്രോജക്റ്റുകളെ പിന്തുണയ്ക്കുന്നു  
> (ഉദാഹരണത്തിന്: AI for Beginners, മറ്റ് സ്റ്റാൻഡേർഡ് open-source റീപോകൾ).  
> 
> Astro, Docusaurus, Hugo പോലുള്ള ആധുനിക ഡോക്യുമെന്റേഷൻ ഫ്രെയിംവർക്ക്‌ക്കുള്ള പിന്തുണ സജീവമായി വികസിപ്പിക്കുകയിലാണ്.


---

## സൈൻ ഇൻ ചെയ്ത് GitHub ആപ്പ് ഇൻസ്റ്റാൾ ചെയ്യുക

1. **[localizeflow.com](https://localizeflow.com/)** സന്ദർശിക്കുക.
2. **Start with free trial** തിരഞ്ഞെടുക്കുക.  
   ![Select Start with free trial](../../../../translated_images/ml/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **Sign in with GitHub** തിരഞ്ഞെടുക്കുക.  
   ![Sign in with GitHub](../../../../translated_images/ml/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. നിങ്ങളുടെ GitHub അക്കൗണ്ട് ഉപയോഗിച്ച് സൈൻ ഇൻ ചെയ്യുക.  
   ![GitHub login](../../../../translated_images/ml/github-login.02bbaee0270b292e.webp)
5. Localizeflow GitHub ആപ്പ് ഇൻസ്റ്റാൾ ചെയ്യാൻ നിങ്ങൾ തിരഞ്ഞെടുക്കേണ്ട അക്കൗണ്ട് — നിങ്ങളുടെ വ്യക്തിഗത അക്കൗണ്ട് അല്ലെങ്കിൽ ഒരു ഓർഗനൈസേഷൻ.  
   ![Select account](../../../../translated_images/ml/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflow ആക്‌സസ് ചെയ്യാൻ ഇഷ്ടമുള്ള റീപ്പോസിറ്ററികൾ തെരഞ്ഞെടുത്ത് **Save** തിരഞ്ഞെടുക്കുക.  
   ![Select repo and save](../../../../translated_images/ml/select-repo-and-save.5a95ae288aefec6e.webp)
7. നിങ്ങൾ Localizeflow ഹോം പേജിലേക്കു റീഡയറക്ട് ചെയ്യും.

> [!TIP]
> പിന്നീട് കൂടുതൽ റീപ്പോസിറ്ററികൾ ചേർക്കാൻ, തലക്കൊളിയിൽ നിങ്ങളുടെ അക്കൗണ്ട് തെരഞ്ഞെടുക്കും, തുടർന്ന് **+ Add more repositories** തെരഞ്ഞെടുക്കുക.  
> ![Add more repositories](../../../../translated_images/ml/add-more-repo.2ca5154473aaaafb.webp)

---

## നിങ്ങളുടെ റീപ്പോസിറ്ററികൾ Localizeflow-യുമായി കണക്റ്റ് ചെയ്യുക

1. Localizeflow ഹോം പേജിൽ **+ Connect repositories** തിരഞ്ഞെടുക്കുക.  
   ![Select connect repositories](../../../../translated_images/ml/select-connect-repos.8ac6f96f77dcc62c.webp)

2. നിങ്ങൾ കണക്റ്റ് ചെയ്യാൻ ആഗ്രഹിക്കുന്ന ഇൻസ്റ്റാൾ ചെയ്തിട്ടുള്ള റീപ്പോസിറ്ററികളിൽ ഒന്നിനെ തിരഞ്ഞെടുക്കുകയും **Save** അമർത്തുക.  
   ![Select repository](../../../../translated_images/ml/select-repo.dce94db722b44cf3.webp)

3. നിങ്ങൾ കണക്റ്റ് ചെയ്തിട്ടുള്ള റീപ്പോസിറ്ററികൾ ഹോം പേജിലും റീപ്പോസ് പേജിലും ഇപ്പോൾ കാണുകയും ചെയ്യും.  
   ![Connected repositories](../../../../translated_images/ml/repo-connected.9e5c21ee789fdcaa.webp)

---

## സ്വയം വിവർത്തനം തുടങ്ങുക

1. നിങ്ങൾ കണക്റ്റ് ചെയ്ത റീപ്പോസിറ്ററി തിരഞ്ഞെടുക്കുക.  
   ![Select repository](../../../../translated_images/ml/select-repo-to-detail.55e53233531f8518.webp)

2. റീപ്പോസിറ്ററി വിശദമായ പേജിൽ താഴെ **Edit** തിരഞ്ഞെടുക്കുക.  
   ![Select edit](../../../../translated_images/ml/select-edit.225184c8c46d7001.webp)

3. നിങ്ങളുടെ വിവർത്തന ക്രമീകരണങ്ങൾ സജ്ജമാക്കുക — ലക്ഷ്യ ബ്രാഞ്ച് (ഡീഫാൾട്ട്: `main`), ലക്ഷ്യ ഭാഷകൾ, സോഴ്സ് ഭാഷ (ഡീഫാൾട്ട്: `en`). **Save** തിരഞ്ഞെടുക്കുക.  
   ![Configure translation settings](../../../../translated_images/ml/configuration.ab55d0f8bab5711b.webp)

4. **Start & Automate** തിരഞ്ഞെടുക്കുക.  
   Localizeflow ഇനി സോഴ്സ് മാറ്റം വന്നപ്പൊഴും നിങ്ങളുടെ ഡോക്യുമെന്റേഷൻ സ്വയം വിവർത്തനം ചെയ്ത് പുൽ റിക്വസ്റ്റ് തുറക്കും.  
   ![Start & Automate](../../../../translated_images/ml/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**അസൂയാകൂട്ട്**:  
ഈ ഡോക്യുമെന്റ് AI വിവർത്തന സേവനം [Co-op Translator](https://github.com/Azure/co-op-translator) ഉപയോഗിച്ച് വിവർത്തനം ചെയ്തതാണ്. നാം കൃത്യതയ്ക്ക് പ്രയത്‌നം ചെയ്യുമ്പോഴും, സ്വയംമാറ്റം ചെയ്ത വിവർത്തനങ്ങളിൽ തെറ്റുകൾ അല്ലെങ്കിൽ തെറ്റിദ്ധാരണകൾ ഉണ്ടായിരിക്കാം എന്ന് മനസ്സിലാക്കിയിരിക്കണം. അതിന്റെ മാതൃഭാഷയിലെ ആദ്യരൂപം ഔദ്യോഗിക സ്രോതസ്സായി കണക്കാക്കണം. ഗുരുതരമായ വിവരങ്ങൾക്കായി പ്രൊഫഷണൽ മനുഷ്യ വിവർത്തനം നിർദ്ദേശിക്കുന്നു. ഈ വിവർത്തനത്തിന്റെ ഉപയോഗത്തിൽ ഉണ്ടായേക്കാവുന്ന ഏതെങ്കിലും തെറ്റുള്ള മനസ്സിലാക്കലുകളും തെറ്റിദ്ധാരണകളും സംബന്ധിച്ച് ഞങ്ങൾ ഉത്തരവാദികളല്ല.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->