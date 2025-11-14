<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "4672617ab23a0cf61691b673509ab29e",
  "translation_date": "2025-11-14T07:53:16+00:00",
  "source_file": "README.md",
  "language_code": "bn"
}
-->
# Localizeflow – দ্রুত শুরু করার গাইড

#### [Localizeflow](https://localizeflow.com/) দ্বারা সমর্থিত

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](./README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow স্বয়ংক্রিয়ভাবে আপনার ডকুমেন্টেশন অনুবাদ করে এবং সোর্স ফাইল পরিবর্তিত হলে পুল রিকোয়েস্ট খুলে দেয়।  
এই গাইডটি দেখায় কিভাবে GitHub অ্যাপ ইনস্টল করবেন এবং ২ মিনিটের মধ্যে প্রথম অনুবাদ চালাবেন।

---

## সাইন ইন করুন এবং GitHub অ্যাপ ইনস্টল করুন

1. **[localizeflow.com](https://localizeflow.com/)** এ যান।
2. **Start with free trial** নির্বাচন করুন।  
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. **Sign in with GitHub** নির্বাচন করুন।  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. আপনার GitHub অ্যাকাউন্ট দিয়ে সাইন ইন করুন।  
   ![GitHub login](/images/github-login.png)
5. Localizeflow GitHub অ্যাপটি কোথায় ইনস্টল করবেন তা নির্বাচন করুন — আপনার ব্যক্তিগত অ্যাকাউন্ট অথবা আপনি যে কোনো প্রতিষ্ঠান পরিচালনা করেন।  
   ![Select account](/images/select-which-account-to-use.png)
6. Localizeflow কে অ্যাক্সেস দিতে চান এমন রিপোজিটোরিগুলো নির্বাচন করুন, তারপর **Save** ক্লিক করুন।  
   ![Select repo and save](/images/select-repo-and-save.png)
7. আপনি Localizeflow হোম পেজে পুনঃনির্দেশিত হবেন।

> [!TIP]
> পরবর্তীতে আরও রিপোজিটোরি যোগ করতে, হেডারে আপনার অ্যাকাউন্ট নির্বাচন করুন এবং **+ Add more repositories** নির্বাচন করুন।  
> ![Add more repositories](/images/add-more-repo.png)

---

## আপনার রিপোজিটোরিগুলো Localizeflow এর সাথে সংযুক্ত করুন

1. Localizeflow হোম পেজে **+ Connect repositories** নির্বাচন করুন।  
   ![Select connect repositories](/images/select-connect-repos.png)

2. ইনস্টল করা রিপোজিটোরিগুলোর মধ্যে থেকে একটি নির্বাচন করুন এবং **Save** ক্লিক করুন।  
   ![Select repository](/images/select-repo.png)

3. আপনার সংযুক্ত রিপোজিটোরিগুলো এখন হোম পেজ এবং রিপোজিটোরি পেজ উভয়েই দেখা যাবে।  
   ![Connected repositories](/images/repo-connected.png)

---

## স্বয়ংক্রিয় অনুবাদ শুরু করুন

1. আপনি যেই রিপোজিটোরি সংযুক্ত করেছেন তা নির্বাচন করুন।  
   ![Select repository](/images/select-repo-to-detail.png)

2. রিপোজিটোরি বিস্তারিত পেজে নিচে **Edit** নির্বাচন করুন।  
   ![Select edit](/images/select-edit.png)

3. আপনার অনুবাদ সেটিংস কনফিগার করুন — লক্ষ্য ব্রাঞ্চ (ডিফল্ট: `main`), লক্ষ্য ভাষাসমূহ, এবং সোর্স ভাষা (ডিফল্ট: `en`)। তারপর **Save** ক্লিক করুন।  
   ![Configure translation settings](/images/configuration.png)

4. **Start & Automate** নির্বাচন করুন।  
   Localizeflow এখন স্বয়ংক্রিয়ভাবে আপনার ডকুমেন্টেশন অনুবাদ করবে এবং সোর্স পরিবর্তিত হলে পুল রিকোয়েস্ট খুলবে।  
   ![Start & Automate](/images/select-automate.png)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**অস্বীকৃতি**:  
এই নথিটি AI অনুবাদ সেবা [Co-op Translator](https://github.com/Azure/co-op-translator) ব্যবহার করে অনূদিত হয়েছে। আমরা যথাসাধ্য সঠিকতার চেষ্টা করি, তবে স্বয়ংক্রিয় অনুবাদে ত্রুটি বা অসঙ্গতি থাকতে পারে। মূল নথিটি তার নিজস্ব ভাষায়ই কর্তৃত্বপূর্ণ উৎস হিসেবে বিবেচিত হওয়া উচিত। গুরুত্বপূর্ণ তথ্যের জন্য পেশাদার মানব অনুবাদ গ্রহণ করার পরামর্শ দেওয়া হয়। এই অনুবাদের ব্যবহারে সৃষ্ট কোনো ভুল বোঝাবুঝি বা ভুল ব্যাখ্যার জন্য আমরা দায়ী নই।
<!-- CO-OP TRANSLATOR DISCLAIMER END -->