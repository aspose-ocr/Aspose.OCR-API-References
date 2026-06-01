---
title: "PreprocessingFilter"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "画像処理コマンドの基底クラス"
type: docs
weight: 24
url: /ja/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

画像処理コマンドの基底クラスです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Empty](#Empty) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | 画像を改善しノイズを低減するために、追加のニューラルネットワークの使用を可能にします。 |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | 画像の一部を改善しノイズを低減するために、追加のニューラルネットワークの使用を可能にします。 |
| [AutoDewarping()](#AutoDewarping) | 画像の幾何学的歪みを自動的に補正します。 |
| [AutoSkew()](#AutoSkew) | 画像の自動傾き補正を可能にします。 |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | 画像の一部の自動傾き補正を可能にします。 |
| [Binarize()](#Binarize) | 画像を白黒画像に変換します。 |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | 画像の一部を白黒画像に変換します。 |
| [BinarizeAndDilate()](#BinarizeAndDilate) | 膨張処理は画像内のオブジェクトの境界にピクセルを追加します。 |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | 膨張処理は画像の一部にあるオブジェクトの境界にピクセルを追加します。 |
| [ContrastCorrection()](#ContrastCorrection) | コントラスト補正フィルタ。 |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | 画像の一部用コントラスト補正フィルタ。 |
| [Invert()](#Invert) | 文書画像の色を自動的に反転させます。 |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | 画像の一部の色を自動的に反転させます。 |
| [Median()](#Median) | メディアンフィルタは画像の各要素を走査し、各ピクセルを隣接ピクセルの中央値に置き換えます。 |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | 中央値フィルタは画像の一部の各要素を通過し、各ピクセルを隣接ピクセルの中央値に置き換えます。 |
| [Resize(int width, int height)](#Resize-int-int) | 画像のリスケール - 解像度を拡大または縮小します。 |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | 画像のリスケール - 解像度を拡大または縮小します。 |
| [Rotate(float angle)](#Rotate-float) | 元画像を回転します。 |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | 画像の一部を回転します。 |
| [Scale(float ratio)](#Scale-float) | 画像のリスケール - 解像度を拡大または縮小します。 |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | 画像のリスケール - 解像度を拡大または縮小します。 |
| [Threshold(int value)](#Threshold-int) | 元画像のピクセル強度に閾値を設定して二値画像を作成します。 |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | 元画像の一部のピクセル強度に閾値を設定して二値画像の一部を作成します。 |
| [ToGrayscale()](#ToGrayscale) | 画像をグレースケール画像に変換します。 |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | 新しいフィルタをコレクションに追加して、すべての操作をさらに実行します。 |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### PreprocessingFilter() {#PreprocessingFilter}
```
public PreprocessingFilter()
```


### Empty {#Empty}
```
public static final PreprocessingFilter Empty
```


### AutoDenoising() {#AutoDenoising}
```
public static PreprocessingFilter AutoDenoising()
```


追加のニューラルネットワークを使用して画像を改善し、ノイズを低減できるようにします。スキャンアーティファクト、歪み、スポット、フレア、グラデーション、異物がある画像に有用です。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


追加のニューラルネットワークを使用して画像の一部を改善し、ノイズを低減できるようにします。スキャンアーティファクト、歪み、スポット、フレア、グラデーション、異物がある画像に有用です。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 領域 | java.awt.Rectangle | 前処理用の矩形。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


画像の幾何学的歪みを自動的に補正します。非常にリソースを多く消費します！

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


画像の自動傾き補正を可能にします。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


画像の一部の自動傾き補正を可能にします。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 領域 | java.awt.Rectangle | 前処理用の矩形。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


画像を白黒画像に変換します。二値画像は、ピクセルが 2 つの強度値しか持たない画像です。通常は白黒で表示されます。数値的には、黒が 0、白が 255 とすることが一般的です。二値画像は画像の自動閾値処理によって生成されます。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


画像の一部を白黒画像に変換します。二値画像は、ピクセルが 2 つの強度値しか持たない画像です。通常は白黒で表示されます。数値的には、黒が 0、白が 255 とすることが一般的です。二値画像は画像の自動閾値処理によって生成されます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 領域 | java.awt.Rectangle | 前処理用の矩形。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


膨張処理は画像内のオブジェクトの境界にピクセルを追加します。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


膨張処理は画像の一部にあるオブジェクトの境界にピクセルを追加します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 領域 | java.awt.Rectangle | 前処理用の矩形。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


コントラスト補正フィルタ。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


画像の一部用コントラスト補正フィルタ。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 領域 | java.awt.Rectangle | 前処理用の矩形。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


文書画像の色を自動的に反転させます。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


画像の一部の色を自動的に反転させます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 領域 | java.awt.Rectangle | 前処理用の矩形。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


メディアンフィルタは画像の各要素を走査し、各ピクセルを隣接ピクセルの中央値に置き換えます。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


中央値フィルタは画像の一部の各要素を通過し、各ピクセルを隣接ピクセルの中央値に置き換えます。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 領域 | java.awt.Rectangle | 前処理用の矩形。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


画像のリスケール - 解像度を拡大または縮小します。InterpolationFilterType = bilinear または nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 幅 | int | 画像の新しい幅。 |
| 高さ | int | 画像の新しい高さ。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


画像のリスケール - 解像度を拡大または縮小します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 幅 | int | 画像の新しい幅。 |
| 高さ | int | 画像の新しい高さ。 |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


元画像を回転します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。値は -360 から 360 までです。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


画像の一部を回転します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。値は -360 から 360 までです。 |
| 領域 | java.awt.Rectangle | 前処理用の矩形。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


画像のリスケール - 画像解像度を拡大または縮小します。InterpolationFilterType のデフォルトはバイリニアまたは最近傍です @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 比率 | float | スケーリング係数。縮小する場合は 0.1 から 1、拡大する場合は 1 から 10 が推奨値です。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


画像のリスケール - 解像度を拡大または縮小します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 比率 | float | スケーリング係数。縮小する場合は 0.1 から 1、拡大する場合は 1 から 10 が推奨値です。 |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


元画像のピクセル強度に閾値を設定して二値画像を作成します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 値 | int | 最大値です。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


元画像の一部のピクセル強度に閾値を設定して二値画像の一部を作成します。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 値 | int | 最大値です。 |
| 領域 | java.awt.Rectangle | 前処理用の矩形。 |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


画像をグレースケール画像に変換します。グレースケール画像は画像内の明るさを 256 段階（0〜255）で表現します。

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


新しいフィルタをコレクションに追加して、すべての操作をさらに実行します。コレクション内の一貫性が重要です。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | フィルタリストに追加する新しい操作です。 |

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
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




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

