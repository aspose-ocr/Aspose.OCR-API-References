---
title: "RecognitionResult"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Los resultados del reconocimiento de imágenes"
type: docs
weight: 26
url: /es/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

Los resultados del reconocimiento de imágenes. Contiene elementos con información de reconocimiento y métodos para la exportación de resultados.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Inicializa una nueva instancia de la |
## Campos

| Campo | Descripción |
| --- | --- |
| [language](#language) | El idioma del texto reconocido en la imagen. |
| [recognitionCharactersList](#recognitionCharactersList) | Un conjunto de caracteres encontrados por el algoritmo de reconocimiento y ordenados en orden descendente de probabilidad. |
| [recognitionLinesResult](#recognitionLinesResult) | Obtiene una lista de resultados de reconocimiento con una lista de filas (Rectángulos). |
| [recognitionRegionsResult](#recognitionRegionsResult) | Obtiene una lista de resultados de reconocimiento con una lista de regiones (Rectángulos). |
| [recognitionText](#recognitionText) | Resultado del reconocimiento de toda la página o de una zona. |
| [warnings](#warnings) | Obtiene o establece la lista de mensajes de advertencia que describen fallos no críticos ocurridos durante la generación. |
## Métodos

| Método | Descripción |
| --- | --- |
| [GetJson()](#GetJson) | Forma una cadena JSON con los resultados del reconocimiento. |
| [GetKeywords()](#GetKeywords) | Obtén palabras clave del pasaporte (Modo de prueba. |
| [GetXml()](#GetXml) | Forma una cadena JSON con los resultados del reconocimiento. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Corrige el texto (reemplaza palabras mal escritas). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Corrige el texto (reemplaza palabras mal escritas). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Encuentra las palabras mal escritas con ortografías sugeridas para un texto de entrada dado. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Encuentra las palabras mal escritas con ortografías sugeridas para un texto de entrada dado. |
| [save(String fullFileName)](#save-java.lang.String) | Guarda el documento en texto plano |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Guarda el documento en texto plano o en otro formato de documento. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Guarda el documento en texto plano o en otro formato de documento. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Guarda el texto corregido con el diccionario inglés en el documento en texto plano o en formato de documento de texto de Microsoft Word. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Guarda el texto corregido en el documento en texto plano o en otro formato. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Permite usar un diccionario propio para la corrección ortográfica. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Inicializa una nueva instancia de la

### language {#language}
```
public Language language
```


El idioma del texto reconocido en la imagen. Este valor se determina automáticamente si se selecciona Language.AUTO, Language.MULTILANGUAGE o Language.UNIVERSAL.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


Un conjunto de caracteres encontrados por el algoritmo de reconocimiento y ordenados en orden descendente de probabilidad.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Obtiene una lista de resultados de reconocimiento con una lista de filas (Rectángulos).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Obtiene una lista de resultados de reconocimiento con una lista de regiones (Rectángulos).

### recognitionText {#recognitionText}
```
public String recognitionText
```


Resultado del reconocimiento de toda la página o de una zona.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Obtiene o establece la lista de mensajes de advertencia que describen fallos no críticos ocurridos durante la generación.

### GetJson() {#GetJson}
```
public String GetJson()
```


Forma una cadena JSON con los resultados del reconocimiento.

**Returns:**
java.lang.String - Resultados del reconocimiento como cadena JSON.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Obtén palabras clave del pasaporte (modo de prueba. Funciona solo para pasaportes de EE. UU. y MADAGASCAR).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - Diccionario con la palabra clave como clave y LinesResult como valor.
### GetXml() {#GetXml}
```
public String GetXml()
```


Forma una cadena JSON con los resultados del reconocimiento.

**Returns:**
java.lang.String - Resultados del reconocimiento como cadena XML.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Corrige el texto (reemplaza palabras mal escritas).

**Returns:**
java.lang.String - Cadena de resultados de reconocimiento corregidos. Diccionario inglés predeterminado.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Corrige el texto (reemplaza palabras mal escritas).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Diccionario a usar. |

**Returns:**
java.lang.String - Cadena de resultados de reconocimiento corregidos.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Encuentra las palabras mal escritas con ortografías sugeridas para un texto de entrada dado. Diccionario inglés predeterminado.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList de objetos SpellCheckError que representan palabras mal escritas con listas de ortografías correctas sugeridas para cada palabra mal escrita, y con la distancia de edición.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Encuentra las palabras mal escritas con ortografías sugeridas para un texto de entrada dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Diccionario a usar. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList de objetos SpellCheckError que representan palabras mal escritas con listas de ortografías correctas sugeridas para cada palabra mal escrita, y con la distancia de edición.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Guarda el documento en texto plano

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Guarda el documento en texto plano o en otro formato de documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento. |
| format | [Format](../../com.aspose.ocr.models/format/) | Tipo de enumeración de formato de documento. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Guarda el documento en texto plano o en otro formato de documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento. |
| format | [Format](../../com.aspose.ocr.models/format/) | Tipo de enumeración de formato de documento. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduce el tamaño del archivo PDF disminuyendo la calidad de las imágenes de fondo. Por defecto, se conserva la calidad original de la imagen. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Guarda el texto corregido con el diccionario inglés en el documento en texto plano o en formato de documento de texto de Microsoft Word.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento. |
| format | [Format](../../com.aspose.ocr.models/format/) | Tipo de enumeración de formato de documento. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Guarda el texto corregido en el documento en texto plano o en otro formato.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fullFileName | java.lang.String | Nombre de archivo con una ruta para guardar el resultado del reconocimiento. |
| format | [Format](../../com.aspose.ocr.models/format/) | Tipo de enumeración de formato de documento. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Diccionario para la corrección ortográfica. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Permite usar un diccionario propio para la corrección ortográfica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Ruta completa al diccionario de usuario (diccionario de frecuencias). Formato del archivo de diccionario: archivo de texto plano con codificación UTF-8. La palabra y su frecuencia están separadas por una coma; se espera que la palabra esté en la primera columna y la frecuencia en la segunda columna. Cada par palabra-frecuencia en una línea separada. Una línea se define como una secuencia de caracteres seguida de un salto de línea ("\\n"), un retorno de carro ("\\r"), o un retorno de carro seguido inmediatamente de un salto de línea ("\\r\\n"). Se espera que cada palabra esté en minúsculas. |
