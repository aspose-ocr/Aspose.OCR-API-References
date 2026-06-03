---
title: "OcrInput"
second_title: "Aspose.OCR Python için .NET API Referansı"
description: 
type: docs
weight: 240
url: /tr/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

Ön işleme / tanıma için tüm görüntüleri / belgeleri toplamak amacıyla bir kapsayıcı.

OcrInput türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| OcrInput(type, filters) | OcrInput sınıfının yeni bir örneğini başlatır |
| OcrInput(type) | OcrInput sınıfının yeni bir örneğini başlatır |
## Indexer
| Ad | Açıklama |
| :- | :- |
| [index] | İşlenen / tanınan görüntü hakkında bilgi döndürür. |
## Methods
| Ad | Açıklama |
| :- | :- |
| add(full_path) | Tanıma / işleme için görüntüyü içeren yolu veya URI'yi ekleyin.<br/>            Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir. |
| add(stream) | Tanıma / işleme için görüntüyü içeren bellek akışını ekleyin.<br/>            Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir. |
| add(full_path, start_page, pages_count) | Tanıma / işleme için çok sayfalı görüntüleri / belgeleri ekleyin.<br/>            Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir. |
| add(stream, start_page, pages_count) | Tanıma / işleme için çok sayfalı görüntüyü içeren bellek akışını ekleyin.<br/>            Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir. |
| add(arr, width, height, pixel_format) | Çözülmüş görüntüyü tanıma / işleme listesine ekleyin.<br/>            Görüntünün türü, yapıcıda belirtilen türe (SingleImage) uygun olmalıdır. |
| replace_filters(filters) | Eski filtreleri kaldırın ve yenilerini ayarlayın. |
| clear_filters() | Tüm filtreleri kaldırın. |
| add_base64(base64) | Tanıma / işleme için görüntüyü içeren base64 dizesini ekleyin.<br/>            Görüntünün türü, yapıcıda belirtilen türe uygun olmalıdır. |
| clear() | Tüm filtreleri kaldırın. |
| count() | İşleme / tanıma için öğe sayısı. |
| get_input_type() | Tanıma için izin verilen görüntü türleri. |

### Ayrıca Bakınız

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

