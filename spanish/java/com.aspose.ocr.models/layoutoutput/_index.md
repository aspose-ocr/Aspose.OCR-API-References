---
title: "LayoutOutput"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Información sobre áreas de contenido detectadas en la imagen"
type: docs
weight: 15
url: /es/java/com.aspose.ocr.models/layoutoutput/
---

**Inheritance:**
java.lang.Object
```
public class LayoutOutput
```

Información sobre áreas de contenido detectadas en la imagen.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LayoutOutput()](#LayoutOutput) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [captions](#captions) | Subtítulos detectados. |
| [equations](#equations) | Ecuaciones detectadas. |
| [headers](#headers) | Encabezados detectados. |
| [images](#images) | Imágenes/ilustraciones detectadas. |
| [lists](#lists) | Listas detectadas. |
| [page](#page) | Número de página. |
| [paragraphs](#paragraphs) | Párrafos detectados. |
| [source](#source) | La ruta completa al archivo o URL, si existe. |
| [tables](#tables) | Tablas detectadas. |

### LayoutOutput() {#LayoutOutput}
```
public LayoutOutput()
```


### captions {#captions}
```
public ArrayList<ContentArea> captions
```


Subtítulos detectados.

### equations {#equations}
```
public ArrayList<ContentArea> equations
```


Ecuaciones detectadas.

### headers {#headers}
```
public ArrayList<ContentArea> headers
```


Encabezados detectados.

### images {#images}
```
public ArrayList<ContentArea> images
```


Imágenes/ilustraciones detectadas.

### lists {#lists}
```
public ArrayList<ContentArea> lists
```


Listas detectadas.

### page {#page}
```
public int page
```


Número de página.

### paragraphs {#paragraphs}
```
public ArrayList<ContentArea> paragraphs
```


Párrafos detectados.

### source {#source}
```
public String source
```


La ruta completa al archivo o URL, si la hay. Vacío para flujos, matrices de bytes, base64.

### tables {#tables}
```
public ArrayList<ContentArea> tables
```


Tablas detectadas.

