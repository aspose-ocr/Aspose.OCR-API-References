---
title: "RecognitionSettings"
second_title: "Aspose.OCR Python için .NET API Referansı"
description: 
type: docs
weight: 330
url: /tr/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

Görüntü tanıma ayarları.<br/>            Tanıma sürecini özelleştirmeye izin veren öğeleri içerir.

RecognitionSettings türü aşağıdaki üyeleri ortaya çıkar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| RecognitionSettings() | Yeni bir örnek başlatır |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | RecognitionSettings sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | İşleme için iş parçacığı sayısını alır veya ayarlar. |
| language | OCR için kullanılan dili alır veya ayarlar. |
| ignored_symbols | Tanıma sembolleri için kara listeyi ayarlar. |
| allowed_symbols | Alfabe özelliği ile izin verilen karakterleri ayarla. |
| allowed_characters | İzin verilen karakterler kümesi. Tanıma sonucunda izin verilen karakter tipini belirler. |
| automatic_color_inversion | Koyu/siyah arka plan üzerindeki beyaz metinli görüntüleri algılar ve bunlar için otomatik olarak özel bir OCR algoritması seçer. |
| recognition_areas | İşleme için metin alanları listesini alır veya ayarlar. |
| recognize_single_line | Tek satır görüntü tanımasını ayarlar. <br/>            Varsayılan olarak devre dışı (false). <br/>            Satırlara bölme ile ilişkili tüm işleme adımlarını devre dışı bırakır. <br/>            Görüntünüz yalnızca bir satır içeriyorsa bu parametreyi true olarak ayarlayın. RecognitionAreas ayarlarını devre dışı bırakır, bu yüzden tüm alan ayarları göz ardı edilecektir. |
| language_detection_level |  |
| lines_filtration | Tablolardaki (çevresinde çizgiler bulunan bölgeler) metni tanımaya izin verir. |
| detect_areas_mode | Belge türü alanları için optimal modu seçmeye izin verir: belge, fotoğraf, düz metin, sütun, görüntü. |
| upscale_small_font | Küçük font tanıması için özel olarak ek algoritmalar kullanmanıza izin verir.<br/>            Küçük boyutlu karakterlere sahip görüntüler için faydalıdır. |

### Ayrıca Bakınız

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

