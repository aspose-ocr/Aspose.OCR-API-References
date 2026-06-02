---
title: "DefectOutput"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Áreas que contienen defectos identificados en la imagen"
type: docs
weight: 16
url: /es/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

Áreas que contienen defectos identificados en la imagen.
## Campos

| Campo | Descripción |
| --- | --- |
| [Page](#Page) | Número de página. |
| [Source](#Source) | La ruta completa al archivo o URL, si existe. |
| [defectAreas](#defectAreas) | La lista de defectos de imagen y áreas donde se encontraron. |


### Page {#Page}
```
public int Page
```


Número de página.

### Source {#Source}
```
public String Source
```


La ruta completa al archivo o URL, si existe. Vacío para flujos, matrices de bytes y archivos codificados en Base64.

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


La lista de defectos de imagen y áreas donde se encontraron.
