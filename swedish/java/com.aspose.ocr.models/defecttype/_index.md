---
title: "DefectType"
second_title: "Aspose.OCR för Java API-referens"
description: "Typerna av bilddefekter"
type: docs
weight: 22
url: /sv/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

Typerna av bilddefekter.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ALL](#ALL) | Alla stödda bilddefekter. |
| [BLUR](#BLUR) | Bilden är oskarp. |
| [GLARE](#GLARE) | Områden i en bild som orsakas av ojämn belysning, såsom spotlights eller blixt. |
| [LOW_CONTRAST](#LOW-CONTRAST) | Höjdpunkter och skuggor som vanligtvis visas på böjda sidor. |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | Slumpmässiga vita och svarta pixlar spridda över området. |

### ALL {#ALL}
```
public static final DefectType ALL
```


Alla stödda bilddefekter.

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


Bilden är oskarp. Denna detekteringsalgoritm kan bara identifiera hela bilden som suddig. Specifika områden kan inte upptäckas.

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


Områden i en bild som orsakas av ojämn belysning, såsom spotlights eller blixt.

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


Höjdpunkter och skuggor som vanligtvis visas på böjda sidor.

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


Slumpmässiga vita och svarta pixlar spridda över området. Förekommer ofta i digitala fotografier.

