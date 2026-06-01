---
title: "OcrOutput"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: 
type: docs
weight: 21
url: /el/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OcrOutput()](#OcrOutput) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης OcrOutput με μια κενή συλλογή. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |

| [getTableData()](#getTableData) | Επιστρέφει δομημένα δεδομένα πίνακα που εξάγονται από όλες τις αναγνωρισμένες σελίδες. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Αποθηκεύει όλα τα αποτελέσματα αναγνώρισης σε ροή μνήμης με τη συγκεκριμένη μορφή. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Αποθηκεύει όλα τα αποτελέσματα αναγνώρισης σε ροή μνήμης με τη συγκεκριμένη μορφή. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Αποθηκεύει όλα τα αποτελέσματα αναγνώρισης σε ροή μνήμης με τη συγκεκριμένη μορφή. |
| [save(String fullFileName)](#save-java.lang.String) | Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αρχείο. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αρχείο. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αρχείο. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα εγχώριο αναζητήσιμο PDF έγγραφο, ενσωματώνοντας τις αρχικές εικόνες ως φόντο. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα εγχώριο αναζητήσιμο PDF έγγραφο, ενσωματώνοντας τις αρχικές εικόνες ως φόντο. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αναζητήσιμο αρχείο PDF, με τις αρχικές εικόνες ορισμένες ως φόντο. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αναζητήσιμο αρχείο PDF, με τις αρχικές εικόνες ορισμένες ως φόντο. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Επιστρέφει δομημένα δεδομένα πίνακα που εξάγονται από όλες τις αναγνωρισμένες σελίδες.

Κάθε σελίδα περιέχει γραμμές και κάθε γραμμή περιέχει κελιά με αναγνωρισμένο κείμενο και προαιρετικές πληροφορίες θέσης.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Αποθηκεύει όλα τα αποτελέσματα αναγνώρισης σε ροή μνήμης με τη συγκεκριμένη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Αποθηκεύει όλα τα αποτελέσματα αναγνώρισης σε ροή μνήμης με τη συγκεκριμένη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Αποθηκεύει όλα τα αποτελέσματα αναγνώρισης σε ροή μνήμης με τη συγκεκριμένη μορφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Προαιρετικό. Πλήρης διαδρομή προς τη γραμματοσειρά του χρήστη. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Μειώστε το μέγεθος του αρχείου PDF μειώνοντας την ποιότητα των εικόνων φόντου. Από προεπιλογή, διατηρείται η αρχική ποιότητα της εικόνας. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Μορφή εγγράφου (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Προαιρετικό. Πλήρης διαδρομή προς τη γραμματοσειρά του χρήστη. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Μειώστε το μέγεθος του αρχείου PDF μειώνοντας την ποιότητα των εικόνων φόντου. Από προεπιλογή, διατηρείται η αρχική ποιότητα της εικόνας. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα εγχώριο αναζητήσιμο PDF έγγραφο, ενσωματώνοντας τις αρχικές εικόνες ως φόντο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα εγχώριο αναζητήσιμο PDF έγγραφο, ενσωματώνοντας τις αρχικές εικόνες ως φόντο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| embeddedFontPath | java.lang.String | Προαιρετικό. Πλήρης διαδρομή προς τη γραμματοσειρά του χρήστη. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Μειώστε το μέγεθος του αρχείου PDF μειώνοντας την ποιότητα των εικόνων φόντου. Από προεπιλογή, διατηρείται η αρχική ποιότητα της εικόνας. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αναζητήσιμο αρχείο PDF, με τις αρχικές εικόνες ορισμένες ως φόντο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Αποθηκεύστε όλα τα αποτελέσματα αναγνώρισης σε ένα αναζητήσιμο αρχείο PDF, με τις αρχικές εικόνες ορισμένες ως φόντο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullFileName | java.lang.String | Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή. |
| embeddedFontPath | java.lang.String | Προαιρετικό. Πλήρης διαδρομή προς τη γραμματοσειρά του χρήστη. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Μειώστε το μέγεθος του αρχείου PDF μειώνοντας την ποιότητα των εικόνων φόντου. Από προεπιλογή, διατηρείται η αρχική ποιότητα της εικόνας. |

### size() {#size}
```
public int size()
```




**Returns:**
int
