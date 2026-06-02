---
title: "RecognitionSettings"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "이미지 인식을 위한 설정"
type: docs
weight: 27
url: /ko/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

이미지 인식을 위한 설정. 인식 프로세스를 사용자 정의할 수 있는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | 기본 생성자: recognitionAreas를 null로 설정하고, linesFiltration을 false, autoSkew를 false, recognizeSingleLine을 false로 설정합니다. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | 생성자를 사용하면 모든 옵션을 설정할 수 있습니다. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | 생성자를 사용하면 recognizeSingleLine을 설정할 수 있습니다. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | 허용된 문자 집합입니다. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | 허용된 문자 집합입니다. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | 어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | 영역 감지에 사용되는 신경망 유형을 결정합니다. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | 인식 기호에 대한 블랙리스트를 설정합니다. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | 텍스트 인식을 위한 언어 감지 수준을 지정합니다. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | 표(선으로 둘러싸인 영역)에서 텍스트를 인식할 수 있습니다. |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | 처리를 위한 텍스트 영역 목록을 설정합니다. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | 단일 라인 이미지 인식을 설정합니다. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | 처리를 위한 스레드 수를 가져오거나 설정합니다. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | 작은 글꼴 인식을 위해 특별히 추가 알고리즘을 사용할 수 있게 합니다. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


기본 생성자: recognitionAreas를 null로 설정하고, linesFiltration을 false, autoSkew를 false, recognizeSingleLine을 false로 설정합니다.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


생성자를 사용하면 모든 옵션을 설정할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | 인식용 사각형. |
| recognizeSingleLine | boolean | 이미지가 한 줄만 포함하는 경우 True. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


생성자는 recognizeSingleLine을 설정할 수 있습니다. 이 경우 기본값: detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recognizeSingleLine | boolean | 이미지가 한 줄만 포함하는 경우 True. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




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
| allowedCharacters | java.lang.String | 문자열을 포함합니다. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| automaticColorInversion | boolean | boolean 값이 포함됩니다 - automaticColorInversion이 설정됩니다. 기본값은 True. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


영역 감지에 사용되는 신경망 유형을 결정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | enum 값이 포함됩니다 @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


표(선으로 둘러싸인 영역)에서 텍스트를 인식할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| linesFiltration | boolean | false - 성능을 향상시키고 테이블을 감지하지 않으며 라인을 제거하도록 허용합니다; 그렇지 않으면 - true. 기본값은 비활성화 (false)입니다. |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


처리를 위한 텍스트 영역 목록을 설정합니다. 보다 정확한 인식을 위해 텍스트가 있는 영역을 수동으로 지정할 수 있습니다. 사용자 정의 영역이 설정된 경우 [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\}가 NONE이 아니거나 [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} 속성이 무시됩니다. DetectAreas와 AutoSkew를 비활성화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | 인식용 사각형. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


단일 라인 이미지 인식을 설정합니다. 기본값은 비활성화 (false)입니다. 라인으로 분할하는 모든 처리 단계를 비활성화합니다. 이미지가 한 줄만 포함하는 경우 이 매개변수를 true로 설정하십시오. [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList) 설정을 비활성화하여 모든 영역 설정이 무시됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| recognizeSingleLine | boolean | 단일 라인 이미지에 대해 True |

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
| upscaleSmallFont | boolean | boolean 값이 포함됩니다 - upscaleSmallFont가 설정됩니다. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String