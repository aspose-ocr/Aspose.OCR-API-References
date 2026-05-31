---
title: "معالجة الصور"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "فئة مساعدة لمكتبة Aspose OCR"
type: docs
weight: 19
url: /ar/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

فئة مساعدة لمكتبة Aspose OCR. تسمح بالمعالجة المسبقة وحفظ الصور.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | استخدم معالجة الصور لتحسين دقة OCR. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | استخدم معالجة الصور لتحسين دقة OCR. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


استخدم معالجة الصور لتحسين دقة OCR. أنشئ قائمة من المرشحات التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء المرشحات: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); لا تحتاج إلى جميعها. عيّن فقط ما تحتاجه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | كائن OcrInput يحتوي على صور مختلفة @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


استخدم معالجة الصور لتحسين دقة OCR. أنشئ قائمة من المرشحات التي سيتم تطبيقها على الصورة المدخلة بالترتيب الذي تحدده. مثال لإنشاء المرشحات: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); لا تحتاج إلى جميعها. عيّن فقط ما تحتاجه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | كائن OcrInput يحتوي على صور مختلفة @see \#OcrInput. |
| folderPath | java.lang.String | المسار بدون أسماء الصور لحفظ الصور المعالجة. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
