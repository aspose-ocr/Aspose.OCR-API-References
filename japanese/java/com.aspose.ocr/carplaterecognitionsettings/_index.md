---
title: "CarPlateRecognitionSettings"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "車両ナンバー認識の設定。認識プロセスをカスタマイズできる要素が含まれています。"
type: docs
weight: 12
url: /ja/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

車両ナンバー認識の設定。認識プロセスをカスタマイズできる要素が含まれています。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | デフォルトコンストラクタ: autoSkew を true に設定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | 許可された文字セット。 |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | 暗い/黒い背景に白いテキストがある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。 |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | 認識シンボルのブラックリストを設定します。 |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


デフォルトコンストラクタ: autoSkew を true に設定します。





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


許可された文字セット。認識結果で許可される文字の種類を決定します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) の値を含みます。 |

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

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | OCRで使用する言語を設定します。デフォルトはマルチ言語（なし）です。 |

