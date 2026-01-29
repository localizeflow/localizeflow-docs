# Localizeflow – فوری رہنمائی

#### کے تعاون سے [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](./README.md) | [Vietnamese](../vi/README.md)

> **کیا آپ مقامی کلوننگ کو ترجیح دیتے ہیں؟**

> اس مخزن میں 50+ زبانوں کے تراجم شامل ہیں جو ڈاؤن لوڈ سائز کو نمایاں طور پر بڑھاتے ہیں۔ بغیر تراجم کے کلون کرنے کے لیے sparse checkout استعمال کریں:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> یہ آپ کو وہ سب کچھ دیتا ہے جو آپ کو کورس مکمل کرنے کے لیے چاہیئے، اس کے ساتھ ڈاؤن لوڈ بہت تیز ہوجاتا ہے۔
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow خود بخود آپ کی دستاویزات کا ترجمہ کرتا ہے اور جب بھی ماخذ فائل میں تبدیلی آتی ہے، پل ریکویسٹ کھول دیتا ہے۔  
یہ رہنمائی آپ کو دکھاتی ہے کہ GitHub ایپ کو کیسے انسٹال کیا جائے اور دو منٹ سے بھی کم وقت میں اپنی پہلی ترجمہ کاری کیسے چلائی جائے۔


> [!NOTE]
>
> Localizeflow اس وقت صرف GitHub پر مبنی دستاویزات کے پروجیکٹس کی مدد کرتا ہے  
> (مثال کے طور پر: AI for Beginners اور زیادہ تر معیاری اوپن سورس مخزن)۔  
> 
> جدید دستاویزات کے فریم ورکس جیسے Astro، Docusaurus، اور Hugo کے لیے سپورٹ  
> زیر ترقی ہے۔


---

## سائن ان کریں اور GitHub ایپ انسٹال کریں

1. دورہ کریں **[localizeflow.com](https://localizeflow.com/)**۔
2. منتخب کریں **Start with free trial**۔  
   ![Select Start with free trial](../../../../translated_images/ur/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. منتخب کریں **Sign in with GitHub**۔  
   ![Sign in with GitHub](../../../../translated_images/ur/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. اپنے GitHub اکاؤنٹ سے سائن ان کریں۔  
   ![GitHub login](../../../../translated_images/ur/github-login.02bbaee0270b292e.webp)
5. وہ اکاؤنٹ منتخب کریں جہاں آپ Localizeflow GitHub App انسٹال کرنا چاہتے ہیں — آپ کا ذاتی اکاؤنٹ یا کوئی تنظیم جس کا آپ انتظام کرتے ہیں۔  
   ![Select account](../../../../translated_images/ur/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. وہ repositories منتخب کریں جن تک آپ چاہتے ہیں کہ Localizeflow رسائی حاصل کرے، پھر **Save** منتخب کریں۔  
   ![Select repo and save](../../../../translated_images/ur/select-repo-and-save.5a95ae288aefec6e.webp)
7. آپ کو Localizeflow ہوم پیج پر ری ڈائریکٹ کیا جائے گا۔

> [!TIP]
> بعد میں مزید repositories شامل کرنے کے لیے، ہیدر میں اپنا اکاؤنٹ منتخب کریں اور **+ Add more repositories** منتخب کریں۔  
> ![Add more repositories](../../../../translated_images/ur/add-more-repo.2ca5154473aaaafb.webp)

---

## اپنے repositories کو Localizeflow سے منسلک کریں

1. Localizeflow ہوم پیج پر، منتخب کریں **+ Connect repositories**۔  
   ![Select connect repositories](../../../../translated_images/ur/select-connect-repos.8ac6f96f77dcc62c.webp)

2. انسٹال شدہ repositories میں سے جسے آپ منسلک کرنا چاہتے ہیں اسے منتخب کریں اور **Save** منتخب کریں۔  
   ![Select repository](../../../../translated_images/ur/select-repo.dce94db722b44cf3.webp)

3. آپ کے منسلک repositories اب ہوم پیج اور repositories صفحہ دونوں پر ظاہر ہوں گے۔  
   ![Connected repositories](../../../../translated_images/ur/repo-connected.9e5c21ee789fdcaa.webp)

---

## خودکار ترجمہ شروع کریں

1. حال ہی میں منسلک شدہ repository منتخب کریں۔  
   ![Select repository](../../../../translated_images/ur/select-repo-to-detail.55e53233531f8518.webp)

2. repository تفصیل کے صفحہ پر نیچے **Edit** منتخب کریں۔  
   ![Select edit](../../../../translated_images/ur/select-edit.225184c8c46d7001.webp)

3. ترجمہ کی ترتیبات ترتیب دیں — ہدف شاخ (ڈیفالٹ: `main`)، ہدف زبانیں، اور ماخذ زبان (ڈیفالٹ: `en`)۔ پھر **Save** منتخب کریں۔  
   ![Configure translation settings](../../../../translated_images/ur/configuration.ab55d0f8bab5711b.webp)

4. منتخب کریں **Start & Automate**۔  
   اب Localizeflow خود بخود آپ کی دستاویزات کا ترجمہ کرے گا اور جب بھی ماخذ میں تبدیلی ہوگی تو پل ریکویسٹ کھولے گا۔  
   ![Start & Automate](../../../../translated_images/ur/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**تنبیہہ**:  
یہ دستاویز AI ترجمہ سروس [Co-op Translator](https://github.com/Azure/co-op-translator) کے ذریعے ترجمہ کی گئی ہے۔ اگرچہ ہم درستگی کے لیے کوشاں ہیں، براہ کرم اس بات کا خیال رکھیں کہ خودکار تراجم میں غلطیاں یا بے ضابطگیاں ہو سکتی ہیں۔ اصل دستاویز اپنی مادری زبان میں ہی معتبر ماخذ سمجھی جانی چاہیے۔ اہم معلومات کے لیے ماہر انسانی ترجمہ کی سفارش کی جاتی ہے۔ اس ترجمہ کے استعمال سے پیدا ہونے والی کسی بھی غلط فہمی یا غلط تعبیر کی ذمہ داری ہم پر نہیں ہے۔
<!-- CO-OP TRANSLATOR DISCLAIMER END -->