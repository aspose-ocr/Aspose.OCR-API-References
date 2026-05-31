---
title: "PdfOptimizationMode"
second_title: "Aspose.OCR for Java API 参考"
description: "显著减小 PDF 文件大小，代价是降低图像质量。"
type: docs
weight: 27
url: /zh/java/com.aspose.ocr.models/pdfoptimizationmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfOptimizationMode extends Enum<PdfOptimizationMode>
```

显著减小 PDF 文件大小，但会降低图像质量。

指定已保存 PDF 的文件大小与图像质量之间的平衡。
## 字段

| 字段 | 描述 |
| --- | --- |
| [AGGRESSIVE](#AGGRESSIVE) | 显著减小 PDF 文件大小，但会降低图像质量。 |
| [BALANCED](#BALANCED) | 对图像进行降采样，以平衡文件大小和图像质量。 |
| [HIGH_QUALITY](#HIGH-QUALITY) | 以轻微的图像降采样为代价，获得更小的 PDF 文件大小。 |
| [MAXIMUM_QUALITY](#MAXIMUM-QUALITY) | 在保持最高图像质量的同时优化文件大小。 |
| [NONE](#NONE) | 不优化 PDF 大小。 |

### AGGRESSIVE {#AGGRESSIVE}
```
public static final PdfOptimizationMode AGGRESSIVE
```


显著减小 PDF 文件大小，但会降低图像质量。

### BALANCED {#BALANCED}
```
public static final PdfOptimizationMode BALANCED
```


对图像进行降采样，以平衡文件大小和图像质量。

### HIGH_QUALITY {#HIGH-QUALITY}
```
public static final PdfOptimizationMode HIGH_QUALITY
```


以轻微的图像降采样为代价，获得更小的 PDF 文件大小。

### MAXIMUM_QUALITY {#MAXIMUM-QUALITY}
```
public static final PdfOptimizationMode MAXIMUM_QUALITY
```


在保持最高图像质量的同时优化文件大小。

### NONE {#NONE}
```
public static final PdfOptimizationMode NONE
```


不优化 PDF 大小。
