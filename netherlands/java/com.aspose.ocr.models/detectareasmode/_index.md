---
title: "DetectAreasMode"
second_title: "Aspose.OCR for Java API-referentie"
description: 
type: docs
weight: 28
url: /nl/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | Corrigeert automatisch gebogen tekstregels in de afbeelding, verbetert de herkenningsnauwkeurigheid en maakt het mogelijk meer tekst te herstellen en te extraheren. |
| [FORMULA](#FORMULA) | Detecteert alle blokken met wiskundige formules. |
| [LEAN](#LEAN) | Geeft prioriteit aan snelheid en vermindert het resourceverbruik door ondersteuning voor complexe lay-outs weg te laten. |
| [MULTICOLUMN](#MULTICOLUMN) | Detecteert grote tekstblokken die in kolommen zijn opgemaakt. |
| [TABLE](#TABLE) | Detecteert tabelstructuren in de afbeelding en extraheert tekst uit individuele cellen. |
| [UNIVERSAL](#UNIVERSAL) | Detecteert alle tekstblokken in de afbeelding, inclusief verspreide en onregelmatige tekst op foto’s. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


Corrigeert automatisch gebogen tekstregels in de afbeelding, verbetert de herkenningsnauwkeurigheid en maakt het mogelijk meer tekst te herstellen en te extraheren. Vereist aanzienlijke verwerkingskracht en RAM.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


Detecteert alle blokken met wiskundige formules.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


Geeft prioriteit aan snelheid en vermindert het resourceverbruik door ondersteuning voor complexe lay-outs weg te laten. Alleen geschikt voor eenvoudige afbeeldingen met enkele tekstregels zonder illustraties of opmaak.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


Detecteert grote tekstblokken die in kolommen zijn opgemaakt. Beste keuze voor meerkolomslay-outs zoals boekpagina’s, artikelen of contracten.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


Detecteert tabelstructuren in de afbeelding en extraheert tekst uit individuele cellen. Aanbevolen voor gescande spreadsheets, rapporten en andere tabelgebaseerde documenten.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


Detecteert alle tekstblokken in de afbeelding, inclusief verspreide en onregelmatige tekst op foto’s. Een veelzijdige optie voor de meeste afbeeldingen, behalve voor tabellen en meerkolomslay-outs.

