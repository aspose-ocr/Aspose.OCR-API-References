---
title: "DetectAreasMode"
second_title: "Aspose.OCR für Java API-Referenz"
description: 
type: docs
weight: 28
url: /de/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | Richtet automatisch gekrümmte Textzeilen im Bild aus, verbessert die Erkennungsgenauigkeit und ermöglicht das Wiederherstellen und Extrahieren von mehr Text. |
| [FORMULA](#FORMULA) | Erkennt alle Blöcke mit mathematischen Formeln. |
| [LEAN](#LEAN) | Priorisiert Geschwindigkeit und reduziert den Ressourcenverbrauch, indem die Unterstützung für komplexe Layouts weggelassen wird. |
| [MULTICOLUMN](#MULTICOLUMN) | Erkennt große Textblöcke, die in Spalten formatiert sind. |
| [TABLE](#TABLE) | Erkennt tabellarische Strukturen im Bild und extrahiert Text aus einzelnen Zellen. |
| [UNIVERSAL](#UNIVERSAL) | Erkennt alle Textblöcke im Bild, einschließlich spärlichem und unregelmäßigem Text auf Fotos. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


Richtet automatisch gekrümmte Textzeilen im Bild aus, verbessert die Erkennungsgenauigkeit und ermöglicht das Wiederherstellen und Extrahieren von mehr Text. Erfordert erhebliche Rechenleistung und RAM.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


Erkennt alle Blöcke mit mathematischen Formeln.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


Priorisiert Geschwindigkeit und reduziert den Ressourcenverbrauch, indem die Unterstützung für komplexe Layouts weggelassen wird. Nur für einfache Bilder mit wenigen Textzeilen ohne Illustrationen oder Formatierung geeignet.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


Erkennt große Textblöcke, die in Spalten formatiert sind. Beste Wahl für mehrspaltige Layouts wie Buchseiten, Artikel oder Verträge.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


Erkennt tabellarische Strukturen im Bild und extrahiert Text aus einzelnen Zellen. Empfohlen für gescannte Tabellenkalkulationen, Berichte und andere tabellenbasierte Dokumente.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


Erkennt alle Textblöcke im Bild, einschließlich spärlichem und unregelmäßigem Text auf Fotos. Eine vielseitige Option für die meisten Bilder, außer für Tabellen und mehrspaltige Layouts.

