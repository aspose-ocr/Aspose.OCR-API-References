---
title: "GetSpellCheckCorrectedText"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "纠正文本，替换拼写错误的单词。"
type: docs
weight: 120
url: /zh/net/aspose.ocr/recognitionresult/getspellcheckcorrectedtext/
---
## RecognitionResult.GetSpellCheckCorrectedText method

纠正文本（替换拼写错误的单词）。

```csharp
public string GetSpellCheckCorrectedText(SpellCheckLanguage language = SpellCheckLanguage.Eng, 
    string dictionaryPath = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| language | SpellCheckLanguage | 使用的词典。 |
| dictionaryPath | String | 可选。用户词典（频率词典）的完整路径。词典文件格式：UTF-8 编码的纯文本文件。单词和词频以空格或制表符分隔。默认情况下，单词应位于第一列，频率位于第二列。每个单词-频率对占一行。行定义为以换行符（"\n"）、回车符（"\r"）或回车紧跟换行符（"\r\n"）结束的字符序列。所有单词应为小写。 |

### 返回值

已替换单词的文本。

### 另见

* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
