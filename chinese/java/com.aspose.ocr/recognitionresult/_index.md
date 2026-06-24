---
title: "RecognitionResult"
second_title: "Aspose.OCR for Java API 参考"
description: "图像识别的结果"
type: docs
weight: 26
url: /zh/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

图像识别的结果。包含带有识别信息的元素和用于导出结果的方法。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | 初始化新的实例 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [language](#language) | 图像中已识别文本的语言。 |
| [recognitionCharactersList](#recognitionCharactersList) | 识别算法找到的字符集合，按概率降序排列。 |
| [recognitionLinesResult](#recognitionLinesResult) | 获取包含行列表（矩形）的识别结果列表。 |
| [recognitionRegionsResult](#recognitionRegionsResult) | 获取包含区域列表（矩形）的识别结果列表。 |
| [recognitionText](#recognitionText) | 所有页面或单个区域的识别结果。 |
| [warnings](#warnings) | 获取或设置描述生成期间出现的非关键错误的警告消息列表。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [GetJson()](#GetJson) | 生成包含识别结果的 JSON 字符串。 |
| [GetKeywords()](#GetKeywords) | 从护照获取关键字（测试模式。 |
| [GetXml()](#GetXml) | 生成包含识别结果的 JSON 字符串。 |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | 纠正文本（替换拼写错误的单词）。 |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 纠正文本（替换拼写错误的单词）。 |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | 查找给定输入文本中拼写错误的单词并提供建议的拼写。 |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 查找给定输入文本中拼写错误的单词并提供建议的拼写。 |
| [save(String fullFileName)](#save-java.lang.String) | 将文档保存为纯文本 |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | 将文档保存为纯文本或其他文档格式。 |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | 将文档保存为纯文本或其他文档格式。 |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | 将使用英文词典校正后的文本保存为纯文本或 Microsoft Word 文本文档格式。 |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 将校正后的文本保存为纯文本或其他格式。 |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | 允许使用自定义词典进行拼写检查校正。 |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


初始化新的实例

### language {#language}
```
public Language language
```


图像中识别文本的语言。如果选择 Language.AUTO、Language.MULTILANGUAGE 或 Language.UNIVERSAL，则此值会自动确定。

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


识别算法找到的字符集合，按概率降序排列。

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


获取包含行列表（矩形）的识别结果列表。

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


获取包含区域列表（矩形）的识别结果列表。

### recognitionText {#recognitionText}
```
public String recognitionText
```


所有页面或单个区域的识别结果。

### warnings {#warnings}
```
public ArrayList<String> warnings
```


获取或设置描述生成期间出现的非关键错误的警告消息列表。

### GetJson() {#GetJson}
```
public String GetJson()
```


生成包含识别结果的 JSON 字符串。

**Returns:**
java.lang.String - 识别结果的 JSON 字符串。
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


从护照获取关键字（测试模式。仅适用于美国和马达加斯加护照）。

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - 以关键字为键、LinesResult 为值的字典。
### GetXml() {#GetXml}
```
public String GetXml()
```


生成包含识别结果的 JSON 字符串。

**Returns:**
java.lang.String - 识别结果的 XML 字符串。
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


纠正文本（替换拼写错误的单词）。

**Returns:**
java.lang.String - 校正后的识别结果字符串。默认英文词典。
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


纠正文本（替换拼写错误的单词）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 要使用的词典。 |

**Returns:**
java.lang.String - 校正后的识别结果字符串。
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


查找给定输入文本中拼写错误的单词并提供建议的拼写。默认英文词典。

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - 表示拼写错误单词的 SpellCheckError 对象的 ArrayList，包含每个错误单词的建议正确拼写列表以及编辑距离。
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


查找给定输入文本中拼写错误的单词并提供建议的拼写。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 要使用的词典。 |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - 表示拼写错误单词的 SpellCheckError 对象的 ArrayList，包含每个错误单词的建议正确拼写列表以及编辑距离。




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


将文档保存为纯文本

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于保存识别结果的带路径的文件名 |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


将文档保存为纯文本或其他文档格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于保存识别结果的带路径的文件名。 |
| format | [Format](../../com.aspose.ocr.models/format/) | 文档格式的枚举类型 Format。 |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


将文档保存为纯文本或其他文档格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于保存识别结果的带路径的文件名。 |
| format | [Format](../../com.aspose.ocr.models/format/) | 文档格式的枚举类型 Format。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 通过降低背景图像的质量来减小 PDF 文件大小。默认情况下，保留原始图像质量。 |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


将使用英文词典校正后的文本保存为纯文本或 Microsoft Word 文本文档格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于保存识别结果的带路径的文件名。 |
| format | [Format](../../com.aspose.ocr.models/format/) | 文档格式的枚举类型 Format。 |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


将校正后的文本保存为纯文本或其他格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fullFileName | java.lang.String | 用于保存识别结果的带路径的文件名。 |
| format | [Format](../../com.aspose.ocr.models/format/) | 文档格式的枚举类型 Format。 |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 拼写检查用的词典。 |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


允许使用自定义词典进行拼写检查校正。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dictionaryPath | java.lang.String | 用户字典（频率字典）的完整路径。字典文件格式：UTF-8 编码的纯文本文件。单词和词频用逗号分隔，单词位于第一列，词频位于第二列。每个单词‑词频对占一行。行的定义是以换行符（"\\n"）、回车符（"\\r"）或回车紧跟换行符（"\\r\\n"）结束的字符序列。所有单词均应为小写。 |
