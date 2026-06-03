---
title: "RecognitionResult"
second_title: "Aspose.OCR για Python μέσω .NET Αναφορά API"
description: 
type: docs
weight: 290
url: /el/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

Τα αποτελέσματα της αναγνώρισης εικόνας.<br/>            Περιέχει στοιχεία με πληροφορίες αναγνώρισης και μεθόδους για εξαγωγή αποτελεσμάτων.

Ο τύπος RecognitionResult εκθέτει τα παρακάτω μέλη:


## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| recognition_regions_result | Λαμβάνει μια λίστα αποτελεσμάτων αναγνώρισης με μια λίστα περιοχών (Ορθογώνια). |
| recognition_lines_result | Λαμβάνει μια λίστα αποτελεσμάτων αναγνώρισης με μια λίστα γραμμών (Ορθογώνια). |
| recognition_characters_list | Σύνολο χαρακτήρων που βρέθηκαν από τον αλγόριθμο αναγνώρισης και ταξινομήθηκαν κατά φθίνουσα σειρά πιθανότητας. |
| recognition_text | Λαμβάνει το αποτέλεσμα της αναγνώρισης σε μία συμβολοσειρά. |
| file_name | Πλήρης διαδρομή προς το αρχείο. |
| warnings | Λαμβάνει λίστα των μηνυμάτων προειδοποίησης που περιγράφουν μη κρίσιμα σφάλματα που εμφανίστηκαν κατά τη δημιουργία. |
| serializable_image |  |
## Methods
| Όνομα | Περιγραφή |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Αποθηκεύει το έγγραφο ως απλό κείμενο, PDF ή έγγραφο Microsoft Word. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Αποθηκεύει το έγγραφο ως απλό κείμενο, PDF ή έγγραφο Microsoft Word. |
| save(full_file_name, save_format, optimize_pdf) | Αποθηκεύει το έγγραφο ως απλό κείμενο, PDF ή έγγραφο Microsoft Word. |
| save(stream, save_format, optimize_pdf) | Αποθηκεύει το έγγραφο ως απλό κείμενο, PDF ή έγγραφο Microsoft Word. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Αποθηκεύει το έγγραφο ως απλό κείμενο, PDF ή έγγραφο Microsoft Word. |
| get_spell_check_corrected_text(language, dictionary_path) | Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις). |
| get_spell_check_error_list(language, dictionary_path) | Βρίσκει τις λανθασμένες λέξεις με προτεινόμενες ορθογραφίες για ένα δεδομένο κείμενο εισόδου. |
| get_json(is_readable) | Δημιουργεί συμβολοσειρά JSON με τα αποτελέσματα αναγνώρισης. |
| get_xml() | Δημιουργεί συμβολοσειρά XML με τα αποτελέσματα αναγνώρισης. |
| get_keywords() | Αποκτήστε λέξεις-κλειδιά από διαβατήριο (Λειτουργία δοκιμής. Λειτουργεί μόνο για διαβατήρια ΗΠΑ και Μαδαγασκάρης). |

### Δείτε επίσης

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

