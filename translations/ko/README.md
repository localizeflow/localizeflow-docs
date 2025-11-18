<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T10:41:08+00:00",
  "source_file": "README.md",
  "language_code": "ko"
}
-->
# Localizeflow – 빠른 시작 가이드

#### [Localizeflow](https://localizeflow.com/) 지원

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](./README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow는 문서가 변경될 때마다 자동으로 번역하고 풀 리퀘스트를 엽니다.  
이 가이드는 GitHub 앱을 설치하고 2분 이내에 첫 번째 번역을 실행하는 방법을 보여줍니다.


> [!NOTE]
>
> Localizeflow는 현재 GitHub 기반 문서 프로젝트를 지원합니다  
> (예: AI for Beginners 및 대부분의 표준 오픈 소스 저장소).  
> 
> Astro, Docusaurus, Hugo와 같은 최신 문서 프레임워크 지원은  
> 현재 활발히 개발 중입니다.


---

## GitHub 앱에 로그인하고 설치하기

1. **[localizeflow.com](https://localizeflow.com/)**에 방문합니다.
2. **Start with free trial**을 선택합니다.  
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. **Sign in with GitHub**를 선택합니다.  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. GitHub 계정으로 로그인합니다.  
   ![GitHub login](/images/github-login.png)
5. Localizeflow GitHub 앱을 설치할 계정을 선택합니다 — 개인 계정 또는 관리하는 조직.  
   ![Select account](/images/select-which-account-to-use.png)
6. Localizeflow가 접근할 저장소를 선택한 후 **Save**를 선택합니다.  
   ![Select repo and save](/images/select-repo-and-save.png)
7. Localizeflow 홈 페이지로 리디렉션됩니다.

> [!TIP]
> 나중에 저장소를 추가하려면 헤더에서 계정을 선택하고 **+ Add more repositories**를 선택하세요.  
> ![Add more repositories](/images/add-more-repo.png)

---

## 저장소를 Localizeflow에 연결하기

1. Localizeflow 홈 페이지에서 **+ Connect repositories**를 선택합니다.  
   ![Select connect repositories](/images/select-connect-repos.png)

2. 연결할 설치된 저장소 중 하나를 선택하고 **Save**를 선택합니다.  
   ![Select repository](/images/select-repo.png)

3. 연결된 저장소가 홈 페이지와 저장소 페이지 모두에 표시됩니다.  
   ![Connected repositories](/images/repo-connected.png)

---

## 자동 번역 시작하기

1. 방금 연결한 저장소를 선택합니다.  
   ![Select repository](/images/select-repo-to-detail.png)

2. 저장소 상세 페이지 하단에서 **Edit**를 선택합니다.  
   ![Select edit](/images/select-edit.png)

3. 번역 설정을 구성합니다 — 대상 브랜치(기본값: `main`), 대상 언어, 원본 언어(기본값: `en`). **Save**를 선택합니다.  
   ![Configure translation settings](/images/configuration.png)

4. **Start & Automate**를 선택합니다.  
   Localizeflow가 이제 문서를 자동으로 번역하고 원본이 변경될 때마다 풀 리퀘스트를 엽니다.  
   ![Start & Automate](/images/select-automate.png)