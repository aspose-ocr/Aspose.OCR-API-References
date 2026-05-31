---
title: "InvoiceRecognitionSettings"
second_title: "Aspose.OCR for Java API 参考"
description: "发票识别的设置包含允许自定义识别过程的元素。"
type: docs
weight: 17
url: /zh/java/com.aspose.ocr/invoicerecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class InvoiceRecognitionSettings extends ReceiptRecognitionSettings
```

发票识别的设置包含允许自定义识别过程的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [InvoiceRecognitionSettings()](#InvoiceRecognitionSettings) | 默认构造函数：将 autoSkew 设置为 true。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | 允许的字符集合。 |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | 允许的字符集合。 |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | 检测暗色/黑色背景上白色文字的图像，并自动为其选择专用的 OCR 算法。 |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | 设置识别符号的黑名单。 |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | 指定文本识别的语言检测级别。 |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | 获取或设置处理的线程数。 |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | 允许您专门用于小字体识别的额外算法。 |
### InvoiceRecognitionSettings() {#InvoiceRecognitionSettings}
```
public InvoiceRecognitionSettings()
```


默认构造函数：将 autoSkew 设置为 true。



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
| allowedCharacters | java.lang.String | 包含字符数组。 |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


检测暗色/黑色背景上白色文字的图像，并自动为其选择专用的 OCR 算法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| automaticColorInversion | boolean | 包含布尔值 - 已设置 automaticColorInversion。 |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | 用于设置级别的枚举值（Paragraph、Word、Page）。 |

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
