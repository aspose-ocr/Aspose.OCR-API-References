---
title: "DetectAreasMode"
second_title: "Riferimento API di Aspose.OCR per Java"
description: 
type: docs
weight: 28
url: /it/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## Campi

| Campo | Descrizione |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | Raddrizza automaticamente le linee curve del testo nell'immagine, migliorando la precisione del riconoscimento e consentendo di recuperare ed estrarre più testo. |
| [FORMULA](#FORMULA) | Rileva tutti i blocchi contenenti formule matematiche. |
| [LEAN](#LEAN) | Prioritizza la velocità e riduce il consumo di risorse omettendo il supporto per layout complessi. |
| [MULTICOLUMN](#MULTICOLUMN) | Rileva grandi blocchi di testo formattati in colonne. |
| [TABLE](#TABLE) | Rileva strutture tabulari nell'immagine ed estrae il testo dalle singole celle. |
| [UNIVERSAL](#UNIVERSAL) | Rileva tutti i blocchi di testo nell'immagine, inclusi testo sparso e irregolare sulle foto. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


Raddrizza automaticamente le linee curve del testo nell'immagine, migliorando la precisione del riconoscimento e consentendo di recuperare ed estrarre più testo. Richiede una notevole potenza di elaborazione e RAM.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


Rileva tutti i blocchi contenenti formule matematiche.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


Prioritizza la velocità e riduce il consumo di risorse omettendo il supporto per layout complessi. Adatto solo per immagini semplici con poche righe di testo, senza illustrazioni o formattazione.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


Rileva grandi blocchi di testo formattati in colonne. La scelta migliore per layout a più colonne come pagine di libri, articoli o contratti.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


Rileva strutture tabulari nell'immagine ed estrae il testo dalle singole celle. Consigliato per fogli di calcolo scansionati, report e altri documenti basati su tabelle.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


Rileva tutti i blocchi di testo nell'immagine, inclusi testo sparso e irregolare sulle foto. Un'opzione versatile per la maggior parte delle immagini, eccetto tabelle e layout a più colonne.

