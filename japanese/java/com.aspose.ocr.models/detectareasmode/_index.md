---
title: "DetectAreasMode"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: 
type: docs
weight: 28
url: /ja/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | 画像内の曲がったテキスト行を自動的に補正し、認識精度を向上させ、より多くのテキストを復元・抽出できるようにします。 |
| [FORMULA](#FORMULA) | 数式が含まれるすべてのブロックを検出します。 |
| [LEAN](#LEAN) | 複雑なレイアウトのサポートを省くことで、速度を優先し、リソース消費を削減します。 |
| [MULTICOLUMN](#MULTICOLUMN) | 列でフォーマットされた大きなテキストブロックを検出します。 |
| [TABLE](#TABLE) | 画像内の表構造を検出し、個々のセルからテキストを抽出します。 |
| [UNIVERSAL](#UNIVERSAL) | 画像内のすべてのテキストブロックを検出し、写真上の散在した不規則なテキストも含みます。 |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


画像内の曲がったテキスト行を自動的に補正し、認識精度を向上させ、より多くのテキストを復元・抽出できるようにします。大量の処理能力とRAMが必要です。

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


数式が含まれるすべてのブロックを検出します。

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


複雑なレイアウトのサポートを省くことで、速度を優先し、リソース消費を削減します。イラストや書式設定のない、数行のテキストだけのシンプルな画像にのみ適しています。

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


列でフォーマットされた大きなテキストブロックを検出します。書籍のページ、記事、契約書などのマルチカラムレイアウトに最適な選択です。

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


画像内の表構造を検出し、個々のセルからテキストを抽出します。スキャンしたスプレッドシート、レポート、その他の表形式文書に推奨されます。

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


画像内のすべてのテキストブロックを検出し、写真上の散在した不規則なテキストも含みます。表やマルチカラムレイアウトを除くほとんどの画像に汎用的に適しています。

