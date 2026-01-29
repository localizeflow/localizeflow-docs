# Localizeflow – Водич за брзи почетак

#### Подржано од стране [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](./README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Волите да клонирате локално?**

> Овај репозиторијум укључује више од 50 превода на језике, што значајно повећава величину преузимања. За клонирање без превода користите sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Ово вам даје све што вам је потребно да завршите курс са знатно бржим преузимањем.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow аутоматски преводи вашу документацију и отвара pull захтеве кад год се датотека извора промени.  
Овај водич вам показује како да инсталирате GitHub апликацију и покренете први превод за мање од 2 минута.


> [!NOTE]
>
> Localizeflow тренутно подржава документационе пројекте базиране на GitHub-у  
> (на пример: AI for Beginners и већина стандардних open-source репозиторијума).  
> 
> Подршка за савремене документационе оквире као што су Astro, Docusaurus и Hugo  
> је у активној развоју.


---

## Пријавите се и инсталирајте GitHub апликацију

1. Посетите **[localizeflow.com](https://localizeflow.com/)**.
2. Изаберите **Start with free trial**.
   ![Select Start with free trial](../../translated_images/sr/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Изаберите **Sign in with GitHub**.  
   ![Sign in with GitHub](../../translated_images/sr/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Пријавите се са вашим GitHub налогом.  
   ![GitHub login](../../translated_images/sr/github-login.02bbaee0270b292e.webp)
5. Изаберите налог на који желите да инсталирате Localizeflow GitHub апликацију — ваш лични налог или организацију којом управљате.  
   ![Select account](../../translated_images/sr/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Изаберите репозиторијуме којима желите да Localizeflow приступи, затим одаберите **Save**.  
   ![Select repo and save](../../translated_images/sr/select-repo-and-save.5a95ae288aefec6e.webp)
7. Бићете преусмерени на почетну страницу Localizeflow-а.

> [!TIP]
> Да бисте касније додали више репозиторијума, изаберите ваш налог у заглављу и кликните на **+ Add more repositories**.  
> ![Add more repositories](../../translated_images/sr/add-more-repo.2ca5154473aaaafb.webp)

---

## Повежите ваше репозиторијуме са Localizeflow-ом

1. На почетној страници Localizeflow-а, изаберите **+ Connect repositories**.  
   ![Select connect repositories](../../translated_images/sr/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Изаберите један од инсталираних репозиторијума који желите да повежете и изаберите **Save**.  
   ![Select repository](../../translated_images/sr/select-repo.dce94db722b44cf3.webp)

3. Ваши повезани репозиторијуми ће се сада појавити и на почетној страници и на страници са репозиторијумима.  
   ![Connected repositories](../../translated_images/sr/repo-connected.9e5c21ee789fdcaa.webp)

---

## Покрените аутоматски превод

1. Изаберите репозиторијум који сте управо повезали.  
   ![Select repository](../../translated_images/sr/select-repo-to-detail.55e53233531f8518.webp)

2. На страници са детаљима репозиторијума, изаберите **Edit** на дну странице.  
   ![Select edit](../../translated_images/sr/select-edit.225184c8c46d7001.webp)

3. Конфигуришите поставке превода — циљну грану (подразумевано: `main`), циљне језике и изворни језик (подразумевано: `en`). Изаберите **Save**.  
   ![Configure translation settings](../../translated_images/sr/configuration.ab55d0f8bab5711b.webp)

4. Изаберите **Start & Automate**.  
   Localizeflow ће сада аутоматски преводити вашу документацију и отварати pull захтеве кад год се извор промени.  
   ![Start & Automate](../../translated_images/sr/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Изјава о одговорности**:  
Овај документ је преведен коришћењем AI преводилачке услуге [Co-op Translator](https://github.com/Azure/co-op-translator). Иако се трудимо да превод буде тачан, имајте у виду да аутоматски преводи могу садржати грешке или нетачности. Изворни документ на свом оригиналном језику треба сматрати ауторитетним извором. За критичне информације препоручује се стручни људски превод. Нисмо одговорни за било каква неспоразума или погрешног тумачења која могу произићи из коришћења овог превода.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->