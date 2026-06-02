---
title: "许可证"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "提供对组件授权的方法。"
type: docs
weight: 40
url: /zh/net/aspose.ocr/license/
---
## License class

提供对组件授权的方法。

```csharp
public class License
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license)() | 初始化此类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsLicensed](../../aspose.ocr/license/islicensed) { get; } | 获取指示产品是否已授权的值。 |

## Methods

| 名称 | 描述 |
| --- | --- |
| [SetLicense](../../aspose.ocr/license/setlicense#setlicense)(Stream) | 为组件授权。 |
| [SetLicense](../../aspose.ocr/license/setlicense#setlicense_1)(string) | 为组件授权。 |

### 示例

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

组件 jar 文件：

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### 另见

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
