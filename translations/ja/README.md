<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T06:50:00+00:00",
  "source_file": "README.md",
  "language_code": "ja"
}
-->
# Localizeflow – クイックスタートガイド

#### サポート: [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](./README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflowは、ドキュメントを自動で翻訳し、ソースファイルが変更されるたびにプルリクエストを作成します。  
このガイドでは、GitHubアプリのインストールから最初の翻訳まで、2分以内で始める方法を説明します。


> [!NOTE]
>
> Localizeflowは現在、GitHubベースのドキュメントプロジェクトに対応しています
> （例：AI for Beginners や一般的なオープンソースリポジトリ）。  
> 
> Astro、Docusaurus、Hugoなどの最新ドキュメントフレームワークへの対応も
> 開発中です。


---

## サインインとGitHubアプリのインストール

1. **[localizeflow.com](https://localizeflow.com/)** にアクセスします。
2. **Start with free trial** を選択します。
   <img alt="Select Start with free trial" src="/images/select-start-with-free-trial.png">
3. **Sign in with GitHub** を選択します。  
   <img alt="Sign in with GitHub" src="/images/select-sign-in-with-github.png">
4. GitHubアカウントでサインインします。  
   <img alt="GitHub login" src="/images/github-login.png">
5. Localizeflow GitHubアプリをインストールするアカウント（個人アカウントまたは管理している組織）を選びます。  
   <img alt="Select account" src="/images/select-which-account-to-use.png">
6. Localizeflowにアクセスさせたいリポジトリを選択し、**Save** をクリックします。  
   <img alt="Select repo and save" src="/images/select-repo-and-save.png">
7. Localizeflowのホームページにリダイレクトされます。

> [!TIP]
> 後からリポジトリを追加したい場合は、ヘッダーのアカウント名をクリックし、**+ Add more repositories** を選択してください。  
> <img alt="Add more repositories" src="/images/add-more-repo.png">

---

## リポジトリをLocalizeflowに接続する

1. Localizeflowのホームページで **+ Connect repositories** を選択します。  
   <img alt="Select connect repositories" src="/images/select-connect-repos.png">

2. インストール済みリポジトリの中から接続したいものを選び、**Save** をクリックします。  
   <img alt="Select repository" src="/images/select-repo.png">

3. 接続したリポジトリは、ホームページとリポジトリページの両方に表示されます。  
   <img alt="Connected repositories" src="/images/repo-connected.png">

---

## 自動翻訳を開始する

1. 接続したリポジトリを選択します。  
   <img alt="Select repository" src="/images/select-repo-to-detail.png">

2. リポジトリ詳細ページの下部で **Edit** を選択します。  
   <img alt="Select edit" src="/images/select-edit.png">

3. 翻訳設定を行います — 対象ブランチ（デフォルト: `main`）、翻訳先言語、ソース言語（デフォルト: `en`）を設定し、**Save** をクリックします。  
   <img alt="Configure translation settings" src="/images/configuration.png">

4. **Start & Automate** を選択します。  
   これでLocalizeflowがドキュメントを自動翻訳し、ソースが変更されるたびにプルリクエストを作成します。  
   <img alt="Start & Automate" src="/images/select-automate.png">