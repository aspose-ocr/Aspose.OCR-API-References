---
title: "CarPlateRecognitionSettings"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Impostazioni per il riconoscimento delle targhe automobilistiche Contiene elementi che consentono di personalizzare il processo di riconoscimento"
type: docs
weight: 12
url: /it/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Impostazioni per il riconoscimento delle targhe automobilistiche Contiene elementi che consentono di personalizzare il processo di riconoscimento
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Costruttore predefinito: imposta autoSkew true. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | Insieme di caratteri consentiti. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Rileva immagini con testo bianco su sfondo scuro/nero e scegli automaticamente un algoritmo OCR speciale per esse. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Imposta la lista nera per i simboli di riconoscimento. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Costruttore predefinito: imposta autoSkew true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Insieme di caratteri consentiti. Determina il tipo di caratteri consentiti per il risultato del riconoscimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | contiene il valore enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/). |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Rileva immagini con testo bianco su sfondo scuro/nero e scegli automaticamente un algoritmo OCR speciale per esse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| automaticColorInversion | boolean | contiene valore booleano - è impostato automaticColorInversion. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Imposta la lista nera per i simboli di riconoscimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| characters | java.lang.String | Caratteri esclusi dal riconoscimento. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | Imposta la lingua usata per l'OCR. Multilingua (nessuna) per impostazione predefinita. |

