---
title: "ImageProcessing"
second_title: "Aspose.OCR για Python μέσω .NET Αναφορά API"
description: 
type: docs
weight: 120
url: /el/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Βοηθητική κλάση για τη βιβλιοθήκη Aspose OCR. Επιτρέπει την προεπεξεργασία και αποθήκευση εικόνων.

Ο τύπος ImageProcessing εκθέτει τα παρακάτω μέλη:
## Methods
| Όνομα | Περιγραφή |
| :- | :- |
| save(images, folder_path) | Χρησιμοποιήστε επεξεργασία εικόνας για να βελτιώσετε την ακρίβεια του OCR.<br/>            Δημιουργήστε μια λίστα φίλτρων που θα εφαρμοστούν στην εικόνα εισόδου με τη σειρά που καθορίζετε.<br/>            Παράδειγμα δημιουργίας φίλτρων:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Δεν χρειάζεστε όλα. Ορίστε μόνο ό,τι χρειάζεστε. |
| render(images) | Χρησιμοποιήστε επεξεργασία εικόνας για να βελτιώσετε την ακρίβεια του OCR.<br/>            Δημιουργήστε μια λίστα φίλτρων που θα εφαρμοστούν στην εικόνα εισόδου με τη σειρά που καθορίζετε.<br/>            παράδειγμα δημιουργίας φίλτρων:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Δεν χρειάζεστε όλα. Ορίστε μόνο ό,τι χρειάζεστε. |

### Δείτε επίσης

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

