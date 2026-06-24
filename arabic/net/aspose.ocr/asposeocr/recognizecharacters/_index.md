---
title: "RecognizeCharacters"
second_title: "Aspose.OCR لـ .NET مرجع API"
description: "يكتشف الرموز في الصور. يدعم GIF PNG JPEG BMP TIFF JFIF تدفقات المجلدات والمصفوفات والأرشيفات."
type: docs
weight: 160
url: /ar/net/aspose.ocr/asposeocr/recognizecharacters/
---
## RecognizeCharacters(OcrInput) {#recognizecharacters}

يكشف عن الرموز في الصور. يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات.

```csharp
public List<CharacterRecognitionResult> RecognizeCharacters(OcrInput images)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| images | OcrInput | الحاوية التي تحتوي على المصادر.[`OcrInput`](../../ocrinput) |

### قيمة الإرجاع

قائمة من [`CharacterRecognitionResult`](../../characterrecognitionresult) مع بيانات الرموز المكتشفة.

### انظر أيضًا

* class [CharacterRecognitionResult](../../characterrecognitionresult)
* class [OcrInput](../../ocrinput)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizeCharacters(OcrInput, DetectAreasMode, Language) {#recognizecharacters_1}

يكشف عن الرموز في الصور. يدعم GIF و PNG و JPEG و BMP و TIFF و JFIF، التدفق، المجلد، المصفوفات، الأرشيفات.

```csharp
public List<CharacterRecognitionResult> RecognizeCharacters(OcrInput images, 
    DetectAreasMode detectAreasMode = DetectAreasMode.UNIVERSAL, Language language = Language.Latin)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| images | OcrInput | الحاوية التي تحتوي على المصادر.[`OcrInput`](../../ocrinput) |
| detectAreasMode | DetectAreasMode | يحدد نوع الشبكة العصبية المستخدمة لاكتشاف المناطق. |
| language | اللغة | اللغة المستخدمة في OCR.. |

### قيمة الإرجاع

قائمة من [`Character`](../../character) مع بيانات الرموز المكتشفة.

### انظر أيضًا

* class [CharacterRecognitionResult](../../characterrecognitionresult)
* class [OcrInput](../../ocrinput)
* enum [DetectAreasMode](../../detectareasmode)
* enum [Language](../../language)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ Aspose.OCR.dll -->
