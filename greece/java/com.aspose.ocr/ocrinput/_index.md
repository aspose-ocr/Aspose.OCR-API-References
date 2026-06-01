---
title: "OcrInput"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Κύρια κλάση για την αναγνώριση κειμένου από εικόνες"
type: docs
weight: 20
url: /el/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Κύρια κλάση για την αναγνώριση κειμένου από εικόνες.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Κατασκευαστής για δημιουργία κοντέινερ και ορισμό του τύπου εικόνων / εγγράφων και φίλτρων για περαιτέρω επεξεργασία / αναγνώριση. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Προσθέστε την αποκωδικοποιημένη εικόνα στη λίστα για αναγνώριση / επεξεργασία. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Προσθέστε το BufferedImage που περιέχει την εικόνα για αναγνώριση / επεξεργασία. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Προσθέστε το BufferedImage που περιέχει την πολυσελίδα εικόνα για αναγνώριση / επεξεργασία. |
| [add(InputStream stream)](#add-java.io.InputStream) | Προσθέστε το InputStream που περιέχει την εικόνα για αναγνώριση / επεξεργασία. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Προσθέστε το InputStream που περιέχει την πολυσελίδα εικόνα για αναγνώριση / επεξεργασία. |
| [add(String fullPath)](#add-java.lang.String) | Προσθέστε τη διαδρομή ή το URI που περιέχει την εικόνα για αναγνώριση / επεξεργασία. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Προσθέστε τις πολυσελίδα εικόνες / έγγραφα για αναγνώριση / επεξεργασία. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Προσθέστε τη συμβολοσειρά base64 που περιέχει την εικόνα για αναγνώριση / επεξεργασία. |
| [clear()](#clear) | Ορίστε την ποσότητα των στοιχείων για επεξεργασία / αναγνώριση σε 0. |
| [clearFilters()](#clearFilters) | Αφαιρέστε όλα τα φίλτρα. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | Επιστρέφει πληροφορίες σχετικά με την επεξεργασμένη / αναγνωρισμένη εικόνα. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Αφαιρέστε τα παλιά φίλτρα και ορίστε νέα. |
| [size()](#size) | Ποσότητα στοιχείων για επεξεργασία / αναγνώριση. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Κατασκευαστής για δημιουργία κοντέινερ και ορισμό του τύπου εικόνων / εγγράφων και φίλτρων για περαιτέρω επεξεργασία / αναγνώριση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Ορίστε τον τύπο εικόνων/εγγράφων που θα προστεθεί στο κοντέινερ. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Ορίστε τα φίλτρα επεξεργασίας που θα εφαρμοστούν για περαιτέρω επεξεργασία ή αναγνώριση. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Προσθέστε την αποκωδικοποιημένη εικόνα στη λίστα για αναγνώριση / επεξεργασία. Ο τύπος της εικόνας πρέπει να αντιστοιχεί στον τύπο που ορίζεται στον κατασκευαστή (SingleImage).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | int[] | Τα pixel αναπαριστώνται ως 32-bit ακέραιες τιμές (rgb). |
| πλάτος | int | Πλάτος εικόνας. |
| ύψος | int | Ύψος εικόνας. |
| bitsPerPixel | int | Υποστηρίζει 1-32 bits. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Προσθέστε το BufferedImage που περιέχει την εικόνα για αναγνώριση / επεξεργασία. Ο τύπος της εικόνας πρέπει να αντιστοιχεί στον τύπο που ορίζεται στον κατασκευαστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | java.awt.image.BufferedImage | BufferedImage που περιέχει την εικόνα ή το έγγραφο. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Προσθέστε το BufferedImage που περιέχει την πολυσελίδα εικόνα για αναγνώριση / επεξεργασία. Ο τύπος της εικόνας πρέπει να αντιστοιχεί στον τύπο που ορίζεται στον κατασκευαστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | java.awt.image.BufferedImage | BufferedImage που περιέχει το πολυσελίδα έγγραφο. |
| startPage | int | Η πρώτη σελίδα/εικόνα για επεξεργασία / αναγνώριση. Χρησιμοποιείται για έγγραφα. |
| pagesCount | int | Η συνολική ποσότητα σελίδων/εικόνων για επεξεργασία / αναγνώριση. Χρησιμοποιείται για έγγραφα. Προεπιλογή = όλα. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Προσθέστε το InputStream που περιέχει την εικόνα για αναγνώριση / επεξεργασία. Ο τύπος της εικόνας πρέπει να αντιστοιχεί στον τύπο που ορίζεται στον κατασκευαστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream που περιέχει την εικόνα ή το έγγραφο. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Προσθέστε το InputStream που περιέχει την πολυσελίδα εικόνα για αναγνώριση / επεξεργασία. Ο τύπος της εικόνας πρέπει να αντιστοιχεί στον τύπο που καθορίζεται στον κατασκευαστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream που περιέχει το πολυσελιδικό έγγραφο. |
| startPage | int | Η πρώτη σελίδα/εικόνα για επεξεργασία / αναγνώριση. Χρησιμοποιείται για έγγραφα. |
| pagesCount | int | Η συνολική ποσότητα σελίδων/εικόνων για επεξεργασία / αναγνώριση. Χρησιμοποιείται για έγγραφα. Προεπιλογή = όλα. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Προσθέστε τη διαδρομή ή το URI που περιέχει την εικόνα για αναγνώριση / επεξεργασία. Ο τύπος της εικόνας πρέπει να αντιστοιχεί στον τύπο που καθορίζεται στον κατασκευαστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath | java.lang.String | Διαδρομή προς την εικόνα/ έγγραφο / φάκελο / αρχείο. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Προσθέστε τις πολυσελιδικές εικόνες / έγγραφα για αναγνώριση / επεξεργασία. Ο τύπος της εικόνας πρέπει να αντιστοιχεί στον τύπο που καθορίζεται στον κατασκευαστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fullPath | java.lang.String | Διαδρομή προς την εικόνα/ έγγραφο / φάκελο / αρχείο. |
| startPage | int | Η πρώτη σελίδα/εικόνα για επεξεργασία / αναγνώριση. Χρησιμοποιήστε για έγγραφα, zip, φακέλους. |
| pagesCount | int | Το συνολικό πλήθος σελίδων/εικόνων για επεξεργασία / αναγνώριση. Χρησιμοποιήστε για έγγραφα, zip, φακέλους. Προεπιλογή = όλα. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Προσθέστε τη συμβολοσειρά base64 που περιέχει την εικόνα για αναγνώριση / επεξεργασία. Ο τύπος της εικόνας πρέπει να αντιστοιχεί στον τύπο που καθορίζεται στον κατασκευαστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| base64 | java.lang.String | Base64 συμβολοσειρά με μία εικόνα. |

### clear() {#clear}
```
public void clear()
```


Ορίστε το πλήθος των στοιχείων για επεξεργασία / αναγνώριση σε 0. Καθαρίστε τη συλλογή.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Αφαιρέστε όλα τα φίλτρα.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int}
```
public ImageData get(int index)
```


Επιστρέφει πληροφορίες σχετικά με την επεξεργασμένη / αναγνωρισμένη εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση της εικόνας στη Λίστα. |

**Returns:**
[ImageData](../../com.aspose.ocr/imagedata/) - The object of @see [ImageData](../../com.aspose.ocr/imagedata/)
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator}
```
public Iterator<ImageData> iterator()
```




**Returns:**
java.util.Iterator<com.aspose.ocr.ImageData>
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### replaceFilters(PreprocessingFilter filters) {#replaceFilters-com.aspose.ocr.PreprocessingFilter}
```
public void replaceFilters(PreprocessingFilter filters)
```


Αφαιρέστε τα παλιά φίλτρα και ορίστε νέα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Τα φίλτρα επεξεργασίας θα εφαρμοστούν για περαιτέρω επεξεργασία ή αναγνώριση. |

### size() {#size}
```
public int size()
```


Ποσότητα στοιχείων για επεξεργασία / αναγνώριση.

**Returns:**
int - Πλήθος στοιχείων.
### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

