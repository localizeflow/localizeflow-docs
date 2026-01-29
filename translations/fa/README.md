# Localizeflow – راهنمای شروع سریع

#### تحت پشتیبانی [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](./README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **ترجیح می‌دهید به صورت محلی کلون کنید؟**

> این مخزن دارای بیش از ۵۰ ترجمه زبان است که حجم دانلود را به طور قابل توجهی افزایش می‌دهد. برای کلون بدون ترجمه‌ها، از sparse checkout استفاده کنید:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> این به شما همه چیز لازم برای تکمیل دوره با دانلود بسیار سریع‌تر را می‌دهد.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow به صورت خودکار مستندات شما را ترجمه می‌کند و هر بار که فایل منبع تغییر کند، درخواست pull ایجاد می‌کند.  
این راهنما به شما نشان می‌دهد چگونه برنامه GitHub را نصب کنید و اولین ترجمه خود را در کمتر از ۲ دقیقه اجرا کنید.


> [!NOTE]
>
> در حال حاضر Localizeflow از پروژه‌های مستندسازی مبتنی بر GitHub پشتیبانی می‌کند  
> (مثلاً: AI for Beginners و بیشتر مخازن استاندارد متن‌باز).  
> 
> پشتیبانی از فریم‌ورک‌های مدرن مستندسازی مانند Astro، Docusaurus و Hugo  
> در حال توسعه فعال است.


---

## ورود و نصب برنامه GitHub

۱. به **[localizeflow.com](https://localizeflow.com/)** مراجعه کنید.  
۲. گزینه **Start with free trial** را انتخاب کنید.  
   ![Select Start with free trial](../../../../translated_images/fa/select-start-with-free-trial.6c2e287133ff9c8b.webp)  
۳. گزینه **Sign in with GitHub** را انتخاب کنید.  
   ![Sign in with GitHub](../../../../translated_images/fa/select-sign-in-with-github.f2850ffdd49cc894.webp)  
۴. با حساب GitHub خود وارد شوید.  
   ![GitHub login](../../../../translated_images/fa/github-login.02bbaee0270b292e.webp)  
۵. حسابی که می‌خواهید برنامه Localizeflow GitHub روی آن نصب شود را انتخاب کنید — حساب شخصی خود یا سازمانی که مدیریت می‌کنید.  
   ![Select account](../../../../translated_images/fa/select-which-account-to-use.7050f5ed0b773bb0.webp)  
۶. مخازنی که می‌خواهید Localizeflow به آن‌ها دسترسی داشته باشد را انتخاب کرده، سپس **Save** را بزنید.  
   ![Select repo and save](../../../../translated_images/fa/select-repo-and-save.5a95ae288aefec6e.webp)  
۷. به صفحه اصلی Localizeflow هدایت خواهید شد.

> [!TIP]
> برای افزودن مخازن بیشتر بعداً، حساب خود را از هدر انتخاب کرده و **+ Add more repositories** را بزنید.  
> ![Add more repositories](../../../../translated_images/fa/add-more-repo.2ca5154473aaaafb.webp)

---

## اتصال مخازن به Localizeflow

۱. در صفحه اصلی Localizeflow، گزینه **+ Connect repositories** را انتخاب کنید.  
   ![Select connect repositories](../../../../translated_images/fa/select-connect-repos.8ac6f96f77dcc62c.webp)

۲. یکی از مخازن نصب شده‌ای که می‌خواهید متصل کنید را انتخاب کرده و **Save** را بزنید.  
   ![Select repository](../../../../translated_images/fa/select-repo.dce94db722b44cf3.webp)

۳. مخازن متصل شده شما اکنون هم در صفحه اصلی و هم در صفحه مخازن نمایش داده خواهند شد.  
   ![Connected repositories](../../../../translated_images/fa/repo-connected.9e5c21ee789fdcaa.webp)

---

## شروع ترجمه خودکار

۱. مخزن تازه متصل شده را انتخاب کنید.  
   ![Select repository](../../../../translated_images/fa/select-repo-to-detail.55e53233531f8518.webp)

۲. در صفحه جزئیات مخزن، گزینه **Edit** در پایین را انتخاب کنید.  
   ![Select edit](../../../../translated_images/fa/select-edit.225184c8c46d7001.webp)

۳. تنظیمات ترجمه خود را پیکربندی کنید — شاخه هدف (پیش‌فرض: `main`)، زبان‌های هدف، و زبان منبع (پیش‌فرض: `en`). سپس **Save** را انتخاب کنید.  
   ![Configure translation settings](../../../../translated_images/fa/configuration.ab55d0f8bab5711b.webp)

۴. گزینه **Start & Automate** را انتخاب کنید.  
   اکنون Localizeflow مستندات شما را به صورت خودکار ترجمه می‌کند و هر بار که منبع تغییر کند، درخواست pull باز می‌کند.  
   ![Start & Automate](../../../../translated_images/fa/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**سلب مسئولیت**:
این سند با استفاده از سرویس ترجمه هوش مصنوعی [Co-op Translator](https://github.com/Azure/co-op-translator) ترجمه شده است. در حالی که ما به دقت تلاش می‌کنیم، لطفاً توجه داشته باشید که ترجمه‌های خودکار ممکن است شامل خطاها یا نواقصی باشند. سند اصلی به زبان بومی خود باید به عنوان منبع معتبر در نظر گرفته شود. برای اطلاعات حیاتی، استفاده از ترجمه حرفه‌ای انسانی توصیه می‌شود. ما مسئول هیچ گونه سوء تفاهم یا برداشت نادرست ناشی از استفاده از این ترجمه نیستیم.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->