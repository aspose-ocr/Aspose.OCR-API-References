---
title: "AsposeOcr"
second_title: "Αναφορά API του Aspose.OCR για Python μέσω Java"
description: 
type: docs
weight: 11
url: /el/python-java/aspose/asposeocr/
---


Μονάδα asposeocr
================
Διεπαφή Python για το Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
ενώ εύχρηστη η οπτική αναγνώριση χαρακτήρων (OCR)
μηχανή για τις εφαρμογές Python και τα σημειωματάρια σας.
Σε λιγότερες από **10** γραμμές κώδικα, μπορείτε να αναγνωρίσετε
κείμενο σε **28** γλώσσες βασισμένες σε Λατινικό, Κυριλλικό,
και ασιατικά σενάρια, επιστρέφοντας αποτελέσματα στις πιο δημοφιλείς
μορφές εγγράφων και ανταλλαγής δεδομένων.
Δεν χρειάζεται να μάθετε πολύπλοκα μαθηματικά μοντέλα,
να δημιουργήσετε αλγόριθμους μηχανικής μάθησης και να εκπαιδεύσετε νευρωνικά
δίκτυα — το απλό και ανθεκτικό API μας θα κάνει τα πάντα για εσάς.

Κλάσεις
-------

`AsposeOcr()`
:
Κύρια κλάση AsposeOcr για αναγνώριση.
    
Αυτό το παράδειγμα δείχνει πώς να αναγνωρίσετε εικόνα.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Στατικές μέθοδοι

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
Επιτρέπει τη λήψη πολυσέλιδου εγγράφου από λίστα αντικειμένων RecognitionResult.
@param fullFileName: Όνομα αρχείου με διαδρομή για αποθήκευση του αποτελέσματος αναγνώρισης στην επιλεγμένη μορφή.
@param saveFormat: Μορφή εγγράφου (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Μέθοδοι

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Υπολογίζει τις γωνίες κλίσης μιας εικόνας.
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance. Ο container με τις πηγές.
@return: Λίστα γωνιών κλίσης σε μοίρες - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Ελέγχει εάν δύο εικόνες περιέχουν το ίδιο κείμενο.
@param fullPath1: Διαδρομή προς την πρώτη εικόνα.
@param fullPath2: Διαδρομή προς τη δεύτερη εικόνα.
@param settings: Ρυθμίσεις αναγνώρισης.
@param ignoreCase: True - σημαίνει αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων.
@return: True εάν οι εικόνες έχουν το ίδιο κείμενο (90% ομοιότητα).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις).
@param text: Κείμενο για διόρθωση.
@param language: Λεξικό προς χρήση SpellCheckLanguage.
@return: Κείμενο με αντικατεστημένες λέξεις.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Ανιχνεύει περιοχές κειμένου σε εικόνες.
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param areasType: Καθορίζει ποια ορθογώνια να επιστραφούν - γραμμή, παραγράφους ή λέξεις.
@param isDetectAreas: Ενεργοποιεί την αυτόματη ανίχνευση περιοχών κειμένου.
@return: Λίστα RectangleOutput με τις ανιχνευμένες περιοχές κειμένου ή γραμμές.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Ελέγχει εάν η εικόνα περιέχει το παρεχόμενο τμήμα κείμενου.
@param fullPath: Διαδρομή προς την εικόνα.
@param text: Απόσπασμα κειμένου για αναζήτηση στην εικόνα.
@param settings: Ρυθμίσεις αναγνώρισης.
@param ignoreCase: True - σημαίνει αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων.
@return: True αν η εικόνα περιέχει το απόσπασμα κειμένου. False - η εικόνα δεν περιέχει το απόσπασμα κειμένου.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
Συγκρίνετε τα κείμενα στις δύο εικόνες και επιστρέψτε έναν αριθμό που αντιπροσωπεύει πόσο παρόμοια είναι (0 έως 1).
@param fullPath1: Διαδρομή προς την πρώτη εικόνα.
@param fullPath2: Διαδρομή προς τη δεύτερη εικόνα.
@param settings: Ρυθμίσεις αναγνώρισης.
@param ignoreCase: True - σημαίνει αναζήτηση χωρίς διάκριση πεζών-κεφαλαίων.
@return: 0 σημαίνει ότι τα κείμενα είναι εντελώς διαφορετικά· 1 σημαίνει ότι τα κείμενα είναι πανομοιότυπα.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Αναγνωρίζει την εικόνα με τη δυνατότητα να καθορίσετε το RecognitionSettings.
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: αντικείμενο RecognitionSettings.
@return: λίστα RecognitionResult με τα αποτελέσματα αναγνώρισης εικόνων.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Αναγνωρίζει πινακίδα αυτοκινήτου με τη δυνατότητα να καθορίσετε το CarPlateRecognitionSettings.
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: CarPlateRecognitionSettings
@return: λίστα RecognitionResult με τα αποτελέσματα αναγνώρισης εικόνων.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Αναγνωρίζει κείμενο σε εικόνα καλής ποιότητας. Δεν χρησιμοποιεί αυτόματη διόρθωση κλίσης εικόνας και περιοχές κειμένου
ανίχνευση.
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@return: λίστα RecognitionResult με τα αποτελέσματα αναγνώρισης εικόνων.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Αναγνωρίζει ταυτότητα με τη δυνατότητα να καθορίσετε το IDCardRecognitionSettings.
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: IDCardRecognitionSettings
@return: λίστα RecognitionResult με τα αποτελέσματα αναγνώρισης εικόνων.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Αναγνωρίζει τιμολόγιο με τη δυνατότητα να καθορίσετε το InvoiceRecognitionSettings
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: InvoiceRecognitionSettings
@return: λίστα RecognitionResult με τα αποτελέσματα αναγνώρισης εικόνων.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Αναγνωρίζει εικόνα μονής γραμμής με τη δυνατότητα να καθορίσετε το RecognitionSettings.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: αντικείμενο RecognitionSettings.
@return: λίστα RecognitionResult με τα αποτελέσματα αναγνώρισης εικόνων.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Αναγνωρίζει διαβατήριο με τη δυνατότητα να καθορίσετε το PassportRecognitionSettings.
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: PassportRecognitionSettings
@return: λίστα RecognitionResult με τα αποτελέσματα αναγνώρισης εικόνων.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Αναγνωρίστε αποδείξεις με τη δυνατότητα να καθορίσετε το ReceiptRecognitionSettings.
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: ReceiptRecognitionSettings
@return: λίστα RecognitionResult με τα αποτελέσματα αναγνώρισης εικόνων.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Αναγνωρίζει κείμενο σε φωτογραφίες δρόμου.
Εξάγετε κείμενο από φωτογραφίες δρόμου, εικόνες κυκλοφοριακών καμερών, ταυτότητες, διπλώματα οδήγησης και άλλες εικόνες με αραιό κείμενο και θορυβώδη/χρωματιστά φόντα.
Υποστηρίζει GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, δυαδικό πίνακα, φάκελο, πίνακα, αρχείο zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@return: λίστα RecognitionResult με τα αποτελέσματα αναγνώρισης εικόνων.

