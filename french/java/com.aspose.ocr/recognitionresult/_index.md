---
title: "RecognitionResult"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Les résultats de la reconnaissance d'image"
type: docs
weight: 26
url: /fr/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

Les résultats de la reconnaissance d'image. Contient des éléments avec des informations de reconnaissance et des méthodes pour l'exportation des résultats.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Initialise une nouvelle instance de |
## Champs

| Champ | Description |
| --- | --- |
| [language](#language) | La langue du texte reconnu dans l'image. |
| [recognitionCharactersList](#recognitionCharactersList) | Un ensemble de caractères trouvés par l'algorithme de reconnaissance et classés par ordre décroissant de probabilité. |
| [recognitionLinesResult](#recognitionLinesResult) | Obtient une liste de résultats de reconnaissance avec une liste de lignes (Rectangles). |
| [recognitionRegionsResult](#recognitionRegionsResult) | Obtient une liste de résultats de reconnaissance avec une liste de régions (Rectangles). |
| [recognitionText](#recognitionText) | Résultat de reconnaissance de toutes les pages ou d'une zone. |
| [warnings](#warnings) | Obtient ou définit la liste des messages d'avertissement décrivant les défauts non critiques survenus lors de la génération. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [GetJson()](#GetJson) | Forme une chaîne JSON avec les résultats de reconnaissance. |
| [GetKeywords()](#GetKeywords) | Obtenir les mots-clés du passeport (mode test. |
| [GetXml()](#GetXml) | Forme une chaîne JSON avec les résultats de reconnaissance. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Corrige le texte (remplace les mots mal orthographiés). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Corrige le texte (remplace les mots mal orthographiés). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Trouver les mots mal orthographiés avec les orthographes suggérées pour un texte d'entrée donné. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Trouver les mots mal orthographiés avec les orthographes suggérées pour un texte d'entrée donné. |
| [save(String fullFileName)](#save-java.lang.String) | Enregistre le document au format texte brut |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Enregistre le document au format texte brut ou dans un autre format de document. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Enregistre le document au format texte brut ou dans un autre format de document. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Enregistre le texte corrigé avec le dictionnaire anglais dans le document au format texte brut ou au format Document texte Microsoft Word. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Enregistre le texte corrigé dans le document au format texte brut ou dans un autre format. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Permet d'utiliser son propre dictionnaire pour la correction orthographique. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Initialise une nouvelle instance de

### language {#language}
```
public Language language
```


La langue du texte reconnu dans l'image. Cette valeur est déterminée automatiquement si  Language.AUTO ,  Language.MULTILANGUAGE , ou  Language.UNIVERSAL  est sélectionnée.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


Un ensemble de caractères trouvés par l'algorithme de reconnaissance et classés par ordre décroissant de probabilité.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Obtient une liste de résultats de reconnaissance avec une liste de lignes (Rectangles).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Obtient une liste de résultats de reconnaissance avec une liste de régions (Rectangles).

### recognitionText {#recognitionText}
```
public String recognitionText
```


Résultat de reconnaissance de toutes les pages ou d'une zone.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Obtient ou définit la liste des messages d'avertissement décrivant les défauts non critiques survenus lors de la génération.

### GetJson() {#GetJson}
```
public String GetJson()
```


Forme une chaîne JSON avec les résultats de reconnaissance.

**Returns:**
java.lang.String - Résultats de reconnaissance sous forme de chaîne JSON.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Obtenir les mots-clés du passeport (mode test. Fonctionne uniquement pour les passeports des États‑Unis et de MADAGASCAR).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - Dictionnaire avec le mot-clé comme clé et LinesResult comme valeur.
### GetXml() {#GetXml}
```
public String GetXml()
```


Forme une chaîne JSON avec les résultats de reconnaissance.

**Returns:**
java.lang.String - Résultats de reconnaissance sous forme de chaîne XML.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Corrige le texte (remplace les mots mal orthographiés).

**Returns:**
java.lang.String - Chaîne de résultats de reconnaissance corrigés. Dictionnaire anglais par défaut.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Corrige le texte (remplace les mots mal orthographiés).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dictionnaire à utiliser. |

**Returns:**
java.lang.String - Chaîne de résultats de reconnaissance corrigés.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Trouver les mots mal orthographiés avec les orthographes suggérées pour un texte d'entrée donné. Dictionnaire anglais par défaut.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList d'objets SpellCheckError représentant les mots mal orthographiés avec des listes d'orthographes correctes suggérées pour chaque mot mal orthographié, ainsi que la distance d'édition.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Trouver les mots mal orthographiés avec les orthographes suggérées pour un texte d'entrée donné.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dictionnaire à utiliser. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList d'objets SpellCheckError représentant les mots mal orthographiés avec des listes d'orthographes correctes suggérées pour chaque mot mal orthographié, ainsi que la distance d'édition.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Enregistre le document au format texte brut

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Enregistre le document au format texte brut ou dans un autre format de document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance. |
| format | [Format](../../com.aspose.ocr.models/format/) | Énumération du type de format de document Format. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Enregistre le document au format texte brut ou dans un autre format de document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance. |
| format | [Format](../../com.aspose.ocr.models/format/) | Énumération du type de format de document Format. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Réduisez la taille du fichier PDF en abaissant la qualité des images d'arrière-plan. Par défaut, la qualité originale de l'image est conservée. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Enregistre le texte corrigé avec le dictionnaire anglais dans le document au format texte brut ou au format Document texte Microsoft Word.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance. |
| format | [Format](../../com.aspose.ocr.models/format/) | Énumération du type de format de document Format. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Enregistre le texte corrigé dans le document au format texte brut ou dans un autre format.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance. |
| format | [Format](../../com.aspose.ocr.models/format/) | Énumération du type de format de document Format. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dictionnaire pour la vérification orthographique. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Permet d'utiliser son propre dictionnaire pour la correction orthographique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Chemin complet vers le dictionnaire utilisateur (dictionnaire de fréquence). Format du fichier dictionnaire : fichier texte brut en encodage UTF-8. Le mot et sa fréquence sont séparés par une virgule, le mot étant attendu dans la première colonne et la fréquence dans la deuxième colonne. Chaque paire mot-fréquence se trouve sur une ligne distincte. Une ligne est définie comme une séquence de caractères suivie d'un saut de ligne ("\\n"), d'un retour chariot ("\\r"), ou d'un retour chariot immédiatement suivi d'un saut de ligne ("\\r\\n"). Chaque mot doit être en minuscules. |
