---
title: "DetectAreasMode"
second_title: "Aspose.OCR para Python a través de .NET Referencia de API"
description: 
type: docs
weight: 540
url: /es/python-net/aspose.ocr/detectareasmode/
---

## DetectAreasMode enumeration

Determina el tipo de red neuronal utilizada para la detección de áreas.

## Members
| Nombre del miembro | Descripción |
| :- | :- |
| LEAN | Prioriza la velocidad y reduce el consumo de recursos al omitir el soporte para diseños complejos. Adecuado solo para imágenes simples con unas pocas líneas de texto sin ilustraciones ni formato. |
| MULTICOLUMN | Detecta grandes bloques de texto formateados en columnas. La mejor opción para diseños de varias columnas como páginas de libros, artículos o contratos. |
| UNIVERSAL | Detecta todos los bloques de texto en la imagen, incluyendo texto escaso e irregular en fotos. Una opción versátil para la mayoría de imágenes, excepto para tablas y diseños de varias columnas. |
| TABLE | Detecta estructuras tabulares en la imagen y extrae texto de celdas individuales. Recomendado para hojas de cálculo escaneadas, informes y otros documentos basados en tablas. |
| CURVED_TEXT | Endereza automáticamente líneas de texto curvadas en la imagen, mejorando la precisión del reconocimiento y permitiendo que se recupere y extraiga más texto. Requiere una potencia de procesamiento y RAM significativas. |
| FORMULA |  |

### Ver también

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.OCR](/ocr/python-net/)

