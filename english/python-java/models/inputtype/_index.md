---
title: "InputType"
linktitle: "InputType"
second_title: "Aspose.OCR for Python via Java"
description: "Types of image/ documents for processing / recognition."
type: docs
weight: 10
url: /python-java/models/inputtype/
---

## InputType enum

**Module:** `models`


Types of image/ documents for processing / recognition.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [BASE64](#base64) | `6 base64 string with the image or path to the .txt file with the base64 content. Supports GIF, PNG, JPEG, BMP, TIFF.` |  |
| [DIRECTORY](#directory) | `4 Path to the directory. Nested archives and folders are not supported. Supports GIF, PNG, JPEG, BMP, TIFF. Default amount of processed images is all.` |  |
| [PDF](#pdf) | `1 Scanned PDF document from file or from bynary array.` |  |
| [SINGLE_IMAGE](#single_image) | `0 Supports GIF, PNG, JPEG, BMP, TIFF, JFIF, binary array.` |  |
| [TIFF](#tiff) | `2 Multipage TIFF, TIF document from file or from InputStream.` |  |
| [URL](#url) | `3 Link on the image. Supports GIF, PNG, JPEG, BMP, TIFF.` |  |
| [ZIP](#zip) | `5 Full name of the ZIP archive. Nested archives and folders are not supported. Supports GIF, PNG, JPEG, BMP, TIFF, JFIF. Default amount of processed images is all.` |  |
### InputType.BASE64 {#base64}

**Type:** `int`

**Value:** `6 base64 string with the image or path to the .txt file with the base64 content. Supports GIF, PNG, JPEG, BMP, TIFF.`

### InputType.DIRECTORY {#directory}

**Type:** `int`

**Value:** `4 Path to the directory. Nested archives and folders are not supported. Supports GIF, PNG, JPEG, BMP, TIFF. Default amount of processed images is all.`

### InputType.PDF {#pdf}

**Type:** `int`

**Value:** `1 Scanned PDF document from file or from bynary array.`

### InputType.SINGLE_IMAGE {#single_image}

**Type:** `int`

**Value:** `0 Supports GIF, PNG, JPEG, BMP, TIFF, JFIF, binary array.`

### InputType.TIFF {#tiff}

**Type:** `int`

**Value:** `2 Multipage TIFF, TIF document from file or from InputStream.`

### InputType.URL {#url}

**Type:** `int`

**Value:** `3 Link on the image. Supports GIF, PNG, JPEG, BMP, TIFF.`

### InputType.ZIP {#zip}

**Type:** `int`

**Value:** `5 Full name of the ZIP archive. Nested archives and folders are not supported. Supports GIF, PNG, JPEG, BMP, TIFF, JFIF. Default amount of processed images is all.`

