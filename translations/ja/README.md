<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T10:41:52+00:00",
  "source_file": "README.md",
  "language_code": "ja"
}
-->
# Localizeflow – クイックスタートガイド

#### [Localizeflow](https://localizeflow.com/) によるサポート

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](./README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflowは、ドキュメントを自動的に翻訳し、ソースファイルが変更されるたびにプルリクエストを作成します。  
このガイドでは、GitHubアプリのインストール方法と最初の翻訳を2分以内で実行する方法を説明します。

> [!NOTE]
>
> Localizeflowは現在、GitHubベースのドキュメントプロジェクトをサポートしています  
> （例：AI for Beginnersやほとんどの標準的なオープンソースリポジトリ）。  
> 
> Astro、Docusaurus、Hugoなどの最新のドキュメントフレームワークのサポートは  
> 現在積極的に開発中です。

---

## サインインしてGitHubアプリをインストールする

1. **[localizeflow.com](https://localizeflow.com/)** にアクセスします。  
2. **Start with free trial** を選択します。  
   ![Select Start with free trial](/images/select-start-with-free-trial.png)  
3. **Sign in with GitHub** を選択します。  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)  
4. GitHubアカウントでサインインします。  
   ![GitHub login](/images/github-login.png)  
5. Localizeflow GitHubアプリをインストールするアカウントを選択します — 個人アカウントまたは管理している組織。  
   ![Select account](/images/select-which-account-to-use.png)  
6. Localizeflowにアクセスを許可するリポジトリを選択し、**Save** を選択します。  
   ![Select repo and save](/images/select-repo-and-save.png)  
7. Localizeflowのホームページにリダイレクトされます。

> [!TIP]
> 後でリポジトリを追加するには、ヘッダーのアカウントを選択し、**+ Add more repositories** を選択します。  
> ![Add more repositories](/images/add-more-repo.png)

---

## リポジトリをLocalizeflowに接続する

1. Localizeflowのホームページで、**+ Connect repositories** を選択します。  
   ![Select connect repositories](/images/select-connect-repos.png)

2. 接続したいインストール済みのリポジトリの1つを選択し、**Save** を選択します。  
   ![Select repository](/images/select-repo.png)

3. 接続されたリポジトリはホームページとリポジトリページの両方に表示されます。  
   ![Connected repositories](/images/repo-connected.png)

---

## 自動翻訳を開始する

1. 先ほど接続したリポジトリを選択します。  
   ![Select repository](/images/select-repo-to-detail.png)

2. リポジトリ詳細ページの下部にある **Edit** を選択します。  
   ![Select edit](/images/select-edit.png)

3. 翻訳設定を構成します — 対象ブランチ（デフォルト：`main`）、対象言語、ソース言語（デフォルト：`en`）。**Save** を選択します。  
   ![Configure translation settings](/images/configuration.png)

4. **Start & Automate** を選択します。  
   Localizeflowはこれでドキュメントを自動的に翻訳し、ソースが変更されるたびにプルリクエストを作成します。  
   ![Start & Automate](/images/select-automate.png)