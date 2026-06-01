---
title: "SkewOutput"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Dati sull'angolo di inclinazione in gradi e sul nome del file"
type: docs
weight: 23
url: /it/java/com.aspose.ocr.models/skewoutput/
---

**Inheritance:**
java.lang.Object
```
public class SkewOutput
```

Dati sull'angolo di inclinazione in gradi e nome del file.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SkewOutput()](#SkewOutput) |  |
| [SkewOutput(String source, double angle, int page)](#SkewOutput-java.lang.String-double-int) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [Angle](#Angle) | Angolo di inclinazione in gradi. |
| [Page](#Page) | Numero di pagina. |
| [Source](#Source) | Il percorso completo al file o URL, se presente. |

### SkewOutput() {#SkewOutput}
```
public SkewOutput()
```


### SkewOutput(String source, double angle, int page) {#SkewOutput-java.lang.String-double-int}
```
public SkewOutput(String source, double angle, int page)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origine | java.lang.String |  |
| angolo | double |  |
| pagina | int |  |

### Angle {#Angle}
```
public double Angle
```


Angolo di inclinazione in gradi.

### Page {#Page}
```
public int Page
```


Numero di pagina.

### Source {#Source}
```
public String Source
```


Il percorso completo al file o URL, se presente. Vuoto per stream, array di byte, base64.
