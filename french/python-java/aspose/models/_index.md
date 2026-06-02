---
title: "modèles"
second_title: "Référence de l'API Aspose.OCR pour Python via Java"
description: 
type: docs
weight: 271
url: /fr/python-java/aspose/models/
---

Module modèles
=============

Classes
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Détermine le type de régions détectées par le modèle.
Utilisé dans get_text_areas pour indiquer quel résultat sera obtenu – coordonnées de paragraphe ou coordonnées de ligne.

### Ancêtres (dans MRO)

    * enum.Enum

### variables de classe

`LINES`
:   Définit les régions comme des lignes

`PARAGRAPHS`
:   Définit les régions comme des paragraphes

`WORDS`
:   Définit les régions comme des mots

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Détermine le type de réseau neuronal utilisé pour la détection des zones.
Utilisé dans RecognitionSettings pour spécifier le type d'image que vous souhaitez reconnaître.

### Ancêtres (dans MRO)

    * enum.Enum

### variables de classe

`COMBINE`
:   Détecte les paragraphes contenant du texte puis utilise un autre modèle NN pour détecter les zones à l'intérieur des paragraphes.
Mieux pour les images à structure complexe.

`CURVED_TEXT`
:   Détecte les lignes et reconnaît le texte sur des images courbées.
Mode préféré pour les photos de pages de livres et de magazines.

`DOCUMENT`
:   Détecte les paragraphes en utilisant le modèle NN pour les documents.
Mieux pour les documents multicolumnes, les documents avec images ou avec d'autres objets non textuels.

`NONE`
:   Ne détecte pas les paragraphes.
Mieux pour un document simple à une colonne sans images.

`PHOTO`
:   Détecte les paragraphes en utilisant le modèle NN pour les photos.
Mieux pour les images contenant de nombreuses photos et d'autres objets non textuels.

`TABLE`
:   Détecte les cellules contenant du texte.
Mode préférable pour les images à structure de tableau.

`TEXT_IN_WILD`
:   Un réseau neuronal ultra‑puissant spécialisé dans l'extraction de mots à partir d'images de basse qualité telles que les photos de rue, les plaques d'immatriculation, les photos de passeport, les photos de compteurs et les photos avec des arrière‑plans bruyants.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Format pour enregistrer le résultat de reconnaissance en tant que document.

### Ancêtres (dans MRO)

    * enum.Enum

### variables de classe

`DOCX`
:   Enregistre le résultat sous forme de document Office Open XML Word processing ML (sans macro).

`EPUB`
:   Enregistre le document sous forme de fichier EPUB.

`HTML`
:   Enregistre le document au format HTML.

`JSON`
:   Enregistre le résultat sous forme de texte brut écrit en notation d'objet JavaScript.

`PDF`
:   Enregistre le résultat au format PDF (Adobe Portable Document) Document.

`PDF_NO_IMG`
:   Enregistre le document au format PDF recherchable (Adobe Portable Document) Document sans image.

`RTF`
:   Enregistre le document au format rtf.

`TEXT`
:   Enregistre le résultat au format texte brut.

`XLSX`
:   Enregistre le résultat au format Excel (2007 et versions ultérieures) cahier Document.

`XML`
:   Enregistre le résultat au format XML Document.

`ImageData(javaClass)`
:

### Ancêtres (dans MRO)

    * aspose.helper.BaseJavaClass

### Méthodes

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Types d'images/documents pour le traitement / la reconnaissance.

### Ancêtres (dans MRO)

    * enum.Enum

### variables de classe

`BASE64`
:   chaîne base64 contenant l'image ou le chemin vers le fichier .txt avec le contenu base64. Prend en charge GIF, PNG, JPEG, BMP, TIFF.

`DIRECTORY`
:   Chemin vers le répertoire. Les archives et dossiers imbriqués ne sont pas pris en charge.
Prend en charge GIF, PNG, JPEG, BMP, TIFF.
Le nombre d'images traitées par défaut est toutes les images.

`PDF`
:   Document PDF numérisé à partir d'un fichier ou d'un tableau binaire.

`SINGLE_IMAGE`
:   Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, tableau binaire.

`TIFF`
:   Document TIFF multipage, TIF à partir d'un fichier ou d'un InputStream.

`URL`
:   Lien sur l'image. Prend en charge GIF, PNG, JPEG, BMP, TIFF.

