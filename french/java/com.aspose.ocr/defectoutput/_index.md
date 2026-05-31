---
title: "DefectOutput"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Zones contenant des défauts identifiés dans l'image"
type: docs
weight: 16
url: /fr/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

Zones contenant des défauts identifiés dans l'image.
## Champs

| Champ | Description |
| --- | --- |
| [Page](#Page) | Numéro de page. |
| [Source](#Source) | Le chemin complet du fichier ou de l'URL, le cas échéant. |
| [defectAreas](#defectAreas) | La liste des défauts d'image et des zones où ils ont été trouvés. |


### Page {#Page}
```
public int Page
```


Numéro de page.

### Source {#Source}
```
public String Source
```


Le chemin complet du fichier ou de l'URL, le cas échéant. Vide pour les flux, les tableaux d'octets et les fichiers encodés en Base64.

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


La liste des défauts d'image et des zones où ils ont été trouvés.
