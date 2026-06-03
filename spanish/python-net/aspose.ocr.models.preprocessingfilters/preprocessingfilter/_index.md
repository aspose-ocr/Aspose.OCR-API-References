---
title: "PreprocessingFilter"
second_title: "Aspose.OCR para Python a través de .NET Referencia de API"
description: 
type: docs
weight: 10
url: /es/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

Clase base para comandos de procesamiento de imágenes.

El tipo PreprocessingFilter expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PreprocessingFilter() | Inicializa una nueva instancia de la clase PreprocessingFilter |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| predeterminado | La colección de filtros predeterminada contiene el filtro AutoSkew |
| empty | Colección de filtros vacía |
## Methods
| Nombre | Descripción |
| :- | :- |
| binarize() | Convierte una imagen a una imagen en blanco y negro.<br/>            Las imágenes binarias son imágenes cuyos píxeles tienen solo dos valores de intensidad posibles. <br/>            Normalmente se muestran en blanco y negro. Numéricamente, los dos valores suelen ser 0 para negro y 255 para blanco.<br/>            Las imágenes binarias se producen mediante umbralado automático de una imagen. |
| binarize(area) | Convierte una parte de la imagen a una imagen en blanco y negro.<br/>            Las imágenes binarias son imágenes cuyos píxeles tienen solo dos valores de intensidad posibles. <br/>            Normalmente se muestran en blanco y negro. Numéricamente, los dos valores suelen ser 0 para negro y 255 para blanco.<br/>            Las imágenes binarias se producen mediante umbralado automático de una imagen. |
| resize(width, height, type) | Reescalar imagen - Aumentar o reducir la resolución de la imagen. |
| resize(width, height) | Reescalar imagen - Aumentar o reducir la resolución de la imagen. |
| dilate() | La dilatación agrega píxeles a los bordes de los objetos en una imagen. |
| dilate(area) | La dilatación agrega píxeles a los bordes de los objetos en una parte de la imagen. |
| invert() | Invierte automáticamente los colores en una imagen de documento. |
| invert(area) | Invierte automáticamente los colores en una parte de la imagen. |
| rotate(angle) | Rotar la imagen original. |
| rotate(angle, area) | Rotar una parte de la imagen. |
| scale(ratio) | Reescalar imagen - Aumentar o reducir la resolución de la imagen.<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | Reescalar imagen - Aumentar o reducir la resolución de la imagen. |
| threshold(value) | Crear una imagen binaria basándose en establecer un valor de umbral en la intensidad de píxel de la imagen original. |
| threshold(value, area) | Crear una parte binaria de la imagen basándose en establecer un valor de umbral en la intensidad de píxel de la parte original de la imagen. |
| median() | El filtro mediano recorre cada elemento de la imagen y reemplaza cada píxel con la mediana de sus píxeles vecinos. |
| median(area) | El filtro mediano recorre cada elemento de la parte de la imagen y reemplaza cada píxel con la mediana de sus píxeles vecinos. |
| auto_denoising() | Permite el uso de una red neuronal adicional para mejorar la imagen - reducir el ruido.<br/>            Útil para imágenes con artefactos de escaneo, distorsión, manchas, reflejos, gradientes, elementos extraños. |
| auto_denoising(area) | Permite el uso de una red neuronal adicional para mejorar la parte de la imagen - reducir el ruido.<br/>            Útil para imágenes con artefactos de escaneo, distorsión, manchas, reflejos, gradientes, elementos extraños. |
| auto_skew() | Permite la corrección automática de la inclinación de la imagen. |
| auto_skew(area) | Permite la corrección automática de la inclinación de la parte de la imagen. |
| contrast_correction_filter() | Filtro de corrección de contraste. |
| contrast_correction_filter(area) | Filtro de corrección de contraste para la parte de la imagen. |
| to_grayscale() | Convierte una imagen a una imagen en escala de grises.<br/>            La imagen en escala de grises tiene 256 niveles de luz en la imagen (0 a 255). |
| auto_dewarping() | Corrige automáticamente las distorsiones geométricas en la imagen.<br/>            ¡Extremadamente intensivo en recursos! |
| add(filter) | Agrega el nuevo filtro a la colección para ejecutar todas las operaciones.<br/>            La consistencia en la colección es importante. |

### Ver también

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