`ZIP`
:   Nom complet de l'archive ZIP. Les archives imbriquées et les dossiers ne sont pas pris en charge.
Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF.
Le nombre d'images traitées par défaut est toutes les images.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Modèle de langue pour la reconnaissance.

### Ancêtres (dans MRO)

    * enum.Enum

### variables de classe

`BEL`
:   Alphabet biélorusse

`BUL`
:   Alphabet bulgare

`CHI`
:   Alphabet chinois

`CYRILLIC`
:   Prise en charge multilingue (alphabet cyrillique)

`CZE`
:   Alphabet tchèque

`DAN`
:   Alphabet danois

`DEU`
:   alphabet allemand

`DUM`
:   alphabet néerlandais

`ENG`
:   alphabet anglais

`EST`
:   alphabet estonien

`FIN`
:   alphabet finnois

`FRA`
:   alphabet français

`HIN`
:   alphabet hindi

`ITA`
:   alphabet italien

`KAZ`
:   alphabet kazakh

`LATIN`
:   Prise en charge multi - langue (alphabet latin)

`LAV`
:   alphabet letton

`LIT`
:   alphabet lituanien

`NONE`
:   Prise en charge multi - langue

`NOR`
:   alphabet norvégien

`POL`
:   alphabet polonais

`POR`
:   alphabet portugais

`RUM`
:   alphabet roumain

`RUS`
:   alphabet russe

`SLK`
:   alphabet slovaque

`SLV`
:   alphabet slovène

`SPA`
:   alphabet espagnol

`SRP`
:   alphabet serbe

`SRP_HRV`
:   alphabet serbo-croate

`SWE`
:   alphabet suédois

`UKR`
:   alphabet ukrainien

`ModelsConverter()`
:

### Méthodes

`convertInputTypeToJava(jType)`
:

`convertToJavaAreasMode(jType)`
:

`convertToJavaAreasType(jType)`
:

`convertToJavaFormat(jType)`
:

`convertToJavaLanguage(jType)`
:

`convertToJavaSpellCheckLanguage(jType)`
:

`OcrInput(type: models.InputType, filters: models.PreprocessingFilter = None)`
:   Classe principale pour collecter les images.
    
Constructeur pour créer le conteneur et définir le type d'images / documents ainsi que les filtres pour le traitement / la reconnaissance ultérieurs.
@param type: Définir le type d'images/documents qui sera ajouté au conteneur.
@param filters: Définir les filtres de traitement qui seront appliqués pour le traitement ou la reconnaissance ultérieurs.

### Méthodes

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   Ajouter le chemin ou l'URI contenant l'image pour la reconnaissance / le traitement.
Le type de l'image doit correspondre au type spécifié dans le constructeur.
@param fullPath: Chemin vers l'image / le document / le dossier / l'archive.
@param startPage: La première page/image pour le traitement / la reconnaissance. À utiliser pour les documents, les archives zip, les dossiers.
@param pagesNumber: Le nombre total de pages/images pour le traitement / la reconnaissance. À utiliser pour les documents, les archives zip, les dossiers. Par défaut = tous.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   Ajouter le InputStream contenant l'image pour la reconnaissance / le traitement.
Le type de l'image doit correspondre au type spécifié dans le constructeur.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: contenant l'image ou le document.
@param startPage: La première page/image pour le traitement / la reconnaissance. À utiliser pour les documents, les archives zip, les dossiers.
@param pagesNumber: Le nombre total de pages/images pour le traitement / la reconnaissance. À utiliser pour les documents, les archives zip, les dossiers. Par défaut = tous.

`add_base64(self, base64: str)`
:   Ajoutez la chaîne base64 contenant l'image pour la reconnaissance / le traitement.
Le type de l'image doit correspondre au type spécifié dans le constructeur.
@param base64: Chaîne Base64 avec une seule image.

`clear(self)`
:   Définissez le nombre d'éléments pour le traitement / la reconnaissance à 0.
Effacez la collection.

`clear_filters(self)`
:   Supprimez tous les filtres.

`get(self, index: int) ‑> models.ImageData`
:   Retourne des informations sur l'image traitée / reconnue.
@param index: Position de l'image dans la liste.
@return: L'objet ImageData.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   Nombre d'éléments pour le traitement / la reconnaissance.
@return: Nombre d'éléments.

`PreprocessingFilter()`
:   Classe de base pour les commandes de traitement d'image.

