---
title: "OcrOutput"
second_title: "Aspose.OCR for Java API-referentie"
description: 
type: docs
weight: 21
url: /nl/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OcrOutput()](#OcrOutput) | Initialiseert een nieuw exemplaar van de OcrOutput‑klasse met een lege collectie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |

| [getTableData()](#getTableData) | Retourneert gestructureerde tabelgegevens die zijn geëxtraheerd uit alle herkende pagina's. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Sla alle herkenningsresultaten op in een geheugenstroom in het opgegeven formaat. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Sla alle herkenningsresultaten op in een geheugenstroom in het opgegeven formaat. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Sla alle herkenningsresultaten op in een geheugenstroom in het opgegeven formaat. |
| [save(String fullFileName)](#save-java.lang.String) | Sla alle herkenningsresultaten op in een bestand. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Sla alle herkenningsresultaten op in een bestand. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Sla alle herkenningsresultaten op in een bestand. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Sla alle herkenningsresultaten op in een in‑memory doorzoekbaar PDF‑document, waarbij de originele afbeeldingen als achtergrond worden ingebed. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Sla alle herkenningsresultaten op in een in‑memory doorzoekbaar PDF‑document, waarbij de originele afbeeldingen als achtergrond worden ingebed. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Sla alle herkenningsresultaten op in een doorzoekbaar PDF‑bestand, waarbij de originele afbeeldingen als achtergrond worden ingesteld. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Sla alle herkenningsresultaten op in een doorzoekbaar PDF‑bestand, waarbij de originele afbeeldingen als achtergrond worden ingesteld. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Retourneert gestructureerde tabelgegevens die zijn geëxtraheerd uit alle herkende pagina's.

Elke pagina bevat rijen, en elke rij bevat cellen met herkende tekst en optionele positie‑informatie.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Sla alle herkenningsresultaten op in een geheugenstroom in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Sla alle herkenningsresultaten op in een geheugenstroom in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Sla alle herkenningsresultaten op in een geheugenstroom in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Optioneel. Volledig pad naar het gebruikerslettertype. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Verminder de PDF-bestandsgrootte door de kwaliteit van achtergrondafbeeldingen te verlagen. Standaard wordt de oorspronkelijke beeldkwaliteit behouden. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Sla alle herkenningsresultaten op in een bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met een pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Sla alle herkenningsresultaten op in een bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met een pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Sla alle herkenningsresultaten op in een bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met een pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Optioneel. Volledig pad naar het gebruikerslettertype. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Verminder de PDF-bestandsgrootte door de kwaliteit van achtergrondafbeeldingen te verlagen. Standaard wordt de oorspronkelijke beeldkwaliteit behouden. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Sla alle herkenningsresultaten op in een in‑memory doorzoekbaar PDF‑document, waarbij de originele afbeeldingen als achtergrond worden ingebed.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Sla alle herkenningsresultaten op in een in‑memory doorzoekbaar PDF‑document, waarbij de originele afbeeldingen als achtergrond worden ingebed.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| embeddedFontPath | java.lang.String | Optioneel. Volledig pad naar het gebruikerslettertype. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Verminder de PDF-bestandsgrootte door de kwaliteit van achtergrondafbeeldingen te verlagen. Standaard wordt de oorspronkelijke beeldkwaliteit behouden. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Sla alle herkenningsresultaten op in een doorzoekbaar PDF‑bestand, waarbij de originele afbeeldingen als achtergrond worden ingesteld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met een pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Sla alle herkenningsresultaten op in een doorzoekbaar PDF‑bestand, waarbij de originele afbeeldingen als achtergrond worden ingesteld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met een pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| embeddedFontPath | java.lang.String | Optioneel. Volledig pad naar het gebruikerslettertype. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Verminder de PDF-bestandsgrootte door de kwaliteit van achtergrondafbeeldingen te verlagen. Standaard wordt de oorspronkelijke beeldkwaliteit behouden. |

### size() {#size}
```
public int size()
```




**Returns:**
int
