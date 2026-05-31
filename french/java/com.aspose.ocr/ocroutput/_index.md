---
title: "OcrOutput"
second_title: "Référence API d'Aspose.OCR pour Java"
description: 
type: docs
weight: 21
url: /fr/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OcrOutput()](#OcrOutput) | Initialise une nouvelle instance de la classe OcrOutput avec une collection vide. |
## Méthodes

| Méthode | Description |
| --- | --- |

| [getTableData()](#getTableData) | Renvoie les données de tableau structurées extraites de toutes les pages reconnues. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Enregistrez tous les résultats de reconnaissance dans un flux mémoire au format spécifié. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Enregistrez tous les résultats de reconnaissance dans un flux mémoire au format spécifié. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Enregistrez tous les résultats de reconnaissance dans un flux mémoire au format spécifié. |
| [save(String fullFileName)](#save-java.lang.String) | Enregistrez tous les résultats de reconnaissance dans un fichier. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Enregistrez tous les résultats de reconnaissance dans un fichier. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Enregistrez tous les résultats de reconnaissance dans un fichier. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Enregistrez tous les résultats de reconnaissance dans un document PDF consultable en mémoire, en intégrant les images originales comme arrière-plan. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Enregistrez tous les résultats de reconnaissance dans un document PDF consultable en mémoire, en intégrant les images originales comme arrière-plan. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Enregistrez tous les résultats de reconnaissance dans un fichier PDF consultable, avec les images originales définies comme arrière-plan. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Enregistrez tous les résultats de reconnaissance dans un fichier PDF consultable, avec les images originales définies comme arrière-plan. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Renvoie les données de tableau structurées extraites de toutes les pages reconnues.

Chaque page contient des lignes, et chaque ligne contient des cellules avec le texte reconnu et des informations de position facultatives.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Enregistrez tous les résultats de reconnaissance dans un flux mémoire au format spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream pour enregistrer le résultat de la reconnaissance dans le format sélectionné. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Enregistrez tous les résultats de reconnaissance dans un flux mémoire au format spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream pour enregistrer le résultat de la reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format de document (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Enregistrez tous les résultats de reconnaissance dans un flux mémoire au format spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream pour enregistrer le résultat de la reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format de document (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Facultatif. Chemin complet vers la police utilisateur. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Réduisez la taille du fichier PDF en abaissant la qualité des images d'arrière-plan. Par défaut, la qualité originale de l'image est conservée. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Enregistrez tous les résultats de reconnaissance dans un fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Enregistrez tous les résultats de reconnaissance dans un fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format de document (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Enregistrez tous les résultats de reconnaissance dans un fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format de document (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Facultatif. Chemin complet vers la police utilisateur. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Réduisez la taille du fichier PDF en abaissant la qualité des images d'arrière-plan. Par défaut, la qualité originale de l'image est conservée. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Enregistrez tous les résultats de reconnaissance dans un document PDF consultable en mémoire, en intégrant les images originales comme arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream pour enregistrer le résultat de la reconnaissance dans le format sélectionné. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Enregistrez tous les résultats de reconnaissance dans un document PDF consultable en mémoire, en intégrant les images originales comme arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream pour enregistrer le résultat de la reconnaissance dans le format sélectionné. |
| embeddedFontPath | java.lang.String | Facultatif. Chemin complet vers la police utilisateur. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Réduisez la taille du fichier PDF en abaissant la qualité des images d'arrière-plan. Par défaut, la qualité originale de l'image est conservée. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Enregistrez tous les résultats de reconnaissance dans un fichier PDF consultable, avec les images originales définies comme arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Enregistrez tous les résultats de reconnaissance dans un fichier PDF consultable, avec les images originales définies comme arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné. |
| embeddedFontPath | java.lang.String | Facultatif. Chemin complet vers la police utilisateur. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Réduisez la taille du fichier PDF en abaissant la qualité des images d'arrière-plan. Par défaut, la qualité originale de l'image est conservée. |

### size() {#size}
```
public int size()
```




**Returns:**
int
