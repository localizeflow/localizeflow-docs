# Localizeflow – দ্রুত শুরুর গাইড

#### দ্বারা সমর্থিত [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](./README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **স্থানীয়ভাবে ক্লোন করতে চান?**

> এই রিপোজিটরিতে ৫০+ ভাষার অনুবাদ অন্তর্ভুক্ত রয়েছে যা ডাউনলোডের আকার উল্লেখযোগ্যভাবে বৃদ্ধি করে। অনুবাদ ছাড়া ক্লোন করতে sparse checkout ব্যবহার করুন:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> এটি আপনাকে কোর্স সম্পন্ন করার জন্য প্রয়োজনীয় সবকিছু দেয়, যা অনেক দ্রুত ডাউনলোড হয়।
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow স্বয়ংক্রিয়ভাবে আপনার ডকুমেন্টেশন অনূদিত করে এবং সোর্স ফাইল পরিবর্তিত হলে pull request খুলে দেয়।  
এই গাইডটি আপনাকে দেখাবে কিভাবে GitHub App ইনস্টল করে ২ মিনিটের মধ্যে আপনার প্রথম অনুবাদ চালাতে হয়।


> [!NOTE]
>
> Localizeflow বর্তমানে GitHub-ভিত্তিক ডকুমেন্টেশন প্রকল্প সমর্থন করে  
> (উদাহরণস্বরূপ: AI for Beginners এবং বেশিরভাগ স্ট্যান্ডার্ড ওপেন-সোর্স রিপোজ)।  
> 
> আধুনিক ডকুমেন্টেশন ফ্রেমওয়ার্ক যেমন Astro, Docusaurus, এবং Hugo  
> এর জন্য সমর্থন সক্রিয় উন্নয়নের অধীনে রয়েছে।


---

## সাইন ইন করুন এবং GitHub App ইনস্টল করুন

1. যান **[localizeflow.com](https://localizeflow.com/)** এ।
2. নির্বাচন করুন **Start with free trial**।  
   ![Select Start with free trial](../../../../translated_images/bn/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. নির্বাচন করুন **Sign in with GitHub**।  
   ![Sign in with GitHub](../../../../translated_images/bn/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. আপনার GitHub অ্যাকাউন্ট দিয়ে সাইন ইন করুন।  
   ![GitHub login](../../../../translated_images/bn/github-login.02bbaee0270b292e.webp)
5. যে অ্যাকাউন্টে আপনি Localizeflow GitHub App ইনস্টল করতে চান সেই অ্যাকাউন্ট নির্বাচন করুন — আপনার ব্যক্তিগত অ্যাকাউন্ট বা আপনার পরিচালিত কোনো প্রতিষ্ঠান।  
   ![Select account](../../../../translated_images/bn/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Localizeflow-কে অ্যাক্সেস দিতে চান এমন রিপোজিটরিগুলো নির্বাচন করুন, তারপর **Save** নির্বাচন করুন।  
   ![Select repo and save](../../../../translated_images/bn/select-repo-and-save.5a95ae288aefec6e.webp)
7. আপনি Localizeflow হোম পেজে পুনঃনির্দেশিত হবেন।

> [!TIP]
> পরবর্তীতে আরও রিপোজিটরি যোগ করতে, হেডারে আপনার অ্যাকাউন্ট নির্বাচন করুন এবং **+ Add more repositories** নির্বাচন করুন।  
> ![Add more repositories](../../../../translated_images/bn/add-more-repo.2ca5154473aaaafb.webp)

---

## আপনার রিপোজিটরিগুলো Localizeflow-তে সংযুক্ত করুন

1. Localizeflow হোম পেজে যান এবং নির্বাচন করুন **+ Connect repositories**।  
   ![Select connect repositories](../../../../translated_images/bn/select-connect-repos.8ac6f96f77dcc62c.webp)

2. ইনস্টল করা রিপোজিটরিগুলোর মধ্যে আপনি যে রিপোজিটরি সংযুক্ত করতে চান তা নির্বাচন করুন এবং **Save** নির্বাচন করুন।  
   ![Select repository](../../../../translated_images/bn/select-repo.dce94db722b44cf3.webp)

3. এখন আপনার সংযুক্ত রিপোজিটরিগুলো হোম পেজ এবং রিপোজিটরি পেজ উভয় জায়গায় প্রদর্শিত হবে।  
   ![Connected repositories](../../../../translated_images/bn/repo-connected.9e5c21ee789fdcaa.webp)

---

## স্বয়ংক্রিয় অনুবাদ শুরু করুন

1. যে রিপোজিটরিটি আপনি সংযুক্ত করেছেন তা নির্বাচন করুন।  
   ![Select repository](../../../../translated_images/bn/select-repo-to-detail.55e53233531f8518.webp)

2. রিপোজিটরি ডিটেইল পেজে নিচে **Edit** নির্বাচন করুন।  
   ![Select edit](../../../../translated_images/bn/select-edit.225184c8c46d7001.webp)

3. আপনার অনুবাদের সেটিংস কনফিগার করুন — লক্ষ্য ব্রাঞ্চ (ডিফল্ট: `main`), লক্ষ্য ভাষাসমূহ, এবং সোর্স ভাষা (ডিফল্ট: `en`)। তারপর **Save** নির্বাচন করুন।  
   ![Configure translation settings](../../../../translated_images/bn/configuration.ab55d0f8bab5711b.webp)

4. নির্বাচন করুন **Start & Automate**।  
   Localizeflow এখন স্বয়ংক্রিয়ভাবে আপনার ডকুমেন্টেশন অনুবাদ শুরু করবে এবং সোর্স পরিবর্তিত হলে pull request খুলবে।  
   ![Start & Automate](../../../../translated_images/bn/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**বিদ্রূপ**:
এই নথিটি AI অনুবাদ সেবা [Co-op Translator](https://github.com/Azure/co-op-translator) ব্যবহার করে অনূদিত হয়েছে। আমরা যথাসাধ্য সঠিকতার চেষ্টা করি, তবে অনুগ্রহ করে মনে রাখবেন যে স্বয়ংক্রিয় অনুবাদে ত্রুটি বা ভুল থাকতে পারে। মূল ভাষায় থাকা নথিটিকেই কর্তৃপক্ষের উৎস হিসেবে বিবেচনা করা উচিত। গুরুত্বপূর্ণ তথ্যের জন্য পেশাদার মানব অনুবাদ সুপারিশ করা হয়। এই অনুবাদের ব্যবহারে কোনো ভুল বোঝাবুঝি বা ভুল ব্যাখ্যার জন্য আমরা দায়বদ্ধ নই।
<!-- CO-OP TRANSLATOR DISCLAIMER END -->