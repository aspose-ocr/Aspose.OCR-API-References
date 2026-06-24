---
title: "DefectType"
second_title: "مرجع Aspose.OCR لـ Java API"
description: "أنواع عيوب الصورة"
type: docs
weight: 22
url: /ar/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

أنواع عيوب الصورة.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [ALL](#ALL) | جميع عيوب الصورة المدعومة. |
| [BLUR](#BLUR) | الصورة غير واضحة. |
| [GLARE](#GLARE) | المناطق في الصورة التي تسببها إضاءة غير متساوية، مثل الأضواء المركزة أو الفلاش. |
| [LOW_CONTRAST](#LOW-CONTRAST) | الإضاءات والظلال التي تظهر عادةً على الصفحات المنحنية. |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | بكسلات بيضاء وسوداء عشوائية متناثرة عبر المنطقة. |

### ALL {#ALL}
```
public static final DefectType ALL
```


جميع عيوب الصورة المدعومة.

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


الصورة غير مركزة. لا يمكن لهذا الخوارزمية الكشف إلا عن الصورة بأكملها كضبابية. لا يمكن اكتشاف المناطق المحددة.

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


المناطق في الصورة التي تسببها إضاءة غير متساوية، مثل الأضواء المركزة أو الفلاش.

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


الإضاءات والظلال التي تظهر عادةً على الصفحات المنحنية.

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


بكسلات بيضاء وسوداء عشوائية متناثرة عبر المنطقة. غالبًا ما تحدث في الصور الرقمية.

