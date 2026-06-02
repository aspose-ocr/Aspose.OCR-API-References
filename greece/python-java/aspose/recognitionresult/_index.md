---
title: "RecognitionResult"
second_title: "Αναφορά API του Aspose.OCR για Python μέσω Java"
description: 
type: docs
weight: 171
url: /el/python-java/aspose/recognitionresult/
---

Μονάδα recognitionresult
========================

Κλάσεις
-------

`LinesResult(javaClass)`
:

### Προγόνους (in MRO)

    * aspose.helper.BaseJavaClass

### Μέθοδοι

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
Τα αποτελέσματα της αναγνώρισης εικόνας. Περιέχει στοιχεία με αναγνώριση
πληροφορίες και μεθόδους για εξαγωγή αποτελεσμάτων.

### Στατικές μέθοδοι

`save_multipage_document(self, fullPath: str)`
:
Ιδιωτικό

### Μεταβλητές στιγμιοτύπου

`recognition_areas_text`
:   Λίστα αποτελεσμάτων αναγνώρισης μιας λίστας περιοχών (Ορθογώνια).

`recognition_lines_result`
:   Επιστρέφει μια λίστα αποτελεσμάτων αναγνώρισης με μια λίστα γραμμών (Ορθογώνια).

### Μέθοδοι

`getJavaClass(self)`
:

`get_json(self)`
:
Δημιουργεί συμβολοσειρά JSON με τα αποτελέσματα αναγνώρισης.
@return: Αποτελέσματα αναγνώρισης ως συμβολοσειρά JSON.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις).
@param language: Λεξικό για χρήση.
@return: Συμβολοσειρά διορθωμένων αποτελεσμάτων αναγνώρισης.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Βρείτε τις λανθασμένες λέξεις με προτεινόμενες ορθογραφίες για ένα δεδομένο κείμενο εισόδου.
@param language: Λεξικό για χρήση.
@return: Λίστα αντικειμένων SpellCheckError που αντιπροσωπεύουν λανθασμένες λέξεις με λίστες προτεινόμενων σωστών ορθογραφιών για κάθε λανθασμένη λέξη,
και με την απόσταση επεξεργασίας.

`get_xml(self)`
:
Δημιουργεί συμβολοσειρά JSON με τα αποτελέσματα αναγνώρισης.
@return: Αποτελέσματα αναγνώρισης ως XML συμβολοσειρά.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Αποθηκεύει το έγγραφο σε απλό κείμενο ή σε άλλη μορφή εγγράφου.
@param fullFileName: Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης.
@param format: Τύπος enum μορφής εγγράφου Format.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις).
Αποθηκεύει το διορθωμένο κείμενο στο έγγραφο σε απλό κείμενο ή σε άλλη μορφή.
@param fullFileName: Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης
@param format: Τύπος enum μορφής εγγράφου Format.
@param language: Λεξικό για ορθογραφικό έλεγχο.

`use_user_dictionary(self, dictionaryPath: str)`
:
Επιτρέπει τη χρήση δικού σας λεξικού για διόρθωση ορθογραφικού ελέγχου.
@param dictionaryPath: Πλήρης διαδρομή προς το λεξικό χρήστη (λεξικό συχνότητας).
Μορφή αρχείου λεξικού:
Αρχείο απλού κειμένου σε κωδικοποίηση UTF-8.
Η λέξη και η συχνότητα λέξης χωρίζονται με κόμμα, η λέξη αναμένεται στην πρώτη στήλη και η συχνότητα στη δεύτερη στήλη.
Κάθε ζεύγος λέξη‑συχνότητα σε ξεχωριστή γραμμή. Μια γραμμή ορίζεται ως μια ακολουθία χαρακτήρων που ακολουθείται από αλλαγή γραμμής (\"
\", επιστροφή καρτέλας (\"
"),
ή μια επιστροφή καροτσιού αμέσως ακολουθούμενη από αλλαγή γραμμής("

").
Κάθε λέξη αναμένεται να είναι σε πεζά γράμματα.
Παράδειγμα:
\code
λέξη,5984819
γεια,5761742
κάτω,5582768
\endcode

`RectangleOutput(javaClass)`
:
Δεδομένα σχετικά με τις ανιχνευμένες περιοχές κειμένου ή γραμμές.
\code
source - Η πλήρης διαδρομή προς το αρχείο ή το URL, εάν υπάρχει. Κενό για ροές, πίνακες byte, base64.
page - Αριθμός σελίδας.
image_index - Αριθμός ακολουθίας της εικόνας στη σελίδα.
rectangles - Λίστα των εντοπισμένων περιοχών κειμένου ή γραμμών.
\endcode

### Προγόνους (in MRO)

    * aspose.helper.BaseJavaClass

### Μέθοδοι

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Δεδομένα σχετικά με τη γωνία κλίσης σε μοίρες και το όνομα του αρχείου.
\code
source - Η πλήρης διαδρομή προς το αρχείο ή το URL, εάν υπάρχει. Κενό για ροές, πίνακες byte, base64.
page - Αριθμός σελίδας.
image_index - Αριθμός ακολουθίας της εικόνας στη σελίδα.
angle - Γωνία κλίσης σε μοίρες.
\endcode

### Προγόνους (in MRO)

    * aspose.helper.BaseJavaClass

### Μέθοδοι

`initParams(self)`
:


### Δείτε επίσης

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)