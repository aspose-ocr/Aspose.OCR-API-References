---
title: "modeller"
second_title: "Python için Java üzerinden Aspose.OCR API Referansı"
description: 
type: docs
weight: 271
url: /tr/python-java/aspose/models/
---

Modül modelleri
=============

Sınıflar
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Model tarafından algılanan bölgelerin türünü belirler.
get_text_areas içinde hangi sonucun elde edileceğini göstermek için kullanılır - paragraf koordinatları veya satır koordinatları.

### Atalar (MRO içinde)

    * enum.Enum

### Sınıf değişkenleri

`LINES`
:   Bölgeleri satır olarak ayarlar

`PARAGRAPHS`
:   Bölgeleri paragraf olarak ayarlar

`WORDS`
:   Bölgeleri kelime olarak ayarlar

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Alan algılamada kullanılan sinir ağının türünü belirler.
RecognitionSettings içinde tanımak istediğiniz görüntü türünü belirtmek için kullanılır.

### Atalar (MRO içinde)

    * enum.Enum

### Sınıf değişkenleri

`COMBINE`
:   Metin içeren paragrafları algılar ve ardından diğer bir NN modeli kullanarak paragrafların içindeki alanları tespit eder.
Karmaşık yapıya sahip görüntüler için daha iyidir.

`CURVED_TEXT`
:   Eğri görüntülerde satırları algılar ve metni tanır.
Kitap ve dergi sayfalarının fotoğrafları için tercih edilen mod.

`DOCUMENT`
:   Paragrafları algılar ve belgeler için NN modeli kullanır.
Çok sütunlu belge, resimli belge veya metin olmayan diğer nesneler içeren belgeler için daha iyidir.

`NONE`
:   Paragrafları algılamaz.
Resimsiz basit tek sütunlu bir belge için daha iyidir.

`PHOTO`
:   Fotoğraflar için paragrafları algılar ve NN modeli kullanır.
Birçok resim ve metin olmayan diğer nesneler içeren görüntüler için daha iyidir.

`TABLE`
:   Metin içeren hücreleri algılar.
Tablo yapısına sahip görüntüler için tercih edilen mod.

`TEXT_IN_WILD`
:   Sokak fotoğrafları, plaka fotoğrafları, pasaport fotoğrafları, sayaç fotoğrafları ve gürültülü arka planlı fotoğraflar gibi düşük kaliteli görüntülerden kelimeleri çıkarmada uzmanlaşmış süper güçlü bir sinir ağı.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Tanıma sonucunu belge olarak kaydetmek için biçim.

### Atalar (MRO içinde)

    * enum.Enum

### Sınıf değişkenleri

`DOCX`
:   Sonucu Office Open XML Word işleme ML Belgesi (makrosuz) olarak kaydeder.

`EPUB`
:   Belgeyi EPUB dosyası olarak kaydeder.

`HTML`
:   Belgeyi HTML dosyası olarak kaydeder.

`JSON`
:   Sonucu JavaScript nesne gösterimiyle yazılmış düz metin olarak kaydeder.

`PDF`
:   Sonucu PDF (Adobe Portable Document) belgesi olarak kaydeder.

`PDF_NO_IMG`
:   Belgeyi görüntü olmadan Aranabilir PDF (Adobe Portable Document) belgesi olarak kaydeder.

`RTF`
:   Belgeyi rtf dosyası olarak kaydeder.

`TEXT`
:   Sonucu düz metin formatında kaydeder.

`XLSX`
:   Sonucu Excel (2007 ve sonrası) çalışma kitabı belgesi olarak kaydeder.

`XML`
:   Sonucu XML belgesi olarak kaydeder.

`ImageData(javaClass)`
:

### Atalar (MRO içinde)

    * aspose.helper.BaseJavaClass

### Yöntemler

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   İşleme / tanıma için görüntü/ belgeler türleri.

### Atalar (MRO içinde)

    * enum.Enum

### Sınıf değişkenleri

`BASE64`
:   Görüntü içeren base64 dizesi veya base64 içeriğine sahip .txt dosyasının yolu. GIF, PNG, JPEG, BMP, TIFF desteklenir.

`DIRECTORY`
:   Dizin yolu. İç içe arşivler ve klasörler desteklenmez.
GIF, PNG, JPEG, BMP, TIFF desteklenir.
İşlenen görüntülerin varsayılan sayısı tümüdür.

`PDF`
:   Dosyadan veya ikili dizi üzerinden taranmış PDF belgesi.

`SINGLE_IMAGE`
:   GIF, PNG, JPEG, BMP, TIFF, JFIF ve ikili dizi desteklenir.

`TIFF`
:   Dosyadan veya InputStream üzerinden çok sayfalı TIFF, TIF belgesi.

`URL`
:   Görüntü üzerindeki bağlantı. GIF, PNG, JPEG, BMP, TIFF desteklenir.

