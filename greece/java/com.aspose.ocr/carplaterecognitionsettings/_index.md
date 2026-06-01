---
title: "CarPlateRecognitionSettings"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Ρυθμίσεις για την αναγνώριση αριθμού αυτοκινήτου. Περιέχει στοιχεία που επιτρέπουν την προσαρμογή της διαδικασίας αναγνώρισης."
type: docs
weight: 12
url: /el/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Ρυθμίσεις για την αναγνώριση αριθμού αυτοκινήτου. Περιέχει στοιχεία που επιτρέπουν την προσαρμογή της διαδικασίας αναγνώρισης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Προεπιλεγμένος κατασκευαστής: ορίστε autoSkew σε true. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | Σύνολο επιτρεπόμενων χαρακτήρων. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και επιλέγει αυτόματα έναν ειδικό αλγόριθμο OCR για αυτές. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Ορίζει τη μαύρη λίστα για σύμβολα αναγνώρισης. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Προεπιλεγμένος κατασκευαστής: ορίστε autoSkew σε true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Σύνολο επιτρεπόμενων χαρακτήρων. Καθορίζει τον τύπο των χαρακτήρων που επιτρέπονται για το αποτέλεσμα της αναγνώρισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | περιέχει την τιμή enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) |

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

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | Ορίζει τη γλώσσα που χρησιμοποιείται για OCR. Πολλαπλές γλώσσες (καμία) από προεπιλογή. |

