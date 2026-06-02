---
title: "Görüntü İşleme"
second_title: "Aspose.OCR for Java API Referansı"
description: "Aspose OCR kütüphanesi için yardımcı sınıf"
type: docs
weight: 19
url: /tr/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Aspose OCR kütüphanesi için yardımcı sınıf. Görüntüleri ön işleme ve kaydetmeye olanak tanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | OCR doğruluğunu artırmak için görüntü işleme kullanın. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | OCR doğruluğunu artırmak için görüntü işleme kullanın. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


OCR doğruluğunu artırmak için görüntü işleme kullanın. Giriş görüntüsüne belirttiğiniz sırayla uygulanacak filtrelerin bir listesini oluşturun. Filtre oluşturma örneği: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Hepsine ihtiyacınız yok. Sadece ihtiyacınız olanı ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Farklı görüntüler içeren OcrInput nesnesi @see \\#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


OCR doğruluğunu artırmak için görüntü işleme kullanın. Giriş görüntüsüne belirttiğiniz sırayla uygulanacak filtrelerin bir listesini oluşturun. Filtre oluşturma örneği: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Hepsine ihtiyacınız yok. Sadece ihtiyacınız olanı ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Farklı görüntüler içeren OcrInput nesnesi @see \\#OcrInput. |
| folderPath | java.lang.String | İşlenmiş görüntüleri kaydetmek için görüntü adları içermeyen yol. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
