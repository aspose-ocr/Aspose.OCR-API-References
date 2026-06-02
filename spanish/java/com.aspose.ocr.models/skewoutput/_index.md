---
title: "SkewOutput"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Datos sobre el ángulo de sesgo en grados y el nombre del archivo"
type: docs
weight: 23
url: /es/java/com.aspose.ocr.models/skewoutput/
---

**Inheritance:**
java.lang.Object
```
public class SkewOutput
```

Datos sobre el ángulo de sesgo en grados y el nombre del archivo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SkewOutput()](#SkewOutput) |  |
| [SkewOutput(String source, double angle, int page)](#SkewOutput-java.lang.String-double-int) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [Angle](#Angle) | Ángulo de sesgo en grados. |
| [Page](#Page) | Número de página. |
| [Source](#Source) | La ruta completa al archivo o URL, si existe. |

### SkewOutput() {#SkewOutput}
```
public SkewOutput()
```


### SkewOutput(String source, double angle, int page) {#SkewOutput-java.lang.String-double-int}
```
public SkewOutput(String source, double angle, int page)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | java.lang.String |  |
| ángulo | double |  |
| página | int |  |

### Angle {#Angle}
```
public double Angle
```


Ángulo de sesgo en grados.

### Page {#Page}
```
public int Page
```


Número de página.

### Source {#Source}
```
public String Source
```


La ruta completa al archivo o URL, si la hay. Vacío para flujos, matrices de bytes, base64.
