---
title: "RecognizeMultipleImages"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "从列表中识别多个图像。不支持归档和文件夹。最大处理图像数量为 20。支持 GIF、PNG、JPEG、BMP、TIFF、JFIF。"
type: docs
weight: 200
url: /zh/net/aspose.ocr/asposeocr/recognizemultipleimages/
---
## RecognizeMultipleImages(List&lt;string&gt;, RecognitionSettings) {#recognizemultipleimages_1}

从列表中识别多个图像。不支持归档和文件夹。最大处理图像数量为 20。支持 GIF、PNG、JPEG、BMP、TIFF、JFIF。

```csharp
public List<RecognitionResult> RecognizeMultipleImages(List<string> files, 
    RecognitionSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件 | List`1 | 图像的完整路径。 |
| settings | RecognitionSettings | 识别设置。 |

### 返回值

包含每个处理后图像的识别结果的[`RecognitionResult`](../../recognitionresult)对象数组。

### 另见

* class [RecognitionResult](../../recognitionresult)
* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizeMultipleImages(List&lt;string&gt;) {#recognizemultipleimages}

使用默认设置识别列表中的多张图像。 不支持存档和文件夹。 最大处理图像数量为 20。 支持 GIF、PNG、JPEG、BMP、TIFF、JFIF。

```csharp
public List<RecognitionResult> RecognizeMultipleImages(List<string> files)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件 | List`1 | 图像的完整路径。 |

### 返回值

包含每个处理后图像的识别结果的[`RecognitionResult`](../../recognitionresult)对象数组。

### 另见

* class [RecognitionResult](../../recognitionresult)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizeMultipleImages(string, RecognitionSettings) {#recognizemultipleimages_3}

识别压缩为 ZIP 存档或位于文件夹中的多张图像。 不支持嵌套存档和文件夹。 最大处理图像数量为 20。 支持 GIF、PNG、JPEG、BMP、TIFF、JFIF。

```csharp
public List<RecognitionResult> RecognizeMultipleImages(string path, RecognitionSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | ZIP 存档的完整路径（包括 .zip 扩展名）或图像文件夹的完整路径。 |
| settings | RecognitionSettings | 识别设置。 |

### 返回值

包含每个处理后图像的识别结果的[`RecognitionResult`](../../recognitionresult)对象数组。

### 另见

* class [RecognitionResult](../../recognitionresult)
* class [RecognitionSettings](../../recognitionsettings)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

---

## RecognizeMultipleImages(string) {#recognizemultipleimages_2}

使用默认设置识别压缩为 ZIP 存档或位于文件夹中的多张图像。 不支持嵌套存档和文件夹。 最大处理图像数量为 20。 支持 GIF、PNG、JPEG、BMP、TIFF、JFIF。

```csharp
public List<RecognitionResult> RecognizeMultipleImages(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | String | ZIP 存档的完整路径（包括 .zip 扩展名）或图像文件夹的完整路径。 |

### 返回值

包含每个处理后图像的识别结果的[`RecognitionResult`](../../recognitionresult)对象数组。

### 另见

* class [RecognitionResult](../../recognitionresult)
* class [AsposeOcr](../../asposeocr)
* namespace [Aspose.OCR](../../asposeocr)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
