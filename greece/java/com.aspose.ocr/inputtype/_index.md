---
title: "InputType"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Τύποι εικόνων/ εγγράφων για επεξεργασία / αναγνώριση"
type: docs
weight: 38
url: /el/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

Τύποι εικόνας/ εγγράφων για επεξεργασία / αναγνώριση.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Base64](#Base64) | Συμβολοσειρά base64 με την εικόνα ή διαδρομή προς το αρχείο .txt με το περιεχόμενο base64. |
| [Directory](#Directory) | Διαδρομή προς τον φάκελο. |
| [PDF](#PDF) | Σαρωμένο έγγραφο PDF από αρχείο ή από InputStream. |
| [SingleImage](#SingleImage) | Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage. |
| [TIFF](#TIFF) | Έγγραφο πολλαπλών σελίδων TIFF, TIF από αρχείο ή από InputStream. |
| [URL](#URL) | Σύνδεσμος στην εικόνα. |
| [Zip](#Zip) | Πλήρες όνομα του αρχείου ZIP. |

### Base64 {#Base64}
```
public static final InputType Base64
```


Συμβολοσειρά base64 με την εικόνα ή διαδρομή προς το αρχείο .txt με το περιεχόμενο base64. Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


Διαδρομή προς τον φάκελο. Τα ενσωματωμένα αρχεία και φάκελοι δεν υποστηρίζονται. Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF. Η προεπιλεγμένη ποσότητα επεξεργασμένων εικόνων είναι όλες.

### PDF {#PDF}
```
public static final InputType PDF
```


Σαρωμένο έγγραφο PDF από αρχείο ή από InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Έγγραφο πολλαπλών σελίδων TIFF, TIF από αρχείο ή από InputStream.

### URL {#URL}
```
public static final InputType URL
```


Σύνδεσμος στην εικόνα. Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


Πλήρες όνομα του αρχείου ZIP. Τα ενσωματωμένα αρχεία και φάκελοι δεν υποστηρίζονται. Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF. Η προεπιλεγμένη ποσότητα επεξεργασμένων εικόνων είναι όλες.
