---
title: "OcrInput"
second_title: "Aspose.OCR for Python via .NET API Reference"
description: 
type: docs
weight: 240
url: /ko/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

전처리/인식을 위해 모든 이미지/문서를 수집하는 컨테이너입니다.

OcrInput 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| OcrInput(type, filters) | OcrInput 클래스의 새 인스턴스를 초기화합니다 |
| OcrInput(type) | OcrInput 클래스의 새 인스턴스를 초기화합니다 |
## Indexer
| 이름 | 설명 |
| :- | :- |
| [index] | 처리/인식된 이미지에 대한 정보를 반환합니다. |
## Methods
| 이름 | 설명 |
| :- | :- |
| add(full_path) | 인식/처리를 위한 이미지를 포함하는 경로나 URI를 추가합니다.<br/>            이미지 유형은 생성자에서 지정한 유형과 일치해야 합니다. |
| add(stream) | 인식/처리를 위한 이미지를 포함하는 메모리 스트림을 추가합니다.<br/>            이미지 유형은 생성자에서 지정한 유형과 일치해야 합니다. |
| add(full_path, start_page, pages_count) | 인식/처리를 위한 다중 페이지 이미지/문서를 추가합니다.<br/>            이미지 유형은 생성자에서 지정한 유형과 일치해야 합니다. |
| add(stream, start_page, pages_count) | 인식/처리를 위한 다중 페이지 이미지를 포함하는 메모리 스트림을 추가합니다.<br/>            이미지 유형은 생성자에서 지정한 유형과 일치해야 합니다. |
| add(arr, width, height, pixel_format) | 디코딩된 이미지를 인식/처리를 위한 목록에 추가합니다.<br/>            이미지 유형은 생성자에 지정된 유형 (SingleImage)과 일치해야 합니다. |
| replace_filters(filters) | 이전 필터를 제거하고 새 필터를 설정합니다. |
| clear_filters() | 모든 필터를 제거합니다. |
| add_base64(base64) | 인식/처리를 위한 이미지가 포함된 base64 문자열을 추가합니다.<br/>            이미지 유형은 생성자에 지정된 유형과 일치해야 합니다. |
| clear() | 모든 필터를 제거합니다. |
| count() | 처리/인식을 위한 항목 수. |
| get_input_type() | 인식에 허용되는 이미지 유형. |

### 참조

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

