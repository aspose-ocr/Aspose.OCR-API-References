---
title: "RecognizePdf"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "从扫描的 PDF 中识别文本并提取图像。能够指定 DocumentRecognitionSettingsaspose.ocr/documentrecognitionsettings 来识别 PDF 文件。仅支持扫描的 PDF。不支持可搜索的 PDF。"
type: docs
weight: 220
url: /zh/net/aspose.ocr/asposeocr/recognizepdf/
---
## RecognizePdf(string, DocumentRecognitionSettings) {#recognizepdf_1}

从扫描的 PDF（提取图像）中识别文本。能够指定 [`DocumentRecognitionSettings`](../../documentrecognitionsettings) 来识别 PDF 文件。仅支持扫描的 PDF。不支持可搜索的 PDF。

```csharp
public List<RecognitionResult> RecognizePdf(string fullPath, DocumentRecognitionSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | String | 图像的完整路径。 |
| settings | DocumentRecognitionSettings | 识别设置。 |

### 返回值

[`RecognitionResult`](../../recognitionresult) 对象，包含图像识别结果。

### 另见

* class [RecognitionResult](../../recognitionresult)
* class [DocumentRecognitionSettings](../../documentrecognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizePdf(MemoryStream, DocumentRecognitionSettings) {#recognizepdf}

从扫描的 PDF（提取图像）中识别文本。能够指定 [`RecognitionSettings`](../../recognitionsettings) 来识别 PDF 文件。仅支持扫描的 PDF。不支持可搜索的 PDF。

```csharp
public List<RecognitionResult> RecognizePdf(MemoryStream stream, 
    DocumentRecognitionSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | MemoryStream | 包含 PDF 文件的内存流。 |
| settings | DocumentRecognitionSettings | 识别设置。 |

### 返回值

[`RecognitionResult`](../../recognitionresult) 对象，包含图像识别结果。

### 另见

* class [RecognitionResult](../../recognitionresult)
* class [DocumentRecognitionSettings](../../documentrecognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
