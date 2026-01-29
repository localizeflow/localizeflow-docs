# Localizeflow – 빠른 시작 가이드

#### [Localizeflow](https://localizeflow.com/)에서 지원

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](./README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **로컬로 클론하기를 선호하시나요?**

> 이 저장소에는 50개 이상의 언어 번역이 포함되어 있어 다운로드 크기가 크게 증가합니다. 번역 없이 클론하려면 sparse checkout을 사용하세요:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> 이렇게 하면 훨씬 빠른 다운로드 속도로 강의를 완료하는 데 필요한 모든 것을 얻을 수 있습니다.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow는 문서가 변경될 때마다 자동으로 번역하고 풀 리퀘스트를 엽니다.  
이 가이드에서는 GitHub 앱 설치 및 2분 이내에 첫 번째 번역을 실행하는 방법을 안내합니다.


> [!NOTE]
>
> Localizeflow는 현재 GitHub 기반 문서 프로젝트를 지원합니다.
> (예: AI for Beginners 및 대부분의 표준 오픈소스 저장소).  
> 
> Astro, Docusaurus, Hugo와 같은 최신 문서 프레임워크 지원은  
> 적극적으로 개발 중입니다.


---

## 로그인하고 GitHub 앱 설치하기

1. **[localizeflow.com](https://localizeflow.com/)**을 방문합니다.
2. **무료 체험으로 시작**을 선택합니다.
   ![무료 체험으로 시작 선택](../../../../translated images/ko/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **GitHub로 로그인**을 선택합니다.  
   ![GitHub로 로그인](../../../../translated images/ko/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. GitHub 계정으로 로그인합니다.  
   ![GitHub 로그인](../../../../translated images/ko/github-login.02bbaee0270b292e.webp)
5. Localizeflow GitHub 앱을 설치할 계정을 선택합니다 — 개인 계정 또는 관리하는 조직.  
   ![계정 선택](../../../../translated images/ko/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflow가 접근할 저장소를 선택한 뒤 **저장**을 선택합니다.  
   ![저장소 선택 후 저장](../../../../translated images/ko/select-repo-and-save.5a95ae288aefec6e.webp)
7. Localizeflow 홈 페이지로 리디렉션됩니다.

> [!TIP]
> 나중에 저장소를 추가하려면 헤더에서 계정을 선택한 후 **+ 저장소 추가**를 선택하세요.  
> ![저장소 추가](../../../../translated images/ko/add-more-repo.2ca5154473aaaafb.webp)

---

## 저장소를 Localizeflow에 연결하기

1. Localizeflow 홈 페이지에서 **+ 저장소 연결**을 선택합니다.  
   ![저장소 연결 선택](../../../../translated images/ko/select-connect-repos.8ac6f96f77dcc62c.webp)

2. 연결하려는 설치된 저장소 중 하나를 선택하고 **저장**을 선택합니다.  
   ![저장소 선택](../../../../translated images/ko/select-repo.dce94db722b44cf3.webp)

3. 연결한 저장소가 홈 페이지와 저장소 페이지 두 곳에 표시됩니다.  
   ![연결된 저장소](../../../../translated images/ko/repo-connected.9e5c21ee789fdcaa.webp)

---

## 자동 번역 시작하기

1. 방금 연결한 저장소를 선택합니다.  
   ![저장소 선택](../../../../translated images/ko/select-repo-to-detail.55e53233531f8518.webp)

2. 저장소 상세 페이지에서 아래쪽의 **편집**을 선택합니다.  
   ![편집 선택](../../../../translated images/ko/select-edit.225184c8c46d7001.webp)

3. 번역 설정을 구성합니다 — 대상 브랜치 (기본값: `main`), 대상 언어, 원본 언어 (기본값: `en`). **저장**을 선택합니다.  
   ![번역 설정 구성](../../../../translated images/ko/configuration.ab55d0f8bab5711b.webp)

4. **시작 및 자동화**를 선택합니다.  
   Localizeflow가 이제 문서를 자동으로 번역하고 원본 변경 시마다 풀 리퀘스트를 엽니다.  
   ![시작 및 자동화](../../../../translated images/ko/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**면책 조항**:  
본 문서는 AI 번역 서비스 [Co-op Translator](https://github.com/Azure/co-op-translator)를 사용하여 번역되었습니다. 정확성을 위해 노력하고 있으나, 자동 번역에는 오류나 부정확성이 포함될 수 있음을 유의하시기 바랍니다. 원문 문서가 권위 있는 출처임을 인정하며, 중요한 정보의 경우 전문 번역가에 의한 번역을 권장합니다. 본 번역 사용으로 인한 오해나 잘못된 해석에 대해 당사는 책임을 지지 않습니다.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->