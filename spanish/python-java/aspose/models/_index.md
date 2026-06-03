---
title: "modelos"
second_title: "Referencia de la API de Aspose.OCR para Python vía Java"
description: 
type: docs
weight: 271
url: /es/python-java/aspose/models/
---

Módulo modelos
=============

Clases
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Determina el tipo de regiones detectadas por el modelo.
Usado en get_text_areas para indicar qué resultado se obtendrá - coordenadas de párrafo o coordenadas de línea.

### Ancestros (en MRO)

    * enum.Enum

### Variables de clase

`LINES`
:   Establece regiones como líneas

`PARAGRAPHS`
:   Establece regiones como párrafos

`WORDS`
:   Establece regiones como palabras

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Determina el tipo de red neuronal utilizada para la detección de áreas.
Usado en RecognitionSettings para especificar qué tipo de imagen desea reconocer.

### Ancestros (en MRO)

    * enum.Enum

### Variables de clase

`COMBINE`
:   Detecta párrafos con texto y luego usa otro modelo NN para detectar áreas dentro de los párrafos.
Mejor para imágenes con estructura compleja.

`CURVED_TEXT`
:   Detecta líneas y reconoce texto en imágenes curvadas.
Modo preferido para fotos de páginas de libros y revistas.

`DOCUMENT`
:   Detecta párrafos usando modelo NN para documentos.
Mejor para documentos multicolumna, documentos con imágenes o con otros objetos que no son texto.

`NONE`
:   No detecta párrafos.
Mejor para un documento simple de una sola columna sin imágenes.

`PHOTO`
:   Detecta párrafos usando modelo NN para fotos.
Mejor para imágenes con muchas fotos y otros objetos que no son texto.

`TABLE`
:   Detecta celdas con texto.
Modo preferible para imágenes con estructura de tabla.

`TEXT_IN_WILD`
:   Una red neuronal superpotente especializada en extraer palabras de imágenes de baja calidad como fotos de calle, matrículas, fotos de pasaporte, fotos de medidores y fotos con fondos ruidosos.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Formato para guardar el resultado del reconocimiento como documento.

### Ancestros (en MRO)

    * enum.Enum

### Variables de clase

`DOCX`
:   Guarda el resultado como un Documento de Procesamiento de Texto Office Open XML (sin macros).

`EPUB`
:   Guarda el documento como un archivo EPUB.

`HTML`
:   Guarda el documento como un archivo HTML.

`JSON`
:   Guarda el resultado como texto plano escrito en notación de objetos JavaScript.

`PDF`
:   Guarda el resultado como un documento PDF (Adobe Portable Document).

`PDF_NO_IMG`
:   Guarda el documento como un PDF buscable (Adobe Portable Document) sin imagen.

`RTF`
:   Guarda el documento como un archivo rtf.

`TEXT`
:   Guarda el resultado en formato de texto plano.

`XLSX`
:   Guarda el resultado como un libro de trabajo Excel (2007 y posteriores).

`XML`
:   Guarda el resultado como un documento XML.

`ImageData(javaClass)`
:

### Ancestros (en MRO)

    * aspose.helper.BaseJavaClass

### Métodos

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Tipos de imágenes/documentos para procesamiento / reconocimiento.

### Ancestros (en MRO)

    * enum.Enum

### Variables de clase

`BASE64`
:   cadena base64 con la imagen o ruta al archivo .txt con el contenido base64. Compatible con GIF, PNG, JPEG, BMP, TIFF.

`DIRECTORY`
:   Ruta al directorio. Los archivos y carpetas anidados no son compatibles.
Compatible con GIF, PNG, JPEG, BMP, TIFF.
La cantidad predeterminada de imágenes procesadas es todas.

`PDF`
:   Documento PDF escaneado desde archivo o desde una matriz binaria.

`SINGLE_IMAGE`
:   Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF, matriz binaria.

`TIFF`
:   Documento TIFF multipágina, TIF desde archivo o desde InputStream.

`URL`
:   Enlace en la imagen. Soporta GIF, PNG, JPEG, BMP, TIFF.

