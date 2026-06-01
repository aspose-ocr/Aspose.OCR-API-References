---
title: "OcrOutput"
second_title: "Riferimento API di Aspose.OCR per Java"
description: 
type: docs
weight: 21
url: /it/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OcrOutput()](#OcrOutput) | Inizializza una nuova istanza della classe OcrOutput con una collezione vuota. |
## Metodi

| Metodo | Descrizione |
| --- | --- |

| [getTableData()](#getTableData) | Restituisce i dati della tabella strutturata estratti da tutte le pagine riconosciute. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Salva tutti i risultati del riconoscimento in uno stream di memoria nel formato specificato. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Salva tutti i risultati del riconoscimento in uno stream di memoria nel formato specificato. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Salva tutti i risultati del riconoscimento in uno stream di memoria nel formato specificato. |
| [save(String fullFileName)](#save-java.lang.String) | Salva tutti i risultati del riconoscimento in un file. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Salva tutti i risultati del riconoscimento in un file. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Salva tutti i risultati del riconoscimento in un file. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Salva tutti i risultati del riconoscimento in un documento PDF ricercabile in memoria, incorporando le immagini originali come sfondo. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Salva tutti i risultati del riconoscimento in un documento PDF ricercabile in memoria, incorporando le immagini originali come sfondo. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Salva tutti i risultati del riconoscimento in un file PDF ricercabile, con le immagini originali impostate come sfondo. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Salva tutti i risultati del riconoscimento in un file PDF ricercabile, con le immagini originali impostate come sfondo. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Restituisce i dati della tabella strutturata estratti da tutte le pagine riconosciute.

Ogni pagina contiene righe, e ogni riga contiene celle con testo riconosciuto e informazioni di posizione opzionali.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Salva tutti i risultati del riconoscimento in uno stream di memoria nel formato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream per salvare il risultato del riconoscimento nel formato selezionato. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Salva tutti i risultati del riconoscimento in uno stream di memoria nel formato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Salva tutti i risultati del riconoscimento in uno stream di memoria nel formato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Opzionale. Percorso completo al font dell'utente. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Riduci le dimensioni del file PDF abbassando la qualità delle immagini di sfondo. Per impostazione predefinita, la qualità originale dell'immagine viene conservata. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Salva tutti i risultati del riconoscimento in un file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Salva tutti i risultati del riconoscimento in un file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Salva tutti i risultati del riconoscimento in un file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Opzionale. Percorso completo al font dell'utente. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Riduci le dimensioni del file PDF abbassando la qualità delle immagini di sfondo. Per impostazione predefinita, la qualità originale dell'immagine viene conservata. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Salva tutti i risultati del riconoscimento in un documento PDF ricercabile in memoria, incorporando le immagini originali come sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream per salvare il risultato del riconoscimento nel formato selezionato. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Salva tutti i risultati del riconoscimento in un documento PDF ricercabile in memoria, incorporando le immagini originali come sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream per salvare il risultato del riconoscimento nel formato selezionato. |
| embeddedFontPath | java.lang.String | Opzionale. Percorso completo al font dell'utente. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Riduci le dimensioni del file PDF abbassando la qualità delle immagini di sfondo. Per impostazione predefinita, la qualità originale dell'immagine viene conservata. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Salva tutti i risultati del riconoscimento in un file PDF ricercabile, con le immagini originali impostate come sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Salva tutti i risultati del riconoscimento in un file PDF ricercabile, con le immagini originali impostate come sfondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato. |
| embeddedFontPath | java.lang.String | Opzionale. Percorso completo al font dell'utente. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Riduci le dimensioni del file PDF abbassando la qualità delle immagini di sfondo. Per impostazione predefinita, la qualità originale dell'immagine viene conservata. |

### size() {#size}
```
public int size()
```




**Returns:**
int
