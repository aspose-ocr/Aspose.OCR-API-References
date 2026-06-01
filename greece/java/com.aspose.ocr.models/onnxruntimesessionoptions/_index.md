---
title: "OnnxRuntimeSessionOptions"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Επιλογές διαμόρφωσης για τη δημιουργία του ONNX InferenceSession"
type: docs
weight: 20
url: /el/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

Επιλογές διαμόρφωσης για τη δημιουργία του ONNX InferenceSession. Συνιστούμε να διατηρείτε τις βελτιστοποιημένες προεπιλογές, εκτός εάν είστε απολύτως βέβαιοι για τις τροποποιήσεις. Για τεχνικές λεπτομέρειες, ανατρέξτε στην τεκμηρίωση του ONNX Runtime.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | Ενεργοποιεί ή απενεργοποιεί τον κατανεμητή μνήμης arena CPU που χρησιμοποιείται από το ONNX Runtime. |
| [enableMemoryPattern](#enableMemoryPattern) | Ενεργοποιεί ή απενεργοποιεί τη βελτιστοποίηση προτύπου μνήμης για τα εισαγώμενα τανυστές. |
| [executionMode](#executionMode) | Λειτουργία εκτέλεσης για τη συνεδρία. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Επίπεδο βελτιστοποίησης γραφήματος για τη συνεδρία. |
| [interOpNumThreads](#interOpNumThreads) | Αριθμός νημάτων για την εκτέλεση πολλαπλών λειτουργιών παράλληλα. |
| [intraOpNumThreads](#intraOpNumThreads) | Αριθμός νημάτων για μία ενιαία λειτουργία. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


Ενεργοποιεί ή απενεργοποιεί τον κατανεμητή μνήμης arena CPU που χρησιμοποιείται από το ONNX Runtime. Όταν είναι ενεργοποιημένος, η μνήμη συγκεντρώνεται και επαναχρησιμοποιείται για καλύτερη απόδοση, αλλά μπορεί να οδηγήσει σε αυξημένη κατανάλωση μνήμης σε σενάρια πολλαπλών νημάτων. Απενεργοποιήστε το για να μειώσετε τη μέγιστη χρήση μνήμης με κόστος την απόδοση.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Ενεργοποιεί ή απενεργοποιεί τη βελτιστοποίηση προτύπου μνήμης για τα εισαγώμενα τανυστές. Όταν είναι ενεργοποιημένο, το ONNX Runtime αποθηκεύει στην κρυφή μνήμη πρότυπα κατανομής μνήμης για ταχύτερη εκτέλεση, αλλά μπορεί να αυξήσει τη χρήση μνήμης για δυναμικά σχήματα εισόδου. Απενεργοποιήστε το εάν οι εισροές διαφέρουν σημαντικά ή για μείωση του αποτυπώματος μνήμης.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Λειτουργία εκτέλεσης για τη συνεδρία. Από προεπιλογή, οι τελεστές εκτελούνται ταυτόχρονα, όποτε είναι δυνατόν.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Επίπεδο βελτιστοποίησης γραφήματος για τη συνεδρία. Από προεπιλογή, όλες οι διαθέσιμες βελτιστοποιήσεις είναι ενεργοποιημένες για μέγιστη απόδοση.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Αριθμός νημάτων για την εκτέλεση πολλαπλών λειτουργιών παράλληλα. Εάν η διαδοχική εκτέλεση είναι ενεργοποιημένη, αυτή η τιμή αγνοείται.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Αριθμός νημάτων για μία ενιαία λειτουργία.