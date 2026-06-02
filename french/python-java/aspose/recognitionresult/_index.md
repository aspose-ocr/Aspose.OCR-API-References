---
title: "RecognitionResult"
second_title: "Référence de l'API Aspose.OCR pour Python via Java"
description: 
type: docs
weight: 171
url: /fr/python-java/aspose/recognitionresult/
---

Module recognitionresult
========================

Classes
-------

`LinesResult(javaClass)`
:

### Ancêtres (dans MRO)

    * aspose.helper.BaseJavaClass

### Méthodes

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
Les résultats de la reconnaissance d'image. Contient des éléments avec reconnaissance
information et méthodes pour l'exportation des résultats.

### Méthodes statiques

`save_multipage_document(self, fullPath: str)`
:
Privé

### Variables d'instance

`recognition_areas_text`
:   Liste des résultats de reconnaissance d'une liste de zones (Rectangles).

`recognition_lines_result`
:   Obtient une liste de résultats de reconnaissance avec une liste de lignes (Rectangles).

### Méthodes

`getJavaClass(self)`
:

`get_json(self)`
:
Forme une chaîne JSON avec les résultats de reconnaissance.
@return: Résultats de reconnaissance sous forme de chaîne JSON.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Corrige le texte (remplace les mots mal orthographiés).
@param language: Dictionnaire à utiliser.
@return: Chaîne de résultats de reconnaissance corrigés.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Trouvez les mots mal orthographiés avec les orthographes suggérées pour un texte d'entrée donné.
@param language: Dictionnaire à utiliser.
@return: Liste d'objets SpellCheckError représentant les mots mal orthographiés avec des listes d'orthographes correctes suggérées pour chaque mot mal orthographié,
et avec la distance d'édition.

`get_xml(self)`
:
Forme une chaîne JSON avec les résultats de reconnaissance.
@return: Résultats de reconnaissance sous forme de chaîne XML.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Enregistre le document au format texte brut ou dans un autre format de document.
@param fullFileName: Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance.
@param format: Type d'énumération du format de document Format.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Corrige le texte (remplace les mots mal orthographiés).
Enregistre le texte corrigé dans le document au format texte brut ou dans un autre format.
@param fullFileName: Nom de fichier avec un chemin pour enregistrer le résultat de reconnaissance
@param format: Type d'énumération du format de document Format.
@param language: Dictionnaire pour la vérification orthographique.

`use_user_dictionary(self, dictionaryPath: str)`
:
Permet d'utiliser son propre dictionnaire pour la correction orthographique.
@param dictionaryPath: Chemin complet vers le dictionnaire utilisateur (dictionnaire de fréquence).
Format du fichier dictionnaire :
Fichier texte brut en encodage UTF-8.
Le mot et la fréquence du mot sont séparés par une virgule, le mot étant attendu dans la première colonne et la fréquence dans la deuxième colonne.
Chaque paire mot-fréquence sur une ligne séparée. Une ligne est définie comme une séquence de caractères suivie d'un saut de ligne ("
"), un retour chariot ("
"),
ou un retour chariot immédiatement suivi d'un saut de ligne(\"

"\).
Chaque mot doit être en minuscules.
Exemple:
\code
word,5984819
hello,5761742
down,5582768
\endcode

`RectangleOutput(javaClass)`
:
Données sur les zones de texte ou les lignes détectées.
\code
source - Le chemin complet du fichier ou de l'URL, le cas échéant. Vide pour les flux, les tableaux d'octets, base64.
page - Numéro de page.
image_index - Numéro de séquence de l'image sur la page.
rectangles - Liste des zones de texte ou des lignes détectées.
\endcode

### Ancêtres (dans MRO)

    * aspose.helper.BaseJavaClass

### Méthodes

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Données sur l'angle d'inclinaison en degrés et le nom du fichier.
\code
source - Le chemin complet du fichier ou de l'URL, le cas échéant. Vide pour les flux, les tableaux d'octets, base64.
page - Numéro de page.
image_index - Numéro de séquence de l'image sur la page.
angle - Angle d'inclinaison en degrés.
\endcode

### Ancêtres (dans MRO)

    * aspose.helper.BaseJavaClass

### Méthodes

`initParams(self)`
:


### Voir aussi

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)