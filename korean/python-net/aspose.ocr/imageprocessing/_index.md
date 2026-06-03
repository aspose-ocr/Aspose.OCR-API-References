---
title: "ImageProcessing"
second_title: "Aspose.OCR for Python via .NET API Reference"
description: 
type: docs
weight: 120
url: /ko/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Aspose OCR 라이브러리를 위한 도우미 클래스. 이미지를 전처리하고 저장할 수 있습니다.

ImageProcessing 형식은 다음 멤버를 노출합니다:
## Methods
| 이름 | 설명 |
| :- | :- |
| save(images, folder_path) | 이미지 처리를 사용하여 OCR 정확도를 향상시킵니다.<br/>            지정한 순서대로 입력 이미지에 적용될 필터 목록을 만듭니다.<br/>            필터를 생성하는 예:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            모든 필터가 필요한 것은 아닙니다. 필요한 것만 설정하십시오. |
| render(images) | 이미지 처리를 사용하여 OCR 정확도를 향상시킵니다.<br/>            지정한 순서대로 입력 이미지에 적용될 필터 목록을 만듭니다.<br/>            필터를 생성하는 예시:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            모든 필터가 필요한 것은 아닙니다. 필요한 것만 설정하십시오. |

### 참조

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

