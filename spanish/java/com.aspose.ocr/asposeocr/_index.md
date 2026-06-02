---
title: "AsposeOCR"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Clase principal para reconocer texto de imágenes"
type: docs
weight: 10
url: /es/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Clase principal para reconocer texto de imágenes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Constructor público. |
## Campos

| Campo | Descripción |
| --- | --- |
| [DebugMode](#DebugMode) | Habilita el modo de depuración. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Directorio donde se guardarán los resultados de depuración. |
## Métodos

| Método | Descripción |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Calcula los ángulos de inclinación de una imagen. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | Comprueba si dos imágenes contienen el mismo texto. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Comprueba si dos imágenes contienen el mismo texto. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Comprueba si dos imágenes contienen el mismo texto. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Corrige el texto (reemplaza palabras mal escritas). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Corrige el texto (reemplaza palabras mal escritas). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | Encuentra automáticamente áreas problemáticas de una imagen que pueden afectar significativamente la precisión del OCR. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Analiza la imagen e identifica los diferentes tipos de áreas de contenido dentro de ella. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Analiza el texto de la imagen para determinar los idiomas en los que está escrito. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Detecta áreas de texto en imágenes. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Detecta regiones de tabla en imágenes. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Comprueba si la imagen contiene el fragmento de texto proporcionado con una búsqueda sin distinción de mayúsculas. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Comprueba si la imagen contiene el fragmento de texto proporcionado con una búsqueda sin distinción de mayúsculas. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Comprueba si la imagen contiene el fragmento de texto proporcionado. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Comprueba si el texto de la imagen coincide con la expresión regular proporcionada. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Comprueba si el texto de la imagen coincide con la expresión regular proporcionada. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | Compara los textos de las dos imágenes y devuelve un número que representa cuán similares son (0 a 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Compara los textos de las dos imágenes y devuelve un número que representa cuán similares son (0 a 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Compara los textos de las dos imágenes y devuelve un número que representa cuán similares son (0 a 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Reconoce imágenes con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Reconoce imágenes con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Reconoce matrículas de coche con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Detecta símbolos en imágenes. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Detecta símbolos en imágenes. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | Reconoce texto en una imagen de buena calidad. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Reconoce fórmulas matemáticas a partir de las imágenes de entrada proporcionadas. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Reconoce texto manuscrito en imágenes. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Reconoce tarjetas de identificación con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Reconoce facturas con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Reconoce pasaportes con la capacidad de especificar. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Reconoce recibos con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Detecta tablas y estructura, reconoce celdas de texto. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult con corrección ortográfica. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Constructor público.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Habilita el modo de depuración. Cuando está habilitado, el sistema guarda resultados intermedios del procesamiento de imágenes, como imágenes preprocesadas e imágenes con rectángulos dibujados alrededor de líneas de texto.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Directorio donde se guardarán los resultados de depuración. Si no se establece, se usará el directorio de trabajo actual por defecto.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Calcula los ángulos de inclinación de una imagen. Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | El contenedor con fuentes.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - Lista de ángulos de inclinación en grados [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


Comprueba si dos imágenes contienen el mismo texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath1 | java.lang.String | Ruta a la primera imagen. |
| fullPath2 | java.lang.String | Ruta a la segunda imagen. |

**Returns:**
boolean - Verdadero si las imágenes tienen el mismo texto (90% de similitud).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Comprueba si dos imágenes contienen el mismo texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath1 | java.lang.String | Ruta a la primera imagen. |
| fullPath2 | java.lang.String | Ruta a la segunda imagen. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Configuración de reconocimiento. |

**Returns:**
boolean - Verdadero si las imágenes tienen el mismo texto (90% de similitud).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Comprueba si dos imágenes contienen el mismo texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath1 | java.lang.String | Ruta a la primera imagen. |
| fullPath2 | java.lang.String | Ruta a la segunda imagen. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Configuración de reconocimiento. |
| ignoreCase | boolean | Verdadero - indica una búsqueda sin distinción de mayúsculas y minúsculas. |

**Returns:**
boolean - Verdadero si las imágenes tienen el mismo texto (90% de similitud).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Corrige el texto (reemplaza palabras mal escritas).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto para corrección. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Diccionario a usar [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Texto con palabras reemplazadas.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Corrige el texto (reemplaza palabras mal escritas).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto para corrección. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Diccionario a usar [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Ruta completa al diccionario de usuario (diccionario de frecuencias). Formato del archivo de diccionario: archivo de texto plano con codificación UTF-8. La palabra y su frecuencia están separadas por una coma; se espera que la palabra esté en la primera columna y la frecuencia en la segunda columna. Cada par palabra-frecuencia en una línea separada. Una línea se define como una secuencia de caracteres seguida de un salto de línea ("\\n"), un retorno de carro ("\\r"), o un retorno de carro seguido inmediatamente de un salto de línea ("\\r\\n"). Se espera que cada palabra esté en minúsculas. |

**Returns:**
java.lang.String - Texto con palabras reemplazadas.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


Encuentra automáticamente áreas problemáticas de una imagen que pueden afectar significativamente la precisión del OCR. Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | El contenedor con fuentes.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | Los tipos de defectos a reconocer [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - ArrayList de [DefectOutput](../../com.aspose.ocr/defectoutput/) con áreas de texto detectadas o líneas.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Analiza la imagen e identifica los diferentes tipos de áreas de contenido dentro de ella. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | El contenedor con fuentes.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Áreas de contenido detectadas. ArrayList de [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Analiza el texto de la imagen para determinar los idiomas en los que está escrito. Esto permite seleccionar el idioma de reconocimiento más adecuado y ayuda en tareas posteriores de procesamiento de texto, como corrección ortográfica o traducción. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | El contenedor con fuentes.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Devuelve una lista de los idiomas más probables, ordenados por probabilidad. ArrayList de [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Detecta áreas de texto en imágenes. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | El contenedor con fuentes.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Determina qué rectángulos devolver - línea o párrafos. |
| isDetectAreas | boolean | Habilita la detección automática de áreas de texto. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList de [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) con áreas de texto detectadas o líneas.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Detecta regiones de tabla en imágenes. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | El contenedor con fuentes.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList de [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) con áreas de tabla detectadas.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Comprueba si la imagen contiene el fragmento de texto proporcionado con una búsqueda sin distinción de mayúsculas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath | java.lang.String | Ruta a la imagen. |
| text | java.lang.String | Fragmento de texto para buscar en la imagen. |

**Returns:**
boolean - Verdadero si la imagen contiene el fragmento de texto. Falso - la imagen no contiene el fragmento de texto.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Comprueba si la imagen contiene el fragmento de texto proporcionado con una búsqueda sin distinción de mayúsculas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath | java.lang.String | Ruta a la imagen. |
| text | java.lang.String | Fragmento de texto para buscar en la imagen. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Configuración de reconocimiento. |

**Returns:**
boolean - Verdadero si la imagen contiene el fragmento de texto. Falso - la imagen no contiene el fragmento de texto.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Comprueba si la imagen contiene el fragmento de texto proporcionado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath | java.lang.String | Ruta a la imagen. |
| text | java.lang.String | Fragmento de texto para buscar en la imagen. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Configuración de reconocimiento. |
| ignoreCase | boolean | Verdadero - indica una búsqueda sin distinción de mayúsculas y minúsculas. |

**Returns:**
boolean - Verdadero si la imagen contiene el fragmento de texto. Falso - la imagen no contiene el fragmento de texto.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Comprueba si el texto de la imagen coincide con la expresión regular proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath | java.lang.String | Ruta a la imagen. |
| regex | java.util.regex.Pattern | Objeto java.util.regex.Pattern con el patrón y las opciones proporcionados. |

**Returns:**
boolean - Verdadero si el texto de la imagen coincide con la expresión regular proporcionada.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Comprueba si el texto de la imagen coincide con la expresión regular proporcionada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath | java.lang.String | Ruta a la imagen. |
| regex | java.util.regex.Pattern | Objeto java.util.regex.Pattern con el patrón y las opciones proporcionados. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Configuración de reconocimiento. |

**Returns:**
boolean - Verdadero si el texto de la imagen coincide con la expresión regular proporcionada.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


Compara los textos de las dos imágenes y devuelve un número que representa cuán similares son (0 a 1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath1 | java.lang.String | Ruta a la primera imagen. |
| fullPath2 | java.lang.String | Ruta a la segunda imagen. |

**Returns:**
float - 0 significa que los textos son completamente diferentes; 1 significa que los textos son idénticos.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Compara los textos de las dos imágenes y devuelve un número que representa cuán similares son (0 a 1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath1 | java.lang.String | Ruta a la primera imagen. |
| fullPath2 | java.lang.String | Ruta a la segunda imagen. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Configuración de reconocimiento. |

**Returns:**
float - 0 significa que los textos son completamente diferentes; 1 significa que los textos son idénticos.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Compara los textos de las dos imágenes y devuelve un número que representa cuán similares son (0 a 1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullPath1 | java.lang.String | Ruta a la primera imagen. |
| fullPath2 | java.lang.String | Ruta a la segunda imagen. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Configuración de reconocimiento. |
| ignoreCase | boolean | Verdadero - indica una búsqueda sin distinción de mayúsculas y minúsculas. |

**Returns:**
float - 0 significa que los textos son completamente diferentes; 1 significa que los textos son idénticos.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Reconoce imágenes con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instancia. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Reconoce imágenes con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instancia. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Reconoce matrículas de coche con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instancia. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Detecta símbolos en imágenes. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | El contenedor con fuentes.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList de [Character](../../com.aspose.ocr.models/character/) con datos de símbolos detectados para cada imagen.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Detecta símbolos en imágenes. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | El contenedor con fuentes.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Determina el tipo de red neuronal utilizada para la detección de áreas. |
| language | [Language](../../com.aspose.ocr.models/language/) | Idioma utilizado para OCR. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList de [Character](../../com.aspose.ocr.models/character/) con datos de símbolos detectados.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


Reconoce texto en imágenes de buena calidad. No utiliza corrección automática de inclinación de la imagen ni detección de áreas de texto. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Instancia de [OcrInput](../../com.aspose.ocr/ocrinput/). |

**Returns:**
java.util.ArrayList<java.lang.String> - ArrayList con texto reconocido.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Reconoce fórmulas matemáticas a partir de las imágenes de entrada proporcionadas. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instancia. |
| detectAreas | boolean | Si se establece en true, detecta y aísla automáticamente las regiones de fórmulas antes de realizar el reconocimiento. Si se establece en false, procesa la imagen completa como una fórmula. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Reconoce texto manuscrito en imágenes. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). El contenedor con fuentes.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Reconoce tarjetas de identificación con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instancia. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Reconoce facturas con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, arreglo, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instancia. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Reconoce pasaportes con la capacidad de especificar. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instancia. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Reconoce recibos con la capacidad de especificar Soporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instancia. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Detecta tablas y su estructura, reconoce celdas de texto. Compatible con GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, carpeta, matriz, archivo zip, URL, base64.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instancia. |
| language | [Language](../../com.aspose.ocr.models/language/) | Determina el alfabeto utilizado durante el reconocimiento. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - Objetos de lista OCRTablePage con textos reconocidos en tablas. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista de [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objetos. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista de [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objetos. |
| embeddedFontPath | java.lang.String | Opcionalmente. Ruta completa a la fuente del usuario. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista de [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objetos. |
| embeddedFontPath | java.lang.String | Opcionalmente. Ruta completa a la fuente del usuario. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduce el tamaño del archivo PDF disminuyendo la calidad de las imágenes de fondo. Por defecto, se conserva la calidad original de la imagen. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista de [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objetos. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult con corrección ortográfica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista de [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objetos. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) valor de enumeración. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista de [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objetos. |
| embeddedFontPath | java.lang.String | Opcionalmente. Ruta completa a la fuente del usuario. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento en el formato seleccionado. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato de documento (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista de [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objetos. |
| embeddedFontPath | java.lang.String | Opcionalmente. Ruta completa a la fuente del usuario. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduce el tamaño del archivo PDF disminuyendo la calidad de las imágenes de fondo. Por defecto, se conserva la calidad original de la imagen. |

### close() {#close}
```
public void close()
```