---
title: "DetectAreasMode"
second_title: "Aspose.OCR för Java API-referens"
description: 
type: docs
weight: 28
url: /sv/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | Rätar automatiskt upp böjda textrader i bilden, vilket förbättrar igenkänningsnoggrannheten och möjliggör att mer text återvinns och extraheras. |
| [FORMULA](#FORMULA) | Detekterar alla block med matematiska formler. |
| [LEAN](#LEAN) | Prioriterar hastighet och minskar resursförbrukning genom att utelämna stöd för komplexa layouter. |
| [MULTICOLUMN](#MULTICOLUMN) | Detekterar stora textblock formaterade i kolumner. |
| [TABLE](#TABLE) | Detekterar tabellstrukturer i bilden och extraherar text från enskilda celler. |
| [UNIVERSAL](#UNIVERSAL) | Detekterar alla textblock i bilden, inklusive gles och oregelbunden text på foton. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


Rätar automatiskt upp böjda textrader i bilden, vilket förbättrar igenkänningsnoggrannheten och möjliggör att mer text återvinns och extraheras. Kräver betydande processorkraft och RAM.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


Detekterar alla block med matematiska formler.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


Prioriterar hastighet och minskar resursförbrukning genom att utelämna stöd för komplexa layouter. Endast lämplig för enkla bilder med några textrader utan illustrationer eller formatering.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


Detekterar stora textblock formaterade i kolumner. Bästa valet för flerkolumnslayouter såsom boksidor, artiklar eller kontrakt.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


Detekterar tabellstrukturer i bilden och extraherar text från enskilda celler. Rekommenderas för skannade kalkylblad, rapporter och andra tabellbaserade dokument.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


Detekterar alla textblock i bilden, inklusive gles och oregelbunden text på foton. Ett mångsidigt alternativ för de flesta bilder, förutom tabeller och flerkolumnslayouter.

