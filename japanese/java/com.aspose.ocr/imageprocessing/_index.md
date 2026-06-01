---
title: "画像処理"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "Aspose OCR ライブラリ用のヘルパークラス"
type: docs
weight: 19
url: /ja/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Aspose OCR ライブラリ用のヘルパークラスです。画像の前処理と保存が可能です。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | 画像処理を使用して OCR の精度を向上させます。 |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | 画像処理を使用して OCR の精度を向上させます。 |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


OCR の精度を向上させるために画像処理を使用します。指定した順序で入力画像に適用されるフィルタのリストを作成します。フィルタ作成の例: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); すべてのフィルタが必要なわけではありません。必要なものだけを設定してください。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | さまざまな画像を含む OcrInput オブジェクト @see \#OcrInput。 |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


OCR の精度を向上させるために画像処理を使用します。指定した順序で入力画像に適用されるフィルタのリストを作成します。フィルタ作成の例: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); すべてのフィルタが必要なわけではありません。必要なものだけを設定してください。

**Parameters:**
| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | さまざまな画像を含む OcrInput オブジェクト @see \#OcrInput。 |
| folderPath | java.lang.String | 処理済み画像を保存するための、画像名を除いたパス。 |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
