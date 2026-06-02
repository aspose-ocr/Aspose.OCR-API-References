---
title: "IDCardRecognitionSettings"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Configuración para el reconocimiento de tarjetas de identificación contiene elementos que permiten personalizar el proceso de reconocimiento."
type: docs
weight: 14
url: /es/java/com.aspose.ocr/idcardrecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class IDCardRecognitionSettings extends ReceiptRecognitionSettings
```

Configuración para el reconocimiento de tarjetas de identificación contiene elementos que permiten personalizar el proceso de reconocimiento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [IDCardRecognitionSettings()](#IDCardRecognitionSettings) | Constructor predeterminado: establecer autoSkew en true. |
## Métodos

| Método | Descripción |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Conjunto de caracteres permitidos. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Conjunto de caracteres permitidos. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detecta imágenes con texto blanco sobre fondo oscuro/negro y elige automáticamente un algoritmo OCR especial para ellas. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Establece la lista negra para los símbolos de reconocimiento. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Especifica el nivel de detección de idioma para el reconocimiento de texto. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Obtiene o establece el número de hilos para el procesamiento. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Permite usar algoritmos adicionales específicamente para el reconocimiento de fuentes pequeñas. |
### IDCardRecognitionSettings() {#IDCardRecognitionSettings}
```
public IDCardRecognitionSettings()
```


Constructor predeterminado: establecer autoSkew en true.



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
| allowedCharacters | java.lang.String | contiene una matriz de caracteres. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Detecta imágenes con texto blanco sobre fondo oscuro/negro y elige automáticamente un algoritmo OCR especial para ellas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| automaticColorInversion | boolean | contiene un valor booleano - se establece automaticColorInversion. |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | valor de enumeración para establecer el nivel (Paragraph, Word, Page). |

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
| upscaleSmallFont | boolean | contiene un valor booleano - se establece upscaleSmallFont. |

