---
title: "InvoiceRecognitionSettings"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Ρυθμίσεις για την αναγνώριση τιμολογίου. Περιέχει στοιχεία που επιτρέπουν την προσαρμογή της διαδικασίας αναγνώρισης."
type: docs
weight: 17
url: /el/java/com.aspose.ocr/invoicerecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class InvoiceRecognitionSettings extends ReceiptRecognitionSettings
```

Ρυθμίσεις για την αναγνώριση τιμολογίου. Περιέχει στοιχεία που επιτρέπουν την προσαρμογή της διαδικασίας αναγνώρισης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [InvoiceRecognitionSettings()](#InvoiceRecognitionSettings) | Προεπιλεγμένος κατασκευαστής: ορίστε autoSkew σε true. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Σύνολο επιτρεπόμενων χαρακτήρων. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Σύνολο επιτρεπόμενων χαρακτήρων. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και επιλέγει αυτόματα έναν ειδικό αλγόριθμο OCR για αυτές. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Ορίζει τη μαύρη λίστα για σύμβολα αναγνώρισης. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Καθορίζει το επίπεδο ανίχνευσης γλώσσας για την αναγνώριση κειμένου. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Λαμβάνει ή ορίζει τον αριθμό των νημάτων για επεξεργασία. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Σας επιτρέπει να χρησιμοποιήσετε πρόσθετους αλγόριθμους ειδικά για την αναγνώριση μικρών γραμματοσειρών. |
### InvoiceRecognitionSettings() {#InvoiceRecognitionSettings}
```
public InvoiceRecognitionSettings()
```


Προεπιλεγμένος κατασκευαστής: ορίστε autoSkew σε true.



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
| allowedCharacters | java.lang.String | περιέχει πίνακα χαρακτήρων. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και επιλέγει αυτόματα έναν ειδικό αλγόριθμο OCR για αυτές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| automaticColorInversion | boolean | περιέχει boolean τιμή - ένα automaticColorInversion έχει οριστεί. |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | Τιμή enum για ορισμό επιπέδου (Paragraph, Word, Page). |

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
