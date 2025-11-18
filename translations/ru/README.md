<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T10:46:39+00:00",
  "source_file": "README.md",
  "language_code": "ru"
}
-->
# Localizeflow – Руководство по быстрому старту

#### Поддерживается [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](./README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow автоматически переводит вашу документацию и открывает pull-запросы при каждом изменении исходного файла.  
Это руководство покажет вам, как установить GitHub App и выполнить первый перевод менее чем за 2 минуты.


> [!NOTE]
>
> В настоящее время Localizeflow поддерживает проекты документации на базе GitHub  
> (например: AI for Beginners и большинство стандартных open-source репозиториев).  
> 
> Поддержка современных фреймворков для документации, таких как Astro, Docusaurus и Hugo,  
> находится в активной разработке.


---

## Вход и установка GitHub App

1. Перейдите на **[localizeflow.com](https://localizeflow.com/)**.
2. Выберите **Start with free trial**.
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. Выберите **Sign in with GitHub**.  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. Войдите в систему с помощью вашей учетной записи GitHub.  
   ![GitHub login](/images/github-login.png)
5. Выберите аккаунт, в который хотите установить Localizeflow GitHub App — личный аккаунт или организацию, которой вы управляете.  
   ![Select account](/images/select-which-account-to-use.png)
6. Выберите репозитории, к которым Localizeflow должен получить доступ, затем нажмите **Save**.  
   ![Select repo and save](/images/select-repo-and-save.png)
7. Вы будете перенаправлены на главную страницу Localizeflow.

> [!TIP]
> Чтобы добавить больше репозиториев позже, выберите ваш аккаунт в шапке и нажмите **+ Add more repositories**.  
> ![Add more repositories](/images/add-more-repo.png)

---

## Подключение репозиториев к Localizeflow

1. На главной странице Localizeflow выберите **+ Connect repositories**.  
   ![Select connect repositories](/images/select-connect-repos.png)

2. Выберите один из установленных репозиториев, который хотите подключить, и нажмите **Save**.  
   ![Select repository](/images/select-repo.png)

3. Ваши подключенные репозитории теперь будут отображаться как на главной странице, так и на странице Репозиториев.  
   ![Connected repositories](/images/repo-connected.png)

---

## Запуск автоматического перевода

1. Выберите только что подключенный репозиторий.  
   ![Select repository](/images/select-repo-to-detail.png)

2. На странице с деталями репозитория выберите **Edit** внизу.  
   ![Select edit](/images/select-edit.png)

3. Настройте параметры перевода — целевая ветка (по умолчанию: `main`), целевые языки и исходный язык (по умолчанию: `en`). Нажмите **Save**.  
   ![Configure translation settings](/images/configuration.png)

4. Нажмите **Start & Automate**.  
   Localizeflow теперь будет автоматически переводить вашу документацию и открывать pull-запросы при каждом изменении исходных данных.  
   ![Start & Automate](/images/select-automate.png)