---
title: "RecognitionResult"
second_title: "Aspose.OCR for Java API-referentie"
description: "De resultaten van de beeldherkenning"
type: docs
weight: 26
url: /nl/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

De resultaten van de beeldherkenning. Bevat elementen met herkenningsinformatie en methoden voor het exporteren van resultaten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Initialiseert een nieuw exemplaar van de |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [language](#language) | De taal van de herkende tekst in de afbeelding. |
| [recognitionCharactersList](#recognitionCharactersList) | Een set tekens gevonden door het herkenningsalgoritme en gerangschikt in aflopende volgorde van waarschijnlijkheid. |
| [recognitionLinesResult](#recognitionLinesResult) | Haalt een lijst met herkenningsresultaten op met een lijst van rijen (Rechthoeken). |
| [recognitionRegionsResult](#recognitionRegionsResult) | Haalt een lijst met herkenningsresultaten op met een lijst van gebieden (Rechthoeken). |
| [recognitionText](#recognitionText) | Herkenningsresultaat van alle pagina's of één gebied. |
| [warnings](#warnings) | Haalt op of stelt een lijst in van waarschuwingsberichten die niet-kritieke fouten beschrijven die tijdens de generatie zijn opgetreden. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [GetJson()](#GetJson) | Formuleer JSON-string met herkenningsresultaten. |
| [GetKeywords()](#GetKeywords) | Haal trefwoorden op uit paspoort (Testmodus. |
| [GetXml()](#GetXml) | Formuleer JSON-string met herkenningsresultaten. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Corrigeert tekst (vervangt verkeerd gespelde woorden). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Corrigeert tekst (vervangt verkeerd gespelde woorden). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Zoek de verkeerd gespelde woorden met voorgestelde spellingen voor een gegeven invoertekst. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Zoek de verkeerd gespelde woorden met voorgestelde spellingen voor een gegeven invoertekst. |
| [save(String fullFileName)](#save-java.lang.String) | Slaat het document op in platte tekst |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Slaat het document op in platte tekst of een ander documentformaat. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Slaat het document op in platte tekst of een ander documentformaat. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Slaat de met het Engelse woordenboek gecorrigeerde tekst op in het document in platte tekst of Microsoft Word-tekstdocumentformaat. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Slaat de gecorrigeerde tekst op in het document in platte tekst of een ander formaat. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Staat toe een eigen woordenboek te gebruiken voor spellingscorrectie. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Initialiseert een nieuw exemplaar van de

### language {#language}
```
public Language language
```


De taal van de herkende tekst in de afbeelding. Deze waarde wordt automatisch bepaald als  Language.AUTO ,  Language.MULTILANGUAGE , of  Language.UNIVERSAL  is geselecteerd.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


Een set tekens gevonden door het herkenningsalgoritme en gerangschikt in aflopende volgorde van waarschijnlijkheid.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Haalt een lijst met herkenningsresultaten op met een lijst van rijen (Rechthoeken).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Haalt een lijst met herkenningsresultaten op met een lijst van gebieden (Rechthoeken).

### recognitionText {#recognitionText}
```
public String recognitionText
```


Herkenningsresultaat van alle pagina's of één gebied.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Haalt op of stelt een lijst in van waarschuwingsberichten die niet-kritieke fouten beschrijven die tijdens de generatie zijn opgetreden.

### GetJson() {#GetJson}
```
public String GetJson()
```


Formuleer JSON-string met herkenningsresultaten.

**Returns:**
java.lang.String - Herkenningsresultaten als JSON‑string.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Haal trefwoorden op uit paspoort (testmodus. Werkt alleen voor USA- en MADAGASCAR-paspoorten).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - Woordenboek met trefwoord als sleutel en LinesResult als waarde.
### GetXml() {#GetXml}
```
public String GetXml()
```


Formuleer JSON-string met herkenningsresultaten.

**Returns:**
java.lang.String - Herkenningsresultaten als XML‑string.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Corrigeert tekst (vervangt verkeerd gespelde woorden).

**Returns:**
java.lang.String - Gecorrigeerde herkenningsresultaten‑string. Standaard Engelse woordenboek.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Corrigeert tekst (vervangt verkeerd gespelde woorden).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Te gebruiken woordenboek. |

**Returns:**
java.lang.String - Gecorrigeerde herkenningsresultaten‑string.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Zoek de verkeerd gespelde woorden met voorgestelde spellingen voor een gegeven invoertekst. Standaard Engelse woordenboek.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList van SpellCheckError‑objecten die verkeerd gespelde woorden weergeven met lijsten van voorgestelde correcte spellingen voor elk verkeerd gespeld woord, en met de bewerkingsafstand.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Zoek de verkeerd gespelde woorden met voorgestelde spellingen voor een gegeven invoertekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Te gebruiken woordenboek. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList van SpellCheckError‑objecten die verkeerd gespelde woorden weergeven met lijsten van voorgestelde correcte spellingen voor elk verkeerd gespeld woord, en met de bewerkingsafstand.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Slaat het document op in platte tekst

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met pad voor het opslaan van het herkenningsresultaat |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Slaat het document op in platte tekst of een ander documentformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met pad voor het opslaan van het herkenningsresultaat. |
| format | [Format](../../com.aspose.ocr.models/format/) | Documentformaat enum‑type van Format. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Slaat het document op in platte tekst of een ander documentformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met pad voor het opslaan van het herkenningsresultaat. |
| format | [Format](../../com.aspose.ocr.models/format/) | Documentformaat enum‑type van Format. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Verminder de PDF-bestandsgrootte door de kwaliteit van achtergrondafbeeldingen te verlagen. Standaard wordt de oorspronkelijke beeldkwaliteit behouden. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Slaat de met het Engelse woordenboek gecorrigeerde tekst op in het document in platte tekst of Microsoft Word-tekstdocumentformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met pad voor het opslaan van het herkenningsresultaat. |
| format | [Format](../../com.aspose.ocr.models/format/) | Documentformaat enum‑type van Format. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Slaat de gecorrigeerde tekst op in het document in platte tekst of een ander formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met pad voor het opslaan van het herkenningsresultaat. |
| format | [Format](../../com.aspose.ocr.models/format/) | Documentformaat enum‑type van Format. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Woordenboek voor spellingscontrole. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Staat toe een eigen woordenboek te gebruiken voor spellingscorrectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Volledig pad naar het gebruikerswoordenboek (frequentiewoordenboek). Formaat van het woordenboekbestand: platte tekstbestand in UTF-8-codering. Woord en woordfrequentie worden gescheiden door een komma; het woord wordt verwacht in de eerste kolom en de frequentie in de tweede kolom. Elk woord-frequentie-paar staat op een aparte regel. Een regel wordt gedefinieerd als een reeks tekens gevolgd door een regeleinde ("\\n"), een carriage return ("\\r"), of een carriage return direct gevolgd door een regeleinde ("\\r\\n"). Elk woord wordt verwacht in kleine letters. |
