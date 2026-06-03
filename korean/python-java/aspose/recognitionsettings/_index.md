---
title: "RecognitionSettings"
second_title: "Java API 레퍼런스를 통한 Python용 Aspose.OCR"
description: 
type: docs
weight: 191
url: /ko/python-java/aspose/recognitionsettings/
---

모듈 recognitionsettings
==========================

클래스
-------

`CarPlateRecognitionSettings()`
:

### 클래스 변수

`JAVA_CLASS_NAME`
:

### Methods

`set_allowed_characters(self, allowedCharacters: str)`
:
허용된 문자 집합. 인식 결과에 허용되는 문자 배열을 결정합니다.
@param allowedCharacters: 문자열 형태의 문자를 포함합니다.

`set_ignored_characters(self, ignoredCharacters: str)`
:
인식 기호에 대한 블랙리스트를 설정합니다.
@param ignoredCharacters: 인식에서 제외되는 문자.

`set_language(self, language: aspose.models.Language)`
:
OCR에 사용되는 언어를 설정합니다.
기본값은 다국어(없음)입니다.
@param language: enum Language 값을 포함합니다.

`set_threads_count(self, threadsCount: int)`
:
처리를 위한 스레드 수를 가져오거나 설정합니다.
기본값인 0은 이미지가 프로세서 수와 동일한 스레드 수로 처리됨을 의미합니다.
ThreadsCount = 1은 이미지가 메인 스레드에서 처리됨을 의미합니다.
@param threadsCount: 이미지 조각을 병렬 인식하기 위해 생성될 스레드 수.

`IDCardRecognitionSettings()`
:

### 클래스 변수

`JAVA_CLASS_NAME`
:

### Methods

`set_allowed_characters(self, allowedCharacters: str)`
:
허용된 문자 집합. 인식 결과에 허용되는 문자 배열을 결정합니다.
@param allowedCharacters: 문자열 형태의 문자를 포함합니다.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다.
@param automaticColorInversion: boolean 값을 포함합니다 - automaticColorInversion이 설정됩니다. 기본값은 True입니다.

`set_ignored_characters(self, ignoredCharacters: str)`
:
인식 기호에 대한 블랙리스트를 설정합니다.
@param ignoredCharacters: 인식에서 제외되는 문자.

`set_language(self, language: aspose.models.Language)`
:
OCR에 사용되는 언어를 설정합니다.
기본값은 다국어(없음)입니다.
@param language: enum Language 값을 포함합니다.

`set_threads_count(self, threadsCount: int)`
:
처리를 위한 스레드 수를 가져오거나 설정합니다.
기본값인 0은 이미지가 프로세서 수와 동일한 스레드 수로 처리됨을 의미합니다.
ThreadsCount = 1은 이미지가 메인 스레드에서 처리됨을 의미합니다.
@param threadsCount: 이미지 조각을 병렬 인식하기 위해 생성될 스레드 수.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
작은 글꼴 인식을 위해 추가 알고리즘을 사용할 수 있게 합니다.
작은 크기의 문자 이미지에 유용합니다.
@param upscaleSmallFont: boolean 값을 포함합니다 - upscaleSmallFont이 설정됩니다.

`InvoiceRecognitionSettings()`
:

### 클래스 변수

`JAVA_CLASS_NAME`
:

### Methods

`set_allowed_characters(self, allowedCharacters: str)`
:
허용된 문자 집합. 인식 결과에 허용되는 문자 배열을 결정합니다.
@param allowedCharacters: 문자열 형태의 문자를 포함합니다.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다.
@param automaticColorInversion: boolean 값을 포함합니다 - automaticColorInversion이 설정됩니다. 기본값은 True입니다.

`set_ignored_characters(self, ignoredCharacters: str)`
:
인식 기호에 대한 블랙리스트를 설정합니다.
@param ignoredCharacters: 인식에서 제외되는 문자.

`set_language(self, language: aspose.models.Language)`
:
OCR에 사용되는 언어를 설정합니다.
기본값은 다국어(없음)입니다.
@param language: enum Language 값을 포함합니다.

`set_threads_count(self, threadsCount: int)`
:
처리를 위한 스레드 수를 가져오거나 설정합니다.
기본값인 0은 이미지가 프로세서 수와 동일한 스레드 수로 처리됨을 의미합니다.
ThreadsCount = 1은 이미지가 메인 스레드에서 처리됨을 의미합니다.
@param threadsCount: 이미지 조각을 병렬 인식하기 위해 생성될 스레드 수.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
작은 글꼴 인식을 위해 추가 알고리즘을 사용할 수 있게 합니다.
작은 크기의 문자 이미지에 유용합니다.
@param upscaleSmallFont: boolean 값을 포함합니다 - upscaleSmallFont이 설정됩니다.

`PassportRecognitionSettings()`
:

### 클래스 변수

`JAVA_CLASS_NAME`
:

### Methods

`set_allowed_characters(self, allowedCharacters: str)`
:
허용된 문자 집합. 인식 결과에 허용되는 문자 배열을 결정합니다.
@param allowedCharacters: 문자열 형태의 문자를 포함합니다.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다.
@param automaticColorInversion: boolean 값을 포함합니다 - automaticColorInversion이 설정됩니다. 기본값은 True입니다.

