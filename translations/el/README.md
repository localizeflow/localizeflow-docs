# Localizeflow – Γρήγορος Οδηγός Εκκίνησης

#### Υποστηρίζεται από το [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](./README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Προτιμάτε να κάνετε κλωνοποίηση τοπικά;**

> Αυτό το αποθετήριο περιλαμβάνει πάνω από 50 μεταφράσεις γλωσσών που αυξάνουν σημαντικά το μέγεθος λήψης. Για να κάνετε κλωνοποίηση χωρίς τις μεταφράσεις, χρησιμοποιήστε το sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Αυτό σας δίνει όλα όσα χρειάζεστε για να ολοκληρώσετε το μάθημα με πολύ ταχύτερη λήψη.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Το Localizeflow μεταφράζει αυτόματα την τεκμηρίωσή σας και ανοίγει αιτήματα έλξης (pull requests) όποτε το αρχείο προέλευσης αλλάζει.  
Αυτός ο οδηγός σας δείχνει πώς να εγκαταστήσετε την εφαρμογή GitHub και να εκτελέσετε την πρώτη σας μετάφραση σε λιγότερο από 2 λεπτά.


> [!NOTE]
>
> Το Localizeflow υποστηρίζει αυτή τη στιγμή έργα τεκμηρίωσης που βασίζονται στο GitHub  
> (για παράδειγμα: AI for Beginners και τα περισσότερα τυπικά αποθετήρια ανοιχτού κώδικα).  
> 
> Η υποστήριξη για σύγχρονα πλαίσια τεκμηρίωσης όπως τα Astro, Docusaurus και Hugo  
> βρίσκεται σε ενεργή ανάπτυξη.


---

## Συνδεθείτε και εγκαταστήστε την εφαρμογή GitHub

1. Επισκεφθείτε το **[localizeflow.com](https://localizeflow.com/)**.
2. Επιλέξτε **Ξεκινήστε με δοκιμαστική έκδοση δωρεάν**.  
   ![Select Start with free trial](../../../../translated_images/el/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Επιλέξτε **Σύνδεση με το GitHub**.  
   ![Sign in with GitHub](../../../../translated_images/el/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Συνδεθείτε με τον λογαριασμό σας στο GitHub.  
   ![GitHub login](../../../../translated_images/el/github-login.02bbaee0270b292e.webp)
5. Επιλέξτε τον λογαριασμό όπου θέλετε να εγκαταστήσετε την εφαρμογή Localizeflow GitHub — τον προσωπικό σας λογαριασμό ή έναν οργανισμό που διαχειρίζεστε.  
   ![Select account](../../../../translated_images/el/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Επιλέξτε τα αποθετήρια στα οποία θέλετε να έχει πρόσβαση το Localizeflow και στη συνέχεια επιλέξτε **Αποθήκευση**.  
   ![Select repo and save](../../../../translated_images/el/select-repo-and-save.5a95ae288aefec6e.webp)
7. Θα ανακατευθυνθείτε στην αρχική σελίδα του Localizeflow.

> [!TIP]
> Για να προσθέσετε περισσότερα αποθετήρια αργότερα, επιλέξτε τον λογαριασμό σας στην κεφαλίδα και επιλέξτε **+ Προσθήκη περισσότερων αποθετηρίων**.  
> ![Add more repositories](../../../../translated_images/el/add-more-repo.2ca5154473aaaafb.webp)

---

## Συνδέστε τα αποθετήριά σας με το Localizeflow

1. Στην αρχική σελίδα του Localizeflow, επιλέξτε **+ Σύνδεση αποθετηρίων**.  
   ![Select connect repositories](../../../../translated_images/el/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Επιλέξτε ένα από τα εγκατεστημένα αποθετήρια που θέλετε να συνδέσετε και πατήστε **Αποθήκευση**.  
   ![Select repository](../../../../translated_images/el/select-repo.dce94db722b44cf3.webp)

3. Τα συνδεδεμένα αποθετήριά σας θα εμφανίζονται πλέον τόσο στην Αρχική σελίδα όσο και στη σελίδα των Αποθετηρίων.  
   ![Connected repositories](../../../../translated_images/el/repo-connected.9e5c21ee789fdcaa.webp)

---

## Ξεκινήστε αυτόματη μετάφραση

1. Επιλέξτε το αποθετήριο που μόλις συνδέσατε.  
   ![Select repository](../../../../translated_images/el/select-repo-to-detail.55e53233531f8518.webp)

2. Στη σελίδα λεπτομερειών του αποθετηρίου, επιλέξτε **Επεξεργασία** στο κάτω μέρος.  
   ![Select edit](../../../../translated_images/el/select-edit.225184c8c46d7001.webp)

3. Διαμορφώστε τις ρυθμίσεις μετάφρασής σας — προορισμός branch (default: `main`), γλώσσες προορισμού, και γλώσσα προέλευσης (default: `en`). Επιλέξτε **Αποθήκευση**.  
   ![Configure translation settings](../../../../translated_images/el/configuration.ab55d0f8bab5711b.webp)

4. Επιλέξτε **Έναρξη & Αύτοματισμός**.  
   Το Localizeflow θα αρχίσει πλέον να μεταφράζει αυτόματα την τεκμηρίωσή σας και να ανοίγει αιτήματα έλξης όποτε αλλάζει το αρχείο προέλευσης.  
   ![Start & Automate](../../../../translated_images/el/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Αποποίηση ευθυνών**:  
Αυτό το έγγραφο έχει μεταφραστεί χρησιμοποιώντας την υπηρεσία αυτόματης μετάφρασης [Co-op Translator](https://github.com/Azure/co-op-translator). Παρόλο που καταβάλλουμε προσπάθειες για ακρίβεια, παρακαλούμε να γνωρίζετε ότι οι αυτόματες μεταφράσεις μπορεί να περιέχουν σφάλματα ή ανακρίβειες. Το πρωτότυπο έγγραφο στη γλώσσα του θεωρείται η επίσημη πηγή. Για κρίσιμες πληροφορίες συνιστάται επαγγελματική ανθρώπινη μετάφραση. Δεν φέρουμε ευθύνη για τυχόν παρεξηγήσεις ή λανθασμένες ερμηνείες που προκύπτουν από τη χρήση αυτής της μετάφρασης.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->