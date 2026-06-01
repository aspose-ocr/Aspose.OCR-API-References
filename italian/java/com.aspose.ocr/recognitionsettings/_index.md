---
title: "RecognitionSettings"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Impostazioni per il riconoscimento dell'immagine"
type: docs
weight: 27
url: /it/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Impostazioni per il riconoscimento dell'immagine. Contiene elementi che consentono di personalizzare il processo di riconoscimento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Costruttore predefinito: imposta recognitionAreas a null, linesFiltration a false, autoSkew a false, recognizeSingleLine a false. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | Il costruttore consente di impostare tutte le opzioni. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | Il costruttore consente di impostare recognizeSingleLine. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Insieme di caratteri consentiti. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Insieme di caratteri consentiti. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Rileva immagini con testo bianco su sfondo scuro/nero e scegli automaticamente un algoritmo OCR speciale per esse. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Determina il tipo di rete neurale utilizzata per il rilevamento delle aree. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Imposta la lista nera per i simboli di riconoscimento. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Specifica il livello di rilevamento della lingua per il riconoscimento del testo. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Consente di riconoscere il testo nelle tabelle (regioni circondate da linee). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | Imposta l'elenco delle aree di testo per l'elaborazione. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Imposta il riconoscimento dell'immagine a singola riga. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Ottiene o imposta il numero di thread per l'elaborazione. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Consente di utilizzare algoritmi aggiuntivi specificamente per il riconoscimento di caratteri di piccole dimensioni. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Costruttore predefinito: imposta recognitionAreas a null, linesFiltration a false, autoSkew a false, recognizeSingleLine a false.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


Il costruttore consente di impostare tutte le opzioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rettangoli per il riconoscimento. |
| recognizeSingleLine | boolean | Vero se l'immagine contiene una sola riga. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


Il costruttore consente di impostare recognizeSingleLine. Valori predefiniti in questo caso: detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recognizeSingleLine | boolean | Vero se l'immagine contiene una sola riga. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




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
| allowedCharacters | java.lang.String | contiene una stringa di caratteri. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Rileva immagini con testo bianco su sfondo scuro/nero e scegli automaticamente un algoritmo OCR speciale per esse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| automaticColorInversion | boolean | contiene un valore booleano - è impostato automaticColorInversion. Vero per impostazione predefinita. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Determina il tipo di rete neurale utilizzata per il rilevamento delle aree.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | contiene il valore enum @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/). |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Consente di riconoscere il testo nelle tabelle (regioni circondate da linee).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| linesFiltration | boolean | false - consente di aumentare le prestazioni e non rileva tabelle e rimuove le linee; altrimenti - true. Disabilitato (false) per impostazione predefinita. |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


Imposta l'elenco delle aree di testo per l'elaborazione. Consente di specificare manualmente le aree con testo per un riconoscimento più accurato. Se le aree personalizzate sono impostate [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)} non NONE o [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)} le proprietà saranno ignorate. Disabilita DetectAreas e AutoSkew.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rettangoli per il riconoscimento. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Imposta il riconoscimento di immagini a riga singola. Disabilitato (false) per impostazione predefinita. Disabilita tutti i passaggi di elaborazione associati alla divisione in righe. Imposta questo parametro su true se la tua immagine contiene una sola riga. Disabilita le impostazioni [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList), quindi tutte le impostazioni delle aree saranno ignorate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recognizeSingleLine | boolean | Vero per immagine a riga singola |

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
| upscaleSmallFont | boolean | contiene un valore booleano - è impostato upscaleSmallFont. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String