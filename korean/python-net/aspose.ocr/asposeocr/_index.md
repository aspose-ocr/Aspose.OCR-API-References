---
title: "AsposeOcr"
second_title: "Aspose.OCR for Python via .NET API Reference"
description: 
type: docs
weight: 10
url: /ko/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Aspose OCR 라이브러리의 주요 API

AsposeOcr 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| AsposeOcr() | 새 인스턴스를 초기화합니다. [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/) 클래스.<br/>            빈 생성자. |
## 속성
| 이름 | 설명 |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| 이름 | 설명 |
| :- | :- |
| recognize(images) | 이미지/문서의 텍스트를 인식합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 디렉터리, 배열, 아카이브를 지원합니다. |
| recognize(images, preset) |  |
| recognize(images, settings) | 이미지/문서의 텍스트를 인식합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 디렉터리, 배열, 아카이브를 지원합니다. |
| recognize_receipt(images) | 영수증의 텍스트를 인식합니다. |
| recognize_receipt(images, settings) | 영수증의 텍스트를 인식합니다. |
| recognize_invoice(images) | 청구서의 텍스트를 인식합니다. |
| recognize_invoice(images, settings) | 청구서의 텍스트를 인식합니다. |
| recognize_id_card(images) | ID 카드의 텍스트를 인식합니다. |
| recognize_id_card(images, settings) | ID 카드의 텍스트를 인식합니다. |
| recognize_car_plate(images) | 자동차 번호판의 텍스트를 인식합니다. |
| recognize_car_plate(images, settings) | 자동차 번호판의 텍스트를 인식합니다. |
| recognize_passport(images) | 여권의 텍스트를 인식합니다. |
| recognize_passport(images, settings) | 여권의 텍스트를 인식합니다. |
| recognize_lines(images) | 단일 텍스트 라인이 포함된 이미지를 인식합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 폴더, 배열, 아카이브를 지원합니다. |
| recognize_lines(images, settings) | 단일 텍스트 라인이 포함된 이미지를 인식합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 폴더, 배열, 아카이브를 지원합니다. |
| detect_rectangles(images) | 이미지에서 텍스트 영역을 감지합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 폴더, 배열, 아카이브를 지원합니다. |
| detect_rectangles(images, areas_type, detect_areas) | 이미지에서 텍스트 영역을 감지합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 폴더, 배열, 아카이브를 지원합니다. |
| recognize_characters(images) | 이미지에서 기호를 감지합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 폴더, 배열, 아카이브를 지원합니다. |
| recognize_characters(images, detect_areas_mode, language) | 이미지에서 기호를 감지합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 폴더, 배열, 아카이브를 지원합니다. |
| save_multipage_document(full_file_name, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results) |  |
| save_multipage_document(stream, save_format, results) |  |
| save_multipage_document(stream, save_format, results, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| recognize_fast(images) | 이미지/문서의 텍스트를 인식합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 디렉터리, 배열, 아카이브를 지원합니다. |
| recognize_handwritten_text(images) | 이미지에서 손글씨 텍스트를 인식합니다. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | 이미지의 기울기 각도를 계산합니다.<br/>            GIF, PNG, JPEG, BMP, TIFF, JFIF, 스트림, 폴더, 배열, 아카이브를 지원합니다. |
| detect_defects(images, defect_type) | 이미지에서 OCR 정확도에 크게 영향을 줄 수 있는 문제 영역을 자동으로 찾습니다.<br/>            파일, 스트림 또는 픽셀 배열로 제공되는 PNG, JPEG, BMP, TIFF, JFIF 및 GIF 이미지를 지원합니다. 대량 인식을 지원합니다. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | 이미지가 제공된 텍스트 조각을 포함하고 있는지 확인합니다. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | 두 이미지가 동일한 텍스트를 포함하고 있는지 확인합니다. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | 두 이미지의 텍스트를 비교하고 유사성을 나타내는 숫자(0~1)를 반환합니다. |
| correct_spelling(text, language, dictionary_path) | 텍스트를 교정합니다(잘못된 단어를 교체). |

### 참조

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

