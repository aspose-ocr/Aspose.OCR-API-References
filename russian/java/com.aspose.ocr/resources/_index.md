---
title: "Ресурсы"
second_title: "Aspose.OCR для Java API Reference"
description: "Управляйте загружаемыми ресурсами, которые повышают возможности распознавания Aspose.OCR"
type: docs
weight: 32
url: /ru/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Управляйте загружаемыми ресурсами, которые расширяют возможности распознавания Aspose.OCR.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Resources()](#Resources) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Разрешить (true) или блокировать (false) автоматическую загрузку необходимых ресурсов из онлайн‑репозитория. |
| [FetchAll()](#FetchAll) | Скачайте все совместимые ресурсы из онлайн‑репозитория. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Скачайте ресурс, указанный в параметре name, из онлайн‑репозитория. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Скачайте ресурсы, указанные в параметре names, из онлайн‑репозитория. |
| [GetLocalPath()](#GetLocalPath) | Верните полный путь к каталогу, куда будут загружаться ресурсы. |
| [GetRepository()](#GetRepository) | Верните URL онлайн‑репозитория, из которого загружаются ресурсы Aspose.OCR. |
| [ListLocal()](#ListLocal) | Выведите список всех ресурсов Aspose.OCR, хранящихся в локальном каталоге. |
| [ListRemote()](#ListRemote) | Выведите список всех совместимых ресурсов из онлайн‑репозитория. |
| [ReleaseMemory()](#ReleaseMemory) | Выгрузите модули OCR, чтобы освободить память. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Удаляет локально сохранённый ресурс Aspose.OCR. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Укажите абсолютный или относительный путь к каталогу, куда будут загружаться ресурсы. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Укажите абсолютный или относительный путь к каталогу, куда будут загружаться ресурсы. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Укажите URL онлайн‑репозитория, из которого будут загружаться ресурсы Aspose.OCR. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Разрешить (true) или блокировать (false) автоматическую загрузку необходимых ресурсов из онлайн‑репозитория. По умолчанию ресурс автоматически загружается, когда вызывается метод, зависящий от него.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| allow | java.lang.Boolean | Булево значение, позволяющее разрешить или блокировать автоматическую загрузку необходимых ресурсов. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Скачайте все совместимые ресурсы из онлайн‑репозитория. Существующие файлы ресурсов будут перезаписаны.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Скачайте ресурс, указанный в параметре name, из онлайн‑репозитория. Если ресурс уже загружен, он будет перезаписан. Вы можете опустить расширение .OCR и использовать только имя файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Строка с именем ресурса. См. метод ListRemote. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Скачайте ресурсы, указанные в параметре names, из онлайн‑репозитория. Если один или несколько ресурсов уже загружены, они будут перезаписаны. Вы можете опустить расширение .OCR и использовать только имена файлов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| names | java.lang.String[] | Массив с именами ресурсов. См. метод ListRemote. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Верните полный путь к каталогу, куда будут загружаться ресурсы.

**Returns:**
java.lang.String - Строка с путём к каталогу ресурсов.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Верните URL онлайн‑репозитория, из которого загружаются ресурсы Aspose.OCR.

**Returns:**
java.lang.String - URL онлайн‑репозитория.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Выведите список всех ресурсов Aspose.OCR, хранящихся в локальном каталоге.

**Returns:**
java.util.List<java.lang.String> - Список всех ресурсов Aspose.OCR, хранящихся в локальном каталоге.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Выведите список всех совместимых ресурсов из онлайн‑репозитория.

**Returns:**
java.util.List<java.lang.String> - Список имен ресурсов.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Выгрузите OCR‑модули, чтобы освободить память. Загруженные файлы модулей останутся нетронутыми.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Удаляет локально сохранённый ресурс Aspose.OCR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Укажите абсолютный или относительный путь к каталогу, в который будут загружаться ресурсы. Если каталог не существует, он будет создан автоматически. По умолчанию ресурсы загружаются в каталог aspose\_data в рабочем каталоге приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | java.lang.String | Абсолютный или относительный путь к каталогу. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Укажите абсолютный или относительный путь к каталогу, в который будут загружаться ресурсы. Передайте false параметру create, чтобы предотвратить автоматическое создание каталога. Если указанный каталог не существует и создание не разрешено, ресурсы будут загружены в каталог aspose\_data в рабочем каталоге приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | java.lang.String | Абсолютный или относительный путь к каталогу. |
| create | java.lang.Boolean | Параметр, предотвращающий автоматическое создание каталога. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Укажите URL онлайн‑репозитория, из которого будут загружаться ресурсы Aspose.OCR. По умолчанию ресурсы загружаются с https://github.com/aspose-ocr/resources/.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL онлайн‑репозитория. |


