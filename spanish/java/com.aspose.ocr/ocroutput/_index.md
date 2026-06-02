---
title: "OcrOutput"
second_title: "Referencia de API de Aspose.OCR para Java"
description: 
type: docs
weight: 21
url: /es/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OcrOutput()](#OcrOutput) | Inicializa una nueva instancia de la clase OcrOutput con una colección vacía. |
## Métodos

| Método | Descripción |
| --- | --- |

| [getTableData()](#getTableData) | Devuelve datos de tabla estructurados extraídos de todas las páginas reconocidas. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Guarde todos los resultados del reconocimiento en un flujo de memoria en el formato especificado. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Guarde todos los resultados del reconocimiento en un flujo de memoria en el formato especificado. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Guarde todos los resultados del reconocimiento en un flujo de memoria en el formato especificado. |
| [save(String fullFileName)](#save-java.lang.String) | Guardar todo el resultado del reconocimiento en un archivo. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Guardar todo el resultado del reconocimiento en un archivo. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Guardar todo el resultado del reconocimiento en un archivo. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Guardar todos los resultados del reconocimiento en un documento PDF buscable en memoria, incrustando las imágenes originales como fondo. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Guardar todos los resultados del reconocimiento en un documento PDF buscable en memoria, incrustando las imágenes originales como fondo. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Guardar todos los resultados del reconocimiento en un archivo PDF buscable, con las imágenes originales establecidas como fondo. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Guardar todos los resultados del reconocimiento en un archivo PDF buscable, con las imágenes originales establecidas como fondo. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Devuelve datos de tabla estructurados extraídos de todas las páginas reconocidas.

Cada página contiene filas, y cada fila contiene celdas con texto reconocido e información de posición opcional.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Guarde todos los resultados del reconocimiento en un flujo de memoria en el formato especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream para guardar el resultado del reconocimiento en el formato seleccionado. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Guarde todos los resultados del reconocimiento en un flujo de memoria en el formato especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Guarde todos los resultados del reconocimiento en un flujo de memoria en el formato especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Opcional. Ruta completa a la fuente del usuario. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduce el tamaño del archivo PDF disminuyendo la calidad de las imágenes de fondo. Por defecto, se conserva la calidad original de la imagen. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Guardar todo el resultado del reconocimiento en un archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Guardar todo el resultado del reconocimiento en un archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Guardar todo el resultado del reconocimiento en un archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Opcional. Ruta completa a la fuente del usuario. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduce el tamaño del archivo PDF disminuyendo la calidad de las imágenes de fondo. Por defecto, se conserva la calidad original de la imagen. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Guardar todos los resultados del reconocimiento en un documento PDF buscable en memoria, incrustando las imágenes originales como fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream para guardar el resultado del reconocimiento en el formato seleccionado. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Guardar todos los resultados del reconocimiento en un documento PDF buscable en memoria, incrustando las imágenes originales como fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream para guardar el resultado del reconocimiento en el formato seleccionado. |
| embeddedFontPath | java.lang.String | Opcional. Ruta completa a la fuente del usuario. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduce el tamaño del archivo PDF disminuyendo la calidad de las imágenes de fondo. Por defecto, se conserva la calidad original de la imagen. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Guardar todos los resultados del reconocimiento en un archivo PDF buscable, con las imágenes originales establecidas como fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Guardar todos los resultados del reconocimiento en un archivo PDF buscable, con las imágenes originales establecidas como fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |
| embeddedFontPath | java.lang.String | Opcional. Ruta completa a la fuente del usuario. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduce el tamaño del archivo PDF disminuyendo la calidad de las imágenes de fondo. Por defecto, se conserva la calidad original de la imagen. |

### size() {#size}
```
public int size()
```




**Returns:**
int
