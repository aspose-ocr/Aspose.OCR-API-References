---
title: "RecognitionSettings"
second_title: "Αναφορά API του Aspose.OCR για Python μέσω Java"
description: 
type: docs
weight: 191
url: /el/python-java/aspose/recognitionsettings/
---

Μονάδα recognitionsettings
==========================

Κλάσεις
-------

`CarPlateRecognitionSettings()`
:

### Μεταβλητές κλάσης

`JAVA_CLASS_NAME`
:

### Μέθοδοι

`set_allowed_characters(self, allowedCharacters: str)`
:
Ορισμένο σύνολο επιτρεπόμενων χαρακτήρων. Καθορίζει τον πίνακα των χαρακτήρων που επιτρέπονται για το αποτέλεσμα αναγνώρισης.
@param allowedCharacters: περιέχει συμβολοσειρά χαρακτήρων.

`set_ignored_characters(self, ignoredCharacters: str)`
:
Ορίζει τη λίστα αποκλεισμού για σύμβολα αναγνώρισης.
@param ignoredCharacters: Χαρακτήρες που εξαιρούνται από την αναγνώριση.

`set_language(self, language: aspose.models.Language)`
:
Ορίζει τη γλώσσα που χρησιμοποιείται για OCR.
Πολυγλωσσική (καμία) εξ ορισμού.
@param language: περιέχει τιμή enum Language.

`set_threads_count(self, threadsCount: int)`
:
Ανακτά ή ορίζει τον αριθμό των νημάτων για επεξεργασία.
Από προεπιλογή, το 0 σημαίνει ότι η εικόνα θα επεξεργαστεί με αριθμό νημάτων ίσο με τον αριθμό των επεξεργαστών σας.
ThreadsCount = 1 σημαίνει ότι η εικόνα θα επεξεργαστεί στο κύριο νήμα.
@param threadsCount: ο αριθμός των νημάτων που θα δημιουργηθούν για παράλληλη αναγνώριση τμημάτων εικόνας.

`IDCardRecognitionSettings()`
:

### Μεταβλητές κλάσης

`JAVA_CLASS_NAME`
:

### Μέθοδοι

`set_allowed_characters(self, allowedCharacters: str)`
:
Ορισμένο σύνολο επιτρεπόμενων χαρακτήρων. Καθορίζει τον πίνακα των χαρακτήρων που επιτρέπονται για το αποτέλεσμα αναγνώρισης.
@param allowedCharacters: περιέχει συμβολοσειρά χαρακτήρων.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και αυτόματα επιλέγει έναν ειδικό αλγόριθμο OCR για αυτές.
@param automaticColorInversion: περιέχει boolean τιμή - ένα automaticColorInversion έχει οριστεί. True από προεπιλογή.

`set_ignored_characters(self, ignoredCharacters: str)`
:
Ορίζει τη λίστα αποκλεισμού για σύμβολα αναγνώρισης.
@param ignoredCharacters: Χαρακτήρες που εξαιρούνται από την αναγνώριση.

`set_language(self, language: aspose.models.Language)`
:
Ορίζει τη γλώσσα που χρησιμοποιείται για OCR.
Πολυγλωσσική (καμία) εξ ορισμού.
@param language: περιέχει τιμή enum Language.

`set_threads_count(self, threadsCount: int)`
:
Ανακτά ή ορίζει τον αριθμό των νημάτων για επεξεργασία.
Από προεπιλογή, το 0 σημαίνει ότι η εικόνα θα επεξεργαστεί με αριθμό νημάτων ίσο με τον αριθμό των επεξεργαστών σας.
ThreadsCount = 1 σημαίνει ότι η εικόνα θα επεξεργαστεί στο κύριο νήμα.
@param threadsCount: ο αριθμός των νημάτων που θα δημιουργηθούν για παράλληλη αναγνώριση τμημάτων εικόνας.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
Σας επιτρέπει να χρησιμοποιήσετε πρόσθετους αλγόριθμους ειδικά για την αναγνώριση μικρών γραμματοσειρών.
Χρήσιμο για εικόνες με χαρακτήρες μικρού μεγέθους.
@param upscaleSmallFont: περιέχει boolean τιμή - ένα upscaleSmallFont έχει οριστεί.

`InvoiceRecognitionSettings()`
:

### Μεταβλητές κλάσης

`JAVA_CLASS_NAME`
:

### Μέθοδοι

`set_allowed_characters(self, allowedCharacters: str)`
:
Ορισμένο σύνολο επιτρεπόμενων χαρακτήρων. Καθορίζει τον πίνακα των χαρακτήρων που επιτρέπονται για το αποτέλεσμα αναγνώρισης.
@param allowedCharacters: περιέχει συμβολοσειρά χαρακτήρων.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και αυτόματα επιλέγει έναν ειδικό αλγόριθμο OCR για αυτές.
@param automaticColorInversion: περιέχει boolean τιμή - ένα automaticColorInversion έχει οριστεί. True από προεπιλογή.

