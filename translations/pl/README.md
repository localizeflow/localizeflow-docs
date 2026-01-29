# Localizeflow – Przewodnik szybkiego startu

#### Wspierane przez [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](./README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Wolisz sklonować lokalnie?**

> To repozytorium zawiera tłumaczenia na ponad 50 języków, co znacznie zwiększa rozmiar pobierania. Aby sklonować bez tłumaczeń, użyj sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> To dostarczy Ci wszystko, czego potrzebujesz do ukończenia kursu, z dużo szybszym pobieraniem.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow automatycznie tłumaczy Twoją dokumentację i otwiera pull requesty za każdym razem, gdy plik źródłowy się zmienia.  
Ten przewodnik pokaże Ci, jak zainstalować aplikację GitHub i wykonać pierwsze tłumaczenie w mniej niż 2 minuty.


> [!NOTE]
>
> Localizeflow obecnie wspiera projekty dokumentacji oparte na GitHub
> (na przykład: AI for Beginners i większość standardowych repozytoriów open-source).  
> 
> Wsparcie dla nowoczesnych frameworków dokumentacyjnych takich jak Astro, Docusaurus i Hugo  
> jest w trakcie aktywnego rozwoju.


---

## Zaloguj się i zainstaluj aplikację GitHub

1. Odwiedź **[localizeflow.com](https://localizeflow.com/)**.
2. Wybierz **Start with free trial**.
   ![Select Start with free trial](../../../../translated images/pl/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Wybierz **Sign in with GitHub**.  
   ![Sign in with GitHub](../../../../translated images/pl/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Zaloguj się za pomocą konta GitHub.  
   ![GitHub login](../../../../translated images/pl/github-login.02bbaee0270b292e.webp)
5. Wybierz konto, na którym chcesz zainstalować aplikację Localizeflow GitHub — swoje konto osobiste lub organizację, którą zarządzasz.  
   ![Select account](../../../../translated images/pl/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Wybierz repozytoria, do których Localizeflow będzie miał dostęp, a następnie kliknij **Save**.  
   ![Select repo and save](../../../../translated images/pl/select-repo-and-save.5a95ae288aefec6e.webp)
7. Zostaniesz przekierowany na stronę główną Localizeflow.

> [!TIP]
> Aby dodać więcej repozytoriów później, wybierz swoje konto w nagłówku i wybierz **+ Add more repositories**.  
> ![Add more repositories](../../../../translated images/pl/add-more-repo.2ca5154473aaaafb.webp)

---

## Połącz swoje repozytoria z Localizeflow

1. Na stronie głównej Localizeflow wybierz **+ Connect repositories**.  
   ![Select connect repositories](../../../../translated images/pl/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Wybierz jedno z zainstalowanych repozytoriów, które chcesz połączyć i kliknij **Save**.  
   ![Select repository](../../../../translated images/pl/select-repo.dce94db722b44cf3.webp)

3. Twoje połączone repozytoria pojawią się teraz zarówno na stronie głównej, jak i na stronie Repozytoriów.  
   ![Connected repositories](../../../../translated images/pl/repo-connected.9e5c21ee789fdcaa.webp)

---

## Rozpocznij automatyczne tłumaczenie

1. Wybierz repozytorium, które właśnie połączyłeś.  
   ![Select repository](../../../../translated images/pl/select-repo-to-detail.55e53233531f8518.webp)

2. Na stronie szczegółów repozytorium wybierz **Edit** na dole.  
   ![Select edit](../../../../translated images/pl/select-edit.225184c8c46d7001.webp)

3. Skonfiguruj ustawienia tłumaczenia — docelową gałąź (domyślnie: `main`), języki docelowe oraz język źródłowy (domyślnie: `en`). Wybierz **Save**.  
   ![Configure translation settings](../../../../translated images/pl/configuration.ab55d0f8bab5711b.webp)

4. Wybierz **Start & Automate**.  
   Localizeflow będzie teraz automatycznie tłumaczył Twoją dokumentację i otwierał pull requesty za każdym razem, gdy źródło się zmieni.  
   ![Start & Automate](../../../../translated images/pl/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Zastrzeżenie**:  
Niniejszy dokument został przetłumaczony za pomocą usługi tłumaczeń AI [Co-op Translator](https://github.com/Azure/co-op-translator). Mimo że dążymy do jak największej dokładności, prosimy pamiętać, że automatyczne tłumaczenia mogą zawierać błędy lub nieścisłości. Oryginalny dokument w języku źródłowym należy traktować jako autorytatywne źródło. W przypadku istotnych informacji zaleca się skorzystanie z profesjonalnego tłumaczenia wykonanego przez człowieka. Nie ponosimy odpowiedzialności za jakiekolwiek nieporozumienia lub błędne interpretacje wynikające z użycia tego tłumaczenia.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->