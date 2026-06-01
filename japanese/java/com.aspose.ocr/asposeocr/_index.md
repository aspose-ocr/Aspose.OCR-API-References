---
title: "AsposeOCR"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "画像からテキストを認識するためのメインクラス"
type: docs
weight: 10
url: /ja/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

画像からテキストを認識するためのメインクラスです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | パブリックコンストラクタ。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DebugMode](#DebugMode) | デバッグモードを有効にします。 |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | デバッグ結果が保存されるディレクトリ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | 画像の傾き角度を計算します。 |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | 2つの画像が同じテキストを含んでいるか確認します。 |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | 2つの画像が同じテキストを含んでいるか確認します。 |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | 2つの画像が同じテキストを含んでいるか確認します。 |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | テキストを修正します（スペルミスを置き換え）。 |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | テキストを修正します（スペルミスを置き換え）。 |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | OCR の精度に大きく影響する可能性のある画像の問題領域を自動的に検出します。 |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | 画像を解析し、内部のさまざまなコンテンツ領域を特定します。 |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | 画像上のテキストを解析し、使用されている言語を判定します。 |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | 画像上のテキスト領域を検出します。 |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | 画像上のテーブル領域を検出します。 |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | ケースインセンシティブ検索で、画像が提供されたテキストフラグメントを含んでいるか確認します。 |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | ケースインセンシティブ検索で、画像が提供されたテキストフラグメントを含んでいるか確認します。 |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | 画像が提供されたテキストフラグメントを含んでいるか確認します。 |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | 画像のテキストが提供された正規表現に一致するか確認します。 |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | 画像のテキストが提供された正規表現に一致するか確認します。 |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | 2つの画像上のテキストを比較し、類似度を表す数値（0〜1）を返します。 |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | 2つの画像上のテキストを比較し、類似度を表す数値（0〜1）を返します。 |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | 2つの画像上のテキストを比較し、類似度を表す数値（0〜1）を返します。 |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | 画像を認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。 |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | 画像を認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。 |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | 車のナンバープレートを認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。 |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | 画像上のシンボルを検出します。 |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | 画像上のシンボルを検出します。 |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | 高品質な画像のテキストを認識します。 |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | 提供された入力画像から数式を認識します。 |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | 画像上の手書きテキストを認識します。 |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | 身分証明書を認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。 |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | 請求書を認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。 |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | パスポートを認識し、指定できる機能があります。 |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | 領収書を認識し、指定できる機能があります。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、zip アーカイブ、URL、base64 をサポートします。 |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | テーブルと構造を検出し、テキストセルを認識します。 |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。 |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。 |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。 |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。 |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | RecognitionResult オブジェクトのリストから、スペルチェック補正付きのマルチページ文書を取得できます。 |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。 |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。 |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


パブリックコンストラクタ。

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


デバッグモードを有効にします。有効にすると、システムは前処理された画像やテキスト行の矩形が描画された画像など、中間の画像処理結果を保存します。

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


デバッグ結果が保存されるディレクトリです。設定されていない場合、デフォルトで現在の作業ディレクトリが使用されます。

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


画像の傾き角度を計算します。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、zip アーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | ソースを含むコンテナです。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - 度単位の傾き角度の ArrayList [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


2つの画像が同じテキストを含んでいるか確認します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 最初の画像へのパスです。 |
| fullPath2 | java.lang.String | 2 番目の画像へのパスです。 |

**Returns:**
boolean - 画像が同じテキスト（90% の類似度）を持つ場合は True です。
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


2つの画像が同じテキストを含んでいるか確認します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 最初の画像へのパスです。 |
| fullPath2 | java.lang.String | 2 番目の画像へのパスです。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 認識設定です。 |

**Returns:**
boolean - 画像が同じテキスト（90% の類似度）を持つ場合は True です。
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


2つの画像が同じテキストを含んでいるか確認します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 最初の画像へのパスです。 |
| fullPath2 | java.lang.String | 2 番目の画像へのパスです。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 認識設定です。 |
| ignoreCase | boolean | True - 大文字小文字を区別しない検索を意味します。 |

**Returns:**
boolean - 画像が同じテキスト（90% の類似度）を持つ場合は True です。
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


テキストを修正します（スペルミスを置き換え）。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| text | java.lang.String | 補正用テキストです。 |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 使用する辞書です。[SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - 置換された単語を含むテキストです。
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


テキストを修正します（スペルミスを置き換え）。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| text | java.lang.String | 補正用テキストです。 |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 使用する辞書です。[SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | ユーザー辞書（頻度辞書）へのフルパスです。辞書ファイル形式: UTF-8 エンコードのプレーンテキストファイル。単語と単語頻度はカンマで区切られ、単語は最初の列、頻度は2番目の列に配置されます。各単語‑頻度ペアは別々の行に記述されます。行は文字列のシーケンスの後に改行（\"\\\\n\"）、復帰（\"\\\\r\"）または復帰と改行（\"\\\\r\\\\n\"）が続くものとして定義されます。すべての単語は小文字であることが期待されます。 |

**Returns:**
java.lang.String - 置換された単語を含むテキストです。
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


画像の問題領域を自動的に検出し、OCR の精度に大きく影響する可能性があります。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、zip アーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | ソースを含むコンテナです。[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | The types of defects to be recognized [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - 検出されたテキスト領域または行を含む [DefectOutput](../../com.aspose.ocr/defectoutput/) の ArrayList。
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Analyzes the image and identifies the different types of content areas within it. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, zip archive, URL, base64.

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | ソースを含むコンテナです。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Detected content areas. ArrayList of [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Analyzes the text on the image to determine the languages it is written in. This allows to select the most suitable recognition language and helps in further text processing tasks such as spellchecking or translation. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, zip archive, URL, base64.

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | ソースを含むコンテナです。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Returns a list of the most probable languages, ranked by likelihood. ArrayList of [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Detects text areas on images. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, zip archive, URL, base64.

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | ソースを含むコンテナです。[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Determinates wich rectangles to return - line or paragraphs. |
| isDetectAreas | boolean | Enable automatic text areas detection. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList of [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) with detected text areas or lines.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Detects table regions on images. Supports GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, zip archive, URL, base64.

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | ソースを含むコンテナです。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList of [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) with detected table areas.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


ケースインセンシティブ検索で、画像が提供されたテキストフラグメントを含んでいるか確認します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath | java.lang.String | Path to the image. |
| text | java.lang.String | Text fragment for searching on the image. |

**Returns:**
boolean - True if image contains text fragment. False - image doesn't contains text fragment.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


ケースインセンシティブ検索で、画像が提供されたテキストフラグメントを含んでいるか確認します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath | java.lang.String | Path to the image. |
| text | java.lang.String | Text fragment for searching on the image. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 認識設定です。 |

**Returns:**
boolean - True if image contains text fragment. False - image doesn't contains text fragment.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


画像が提供されたテキストフラグメントを含んでいるか確認します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath | java.lang.String | Path to the image. |
| text | java.lang.String | Text fragment for searching on the image. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 認識設定です。 |
| ignoreCase | boolean | True - 大文字小文字を区別しない検索を意味します。 |

**Returns:**
boolean - True if image contains text fragment. False - image doesn't contains text fragment.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


画像のテキストが提供された正規表現に一致するか確認します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath | java.lang.String | Path to the image. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern object with the provided pattern and options. |

**Returns:**
boolean - True if image text matches the provided regular expression.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


画像のテキストが提供された正規表現に一致するか確認します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath | java.lang.String | Path to the image. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern object with the provided pattern and options. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 認識設定です。 |

**Returns:**
boolean - True if image text matches the provided regular expression.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


2つの画像上のテキストを比較し、類似度を表す数値（0〜1）を返します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 最初の画像へのパスです。 |
| fullPath2 | java.lang.String | 2 番目の画像へのパスです。 |

**Returns:**
float - 0 means that the texts are completely different; 1 means the texts are identical.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


2つの画像上のテキストを比較し、類似度を表す数値（0〜1）を返します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 最初の画像へのパスです。 |
| fullPath2 | java.lang.String | 2 番目の画像へのパスです。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 認識設定です。 |

**Returns:**
float - 0 means that the texts are completely different; 1 means the texts are identical.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


2つの画像上のテキストを比較し、類似度を表す数値（0〜1）を返します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath1 | java.lang.String | 最初の画像へのパスです。 |
| fullPath2 | java.lang.String | 2 番目の画像へのパスです。 |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | 認識設定です。 |
| ignoreCase | boolean | True - 大文字小文字を区別しない検索を意味します。 |

**Returns:**
float - 0 means that the texts are completely different; 1 means the texts are identical.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


画像を認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


画像を認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


車のナンバープレートを認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


画像上のシンボルを検出します。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | ソースを含むコンテナです。[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - 各画像の検出されたシンボルデータを含む [Character](../../com.aspose.ocr.models/character/) の ArrayList。
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


画像上のシンボルを検出します。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | ソースを含むコンテナです。[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | 領域検出に使用されるニューラルネットワークのタイプを決定します。 |
| language | [Language](../../com.aspose.ocr.models/language/) | OCR に使用される言語です。 |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - 検出されたシンボルデータを含む [Character](../../com.aspose.ocr.models/character/) の ArrayList。
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


高品質な画像のテキストを認識します。自動画像傾き補正やテキスト領域検出は使用しません。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/) のインスタンス。 |

**Returns:**
java.util.ArrayList<java.lang.String> - 認識されたテキストを含む ArrayList。
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


提供された入力画像から数式を認識します。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| detectAreas | boolean | true に設定すると、認識を実行する前に数式領域を自動的に検出し、分離します。false に設定すると、画像全体を数式として処理します。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


画像上の手書きテキストを認識します。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)。ソースを含むコンテナです。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


身分証明書を認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


請求書を認識し、サポートする形式として GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 を指定できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


パスポートを認識し、指定する機能があります。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


領収書を認識し、指定できる機能があります。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、zip アーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)。 |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


テーブルと構造を検出し、テキストセルを認識します。GIF、PNG、JPEG、WBMP、TIFF、JFIF、TIFF、PDF、InputStream、BufferedImage、フォルダー、配列、ZIPアーカイブ、URL、base64 をサポートします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| language | [Language](../../com.aspose.ocr.models/language/) | 認識時に使用されるアルファベットを決定します。 |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - テーブル内の認識テキストを含む OCRTablePage オブジェクトのリストです。 [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 選択された形式で認識結果を保存するための OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式 (Docx、Txt、Pdf、PdfNoImg、Xlsx、Xml、Json、Rtf)。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | [RecognitionResult](../../com.aspose.ocr/recognitionresult/) のリストです。オブジェクト。 |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 選択された形式で認識結果を保存するための OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式 (Docx、Txt、Pdf、PdfNoImg、Xlsx、Xml、Json、Rtf)。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | [RecognitionResult](../../com.aspose.ocr/recognitionresult/) のリストです。オブジェクト。 |
| embeddedFontPath | java.lang.String | オプションです。ユーザーフォントへの完全パス。 |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 選択された形式で認識結果を保存するための OutputStream。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式 (Docx、Txt、Pdf、PdfNoImg、Xlsx、Xml、Json、Rtf)。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | [RecognitionResult](../../com.aspose.ocr/recognitionresult/) のリストです。オブジェクト。 |
| embeddedFontPath | java.lang.String | オプションです。ユーザーフォントへの完全パス。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 背景画像の品質を下げて PDF ファイルサイズを削減します。デフォルトでは、元の画像品質が保持されます。 |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 選択された形式で認識結果を保存するためのパス付きファイル名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式（Docx、Txt、Pdf、Xlsx、Xml、Json）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | [RecognitionResult](../../com.aspose.ocr/recognitionresult/) のリストです。オブジェクト。 |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


RecognitionResult オブジェクトのリストから、スペルチェック補正付きのマルチページ文書を取得できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 選択された形式で認識結果を保存するためのパス付きファイル名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式（Docx、Txt、Pdf、Xlsx、Xml、Json）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | [RecognitionResult](../../com.aspose.ocr/recognitionresult/) のリストです。オブジェクト。 |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) 列挙型の値です。 |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 選択された形式で認識結果を保存するためのパス付きファイル名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式（Docx、Txt、Pdf、Xlsx、Xml、Json）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | [RecognitionResult](../../com.aspose.ocr/recognitionresult/) のリストです。オブジェクト。 |
| embeddedFontPath | java.lang.String | オプションです。ユーザーフォントへの完全パス。 |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


RecognitionResult オブジェクトのリストからマルチページ文書を取得できます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 選択された形式で認識結果を保存するためのパス付きファイル名。 |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | ドキュメント形式（Docx、Txt、Pdf、Xlsx、Xml、Json）。 |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | [RecognitionResult](../../com.aspose.ocr/recognitionresult/) のリストです。オブジェクト。 |
| embeddedFontPath | java.lang.String | オプションです。ユーザーフォントへの完全パス。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 背景画像の品質を下げて PDF ファイルサイズを削減します。デフォルトでは、元の画像品質が保持されます。 |

### close() {#close}
```
public void close()
```