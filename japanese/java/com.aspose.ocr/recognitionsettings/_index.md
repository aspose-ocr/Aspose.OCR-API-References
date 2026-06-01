---
title: "RecognitionSettings"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "画像認識の設定"
type: docs
weight: 27
url: /ja/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

画像認識の設定です。認識プロセスをカスタマイズできる要素が含まれています。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | デフォルトコンストラクタ: recognitionAreas を null に設定し、linesFiltration を false、autoSkew を false、recognizeSingleLine を false に設定します。 |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | コンストラクタはすべてのオプションを設定できるようにします。 |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | コンストラクタは recognizeSingleLine を設定できるようにします。 |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | 許可された文字セット。 |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | 許可された文字セット。 |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | 暗い/黒い背景に白いテキストがある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。 |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | 領域検出に使用されるニューラルネットワークのタイプを決定します。 |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | 認識シンボルのブラックリストを設定します。 |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | テキスト認識の言語検出レベルを指定します。 |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | テーブル内のテキスト（線で囲まれた領域）を認識できるようにします。 |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | 処理対象のテキスト領域リストを設定します。 |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | 単一行画像認識を設定します。 |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | 処理用スレッド数を取得または設定します。 |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | 小さいフォントの認識専用に追加アルゴリズムを使用できるようにします。 |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


デフォルトコンストラクタ: recognitionAreas を null に設定し、linesFiltration を false、autoSkew を false、recognizeSingleLine を false に設定します。

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


コンストラクタはすべてのオプションを設定できるようにします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | 認識用の矩形。 |
| recognizeSingleLine | boolean | 画像が1行だけの場合は true。 |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


コンストラクタでは **recognizeSingleLine** を設定できます。この場合のデフォルト値: detectAreas - false、autoSkew = false、recognitionAreas - null。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| recognizeSingleLine | boolean | 画像が1行だけの場合は true。 |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


許可された文字セット。認識結果で許可される文字の種類を決定します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) の値を含みます。 |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


許可された文字セット。認識結果で許可される文字の配列を決定します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| allowedCharacters | java.lang.String | 文字列を含みます。 |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


暗い/黒い背景に白いテキストがある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| automaticColorInversion | boolean | ブール値を含みます - automaticColorInversion が設定されています。デフォルトは true。 |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


領域検出に使用されるニューラルネットワークのタイプを決定します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | enum @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) の値を含みます。 |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


認識シンボルのブラックリストを設定します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| characters | java.lang.String | 認識から除外される文字。 |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | OCRで使用する言語を設定します。デフォルトはマルチ言語（なし）です。 |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


テキスト認識の言語検出レベルを指定します。選択された言語が Language.MULTILANGUAGE、Language.AUTO、または Language.UNIVERSAL の場合にのみ機能します。このプロセスは時間がかかり、全体的な認識速度を大幅に低下させます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


テーブル内のテキスト（線で囲まれた領域）を認識できるようにします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| linesFiltration | boolean | false - パフォーマンスが向上し、テーブルの検出や行の除去を行わないようにします；それ以外の場合は true。デフォルトでは無効 (false) です。 |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


処理用のテキスト領域リストを設定します。より正確な認識のために、テキストがある領域を手動で指定できます。カスタム領域が設定されている場合、[setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} が NONE でない、または [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} のプロパティは無視されます。DetectAreas と AutoSkew を無効にします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | 認識用の矩形。 |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


単一行画像の認識を設定します。デフォルトでは無効 (false) です。行に分割するすべての処理ステップを無効にします。画像が1行だけの場合はこのパラメータを true に設定してください。[setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList) の設定を無効にし、すべての領域設定が無視されます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| recognizeSingleLine | boolean | 単一行画像の場合は true |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


処理用スレッド数を取得または設定します。デフォルトでは、0 はプロセッサ数と同じスレッド数で画像が処理されることを意味します。ThreadsCount = 1 は画像がメインスレッドで処理されることを意味します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| threadsCount | int | 画像フラグメントの並列認識のために作成されるスレッド数。 |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


小さいフォントの認識専用に追加アルゴリズムを使用できるようにします。小サイズの文字が含まれる画像に便利です。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| upscaleSmallFont | boolean | ブール値を含みます - upscaleSmallFont が設定されています。 |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String