---
title: "OcrOutput"
second_title: "Aspose.OCR für Java API-Referenz"
description: 
type: docs
weight: 21
url: /de/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OcrOutput()](#OcrOutput) | Initialisiert eine neue Instanz der OcrOutput-Klasse mit einer leeren Sammlung. |
## Methoden

| Methode | Beschreibung |
| --- | --- |

| [getTableData()](#getTableData) | Gibt strukturierte Tabellendaten zurück, die aus allen erkannten Seiten extrahiert wurden. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Speichert alle Erkennungsergebnisse in einen Speicherstrom im angegebenen Format. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Speichert alle Erkennungsergebnisse in einen Speicherstrom im angegebenen Format. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Speichert alle Erkennungsergebnisse in einen Speicherstrom im angegebenen Format. |
| [save(String fullFileName)](#save-java.lang.String) | Speichern Sie das gesamte Erkennungsergebnis in einer Datei. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Speichern Sie das gesamte Erkennungsergebnis in einer Datei. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Speichern Sie das gesamte Erkennungsergebnis in einer Datei. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Speichern Sie alle Erkennungsergebnisse in ein im Speicher befindliches durchsuchbares PDF-Dokument, wobei die Originalbilder als Hintergrund eingebettet werden. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Speichern Sie alle Erkennungsergebnisse in ein im Speicher befindliches durchsuchbares PDF-Dokument, wobei die Originalbilder als Hintergrund eingebettet werden. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Speichern Sie alle Erkennungsergebnisse in einer durchsuchbaren PDF-Datei, wobei die Originalbilder als Hintergrund festgelegt werden. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Speichern Sie alle Erkennungsergebnisse in einer durchsuchbaren PDF-Datei, wobei die Originalbilder als Hintergrund festgelegt werden. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Gibt strukturierte Tabellendaten zurück, die aus allen erkannten Seiten extrahiert wurden.

Jede Seite enthält Zeilen, und jede Zeile enthält Zellen mit erkanntem Text und optionalen Positionsinformationen.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Speichert alle Erkennungsergebnisse in einen Speicherstrom im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | OutputStream zum Speichern des Erkennungsergebnisses im ausgewählten Format. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Speichert alle Erkennungsergebnisse in einen Speicherstrom im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | OutputStream zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Speichert alle Erkennungsergebnisse in einen Speicherstrom im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | OutputStream zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Optional. Vollständiger Pfad zur Benutzerschriftart. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduzieren Sie die PDF-Dateigröße, indem Sie die Qualität von Hintergrundbildern verringern. Standardmäßig wird die ursprüngliche Bildqualität beibehalten. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Speichern Sie das gesamte Erkennungsergebnis in einer Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Speichern Sie das gesamte Erkennungsergebnis in einer Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Speichern Sie das gesamte Erkennungsergebnis in einer Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Optional. Vollständiger Pfad zur Benutzerschriftart. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduzieren Sie die PDF-Dateigröße, indem Sie die Qualität von Hintergrundbildern verringern. Standardmäßig wird die ursprüngliche Bildqualität beibehalten. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Speichern Sie alle Erkennungsergebnisse in ein im Speicher befindliches durchsuchbares PDF-Dokument, wobei die Originalbilder als Hintergrund eingebettet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | OutputStream zum Speichern des Erkennungsergebnisses im ausgewählten Format. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Speichern Sie alle Erkennungsergebnisse in ein im Speicher befindliches durchsuchbares PDF-Dokument, wobei die Originalbilder als Hintergrund eingebettet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | OutputStream zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| embeddedFontPath | java.lang.String | Optional. Vollständiger Pfad zur Benutzerschriftart. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduzieren Sie die PDF-Dateigröße, indem Sie die Qualität von Hintergrundbildern verringern. Standardmäßig wird die ursprüngliche Bildqualität beibehalten. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Speichern Sie alle Erkennungsergebnisse in einer durchsuchbaren PDF-Datei, wobei die Originalbilder als Hintergrund festgelegt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Speichern Sie alle Erkennungsergebnisse in einer durchsuchbaren PDF-Datei, wobei die Originalbilder als Hintergrund festgelegt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| embeddedFontPath | java.lang.String | Optional. Vollständiger Pfad zur Benutzerschriftart. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduzieren Sie die PDF-Dateigröße, indem Sie die Qualität von Hintergrundbildern verringern. Standardmäßig wird die ursprüngliche Bildqualität beibehalten. |

### size() {#size}
```
public int size()
```




**Returns:**
int