`ZIP`
:   Nombre completo del archivo ZIP. Los archivos y carpetas anidados no son compatibles.
Soporta GIF, PNG, JPEG, BMP, TIFF, JFIF.
La cantidad predeterminada de imágenes procesadas es todas.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Modelo de lenguaje para el reconocimiento.

### Ancestros (en MRO)

    * enum.Enum

### Variables de clase

`BEL`
:   Alfabeto bielorruso

`BUL`
:   Alfabeto búlgaro

`CHI`
:   Alfabeto chino

`CYRILLIC`
:   Soporte multilingüe (alfabeto cirílico)

`CZE`
:   Alfabeto checo

`DAN`
:   Alfabeto danés

`DEU`
:   alfabeto alemán

`DUM`
:   alfabeto holandés

`ENG`
:   alfabeto inglés

`EST`
:   alfabeto estonio

`FIN`
:   alfabeto finlandés

`FRA`
:   alfabeto francés

`HIN`
:   alfabeto hindi

`ITA`
:   alfabeto italiano

`KAZ`
:   alfabeto kazajo

`LATIN`
:   soporte multilingüe (alfabeto latino)

`LAV`
:   alfabeto letón

`LIT`
:   alfabeto lituano

`NONE`
:   soporte multilingüe

`NOR`
:   alfabeto noruego

`POL`
:   alfabeto polaco

`POR`
:   alfabeto portugués

`RUM`
:   alfabeto rumano

`RUS`
:   alfabeto ruso

`SLK`
:   alfabeto eslovaco

`SLV`
:   alfabeto esloveno

`SPA`
:   alfabeto español

`SRP`
:   alfabeto serbio

`SRP_HRV`
:   alfabeto serbocroata

`SWE`
:   alfabeto sueco

`UKR`
:   alfabeto ucraniano

`ModelsConverter()`
:

### Métodos

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

`OcrInput(type: models.InputType, filters: models.PreprocessingFilter = None)`
:   Clase principal para recopilar imágenes.
    
Constructor para crear el contenedor y establecer el tipo de imágenes / documentos y los filtros para procesamiento / reconocimiento posteriores.
@param type: Establece el tipo de imágenes/documentos que se añadirá al contenedor.
@param filters: Establece los filtros de procesamiento que se aplicarán para el procesamiento o reconocimiento posterior.

### Métodos

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   Añade la ruta o URI que contiene la imagen para reconocimiento / procesamiento.
El tipo de la imagen debe corresponder al tipo especificado en el constructor.
@param fullPath: Ruta a la imagen/documento/carpeta/archivo.
@param startPage: La primera página/imagen para procesamiento / reconocimiento. Úsese para documentos, zip, carpetas.
@param pagesNumber: La cantidad total de páginas/imagenes para procesamiento / reconocimiento. Úsese para documentos, zip, carpetas. Predeterminado = todas.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   Añade el InputStream que contiene la imagen para reconocimiento / procesamiento.
El tipo de la imagen debe corresponder al tipo especificado en el constructor.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: que contiene la imagen o documento.
@param startPage: La primera página/imagen para procesamiento / reconocimiento. Úsese para documentos, zip, carpetas.
@param pagesNumber: La cantidad total de páginas/imagenes para procesamiento / reconocimiento. Úsese para documentos, zip, carpetas. Predeterminado = todas.

`add_base64(self, base64: str)`
:   Añade la cadena base64 que contiene la imagen para reconocimiento / procesamiento.
El tipo de la imagen debe corresponder al tipo especificado en el constructor.
@param base64: Cadena Base64 con una sola imagen.

`clear(self)`
:   Establece la cantidad de elementos para procesamiento / reconocimiento en 0.
Borra la colección.

`clear_filters(self)`
:   Elimina todos los filtros.

`get(self, index: int) ‑> models.ImageData`
:   Devuelve información sobre la imagen procesada / reconocida.
@param index: Posición de la imagen en la Lista.
@return: El objeto ImageData.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   Cantidad de elementos para procesamiento / reconocimiento.
@return: Cantidad de elementos.

`PreprocessingFilter()`
:   Clase base para comandos de procesamiento de imágenes.

### Ancestros (en MRO)

    * aspose.helper.BaseJavaClass

### Variables de clase

`JAVA_CLASS_NAME`
:

