---
title: "RecognitionResult"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "画像認識の結果"
type: docs
weight: 26
url: /ja/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

画像認識の結果です。認識情報を含む要素と結果エクスポート用のメソッドが含まれます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | 新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [language](#language) | 画像内の認識テキストの言語です。 |
| [recognitionCharactersList](#recognitionCharactersList) | 認識アルゴリズムで見つかった文字のセットで、確率の高い順に並べられています。 |
| [recognitionLinesResult](#recognitionLinesResult) | 行（矩形）のリストを含む認識結果のリストを取得します。 |
| [recognitionRegionsResult](#recognitionRegionsResult) | 領域（矩形）のリストを含む認識結果のリストを取得します。 |
| [recognitionText](#recognitionText) | すべてのページまたは単一領域の認識結果です。 |
| [warnings](#warnings) | 生成中に発生した非致命的な障害を説明する警告メッセージのリストを取得または設定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [GetJson()](#GetJson) | 認識結果を含む JSON 文字列を作成します。 |
| [GetKeywords()](#GetKeywords) | パスポートからキーワードを取得します（テストモード）。 |
| [GetXml()](#GetXml) | 認識結果を含む JSON 文字列を作成します。 |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | テキストを修正します（スペルミスを置き換え）。 |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | テキストを修正します（スペルミスを置き換え）。 |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | 指定された入力テキストに対して、スペルミスした単語と提案されたスペルを見つけます。 |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 指定された入力テキストに対して、スペルミスした単語と提案されたスペルを見つけます。 |
| [save(String fullFileName)](#save-java.lang.String) | ドキュメントをプレーンテキストで保存します |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | ドキュメントをプレーンテキストまたは他のドキュメント形式で保存します。 |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | ドキュメントをプレーンテキストまたは他のドキュメント形式で保存します。 |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | 英語辞書で修正されたテキストを、プレーンテキストまたは Microsoft Word テキストドキュメント形式でドキュメントに保存します。 |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | 修正されたテキストをプレーンテキストまたは他の形式でドキュメントに保存します。 |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | スペルチェックの修正に独自の辞書を使用できるようにします。 |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


新しいインスタンスを初期化します。

### language {#language}
```
public Language language
```


画像内で認識されたテキストの言語です。Language.AUTO、Language.MULTILANGUAGE、または Language.UNIVERSAL が選択されている場合、この値は自動的に決定されます。

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


認識アルゴリズムで見つかった文字のセットで、確率の高い順に並べられています。

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


行（矩形）のリストを含む認識結果のリストを取得します。

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


領域（矩形）のリストを含む認識結果のリストを取得します。

### recognitionText {#recognitionText}
```
public String recognitionText
```


すべてのページまたは単一領域の認識結果です。

### warnings {#warnings}
```
public ArrayList<String> warnings
```


生成中に発生した非致命的な障害を説明する警告メッセージのリストを取得または設定します。

### GetJson() {#GetJson}
```
public String GetJson()
```


認識結果を含む JSON 文字列を作成します。

**Returns:**
java.lang.String - 認識結果を JSON 文字列として取得します。
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


パスポートからキーワードを取得します（テストモード。USA と MADAGASCAR のパスポートでのみ動作）。

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - キーワードをキー、LinesResult を値とする辞書です。
### GetXml() {#GetXml}
```
public String GetXml()
```


認識結果を含む JSON 文字列を作成します。

**Returns:**
java.lang.String - 認識結果を XML 文字列として取得します。
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


テキストを修正します（スペルミスを置き換え）。

**Returns:**
java.lang.String - 修正された認識結果文字列です。デフォルトは英語辞書です。
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


テキストを修正します（スペルミスを置き換え）。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 使用する辞書。 |

**Returns:**
java.lang.String - 修正された認識結果文字列です。
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


指定された入力テキストに対して、スペルミスした単語と提案されたスペルを見つけます。デフォルトは英語辞書です。

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - スペルミスした単語を表す SpellCheckError オブジェクトの ArrayList で、各単語に対する提案された正しいスペルのリストと編集距離を含みます。
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


指定された入力テキストに対して、スペルミスした単語と提案されたスペルを見つけます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | 使用する辞書。 |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - スペルミスした単語を表す SpellCheckError オブジェクトの ArrayList で、各単語に対する提案された正しいスペルのリストと編集距離を含みます。




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


ドキュメントをプレーンテキストで保存します

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 認識結果を保存するためのパス付きファイル名 |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


ドキュメントをプレーンテキストまたは他のドキュメント形式で保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 認識結果を保存するためのパス付きファイル名です。 |
| format | [Format](../../com.aspose.ocr.models/format/) | Format のドキュメント形式列挙型です。 |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


ドキュメントをプレーンテキストまたは他のドキュメント形式で保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 認識結果を保存するためのパス付きファイル名です。 |
| format | [Format](../../com.aspose.ocr.models/format/) | Format のドキュメント形式列挙型です。 |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 背景画像の品質を下げて PDF ファイルサイズを削減します。デフォルトでは、元の画像品質が保持されます。 |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


英語辞書で修正されたテキストを、プレーンテキストまたは Microsoft Word テキストドキュメント形式でドキュメントに保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 認識結果を保存するためのパス付きファイル名です。 |
| format | [Format](../../com.aspose.ocr.models/format/) | Format のドキュメント形式列挙型です。 |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


修正されたテキストをプレーンテキストまたは他の形式でドキュメントに保存します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullFileName | java.lang.String | 認識結果を保存するためのパス付きファイル名です。 |
| format | [Format](../../com.aspose.ocr.models/format/) | Format のドキュメント形式列挙型です。 |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | スペルチェック用の辞書。 |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


スペルチェックの修正に独自の辞書を使用できるようにします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| dictionaryPath | java.lang.String | ユーザー辞書（頻度辞書）へのフルパスです。辞書ファイル形式: UTF-8 エンコードのプレーンテキストファイル。単語と単語頻度はカンマで区切られ、単語は最初の列、頻度は2番目の列に配置されます。各単語‑頻度ペアは別々の行に記述されます。行は文字列のシーケンスの後に改行（\"\\\\n\"）、復帰（\"\\\\r\"）または復帰と改行（\"\\\\r\\\\n\"）が続くものとして定義されます。すべての単語は小文字であることが期待されます。 |
