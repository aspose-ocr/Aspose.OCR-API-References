---
title: "OcrOutput"
second_title: "Aspose.OCR for Java API 参考"
description: 
type: docs
weight: 21
url: /zh/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OcrOutput()](#OcrOutput) | 使用空集合初始化 OcrOutput 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |

| [getTableData()](#getTableData) | 返回从所有已识别页面提取的结构化表格数据。 |
| [save(OutputStream stream)](#save-java.io.OutputStream) | 将所有识别结果以指定格式保存到内存流中。 |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | 将所有识别结果以指定格式保存到内存流中。 |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 将所有识别结果以指定格式保存到内存流中。 |
| [save(String fullFileName)](#save-java.lang.String) | 将所有识别结果保存到文件中。 |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | 将所有识别结果保存到文件中。 |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 将所有识别结果保存到文件中。 |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | 将所有识别结果保存到内存中的可搜索 PDF 文档中，并将原始图像嵌入为背景。 |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 将所有识别结果保存到内存中的可搜索 PDF 文档中，并将原始图像嵌入为背景。 |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | 将所有识别结果保存到可搜索的 PDF 文件中，原始图像设置为背景。 |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 将所有识别结果保存到可搜索的 PDF 文件中，原始图像设置为背景。 |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


返回从所有已识别页面提取的结构化表格数据。

每页包含行，每行包含带有识别文本和可选位置信息的单元格。

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


将所有识别结果以指定格式保存到内存流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于以选定格式保存识别结果的 OutputStream。 |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


将所有识别结果以指定格式保存到内存流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于以选定格式保存识别结果的 OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、Xlsx、Rtf、Json、Xml、Epub）。 |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


将所有识别结果以指定格式保存到内存流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于以选定格式保存识别结果的 OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、Xlsx、Rtf、Json、Xml、Epub）。 |
| embeddedFontPath | java.lang.String | 可选。用户字体的完整路径。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 通过降低背景图像的质量来减小 PDF 文件大小。默认情况下，保留原始图像质量。 |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


将所有识别结果保存到文件中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于在选定格式中保存识别结果的带路径的文件名。 |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


将所有识别结果保存到文件中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于在选定格式中保存识别结果的带路径的文件名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、Xlsx、Rtf、Json、Xml、Epub）。 |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


将所有识别结果保存到文件中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于在选定格式中保存识别结果的带路径的文件名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、Xlsx、Rtf、Json、Xml、Epub）。 |
| embeddedFontPath | java.lang.String | 可选。用户字体的完整路径。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 通过降低背景图像的质量来减小 PDF 文件大小。默认情况下，保留原始图像质量。 |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


将所有识别结果保存到内存中的可搜索 PDF 文档中，并将原始图像嵌入为背景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于以选定格式保存识别结果的 OutputStream。 |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


将所有识别结果保存到内存中的可搜索 PDF 文档中，并将原始图像嵌入为背景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于以选定格式保存识别结果的 OutputStream。 |
| embeddedFontPath | java.lang.String | 可选。用户字体的完整路径。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 通过降低背景图像的质量来减小 PDF 文件大小。默认情况下，保留原始图像质量。 |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


将所有识别结果保存到可搜索的 PDF 文件中，原始图像设置为背景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于在选定格式中保存识别结果的带路径的文件名。 |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


将所有识别结果保存到可搜索的 PDF 文件中，原始图像设置为背景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于在选定格式中保存识别结果的带路径的文件名。 |
| embeddedFontPath | java.lang.String | 可选。用户字体的完整路径。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 通过降低背景图像的质量来减小 PDF 文件大小。默认情况下，保留原始图像质量。 |

### size() {#size}
```
public int size()
```




**Returns:**
int
