---
title: "リソース"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "Aspose.OCR の認識機能を強化するダウンロード可能なリソースを管理します"
type: docs
weight: 32
url: /ja/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Aspose.OCR の認識機能を強化するダウンロード可能なリソースを管理します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Resources()](#Resources) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | オンラインリポジトリから必要なリソースの自動ダウンロードを許可 (true) またはブロック (false) します。 |
| [FetchAll()](#FetchAll) | オンラインリポジトリからすべての互換リソースをダウンロードします。 |
| [FetchResource(String name)](#FetchResource-java.lang.String) | オンラインリポジトリから name パラメータで指定されたリソースをダウンロードします。 |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | オンラインリポジトリから names パラメータで指定されたリソースをダウンロードします。 |
| [GetLocalPath()](#GetLocalPath) | リソースがダウンロードされるディレクトリへのフルパスを返します。 |
| [GetRepository()](#GetRepository) | Aspose.OCR リソースがダウンロードされるオンラインリポジトリの URL を返します。 |
| [ListLocal()](#ListLocal) | ローカルディレクトリに保存されているすべての Aspose.OCR リソースを一覧表示します。 |
| [ListRemote()](#ListRemote) | オンラインリポジトリからすべての互換リソースを一覧表示します。 |
| [ReleaseMemory()](#ReleaseMemory) | メモリを解放するために OCR モジュールをアンロードします。 |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | ローカルに保存された Aspose.OCR リソースを削除します。 |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | リソースがダウンロードされるディレクトリへの絶対パスまたは相対パスを指定します。 |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | リソースがダウンロードされるディレクトリへの絶対パスまたは相対パスを指定します。 |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Aspose.OCR リソースがダウンロードされるオンラインリポジトリの URL を指定します。 |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


オンラインリポジトリから必要なリソースの自動ダウンロードを許可 (true) またはブロック (false) します。デフォルトでは、リソースに依存するメソッドが呼び出されたときにリソースが自動的にダウンロードされます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 許可 | java.lang.Boolean | 必要なリソースの自動ダウンロードを許可またはブロックするための Boolean 値。 |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


オンラインリポジトリからすべての互換リソースをダウンロードします。既存のリソースファイルは上書きされます。

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


オンラインリポジトリから name パラメータで指定されたリソースをダウンロードします。リソースが既にダウンロードされている場合は上書きされます。.OCR 拡張子を省略してファイル名だけを使用することができます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| name | java.lang.String | リソース名を含む文字列。ListRemote メソッドを参照してください。 |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


オンラインリポジトリから names パラメータで指定されたリソースをダウンロードします。1 つ以上のリソースが既にダウンロードされている場合は上書きされます。.OCR 拡張子を省略してファイル名だけを使用することができます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| names | java.lang.String[] | リソース名の配列。ListRemote メソッドを参照してください。 |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


リソースがダウンロードされるディレクトリへのフルパスを返します。

**Returns:**
java.lang.String - リソースディレクトリへのパスを含む文字列。
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Aspose.OCR リソースがダウンロードされるオンラインリポジトリの URL を返します。

**Returns:**
java.lang.String - オンラインリポジトリの URL。
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


ローカルディレクトリに保存されているすべての Aspose.OCR リソースを一覧表示します。

**Returns:**
java.util.List<java.lang.String> - ローカルディレクトリに保存されているすべての Aspose.OCR リソースを一覧表示します。
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


オンラインリポジトリからすべての互換リソースを一覧表示します。

**Returns:**
java.util.List<java.lang.String> - リソース名のリスト。
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


OCR モジュールをアンロードしてメモリを解放します。ダウンロードされたモジュールファイルはそのまま残ります。

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


ローカルに保存された Aspose.OCR リソースを削除します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


リソースがダウンロードされるディレクトリへの絶対パスまたは相対パスを指定します。ディレクトリが存在しない場合は自動的に作成されます。デフォルトでは、リソースはアプリケーションの作業ディレクトリ内の aspose\_data ディレクトリにダウンロードされます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | java.lang.String | ディレクトリへの絶対パスまたは相対パス。 |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


リソースがダウンロードされるディレクトリへの絶対パスまたは相対パスを指定します。ディレクトリを自動的に作成しないようにするには、create パラメータに false を渡します。指定されたディレクトリが存在せず、作成が許可されていない場合、リソースはアプリケーションの作業ディレクトリ内の aspose\_data ディレクトリにロードされます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | java.lang.String | ディレクトリへの絶対パスまたは相対パス。 |
| create | java.lang.Boolean | ディレクトリが自動的に作成されるのを防止するパラメータ。 |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Aspose.OCR リソースがダウンロードされるオンラインリポジトリの URL を指定します。デフォルトでは、リソースは https://github.com/aspose-ocr/resources/ からダウンロードされます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | java.lang.String | オンラインリポジトリの URL。 |


