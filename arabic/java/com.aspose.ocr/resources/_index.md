---
title: "الموارد"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "إدارة الموارد القابلة للتنزيل التي تعزز قدرات التعرف في Aspose.OCR"
type: docs
weight: 32
url: /ar/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

إدارة الموارد القابلة للتنزيل التي تعزز قدرات التعرف في Aspose.OCR.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Resources()](#Resources) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | السماح (true) أو حظر (false) التنزيل التلقائي للموارد المطلوبة من المستودع عبر الإنترنت. |
| [FetchAll()](#FetchAll) | قم بتنزيل جميع الموارد المتوافقة من المستودع عبر الإنترنت. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | قم بتنزيل المورد المحدد في معامل الاسم من المستودع عبر الإنترنت. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | قم بتنزيل الموارد المحددة في معامل الأسماء من المستودع عبر الإنترنت. |
| [GetLocalPath()](#GetLocalPath) | أرجع المسار الكامل إلى الدليل حيث سيتم تنزيل الموارد. |
| [GetRepository()](#GetRepository) | أرجع عنوان URL للمستودع عبر الإنترنت الذي يتم منه تنزيل موارد Aspose.OCR. |
| [ListLocal()](#ListLocal) | اعرض جميع موارد Aspose.OCR المخزنة في الدليل المحلي. |
| [ListRemote()](#ListRemote) | اعرض جميع الموارد المتوافقة من المستودع عبر الإنترنت. |
| [ReleaseMemory()](#ReleaseMemory) | أفرغ وحدات OCR لتحرير الذاكرة. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | يزيل المورد المخزن محليًا من Aspose.OCR. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | حدد مسارًا مطلقًا أو نسبيًا إلى الدليل حيث سيتم تنزيل الموارد. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | حدد مسارًا مطلقًا أو نسبيًا إلى الدليل حيث سيتم تنزيل الموارد. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | حدد عنوان URL للمستودع عبر الإنترنت الذي سيتم تنزيل موارد Aspose.OCR منه. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


السماح (true) أو حظر (false) التنزيل التلقائي للموارد المطلوبة من المستودع عبر الإنترنت. بشكل افتراضي، يتم تنزيل المورد تلقائيًا عندما يتم استدعاء طريقة تعتمد عليه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السماح | java.lang.Boolean | قيمة Boolean للسماح أو حظر التنزيل التلقائي للموارد المطلوبة. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


قم بتنزيل جميع الموارد المتوافقة من المستودع عبر الإنترنت. سيتم استبدال ملفات الموارد الموجودة.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


قم بتنزيل المورد المحدد في معامل الاسم من المستودع عبر الإنترنت. إذا كان المورد قد تم تنزيله بالفعل، فسيتم استبداله. يمكنك حذف امتداد .OCR واستخدام اسم الملف فقط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | سلسلة تحتوي على اسم المورد. راجع طريقة ListRemote. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


قم بتنزيل الموارد المحددة في معامل الأسماء من المستودع عبر الإنترنت. إذا تم تنزيل مورد واحد أو أكثر بالفعل، فسيتم استبداله. يمكنك حذف امتداد .OCR واستخدام أسماء الملفات فقط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الأسماء | java.lang.String[] | مصفوفة تحتوي على أسماء الموارد. راجع طريقة ListRemote. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


أرجع المسار الكامل إلى الدليل حيث سيتم تنزيل الموارد.

**Returns:**
java.lang.String - سلسلة تحتوي على المسار إلى دليل الموارد.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


أرجع عنوان URL للمستودع عبر الإنترنت الذي يتم منه تنزيل موارد Aspose.OCR.

**Returns:**
java.lang.String - عنوان URL للمستودع عبر الإنترنت.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


اعرض جميع موارد Aspose.OCR المخزنة في الدليل المحلي.

**Returns:**
java.util.List<java.lang.String> - اعرض جميع موارد Aspose.OCR المخزنة في الدليل المحلي.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


اعرض جميع الموارد المتوافقة من المستودع عبر الإنترنت.

**Returns:**
java.util.List<java.lang.String> - قائمة بأسماء الموارد.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


قم بإلغاء تحميل وحدات OCR لتفريغ الذاكرة. ستظل ملفات الوحدات التي تم تنزيلها سليمة.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


يزيل المورد المخزن محليًا من Aspose.OCR.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


حدد مسارًا مطلقًا أو نسبيًا إلى الدليل الذي سيتم تنزيل الموارد فيه. إذا لم يكن الدليل موجودًا، سيتم إنشاؤه تلقائيًا. بشكل افتراضي، يتم تنزيل الموارد إلى دليل aspose\_data في دليل عمل التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | مسار مطلق أو نسبي إلى الدليل. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


حدد مسارًا مطلقًا أو نسبيًا إلى الدليل الذي سيتم تنزيل الموارد فيه. مرّر القيمة false إلى معامل create لمنع إنشاء الدليل تلقائيًا. إذا لم يكن الدليل المحدد موجودًا ولم يُسمح بالإنشاء، سيتم تحميل الموارد إلى دليل aspose\_data في دليل عمل التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | مسار مطلق أو نسبي إلى الدليل. |
| إنشاء | java.lang.Boolean | معامل لمنع إنشاء الدليل تلقائيًا. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


حدد عنوان URL للمستودع عبر الإنترنت الذي سيتم تنزيل موارد Aspose.OCR منه. بشكل افتراضي، يتم تنزيل الموارد من https://github.com/aspose-ocr/resources/.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| عنوان URL | java.lang.String | عنوان URL للمستودع عبر الإنترنت. |


