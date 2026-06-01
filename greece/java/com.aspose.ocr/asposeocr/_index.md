---
title: "AsposeOCR"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Κύρια κλάση για την αναγνώριση κειμένου από εικόνες"
type: docs
weight: 10
url: /el/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Κύρια κλάση για την αναγνώριση κειμένου από εικόνες.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Δημόσιος κατασκευαστής. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DebugMode](#DebugMode) | Ενεργοποιεί τη λειτουργία αποσφαλμάτωσης. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Κατάλογος όπου θα αποθηκευτούν τα αποτελέσματα αποσφαλμάτωσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Υπολογίζει τις γωνίες κλίσης μιας εικόνας. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | Ελέγχει αν δύο εικόνες περιέχουν το ίδιο κείμενο. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Ελέγχει αν δύο εικόνες περιέχουν το ίδιο κείμενο. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Ελέγχει αν δύο εικόνες περιέχουν το ίδιο κείμενο. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | Αυτόματα εντοπίζει προβληματικές περιοχές μιας εικόνας που μπορούν να επηρεάσουν σημαντικά την ακρίβεια του OCR. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Αναλύει την εικόνα και προσδιορίζει τους διαφορετικούς τύπους περιοχών περιεχομένου μέσα σε αυτήν. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Αναλύει το κείμενο στην εικόνα για να προσδιορίσει τις γλώσσες στις οποίες είναι γραμμένο. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Ανιχνεύει περιοχές κειμένου σε εικόνες. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Ανιχνεύει περιοχές πινάκων σε εικόνες. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Ελέγχει αν η εικόνα περιέχει το δοσμένο απόσπασμα κειμένου με αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Ελέγχει αν η εικόνα περιέχει το δοσμένο απόσπασμα κειμένου με αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Ελέγχει αν η εικόνα περιέχει το δοσμένο απόσπασμα κειμένου. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Ελέγχει αν το κείμενο της εικόνας ταιριάζει με την παρεχόμενη κανονική έκφραση. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Ελέγχει αν το κείμενο της εικόνας ταιριάζει με την παρεχόμενη κανονική έκφραση. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | Συγκρίνει τα κείμενα των δύο εικόνων και επιστρέφει έναν αριθμό που αντιπροσωπεύει πόσο παρόμοια είναι (0 έως 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Συγκρίνει τα κείμενα των δύο εικόνων και επιστρέφει έναν αριθμό που αντιπροσωπεύει πόσο παρόμοια είναι (0 έως 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Συγκρίνει τα κείμενα των δύο εικόνων και επιστρέφει έναν αριθμό που αντιπροσωπεύει πόσο παρόμοια είναι (0 έως 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Αναγνωρίζει εικόνα με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Αναγνωρίζει εικόνα με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Αναγνωρίζει πινακίδα αυτοκινήτου με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Ανιχνεύει σύμβολα σε εικόνες. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Ανιχνεύει σύμβολα σε εικόνες. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | Αναγνωρίζει κείμενο σε εικόνα υψηλής ποιότητας. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Αναγνωρίζει μαθηματικούς τύπους από τις παρεχόμενες εικόνες εισόδου. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Αναγνωρίζει χειρόγραφο κείμενο σε εικόνες. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Αναγνωρίζει ταυτότητα με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Αναγνωρίζει τιμολόγιο με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Αναγνωρίζει διαβατήριο με τη δυνατότητα καθορισμού. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Αναγνωρίζει αποδείξεις με τη δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Εντοπίζει πίνακες και δομή, αναγνωρίζει κελιά κειμένου. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult με διόρθωση ορθογραφικού ελέγχου. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Δημόσιος κατασκευαστής.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Ενεργοποιεί τη λειτουργία αποσφαλμάτωσης. Όταν είναι ενεργοποιημένη, το σύστημα αποθηκεύει ενδιάμεσα αποτελέσματα επεξεργασίας εικόνας όπως προεπεξεργασμένες εικόνες και εικόνες με σχεδιασμένα ορθογώνια γραμμών κειμένου.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Κατάλογος όπου θα αποθηκευτούν τα αποτελέσματα αποσφαλμάτωσης. Εάν δεν οριστεί, θα χρησιμοποιηθεί ο τρέχων ενεργός κατάλογος εξ ορισμού.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Υπολογίζει τις γωνίες κλίσης μιας εικόνας. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Το δοχείο με τις πηγές.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - Λίστα ArrayList με γωνίες κλίσης σε μοίρες [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


Ελέγχει αν δύο εικόνες περιέχουν το ίδιο κείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath1 | java.lang.String | Διαδρομή προς την πρώτη εικόνα. |
| fullPath2 | java.lang.String | Διαδρομή προς τη δεύτερη εικόνα. |

**Returns:**
boolean - Αληθές εάν οι εικόνες έχουν το ίδιο κείμενο (90% ομοιότητα).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Ελέγχει αν δύο εικόνες περιέχουν το ίδιο κείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath1 | java.lang.String | Διαδρομή προς την πρώτη εικόνα. |
| fullPath2 | java.lang.String | Διαδρομή προς τη δεύτερη εικόνα. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Ρυθμίσεις αναγνώρισης. |

**Returns:**
boolean - Αληθές εάν οι εικόνες έχουν το ίδιο κείμενο (90% ομοιότητα).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Ελέγχει αν δύο εικόνες περιέχουν το ίδιο κείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath1 | java.lang.String | Διαδρομή προς την πρώτη εικόνα. |
| fullPath2 | java.lang.String | Διαδρομή προς τη δεύτερη εικόνα. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Ρυθμίσεις αναγνώρισης. |
| ignoreCase | boolean | Αληθές - σημαίνει αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων. |

**Returns:**
boolean - Αληθές εάν οι εικόνες έχουν το ίδιο κείμενο (90% ομοιότητα).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο για διόρθωση. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Λεξικό προς χρήση [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Κείμενο με αντικατεστημένες λέξεις.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο για διόρθωση. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Λεξικό προς χρήση [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Πλήρης διαδρομή προς το λεξικό χρήστη (λεξικό συχνότητας). Μορφή αρχείου λεξικού: Απλό αρχείο κειμένου σε κωδικοποίηση UTF-8. Η λέξη και η συχνότητα λέξης χωρίζονται με κόμμα, η λέξη αναμένεται στην πρώτη στήλη και η συχνότητα στη δεύτερη στήλη. Κάθε ζεύγος λέξη-συχνότητα σε ξεχωριστή γραμμή. Μια γραμμή ορίζεται ως μια ακολουθία χαρακτήρων που ακολουθείται από αλλαγή γραμμής ("\n"), επιστροφή καρτέλας ("\r"), ή επιστροφή καρτέλας αμέσως ακολουθούμενη από αλλαγή γραμμής ("\r\n"). Κάθε λέξη αναμένεται να είναι σε πεζά. |

**Returns:**
java.lang.String - Κείμενο με αντικατεστημένες λέξεις.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


Αυτόματη εύρεση προβληματικών περιοχών μιας εικόνας που μπορούν να επηρεάσουν σημαντικά την ακρίβεια του OCR. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Το δοχείο με τις πηγές.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | Οι τύποι ελαττωμάτων που πρέπει να αναγνωριστούν [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - ArrayList του [DefectOutput](../../com.aspose.ocr/defectoutput/) με εντοπισμένες περιοχές κειμένου ή γραμμές.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Αναλύει την εικόνα και προσδιορίζει τους διαφορετικούς τύπους περιοχών περιεχομένου μέσα σε αυτήν. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Το δοχείο με τις πηγές.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Εντοπισμένες περιοχές περιεχομένου. ArrayList του [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Αναλύει το κείμενο στην εικόνα για να προσδιορίσει τις γλώσσες στις οποίες είναι γραμμένο. Αυτό επιτρέπει την επιλογή της πιο κατάλληλης γλώσσας αναγνώρισης και βοηθά σε περαιτέρω εργασίες επεξεργασίας κειμένου όπως ο ορθογραφικός έλεγχος ή η μετάφραση. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Το δοχείο με τις πηγές.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Επιστρέφει μια λίστα με τις πιο πιθανές γλώσσες, ταξινομημένες κατά πιθανότητα. ArrayList του [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Εντοπίζει περιοχές κειμένου σε εικόνες. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Το δοχείο με τις πηγές.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Καθορίζει ποια ορθογώνια θα επιστραφούν - γραμμή ή παραγράφους. |
| isDetectAreas | boolean | Ενεργοποίηση αυτόματης ανίχνευσης περιοχών κειμένου. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList του [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) με εντοπισμένες περιοχές κειμένου ή γραμμές.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Εντοπίζει περιοχές πινάκων σε εικόνες. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Το δοχείο με τις πηγές.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList του [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) με εντοπισμένες περιοχές πινάκων.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Ελέγχει αν η εικόνα περιέχει το δοσμένο απόσπασμα κειμένου με αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath | java.lang.String | Διαδρομή προς την εικόνα. |
| text | java.lang.String | Τμήμα κειμένου για αναζήτηση στην εικόνα. |

**Returns:**
boolean - Αληθές εάν η εικόνα περιέχει τμήμα κειμένου. Ψευδές - η εικόνα δεν περιέχει τμήμα κειμένου.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Ελέγχει αν η εικόνα περιέχει το δοσμένο απόσπασμα κειμένου με αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath | java.lang.String | Διαδρομή προς την εικόνα. |
| text | java.lang.String | Τμήμα κειμένου για αναζήτηση στην εικόνα. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Ρυθμίσεις αναγνώρισης. |

**Returns:**
boolean - Αληθές εάν η εικόνα περιέχει τμήμα κειμένου. Ψευδές - η εικόνα δεν περιέχει τμήμα κειμένου.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Ελέγχει αν η εικόνα περιέχει το δοσμένο απόσπασμα κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath | java.lang.String | Διαδρομή προς την εικόνα. |
| text | java.lang.String | Τμήμα κειμένου για αναζήτηση στην εικόνα. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Ρυθμίσεις αναγνώρισης. |
| ignoreCase | boolean | Αληθές - σημαίνει αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων. |

**Returns:**
boolean - Αληθές εάν η εικόνα περιέχει τμήμα κειμένου. Ψευδές - η εικόνα δεν περιέχει τμήμα κειμένου.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Ελέγχει αν το κείμενο της εικόνας ταιριάζει με την παρεχόμενη κανονική έκφραση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath | java.lang.String | Διαδρομή προς την εικόνα. |
| regex | java.util.regex.Pattern | Αντικείμενο java.util.regex.Pattern με το παρεχόμενο μοτίβο και τις επιλογές. |

**Returns:**
boolean - Αληθές εάν το κείμενο της εικόνας ταιριάζει με την παρεχόμενη κανονική έκφραση.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Ελέγχει αν το κείμενο της εικόνας ταιριάζει με την παρεχόμενη κανονική έκφραση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath | java.lang.String | Διαδρομή προς την εικόνα. |
| regex | java.util.regex.Pattern | Αντικείμενο java.util.regex.Pattern με το παρεχόμενο μοτίβο και τις επιλογές. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Ρυθμίσεις αναγνώρισης. |

**Returns:**
boolean - Αληθές εάν το κείμενο της εικόνας ταιριάζει με την παρεχόμενη κανονική έκφραση.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


Συγκρίνει τα κείμενα των δύο εικόνων και επιστρέφει έναν αριθμό που αντιπροσωπεύει πόσο παρόμοια είναι (0 έως 1).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath1 | java.lang.String | Διαδρομή προς την πρώτη εικόνα. |
| fullPath2 | java.lang.String | Διαδρομή προς τη δεύτερη εικόνα. |

**Returns:**
float - 0 σημαίνει ότι τα κείμενα είναι εντελώς διαφορετικά· 1 σημαίνει ότι τα κείμενα είναι ταυτόσημα.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Συγκρίνει τα κείμενα των δύο εικόνων και επιστρέφει έναν αριθμό που αντιπροσωπεύει πόσο παρόμοια είναι (0 έως 1).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath1 | java.lang.String | Διαδρομή προς την πρώτη εικόνα. |
| fullPath2 | java.lang.String | Διαδρομή προς τη δεύτερη εικόνα. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Ρυθμίσεις αναγνώρισης. |

**Returns:**
float - 0 σημαίνει ότι τα κείμενα είναι εντελώς διαφορετικά· 1 σημαίνει ότι τα κείμενα είναι ταυτόσημα.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Συγκρίνει τα κείμενα των δύο εικόνων και επιστρέφει έναν αριθμό που αντιπροσωπεύει πόσο παρόμοια είναι (0 έως 1).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath1 | java.lang.String | Διαδρομή προς την πρώτη εικόνα. |
| fullPath2 | java.lang.String | Διαδρομή προς τη δεύτερη εικόνα. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Ρυθμίσεις αναγνώρισης. |
| ignoreCase | boolean | Αληθές - σημαίνει αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων. |

**Returns:**
float - 0 σημαίνει ότι τα κείμενα είναι εντελώς διαφορετικά· 1 σημαίνει ότι τα κείμενα είναι ταυτόσημα.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Αναγνωρίζει εικόνα με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). παράδειγμα. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Αναγνωρίζει εικόνα με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). παράδειγμα. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Αναγνωρίζει πινακίδα αυτοκινήτου με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). παράδειγμα. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Ανιχνεύει σύμβολα σε εικόνες. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Το δοχείο με τις πηγές.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList του [Character](../../com.aspose.ocr.models/character/) με δεδομένα ανιχνευμένων συμβόλων για κάθε εικόνα.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Ανιχνεύει σύμβολα σε εικόνες. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Το δοχείο με τις πηγές.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Καθορίζει τον τύπο του νευρωνικού δικτύου που χρησιμοποιείται για την ανίχνευση περιοχών. |
| language | [Language](../../com.aspose.ocr.models/language/) | Γλώσσα που χρησιμοποιείται για OCR. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList του [Character](../../com.aspose.ocr.models/character/) με δεδομένα ανιχνευμένων συμβόλων.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


Αναγνωρίζει κείμενο σε εικόνα υψηλής ποιότητας. Δεν χρησιμοποιεί αυτόματη διόρθωση κλίσης εικόνας και ανίχνευση περιοχών κειμένου. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Αντίγραφο [OcrInput](../../com.aspose.ocr/ocrinput/). |

**Returns:**
java.util.ArrayList<java.lang.String> - ArrayList με αναγνωρισμένο κείμενο.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Αναγνωρίζει μαθηματικούς τύπους από τις παρεχόμενες εικόνες εισόδου. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). παράδειγμα. |
| detectAreas | boolean | Εάν οριστεί σε true, ανιχνεύει αυτόματα και απομονώνει περιοχές τύπων πριν από την αναγνώριση. Εάν είναι false, επεξεργάζεται ολόκληρη την εικόνα ως τύπο. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Αναγνωρίζει χειρόγραφο κείμενο σε εικόνες. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Το δοχείο με τις πηγές.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Αναγνωρίζει ταυτότητα με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). παράδειγμα. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Αναγνωρίζει τιμολόγιο με δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). παράδειγμα. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Αναγνωρίζει διαβατήριο με δυνατότητα προσαρμογής. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). παράδειγμα. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Αναγνωρίζει αποδείξεις με τη δυνατότητα καθορισμού. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). παράδειγμα. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Ανιχνεύει πίνακες και δομή, αναγνωρίζει κελιά κειμένου. Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, φάκελο, πίνακα, αρχείο zip, URL, base64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). παράδειγμα. |
| language | [Language](../../com.aspose.ocr.models/language/) | Καθορίζει το αλφάβητο που χρησιμοποιείται κατά την αναγνώριση. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - αντικείμενα λίστας OCRTablePage με αναγνωρισμένα κείμενα σε πίνακες. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Λίστα των [RecognitionResult](../../com.aspose.ocr/recognitionresult/). αντικειμένων. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Λίστα των [RecognitionResult](../../com.aspose.ocr/recognitionresult/). αντικειμένων. |
| embeddedFontPath | java.lang.String | Προαιρετικά. Πλήρης διαδρομή προς τη γραμματοσειρά του χρήστη. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Λίστα των [RecognitionResult](../../com.aspose.ocr/recognitionresult/). αντικειμένων. |
| embeddedFontPath | java.lang.String | Προαιρετικά. Πλήρης διαδρομή προς τη γραμματοσειρά του χρήστη. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Μειώστε το μέγεθος του αρχείου PDF μειώνοντας την ποιότητα των εικόνων φόντου. Από προεπιλογή, διατηρείται η αρχική ποιότητα της εικόνας. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Λίστα των [RecognitionResult](../../com.aspose.ocr/recognitionresult/). αντικειμένων. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult με διόρθωση ορθογραφικού ελέγχου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Λίστα των [RecognitionResult](../../com.aspose.ocr/recognitionresult/). αντικειμένων. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) τιμή enum. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Λίστα των [RecognitionResult](../../com.aspose.ocr/recognitionresult/). αντικειμένων. |
| embeddedFontPath | java.lang.String | Προαιρετικά. Πλήρης διαδρομή προς τη γραμματοσειρά του χρήστη. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Επιτρέπει την απόκτηση πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Λίστα των [RecognitionResult](../../com.aspose.ocr/recognitionresult/). αντικειμένων. |
| embeddedFontPath | java.lang.String | Προαιρετικά. Πλήρης διαδρομή προς τη γραμματοσειρά του χρήστη. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Μειώστε το μέγεθος του αρχείου PDF μειώνοντας την ποιότητα των εικόνων φόντου. Από προεπιλογή, διατηρείται η αρχική ποιότητα της εικόνας. |

### close() {#close}
```
public void close()
```