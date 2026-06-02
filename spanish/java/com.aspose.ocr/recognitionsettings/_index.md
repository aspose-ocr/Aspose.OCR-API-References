---
title: "RecognitionSettings"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Configuración para el reconocimiento de imágenes"
type: docs
weight: 27
url: /es/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Configuración para el reconocimiento de imágenes. Contiene elementos que permiten personalizar el proceso de reconocimiento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Constructor predeterminado: establecer recognitionAreas nulo, linesFiltration falso, autoSkew falso, recognizeSingleLine falso. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | El constructor permite establecer todas las opciones. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | El constructor permite establecer recognizeSingleLine. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Conjunto de caracteres permitidos. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Conjunto de caracteres permitidos. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detecta imágenes con texto blanco sobre fondo oscuro/negro y elige automáticamente un algoritmo OCR especial para ellas. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Determina el tipo de red neuronal utilizada para la detección de áreas. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Establece la lista negra para los símbolos de reconocimiento. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Especifica el nivel de detección de idioma para el reconocimiento de texto. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Permite reconocer texto en las tablas (regiones rodeadas de líneas). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | Establece la lista de áreas de texto para el procesamiento. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Establece el reconocimiento de imagen de una sola línea. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Obtiene o establece el número de hilos para el procesamiento. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Permite usar algoritmos adicionales específicamente para el reconocimiento de fuentes pequeñas. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Constructor predeterminado: establecer recognitionAreas nulo, linesFiltration falso, autoSkew falso, recognizeSingleLine falso.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


El constructor permite establecer todas las opciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rectángulos para reconocimiento. |
| recognizeSingleLine | boolean | Verdadero si la imagen contiene solo una línea. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


El constructor permite establecer recognizeSingleLine. Valores predeterminados en este caso: detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recognizeSingleLine | boolean | Verdadero si la imagen contiene solo una línea. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Conjunto de caracteres permitidos. Determina el tipo de caracteres permitidos para el resultado del reconocimiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | contiene el valor de enumeración @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/). |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Conjunto de caracteres permitidos. Determina la matriz de caracteres permitidos para el resultado del reconocimiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| allowedCharacters | java.lang.String | contiene cadena de caracteres. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Detecta imágenes con texto blanco sobre fondo oscuro/negro y elige automáticamente un algoritmo OCR especial para ellas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| automaticColorInversion | boolean | contiene valor booleano - se establece automaticColorInversion. Verdadero por defecto. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Determina el tipo de red neuronal utilizada para la detección de áreas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | contiene valor de enumeración @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/). |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Establece la lista negra para los símbolos de reconocimiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| characters | java.lang.String | Caracteres excluidos del reconocimiento. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Establece el idioma usado para OCR. Multilingüe (ninguno) por defecto. |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Especifica el nivel de detección de idioma para el reconocimiento de texto. Funciona solo si el idioma seleccionado es Language.MULTILANGUAGE, Language.AUTO o Language.UNIVERSAL. Este proceso consume tiempo y ralentiza significativamente el reconocimiento general.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Permite reconocer texto en las tablas (regiones rodeadas de líneas).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| linesFiltration | boolean | false - permite aumentar el rendimiento y no detectar tablas y eliminar líneas; de lo contrario - true. Deshabilitado (false) por defecto. |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


Establece la lista de áreas de texto para el procesamiento. Permite especificar manualmente las áreas con texto para un reconocimiento más preciso. Si se establecen áreas personalizadas [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)} no NONE o [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/#AutoSkew) (boolean)} las propiedades serán ignoradas. Deshabilita DetectAreas y AutoSkew.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rectángulos para reconocimiento. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Establece el reconocimiento de imagen de una sola línea. Deshabilitado (false) por defecto. Desactiva todos los pasos de procesamiento asociados con la división en líneas. Establezca este parámetro a true si su imagen contiene solo una línea. Deshabilita la configuración [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/#setRecognitionAreas-ArrayList), por lo que todas las configuraciones de áreas serán ignoradas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recognizeSingleLine | boolean | Verdadero para imagen de una sola línea |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Obtiene o establece el número de hilos para el procesamiento. Por defecto, 0 significa que la imagen se procesará con un número de hilos igual al número de procesadores. ThreadsCount = 1 significa que la imagen se procesará en el hilo principal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threadsCount | int | el número de hilos que se crearán para el reconocimiento paralelo de fragmentos de imagen. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Permite usar algoritmos adicionales específicamente para el reconocimiento de fuentes pequeñas. Útil para imágenes con caracteres de tamaño pequeño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| upscaleSmallFont | boolean | contiene valor booleano - se establece upscaleSmallFont. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String