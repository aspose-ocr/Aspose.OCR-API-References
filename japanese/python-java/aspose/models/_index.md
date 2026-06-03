---
title: "モデル"
second_title: "Java 経由で Python 用 Aspose.OCR API リファレンス"
description: 
type: docs
weight: 271
url: /ja/python-java/aspose/models/
---

モジュール models
=============

クラス
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   モデルによって検出された領域のタイプを決定します。
get_text_areas で使用され、取得される結果（段落座標または行座標）を示します。

### 継承元 (MRO内)

    * enum.Enum

### クラス変数

`LINES`
:   領域を行として設定します。

`PARAGRAPHS`
:   領域を段落として設定します。

`WORDS`
:   領域を単語として設定します。

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   領域検出に使用されるニューラルネットワークのタイプを決定します。
RecognitionSettings で使用され、認識したい画像のタイプを指定します。

### 継承元 (MRO内)

    * enum.Enum

### クラス変数

`COMBINE`
:   テキストが含まれる段落を検出し、他のニューラルネットワークモデルを使用して段落内の領域を検出します。
複雑な構造を持つ画像に適しています。

`CURVED_TEXT`
:   曲線状の画像上の行を検出し、テキストを認識します。
書籍や雑誌のページの写真に推奨されるモードです。

`DOCUMENT`
:   文書用のニューラルネットワークモデルを使用して段落を検出します。
複数列の文書、画像を含む文書、またはテキスト以外のオブジェクトがある文書に適しています。

`NONE`
:   段落を検出しません。
画像のないシンプルな1列文書に適しています。

`PHOTO`
:   写真用のニューラルネットワークモデルを使用して段落を検出します。
多数の画像やテキスト以外のオブジェクトが含まれる画像に適しています。

`TABLE`
:   テキストを含むセルを検出します。
テーブル構造を持つ画像に好ましいモードです。

`TEXT_IN_WILD`
:   路上写真、ナンバープレート、パスポート写真、メーター写真、ノイズの多い背景の写真など、低品質画像から単語を抽出することに特化した超強力なニューラルネットワークです。

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   認識結果を文書として保存するためのフォーマットです。

### 継承元 (MRO内)

    * enum.Enum

### クラス変数

`DOCX`
:   結果を Office Open XML Word 処理用 ML ドキュメント（マクロなし）として保存します。

`EPUB`
:   文書を EPUB ファイルとして保存します。

`HTML`
:   ドキュメントをHTMLファイルとして保存します。

`JSON`
:   結果をJavaScriptオブジェクト表記のプレーンテキストとして保存します。

`PDF`
:   結果をPDF（Adobe Portable Document）ドキュメントとして保存します。

`PDF_NO_IMG`
:   画像なしで検索可能なPDF（Adobe Portable Document）ドキュメントとして保存します。

`RTF`
:   ドキュメントをRTFファイルとして保存します。

`TEXT`
:   結果をプレーンテキスト形式で保存します。

`XLSX`
:   結果をExcel（2007以降）ワークブックドキュメントとして保存します。

`XML`
:   結果をXMLドキュメントとして保存します。

`ImageData(javaClass)`
:

### 継承元 (MRO内)

    * aspose.helper.BaseJavaClass

### メソッド

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   処理/認識用の画像/ドキュメントのタイプです。

### 継承元 (MRO内)

    * enum.Enum

### クラス変数

`BASE64`
:   画像のbase64文字列またはbase64内容が記載された.txtファイルへのパスです。GIF、PNG、JPEG、BMP、TIFFに対応しています。

`DIRECTORY`
:   ディレクトリへのパスです。入れ子になったアーカイブやフォルダはサポートされていません。
GIF、PNG、JPEG、BMP、TIFFに対応しています。
デフォルトの処理画像数はすべてです。

`PDF`
:   ファイルまたはバイナリ配列からスキャンされたPDFドキュメント。

`SINGLE_IMAGE`
:   GIF、PNG、JPEG、BMP、TIFF、JFIF、バイナリ配列をサポートします。

`TIFF`
:   ファイルまたはInputStreamからのマルチページTIFF、TIFドキュメント。

`URL`
:   画像へのリンクです。GIF、PNG、JPEG、BMP、TIFFをサポートします。