`shutdown(self)`
:
Τερματίστε τη μηχανή JVM.

`ImageProcessing()`
:
Βοηθητική κλάση για τη βιβλιοθήκη Aspose OCR. Επιτρέπει την προεπεξεργασία και αποθήκευση εικόνων.

### Στατικές μέθοδοι

`save(images, folderPath)`
:
Χρησιμοποιήστε την επεξεργασία εικόνας για να βελτιώσετε την ακρίβεια του OCR.
Δημιουργήστε μια λίστα φίλτρων που θα εφαρμοστούν στην εικόνα εισόδου με τη σειρά που καθορίζετε.
\code
filters = new PreprocessingFilter();
filters.add(PreprocessingFilter.auto_dewarping());
filters.add(PreprocessingFilter.invert());
filters.add(PreprocessingFilter.threshold(150));
filters.add(PreprocessingFilter.binarize());
filters.add(PreprocessingFilter.rotate(180));
filters.add(PreprocessingFilter.scale(6));
filters.add(PreprocessingFilter.dilate());
        
images = OcrInput(InputType.PDF, filters);
\endcode
Δεν χρειάζεστε όλα αυτά. Ορίστε μόνο ό,τι χρειάζεστε.
@param images: OcrInput αντικείμενο που περιέχει διαφορετικές εικόνες OcrInput.
@param folderPath: Διαδρομή χωρίς ονόματα εικόνων για αποθήκευση επεξεργασμένων εικόνων.
@return: OcrInput αντικείμενο που περιέχει τα αποτελέσματα των επεξεργασμένων εικόνων OcrInput.


### Δείτε επίσης

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)