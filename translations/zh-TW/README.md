# Localizeflow – 快速入門指南

#### 由 [Localizeflow](https://localizeflow.com/) 支援

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[阿拉伯語](../ar/README.md) | [孟加拉語](../bn/README.md) | [保加利亞語](../bg/README.md) | [緬甸語](../my/README.md) | [中文 (簡體)](../zh-CN/README.md) | [中文 (繁體，香港)](../zh-HK/README.md) | [中文 (繁體，澳門)](../zh-MO/README.md) | [中文 (繁體，台灣)](./README.md) | [克羅埃西亞語](../hr/README.md) | [捷克語](../cs/README.md) | [丹麥語](../da/README.md) | [荷蘭語](../nl/README.md) | [愛沙尼亞語](../et/README.md) | [芬蘭語](../fi/README.md) | [法語](../fr/README.md) | [德語](../de/README.md) | [希臘語](../el/README.md) | [希伯來語](../he/README.md) | [印地語](../hi/README.md) | [匈牙利語](../hu/README.md) | [印尼語](../id/README.md) | [義大利語](../it/README.md) | [日語](../ja/README.md) | [坎納達語](../kn/README.md) | [韓語](../ko/README.md) | [立陶宛語](../lt/README.md) | [馬來語](../ms/README.md) | [馬拉雅拉姆語](../ml/README.md) | [馬拉蒂語](../mr/README.md) | [尼泊爾語](../ne/README.md) | [奈及利亞皮欽語](../pcm/README.md) | [挪威語](../no/README.md) | [波斯語 (法爾西語)](../fa/README.md) | [波蘭語](../pl/README.md) | [葡萄牙語 (巴西)](../pt-BR/README.md) | [葡萄牙語 (葡萄牙)](../pt-PT/README.md) | [旁遮普語 (Gurmukhi)](../pa/README.md) | [羅馬尼亞語](../ro/README.md) | [俄語](../ru/README.md) | [塞爾維亞語 (西里爾字母)](../sr/README.md) | [斯洛伐克語](../sk/README.md) | [斯洛文尼亞語](../sl/README.md) | [西班牙語](../es/README.md) | [斯瓦希里語](../sw/README.md) | [瑞典語](../sv/README.md) | [他加祿語 (菲律賓語)](../tl/README.md) | [泰米爾語](../ta/README.md) | [泰盧固語](../te/README.md) | [泰語](../th/README.md) | [土耳其語](../tr/README.md) | [烏克蘭語](../uk/README.md) | [烏爾都語](../ur/README.md) | [越南語](../vi/README.md)

> **偏好本機複製？**

> 此倉庫包含 50 多種語言翻譯，會大幅增加下載大小。若想不含翻譯檔案進行複製，請使用稀疏簽出：  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 這樣可更快速下載，並包含您完成課程所需的所有資源。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 會自動翻譯您的文件，並在來源檔案變更時自動開啟 pull request。  
本指南將指導您如何安裝 GitHub App，並在 2 分鐘內完成第一次翻譯。


> [!NOTE]
>
> Localizeflow 目前支援基於 GitHub 的文件專案  
> （例如：AI for Beginners 以及大部分標準開源專案）。  
> 
> 對現代文件框架如 Astro、Docusaurus 與 Hugo 的支援  
> 正在積極開發中。


---

## 登入並安裝 GitHub App

1. 前往 **[localizeflow.com](https://localizeflow.com/)**。  
2. 選擇 **Start with free trial**（開始免費試用）。  
   ![選擇 Start with free trial](../../../../translated images/zh-TW/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. 選擇 **Sign in with GitHub**（用 GitHub 登入）。  
   ![用 GitHub 登入](../../../../translated images/zh-TW/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. 使用您的 GitHub 帳號登入。  
   ![GitHub 登入畫面](../../../../translated images/zh-TW/github-login.02bbaee0270b292e.webp)
5. 選擇要安裝 Localizeflow GitHub App 的帳戶 — 您的個人帳戶或您管理的組織。  
   ![選擇帳戶](../../../../translated images/zh-TW/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. 選擇您想讓 Localizeflow 存取的儲存庫，然後按 **Save**。  
   ![選擇儲存庫並保存](../../../../translated images/zh-TW/select-repo-and-save.5a95ae288aefec6e.webp)
7. 系統會將您導回 Localizeflow 首頁。

> [!TIP]
> 若日後想要新增更多儲存庫，可在頁首選擇您的帳戶並點選 **+ Add more repositories**。  
> ![新增更多儲存庫](../../../../translated images/zh-TW/add-more-repo.2ca5154473aaaafb.webp)

---

## 將儲存庫連接至 Localizeflow

1. 在 Localizeflow 首頁，選擇 **+ Connect repositories**（連接儲存庫）。  
   ![選擇連接儲存庫](../../../../translated images/zh-TW/select-connect-repos.8ac6f96f77dcc62c.webp)

2. 選擇您想連接的已安裝儲存庫，然後按 **Save**。  
   ![選擇儲存庫](../../../../translated images/zh-TW/select-repo.dce94db722b44cf3.webp)

3. 您所連接的儲存庫會出現在首頁及儲存庫頁面。  
   ![已連接的儲存庫](../../../../translated images/zh-TW/repo-connected.9e5c21ee789fdcaa.webp)

---

## 開始自動翻譯

1. 選擇您剛連接的儲存庫。  
   ![選擇儲存庫](../../../../translated images/zh-TW/select-repo-to-detail.55e53233531f8518.webp)

2. 在儲存庫詳細頁面，選擇底部的 **Edit**。  
   ![選擇編輯](../../../../translated images/zh-TW/select-edit.225184c8c46d7001.webp)

3. 配置翻譯設定 — 目標分支（預設：`main`）、目標語言，以及來源語言（預設：`en`）。選擇 **Save**。  
   ![配置翻譯設定](../../../../translated images/zh-TW/configuration.ab55d0f8bab5711b.webp)

4. 選擇 **Start & Automate**。  
   Localizeflow 現在將自動翻譯您的文件，並在來源變動時自動開啟 pull request。  
   ![開始並自動化](../../../../translated images/zh-TW/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責聲明**：  
本文件係使用 AI 翻譯服務 [Co-op Translator](https://github.com/Azure/co-op-translator) 翻譯而成。雖然我們力求準確，但請注意，自動翻譯可能包含錯誤或不準確之處。原始文件的母語版本應視為權威資料來源。對於重要資訊，建議採用專業人工翻譯。我們不對因使用本翻譯結果所產生的任何誤解或誤譯承擔責任。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->