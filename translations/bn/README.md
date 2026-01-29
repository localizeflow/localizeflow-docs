# Localizeflow – দ্রুত শুরু করার গাইড

#### দ্বারা সমর্থিত [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](./README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **স্থানীয় ক্লোন করতে পছন্দ করেন?**

> এই রিপোজিটোরিতে ৫০+ ভাষার অনুবাদ রয়েছে যা ডাউনলোড সাইজটি উল্লেখযোগ্যভাবে বৃদ্ধি করে। অনুবাদ ছাড়া ক্লোন করতে sparse checkout ব্যবহার করুন:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> এটা আপনাকে একটি অনেক দ্রুত ডাউনলোডের সাথে কোর্স সম্পন্ন করার জন্য প্রয়োজনীয় সবকিছু দেয়।
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow স্বয়ংক্রিয়ভাবে আপনার ডকুমেন্টেশন অনুবাদ করে এবং উৎস ফাইল পরিবর্তিত হলে পুল রিকোয়েস্ট খুলে।  
এই গাইডটি দেখায় আপনি কিভাবে GitHub অ্যাপ ইন্সটল করবেন এবং ২ মিনিটের কম সময়ে প্রথম অনুবাদ চালাবেন।


> [!NOTE]
>
> Localizeflow বর্তমানে GitHub-ভিত্তিক ডকুমেন্টেশন প্রকল্পগুলি সমর্থন করে  
> (উদাহরণস্বরূপ: AI for Beginners এবং বেশিরভাগ স্ট্যান্ডার্ড ওপেন সোর্স রিপোজ)।  
> 
> Astro, Docusaurus, এবং Hugo এর মতো আধুনিক ডকুমেন্টেশন ফ্রেমওয়ার্কের জন্য সমর্থন  
> সক্রিয় উন্নয়নের ধাপে রয়েছে।


---

## সাইন ইন করুন এবং GitHub অ্যাপ ইন্সটল করুন

1. যান **[localizeflow.com](https://localizeflow.com/)** এ।
2. নির্বাচন করুন **Start with free trial**।
   ![Select Start with free trial](../../../../translated images/bn/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. নির্বাচন করুন **Sign in with GitHub**।  
   ![Sign in with GitHub](../../../../translated images/bn/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. আপনার GitHub অ্যাকাউন্ট দিয়ে সাইন ইন করুন।  
   ![GitHub login](../../../../translated images/bn/github-login.02bbaee0270b292e.webp)
5. নির্বাচন করুন যে অ্যাকাউন্টে আপনি Localizeflow GitHub অ্যাপ ইন্সটল করতে চান — আপনার ব্যক্তিগত অ্যাকাউন্ট অথবা আপনার ম্যানেজ করা কোনো সংগঠন।  
   ![Select account](../../../../translated images/bn/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. নির্বাচন করুন Localizeflow যে রিপোজিটোরিগুলো অ্যাক্সেস করবে, তারপর **Save** চাপুন।  
   ![Select repo and save](../../../../translated images/bn/select-repo-and-save.5a95ae288aefec6e.webp)
7. আপনি Localizeflow মূল পৃষ্ঠায় পুনঃনির্দেশিত হবেন।

> [!TIP]
> পরবর্তীতে আরও রিপোজিটরি যোগ করতে, হেডারে আপনার অ্যাকাউন্ট নির্বাচন করুন এবং **+ Add more repositories** বেছে নিন।  
> ![Add more repositories](../../../../translated images/bn/add-more-repo.2ca5154473aaaafb.webp)

---

## আপনার রিপোজিটরি গুলো Localizeflow এর সাথে সংযুক্ত করুন

1. Localizeflow মূল পৃষ্ঠায়, নির্বাচন করুন **+ Connect repositories**।  
   ![Select connect repositories](../../../../translated images/bn/select-connect-repos.8ac6f96f77dcc62c.webp)

2. ইন্সটল করা রিপোজিটরিগুলো থেকে যেটি সংযুক্ত করতে চান সেটি নির্বাচন করুন এবং **Save** চাপুন।  
   ![Select repository](../../../../translated images/bn/select-repo.dce94db722b44cf3.webp)

3. আপনার সংযুক্ত রিপোজিটরি এখন হোম পৃষ্ঠা এবং রিপোজিটরি পৃষ্ঠায় প্রদর্শিত হবে।  
   ![Connected repositories](../../../../translated images/bn/repo-connected.9e5c21ee789fdcaa.webp)

---

## স্বয়ংক্রিয় অনুবাদ শুরু করুন

1. আপনি যে রিপোজিটরি সংযুক্ত করেছেন সেটি নির্বাচন করুন।  
   ![Select repository](../../../../translated images/bn/select-repo-to-detail.55e53233531f8518.webp)

2. রিপোজিটরি বিস্তারিত পৃষ্ঠায়, নিচে **Edit** নির্বাচন করুন।  
   ![Select edit](../../../../translated images/bn/select-edit.225184c8c46d7001.webp)

3. আপনার অনুবাদ সেটিংস কনফিগার করুন — টার্গেট ব্রাঞ্চ (ডিফল্ট: `main`), টার্গেট ভাষা এবং উৎস ভাষা (ডিফল্ট: `en`)। নির্বাচন করুন **Save**।  
   ![Configure translation settings](../../../../translated images/bn/configuration.ab55d0f8bab5711b.webp)

4. নির্বাচন করুন **Start & Automate**।  
   Localizeflow এখন স্বয়ংক্রিয়ভাবে আপনার ডকুমেন্টেশন অনুবাদ করবে এবং উৎস পরিবর্তিত হলে পুল রিকোয়েস্ট খুলবে।  
   ![Start & Automate](../../../../translated images/bn/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**দ্বিতীয় সতর্কতা**:
এই ডকুমেন্টটি AI অনুবাদ সেবা [Co-op Translator](https://github.com/Azure/co-op-translator) ব্যবহার করে অনূদিত হয়েছে। আমরা সঠিকতার জন্য চেষ্টা করি, তবুও স্বয়ংক্রিয় অনুবাদে ভুল বা অসঙ্গতির সম্ভাবনা থাকতে পারে। মূল নথি এর নিজস্ব ভাষায় কর্তৃত্বপূর্ণ উৎস হিসেবে বিবেচিত হওয়া উচিত। গুরুত্বপূর্ণ তথ্যের জন্য পেশাদার মানুষের অনুবাদ সুপারিশ করা হয়। এই অনুবাদের ব্যবহার থেকে উদ্ভূত কোনও ভুল বা ভুল বোঝাবুঝির জন্য আমরা দায়ী নই।
<!-- CO-OP TRANSLATOR DISCLAIMER END -->