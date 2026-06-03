---
title: "PreprocessingFilter"
second_title: "Aspose.OCR for Python via .NET API Reference"
description: 
type: docs
weight: 10
url: /ko/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

이미지 처리 명령에 대한 기본 클래스입니다.

PreprocessingFilter 유형은 다음 멤버를 제공합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PreprocessingFilter() | PreprocessingFilter 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| 기본 | 기본 필터 컬렉션에는 AutoSkew 필터가 포함됩니다 |
| empty | 빈 필터 컬렉션 |
## Methods
| 이름 | 설명 |
| :- | :- |
| binarize() | 이미지를 흑백 이미지로 변환합니다.<br/>            이진 이미지는 픽셀의 강도 값이 두 가지만 가능한 이미지입니다. <br/>            일반적으로 흑백으로 표시됩니다. 수치적으로 두 값은 보통 검은색은 0, 흰색은 255입니다.<br/>            이진 이미지는 이미지에 자동 임계값을 적용하여 생성됩니다. |
| binarize(area) | 이미지의 일부를 흑백 이미지로 변환합니다.<br/>            이진 이미지는 픽셀의 강도 값이 두 가지만 가능한 이미지입니다. <br/>            일반적으로 흑백으로 표시됩니다. 수치적으로 두 값은 보통 검은색은 0, 흰색은 255입니다.<br/>            이진 이미지는 이미지에 자동 임계값을 적용하여 생성됩니다. |
| resize(width, height, type) | 이미지를 재조정합니다 - 이미지 해상도를 확대하거나 축소합니다. |
| resize(width, height) | 이미지를 재조정합니다 - 이미지 해상도를 확대하거나 축소합니다. |
| dilate() | 팽창은 이미지 내 객체의 경계에 픽셀을 추가합니다. |
| dilate(area) | 팽창은 이미지의 일부에 있는 객체 경계에 픽셀을 추가합니다. |
| invert() | 문서 이미지의 색상을 자동으로 반전시킵니다. |
| invert(area) | 이미지의 일부 색상을 자동으로 반전시킵니다. |
| rotate(angle) | 원본 이미지를 회전합니다. |
| rotate(angle, area) | 이미지의 일부를 회전합니다. |
| scale(ratio) | 이미지 크기 조정 - 이미지 해상도를 확대하거나 축소합니다.<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | 이미지를 재조정합니다 - 이미지 해상도를 확대하거나 축소합니다. |
| threshold(value) | 원본 이미지의 픽셀 강도에 임계값을 설정하여 이진 이미지를 생성합니다. |
| threshold(value, area) | 원본 이미지 부분의 픽셀 강도에 임계값을 설정하여 이미지의 이진 부분을 생성합니다. |
| median() | 중간값 필터는 이미지의 각 요소를 순회하며 각 픽셀을 인접 픽셀들의 중간값으로 교체합니다. |
| median(area) | 중간값 필터는 이미지 부분의 각 요소를 순회하며 각 픽셀을 인접 픽셀들의 중간값으로 교체합니다. |
| auto_denoising() | 추가 신경망을 사용하여 이미지를 개선하고 노이즈를 감소시킵니다.<br/>            스캔 아티팩트, 왜곡, 점, 플레어, 그라디언트, 외부 요소가 있는 이미지에 유용합니다. |
| auto_denoising(area) | 추가 신경망을 사용하여 이미지 부분을 개선하고 노이즈를 감소시킵니다.<br/>            스캔 아티팩트, 왜곡, 점, 플레어, 그라디언트, 외부 요소가 있는 이미지에 유용합니다. |
| auto_skew() | 자동 이미지 기울기 보정을 활성화합니다. |
| auto_skew(area) | 자동 이미지 부분 기울기 보정을 활성화합니다. |
| contrast_correction_filter() | 대비 보정 필터. |
| contrast_correction_filter(area) | 이미지 부분에 대한 대비 보정 필터. |
| to_grayscale() | 이미지를 그레이스케일 이미지로 변환합니다.<br/>            그레이스케일 이미지는 이미지 내에 256 단계의 밝기(0~255)를 가집니다. |
| auto_dewarping() | 이미지의 기하학적 왜곡을 자동으로 교정합니다.<br/>            매우 높은 리소스를 사용합니다! |
| add(filter) | 새 필터를 컬렉션에 추가하여 모든 작업을 계속 실행합니다.<br/>            컬렉션의 일관성이 중요합니다. |

### 참조

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

