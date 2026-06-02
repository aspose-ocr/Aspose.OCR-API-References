---
title: "GetSpellCheckErrorList"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "查找给定输入文本中拼写错误的单词并提供建议拼写。"
type: docs
weight: 130
url: /zh/net/aspose.ocr/recognitionresult/getspellcheckerrorlist/
---
## RecognitionResult.GetSpellCheckErrorList method

查找给定输入文本中拼写错误的单词并提供建议拼写。

```csharp
public List<SpellCheckError> GetSpellCheckErrorList(
    SpellCheckLanguage language = SpellCheckLanguage.Eng, string dictionaryPath = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| language | SpellCheckLanguage | 使用的词典。 |
| dictionaryPath | String | 可选。用户词典（频率词典）的完整路径。词典文件格式：UTF-8 编码的纯文本文件。单词和词频之间用空格或制表符分隔。默认情况下，单词应位于第一列，词频位于第二列。每个单词-词频对占一行。行的定义是以换行符（"\n"）、回车符（"\r"）或回车紧跟换行符（"\r\n"）结束的字符序列。所有单词应为小写。 |

### 返回值

一个 SpellCheckError 对象列表，表示拼写错误的单词，并为每个拼写错误的单词提供建议的正确拼写列表以及编辑距离。

### 另见

* struct [SpellCheckError](../../../aspose.ocr.spellchecker/spellcheckerror)
* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
