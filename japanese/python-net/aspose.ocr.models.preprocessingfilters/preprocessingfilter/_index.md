---
title: "PreprocessingFilter"
second_title: "Python 用 Aspose.OCR via .NET API リファレンス"
description: 
type: docs
weight: 10
url: /ja/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

画像処理コマンドの基底クラス。

PreprocessingFilter 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PreprocessingFilter() | PreprocessingFilter クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| デフォルト | デフォルトのフィルタコレクションには AutoSkew フィルタが含まれています |
| empty | 空のフィルタコレクション |
## Methods
| 名前 | 説明 |
| :- | :- |
| binarize() | 画像を白黒画像に変換します。<br/>            バイナリ画像は、ピクセルが 2 つの強度値しか持たない画像です。 <br/>            通常、白黒で表示されます。数値的には、黒が 0、白が 255 であることが多いです。<br/>            バイナリ画像は、画像の自動しきい値処理によって生成されます。 |
| binarize(area) | 画像の一部を白黒画像に変換します。<br/>            バイナリ画像は、ピクセルが 2 つの強度値しか持たない画像です。 <br/>            通常、白黒で表示されます。数値的には、黒が 0、白が 255 であることが多いです。<br/>            バイナリ画像は、画像の自動しきい値処理によって生成されます。 |
| resize(width, height, type) | 画像のサイズを再スケーリングします - 画像解像度を拡大または縮小します。 |
| resize(width, height) | 画像のサイズを再スケーリングします - 画像解像度を拡大または縮小します。 |
| dilate() | 膨張処理は、画像内のオブジェクトの境界にピクセルを追加します。 |
| dilate(area) | 膨張処理は、画像の一部にあるオブジェクトの境界にピクセルを追加します。 |
| invert() | 文書画像の色を自動的に反転させます。 |
| invert(area) | 画像の一部の色を自動的に反転させます。 |
| rotate(angle) | 元の画像を回転させます。 |
| rotate(angle, area) | 画像の一部を回転させます。 |
| scale(ratio) | 画像のリスケール - 画像解像度を拡大または縮小します。<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | 画像のサイズを再スケーリングします - 画像解像度を拡大または縮小します。 |
| threshold(value) | 元画像のピクセル強度に閾値を設定して、2値画像を作成します。 |
| threshold(value, area) | 元画像の一部のピクセル強度に閾値を設定して、画像の一部を2値化します。 |
| median() | メディアンフィルタは画像の各要素を走査し、各ピクセルを隣接ピクセルの中央値で置き換えます。 |
| median(area) | メディアンフィルタは画像の一部の各要素を走査し、各ピクセルを隣接ピクセルの中央値で置き換えます。 |
| auto_denoising() | 追加のニューラルネットワークを使用して画像を改善し、ノイズを低減します。<br/>            スキャンアーティファクト、歪み、スポット、フレア、グラデーション、異物がある画像に有用です。 |
| auto_denoising(area) | 追加のニューラルネットワークを使用して画像の一部を改善し、ノイズを低減します。<br/>            スキャンアーティファクト、歪み、スポット、フレア、グラデーション、異物がある画像に有用です。 |
| auto_skew() | 画像の自動傾き補正を有効にします。 |
| auto_skew(area) | 画像の一部の自動傾き補正を有効にします。 |
| contrast_correction_filter() | コントラスト補正フィルタ。 |
| contrast_correction_filter(area) | 画像の一部に対するコントラスト補正フィルタ。 |
| to_grayscale() | 画像をグレースケール画像に変換します。<br/>            グレースケール画像は画像内の明るさを256レベル（0〜255）で表現します。 |
| auto_dewarping() | 画像の幾何学的歪みを自動的に補正します。<br/>            非常にリソース集約的です！ |
| add(filter) | 新しいフィルタをコレクションに追加して、すべての操作をさらに実行します。<br/>            コレクション内の一貫性が重要です。 |

### 参照

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

