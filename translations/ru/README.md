# Localizeflow – Руководство по быстрому старту

#### Поддерживается [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](./README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Отдаёте предпочтение локальному клонированию?**

> Этот репозиторий включает более 50 языковых переводов, что значительно увеличивает размер загрузки. Чтобы клонировать без переводов, используйте sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Это даст вам всё необходимое для прохождения курса с гораздо более быстрой загрузкой.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow автоматически переводит вашу документацию и создаёт pull-запросы всякий раз, когда исходный файл изменяется.  
Это руководство покажет, как установить GitHub App и выполнить ваш первый перевод менее чем за 2 минуты.


> [!NOTE]
>
> В настоящее время Localizeflow поддерживает проекты документации на базе GitHub  
> (например: AI for Beginners и большинство стандартных open-source репозиториев).  
>  
> Поддержка современных фреймворков для документации, таких как Astro, Docusaurus и Hugo,  
> находится в активной разработке.


---

## Войдите и установите GitHub App

1. Перейдите на **[localizeflow.com](https://localizeflow.com/)**.
2. Выберите **Начать бесплатную пробную версию**.  
   ![Выберите Начать бесплатную пробную версию](../../../../translated images/ru/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Выберите **Войти через GitHub**.  
   ![Войти через GitHub](../../../../translated images/ru/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Войдите в свою учётную запись GitHub.  
   ![Вход в GitHub](../../../../translated images/ru/github-login.02bbaee0270b292e.webp)
5. Выберите учётную запись, в которую хотите установить Localizeflow GitHub App — личную или организацию, которой управляете.  
   ![Выберите учётную запись](../../../../translated images/ru/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Выберите репозитории, к которым Localizeflow будет иметь доступ, затем нажмите **Сохранить**.  
   ![Выберите репозиторий и сохраните](../../../../translated images/ru/select-repo-and-save.5a95ae288aefec6e.webp)
7. Вас перенаправит на главную страницу Localizeflow.

> [!TIP]
> Чтобы добавить репозитории позже, выберите свою учётную запись в шапке и нажмите **+ Добавить ещё репозитории**.  
> ![Добавить ещё репозитории](../../../../translated images/ru/add-more-repo.2ca5154473aaaafb.webp)

---

## Подключите ваши репозитории к Localizeflow

1. На главной странице Localizeflow выберите **+ Подключить репозитории**.  
   ![Выберите подключить репозитории](../../../../translated images/ru/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Выберите один из установленных репозиториев, который хотите подключить, и нажмите **Сохранить**.  
   ![Выберите репозиторий](../../../../translated images/ru/select-repo.dce94db722b44cf3.webp)

3. Ваши подключённые репозитории теперь будут отображаться как на главной странице, так и на странице Репозиториев.  
   ![Подключённые репозитории](../../../../translated images/ru/repo-connected.9e5c21ee789fdcaa.webp)

---

## Запустите автоматический перевод

1. Выберите только что подключённый репозиторий.  
   ![Выберите репозиторий](../../../../translated images/ru/select-repo-to-detail.55e53233531f8518.webp)

2. На странице с деталями репозитория выберите **Редактировать** внизу.  
   ![Выберите редактировать](../../../../translated images/ru/select-edit.225184c8c46d7001.webp)

3. Настройте параметры перевода — целевую ветку (по умолчанию: `main`), целевые языки и исходный язык (по умолчанию: `en`). Нажмите **Сохранить**.  
   ![Настройте параметры перевода](../../../../translated images/ru/configuration.ab55d0f8bab5711b.webp)

4. Нажмите **Запустить и автоматизировать**.  
   Теперь Localizeflow будет автоматически переводить вашу документацию и создавать pull-запросы при каждом изменении исходных файлов.  
   ![Запустить и автоматизировать](../../../../translated images/ru/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Отказ от ответственности**:  
Этот документ был переведен с помощью AI-сервиса перевода [Co-op Translator](https://github.com/Azure/co-op-translator). Несмотря на наши старания обеспечить точность, просим учитывать, что автоматические переводы могут содержать ошибки или неточности. Оригинальный документ на исходном языке следует считать авторитетным источником. Для получения критически важной информации рекомендуется обращаться к профессиональному переводу, выполненному человеком. Мы не несем ответственности за любые недоразумения или неправильные толкования, возникшие в результате использования данного перевода.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->