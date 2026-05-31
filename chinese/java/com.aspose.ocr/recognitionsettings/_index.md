---
title: "RecognitionSettings"
second_title: "Aspose.OCR for Java API 参考"
description: "图像识别的设置"
type: docs
weight: 27
url: /zh/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

图像识别的设置。包含允许自定义识别过程的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | 默认构造函数：将 recognitionAreas 设置为 null，linesFiltration 为 false，autoSkew 为 false，recognizeSingleLine 为 false。 |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | 构造函数允许设置所有选项。 |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | 构造函数允许设置 recognizeSingleLine。 |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | 允许的字符集合。 |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | 允许的字符集合。 |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | 检测暗色/黑色背景上白色文字的图像，并自动为其选择专用的 OCR 算法。 |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | 确定用于区域检测的神经网络类型。 |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | 设置识别符号的黑名单。 |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | 指定文本识别的语言检测级别。 |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | 允许识别表格中的文本（被线围绕的区域）。 |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | 设置用于处理的文本区域列表。 |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | 设置单行图像识别。 |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | 获取或设置处理的线程数。 |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | 允许您专门用于小字体识别的额外算法。 |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


默认构造函数：将 recognitionAreas 设置为 null，linesFiltration 为 false，autoSkew 为 false，recognizeSingleLine 为 false。

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


构造函数允许设置所有选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | 用于识别的矩形。 |
| recognizeSingleLine | boolean | 如果图像仅包含一行，则为 True。 |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


构造函数允许设置 recognizeSingleLine。此情况下的默认值：detectAreas - false，autoSkew = false，recognitionAreas - null。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognizeSingleLine | boolean | 如果图像仅包含一行，则为 True。 |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


允许字符集。确定识别结果中允许的字符类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | 包含枚举 @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) 值。 |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


允许字符集。确定识别结果中允许的字符数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| allowedCharacters | java.lang.String | 包含字符字符串。 |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


检测暗色/黑色背景上白色文字的图像，并自动为其选择专用的 OCR 算法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| automaticColorInversion | boolean | 包含布尔值 - 已设置 automaticColorInversion。默认为 True。 |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


确定用于区域检测的神经网络类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | 包含枚举 @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) 值。 |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


设置识别符号的黑名单。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| characters | java.lang.String | 从识别中排除的字符。 |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | 设置用于 OCR 的语言。默认是多语言（无）。 |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


指定文本识别的语言检测级别。仅在所选语言为 Language.MULTILANGUAGE、Language.AUTO 或 Language.UNIVERSAL 时有效。此过程耗时且会显著减慢整体识别速度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


允许识别表格中的文本（被线围绕的区域）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| linesFiltration | boolean | false - 允许提升性能并且不检测表格和删除线；否则为 true。默认禁用 (false)。 |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


设置用于处理的文本区域列表。允许手动指定带文本的区域以获得更精确的识别。如果自定义区域已设置 [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} 不是 NONE，或 [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} 属性将被忽略。禁用 DetectAreas 和 AutoSkew。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | 用于识别的矩形。 |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


设置单行图像识别。默认禁用 (false)。禁用所有与行拆分相关的处理步骤。如果图像仅包含一行，请将此参数设为 true。禁用 [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList) 设置，所有区域设置将被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognizeSingleLine | boolean | 单行图像为 True |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


获取或设置处理的线程数。默认情况下，0 表示图像将使用等于处理器数量的线程进行处理。ThreadsCount = 1 表示图像将在主线程中处理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threadsCount | int | 将为图像片段的并行识别创建的线程数。 |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


允许您专门用于小字体识别的额外算法。对包含小尺寸字符的图像很有用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| upscaleSmallFont | boolean | 包含布尔值 - 已设置 upscaleSmallFont。 |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String