---
title: "AsposeOcr"
second_title: "Python için Java üzerinden Aspose.OCR API Referansı"
description: 
type: docs
weight: 11
url: /tr/python-java/aspose/asposeocr/
---


modül asposeocr
================
Aspose OCR için Python arayüzü

**Aspose.OCR for Python via .Java** is a powerful,
kolay kullanılabilir optik karakter tanıma (OCR)
Python uygulamalarınız ve not defterleriniz için motor.
Kodun **10** satırından daha azında, tanıyabilirsiniz
Latin, Kiril temelli **28** dilde metin,
ve Asya yazı sistemlerinde, sonuçları en popüler
belge ve veri değişim formatlarında.
Karmaşık matematiksel modelleri öğrenmeye gerek yok,
makine öğrenimi algoritmalarını oluşturun ve sinir
ağları — basit ve sağlam API’miz sizin için her şeyi yapacak.

Sınıflar
-------

`AsposeOcr()`
:
AsposeOcr tanıma için ana sınıf.
    
Bu örnek, görüntüyü nasıl tanıyacağınızı gösterir.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Statik yöntemler

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
RecognitionResult nesnelerinin listesinden çok sayfalı belge almanıza izin verir.
@param fullFileName: Seçilen formatta tanıma sonucunu kaydetmek için yol içeren dosya adı.
@param saveFormat: Belge formatı (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Yöntemler

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Bir görüntünün eğim açılarını hesaplar.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek. Kaynakları içeren kapsayıcı.
@return: Derece cinsinden eğim açıları listesi - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
İki görüntünün aynı metni içerip içermediğini kontrol eder.
@param fullPath1: İlk görüntünün yolu.
@param fullPath2: İkinci görüntünün yolu.
@param settings: Tanıma ayarları.
@param ignoreCase: True - büyük/küçük harf duyarsız bir arama anlamına gelir.
@return: Görüntüler aynı metni (%90 benzerlik) içeriyorsa True.

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Metni düzeltir (yanlış yazılmış kelimeleri değiştirir).
@param text: Düzeltme için metin.
@param language: SpellCheckLanguage için kullanılacak sözlük.
@return: Değiştirilen kelimelerle metin.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Görüntülerdeki metin alanlarını algılar.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@param areasType: Hangi dikdörtgenlerin döndürüleceğini belirler - satır, paragraf veya kelimeler.
@param isDetectAreas: Otomatik metin alanı algılamayı etkinleştir.
@return: Algılanan metin alanları veya satırlarla RectangleOutput listesi.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Görüntünün sağlanan metin parçasını içerip içermediğini kontrol eder.
@param fullPath: Görüntünün yolu.
@param text: Görüntü üzerinde arama için metin parçacığı.
@param settings: Tanıma ayarları.
@param ignoreCase: True - büyük/küçük harf duyarsız bir arama anlamına gelir.
@return: Görüntü metin parçacığını içeriyorsa True. Aksi takdirde False - görüntü metin parçacığını içermiyor.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
İki görüntüdeki metinleri karşılaştırın ve benzerliklerini (0 ile 1 arasında) temsil eden bir sayı döndürün.
@param fullPath1: İlk görüntünün yolu.
@param fullPath2: İkinci görüntünün yolu.
@param settings: Tanıma ayarları.
@param ignoreCase: True - büyük/küçük harf duyarsız bir arama anlamına gelir.
@return: 0, metinlerin tamamen farklı olduğunu; 1, metinlerin aynı olduğunu gösterir.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
RecognitionSettings belirtme yeteneğiyle görüntüyü tanır.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@param settings: RecognitionSettings nesnesi.
@return: Görüntü tanıma sonuçlarını içeren RecognitionResult listesi.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
CarPlateRecognitionSettings belirtme yeteneğiyle araç plakası tanır.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@param settings: CarPlateRecognitionSettings
@return: Görüntü tanıma sonuçlarını içeren RecognitionResult listesi.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
İyi kalite bir görüntüdeki metni tanır. Otomatik görüntü eğimi düzeltmesi ve metin alanlarını kullanmaz
algılama.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@return: Görüntü tanıma sonuçlarını içeren RecognitionResult listesi.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
IDCardRecognitionSettings belirtme yeteneğiyle kimlik kartını tanır.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@param settings: IDCardRecognitionSettings
@return: Görüntü tanıma sonuçlarını içeren RecognitionResult listesi.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
InvoiceRecognitionSettings belirtme yeteneğiyle faturayı tanır
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@param settings: InvoiceRecognitionSettings
@return: Görüntü tanıma sonuçlarını içeren RecognitionResult listesi.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
RecognitionSettings belirtme yeteneğiyle tek satır görüntüyü tanır.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@param settings: RecognitionSettings nesnesi.
@return: Görüntü tanıma sonuçlarını içeren RecognitionResult listesi.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Pasaportu tanır ve PassportRecognitionSettings ayarlamasını belirleme yeteneğine sahiptir.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@param settings: PassportRecognitionSettings
@return: Görüntü tanıma sonuçlarını içeren RecognitionResult listesi.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Makbuzları tanır ve ReceiptRecognitionSettings ayarlamasını belirleme yeteneğine sahiptir.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@param settings: ReceiptRecognitionSettings
@return: Görüntü tanıma sonuçlarını içeren RecognitionResult listesi.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Sokak fotoğraflarındaki metni tanır.
Sokak fotoğrafları, trafik kamerası görüntüleri, kimlik kartları, sürücü belgeleri ve seyrek metin ile gürültülü/renkli arka planlara sahip diğer görüntülerden metin çıkarır.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, ikili dizi, klasör, dizi, zip arşivi, URL, base64 formatlarını destekler.
@param input: :py:any:`~aspose.models.OcrInput`. örnek.
@return: Görüntü tanıma sonuçlarını içeren RecognitionResult listesi.

`shutdown(self)`
:
JVM makinesini kapat.

`ImageProcessing()`
:
Aspose OCR kütüphanesi için yardımcı sınıf. Görüntüleri ön işleme ve kaydetmeye izin verir.

### Statik yöntemler

`save(images, folderPath)`
:
OCR doğruluğunu artırmak için görüntü işleme kullanın.
Giriş görüntüsüne belirttiğiniz sırayla uygulanacak filtrelerin bir listesini oluşturun.
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
Hepsine ihtiyacınız yok. Sadece ihtiyacınız olanı ayarlayın.
@param images: Farklı görüntüler içeren OcrInput nesnesi OcrInput.
@param folderPath: İşlenmiş görüntülerin kaydedileceği, görüntü adları içermeyen yol.
@return: Sonuç işlenmiş görüntüleri içeren OcrInput nesnesi OcrInput.


### Ayrıca Bakınız

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)