`set_ignored_characters(self, ignoredCharacters: str)`
:
Ορίζει τη λίστα αποκλεισμού για σύμβολα αναγνώρισης.
@param ignoredCharacters: Χαρακτήρες που εξαιρούνται από την αναγνώριση.

`set_language(self, language: aspose.models.Language)`
:
Ορίζει τη γλώσσα που χρησιμοποιείται για OCR.
Πολυγλωσσική (καμία) εξ ορισμού.
@param language: περιέχει τιμή enum Language.

`set_threads_count(self, threadsCount: int)`
:
Ανακτά ή ορίζει τον αριθμό των νημάτων για επεξεργασία.
Από προεπιλογή, το 0 σημαίνει ότι η εικόνα θα επεξεργαστεί με αριθμό νημάτων ίσο με τον αριθμό των επεξεργαστών σας.
ThreadsCount = 1 σημαίνει ότι η εικόνα θα επεξεργαστεί στο κύριο νήμα.
@param threadsCount: ο αριθμός των νημάτων που θα δημιουργηθούν για παράλληλη αναγνώριση τμημάτων εικόνας.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
Σας επιτρέπει να χρησιμοποιήσετε πρόσθετους αλγόριθμους ειδικά για την αναγνώριση μικρών γραμματοσειρών.
Χρήσιμο για εικόνες με χαρακτήρες μικρού μεγέθους.
@param upscaleSmallFont: περιέχει boolean τιμή - ένα upscaleSmallFont έχει οριστεί.

`PassportRecognitionSettings()`
:

### Μεταβλητές κλάσης

`JAVA_CLASS_NAME`
:

### Μέθοδοι

`set_allowed_characters(self, allowedCharacters: str)`
:
Ορισμένο σύνολο επιτρεπόμενων χαρακτήρων. Καθορίζει τον πίνακα των χαρακτήρων που επιτρέπονται για το αποτέλεσμα αναγνώρισης.
@param allowedCharacters: περιέχει συμβολοσειρά χαρακτήρων.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και αυτόματα επιλέγει έναν ειδικό αλγόριθμο OCR για αυτές.
@param automaticColorInversion: περιέχει boolean τιμή - ένα automaticColorInversion έχει οριστεί. True από προεπιλογή.

`set_ignored_characters(self, ignoredCharacters: str)`
:
Ορίζει τη λίστα αποκλεισμού για σύμβολα αναγνώρισης.
@param ignoredCharacters: Χαρακτήρες που εξαιρούνται από την αναγνώριση.

`set_language(self, language: aspose.models.Language)`
:
Ορίζει τη γλώσσα που χρησιμοποιείται για OCR.
Πολυγλωσσική (καμία) εξ ορισμού.
@param language: περιέχει τιμή enum Language.

`set_threads_count(self, threadsCount: int)`
:
Ανακτά ή ορίζει τον αριθμό των νημάτων για επεξεργασία.
Από προεπιλογή, το 0 σημαίνει ότι η εικόνα θα επεξεργαστεί με αριθμό νημάτων ίσο με τον αριθμό των επεξεργαστών σας.
ThreadsCount = 1 σημαίνει ότι η εικόνα θα επεξεργαστεί στο κύριο νήμα.
@param threadsCount: ο αριθμός των νημάτων που θα δημιουργηθούν για παράλληλη αναγνώριση τμημάτων εικόνας.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
Σας επιτρέπει να χρησιμοποιήσετε πρόσθετους αλγόριθμους ειδικά για την αναγνώριση μικρών γραμματοσειρών.
Χρήσιμο για εικόνες με χαρακτήρες μικρού μεγέθους.
@param upscaleSmallFont: περιέχει boolean τιμή - ένα upscaleSmallFont έχει οριστεί.

`ReceiptRecognitionSettings()`
:

### Μεταβλητές κλάσης

`JAVA_CLASS_NAME`
:

### Μέθοδοι

`set_allowed_characters(self, allowedCharacters: str)`
:
Ορισμένο σύνολο επιτρεπόμενων χαρακτήρων. Καθορίζει τον πίνακα των χαρακτήρων που επιτρέπονται για το αποτέλεσμα αναγνώρισης.
@param allowedCharacters: περιέχει συμβολοσειρά χαρακτήρων.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και αυτόματα επιλέγει έναν ειδικό αλγόριθμο OCR για αυτές.
@param automaticColorInversion: περιέχει boolean τιμή - ένα automaticColorInversion έχει οριστεί. True από προεπιλογή.

`set_ignored_characters(self, ignoredCharacters: str)`
:
Ορίζει τη λίστα αποκλεισμού για σύμβολα αναγνώρισης.
@param ignoredCharacters: Χαρακτήρες που εξαιρούνται από την αναγνώριση.

