---
title: "RecognitionSettings"
second_title: "Aspose.OCR for Python via .NET API Reference"
description: 
type: docs
weight: 330
url: /ko/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

이미지 인식을 위한 설정.<br/>            인식 프로세스를 사용자 정의할 수 있는 요소를 포함합니다.

RecognitionSettings 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| RecognitionSettings() | 새 인스턴스를 초기화합니다 |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | RecognitionSettings 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | 처리를 위한 스레드 수를 가져오거나 설정합니다. |
| language | OCR에 사용되는 언어를 가져오거나 설정합니다. |
| ignored_symbols | 인식 심볼에 대한 블랙리스트를 설정합니다. |
| allowed_symbols | alphabet 속성을 사용하여 허용된 문자를 설정합니다. |
| allowed_characters | 허용된 문자 집합. 인식 결과에 허용되는 문자 유형을 결정합니다. |
| automatic_color_inversion | 어두운/검은 배경에 흰색 텍스트가 있는 이미지를 감지하고 자동으로 특수 OCR 알고리즘을 선택합니다. |
| recognition_areas | 처리를 위한 텍스트 영역 목록을 가져오거나 설정합니다. |
| recognize_single_line | 단일 라인 이미지 인식을 설정합니다. <br/>            기본값은 비활성화(false)입니다. <br/>            라인으로 분할하는 모든 처리 단계를 비활성화합니다. <br/>            이미지에 한 줄만 포함된 경우 이 매개변수를 true로 설정합니다. RecognitionAreas 설정을 비활성화하므로 모든 영역 설정이 무시됩니다. |
| language_detection_level |  |
| lines_filtration | 표(선으로 둘러싸인 영역)에서 텍스트를 인식하도록 허용합니다. |
| detect_areas_mode | 문서 유형 영역(문서, 사진, 일반 텍스트, 열, 이미지)에 대한 최적 모드를 선택하도록 허용합니다. |
| upscale_small_font | 작은 글꼴 인식을 위해 특별히 추가 알고리즘을 사용할 수 있도록 허용합니다.<br/>            작은 크기 문자 이미지에 유용합니다. |

### 참조

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

