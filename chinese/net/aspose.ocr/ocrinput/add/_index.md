---
title: Add
second_title: Aspose.OCR 适用于 .NET API 参考
description: 添加包含图像的路径或 URI 以进行识别/处理。图像的类型必须与构造函数中指定的类型相匹配。
type: docs
weight: 30
url: /zh/net/aspose.ocr/ocrinput/add/
---
## Add(string) {#add_4}

添加包含图像的路径或 URI 以进行识别/处理。图像的类型必须与构造函数中指定的类型相匹配。

```csharp
public void Add(string fullPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | String | Path to the image/ document / folder / archive. |

### 另请参阅

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(MemoryStream) {#add_2}

添加包含图像的内存流以进行识别/处理。图像的类型必须与构造函数中指定的类型相匹配。

```csharp
public void Add(MemoryStream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | MemoryStream | Memory stream containing the image or document. |

### 另请参阅

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(string, int, int) {#add_5}

添加多页图像/文档以进行识别/处理。图像的类型必须与构造函数中指定的类型相匹配。

```csharp
public void Add(string fullPath, int startPage, int pagesCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | String | Path to the image/ document / folder / archive. |
| startPage | Int32 | The first page/image for processing / recognition. Use for documents, zip, folders. |
| pagesCount | Int32 | The total amount of pages/images for processing / recognition. Use for documents, zip, folders. Default = 1. |

### 另请参阅

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(MemoryStream, int, int) {#add_3}

添加包含多页图像的内存流以进行识别/处理。图像的类型必须与构造函数中指定的类型相匹配。

```csharp
public void Add(MemoryStream stream, int startPage, int pagesCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | MemoryStream | Memory stream containing the multipage document. |
| startPage | Int32 | The first page/image for processing / recognition. Use for documents. |
| pagesCount | Int32 | The total amount of pages/images for processing / recognition. Use for documents. Default = 1. |

### 另请参阅

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(byte[], int, int, PixelType) {#add_1}

将解码后的图像添加到列表中以进行识别/处理。图像的类型必须与构造函数中指定的类型（SingleImage）相匹配。

```csharp
public void Add(byte[] arr, int width, int height, PixelType pixelFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arr | Byte[] | 已解码的图像以 Aspose.Drawing.Color 数组形式呈现。 |
| width | Int32 | 图像宽度。 |
| 高度 | Int32 | 图像高度。 |
| 像素格式 | PixelType | 支持 byte、rgb、bgr、rgba。 |

### 另请参阅

* enum [PixelType](../../pixeltype)
* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

---

## Add(Color[], int, int) {#add}

将解码后的图像添加到列表中以进行识别/处理。图像的类型必须与构造函数中指定的类型（SingleImage）相匹配。

```csharp
public void Add(Color[] imageData, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageData | Color[] | 已解码的图像以 Aspose.Drawing.Color 数组形式呈现。 |
| width | Int32 | 图像宽度。 |
| 高度 | Int32 | 图像高度。 |

### 另请参阅

* class [OcrInput](../../ocrinput)
* namespace [Aspose.OCR](../../ocrinput)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
