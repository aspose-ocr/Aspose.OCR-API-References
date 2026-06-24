---
title: "Metered"
second_title: "适用于 Python via .NET 的 Aspose.OCR API 参考"
description: 
type: docs
weight: 190
url: /zh/python-net/aspose.ocr/metered/
---

## Metered class

提供设置计量密钥的方法。

Metered 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Metered() | 初始化此类的新实例。 |
## Methods
| 名称 | 描述 |
| :- | :- |
| set_metered_key(public_key, private_key) | 设置计量版的公钥和私钥。<br/>            如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这就足够。<br/>            但是，如果始终无法上传使用数据且超过 24 小时，许可证将被设为评估状态，<br/>            为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
| get_consumption_quantity() | 获取消费文件大小。 |
| get_consumption_credit() | 获取消费积分。 |

### 另请参见

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

