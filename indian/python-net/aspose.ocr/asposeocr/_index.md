---
title: "AsposeOcr"
second_title: "Aspose.OCR Python के लिए via .NET API संदर्भ"
description: 
type: docs
weight: 10
url: /hi/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Aspose OCR लाइब्रेरी के लिए मुख्य API

AsposeOcr प्रकार निम्नलिखित सदस्य प्रकट करता है:
## निर्माता
| नाम | विवरण |
| :- | :- |
| AsposeOcr() | नई इंस्टेंस को प्रारंभ करता है [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/) वर्ग की।<br/>            खाली कंस्ट्रक्टर। |
## गुणधर्म
| नाम | विवरण |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## विधियाँ
| नाम | विवरण |
| :- | :- |
| recognize(images) | छवियों / दस्तावेज़ों पर पाठ को पहचानता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, डायरेक्टरी, एरेज़, आर्काइव्स का समर्थन करता है। |
| recognize(images, preset) |  |
| recognize(images, settings) | छवियों / दस्तावेज़ों पर पाठ को पहचानता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, डायरेक्टरी, एरेज़, आर्काइव्स का समर्थन करता है। |
| recognize_receipt(images) | रसीदों पर पाठ को पहचानता है। |
| recognize_receipt(images, settings) | रसीदों पर पाठ को पहचानता है। |
| recognize_invoice(images) | इनवॉइस पर पाठ को पहचानता है। |
| recognize_invoice(images, settings) | इनवॉइस पर पाठ को पहचानता है। |
| recognize_id_card(images) | ID कार्ड पर पाठ को पहचानता है। |
| recognize_id_card(images, settings) | ID कार्ड पर पाठ को पहचानता है। |
| recognize_car_plate(images) | कार प्लेट पर पाठ को पहचानता है। |
| recognize_car_plate(images, settings) | कार प्लेट पर पाठ को पहचानता है। |
| recognize_passport(images) | पासपोर्ट पर पाठ को पहचानता है। |
| recognize_passport(images, settings) | पासपोर्ट पर पाठ को पहचानता है। |
| recognize_lines(images) | एकल पंक्ति वाले पाठ वाली छवियों को पहचानता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, फ़ोल्डर, एरेज़, आर्काइव्स को सपोर्ट करता है। |
| recognize_lines(images, settings) | एकल पंक्ति वाले पाठ वाली छवियों को पहचानता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, फ़ोल्डर, एरेज़, आर्काइव्स को सपोर्ट करता है। |
| detect_rectangles(images) | छवियों में पाठ क्षेत्रों का पता लगाता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, फ़ोल्डर, एरेज़, आर्काइव्स को सपोर्ट करता है। |
| detect_rectangles(images, areas_type, detect_areas) | छवियों में पाठ क्षेत्रों का पता लगाता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, फ़ोल्डर, एरेज़, आर्काइव्स को सपोर्ट करता है। |
| recognize_characters(images) | छवियों में प्रतीकों का पता लगाता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, फ़ोल्डर, एरेज़, आर्काइव्स को सपोर्ट करता है। |
| recognize_characters(images, detect_areas_mode, language) | छवियों में प्रतीकों का पता लगाता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, फ़ोल्डर, एरेज़, आर्काइव्स को सपोर्ट करता है। |
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
| recognize_fast(images) | छवियों / दस्तावेज़ों पर पाठ को पहचानता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, डायरेक्टरी, एरेज़, आर्काइव्स का समर्थन करता है। |
| recognize_handwritten_text(images) | छवियों पर हस्तलिखित पाठ को पहचानता है। |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | छवियों के तिरछे कोणों की गणना करता है।<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, स्ट्रीम, फ़ोल्डर, एरेज़, आर्काइव्स का समर्थन करता है। |
| detect_defects(images, defect_type) | स्वचालित रूप से किसी छवि के समस्याग्रस्त क्षेत्रों को खोजता है जो OCR की सटीकता को काफी प्रभावित कर सकते हैं।<br/>            फ़ाइल, स्ट्रीम, या पिक्सेल एरे के रूप में प्रदान की गई PNG, JPEG, BMP, TIFF, JFIF, और GIF छवियों का समर्थन करता है। बड़े पैमाने पर पहचान का समर्थन करता है। |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | जाँचें कि छवि में प्रदान किया गया पाठ अंश मौजूद है या नहीं। |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | जाँचें कि दो छवियों में समान पाठ है या नहीं। |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | दो छवियों पर मौजूद पाठों की तुलना करें और एक संख्या लौटाएँ जो दर्शाती है कि वे कितने समान हैं (0 से 1)। |
| correct_spelling(text, language, dictionary_path) | पाठ को सुधारता है (गलत वर्तनी वाले शब्दों को बदलता है)। |

### संबंधित देखें

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

