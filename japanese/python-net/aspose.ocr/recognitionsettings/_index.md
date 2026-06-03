---
title: "RecognitionSettings"
second_title: "Python 用 Aspose.OCR via .NET API リファレンス"
description: 
type: docs
weight: 330
url: /ja/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

画像認識の設定。<br/>            カスタマイズ可能な認識プロセスを許可する要素が含まれています。

RecognitionSettings 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| RecognitionSettings() | 新しいインスタンスを初期化します |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | RecognitionSettings クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | 処理用スレッド数を取得または設定します。 |
| language | OCR に使用される言語を取得または設定します。 |
| ignored_symbols | 認識シンボルのブラックリストを設定します。 |
| allowed_symbols | alphabet プロパティで許可される文字を設定します。 |
| allowed_characters | 許可された文字のセット。認識結果で許可される文字の種類を決定します。 |
| automatic_color_inversion | 暗い／黒い背景に白いテキストがある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。 |
| recognition_areas | 処理対象のテキスト領域のリストを取得または設定します。 |
| recognize_single_line | 単一行画像認識を設定します。 <br/>            デフォルトでは無効 (false) です。 <br/>            行に分割するためのすべての処理ステップを無効にします。 <br/>            画像が1行だけの場合はこのパラメータを true に設定します。RecognitionAreas の設定を無効にするため、すべてのエリア設定は無視されます。 |
| language_detection_level |  |
| lines_filtration | テーブル内のテキストを認識できるようにします（線で囲まれた領域）。 |
| detect_areas_mode | ドキュメントタイプ領域（document、photo、plain text、column、image）に最適なモードを選択できるようにします。 |
| upscale_small_font | 小さいフォントの認識に特化した追加アルゴリズムを使用できるようにします。<br/>            小さな文字サイズの画像に役立ちます。 |

### 参照

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

