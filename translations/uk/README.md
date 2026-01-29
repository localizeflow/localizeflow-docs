# Localizeflow – Швидкий посібник для початку

#### Підтримується [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](./README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Віддаєте перевагу клонувати локально?**

> Цей репозиторій містить понад 50 мовних перекладів, що значно збільшує розмір завантаження. Щоб клонувати без перекладів, використовуйте sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Це дає вам усе необхідне для проходження курсу з набагато швидшим завантаженням.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow автоматично перекладає вашу документацію та відкриває pull-реквести щоразу, коли змінюється вихідний файл.  
Цей посібник показує, як встановити GitHub App і запустити перший переклад менш ніж за 2 хвилини.


> [!NOTE]
>
> Наразі Localizeflow підтримує проекти документації на базі GitHub
> (наприклад: AI for Beginners і більшість стандартних відкритих репозиторіїв).  
> 
> Підтримка сучасних фреймворків документації, таких як Astro, Docusaurus та Hugo,  
> перебуває в активній розробці.


---

## Увійдіть і встановіть GitHub App

1. Відвідайте **[localizeflow.com](https://localizeflow.com/)**.
2. Виберіть **Start with free trial**.
   ![Select Start with free trial](../../../../translated_images/uk/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Виберіть **Sign in with GitHub**.  
   ![Sign in with GitHub](../../../../translated_images/uk/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Увійдіть за допомогою облікового запису GitHub.  
   ![GitHub login](../../../../translated_images/uk/github-login.02bbaee0270b292e.webp)
5. Виберіть обліковий запис, у якому хочете встановити Localizeflow GitHub App — ваш особистий акаунт або організацію, якою керуєте.  
   ![Select account](../../../../translated_images/uk/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Виберіть репозиторії, до яких ви хочете надати доступ Localizeflow, потім натисніть **Save**.  
   ![Select repo and save](../../../../translated_images/uk/select-repo-and-save.5a95ae288aefec6e.webp)
7. Вас буде перенаправлено на головну сторінку Localizeflow.

> [!TIP]
> Щоб додати більше репозиторіїв пізніше, виберіть ваш акаунт у шапці і оберіть **+ Add more repositories**.  
> ![Add more repositories](../../../../translated_images/uk/add-more-repo.2ca5154473aaaafb.webp)

---

## Підключіть ваші репозиторії до Localizeflow

1. На головній сторінці Localizeflow виберіть **+ Connect repositories**.  
   ![Select connect repositories](../../../../translated_images/uk/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Оберіть один із встановлених репозиторіїв, який хочете підключити, і натисніть **Save**.  
   ![Select repository](../../../../translated_images/uk/select-repo.dce94db722b44cf3.webp)

3. Підключені репозиторії тепер з’являться як на головній сторінці, так і на сторінці Репозиторіїв.  
   ![Connected repositories](../../../../translated_images/uk/repo-connected.9e5c21ee789fdcaa.webp)

---

## Почніть автоматичний переклад

1. Виберіть щойно підключений репозиторій.  
   ![Select repository](../../../../translated_images/uk/select-repo-to-detail.55e53233531f8518.webp)

2. На сторінці деталей репозиторію виберіть **Edit** внизу.  
   ![Select edit](../../../../translated_images/uk/select-edit.225184c8c46d7001.webp)

3. Налаштуйте параметри перекладу — цільова гілка (за замовчуванням: `main`), цільові мови та початкова мова (за замовчуванням: `en`). Натисніть **Save**.  
   ![Configure translation settings](../../../../translated_images/uk/configuration.ab55d0f8bab5711b.webp)

4. Виберіть **Start & Automate**.  
   Localizeflow тепер автоматично перекладатиме вашу документацію та відкриватиме pull-реквести щоразу, коли вихідний файл змінюється.  
   ![Start & Automate](../../../../translated_images/uk/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Відмова від відповідальності**:  
Цей документ було перекладено за допомогою сервісу автоматичного перекладу штучного інтелекту [Co-op Translator](https://github.com/Azure/co-op-translator). Хоча ми прагнемо до точності, будь ласка, майте на увазі, що автоматичні переклади можуть містити помилки або неточності. Оригінальний документ рідною мовою слід вважати авторитетним джерелом. Для критично важливої інформації рекомендується професійний людський переклад. Ми не несемо відповідальності за будь-які непорозуміння або хибні тлумачення, що виникли внаслідок використання цього перекладу.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->