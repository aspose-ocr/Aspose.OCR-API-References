---
title: "OcrInput"
second_title: "Aspose.OCR para Python a través de .NET Referencia de API"
description: 
type: docs
weight: 240
url: /es/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

Contenedor para recopilar todas las imágenes / documentos para el preprocesamiento / reconocimiento.

El tipo OcrInput expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| OcrInput(type, filters) | Inicializa una nueva instancia de la clase OcrInput |
| OcrInput(type) | Inicializa una nueva instancia de la clase OcrInput |
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Devuelve información sobre la imagen procesada / reconocida. |
## Methods
| Nombre | Descripción |
| :- | :- |
| add(full_path) | Agrega la ruta o URI que contiene la imagen para reconocimiento / procesamiento.<br/>            El tipo de la imagen debe corresponder al tipo especificado en el constructor. |
| add(stream) | Agrega el flujo de memoria que contiene la imagen para reconocimiento / procesamiento.<br/>            El tipo de la imagen debe corresponder al tipo especificado en el constructor. |
| add(full_path, start_page, pages_count) | Agrega las imágenes / documentos multipágina para reconocimiento / procesamiento.<br/>            El tipo de la imagen debe corresponder al tipo especificado en el constructor. |
| add(stream, start_page, pages_count) | Agrega el flujo de memoria que contiene la imagen multipágina para reconocimiento / procesamiento.<br/>            El tipo de la imagen debe corresponder al tipo especificado en el constructor. |
| add(arr, width, height, pixel_format) | Agrega la imagen decodificada a la lista para reconocimiento / procesamiento.<br/>            El tipo de la imagen debe corresponder al tipo especificado en el constructor (SingleImage). |
| replace_filters(filters) | Elimina los filtros antiguos y establece nuevos. |
| clear_filters() | Elimina todos los filtros. |
| add_base64(base64) | Agrega la cadena base64 que contiene la imagen para reconocimiento / procesamiento.<br/>            El tipo de la imagen debe corresponder al tipo especificado en el constructor. |
| clear() | Elimina todos los filtros. |
| count() | Cantidad de elementos para procesamiento / reconocimiento. |
| get_input_type() | Tipo de imágenes permitidas para reconocimiento. |

### Ver también

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

