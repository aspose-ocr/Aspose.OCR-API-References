---
title: "DefectOutput"
second_title: "Αναφορά API του Aspose.OCR για Java"
description: "Περιοχές που περιέχουν ελαττώματα που εντοπίστηκαν στην εικόνα"
type: docs
weight: 16
url: /el/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

Περιοχές που περιέχουν ελαττώματα που εντοπίστηκαν στην εικόνα.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Page](#Page) | Αριθμός σελίδας. |
| [Source](#Source) | Η πλήρης διαδρομή προς το αρχείο ή το URL, εάν υπάρχει. |
| [defectAreas](#defectAreas) | Η λίστα των ελαττωμάτων εικόνας και των περιοχών όπου βρέθηκαν. |


### Page {#Page}
```
public int Page
```


Αριθμός σελίδας.

### Source {#Source}
```
public String Source
```


Η πλήρης διαδρομή προς το αρχείο ή το URL, εάν υπάρχει. Κενό για ροές, πίνακες byte και αρχεία κωδικοποιημένα σε Base64.

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


Η λίστα των ελαττωμάτων εικόνας και των περιοχών όπου βρέθηκαν.
