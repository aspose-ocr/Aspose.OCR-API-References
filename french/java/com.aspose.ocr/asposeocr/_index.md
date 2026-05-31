---
title: "AsposeOCR"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Classe principale pour reconnaître le texte à partir d'images."
type: docs
weight: 10
url: /fr/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Classe principale pour reconnaître du texte à partir d'images.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Constructeur public. |
## Champs

| Champ | Description |
| --- | --- |
| [DebugMode](#DebugMode) | Active le mode de débogage. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Répertoire où les résultats de débogage seront enregistrés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Calcule les angles d'inclinaison d'une image. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | Vérifie si deux images contiennent le même texte. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Vérifie si deux images contiennent le même texte. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Vérifie si deux images contiennent le même texte. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Corrige le texte (remplace les mots mal orthographiés). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Corrige le texte (remplace les mots mal orthographiés). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | Trouve automatiquement les zones problématiques d'une image qui peuvent affecter significativement la précision de l'OCR. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Analyse l'image et identifie les différents types de zones de contenu qu'elle contient. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Analyse le texte sur l'image pour déterminer les langues dans lesquelles il est écrit. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Détecte les zones de texte sur les images. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Détecte les régions de tableau sur les images. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Vérifie si l'image contient le fragment de texte fourni avec une recherche insensible à la casse. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Vérifie si l'image contient le fragment de texte fourni avec une recherche insensible à la casse. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Vérifie si l'image contient le fragment de texte fourni. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Vérifie si le texte de l'image correspond à l'expression régulière fournie. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Vérifie si le texte de l'image correspond à l'expression régulière fournie. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | Compare les textes des deux images et renvoie un nombre représentant leur similarité (0 à 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Compare les textes des deux images et renvoie un nombre représentant leur similarité (0 à 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Compare les textes des deux images et renvoie un nombre représentant leur similarité (0 à 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Reconnaît les images avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Reconnaît les images avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Reconnaît les plaques d'immatriculation avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Détecte les symboles sur les images. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Détecte les symboles sur les images. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | Reconnaît le texte sur une image de bonne qualité. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Reconnaît les formules mathématiques à partir des images d'entrée fournies. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Reconnaît le texte manuscrit sur les images. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Reconnaît les cartes d'identité avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Reconnaît les factures avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Reconnaît les passeports avec la possibilité de spécifier. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Reconnaît les reçus avec la possibilité de spécifier. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Détecte les tableaux et la structure, reconnaît les cellules de texte. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult avec correction orthographique. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Constructeur public.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Active le mode débogage. Lorsqu'il est activé, le système enregistre les résultats intermédiaires du traitement d'image tels que les images prétraitées et les images avec des rectangles dessinés autour des lignes de texte.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Répertoire où les résultats de débogage seront enregistrés. S'il n'est pas défini, le répertoire de travail actuel sera utilisé par défaut.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Calcule les angles d'inclinaison d'une image. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Le conteneur avec les sources.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - Liste d'angles d'inclinaison en degrés [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


Vérifie si deux images contiennent le même texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath1 | java.lang.String | Chemin vers la première image. |
| fullPath2 | java.lang.String | Chemin vers la deuxième image. |

**Returns:**
boolean - Vrai si les images ont le même texte (90 % de similarité).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Vérifie si deux images contiennent le même texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath1 | java.lang.String | Chemin vers la première image. |
| fullPath2 | java.lang.String | Chemin vers la deuxième image. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Paramètres de reconnaissance. |

**Returns:**
boolean - Vrai si les images ont le même texte (90 % de similarité).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Vérifie si deux images contiennent le même texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath1 | java.lang.String | Chemin vers la première image. |
| fullPath2 | java.lang.String | Chemin vers la deuxième image. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Paramètres de reconnaissance. |
| ignoreCase | boolean | Vrai - signifie une recherche insensible à la casse. |

**Returns:**
boolean - Vrai si les images ont le même texte (90 % de similarité).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Corrige le texte (remplace les mots mal orthographiés).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte pour la correction. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dictionnaire à utiliser [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Texte avec les mots remplacés.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Corrige le texte (remplace les mots mal orthographiés).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte pour la correction. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dictionnaire à utiliser [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Chemin complet vers le dictionnaire utilisateur (dictionnaire de fréquence). Format du fichier dictionnaire : fichier texte brut en encodage UTF-8. Le mot et sa fréquence sont séparés par une virgule, le mot étant attendu dans la première colonne et la fréquence dans la deuxième colonne. Chaque paire mot-fréquence se trouve sur une ligne distincte. Une ligne est définie comme une séquence de caractères suivie d'un saut de ligne ("\\n"), d'un retour chariot ("\\r"), ou d'un retour chariot immédiatement suivi d'un saut de ligne ("\\r\\n"). Chaque mot doit être en minuscules. |

**Returns:**
java.lang.String - Texte avec les mots remplacés.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


Trouve automatiquement les zones problématiques d'une image qui peuvent affecter significativement la précision de l'OCR. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Le conteneur avec les sources.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | Les types de défauts à reconnaître [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - ArrayList de [DefectOutput](../../com.aspose.ocr/defectoutput/) avec les zones de texte détectées ou les lignes.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Analyse l'image et identifie les différents types de zones de contenu qu'elle contient. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Le conteneur avec les sources.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Zones de contenu détectées. ArrayList de [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Analyse le texte de l'image pour déterminer les langues dans lesquelles il est écrit. Cela permet de choisir la langue de reconnaissance la plus adaptée et aide aux tâches ultérieures de traitement du texte telles que la vérification orthographique ou la traduction. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Le conteneur avec les sources.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Retourne une liste des langues les plus probables, classées par probabilité. ArrayList de [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Détecte les zones de texte sur les images. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Le conteneur avec les sources.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Détermine quels rectangles retourner - ligne ou paragraphes. |
| isDetectAreas | boolean | Active la détection automatique des zones de texte. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList de [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) avec les zones de texte détectées ou les lignes.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Détecte les régions de tableau sur les images. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Le conteneur avec les sources.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList de [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) avec les zones de tableau détectées.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Vérifie si l'image contient le fragment de texte fourni avec une recherche insensible à la casse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath | java.lang.String | Chemin vers l'image. |
| text | java.lang.String | Fragment de texte pour la recherche sur l'image. |

**Returns:**
boolean - Vrai si l'image contient le fragment de texte. Faux - l'image ne contient pas le fragment de texte.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Vérifie si l'image contient le fragment de texte fourni avec une recherche insensible à la casse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath | java.lang.String | Chemin vers l'image. |
| text | java.lang.String | Fragment de texte pour la recherche sur l'image. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Paramètres de reconnaissance. |

**Returns:**
boolean - Vrai si l'image contient le fragment de texte. Faux - l'image ne contient pas le fragment de texte.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Vérifie si l'image contient le fragment de texte fourni.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath | java.lang.String | Chemin vers l'image. |
| text | java.lang.String | Fragment de texte pour la recherche sur l'image. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Paramètres de reconnaissance. |
| ignoreCase | boolean | Vrai - signifie une recherche insensible à la casse. |

**Returns:**
boolean - Vrai si l'image contient le fragment de texte. Faux - l'image ne contient pas le fragment de texte.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Vérifie si le texte de l'image correspond à l'expression régulière fournie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath | java.lang.String | Chemin vers l'image. |
| regex | java.util.regex.Pattern | Objet java.util.regex.Pattern avec le motif fourni et les options. |

**Returns:**
boolean - Vrai si le texte de l'image correspond à l'expression régulière fournie.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Vérifie si le texte de l'image correspond à l'expression régulière fournie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath | java.lang.String | Chemin vers l'image. |
| regex | java.util.regex.Pattern | Objet java.util.regex.Pattern avec le motif fourni et les options. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Paramètres de reconnaissance. |

**Returns:**
boolean - Vrai si le texte de l'image correspond à l'expression régulière fournie.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


Compare les textes des deux images et renvoie un nombre représentant leur similarité (0 à 1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath1 | java.lang.String | Chemin vers la première image. |
| fullPath2 | java.lang.String | Chemin vers la deuxième image. |

**Returns:**
float - 0 signifie que les textes sont complètement différents ; 1 signifie que les textes sont identiques.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Compare les textes des deux images et renvoie un nombre représentant leur similarité (0 à 1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath1 | java.lang.String | Chemin vers la première image. |
| fullPath2 | java.lang.String | Chemin vers la deuxième image. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Paramètres de reconnaissance. |

**Returns:**
float - 0 signifie que les textes sont complètement différents ; 1 signifie que les textes sont identiques.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Compare les textes des deux images et renvoie un nombre représentant leur similarité (0 à 1).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullPath1 | java.lang.String | Chemin vers la première image. |
| fullPath2 | java.lang.String | Chemin vers la deuxième image. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Paramètres de reconnaissance. |
| ignoreCase | boolean | Vrai - signifie une recherche insensible à la casse. |

**Returns:**
float - 0 signifie que les textes sont complètement différents ; 1 signifie que les textes sont identiques.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Reconnaît les images avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Reconnaît les images avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Reconnaît les plaques d'immatriculation avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Détecte les symboles sur les images. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Le conteneur avec les sources.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList de [Character](../../com.aspose.ocr.models/character/) contenant les données des symboles détectés pour chaque image.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Détecte les symboles sur les images. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Le conteneur avec les sources.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Détermine le type de réseau neuronal utilisé pour la détection des zones. |
| language | [Language](../../com.aspose.ocr.models/language/) | Langue utilisée pour l'OCR. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList de [Character](../../com.aspose.ocr.models/character/) contenant les données des symboles détectés.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


Reconnaît le texte sur une image de bonne qualité. N'utilise pas de correction automatique de l'inclinaison de l'image ni de détection des zones de texte. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Instance de [OcrInput](../../com.aspose.ocr/ocrinput/). |

**Returns:**
java.util.ArrayList<java.lang.String> - ArrayList contenant le texte reconnu.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Reconnaît les formules mathématiques à partir des images d'entrée fournies. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| detectAreas | boolean | Si défini sur true, détecte et isole automatiquement les zones de formule avant d'effectuer la reconnaissance. Si false, traite l'image entière comme une formule. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Reconnaît le texte manuscrit sur les images. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Le conteneur avec les sources.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Reconnaît les cartes d'identité avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Reconnaît les factures avec la capacité de spécifier la prise en charge de GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Reconnaît le passeport avec la possibilité de spécifier. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Reconnaît les reçus avec la possibilité de spécifier. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Détecte les tables et la structure, reconnaît les cellules de texte. Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, dossier, tableau, archive zip, URL, base64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instance. |
| language | [Language](../../com.aspose.ocr.models/language/) | Détermine l'alphabet utilisé pendant la reconnaissance. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - objets de liste OCRTablePage contenant les textes reconnus dans les tables. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream pour enregistrer le résultat de la reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format de document (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste des [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objets. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream pour enregistrer le résultat de la reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format de document (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste des [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objets. |
| embeddedFontPath | java.lang.String | Optionnellement. Chemin complet vers la police de l'utilisateur. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream pour enregistrer le résultat de la reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format de document (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste des [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objets. |
| embeddedFontPath | java.lang.String | Optionnellement. Chemin complet vers la police de l'utilisateur. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Réduisez la taille du fichier PDF en abaissant la qualité des images d'arrière-plan. Par défaut, la qualité originale de l'image est conservée. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format du document (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste des [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objets. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult avec correction orthographique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format du document (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste des [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objets. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Valeur d'énumération [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format du document (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste des [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objets. |
| embeddedFontPath | java.lang.String | Optionnellement. Chemin complet vers la police de l'utilisateur. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fullFileName | java.lang.String | Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format du document (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste des [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objets. |
| embeddedFontPath | java.lang.String | Optionnellement. Chemin complet vers la police de l'utilisateur. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Réduisez la taille du fichier PDF en abaissant la qualité des images d'arrière-plan. Par défaut, la qualité originale de l'image est conservée. |

### close() {#close}
```
public void close()
```