`ZIP`
:   ZIP arşivinin tam adı. İç içe arşivler ve klasörler desteklenmez.
GIF, PNG, JPEG, BMP, TIFF, JFIF desteklenir.
İşlenen görüntülerin varsayılan sayısı tümüdür.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Tanıma için dil modeli.

### Atalar (MRO içinde)

    * enum.Enum

### Sınıf değişkenleri

`BEL`
:   Beyaz Rus alfabesi

`BUL`
:   Bulgar alfabesi

`CHI`
:   Çince alfabe

`CYRILLIC`
:   Çok dilli (Kiril alfabesi) desteği

`CZE`
:   Çek alfabesi

`DAN`
:   Danimarka alfabesi

`DEU`
:   Alman alfabesi

`DUM`
:   Hollandaca alfabesi

`ENG`
:   İngiliz alfabesi

`EST`
:   Estonca alfabesi

`FIN`
:   Fince alfabesi

`FRA`
:   Fransız alfabesi

`HIN`
:   Hint alfabesi

`ITA`
:   İtalyan alfabesi

`KAZ`
:   Kazak alfabesi

`LATIN`
:   Çok dilli (latin alfabesi) desteği

`LAV`
:   Leton alfabesi

`LIT`
:   Litvanya alfabesi

`NONE`
:   Çok dilli destek

`NOR`
:   Norveç alfabesi

`POL`
:   Polonya alfabesi

`POR`
:   Portekiz alfabesi

`RUM`
:   Rumence alfabesi

`RUS`
:   Rus alfabesi

`SLK`
:   Slovak alfabesi

`SLV`
:   Slovence alfabesi

`SPA`
:   İspanyol alfabesi

`SRP`
:   Sırp alfabesi

`SRP_HRV`
:   Sırp-Hırvatça alfabesi

`SWE`
:   İsveç alfabesi

`UKR`
:   Ukraynaca alfabesi

`ModelsConverter()`
:

### Yöntemler

`convertInputTypeToJava(jType)`
:

`convertToJavaAreasMode(jType)`
:

`convertToJavaAreasType(jType)`
:

`convertToJavaFormat(jType)`
:

`convertToJavaLanguage(jType)`
:

`convertToJavaSpellCheckLanguage(jType)`
:

`OcrInput(type: models.InputType, filters: models.PreprocessingFilter = None)`
:   Görüntüleri toplamak için ana sınıf.
    
Konteyner oluşturmak ve görüntü / belge türünü ve daha sonraki işleme / tanıma için filtreleri ayarlamak için yapıcı.
@param type: Konteynere eklenecek görüntü/belge türünü ayarlar.
@param filters: Daha sonraki işleme veya tanıma uygulanacak işleme filtrelerini ayarlar.

### Yöntemler

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   Tanıma / işleme için görüntüyü içeren yolu veya URI'yi ekle.
Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir.
@param fullPath: Görüntü/ belge / klasör / arşiv yolu.
@param startPage: İşleme / tanıma için ilk sayfa/görüntü. Belgeler, zip, klasörler için kullanın.
@param pagesNumber: İşleme / tanıma için toplam sayfa/görüntü sayısı. Belgeler, zip, klasörler için kullanın. Varsayılan = tümü.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   Tanıma / işleme için görüntüyü içeren InputStream'i ekle.
Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: görüntüyü veya belgeyi içeren.
@param startPage: İşleme / tanıma için ilk sayfa/görüntü. Belgeler, zip, klasörler için kullanın.
@param pagesNumber: İşleme / tanıma için toplam sayfa/görüntü sayısı. Belgeler, zip, klasörler için kullanın. Varsayılan = tümü.

`add_base64(self, base64: str)`
:   Tanıma / işleme için görüntüyü içeren base64 dizesini ekleyin.
Görüntünün türü, yapıcıda belirtilen türe karşılık gelmelidir.
@param base64: Tek görüntülü Base64 dizesi.

`clear(self)`
:   İşleme / tanıma için öğe sayısını 0 olarak ayarlayın.
Koleksiyonu temizleyin.

`clear_filters(self)`
:   Tüm filtreleri kaldırın.

`get(self, index: int) ‑> models.ImageData`
:   İşlenen / tanımlanan görüntü hakkında bilgi döndürür.
@param index: Görüntünün Listedeki konumu.
@return: ImageData nesnesi.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   İşleme / tanıma için öğe sayısı.
@return: Öğelerin sayısı.

`PreprocessingFilter()`
:   Görüntü işleme komutları için temel sınıf.

### Atalar (MRO içinde)

    * aspose.helper.BaseJavaClass

### Sınıf değişkenleri

`JAVA_CLASS_NAME`
:

### Statik yöntemler

