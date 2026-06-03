---
title: "Resources"
second_title: "Python 用 Aspose.OCR via .NET API リファレンス"
description: 
type: docs
weight: 360
url: /ja/python-net/aspose.ocr/resources/
---

## Resources class

Aspose.OCR の認識機能を強化するダウンロード可能なリソースを管理します。

Resources 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Resources() | Resources クラスの新しいインスタンスを初期化します |
## Methods
| 名前 | 説明 |
| :- | :- |
| set_local_path(path) | リソースがダウンロードされるディレクトリへの絶対パスまたは相対パスを指定します。<br/>            ディレクトリが存在しない場合は自動的に作成されます。<br/>            デフォルトでは、リソースはアプリケーションの作業ディレクトリ内の aspose_data ディレクトリにダウンロードされます。 |
| set_local_path(path, create) | リソースがダウンロードされるディレクトリへの絶対パスまたは相対パスを指定します。<br/>            `create` パラメータに `false` を渡すと、ディレクトリが自動的に作成されるのを防止します。<br/>            指定されたディレクトリが存在せず、作成が許可されていない場合、リソースはアプリケーションの作業ディレクトリ内の aspose_data ディレクトリにロードされます。 |
| set_repository(url) | オンラインリポジトリから Aspose.OCR リソースをダウンロードする URL を指定します。<br/>            デフォルトでは、リソースは https://github.com/aspose-ocr/resources/ からダウンロードされます。 |
| get_repository() | Aspose.OCR リソースがダウンロードされるオンラインリポジトリの URL を返します。 |
| list_remote() | オンラインリポジトリからすべての互換リソースを一覧表示します。 |
| get_local_path() | リソースがダウンロードされるディレクトリへのフルパスを返します。 |
| list_local() | ローカルディレクトリに保存されているすべての Aspose.OCR リソースを一覧表示します。 |
| allow_automatic_downloads(allow) | オンラインリポジトリから必要なリソースの自動ダウンロードを許可 (true) またはブロック (false) します。<br/>             デフォルトでは、依存するメソッドが呼び出されたときにリソースが自動的にダウンロードされます。 |
| fetch_resources(names) | オンラインリポジトリから `names` パラメータで指定されたリソースをダウンロードします。すでにダウンロードされているリソースがある場合は上書きされます。<br/>            .OCR 拡張子を省略してファイル名だけを使用することもできます。 |
| fetch_resource(name) | オンラインリポジトリから `names` パラメータで指定されたリソースをダウンロードします。すでにダウンロードされているリソースがある場合は上書きされます。<br/>            .OCR 拡張子を省略してファイル名だけを使用することもできます。 |
| fetch_all() | オンラインリポジトリからすべての互換リソースをダウンロードします。既存のリソースファイルは上書きされます。 |
| remove_local(name) | ローカルに保存されている Aspose.OCR リソースを削除します。 |
| release_memory() |  |

### 参照

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

