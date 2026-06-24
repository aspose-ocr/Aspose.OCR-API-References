---
title: "OcrInput"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "用于收集所有图像/文档以进行预处理/识别的容器。"
type: docs
weight: 420
url: /zh/net/aspose.ocr/ocrinput/
---
## OcrInput class

用于收集所有图像/文档以进行预处理/识别的容器。

```csharp
public class OcrInput : IDisposable, IEnumerable<ImageData>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OcrInput](ocrinput)(InputType, PreprocessingFilter) | 构造函数，用于创建容器并设置图像/文档的类型以及用于后续预处理/识别的过滤器。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Item](../../aspose.ocr/ocrinput/item) { get; set; } | 返回有关已处理/已识别图像的信息。 |

## Methods

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.ocr/ocrinput/add#add_2)(MemoryStream) | 添加包含图像的内存流以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应。 |
| [Add](../../aspose.ocr/ocrinput/add#add_4)(string) | 添加包含图像的路径或 URI 以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应。 |
| [Add](../../aspose.ocr/ocrinput/add#add)(Color[], int, int) | 将解码后的图像添加到列表中以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应（SingleImage）。 |
| [Add](../../aspose.ocr/ocrinput/add#add_3)(MemoryStream, int, int) | 添加包含多页图像的内存流以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应。 |
| [Add](../../aspose.ocr/ocrinput/add#add_5)(string, int, int) | 添加多页图像/文档以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应。 |
| [Add](../../aspose.ocr/ocrinput/add#add_1)(byte[], int, int, PixelType) | 将解码后的图像添加到列表中以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应（SingleImage）。 |
| [AddBase64](../../aspose.ocr/ocrinput/addbase64)(string) | 添加包含图像的 base64 字符串以进行识别/处理。图像的类型必须与构造函数中指定的类型相对应。 |
| [Clear](../../aspose.ocr/ocrinput/clear)() | 将用于处理/识别的项目数量设置为 0。清空集合。 |
| [ClearFilters](../../aspose.ocr/ocrinput/clearfilters)() | 移除所有过滤器。 |
| [Count](../../aspose.ocr/ocrinput/count)() | 用于处理/识别的项目数量。 |
| [Dispose](../../aspose.ocr/ocrinput/dispose)() | 将用于处理/识别的项目数量设置为 0。清空集合。 |
| [GetEnumerator](../../aspose.ocr/ocrinput/getenumerator)() | 返回集合枚举器。 |
| [GetInputType](../../aspose.ocr/ocrinput/getinputtype)() | 允许用于识别的图像类型。 |
| [ReplaceFilters](../../aspose.ocr/ocrinput/replacefilters)(PreprocessingFilter) | 删除旧过滤器并设置新过滤器。 |

### 另见

* class [ImageData](../imagedata)
* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
