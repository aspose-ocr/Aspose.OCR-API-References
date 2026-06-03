---
title: "OcrInput"
second_title: "Python 用 Aspose.OCR via .NET API リファレンス"
description: 
type: docs
weight: 240
url: /ja/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

前処理/認識のためにすべての画像/ドキュメントを収集するコンテナ。

OcrInput 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| OcrInput(type, filters) | OcrInput クラスの新しいインスタンスを初期化します |
| OcrInput(type) | OcrInput クラスの新しいインスタンスを初期化します |
## Indexer
| 名前 | 説明 |
| :- | :- |
| [index] | 処理または認識された画像に関する情報を返します。 |
## Methods
| 名前 | 説明 |
| :- | :- |
| add(full_path) | 認識/処理用の画像が含まれるパスまたは URI を追加します。<br/>            画像のタイプはコンストラクタで指定されたタイプと一致する必要があります。 |
| add(stream) | 認識/処理用の画像を含むメモリストリームを追加します。<br/>            画像のタイプはコンストラクタで指定されたタイプと一致する必要があります。 |
| add(full_path, start_page, pages_count) | 認識/処理用のマルチページ画像/ドキュメントを追加します。<br/>            画像のタイプはコンストラクタで指定されたタイプと一致する必要があります。 |
| add(stream, start_page, pages_count) | 認識/処理用のマルチページ画像を含むメモリストリームを追加します。<br/>            画像のタイプはコンストラクタで指定されたタイプと一致する必要があります。 |
| add(arr, width, height, pixel_format) | デコードされた画像を認識/処理のリストに追加します。<br/>            画像のタイプはコンストラクタで指定されたタイプ（SingleImage）に対応している必要があります。 |
| replace_filters(filters) | 古いフィルターを削除し、新しいフィルターを設定します。 |
| clear_filters() | すべてのフィルターを削除します。 |
| add_base64(base64) | 認識/処理のための画像を含む base64 文字列を追加します。<br/>            画像のタイプはコンストラクタで指定されたタイプに対応している必要があります。 |
| clear() | すべてのフィルターを削除します。 |
| count() | 処理/認識対象のアイテム数。 |
| get_input_type() | 認識で許可される画像のタイプ。 |

### 参照

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

