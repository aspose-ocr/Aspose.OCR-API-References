---
title: "DefectOutput"
second_title: "Aspose.OCR для Java API Reference"
description: "Области, содержащие дефекты, обнаруженные на изображении"
type: docs
weight: 16
url: /ru/java/com.aspose.ocr/defectoutput/
---

**Inheritance:**
java.lang.Object
```
public class DefectOutput
```

Области, содержащие дефекты, обнаруженные на изображении.
## Поля

| Поле | Описание |
| --- | --- |
| [Page](#Page) | Номер страницы. |
| [Source](#Source) | Полный путь к файлу или URL, если имеется. |
| [defectAreas](#defectAreas) | Список дефектов изображения и областей, где они были обнаружены. |


### Page {#Page}
```
public int Page
```


Номер страницы.

### Source {#Source}
```
public String Source
```


Полный путь к файлу или URL, если имеется. Пусто для потоков, массивов байтов и файлов, закодированных в Base64.

### defectAreas {#defectAreas}
```
public ArrayList<DefectAreas> defectAreas
```


Список дефектов изображения и областей, где они были обнаружены.
