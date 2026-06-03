---
title: "ImageProcessing"
second_title: "Aspose.OCR Python için .NET API Referansı"
description: 
type: docs
weight: 120
url: /tr/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Aspose OCR kitaplığı için yardımcı sınıf. Görüntüleri ön işleme ve kaydetmeye izin verir.

ImageProcessing türü aşağıdaki üyeleri içerir:
## Methods
| Ad | Açıklama |
| :- | :- |
| save(images, folder_path) | OCR doğruluğunu artırmak için görüntü işleme kullanın.<br/>            Girdi görüntüsüne, belirttiğiniz sırada uygulanacak filtrelerin bir listesini oluşturun.<br/>            Filtreleri oluşturma örneği:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Hepsine ihtiyacınız yok. Sadece ihtiyacınız olanları ayarlayın. |
| render(images) | OCR doğruluğunu artırmak için görüntü işleme kullanın.<br/>            Girdi görüntüsüne, belirttiğiniz sırada uygulanacak filtrelerin bir listesini oluşturun.<br/>            filtreleri oluşturma örneği:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Hepsine ihtiyacınız yok. Sadece ihtiyacınız olanları ayarlayın. |

### Ayrıca Bakınız

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

