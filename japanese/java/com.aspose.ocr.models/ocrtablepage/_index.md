---
title: "OCRTablePage"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "OCRドキュメント全体のページに対する構造化テーブルデータを表します"
type: docs
weight: 18
url: /ja/java/com.aspose.ocr.models/ocrtablepage/
---

**Inheritance:**
java.lang.Object
```
public class OCRTablePage
```

OCRドキュメント全ページの構造化された表データを表します。

このオブジェクトは、1つの処理されたページ全体で認識されたすべてのテーブルを集約します。各ページには1つ以上の検出されたテーブルが含まれる場合があり、[OCRTable](../../com.aspose.ocr.models/ocrtable/) エントリとして表されます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OCRTablePage()](#OCRTablePage) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addTable(OCRTable table)](#addTable-com.aspose.ocr.models.OCRTable) |  |
| [getTables()](#getTables) |  |

### OCRTablePage() {#OCRTablePage}
```
public OCRTablePage()
```


### addTable(OCRTable table) {#addTable-com.aspose.ocr.models.OCRTable}
```
public void addTable(OCRTable table)
```




**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| table | [OCRTable](../../com.aspose.ocr.models/ocrtable/) |  |



### getTables() {#getTables}
```
public List<OCRTable> getTables()
```




**Returns:**
java.util.List<com.aspose.ocr.models.OCRTable>
