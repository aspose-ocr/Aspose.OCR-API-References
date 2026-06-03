---
title: "Resources"
second_title: "Aspose.OCR 用于 Python via .NET API 参考"
description: 
type: docs
weight: 360
url: /zh/python-net/aspose.ocr/resources/
---

## Resources class

管理可下载的资源，以增强 Aspose.OCR 的识别能力。

Resources 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Resources() | 初始化 Resources 类的新实例 |
## 方法
| 名称 | 描述 |
| :- | :- |
| set_local_path(path) | 指定资源将下载到的目录的绝对路径或相对路径。<br/>            如果目录不存在，将自动创建。<br/>            默认情况下，资源会下载到应用程序工作目录中的 aspose_data 目录。 |
| set_local_path(path, create) | 指定资源将下载到的目录的绝对路径或相对路径。<br/>            将 `false` 传递给 `create` 参数以阻止自动创建目录。<br/>            如果提供的目录不存在且不允许创建，资源将加载到应用程序工作目录中的 aspose_data 目录。 |
| set_repository(url) | 指定将从中下载 Aspose.OCR 资源的在线仓库的 URL。<br/>            默认情况下，资源从 https://github.com/aspose-ocr/resources/ 下载。 |
| get_repository() | 返回下载 Aspose.OCR 资源的在线仓库的 URL。 |
| list_remote() | 列出在线仓库中所有兼容的资源。 |
| get_local_path() | 返回资源将被下载到的目录的完整路径。 |
| list_local() | 列出本地目录中存储的所有 Aspose.OCR 资源。 |
| allow_automatic_downloads(allow) | 允许（true）或阻止（false）从在线仓库自动下载所需资源。<br/>             默认情况下，当调用依赖该资源的方法时，会自动下载该资源。 |
| fetch_resources(names) | 从在线仓库下载 `names` 参数中指定的资源。如果一个或多个资源已经下载，它们将被覆盖。<br/>            您可以省略 .OCR 扩展名，只使用文件名。 |
| fetch_resource(name) | 从在线仓库下载 `names` 参数中指定的资源。如果一个或多个资源已经下载，它们将被覆盖。<br/>            您可以省略 .OCR 扩展名，只使用文件名。 |
| fetch_all() | 下载在线仓库中所有兼容的资源。现有的资源文件将被覆盖。 |
| remove_local(name) | 删除本地存储的 Aspose.OCR 资源。 |
| release_memory() |  |

### 另请参见

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

