---
title: "DetectAreasMode"
second_title: "مرجع Aspose.OCR لـ Java API"
description: 
type: docs
weight: 28
url: /ar/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## الحقول

| حقل | الوصف |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | يقوم تلقائيًا بتقويم الخطوط المنحنية للنص في الصورة، مما يحسن دقة التعرف ويسمح باستعادة واستخراج المزيد من النص. |
| [FORMULA](#FORMULA) | يكتشف جميع الكتل التي تحتوي على صيغ رياضية. |
| [LEAN](#LEAN) | يعطي الأولوية للسرعة ويقلل استهلاك الموارد عن طريق حذف دعم التخطيطات المعقدة. |
| [MULTICOLUMN](#MULTICOLUMN) | يكتشف كتل نصية كبيرة مُنسقة في أعمدة. |
| [TABLE](#TABLE) | يكتشف الهياكل الجدولية في الصورة ويستخرج النص من الخلايا الفردية. |
| [UNIVERSAL](#UNIVERSAL) | يكتشف جميع كتل النص في الصورة، بما في ذلك النص المتناثر وغير المنتظم على الصور. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


يقوم تلقائيًا بتقويم الخطوط المنحنية للنص في الصورة، مما يحسن دقة التعرف ويسمح باستعادة واستخراج المزيد من النص. يتطلب قدرة معالجة وذاكرة RAM كبيرة.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


يكتشف جميع الكتل التي تحتوي على صيغ رياضية.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


يعطي الأولوية للسرعة ويقلل استهلاك الموارد عن طريق حذف دعم التخطيطات المعقدة. مناسب فقط للصور البسيطة التي تحتوي على عدد قليل من أسطر النص دون رسومات أو تنسيق.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


يكتشف كتل نصية كبيرة مُنسقة في أعمدة. الخيار الأفضل للتخطيطات متعددة الأعمدة مثل صفحات الكتب، المقالات، أو العقود.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


يكتشف الهياكل الجدولية في الصورة ويستخرج النص من الخلايا الفردية. يُنصح به للملفات الممسوحة ضوئيًا مثل جداول البيانات، التقارير، وغيرها من المستندات القائمة على الجداول.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


يكتشف جميع كتل النص في الصورة، بما في ذلك النص المتناثر وغير المنتظم على الصور. خيار متعدد الاستخدامات لمعظم الصور، باستثناء الجداول والتخطيطات متعددة الأعمدة.