`ZIP`
:   ZIPアーカイブのフルネームです。入れ子のアーカイブやフォルダーはサポートされていません。
GIF、PNG、JPEG、BMP、TIFF、JFIFをサポートします。
デフォルトの処理画像数はすべてです。

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   認識用の言語モデルです。

### 継承元 (MRO内)

    * enum.Enum

### クラス変数

`BEL`
:   ベラルーシ語アルファベット

`BUL`
:   ブルガリア語アルファベット

`CHI`
:   中国語アルファベット

`CYRILLIC`
:   マルチ言語（キリル文字アルファベット）サポート

`CZE`
:   チェコ語アルファベット

`DAN`
:   デンマーク語アルファベット

`DEU`
:   ドイツ語アルファベット

`DUM`
:   オランダ語アルファベット

`ENG`
:   英語アルファベット

`EST`
:   エストニア語アルファベット

`FIN`
:   フィンランド語アルファベット

`FRA`
:   フランス語アルファベット

`HIN`
:   ヒンディー語アルファベット

`ITA`
:   イタリア語アルファベット

`KAZ`
:   カザフ語アルファベット

`LATIN`
:   マルチ - 言語（ラテン文字）サポート

`LAV`
:   ラトビア語アルファベット

`LIT`
:   リトアニア語アルファベット

`NONE`
:   マルチ - 言語サポート

`NOR`
:   ノルウェー語アルファベット

`POL`
:   ポーランド語アルファベット

`POR`
:   ポルトガル語アルファベット

`RUM`
:   ルーマニア語アルファベット

`RUS`
:   ロシア語アルファベット

`SLK`
:   スロバキア語アルファベット

`SLV`
:   スロベニア語アルファベット

`SPA`
:   スペイン語アルファベット

`SRP`
:   セルビア語アルファベット

`SRP_HRV`
:   セルビア・クロアチア語アルファベット

`SWE`
:   スウェーデン語アルファベット

`UKR`
:   ウクライナ語アルファベット

`ModelsConverter()`
:

### メソッド

`convertInputTypeToJava(jType)`
:

`convertToJavaAreasMode(jType)`
:

`convertToJavaAreasType(jType)`
:

`convertToJavaFormat(jType)`
:

`convertToJavaLanguage(jType)`
:

`convertToJavaSpellCheckLanguage(jType)`
:

`OcrInput(type: models.InputType, filters: models.PreprocessingFilter = None)`
:   画像を収集するためのメインクラスです。
    
コンテナを作成し、画像/ドキュメントのタイプと、さらに処理/認識のためのフィルタを設定するコンストラクタです。
@param type: コンテナに追加される画像/ドキュメントのタイプを設定します。
@param filters: さらに処理または認識のために適用される処理フィルタを設定します。

### メソッド

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   認識/処理のために画像を含むパスまたはURIを追加します。
画像のタイプは、コンストラクタで指定されたタイプと一致する必要があります。
@param fullPath: 画像/ドキュメント/フォルダー/アーカイブへのパスです。
@param startPage: 処理/認識のための最初のページ/画像です。ドキュメント、ZIP、フォルダーで使用します。
@param pagesNumber: 処理/認識のためのページ/画像の総数です。ドキュメント、ZIP、フォルダーで使用します。デフォルトはすべてです。

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   認識/処理のために画像を含むInputStreamを追加します。
画像のタイプは、コンストラクタで指定されたタイプと一致する必要があります。
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, \"rb\")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: 画像またはドキュメントを含むデータです。
@param startPage: 処理/認識のための最初のページ/画像です。ドキュメント、ZIP、フォルダーで使用します。
@param pagesNumber: 処理/認識のためのページ/画像の総数です。ドキュメント、ZIP、フォルダーで使用します。デフォルトはすべてです。

`add_base64(self, base64: str)`
:   画像認識/処理に使用する base64 文字列を追加します。
画像のタイプは、コンストラクタで指定されたタイプと一致する必要があります。
@param base64: 単一画像を含む Base64 文字列。

`clear(self)`
:   処理/認識対象の項目数を 0 に設定します。
コレクションをクリアします。

`clear_filters(self)`
:   すべてのフィルタを削除します。

`get(self, index: int) ‑> models.ImageData`
:   処理/認識された画像に関する情報を返します。
@param index: リスト内の画像の位置。
@return: ImageData オブジェクト。

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   処理/認識対象の項目数。
@return: 項目数。

