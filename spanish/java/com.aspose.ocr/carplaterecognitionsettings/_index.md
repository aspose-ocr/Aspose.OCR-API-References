---
title: "CarPlateRecognitionSettings"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Configuración para el reconocimiento de matrículas de coche contiene elementos que permiten personalizar el proceso de reconocimiento."
type: docs
weight: 12
url: /es/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Configuración para el reconocimiento de matrículas de coche contiene elementos que permiten personalizar el proceso de reconocimiento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Constructor predeterminado: establecer autoSkew en true. |
## Métodos

| Método | Descripción |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | Conjunto de caracteres permitidos. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detecta imágenes con texto blanco sobre fondo oscuro/negro y elige automáticamente un algoritmo OCR especial para ellas. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Establece la lista negra para los símbolos de reconocimiento. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Constructor predeterminado: establecer autoSkew en true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Conjunto de caracteres permitidos. Determina el tipo de caracteres permitidos para el resultado del reconocimiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | contiene el valor del enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/). |

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

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | Establece el idioma usado para OCR. Multilingüe (ninguno) por defecto. |