### Ancêtres (dans MRO)

    * aspose.helper.BaseJavaClass

### variables de classe

`JAVA_CLASS_NAME`
:

### Méthodes statiques

`auto_denoising()`
:   Permet l'utilisation d'un réseau neuronal supplémentaire pour améliorer l'image - réduire le bruit.
Utile pour les images présentant des artefacts de numérisation, des distorsions, des taches, des reflets, des dégradés, des éléments étrangers.
@return: Objet AutoDenoisingFilter.

`auto_dewarping()`
:   Corrige automatiquement les distorsions géométriques de l'image.
Extrêmement gourmand en ressources!
@return: Objet AutoDewarpingFilter.

`auto_skew()`
:   Active la correction automatique de l'inclinaison d'image.
@return: objet AutoSkewFilter.

`binarize()`
:   Convertit une image en image noir et blanc.
Les images binaires sont des images dont les pixels n'ont que deux valeurs d'intensité possibles.
Elles sont généralement affichées en noir et blanc. Numériquement, les deux valeurs sont souvent 0 pour le noir et 255 pour le blanc.
Les images binaires sont produites par un seuillage automatique d'une image.
@return: objet BinarizeFilter.

`binarize_and_dilate()`
:   La dilatation ajoute des pixels aux frontières des objets dans une image.
@return: objet DilateFilter.

`contrast_correction()`
:   Filtre de correction de contraste.
@return: objet ContrastCorrectionFilter.

`invert()`
:   Inverse automatiquement les couleurs d'une image de document.
@return: objet InvertFilter.

`median()`
:   Le filtre médian parcourt chaque élément de l'image et remplace chaque pixel par la médiane de ses pixels voisins.
@return: objet MedianFilter.

`resize(width: int, height: int)`
:   Redimensionne l'image - augmente ou diminue la résolution de l'image.
@param width: La nouvelle largeur de l'image.
@param height: La nouvelle hauteur de l'image.
@return: objet ResizeFilter.

`rotate(angle: float)`
:   Faire pivoter l'image originale.
@param angle: angle de rotation. Valeur de -360 à 360.
@return: objet RotateFilter.

`scale(ratio: float)`
:   Redimensionner l'image - augmenter ou diminuer la résolution de l'image.
InterpolationFilterType bilinéaire ou voisin le plus proche.
@param ratio: le facteur d'échelle. Valeur recommandée de 0,1 à 1 pour réduire. De 1 à 10 pour agrandir.
@return: objet ScaleFilter.

`threshold(value: int)`
:   Créer une image binaire en définissant une valeur de seuil sur l'intensité des pixels de l'image originale.
@param value: la valeur maximale.
@return: objet BinarizeFilter.

`to_grayscale()`
:   Convertit une image en image en niveaux de gris.
L'image en niveaux de gris possède 256 niveaux de luminosité (0 à 255).
@return: objet GrayscaleFilter.

### Méthodes

`add(self, filter)`
:   Ajouter le filtre à la collection pour un prétraitement ultérieur.
@param filter: objet PreprocessingFilter.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   Représente un mot mal orthographié avec des données supplémentaires.

### Ancêtres (dans MRO)

    * aspose.helper.BaseJavaClass

### Méthodes

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Langue du dictionnaire pour la correction orthographique.

### Ancêtres (dans MRO)

    * enum.Enum

### variables de classe

`CZE`
:   Dictionnaire tchèque

`DAN`
:   dictionnaire danois

`DEU`
:   dictionnaire allemand

`DUM`
:   dictionnaire néerlandais

`ENG`
:   dictionnaire anglais

`EST`
:   dictionnaire estonien

`FIN`
:   dictionnaire finnois

`FRA`
:   dictionnaire français

`ITA`
:   dictionnaire italien

`LAV`
:   dictionnaire letton

`LIT`
:   dictionnaire lituanien

`POL`
:   dictionnaire polonais

`POR`
:   dictionnaire portugais

`RUM`
:   dictionnaire roumain

`SLK`
:   dictionnaire slovaque

`SLV`
:   dictionnaire slovène

`SPA`
:   dictionnaire espagnol

`SWE`
:   dictionnaire suédois

`SuggestedWord(javaClass)`
:   Suggestion d'orthographe renvoyée par get_spell_check_error_list.

### Ancêtres (dans MRO)

    * aspose.helper.BaseJavaClass

### Méthodes

`initParams(self)`
:


### Voir aussi

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)