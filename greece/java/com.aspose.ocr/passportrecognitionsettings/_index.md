---
title: "PassportRecognitionSettings"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Ρυθμίσεις για την αναγνώριση διαβατηρίου. Περιέχει στοιχεία που επιτρέπουν την προσαρμογή της διαδικασίας αναγνώρισης."
type: docs
weight: 23
url: /el/java/com.aspose.ocr/passportrecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class PassportRecognitionSettings extends ReceiptRecognitionSettings
```

Ρυθμίσεις για την αναγνώριση διαβατηρίου. Περιέχει στοιχεία που επιτρέπουν την προσαρμογή της διαδικασίας αναγνώρισης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PassportRecognitionSettings()](#PassportRecognitionSettings) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Σύνολο επιτρεπόμενων χαρακτήρων. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Σύνολο επιτρεπόμενων χαρακτήρων. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και επιλέγει αυτόματα έναν ειδικό αλγόριθμο OCR για αυτές. |
| [setCountry(Country country)](#setCountry-com.aspose.ocr.models.Country) | Ορίστε το πρότυπο για την αναγνώριση διαβατηρίου και την εξαγωγή των λέξεων-κλειδιών. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Ορίζει τη μαύρη λίστα για σύμβολα αναγνώρισης. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Καθορίζει το επίπεδο ανίχνευσης γλώσσας για την αναγνώριση κειμένου. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Λαμβάνει ή ορίζει τον αριθμό των νημάτων για επεξεργασία. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Σας επιτρέπει να χρησιμοποιήσετε πρόσθετους αλγόριθμους ειδικά για την αναγνώριση μικρών γραμματοσειρών. |
### PassportRecognitionSettings() {#PassportRecognitionSettings}
```
public PassportRecognitionSettings()
```





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

### setCountry(Country country) {#setCountry-com.aspose.ocr.models.Country}
```
public void setCountry(Country country)
```


Ορίστε το πρότυπο για την αναγνώριση διαβατηρίου και την εξαγωγή των λέξεων-κλειδιών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| country | [Country](../../com.aspose.ocr.models/country/) | χώρα διαβατηρίου. |

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
