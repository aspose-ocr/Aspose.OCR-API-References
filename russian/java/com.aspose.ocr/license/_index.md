---
title: "Лицензия"
second_title: "Aspose.OCR для Java API Reference"
description: "Предоставляет методы для лицензирования компонента"
type: docs
weight: 21
url: /ru/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Предоставляет методы для лицензирования компонента.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [License()](#License) | Инициализирует новый экземпляр этого класса. |
## Методы

| Метод | Описание |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Лицензирует компонент. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Лицензирует компонент. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Лицензирует компонент. |
| [isValid()](#isValid--) | Проверить лицензию. |
### License() {#License}
```
public License()
```


Инициализирует новый экземпляр этого класса.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Лицензирует компонент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseFile | java.io.File | представление пути к файлу |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Лицензирует компонент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий лицензию. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Лицензирует компонент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Может быть полным или коротким именем файла. Используйте пустую строку, чтобы переключиться в режим оценки. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Проверить лицензию.

**Returns:**
boolean — логическое значение, указывающее, действительна ли лицензия.
