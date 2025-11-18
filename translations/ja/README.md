<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T07:37:12+00:00",
  "source_file": "README.md",
  "language_code": "ja"
}
-->
# Localizeflow – クイックスタートガイド

#### サポート: <a href="https://localizeflow.com/">Localizeflow</a>

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
<a href="./translations/ar/README.md">アラビア語</a> | <a href="./translations/bn/README.md">ベンガル語</a> | <a href="./translations/bg/README.md">ブルガリア語</a> | <a href="./translations/my/README.md">ビルマ語（ミャンマー）</a> | <a href="./translations/zh/README.md">中国語（簡体字）</a> | <a href="./translations/hk/README.md">中国語（繁体字・香港）</a> | <a href="./translations/mo/README.md">中国語（繁体字・マカオ）</a> | <a href="./translations/tw/README.md">中国語（繁体字・台湾）</a> | <a href="./translations/hr/README.md">クロアチア語</a> | <a href="./translations/cs/README.md">チェコ語</a> | <a href="./translations/da/README.md">デンマーク語</a> | <a href="./translations/nl/README.md">オランダ語</a> | <a href="./translations/et/README.md">エストニア語</a> | <a href="./translations/fi/README.md">フィンランド語</a> | <a href="./translations/fr/README.md">フランス語</a> | <a href="./translations/de/README.md">ドイツ語</a> | <a href="./translations/el/README.md">ギリシャ語</a> | <a href="./translations/he/README.md">ヘブライ語</a> | <a href="./translations/hi/README.md">ヒンディー語</a> | <a href="./translations/hu/README.md">ハンガリー語</a> | <a href="./translations/id/README.md">インドネシア語</a> | <a href="./translations/it/README.md">イタリア語</a> | <a href="./translations/ja/README.md">日本語</a> | <a href="./translations/ko/README.md">韓国語</a> | <a href="./translations/lt/README.md">リトアニア語</a> | <a href="./translations/ms/README.md">マレー語</a> | <a href="./translations/mr/README.md">マラーティー語</a> | <a href="./translations/ne/README.md">ネパール語</a> | <a href="./translations/pcm/README.md">ナイジェリア・ピジン</a> | <a href="./translations/no/README.md">ノルウェー語</a> | <a href="./translations/fa/README.md">ペルシャ語（ファルシ）</a> | <a href="./translations/pl/README.md">ポーランド語</a> | <a href="./translations/br/README.md">ポルトガル語（ブラジル）</a> | <a href="./translations/pt/README.md">ポルトガル語（ポルトガル）</a> | <a href="./translations/pa/README.md">パンジャブ語（グルムキー）</a> | <a href="./translations/ro/README.md">ルーマニア語</a> | <a href="./translations/ru/README.md">ロシア語</a> | <a href="./translations/sr/README.md">セルビア語（キリル）</a> | <a href="./translations/sk/README.md">スロバキア語</a> | <a href="./translations/sl/README.md">スロベニア語</a> | <a href="./translations/es/README.md">スペイン語</a> | <a href="./translations/sw/README.md">スワヒリ語</a> | <a href="./translations/sv/README.md">スウェーデン語</a> | <a href="./translations/tl/README.md">タガログ語（フィリピン）</a> | <a href="./translations/ta/README.md">タミル語</a> | <a href="./translations/th/README.md">タイ語</a> | <a href="./translations/tr/README.md">トルコ語</a> | <a href="./translations/uk/README.md">ウクライナ語</a> | <a href="./translations/ur/README.md">ウルドゥー語</a> | <a href="./translations/vi/README.md">ベトナム語</a>
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

## サインインしてGitHubアプリをインストールする

1. **<a href="https://localizeflow.com/">localizeflow.com</a>** にアクセスします。
2. **Start with free trial** を選択します。
   <img src="/images/select-start-with-free-trial.png" alt="Select Start with free trial">
3. **Sign in with GitHub** を選択します。  
   <img src="/images/select-sign-in-with-github.png" alt="Sign in with GitHub">
4. GitHubアカウントでサインインします。  
   <img src="/images/github-login.png" alt="GitHub login">
5. Localizeflow GitHubアプリをインストールするアカウント（個人アカウントまたは管理している組織）を選択します。  
   <img src="/images/select-which-account-to-use.png" alt="Select account">
6. Localizeflowにアクセスさせたいリポジトリを選び、**Save** をクリックします。  
   <img src="/images/select-repo-and-save.png" alt="Select repo and save">
7. Localizeflowのホームページにリダイレクトされます。

> [!TIP]
> 後からリポジトリを追加したい場合は、ヘッダーのアカウント名をクリックし、**+ Add more repositories** を選択してください。  
> <img src="/images/add-more-repo.png" alt="Add more repositories">

---

## リポジトリをLocalizeflowに接続する

1. Localizeflowのホームページで、**+ Connect repositories** を選択します。  
   <img src="/images/select-connect-repos.png" alt="Select connect repositories">

2. インストール済みリポジトリの中から接続したいものを選び、**Save** をクリックします。  
   <img src="/images/select-repo.png" alt="Select repository">

3. 接続したリポジトリは、ホームページとリポジトリ一覧ページの両方に表示されます。  
   <img src="/images/repo-connected.png" alt="Connected repositories">

---

## 自動翻訳を開始する

1. 接続したリポジトリを選択します。  
   <img src="/images/select-repo-to-detail.png" alt="Select repository">

2. リポジトリ詳細ページの下部で **Edit** を選択します。  
   <img src="/images/select-edit.png" alt="Select edit">

3. 翻訳設定を行います — 対象ブランチ（デフォルト: `main`）、翻訳先言語、ソース言語（デフォルト: `en`）を設定し、**Save** をクリックします。  
   <img src="/images/configuration.png" alt="Configure translation settings">

4. **Start & Automate** を選択します。  
   これでLocalizeflowがドキュメントを自動翻訳し、ソースが変更されるたびにプルリクエストを作成します。  
   <img src="/images/select-automate.png" alt="Start & Automate">