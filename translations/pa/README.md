# Localizeflow – ਤਰਤੀਬੀ ਸ਼ੁਰੂਆਤੀ ਗਾਈਡ

#### ਸਹਿਯੋਗ [Localizeflow](https://localizeflow.com/) ਵੱਲੋਂ

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](./README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **ਕੀ ਤੁਸੀਂ ਸਥਾਨਕ ਤੌਰ 'ਤੇ ਕਲੋਨ ਕਰਨਾ ਪਸੰਦ ਕਰਦੇ ਹੋ?**

> ਇਹ repository 50+ ਭਾਸ਼ਾ ਅਨੁਵਾਦਾਂ ਨੂੰ ਸ਼ਾਮਲ ਕਰਦਾ ਹੈ ਜਿਸ ਨਾਲ ਡਾਊਨਲੋਡ ਦਾ ਆਕਾਰ ਕਾਫੀ ਵਧ ਜਾਂਦਾ ਹੈ। ਬਿਨਾਂ ਅਨੁਵਾਦਾਂ ਦੇ ਕਲੋਨ ਕਰਨ ਲਈ, sparse checkout ਵਰਤੋਂ:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> ਇਸ ਨਾਲ ਤੁਹਾਨੂੰ ਕੋਰਸ ਪੂਰਾ ਕਰਨ ਲਈ ਸਾਰੀ ਜ਼ਰੂਰੀ ਚੀਜ਼ਾਂ ਮਿਲ਼ਦੀਆਂ ਹਨ ਤੇ ਡਾਊਨਲੋਡ ਜ਼ਿਆਦਾ ਤੇਜ਼ ਹੋ ਜਾਂਦਾ ਹੈ।
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow ਤੁਹਾਡੇ ਦਸਤਾਵੇਜ਼ਾਂ ਨੂੰ ਆਟੋਮੈਟਿਕ ਤੌਰ 'ਤੇ ਅਨੁਵਾਦ ਕਰਦਾ ਹੈ ਅਤੇ ਜਦੋਂ ਵੀ ਸੋਰਸ ਫਾਇਲ ਬਦਲਦੀ ਹੈ ਤਾਂ ਪੁੱਲ ਰਿਕਵੇਸਟ ਖੋਲ੍ਹਦਾ ਹੈ।  
ਇਹ ਗਾਈਡ ਦਿਖਾਉਂਦਾ ਹੈ ਕਿ GitHub ਐਪ ਨੂੰ ਕਿਵੇਂ ਇੰਸਟਾਲ ਕਰਨਾ ਹੈ ਅਤੇ ਪਹਿਲਾ ਅਨੁਵਾਦ 2 ਮਿੰਟਾਂ ਤੋਂ ਘੱਟ ਸਮੇਂ ਵਿੱਚ ਕਿਵੇਂ ਚਲਾਉਣਾ ਹੈ।


> [!NOTE]
>
> Localizeflow ਇਸ ਸਮੇਂ GitHub ਅਧਾਰਿਤ ਦਸਤਾਵੇਜ਼ ਪ੍ਰੋਜੈਕਟਾਂ ਦਾ ਸਮਰਥਨ ਕਰਦਾ ਹੈ  
> (ਉਦਾਹਰਣ ਲਈ: AI for Beginners ਅਤੇ ਜ਼ਿਆਦਾਤਰ ਸਧਾਰਣ open-source ਰਿਪੋਸ).  
> 
> ਆਪਣੇ ਦਸਤਾਵੇਜ਼ ਫਰੇਮਵਰਕਾਂ ਲਈ ਜਿਵੇਂ ਕਿ Astro, Docusaurus, ਅਤੇ Hugo ਦਾ ਸਮਰਥਨ  
> ਸਰਗਰਮ ਵਿਕਾਸ ਵਿੱਚ ਹੈ।


---

## ਸਾਈਨ ਇਨ ਕਰੋ ਅਤੇ GitHub ਐਪ ਇੰਸਟਾਲ ਕਰੋ

1. ਜਾਓ **[localizeflow.com](https://localizeflow.com/)**.
2. ਚੁਣੋ **Start with free trial**.
   ![Select Start with free trial](../../../../translated images/pa/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. ਚੁਣੋ **Sign in with GitHub**.  
   ![Sign in with GitHub](../../../../translated images/pa/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. ਆਪਣਾ GitHub ਅਕਾਊਂਟ ਨਾਲ ਸਾਈਨ ਇਨ ਕਰੋ।  
   ![GitHub login](../../../../translated images/pa/github-login.02bbaee0270b292e.webp)
5. ਚੁਣੋ ਕਿ ਕਿਸ ਅਕਾਊਂਟ ਵਿੱਚ ਤੁਸੀਂ Localizeflow GitHub ਐਪ ਇੰਸਟਾਲ ਕਰਨਾ ਚਾਹੁੰਦੇ ਹੋ — ਆਪਣਾ ਨਿੱਜੀ ਅਕਾਊਂਟ ਜਾਂ ਤੁਸੀਂ ਜੋ ਔਰਗਨਾਈਜੇਸ਼ਨ ਚਲਾਉਂਦੇ ਹੋ।  
   ![Select account](../../../../translated images/pa/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. ਉਹ ਰਿਪੋਜ਼ਿਟਰੀਆਂ ਚੁਣੋ ਜਿਨ੍ਹਾਂ ਨੂੰ ਤੁਸੀਂ Localizeflow ਨੂੰ ਪਹੁੰਚ ਦੇਣਾ ਚਾਹੁੰਦੇ ਹੋ, ਫਿਰ **Save** ਨੂੰ ਚੁਣੋ।  
   ![Select repo and save](../../../../translated images/pa/select-repo-and-save.5a95ae288aefec6e.webp)
7. ਤੁਹਾਨੂੰ Localizeflow ਮੁੱਖ ਪੰਨਾ ਤੇ ਮੁੜ-ਰਾਹਤ ਦਿੱਤੀ ਜਾਵੇਗੀ।

> [!TIP]
> ਬਾਅਦ ਵਿੱਚ ਹੋਰ ਰਿਪੋਜ਼ਿਟਰੀਆਂ ਸ਼ਾਮਲ ਕਰਨ ਲਈ, ਹੈਡਰ ਵਿੱਚ ਆਪਣੇ ਅਕਾਊਂਟ ਨੂੰ ਚੁਣੋ ਅਤੇ **+ Add more repositories** ਨੂੰ ਚੁਣੋ।  
> ![Add more repositories](../../../../translated images/pa/add-more-repo.2ca5154473aaaafb.webp)

---

## ਆਪਣੇ ਰਿਪੋਜ਼ਿਟਰੀਆਂ ਨੂੰ Localizeflow ਨਾਲ ਜੁੜੋ

1. Localizeflow ਮੁੱਖ ਪੰਨੇ ਤੇ ਜਾਓ, ਫਿਰ **+ Connect repositories** ਨੂੰ ਚੁਣੋ।  
   ![Select connect repositories](../../../../translated images/pa/select-connect-repos.8ac6f96f77dcc62c.webp)

2. ਇੰਸਟਾਲ ਕੀਤੇ ਗਏ ਰਿਪੋਜ਼ਿਟਰੀਆਂ ਵਿੱਚੋਂ ਇੱਕ ਚੁਣੋ ਜਿਸਨੂੰ ਤੁਸੀਂ ਜੁੜਨਾ ਚਾਹੁੰਦੇ ਹੋ ਅਤੇ **Save** ਨੂੰ ਲੱਭੋ।  
   ![Select repository](../../../../translated images/pa/select-repo.dce94db722b44cf3.webp)

3. ਹੁਣ ਤੁਹਾਡੇ ਜੁੜੇ ਹੋਏ ਰਿਪੋਜ਼ਿਟਰੀਆਂ ਮੁੱਖ ਪੰਨੇ ਅਤੇ ਰਿਪੋਜ਼ਿਟਰੀਆਂ ਪੰਨੇ ਦੋਵਾਂ ਤੇ ਦਿਖਾਈ ਦੇਣਗੇ।  
   ![Connected repositories](../../../../translated images/pa/repo-connected.9e5c21ee789fdcaa.webp)

---

## ਆਟੋਮੈਟਿਕ ਅਨੁਵਾਦ ਸ਼ੁਰੂ ਕਰੋ

1. ਉਸ ਰਿਪੋਜ਼ਿਟਰੀ ਨੂੰ ਚੁਣੋ ਜੋ ਤੁਸੀਂ ਹਾਲ ਹੀ ਵਿੱਚ ਜੁੜਾਇਆ ਸੀ।  
   ![Select repository](../../../../translated images/pa/select-repo-to-detail.55e53233531f8518.webp)

2. ਰਿਪੋਜ਼ਿਟਰੀ ਦੇ ਵੇਰਵਾ ਪੰਨੇ ਤੇ, ਹੇਠਾਂ **Edit** ਨੂੰ ਚੁਣੋ।  
   ![Select edit](../../../../translated images/pa/select-edit.225184c8c46d7001.webp)

3. ਆਪਣੀਆਂ ਅਨੁਵਾਦ ਸੈਟਿੰਗਾਂ ਕਨਫਿਗਰ ਕਰੋ — ਟਾਰਗੇਟ ਬ੍ਰਾਂਚ (ਡਿਫੌਲਟ: `main`), ਟਾਰਗੇਟ ਭਾਸ਼ਾਵਾਂ, ਅਤੇ ਸੋਰਸ ਭਾਸ਼ਾ (ਡਿਫੌਲਟ: `en`). ਫਿਰ **Save** ਚੁਣੋ।  
   ![Configure translation settings](../../../../translated images/pa/configuration.ab55d0f8bab5711b.webp)

4. **Start & Automate** ਨੂੰ ਚੁਣੋ।  
   Localizeflow ਹੁਣ ਆਟੋਮੈਟਿਕ ਤੁਹਾਡੇ ਦਸਤਾਵੇਜ਼ਾਂ ਦਾ ਅਨੁਵਾਦ ਕਰੇਗਾ ਅਤੇ ਜਦੋਂ ਵੀ ਸੋਰਸ ਬਦਲੇਗੀ, ਪੁੱਲ ਰਿਕਵੇਸਟ ਖੋਲ੍ਹੇਗਾ।  
   ![Start & Automate](../../../../translated images/pa/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**ਅਸਵੀਕਾਰੋਪੱਤਰ**:
ਇਹ ਦਸਤਾਵੇਜ਼ AI ਅਨੁਵਾਦ ਸੇਵਾ [Co-op Translator](https://github.com/Azure/co-op-translator) ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਅਨੁਵਾਦ ਕੀਤਾ ਗਿਆ ਹੈ। ਜਦੋਂ ਕਿ ਅਸੀਂ ਸਹੀਤਾ ਲਈ ਯਤਨਸ਼ੀਲ ਹਾਂ, ਕਿਰਪਾ ਕਰਕੇ ਧਿਆਨ ਵਿੱਚ ਰੱਖੋ ਕਿ ਆਟੋਮੈਟਿਕ ਅਨੁਵਾਦਾਂ ਵਿੱਚ ਗਲਤੀਆਂ ਜਾਂ ਅਸਥਿਰਤਾਵਾਂ ਹੋ ਸਕਦੀਆਂ ਹਨ। ਮੂਲ ਦਸਤਾਵੇਜ਼ ਆਪਣੇ ਮੂਲ ਭਾਸ਼ਾ ਵਿੱਚ ਅਧਿਕਾਰਿਤ ਸਰੋਤ ਮੰਨਿਆ ਜਾਵੇ। ਮਹੱਤਵਪੂਰਣ ਜਾਣਕਾਰੀ ਲਈ, ਪੇਸ਼ੇਵਰ ਮਨੁੱਖੀ ਅਨੁਵਾਦ ਦੀ ਸਿਫਾਰਸ਼ ਕੀਤੀ ਜਾਂਦੀ ਹੈ। ਅਸੀਂ ਇਸ ਅਨੁਵਾਦ ਦੀ ਵਰਤੋਂ ਤੋਂ ਉਤਪੰਨ ਕਿਸੇ ਵੀ ਗਲਤਫਹਿਮੀ ਜਾਂ ਗਲਤ ਤਰਜਮੇ ਲਈ ਜ਼ਿੰਮੇਵਾਰ ਨਹੀਂ ਹਾਂ।
<!-- CO-OP TRANSLATOR DISCLAIMER END -->