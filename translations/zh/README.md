<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T10:42:44+00:00",
  "source_file": "README.md",
  "language_code": "zh"
}
-->
# Localizeflow – 快速入门指南

#### 由 [Localizeflow](https://localizeflow.com/) 支持

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](./README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 会自动翻译您的文档，并在源文件更改时自动发起拉取请求。  
本指南将向您展示如何安装 GitHub 应用并在 2 分钟内运行您的第一次翻译。

> [!NOTE]
>
> Localizeflow 目前支持基于 GitHub 的文档项目  
> （例如：AI for Beginners 以及大多数标准开源仓库）。  
> 
> 对现代文档框架如 Astro、Docusaurus 和 Hugo 的支持  
> 正在积极开发中。

---

## 登录并安装 GitHub 应用

1. 访问 **[localizeflow.com](https://localizeflow.com/)**。
2. 选择 **Start with free trial**。  
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. 选择 **Sign in with GitHub**。  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. 使用您的 GitHub 账号登录。  
   ![GitHub login](/images/github-login.png)
5. 选择您想安装 Localizeflow GitHub 应用的账户——您的个人账户或您管理的组织。  
   ![Select account](/images/select-which-account-to-use.png)
6. 选择您希望 Localizeflow 访问的仓库，然后选择 **Save**。  
   ![Select repo and save](/images/select-repo-and-save.png)
7. 您将被重定向到 Localizeflow 首页。

> [!TIP]
> 若要稍后添加更多仓库，请在页眉中选择您的账户，然后选择 **+ Add more repositories**。  
> ![Add more repositories](/images/add-more-repo.png)

---

## 将您的仓库连接到 Localizeflow

1. 在 Localizeflow 首页，选择 **+ Connect repositories**。  
   ![Select connect repositories](/images/select-connect-repos.png)

2. 选择您想连接的已安装仓库之一，然后选择 **Save**。  
   ![Select repository](/images/select-repo.png)

3. 您连接的仓库现在将显示在首页和仓库页面。  
   ![Connected repositories](/images/repo-connected.png)

---

## 开始自动翻译

1. 选择您刚连接的仓库。  
   ![Select repository](/images/select-repo-to-detail.png)

2. 在仓库详情页底部选择 **Edit**。  
   ![Select edit](/images/select-edit.png)

3. 配置您的翻译设置——目标分支（默认：`main`）、目标语言和源语言（默认：`en`）。选择 **Save**。  
   ![Configure translation settings](/images/configuration.png)

4. 选择 **Start & Automate**。  
   Localizeflow 现在将自动翻译您的文档，并在源文件更改时自动发起拉取请求。  
   ![Start & Automate](/images/select-automate.png)