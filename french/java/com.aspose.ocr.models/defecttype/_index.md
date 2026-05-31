---
title: "DefectType"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Les types de défauts d'image"
type: docs
weight: 22
url: /fr/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

Les types de défauts d'image.
## Champs

| Champ | Description |
| --- | --- |
| [ALL](#ALL) | Tous les défauts d'image pris en charge. |
| [BLUR](#BLUR) | L'image est floue. |
| [GLARE](#GLARE) | Zones d'une image causées par un éclairage inégal, comme les spots ou le flash. |
| [LOW_CONTRAST](#LOW-CONTRAST) | Reflets et ombres apparaissant généralement sur des pages courbées. |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | Pixels blancs et noirs aléatoires dispersés sur la zone. |

### ALL {#ALL}
```
public static final DefectType ALL
```


Tous les défauts d'image pris en charge.

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


L'image est hors de mise au point. Cet algorithme de détection ne peut identifier que l'image entière comme floue. Les zones spécifiques ne peuvent pas être détectées.

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


Zones d'une image causées par un éclairage inégal, comme les spots ou le flash.

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


Reflets et ombres apparaissant généralement sur des pages courbées.

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


Pixels blancs et noirs aléatoires dispersés sur la zone. Se produit souvent dans les photographies numériques.

