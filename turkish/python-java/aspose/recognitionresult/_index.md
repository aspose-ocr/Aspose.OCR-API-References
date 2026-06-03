---
title: "RecognitionResult"
second_title: "Python için Java üzerinden Aspose.OCR API Referansı"
description: 
type: docs
weight: 171
url: /tr/python-java/aspose/recognitionresult/
---

Modül recognitionresult
========================

Sınıflar
-------

`LinesResult(javaClass)`
:

### Atalar (MRO içinde)

    * aspose.helper.BaseJavaClass

### Yöntemler

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
Görüntü tanımasının sonuçları. Tanıma içeren öğeler içerir.
sonuç dışa aktarımı için bilgi ve yöntemler.

### Statik yöntemler

`save_multipage_document(self, fullPath: str)`
:
Özel

### Örnek değişkenleri

`recognition_areas_text`
:   Alanların (Dikdörtgenlerin) bir listesinin tanıma sonuçları listesi.

`recognition_lines_result`
:   Satırların (Dikdörtgenlerin) bir listesini içeren tanıma sonuçları listesini alır.

### Yöntemler

`getJavaClass(self)`
:

`get_json(self)`
:
Tanıma sonuçlarıyla JSON dizesi oluştur.
@return: Tanıma sonuçları JSON dizesi olarak.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Metni düzeltir (yanlış yazılmış kelimeleri değiştirir).
@param language: Kullanılacak sözlük.
@return: Düzeltildi tanıma sonuçları dizesi.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Verilen giriş metni için önerilen yazım düzeltmeleriyle hatalı kelimeleri bulun.
@param language: Kullanılacak sözlük.
@return: Her hatalı kelime için önerilen doğru yazımları içeren listelerle hatalı kelimeleri temsil eden SpellCheckError nesnelerinin listesi,
ve düzenleme mesafesiyle.

`get_xml(self)`
:
Tanıma sonuçlarıyla JSON dizesi oluştur.
@return: Tanıma sonuçları XML dizesi olarak.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Belgeyi düz metin veya diğer belge formatında kaydeder.
@param fullFileName: Tanıma sonucunu kaydetmek için yol içeren dosya adı.
@param format: Format enum tipindeki belge formatı.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Metni düzeltir (yanlış yazılmış kelimeleri değiştirir).
Düzeltildi metni belge içinde düz metin veya diğer formatta kaydeder.
@param fullFileName: Tanıma sonucunu kaydetmek için yol içeren dosya adı
@param format: Format enum tipindeki belge formatı.
@param language: Yazım denetimi için sözlük.

`use_user_dictionary(self, dictionaryPath: str)`
:
Yazım denetimi düzeltmesi için kendi sözlüğünüzü kullanmanıza izin verir.
@param dictionaryPath: Kullanıcı sözlüğünün (frekans sözlüğü) tam yolu.
Sözlük dosya formatı:
UTF-8 kodlamalı düz metin dosyası.
Kelime ve kelime frekansı virgülle ayrılır, kelime ilk sütunda, frekans ikinci sütunda beklenir.
Her kelime-frekans çifti ayrı bir satırda. Bir satır, karakter dizisinin satır beslemesi ("
") , bir taşıma dönüşü ("
"),
veya satır başı karakteri hemen ardından gelen satır beslemesi("

").
Her kelimenin küçük harfle olması beklenir.
Örnek:
\code
word,5984819
hello,5761742
down,5582768
\endcode

`RectangleOutput(javaClass)`
:
Algılanan metin alanları veya satırlar hakkında veri.
\code
source - Dosyanın veya URL'nin tam yolu, eğer varsa. Akışlar, bayt dizileri, base64 için boş bırakılabilir.
page - Sayfa numarası.
image_index - Sayfadaki görüntünün sıra numarası.
rectangles - Algılanan metin alanları veya satırların listesi.
\endcode

### Atalar (MRO içinde)

    * aspose.helper.BaseJavaClass

### Yöntemler

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Derece cinsinden eğim açısı ve dosya adı hakkında veri.
\code
source - Dosyanın veya URL'nin tam yolu, eğer varsa. Akışlar, bayt dizileri, base64 için boş bırakılabilir.
page - Sayfa numarası.
image_index - Sayfadaki görüntünün sıra numarası.
angle - Sapma açısı derece cinsinden.
\endcode

### Atalar (MRO içinde)

    * aspose.helper.BaseJavaClass

### Yöntemler

`initParams(self)`
:


### Ayrıca Bakınız

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)