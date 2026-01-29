# Localizeflow – Hızlı Başlangıç Kılavuzu

#### Destekleyen [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](./README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Yerel olarak klonlamayı mı tercih ediyorsunuz?**

> Bu depo, indirilen boyutu önemli ölçüde artıran 50'den fazla dil çevirisi içerir. Çeviri olmadan klonlamak için, seyrek checkout kullanın:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Bu, kursu tamamlamak için ihtiyacınız olan her şeyi çok daha hızlı bir indirme ile sağlar.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow belgelerinizi otomatik olarak çevirir ve kaynak dosya her değiştiğinde pull request açar.  
Bu kılavuz, GitHub Uygulamasını nasıl kuracağınızı ve ilk çevirinizi 2 dakika içinde nasıl çalıştıracağınızı gösterir.


> [!NOTE]
>
> Localizeflow şu anda GitHub tabanlı dokümantasyon projelerini desteklemektedir  
> (örneğin: AI for Beginners ve çoğu standart açık kaynak repo).  
> 
> Astro, Docusaurus ve Hugo gibi modern dokümantasyon framework'leri için destek  
> aktif olarak geliştirilmektedir.


---

## GitHub Uygulamasına giriş yapın ve yükleyin

1. **[localizeflow.com](https://localizeflow.com/)** adresini ziyaret edin.
2. **Ücretsiz deneme ile başlayın** seçeneğini seçin.
   ![Ücretsiz deneme ile başlayın seçin](../../../../translated images/tr/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. **GitHub ile giriş yapın** seçeneğini seçin.  
   ![GitHub ile giriş yap](../../../../translated images/tr/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. GitHub hesabınızla giriş yapın.  
   ![GitHub giriş](../../../../translated images/tr/github-login.02bbaee0270b292e.webp)
5. Localizeflow GitHub Uygulamasını yüklemek istediğiniz hesabı seçin — kişisel hesabınız veya yönettiğiniz bir organizasyon.  
   ![Hesabı seçin](../../../../translated images/tr/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflow’nin erişmesini istediğiniz depoları seçin, ardından **Kaydet**’i seçin.  
   ![Depoyu seç ve kaydet](../../../../translated images/tr/select-repo-and-save.5a95ae288aefec6e.webp)
7. Localizeflow ana sayfasına yönlendirileceksiniz.

> [!TIP]
> Daha sonra daha fazla depo eklemek için, üstbilgide hesabınızı seçin ve **+ Daha fazla depo ekle** seçeneğini seçin.  
> ![Daha fazla depo ekle](../../../../translated images/tr/add-more-repo.2ca5154473aaaafb.webp)

---

## Depolarınızı Localizeflow’e bağlayın

1. Localizeflow ana sayfasında, **+ Depoları bağla** seçeneğini seçin.  
   ![Depoları bağla seç](../../../../translated images/tr/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Bağlamak istediğiniz yüklü depolardan birini seçin ve **Kaydet**’i seçin.  
   ![Depoyu seç](../../../../translated images/tr/select-repo.dce94db722b44cf3.webp)

3. Bağlanmış depolarınız artık hem Ana Sayfa hem de Depolar sayfasında görünecektir.  
   ![Bağlı depolar](../../../../translated images/tr/repo-connected.9e5c21ee789fdcaa.webp)

---

## Otomatik çeviriye başlayın

1. Az önce bağladığınız depoyu seçin.  
   ![Depoyu seç](../../../../translated images/tr/select-repo-to-detail.55e53233531f8518.webp)

2. Depo detay sayfasında, altta **Düzenle** seçeneğini seçin.  
   ![Düzenle seç](../../../../translated images/tr/select-edit.225184c8c46d7001.webp)

3. Çeviri ayarlarınızı yapılandırın — hedef dal (varsayılan: `main`), hedef diller ve kaynak dil (varsayılan: `en`). **Kaydet**’i seçin.  
   ![Çeviri ayarlarını yapılandır](../../../../translated images/tr/configuration.ab55d0f8bab5711b.webp)

4. **Başlat ve Otomatikleştir** seçeneğini seçin.  
   Localizeflow artık belgelerinizi otomatik olarak çevirecek ve kaynak değiştiğinde pull request açacaktır.  
   ![Başlat ve Otomatikleştir](../../../../translated images/tr/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Feragatname**:  
Bu belge, yapay zeka çeviri hizmeti [Co-op Translator](https://github.com/Azure/co-op-translator) kullanılarak çevrilmiştir. Doğruluk için çaba gösterilse de, otomatik çevirilerin hatalar veya yanlışlıklar içerebileceğini lütfen göz önünde bulundurun. Orijinal belge, özellikle kritik bilgiler için yetkili kaynak olarak kabul edilmelidir. Önemli bilgiler için profesyonel insan çevirisi önerilir. Bu çevirinin kullanımı sonucunda meydana gelebilecek yanlış anlamalar veya yanlış yorumlamalardan dolayı sorumluluk kabul edilmez.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->