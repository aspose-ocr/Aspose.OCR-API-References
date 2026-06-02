---
title: "OcrInput"
second_title: "Aspose.OCR для Java API Reference"
description: "Основной класс для распознавания текста с изображений"
type: docs
weight: 20
url: /ru/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Основной класс для распознавания текста с изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Конструктор для создания контейнера и установки типа изображений / документов и фильтров для дальнейшей обработки / распознавания. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Добавить декодированное изображение в список для распознавания / обработки. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Добавить BufferedImage, содержащий изображение, для распознавания / обработки. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Добавить BufferedImage, содержащий многостраничное изображение, для распознавания / обработки. |
| [add(InputStream stream)](#add-java.io.InputStream) | Добавить InputStream, содержащий изображение, для распознавания / обработки. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Добавить InputStream, содержащий многостраничное изображение, для распознавания / обработки. |
| [add(String fullPath)](#add-java.lang.String) | Добавить путь или URI, содержащий изображение, для распознавания / обработки. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Добавить многостраничные изображения / документы для распознавания / обработки. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Добавить строку base64, содержащую изображение, для распознавания / обработки. |
| [clear()](#clear) | Установить количество элементов для обработки / распознавания равным 0. |
| [clearFilters()](#clearFilters) | Удалить все фильтры. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | Возвращает информацию о обработанном / распознанном изображении. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Удалить старые фильтры и установить новые. |
| [size()](#size) | Количество элементов для обработки / распознавания. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Конструктор для создания контейнера и установки типа изображений / документов и фильтров для дальнейшей обработки / распознавания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Установить тип изображений/документов, который будет добавлен в контейнер. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Установить фильтры обработки, которые будут применяться для дальнейшей обработки или распознавания. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Добавить декодированное изображение в список для распознавания / обработки. Тип изображения должен соответствовать типу, указанному в конструкторе (SingleImage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | Пиксели представлены 32-битными целочисленными значениями (rgb). |
| ширина | int | Ширина изображения. |
| высота | int | Высота изображения. |
| bitsPerPixel | int | Поддерживает 1-32 бита. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Добавить BufferedImage, содержащий изображение для распознавания / обработки. Тип изображения должен соответствовать типу, указанному в конструкторе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | java.awt.image.BufferedImage | BufferedImage, содержащий изображение или документ. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Добавить BufferedImage, содержащий многократное изображение для распознавания / обработки. Тип изображения должен соответствовать типу, указанному в конструкторе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | java.awt.image.BufferedImage | BufferedImage, содержащий многократный документ. |
| startPage | int | Первая страница/изображение для обработки / распознавания. Используется для документов. |
| pagesCount | int | Общее количество страниц/изображений для обработки / распознавания. Используется для документов. По умолчанию = все. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Добавить InputStream, содержащий изображение для распознавания / обработки. Тип изображения должен соответствовать типу, указанному в конструкторе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream, содержащий изображение или документ. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Добавьте InputStream, содержащий многостраничное изображение для распознавания / обработки. Тип изображения должен соответствовать типу, указанному в конструкторе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream, содержащий многостраничный документ. |
| startPage | int | Первая страница/изображение для обработки / распознавания. Используется для документов. |
| pagesCount | int | Общее количество страниц/изображений для обработки / распознавания. Используется для документов. По умолчанию = все. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Добавьте путь или URI, содержащий изображение для распознавания / обработки. Тип изображения должен соответствовать типу, указанному в конструкторе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath | java.lang.String | Путь к изображению/документу/папке/архиву. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Добавьте многостраничные изображения/документы для распознавания / обработки. Тип изображения должен соответствовать типу, указанному в конструкторе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fullPath | java.lang.String | Путь к изображению/документу/папке/архиву. |
| startPage | int | Первая страница/изображение для обработки / распознавания. Используется для документов, zip, папок. |
| pagesCount | int | Общее количество страниц/изображений для обработки / распознавания. Используется для документов, zip, папок. По умолчанию = все. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Добавьте строку base64, содержащую изображение для распознавания / обработки. Тип изображения должен соответствовать типу, указанному в конструкторе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| base64 | java.lang.String | Строка Base64 с одним изображением. |

### clear() {#clear}
```
public void clear()
```


Установите количество элементов для обработки / распознавания в 0. Очистите коллекцию.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Удалить все фильтры.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int}
```
public ImageData get(int index)
```


Возвращает информацию о обработанном / распознанном изображении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция изображения в списке. |

**Returns:**
[ImageData](../../com.aspose.ocr/imagedata/) - The object of @see [ImageData](../../com.aspose.ocr/imagedata/)
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator}
```
public Iterator<ImageData> iterator()
```




**Returns:**
java.util.Iterator<com.aspose.ocr.ImageData>
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### replaceFilters(PreprocessingFilter filters) {#replaceFilters-com.aspose.ocr.PreprocessingFilter}
```
public void replaceFilters(PreprocessingFilter filters)
```


Удалить старые фильтры и установить новые.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Фильтры обработки будут применены для дальнейшей обработки или распознавания. |

### size() {#size}
```
public int size()
```


Количество элементов для обработки / распознавания.

**Returns:**
int — количество элементов.
### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

