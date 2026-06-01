---
title: "LanguageDetectionOutput"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "画像テキストで検出された言語"
type: docs
weight: 14
url: /ja/java/com.aspose.ocr.models/languagedetectionoutput/
---

**Inheritance:**
java.lang.Object
```
public class LanguageDetectionOutput
```

画像テキストで検出された言語。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)](#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [languages](#languages) | 画像テキストで検出された言語のリストで、可能性の高い順にランク付けされています。 |
| [page](#page) | ページ番号です。 |
| [source](#source) | ファイルまたは URL のフルパス（該当する場合）。 |

### LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page) {#LanguageDetectionOutput-java.lang.String-java.util.List-java.util.Map.Entry-com.aspose.ocr.models.Language-java.lang.Float---int}
```
public LanguageDetectionOutput(String _source, List<Map.Entry<Language,Float>> _languages, int _page)
```


**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| _source | java.lang.String |  |
| _languages | java.util.List<java.util.Map.Entry<com.aspose.ocr.models.Language,java.lang.Float>> |  |
| _page | int |  |

### languages {#languages}
```
public List<Map.Entry<Language,Float>> languages
```


画像テキストで検出された言語のリストで、可能性の高い順にランク付けされています。

### page {#page}
```
public int page
```


ページ番号です。

### source {#source}
```
public String source
```


ファイルまたは URL の完全パス（該当する場合）。ストリーム、バイト配列、Base64 の場合は空です。

