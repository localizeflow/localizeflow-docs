<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T06:49:46+00:00",
  "source_file": "README.md",
  "language_code": "zh"
}
-->
# Localizeflow – 快速入门指南

#### 由 <a href="https://localizeflow.com/">Localizeflow</a> 提供支持

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
<a href="./translations/ar/README.md">阿拉伯语</a> | <a href="./translations/bn/README.md">孟加拉语</a> | <a href="./translations/bg/README.md">保加利亚语</a> | <a href="./translations/my/README.md">缅甸语</a> | <a href="./translations/zh/README.md">中文（简体）</a> | <a href="./translations/hk/README.md">中文（繁体，香港）</a> | <a href="./translations/mo/README.md">中文（繁体，澳门）</a> | <a href="./translations/tw/README.md">中文（繁体，台湾）</a> | <a href="./translations/hr/README.md">克罗地亚语</a> | <a href="./translations/cs/README.md">捷克语</a> | <a href="./translations/da/README.md">丹麦语</a> | <a href="./translations/nl/README.md">荷兰语</a> | <a href="./translations/et/README.md">爱沙尼亚语</a> | <a href="./translations/fi/README.md">芬兰语</a> | <a href="./translations/fr/README.md">法语</a> | <a href="./translations/de/README.md">德语</a> | <a href="./translations/el/README.md">希腊语</a> | <a href="./translations/he/README.md">希伯来语</a> | <a href="./translations/hi/README.md">印地语</a> | <a href="./translations/hu/README.md">匈牙利语</a> | <a href="./translations/id/README.md">印尼语</a> | <a href="./translations/it/README.md">意大利语</a> | <a href="./translations/ja/README.md">日语</a> | <a href="./translations/ko/README.md">韩语</a> | <a href="./translations/lt/README.md">立陶宛语</a> | <a href="./translations/ms/README.md">马来语</a> | <a href="./translations/mr/README.md">马拉地语</a> | <a href="./translations/ne/README.md">尼泊尔语</a> | <a href="./translations/pcm/README.md">尼日利亚皮钦语</a> | <a href="./translations/no/README.md">挪威语</a> | <a href="./translations/fa/README.md">波斯语</a> | <a href="./translations/pl/README.md">波兰语</a> | <a href="./translations/br/README.md">葡萄牙语（巴西）</a> | <a href="./translations/pt/README.md">葡萄牙语（葡萄牙）</a> | <a href="./translations/pa/README.md">旁遮普语（古木基文）</a> | <a href="./translations/ro/README.md">罗马尼亚语</a> | <a href="./translations/ru/README.md">俄语</a> | <a href="./translations/sr/README.md">塞尔维亚语（西里尔文）</a> | <a href="./translations/sk/README.md">斯洛伐克语</a> | <a href="./translations/sl/README.md">斯洛文尼亚语</a> | <a href="./translations/es/README.md">西班牙语</a> | <a href="./translations/sw/README.md">斯瓦希里语</a> | <a href="./translations/sv/README.md">瑞典语</a> | <a href="./translations/tl/README.md">他加禄语（菲律宾语）</a> | <a href="./translations/ta/README.md">泰米尔语</a> | <a href="./translations/th/README.md">泰语</a> | <a href="./translations/tr/README.md">土耳其语</a> | <a href="./translations/uk/README.md">乌克兰语</a> | <a href="./translations/ur/README.md">乌尔都语</a> | <a href="./translations/vi/README.md">越南语</a>
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow 会自动翻译你的文档，并在源文件发生更改时自动创建拉取请求。  
本指南将带你在 2 分钟内完成 GitHub 应用的安装并运行首次翻译。

> [!NOTE]
>
> Localizeflow 目前支持基于 GitHub 的文档项目  
> （例如：AI for Beginners 以及大多数标准开源仓库）。
>
> 对于 Astro、Docusaurus、Hugo 等现代文档框架的支持  
> 正在积极开发中。

---

## 登录并安装 GitHub 应用

1. 访问 **<a href="https://localizeflow.com/">localizeflow.com</a>**。
2. 选择 **Start with free trial（免费试用）**。
   <img src="/images/select-start-with-free-trial.png" alt="选择免费试用">
3. 选择 **Sign in with GitHub（使用 GitHub 登录）**。  
   <img src="/images/select-sign-in-with-github.png" alt="使用 GitHub 登录">
4. 使用你的 GitHub 账号登录。  
   <img src="/images/github-login.png" alt="GitHub 登录">
5. 选择你要安装 Localizeflow GitHub 应用的账号——可以是你的个人账号，也可以是你管理的组织。  
   <img src="/images/select-which-account-to-use.png" alt="选择账号">
6. 选择你希望 Localizeflow 访问的仓库，然后点击 **Save（保存）**。  
   <img src="/images/select-repo-and-save.png" alt="选择仓库并保存">
7. 系统会自动跳转到 Localizeflow 首页。

> [!TIP]
> 如果之后需要添加更多仓库，可以在页面顶部点击你的账号，然后选择 **+ Add more repositories（添加更多仓库）**。  
> <img src="/images/add-more-repo.png" alt="添加更多仓库">

---

## 将你的仓库连接到 Localizeflow

1. 在 Localizeflow 首页，点击 **+ Connect repositories（连接仓库）**。  
   <img src="/images/select-connect-repos.png" alt="选择连接仓库">

2. 选择你已安装的某个仓库，点击 **Save（保存）**。  
   <img src="/images/select-repo.png" alt="选择仓库">

3. 你已连接的仓库会显示在首页和“Repositories（仓库）”页面。  
   <img src="/images/repo-connected.png" alt="已连接的仓库">

---

## 开始自动翻译

1. 选择你刚刚连接的仓库。  
   <img src="/images/select-repo-to-detail.png" alt="选择仓库">

2. 在仓库详情页底部，点击 **Edit（编辑）**。  
   <img src="/images/select-edit.png" alt="选择编辑">

3. 配置你的翻译设置——目标分支（默认：`main`）、目标语言和源语言（默认：`en`）。点击 **Save（保存）**。  
   <img src="/images/configuration.png" alt="配置翻译设置">

4. 点击 **Start & Automate（开始并自动化）**。  
   Localizeflow 现在会自动翻译你的文档，并在源文件变更时自动创建拉取请求。  
   <img src="/images/select-automate.png" alt="开始并自动化">