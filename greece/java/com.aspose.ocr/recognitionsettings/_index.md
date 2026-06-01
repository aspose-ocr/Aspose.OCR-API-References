---
title: "RecognitionSettings"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Ρυθμίσεις για την αναγνώριση εικόνας"
type: docs
weight: 27
url: /el/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Ρυθμίσεις για την αναγνώριση εικόνας. Περιέχει στοιχεία που επιτρέπουν την προσαρμογή της διαδικασίας αναγνώρισης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Προεπιλεγμένος κατασκευαστής: ορίζει το recognitionAreas σε null, το linesFiltration σε false, το autoSkew σε false, το recognizeSingleLine σε false. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | Ο κατασκευαστής επιτρέπει τον ορισμό όλων των επιλογών. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | Ο κατασκευαστής επιτρέπει τον ορισμό του recognizeSingleLine. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Σύνολο επιτρεπόμενων χαρακτήρων. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Σύνολο επιτρεπόμενων χαρακτήρων. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και επιλέγει αυτόματα έναν ειδικό αλγόριθμο OCR για αυτές. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Καθορίζει τον τύπο του νευρωνικού δικτύου που χρησιμοποιείται για την ανίχνευση περιοχών. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Ορίζει τη μαύρη λίστα για σύμβολα αναγνώρισης. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Καθορίζει το επίπεδο ανίχνευσης γλώσσας για την αναγνώριση κειμένου. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Επιτρέπει την αναγνώριση κειμένου στους πίνακες (περιοχές περιτριγυρισμένες από γραμμές). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | Ορίζει τη λίστα των περιοχών κειμένου για επεξεργασία. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Ορίζει την αναγνώριση εικόνας μιας γραμμής. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Λαμβάνει ή ορίζει τον αριθμό των νημάτων για επεξεργασία. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Σας επιτρέπει να χρησιμοποιήσετε πρόσθετους αλγόριθμους ειδικά για την αναγνώριση μικρών γραμματοσειρών. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Προεπιλεγμένος κατασκευαστής: ορίζει το recognitionAreas σε null, το linesFiltration σε false, το autoSkew σε false, το recognizeSingleLine σε false.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


Ο κατασκευαστής επιτρέπει τον ορισμό όλων των επιλογών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Ορθογώνια για αναγνώριση. |
| recognizeSingleLine | boolean | True εάν η εικόνα περιέχει μόνο μία γραμμή. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


Ο κατασκευαστής επιτρέπει τον ορισμό του recognizeSingleLine. Προεπιλεγμένες τιμές σε αυτήν την περίπτωση: detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recognizeSingleLine | boolean | True εάν η εικόνα περιέχει μόνο μία γραμμή. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Σύνολο επιτρεπόμενων χαρακτήρων. Καθορίζει τον τύπο των χαρακτήρων που επιτρέπονται για το αποτέλεσμα της αναγνώρισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | περιέχει τιμή enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/). |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Σύνολο επιτρεπόμενων χαρακτήρων. Καθορίζει τον πίνακα των χαρακτήρων που επιτρέπονται για το αποτέλεσμα της αναγνώρισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| allowedCharacters | java.lang.String | περιέχει συμβολοσειρά χαρακτήρων. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και επιλέγει αυτόματα έναν ειδικό αλγόριθμο OCR για αυτές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| automaticColorInversion | boolean | περιέχει boolean τιμή - ένα automaticColorInversion έχει οριστεί. True από προεπιλογή. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Καθορίζει τον τύπο του νευρωνικού δικτύου που χρησιμοποιείται για την ανίχνευση περιοχών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | περιέχει enum @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) τιμή. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Ορίζει τη μαύρη λίστα για σύμβολα αναγνώρισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| characters | java.lang.String | Χαρακτήρες που εξαιρούνται από την αναγνώριση. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Ορίζει τη γλώσσα που χρησιμοποιείται για OCR. Πολλαπλές γλώσσες (καμία) από προεπιλογή. |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Καθορίζει το επίπεδο ανίχνευσης γλώσσας για την αναγνώριση κειμένου. Λειτουργεί μόνο εάν η επιλεγμένη γλώσσα είναι Language.MULTILANGUAGE, Language.AUTO ή Language.UNIVERSAL. Αυτή η διαδικασία είναι χρονοβόρα και επιβραδύνει σημαντικά τη συνολική αναγνώριση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Επιτρέπει την αναγνώριση κειμένου στους πίνακες (περιοχές περιτριγυρισμένες από γραμμές).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| linesFiltration | boolean | false - επιτρέπει την αύξηση της απόδοσης και δεν εντοπίζει πίνακες και αφαιρεί γραμμές· διαφορετικά - true. Απενεργοποιημένο (false) από προεπιλογή. |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


Ορίζει τη λίστα των περιοχών κειμένου για επεξεργασία. Επιτρέπει τον χειροκίνητο καθορισμό των περιοχών με κείμενο για πιο ακριβή αναγνώριση. Εάν οι προσαρμοσμένες περιοχές έχουν οριστεί [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} όχι NONE ή [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} ιδιότητες θα αγνοηθούν. Απενεργοποιεί τα DetectAreas και AutoSkew.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Ορθογώνια για αναγνώριση. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Ορίζει την αναγνώριση εικόνας μονής γραμμής. Απενεργοποιημένο (false) από προεπιλογή. Απενεργοποιεί όλα τα βήματα επεξεργασίας που σχετίζονται με το διαχωρισμό σε γραμμές. Ορίστε αυτήν την παράμετρο σε true εάν η εικόνα σας περιέχει μόνο μία γραμμή. Απενεργοποιεί τις ρυθμίσεις [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList) ώστε όλες οι ρυθμίσεις περιοχών να αγνοηθούν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| recognizeSingleLine | boolean | True για εικόνα μονής γραμμής |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Λαμβάνει ή ορίζει τον αριθμό των νημάτων για επεξεργασία. Από προεπιλογή, το 0 σημαίνει ότι η εικόνα θα επεξεργαστεί με αριθμό νημάτων ίσο με τον αριθμό των επεξεργαστών σας. ThreadsCount = 1 σημαίνει ότι η εικόνα θα επεξεργαστεί στο κύριο νήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threadsCount | int | ο αριθμός των νημάτων που θα δημιουργηθούν για παράλληλη αναγνώριση τμημάτων εικόνας. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Σας επιτρέπει να χρησιμοποιήσετε πρόσθετους αλγόριθμους ειδικά για την αναγνώριση μικρών γραμματοσειρών. Χρήσιμο για εικόνες με χαρακτήρες μικρού μεγέθους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| upscaleSmallFont | boolean | περιέχει boolean τιμή - ένα upscaleSmallFont έχει οριστεί. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String