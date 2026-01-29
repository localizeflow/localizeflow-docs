# Localizeflow – Ръководство за бърз старт

#### Поддържано от [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](./README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Предпочитате да клонирате локално?**

> Това хранилище включва 50+ езикови превода, което значително увеличава размера за изтегляне. За да клонирате без преводи, използвайте sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Това ви дава всичко необходимо да завършите курса с много по-бързо изтегляне.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow автоматично превежда вашата документация и отваря pull заявки всеки път, когато изходният файл се променя.  
Това ръководство ви показва как да инсталирате GitHub приложението и да направите първия си превод за по-малко от 2 минути.


> [!NOTE]
>
> В момента Localizeflow поддържа документирани проекти на базата на GitHub  
> (например: AI for Beginners и повечето стандартни отворени хранилища).  
> 
> Поддръжката за модерни системи за документация като Astro, Docusaurus и Hugo  
> е в активна разработка.


---

## Влезте и инсталирайте GitHub приложението

1. Посетете **[localizeflow.com](https://localizeflow.com/)**.
2. Изберете **Start with free trial**.
   ![Изберете Start with free trial](../../../../translated images/bg/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Изберете **Sign in with GitHub**.  
   ![Влезте с GitHub](../../../../translated images/bg/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Влезте с вашия GitHub акаунт.  
   ![GitHub вход](../../../../translated images/bg/github-login.02bbaee0270b292e.webp)
5. Изберете акаунта, където искате да инсталирате Localizeflow GitHub приложението – личния си акаунт или организация, която управлявате.  
   ![Изберете акаунт](../../../../translated images/bg/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Изберете хранилищата, към които искате Localizeflow да има достъп, след това изберете **Save**.  
   ![Изберете хранилище и запишете](../../../../translated images/bg/select-repo-and-save.5a95ae288aefec6e.webp)
7. Ще бъдете пренасочени към началната страница на Localizeflow.

> [!TIP]
> За да добавите повече хранилища по-късно, изберете своя акаунт в горната лента и изберете **+ Add more repositories**.  
> ![Добавяне на още хранилища](../../../../translated images/bg/add-more-repo.2ca5154473aaaafb.webp)

---

## Свържете вашите хранилища с Localizeflow

1. На началната страница на Localizeflow изберете **+ Connect repositories**.  
   ![Изберете свързване на хранилища](../../../../translated images/bg/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Изберете едно от инсталираните хранилища, което искате да свържете, и изберете **Save**.  
   ![Изберете хранилище](../../../../translated images/bg/select-repo.dce94db722b44cf3.webp)

3. Вашите свързани хранилища сега ще се появят както на началната страница, така и на страницата с хранилища.  
   ![Свързани хранилища](../../../../translated images/bg/repo-connected.9e5c21ee789fdcaa.webp)

---

## Стартирайте автоматичен превод

1. Изберете току-що свързаното хранилище.  
   ![Изберете хранилище](../../../../translated images/bg/select-repo-to-detail.55e53233531f8518.webp)

2. На страницата с подробности за хранилището изберете **Edit** в долната част.  
   ![Изберете редактиране](../../../../translated images/bg/select-edit.225184c8c46d7001.webp)

3. Конфигурирайте настройките за превод — целеви клон (по подразбиране: `main`), целеви езици и изходен език (по подразбиране: `en`). Изберете **Save**.  
   ![Конфигуриране на настройки за превод](../../../../translated images/bg/configuration.ab55d0f8bab5711b.webp)

4. Изберете **Start & Automate**.  
   Localizeflow сега ще превежда автоматично вашата документация и ще отваря pull заявки всеки път при промяна в изходния код.  
   ![Start & Automate](../../../../translated images/bg/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Отказ от отговорност**:  
Този документ е преведен с помощта на AI преводаческа услуга [Co-op Translator](https://github.com/Azure/co-op-translator). Въпреки че се стремим към точност, моля, имайте предвид, че автоматичните преводи могат да съдържат грешки или неточности. Оригиналният документ на неговия роден език трябва да се счита за авторитетен източник. За критична информация се препоръчва професионален човешки превод. Ние не носим отговорност за каквито и да е недоразумения или погрешни тълкувания, произтичащи от използването на този превод.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->