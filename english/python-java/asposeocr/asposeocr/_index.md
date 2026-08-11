---
title: "AsposeOcr"
linktitle: "AsposeOcr"
second_title: "Aspose.OCR for Python via Java"
description: "AsposeOcr main class for recognition. This sample shows how to recognize image."
type: docs
weight: 10
url: /python-java/asposeocr/asposeocr/
---

## AsposeOcr class

**Module:** `asposeocr`


AsposeOcr main class for recognition. This sample shows how to recognize image.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [calculate_skew](#calculate_skew) | `typing.List[SkewOutput]` | No | Calculates the skew angles of an images. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [compare_image_texts](#compare_image_texts) | `bool` | No | Check if two images contain the same text. |
| [correct_spelling](#correct_spelling) | `str` | No | Corrects text (replaces misspelled words). |
| [detect_rectangles](#detect_rectangles) | `typing.List[RectangleOutput]` | No | Detects text areas on images. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [image_has_text](#image_has_text) | `bool` | No | Check if the image contains the provided text fragment. |
| [image_text_diff](#image_text_diff) | `float` | No | Compare the texts on the two images and return a number representing how similar they are (0 to 1). |
| [recognize](#recognize) | `typing.List[RecognitionResult]` | No | Recognizes image with the ability to specify RecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [recognize_car_plate](#recognize_car_plate) | `typing.List[RecognitionResult]` | No | Recognizes car plate with the ability to specify CarPlateRecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [recognize_fast](#recognize_fast) | `typing.List[RecognitionResult]` | No | Recognizes text on good quality image. Doesn't use automatic image skew correction and text areas detection. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [recognize_id_card](#recognize_id_card) | `typing.List[RecognitionResult]` | No | Recognizes ID card with the ability to specify IDCardRecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [recognize_invoice](#recognize_invoice) | `typing.List[RecognitionResult]` | No | Recognize invoice with the ability to specify InvoiceRecognitionSettings Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [recognize_lines](#recognize_lines) | `typing.List[RecognitionResult]` | No | Recognizes single line image with the ability to specify RecognitionSettings. |
| [recognize_passport](#recognize_passport) | `typing.List[RecognitionResult]` | No | Recognizes passport with the ability to specify PassportRecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [recognize_receipt](#recognize_receipt) | `typing.List[RecognitionResult]` | No | Recognize receipts with the ability to specify ReceiptRecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [recognize_street_photo](#recognize_street_photo) | `typing.List[RecognitionResult]` | No | Recognizes text on street photos. Extract text from street photos, traffic camera images, ID cards, driver licenses, and other images with sparse text and noisy/colored backgrounds. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64. |
| [save_multipage_document](#save_multipage_document) |  | Yes | Allows to get multipage document from list of RecognitionResult objects. |
| [shutdown](#shutdown) |  | No | Shut down the JVM machine. |

### AsposeOcr Constructor {#constructor}

```python
__init__(self)
```

### AsposeOcr.calculate_skew {#calculate_skew}

```python
calculate_skew(self, OcrInput input) -> typing.List[SkewOutput]
```

Calculates the skew angles of an images. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `OcrInput` | :py:any:~aspose.models.OcrInput. instance. The container with sources. |

**Return Type:** `typing.List[SkewOutput]` — List of skew angles in degrees - SkewOutput.

### AsposeOcr.compare_image_texts {#compare_image_texts}

```python
compare_image_texts(self, str fullPath1, str fullPath2, RecognitionSettings settings, bool ignoreCase) -> bool
```

Check if two images contain the same text.

| Parameter | Type | Description |
| --- | --- | --- |
| `fullPath1` | `str` | Path to the first image. |
| `fullPath2` | `str` | Path to the second image. |
| `settings` | `RecognitionSettings` | Recognition settings. |
| `ignoreCase` | `bool` | True - means a case-insensitive search. |

**Return Type:** `bool` — True if images have the same text (90% similarity).

### AsposeOcr.correct_spelling {#correct_spelling}

```python
correct_spelling(self, str text, SpellCheckLanguage language) -> str
```

Corrects text (replaces misspelled words).

| Parameter | Type | Description |
| --- | --- | --- |
| `text` | `str` | Text for correction. |
| `language` | `SpellCheckLanguage` | Dictionary to use SpellCheckLanguage. |

**Return Type:** `str` — Text with replaced words.

### AsposeOcr.detect_rectangles {#detect_rectangles}

```python
detect_rectangles(self, OcrInput input, aspose.models.AreasType areasType, bool isDetectAreas) -> typing.List[RectangleOutput]
```

Detects text areas on images. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `OcrInput` | :py:any:~aspose.models.OcrInput. instance. |
| `areasType` | `aspose.models.AreasType` | Determinates wich rectangles to return - line, paragraphs or words. |
| `isDetectAreas` | `bool` | Enable automatic text areas detection. |

**Return Type:** `typing.List[RectangleOutput]` — List of RectangleOutput with detected text areas or lines.

### AsposeOcr.image_has_text {#image_has_text}

```python
image_has_text(self, str fullPath, str text, RecognitionSettings settings, bool ignoreCase) -> bool
```

Check if the image contains the provided text fragment.

| Parameter | Type | Description |
| --- | --- | --- |
| `fullPath` | `str` | Path to the image. |
| `text` | `str` | Text fragment for searching on the image. |
| `settings` | `RecognitionSettings` | Recognition settings. |
| `ignoreCase` | `bool` | True - means a case-insensitive search. |

**Return Type:** `bool` — True if image contains text fragment. False - image doesn't contains text fragment.

### AsposeOcr.image_text_diff {#image_text_diff}

```python
image_text_diff(self, str fullPath1, str fullPath2, RecognitionSettings settings, bool ignoreCase) -> float
```

Compare the texts on the two images and return a number representing how similar they are (0 to 1).

| Parameter | Type | Description |
| --- | --- | --- |
| `fullPath1` | `str` | Path to the first image. |
| `fullPath2` | `str` | Path to the second image. |
| `settings` | `RecognitionSettings` | Recognition settings. |
| `ignoreCase` | `bool` | True - means a case-insensitive search. |

**Return Type:** `float` — 0 means that the texts are completely different; 1 means the texts are identical.

### AsposeOcr.recognize {#recognize}

```python
recognize(self, OcrInput input, RecognitionSettings settings) -> typing.List[RecognitionResult]
```

Recognizes image with the ability to specify RecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `OcrInput` | :py:any:~aspose.models.OcrInput. instance. |
| `settings` | `RecognitionSettings` | RecognitionSettings object. |

**Return Type:** `typing.List[RecognitionResult]` — RecognitionResult list with images recognition results.

### AsposeOcr.recognize_car_plate {#recognize_car_plate}

```python
recognize_car_plate(self, aspose.models.OcrInput input, aspose.recognitionsettings.CarPlateRecognitionSettings settings) -> typing.List[RecognitionResult]
```

Recognizes car plate with the ability to specify CarPlateRecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `aspose.models.OcrInput` | :py:any:~aspose.models.OcrInput. instance. |
| `settings` | `aspose.recognitionsettings.CarPlateRecognitionSettings` | CarPlateRecognitionSettings |

**Return Type:** `typing.List[RecognitionResult]` — RecognitionResult list with images recognition results.

### AsposeOcr.recognize_fast {#recognize_fast}

```python
recognize_fast(self, OcrInput input) -> typing.List[RecognitionResult]
```

Recognizes text on good quality image. Doesn't use automatic image skew correction and text areas detection. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `OcrInput` | :py:any:~aspose.models.OcrInput. instance. |

**Return Type:** `typing.List[RecognitionResult]` — RecognitionResult list with images recognition results.

### AsposeOcr.recognize_id_card {#recognize_id_card}

```python
recognize_id_card(self, aspose.models.OcrInput input, aspose.recognitionsettings.IDCardRecognitionSettings settings) -> typing.List[RecognitionResult]
```

Recognizes ID card with the ability to specify IDCardRecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `aspose.models.OcrInput` | :py:any:~aspose.models.OcrInput. instance. |
| `settings` | `aspose.recognitionsettings.IDCardRecognitionSettings` | IDCardRecognitionSettings |

**Return Type:** `typing.List[RecognitionResult]` — RecognitionResult list with images recognition results.

### AsposeOcr.recognize_invoice {#recognize_invoice}

```python
recognize_invoice(self, aspose.models.OcrInput input, aspose.recognitionsettings.InvoiceRecognitionSettings settings) -> typing.List[RecognitionResult]
```

Recognize invoice with the ability to specify InvoiceRecognitionSettings Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `aspose.models.OcrInput` | :py:any:~aspose.models.OcrInput. instance. |
| `settings` | `aspose.recognitionsettings.InvoiceRecognitionSettings` | InvoiceRecognitionSettings |

**Return Type:** `typing.List[RecognitionResult]` — RecognitionResult list with images recognition results.

### AsposeOcr.recognize_lines {#recognize_lines}

```python
recognize_lines(self, OcrInput input, RecognitionSettings settings) -> typing.List[RecognitionResult]
```

Recognizes single line image with the ability to specify RecognitionSettings.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `OcrInput` | :py:any:~aspose.models.OcrInput. instance. |
| `settings` | `RecognitionSettings` | RecognitionSettings object. |

**Return Type:** `typing.List[RecognitionResult]` — RecognitionResult list with images recognition results.

### AsposeOcr.recognize_passport {#recognize_passport}

```python
recognize_passport(self, aspose.models.OcrInput input, aspose.recognitionsettings.PassportRecognitionSettings settings) -> typing.List[RecognitionResult]
```

Recognizes passport with the ability to specify PassportRecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `aspose.models.OcrInput` | :py:any:~aspose.models.OcrInput. instance. |
| `settings` | `aspose.recognitionsettings.PassportRecognitionSettings` | PassportRecognitionSettings |

**Return Type:** `typing.List[RecognitionResult]` — RecognitionResult list with images recognition results.

### AsposeOcr.recognize_receipt {#recognize_receipt}

```python
recognize_receipt(self, aspose.models.OcrInput input, aspose.recognitionsettings.ReceiptRecognitionSettings settings) -> typing.List[RecognitionResult]
```

Recognize receipts with the ability to specify ReceiptRecognitionSettings. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `aspose.models.OcrInput` | :py:any:~aspose.models.OcrInput. instance. |
| `settings` | `aspose.recognitionsettings.ReceiptRecognitionSettings` | ReceiptRecognitionSettings |

**Return Type:** `typing.List[RecognitionResult]` — RecognitionResult list with images recognition results.

### AsposeOcr.recognize_street_photo {#recognize_street_photo}

```python
recognize_street_photo(self, OcrInput input) -> typing.List[RecognitionResult]
```

Recognizes text on street photos. Extract text from street photos, traffic camera images, ID cards, driver licenses, and other images with sparse text and noisy/colored backgrounds. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binary array, folder, array, zip archive, URL, base64.

| Parameter | Type | Description |
| --- | --- | --- |
| `input` | `OcrInput` | :py:any:~aspose.models.OcrInput. instance. |

**Return Type:** `typing.List[RecognitionResult]` — RecognitionResult list with images recognition results.

### AsposeOcr.save_multipage_document (static) {#save_multipage_document}

```python
save_multipage_document(str fullFileName, Format saveFormat, List results)
```

Allows to get multipage document from list of RecognitionResult objects.

| Parameter | Type | Description |
| --- | --- | --- |
| `fullFileName` | `str` | Filename with a path for saving recognition result in the selected format. |
| `saveFormat` | `Format` | Document format (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| `results` | `List` |  |

### AsposeOcr.shutdown {#shutdown}

```python
shutdown(self)
```

Shut down the JVM machine.

