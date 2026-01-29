# Localizeflow – Panduan Memulai Cepat

#### Didukung oleh [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](./README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Lebih Suka Meng-clone Secara Lokal?**

> Repositori ini mencakup lebih dari 50+ terjemahan bahasa yang secara signifikan meningkatkan ukuran unduhan. Untuk meng-clone tanpa terjemahan, gunakan sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Ini memberikan Anda semua yang Anda butuhkan untuk menyelesaikan kursus dengan unduhan yang jauh lebih cepat.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow secara otomatis menerjemahkan dokumentasi Anda dan membuka permintaan tarik setiap kali file sumber berubah.  
Panduan ini menunjukkan cara menginstal GitHub App dan menjalankan terjemahan pertama Anda dalam waktu kurang dari 2 menit.


> [!NOTE]
>
> Saat ini Localizeflow mendukung proyek dokumentasi berbasis GitHub  
> (misalnya: AI untuk Pemula dan kebanyakan repositori open-source standar).  
>  
> Dukungan untuk kerangka dokumentasi modern seperti Astro, Docusaurus, dan Hugo  
> sedang dalam pengembangan aktif.


---

## Masuk dan pasang GitHub App

1. Kunjungi **[localizeflow.com](https://localizeflow.com/)**.
2. Pilih **Mulai dengan uji coba gratis**.
   ![Select Start with free trial](../../../../translated images/id/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Pilih **Masuk dengan GitHub**.  
   ![Sign in with GitHub](../../../../translated images/id/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Masuk dengan akun GitHub Anda.  
   ![GitHub login](../../../../translated images/id/github-login.02bbaee0270b292e.webp)
5. Pilih akun tempat Anda ingin memasang Localizeflow GitHub App — akun pribadi Anda atau organisasi yang Anda kelola.  
   ![Select account](../../../../translated images/id/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Pilih repositori yang ingin Anda izinkan Localizeflow akses, lalu pilih **Simpan**.  
   ![Select repo and save](../../../../translated images/id/select-repo-and-save.5a95ae288aefec6e.webp)
7. Anda akan diarahkan ke halaman utama Localizeflow.

> [!TIP]
> Untuk menambahkan lebih banyak repositori nanti, pilih akun Anda di header dan pilih **+ Tambah lebih banyak repositori**.  
> ![Add more repositories](../../../../translated images/id/add-more-repo.2ca5154473aaaafb.webp)

---

## Hubungkan repositori Anda ke Localizeflow

1. Di halaman utama Localizeflow, pilih **+ Hubungkan repositori**.  
   ![Select connect repositories](../../../../translated images/id/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Pilih salah satu repositori yang sudah terpasang yang ingin Anda hubungkan dan pilih **Simpan**.  
   ![Select repository](../../../../translated images/id/select-repo.dce94db722b44cf3.webp)

3. Repositori yang terhubung sekarang akan muncul di halaman Beranda dan halaman Repositori.  
   ![Connected repositories](../../../../translated images/id/repo-connected.9e5c21ee789fdcaa.webp)

---

## Mulai terjemahan otomatis

1. Pilih repositori yang baru saja Anda hubungkan.  
   ![Select repository](../../../../translated images/id/select-repo-to-detail.55e53233531f8518.webp)

2. Di halaman detail repositori, pilih **Edit** di bagian bawah.  
   ![Select edit](../../../../translated images/id/select-edit.225184c8c46d7001.webp)

3. Konfigurasikan pengaturan terjemahan Anda — cabang target (default: `main`), bahasa target, dan bahasa sumber (default: `en`). Pilih **Simpan**.  
   ![Configure translation settings](../../../../translated images/id/configuration.ab55d0f8bab5711b.webp)

4. Pilih **Mulai & Otomatiskan**.  
   Localizeflow sekarang akan secara otomatis menerjemahkan dokumentasi Anda dan membuka permintaan tarik setiap kali sumber berubah.  
   ![Start & Automate](../../../../translated images/id/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Penafian**:  
Dokumen ini telah diterjemahkan menggunakan layanan terjemahan AI [Co-op Translator](https://github.com/Azure/co-op-translator). Meskipun kami berupaya untuk akurat, harap diingat bahwa terjemahan otomatis dapat mengandung kesalahan atau ketidakakuratan. Dokumen asli dalam bahasa sumber harus dianggap sebagai sumber otoritatif. Untuk informasi penting, disarankan menggunakan terjemahan profesional oleh manusia. Kami tidak bertanggung jawab atas kesalahpahaman atau salah tafsir yang timbul dari penggunaan terjemahan ini.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->