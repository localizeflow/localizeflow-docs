# Localizeflow – فوری آغاز کی رہنمائی

#### حمایت یافتہ بذریعہ [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](./README.md) | [Vietnamese](../vi/README.md)

> **مقامی طور پر کلون کرنا پسند ہے؟**

> یہ ریپوزیٹری 50+ زبانوں میں تراجم شامل کرتی ہے جو ڈاؤن لوڈ سائز کو نمایاں طور پر بڑھا دیتی ہیں۔ تراجم کے بغیر کلون کرنے کے لیے sparse checkout استعمال کریں:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> یہ آپ کو کورس مکمل کرنے کے لیے سب کچھ دیتا ہے اور ڈاؤن لوڈ بہت تیز ہو جاتا ہے۔
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow آپ کی دستاویزات کو خود بخود ترجمہ کرتا ہے اور سورس فائل میں تبدیلی پر پل ریکوئسٹ کھول دیتا ہے۔  
یہ رہنمائی آپ کو دکھاتی ہے کہ کیسے GitHub ایپ انسٹال کریں اور 2 منٹ سے کم وقت میں اپنی پہلی ترجمہ چلائیں۔

> [!NOTE]
>
> Localizeflow اس وقت GitHub پر مبنی دستاویزی منصوبوں کی حمایت کرتا ہے  
> (مثال کے طور پر: AI for Beginners اور زیادہ تر معیاری اوپن سورس ریپوز)۔  
> 
> Astro، Docusaurus، اور Hugo جیسے جدید دستاویزی فریم ورکس کے لیے حمایت فعال ترقی میں ہے۔

---

## سائن ان کریں اور GitHub ایپ انسٹال کریں

1. **[localizeflow.com](https://localizeflow.com/)** پر جائیں۔
2. **Start with free trial** منتخب کریں۔  
   ![Start with free trial منتخب کریں](../../../../translated images/ur/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **Sign in with GitHub** منتخب کریں۔  
   ![GitHub کے ساتھ سائن ان کریں](../../../../translated images/ur/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. اپنے GitHub اکاؤنٹ سے سائن ان کریں۔  
   ![GitHub میں لاگ ان](../../../../translated images/ur/github-login.02bbaee0270b292e.webp)
5. وہ اکاؤنٹ منتخب کریں جہاں آپ Localizeflow GitHub ایپ انسٹال کرنا چاہتے ہیں — آپ کا ذاتی اکاؤنٹ یا کوئی تنظیم جسے آپ مینج کرتے ہیں۔  
   ![اکاؤنٹ منتخب کریں](../../../../translated images/ur/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. وہ repositories منتخب کریں جن تک آپ چاہتے ہیں کہ Localizeflow رسائی حاصل کرے، پھر **Save** منتخب کریں۔  
   ![ریپوز منتخب کریں اور سیو کریں](../../../../translated images/ur/select-repo-and-save.5a95ae288aefec6e.webp)
7. آپ کو Localizeflow کے ہوم پیج پر ری ڈائریکٹ کیا جائے گا۔

> [!TIP]
> بعد میں مزید repositories شامل کرنے کے لیے، ہیڈر میں اپنا اکاؤنٹ منتخب کریں اور **+ Add more repositories** منتخب کریں۔  
> ![مزید ریپوز شامل کریں](../../../../translated images/ur/add-more-repo.2ca5154473aaaafb.webp)

---

## اپنے repositories کو Localizeflow سے جوڑیں

1. Localizeflow کے ہوم پیج پر **+ Connect repositories** منتخب کریں۔  
   ![Connect repositories منتخب کریں](../../../../translated images/ur/select-connect-repos.8ac6f96f77dcc62c.webp)

2. اپنی انسٹال شدہ repositories میں سے جسے آپ جوڑنا چاہتے ہیں اسے منتخب کریں اور **Save** منتخب کریں۔  
   ![ریپوز منتخب کریں](../../../../translated images/ur/select-repo.dce94db722b44cf3.webp)

3. آپ کی جڑی ہوئی repositories اب ہوم پیج اور repositories کے صفحہ دونوں پر نظر آئیں گی۔  
   ![جڑی ہوئی repositories](../../../../translated images/ur/repo-connected.9e5c21ee789fdcaa.webp)

---

## خودکار ترجمہ شروع کریں

1. وہ repository منتخب کریں جو آپ نے ابھی جوڑا ہے۔  
   ![ریپوز منتخب کریں](../../../../translated images/ur/select-repo-to-detail.55e53233531f8518.webp)

2. repository تفصیلات کے صفحے پر نیچے **Edit** منتخب کریں۔  
   ![Edit منتخب کریں](../../../../translated images/ur/select-edit.225184c8c46d7001.webp)

3. اپنی ترجمہ کی ترتیبات ترتیب دیں — ہدف برانچ (ڈیفالٹ: `main`)، ہدف زبانیں، اور سورس زبان (ڈیفالٹ: `en`)۔ پھر **Save** منتخب کریں۔  
   ![ترجمہ کی ترتیبات ترتیب دیں](../../../../translated images/ur/configuration.ab55d0f8bab5711b.webp)

4. **Start & Automate** منتخب کریں۔  
   Localizeflow اب آپ کی دستاویزات کو خود بخود ترجمہ کرے گا اور سورس میں تبدیلی پر پل ریکوئسٹ کھولے گا۔  
   ![Start & Automate منتخب کریں](../../../../translated images/ur/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**دستخطی نوٹ**:  
یہ دستاویز AI ترجمے کی سروس [Co-op Translator](https://github.com/Azure/co-op-translator) کے ذریعے ترجمہ کی گئی ہے۔ اگرچہ ہم درستگی کی کوشش کرتے ہیں، براہ کرم آگاہ رہیں کہ خودکار ترجمے میں غلطیاں یا نقائص ہو سکتے ہیں۔ اصل دستاویز اپنی مادری زبان میں معتبر ذریعہ سمجھی جائے۔ اہم معلومات کے لیے پیشہ ور انسانی ترجمہ کی سفارش کی جاتی ہے۔ اس ترجمے کے استعمال سے پیدا ہونے والی کسی بھی غلط فہمی یا معنوی غلطی کی ذمہ داری ہم پر عائد نہیں ہوتی۔
<!-- CO-OP TRANSLATOR DISCLAIMER END -->