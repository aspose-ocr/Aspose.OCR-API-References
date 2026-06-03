---
title: "RecognitionResult"
second_title: "Python 用 Aspose.OCR via .NET API リファレンス"
description: 
type: docs
weight: 290
url: /ja/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

画像認識の結果。<br/>            認識情報と結果エクスポート用のメソッドを含む要素を含みます。

RecognitionResult 型は次のメンバーを公開します:


## プロパティ
| 名前 | 説明 |
| :- | :- |
| recognition_regions_result | 領域（矩形）のリストとともに認識結果のリストを取得します。 |
| recognition_lines_result | 認識結果のリストと、行（矩形）のリストを取得します。 |
| recognition_characters_list | 認識アルゴリズムで見つかった文字の集合で、確率の高い順に並べられています。 |
| recognition_text | 認識結果を1つの文字列として取得します。 |
| file_name | ファイルへのフルパスです。 |
| warnings | 生成中に発生した非致命的な障害を説明する警告メッセージのリストを取得します。 |
| serializable_image |  |
## Methods
| 名前 | 説明 |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | ドキュメントをプレーンテキスト、PDF、またはMicrosoft Word文書として保存します。 |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | ドキュメントをプレーンテキスト、PDF、またはMicrosoft Word文書として保存します。 |
| save(full_file_name, save_format, optimize_pdf) | ドキュメントをプレーンテキスト、PDF、またはMicrosoft Word文書として保存します。 |
| save(stream, save_format, optimize_pdf) | ドキュメントをプレーンテキスト、PDF、またはMicrosoft Word文書として保存します。 |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | ドキュメントをプレーンテキスト、PDF、またはMicrosoft Word文書として保存します。 |
| get_spell_check_corrected_text(language, dictionary_path) | テキストを修正します（誤字を置き換えます）。 |
| get_spell_check_error_list(language, dictionary_path) | 指定された入力テキストに対して、誤字を見つけ、提案された綴りを表示します。 |
| get_json(is_readable) | 認識結果を含むJSON文字列を生成します。 |
| get_xml() | 認識結果を含むXML文字列を生成します。 |
| get_keywords() | パスポートからキーワードを取得します（テストモード。USA と MADAGASCAR のパスポートでのみ動作します）。 |

### 参照

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

