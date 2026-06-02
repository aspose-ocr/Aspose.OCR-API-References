---
title: "이미지 처리"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "Aspose OCR 라이브러리를 위한 도우미 클래스"
type: docs
weight: 19
url: /ko/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Aspose OCR 라이브러리를 위한 도우미 클래스. 이미지를 전처리하고 저장할 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | 이미지 처리를 사용하여 OCR 정확도를 향상시킵니다. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | 이미지 처리를 사용하여 OCR 정확도를 향상시킵니다. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


이미지 처리를 사용하여 OCR 정확도를 향상시킵니다. 입력 이미지에 적용될 필터 목록을 지정한 순서대로 생성합니다. 필터를 생성하는 예시: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); 모든 필터가 필요하지는 않습니다. 필요한 것만 설정하세요.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | 다양한 이미지를 포함하는 OcrInput 객체 @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


이미지 처리를 사용하여 OCR 정확도를 향상시킵니다. 입력 이미지에 적용될 필터 목록을 지정한 순서대로 생성합니다. 필터를 생성하는 예시: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); 모든 필터가 필요하지는 않습니다. 필요한 것만 설정하세요.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | 다양한 이미지를 포함하는 OcrInput 객체 @see \#OcrInput. |
| folderPath | java.lang.String | 전처리된 이미지를 저장하기 위한 이미지 이름이 없는 경로. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
