# Localizeflow – Schnellstartanleitung

#### Unterstützt von [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](./README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Möchten Sie lieber lokal klonen?**

> Dieses Repository enthält 50+ Sprachübersetzungen, was die Downloadgröße erheblich erhöht. Um ohne Übersetzungen zu klonen, verwenden Sie Sparse Checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Damit erhalten Sie alles, was Sie benötigen, um den Kurs abzuschließen, bei einem viel schnelleren Download.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow übersetzt automatisch Ihre Dokumentation und öffnet Pull Requests, sobald sich die Quelldatei ändert.  
Diese Anleitung zeigt Ihnen, wie Sie die GitHub-App installieren und Ihre erste Übersetzung in weniger als 2 Minuten durchführen.

> [!NOTE]
>
> Localizeflow unterstützt derzeit GitHub-basierte Dokumentationsprojekte
> (z. B.: AI for Beginners und die meisten Standard-Open-Source-Repos).  
> 
> Die Unterstützung für moderne Dokumentationsframeworks wie Astro, Docusaurus und Hugo  
> befindet sich in aktiver Entwicklung.


---

## Melden Sie sich an und installieren Sie die GitHub-App

1. Besuchen Sie **[localizeflow.com](https://localizeflow.com/)**.
2. Wählen Sie **Start with free trial**.
   ![Wählen Sie Start with free trial](../../../../translated images/de/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Wählen Sie **Sign in with GitHub**.  
   ![Mit GitHub anmelden](../../../../translated images/de/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Melden Sie sich mit Ihrem GitHub-Konto an.  
   ![GitHub-Anmeldung](../../../../translated images/de/github-login.02bbaee0270b292e.webp)
5. Wählen Sie das Konto, bei dem Sie die Localizeflow GitHub-App installieren möchten — Ihr persönliches Konto oder eine Organisation, die Sie verwalten.  
   ![Konto auswählen](../../../../translated images/de/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Wählen Sie die Repositories aus, auf die Localizeflow zugreifen soll, und wählen Sie dann **Save**.  
   ![Repo auswählen und speichern](../../../../translated images/de/select-repo-and-save.5a95ae288aefec6e.webp)
7. Sie werden zur Localizeflow-Startseite weitergeleitet.

> [!TIP]
> Um später weitere Repositories hinzuzufügen, wählen Sie Ihr Konto in der Kopfzeile aus und klicken Sie auf **+ Add more repositories**.  
> ![Weitere Repositories hinzufügen](../../../../translated images/de/add-more-repo.2ca5154473aaaafb.webp)

---

## Verbinden Sie Ihre Repositories mit Localizeflow

1. Wählen Sie auf der Localizeflow-Startseite **+ Connect repositories**.  
   ![Connect repositories auswählen](../../../../translated images/de/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Wählen Sie eines der installierten Repositories aus, das Sie verbinden möchten, und klicken Sie auf **Save**.  
   ![Repository auswählen](../../../../translated images/de/select-repo.dce94db722b44cf3.webp)

3. Die verbundenen Repositories werden nun sowohl auf der Startseite als auch auf der Repositories-Seite angezeigt.  
   ![Verbundenes Repository](../../../../translated images/de/repo-connected.9e5c21ee789fdcaa.webp)

---

## Automatische Übersetzung starten

1. Wählen Sie das Repository aus, das Sie gerade verbunden haben.  
   ![Repository auswählen](../../../../translated images/de/select-repo-to-detail.55e53233531f8518.webp)

2. Wählen Sie auf der Detailseite des Repositories unten **Edit** aus.  
   ![Edit auswählen](../../../../translated images/de/select-edit.225184c8c46d7001.webp)

3. Konfigurieren Sie Ihre Übersetzungseinstellungen — Ziel-Branch (Standard: `main`), Zielsprachen und Quellsprache (Standard: `en`). Wählen Sie **Save**.  
   ![Übersetzungseinstellungen konfigurieren](../../../../translated images/de/configuration.ab55d0f8bab5711b.webp)

4. Wählen Sie **Start & Automate**.  
   Localizeflow wird nun Ihre Dokumentation automatisch übersetzen und Pull Requests öffnen, sobald sich die Quelle ändert.  
   ![Start & Automate](../../../../translated images/de/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Haftungsausschluss**:  
Dieses Dokument wurde mithilfe des KI-Übersetzungsdienstes [Co-op Translator](https://github.com/Azure/co-op-translator) übersetzt. Obwohl wir auf Genauigkeit achten, können automatisierte Übersetzungen Fehler oder Ungenauigkeiten enthalten. Die Originalfassung des Dokuments in der Ursprungssprache ist als maßgebliche Quelle zu betrachten. Für wichtige Informationen wird eine professionelle menschliche Übersetzung empfohlen. Wir übernehmen keine Haftung für Missverständnisse oder Fehlinterpretationen, die durch die Nutzung dieser Übersetzung entstehen.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->