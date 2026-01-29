# Localizeflow – Guide de démarrage rapide

#### Pris en charge par [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](./README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Préférez cloner localement ?**

> Ce dépôt inclut plus de 50 traductions de langues, ce qui augmente considérablement la taille du téléchargement. Pour cloner sans les traductions, utilisez le sparse checkout :
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Cela vous donne tout ce dont vous avez besoin pour suivre le cours avec un téléchargement beaucoup plus rapide.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow traduit automatiquement votre documentation et ouvre des pull requests chaque fois que le fichier source change.  
Ce guide vous montre comment installer l’App GitHub et effectuer votre première traduction en moins de 2 minutes.


> [!NOTE]
>
> Localizeflow supporte actuellement les projets de documentation basés sur GitHub
> (par exemple : AI for Beginners et la plupart des dépôts open-source standards).  
> 
> La prise en charge des frameworks modernes de documentation tels qu’Astro, Docusaurus et Hugo  
> est en cours de développement actif.


---

## Connectez-vous et installez l’App GitHub

1. Visitez **[localizeflow.com](https://localizeflow.com/)**.
2. Sélectionnez **Commencer avec un essai gratuit**.
   ![Sélectionner Commencer avec un essai gratuit](../../../../translated_images/fr/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Sélectionnez **Se connecter avec GitHub**.  
   ![Se connecter avec GitHub](../../../../translated_images/fr/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Connectez-vous avec votre compte GitHub.  
   ![Connexion GitHub](../../../../translated_images/fr/github-login.02bbaee0270b292e.webp)
5. Choisissez le compte sur lequel vous souhaitez installer l’App GitHub Localizeflow — votre compte personnel ou une organisation que vous gérez.  
   ![Sélectionner le compte](../../../../translated_images/fr/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Sélectionnez les dépôts auxquels vous souhaitez que Localizeflow accède, puis choisissez **Enregistrer**.  
   ![Sélectionner le dépôt et enregistrer](../../../../translated_images/fr/select-repo-and-save.5a95ae288aefec6e.webp)
7. Vous serez redirigé vers la page d’accueil de Localizeflow.

> [!TIP]
> Pour ajouter plus de dépôts plus tard, sélectionnez votre compte dans l’en-tête et choisissez **+ Ajouter plus de dépôts**.  
> ![Ajouter plus de dépôts](../../../../translated_images/fr/add-more-repo.2ca5154473aaaafb.webp)

---

## Connectez vos dépôts à Localizeflow

1. Sur la page d’accueil de Localizeflow, sélectionnez **+ Connecter des dépôts**.  
   ![Sélectionner connecter des dépôts](../../../../translated_images/fr/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Choisissez un des dépôts installés que vous souhaitez connecter, puis sélectionnez **Enregistrer**.  
   ![Sélectionner le dépôt](../../../../translated_images/fr/select-repo.dce94db722b44cf3.webp)

3. Vos dépôts connectés apparaîtront désormais à la fois sur la page d’accueil et la page des dépôts.  
   ![Dépôts connectés](../../../../translated_images/fr/repo-connected.9e5c21ee789fdcaa.webp)

---

## Démarrer la traduction automatique

1. Sélectionnez le dépôt que vous venez de connecter.  
   ![Sélectionner le dépôt](../../../../translated_images/fr/select-repo-to-detail.55e53233531f8518.webp)

2. Sur la page de détail du dépôt, sélectionnez **Modifier** en bas.  
   ![Sélectionner modifier](../../../../translated_images/fr/select-edit.225184c8c46d7001.webp)

3. Configurez vos paramètres de traduction — branche cible (par défaut : `main`), langues cibles, et langue source (par défaut : `en`). Sélectionnez **Enregistrer**.  
   ![Configurer les paramètres de traduction](../../../../translated_images/fr/configuration.ab55d0f8bab5711b.webp)

4. Sélectionnez **Démarrer & Automatiser**.  
   Localizeflow traduira désormais automatiquement votre documentation et ouvrira des pull requests chaque fois que la source changera.  
   ![Démarrer & Automatiser](../../../../translated_images/fr/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Avertissement** :  
Ce document a été traduit à l'aide du service de traduction automatique [Co-op Translator](https://github.com/Azure/co-op-translator). Bien que nous nous efforcions d'assurer l'exactitude, veuillez noter que les traductions automatiques peuvent contenir des erreurs ou des inexactitudes. Le document original dans sa langue d'origine doit être considéré comme la source faisant foi. Pour les informations critiques, il est recommandé de recourir à une traduction professionnelle réalisée par un traducteur humain. Nous déclinons toute responsabilité en cas de malentendus ou de mauvaises interprétations résultant de l'utilisation de cette traduction.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->