`set_language(self, language: aspose.models.Language)`
:
Ορίζει τη γλώσσα που χρησιμοποιείται για OCR.
Πολυγλωσσική (καμία) εξ ορισμού.
@param language: περιέχει τιμή enum Language.

`set_threads_count(self, threadsCount: int)`
:
Ανακτά ή ορίζει τον αριθμό των νημάτων για επεξεργασία.
Από προεπιλογή, το 0 σημαίνει ότι η εικόνα θα επεξεργαστεί με αριθμό νημάτων ίσο με τον αριθμό των επεξεργαστών σας.
ThreadsCount = 1 σημαίνει ότι η εικόνα θα επεξεργαστεί στο κύριο νήμα.
@param threadsCount: ο αριθμός των νημάτων που θα δημιουργηθούν για παράλληλη αναγνώριση τμημάτων εικόνας.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
Σας επιτρέπει να χρησιμοποιήσετε πρόσθετους αλγόριθμους ειδικά για την αναγνώριση μικρών γραμματοσειρών.
Χρήσιμο για εικόνες με χαρακτήρες μικρού μεγέθους.
@param upscaleSmallFont: περιέχει boolean τιμή - ένα upscaleSmallFont έχει οριστεί.

`RecognitionSettings()`
:
Ρυθμίσεις για την αναγνώριση εικόνας.
Περιέχει στοιχεία που επιτρέπουν την προσαρμογή της διαδικασίας αναγνώρισης.
    
    
Προεπιλεγμένος κατασκευαστής: set recognitionAreas null, linesFiltration false, autoSkew false, recognizeSingleLine false.

### Μεταβλητές κλάσης

`JAVA_CLASS_NAME`
:

### Μέθοδοι

`set_allowed_characters(self, allowedCharacters: str)`
:
Ορισμένο σύνολο επιτρεπόμενων χαρακτήρων. Καθορίζει τον πίνακα των χαρακτήρων που επιτρέπονται για το αποτέλεσμα αναγνώρισης.
@param allowedCharacters: περιέχει συμβολοσειρά χαρακτήρων.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
Ανιχνεύει εικόνες με λευκό κείμενο σε σκούρο/μαύρο φόντο και αυτόματα επιλέγει έναν ειδικό αλγόριθμο OCR για αυτές.
@param automaticColorInversion: περιέχει boolean τιμή - ένα automaticColorInversion έχει οριστεί. True από προεπιλογή.

`set_detect_areas_mode(self, detectAreasMode: aspose.models.DetectAreasMode)`
:
Καθορίζει τον τύπο του νευρωνικού δικτύου που χρησιμοποιείται για την ανίχνευση περιοχών.
@param detectAreasMode: περιέχει την τιμή του enum DetectAreasMode.

`set_ignored_characters(self, ignoredCharacters: str)`
:
Ορίζει τη λίστα αποκλεισμού για σύμβολα αναγνώρισης.
@param ignoredCharacters: Χαρακτήρες που εξαιρούνται από την αναγνώριση.

`set_language(self, language: aspose.models.Language)`
:
Ορίζει τη γλώσσα που χρησιμοποιείται για OCR.
Πολυγλωσσική (καμία) εξ ορισμού.
@param language: περιέχει τιμή enum Language.

`set_recognize_single_line(self, recognizeSingleLine: bool)`
:
Ορίζει την αναγνώριση εικόνας μονής γραμμής.
Απενεργοποιημένο (false) εξ ορισμού.
Απενεργοποιήστε όλα τα βήματα επεξεργασίας που σχετίζονται με το διαχωρισμό σε γραμμές.
Ορίστε αυτήν την παράμετρο σε true εάν η εικόνα σας περιέχει μόνο μία γραμμή. Απενεργοποιεί τις ρυθμίσεις set_recognition_areas, έτσι όλες οι ρυθμίσεις περιοχών θα αγνοηθούν.
@param recognizeSingleLine: True για εικόνα μονής γραμμής

`set_threads_count(self, threadsCount: int)`
:
Ανακτά ή ορίζει τον αριθμό των νημάτων για επεξεργασία.
Από προεπιλογή, το 0 σημαίνει ότι η εικόνα θα επεξεργαστεί με αριθμό νημάτων ίσο με τον αριθμό των επεξεργαστών σας.
ThreadsCount = 1 σημαίνει ότι η εικόνα θα επεξεργαστεί στο κύριο νήμα.
@param threadsCount: ο αριθμός των νημάτων που θα δημιουργηθούν για παράλληλη αναγνώριση τμημάτων εικόνας.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
Σας επιτρέπει να χρησιμοποιήσετε πρόσθετους αλγόριθμους ειδικά για την αναγνώριση μικρών γραμματοσειρών.
Χρήσιμο για εικόνες με χαρακτήρες μικρού μεγέθους.
@param upscaleSmallFont: περιέχει boolean τιμή - ένα upscaleSmallFont έχει οριστεί.



### Δείτε επίσης

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)