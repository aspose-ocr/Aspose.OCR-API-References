---
title: "RecognitionResult"
second_title: "Java 経由で Python 用 Aspose.OCR API リファレンス"
description: 
type: docs
weight: 171
url: /ja/python-java/aspose/recognitionresult/
---

モジュール recognitionresult
========================

クラス
-------

`LinesResult(javaClass)`
:

### 継承元 (MRO内)

    * aspose.helper.BaseJavaClass

### メソッド

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
画像認識の結果です。認識された要素を含みます。
結果エクスポートのための情報とメソッドです。

### 静的メソッド

`save_multipage_document(self, fullPath: str)`
:
プライベート

### インスタンス変数

`recognition_areas_text`
:   エリア（矩形）のリストに対する認識結果のリストです。

`recognition_lines_result`
:   行（矩形）のリストに対する認識結果のリストを取得します。

### メソッド

`getJavaClass(self)`
:

`get_json(self)`
:
認識結果を含む JSON 文字列を作成します。
@return: 認識結果を JSON 文字列として返します。

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
テキストを修正します（誤字を置換）。
@param language: 使用する辞書。
@return: 修正された認識結果文字列。

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
指定された入力テキストに対して、提案されたスペルで誤字を見つけます。
@param language: 使用する辞書。
@return: 各誤字に対する提案された正しいスペルのリストを含む、SpellCheckError オブジェクトのリスト、
および編集距離を含みます。

`get_xml(self)`
:
認識結果を含む JSON 文字列を作成します。
@return: 認識結果を XML 文字列として返します。

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
文書をプレーンテキストまたは他のドキュメント形式で保存します。
@param fullFileName: 認識結果を保存するためのパス付きファイル名。
@param format: Format の列挙型で示すドキュメント形式。

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
テキストを修正します（誤字を置換）。
文書内の修正されたテキストをプレーンテキストまたは他の形式で保存します。
@param fullFileName: 認識結果を保存するためのパス付きファイル名
@param format: Format の列挙型で示すドキュメント形式。
@param language: スペルチェック用の辞書。

`use_user_dictionary(self, dictionaryPath: str)`
:
スペルチェックの補正に独自の辞書を使用できるようにします。
@param dictionaryPath: ユーザー辞書（頻度辞書）へのフルパス。
辞書ファイル形式:
UTF-8 エンコードのプレーンテキストファイル。
単語と単語頻度はカンマで区切られ、単語は最初の列、頻度は2番目の列に配置されます。
各単語-頻度ペアは別々の行にあります。行は文字列に続く改行 (\"
\"), キャリッジリターン (\"\")
"),
または、キャリッジリターンの直後に改行が続く場合("

").
すべての単語は小文字であることが期待されます。
例:
\code
単語,5984819
こんにちは,5761742
下,5582768
\endcode

`RectangleOutput(javaClass)`
:
検出されたテキスト領域または行に関するデータ。
\code
source - ファイルまたはURL（存在する場合）の完全パスです。ストリーム、バイト配列、base64 の場合は空です。
page - ページ番号です。
image_index - ページ上の画像のシーケンス番号です。
rectangles - 検出されたテキスト領域または行のリストです。
\endcode

### 継承元 (MRO内)

    * aspose.helper.BaseJavaClass

### メソッド

`initParams(self)`
:

`SkewOutput(javaClass)`
:
傾き角度（度単位）とファイル名に関するデータ。
\code
source - ファイルまたはURL（存在する場合）の完全パスです。ストリーム、バイト配列、base64 の場合は空です。
page - ページ番号です。
image_index - ページ上の画像のシーケンス番号です。
angle - 角度（度単位）の傾きです。
\endcode

### 継承元 (MRO内)

    * aspose.helper.BaseJavaClass

### メソッド

`initParams(self)`
:


### 参照

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)