`auto_denoising()`
:   Görüntüyü iyileştirmek için ek bir sinir ağı kullanımını etkinleştirir - gürültüyü azaltır.
Tarama artefaktları, bozulma, lekeler, parlamalar, gradyanlar, yabancı öğeler içeren görüntüler için faydalıdır.
@return: AutoDenoisingFilter nesnesi.

`auto_dewarping()`
:   Görüntüdeki geometrik bozulmaları otomatik olarak düzeltir.
Son derece kaynak yoğun!
@return: AutoDewarpingFilter nesnesi.

`auto_skew()`
:   Otomatik görüntü eğimi düzeltmesini etkinleştirir.
@return: AutoSkewFilter nesnesi.

`binarize()`
:   Bir görüntüyü siyah-beyaz görüntüye dönüştürür.
İkili görüntüler, piksellerinin yalnızca iki olası yoğunluk değerine sahip olduğu görüntülerdir.
Genellikle siyah ve beyaz olarak görüntülenirler. Sayısal olarak, iki değer genellikle siyah için 0 ve beyaz için 255'tir.
İkili görüntüler, bir görüntünün otomatik eşikleme ile üretilir.
@return: BinarizeFilter nesnesi.

`binarize_and_dilate()`
:   Genişletme, bir görüntüdeki nesnelerin sınırlarına piksel ekler.
@return: DilateFilter nesnesi.

`contrast_correction()`
:   Kontrast düzeltme filtresi.
@return: ContrastCorrectionFilter nesnesi.

`invert()`
:   Belge görüntüsündeki renkleri otomatik olarak tersine çevirir.
@return: InvertFilter nesnesi.

`median()`
:   Medyan filtresi, görüntünün her öğesinden geçer ve her pikseli komşu piksellerin medyanı ile değiştirir.
@return: MedianFilter nesnesi.

`resize(width: int, height: int)`
:   Görüntüyü yeniden ölçeklendir - görüntü çözünürlüğünü artırır veya azaltır.
@param width: Görüntünün yeni genişliği.
@param height: Görüntünün yeni yüksekliği.
@return: ResizeFilter nesnesi.

`rotate(angle: float)`
:   Orijinal görüntüyü döndür.
@param angle: Dönüş açısı. Değer -360 ile 360 arasında.
@return: RotateFilter nesnesi.

`scale(ratio: float)`
:   Görüntüyü yeniden ölçeklendir - Görüntü çözünürlüğünü artır veya azalt.
InterpolationFilterType bilinear veya en yakın komşu.
@param ratio: Ölçekleme faktörü. Küçültmek için önerilen değer 0.1 ile 1 arasındadır. Büyütmek için 1 ile 10 arasındadır.
@return: ScaleFilter nesnesi.

`threshold(value: int)`
:   Orijinal görüntünün piksel yoğunluğuna bir eşik değeri ayarlayarak ikili görüntü oluştur.
@param value: Azami değer.
@return: BinarizeFilter nesnesi.

`to_grayscale()`
:   Bir görüntüyü gri tonlamalı görüntüye dönüştürür.
Gri tonlamalı görüntü, görüntüde 256 ışık seviyesi (0'dan 255'e) içerir.
@return: GrayscaleFilter nesnesi.

### Yöntemler

`add(self, filter)`
:   Daha sonraki ön işleme için filtreyi koleksiyona ekle.
@param filter: PreprocessingFilter nesnesi.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   Yanlış yazılmış kelimeyi ek veriyle temsil eder.

### Atalar (MRO içinde)

    * aspose.helper.BaseJavaClass

### Yöntemler

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Yazım denetimi düzeltmesi için sözlük dili.

### Atalar (MRO içinde)

    * enum.Enum

### Sınıf değişkenleri

`CZE`
:   Çekçe sözlük

`DAN`
:   Danimarka sözlüğü

`DEU`
:   Almanca sözlüğü

`DUM`
:   Hollandaca sözlüğü

`ENG`
:   İngilizce sözlüğü

`EST`
:   Estonca sözlüğü

`FIN`
:   Fince sözlüğü

`FRA`
:   Fransızca sözlüğü

`ITA`
:   İtalyanca sözlüğü

`LAV`
:   Letonca sözlüğü

`LIT`
:   Litvanca sözlüğü

`POL`
:   Lehçe sözlüğü

`POR`
:   Portekizce sözlüğü

`RUM`
:   Rumence sözlüğü

`SLK`
:   Slovakça sözlüğü

`SLV`
:   Slovence sözlüğü

`SPA`
:   İspanyolca sözlüğü

`SWE`
:   İsveççe sözlüğü

`SuggestedWord(javaClass)`
:   Yazım önerisi get_spell_check_error_list'den döndürüldü.

### Atalar (MRO içinde)

    * aspose.helper.BaseJavaClass

### Yöntemler

`initParams(self)`
:


### Ayrıca Bakınız

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)