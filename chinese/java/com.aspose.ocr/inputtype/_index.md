---
title: "输入类型"
second_title: "Aspose.OCR for Java API 参考"
description: "用于处理/识别的图像/文档类型"
type: docs
weight: 38
url: /zh/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

用于处理/识别的图像/文档类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Base64](#Base64) | 包含图像的 base64 字符串或指向包含 base64 内容的 .txt 文件的路径。 |
| [Directory](#Directory) | 目录路径。 |
| [PDF](#PDF) | 从文件或 InputStream 中的扫描 PDF 文档。 |
| [SingleImage](#SingleImage) | 支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、InputStream、BufferedImage。 |
| [TIFF](#TIFF) | 从文件或 InputStream 中的多页 TIFF、TIF 文档。 |
| [URL](#URL) | 图像链接。 |
| [Zip](#Zip) | ZIP 存档的完整名称。 |

### Base64 {#Base64}
```
public static final InputType Base64
```


包含图像的 base64 字符串或指向包含 base64 内容的 .txt 文件的路径。支持 GIF、PNG、JPEG、BMP、TIFF。

### Directory {#Directory}
```
public static final InputType Directory
```


目录路径。不支持嵌套存档和文件夹。支持 GIF、PNG、JPEG、BMP、TIFF。默认处理的图像数量为全部。

### PDF {#PDF}
```
public static final InputType PDF
```


从文件或 InputStream 中的扫描 PDF 文档。

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、InputStream、BufferedImage。

### TIFF {#TIFF}
```
public static final InputType TIFF
```


从文件或 InputStream 中的多页 TIFF、TIF 文档。

### URL {#URL}
```
public static final InputType URL
```


图像链接。支持 GIF、PNG、JPEG、BMP、TIFF。

### Zip {#Zip}
```
public static final InputType Zip
```


ZIP 存档的完整名称。不支持嵌套存档和文件夹。支持 GIF、PNG、JPEG、BMP、TIFF、JFIF。默认处理的图像数量为全部。
