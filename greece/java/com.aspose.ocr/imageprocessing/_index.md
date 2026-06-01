---
title: "Επεξεργασία εικόνας"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Βοηθητική κλάση για τη βιβλιοθήκη Aspose OCR"
type: docs
weight: 19
url: /el/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Βοηθητική κλάση για τη βιβλιοθήκη Aspose OCR. Επιτρέπει την προεπεξεργασία και αποθήκευση εικόνων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | Χρησιμοποιήστε την επεξεργασία εικόνας για να βελτιώσετε την ακρίβεια του OCR. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | Χρησιμοποιήστε την επεξεργασία εικόνας για να βελτιώσετε την ακρίβεια του OCR. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


Χρησιμοποιήστε την επεξεργασία εικόνας για να βελτιώσετε την ακρίβεια του OCR. Δημιουργήστε μια λίστα φίλτρων που θα εφαρμοστούν στην εικόνα εισόδου με τη σειρά που καθορίζετε. Παράδειγμα για τη δημιουργία φίλτρων: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Δεν χρειάζεστε όλα αυτά. Ορίστε μόνο όσα χρειάζεστε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Αντικείμενο OcrInput που περιέχει διαφορετικές εικόνες @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


Χρησιμοποιήστε την επεξεργασία εικόνας για να βελτιώσετε την ακρίβεια του OCR. Δημιουργήστε μια λίστα φίλτρων που θα εφαρμοστούν στην εικόνα εισόδου με τη σειρά που καθορίζετε. Παράδειγμα για τη δημιουργία φίλτρων: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Δεν χρειάζεστε όλα αυτά. Ορίστε μόνο όσα χρειάζεστε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Αντικείμενο OcrInput που περιέχει διαφορετικές εικόνες @see \#OcrInput. |
| folderPath | java.lang.String | Διαδρομή χωρίς ονόματα εικόνων για την αποθήκευση επεξεργασμένων εικόνων. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
