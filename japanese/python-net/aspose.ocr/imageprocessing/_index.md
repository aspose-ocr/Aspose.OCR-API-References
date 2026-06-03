---
title: "ImageProcessing"
second_title: "Python 用 Aspose.OCR via .NET API リファレンス"
description: 
type: docs
weight: 120
url: /ja/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Aspose OCR ライブラリ用ヘルパークラス。画像の前処理と保存を可能にします。

ImageProcessing 型は次のメンバーを公開します：
## Methods
| 名前 | 説明 |
| :- | :- |
| save(images, folder_path) | 画像処理を使用して OCR の精度を向上させます。<br/>            指定した順序で入力画像に適用されるフィルタのリストを作成します。<br/>            フィルタを作成する例：<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            すべて必要なわけではありません。必要なものだけを設定してください。 |
| render(images) | 画像処理を使用して OCR の精度を向上させます。<br/>            指定した順序で入力画像に適用されるフィルタのリストを作成します。<br/>            フィルタを作成する例：<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            すべて必要なわけではありません。必要なものだけを設定してください。 |

### 参照

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

