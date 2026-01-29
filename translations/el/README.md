# Localizeflow – Οδηγός Γρήγορης Εκκίνησης

#### Υποστηρίζεται από [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](./README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **Προτιμάτε να κάνετε κλώνο τοπικά;**

> Αυτό το αποθετήριο περιλαμβάνει 50+ μεταφράσεις γλωσσών που αυξάνουν σημαντικά το μέγεθος λήψης. Για κλώνο χωρίς μεταφράσεις, χρησιμοποιήστε sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Αυτό σας δίνει όλα όσα χρειάζεστε για να ολοκληρώσετε το μάθημα με πολύ πιο γρήγορη λήψη.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Το Localizeflow μεταφράζει αυτόματα την τεκμηρίωσή σας και ανοίγει pull requests κάθε φορά που αλλάζει το αρχείο προέλευσης.  
Αυτός ο οδηγός σας δείχνει πώς να εγκαταστήσετε την εφαρμογή GitHub και να εκτελέσετε την πρώτη σας μετάφραση σε λιγότερο από 2 λεπτά.


> [!NOTE]
>
> Το Localizeflow υποστηρίζει αυτήν τη στιγμή έργα τεκμηρίωσης βασισμένα στο GitHub  
> (για παράδειγμα: AI for Beginners και τα περισσότερα τυπικά αποθετήρια ανοιχτού κώδικα).  
> 
> Η υποστήριξη για σύγχρονα πλαίσια τεκμηρίωσης όπως τα Astro, Docusaurus και Hugo  
> βρίσκεται σε ενεργή ανάπτυξη.


---

## Συνδεθείτε και εγκαταστήστε την εφαρμογή GitHub

1. Επισκεφθείτε το **[localizeflow.com](https://localizeflow.com/)**.
2. Επιλέξτε **Ξεκινήστε με δωρεάν δοκιμή**.
   ![Επιλέξτε Ξεκινήστε με δωρεάν δοκιμή](../../../../translated images/el/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Επιλέξτε **Σύνδεση με GitHub**.  
   ![Σύνδεση με GitHub](../../../../translated images/el/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Συνδεθείτε με τον λογαριασμό GitHub σας.  
   ![Είσοδος GitHub](../../../../translated images/el/github-login.02bbaee0270b292e.webp)
5. Επιλέξτε τον λογαριασμό όπου θέλετε να εγκαταστήσετε την εφαρμογή Localizeflow στο GitHub — τον προσωπικό σας λογαριασμό ή έναν οργανισμό που διαχειρίζεστε.  
   ![Επιλέξτε λογαριασμό](../../../../translated images/el/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Επιλέξτε τα αποθετήρια που θέλετε να έχει πρόσβαση το Localizeflow και μετά επιλέξτε **Αποθήκευση**.  
   ![Επιλέξτε αποθετήριο και αποθήκευση](../../../../translated images/el/select-repo-and-save.5a95ae288aefec6e.webp)
7. Θα ανακατευθυνθείτε στην αρχική σελίδα του Localizeflow.

> [!TIP]
> Για να προσθέσετε περισσότερα αποθετήρια αργότερα, επιλέξτε τον λογαριασμό σας στην κεφαλίδα και πατήστε **+ Προσθέστε περισσότερα αποθετήρια**.  
> ![Προσθήκη περισσότερων αποθετηρίων](../../../../translated images/el/add-more-repo.2ca5154473aaaafb.webp)

---

## Συνδέστε τα αποθετήριά σας με το Localizeflow

1. Στην αρχική σελίδα του Localizeflow, επιλέξτε **+ Συνδέστε αποθετήρια**.  
   ![Επιλέξτε συνδέστε αποθετήρια](../../../../translated images/el/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Επιλέξτε ένα από τα εγκατεστημένα αποθετήρια που θέλετε να συνδέσετε και πατήστε **Αποθήκευση**.  
   ![Επιλέξτε αποθετήριο](../../../../translated images/el/select-repo.dce94db722b44cf3.webp)

3. Τα συνδεδεμένα αποθετήριά σας θα εμφανιστούν τώρα τόσο στην αρχική σελίδα όσο και στη σελίδα των αποθετηρίων.  
   ![Συνδεδεμένα αποθετήρια](../../../../translated images/el/repo-connected.9e5c21ee789fdcaa.webp)

---

## Ξεκινήστε την αυτόματη μετάφραση

1. Επιλέξτε το αποθετήριο που μόλις συνδέσατε.  
   ![Επιλέξτε αποθετήριο](../../../../translated images/el/select-repo-to-detail.55e53233531f8518.webp)

2. Στη σελίδα λεπτομερειών αποθετηρίου, επιλέξτε **Επεξεργασία** στο κάτω μέρος.  
   ![Επιλέξτε επεξεργασία](../../../../translated images/el/select-edit.225184c8c46d7001.webp)

3. Διαμορφώστε τις ρυθμίσεις μετάφρασής σας — στοχευμένο branch (προεπιλογή: `main`), γλώσσες στόχους, και γλώσσα προέλευσης (προεπιλογή: `en`). Επιλέξτε **Αποθήκευση**.  
   ![Διαμόρφωση ρυθμίσεων μετάφρασης](../../../../translated images/el/configuration.ab55d0f8bab5711b.webp)

4. Επιλέξτε **Έναρξη & Αυτοματοποίηση**.  
   Το Localizeflow θα ξεκινήσει αυτόματα τη μετάφραση της τεκμηρίωσής σας και θα ανοίγει pull requests κάθε φορά που η πηγή αλλάζει.  
   ![Έναρξη & Αυτοματοποίηση](../../../../translated images/el/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Αποποίηση Ευθύνης**:  
Αυτό το έγγραφο έχει μεταφραστεί χρησιμοποιώντας την υπηρεσία μετάφρασης AI [Co-op Translator](https://github.com/Azure/co-op-translator). Παρότι προσπαθούμε για ακρίβεια, παρακαλούμε να γνωρίζετε ότι οι αυτόματες μεταφράσεις μπορεί να περιέχουν σφάλματα ή ανακρίβειες. Το αρχικό έγγραφο στη γλώσσα του θεωρείται η επίσημη πηγή. Για κρίσιμες πληροφορίες, συνιστάται επαγγελματική ανθρώπινη μετάφραση. Δεν φέρουμε ευθύνη για τυχόν παρεξηγήσεις ή λανθασμένες ερμηνείες που προκύπτουν από τη χρήση αυτής της μετάφρασης.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->