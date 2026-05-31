---
title: "DefectType"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Die Arten von Bildfehlern"
type: docs
weight: 22
url: /de/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

Die Arten von Bilddefekten.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ALL](#ALL) | Alle unterstützten Bildfehler. |
| [BLUR](#BLUR) | Das Bild ist unscharf. |
| [GLARE](#GLARE) | Bereiche in einem Bild, die durch ungleichmäßige Beleuchtung verursacht werden, wie Spotlights oder Blitz. |
| [LOW_CONTRAST](#LOW-CONTRAST) | Lichter und Schatten, die typischerweise auf gewölbten Seiten erscheinen. |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | Zufällige weiße und schwarze Pixel, die über das Gebiet verstreut sind. |

### ALL {#ALL}
```
public static final DefectType ALL
```


Alle unterstützten Bildfehler.

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


Das Bild ist unscharf. Dieser Erkennungsalgorithmus kann nur das gesamte Bild als verschwommen identifizieren. Einzelne Bereiche können nicht erkannt werden.

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


Bereiche in einem Bild, die durch ungleichmäßige Beleuchtung verursacht werden, wie Spotlights oder Blitz.

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


Lichter und Schatten, die typischerweise auf gewölbten Seiten erscheinen.

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


Zufällige weiße und schwarze Pixel, die über das Gebiet verstreut sind. Tritt häufig in digitalen Fotografien auf.

