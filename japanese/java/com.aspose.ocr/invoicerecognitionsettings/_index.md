---
title: "InvoiceRecognitionSettings"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "請求書認識の設定。認識プロセスをカスタマイズできる要素が含まれています。"
type: docs
weight: 17
url: /ja/java/com.aspose.ocr/invoicerecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class InvoiceRecognitionSettings extends ReceiptRecognitionSettings
```

請求書認識の設定。認識プロセスをカスタマイズできる要素が含まれています。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [InvoiceRecognitionSettings()](#InvoiceRecognitionSettings) | デフォルトコンストラクタ: autoSkew を true に設定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | 許可された文字セット。 |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | 許可された文字セット。 |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | 暗い/黒い背景に白いテキストがある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。 |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | 認識シンボルのブラックリストを設定します。 |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | テキスト認識の言語検出レベルを指定します。 |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | 処理用スレッド数を取得または設定します。 |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | 小さいフォントの認識専用に追加アルゴリズムを使用できるようにします。 |
### InvoiceRecognitionSettings() {#InvoiceRecognitionSettings}
```
public InvoiceRecognitionSettings()
```


デフォルトコンストラクタ: autoSkew を true に設定します。



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
| allowedCharacters | java.lang.String | 文字の配列を含みます。 |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


暗い/黒い背景に白いテキストがある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| automaticColorInversion | boolean | ブール値を含みます - automaticColorInversion が設定されています。 |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | レベル（Paragraph、Word、Page）を設定するための enum 値。 |

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
