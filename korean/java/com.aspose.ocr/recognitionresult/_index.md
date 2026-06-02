---
title: "RecognitionResult"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "이미지 인식 결과"
type: docs
weight: 26
url: /ko/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

이미지 인식 결과. 인식 정보가 포함된 요소와 결과 내보내기 메서드를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | 새 인스턴스를 초기화합니다 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [language](#language) | 이미지에서 인식된 텍스트의 언어. |
| [recognitionCharactersList](#recognitionCharactersList) | 인식 알고리즘에 의해 찾아진 문자 집합으로, 확률 내림차순으로 정렬됩니다. |
| [recognitionLinesResult](#recognitionLinesResult) | 행 목록(Rectangles)과 함께 인식 결과 목록을 가져옵니다. |
| [recognitionRegionsResult](#recognitionRegionsResult) | 영역 목록(Rectangles)과 함께 인식 결과 목록을 가져옵니다. |
| [recognitionText](#recognitionText) | 전체 페이지 또는 하나의 영역에 대한 인식 결과. |
| [warnings](#warnings) | 생성 중 발생한 비치명적 오류를 설명하는 경고 메시지 목록을 가져오거나 설정합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [GetJson()](#GetJson) | 인식 결과를 포함한 JSON 문자열을 형성합니다. |
| [GetKeywords()](#GetKeywords) | 여권에서 키워드를 가져옵니다 (테스트 모드. |
| [GetXml()](#GetXml) | 인식 결과를 포함한 JSON 문자열을 형성합니다. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | 텍스트를 교정합니다 (오타를 교정합니다). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 텍스트를 교정합니다 (오타를 교정합니다). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | 주어진 입력 텍스트에 대한 맞춤법 오류 단어와 제안된 철자를 찾습니다. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 주어진 입력 텍스트에 대한 맞춤법 오류 단어와 제안된 철자를 찾습니다. |
| [save(String fullFileName)](#save-java.lang.String) | 문서를 일반 텍스트 형식으로 저장합니다. |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | 문서를 일반 텍스트 또는 다른 문서 형식으로 저장합니다. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | 문서를 일반 텍스트 또는 다른 문서 형식으로 저장합니다. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | 수정된 영어 사전 텍스트를 일반 텍스트 또는 Microsoft Word 텍스트 문서 형식으로 문서에 저장합니다. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 수정된 텍스트를 일반 텍스트 또는 다른 형식으로 문서에 저장합니다. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | 맞춤법 검사 교정을 위해 자체 사전을 사용할 수 있습니다. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


새 인스턴스를 초기화합니다

### language {#language}
```
public Language language
```


이미지에서 인식된 텍스트의 언어입니다. Language.AUTO, Language.MULTILANGUAGE 또는 Language.UNIVERSAL을 선택하면 이 값이 자동으로 결정됩니다.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


인식 알고리즘에 의해 찾아진 문자 집합으로, 확률 내림차순으로 정렬됩니다.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


행 목록(Rectangles)과 함께 인식 결과 목록을 가져옵니다.

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


영역 목록(Rectangles)과 함께 인식 결과 목록을 가져옵니다.

### recognitionText {#recognitionText}
```
public String recognitionText
```


전체 페이지 또는 하나의 영역에 대한 인식 결과.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


생성 중 발생한 비치명적 오류를 설명하는 경고 메시지 목록을 가져오거나 설정합니다.

### GetJson() {#GetJson}
```
public String GetJson()
```


인식 결과를 포함한 JSON 문자열을 형성합니다.

**Returns:**
java.lang.String - 인식 결과를 JSON 문자열로 반환합니다.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


여권에서 키워드를 가져옵니다 (테스트 모드. 미국 및 마다가스카르 여권에만 작동합니다).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - 키워드를 키로, LinesResult를 값으로 하는 사전입니다.
### GetXml() {#GetXml}
```
public String GetXml()
```


인식 결과를 포함한 JSON 문자열을 형성합니다.

**Returns:**
java.lang.String - 인식 결과를 XML 문자열로 반환합니다.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


텍스트를 교정합니다 (오타를 교정합니다).

**Returns:**
java.lang.String - 교정된 인식 결과 문자열입니다. 기본 영어 사전.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


텍스트를 교정합니다 (오타를 교정합니다).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 사용할 사전입니다. |

**Returns:**
java.lang.String - 교정된 인식 결과 문자열입니다.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


주어진 입력 텍스트에 대한 맞춤법 오류 단어와 제안된 철자를 찾습니다. 기본 영어 사전.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - 맞춤법 오류 단어를 나타내는 SpellCheckError 객체의 ArrayList이며, 각 오류 단어에 대한 제안된 올바른 철자 목록과 편집 거리를 포함합니다.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


주어진 입력 텍스트에 대한 맞춤법 오류 단어와 제안된 철자를 찾습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 사용할 사전입니다. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - 맞춤법 오류 단어를 나타내는 SpellCheckError 객체의 ArrayList이며, 각 오류 단어에 대한 제안된 올바른 철자 목록과 편집 거리를 포함합니다.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


문서를 일반 텍스트 형식으로 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 인식 결과를 저장하기 위한 경로가 포함된 파일 이름 |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


문서를 일반 텍스트 또는 다른 문서 형식으로 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 인식 결과를 저장하기 위한 경로가 포함된 파일 이름입니다. |
| format | [Format](../../com.aspose.ocr.models/format/) | Format의 문서 형식 열거형 타입입니다. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


문서를 일반 텍스트 또는 다른 문서 형식으로 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 인식 결과를 저장하기 위한 경로가 포함된 파일 이름입니다. |
| format | [Format](../../com.aspose.ocr.models/format/) | Format의 문서 형식 열거형 타입입니다. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 배경 이미지 품질을 낮춰 PDF 파일 크기를 줄입니다. 기본적으로 원본 이미지 품질이 유지됩니다. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


수정된 영어 사전 텍스트를 일반 텍스트 또는 Microsoft Word 텍스트 문서 형식으로 문서에 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 인식 결과를 저장하기 위한 경로가 포함된 파일 이름입니다. |
| format | [Format](../../com.aspose.ocr.models/format/) | Format의 문서 형식 열거형 타입입니다. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


수정된 텍스트를 일반 텍스트 또는 다른 형식으로 문서에 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 인식 결과를 저장하기 위한 경로가 포함된 파일 이름입니다. |
| format | [Format](../../com.aspose.ocr.models/format/) | Format의 문서 형식 열거형 타입입니다. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 맞춤법 검사용 사전입니다. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


맞춤법 검사 교정을 위해 자체 사전을 사용할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dictionaryPath | java.lang.String | 사용자 사전(빈도 사전)의 전체 경로입니다. 사전 파일 형식: UTF-8 인코딩의 일반 텍스트 파일. 단어와 단어 빈도는 쉼표로 구분되며, 단어는 첫 번째 열에, 빈도는 두 번째 열에 위치합니다. 각 단어-빈도 쌍은 별도의 라인에 있습니다. 라인은 문자 시퀀스 뒤에 라인 피드 ("\\n"), 캐리지 리턴 ("\\r"), 혹은 캐리지 리턴 바로 뒤에 라인 피드 ("\\r\\n")가 따라오는 것으로 정의됩니다. 모든 단어는 소문자로 입력되어야 합니다. |