`set_ignored_characters(self, ignoredCharacters: str)`
:
인식 기호에 대한 블랙리스트를 설정합니다.
@param ignoredCharacters: 인식에서 제외되는 문자.

`set_language(self, language: aspose.models.Language)`
:
OCR에 사용되는 언어를 설정합니다.
기본값은 다국어(없음)입니다.
@param language: enum Language 값을 포함합니다.

`set_threads_count(self, threadsCount: int)`
:
처리를 위한 스레드 수를 가져오거나 설정합니다.
기본값인 0은 이미지가 프로세서 수와 동일한 스레드 수로 처리됨을 의미합니다.
ThreadsCount = 1은 이미지가 메인 스레드에서 처리됨을 의미합니다.
@param threadsCount: 이미지 조각을 병렬 인식하기 위해 생성될 스레드 수.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
작은 글꼴 인식을 위해 추가 알고리즘을 사용할 수 있게 합니다.
작은 크기의 문자 이미지에 유용합니다.
@param upscaleSmallFont: boolean 값을 포함합니다 - upscaleSmallFont이 설정됩니다.

`ReceiptRecognitionSettings()`
:

### 클래스 변수

`JAVA_CLASS_NAME`
:

### Methods

`set_allowed_characters(self, allowedCharacters: str)`
:
허용된 문자 집합. 인식 결과에 허용되는 문자 배열을 결정합니다.
@param allowedCharacters: 문자열 형태의 문자를 포함합니다.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다.
@param automaticColorInversion: boolean 값을 포함합니다 - automaticColorInversion이 설정됩니다. 기본값은 True입니다.

`set_ignored_characters(self, ignoredCharacters: str)`
:
인식 기호에 대한 블랙리스트를 설정합니다.
@param ignoredCharacters: 인식에서 제외되는 문자.

`set_language(self, language: aspose.models.Language)`
:
OCR에 사용되는 언어를 설정합니다.
기본값은 다국어(없음)입니다.
@param language: enum Language 값을 포함합니다.

`set_threads_count(self, threadsCount: int)`
:
처리를 위한 스레드 수를 가져오거나 설정합니다.
기본값인 0은 이미지가 프로세서 수와 동일한 스레드 수로 처리됨을 의미합니다.
ThreadsCount = 1은 이미지가 메인 스레드에서 처리됨을 의미합니다.
@param threadsCount: 이미지 조각을 병렬 인식하기 위해 생성될 스레드 수.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
작은 글꼴 인식을 위해 추가 알고리즘을 사용할 수 있게 합니다.
작은 크기의 문자 이미지에 유용합니다.
@param upscaleSmallFont: boolean 값을 포함합니다 - upscaleSmallFont이 설정됩니다.

`RecognitionSettings()`
:
이미지 인식을 위한 설정입니다.
인식 프로세스를 사용자 정의할 수 있는 요소를 포함합니다.
    
    
기본 생성자: recognitionAreas를 null로 설정하고, linesFiltration을 false, autoSkew를 false, recognizeSingleLine을 false로 설정합니다.

### 클래스 변수

`JAVA_CLASS_NAME`
:

### Methods

`set_allowed_characters(self, allowedCharacters: str)`
:
허용된 문자 집합. 인식 결과에 허용되는 문자 배열을 결정합니다.
@param allowedCharacters: 문자열 형태의 문자를 포함합니다.

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다.
@param automaticColorInversion: boolean 값을 포함합니다 - automaticColorInversion이 설정됩니다. 기본값은 True입니다.

`set_detect_areas_mode(self, detectAreasMode: aspose.models.DetectAreasMode)`
:
영역 감지에 사용되는 신경망 유형을 결정합니다.
@param detectAreasMode: DetectAreasMode 열거형 값을 포함합니다.

`set_ignored_characters(self, ignoredCharacters: str)`
:
인식 기호에 대한 블랙리스트를 설정합니다.
@param ignoredCharacters: 인식에서 제외되는 문자.

`set_language(self, language: aspose.models.Language)`
:
OCR에 사용되는 언어를 설정합니다.
기본값은 다국어(없음)입니다.
@param language: enum Language 값을 포함합니다.

`set_recognize_single_line(self, recognizeSingleLine: bool)`
:
단일 라인 이미지 인식을 설정합니다.
기본적으로 비활성화됩니다 (false).
라인으로 분할하는 모든 처리 단계를 비활성화합니다.
이미지에 한 줄만 포함된 경우 이 매개변수를 true로 설정하십시오. set_recognition_areas 설정을 비활성화하므로 모든 영역 설정이 무시됩니다.
@param recognizeSingleLine: 단일 라인 이미지의 경우 True

`set_threads_count(self, threadsCount: int)`
:
처리를 위한 스레드 수를 가져오거나 설정합니다.
기본값인 0은 이미지가 프로세서 수와 동일한 스레드 수로 처리됨을 의미합니다.
ThreadsCount = 1은 이미지가 메인 스레드에서 처리됨을 의미합니다.
@param threadsCount: 이미지 조각을 병렬 인식하기 위해 생성될 스레드 수.

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
작은 글꼴 인식을 위해 추가 알고리즘을 사용할 수 있게 합니다.
작은 크기의 문자 이미지에 유용합니다.
@param upscaleSmallFont: boolean 값을 포함합니다 - upscaleSmallFont이 설정됩니다.



### 참고

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)