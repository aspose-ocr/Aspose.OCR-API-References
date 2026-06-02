---
title: "DefectType"
second_title: "Aspose.OCR for Java API Referansı"
description: "Görüntü kusurlarının türleri"
type: docs
weight: 22
url: /tr/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

Görüntü kusurlarının türleri.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ALL](#ALL) | Desteklenen tüm görüntü kusurları. |
| [BLUR](#BLUR) | Görüntü odakta değil. |
| [GLARE](#GLARE) | Düzensiz aydınlatma, örneğin spot ışıkları veya flaş nedeniyle bir görüntüde oluşan alanlar. |
| [LOW_CONTRAST](#LOW-CONTRAST) | Kavisli sayfalarda tipik olarak görülen vurgular ve gölgeler. |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | Alan boyunca rastgele dağıtılmış beyaz ve siyah pikseller. |

### ALL {#ALL}
```
public static final DefectType ALL
```


Desteklenen tüm görüntü kusurları.

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


Görüntü odakta değil. Bu algılama algoritması yalnızca tüm görüntünün bulanık olduğunu tespit edebilir. Belirli alanlar algılanamaz.

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


Düzensiz aydınlatma, örneğin spot ışıkları veya flaş nedeniyle bir görüntüde oluşan alanlar.

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


Kavisli sayfalarda tipik olarak görülen vurgular ve gölgeler.

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


Alan boyunca rastgele dağıtılmış beyaz ve siyah pikseller. Genellikle dijital fotoğraflarda görülür.

