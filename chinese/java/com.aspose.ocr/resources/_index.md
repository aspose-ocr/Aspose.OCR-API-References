---
title: "资源"
second_title: "Aspose.OCR for Java API 参考"
description: "管理可下载的资源，以提升 Aspose.OCR 的识别能力"
type: docs
weight: 32
url: /zh/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

管理可下载的资源，以增强 Aspose.OCR 的识别能力。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Resources()](#Resources) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | 允许（true）或阻止（false）从在线仓库自动下载所需资源。 |
| [FetchAll()](#FetchAll) | 从在线仓库下载所有兼容的资源。 |
| [FetchResource(String name)](#FetchResource-java.lang.String) | 从在线存储库下载 name 参数指定的资源。 |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | 从在线存储库下载 names 参数指定的资源。 |
| [GetLocalPath()](#GetLocalPath) | 返回资源将被下载的目录的完整路径。 |
| [GetRepository()](#GetRepository) | 返回下载 Aspose.OCR 资源的在线存储库的 URL。 |
| [ListLocal()](#ListLocal) | 列出本地目录中存储的所有 Aspose.OCR 资源。 |
| [ListRemote()](#ListRemote) | 列出在线存储库中所有兼容的资源。 |
| [ReleaseMemory()](#ReleaseMemory) | 卸载 OCR 模块以释放内存。 |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | 删除本地存储的 Aspose.OCR 资源。 |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | 指定资源将被下载的目录的绝对或相对路径。 |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | 指定资源将被下载的目录的绝对或相对路径。 |
| [SetRepository(String url)](#SetRepository-java.lang.String) | 指定将下载 Aspose.OCR 资源的在线存储库的 URL。 |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


允许 (true) 或阻止 (false) 自动下载在线存储库中所需的资源。默认情况下，当调用依赖该资源的方法时，会自动下载资源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| allow | java.lang.Boolean | 用于允许或阻止自动下载所需资源的布尔值。 |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


从在线存储库下载所有兼容的资源。现有的资源文件将被覆盖。

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


从在线存储库下载 name 参数指定的资源。如果资源已下载，它将被覆盖。您可以省略 .OCR 扩展名，仅使用文件名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 包含资源名称的字符串。参见 ListRemote 方法。 |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


从在线存储库下载 names 参数指定的资源。如果一个或多个资源已下载，它们将被覆盖。您可以省略 .OCR 扩展名，仅使用文件名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| names | java.lang.String[] | 包含资源名称的数组。参见 ListRemote 方法。 |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


返回资源将被下载的目录的完整路径。

**Returns:**
java.lang.String - 包含资源目录路径的字符串。
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


返回下载 Aspose.OCR 资源的在线存储库的 URL。

**Returns:**
java.lang.String - 在线存储库的 URL。
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


列出本地目录中存储的所有 Aspose.OCR 资源。

**Returns:**
java.util.List<java.lang.String> - 列出本地目录中存储的所有 Aspose.OCR 资源。
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


列出在线存储库中所有兼容的资源。

**Returns:**
java.util.List<java.lang.String> - 资源名称列表。
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


卸载 OCR 模块以释放内存。已下载的模块文件将保持完整。

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


删除本地存储的 Aspose.OCR 资源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


指定资源将下载到的目录的绝对路径或相对路径。如果目录不存在，它将自动创建。默认情况下，资源下载到应用程序工作目录中的 aspose\_data 目录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 目录的绝对路径或相对路径。 |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


指定资源将下载到的目录的绝对路径或相对路径。将 false 传递给 create 参数以阻止自动创建目录。如果提供的目录不存在且不允许创建，资源将加载到应用程序工作目录中的 aspose\_data 目录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 目录的绝对路径或相对路径。 |
| create | java.lang.Boolean | 阻止目录自动创建的参数。 |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


指定将下载 Aspose.OCR 资源的在线仓库的 URL。默认情况下，资源从 https://github.com/aspose-ocr/resources/ 下载。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 在线仓库的 URL。 |


