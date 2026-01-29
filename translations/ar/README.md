# Localizeflow – دليل البدء السريع

#### مدعوم من قبل [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](./README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **تفضل النسخ محليًا؟**

> يتضمن هذا المستودع أكثر من 50 ترجمة لغة مما يزيد بشكل كبير من حجم التنزيل. للنسخ بدون الترجمات، استخدم sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> هذا يمنحك كل ما تحتاجه لإكمال الدورة مع تنزيل أسرع بكثير.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

يقوم Localizeflow بترجمة مستنداتك تلقائيًا ويفتح طلبات السحب كلما تم تغيير الملف المصدر.  
يُظهر لك هذا الدليل كيفية تثبيت تطبيق GitHub وتشغيل الترجمة الأولى في أقل من دقيقتين.


> [!NOTE]
>
> يدعم Localizeflow حاليًا مشاريع التوثيق المعتمدة على GitHub  
>(على سبيل المثال: AI for Beginners ومعظم المستودعات مفتوحة المصدر القياسية).  
> 
> الدعم لأُطُر التوثيق الحديثة مثل Astro و Docusaurus و Hugo  
> قيد التطوير النشط.


---

## تسجيل الدخول وتثبيت تطبيق GitHub

1. زر **[localizeflow.com](https://localizeflow.com/)**.
2. اختر **ابدأ بالتجربة المجانية**.
   ![اختر ابدأ بالتجربة المجانية](../../translated_images/ar/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. اختر **تسجيل الدخول بواسطة GitHub**.  
   ![تسجيل الدخول بواسطة GitHub](../../translated_images/ar/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. قم بتسجيل الدخول باستخدام حساب GitHub الخاص بك.  
   ![تسجيل الدخول GitHub](../../translated_images/ar/github-login.02bbaee0270b292e.webp)
5. اختر الحساب الذي تريد تثبيت تطبيق Localizeflow GitHub عليه — حسابك الشخصي أو منظمة تديرها.  
   ![اختر الحساب](../../translated_images/ar/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. اختر المستودعات التي تريد أن يصل إليها Localizeflow، ثم اختر **حفظ**.  
   ![اختر المستودع وحفظ](../../translated_images/ar/select-repo-and-save.5a95ae288aefec6e.webp)
7. سيتم توجيهك إلى الصفحة الرئيسية لـ Localizeflow.

> [!TIP]
> لإضافة المزيد من المستودعات لاحقًا، اختر حسابك في الرأس ثم اختر **+ إضافة المزيد من المستودعات**.  
> ![إضافة المزيد من المستودعات](../../translated_images/ar/add-more-repo.2ca5154473aaaafb.webp)

---

## ربط مستودعاتك بـ Localizeflow

1. في الصفحة الرئيسية لـ Localizeflow، اختر **+ ربط المستودعات**.  
   ![اختر ربط المستودعات](../../translated_images/ar/select-connect-repos.8ac6f96f77dcc62c.webp)

2. اختر أحد المستودعات المثبتة التي تريد ربطها ثم اختر **حفظ**.  
   ![اختر المستودع](../../translated_images/ar/select-repo.dce94db722b44cf3.webp)

3. ستظهر مستودعاتك المربوطة الآن في كل من الصفحة الرئيسية وصفحة المستودعات.  
   ![المستودعات المربوطة](../../translated_images/ar/repo-connected.9e5c21ee789fdcaa.webp)

---

## بدء الترجمة التلقائية

1. اختر المستودع الذي قمت بربطه للتو.  
   ![اختر المستودع](../../translated_images/ar/select-repo-to-detail.55e53233531f8518.webp)

2. في صفحة تفاصيل المستودع، اختر **تحرير** في الأسفل.  
   ![اختر تحرير](../../translated_images/ar/select-edit.225184c8c46d7001.webp)

3. قم بضبط إعدادات الترجمة الخاصة بك — الفرع الهدف (الافتراضي: `main`)، اللغات الهدف، واللغة المصدر (الافتراضي: `en`). اختر **حفظ**.  
   ![ضبط إعدادات الترجمة](../../translated_images/ar/configuration.ab55d0f8bab5711b.webp)

4. اختر **ابدأ والتشغيل الآلي**.  
   سيقوم Localizeflow الآن بترجمة مستنداتك تلقائيًا وفتح طلبات السحب كلما تغير المصدر.  
   ![ابدأ والتشغيل الآلي](../../translated_images/ar/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**تنويه**:  
تمت ترجمة هذا المستند باستخدام خدمة الترجمة الآلية [Co-op Translator](https://github.com/Azure/co-op-translator). بينما نسعى جاهدين لتحقيق الدقة، يرجى العلم أن الترجمات الآلية قد تحتوي على أخطاء أو عدم دقة. يجب اعتبار المستند الأصلي بلغته الأصلية المصدر الرسمي والموثوق. بالنسبة للمعلومات الحساسة أو الهامة، يُنصح بالاستعانة بترجمة بشرية مهنية. نحن غير مسؤولين عن أي سوء فهم أو تفسير ناتج عن استخدام هذه الترجمة.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->