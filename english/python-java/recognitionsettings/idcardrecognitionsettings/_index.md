---
title: "IDCardRecognitionSettings"
linktitle: "IDCardRecognitionSettings"
second_title: "Aspose.OCR for Python via Java"
description: ""
type: docs
weight: 10
url: /python-java/recognitionsettings/idcardrecognitionsettings/
---

## IDCardRecognitionSettings class

**Module:** `recognitionsettings`


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [set_allowed_characters](#set_allowed_characters) |  | No | Allowed characters set. Determines the array of characters allowed for recognition result. |
| [set_automatic_color_inversion](#set_automatic_color_inversion) |  | No | Detect images with white text on dark/black background and automatically choose a special OCR algorithm for them. |
| [set_ignored_characters](#set_ignored_characters) |  | No | Sets blacklist for recognition symbols. |
| [set_language](#set_language) |  | No | Sets the language used for OCR. Multi-language (none) by default. |
| [set_threads_count](#set_threads_count) |  | No | Gets or sets the number of threads for processing. By default, 0 means that the image will be processed with the number of threads equal to your number of processors. ThreadsCount = 1 means that the image will be processed in the main thread. |
| [set_upscale_small_font](#set_upscale_small_font) |  | No | Allows you to use additional algorithms specifically for small font recognition. Useful for images with small size characters. |

## Fields

| Name | Value | Description |
| --- | --- | --- |
| [JAVA_CLASS_NAME](#java_class_name) | `"com.aspose.ocr.IDCardRecognitionSettings"` |  |

### IDCardRecognitionSettings Constructor {#constructor}

```python
__init__(self)
```

### IDCardRecognitionSettings.set_allowed_characters {#set_allowed_characters}

```python
set_allowed_characters(self, str allowedCharacters)
```

Allowed characters set. Determines the array of characters allowed for recognition result.

| Parameter | Type | Description |
| --- | --- | --- |
| `allowedCharacters` | `str` | contains string of characters. |

### IDCardRecognitionSettings.set_automatic_color_inversion {#set_automatic_color_inversion}

```python
set_automatic_color_inversion(self, bool automaticColorInversion)
```

Detect images with white text on dark/black background and automatically choose a special OCR algorithm for them.

| Parameter | Type | Description |
| --- | --- | --- |
| `automaticColorInversion` | `bool` | contains boolean value - a automaticColorInversion is set. True by default. |

### IDCardRecognitionSettings.set_ignored_characters {#set_ignored_characters}

```python
set_ignored_characters(self, str ignoredCharacters)
```

Sets blacklist for recognition symbols.

| Parameter | Type | Description |
| --- | --- | --- |
| `ignoredCharacters` | `str` | Characters excluded from recognition. |

### IDCardRecognitionSettings.set_language {#set_language}

```python
set_language(self, Language language)
```

Sets the language used for OCR. Multi-language (none) by default.

| Parameter | Type | Description |
| --- | --- | --- |
| `language` | `Language` | contains enum Language value. |

### IDCardRecognitionSettings.set_threads_count {#set_threads_count}

```python
set_threads_count(self, int threadsCount)
```

Gets or sets the number of threads for processing. By default, 0 means that the image will be processed with the number of threads equal to your number of processors. ThreadsCount = 1 means that the image will be processed in the main thread.

| Parameter | Type | Description |
| --- | --- | --- |
| `threadsCount` | `int` | the number of threads that will be created for parallel recognition of image fragments. |

### IDCardRecognitionSettings.set_upscale_small_font {#set_upscale_small_font}

```python
set_upscale_small_font(self, bool upscaleSmallFont)
```

Allows you to use additional algorithms specifically for small font recognition. Useful for images with small size characters.

| Parameter | Type | Description |
| --- | --- | --- |
| `upscaleSmallFont` | `bool` | contains boolean value - an upscaleSmallFont is set. |

### IDCardRecognitionSettings.JAVA_CLASS_NAME {#java_class_name}

**Type:** `str`

**Value:** `"com.aspose.ocr.IDCardRecognitionSettings"`

