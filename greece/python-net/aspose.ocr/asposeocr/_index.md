---
title: "AsposeOcr"
second_title: "Aspose.OCR για Python μέσω .NET Αναφορά API"
description: 
type: docs
weight: 10
url: /el/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Κύριο API για τη βιβλιοθήκη Aspose OCR

Ο τύπος AsposeOcr εκθέτει τα παρακάτω μέλη:
## Κατασκευαστές
| Όνομα | Περιγραφή |
| :- | :- |
| AsposeOcr() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/).<br/>            Κενός κατασκευαστής. |
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| Όνομα | Περιγραφή |
| :- | :- |
| recognize(images) | Αναγνωρίζει κείμενο σε εικόνες / έγγραφα.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, ροή, φάκελο, πίνακες, αρχεία. |
| recognize(images, preset) |  |
| recognize(images, settings) | Αναγνωρίζει κείμενο σε εικόνες / έγγραφα.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, ροή, φάκελο, πίνακες, αρχεία. |
| recognize_receipt(images) | Αναγνωρίζει κείμενο σε αποδείξεις. |
| recognize_receipt(images, settings) | Αναγνωρίζει κείμενο σε αποδείξεις. |
| recognize_invoice(images) | Αναγνωρίζει κείμενο σε τιμολόγια. |
| recognize_invoice(images, settings) | Αναγνωρίζει κείμενο σε τιμολόγια. |
| recognize_id_card(images) | Αναγνωρίζει κείμενο στην ταυτότητα. |
| recognize_id_card(images, settings) | Αναγνωρίζει κείμενο στην ταυτότητα. |
| recognize_car_plate(images) | Αναγνωρίζει κείμενο στην πινακίδα κυκλοφορίας. |
| recognize_car_plate(images, settings) | Αναγνωρίζει κείμενο στην πινακίδα κυκλοφορίας. |
| recognize_passport(images) | Αναγνωρίζει κείμενο στο διαβατήριο. |
| recognize_passport(images, settings) | Αναγνωρίζει κείμενο στο διαβατήριο. |
| recognize_lines(images) | Αναγνωρίζει εικόνες που περιέχουν μία γραμμή κειμένου.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| recognize_lines(images, settings) | Αναγνωρίζει εικόνες που περιέχουν μία γραμμή κειμένου.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| detect_rectangles(images) | Εντοπίζει περιοχές κειμένου σε εικόνες.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| detect_rectangles(images, areas_type, detect_areas) | Εντοπίζει περιοχές κειμένου σε εικόνες.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| recognize_characters(images) | Εντοπίζει σύμβολα σε εικόνες.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| recognize_characters(images, detect_areas_mode, language) | Εντοπίζει σύμβολα σε εικόνες.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| save_multipage_document(full_file_name, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results) |  |
| save_multipage_document(stream, save_format, results) |  |
| save_multipage_document(stream, save_format, results, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| recognize_fast(images) | Αναγνωρίζει κείμενο σε εικόνες / έγγραφα.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, ροή, φάκελο, πίνακες, αρχεία. |
| recognize_handwritten_text(images) | Αναγνωρίζει χειρόγραφο κείμενο σε εικόνες. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Υπολογίζει τις γωνίες κλίσης των εικόνων.<br/>            Υποστηρίζει GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, arrays, archives. |
| detect_defects(images, defect_type) | Αυτόματα εντοπίζει προβληματικές περιοχές μιας εικόνας που μπορούν να επηρεάσουν σημαντικά την ακρίβεια του OCR.<br/>            Υποστηρίζει PNG, JPEG, BMP, TIFF, JFIF, και GIF εικόνες που παρέχονται ως αρχείο, stream ή πίνακας pixel. Υποστηρίζει μαζική αναγνώριση. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Ελέγξτε αν η εικόνα περιέχει το παρεχόμενο τμήμα κειμένου. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | Ελέγξτε αν δύο εικόνες περιέχουν το ίδιο κείμενο. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | Συγκρίνετε τα κείμενα στις δύο εικόνες και επιστρέψτε έναν αριθμό που αντιπροσωπεύει πόσο παρόμοια είναι (0 έως 1). |
| correct_spelling(text, language, dictionary_path) | Διορθώνει το κείμενο (αντικαθιστά λανθασμένες λέξεις). |

### Δείτε επίσης

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

