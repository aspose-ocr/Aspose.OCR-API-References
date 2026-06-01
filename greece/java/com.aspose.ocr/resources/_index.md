---
title: "Πόροι"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Διαχειριστείτε τους λήψιμο πόρους που ενισχύουν τις δυνατότητες αναγνώρισης του Aspose.OCR"
type: docs
weight: 32
url: /el/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Διαχειριστείτε πόρους που μπορούν να ληφθούν και ενισχύουν τις δυνατότητες αναγνώρισης του Aspose.OCR.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Resources()](#Resources) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Επιτρέψτε (true) ή αποκλείστε (false) την αυτόματη λήψη των απαιτούμενων πόρων από το διαδικτυακό αποθετήριο. |
| [FetchAll()](#FetchAll) | Κατεβάστε όλους τους συμβατούς πόρους από το διαδικτυακό αποθετήριο. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Κατεβάστε τον πόρο που καθορίζεται στην παράμετρο name από το διαδικτυακό αποθετήριο. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Κατεβάστε τους πόρους που καθορίζονται στην παράμετρο names από το διαδικτυακό αποθετήριο. |
| [GetLocalPath()](#GetLocalPath) | Επιστρέψτε τη πλήρη διαδρομή προς το φάκελο όπου θα ληφθούν οι πόροι. |
| [GetRepository()](#GetRepository) | Επιστρέψτε το URL του διαδικτυακού αποθετηρίου από το οποίο κατεβάζονται οι πόροι Aspose.OCR. |
| [ListLocal()](#ListLocal) | Λίστα όλων των πόρων Aspose.OCR που αποθηκεύονται στον τοπικό φάκελο. |
| [ListRemote()](#ListRemote) | Λίστα όλων των συμβατών πόρων από το διαδικτυακό αποθετήριο. |
| [ReleaseMemory()](#ReleaseMemory) | Αποφορτώστε τα OCR modules για να ελευθερώσετε μνήμη. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Αφαιρεί τον τοπικά αποθηκευμένο πόρο Aspose.OCR. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Καθορίστε απόλυτη ή σχετική διαδρομή προς το φάκελο όπου θα ληφθούν οι πόροι. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Καθορίστε απόλυτη ή σχετική διαδρομή προς το φάκελο όπου θα ληφθούν οι πόροι. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Καθορίστε το URL του διαδικτυακού αποθετηρίου από το οποίο θα ληφθούν οι πόροι Aspose.OCR. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Επιτρέψτε (true) ή αποκλείστε (false) την αυτόματη λήψη των απαιτούμενων πόρων από το διαδικτυακό αποθετήριο. Από προεπιλογή, ένας πόρος λήγεται αυτόματα όταν κληθεί μια μέθοδος που εξαρτάται από αυτό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| επιτρέπεται | java.lang.Boolean | Τιμή Boolean για να επιτρέψετε ή να αποκλείσετε την αυτόματη λήψη των απαιτούμενων πόρων. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Κατεβάστε όλους τους συμβατούς πόρους από το διαδικτυακό αποθετήριο. Τα υπάρχοντα αρχεία πόρων θα αντικατασταθούν.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Κατεβάστε τον πόρο που καθορίζεται στην παράμετρο name από το διαδικτυακό αποθετήριο. Εάν ο πόρος είναι ήδη ληφθεί, θα αντικατασταθεί. Μπορείτε να παραλείψετε την επέκταση .OCR και να χρησιμοποιήσετε μόνο το όνομα αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Συμβολοσειρά με το όνομα του πόρου. Δείτε τη μέθοδο ListRemote. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Κατεβάστε τους πόρους που καθορίζονται στην παράμετρο names από το διαδικτυακό αποθετήριο. Εάν ένας ή περισσότεροι πόροι είναι ήδη ληφθεί, θα αντικατασταθούν. Μπορείτε να παραλείψετε την επέκταση .OCR και να χρησιμοποιήσετε μόνο τα ονόματα αρχείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| names | java.lang.String[] | Πίνακας με τα ονόματα των πόρων. Δείτε τη μέθοδο ListRemote. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Επιστρέψτε τη πλήρη διαδρομή προς το φάκελο όπου θα ληφθούν οι πόροι.

**Returns:**
java.lang.String - Συμβολοσειρά με τη διαδρομή προς το φάκελο των πόρων.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Επιστρέψτε το URL του διαδικτυακού αποθετηρίου από το οποίο κατεβάζονται οι πόροι Aspose.OCR.

**Returns:**
java.lang.String - URL του διαδικτυακού αποθετηρίου.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Λίστα όλων των πόρων Aspose.OCR που αποθηκεύονται στον τοπικό φάκελο.

**Returns:**
java.util.List<java.lang.String> - Λίστα όλων των πόρων Aspose.OCR που αποθηκεύονται στον τοπικό φάκελο.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Λίστα όλων των συμβατών πόρων από το διαδικτυακό αποθετήριο.

**Returns:**
java.util.List<java.lang.String> - Λίστα ονομάτων πόρων.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Αποφορτώστε τις μονάδες OCR για να ελευθερώσετε μνήμη. Τα ληφθέντα αρχεία μονάδων θα παραμείνουν αμετάβλητα.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Αφαιρεί τον τοπικά αποθηκευμένο πόρο Aspose.OCR.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Καθορίστε απόλυτη ή σχετική διαδρομή προς τον φάκελο όπου θα ληφθούν τα αρχεία πόρων. Εάν ο φάκελος δεν υπάρχει, θα δημιουργηθεί αυτόματα. Από προεπιλογή, οι πόροι λήγονται στον φάκελο aspose\_data στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | java.lang.String | Απόλυτη ή σχετική διαδρομή προς τον φάκελο. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Καθορίστε απόλυτη ή σχετική διαδρομή προς τον φάκελο όπου θα ληφθούν τα αρχεία πόρων. Περάστε false στην παράμετρο create για να αποτρέψετε τη δημιουργία του φακέλου αυτόματα. Εάν ο παρεχόμενος φάκελος δεν υπάρχει και η δημιουργία δεν επιτρέπεται, οι πόροι θα φορτωθούν στον φάκελο aspose\_data στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | java.lang.String | Απόλυτη ή σχετική διαδρομή προς τον φάκελο. |
| create | java.lang.Boolean | Παράμετρος για την αποτροπή της αυτόματης δημιουργίας του φακέλου. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Καθορίστε το URL του διαδικτυακού αποθετηρίου από το οποίο θα ληφθούν οι πόροι Aspose.OCR. Από προεπιλογή, οι πόροι λήγονται από https://github.com/aspose-ocr/resources/.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | java.lang.String | URL του διαδικτυακού αποθετηρίου. |


