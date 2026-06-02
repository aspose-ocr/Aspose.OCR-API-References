---
title: "OcrOutput"
second_title: "Aspose.OCR för Java API-referens"
description: 
type: docs
weight: 21
url: /sv/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OcrOutput()](#OcrOutput) | Initierar en ny instans av OcrOutput‑klassen med en tom samling. |
## Metoder

| Metod | Beskrivning |
| --- | --- |

| [getTableData()](#getTableData) | Returnerar strukturerad tabelldata extraherad från alla igenkända sidor. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Spara alla igenkänningsresultat till ett minnesström i det angivna formatet. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Spara alla igenkänningsresultat till ett minnesström i det angivna formatet. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Spara alla igenkänningsresultat till ett minnesström i det angivna formatet. |
| [save(String fullFileName)](#save-java.lang.String) | Spara alla igenkänningsresultat till en fil. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Spara alla igenkänningsresultat till en fil. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Spara alla igenkänningsresultat till en fil. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Spara alla igenkänningsresultat i ett minnesbaserat sökbart PDF-dokument, där de ursprungliga bilderna bäddas in som bakgrund. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Spara alla igenkänningsresultat i ett minnesbaserat sökbart PDF-dokument, där de ursprungliga bilderna bäddas in som bakgrund. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Spara alla igenkänningsresultat i en sökbar PDF-fil, med de ursprungliga bilderna som bakgrund. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Spara alla igenkänningsresultat i en sökbar PDF-fil, med de ursprungliga bilderna som bakgrund. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Returnerar strukturerad tabelldata extraherad från alla igenkända sidor.

Varje sida innehåller rader, och varje rad innehåller celler med igenkänd text och valfri positionsinformation.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Spara alla igenkänningsresultat till ett minnesström i det angivna formatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream för att spara igenkänningsresultat i det valda formatet. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Spara alla igenkänningsresultat till ett minnesström i det angivna formatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream för att spara igenkänningsresultat i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Spara alla igenkänningsresultat till ett minnesström i det angivna formatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream för att spara igenkänningsresultat i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Valfritt. Fullständig sökväg till användarens teckensnitt. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Minska PDF-filens storlek genom att sänka kvaliteten på bakgrundsbilder. Som standard bevaras den ursprungliga bildkvaliteten. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Spara alla igenkänningsresultat till en fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Spara alla igenkänningsresultat till en fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Spara alla igenkänningsresultat till en fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Valfritt. Fullständig sökväg till användarens teckensnitt. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Minska PDF-filens storlek genom att sänka kvaliteten på bakgrundsbilder. Som standard bevaras den ursprungliga bildkvaliteten. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Spara alla igenkänningsresultat i ett minnesbaserat sökbart PDF-dokument, där de ursprungliga bilderna bäddas in som bakgrund.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream för att spara igenkänningsresultat i det valda formatet. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Spara alla igenkänningsresultat i ett minnesbaserat sökbart PDF-dokument, där de ursprungliga bilderna bäddas in som bakgrund.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream för att spara igenkänningsresultat i det valda formatet. |
| embeddedFontPath | java.lang.String | Valfritt. Fullständig sökväg till användarens teckensnitt. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Minska PDF-filens storlek genom att sänka kvaliteten på bakgrundsbilder. Som standard bevaras den ursprungliga bildkvaliteten. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Spara alla igenkänningsresultat i en sökbar PDF-fil, med de ursprungliga bilderna som bakgrund.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Spara alla igenkänningsresultat i en sökbar PDF-fil, med de ursprungliga bilderna som bakgrund.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet. |
| embeddedFontPath | java.lang.String | Valfritt. Fullständig sökväg till användarens teckensnitt. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Minska PDF-filens storlek genom att sänka kvaliteten på bakgrundsbilder. Som standard bevaras den ursprungliga bildkvaliteten. |

### size() {#size}
```
public int size()
```




**Returns:**
int
