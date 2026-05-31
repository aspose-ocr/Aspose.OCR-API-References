---
title: "DefectType"
second_title: "Aspose.OCR for Java API 参考"
description: "图像缺陷的类型"
type: docs
weight: 22
url: /zh/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

图像缺陷的类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ALL](#ALL) | 所有支持的图像缺陷。 |
| [BLUR](#BLUR) | 图像失焦。 |
| [GLARE](#GLARE) | 图像中因光照不均导致的区域，例如聚光灯或闪光灯。 |
| [LOW_CONTRAST](#LOW-CONTRAST) | 在弯曲页面上通常出现的高光和阴影。 |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | 随机的白色和黑色像素散布在整个区域。 |

### ALL {#ALL}
```
public static final DefectType ALL
```


所有支持的图像缺陷。

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


图像失焦。此检测算法只能识别整幅图像模糊，无法检测特定区域。

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


图像中因光照不均导致的区域，例如聚光灯或闪光灯。

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


在弯曲页面上通常出现的高光和阴影。

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


随机的白色和黑色像素散布在整个区域。常见于数码照片。

