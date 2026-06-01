---
title: "DefectOutput"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Aree contenenti difetti identificati nell'immagine"
type: docs
weight: 16
url: /it/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

Aree contenenti difetti identificati nell'immagine.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Page](#Page) | Numero di pagina. |
| [Source](#Source) | Il percorso completo al file o URL, se presente. |
| [defectAreas](#defectAreas) | L'elenco dei difetti dell'immagine e delle aree in cui sono stati trovati. |


### Page {#Page}
```
public int Page
```


Numero di pagina.

### Source {#Source}
```
public String Source
```


Il percorso completo al file o URL, se presente. Vuoto per stream, array di byte e file codificati in Base64.

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


L'elenco dei difetti dell'immagine e delle aree in cui sono stati trovati.
