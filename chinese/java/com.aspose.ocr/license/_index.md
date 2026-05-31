---
title: "许可证"
second_title: "Aspose.OCR for Java API 参考"
description: "提供对组件进行授权的方法"
type: docs
weight: 21
url: /zh/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

提供对组件授权的方法。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License) | 初始化此类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | 对组件授权。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | 对组件授权。 |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | 对组件授权。 |
| [isValid()](#isValid--) | 检查许可证。 |
### License() {#License}
```
public License()
```


初始化此类的新实例。


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


对组件授权。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseFile | java.io.File | 文件路径名的表示 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


对组件授权。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含许可证的流。 |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


对组件授权。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseFilePath | java.lang.String | 可以是完整或短文件名。使用空字符串切换到评估模式。 |



### isValid() {#isValid--}
```
public static boolean isValid()
```


检查许可证。

**Returns:**
boolean - 布尔值，表示许可证是否有效。
