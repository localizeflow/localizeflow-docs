# Localizeflow – מדריך התחלה מהירה

#### בתמיכה של [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](./README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **מעדיפים לשכפל מקומית?**

> מאגר זה כולל יותר מ-50 שפות תרגום שמגבירות משמעותית את גודל ההורדה. כדי לשכפל ללא תרגומים, השתמשו ב-sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> זה נותן לכם את כל מה שצריך כדי להשלים את הקורס עם הורדה הרבה יותר מהירה.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow מתרגם אוטומטית את התיעוד שלכם ופותח בקשות משיכה בכל פעם שקובץ המקור משתנה.  
מדריך זה מראה לכם כיצד להתקין את אפליקציית GitHub ולהריץ את התרגום הראשון שלכם בפחות מ-2 דקות.


> [!NOTE]
>
> Localizeflow תומך כיום בפרויקטי תיעוד מבוססי GitHub  
> (למשל: AI for Beginners ורוב המאגרי קוד הפתוחים הסטנדרטיים).  
> 
> התמיכה במסגרת תיעוד מודרנית כמו Astro, Docusaurus ו-Hugo  
> נמצאת בפיתוח פעיל.


---

## התחברו והתקינו את אפליקציית GitHub

1. בקרו ב-**[localizeflow.com](https://localizeflow.com/)**.  
2. בחרו ב-**Start with free trial**.  
   ![Select Start with free trial](../../../../translated_images/he/select-start-with-free-trial.6c2e287133ff9c8b.webp)  
3. בחרו ב-**Sign in with GitHub**.  
   ![Sign in with GitHub](../../../../translated_images/he/select-sign-in-with-github.f2850ffdd49cc894.webp)  
4. התחברו באמצעות חשבון GitHub שלכם.  
   ![GitHub login](../../../../translated_images/he/github-login.02bbaee0270b292e.webp)  
5. בחרו את החשבון שבו תרצו להתקין את אפליקציית Localizeflow — חשבון אישי שלכם או ארגון שאתם מנהלים.  
   ![Select account](../../../../translated_images/he/select-which-account-to-use.7050f5ed0b773bb0.webp)  
6. בחרו את המאגר(ים) שאליהם תרצו ש-Localizeflow יקבל גישה, ואז בחרו **Save**.  
   ![Select repo and save](../../../../translated_images/he/select-repo-and-save.5a95ae288aefec6e.webp)  
7. תועברו חזרה לדף הבית של Localizeflow.

> [!TIP]  
> כדי להוסיף מאגרים נוספים מאוחר יותר, בחרו את החשבון שלכם בכותרת ובחרו **+ Add more repositories**.  
> ![Add more repositories](../../../../translated_images/he/add-more-repo.2ca5154473aaaafb.webp)

---

## חברו את המאגרים שלכם ל-Localizeflow

1. בדף הבית של Localizeflow, בחרו **+ Connect repositories**.  
   ![Select connect repositories](../../../../translated_images/he/select-connect-repos.8ac6f96f77dcc62c.webp)

2. בחרו אחד מהמאגרים שהתקנתם שברצונכם לחבר, ובחרו **Save**.  
   ![Select repository](../../../../translated_images/he/select-repo.dce94db722b44cf3.webp)

3. המאגרים המחוברים שלכם יוצגו כעת גם בדף הבית וגם בדף המאגרים.  
   ![Connected repositories](../../../../translated_images/he/repo-connected.9e5c21ee789fdcaa.webp)

---

## התחילו את התרגום האוטומטי

1. בחרו את המאגר שהתחברתם אליו כעת.  
   ![Select repository](../../../../translated_images/he/select-repo-to-detail.55e53233531f8518.webp)

2. בדף פרטי המאגר, בחרו **Edit** בתחתית.  
   ![Select edit](../../../../translated_images/he/select-edit.225184c8c46d7001.webp)

3. הגדרו את הגדרות התרגום שלכם — ענף היעד (ברירת מחדל: `main`), שפות היעד ושפת המקור (ברירת מחדל: `en`). בחרו **Save**.  
   ![Configure translation settings](../../../../translated_images/he/configuration.ab55d0f8bab5711b.webp)

4. בחרו **Start & Automate**.  
   Localizeflow יתחיל לתרגם אוטומטית את התיעוד ויפתח בקשות משיכה בכל שינוי במקור.  
   ![Start & Automate](../../../../translated_images/he/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**כתב גילוי נאות**:
מסמך זה תורגם תוך שימוש בשירות תרגום מבוסס בינה מלאכותית [Co-op Translator](https://github.com/Azure/co-op-translator). למרות שאנו שואפים לדיוק, יש לשים לב כי תרגומים אוטומטיים עלולים להכיל שגיאות או אי-דיוקים. המסמך המקורי בשפתו המקורית מהווה את המקור המהימן והסמכותי. למידע קריטי מומלץ להשתמש בשירותי תרגום מקצועיים על ידי מתרגמים אנושיים. אנו לא נושאים באחריות לכל אי-הבנה או פרשנות שגויה הנובעת משימוש בתרגום זה.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->