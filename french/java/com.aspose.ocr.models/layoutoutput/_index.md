---
title: "LayoutOutput"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Informations sur les zones de contenu détectées dans l'image"
type: docs
weight: 15
url: /fr/java/com.aspose.ocr.models/layoutoutput/
---

**Inheritance:**
java.lang.Object
```
public class LayoutOutput
```

Informations sur les zones de contenu détectées dans l'image.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LayoutOutput()](#LayoutOutput) |  |
## Champs

| Champ | Description |
| --- | --- |
| [captions](#captions) | Légendes détectées. |
| [equations](#equations) | Équations détectées. |
| [headers](#headers) | En-têtes détectés. |
| [images](#images) | Images/illustrations détectées. |
| [lists](#lists) | Listes détectées. |
| [page](#page) | Numéro de page. |
| [paragraphs](#paragraphs) | Paragraphes détectés. |
| [source](#source) | Le chemin complet du fichier ou de l'URL, le cas échéant. |
| [tables](#tables) | Tableaux détectés. |

### LayoutOutput() {#LayoutOutput}
```
public LayoutOutput()
```


### captions {#captions}
```
public ArrayList<ContentArea> captions
```


Légendes détectées.

### equations {#equations}
```
public ArrayList<ContentArea> equations
```


Équations détectées.

### headers {#headers}
```
public ArrayList<ContentArea> headers
```


En-têtes détectés.

### images {#images}
```
public ArrayList<ContentArea> images
```


Images/illustrations détectées.

### lists {#lists}
```
public ArrayList<ContentArea> lists
```


Listes détectées.

### page {#page}
```
public int page
```


Numéro de page.

### paragraphs {#paragraphs}
```
public ArrayList<ContentArea> paragraphs
```


Paragraphes détectés.

### source {#source}
```
public String source
```


Le chemin complet vers le fichier ou l'URL, le cas échéant. Vide pour les flux, les tableaux d'octets, base64.

### tables {#tables}
```
public ArrayList<ContentArea> tables
```


Tableaux détectés.

