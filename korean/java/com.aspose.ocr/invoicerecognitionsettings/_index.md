---
title: "InvoiceRecognitionSettings"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "청구서 인식을 위한 설정은 인식 프로세스를 사용자 정의할 수 있는 요소를 포함합니다."
type: docs
weight: 17
url: /ko/java/com.aspose.ocr/invoicerecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class InvoiceRecognitionSettings extends ReceiptRecognitionSettings
```

청구서 인식을 위한 설정은 인식 프로세스를 사용자 정의할 수 있는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [InvoiceRecognitionSettings()](#InvoiceRecognitionSettings) | 기본 생성자: autoSkew를 true로 설정합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | 허용된 문자 집합입니다. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | 허용된 문자 집합입니다. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | 어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | 인식 기호에 대한 블랙리스트를 설정합니다. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | 텍스트 인식을 위한 언어 감지 수준을 지정합니다. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | 처리를 위한 스레드 수를 가져오거나 설정합니다. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | 작은 글꼴 인식을 위해 특별히 추가 알고리즘을 사용할 수 있게 합니다. |
### InvoiceRecognitionSettings() {#InvoiceRecognitionSettings}
```
public InvoiceRecognitionSettings()
```


기본 생성자: autoSkew를 true로 설정합니다.



### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


허용된 문자 집합. 인식 결과에 허용되는 문자 유형을을 결정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) 값을 포함합니다. |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


허용된 문자 집합. 인식 결과에 허용되는 문자 배열을 결정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| allowedCharacters | java.lang.String | 문자 배열을 포함합니다. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| automaticColorInversion | boolean | 불리언 값을 포함합니다 - automaticColorInversion이 설정됩니다. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


인식 기호에 대한 블랙리스트를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| characters | java.lang.String | 인식에서 제외된 문자. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | OCR에 사용되는 언어를 설정합니다. 기본값은 다중 언어(없음)입니다. |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


텍스트 인식을 위한 언어 감지 수준을 지정합니다. 선택된 언어가 Language.MULTILANGUAGE, Language.AUTO 또는 Language.UNIVERSAL인 경우에만 작동합니다. 이 과정은 시간이 많이 걸리며 전체 인식 속도를 크게 늦춥니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | 레벨을 설정하기 위한 enum 값 (Paragraph, Word, Page). |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


처리를 위한 스레드 수를 가져오거나 설정합니다. 기본값인 0은 이미지가 프로세서 수와 동일한 스레드 수로 처리됨을 의미합니다. ThreadsCount = 1은 이미지가 메인 스레드에서 처리됨을 의미합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| threadsCount | int | 이미지 조각을 병렬로 인식하기 위해 생성될 스레드 수. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


작은 글꼴 인식을 위해 특별히 추가 알고리즘을 사용할 수 있게 합니다. 작은 크기 문자 이미지에 유용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| upscaleSmallFont | boolean | 불리언 값을 포함합니다 - upscaleSmallFont이 설정됩니다. |
