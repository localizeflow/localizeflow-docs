# Localizeflow – Quick Start Guide

#### Supported by [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](./translations/ar/README.md) | [Bengali](./translations/bn/README.md) | [Bulgarian](./translations/bg/README.md) | [Burmese (Myanmar)](./translations/my/README.md) | [Chinese (Simplified)](./translations/zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](./translations/zh-HK/README.md) | [Chinese (Traditional, Macau)](./translations/zh-MO/README.md) | [Chinese (Traditional, Taiwan)](./translations/zh-TW/README.md) | [Croatian](./translations/hr/README.md) | [Czech](./translations/cs/README.md) | [Danish](./translations/da/README.md) | [Dutch](./translations/nl/README.md) | [Estonian](./translations/et/README.md) | [Finnish](./translations/fi/README.md) | [French](./translations/fr/README.md) | [German](./translations/de/README.md) | [Greek](./translations/el/README.md) | [Hebrew](./translations/he/README.md) | [Hindi](./translations/hi/README.md) | [Hungarian](./translations/hu/README.md) | [Indonesian](./translations/id/README.md) | [Italian](./translations/it/README.md) | [Japanese](./translations/ja/README.md) | [Kannada](./translations/kn/README.md) | [Korean](./translations/ko/README.md) | [Lithuanian](./translations/lt/README.md) | [Malay](./translations/ms/README.md) | [Malayalam](./translations/ml/README.md) | [Marathi](./translations/mr/README.md) | [Nepali](./translations/ne/README.md) | [Nigerian Pidgin](./translations/pcm/README.md) | [Norwegian](./translations/no/README.md) | [Persian (Farsi)](./translations/fa/README.md) | [Polish](./translations/pl/README.md) | [Portuguese (Brazil)](./translations/pt-BR/README.md) | [Portuguese (Portugal)](./translations/pt-PT/README.md) | [Punjabi (Gurmukhi)](./translations/pa/README.md) | [Romanian](./translations/ro/README.md) | [Russian](./translations/ru/README.md) | [Serbian (Cyrillic)](./translations/sr/README.md) | [Slovak](./translations/sk/README.md) | [Slovenian](./translations/sl/README.md) | [Spanish](./translations/es/README.md) | [Swahili](./translations/sw/README.md) | [Swedish](./translations/sv/README.md) | [Tagalog (Filipino)](./translations/tl/README.md) | [Tamil](./translations/ta/README.md) | [Telugu](./translations/te/README.md) | [Thai](./translations/th/README.md) | [Turkish](./translations/tr/README.md) | [Ukrainian](./translations/uk/README.md) | [Urdu](./translations/ur/README.md) | [Vietnamese](./translations/vi/README.md)

> **Prefer to Clone Locally?**

> This repository includes 50+ language translations which significantly increases the download size. To clone without translations, use sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> This gives you everything you need to complete the course with a much faster download.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow automatically translates your documentation and opens pull requests whenever the source file changes.  
This guide shows you how to install the GitHub App and run your first translation in under 2 minutes.


> [!NOTE]
>
> Localizeflow currently supports GitHub-based documentation projects
> (for example: AI for Beginners and most standard open-source repos).  
> 
> Support for modern documentation frameworks such as Astro, Docusaurus, and Hugo  
> is in active development.


---

## Sign in and install the GitHub App

1. Visit **[localizeflow.com](https://localizeflow.com/)**.
2. Select **Start with free trial**.
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. Select **Sign in with GitHub**.  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. Sign in with your GitHub account.  
   ![GitHub login](/images/github-login.png)
5. Choose the account where you want to install the Localizeflow GitHub App — your personal account or an organization you manage.  
   ![Select account](/images/select-which-account-to-use.png)
6. Select the repositories you want Localizeflow to access, then choose **Save**.  
   ![Select repo and save](/images/select-repo-and-save.png)
7. You will be redirected to the Localizeflow home page.

> [!TIP]
> To add more repositories later, select your account in the header and choose **+ Add more repositories**.  
> ![Add more repositories](/images/add-more-repo.png)

---

## Connect your repositories to Localizeflow

1. On the Localizeflow home page, select **+ Connect repositories**.  
   ![Select connect repositories](/images/select-connect-repos.png)

2. Choose one of the installed repositories you want to connect and select **Save**.  
   ![Select repository](/images/select-repo.png)

3. Your connected repositories will now appear on both the Home page and the Repositories page.  
   ![Connected repositories](/images/repo-connected.png)

---

## Start automatic translation

1. Select the repository you just connected.  
   ![Select repository](/images/select-repo-to-detail.png)

2. On the repository detail page, select **Edit** at the bottom.  
   ![Select edit](/images/select-edit.png)

3. Configure your translation settings — target branch (default: `main`), target languages, and source language (default: `en`). Select **Save**.  
   ![Configure translation settings](/images/configuration.png)

4. Select **Start & Automate**.  
   Localizeflow will now automatically translate your documentation and open pull requests whenever the source changes.  
   ![Start & Automate](/images/select-automate.png)
