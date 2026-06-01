---
title: "PreprocessingFilter"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Βασική κλάση για εντολές επεξεργασίας εικόνας"
type: docs
weight: 24
url: /el/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Βασική κλάση για εντολές επεξεργασίας εικόνας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Empty](#Empty) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Επιτρέπει τη χρήση ενός πρόσθετου νευρωνικού δικτύου για τη βελτίωση της εικόνας - μείωση του θορύβου. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Επιτρέπει τη χρήση ενός πρόσθετου νευρωνικού δικτύου για τη βελτίωση του τμήματος της εικόνας - μείωση του θορύβου. |
| [AutoDewarping()](#AutoDewarping) | Διορθώνει αυτόματα τις γεωμετρικές παραμορφώσεις στην εικόνα. |
| [AutoSkew()](#AutoSkew) | Επιτρέπει την αυτόματη διόρθωση κλίσης της εικόνας. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Επιτρέπει την αυτόματη διόρθωση κλίσης του τμήματος της εικόνας. |
| [Binarize()](#Binarize) | Μετατρέπει μια εικόνα σε ασπρόμαυρη εικόνα. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Μετατρέπει ένα τμήμα της εικόνας σε ασπρόμαυρη εικόνα. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | Η διάταση προσθέτει εικονοστοιχεία στα σύνορα των αντικειμένων σε μια εικόνα. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | Η διάταση προσθέτει εικονοστοιχεία στα σύνορα των αντικειμένων σε ένα τμήμα της εικόνας. |
| [ContrastCorrection()](#ContrastCorrection) | Φίλτρο διόρθωσης αντίθεσης. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Φίλτρο διόρθωσης αντίθεσης για το τμήμα της εικόνας. |
| [Invert()](#Invert) | Αντιστρέφει αυτόματα τα χρώματα σε εικόνα εγγράφου. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Αντιστρέφει αυτόματα τα χρώματα σε ένα τμήμα της εικόνας. |
| [Median()](#Median) | Το φίλτρο διαμέσου διατρέχει κάθε στοιχείο της εικόνας και αντικαθιστά κάθε εικονοστοιχείο με τη διάμεσο των γειτονικών του εικονοστοιχείων. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | Το φίλτρο διαμέσου εκτελείται σε κάθε στοιχείο του τμήματος της εικόνας και αντικαθιστά κάθε pixel με τη διάμεσο των γειτονικών του pixel. |
| [Resize(int width, int height)](#Resize-int-int) | Ανακλιμάκωση εικόνας - Αύξηση ή μείωση της ανάλυσης της εικόνας. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Ανακλιμάκωση εικόνας - αύξηση ή μείωση της ανάλυσης της εικόνας. |
| [Rotate(float angle)](#Rotate-float) | Περιστροφή αρχικής εικόνας. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Περιστροφή του τμήματος της εικόνας. |
| [Scale(float ratio)](#Scale-float) | Ανακλιμάκωση εικόνας - Αύξηση ή μείωση της ανάλυσης της εικόνας. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Ανακλιμάκωση εικόνας - Αύξηση ή μείωση της ανάλυσης της εικόνας. |
| [Threshold(int value)](#Threshold-int) | Δημιουργία δυαδικής εικόνας με βάση τον καθορισμό μιας τιμής κατωφλίου στην ένταση των pixel της αρχικής εικόνας. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Δημιουργία τμήματος δυαδικής εικόνας με βάση τον καθορισμό μιας τιμής κατωφλίου στην ένταση των pixel του αρχικού τμήματος της εικόνας. |
| [ToGrayscale()](#ToGrayscale) | Μετατρέπει μια εικόνα σε εικόνα σε κλίμακα του γκρι. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Προσθέστε το νέο φίλτρο στη συλλογή για να εκτελεστούν περαιτέρω όλες οι λειτουργίες. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### PreprocessingFilter() {#PreprocessingFilter}
```
public PreprocessingFilter()
```


### Empty {#Empty}
```
public static final PreprocessingFilter Empty
```


### AutoDenoising() {#AutoDenoising}
```
public static PreprocessingFilter AutoDenoising()
```


Επιτρέπει τη χρήση ενός πρόσθετου νευρωνικού δικτύου για τη βελτίωση της εικόνας - μείωση του θορύβου. Χρήσιμο για εικόνες με ελαττώματα σάρωσης, παραμόρφωση, κηλίδες, λάμψεις, διαβαθμίσεις, ξένα στοιχεία.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Επιτρέπει τη χρήση ενός πρόσθετου νευρωνικού δικτύου για τη βελτίωση του τμήματος της εικόνας - μείωση του θορύβου. Χρήσιμο για εικόνες με ελαττώματα σάρωσης, παραμόρφωση, κηλίδες, λάμψεις, διαβαθμίσεις, ξένα στοιχεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιοχή | java.awt.Rectangle | Rectangle για προεπεξεργασία. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Διορθώνει αυτόματα γεωμετρικές παραμορφώσεις στην εικόνα. Εξαιρετικά απαιτητικό σε πόρους!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Επιτρέπει την αυτόματη διόρθωση κλίσης της εικόνας.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Επιτρέπει την αυτόματη διόρθωση κλίσης του τμήματος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιοχή | java.awt.Rectangle | Rectangle για προεπεξεργασία. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Μετατρέπει μια εικόνα σε ασπρόμαυρη εικόνα. Οι δυαδικές εικόνες είναι εικόνες των οποίων τα pixel έχουν μόνο δύο δυνατές τιμές έντασης. Συνήθως εμφανίζονται ως μαύρο και λευκό. Αριθμητικά, οι δύο τιμές είναι συχνά 0 για το μαύρο και 255 για το λευκό. Οι δυαδικές εικόνες παράγονται με αυτόματο καθορισμό κατωφλίου μιας εικόνας.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Μετατρέπει ένα τμήμα της εικόνας σε ασπρόμαυρη εικόνα. Οι δυαδικές εικόνες είναι εικόνες των οποίων τα pixel έχουν μόνο δύο δυνατές τιμές έντασης. Συνήθως εμφανίζονται ως μαύρο και λευκό. Αριθμητικά, οι δύο τιμές είναι συχνά 0 για το μαύρο και 255 για το λευκό. Οι δυαδικές εικόνες παράγονται με αυτόματο καθορισμό κατωφλίου μιας εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιοχή | java.awt.Rectangle | Rectangle για προεπεξεργασία. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


Η διάταση προσθέτει εικονοστοιχεία στα σύνορα των αντικειμένων σε μια εικόνα.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


Η διάταση προσθέτει εικονοστοιχεία στα σύνορα των αντικειμένων σε ένα τμήμα της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιοχή | java.awt.Rectangle | Rectangle για προεπεξεργασία. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Φίλτρο διόρθωσης αντίθεσης.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Φίλτρο διόρθωσης αντίθεσης για το τμήμα της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιοχή | java.awt.Rectangle | Rectangle για προεπεξεργασία. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Αντιστρέφει αυτόματα τα χρώματα σε εικόνα εγγράφου.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Αντιστρέφει αυτόματα τα χρώματα σε ένα τμήμα της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιοχή | java.awt.Rectangle | Rectangle για προεπεξεργασία. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


Το φίλτρο διαμέσου διατρέχει κάθε στοιχείο της εικόνας και αντικαθιστά κάθε εικονοστοιχείο με τη διάμεσο των γειτονικών του εικονοστοιχείων.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


Το φίλτρο διαμέσου εκτελείται σε κάθε στοιχείο του τμήματος της εικόνας και αντικαθιστά κάθε pixel με τη διάμεσο των γειτονικών του pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιοχή | java.awt.Rectangle | Rectangle για προεπεξεργασία. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Ανακλιμάκωση εικόνας - Αύξηση ή μείωση της ανάλυσης της εικόνας. InterpolationFilterType = bilinear ή nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το νέο πλάτος της εικόνας. |
| ύψος | int | Το νέο ύψος της εικόνας. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Ανακλιμάκωση εικόνας - αύξηση ή μείωση της ανάλυσης της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το νέο πλάτος της εικόνας. |
| ύψος | int | Το νέο ύψος της εικόνας. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Περιστροφή αρχικής εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Γωνία περιστροφής. Τιμή από -360 έως 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Περιστροφή του τμήματος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | float | Γωνία περιστροφής. Τιμή από -360 έως 360. |
| περιοχή | java.awt.Rectangle | Rectangle για προεπεξεργασία. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Ανακλιμάκωση εικόνας - Αύξηση ή μείωση της ανάλυσης της εικόνας. InterpolationFilterType προεπιλογή bilinear ή nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αναλογία | float | Ο συντελεστής κλιμάκωσης. Συνιστώμενη τιμή από 0.1 έως 1 για συρρίκνωση. Από 1 έως 10 για μεγέθυνση. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Ανακλιμάκωση εικόνας - Αύξηση ή μείωση της ανάλυσης της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αναλογία | float | Ο συντελεστής κλιμάκωσης. Συνιστώμενη τιμή από 0.1 έως 1 για συρρίκνωση. Από 1 έως 10 για μεγέθυνση. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Δημιουργία δυαδικής εικόνας με βάση τον καθορισμό μιας τιμής κατωφλίου στην ένταση των pixel της αρχικής εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η μέγιστη τιμή. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Δημιουργία τμήματος δυαδικής εικόνας με βάση τον καθορισμό μιας τιμής κατωφλίου στην ένταση των pixel του αρχικού τμήματος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η μέγιστη τιμή. |
| περιοχή | java.awt.Rectangle | Rectangle για προεπεξεργασία. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Μετατρέπει μια εικόνα σε εικόνα σε κλίμακα του γκρι. Η εικόνα σε κλίμακα του γκρι έχει 256 επίπεδα φωτός στην εικόνα (0 έως 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Προσθέστε το νέο φίλτρο στη συλλογή για να εκτελεστούν περαιτέρω όλες οι λειτουργίες. Η συνοχή στη συλλογή είναι σημαντική.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Νέα λειτουργία για προσθήκη στη λίστα φίλτρων. |

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
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




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

