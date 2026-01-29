# Localizeflow – クイックスタートガイド

#### 提供：[Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](./README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **ローカルにクローンしたいですか？**

> このリポジトリには50以上の言語翻訳が含まれているため、ダウンロードサイズが大きくなります。翻訳なしでクローンする場合はスパースチェックアウトを使用してください：
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> これにより、コースを完了するために必要なすべてを、はるかに高速にダウンロードできます。
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflowはあなたのドキュメントを自動的に翻訳し、ソースファイルが変更されるたびにプルリクエストを開きます。  
このガイドではGitHub Appをインストールし、2分以内に最初の翻訳を実行する方法を説明します。


> [!NOTE]
>
> Localizeflowは現在GitHubベースのドキュメントプロジェクトをサポートしています  
> （例：AI for Beginnersやほとんどの標準的なオープンソースリポジトリ）。  
> 最新のドキュメントフレームワークであるAstro、Docusaurus、Hugoのサポートは  
> 現在開発中です。


---

## GitHub Appへサインインしてインストールする

1. **[localizeflow.com](https://localizeflow.com/)** を訪問します。
2. **無料トライアルで始める** を選択します。
   ![無料トライアルで始めるを選択](../../../../translated images/ja/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **GitHubでサインイン** を選択します。  
   ![GitHubでサインイン](../../../../translated images/ja/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. GitHubアカウントでサインインします。  
   ![GitHubログイン](../../../../translated images/ja/github-login.02bbaee0270b292e.webp)
5. Localizeflow GitHub Appをインストールするアカウントを選択します — 個人アカウントか管理している組織。  
   ![アカウントを選択](../../../../translated images/ja/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflowにアクセスさせたいリポジトリを選択し、**保存** を選択します。  
   ![リポジトリを選択して保存](../../../../translated images/ja/select-repo-and-save.5a95ae288aefec6e.webp)
7. Localizeflowのホームページにリダイレクトされます。

> [!TIP]
> 後からリポジトリを追加したい場合は、ヘッダーのアカウントを選択し、**＋リポジトリを追加** を選択してください。  
> ![リポジトリを追加](../../../../translated images/ja/add-more-repo.2ca5154473aaaafb.webp)

---

## リポジトリをLocalizeflowに接続する

1. Localizeflowホームページで **＋リポジトリを接続** を選択します。  
   ![リポジトリを接続を選択](../../../../translated images/ja/select-connect-repos.8ac6f96f77dcc62c.webp)

2. 接続したいインストール済みリポジトリの1つを選択し、**保存** を選択します。  
   ![リポジトリを選択](../../../../translated images/ja/select-repo.dce94db722b44cf3.webp)

3. 接続されたリポジトリがホームページとリポジトリページの両方に表示されます。  
   ![接続されたリポジトリ](../../../../translated images/ja/repo-connected.9e5c21ee789fdcaa.webp)

---

## 自動翻訳を開始する

1. 先ほど接続したリポジトリを選択します。  
   ![リポジトリを選択](../../../../translated images/ja/select-repo-to-detail.55e53233531f8518.webp)

2. リポジトリ詳細ページで下部の **編集** を選択します。  
   ![編集を選択](../../../../translated images/ja/select-edit.225184c8c46d7001.webp)

3. 翻訳設定を構成します — 対象ブランチ（デフォルト:`main`）、対象言語、ソース言語（デフォルト:`en`）。**保存** を選択します。  
   ![翻訳設定を構成](../../../../translated images/ja/configuration.ab55d0f8bab5711b.webp)

4. **開始＆自動化** を選択します。  
   Localizeflowはこれでドキュメントを自動的に翻訳し、ソースが変更されるたびにプルリクエストを開きます。  
   ![開始＆自動化](../../../../translated images/ja/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**免責事項**：  
本書類はAI翻訳サービス「Co-op Translator」（https://github.com/Azure/co-op-translator）を使用して翻訳されました。正確性を期してはおりますが、自動翻訳には誤りや不正確な箇所が含まれる可能性があることをご承知おきください。原文の言語による文書が正式な情報源とみなされます。重要な情報については、専門の人間による翻訳を推奨します。本翻訳の利用により生じたいかなる誤解や解釈の相違についても、一切の責任を負いかねます。
<!-- CO-OP TRANSLATOR DISCLAIMER END -->