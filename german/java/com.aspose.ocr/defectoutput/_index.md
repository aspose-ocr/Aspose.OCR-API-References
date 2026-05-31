---
title: "DefectOutput"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Bereiche, die Defekte im Bild enthalten"
type: docs
weight: 16
url: /de/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

Bereiche, die im Bild erkannte Defekte enthalten.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Page](#Page) | Seitennummer. |
| [Source](#Source) | Der vollständige Pfad zur Datei oder URL, falls vorhanden. |
| [defectAreas](#defectAreas) | Die Liste der Bilddefekte und der Bereiche, in denen sie gefunden wurden. |


### Page {#Page}
```
public int Page
```


Seitennummer.

### Source {#Source}
```
public String Source
```


Der vollständige Pfad zur Datei oder URL, falls vorhanden. Leer für Streams, Byte-Arrays und Base64-codierte Dateien.

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


Die Liste der Bilddefekte und der Bereiche, in denen sie gefunden wurden.
