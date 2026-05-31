---
title: "LayoutOutput"
second_title: "Aspose.OCR for Java API 参考"
description: "图像中检测到的内容区域信息"
type: docs
weight: 15
url: /zh/java/com.aspose.ocr.models/layoutoutput/
---

**Inheritance:**
java.lang.Object
```
public class LayoutOutput
```

图像中检测到的内容区域信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LayoutOutput()](#LayoutOutput) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [captions](#captions) | 检测到的标题。 |
| [equations](#equations) | 检测到的公式。 |
| [headers](#headers) | 检测到的页眉。 |
| [images](#images) | 检测到的图片/插图。 |
| [lists](#lists) | 检测到的列表。 |
| [page](#page) | 页码。 |
| [paragraphs](#paragraphs) | 检测到的段落。 |
| [source](#source) | 文件或 URL 的完整路径（如果有）。 |
| [tables](#tables) | 检测到的表格。 |

### LayoutOutput() {#LayoutOutput}
```
public LayoutOutput()
```


### captions {#captions}
```
public ArrayList<ContentArea> captions
```


检测到的标题。

### equations {#equations}
```
public ArrayList<ContentArea> equations
```


检测到的公式。

### headers {#headers}
```
public ArrayList<ContentArea> headers
```


检测到的页眉。

### images {#images}
```
public ArrayList<ContentArea> images
```


检测到的图片/插图。

### lists {#lists}
```
public ArrayList<ContentArea> lists
```


检测到的列表。

### page {#page}
```
public int page
```


页码。

### paragraphs {#paragraphs}
```
public ArrayList<ContentArea> paragraphs
```


检测到的段落。

### source {#source}
```
public String source
```


文件或 URL 的完整路径（如果有）。对于流、字节数组、base64 为空。

### tables {#tables}
```
public ArrayList<ContentArea> tables
```


检测到的表格。

