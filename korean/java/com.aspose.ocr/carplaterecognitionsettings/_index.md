---
title: "CarPlateRecognitionSettings"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "자동차 번호 인식을 위한 설정은 인식 프로세스를 사용자 정의할 수 있는 요소를 포함합니다."
type: docs
weight: 12
url: /ko/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

자동차 번호 인식을 위한 설정은 인식 프로세스를 사용자 정의할 수 있는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | 기본 생성자: autoSkew를 true로 설정합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | 허용된 문자 집합입니다. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | 어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | 인식 기호에 대한 블랙리스트를 설정합니다. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


기본 생성자: autoSkew를 true로 설정합니다.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


허용된 문자 집합. 인식 결과에 허용되는 문자 유형을을 결정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) 값을 포함합니다. |

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

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | OCR에 사용되는 언어를 설정합니다. 기본값은 다중 언어(없음)입니다. |

