---
title: "AsposeOcr"
second_title: "Python 用 Aspose.OCR via .NET API リファレンス"
description: 
type: docs
weight: 10
url: /ja/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Aspose OCR ライブラリのメイン API

AsposeOcr 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| AsposeOcr() | [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/) クラスの新しいインスタンスを初期化します。<br/>            空のコンストラクタです。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| 名前 | 説明 |
| :- | :- |
| recognize(images) | 画像 / ドキュメント上のテキストを認識します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、ディレクトリ、配列、アーカイブをサポートします。 |
| recognize(images, preset) |  |
| recognize(images, settings) | 画像 / ドキュメント上のテキストを認識します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、ディレクトリ、配列、アーカイブをサポートします。 |
| recognize_receipt(images) | レシート上のテキストを認識します。 |
| recognize_receipt(images, settings) | レシート上のテキストを認識します。 |
| recognize_invoice(images) | 請求書上のテキストを認識します。 |
| recognize_invoice(images, settings) | 請求書上のテキストを認識します。 |
| recognize_id_card(images) | IDカード上のテキストを認識します。 |
| recognize_id_card(images, settings) | IDカード上のテキストを認識します。 |
| recognize_car_plate(images) | ナンバープレート上のテキストを認識します。 |
| recognize_car_plate(images, settings) | ナンバープレート上のテキストを認識します。 |
| recognize_passport(images) | パスポート上のテキストを認識します。 |
| recognize_passport(images, settings) | パスポート上のテキストを認識します。 |
| recognize_lines(images) | 単一行のテキストを含む画像を認識します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、フォルダー、配列、アーカイブをサポートします。 |
| recognize_lines(images, settings) | 単一行のテキストを含む画像を認識します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、フォルダー、配列、アーカイブをサポートします。 |
| detect_rectangles(images) | 画像上のテキスト領域を検出します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、フォルダー、配列、アーカイブをサポートします。 |
| detect_rectangles(images, areas_type, detect_areas) | 画像上のテキスト領域を検出します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、フォルダー、配列、アーカイブをサポートします。 |
| recognize_characters(images) | 画像上のシンボルを検出します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、フォルダー、配列、アーカイブをサポートします。 |
| recognize_characters(images, detect_areas_mode, language) | 画像上のシンボルを検出します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、フォルダー、配列、アーカイブをサポートします。 |
| save_multipage_document(full_file_name, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results) |  |
| save_multipage_document(stream, save_format, results) |  |
| save_multipage_document(stream, save_format, results, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| recognize_fast(images) | 画像 / ドキュメント上のテキストを認識します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、ディレクトリ、配列、アーカイブをサポートします。 |
| recognize_handwritten_text(images) | 画像上の手書きテキストを認識します。 |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | 画像の傾き角度を計算します。<br/>            GIF、PNG、JPEG、BMP、TIFF、JFIF、ストリーム、フォルダー、配列、アーカイブをサポートします。 |
| detect_defects(images, defect_type) | 画像の問題領域を自動的に検出し、OCR の精度に大きく影響する可能性があります。<br/>            ファイル、ストリーム、またはピクセル配列として提供される PNG、JPEG、BMP、TIFF、JFIF、GIF 画像をサポートします。大量認識をサポートします。 |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | 画像が提供されたテキストフラグメントを含んでいるか確認します。 |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | 2 つの画像が同じテキストを含んでいるか確認します。 |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | 2 つの画像上のテキストを比較し、類似度を表す数値（0 から 1）を返します。 |
| correct_spelling(text, language, dictionary_path) | テキストを修正します（誤字を置き換えます）。 |

### 参照

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

