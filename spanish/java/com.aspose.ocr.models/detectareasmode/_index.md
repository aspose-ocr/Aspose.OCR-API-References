---
title: "DetectAreasMode"
second_title: "Referencia de API de Aspose.OCR para Java"
description: 
type: docs
weight: 28
url: /es/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## Campos

| Campo | Descripción |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | Endereza automáticamente las líneas curvas de texto en la imagen, mejorando la precisión del reconocimiento y permitiendo que se recupere y extraiga más texto. |
| [FORMULA](#FORMULA) | Detecta todos los bloques con fórmulas matemáticas. |
| [LEAN](#LEAN) | Prioriza la velocidad y reduce el consumo de recursos al omitir el soporte para diseños complejos. |
| [MULTICOLUMN](#MULTICOLUMN) | Detecta grandes bloques de texto formateados en columnas. |
| [TABLE](#TABLE) | Detecta estructuras tabulares en la imagen y extrae texto de celdas individuales. |
| [UNIVERSAL](#UNIVERSAL) | Detecta todos los bloques de texto en la imagen, incluyendo texto escaso e irregular en fotos. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


Endereza automáticamente las líneas curvas de texto en la imagen, mejorando la precisión del reconocimiento y permitiendo que se recupere y extraiga más texto. Requiere una potencia de procesamiento y RAM significativas.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


Detecta todos los bloques con fórmulas matemáticas.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


Prioriza la velocidad y reduce el consumo de recursos al omitir el soporte para diseños complejos. Adecuado solo para imágenes simples con unas pocas líneas de texto sin ilustraciones ni formato.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


Detecta grandes bloques de texto formateados en columnas. La mejor opción para diseños multicolumna como páginas de libros, artículos o contratos.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


Detecta estructuras tabulares en la imagen y extrae texto de celdas individuales. Recomendado para hojas de cálculo escaneadas, informes y otros documentos basados en tablas.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


Detecta todos los bloques de texto en la imagen, incluyendo texto escaso e irregular en fotos. Una opción versátil para la mayoría de imágenes, excepto para tablas y diseños multicolumna.

