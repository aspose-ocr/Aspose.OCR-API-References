---
title: "ImageProcessing"
second_title: "Справочник API Aspose.OCR для Python через .NET"
description: 
type: docs
weight: 120
url: /ru/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Вспомогательный класс для библиотеки Aspose OCR. Позволяет предварительно обрабатывать и сохранять изображения.

Тип ImageProcessing раскрывает следующие члены:
## Методы
| Имя | Описание |
| :- | :- |
| save(images, folder_path) | Используйте обработку изображений для повышения точности OCR.<br/>            Создайте список фильтров, которые будут применяться к входному изображению в указанном порядке.<br/>            Пример создания фильтров:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Вам не нужны все из них. Установите только необходимые. |
| render(images) | Используйте обработку изображений для повышения точности OCR.<br/>            Создайте список фильтров, которые будут применяться к входному изображению в указанном порядке.<br/>            пример создания фильтров:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Вам не нужны все из них. Установите только необходимые. |

### См. также

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

