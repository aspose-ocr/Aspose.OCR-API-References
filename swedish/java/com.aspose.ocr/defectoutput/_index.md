---
title: "DefectOutput"
second_title: "Aspose.OCR för Java API-referens"
description: "Områden som innehåller defekter identifierade i bilden"
type: docs
weight: 16
url: /sv/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

Områden som innehåller defekter identifierade i bilden.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Page](#Page) | Sidnummer. |
| [Source](#Source) | Den fullständiga sökvägen till filen eller URL:en, om någon. |
| [defectAreas](#defectAreas) | Listan över bilddefekter och områden där de hittades. |


### Page {#Page}
```
public int Page
```


Sidnummer.

### Source {#Source}
```
public String Source
```


Den fullständiga sökvägen till filen eller URL:en, om någon. Tom för strömmar, byte-arrayer och Base64-kodade filer.

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


Listan över bilddefekter och områden där de hittades.
