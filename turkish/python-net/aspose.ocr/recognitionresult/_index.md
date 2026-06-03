---
title: "RecognitionResult"
second_title: "Aspose.OCR Python için .NET API Referansı"
description: 
type: docs
weight: 290
url: /tr/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

Görüntü tanıma sonuçları.<br/>            Tanıma bilgileri ve sonuç dışa aktarma yöntemleri içeren öğeler içerir.

RecognitionResult türü aşağıdaki üyeleri sunar:


## Özellikler
| Ad | Açıklama |
| :- | :- |
| recognition_regions_result | Bölgeler (Dikdörtgenler) listesiyle birlikte tanıma sonuçlarının bir listesini alır. |
| recognition_lines_result | Tanıma sonuçlarının bir listesini, satırların (Dikdörtgenler) bir listesiyle alır. |
| recognition_characters_list | Tanıma algoritması tarafından bulunan ve olasılık sırasına göre azalan şekilde düzenlenmiş bir karakter kümesi. |
| recognition_text | Tanıma sonucunu tek bir dize olarak alır. |
| file_name | Dosyanın tam yolu. |
| warnings | Oluşturma sırasında ortaya çıkan kritik olmayan hataları tanımlayan uyarı mesajlarının listesini alır. |
| serializable_image |  |
## Methods
| Ad | Açıklama |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Belgeyi düz metin, PDF veya Microsoft Word Belgesi olarak kaydeder. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Belgeyi düz metin, PDF veya Microsoft Word Belgesi olarak kaydeder. |
| save(full_file_name, save_format, optimize_pdf) | Belgeyi düz metin, PDF veya Microsoft Word Belgesi olarak kaydeder. |
| save(stream, save_format, optimize_pdf) | Belgeyi düz metin, PDF veya Microsoft Word Belgesi olarak kaydeder. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Belgeyi düz metin, PDF veya Microsoft Word Belgesi olarak kaydeder. |
| get_spell_check_corrected_text(language, dictionary_path) | Metni düzeltir (yanlış yazılmış kelimeleri değiştirir). |
| get_spell_check_error_list(language, dictionary_path) | Verilen giriş metni için önerilen yazım düzeltmeleriyle hatalı yazılmış kelimeleri bulun. |
| get_json(is_readable) | Tanıma sonuçlarıyla JSON dizesi oluştur. |
| get_xml() | Tanıma sonuçlarıyla XML dizesi oluştur. |
| get_keywords() | Pasaporttan anahtar kelimeleri al (Test modu. Yalnızca ABD ve MADAGASKAR pasaportları için çalışır). |

### Ayrıca Bakınız

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

