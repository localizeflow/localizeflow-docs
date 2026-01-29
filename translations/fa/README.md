# Localizeflow – راهنمای شروع سریع

#### پشتیبانی شده توسط [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](./README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **ترجیح می‌دهید به‌صورت محلی کلون کنید؟**

> این مخزن شامل بیش از ۵۰ ترجمه زبان است که به طور قابل توجهی حجم دانلود را افزایش می‌دهد. برای کلون کردن بدون ترجمه‌ها از sparse checkout استفاده کنید:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> این به شما همه چیز لازم برای کامل کردن دوره را با دانلود بسیار سریع‌تر می‌دهد.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow به طور خودکار مستندات شما را ترجمه کرده و هر زمان که فایل منبع تغییر کند درخواست‌های پول را باز می‌کند.  
این راهنما به شما نشان می‌دهد چگونه اپلیکیشن GitHub را نصب کرده و در کمتر از ۲ دقیقه اولین ترجمه خود را اجرا کنید.


> [!NOTE]
>
> Localizeflow در حال حاضر پروژه‌های مستندسازی مبتنی بر GitHub را پشتیبانی می‌کند  
> (برای مثال: AI for Beginners و بیشتر مخازن متن‌باز استاندارد).  
>  
> پشتیبانی از فریمورک‌های مدرن مستندسازی مانند Astro، Docusaurus و Hugo  
> در حال توسعه فعال است.


---

## ورود به سیستم و نصب اپلیکیشن GitHub

1. به **[localizeflow.com](https://localizeflow.com/)** مراجعه کنید.
2. گزینه **شروع با دوره آزمایشی رایگان** را انتخاب کنید.
   ![Select Start with free trial](../../../../translated images/fa/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. گزینه **ورود با GitHub** را انتخاب کنید.  
   ![Sign in with GitHub](../../../../translated images/fa/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. با حساب GitHub خود وارد شوید.  
   ![GitHub login](../../../../translated images/fa/github-login.02bbaee0270b292e.webp)
5. حسابی که می‌خواهید اپلیکیشن Localizeflow GitHub را روی آن نصب کنید انتخاب کنید — حساب شخصی خود یا سازمانی که مدیریت می‌کنید.  
   ![Select account](../../../../translated images/fa/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. مخازنی که می‌خواهید Localizeflow به آنها دسترسی داشته باشد انتخاب کرده و سپس **ذخیره** را بزنید.  
   ![Select repo and save](../../../../translated images/fa/select-repo-and-save.5a95ae288aefec6e.webp)
7. به صفحه اصلی Localizeflow هدایت خواهید شد.

> [!TIP]
> برای افزودن مخازن بیشتر بعداً، حساب خود را در هدر انتخاب کرده و گزینه **+ افزودن مخازن بیشتر** را بزنید.  
> ![Add more repositories](../../../../translated images/fa/add-more-repo.2ca5154473aaaafb.webp)

---

## اتصال مخازن به Localizeflow

1. در صفحه اصلی Localizeflow، گزینه **+ اتصال مخازن** را انتخاب کنید.  
   ![Select connect repositories](../../../../translated images/fa/select-connect-repos.8ac6f96f77dcc62c.webp)

2. یکی از مخازن نصب شده که می‌خواهید متصل کنید را انتخاب کرده و **ذخیره** را بزنید.  
   ![Select repository](../../../../translated images/fa/select-repo.dce94db722b44cf3.webp)

3. حالا مخازن متصل شما در صفحه اصلی و صفحه مخازن نمایش داده خواهند شد.  
   ![Connected repositories](../../../../translated images/fa/repo-connected.9e5c21ee789fdcaa.webp)

---

## شروع ترجمه خودکار

1. مخزنی را که تازه متصل کرده‌اید انتخاب کنید.  
   ![Select repository](../../../../translated images/fa/select-repo-to-detail.55e53233531f8518.webp)

2. در صفحه جزئیات مخزن، گزینه **ویرایش** در پایین صفحه را انتخاب کنید.  
   ![Select edit](../../../../translated images/fa/select-edit.225184c8c46d7001.webp)

3. تنظیمات ترجمه خود را پیکربندی کنید — شاخه هدف (پیش‌فرض: `main`)، زبان‌های هدف، و زبان منبع (پیش‌فرض: `en`). سپس **ذخیره** را بزنید.  
   ![Configure translation settings](../../../../translated images/fa/configuration.ab55d0f8bab5711b.webp)

4. گزینه **شروع و خودکارسازی** را انتخاب کنید.  
   اکنون Localizeflow مستندات شما را به صورت خودکار ترجمه کرده و هر زمان منبع تغییر کند درخواست‌های پول را باز می‌کند.  
   ![Start & Automate](../../../../translated images/fa/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**سلب مسئولیت**:  
این سند با استفاده از سرویس ترجمه هوش مصنوعی [Co-op Translator](https://github.com/Azure/co-op-translator) ترجمه شده است. در حالی که ما برای دقت تلاش می‌کنیم، لطفاً توجه داشته باشید که ترجمه‌های خودکار ممکن است حاوی خطا یا نادرستی باشند. سند اصلی در زبان بومی خود باید به عنوان منبع معتبر در نظر گرفته شود. برای اطلاعات حیاتی، ترجمه حرفه‌ای توسط انسان توصیه می‌شود. ما مسئول هیچگونه سو تفاهم یا تفسیر نادرست ناشی از استفاده از این ترجمه نیستیم.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->