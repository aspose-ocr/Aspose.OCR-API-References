---
title: "DetectAreasMode"
second_title: "Python 用 Aspose.OCR via .NET API リファレンス"
description: 
type: docs
weight: 540
url: /ja/python-net/aspose.ocr/detectareasmode/
---

## DetectAreasMode enumeration

領域検出に使用されるニューラルネットワークのタイプを決定します。

## Members
| メンバー名 | 説明 |
| :- | :- |
| LEAN | 複雑なレイアウトのサポートを省くことで速度を優先し、リソース消費を削減します。イラストや書式設定のない、数行のテキストだけのシンプルな画像にのみ適しています。 |
| MULTICOLUMN | 列でフォーマットされた大きなテキストブロックを検出します。書籍のページ、記事、契約書などのマルチカラムレイアウトに最適な選択肢です。 |
| UNIVERSAL | 画像内のすべてのテキストブロックを検出します。写真上のまばらで不規則なテキストも含みます。テーブルやマルチカラムレイアウトを除く、ほとんどの画像に汎用的に使用できます。 |
| TABLE | 画像内の表構造を検出し、個々のセルからテキストを抽出します。スキャンしたスプレッドシート、レポート、その他の表形式の文書に推奨されます。 |
| CURVED_TEXT | 画像内の曲がったテキスト行を自動的に伸ばし、認識精度を向上させ、より多くのテキストを復元・抽出できるようにします。大量の処理能力とメモリが必要です。 |
| FORMULA |  |

### 参照

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.OCR](/ocr/python-net/)

