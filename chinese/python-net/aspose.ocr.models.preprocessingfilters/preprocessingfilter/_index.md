---
title: "PreprocessingFilter"
second_title: "适用于 Python via .NET 的 Aspose.OCR API 参考"
description: 
type: docs
weight: 10
url: /zh/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

图像处理命令的基类。

该 PreprocessingFilter 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| PreprocessingFilter() | 初始化 PreprocessingFilter 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| 默认 | 默认过滤器集合包含 AutoSkew 过滤器 |
| empty | 空的过滤器集合 |
## Methods
| 名称 | 描述 |
| :- | :- |
| binarize() | 将图像转换为黑白图像。<br/>            二值图像是像素仅具有两种可能强度值的图像。 <br/>            它们通常显示为黑白。数值上，这两个值通常分别为 0 表示黑色，255 表示白色。<br/>            二值图像是通过对图像进行自动阈值处理生成的。 |
| binarize(area) | 将图像的一部分转换为黑白图像。<br/>            二值图像是像素仅具有两种可能强度值的图像。 <br/>            它们通常显示为黑白。数值上，这两个值通常分别为 0 表示黑色，255 表示白色。<br/>            二值图像是通过对图像进行自动阈值处理生成的。 |
| resize(width, height, type) | 重新缩放图像 - 放大或缩小图像分辨率。 |
| resize(width, height) | 重新缩放图像 - 放大或缩小图像分辨率。 |
| dilate() | 膨胀会向图像中对象的边界添加像素。 |
| dilate(area) | 膨胀会向图像的一部分中对象的边界添加像素。 |
| invert() | 自动反转文档图像中的颜色。 |
| invert(area) | 自动反转图像一部分的颜色。 |
| rotate(angle) | 旋转原始图像。 |
| rotate(angle, area) | 旋转图像的一部分。 |
| scale(ratio) | 重新缩放图像 - 放大或缩小图像分辨率。<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | 重新缩放图像 - 放大或缩小图像分辨率。 |
| threshold(value) | 基于对原始图像像素强度设置阈值来创建二值图像。 |
| threshold(value, area) | 基于对原始图像部分像素强度设置阈值来创建图像的二值部分。 |
| median() | 中值滤波器遍历图像的每个元素，并用其邻近像素的中值替换每个像素。 |
| median(area) | 中值滤波器遍历图像部分的每个元素，并用其邻近像素的中值替换每个像素。 |
| auto_denoising() | 启用额外神经网络来改进图像 - 降低噪声。<br/>            对于存在扫描伪影、失真、斑点、耀光、渐变、外来元素的图像非常有用。 |
| auto_denoising(area) | 启用额外神经网络来改进图像部分 - 降低噪声。<br/>            对于存在扫描伪影、失真、斑点、耀光、渐变、外来元素的图像非常有用。 |
| auto_skew() | 启用自动图像倾斜校正。 |
| auto_skew(area) | 启用自动图像部分倾斜校正。 |
| contrast_correction_filter() | 对比度校正滤波器。 |
| contrast_correction_filter(area) | 针对图像部分的对比度校正滤波器。 |
| to_grayscale() | 将图像转换为灰度图像。<br/>            灰度图像在图像中有 256 级亮度（0 到 255）。 |
| auto_dewarping() | 自动纠正图像中的几何失真。<br/>            极度占用资源！ |
| add(filter) | 将新过滤器添加到集合中，以进一步运行所有操作。<br/>            集合的一致性很重要。 |

### 另请参见

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

