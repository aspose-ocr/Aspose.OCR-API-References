---
title: "OcrOutput"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: 
type: docs
weight: 21
url: /ja/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OcrOutput()](#OcrOutput) | 空のコレクションで OcrOutput クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |

| [getTableData()](#getTableData) | 認識されたすべてのページから抽出された構造化テーブルデータを返します。 |
| [save(OutputStream stream)](#save-java.io.OutputStream) | すべての認識結果を指定された形式でメモリストリームに保存します。 |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | すべての認識結果を指定された形式でメモリストリームに保存します。 |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | すべての認識結果を指定された形式でメモリストリームに保存します。 |
| [save(String fullFileName)](#save-java.lang.String) | すべての認識結果をファイルに保存します。 |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | すべての認識結果をファイルに保存します。 |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | すべての認識結果をファイルに保存します。 |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | すべての認識結果をインメモリの検索可能な PDF ドキュメントに保存し、元の画像を背景として埋め込みます。 |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | すべての認識結果をインメモリの検索可能な PDF ドキュメントに保存し、元の画像を背景として埋め込みます。 |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | すべての認識結果を検索可能な PDF ファイルに保存し、元の画像を背景に設定します。 |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | すべての認識結果を検索可能な PDF ファイルに保存し、元の画像を背景に設定します。 |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


認識されたすべてのページから抽出された構造化テーブルデータを返します。

各ページは行を含み、各行は認識されたテキストとオプションの位置情報を持つセルを含みます。

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


すべての認識結果を指定された形式でメモリストリームに保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 選択された形式で認識結果を保存するための OutputStream。 |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


すべての認識結果を指定された形式でメモリストリームに保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 選択された形式で認識結果を保存するための OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式（Docx、Txt、Pdf、Xlsx、Rtf、Json、Xml、Epub）。 |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


すべての認識結果を指定された形式でメモリストリームに保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 選択された形式で認識結果を保存するための OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式（Docx、Txt、Pdf、Xlsx、Rtf、Json、Xml、Epub）。 |
| embeddedFontPath | java.lang.String | オプション。ユーザーフォントへのフルパス。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 背景画像の品質を下げて PDF ファイルサイズを削減します。デフォルトでは、元の画像品質が保持されます。 |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


すべての認識結果をファイルに保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 選択された形式で認識結果を保存するためのパス付きファイル名。 |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


すべての認識結果をファイルに保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 選択された形式で認識結果を保存するためのパス付きファイル名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式（Docx、Txt、Pdf、Xlsx、Rtf、Json、Xml、Epub）。 |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


すべての認識結果をファイルに保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 選択された形式で認識結果を保存するためのパス付きファイル名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式（Docx、Txt、Pdf、Xlsx、Rtf、Json、Xml、Epub）。 |
| embeddedFontPath | java.lang.String | オプション。ユーザーフォントへのフルパス。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 背景画像の品質を下げて PDF ファイルサイズを削減します。デフォルトでは、元の画像品質が保持されます。 |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


すべての認識結果をインメモリの検索可能な PDF ドキュメントに保存し、元の画像を背景として埋め込みます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 選択された形式で認識結果を保存するための OutputStream。 |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


すべての認識結果をインメモリの検索可能な PDF ドキュメントに保存し、元の画像を背景として埋め込みます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 選択された形式で認識結果を保存するための OutputStream。 |
| embeddedFontPath | java.lang.String | オプション。ユーザーフォントへのフルパス。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 背景画像の品質を下げて PDF ファイルサイズを削減します。デフォルトでは、元の画像品質が保持されます。 |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


すべての認識結果を検索可能な PDF ファイルに保存し、元の画像を背景に設定します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 選択された形式で認識結果を保存するためのパス付きファイル名。 |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


すべての認識結果を検索可能な PDF ファイルに保存し、元の画像を背景に設定します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 選択された形式で認識結果を保存するためのパス付きファイル名。 |
| embeddedFontPath | java.lang.String | オプション。ユーザーフォントへのフルパス。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 背景画像の品質を下げて PDF ファイルサイズを削減します。デフォルトでは、元の画像品質が保持されます。 |

### size() {#size}
```
public int size()
```




**Returns:**
int
