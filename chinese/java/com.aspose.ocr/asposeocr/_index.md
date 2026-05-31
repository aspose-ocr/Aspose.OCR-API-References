---
title: "AsposeOCR"
second_title: "Aspose.OCR for Java API 参考"
description: "用于从图像识别文本的主类"
type: docs
weight: 10
url: /zh/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

用于从图像中识别文本的主类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | 公共构造函数。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DebugMode](#DebugMode) | 启用调试模式。 |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | 保存调试结果的目录。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | 计算图像的倾斜角度。 |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | 检查两个图像是否包含相同的文本。 |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | 检查两个图像是否包含相同的文本。 |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | 检查两个图像是否包含相同的文本。 |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 纠正文本（替换拼写错误的单词）。 |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | 纠正文本（替换拼写错误的单词）。 |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | 自动查找图像中可能显著影响 OCR 准确性的有问题区域。 |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | 分析图像并识别其中不同类型的内容区域。 |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | 分析图像上的文本以确定其所使用的语言。 |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | 检测图像上的文本区域。 |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | 检测图像上的表格区域。 |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | 检查图像是否包含提供的文本片段（不区分大小写搜索）。 |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | 检查图像是否包含提供的文本片段（不区分大小写搜索）。 |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | 检查图像是否包含提供的文本片段。 |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | 检查图像文本是否匹配提供的正则表达式。 |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | 检查图像文本是否匹配提供的正则表达式。 |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | 比较两幅图像上的文本并返回表示相似度的数值（0 到 1）。 |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | 比较两幅图像上的文本并返回表示相似度的数值（0 到 1）。 |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | 比较两幅图像上的文本并返回表示相似度的数值（0 到 1）。 |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | 识别图像，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。 |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | 识别图像，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。 |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | 识别车牌，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。 |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | 检测图像上的符号。 |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | 检测图像上的符号。 |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | 识别高质量图像上的文本。 |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | 识别提供的输入图像中的数学公式。 |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | 识别图像上的手写文本。 |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | 识别身份证，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。 |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | 识别发票，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。 |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | 识别护照并支持指定。 |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | 识别收据并支持指定，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 压缩包、URL、base64。 |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | 检测表格和结构，识别文本单元格。 |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | 允许从 RecognitionResult 对象列表获取多页文档。 |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | 允许从 RecognitionResult 对象列表获取多页文档。 |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 允许从 RecognitionResult 对象列表获取多页文档。 |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | 允许从 RecognitionResult 对象列表获取多页文档。 |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 允许从带有拼写检查校正的 RecognitionResult 对象列表获取多页文档。 |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | 允许从 RecognitionResult 对象列表获取多页文档。 |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 允许从 RecognitionResult 对象列表获取多页文档。 |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


公共构造函数。

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


启用调试模式。启用后，系统会保存中间图像处理结果，例如预处理图像和带有绘制文本行矩形的图像。

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


调试结果保存的目录。如果未设置，默认使用当前工作目录。

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


计算图像的倾斜角度。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 压缩包、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含源的容器。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - 以度为单位的倾斜角度 ArrayList [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


检查两个图像是否包含相同的文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 第一张图像的路径。 |
| fullPath2 | java.lang.String | 第二张图像的路径。 |

**Returns:**
boolean - 如果图像具有相同的文本（相似度 90%），则为 True。
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


检查两个图像是否包含相同的文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 第一张图像的路径。 |
| fullPath2 | java.lang.String | 第二张图像的路径。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 识别设置。 |

**Returns:**
boolean - 如果图像具有相同的文本（相似度 90%），则为 True。
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


检查两个图像是否包含相同的文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 第一张图像的路径。 |
| fullPath2 | java.lang.String | 第二张图像的路径。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 识别设置。 |
| ignoreCase | boolean | True - 表示不区分大小写的搜索。 |

**Returns:**
boolean - 如果图像具有相同的文本（相似度 90%），则为 True。
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


纠正文本（替换拼写错误的单词）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 用于校正的文本。 |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 要使用的字典 [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/)。 |

**Returns:**
java.lang.String - 已替换单词的文本。
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


纠正文本（替换拼写错误的单词）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 用于校正的文本。 |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 要使用的字典 [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/)。 |
| dictionaryPath | java.lang.String | 用户字典（频率字典）的完整路径。字典文件格式：UTF-8 编码的纯文本文件。单词和词频用逗号分隔，单词位于第一列，词频位于第二列。每个单词‑词频对占一行。行的定义是以换行符（"\\n"）、回车符（"\\r"）或回车紧跟换行符（"\\r\\n"）结束的字符序列。所有单词均应为小写。 |

**Returns:**
java.lang.String - 已替换单词的文本。
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


自动查找图像中可能显著影响 OCR 准确性的有问题区域。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 压缩包、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含源的容器。[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | 要识别的缺陷类型 [DefectType](../../com.aspose.ocr.models/defecttype/)。 |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - 包含已检测文本区域或行的 [DefectOutput](../../com.aspose.ocr/defectoutput/) 列表。
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


分析图像并识别其中不同类型的内容区域。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 压缩包、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含源的容器。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - 检测到的内容区域。包含 [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/) 的列表。
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


分析图像上的文本以确定其所使用的语言。这使得能够选择最合适的识别语言，并有助于后续的文本处理任务，如拼写检查或翻译。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 压缩包、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含源的容器。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - 返回按可能性排序的最可能语言列表。包含 [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/) 的列表。
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


检测图像上的文本区域。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 压缩包、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含源的容器。[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | 确定返回哪些矩形——行或段落。 |
| isDetectAreas | boolean | 启用自动文本区域检测。 |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - 包含已检测文本区域或行的 [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) 列表。
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


检测图像上的表格区域。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 压缩包、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含源的容器。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - 包含已检测表格区域的 [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) 列表。
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


检查图像是否包含提供的文本片段（不区分大小写搜索）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | java.lang.String | 图像的路径。 |
| text | java.lang.String | 用于在图像上搜索的文本片段。 |

**Returns:**
boolean - 如果图像包含文本片段则为 True；否则为 False——图像不包含文本片段。
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


检查图像是否包含提供的文本片段（不区分大小写搜索）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | java.lang.String | 图像的路径。 |
| text | java.lang.String | 用于在图像上搜索的文本片段。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 识别设置。 |

**Returns:**
boolean - 如果图像包含文本片段则为 True；否则为 False——图像不包含文本片段。
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


检查图像是否包含提供的文本片段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | java.lang.String | 图像的路径。 |
| text | java.lang.String | 用于在图像上搜索的文本片段。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 识别设置。 |
| ignoreCase | boolean | True - 表示不区分大小写的搜索。 |

**Returns:**
boolean - 如果图像包含文本片段则为 True；否则为 False——图像不包含文本片段。
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


检查图像文本是否匹配提供的正则表达式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | java.lang.String | 图像的路径。 |
| regex | java.util.regex.Pattern | java.util.regex.Pattern 对象，包含提供的模式和选项。 |

**Returns:**
boolean - 如果图像文本匹配提供的正则表达式则为 True。
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


检查图像文本是否匹配提供的正则表达式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath | java.lang.String | 图像的路径。 |
| regex | java.util.regex.Pattern | java.util.regex.Pattern 对象，包含提供的模式和选项。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 识别设置。 |

**Returns:**
boolean - 如果图像文本匹配提供的正则表达式则为 True。
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


比较两幅图像上的文本并返回表示相似度的数值（0 到 1）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 第一张图像的路径。 |
| fullPath2 | java.lang.String | 第二张图像的路径。 |

**Returns:**
float - 0 表示文本完全不同；1 表示文本完全相同。
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


比较两幅图像上的文本并返回表示相似度的数值（0 到 1）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 第一张图像的路径。 |
| fullPath2 | java.lang.String | 第二张图像的路径。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 识别设置。 |

**Returns:**
float - 0 表示文本完全不同；1 表示文本完全相同。
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


比较两幅图像上的文本并返回表示相似度的数值（0 到 1）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 第一张图像的路径。 |
| fullPath2 | java.lang.String | 第二张图像的路径。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 识别设置。 |
| ignoreCase | boolean | True - 表示不区分大小写的搜索。 |

**Returns:**
float - 0 表示文本完全不同；1 表示文本完全相同。
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


识别图像，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。实例。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


识别图像，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。实例。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


识别车牌，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。实例。 |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


检测图像中的符号。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含源的容器。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - 包含每个图像检测到的符号数据的 [Character](../../com.aspose.ocr.models/character/) ArrayList。
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


检测图像中的符号。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | 包含源的容器。[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | 确定用于区域检测的神经网络类型。 |
| language | [Language](../../com.aspose.ocr.models/language/) | OCR 使用的语言。 |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - 包含检测到的符号数据的 [Character](../../com.aspose.ocr.models/character/) ArrayList。
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


识别高质量图像上的文本。不使用自动图像倾斜校正和文本区域检测。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/) 实例。 |

**Returns:**
java.util.ArrayList<java.lang.String> - 包含已识别文本的 ArrayList。
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


识别提供的输入图像中的数学公式。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。实例。 |
| detectAreas | boolean | 如果设置为 true，则在执行识别之前自动检测并分离公式区域。如果设置为 false，则将整幅图像视为公式进行处理。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


识别图像上的手写文本。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。包含源的容器。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


识别身份证，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。实例。 |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


识别发票，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。实例。 |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


识别护照并可进行指定。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。实例。 |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


识别收据并支持指定，支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 压缩包、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。实例。 |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


检测表格及其结构，识别文本单元格。支持 GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、文件夹、数组、zip 存档、URL、base64。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。实例。 |
| language | [Language](../../com.aspose.ocr.models/language/) | 确定识别过程中使用的字母表。 |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - 包含表格中已识别文本的 OCRTablePage 列表对象。 [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


允许从 RecognitionResult 对象列表获取多页文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于以所选格式保存识别结果的 OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、PdfNoImg、Xlsx、Xml、Json、Rtf）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 列出 [RecognitionResult](../../com.aspose.ocr/recognitionresult/) 对象。 |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


允许从 RecognitionResult 对象列表获取多页文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于以所选格式保存识别结果的 OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、PdfNoImg、Xlsx、Xml、Json、Rtf）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 列出 [RecognitionResult](../../com.aspose.ocr/recognitionresult/) 对象。 |
| embeddedFontPath | java.lang.String | 可选。用户字体的完整路径。 |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


允许从 RecognitionResult 对象列表获取多页文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 用于以所选格式保存识别结果的 OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、PdfNoImg、Xlsx、Xml、Json、Rtf）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 列出 [RecognitionResult](../../com.aspose.ocr/recognitionresult/) 对象。 |
| embeddedFontPath | java.lang.String | 可选。用户字体的完整路径。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 通过降低背景图像的质量来减小 PDF 文件大小。默认情况下，保留原始图像质量。 |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


允许从 RecognitionResult 对象列表获取多页文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于以所选格式保存识别结果的带路径的文件名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、Xlsx、Xml、Json）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 列出 [RecognitionResult](../../com.aspose.ocr/recognitionresult/) 对象。 |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


允许从带有拼写检查校正的 RecognitionResult 对象列表获取多页文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于以所选格式保存识别结果的带路径的文件名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、Xlsx、Xml、Json）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 列出 [RecognitionResult](../../com.aspose.ocr/recognitionresult/) 对象。 |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) 枚举值。 |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


允许从 RecognitionResult 对象列表获取多页文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于以所选格式保存识别结果的带路径的文件名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、Xlsx、Xml、Json）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 列出 [RecognitionResult](../../com.aspose.ocr/recognitionresult/) 对象。 |
| embeddedFontPath | java.lang.String | 可选。用户字体的完整路径。 |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


允许从 RecognitionResult 对象列表获取多页文档。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于以所选格式保存识别结果的带路径的文件名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 文档格式（Docx、Txt、Pdf、Xlsx、Xml、Json）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | 列出 [RecognitionResult](../../com.aspose.ocr/recognitionresult/) 对象。 |
| embeddedFontPath | java.lang.String | 可选。用户字体的完整路径。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 通过降低背景图像的质量来减小 PDF 文件大小。默认情况下，保留原始图像质量。 |

### close() {#close}
```
public void close()
```