# Localizeflow – 快速入門指南

#### 由 [Localizeflow](https://localizeflow.com/) 支援

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](./README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **想要本地克隆？**

> 此存儲庫包含 50 多種語言的翻譯，會顯著增加下載大小。如欲克隆時不包含翻譯，請使用稀疏檢出：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 這樣您可以用更快的下載速度獲取完成課程所需的所有內容。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 會自動翻譯您的文件，並在源文件更變時自動開啟拉取請求。  
本指南將指引您如何安裝 GitHub App 並在 2 分鐘內完成您的首次翻譯。

> [!NOTE]
>
> Localizeflow 目前支援基於 GitHub 的文件專案
> （例如：AI for Beginners 與大部分標準開源專案）。  
> 
> 對現代文件框架如 Astro、Docusaurus 和 Hugo 的支援  
> 正在積極開發中。

---

## 登入及安裝 GitHub App

1. 訪問 **[localizeflow.com](https://localizeflow.com/)**。
2. 選擇 **Start with free trial**。
   ![選擇 Start with free trial](../../../../translated images/zh-HK/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. 選擇 **Sign in with GitHub**。  
   ![使用 GitHub 登入](../../../../translated images/zh-HK/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. 用您的 GitHub 帳號登入。  
   ![GitHub 登入](../../../../translated images/zh-HK/github-login.02bbaee0270b292e.webp)
5. 選擇您想安裝 Localizeflow GitHub App 的帳號 — 您的個人帳號或您管理的組織。  
   ![選擇帳號](../../../../translated images/zh-HK/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. 選擇您想讓 Localizeflow 存取的存儲庫，然後選擇 **Save**。  
   ![選擇存儲庫及儲存](../../../../translated images/zh-HK/select-repo-and-save.5a95ae288aefec6e.webp)
7. 您將被重定向至 Localizeflow 首頁。

> [!TIP]
> 若要稍後新增更多存儲庫，請在頁首選擇您的帳號，然後選擇 **+ Add more repositories**。  
> ![新增更多存儲庫](../../../../translated images/zh-HK/add-more-repo.2ca5154473aaaafb.webp)

---

## 將您的存儲庫連接至 Localizeflow

1. 在 Localizeflow 首頁，選擇 **+ Connect repositories**。  
   ![選擇 connect repositories](../../../../translated images/zh-HK/select-connect-repos.8ac6f96f77dcc62c.webp)

2. 選擇一個已安裝的存儲庫連接，然後選擇 **Save**。  
   ![選擇存儲庫](../../../../translated images/zh-HK/select-repo.dce94db722b44cf3.webp)

3. 已連接的存儲庫會同時顯示在首頁和存儲庫頁面。  
   ![已連接的存儲庫](../../../../translated images/zh-HK/repo-connected.9e5c21ee789fdcaa.webp)

---

## 開始自動翻譯

1. 選擇您剛連接的存儲庫。  
   ![選擇存儲庫](../../../../translated images/zh-HK/select-repo-to-detail.55e53233531f8518.webp)

2. 在存儲庫詳細頁面，選擇底部的 **Edit**。  
   ![選擇編輯](../../../../translated images/zh-HK/select-edit.225184c8c46d7001.webp)

3. 設定您的翻譯選項 — 目標分支（預設：`main`）、目標語言及源語言（預設：`en`）。選擇 **Save**。  
   ![設定翻譯選項](../../../../translated images/zh-HK/configuration.ab55d0f8bab5711b.webp)

4. 選擇 **Start & Automate**。  
   Localizeflow 將自動翻譯您的文件，並在源文件發生變更時創建拉取請求。  
   ![開始與自動化](../../../../translated images/zh-HK/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：
本文件使用人工智能翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 進行翻譯。雖然我們努力確保準確性，但請注意，自動翻譯可能包含錯誤或不準確之處。原始文件的母語版本應視為權威來源。對於重要資訊，建議採用專業人工翻譯。我們概不對因使用此翻譯而引起的任何誤解或誤譯承擔責任。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->