---
title: "Metered"
second_title: "Aspose.OCR 适用于 .NET 的 API 参考"
description: "提供设置计量密钥的方法。"
type: docs
weight: 30
url: /zh/net/aspose.ocr/metered/
---
## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered)() | 初始化此类的新实例。 |

## Methods

| 名称 | 描述 |
| --- | --- |
| [SetMeteredKey](../../aspose.ocr/metered/setmeteredkey)(string, string) | 设置计量的公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这就足够了。然而，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态，为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
| static [GetConsumptionCredit](../../aspose.ocr/metered/getconsumptioncredit)() | 获取消耗信用。 |
| static [GetConsumptionQuantity](../../aspose.ocr/metered/getconsumptionquantity)() | 获取消耗文件大小。 |

### 示例

在此示例中，将尝试设置计量的公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

组件 jar 文件：

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 另见

* namespace [Aspose.OCR](../../aspose.ocr)
* assembly [Aspose.OCR](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.OCR.dll 生成 -->
