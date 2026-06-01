---
title: "PassportRecognitionSettings"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Impostazioni per il riconoscimento del passaporto Contiene elementi che consentono di personalizzare il processo di riconoscimento"
type: docs
weight: 23
url: /it/java/com.aspose.ocr/passportrecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class PassportRecognitionSettings extends ReceiptRecognitionSettings
```

Impostazioni per il riconoscimento del passaporto Contiene elementi che consentono di personalizzare il processo di riconoscimento
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PassportRecognitionSettings()](#PassportRecognitionSettings) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Insieme di caratteri consentiti. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Insieme di caratteri consentiti. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Rileva immagini con testo bianco su sfondo scuro/nero e scegli automaticamente un algoritmo OCR speciale per esse. |
| [setCountry(Country country)](#setCountry-com.aspose.ocr.models.Country) | Imposta il modello per il riconoscimento del passaporto e per estrarre le parole chiave. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Imposta la lista nera per i simboli di riconoscimento. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Specifica il livello di rilevamento della lingua per il riconoscimento del testo. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Ottiene o imposta il numero di thread per l'elaborazione. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Consente di utilizzare algoritmi aggiuntivi specificamente per il riconoscimento di caratteri di piccole dimensioni. |
### PassportRecognitionSettings() {#PassportRecognitionSettings}
```
public PassportRecognitionSettings()
```





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Insieme di caratteri consentiti. Determina il tipo di caratteri consentiti per il risultato del riconoscimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | contiene il valore enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/). |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Insieme di caratteri consentiti. Determina l'array di caratteri consentiti per il risultato del riconoscimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| allowedCharacters | java.lang.String | contiene un array di caratteri. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Rileva immagini con testo bianco su sfondo scuro/nero e scegli automaticamente un algoritmo OCR speciale per esse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| automaticColorInversion | boolean | contiene valore booleano - è impostato automaticColorInversion. |

### setCountry(Country country) {#setCountry-com.aspose.ocr.models.Country}
```
public void setCountry(Country country)
```


Imposta il modello per il riconoscimento del passaporto e per estrarre le parole chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| country | [Country](../../com.aspose.ocr.models/country/) | paese del passaporto. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Imposta la lista nera per i simboli di riconoscimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| characters | java.lang.String | Caratteri esclusi dal riconoscimento. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Imposta la lingua usata per l'OCR. Multilingua (nessuna) per impostazione predefinita. |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Specifica il livello di rilevamento della lingua per il riconoscimento del testo. Funziona solo se la lingua selezionata è Language.MULTILANGUAGE, Language.AUTO o Language.UNIVERSAL. Questo processo richiede tempo e rallenta significativamente il riconoscimento complessivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | valore enum per impostare il livello (Paragraph, Word, Page). |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Ottiene o imposta il numero di thread per l'elaborazione. Per impostazione predefinita, 0 significa che l'immagine verrà elaborata con un numero di thread pari al numero dei tuoi processori. ThreadsCount = 1 significa che l'immagine verrà elaborata nel thread principale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadsCount | int | il numero di thread che verranno creati per il riconoscimento parallelo dei frammenti di immagine. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Consente di utilizzare algoritmi aggiuntivi specificamente per il riconoscimento di caratteri di piccole dimensioni. Utile per immagini con caratteri di piccole dimensioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| upscaleSmallFont | boolean | contiene valore booleano - è impostato upscaleSmallFont. |
