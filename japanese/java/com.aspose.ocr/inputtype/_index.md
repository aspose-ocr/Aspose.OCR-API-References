---
title: "InputType"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "処理／認識対象の画像/ドキュメントの種類"
type: docs
weight: 38
url: /ja/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

処理/認識用の画像/ドキュメントのタイプ。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Base64](#Base64) | 画像の base64 文字列または base64 内容が記載された .txt ファイルへのパス。 |
| [Directory](#Directory) | ディレクトリへのパス。 |
| [PDF](#PDF) | ファイルまたは InputStream からのスキャン済み PDF ドキュメント。 |
| [SingleImage](#SingleImage) | GIF、PNG、JPEG、BMP、TIFF、JFIF、InputStream、BufferedImage をサポートします。 |
| [TIFF](#TIFF) | ファイルまたは InputStream からのマルチページ TIFF、TIF ドキュメント。 |
| [URL](#URL) | 画像へのリンク。 |
| [Zip](#Zip) | ZIP アーカイブのフルネーム。 |

### Base64 {#Base64}
```
public static final InputType Base64
```


画像の base64 文字列または base64 内容が記載された .txt ファイルへのパス。GIF、PNG、JPEG、BMP、TIFF をサポートします。

### Directory {#Directory}
```
public static final InputType Directory
```


ディレクトリへのパス。入れ子になったアーカイブやフォルダーはサポートされません。GIF、PNG、JPEG、BMP、TIFF をサポートします。デフォルトの処理画像数はすべてです。

### PDF {#PDF}
```
public static final InputType PDF
```


ファイルまたは InputStream からのスキャン済み PDF ドキュメント。

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


GIF、PNG、JPEG、BMP、TIFF、JFIF、InputStream、BufferedImage をサポートします。

### TIFF {#TIFF}
```
public static final InputType TIFF
```


ファイルまたは InputStream からのマルチページ TIFF、TIF ドキュメント。

### URL {#URL}
```
public static final InputType URL
```


画像へのリンク。GIF、PNG、JPEG、BMP、TIFF をサポートします。

### Zip {#Zip}
```
public static final InputType Zip
```


ZIP アーカイブのフルネーム。入れ子になったアーカイブやフォルダーはサポートされません。GIF、PNG、JPEG、BMP、TIFF、JFIF をサポートします。デフォルトの処理画像数はすべてです。
