---
title: "RecognitionResult"
second_title: "Aspose.OCR Python के लिए via .NET API संदर्भ"
description: 
type: docs
weight: 290
url: /hi/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

छवि पहचान के परिणाम।<br/>            पहचान जानकारी और परिणाम निर्यात के लिए विधियों वाले तत्व शामिल हैं।

RecognitionResult प्रकार निम्नलिखित सदस्यों को उजागर करता है:


## गुणधर्म
| नाम | विवरण |
| :- | :- |
| recognition_regions_result | पहचान परिणामों की सूची को क्षेत्रों (आयत) की सूची के साथ प्राप्त करता है। |
| recognition_lines_result | पहचान परिणामों की सूची को पंक्तियों (आयतों) की सूची के साथ प्राप्त करता है। |
| recognition_characters_list | पहचान एल्गोरिदम द्वारा पाए गए अक्षरों का एक सेट, जिसे संभावना के घटते क्रम में व्यवस्थित किया गया है। |
| recognition_text | पहचान परिणाम को एक स्ट्रिंग में प्राप्त करता है। |
| file_name | फ़ाइल का पूर्ण पथ। |
| warnings | जनरेशन के दौरान उत्पन्न हुए गैर-आलोचनात्मक त्रुटियों का वर्णन करने वाले चेतावनी संदेशों की सूची प्राप्त करता है। |
| serializable_image |  |
## विधियाँ
| नाम | विवरण |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | दस्तावेज़ को साधारण टेक्स्ट, PDF या Microsoft Word दस्तावेज़ के रूप में सहेजता है। |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | दस्तावेज़ को साधारण टेक्स्ट, PDF या Microsoft Word दस्तावेज़ के रूप में सहेजता है। |
| save(full_file_name, save_format, optimize_pdf) | दस्तावेज़ को साधारण टेक्स्ट, PDF या Microsoft Word दस्तावेज़ के रूप में सहेजता है। |
| save(stream, save_format, optimize_pdf) | दस्तावेज़ को साधारण टेक्स्ट, PDF या Microsoft Word दस्तावेज़ के रूप में सहेजता है। |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | दस्तावेज़ को साधारण टेक्स्ट, PDF या Microsoft Word दस्तावेज़ के रूप में सहेजता है। |
| get_spell_check_corrected_text(language, dictionary_path) | पाठ को सुधारता है (गलत वर्तनी वाले शब्दों को बदलता है)। |
| get_spell_check_error_list(language, dictionary_path) | दिए गए इनपुट टेक्स्ट के लिए सुझाए गए वर्तनी के साथ गलत लिखे शब्दों को खोजें। |
| get_json(is_readable) | पहचान परिणामों के साथ JSON स्ट्रिंग बनाएं। |
| get_xml() | पहचान परिणामों के साथ XML स्ट्रिंग बनाएं। |
| get_keywords() | पासपोर्ट से कीवर्ड प्राप्त करें (टेस्ट मोड। केवल USA और MADAGASCAR पासपोर्ट के लिए काम करता है)। |

### संबंधित देखें

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