`PreprocessingFilter()`
:   画像処理コマンドの基底クラスです。

### 継承元 (MRO内)

    * aspose.helper.BaseJavaClass

### クラス変数

`JAVA_CLASS_NAME`
:

### 静的メソッド

`auto_denoising()`
:   画像を改善しノイズを低減するために、追加のニューラルネットワークの使用を有効にします。
スキャンアーティファクト、歪み、スポット、フレア、グラデーション、異物がある画像に有用です。
@return: AutoDenoisingFilter オブジェクト。

`auto_dewarping()`
:   画像の幾何学的歪みを自動的に補正します。
非常にリソースを多く消費します！
@return: AutoDewarpingFilter オブジェクト。

`auto_skew()`
:   自動画像スキュー補正を有効にします。
@return: AutoSkewFilter オブジェクト。

`binarize()`
:   画像を白黒画像に変換します。
バイナリ画像は、ピクセルが2つの強度値しか持たない画像です。
通常、黒と白で表示されます。数値的には、2つの値は黒が0、白が255であることが多いです。
バイナリ画像は、画像の自動しきい値処理によって生成されます。
@return: BinarizeFilter オブジェクト。

`binarize_and_dilate()`
:   膨張処理は、画像内のオブジェクトの境界にピクセルを追加します。
@return: DilateFilter オブジェクト。

`contrast_correction()`
:   コントラスト補正フィルタ。
@return: ContrastCorrectionFilter オブジェクト。

`invert()`
:   文書画像の色を自動的に反転させます。
@return: InvertFilter オブジェクト。

`median()`
:   メディアンフィルタは画像の各要素を走査し、各ピクセルを隣接ピクセルの中央値で置き換えます。
@return: MedianFilter オブジェクト。

`resize(width: int, height: int)`
:   画像をリスケールします - 解像度を拡大または縮小します。
@param width: 画像の新しい幅。
@param height: 画像の新しい高さ。
@return: ResizeFilter オブジェクト。

`rotate(angle: float)`
:   元画像を回転します。
@param angle: 回転角度。値は -360 から 360 までです。
@return: RotateFilter オブジェクト。

`scale(ratio: float)`
:   画像のサイズを変更します - 画像解像度を拡大または縮小します。
InterpolationFilterType は双一次補間または最近傍補間です。
@param ratio: スケーリング係数。縮小する場合は 0.1 から 1、拡大する場合は 1 から 10 が推奨値です。
@return: ScaleFilter オブジェクト。

`threshold(value: int)`
:   元画像のピクセル強度に閾値を設定して二値画像を作成します。
@param value: 最大値。
@return: BinarizeFilter オブジェクト。

`to_grayscale()`
:   画像をグレースケール画像に変換します。
グレースケール画像は 0 から 255 の 256 段階の明るさを持ちます。
@return: GrayscaleFilter オブジェクト。

### メソッド

`add(self, filter)`
:   さらなる前処理のためにフィルタをコレクションに追加します。
@param filter: PreprocessingFilter オブジェクト。

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   誤字単語を追加データとともに表現します。

### 継承元 (MRO内)

    * aspose.helper.BaseJavaClass

### メソッド

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   スペルチェック補正用の辞書言語です。

### 継承元 (MRO内)

    * enum.Enum

### クラス変数

`CZE`
:   チェコ語辞書

`DAN`
:   デンマーク語辞書

`DEU`
:   ドイツ語辞書

`DUM`
:   オランダ語辞書

`ENG`
:   英語辞書

`EST`
:   エストニア語辞書

`FIN`
:   フィンランド語辞書

`FRA`
:   フランス語辞書

`ITA`
:   イタリア語辞書

`LAV`
:   ラトビア語辞書

`LIT`
:   リトアニア語辞書

`POL`
:   ポーランド語辞書

`POR`
:   ポルトガル語辞書

`RUM`
:   ルーマニア語辞書

`SLK`
:   スロバキア語辞書

`SLV`
:   スロベニア語辞書

`SPA`
:   スペイン語辞書

`SWE`
:   スウェーデン語辞書

`SuggestedWord(javaClass)`
:   get_spell_check_error_list から返されたスペル提案。

### 継承元 (MRO内)

    * aspose.helper.BaseJavaClass

### メソッド

`initParams(self)`
:


### 参照

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)