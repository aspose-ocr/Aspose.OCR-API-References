---
title: "AsposeOcr"
second_title: "Referencia de la API de Aspose.OCR para Python vía Java"
description: 
type: docs
weight: 11
url: /es/python-java/aspose/asposeocr/
---


Módulo asposeocr
================
Interfaz de Python para Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
mientras reconocimiento óptico de caracteres (OCR) fácil de usar
motor para tus aplicaciones Python y cuadernos.
En menos de **10** líneas de código, puedes reconocer
texto en **28** idiomas basados en latín, cirílico,
y escrituras asiáticas, devolviendo resultados en los más populares
formatos de documentos e intercambio de datos.
No es necesario aprender modelos matemáticos complejos,
construir algoritmos de aprendizaje automático y entrenar redes neuronales
redes — nuestra API simple y robusta hará todo por ti.

Clases
-------

`AsposeOcr()`
:
Clase principal AsposeOcr para reconocimiento.
    
Este ejemplo muestra cómo reconocer una imagen.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Métodos estáticos

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
Permite obtener un documento multipágina a partir de una lista de objetos RecognitionResult.
@param fullFileName: Nombre de archivo con ruta para guardar el resultado del reconocimiento en el formato seleccionado.
@param saveFormat: Formato del documento (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Métodos

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Calcula los ángulos de sesgo de una imagen.
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia. El contenedor con fuentes.
@return: Lista de ángulos de sesgo en grados - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Comprueba si dos imágenes contienen el mismo texto.
@param fullPath1: Ruta a la primera imagen.
@param fullPath2: Ruta a la segunda imagen.
@param settings: Configuración de reconocimiento.
@param ignoreCase: True - significa una búsqueda sin distinción de mayúsculas y minúsculas.
@return: True si las imágenes tienen el mismo texto (90% de similitud).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Corrige texto (reemplaza palabras mal escritas).
@param text: Texto para corregir.
@param language: Diccionario a usar SpellCheckLanguage.
@return: Texto con palabras reemplazadas.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Detecta áreas de texto en imágenes.
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@param areasType: Determina qué rectángulos devolver - línea, párrafos o palabras.
@param isDetectAreas: Habilita la detección automática de áreas de texto.
@return: Lista de RectangleOutput con áreas de texto o líneas detectadas.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Comprueba si la imagen contiene el fragmento de texto proporcionado.
@param fullPath: Ruta a la imagen.
@param text: Fragmento de texto para buscar en la imagen.
@param settings: Configuración de reconocimiento.
@param ignoreCase: True - significa una búsqueda sin distinción de mayúsculas y minúsculas.
@return: True si la imagen contiene el fragmento de texto. False - la imagen no contiene el fragmento de texto.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
Compara los textos en las dos imágenes y devuelve un número que representa cuán similares son (0 a 1).
@param fullPath1: Ruta a la primera imagen.
@param fullPath2: Ruta a la segunda imagen.
@param settings: Configuración de reconocimiento.
@param ignoreCase: True - significa una búsqueda sin distinción de mayúsculas y minúsculas.
@return: 0 significa que los textos son completamente diferentes; 1 significa que los textos son idénticos.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconoce la imagen con la capacidad de especificar RecognitionSettings.
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@param settings: objeto RecognitionSettings.
@return: lista RecognitionResult con los resultados de reconocimiento de imágenes.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconoce la matrícula del coche con la capacidad de especificar CarPlateRecognitionSettings.
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@param settings: CarPlateRecognitionSettings
@return: lista RecognitionResult con los resultados de reconocimiento de imágenes.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconoce texto en una imagen de buena calidad. No utiliza corrección automática de sesgo de imagen y áreas de texto
detección.
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@return: lista RecognitionResult con los resultados de reconocimiento de imágenes.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconoce la tarjeta de identificación con la capacidad de especificar IDCardRecognitionSettings.
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@param settings: IDCardRecognitionSettings
@return: lista RecognitionResult con los resultados de reconocimiento de imágenes.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconoce la factura con la capacidad de especificar InvoiceRecognitionSettings
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@param settings: InvoiceRecognitionSettings
@return: lista RecognitionResult con los resultados de reconocimiento de imágenes.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconoce una imagen de una sola línea con la capacidad de especificar RecognitionSettings.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@param settings: objeto RecognitionSettings.
@return: lista RecognitionResult con los resultados de reconocimiento de imágenes.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconoce pasaportes con la capacidad de especificar PassportRecognitionSettings.
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@param settings: PassportRecognitionSettings
@return: lista RecognitionResult con los resultados de reconocimiento de imágenes.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconoce recibos con la capacidad de especificar ReceiptRecognitionSettings.
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@param settings: ReceiptRecognitionSettings
@return: lista RecognitionResult con los resultados de reconocimiento de imágenes.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Reconoce texto en fotos de calle.
Extrae texto de fotos de calle, imágenes de cámaras de tráfico, tarjetas de identificación, licencias de conducir y otras imágenes con texto escaso y fondos ruidosos/coloreados.
Admite GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, matriz binaria, carpeta, matriz, archivo zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instancia.
@return: lista RecognitionResult con los resultados de reconocimiento de imágenes.

`shutdown(self)`
:
Apaga la máquina JVM.

`ImageProcessing()`
:
Clase auxiliar para la biblioteca Aspose OCR. Permite preprocesar y guardar imágenes.

### Métodos estáticos

`save(images, folderPath)`
:
Utiliza el procesamiento de imágenes para mejorar la precisión del OCR.
Crea una lista de filtros que se aplicarán a la imagen de entrada en el orden que especifiques.
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
No necesitas todos. Configura solo lo que necesites.
@param images: objeto OcrInput que contiene diferentes imágenes OcrInput.
@param folderPath: Ruta sin nombres de imágenes para guardar imágenes procesadas.
@return: objeto OcrInput que contiene las imágenes procesadas resultantes OcrInput.


### Ver también

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)