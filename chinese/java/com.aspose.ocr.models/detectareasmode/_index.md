---
title: "DetectAreasMode"
second_title: "Aspose.OCR for Java API 参考"
description: 
type: docs
weight: 28
url: /zh/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## 字段

| 字段 | 描述 |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | 自动校正图像中弯曲的文字行，提高识别准确率，并允许恢复和提取更多文本。 |
| [FORMULA](#FORMULA) | 检测所有包含数学公式的块。 |
| [LEAN](#LEAN) | 通过省略对复杂布局的支持，优先考虑速度并降低资源消耗。 |
| [MULTICOLUMN](#MULTICOLUMN) | 检测以列格式排列的大块文本。 |
| [TABLE](#TABLE) | 检测图像中的表格结构并提取各单元格中的文本。 |
| [UNIVERSAL](#UNIVERSAL) | 检测图像中的所有文本块，包括照片上稀疏和不规则的文字。 |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


自动校正图像中弯曲的文字行，提高识别准确率，并允许恢复和提取更多文本。需要大量的处理能力和内存。

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


检测所有包含数学公式的块。

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


通过省略对复杂布局的支持，优先考虑速度并降低资源消耗。仅适用于仅包含少量文字且无插图或格式的简易图像。

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


检测以列格式排列的大块文本。是书页、文章或合同等多列布局的最佳选择。

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


检测图像中的表格结构并提取各单元格中的文本。推荐用于扫描的电子表格、报告及其他基于表格的文档。

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


检测图像中的所有文本块，包括照片上稀疏和不规则的文字。是除表格和多列布局外大多数图像的通用选项。

