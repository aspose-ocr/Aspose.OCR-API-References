---
title: 资源
second_title: Aspose.OCR 适用于 .NET 的 API 参考
description: 管理可下载的资源，以增强 Aspose.OCR 的识别能力。
type: docs
weight: 440
url: /zh/net/aspose.ocr/resources/
---
## Resources class

管理可下载的资源，以增强 Aspose.OCR 的识别能力。

```csharp
public class Resources
```

## 构造函数

| Name | 描述 |
| --- | --- |
| [Resources](resources)() | 默认构造函数。 |

## 方法

| Name | 描述 |
| --- | --- |
| static [AllowAutomaticDownloads](../../aspose.ocr/resources/allowautomaticdownloads)(bool) | 允许（true）或阻止（false）从在线存储库自动下载所需资源。默认情况下，当调用依赖该资源的方法时，会自动下载资源。 |
| static [FetchAll](../../aspose.ocr/resources/fetchall)() | 从在线存储库下载所有兼容的资源。现有的资源文件将被覆盖。 |
| static [FetchResource](../../aspose.ocr/resources/fetchresource)(string) | 从在线存储库下载 `name` 参数指定的资源。如果资源已下载，它将被覆盖。您可以省略 .OCR 扩展名，仅使用文件名。 |
| static [FetchResources](../../aspose.ocr/resources/fetchresources)(string[]) | 从在线存储库下载 `names` 参数指定的资源。如果一个或多个资源已下载，它们将被覆盖。您可以省略 .OCR 扩展名，仅使用文件名。 |
| static [GetLocalPath](../../aspose.ocr/resources/getlocalpath)() | 返回资源将被下载到的目录的完整路径。 |
| static [GetRepository](../../aspose.ocr/resources/getrepository)() | 返回下载 Aspose.OCR 资源的在线存储库的 URL。 |
| static [ListLocal](../../aspose.ocr/resources/listlocal)() | 列出本地目录中存储的所有 Aspose.OCR 资源。 |
| static [ListRemote](../../aspose.ocr/resources/listremote)() | 列出在线存储库中的所有兼容资源。 |
| static [ReleaseMemory](../../aspose.ocr/resources/releasememory)() | 卸载 OCR 模块以释放内存。已下载的模块文件将保持完整。 |
| static [RemoveLocal](../../aspose.ocr/resources/removelocal)(string) | 删除本地存储的 Aspose.OCR 资源。 |
| static [SetLocalPath](../../aspose.ocr/resources/setlocalpath#setlocalpath)(string) | 指定资源将被下载到的目录的绝对或相对路径。如果目录不存在，将自动创建。默认情况下，资源下载到应用程序工作目录下的 aspose_data 目录。 |
| static [SetLocalPath](../../aspose.ocr/resources/setlocalpath#setlocalpath_1)(string, bool) | 指定资源将被下载到的目录的绝对或相对路径。将 `false` 传递给 `create` 参数以阻止自动创建目录。如果提供的目录不存在且不允许创建，资源将加载到应用程序工作目录下的 aspose_data 目录。 |
| static [SetRepository](../../aspose.ocr/resources/setrepository)(string) | 指定下载 Aspose.OCR 资源的在线存储库的 URL。默认情况下，资源从 https://github.com/aspose-ocr/resources/ 下载。 |

### 另请参阅

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- 请勿编辑：由 xmldoccmd 为 Aspose.OCR.dll 生成 -->
