---
title: "SkewOutput"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "度数で表した傾き角度とファイル名に関するデータ"
type: docs
weight: 23
url: /ja/java/com.aspose.ocr.models/skewoutput/
---

**Inheritance:**
java.lang.Object
```
public class SkewOutput
```

傾き角度（度）とファイル名に関するデータ。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SkewOutput()](#SkewOutput) |  |
| [SkewOutput(String source, double angle, int page)](#SkewOutput-java.lang.String-double-int) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Angle](#Angle) | 度数での傾き角度。 |
| [Page](#Page) | ページ番号です。 |
| [Source](#Source) | ファイルまたは URL のフルパス（該当する場合）。 |

### SkewOutput() {#SkewOutput}
```
public SkewOutput()
```


### SkewOutput(String source, double angle, int page) {#SkewOutput-java.lang.String-double-int}
```
public SkewOutput(String source, double angle, int page)
```


**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ソース | java.lang.String |  |
| 角度 | double |  |
| ページ | int |  |

### Angle {#Angle}
```
public double Angle
```


度数での傾き角度。

### Page {#Page}
```
public int Page
```


ページ番号です。

### Source {#Source}
```
public String Source
```


ファイルまたは URL の完全パス（該当する場合）。ストリーム、バイト配列、Base64 の場合は空です。
