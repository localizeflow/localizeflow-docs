# Localizeflow – Schnellstartanleitung

#### Unterstützt von [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](./README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Möchten Sie lieber lokal klonen?**

> Dieses Repository enthält über 50 Sprachübersetzungen, wodurch die Download-Größe deutlich erhöht wird. Um ohne Übersetzungen zu klonen, verwenden Sie sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Damit erhalten Sie alles, was Sie benötigen, um den Kurs abzuschließen, mit einem viel schnelleren Download.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow übersetzt Ihre Dokumentation automatisch und erstellt Pull Requests, sobald sich die Quelldatei ändert.  
Diese Anleitung zeigt Ihnen, wie Sie die GitHub App installieren und Ihre erste Übersetzung in unter 2 Minuten durchführen.


> [!NOTE]
>
> Localizeflow unterstützt derzeit dokumentationsbasierte Projekte auf GitHub  
> (zum Beispiel: AI for Beginners und die meisten Standard-Open-Source-Repositories).  
>  
> Die Unterstützung für moderne Dokumentationsframeworks wie Astro, Docusaurus und Hugo  
> ist in aktiver Entwicklung.


---

## Melden Sie sich an und installieren Sie die GitHub App

1. Besuchen Sie **[localizeflow.com](https://localizeflow.com/)**.
2. Wählen Sie **Kostenlose Testversion starten**.
   ![Kostenlose Testversion starten auswählen](../../../../translated_images/de/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Wählen Sie **Mit GitHub anmelden**.  
   ![Mit GitHub anmelden](../../../../translated_images/de/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Melden Sie sich mit Ihrem GitHub-Konto an.  
   ![GitHub-Anmeldung](../../../../translated_images/de/github-login.02bbaee0270b292e.webp)
5. Wählen Sie das Konto aus, bei dem Sie die Localizeflow GitHub App installieren möchten – Ihr persönliches Konto oder eine von Ihnen verwaltete Organisation.  
   ![Konto auswählen](../../../../translated_images/de/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Wählen Sie die Repositories aus, auf die Localizeflow zugreifen soll, und klicken Sie dann auf **Speichern**.  
   ![Repository auswählen und speichern](../../../../translated_images/de/select-repo-and-save.5a95ae288aefec6e.webp)
7. Sie werden auf die Startseite von Localizeflow weitergeleitet.

> [!TIP]
> Um später weitere Repositories hinzuzufügen, wählen Sie Ihr Konto in der Kopfzeile aus und klicken auf **+ Weitere Repositories hinzufügen**.  
> ![Weitere Repositories hinzufügen](../../../../translated_images/de/add-more-repo.2ca5154473aaaafb.webp)

---

## Verbinden Sie Ihre Repositories mit Localizeflow

1. Klicken Sie auf der Localizeflow-Startseite auf **+ Repositories verbinden**.  
   ![Repositories verbinden auswählen](../../../../translated_images/de/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Wählen Sie eines der installierten Repositories aus, das Sie verbinden möchten, und klicken Sie auf **Speichern**.  
   ![Repository auswählen](../../../../translated_images/de/select-repo.dce94db722b44cf3.webp)

3. Ihre verbundenen Repositories werden nun sowohl auf der Startseite als auch auf der Seite Repositories angezeigt.  
   ![Verbundenes Repository](../../../../translated_images/de/repo-connected.9e5c21ee789fdcaa.webp)

---

## Starten Sie die automatische Übersetzung

1. Wählen Sie das gerade verbundene Repository aus.  
   ![Repository auswählen](../../../../translated_images/de/select-repo-to-detail.55e53233531f8518.webp)

2. Klicken Sie auf der Detailseite des Repositories unten auf **Bearbeiten**.  
   ![Bearbeiten auswählen](../../../../translated_images/de/select-edit.225184c8c46d7001.webp)

3. Konfigurieren Sie Ihre Übersetzungseinstellungen — Zielbranch (Standard: `main`), Zielsprachen und Quellsprache (Standard: `en`). Klicken Sie auf **Speichern**.  
   ![Übersetzungseinstellungen konfigurieren](../../../../translated_images/de/configuration.ab55d0f8bab5711b.webp)

4. Wählen Sie **Starten & Automatisieren**.  
   Localizeflow wird nun Ihre Dokumentation automatisch übersetzen und Pull Requests öffnen, sobald sich die Quelle ändert.  
   ![Starten & Automatisieren](../../../../translated_images/de/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Haftungsausschluss**:  
Dieses Dokument wurde mit dem KI-Übersetzungsdienst [Co-op Translator](https://github.com/Azure/co-op-translator) übersetzt. Obwohl wir uns um Genauigkeit bemühen, kann die automatisierte Übersetzung Fehler oder Ungenauigkeiten enthalten. Das Originaldokument in der Ausgangssprache gilt als maßgebliche Quelle. Für wichtige Informationen wird eine professionelle menschliche Übersetzung empfohlen. Wir übernehmen keine Haftung für Missverständnisse oder Fehlinterpretationen, die durch die Nutzung dieser Übersetzung entstehen.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->