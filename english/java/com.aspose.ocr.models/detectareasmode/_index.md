---
title: DetectAreasMode
second_title: Aspose.OCR for Java API Reference
description: 
type: docs
weight: 26
url: /java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## Fields

| Field | Description |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | Automatically straightens curved lines of text in the image, improving recognition accuracy and allowing more text to be recovered and extracted. |
| [DOCUMENT_LAYOUT](#DOCUMENT-LAYOUT) | Detects complete document layout, including text blocks, headings, columns, tables, images, charts, and formulas. |
| [FORMULA](#FORMULA) | Detects all blocks with mathematical formulas. |
| [LEAN](#LEAN) | Prioritizes speed and reduces resource consumption by omitting support for complex layouts. |
| [MULTICOLUMN](#MULTICOLUMN) | Detects complete document layout, including multi-column text, tables, images, charts, and formulas. |
| [TABLE](#TABLE) | Detects tabular structures in the image and extracts text from individual cells. |
| [UNIVERSAL](#UNIVERSAL) | Detects all blocks of text in the image, including sparse and irregular text on photos. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


Automatically straightens curved lines of text in the image, improving recognition accuracy and allowing more text to be recovered and extracted. Requires significant processing power and RAM.

### DOCUMENT_LAYOUT {#DOCUMENT-LAYOUT}
```
public static final DetectAreasMode DOCUMENT_LAYOUT
```


Detects complete document layout, including text blocks, headings, columns, tables, images, charts, and formulas. Use this mode when the recognized structure must be preserved in DOCX or Markdown output.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


Detects all blocks with mathematical formulas.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


Prioritizes speed and reduces resource consumption by omitting support for complex layouts. Suitable only for simple images with a few lines of text without illustrations or formatting.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


Detects complete document layout, including multi-column text, tables, images, charts, and formulas. Kept for backward compatibility; \#DOCUMENT\_LAYOUT.DOCUMENT\_LAYOUT is the clearer name for this mode.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


Detects tabular structures in the image and extracts text from individual cells. Recommended for scanned spreadsheets, reports, and other table-based documents.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


Detects all blocks of text in the image, including sparse and irregular text on photos. A versatile option for most images, except for tables and multi-column layouts.

