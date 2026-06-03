---
title: "RecognitionSettings"
second_title: "Java 経由で Python 用 Aspose.OCR API リファレンス"
description: 
type: docs
weight: 191
url: /ja/python-java/aspose/recognitionsettings/
---

モジュール recognitionsettings
==========================

クラス
-------

`CarPlateRecognitionSettings()`
:

### クラス変数

`JAVA_CLASS_NAME`
:

### メソッド

`set_allowed_characters(self, allowedCharacters: str)`
:
許可された文字のセットです。認識結果で許可される文字の配列を決定します。
@param allowedCharacters: 文字列を含みます。

`set_ignored_characters(self, ignoredCharacters: str)`
:
認識記号のブラックリストを設定します。
@param ignoredCharacters: 認識から除外される文字です。

`set_language(self, language: aspose.models.Language)`
:
OCR に使用される言語を設定します。
デフォルトではマルチランゲージ（なし）です。
@param language: 列挙型 Language の値が含まれます。

`set_threads_count(self, threadsCount: int)`
:
処理に使用するスレッド数を取得または設定します。
デフォルトでは、0 は画像がプロセッサ数と同じスレッド数で処理されることを意味します。
ThreadsCount = 1 は画像がメインスレッドで処理されることを意味します。
@param threadsCount: 画像フラグメントの並列認識のために作成されるスレッド数です。

`IDCardRecognitionSettings()`
:

### クラス変数

`JAVA_CLASS_NAME`
:

### メソッド

`set_allowed_characters(self, allowedCharacters: str)`
:
許可された文字のセットです。認識結果で許可される文字の配列を決定します。
@param allowedCharacters: 文字列を含みます。

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
暗い／黒い背景に白い文字がある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。
@param automaticColorInversion: 真偽値が含まれます - automaticColorInversion が設定されます。デフォルトは True です。

`set_ignored_characters(self, ignoredCharacters: str)`
:
認識記号のブラックリストを設定します。
@param ignoredCharacters: 認識から除外される文字です。

`set_language(self, language: aspose.models.Language)`
:
OCR に使用される言語を設定します。
デフォルトではマルチランゲージ（なし）です。
@param language: 列挙型 Language の値が含まれます。

`set_threads_count(self, threadsCount: int)`
:
処理に使用するスレッド数を取得または設定します。
デフォルトでは、0 は画像がプロセッサ数と同じスレッド数で処理されることを意味します。
ThreadsCount = 1 は画像がメインスレッドで処理されることを意味します。
@param threadsCount: 画像フラグメントの並列認識のために作成されるスレッド数です。

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
小さなフォントの認識専用の追加アルゴリズムを使用できるようにします。
小さな文字が含まれる画像に便利です。
@param upscaleSmallFont: 真偽値が含まれます - upscaleSmallFont が設定されます。

`InvoiceRecognitionSettings()`
:

### クラス変数

`JAVA_CLASS_NAME`
:

### メソッド

`set_allowed_characters(self, allowedCharacters: str)`
:
許可された文字のセットです。認識結果で許可される文字の配列を決定します。
@param allowedCharacters: 文字列を含みます。

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
暗い／黒い背景に白い文字がある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。
@param automaticColorInversion: 真偽値が含まれます - automaticColorInversion が設定されます。デフォルトは True です。

`set_ignored_characters(self, ignoredCharacters: str)`
:
認識記号のブラックリストを設定します。
@param ignoredCharacters: 認識から除外される文字です。

`set_language(self, language: aspose.models.Language)`
:
OCR に使用される言語を設定します。
デフォルトではマルチランゲージ（なし）です。
@param language: 列挙型 Language の値が含まれます。

`set_threads_count(self, threadsCount: int)`
:
処理に使用するスレッド数を取得または設定します。
デフォルトでは、0 は画像がプロセッサ数と同じスレッド数で処理されることを意味します。
ThreadsCount = 1 は画像がメインスレッドで処理されることを意味します。
@param threadsCount: 画像フラグメントの並列認識のために作成されるスレッド数です。

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
小さなフォントの認識専用の追加アルゴリズムを使用できるようにします。
小さな文字が含まれる画像に便利です。
@param upscaleSmallFont: 真偽値が含まれます - upscaleSmallFont が設定されます。

`PassportRecognitionSettings()`
:

### クラス変数

`JAVA_CLASS_NAME`
:

### メソッド

`set_allowed_characters(self, allowedCharacters: str)`
:
許可された文字のセットです。認識結果で許可される文字の配列を決定します。
@param allowedCharacters: 文字列を含みます。

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
暗い／黒い背景に白い文字がある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。
@param automaticColorInversion: 真偽値が含まれます - automaticColorInversion が設定されます。デフォルトは True です。

`set_ignored_characters(self, ignoredCharacters: str)`
:
認識記号のブラックリストを設定します。
@param ignoredCharacters: 認識から除外される文字です。

