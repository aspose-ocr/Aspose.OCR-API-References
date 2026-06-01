---
title: "DefectOutput"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "画像で特定された欠陥を含む領域"
type: docs
weight: 16
url: /ja/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

画像で識別された欠陥を含む領域です。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Page](#Page) | ページ番号です。 |
| [Source](#Source) | ファイルまたは URL のフルパス（該当する場合）。 |
| [defectAreas](#defectAreas) | 画像の欠陥とそれらが見つかった領域のリストです。 |


### Page {#Page}
```
public int Page
```


ページ番号です。

### Source {#Source}
```
public String Source
```


ファイルまたは URL のフルパス（該当する場合）。ストリーム、バイト配列、Base64 エンコードされたファイルの場合は空です。

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


画像の欠陥とそれらが見つかった領域のリストです。
