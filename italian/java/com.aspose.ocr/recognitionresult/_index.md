---
title: "RecognitionResult"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "I risultati del riconoscimento dell'immagine"
type: docs
weight: 26
url: /it/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

I risultati del riconoscimento dell'immagine. Contiene elementi con informazioni sul riconoscimento e metodi per l'esportazione dei risultati.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Inizializza una nuova istanza di |
## Campi

| Campo | Descrizione |
| --- | --- |
| [language](#language) | La lingua del testo riconosciuto nell'immagine. |
| [recognitionCharactersList](#recognitionCharactersList) | Un insieme di caratteri trovati dall'algoritmo di riconoscimento e ordinati in ordine decrescente di probabilità. |
| [recognitionLinesResult](#recognitionLinesResult) | Ottiene un elenco di risultati di riconoscimento con un elenco di righe (Rettangoli). |
| [recognitionRegionsResult](#recognitionRegionsResult) | Ottiene un elenco di risultati di riconoscimento con un elenco di regioni (Rettangoli). |
| [recognitionText](#recognitionText) | Risultato del riconoscimento di tutte le pagine o di un'area. |
| [warnings](#warnings) | Ottiene o imposta l'elenco dei messaggi di avviso che descrivono errori non critici verificatisi durante la generazione. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [GetJson()](#GetJson) | Crea stringa JSON con i risultati del riconoscimento. |
| [GetKeywords()](#GetKeywords) | Ottieni parole chiave dal passaporto (Modalità test. |
| [GetXml()](#GetXml) | Crea stringa JSON con i risultati del riconoscimento. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Corregge il testo (sostituisce le parole errate). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Corregge il testo (sostituisce le parole errate). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Trova le parole errate con le correzioni suggerite per un testo di input fornito. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Trova le parole errate con le correzioni suggerite per un testo di input fornito. |
| [save(String fullFileName)](#save-java.lang.String) | Salva il documento in testo semplice |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Salva il documento in testo semplice o in un altro formato di documento. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Salva il documento in testo semplice o in un altro formato di documento. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Salva il testo corretto con il dizionario inglese nel documento in formato testo semplice o Microsoft Word Text Document. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Salva il testo corretto nel documento in formato testo semplice o in altro formato. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Consente di utilizzare un dizionario personale per la correzione ortografica. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Inizializza una nuova istanza di

### language {#language}
```
public Language language
```


La lingua del testo riconosciuto nell'immagine. Questo valore viene determinato automaticamente se sono selezionati Language.AUTO, Language.MULTILANGUAGE o Language.UNIVERSAL.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


Un insieme di caratteri trovati dall'algoritmo di riconoscimento e ordinati in ordine decrescente di probabilità.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Ottiene un elenco di risultati di riconoscimento con un elenco di righe (Rettangoli).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Ottiene un elenco di risultati di riconoscimento con un elenco di regioni (Rettangoli).

### recognitionText {#recognitionText}
```
public String recognitionText
```


Risultato del riconoscimento di tutte le pagine o di un'area.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Ottiene o imposta l'elenco dei messaggi di avviso che descrivono errori non critici verificatisi durante la generazione.

### GetJson() {#GetJson}
```
public String GetJson()
```


Crea stringa JSON con i risultati del riconoscimento.

**Returns:**
java.lang.String - Risultati del riconoscimento come stringa JSON.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Ottieni le parole chiave dal passaporto (modalità test. Funziona solo per i passaporti USA e MADAGASCAR).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - Dizionario con la parola chiave come chiave e LinesResult come valore.
### GetXml() {#GetXml}
```
public String GetXml()
```


Crea stringa JSON con i risultati del riconoscimento.

**Returns:**
java.lang.String - Risultati del riconoscimento come stringa XML.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Corregge il testo (sostituisce le parole errate).

**Returns:**
java.lang.String - Stringa dei risultati del riconoscimento corretti. Dizionario inglese predefinito.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Corregge il testo (sostituisce le parole errate).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dizionario da utilizzare. |

**Returns:**
java.lang.String - Stringa dei risultati del riconoscimento corretti.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Trova le parole errate con le correzioni suggerite per un testo di input fornito. Dizionario inglese predefinito.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList di oggetti SpellCheckError che rappresentano parole errate con elenchi di correzioni suggerite per ciascuna parola errata, e con la distanza di modifica.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Trova le parole errate con le correzioni suggerite per un testo di input fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dizionario da utilizzare. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList di oggetti SpellCheckError che rappresentano parole errate con elenchi di correzioni suggerite per ciascuna parola errata, e con la distanza di modifica.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Salva il documento in testo semplice

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Salva il documento in testo semplice o in un altro formato di documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento. |
| format | [Format](../../com.aspose.ocr.models/format/) | Tipo enum di formato documento di Format. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Salva il documento in testo semplice o in un altro formato di documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento. |
| format | [Format](../../com.aspose.ocr.models/format/) | Tipo enum di formato documento di Format. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Riduci le dimensioni del file PDF abbassando la qualità delle immagini di sfondo. Per impostazione predefinita, la qualità originale dell'immagine viene conservata. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Salva il testo corretto con il dizionario inglese nel documento in formato testo semplice o Microsoft Word Text Document.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento. |
| format | [Format](../../com.aspose.ocr.models/format/) | Tipo enum di formato documento di Format. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Salva il testo corretto nel documento in formato testo semplice o in altro formato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento. |
| format | [Format](../../com.aspose.ocr.models/format/) | Tipo enum di formato documento di Format. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dizionario per il controllo ortografico. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Consente di utilizzare un dizionario personale per la correzione ortografica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Percorso completo del dizionario utente (dizionario di frequenza). Formato del file del dizionario: file di testo semplice in codifica UTF-8. La parola e la frequenza della parola sono separate da una virgola, la parola è prevista nella prima colonna e la frequenza nella seconda colonna. Ogni coppia parola-frequenza è su una riga separata. Una riga è definita come una sequenza di caratteri seguita da un ritorno a capo (\"\\n\"), un ritorno a capo (\"\\r\"), o un ritorno a capo immediatamente seguito da un ritorno a capo (\"\\r\\n\"). Ogni parola è prevista in minuscolo. |