### Métodos estáticos

`auto_denoising()`
:   Permite el uso de una red neuronal adicional para mejorar la imagen - reducir ruido.
Útil para imágenes con artefactos de escaneo, distorsión, manchas, destellos, gradientes, elementos extraños.
@return: Objeto AutoDenoisingFilter.

`auto_dewarping()`
:   Corrige automáticamente las distorsiones geométricas en la imagen.
¡Extremadamente intensivo en recursos!
@return: Objeto AutoDewarpingFilter.

`auto_skew()`
:   Habilita la corrección automática de sesgo de la imagen.
@return: objeto AutoSkewFilter.

`binarize()`
:   Convierte una imagen a una imagen en blanco y negro.
Las imágenes binarias son imágenes cuyos píxeles tienen solo dos valores de intensidad posibles.
Normalmente se muestran en blanco y negro. Numéricamente, los dos valores suelen ser 0 para negro y 255 para blanco.
Las imágenes binarias se generan mediante umbralado automático de una imagen.
@return: objeto BinarizeFilter.

`binarize_and_dilate()`
:   La dilatación agrega píxeles a los bordes de los objetos en una imagen.
@return: objeto DilateFilter.

`contrast_correction()`
:   Filtro de corrección de contraste.
@return: objeto ContrastCorrectionFilter.

`invert()`
:   Invierte automáticamente los colores en una imagen de documento.
@return: objeto InvertFilter.

`median()`
:   El filtro de mediana recorre cada elemento de la imagen y reemplaza cada píxel con la mediana de sus píxeles vecinos.
@return: objeto MedianFilter.

`resize(width: int, height: int)`
:   Cambia la escala de la imagen - aumenta o disminuye la resolución de la imagen.
@param width: El nuevo ancho de la imagen.
@param height: El nuevo alto de la imagen.
@return: objeto ResizeFilter.

`rotate(angle: float)`
:   Rotar imagen original.
@param angle: Ángulo de rotación. Valor de -360 a 360.
@return: objeto RotateFilter.

`scale(ratio: float)`
:   Cambiar escala de la imagen - Aumentar o reducir la resolución de la imagen.
InterpolationFilterType bilineal o vecino más cercano.
@param ratio: El factor de escala. Valor recomendado de 0.1 a 1 para reducir. De 1 a 10 para ampliar.
@return: objeto ScaleFilter.

`threshold(value: int)`
:   Crear una imagen binaria estableciendo un valor de umbral sobre la intensidad de píxeles de la imagen original.
@param value: El valor máximo.
@return: objeto BinarizeFilter.

`to_grayscale()`
:   Convierte una imagen a escala de grises.
La imagen en escala de grises tiene 256 niveles de luz (0 a 255).
@return: objeto GrayscaleFilter.

### Métodos

`add(self, filter)`
:   Añadir filtro a la colección para un preprocesamiento adicional.
@param filter: objeto PreprocessingFilter.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   Representa una palabra mal escrita con datos adicionales.

### Ancestros (en MRO)

    * aspose.helper.BaseJavaClass

### Métodos

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Idioma del diccionario para corrección ortográfica.

### Ancestros (en MRO)

    * enum.Enum

### Variables de clase

`CZE`
:   Diccionario checo

`DAN`
:   diccionario danés

`DEU`
:   diccionario alemán

`DUM`
:   diccionario holandés

`ENG`
:   diccionario inglés

`EST`
:   diccionario estonio

`FIN`
:   diccionario finlandés

`FRA`
:   diccionario francés

`ITA`
:   diccionario italiano

`LAV`
:   diccionario letón

`LIT`
:   diccionario lituano

`POL`
:   diccionario polaco

`POR`
:   diccionario portugués

`RUM`
:   diccionario rumano

`SLK`
:   diccionario eslovaco

`SLV`
:   diccionario esloveno

`SPA`
:   diccionario español

`SWE`
:   diccionario sueco

`SuggestedWord(javaClass)`
:   Sugerencia de ortografía devuelta por get_spell_check_error_list.

### Ancestros (en MRO)

    * aspose.helper.BaseJavaClass

### Métodos

`initParams(self)`
:


### Ver también

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)