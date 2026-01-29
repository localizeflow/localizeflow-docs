# Localizeflow – 快速入門指南

#### 由 [Localizeflow](https://localizeflow.com/) 支援

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](./README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **想本地 Clone？**

> 此儲存庫包含 50 多種語言的翻譯，因此會大幅增加下載大小。若想不包含翻譯的情況下 Clone，請使用 sparse checkout：  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
 > 這樣你就能以更快的速度下載完整課程所需的所有內容。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 會自動翻譯你的文件，並在源文件變更時開啟拉取請求。  
本指南將示範如何安裝 GitHub App 並在 2 分鐘內完成首次翻譯。

> [!NOTE]
>
> Localizeflow 目前支援基於 GitHub 的文件專案  
> （例如：AI for Beginners 與大多數標準開源倉庫）。  
> 
> 對現代文件框架如 Astro、Docusaurus 與 Hugo 的支援  
> 正在積極開發中。

---

## 登入並安裝 GitHub App

1. 前往 **[localizeflow.com](https://localizeflow.com/)**。
2. 選擇 **Start with free trial**。  
   ![Select Start with free trial](../../../../translated_images/zh-HK/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. 選擇 **Sign in with GitHub**。  
   ![Sign in with GitHub](../../../../translated_images/zh-HK/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. 使用你的 GitHub 帳號登入。  
   ![GitHub login](../../../../translated_images/zh-HK/github-login.02bbaee0270b292e.webp)
5. 選擇你想安裝 Localizeflow GitHub App 的帳戶 — 個人帳戶或你管理的組織。  
   ![Select account](../../../../translated_images/zh-HK/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. 選擇你希望 Localizeflow 存取的倉庫，然後按 **Save**。  
   ![Select repo and save](../../../../translated_images/zh-HK/select-repo-and-save.5a95ae288aefec6e.webp)
7. 會自動導回 Localizeflow 首頁。

> [!TIP]
> 之後如需新增倉庫，點擊頁首你的帳戶名稱，選擇 **+ Add more repositories**。  
> ![Add more repositories](../../../../translated_images/zh-HK/add-more-repo.2ca5154473aaaafb.webp)

---

## 將你的倉庫連接到 Localizeflow

1. 在 Localizeflow 首頁，點選 **+ Connect repositories**。  
   ![Select connect repositories](../../../../translated_images/zh-HK/select-connect-repos.8ac6f96f77dcc62c.webp)

2. 選擇你想連接的已安裝倉庫，然後選 **Save**。  
   ![Select repository](../../../../translated_images/zh-HK/select-repo.dce94db722b44cf3.webp)

3. 你連接的倉庫現在會同時顯示在首頁與倉庫頁面。  
   ![Connected repositories](../../../../translated_images/zh-HK/repo-connected.9e5c21ee789fdcaa.webp)

---

## 開始自動翻譯

1. 選擇你剛連接的倉庫。  
   ![Select repository](../../../../translated_images/zh-HK/select-repo-to-detail.55e53233531f8518.webp)

2. 在倉庫詳細頁面底部點選 **Edit**。  
   ![Select edit](../../../../translated_images/zh-HK/select-edit.225184c8c46d7001.webp)

3. 配置你的翻譯設置 — 目標分支（預設：`main`）、目標語言及源語言（預設：`en`）。選擇 **Save**。  
   ![Configure translation settings](../../../../translated_images/zh-HK/configuration.ab55d0f8bab5711b.webp)

4. 點選 **Start & Automate**。  
   Localizeflow 將自動翻譯你的文件，並在源變更時自動開啟拉取請求。  
   ![Start & Automate](../../../../translated_images/zh-HK/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：
本文件由 AI 翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 進行翻譯。我們致力於確保翻譯準確，但請注意，自動翻譯可能包含錯誤或不準確之處。原始文件（母語版本）應被視為權威資料來源。對於重要資訊，建議採用專業人工翻譯。本公司不對因使用此翻譯所引起的任何誤解或誤釋負責。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->