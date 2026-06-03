---
title: "RecognitionResult"
second_title: "Referencia de la API de Aspose.OCR para Python vía Java"
description: 
type: docs
weight: 171
url: /es/python-java/aspose/recognitionresult/
---

Módulo recognitionresult
========================

Clases
-------

`LinesResult(javaClass)`
:

### Ancestros (en MRO)

    * aspose.helper.BaseJavaClass

### Métodos

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
Los resultados del reconocimiento de imágenes. Contiene elementos con reconocimiento
información y métodos para la exportación de resultados.

### Métodos estáticos

`save_multipage_document(self, fullPath: str)`
:
Privado

### Variables de instancia

`recognition_areas_text`
:   Lista de resultados de reconocimiento de una lista de áreas (Rectángulos).

`recognition_lines_result`
:   Obtiene una lista de resultados de reconocimiento con una lista de filas (Rectángulos).

### Métodos

`getJavaClass(self)`
:

`get_json(self)`
:
Forma cadena JSON con resultados de reconocimiento.
@return: Resultados de reconocimiento como cadena JSON.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Corrige texto (reemplaza palabras mal escritas).
@param language: Diccionario a usar.
@return: Cadena de resultados de reconocimiento corregidos.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Encuentra las palabras mal escritas con sugerencias de ortografía para un texto de entrada dado.
@param language: Diccionario a usar.
@return: Lista de objetos SpellCheckError que representan palabras mal escritas con listas de sugerencias de ortografía correctas para cada palabra mal escrita,
y con la distancia de edición.

`get_xml(self)`
:
Forma cadena JSON con resultados de reconocimiento.
@return: Resultados de reconocimiento como cadena XML.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Guarda el documento en texto plano u otro formato de documento.
@param fullFileName: Nombre de archivo con ruta para guardar el resultado del reconocimiento.
@param format: Tipo de enumeración del formato de documento.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Corrige texto (reemplaza palabras mal escritas).
Guarda el texto corregido en el documento en texto plano u otro formato.
@param fullFileName: Nombre de archivo con ruta para guardar el resultado del reconocimiento
@param format: Tipo de enumeración del formato de documento.
@param language: Diccionario para la corrección ortográfica.

`use_user_dictionary(self, dictionaryPath: str)`
:
Permite usar un diccionario propio para la corrección ortográfica.
@param dictionaryPath: Ruta completa al diccionario de usuario (diccionario de frecuencias).
Formato del archivo de diccionario:
Archivo de texto plano con codificación UTF-8.
La palabra y la frecuencia de la palabra están separadas por coma, se espera que la palabra esté en la primera columna y la frecuencia en la segunda columna.
Cada par palabra-frecuencia en una línea separada. Una línea se define como una secuencia de caracteres seguida de un salto de línea ("
"), un retorno de carro ("
"),
o un retorno de carro seguido inmediatamente por un salto de línea("

").
Se espera que cada palabra esté en minúsculas.
Ejemplo:
\code
palabra,5984819
hola,5761742
abajo,5582768
\endcode

`RectangleOutput(javaClass)`
:
Datos sobre áreas de texto o líneas detectadas.
\code
source - La ruta completa al archivo o URL, si la hay. Vacío para flujos, matrices de bytes, base64.
page - Número de página.
image_index - Número de secuencia de la imagen en la página.
rectangles - Lista de áreas de texto detectadas o líneas.
\endcode

### Ancestros (en MRO)

    * aspose.helper.BaseJavaClass

### Métodos

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Datos sobre el ángulo de inclinación en grados y el nombre del archivo.
\code
source - La ruta completa al archivo o URL, si la hay. Vacío para flujos, matrices de bytes, base64.
page - Número de página.
image_index - Número de secuencia de la imagen en la página.
angle - Ángulo de inclinación en grados.
\endcode

### Ancestros (en MRO)

    * aspose.helper.BaseJavaClass

### Métodos

`initParams(self)`
:


### Ver también

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)