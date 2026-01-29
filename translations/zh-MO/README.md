# Localizeflow – 快速入門指南

#### 由 [Localizeflow](https://localizeflow.com/) 支持

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](./README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **想要本地克隆？**

> 此儲存庫包含 50 多種語言翻譯，會大幅增加下載大小。若想不包含翻譯地克隆，請使用稀疏擷取（sparse checkout）：  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 這能讓你以更快的速度下載，並擁有完成課程所需的一切。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 會自動翻譯你的文件，並於原始檔案更動時自動建立拉取請求（pull requests）。  
本指南將指引你如何安裝 GitHub 應用程式，並於 2 分鐘內執行首次翻譯。


> [!NOTE]
>
> Localizeflow 目前支援基於 GitHub 的文件專案  
> （例如：AI for Beginners 及大部分標準開源專案）。  
> 
> 正積極開發對 Astro、Docusaurus 和 Hugo 等現代文件框架的支援。


---

## 登入並安裝 GitHub 應用程式

1. 訪問 **[localizeflow.com](https://localizeflow.com/)**。
2. 選擇 **Start with free trial**。
   ![Select Start with free trial](../../../../translated_images/zh-MO/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. 選擇 **Sign in with GitHub**。  
   ![Sign in with GitHub](../../../../translated_images/zh-MO/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. 使用你的 GitHub 帳號登入。  
   ![GitHub login](../../../../translated_images/zh-MO/github-login.02bbaee0270b292e.webp)
5. 選擇你想安裝 Localizeflow GitHub 應用程式的帳戶 — 個人帳戶或你管理的組織。  
   ![Select account](../../../../translated_images/zh-MO/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. 選擇你想讓 Localizeflow 存取的儲存庫，然後選擇 **Save**。  
   ![Select repo and save](../../../../translated_images/zh-MO/select-repo-and-save.5a95ae288aefec6e.webp)
7. 你將被導向 Localizeflow 首頁。

> [!TIP]
> 若之後要新增更多儲存庫，請選擇頁首的帳戶名稱，然後選擇 **+ Add more repositories**。  
> ![Add more repositories](../../../../translated_images/zh-MO/add-more-repo.2ca5154473aaaafb.webp)

---

## 將你的儲存庫連接至 Localizeflow

1. 在 Localizeflow 首頁，選擇 **+ Connect repositories**。  
   ![Select connect repositories](../../../../translated_images/zh-MO/select-connect-repos.8ac6f96f77dcc62c.webp)

2. 選擇你已安裝且想連接的其中一個儲存庫，然後選擇 **Save**。  
   ![Select repository](../../../../translated_images/zh-MO/select-repo.dce94db722b44cf3.webp)

3. 你連接的儲存庫會同時顯示在首頁和儲存庫頁面。  
   ![Connected repositories](../../../../translated_images/zh-MO/repo-connected.9e5c21ee789fdcaa.webp)

---

## 開始自動翻譯

1. 選擇你剛連接的儲存庫。  
   ![Select repository](../../../../translated_images/zh-MO/select-repo-to-detail.55e53233531f8518.webp)

2. 在儲存庫詳細頁面，選擇底部的 **Edit**。  
   ![Select edit](../../../../translated_images/zh-MO/select-edit.225184c8c46d7001.webp)

3. 設定你的翻譯設定 — 目標分支（預設：`main`）、目標語言和來源語言（預設：`en`）。選擇 **Save**。  
   ![Configure translation settings](../../../../translated_images/zh-MO/configuration.ab55d0f8bab5711b.webp)

4. 選擇 **Start & Automate**。  
   Localizeflow 現在會自動翻譯你的文件，並於原始檔案變更時自動開啟拉取請求。  
   ![Start & Automate](../../../../translated_images/zh-MO/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：  
本文件使用 AI 翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 進行翻譯。雖然我們力求準確，但請注意，自動翻譯可能包含錯誤或不準確之處。原始文件的母語版本應視為權威來源。對於重要資訊，建議尋求專業人工翻譯。我們對因使用本翻譯而引起的任何誤解或誤釋不承擔任何責任。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->