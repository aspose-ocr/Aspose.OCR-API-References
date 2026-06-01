---
title: "OcrInput"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "画像からテキストを認識するためのメインクラス"
type: docs
weight: 20
url: /ja/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

画像からテキストを認識するためのメインクラスです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | コンテナを作成し、画像/ドキュメントのタイプと今後の処理/認識用フィルタを設定するためのコンストラクタです。 |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | デコードされた画像を認識/処理用リストに追加します。 |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | 認識/処理用の画像を含む BufferedImage を追加します。 |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | 認識/処理用のマルチページ画像を含む BufferedImage を追加します。 |
| [add(InputStream stream)](#add-java.io.InputStream) | 認識/処理用の画像を含む InputStream を追加します。 |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | 認識/処理用のマルチページ画像を含む InputStream を追加します。 |
| [add(String fullPath)](#add-java.lang.String) | 認識/処理用の画像を含むパスまたは URI を追加します。 |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | 認識/処理用のマルチページ画像/ドキュメントを追加します。 |
| [addBase64(String base64)](#addBase64-java.lang.String) | 認識/処理用の画像を含む base64 文字列を追加します。 |
| [clear()](#clear) | 処理/認識項目数を 0 に設定します。 |
| [clearFilters()](#clearFilters) | すべてのフィルターを削除します。 |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | 処理または認識された画像に関する情報を返します。 |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | 古いフィルターを削除し、新しいフィルターを設定します。 |
| [size()](#size) | 処理または認識のための項目数。 |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


コンテナを作成し、画像/ドキュメントのタイプと今後の処理/認識用フィルタを設定するためのコンストラクタです。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | コンテナに追加される画像/ドキュメントのタイプを設定します。 |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | 設定された処理フィルターは、今後の処理または認識に適用されます。 |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


デコードされた画像を認識/処理用のリストに追加します。画像のタイプは、コンストラクタで指定されたタイプ（SingleImage）と一致する必要があります。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ピクセル | int[] | ピクセルは 32 ビット整数値（rgb）で表されます。 |
| 幅 | int | 画像の幅。 |
| 高さ | int | 画像の高さ。 |
| bitsPerPixel | int | 1〜32 ビットをサポートします。 |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


認識/処理用の画像を含む BufferedImage を追加します。画像のタイプは、コンストラクタで指定されたタイプと一致する必要があります。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 画像 | java.awt.image.BufferedImage | 画像またはドキュメントを含む BufferedImage。 |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


認識/処理用のマルチページ画像を含む BufferedImage を追加します。画像のタイプは、コンストラクタで指定されたタイプと一致する必要があります。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 画像 | java.awt.image.BufferedImage | マルチページドキュメントを含む BufferedImage。 |
| startPage | int | 処理または認識の最初のページ/画像です。ドキュメントに使用します。 |
| pagesCount | int | 処理または認識のためのページ/画像の総数です。ドキュメントに使用します。デフォルト = すべて。 |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


認識/処理用の画像を含む InputStream を追加します。画像のタイプは、コンストラクタで指定されたタイプと一致する必要があります。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 画像またはドキュメントを含む InputStream。 |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


認識/処理用のマルチページ画像を含む InputStream を追加します。画像のタイプはコンストラクタで指定されたタイプと一致する必要があります。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | マルチページドキュメントを含む InputStream。 |
| startPage | int | 処理または認識の最初のページ/画像です。ドキュメントに使用します。 |
| pagesCount | int | 処理または認識のためのページ/画像の総数です。ドキュメントに使用します。デフォルト = すべて。 |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


認識/処理用の画像を含むパスまたは URI を追加します。画像のタイプはコンストラクタで指定されたタイプと一致する必要があります。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath | java.lang.String | 画像/ドキュメント/フォルダー/アーカイブへのパス。 |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


認識/処理用のマルチページ画像/ドキュメントを追加します。画像のタイプはコンストラクタで指定されたタイプと一致する必要があります。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fullPath | java.lang.String | 画像/ドキュメント/フォルダー/アーカイブへのパス。 |
| startPage | int | 処理/認識用の最初のページ/画像です。ドキュメント、ZIP、フォルダーで使用します。 |
| pagesCount | int | 処理/認識用のページ/画像の総数です。ドキュメント、ZIP、フォルダーで使用します。デフォルト = すべて。 |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


認識/処理用の画像を含む base64 文字列を追加します。画像のタイプはコンストラクタで指定されたタイプと一致する必要があります。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| base64 | java.lang.String | 単一画像を含む Base64 文字列。 |

### clear() {#clear}
```
public void clear()
```


処理/認識用の項目数を 0 に設定します。コレクションをクリアします。

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


すべてのフィルターを削除します。

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int}
```
public ImageData get(int index)
```


処理または認識された画像に関する情報を返します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| index | int | リスト内の画像の位置。 |

**Returns:**
[ImageData](../../com.aspose.ocr/imagedata/) - The object of @see [ImageData](../../com.aspose.ocr/imagedata/)
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator}
```
public Iterator<ImageData> iterator()
```




**Returns:**
java.util.Iterator<com.aspose.ocr.ImageData>
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### replaceFilters(PreprocessingFilter filters) {#replaceFilters-com.aspose.ocr.PreprocessingFilter}
```
public void replaceFilters(PreprocessingFilter filters)
```


古いフィルターを削除し、新しいフィルターを設定します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | さらに処理または認識のために処理フィルターが適用されます。 |

### size() {#size}
```
public int size()
```


処理または認識のための項目数。

**Returns:**
int - 項目数。
### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

