---
title: "RecognitionSettings"
second_title: "Aspose.OCR para Python a través de .NET Referencia de API"
description: 
type: docs
weight: 330
url: /es/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

Configuración para el reconocimiento de imágenes.<br/>            Contiene elementos que permiten personalizar el proceso de reconocimiento.

El tipo RecognitionSettings expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| RecognitionSettings() | Inicializa una nueva instancia de |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | Inicializa una nueva instancia de la clase RecognitionSettings |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | Obtiene o establece el número de hilos para el procesamiento. |
| language | Obtiene o establece el idioma usado para OCR. |
| ignored_symbols | Establece la lista negra para los símbolos de reconocimiento. |
| allowed_symbols | Establece los caracteres permitidos con la propiedad alfabeto. |
| allowed_characters | Conjunto de caracteres permitidos. Determina el tipo de caracteres permitidos para el resultado del reconocimiento. |
| automatic_color_inversion | Detecta imágenes con texto blanco sobre fondo oscuro/negro y elige automáticamente un algoritmo OCR especial para ellas. |
| recognition_areas | Obtiene o establece la lista de áreas de texto para el procesamiento. |
| recognize_single_line | Establece el reconocimiento de imágenes de una sola línea. <br/>            Desactivado (false) por defecto. <br/>            Desactiva todos los pasos de procesamiento asociados con la división en líneas. <br/>            Establezca este parámetro en true si su imagen contiene solo una línea. Desactiva la configuración de RecognitionAreas, por lo que todas las configuraciones de áreas serán ignoradas. |
| language_detection_level |  |
| lines_filtration | Permite reconocer texto en las tablas (regiones rodeadas de líneas). |
| detect_areas_mode | Permite seleccionar el modo óptimo para áreas de tipo documento: documento, foto, texto plano, columna, imagen. |
| upscale_small_font | Le permite usar algoritmos adicionales específicamente para el reconocimiento de fuentes pequeñas.<br/>            Útil para imágenes con caracteres de tamaño pequeño. |

### Ver también

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

