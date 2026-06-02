---
title: "DefectType"
second_title: "Aspose.OCR для Java API Reference"
description: "Типы дефектов изображения"
type: docs
weight: 22
url: /ru/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

Типы дефектов изображения.
## Поля

| Поле | Описание |
| --- | --- |
| [ALL](#ALL) | Все поддерживаемые дефекты изображения. |
| [BLUR](#BLUR) | Изображение не в фокусе. |
| [GLARE](#GLARE) | Области на изображении, вызванные неравномерным освещением, например, точечными светильниками или вспышкой. |
| [LOW_CONTRAST](#LOW-CONTRAST) | Блики и тени, обычно появляющиеся на изогнутых страницах. |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | Случайные белые и чёрные пиксели, разбросанные по области. |

### ALL {#ALL}
```
public static final DefectType ALL
```


Все поддерживаемые дефекты изображения.

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


Изображение размазано. Этот алгоритм обнаружения может определить только всё изображение как размытое. Конкретные области обнаружить нельзя.

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


Области на изображении, вызванные неравномерным освещением, например, точечными светильниками или вспышкой.

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


Блики и тени, обычно появляющиеся на изогнутых страницах.

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


Случайные белые и чёрные пиксели, разбросанные по области. Часто встречается в цифровых фотографиях.

