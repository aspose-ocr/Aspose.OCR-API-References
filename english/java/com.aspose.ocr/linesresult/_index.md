---
title: RecognitionResult.LinesResult
second_title: Aspose.OCR for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.ocr/recognitionresult.linesresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult.LinesResult
```
## Fields

| Field | Description |
| --- | --- |
| [confidence](#confidence) | The confidence score assigned to the recognized text line, represented as a floating-point value between 0.0 and 1.0. |
| [font](#font) |  |
| [line](#line) |  |
| [textInLine](#textInLine) |  |


### confidence {#confidence}
```
public double confidence
```


The confidence score assigned to the recognized text line, represented as a floating-point value between 0.0 and 1.0. A score of 1.0 indicates the highest level of recognition certainty.

This value is always set to 0 when using a temporary license. Confidence is only calculated for the following languages: Chinese language group, Arabic, Hindi, European, Korean, Japanese, Telugu, Tamil, and Kannada.

Confidence is not calculated for ExtLatin or languages that contain diacritical marks.

### font {#font}
```
public FontLineResult font
```


### line {#line}
```
public Rectangle line
```


### textInLine {#textInLine}
```
public String textInLine
```


