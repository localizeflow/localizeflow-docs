# Localizeflow – מדריך התחלה מהירה

#### נתמך על ידי [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](./README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **מעדיפים לשכפל מקומית?**

> מאגר זה כולל מעל ל-50 שפות תרגום, מה שמגדיל משמעותית את גודל ההורדה. על מנת לשכפל בלי תרגומים, השתמשו ב- sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> זה נותן לכם את כל מה שצריך כדי להשלים את הקורס במהירות הורדה גבוהה בהרבה.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow מתרגם אוטומטית את התיעוד שלכם ופותח בקשות משיכה בכל פעם שקובץ המקור משתנה.  
מדריך זה מראה לכם כיצד להתקין את אפליקציית GitHub ולהריץ את התרגום הראשון שלכם בפחות משתי דקות.


> [!NOTE]
>
> Localizeflow תומך כרגע בפרויקטים של תיעוד מבוססי GitHub  
> (למשל: AI for Beginners ורוב המאגרי הקוד הפתוח הסטנדרטיים).  
> 
> התמיכה במסגרת תיעוד מודרנית כמו Astro, Docusaurus ו-Hugo  
> נמצאת בפיתוח פעיל.


---

## התחברו והתקינו את אפליקציית GitHub

1. בקרו ב- **[localizeflow.com](https://localizeflow.com/)**.
2. בחרו **התחל בניסיון חינם**.  
   ![בחר התחלה בניסיון חינם](../../../../translated images/he/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. בחרו **התחבר עם GitHub**.  
   ![התחבר עם GitHub](../../../../translated images/he/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. התחברו עם חשבון ה-GitHub שלכם.  
   ![כניסה ל-GitHub](../../../../translated images/he/github-login.02bbaee0270b292e.webp)
5. בחרו את החשבון שבו תרצו להתקין את Localizeflow — החשבון האישי שלכם או ארגון שאתם מנהלים.  
   ![בחר חשבון](../../../../translated images/he/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. בחרו את המאגרי הקוד שאליהם תרצו ש-Localizeflow יקבל גישה, ואז בחרו **שמור**.  
   ![בחר מאגר ושמור](../../../../translated images/he/select-repo-and-save.5a95ae288aefec6e.webp)
7. תתו redirected לעמוד הבית של Localizeflow.

> [!TIP]
> כדי להוסיף מאגרי קוד נוספים מאוחר יותר, בחרו את החשבון בכותרת העליונה ובחרו **+ הוסף מאגרי קוד נוספים**.  
> ![הוספת מאגרים נוספים](../../../../translated images/he/add-more-repo.2ca5154473aaaafb.webp)

---

## קשרו את מאגרי הקוד שלכם ל-Localizeflow

1. בעמוד הבית של Localizeflow, בחרו **+ חיבור מאגרים**.  
   ![בחר חיבור מאגרים](../../../../translated images/he/select-connect-repos.8ac6f96f77dcc62c.webp)

2. בחרו אחד ממאגרי הקוד שהותקנו שברצונכם לחבר ולחצו על **שמור**.  
   ![בחר מאגר](../../../../translated images/he/select-repo.dce94db722b44cf3.webp)

3. מאגרי הקוד המחוברים שלכם יופיעו כעת גם בעמוד הבית וגם בעמוד מאגרי הקוד.  
   ![מאגרי קוד מחוברים](../../../../translated images/he/repo-connected.9e5c21ee789fdcaa.webp)

---

## התחילו תרגום אוטומטי

1. בחרו את מאגר הקוד שחיברתם כרגע.  
   ![בחר מאגר](../../../../translated images/he/select-repo-to-detail.55e53233531f8518.webp)

2. בעמוד פרטי המאגר, בחרו **ערוך** בתחתית.  
   ![בחר ערוך](../../../../translated images/he/select-edit.225184c8c46d7001.webp)

3. הגדירו את הגדרות התרגום שלכם — סניף יעד (ברירת מחדל: `main`), שפות יעד, ושפת המקור (ברירת מחדל: `en`). בחרו **שמור**.  
   ![הגדרות תרגום](../../../../translated images/he/configuration.ab55d0f8bab5711b.webp)

4. בחרו **התחל והפעל אוטומציה**.  
   Localizeflow יתחיל לתרגם אוטומטית את התיעוד ויפתח בקשות משיכה בכל פעם שהמקור משתנה.  
   ![התחל והפעל אוטומציה](../../../../translated images/he/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**כתב ויתור**:  
מסמך זה תורגם באמצעות שירות תרגום מבוסס בינה מלאכותית [Co-op Translator](https://github.com/Azure/co-op-translator). למרות שאנו שואפים לדיוק, יש להכיר בכך שתרגומים אוטומטיים עשויים להכיל שגיאות או אי-דיוקים. יש לראות במסמך המקורי בשפתו המקורית את המקור הסמכותי. עבור מידע קריטי, מומלץ להשתמש בתרגום מקצועי על ידי בני אדם. איננו אחראים לכל אי-הבנות או פרשנויות שגויות הנובעות משימוש בתרגום זה.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->