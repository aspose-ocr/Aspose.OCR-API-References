---
title: "Άδεια"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Παρέχει μεθόδους για την άδεια του στοιχείου."
type: docs
weight: 21
url: /el/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Παρέχει μεθόδους για την άδεια του στοιχείου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [License()](#License) | Αρχικοποιεί ένα νέο αντίτυπο αυτής της κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Παρέχει άδεια στο στοιχείο. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Παρέχει άδεια στο στοιχείο. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Παρέχει άδεια στο στοιχείο. |
| [isValid()](#isValid--) | Ελέγξτε την άδεια. |
### License() {#License}
```
public License()
```


Αρχικοποιεί ένα νέο αντίτυπο αυτής της κλάσης.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Παρέχει άδεια στο στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseFile | java.io.File | αναπαράσταση της διαδρομής αρχείου |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Παρέχει άδεια στο στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Μία ροή που περιέχει την άδεια. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Παρέχει άδεια στο στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Ελέγξτε την άδεια.

**Returns:**
boolean - Boolean τιμή η άδεια είναι έγκυρη.
