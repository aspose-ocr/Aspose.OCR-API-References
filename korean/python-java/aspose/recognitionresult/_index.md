---
title: "RecognitionResult"
second_title: "Java API 레퍼런스를 통한 Python용 Aspose.OCR"
description: 
type: docs
weight: 171
url: /ko/python-java/aspose/recognitionresult/
---

모듈 recognitionresult
========================

클래스
-------

`LinesResult(javaClass)`
:

### 조상 (MRO 내)

    * aspose.helper.BaseJavaClass

### Methods

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
이미지 인식 결과입니다. 인식된 요소를 포함합니다
결과 내보내기를 위한 정보와 메서드.

### Static methods

`save_multipage_document(self, fullPath: str)`
:
비공개

### 인스턴스 변수

`recognition_areas_text`
:   영역(사각형) 목록에 대한 인식 결과 리스트.

`recognition_lines_result`
:   행(사각형) 목록에 대한 인식 결과 리스트를 가져옵니다.

### Methods

`getJavaClass(self)`
:

`get_json(self)`
:
인식 결과를 포함한 JSON 문자열을 형성합니다.
@return: JSON 문자열 형태의 인식 결과.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
텍스트를 교정합니다 (오타 단어를 교체).
@param language: 사용할 사전.
@return: 수정된 인식 결과 문자열.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
주어진 입력 텍스트에 대해 제안된 철자를 사용하여 맞춤법이 틀린 단어를 찾습니다.
@param language: 사용할 사전.
@return: 각 맞춤법 오류 단어에 대해 제안된 올바른 철자 목록을 포함하는 SpellCheckError 객체의 목록,
그리고 편집 거리와 함께.

`get_xml(self)`
:
인식 결과를 포함한 JSON 문자열을 형성합니다.
@return: XML 문자열 형태의 인식 결과.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
문서를 일반 텍스트 또는 다른 문서 형식으로 저장합니다.
@param fullFileName: 인식 결과를 저장하기 위한 경로가 포함된 파일 이름.
@param format: Format의 문서 형식 열거형 타입.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
텍스트를 교정합니다 (오타 단어를 교체).
수정된 텍스트를 일반 텍스트 또는 다른 형식으로 문서에 저장합니다.
@param fullFileName: 인식 결과를 저장하기 위한 경로가 포함된 파일 이름
@param format: Format의 문서 형식 열거형 타입.
@param language: 맞춤법 검사를 위한 사전.

`use_user_dictionary(self, dictionaryPath: str)`
:
맞춤법 교정을 위해 자체 사전을 사용할 수 있습니다.
@param dictionaryPath: 사용자 사전(빈도 사전)의 전체 경로.
사전 파일 형식:
UTF-8 인코딩의 일반 텍스트 파일.
단어와 단어 빈도는 쉼표로 구분되며, 단어는 첫 번째 열에, 빈도는 두 번째 열에 위치합니다.
각 단어-빈도 쌍은 별도의 줄에 있습니다. 줄은 문자 시퀀스로 구성되며, 줄 피드 ("
", 캐리지 리턴 ("
"),
또는 캐리지 리턴 바로 뒤에 라인 피드가 오는 경우(\")

\").
모든 단어는 소문자로 입력되어야 합니다.
예시:
\code
word,5984819
안녕,5761742
아래,5582768
\endcode

`RectangleOutput(javaClass)`
:
감지된 텍스트 영역 또는 라인에 대한 데이터입니다.
\code
source - 파일 또는 URL(있는 경우)의 전체 경로입니다. 스트림, 바이트 배열, base64의 경우 비어 있습니다.
page - 페이지 번호입니다.
image_index - 페이지 내 이미지의 순번입니다.
rectangles - 감지된 텍스트 영역 또는 라인의 목록입니다.
\endcode

### 조상 (MRO 내)

    * aspose.helper.BaseJavaClass

### Methods

`initParams(self)`
:

`SkewOutput(javaClass)`
:
파일 이름 및 각도(도) 단위의 기울기 각도에 대한 데이터입니다.
\code
source - 파일 또는 URL(있는 경우)의 전체 경로입니다. 스트림, 바이트 배열, base64의 경우 비어 있습니다.
page - 페이지 번호입니다.
image_index - 페이지 내 이미지의 순번입니다.
angle - 기울기 각도(도)입니다.
\endcode

### 조상 (MRO 내)

    * aspose.helper.BaseJavaClass

### Methods

`initParams(self)`
:


### 참고

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)