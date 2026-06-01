---
title: "ライセンス"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "コンポーネントにライセンスを付与するメソッドを提供します"
type: docs
weight: 21
url: /ja/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

コンポーネントをライセンスするためのメソッドを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License()](#License) | このクラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | コンポーネントにライセンスを付与します。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | コンポーネントにライセンスを付与します。 |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | コンポーネントにライセンスを付与します。 |
| [isValid()](#isValid--) | ライセンスを確認します。 |
### License() {#License}
```
public License()
```


このクラスの新しいインスタンスを初期化します。


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


コンポーネントにライセンスを付与します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| licenseFile | java.io.File | ファイルパス名の表現 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


コンポーネントにライセンスを付与します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ライセンスを含むストリーム。 |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


コンポーネントにライセンスを付与します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| licenseFilePath | java.lang.String | フルまたは短いファイル名を指定できます。空文字列を使用すると評価モードに切り替わります。 |



### isValid() {#isValid--}
```
public static boolean isValid()
```


ライセンスを確認します。

**Returns:**
boolean - ライセンスが有効かどうかのブール値。
