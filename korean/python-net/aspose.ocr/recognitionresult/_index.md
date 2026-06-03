---
title: "RecognitionResult"
second_title: "Aspose.OCR for Python via .NET API Reference"
description: 
type: docs
weight: 290
url: /ko/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

이미지 인식 결과입니다.<br/>            인식 정보와 결과 내보내기 메서드를 포함하는 요소를 포함합니다.

RecognitionResult 유형은 다음 멤버를 노출합니다:


## 속성
| 이름 | 설명 |
| :- | :- |
| recognition_regions_result | 영역 목록(사각형)과 함께 인식 결과 목록을 가져옵니다. |
| recognition_lines_result | 인식 결과 목록과 행(사각형) 목록을 가져옵니다. |
| recognition_characters_list | 인식 알고리즘에 의해 발견된 문자 집합이며, 확률 내림차순으로 정렬됩니다. |
| recognition_text | 인식 결과를 하나의 문자열로 가져옵니다. |
| file_name | 파일의 전체 경로입니다. |
| warnings | 생성 중 발생한 비중대한 오류를 설명하는 경고 메시지 목록을 가져옵니다. |
| serializable_image |  |
## Methods
| 이름 | 설명 |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | 문서를 일반 텍스트, PDF 또는 Microsoft Word 문서로 저장합니다. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | 문서를 일반 텍스트, PDF 또는 Microsoft Word 문서로 저장합니다. |
| save(full_file_name, save_format, optimize_pdf) | 문서를 일반 텍스트, PDF 또는 Microsoft Word 문서로 저장합니다. |
| save(stream, save_format, optimize_pdf) | 문서를 일반 텍스트, PDF 또는 Microsoft Word 문서로 저장합니다. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | 문서를 일반 텍스트, PDF 또는 Microsoft Word 문서로 저장합니다. |
| get_spell_check_corrected_text(language, dictionary_path) | 텍스트를 교정합니다(잘못된 단어를 교체). |
| get_spell_check_error_list(language, dictionary_path) | 주어진 입력 텍스트에 대해 제안된 철자를 포함한 잘못된 단어를 찾습니다. |
| get_json(is_readable) | 인식 결과를 포함한 JSON 문자열을 생성합니다. |
| get_xml() | 인식 결과를 포함한 XML 문자열을 생성합니다. |
| get_keywords() | 여권에서 키워드를 가져옵니다 (테스트 모드. 미국 및 마다가스카르 여권에만 작동합니다). |

### 참조

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

