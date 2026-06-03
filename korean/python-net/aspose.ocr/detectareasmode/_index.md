---
title: "DetectAreasMode"
second_title: "Aspose.OCR for Python via .NET API Reference"
description: 
type: docs
weight: 540
url: /ko/python-net/aspose.ocr/detectareasmode/
---

## DetectAreasMode enumeration

영역 감지에 사용되는 신경망 유형을 결정합니다.

## Members
| 멤버 이름 | 설명 |
| :- | :- |
| LEAN | 복잡한 레이아웃 지원을 생략하여 속도를 우선시하고 리소스 소비를 줄입니다. 일러스트레이션이나 서식이 없는 몇 줄의 텍스트만 있는 간단한 이미지에만 적합합니다. |
| MULTICOLUMN | 열 형식으로 된 큰 텍스트 블록을 감지합니다. 책 페이지, 기사 또는 계약서와 같은 다중 열 레이아웃에 가장 적합합니다. |
| UNIVERSAL | 이미지에서 모든 텍스트 블록을 감지하며, 사진의 희박하고 불규칙한 텍스트도 포함합니다. 표와 다중 열 레이아웃을 제외한 대부분의 이미지에 다용도로 사용할 수 있는 옵션입니다. |
| TABLE | 이미지에서 표 구조를 감지하고 개별 셀의 텍스트를 추출합니다. 스캔한 스프레드시트, 보고서 및 기타 표 기반 문서에 권장됩니다. |
| CURVED_TEXT | 이미지에서 곡선 형태의 텍스트 라인을 자동으로 곧게 펴서 인식 정확도를 높이고 더 많은 텍스트를 복구 및 추출할 수 있게 합니다. 상당한 처리 능력과 RAM이 필요합니다. |
| FORMULA |  |

### 참조

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.OCR](/ocr/python-net/)

