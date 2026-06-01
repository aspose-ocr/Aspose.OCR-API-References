---
title: "RecognitionResult"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Τα αποτελέσματα της αναγνώρισης εικόνας"
type: docs
weight: 26
url: /el/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

Τα αποτελέσματα της αναγνώρισης εικόνας. Περιέχει στοιχεία με πληροφορίες αναγνώρισης και μεθόδους για εξαγωγή αποτελεσμάτων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Αρχικοποιεί μια νέα παρουσία του |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [language](#language) | Η γλώσσα του αναγνωρισμένου κειμένου στην εικόνα. |
| [recognitionCharactersList](#recognitionCharactersList) | Ένα σύνολο χαρακτήρων που βρέθηκαν από τον αλγόριθμο αναγνώρισης και ταξινομήθηκαν κατά φθίνουσα σειρά πιθανότητας. |
| [recognitionLinesResult](#recognitionLinesResult) | Λαμβάνει μια λίστα αποτελεσμάτων αναγνώρισης με μια λίστα γραμμών (Ορθογώνια). |
| [recognitionRegionsResult](#recognitionRegionsResult) | Λαμβάνει μια λίστα αποτελεσμάτων αναγνώρισης με μια λίστα περιοχών (Ορθογώνια). |
| [recognitionText](#recognitionText) | Αποτέλεσμα αναγνώρισης όλων των σελίδων ή μιας περιοχής. |
| [warnings](#warnings) | Λαμβάνει ή ορίζει τη λίστα των μηνυμάτων προειδοποίησης που περιγράφουν μη κρίσιμα σφάλματα που εμφανίστηκαν κατά τη δημιουργία. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [GetJson()](#GetJson) | Δημιουργεί συμβολοσειρά JSON με τα αποτελέσματα αναγνώρισης. |
| [GetKeywords()](#GetKeywords) | Λάβετε λέξεις-κλειδιά από το διαβατήριο (Λειτουργία δοκιμής. |
| [GetXml()](#GetXml) | Δημιουργεί συμβολοσειρά JSON με τα αποτελέσματα αναγνώρισης. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Βρείτε τις λανθασμένες λέξεις με προτεινόμενες ορθογραφίες για ένα δεδομένο κείμενο εισόδου. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Βρείτε τις λανθασμένες λέξεις με προτεινόμενες ορθογραφίες για ένα δεδομένο κείμενο εισόδου. |
| [save(String fullFileName)](#save-java.lang.String) | Αποθηκεύει το έγγραφο σε απλό κείμενο |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Αποθηκεύει το έγγραφο σε απλό κείμενο ή σε άλλη μορφή εγγράφου. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Αποθηκεύει το έγγραφο σε απλό κείμενο ή σε άλλη μορφή εγγράφου. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Αποθηκεύει το διορθωμένο κείμενο με το αγγλικό λεξικό στο έγγραφο σε απλό κείμενο ή σε μορφή εγγράφου κειμένου Microsoft Word. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Αποθηκεύει το διορθωμένο κείμενο στο έγγραφο σε απλό κείμενο ή σε άλλη μορφή. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Επιτρέπει τη χρήση του δικού σας λεξικού για διόρθωση ορθογραφίας. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Αρχικοποιεί μια νέα παρουσία του

### language {#language}
```
public Language language
```


Η γλώσσα του αναγνωρισμένου κειμένου στην εικόνα. Αυτή η τιμή καθορίζεται αυτόματα εάν επιλεγεί  Language.AUTO ,  Language.MULTILANGUAGE , ή  Language.UNIVERSAL .

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


Ένα σύνολο χαρακτήρων που βρέθηκαν από τον αλγόριθμο αναγνώρισης και ταξινομήθηκαν κατά φθίνουσα σειρά πιθανότητας.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Λαμβάνει μια λίστα αποτελεσμάτων αναγνώρισης με μια λίστα γραμμών (Ορθογώνια).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Λαμβάνει μια λίστα αποτελεσμάτων αναγνώρισης με μια λίστα περιοχών (Ορθογώνια).

### recognitionText {#recognitionText}
```
public String recognitionText
```


Αποτέλεσμα αναγνώρισης όλων των σελίδων ή μιας περιοχής.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Λαμβάνει ή ορίζει τη λίστα των μηνυμάτων προειδοποίησης που περιγράφουν μη κρίσιμα σφάλματα που εμφανίστηκαν κατά τη δημιουργία.

### GetJson() {#GetJson}
```
public String GetJson()
```


Δημιουργεί συμβολοσειρά JSON με τα αποτελέσματα αναγνώρισης.

**Returns:**
java.lang.String - Αποτελέσματα αναγνώρισης ως συμβολοσειρά JSON.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Λάβετε λέξεις-κλειδιά από διαβατήριο (Λειτουργία δοκιμής. Λειτουργεί μόνο για διαβατήρια ΗΠΑ και ΜΑΔΑΓΑΣΚΑΡ).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - Λεξικό με τη λέξη-κλειδί ως κλειδί και το LinesResult ως τιμή.
### GetXml() {#GetXml}
```
public String GetXml()
```


Δημιουργεί συμβολοσειρά JSON με τα αποτελέσματα αναγνώρισης.

**Returns:**
java.lang.String - Αποτελέσματα αναγνώρισης ως συμβολοσειρά XML.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις).

**Returns:**
java.lang.String - Συμβολοσειρά διορθωμένων αποτελεσμάτων αναγνώρισης. Προεπιλεγμένο αγγλικό λεξικό.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Λεξικό προς χρήση. |

**Returns:**
java.lang.String - Συμβολοσειρά διορθωμένων αποτελεσμάτων αναγνώρισης.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Βρείτε τις λανθασμένες λέξεις με προτεινόμενες ορθογραφίες για ένα δεδομένο κείμενο εισόδου. Προεπιλεγμένο αγγλικό λεξικό.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList αντικειμένων SpellCheckError που αντιπροσωπεύουν λανθασμένες λέξεις με λίστες προτεινόμενων σωστών ορθογραφιών για κάθε λανθασμένη λέξη, καθώς και με την απόσταση επεξεργασίας.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Βρείτε τις λανθασμένες λέξεις με προτεινόμενες ορθογραφίες για ένα δεδομένο κείμενο εισόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Λεξικό προς χρήση. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList αντικειμένων SpellCheckError που αντιπροσωπεύουν λανθασμένες λέξεις με λίστες προτεινόμενων σωστών ορθογραφιών για κάθε λανθασμένη λέξη, καθώς και με την απόσταση επεξεργασίας.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Αποθηκεύει το έγγραφο σε απλό κείμενο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Αποθηκεύει το έγγραφο σε απλό κείμενο ή σε άλλη μορφή εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης. |
| format | [Format](../../com.aspose.ocr.models/format/) | Τύπος enum μορφής εγγράφου Format. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Αποθηκεύει το έγγραφο σε απλό κείμενο ή σε άλλη μορφή εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης. |
| format | [Format](../../com.aspose.ocr.models/format/) | Τύπος enum μορφής εγγράφου Format. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Μειώστε το μέγεθος του αρχείου PDF μειώνοντας την ποιότητα των εικόνων φόντου. Από προεπιλογή, διατηρείται η αρχική ποιότητα της εικόνας. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Αποθηκεύει το διορθωμένο κείμενο με το αγγλικό λεξικό στο έγγραφο σε απλό κείμενο ή σε μορφή εγγράφου κειμένου Microsoft Word.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης. |
| format | [Format](../../com.aspose.ocr.models/format/) | Τύπος enum μορφής εγγράφου Format. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Αποθηκεύει το διορθωμένο κείμενο στο έγγραφο σε απλό κείμενο ή σε άλλη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης. |
| format | [Format](../../com.aspose.ocr.models/format/) | Τύπος enum μορφής εγγράφου Format. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Λεξικό για ορθογραφικό έλεγχο. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Επιτρέπει τη χρήση του δικού σας λεξικού για διόρθωση ορθογραφίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Πλήρης διαδρομή προς το λεξικό χρήστη (λεξικό συχνότητας). Μορφή αρχείου λεξικού: Απλό αρχείο κειμένου σε κωδικοποίηση UTF-8. Η λέξη και η συχνότητα λέξης χωρίζονται με κόμμα, η λέξη αναμένεται στην πρώτη στήλη και η συχνότητα στη δεύτερη στήλη. Κάθε ζεύγος λέξη-συχνότητα σε ξεχωριστή γραμμή. Μια γραμμή ορίζεται ως μια ακολουθία χαρακτήρων που ακολουθείται από αλλαγή γραμμής ("\n"), επιστροφή καρτέλας ("\r"), ή επιστροφή καρτέλας αμέσως ακολουθούμενη από αλλαγή γραμμής ("\r\n"). Κάθε λέξη αναμένεται να είναι σε πεζά. |
