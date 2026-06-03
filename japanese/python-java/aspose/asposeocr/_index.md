---
title: "AsposeOcr"
second_title: "Java 経由で Python 用 Aspose.OCR API リファレンス"
description: 
type: docs
weight: 11
url: /ja/python-java/aspose/asposeocr/
---


モジュール asposeocr
================
Aspose OCR の Python インターフェイス

**Aspose.OCR for Python via .Java** is a powerful,
使いやすい光学文字認識（OCR）
Python アプリケーションとノートブック用のエンジンです。
**10** 行未満のコードで、認識できます
ラテン文字、キリル文字に基づく **28** 言語のテキスト、
アジアの文字体系も、最も一般的な
文書およびデータ交換フォーマットです。
複雑な数学モデルを学ぶ必要はありません、
機械学習アルゴリズムを構築し、ニューラル
ネットワーク — 当社のシンプルで堅牢な API がすべてを代行します。

クラス
-------

`AsposeOcr()`
:
認識用の AsposeOcr メインクラスです。
    
このサンプルは画像の認識方法を示しています。
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, \"SpanishOCR.bmp\"))
result = api.recognize(input)
\endcode

### 静的メソッド

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。
@param fullFileName: 選択された形式で認識結果を保存するためのパス付きファイル名。
@param saveFormat: 文書形式 (Docx, Txt, Pdf, Xlsx, Xml, Json)。
@param results:

### メソッド

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
画像の傾き角度を計算します。
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。ソースが含まれるコンテナ。
@return: 度単位の傾き角度のリスト - SkewOutput。

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
2つの画像が同じテキストを含んでいるか確認します。
@param fullPath1: 最初の画像へのパス。
@param fullPath2: 2番目の画像へのパス。
@param settings: 認識設定。
@param ignoreCase: True - 大文字小文字を区別しない検索を意味します。
@return: 画像が同じテキストを持つ場合は True（90% の類似度）。

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
テキストを修正します（誤字を置換）。
@param text: 修正対象のテキスト。
@param language: SpellCheckLanguage で使用する辞書。
@return: 置換された単語を含むテキスト。

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
画像上のテキスト領域を検出します。
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@param areasType: 返す矩形の種類を決定します - 行、段落、または単語。
@param isDetectAreas: 自動テキスト領域検出を有効にします。
@return: 検出されたテキスト領域または行を含む RectangleOutput のリスト。

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
画像が指定されたテキストフラグメントを含んでいるか確認します。
@param fullPath: 画像へのパス。
@param text: 画像上で検索するテキストフラグメント。
@param settings: 認識設定。
@param ignoreCase: True - 大文字小文字を区別しない検索を意味します。
@return: 画像がテキストフラグメントを含む場合は True。含まない場合は False。

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
2つの画像上のテキストを比較し、類似度を表す数値（0〜1）を返します。
@param fullPath1: 最初の画像へのパス。
@param fullPath2: 2番目の画像へのパス。
@param settings: 認識設定。
@param ignoreCase: True - 大文字小文字を区別しない検索を意味します。
@return: 0 はテキストがまったく異なることを意味し、1 はテキストが完全に同一であることを意味します。

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
RecognitionSettings を指定できる画像認識を行います。
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@param settings: RecognitionSettings オブジェクト。
@return: 画像認識結果を含む RecognitionResult のリスト。

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
CarPlateRecognitionSettings を指定できる車両ナンバープレートの認識を行います。
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@param settings: CarPlateRecognitionSettings
@return: 画像認識結果を含む RecognitionResult のリスト。

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
高品質な画像のテキストを認識します。自動画像傾き補正やテキスト領域の
検出。
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@return: 画像認識結果を含む RecognitionResult のリスト。

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
IDCardRecognitionSettings を指定できる身分証明書の認識を行います。
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@param settings: IDCardRecognitionSettings
@return: 画像認識結果を含む RecognitionResult のリスト。

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
InvoiceRecognitionSettings を指定できる請求書の認識を行います
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@param settings: InvoiceRecognitionSettings
@return: 画像認識結果を含む RecognitionResult のリスト。

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
RecognitionSettings を指定できる単一行画像の認識を行います。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@param settings: RecognitionSettings オブジェクト。
@return: 画像認識結果を含む RecognitionResult のリスト。

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
PassportRecognitionSettings を指定できる機能でパスポートを認識します。
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@param settings: PassportRecognitionSettings
@return: 画像認識結果を含む RecognitionResult のリスト。

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
ReceiptRecognitionSettings を指定できる機能で領収書を認識します。
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@param settings: ReceiptRecognitionSettings
@return: 画像認識結果を含む RecognitionResult のリスト。

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
街の写真上のテキストを認識します。
街の写真、交通カメラ画像、身分証明書、運転免許証、その他の文字が少なくノイズや色付き背景の画像からテキストを抽出します。
GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、バイナリ配列、フォルダー、配列、ZIPアーカイブ、URL、Base64 をサポートします。
@param input: :py:any:`~aspose.models.OcrInput`. インスタンス。
@return: 画像認識結果を含む RecognitionResult のリスト。

`shutdown(self)`
:
JVM マシンをシャットダウンします。

`ImageProcessing()`
:
Aspose OCR ライブラリのヘルパークラスです。画像の前処理と保存を可能にします。

### 静的メソッド

`save(images, folderPath)`
:
画像処理を使用して OCR の精度を向上させます。
指定した順序で入力画像に適用されるフィルタのリストを作成します。
\code
filters = new PreprocessingFilter();
filters.add(PreprocessingFilter.auto_dewarping());
filters.add(PreprocessingFilter.invert());
filters.add(PreprocessingFilter.threshold(150));
filters.add(PreprocessingFilter.binarize());
filters.add(PreprocessingFilter.rotate(180));
filters.add(PreprocessingFilter.scale(6));
filters.add(PreprocessingFilter.dilate());
        
images = OcrInput(InputType.PDF, filters);
\endcode
すべてを使用する必要はありません。必要なものだけを設定してください。
@param images: 異なる画像を含む OcrInput オブジェクト OcrInput。
@param folderPath: 処理済み画像を保存するための、画像名を含まないパス。
@return: 処理された画像の結果を含む OcrInput オブジェクト OcrInput。


### 参照

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)