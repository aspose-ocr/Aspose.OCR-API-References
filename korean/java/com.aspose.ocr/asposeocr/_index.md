---
title: "AsposeOCR"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "이미지에서 텍스트를 인식하기 위한 메인 클래스"
type: docs
weight: 10
url: /ko/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

이미지에서 텍스트를 인식하기 위한 메인 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | 공개 생성자. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [DebugMode](#DebugMode) | 디버그 모드를 활성화합니다. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | 디버그 결과가 저장될 디렉터리. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | 이미지의 기울기 각도를 계산합니다. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | 두 이미지가 동일한 텍스트를 포함하는지 확인합니다. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | 두 이미지가 동일한 텍스트를 포함하는지 확인합니다. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | 두 이미지가 동일한 텍스트를 포함하는지 확인합니다. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 텍스트를 교정합니다 (오타를 교정합니다). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | 텍스트를 교정합니다 (오타를 교정합니다). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | OCR 정확도에 크게 영향을 줄 수 있는 이미지의 문제 영역을 자동으로 찾습니다. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | 이미지를 분석하고 그 안의 다양한 콘텐츠 영역 유형을 식별합니다. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | 이미지의 텍스트를 분석하여 사용된 언어를 판별합니다. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | 이미지에서 텍스트 영역을 감지합니다. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | 이미지에서 표 영역을 감지합니다. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | 이미지가 제공된 텍스트 조각을 대소문자 구분 없이 포함하는지 확인합니다. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | 이미지가 제공된 텍스트 조각을 대소문자 구분 없이 포함하는지 확인합니다. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | 이미지가 제공된 텍스트 조각을 포함하는지 확인합니다. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | 이미지 텍스트가 제공된 정규식과 일치하는지 확인합니다. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | 이미지 텍스트가 제공된 정규식과 일치하는지 확인합니다. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | 두 이미지의 텍스트를 비교하고 유사도를 나타내는 숫자(0~1)를 반환합니다. |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | 두 이미지의 텍스트를 비교하고 유사도를 나타내는 숫자(0~1)를 반환합니다. |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | 두 이미지의 텍스트를 비교하고 유사도를 나타내는 숫자(0~1)를 반환합니다. |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | 이미지를 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | 이미지를 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | 자동차 번호판을 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | 이미지에서 기호를 감지합니다. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | 이미지에서 기호를 감지합니다. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | 고품질 이미지에서 텍스트를 인식합니다. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | 제공된 입력 이미지에서 수학 공식을 인식합니다. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | 이미지에서 손글씨 텍스트를 인식합니다. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | 신분증을 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | 청구서를 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | 여권을 지정할 수 있는 기능으로 인식합니다. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | 영수증을 지정할 수 있는 기능으로 인식합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | 표와 구조를 감지하고, 텍스트 셀을 인식합니다. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | RecognitionResult 객체 목록에서 맞춤법 검사 보정이 적용된 다중 페이지 문서를 가져올 수 있습니다. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


공개 생성자.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


디버그 모드를 활성화합니다. 활성화되면 시스템은 전처리된 이미지와 텍스트 라인 사각형이 그려진 이미지와 같은 중간 이미지 처리 결과를 저장합니다.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


디버그 결과가 저장될 디렉터리입니다. 설정되지 않으면 기본적으로 현재 작업 디렉터리가 사용됩니다.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


이미지의 기울기 각도를 계산합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 소스가 포함된 컨테이너.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - 각도(도) 단위의 기울기 각도 ArrayList [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


두 이미지가 동일한 텍스트를 포함하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 첫 번째 이미지의 경로. |
| fullPath2 | java.lang.String | 두 번째 이미지의 경로. |

**Returns:**
boolean - 이미지가 동일한 텍스트(90% 유사도)를 가지고 있으면 true.
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


두 이미지가 동일한 텍스트를 포함하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 첫 번째 이미지의 경로. |
| fullPath2 | java.lang.String | 두 번째 이미지의 경로. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 인식 설정. |

**Returns:**
boolean - 이미지가 동일한 텍스트(90% 유사도)를 가지고 있으면 true.
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


두 이미지가 동일한 텍스트를 포함하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 첫 번째 이미지의 경로. |
| fullPath2 | java.lang.String | 두 번째 이미지의 경로. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 인식 설정. |
| ignoreCase | boolean | True - 대소문자를 구분하지 않는 검색을 의미합니다. |

**Returns:**
boolean - 이미지가 동일한 텍스트(90% 유사도)를 가지고 있으면 true.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


텍스트를 교정합니다 (오타를 교정합니다).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 수정용 텍스트. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 사용할 사전 [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - 교체된 단어가 포함된 텍스트.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


텍스트를 교정합니다 (오타를 교정합니다).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 수정용 텍스트. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 사용할 사전 [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | 사용자 사전(빈도 사전)의 전체 경로입니다. 사전 파일 형식: UTF-8 인코딩의 일반 텍스트 파일. 단어와 단어 빈도는 쉼표로 구분되며, 단어는 첫 번째 열에, 빈도는 두 번째 열에 위치합니다. 각 단어-빈도 쌍은 별도의 라인에 있습니다. 라인은 문자 시퀀스 뒤에 라인 피드 ("\\n"), 캐리지 리턴 ("\\r"), 혹은 캐리지 리턴 바로 뒤에 라인 피드 ("\\r\\n")가 따라오는 것으로 정의됩니다. 모든 단어는 소문자로 입력되어야 합니다. |

**Returns:**
java.lang.String - 교체된 단어가 포함된 텍스트.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


이미지의 문제 영역을 자동으로 찾아 OCR 정확도에 크게 영향을 줄 수 있습니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 소스가 포함된 컨테이너.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | 인식될 결함 유형은 [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - 감지된 텍스트 영역 또는 라인이 포함된 [DefectOutput](../../com.aspose.ocr/defectoutput/)의 ArrayList.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


이미지를 분석하고 그 안의 다양한 콘텐츠 영역 유형을 식별합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 소스가 포함된 컨테이너.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - 감지된 콘텐츠 영역. [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)의 ArrayList.
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


이미지의 텍스트를 분석하여 작성된 언어를 판단합니다. 이를 통해 가장 적합한 인식 언어를 선택하고 맞춤법 검사나 번역과 같은 추가 텍스트 처리 작업에 도움이 됩니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 소스가 포함된 컨테이너.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - 가장 가능성이 높은 언어 목록을 확률 순으로 반환합니다. [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)의 ArrayList.
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


이미지에서 텍스트 영역을 감지합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 소스가 포함된 컨테이너.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | 반환할 사각형을 결정합니다 - 라인 또는 단락. |
| isDetectAreas | boolean | 자동 텍스트 영역 감지를 활성화합니다. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - 감지된 텍스트 영역 또는 라인이 포함된 [RectangleOutput](../../com.aspose.ocr/rectangleoutput/)의 ArrayList.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


이미지에서 표 영역을 감지합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | 소스가 포함된 컨테이너.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - 감지된 표 영역이 포함된 [RectangleOutput](../../com.aspose.ocr/rectangleoutput/)의 ArrayList.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


이미지가 제공된 텍스트 조각을 대소문자 구분 없이 포함하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath | java.lang.String | 이미지 경로. |
| text | java.lang.String | 이미지에서 검색할 텍스트 조각. |

**Returns:**
boolean - 이미지에 텍스트 조각이 포함된 경우 true. false - 이미지에 텍스트 조각이 포함되지 않은 경우.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


이미지가 제공된 텍스트 조각을 대소문자 구분 없이 포함하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath | java.lang.String | 이미지 경로. |
| text | java.lang.String | 이미지에서 검색할 텍스트 조각. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 인식 설정. |

**Returns:**
boolean - 이미지에 텍스트 조각이 포함된 경우 true. false - 이미지에 텍스트 조각이 포함되지 않은 경우.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


이미지가 제공된 텍스트 조각을 포함하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath | java.lang.String | 이미지 경로. |
| text | java.lang.String | 이미지에서 검색할 텍스트 조각. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 인식 설정. |
| ignoreCase | boolean | True - 대소문자를 구분하지 않는 검색을 의미합니다. |

**Returns:**
boolean - 이미지에 텍스트 조각이 포함된 경우 true. false - 이미지에 텍스트 조각이 포함되지 않은 경우.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


이미지 텍스트가 제공된 정규식과 일치하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath | java.lang.String | 이미지 경로. |
| regex | java.util.regex.Pattern | 제공된 패턴과 옵션을 가진 java.util.regex.Pattern 객체. |

**Returns:**
boolean - 이미지 텍스트가 제공된 정규식과 일치하는 경우 true.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


이미지 텍스트가 제공된 정규식과 일치하는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath | java.lang.String | 이미지 경로. |
| regex | java.util.regex.Pattern | 제공된 패턴과 옵션을 가진 java.util.regex.Pattern 객체. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 인식 설정. |

**Returns:**
boolean - 이미지 텍스트가 제공된 정규식과 일치하는 경우 true.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


두 이미지의 텍스트를 비교하고 유사도를 나타내는 숫자(0~1)를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 첫 번째 이미지의 경로. |
| fullPath2 | java.lang.String | 두 번째 이미지의 경로. |

**Returns:**
float - 0은 텍스트가 완전히 다름을 의미하고; 1은 텍스트가 동일함을 의미합니다.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


두 이미지의 텍스트를 비교하고 유사도를 나타내는 숫자(0~1)를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 첫 번째 이미지의 경로. |
| fullPath2 | java.lang.String | 두 번째 이미지의 경로. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 인식 설정. |

**Returns:**
float - 0은 텍스트가 완전히 다름을 의미하고; 1은 텍스트가 동일함을 의미합니다.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


두 이미지의 텍스트를 비교하고 유사도를 나타내는 숫자(0~1)를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 첫 번째 이미지의 경로. |
| fullPath2 | java.lang.String | 두 번째 이미지의 경로. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 인식 설정. |
| ignoreCase | boolean | True - 대소문자를 구분하지 않는 검색을 의미합니다. |

**Returns:**
float - 0은 텍스트가 완전히 다름을 의미하고; 1은 텍스트가 동일함을 의미합니다.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


이미지를 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 인스턴스. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


이미지를 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 인스턴스. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


자동차 번호판을 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 인스턴스. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


이미지에서 기호를 감지합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 소스가 포함된 컨테이너.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - 각 이미지에 대한 감지된 기호 데이터가 포함된 [Character](../../com.aspose.ocr.models/character/)의 ArrayList.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


이미지에서 기호를 감지합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 소스가 포함된 컨테이너.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | 영역 감지에 사용되는 신경망 유형을 결정합니다. |
| language | [Language](../../com.aspose.ocr.models/language/) | OCR에 사용되는 언어입니다. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - 감지된 기호 데이터가 포함된 [Character](../../com.aspose.ocr.models/character/)의 ArrayList.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


고품질 이미지에서 텍스트를 인식합니다. 자동 이미지 기울기 보정 및 텍스트 영역 감지를 사용하지 않습니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/) 인스턴스. |

**Returns:**
java.util.ArrayList<java.lang.String> - 인식된 텍스트가 포함된 ArrayList.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


제공된 입력 이미지에서 수학 공식을 인식합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 인스턴스. |
| detectAreas | boolean | true로 설정하면 인식 수행 전에 공식 영역을 자동으로 감지하고 분리합니다. false로 설정하면 전체 이미지를 하나의 공식으로 처리합니다. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


이미지에서 손글씨 텍스트를 인식합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 소스가 포함된 컨테이너입니다.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


신분증을 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 인스턴스. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


청구서를 인식하며 GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원하도록 지정할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 인스턴스. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


지정 기능을 포함한 여권을 인식합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 인스턴스. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


영수증을 지정할 수 있는 기능으로 인식합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 인스턴스. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


표와 구조를 감지하고 텍스트 셀을 인식합니다. GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, 폴더, 배열, zip 아카이브, URL, base64를 지원합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). 인스턴스. |
| language | [Language](../../com.aspose.ocr.models/language/) | 인식 중에 사용되는 알파벳을 결정합니다. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - 표에서 인식된 텍스트가 포함된 OCRTablePage 객체 목록. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 선택한 형식으로 인식 결과를 저장하기 위한 OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 리스트 [RecognitionResult](../../com.aspose.ocr/recognitionresult/). 객체. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 선택한 형식으로 인식 결과를 저장하기 위한 OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 리스트 [RecognitionResult](../../com.aspose.ocr/recognitionresult/). 객체. |
| embeddedFontPath | java.lang.String | 선택 사항. 사용자 글꼴에 대한 전체 경로. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 선택한 형식으로 인식 결과를 저장하기 위한 OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 리스트 [RecognitionResult](../../com.aspose.ocr/recognitionresult/). 객체. |
| embeddedFontPath | java.lang.String | 선택 사항. 사용자 글꼴에 대한 전체 경로. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 배경 이미지 품질을 낮춰 PDF 파일 크기를 줄입니다. 기본적으로 원본 이미지 품질이 유지됩니다. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 리스트 [RecognitionResult](../../com.aspose.ocr/recognitionresult/). 객체. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


RecognitionResult 객체 목록에서 맞춤법 검사 보정이 적용된 다중 페이지 문서를 가져올 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 리스트 [RecognitionResult](../../com.aspose.ocr/recognitionresult/). 객체. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) 열거형 값. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 리스트 [RecognitionResult](../../com.aspose.ocr/recognitionresult/). 객체. |
| embeddedFontPath | java.lang.String | 선택 사항. 사용자 글꼴에 대한 전체 경로. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


RecognitionResult 객체 목록에서 다중 페이지 문서를 가져올 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 리스트 [RecognitionResult](../../com.aspose.ocr/recognitionresult/). 객체. |
| embeddedFontPath | java.lang.String | 선택 사항. 사용자 글꼴에 대한 전체 경로. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 배경 이미지 품질을 낮춰 PDF 파일 크기를 줄입니다. 기본적으로 원본 이미지 품질이 유지됩니다. |

### close() {#close}
```
public void close()
```