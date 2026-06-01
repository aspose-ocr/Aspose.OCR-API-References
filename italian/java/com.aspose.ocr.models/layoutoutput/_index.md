---
title: "LayoutOutput"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Informazioni sulle aree di contenuto rilevate nell'immagine"
type: docs
weight: 15
url: /it/java/com.aspose.ocr.models/layoutoutput/
---

**Inheritance:**
java.lang.Object
```
public class LayoutOutput
```

Informazioni sulle aree di contenuto rilevate nell'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LayoutOutput()](#LayoutOutput) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [captions](#captions) | Didascalie rilevate. |
| [equations](#equations) | Equazioni rilevate. |
| [headers](#headers) | Intestazioni rilevate. |
| [images](#images) | Immagini/illustrazioni rilevate. |
| [lists](#lists) | Elenchi rilevati. |
| [page](#page) | Numero di pagina. |
| [paragraphs](#paragraphs) | Paragrafi rilevati. |
| [source](#source) | Il percorso completo al file o URL, se presente. |
| [tables](#tables) | Tabelle rilevate. |

### LayoutOutput() {#LayoutOutput}
```
public LayoutOutput()
```


### captions {#captions}
```
public ArrayList<ContentArea> captions
```


Didascalie rilevate.

### equations {#equations}
```
public ArrayList<ContentArea> equations
```


Equazioni rilevate.

### headers {#headers}
```
public ArrayList<ContentArea> headers
```


Intestazioni rilevate.

### images {#images}
```
public ArrayList<ContentArea> images
```


Immagini/illustrazioni rilevate.

### lists {#lists}
```
public ArrayList<ContentArea> lists
```


Elenchi rilevati.

### page {#page}
```
public int page
```


Numero di pagina.

### paragraphs {#paragraphs}
```
public ArrayList<ContentArea> paragraphs
```


Paragrafi rilevati.

### source {#source}
```
public String source
```


Il percorso completo al file o URL, se presente. Vuoto per stream, array di byte, base64.

### tables {#tables}
```
public ArrayList<ContentArea> tables
```


Tabelle rilevate.

