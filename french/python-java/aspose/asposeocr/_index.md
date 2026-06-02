---
title: "AsposeOcr"
second_title: "Référence de l'API Aspose.OCR pour Python via Java"
description: 
type: docs
weight: 11
url: /fr/python-java/aspose/asposeocr/
---


Module asposeocr
================
Interface Python pour l'Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
tout en étant une reconnaissance optique de caractères (OCR) facile à utiliser
moteur pour vos applications Python et notebooks.
En moins de **10** lignes de code, vous pouvez reconnaître
texte en **28** langues basées sur le latin, le cyrillique,
et les scripts asiatiques, renvoyant les résultats dans les formats les plus populaires
formats d'échange de documents et de données.
Il n'est pas nécessaire d'apprendre des modèles mathématiques complexes,
construire des algorithmes d'apprentissage automatique et entraîner des réseaux
neuronaux — notre API simple et robuste fera tout pour vous.

Classes
-------

`AsposeOcr()`
:
Classe principale AsposeOcr pour la reconnaissance.
    
Cet exemple montre comment reconnaître une image.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Méthodes statiques

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
Permet d'obtenir un document multipage à partir d'une liste d'objets RecognitionResult.
@param fullFileName: Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance dans le format sélectionné.
@param saveFormat: Format du document (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Méthodes

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Calcule les angles d'inclinaison d'une image.
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance. Le conteneur avec les sources.
@return: Liste des angles d'inclinaison en degrés - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Vérifie si deux images contiennent le même texte.
@param fullPath1: Chemin vers la première image.
@param fullPath2: Chemin vers la deuxième image.
@param settings: Paramètres de reconnaissance.
@param ignoreCase: True - signifie une recherche insensible à la casse.
@return: True si les images ont le même texte (similarité de 90 %).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Corrige le texte (remplace les mots mal orthographiés).
@param text: Texte à corriger.
@param language: Dictionnaire à utiliser SpellCheckLanguage.
@return: Texte avec les mots remplacés.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Détecte les zones de texte sur les images.
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param areasType: Détermine quels rectangles retourner - ligne, paragraphes ou mots.
@param isDetectAreas: Active la détection automatique des zones de texte.
@return: Liste de RectangleOutput avec les zones de texte détectées ou les lignes.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Vérifie si l'image contient le fragment de texte fourni.
@param fullPath: Chemin vers l'image.
@param text: Fragment de texte à rechercher sur l'image.
@param settings: Paramètres de reconnaissance.
@param ignoreCase: True - signifie une recherche insensible à la casse.
@return: True si l'image contient le fragment de texte. False - l'image ne contient pas le fragment de texte.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) -> float`
:
Compare les textes sur les deux images et renvoie un nombre représentant leur degré de similarité (0 à 1).
@param fullPath1: Chemin vers la première image.
@param fullPath2: Chemin vers la deuxième image.
@param settings: Paramètres de reconnaissance.
@param ignoreCase: True - signifie une recherche insensible à la casse.
@return: 0 signifie que les textes sont complètement différents ; 1 signifie que les textes sont identiques.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) -> List[aspose.recognitionresult.RecognitionResult]`
:
Reconnaît l'image avec la possibilité de spécifier RecognitionSettings.
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: Objet RecognitionSettings.
@return: Liste de RecognitionResult contenant les résultats de reconnaissance des images.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) -> List[aspose.recognitionresult.RecognitionResult]`
:
Reconnaît la plaque d'immatriculation avec la possibilité de spécifier CarPlateRecognitionSettings.
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: CarPlateRecognitionSettings
@return: Liste de RecognitionResult contenant les résultats de reconnaissance des images.

`recognize_fast(self, input: aspose.models.OcrInput) -> List[aspose.recognitionresult.RecognitionResult]`
:
Reconnaît le texte sur une image de bonne qualité. N'utilise pas la correction automatique de l'inclinaison de l'image et les zones de texte
détection.
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@return: Liste de RecognitionResult contenant les résultats de reconnaissance des images.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) -> List[aspose.recognitionresult.RecognitionResult]`
:
Reconnaît la carte d'identité avec la possibilité de spécifier IDCardRecognitionSettings.
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: IDCardRecognitionSettings
@return: Liste de RecognitionResult contenant les résultats de reconnaissance des images.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) -> List[aspose.recognitionresult.RecognitionResult]`
:
Reconnaît la facture avec la possibilité de spécifier InvoiceRecognitionSettings
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: InvoiceRecognitionSettings
@return: Liste de RecognitionResult contenant les résultats de reconnaissance des images.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) -> List[aspose.recognitionresult.RecognitionResult]`
:
Reconnaît une image à ligne unique avec la possibilité de spécifier RecognitionSettings.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: Objet RecognitionSettings.
@return: Liste de RecognitionResult contenant les résultats de reconnaissance des images.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) -> List[aspose.recognitionresult.RecognitionResult]`
:
Reconnaît les passeports avec la possibilité de spécifier PassportRecognitionSettings.
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: PassportRecognitionSettings
@return: Liste de RecognitionResult contenant les résultats de reconnaissance des images.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconnaît les reçus avec la possibilité de spécifier ReceiptRecognitionSettings.
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: ReceiptRecognitionSettings
@return: Liste de RecognitionResult contenant les résultats de reconnaissance des images.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconnaît le texte sur les photos de rue.
Extrait le texte des photos de rue, des images de caméras de circulation, des cartes d'identité, des permis de conduire et d'autres images contenant peu de texte et des arrière-plans bruyants/colorés.
Prend en charge GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, tableau binaire, dossier, tableau, archive zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@return: Liste de RecognitionResult contenant les résultats de reconnaissance des images.

`shutdown(self)`
:
Arrête la machine JVM.

`ImageProcessing()`
:
Classe d'aide pour la bibliothèque Aspose OCR. Permet de prétraiter et d'enregistrer les images.

### Méthodes statiques

`save(images, folderPath)`
:
Utilisez le traitement d'image pour améliorer la précision de l'OCR.
Créez une liste de filtres qui seront appliqués à l'image d'entrée dans l'ordre que vous spécifiez.
\code
filters = new PreprocessingFilter();
filters.add(PreprocessingFilter.auto_dewarping());
filters.add(PreprocessingFilter.invert());
filters.add(PreprocessingFilter.threshold(150));
filters.add(PreprocessingFilter.binarize());
filters.add(PreprocessingFilter.rotate(180));
filters.add(PreprocessingFilter.scale(6));
filters.add(PreprocessingFilter.dilate());
        
images = OcrInput(InputType.PDF, filters);
\endcode
Vous n'avez pas besoin de tous. Définissez uniquement ce dont vous avez besoin.
@param images: objet OcrInput contenant différentes images OcrInput.
@param folderPath: Chemin sans noms d'images pour enregistrer les images traitées.
@return: objet OcrInput contenant les images traitées résultantes OcrInput.


### Voir aussi

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)