`set_language(self, language: aspose.models.Language)`
:
OCR に使用される言語を設定します。
デフォルトではマルチランゲージ（なし）です。
@param language: 列挙型 Language の値が含まれます。

`set_threads_count(self, threadsCount: int)`
:
処理に使用するスレッド数を取得または設定します。
デフォルトでは、0 は画像がプロセッサ数と同じスレッド数で処理されることを意味します。
ThreadsCount = 1 は画像がメインスレッドで処理されることを意味します。
@param threadsCount: 画像フラグメントの並列認識のために作成されるスレッド数です。

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
小さなフォントの認識専用の追加アルゴリズムを使用できるようにします。
小さな文字が含まれる画像に便利です。
@param upscaleSmallFont: 真偽値が含まれます - upscaleSmallFont が設定されます。

`ReceiptRecognitionSettings()`
:

### クラス変数

`JAVA_CLASS_NAME`
:

### メソッド

`set_allowed_characters(self, allowedCharacters: str)`
:
許可された文字のセットです。認識結果で許可される文字の配列を決定します。
@param allowedCharacters: 文字列を含みます。

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
暗い／黒い背景に白い文字がある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。
@param automaticColorInversion: 真偽値が含まれます - automaticColorInversion が設定されます。デフォルトは True です。

`set_ignored_characters(self, ignoredCharacters: str)`
:
認識記号のブラックリストを設定します。
@param ignoredCharacters: 認識から除外される文字です。

`set_language(self, language: aspose.models.Language)`
:
OCR に使用される言語を設定します。
デフォルトではマルチランゲージ（なし）です。
@param language: 列挙型 Language の値が含まれます。

`set_threads_count(self, threadsCount: int)`
:
処理に使用するスレッド数を取得または設定します。
デフォルトでは、0 は画像がプロセッサ数と同じスレッド数で処理されることを意味します。
ThreadsCount = 1 は画像がメインスレッドで処理されることを意味します。
@param threadsCount: 画像フラグメントの並列認識のために作成されるスレッド数です。

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
小さなフォントの認識専用の追加アルゴリズムを使用できるようにします。
小さな文字が含まれる画像に便利です。
@param upscaleSmallFont: 真偽値が含まれます - upscaleSmallFont が設定されます。

`RecognitionSettings()`
:
画像認識の設定です。
認識プロセスをカスタマイズできる要素が含まれています。
    
    
デフォルトコンストラクタ: recognitionAreas を null に設定し、linesFiltration を false、autoSkew を false、recognizeSingleLine を false にします。

### クラス変数

`JAVA_CLASS_NAME`
:

### メソッド

`set_allowed_characters(self, allowedCharacters: str)`
:
許可された文字のセットです。認識結果で許可される文字の配列を決定します。
@param allowedCharacters: 文字列を含みます。

`set_automatic_color_inversion(self, automaticColorInversion: bool)`
:
暗い／黒い背景に白い文字がある画像を検出し、自動的に特別な OCR アルゴリズムを選択します。
@param automaticColorInversion: 真偽値が含まれます - automaticColorInversion が設定されます。デフォルトは True です。

`set_detect_areas_mode(self, detectAreasMode: aspose.models.DetectAreasMode)`
:
領域検出に使用されるニューラルネットワークのタイプを決定します。
@param detectAreasMode: DetectAreasMode 列挙体の値を含みます。

`set_ignored_characters(self, ignoredCharacters: str)`
:
認識記号のブラックリストを設定します。
@param ignoredCharacters: 認識から除外される文字です。

`set_language(self, language: aspose.models.Language)`
:
OCR に使用される言語を設定します。
デフォルトではマルチランゲージ（なし）です。
@param language: 列挙型 Language の値が含まれます。

`set_recognize_single_line(self, recognizeSingleLine: bool)`
:
単一行画像認識を設定します。
デフォルトでは無効 (false) です。
行への分割に関連するすべての処理ステップを無効にします。
画像が1行だけの場合は、このパラメータを true に設定します。set_recognition_areas の設定を無効にし、すべてのエリア設定は無視されます。
@param recognizeSingleLine: 単一行画像の場合は True

`set_threads_count(self, threadsCount: int)`
:
処理に使用するスレッド数を取得または設定します。
デフォルトでは、0 は画像がプロセッサ数と同じスレッド数で処理されることを意味します。
ThreadsCount = 1 は画像がメインスレッドで処理されることを意味します。
@param threadsCount: 画像フラグメントの並列認識のために作成されるスレッド数です。

`set_upscale_small_font(self, upscaleSmallFont: bool)`
:
小さなフォントの認識専用の追加アルゴリズムを使用できるようにします。
小さな文字が含まれる画像に便利です。
@param upscaleSmallFont: 真偽値が含まれます - upscaleSmallFont が設定されます。



### 参照

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)