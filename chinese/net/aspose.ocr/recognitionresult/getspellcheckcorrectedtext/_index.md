---
title: GetSpellCheckCorrectedText
second_title: Aspose.OCR 适用于 .NET API 参考
description: 纠正文本，替换拼写错误的单词。
type: docs
weight: 90
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
| language | SpellCheckLanguage | 要使用的字典。 |
| dictionaryPath | String | 可选。用户字典（频率字典）的完整路径。字典文件格式：UTF-8 编码的纯文本文件。单词和词频之间以空格或制表符分隔。默认情况下，单词应位于第一列，词频位于第二列。每个单词‑词频对占一行。行的定义是以换行符（"\n"）、回车符（"\r"）或回车紧随换行符（"\r\n"）结束的字符序列。所有单词均应为小写。 |

### Return Value

已替换单词的文本。

### 另请参阅

* enum [SpellCheckLanguage](../../../aspose.ocr.spellchecker/spellchecklanguage)
* class [RecognitionResult](../../recognitionresult)
* namespace [Aspose.OCR](../../recognitionresult)
* assembly [Aspose.OCR](../../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
