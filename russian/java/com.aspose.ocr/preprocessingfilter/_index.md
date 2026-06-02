---
title: "PreprocessingFilter"
second_title: "Aspose.OCR для Java API Reference"
description: "Базовый класс для команд обработки изображений"
type: docs
weight: 24
url: /ru/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Базовый класс для команд обработки изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [Empty](#Empty) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Позволяет использовать дополнительную нейронную сеть для улучшения изображения - уменьшить шум. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Позволяет использовать дополнительную нейронную сеть для улучшения части изображения - уменьшить шум. |
| [AutoDewarping()](#AutoDewarping) | Автоматически исправляет геометрические искажения на изображении. |
| [AutoSkew()](#AutoSkew) | Включает автоматическую коррекцию наклона изображения. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Включает автоматическую коррекцию наклона части изображения. |
| [Binarize()](#Binarize) | Преобразует изображение в черно-белое. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Преобразует часть изображения в черно-белое. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | Дилатация добавляет пиксели к границам объектов на изображении. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | Дилатация добавляет пиксели к границам объектов в части изображения. |
| [ContrastCorrection()](#ContrastCorrection) | Фильтр коррекции контраста. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Фильтр коррекции контраста для части изображения. |
| [Invert()](#Invert) | Автоматически инвертирует цвета в документе изображения. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Автоматически инвертирует цвета в части изображения. |
| [Median()](#Median) | Медианный фильтр проходит по каждому элементу изображения и заменяет каждый пиксель медианой соседних пикселей. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | Медианный фильтр проходит через каждый элемент части изображения и заменяет каждый пиксель медианой его соседних пикселей. |
| [Resize(int width, int height)](#Resize-int-int) | Изменить масштаб изображения — увеличить или уменьшить разрешение изображения. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Изменить масштаб изображения — увеличить или уменьшить разрешение изображения. |
| [Rotate(float angle)](#Rotate-float) | Повернуть оригинальное изображение. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Повернуть часть изображения. |
| [Scale(float ratio)](#Scale-float) | Изменить масштаб изображения — увеличить или уменьшить разрешение изображения. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Изменить масштаб изображения — увеличить или уменьшить разрешение изображения. |
| [Threshold(int value)](#Threshold-int) | Создать бинарное изображение, установив пороговое значение интенсивности пикселей оригинального изображения. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Создать часть бинарного изображения, установив пороговое значение интенсивности пикселей части оригинального изображения. |
| [ToGrayscale()](#ToGrayscale) | Преобразует изображение в оттенки серого. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Добавьте новый фильтр в коллекцию, чтобы далее выполнить все операции. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### PreprocessingFilter() {#PreprocessingFilter}
```
public PreprocessingFilter()
```


### Empty {#Empty}
```
public static final PreprocessingFilter Empty
```


### AutoDenoising() {#AutoDenoising}
```
public static PreprocessingFilter AutoDenoising()
```


Позволяет использовать дополнительную нейронную сеть для улучшения изображения — уменьшения шума. Полезно для изображений с артефактами сканирования, искажениями, пятнами, бликами, градиентами, посторонними элементами.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Позволяет использовать дополнительную нейронную сеть для улучшения части изображения — уменьшения шума. Полезно для изображений с артефактами сканирования, искажениями, пятнами, бликами, градиентами, посторонними элементами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| область | java.awt.Rectangle | Rectangle для предварительной обработки. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Автоматически исправляет геометрические искажения в изображении. Требует огромных ресурсов!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Включает автоматическую коррекцию наклона изображения.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Включает автоматическую коррекцию наклона части изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| область | java.awt.Rectangle | Rectangle для предварительной обработки. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Преобразует изображение в черно-белое. Бинарные изображения — это изображения, пиксели которых имеют только два возможных значения интенсивности. Обычно они отображаются как черный и белый. Численно два значения часто равны 0 для черного и 255 для белого. Бинарные изображения получаются автоматическим пороговым преобразованием изображения.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Преобразует часть изображения в черно-белое. Бинарные изображения — это изображения, пиксели которых имеют только два возможных значения интенсивности. Обычно они отображаются как черный и белый. Численно два значения часто равны 0 для черного и 255 для белого. Бинарные изображения получаются автоматическим пороговым преобразованием изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| область | java.awt.Rectangle | Rectangle для предварительной обработки. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


Дилатация добавляет пиксели к границам объектов на изображении.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


Дилатация добавляет пиксели к границам объектов в части изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| область | java.awt.Rectangle | Rectangle для предварительной обработки. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Фильтр коррекции контраста.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Фильтр коррекции контраста для части изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| область | java.awt.Rectangle | Rectangle для предварительной обработки. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Автоматически инвертирует цвета в документе изображения.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Автоматически инвертирует цвета в части изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| область | java.awt.Rectangle | Rectangle для предварительной обработки. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


Медианный фильтр проходит по каждому элементу изображения и заменяет каждый пиксель медианой соседних пикселей.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


Медианный фильтр проходит через каждый элемент части изображения и заменяет каждый пиксель медианой его соседних пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| область | java.awt.Rectangle | Rectangle для предварительной обработки. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Изменить масштаб изображения — увеличить или уменьшить разрешение изображения. InterpolationFilterType = bilinear или nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int | Новая ширина изображения. |
| высота | int | Новая высота изображения. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Изменить масштаб изображения — увеличить или уменьшить разрешение изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина | int | Новая ширина изображения. |
| высота | int | Новая высота изображения. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Повернуть оригинальное изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения. Значение от -360 до 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Повернуть часть изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | float | Угол вращения. Значение от -360 до 360. |
| область | java.awt.Rectangle | Rectangle для предварительной обработки. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Изменить масштаб изображения - увеличить или уменьшить разрешение изображения. InterpolationFilterType default bilinear or nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| коэффициент | float | Коэффициент масштабирования. Рекомендуемое значение от 0.1 до 1 для уменьшения. От 1 до 10 для увеличения. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Изменить масштаб изображения — увеличить или уменьшить разрешение изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| коэффициент | float | Коэффициент масштабирования. Рекомендуемое значение от 0.1 до 1 для уменьшения. От 1 до 10 для увеличения. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Создать бинарное изображение, установив пороговое значение интенсивности пикселей оригинального изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Максимальное значение. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Создать часть бинарного изображения, установив пороговое значение интенсивности пикселей части оригинального изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Максимальное значение. |
| область | java.awt.Rectangle | Rectangle для предварительной обработки. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Преобразует изображение в градацию серого. Градация серого имеет 256 уровней яркости в изображении (от 0 до 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Добавьте новый фильтр в коллекцию, чтобы далее выполнять все операции. Последовательность в коллекции имеет значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Новая операция для добавления в список фильтров. |

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
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




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

