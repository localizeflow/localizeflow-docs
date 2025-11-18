<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T07:37:23+00:00",
  "source_file": "README.md",
  "language_code": "mo"
}
-->
# Localizeflow – 快速入門指南

#### 由 [Localizeflow](https://localizeflow.com/) 支持

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](./README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 會自動幫你翻譯文件，只要原始檔案有變更，就會自動開 pull request。  
本指南會教你如何安裝 GitHub App，並在兩分鐘內完成第一次翻譯。

> [!NOTE]
>
> Localizeflow 目前只支援以 GitHub 為基礎的文件專案
> （例如：AI for Beginners 及大部分標準開源倉庫）。  
> 
> 對於 Astro、Docusaurus、Hugo 等現代文件框架的支援  
> 正在積極開發中。

---

## 登入並安裝 GitHub App

1. 前往 **[localizeflow.com](https://localizeflow.com/)**。
2. 點選 **免費試用**。
   <img alt="選擇免費試用" src="/images/select-start-with-free-trial.png">
3. 點選 **以 GitHub 帳號登入**。  
   <img alt="以 GitHub 登入" src="/images/select-sign-in-with-github.png">
4. 用你的 GitHub 帳號登入。  
   <img alt="GitHub 登入" src="/images/github-login.png">
5. 選擇你要安裝 Localizeflow GitHub App 的帳號——可以是個人帳號或你管理的組織。  
   <img alt="選擇帳號" src="/images/select-which-account-to-use.png">
6. 選擇你想讓 Localizeflow 存取的倉庫，然後點選 **儲存**。  
   <img alt="選擇倉庫並儲存" src="/images/select-repo-and-save.png">
7. 你會被導向 Localizeflow 主頁。

> [!TIP]
> 如果之後想新增更多倉庫，可以在頁面上方選擇你的帳號，再點選 **+ 新增更多倉庫**。  
> <img alt="新增更多倉庫" src="/images/add-more-repo.png">

---

## 連接你的倉庫到 Localizeflow

1. 在 Localizeflow 主頁，點選 **+ 連接倉庫**。  
   <img alt="選擇連接倉庫" src="/images/select-connect-repos.png">

2. 選擇你已安裝的其中一個倉庫，然後點選 **儲存**。  
   <img alt="選擇倉庫" src="/images/select-repo.png">

3. 你連接的倉庫會顯示在主頁和倉庫頁面。  
   <img alt="已連接倉庫" src="/images/repo-connected.png">

---

## 開始自動翻譯

1. 點選你剛連接的倉庫。  
   <img alt="選擇倉庫" src="/images/select-repo-to-detail.png">

2. 在倉庫詳細頁面底部，點選 **編輯**。  
   <img alt="選擇編輯" src="/images/select-edit.png">

3. 設定你的翻譯選項——目標分支（預設：`main`）、目標語言，以及原始語言（預設：`en`）。然後點選 **儲存**。  
   <img alt="設定翻譯選項" src="/images/configuration.png">

4. 點選 **開始並自動化**。  
   Localizeflow 會自動幫你翻譯文件，只要原始檔案有變更，就會自動開 pull request。  
   <img alt="開始並自動化" src="/images/select-automate.png">