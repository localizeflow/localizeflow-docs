<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T11:12:30+00:00",
  "source_file": "README.md",
  "language_code": "hk"
}
-->
# Localizeflow – 快速入門指南

#### 由 [Localizeflow](https://localizeflow.com/) 支援

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](./README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 會自動翻譯您的文件，並在原始檔案變更時自動開啟拉取請求。  
本指南將示範如何安裝 GitHub App 並在 2 分鐘內完成首次翻譯。

> [!NOTE]
>
> Localizeflow 目前支援基於 GitHub 的文件專案  
> （例如：AI for Beginners 及大多數標準開源倉庫）。  
> 
> 對現代文件框架如 Astro、Docusaurus 和 Hugo 的支援  
> 正在積極開發中。

---

## 登入並安裝 GitHub App

1. 訪問 **[localizeflow.com](https://localizeflow.com/)**。
2. 選擇 **Start with free trial**。  
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. 選擇 **Sign in with GitHub**。  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. 使用您的 GitHub 帳戶登入。  
   ![GitHub login](/images/github-login.png)
5. 選擇您想安裝 Localizeflow GitHub App 的帳戶 — 您的個人帳戶或您管理的組織。  
   ![Select account](/images/select-which-account-to-use.png)
6. 選擇您希望 Localizeflow 存取的倉庫，然後選擇 **Save**。  
   ![Select repo and save](/images/select-repo-and-save.png)
7. 您將被導向回 Localizeflow 首頁。

> [!TIP]
> 若日後想新增更多倉庫，請在頁首選擇您的帳戶，然後選擇 **+ Add more repositories**。  
> ![Add more repositories](/images/add-more-repo.png)

---

## 將您的倉庫連接到 Localizeflow

1. 在 Localizeflow 首頁，選擇 **+ Connect repositories**。  
   ![Select connect repositories](/images/select-connect-repos.png)

2. 選擇您想連接的已安裝倉庫，然後選擇 **Save**。  
   ![Select repository](/images/select-repo.png)

3. 您連接的倉庫現在會顯示在首頁和倉庫頁面。  
   ![Connected repositories](/images/repo-connected.png)

---

## 開始自動翻譯

1. 選擇您剛連接的倉庫。  
   ![Select repository](/images/select-repo-to-detail.png)

2. 在倉庫詳細頁面，選擇底部的 **Edit**。  
   ![Select edit](/images/select-edit.png)

3. 配置您的翻譯設定 — 目標分支（預設：`main`）、目標語言及原始語言（預設：`en`）。選擇 **Save**。  
   ![Configure translation settings](/images/configuration.png)

4. 選擇 **Start & Automate**。  
   Localizeflow 現在會自動翻譯您的文件，並在原始檔案變更時自動開啟拉取請求。  
   ![Start & Automate](/images/select-automate.png)