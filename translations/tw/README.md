<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T07:37:45+00:00",
  "source_file": "README.md",
  "language_code": "tw"
}
-->
# Localizeflow – 快速入門指南

#### 由 <a href="https://localizeflow.com/">Localizeflow</a> 支持

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
<a href="./translations/ar/README.md">阿拉伯文</a> | <a href="./translations/bn/README.md">孟加拉文</a> | <a href="./translations/bg/README.md">保加利亞文</a> | <a href="./translations/my/README.md">緬甸文</a> | <a href="./translations/zh/README.md">中文（簡體）</a> | <a href="./translations/hk/README.md">中文（繁體，香港）</a> | <a href="./translations/mo/README.md">中文（繁體，澳門）</a> | <a href="./translations/tw/README.md">中文（繁體，台灣）</a> | <a href="./translations/hr/README.md">克羅埃西亞文</a> | <a href="./translations/cs/README.md">捷克文</a> | <a href="./translations/da/README.md">丹麥文</a> | <a href="./translations/nl/README.md">荷蘭文</a> | <a href="./translations/et/README.md">愛沙尼亞文</a> | <a href="./translations/fi/README.md">芬蘭文</a> | <a href="./translations/fr/README.md">法文</a> | <a href="./translations/de/README.md">德文</a> | <a href="./translations/el/README.md">希臘文</a> | <a href="./translations/he/README.md">希伯來文</a> | <a href="./translations/hi/README.md">印地文</a> | <a href="./translations/hu/README.md">匈牙利文</a> | <a href="./translations/id/README.md">印尼文</a> | <a href="./translations/it/README.md">義大利文</a> | <a href="./translations/ja/README.md">日文</a> | <a href="./translations/ko/README.md">韓文</a> | <a href="./translations/lt/README.md">立陶宛文</a> | <a href="./translations/ms/README.md">馬來文</a> | <a href="./translations/mr/README.md">馬拉地文</a> | <a href="./translations/ne/README.md">尼泊爾文</a> | <a href="./translations/pcm/README.md">奈及利亞皮欽語</a> | <a href="./translations/no/README.md">挪威文</a> | <a href="./translations/fa/README.md">波斯文</a> | <a href="./translations/pl/README.md">波蘭文</a> | <a href="./translations/br/README.md">葡萄牙文（巴西）</a> | <a href="./translations/pt/README.md">葡萄牙文（葡萄牙）</a> | <a href="./translations/pa/README.md">旁遮普文（古爾穆奇文）</a> | <a href="./translations/ro/README.md">羅馬尼亞文</a> | <a href="./translations/ru/README.md">俄文</a> | <a href="./translations/sr/README.md">塞爾維亞文（西里爾字母）</a> | <a href="./translations/sk/README.md">斯洛伐克文</a> | <a href="./translations/sl/README.md">斯洛維尼亞文</a> | <a href="./translations/es/README.md">西班牙文</a> | <a href="./translations/sw/README.md">斯瓦希里文</a> | <a href="./translations/sv/README.md">瑞典文</a> | <a href="./translations/tl/README.md">他加祿文（菲律賓語）</a> | <a href="./translations/ta/README.md">泰米爾文</a> | <a href="./translations/th/README.md">泰文</a> | <a href="./translations/tr/README.md">土耳其文</a> | <a href="./translations/uk/README.md">烏克蘭文</a> | <a href="./translations/ur/README.md">烏爾都文</a> | <a href="./translations/vi/README.md">越南文</a>
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 會自動翻譯你的文件，只要原始檔案有變動就會開啟 pull request。  
本指南教你如何安裝 GitHub App，並在兩分鐘內完成第一次翻譯。

> [!NOTE]
>
> Localizeflow 目前支援以 GitHub 為基礎的文件專案  
> （例如：AI for Beginners 以及大多數標準開源倉庫）。
>
> 對於 Astro、Docusaurus、Hugo 等現代文件框架的支援  
> 正在積極開發中。

---

## 登入並安裝 GitHub App

1. 前往 <strong><a href="https://localizeflow.com/">localizeflow.com</a></strong>。
2. 點選 <strong>免費試用</strong>。
   <img src="/images/select-start-with-free-trial.png" alt="選擇免費試用">
3. 點選 <strong>使用 GitHub 登入</strong>。  
   <img src="/images/select-sign-in-with-github.png" alt="使用 GitHub 登入">
4. 使用你的 GitHub 帳號登入。  
   <img src="/images/github-login.png" alt="GitHub 登入">
5. 選擇你要安裝 Localizeflow GitHub App 的帳號——可以是個人帳號或你管理的組織。  
   <img src="/images/select-which-account-to-use.png" alt="選擇帳號">
6. 選擇你要讓 Localizeflow 存取的倉庫，然後點選 <strong>儲存</strong>。  
   <img src="/images/select-repo-and-save.png" alt="選擇倉庫並儲存">
7. 你會被導向 Localizeflow 首頁。

> [!TIP]
> 如果之後想新增更多倉庫，可以在頁面上方選擇你的帳號，然後點選 <strong>+ 新增更多倉庫</strong>。  
> <img src="/images/add-more-repo.png" alt="新增更多倉庫">

---

## 將你的倉庫連接到 Localizeflow

1. 在 Localizeflow 首頁，點選 <strong>+ 連接倉庫</strong>。  
   <img src="/images/select-connect-repos.png" alt="選擇連接倉庫">

2. 選擇你已安裝的其中一個倉庫，然後點選 <strong>儲存</strong>。  
   <img src="/images/select-repo.png" alt="選擇倉庫">

3. 你連接的倉庫會顯示在首頁和倉庫頁面。  
   <img src="/images/repo-connected.png" alt="已連接的倉庫">

---

## 開始自動翻譯

1. 點選你剛連接的倉庫。  
   <img src="/images/select-repo-to-detail.png" alt="選擇倉庫">

2. 在倉庫詳細頁面底部，點選 <strong>編輯</strong>。  
   <img src="/images/select-edit.png" alt="選擇編輯">

3. 設定你的翻譯選項——目標分支（預設：`main`）、目標語言，以及原始語言（預設：`en`）。點選 <strong>儲存</strong>。  
   <img src="/images/configuration.png" alt="設定翻譯選項">

4. 點選 <strong>開始並自動化</strong>。  
   Localizeflow 會自動翻譯你的文件，只要原始檔案有變動就會開啟 pull request。  
   <img src="/images/select-automate.png" alt="開始並自動化">