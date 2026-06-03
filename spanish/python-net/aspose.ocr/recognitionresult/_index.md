---
title: "RecognitionResult"
second_title: "Aspose.OCR para Python a través de .NET Referencia de API"
description: 
type: docs
weight: 290
url: /es/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

Los resultados del reconocimiento de imágenes.<br/>            Contiene elementos con información de reconocimiento y métodos para exportar los resultados.

El tipo RecognitionResult expone los siguientes miembros:


## Propiedades
| Nombre | Descripción |
| :- | :- |
| recognition_regions_result | Obtiene una lista de resultados de reconocimiento con una lista de regiones (Rectángulos). |
| recognition_lines_result | Obtiene una lista de resultados de reconocimiento con una lista de filas (Rectángulos). |
| recognition_characters_list | Un conjunto de caracteres encontrados por el algoritmo de reconocimiento y ordenados en orden descendente de probabilidad. |
| recognition_text | Obtiene el resultado del reconocimiento en una cadena. |
| file_name | Ruta completa al archivo. |
| warnings | Obtiene una lista de los mensajes de advertencia que describen fallas no críticas que aparecieron durante la generación. |
| serializable_image |  |
## Methods
| Nombre | Descripción |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Guarda el documento como texto plano, PDF o documento de Microsoft Word. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Guarda el documento como texto plano, PDF o documento de Microsoft Word. |
| save(full_file_name, save_format, optimize_pdf) | Guarda el documento como texto plano, PDF o documento de Microsoft Word. |
| save(stream, save_format, optimize_pdf) | Guarda el documento como texto plano, PDF o documento de Microsoft Word. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Guarda el documento como texto plano, PDF o documento de Microsoft Word. |
| get_spell_check_corrected_text(language, dictionary_path) | Corrige texto (reemplaza palabras mal escritas). |
| get_spell_check_error_list(language, dictionary_path) | Encuentra las palabras mal escritas con sugerencias de ortografía para un texto de entrada dado. |
| get_json(is_readable) | Forma una cadena JSON con los resultados de reconocimiento. |
| get_xml() | Forma una cadena XML con los resultados de reconocimiento. |
| get_keywords() | Obtener palabras clave del pasaporte (Modo de prueba. Funciona solo para pasaportes de USA y MADAGASCAR). |

### Ver también

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

