<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T07:36:48+00:00",
  "source_file": "README.md",
  "language_code": "ko"
}
-->
# Localizeflow – 빠른 시작 가이드

#### [Localizeflow](https://localizeflow.com/)에서 지원합니다

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](./README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow는 문서 파일이 변경될 때마다 자동으로 번역하고, 풀 리퀘스트를 생성합니다.  
이 가이드에서는 GitHub 앱을 설치하고 2분 이내에 첫 번역을 실행하는 방법을 안내합니다.


> [!NOTE]
>
> Localizeflow는 현재 GitHub 기반의 문서 프로젝트만 지원합니다  
> (예: AI for Beginners 및 대부분의 오픈소스 저장소).  
> 
> Astro, Docusaurus, Hugo 등 최신 문서 프레임워크 지원은  
> 개발 중입니다.


---

## 로그인 및 GitHub 앱 설치

1. **[localizeflow.com](https://localizeflow.com/)**에 접속하세요.
2. **무료 체험 시작**을 선택하세요.
   <img alt="무료 체험 시작 선택" src="/images/select-start-with-free-trial.png">
3. **GitHub로 로그인**을 선택하세요.  
   <img alt="GitHub로 로그인" src="/images/select-sign-in-with-github.png">
4. GitHub 계정으로 로그인하세요.  
   <img alt="GitHub 로그인" src="/images/github-login.png">
5. Localizeflow GitHub 앱을 설치할 계정(개인 계정 또는 관리하는 조직)을 선택하세요.  
   <img alt="계정 선택" src="/images/select-which-account-to-use.png">
6. Localizeflow가 접근할 저장소를 선택한 후, **저장**을 누르세요.  
   <img alt="저장소 선택 및 저장" src="/images/select-repo-and-save.png">
7. Localizeflow 홈페이지로 이동합니다.

> [!TIP]
> 저장소를 추가로 연결하려면, 상단에서 계정을 선택한 후 **+ 저장소 추가**를 클릭하세요.  
> <img alt="저장소 추가" src="/images/add-more-repo.png">

---

## 저장소를 Localizeflow에 연결하기

1. Localizeflow 홈페이지에서 **+ 저장소 연결**을 선택하세요.  
   <img alt="저장소 연결 선택" src="/images/select-connect-repos.png">

2. 설치된 저장소 중 연결할 저장소를 선택하고 **저장**을 누르세요.  
   <img alt="저장소 선택" src="/images/select-repo.png">

3. 연결된 저장소는 홈 페이지와 저장소 페이지에 표시됩니다.  
   <img alt="연결된 저장소" src="/images/repo-connected.png">

---

## 자동 번역 시작하기

1. 방금 연결한 저장소를 선택하세요.  
   <img alt="저장소 선택" src="/images/select-repo-to-detail.png">

2. 저장소 상세 페이지 하단에서 **편집**을 선택하세요.  
   <img alt="편집 선택" src="/images/select-edit.png">

3. 번역 설정을 구성하세요 — 대상 브랜치(기본값: `main`), 번역할 언어, 원본 언어(기본값: `en`). 설정 후 **저장**을 누르세요.  
   <img alt="번역 설정 구성" src="/images/configuration.png">

4. **시작 및 자동화**를 선택하세요.  
   이제 Localizeflow가 문서를 자동으로 번역하고, 소스가 변경될 때마다 풀 리퀘스트를 생성합니다.  
   <img alt="시작 및 자동화" src="/images/select-automate.png">