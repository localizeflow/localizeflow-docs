# Localizeflow – 快速開始指南

#### 支援者 [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](./README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **偏好本地克隆？**

> 此儲存庫包含超過 50 種語言的翻譯，這會大幅增加下載大小。若要在不下載翻譯的情況下克隆，請使用稀疏檢出：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 這樣可以讓您以更快的速度下載，並完成課程所需的一切。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 會自動翻譯您的文件，並在原始檔案變更時提出拉取請求。  
本指南將示範如何安裝 GitHub App 並在兩分鐘內完成首次翻譯。

> [!NOTE]
>
> Localizeflow 目前支援基於 GitHub 的文件專案  
>（例如：AI for Beginners 及大多數標準開源倉庫）。  
> 
> 正積極開發支援現代文件框架，如 Astro、Docusaurus 和 Hugo。

---

## 登入並安裝 GitHub App

1. 前往 **[localizeflow.com](https://localizeflow.com/)**。
2. 選擇 **Start with free trial**。
   ![Select Start with free trial](../../../../translated images/zh-MO/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. 選擇 **Sign in with GitHub**。  
   ![Sign in with GitHub](../../../../translated images/zh-MO/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. 使用您的 GitHub 帳號登入。  
   ![GitHub login](../../../../translated images/zh-MO/github-login.02bbaee0270b292e.webp)
5. 選擇您要安裝 Localizeflow GitHub App 的帳號 — 您的個人帳號或您管理的組織。  
   ![Select account](../../../../translated images/zh-MO/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. 選擇您想要讓 Localizeflow 存取的資料庫，然後選擇 **Save**。  
   ![Select repo and save](../../../../translated images/zh-MO/select-repo-and-save.5a95ae288aefec6e.webp)
7. 您將被重定向到 Localizeflow 首頁。

> [!TIP]
> 若要稍後新增更多資料庫，請在標題列選擇您的帳號，然後選擇 **+ Add more repositories**。  
> ![Add more repositories](../../../../translated images/zh-MO/add-more-repo.2ca5154473aaaafb.webp)

---

## 將您的資料庫連接到 Localizeflow

1. 在 Localizeflow 首頁，選擇 **+ Connect repositories**。  
   ![Select connect repositories](../../../../translated images/zh-MO/select-connect-repos.8ac6f96f77dcc62c.webp)

2. 選擇您已安裝的要連接的資料庫之一，然後選擇 **Save**。  
   ![Select repository](../../../../translated images/zh-MO/select-repo.dce94db722b44cf3.webp)

3. 您連接的資料庫現在將出現在首頁和資料庫頁面。  
   ![Connected repositories](../../../../translated images/zh-MO/repo-connected.9e5c21ee789fdcaa.webp)

---

## 開始自動翻譯

1. 選擇您剛連接的資料庫。  
   ![Select repository](../../../../translated images/zh-MO/select-repo-to-detail.55e53233531f8518.webp)

2. 在該資料庫詳細頁面，於底部選擇 **Edit**。  
   ![Select edit](../../../../translated images/zh-MO/select-edit.225184c8c46d7001.webp)

3. 配置您的翻譯設定 — 目標分支（預設：`main`）、目標語言和原始語言（預設：`en`）。選擇 **Save**。  
   ![Configure translation settings](../../../../translated images/zh-MO/configuration.ab55d0f8bab5711b.webp)

4. 選擇 **Start & Automate**。  
   Localizeflow 現在會自動翻譯您的文件，並在原始檔案更動時提出拉取請求。  
   ![Start & Automate](../../../../translated images/zh-MO/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：  
本文件經由 AI 翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 翻譯而成。雖然我們致力於提供準確的翻譯，但請注意，自動翻譯可能存在錯誤或不準確之處。原文文件的母語版本應被視為權威來源。對於關鍵資訊，建議採用專業人工翻譯。我們不對因使用本翻譯而引起的任何誤解或錯誤詮釋承擔責任。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->