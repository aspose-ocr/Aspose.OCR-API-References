---
title: "LayoutOutput"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "画像内で検出されたコンテンツ領域に関する情報"
type: docs
weight: 15
url: /ja/java/com.aspose.ocr.models/layoutoutput/
---

**Inheritance:**
java.lang.Object
```
public class LayoutOutput
```

画像内で検出されたコンテンツ領域に関する情報。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LayoutOutput()](#LayoutOutput) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [captions](#captions) | 検出されたキャプション。 |
| [equations](#equations) | 検出された数式。 |
| [headers](#headers) | 検出されたヘッダー。 |
| [images](#images) | 検出された画像/イラスト。 |
| [lists](#lists) | 検出されたリスト。 |
| [page](#page) | ページ番号です。 |
| [paragraphs](#paragraphs) | 検出された段落。 |
| [source](#source) | ファイルまたは URL のフルパス（該当する場合）。 |
| [tables](#tables) | 検出された表。 |

### LayoutOutput() {#LayoutOutput}
```
public LayoutOutput()
```


### captions {#captions}
```
public ArrayList<ContentArea> captions
```


検出されたキャプション。

### equations {#equations}
```
public ArrayList<ContentArea> equations
```


検出された数式。

### headers {#headers}
```
public ArrayList<ContentArea> headers
```


検出されたヘッダー。

### images {#images}
```
public ArrayList<ContentArea> images
```


検出された画像/イラスト。

### lists {#lists}
```
public ArrayList<ContentArea> lists
```


検出されたリスト。

### page {#page}
```
public int page
```


ページ番号です。

### paragraphs {#paragraphs}
```
public ArrayList<ContentArea> paragraphs
```


検出された段落。

### source {#source}
```
public String source
```


ファイルまたは URL の完全パス（該当する場合）。ストリーム、バイト配列、Base64 の場合は空です。

### tables {#tables}
```
public ArrayList<ContentArea> tables
```


検出された表。

