---
title: "CarPlateRecognitionSettings"
second_title: "Aspose.OCR for Java API 参考"
description: "车牌识别的设置 包含允许自定义识别过程的元素"
type: docs
weight: 12
url: /zh/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

车牌识别的设置 包含允许自定义识别过程的元素
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | 默认构造函数：将 autoSkew 设置为 true。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | 允许的字符集。 |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | 检测白色文字位于深色/黑色背景的图像，并自动为其选择特殊的 OCR 算法。 |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | 设置识别符号的黑名单。 |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


默认构造函数：将 autoSkew 设置为 true。





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


允许的字符集。确定识别结果允许的字符类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | 包含枚举 @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) 值。 |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


检测白色文字位于深色/黑色背景的图像，并自动为其选择特殊的 OCR 算法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| automaticColorInversion | boolean | 包含布尔值 - 已设置 automaticColorInversion。 |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


设置识别符号的黑名单。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| characters | java.lang.String | 从识别中排除的字符。 |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | 设置 OCR 使用的语言。默认是多语言（无）。 |

