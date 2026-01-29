# Localizeflow – Ръководство за бърз старт

#### Поддържано от [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](./README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Предпочитате да клонирате локално?**

> Това хранилище включва преводи на 50+ езика, което значително увеличава размера на изтегляне. За да клонирате без преводи, използвайте sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Това ви дава всичко необходимо, за да завършите курса с много по-бързо изтегляне.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow автоматично превежда вашата документация и отваря pull заявки всеки път, когато изходният файл се промени.  
Това ръководство показва как да инсталирате GitHub приложението и да направите първия си превод за по-малко от 2 минути.


> [!NOTE]
>
> В момента Localizeflow поддържа проекти за документация, базирани на GitHub  
> (например: AI for Beginners и повечето стандартни open-source репозитории).  
> 
> Поддръжката за съвременни рамки за документация като Astro, Docusaurus и Hugo  
> е в активна разработка.


---

## Влезте и инсталирайте GitHub приложението

1. Посетете **[localizeflow.com](https://localizeflow.com/)**.
2. Изберете **Start with free trial**.
   ![Select Start with free trial](../../../../translated_images/bg/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Изберете **Sign in with GitHub**.  
   ![Sign in with GitHub](../../../../translated_images/bg/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Влезте с вашия GitHub акаунт.  
   ![GitHub login](../../../../translated_images/bg/github-login.02bbaee0270b292e.webp)
5. Изберете акаунта, в който искате да инсталирате Localizeflow GitHub приложението — личния си акаунт или организация, която управлявате.  
   ![Select account](../../../../translated_images/bg/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Изберете репозиториите, до които искате Localizeflow да има достъп, след това изберете **Save**.  
   ![Select repo and save](../../../../translated_images/bg/select-repo-and-save.5a95ae288aefec6e.webp)
7. Ще бъдете пренасочени към началната страница на Localizeflow.

> [!TIP]
> За да добавите повече репозитории по-късно, изберете акаунта си в горния панел и изберете **+ Add more repositories**.  
> ![Add more repositories](../../../../translated_images/bg/add-more-repo.2ca5154473aaaafb.webp)

---

## Свържете репозиториите си с Localizeflow

1. В началната страница на Localizeflow изберете **+ Connect repositories**.  
   ![Select connect repositories](../../../../translated_images/bg/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Изберете един от инсталираните репозитории, който искате да свържете, и натиснете **Save**.  
   ![Select repository](../../../../translated_images/bg/select-repo.dce94db722b44cf3.webp)

3. Свързаните ви репозитории вече ще се появят както на началната страница, така и на страницата с репозитории.  
   ![Connected repositories](../../../../translated_images/bg/repo-connected.9e5c21ee789fdcaa.webp)

---

## Стартирайте автоматичния превод

1. Изберете репозитория, който току-що свързахте.  
   ![Select repository](../../../../translated_images/bg/select-repo-to-detail.55e53233531f8518.webp)

2. В страницата с детайли на репозитория изберете **Edit** в долната част.  
   ![Select edit](../../../../translated_images/bg/select-edit.225184c8c46d7001.webp)

3. Конфигурирайте настройките за превод — целевия клон (по подразбиране: `main`), целевите езици и изходния език (по подразбиране: `en`). Изберете **Save**.  
   ![Configure translation settings](../../../../translated_images/bg/configuration.ab55d0f8bab5711b.webp)

4. Изберете **Start & Automate**.  
   Localizeflow сега автоматично ще превежда вашата документация и ще отваря pull заявки всеки път, когато източникът се промени.  
   ![Start & Automate](../../../../translated_images/bg/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Отказ от отговорност**:  
Този документ е преведен с помощта на AI преводаческа услуга [Co-op Translator](https://github.com/Azure/co-op-translator). Въпреки че се стремим към точност, моля, имайте предвид, че автоматизираните преводи могат да съдържат грешки или неточности. Оригиналният документ на неговия роден език трябва да се счита за официален източник. За критична информация се препоръчва професионален човешки превод. Ние не носим отговорност за всякакви недоразумения или неправилни тълкувания, произтичащи от използването на този превод.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->